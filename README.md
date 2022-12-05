# Flyweight

---


>`Flyweight` заключается в том, чтобы запустить технологию совместного использования для эффективной поддержки большого количества объектов, избежать большого количества небольших классов с одинаковым содержимым (например, потребление памяти) и позволить всем совместно использовать класс.

>>В `flyweight` есть два важных понятия: внутреннее состояние и внешнее состояние.

>>внутреннее состояние: общая часть внутри объекта `flyweight`, которая не изменяется с изменением внешней среды.
>>внешнее состояние: состояние, которое не может быть разделено, является внешним состоянием, которое изменяется по мере изменения окружающей среды.
  
##### плюсы
  * `Flyweight` может значительно уменьшить количество объектов в системе.
  * `Flyweight` использует внешнее состояние, внешнее состояние относительно независимо и не влияет на внутреннее состояние, поэтому режим flyweight позволяет совместно использовать объект `Flyweight` в разных средах.
##### минусы
  * Поскольку модель веса мухи должна различать внешнее и внутреннее состояния, программа приложения несколько сложнее.
  * Чтобы сделать объект доступным для совместного использования, модель веса мухи должна экстернализировать состояние объекта наилегчайшего веса, а чтение внешнего состояния увеличивает время работы.
##### итоги
`flyweight` в основном используется для уменьшения количества объектов, создаваемых для уменьшения использования памяти и повышения производительности. Этот тип шаблона проектирования представляет собой структурный шаблон, который позволяет уменьшить количество объектов для улучшения структуры объекта, требуемой приложением.
