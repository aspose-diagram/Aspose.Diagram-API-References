---
title: DateTime
second_title: Справочник API Aspose.Diagram for Java
description: Представляет момент времени, обычно выраженный датой и временем суток.
type: docs
weight: 115
url: /ru/java/com.aspose.diagram/datetime/
---

**Inheritance:**
java.lang.Object
```
public class DateTime
```

Представляет момент времени, обычно выраженный датой и временем суток.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DateTime(int year, int month, int day)](#DateTime-int-int-int-) | Инициализирует новый экземпляр объекта DateTime указанными годом, месяцем и днём. |
| [DateTime(int year, int month, int day, int hour, int minute, int second)](#DateTime-int-int-int-int-int-int-) | Инициализирует новый экземпляр объекта DateTime указанными годом, месяцем, днём, часом, минутой и секундой. |
| [DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)](#DateTime-int-int-int-int-int-int-int-) | Инициализирует новый экземпляр объекта DateTime указанными годом, месяцем, днём, часом, минутой, секундой и миллисекундой. |
| [DateTime(Date date)](#DateTime-java.util.Date-) | Инициализирует новый экземпляр объекта DateTime указанным объектом Date. |
| [DateTime(Calendar cld)](#DateTime-java.util.Calendar-) | Инициализирует новый экземпляр объекта DateTime указанным объектом Calendar. |
## Методы

| Метод | Описание |
| --- | --- |
| [addDays(double value)](#addDays-double-) | Добавляет указанное количество дней к значению этого экземпляра. |
| [addHours(double value)](#addHours-double-) | Добавляет указанное количество часов к значению этого экземпляра. |
| [addMilliseconds(double value)](#addMilliseconds-double-) | Добавляет указанное количество миллисекунд к значению этого экземпляра. |
| [addMinutes(double value)](#addMinutes-double-) | Добавляет указанное количество минут к значению этого экземпляра. |
| [addMonths(int months)](#addMonths-int-) | Добавляет указанное количество месяцев к значению этого экземпляра. |
| [addSeconds(double value)](#addSeconds-double-) | Добавляет указанное количество секунд к значению этого экземпляра. |
| [addYears(int value)](#addYears-int-) | Добавляет указанное количество лет к значению этого экземпляра. |
| [compareTo(DateTime value)](#compareTo-com.aspose.diagram.DateTime-) | Сравнивает значение этого экземпляра с указанным значением DateTime и возвращает целое число, указывающее, является ли этот экземпляр более ранним, равным или более поздним, чем указанное значение DateTime. |
| [compareTo(Object value)](#compareTo-java.lang.Object-) | Сравнивает значение этого экземпляра с указанным объектом, содержащим значение DateTime, и возвращает целое число, указывающее, является ли этот экземпляр более ранним, равным или более поздним, чем указанное значение DateTime. |
| [equals(Object value)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли этот экземпляр указанному объекту. |
| [getClass()](#getClass--) |  |
| [getDay()](#getDay--) | Получает день месяца, представленный этим экземпляром. |
| [getDayOfWeek()](#getDayOfWeek--) | Получает день недели, представленный этим экземпляром. |
| [getDayOfYear()](#getDayOfYear--) | Получает день года, представленный этим экземпляром. |
| [getHour()](#getHour--) | Получает компонент часа даты, представленной этим экземпляром. |
| [getMillisecond()](#getMillisecond--) | Получает компонент миллисекунд даты, представленной этим экземпляром. |
| [getMinute()](#getMinute--) | Получает компонент минут даты, представленной этим экземпляром. |
| [getMonth()](#getMonth--) | Получает компонент месяца даты, представленной этим экземпляром. |
| [getNow()](#getNow--) | Получает объект DateTime, установленный на текущие дату и время этого компьютера, выраженный как местное время. |
| [getSecond()](#getSecond--) | Получает компонент секунд даты, представленной этим экземпляром. |
| [getYear()](#getYear--) | Получает компонент года даты, представленной этим экземпляром. |
| [hashCode()](#hashCode--) | Возвращает код хэша для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toCalendar()](#toCalendar--) | Преобразует значение текущего объекта DateTime в объект Calendar. |
| [toDate()](#toDate--) | Преобразует значение текущего объекта DateTime в объект Date. |
| [toLocalTime()](#toLocalTime--) | Преобразует значение текущего объекта DateTime во местное время. |
| [toString()](#toString--) | Преобразует значение текущего объекта DateTime в его эквивалентное строковое представление. |
| [toUniversalTime()](#toUniversalTime--) | Преобразует значение текущего объекта DateTime в координированное всемирное время (UTC). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DateTime(int year, int month, int day) {#DateTime-int-int-int-}
```
public DateTime(int year, int month, int day)
```


Инициализирует новый экземпляр объекта DateTime указанными годом, месяцем и днём.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год (от 1 до 9999). |
| month | int | Месяц (от 1 до 12). |
| day | int | День (от 1 до количества дней в месяце). |

### DateTime(int year, int month, int day, int hour, int minute, int second) {#DateTime-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second)
```


Инициализирует новый экземпляр объекта DateTime указанными годом, месяцем, днём, часом, минутой и секундой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год (от 1 до 9999). |
| month | int | Месяц (от 1 до 12). |
| day | int | День (от 1 до количества дней в месяце). |
| hour | int | Часы (от 0 до 23). |
| minute | int | Минуты (от 0 до 59). |
| second | int | Секунды (от 0 до 59). |

### DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond) {#DateTime-int-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)
```


Инициализирует новый экземпляр объекта DateTime указанными годом, месяцем, днём, часом, минутой, секундой и миллисекундой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| year | int | Год (от 1 до 9999). |
| month | int | Месяц (от 1 до 12). |
| day | int | День (от 1 до количества дней в месяце). |
| hour | int | Часы (от 0 до 23). |
| minute | int | Минуты (от 0 до 59). |
| second | int | Секунды (от 0 до 59). |
| миллисекунда | int | Миллисекунды (от 0 до 999). |

### DateTime(Date date) {#DateTime-java.util.Date-}
```
public DateTime(Date date)
```


Инициализирует новый экземпляр объекта DateTime указанным объектом Date.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| дата | java.util.Date | Объект Date |

### DateTime(Calendar cld) {#DateTime-java.util.Calendar-}
```
public DateTime(Calendar cld)
```


Инициализирует новый экземпляр объекта DateTime указанным объектом Calendar.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cld | java.util.Calendar | Объект Calendar |

### addDays(double value) {#addDays-double-}
```
public DateTime addDays(double value)
```


Добавляет указанное количество дней к значению этого экземпляра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Число целых и дробных дней. Параметр value может быть отрицательным или положительным. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of days represented by value.
### addHours(double value) {#addHours-double-}
```
public DateTime addHours(double value)
```


Добавляет указанное количество часов к значению этого экземпляра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Число целых и дробных часов. Параметр value может быть отрицательным или положительным. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of hours represented by value.
### addMilliseconds(double value) {#addMilliseconds-double-}
```
public DateTime addMilliseconds(double value)
```


Добавляет указанное количество миллисекунд к значению этого экземпляра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Число целых и дробных миллисекунд. Параметр value может быть отрицательным или положительным. Обратите внимание, что это значение округляется до ближайшего целого. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of milliseconds represented by value.
### addMinutes(double value) {#addMinutes-double-}
```
public DateTime addMinutes(double value)
```


Добавляет указанное количество минут к значению этого экземпляра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Число целых и дробных минут. Параметр value может быть отрицательным или положительным. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of minutes represented by value.
### addMonths(int months) {#addMonths-int-}
```
public DateTime addMonths(int months)
```


Добавляет указанное количество месяцев к значению этого экземпляра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| месяцы | int | Число месяцев. Параметр months может быть отрицательным или положительным. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and months.
### addSeconds(double value) {#addSeconds-double-}
```
public DateTime addSeconds(double value)
```


Добавляет указанное количество секунд к значению этого экземпляра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Число целых и дробных секунд. Параметр value может быть отрицательным или положительным. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of seconds represented by value.
### addYears(int value) {#addYears-int-}
```
public DateTime addYears(int value)
```


Добавляет указанное количество лет к значению этого экземпляра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Число лет. Параметр value может быть отрицательным или положительным. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of years represented by value.
### compareTo(DateTime value) {#compareTo-com.aspose.diagram.DateTime-}
```
public int compareTo(DateTime value)
```


Сравнивает значение этого экземпляра с указанным значением DateTime и возвращает целое число, указывающее, является ли этот экземпляр более ранним, равным или более поздним, чем указанное значение DateTime.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) | Объект DateTime для сравнения. |

**Returns:**
int - Подписанное число, указывающее относительные значения этого экземпляра и параметра value. Описание значения Менее нуля Этот экземпляр раньше value. Ноль Этот экземпляр равен value. Более нуля Этот экземпляр позже value.
### compareTo(Object value) {#compareTo-java.lang.Object-}
```
public int compareTo(Object value)
```


Сравнивает значение этого экземпляра с указанным объектом, содержащим значение DateTime, и возвращает целое число, указывающее, является ли этот экземпляр более ранним, равным или более поздним, чем указанное значение DateTime.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object | Упакованный объект DateTime для сравнения или null. |

**Returns:**
int - Подписанное число, указывающее относительные значения этого экземпляра и value. Описание значения Менее нуля Этот экземпляр раньше value. Ноль Этот экземпляр равен value. Более нуля Этот экземпляр позже value, или value равно null.
### equals(Object value) {#equals-java.lang.Object-}
```
public boolean equals(Object value)
```


Возвращает значение, указывающее, равен ли этот экземпляр указанному объекту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object | Объект для сравнения с этим экземпляром. |

**Returns:**
boolean - true, если value является экземпляром DateTime и равен значению этого экземпляра; иначе false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDay() {#getDay--}
```
public int getDay()
```


Получает день месяца, представленный этим экземпляром.

**Returns:**
int - Компонент дня, выраженный значением от 1 до 31.
### getDayOfWeek() {#getDayOfWeek--}
```
public int getDayOfWeek()
```


Получает день недели, представленный этим экземпляром.

**Returns:**
int - день недели значения DateTime.
### getDayOfYear() {#getDayOfYear--}
```
public int getDayOfYear()
```


Получает день года, представленный этим экземпляром.

**Returns:**
int - День года, выраженный значением от 1 до 366.
### getHour() {#getHour--}
```
public int getHour()
```


Получает компонент часа даты, представленной этим экземпляром.

**Returns:**
int - Компонент часа, выраженный значением от 0 до 23.
### getMillisecond() {#getMillisecond--}
```
public int getMillisecond()
```


Получает компонент миллисекунд даты, представленной этим экземпляром.

**Returns:**
int - Компонент миллисекунд, выраженный значением от 0 до 999.
### getMinute() {#getMinute--}
```
public int getMinute()
```


Получает компонент минут даты, представленной этим экземпляром.

**Returns:**
int - Компонент минут, выраженный значением от 0 до 59.
### getMonth() {#getMonth--}
```
public int getMonth()
```


Получает компонент месяца даты, представленной этим экземпляром.

**Returns:**
int - Компонент месяца, выраженный значением от 1 до 12.
### getNow() {#getNow--}
```
public static DateTime getNow()
```


Получает объект DateTime, установленный на текущие дату и время этого компьютера, выраженный как местное время.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the current local date and time.
### getSecond() {#getSecond--}
```
public int getSecond()
```


Получает компонент секунд даты, представленной этим экземпляром.

**Returns:**
int - Секунды, от 0 до 59.
### getYear() {#getYear--}
```
public int getYear()
```


Получает компонент года даты, представленной этим экземпляром.

**Returns:**
int - Год, от 1 до 9999.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает код хэша для этого экземпляра.

**Returns:**
int - 32-битный знаковый целочисленный хеш-код.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toCalendar() {#toCalendar--}
```
public Calendar toCalendar()
```


Преобразует значение текущего объекта DateTime в объект Calendar.

**Returns:**
[Calendar](../../java.util/calendar) - Calendar object
### toDate() {#toDate--}
```
public Date toDate()
```


Преобразует значение текущего объекта DateTime в объект Date.

**Returns:**
java.util.Date - Объект даты
### toLocalTime() {#toLocalTime--}
```
public DateTime toLocalTime()
```


Преобразует значение текущего объекта DateTime во местное время.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object of local
### toString() {#toString--}
```
public String toString()
```


Преобразует значение текущего объекта DateTime в его эквивалентное строковое представление.

**Returns:**
java.lang.String - Строковое представление значения текущего объекта DateTime.
### toUniversalTime() {#toUniversalTime--}
```
public DateTime toUniversalTime()
```


Преобразует значение текущего объекта DateTime в координированное всемирное время (UTC).

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object of UTC
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

