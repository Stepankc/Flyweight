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


[Код ts](https://www.typescriptlang.org/play?#code/FAehAIGMBsEMGd7gKoAUAWB7AdgUwGLQCeA7rgJYDm6ALuAN6gThQ7w0BOArpDZhwAoAtpgAmuaAC5w7DuWyUANDMgdcubNOxchAI1wdlQ3CI5EtO-RwCUDAL5NwDsICYQQLwggYRBAQiCABEECsIG5ufn7ggIIggHwgoV7hgPIgboAcICECgDwg4YAsIH6A3CCAMiDKgLIggFwgPoAMIG7KgPwgxckxXtnW0uGAjCCAkiDFMeCA4iDFUdng7t4+8eBNgFIgfgVexeAAZsRkVLTKBeHRJe1B4PGA7CDJATF+XqHt5YObOwEB8UPufoASIEGAnCBh-mmA0iAAdMBfYFBwiCgYHC4BiOFiQNicHh8QSzUgUag0aRoLB4QhwhY0ZTwTTgbR6Ay2ejOCDEm73YJhSLROKJcACbH1SlRWIJPxLFbhHzhEIbVKANhADuBGq9auASlsMpkAuFlDEXJl9od2mSEskmdTWcl2atuWddm5FUdwOVwuBdv49RcEu1Qi8Pl9gDAEEhkUC0fMESCwRDuLx+MIxBJpLJ5EoVGoNBZ8YZwMZTOZcZYCfZgA5HX8kO74bR8LA-WYveAAA5cXTQciQYso3DwACysCL0nrRYAPCGFMpXai5tmaAA+cAAXlxuBI4GbAmsAG4viwS2WK+BKLgaAHxFIZJxQ1jVOocXirEYTPwEweCUjAd30Z7GCxvdh2OAANa4IhD2OB6DgADU4b3P9jY8zBnO9wHIaY6QAQhodByHgd4i2rOsG3edAEAEF8iGsQlgFAlgYLghCkObd54BXDDX2UPAxy7AgewxNcJB3CNsCPeNsJAu8HFAtQaC4DhsHAAj4MQoFkKLd5l1XTDrEgziHDTJ1-lowtwQfSF8wEWEPVoC9qyzDEsX3JMbBTRSMwBfS82hN9b2LUty0rdhYBoRdtN7XN8wTAyEU8mz32o8AfJzayT0nGdcPshdKyk2jGI3dsw3gXdI0TaM2JPKNDxkYzoxw0C1MfdyMT0t16M9YdaL8k93mK3zQrMSTyMi0CRHXRQWrvZKWI6vDAPjTrp063j+MEwK4rqxYcqGlgFK+Qq6C4UTUQat9h3Gy8CFW8KvmgFdwCWpD3wAbQAXRnaZ+DpPa6HId8AAYpzA8AW3AABGe7PsesDv2-fLwBu-qT3fO6AFJwAAJiHYd7vAAB+cAADYABZwGkN6IYADk4w6xIQrh4HQARcZWrympoOKACJMeQSnlAAVnee6MrMZRyA41NHTYTA9veaBMEoAQAHJlkyABaFxTQiCVSjcV5AFEQcA8ilfVohcIXFBJms+Y0SgYOsLmHx53A+YFgRIspqrytoVguGwRE6ciqrVtq62aGqxrlprEj4HIAAvXBgGnIA)
