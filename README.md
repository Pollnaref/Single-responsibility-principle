Принцип єдиної відповідальності (Single Responsibility Principle, SRP) - це один з п'яти основних принципів об'єктно-орієнтованого програмування та дизайну, відомих як SOLID. Принцип єдиної відповідальності стверджує, що клас повинен мати лише одну причину для змін. Іншими словами, клас повинен виконувати лише одну задачу або мати лише одну область відповідальності.
Якщо ми перекладемо це на контекст класу або модуля в програмному коді, це означає, що клас не повинен бути перевантаженим різноманітністю функцій, які можуть призвести до його змін з багатьох різних причин. Кожен клас повинен бути зосереджений на одному завданні або аспекті програми.

У цьому прикладі, клас Journal відповідальний лише за управління записами журналу, в той час як клас PersistenceManager відповідає за збереження даних журналу в файл. Це розділення обов'язків гарантує, що зміни в процесі збереження не вплинуть на клас Journal, і навпаки.

Такий підхід сприяє створенню модульного коду, який легше підтримувати та тестувати. Якщо потрібно змінити логіку збереження, це не вплине на логіку журналу, оскільки вони розміщені в різних класах.
