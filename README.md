# Lecture-4
# Lecture-4
## Object

### Конструктор Object создаёт объект-обёртку для переданного значения. Если значением является null или undefined, создаёт и возвращает пустой объект, в противном случае возвращает объект такого типа, который соответствует переданному значению. Если значение уже является объектом, конструктор вернёт это значение.При вызове в не-конструктором контексте, Object ведёт себя идентично коду new Object().


## Object.entries

### Возвращаемое значение  Массив перечислений собственных свойств объекта с парами [key, value].
y.png)
### Описание
### Object.entries() возвращает массив, элементами которого являются массивы, соответствующие перечисляемому свойству пары [key, value], найденной прямо в object. Порядок свойств тот же, что и при прохождении циклом по свойствам объекта вручную.

### Object.keys

### Метод Object.keys() возвращает массив из собственных перечисляемых свойств переданного объекта, в том же порядке, в котором они бы обходились циклом for...in (разница между циклом и методом в том, что цикл перечисляет свойства и из цепочки прототипов).

PNG)


## Object.values()
PNG)
### Метод Object.values() возвращает массив значений перечисляемых свойств объекта в том же порядке что и цикл for...in. Разница между циклом и методом в том, что цикл перечисляет свойства и из цепочки прототипов.


##  Destructuring and Spread

###  Destructuring Object


#### Синтаксис деструктурирующего присваивания в выражениях JavaScript позволяет извлекать данные из массивов или объектов при помощи синтаксиса, подобного объявлению массива или литералов в объекте.

### Spread

[alt text](/img3/spread.PNG)

#### Spread syntax позволяет расширить доступные для итерации элементы (например, массивы или строки) в местах 
#### для функций: где ожидаемое количество аргументов для вызовов функций равно нулю или больше нуля
#### для элементов (литералов массива)
#### для выражений объектов: в местах, где количество пар "ключ-значение" должно быть равно нулю или больше (для объектных литералов)

## This
#### Значение
### Свойство контекста выполнения кода (global, function или eval), которое в нестрогом режиме всегда является ссылкой на объект, а в строгом режиме может иметь любое значение.

## NewDate()

#### Создаёт экземпляр объекта Date, представляющего собой момент времени. Объект Дата содержит число миллисекунд прошедших с 1 января 1970 г. UTC

#### Если никаких аргументов передано не было, конструктор создаёт объект Date для текущих даты и времени, согласно системным настройкам.
#### Если передано как минимум два аргумента, отсутствующие аргументы устанавливаются в стартовые значения - день месяца 1 и время полуночи.


## DateNow()

#### Метод Date.now() возвращает количество миллисекунд, прошедших с 1 января 1970 года 00:00:00 по UTC.

## getFullYear()



#### Метод getFullYear() возвращает год указанной даты по местному времени.

## getMonth()



#### Значение, возвращённое методом getMonth(), является целым числом от 0 до 11. 0 соответствует январю, 1 — февралю и так далее.

## getMinutes()

### Значение, возвращённое методом getMinutes(), является целым числом от 0 до 59.

### Метод setDate() устанавливает день месяца указанной даты по местному времени.

### Метод setMonth() устанавливает месяц указанной даты по местному времени.

### Метод setUTCFullYear() устанавливает полный год указанной даты по всемирному координированному времени.