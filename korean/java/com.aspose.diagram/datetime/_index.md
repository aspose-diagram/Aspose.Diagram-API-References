---
title: DateTime
second_title: Aspose.Diagram for Java API 참조
description: 일반적으로 날짜와 시간으로 표현되는 순간을 나타냅니다.
type: docs
weight: 115
url: /ko/java/com.aspose.diagram/datetime/
---

**Inheritance:**
java.lang.Object
```
public class DateTime
```

일반적으로 날짜와 시간으로 표현되는 특정 시점을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DateTime(int year, int month, int day)](#DateTime-int-int-int-) | 지정된 연도, 월 및 일로 DateTime 객체의 새 인스턴스를 초기화합니다. |
| [DateTime(int year, int month, int day, int hour, int minute, int second)](#DateTime-int-int-int-int-int-int-) | 지정된 연도, 월, 일, 시, 분 및 초로 DateTime 객체의 새 인스턴스를 초기화합니다. |
| [DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)](#DateTime-int-int-int-int-int-int-int-) | 지정된 연도, 월, 일, 시, 분, 초 및 밀리초로 DateTime 객체의 새 인스턴스를 초기화합니다. |
| [DateTime(Date date)](#DateTime-java.util.Date-) | 지정된 Date 객체로 DateTime 객체의 새 인스턴스를 초기화합니다. |
| [DateTime(Calendar cld)](#DateTime-java.util.Calendar-) | 지정된 Calendar 객체로 DateTime 객체의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addDays(double value)](#addDays-double-) | 이 인스턴스의 값에 지정된 일 수를 더합니다. |
| [addHours(double value)](#addHours-double-) | 이 인스턴스의 값에 지정된 시간 수를 더합니다. |
| [addMilliseconds(double value)](#addMilliseconds-double-) | 이 인스턴스의 값에 지정된 밀리초 수를 더합니다. |
| [addMinutes(double value)](#addMinutes-double-) | 이 인스턴스의 값에 지정된 분 수를 더합니다. |
| [addMonths(int months)](#addMonths-int-) | 이 인스턴스의 값에 지정된 개월 수를 더합니다. |
| [addSeconds(double value)](#addSeconds-double-) | 이 인스턴스의 값에 지정된 초 수를 더합니다. |
| [addYears(int value)](#addYears-int-) | 이 인스턴스의 값에 지정된 연 수를 더합니다. |
| [compareTo(DateTime value)](#compareTo-com.aspose.diagram.DateTime-) | 이 인스턴스의 값을 지정된 DateTime 값과 비교하고, 이 인스턴스가 지정된 DateTime 값보다 이전인지, 같은지, 이후인지를 나타내는 정수를 반환합니다. |
| [compareTo(Object value)](#compareTo-java.lang.Object-) | 이 인스턴스의 값을 지정된 DateTime 값을 포함하는 객체와 비교하고, 이 인스턴스가 지정된 DateTime 값보다 이전인지, 같은지, 이후인지를 나타내는 정수를 반환합니다. |
| [equals(Object value)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 객체와 같은지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getDay()](#getDay--) | 이 인스턴스가 나타내는 월의 일을 가져옵니다. |
| [getDayOfWeek()](#getDayOfWeek--) | 이 인스턴스가 나타내는 요일을 가져옵니다. |
| [getDayOfYear()](#getDayOfYear--) | 이 인스턴스가 나타내는 연도의 일을 가져옵니다. |
| [getHour()](#getHour--) | 이 인스턴스가 나타내는 날짜의 시 구성 요소를 가져옵니다. |
| [getMillisecond()](#getMillisecond--) | 이 인스턴스가 나타내는 날짜의 밀리초 구성 요소를 가져옵니다. |
| [getMinute()](#getMinute--) | 이 인스턴스가 나타내는 날짜의 분 구성 요소를 가져옵니다. |
| [getMonth()](#getMonth--) | 이 인스턴스가 나타내는 날짜의 월 구성 요소를 가져옵니다. |
| [getNow()](#getNow--) | 이 컴퓨터의 현재 날짜와 시간으로 설정된 DateTime 객체를 로컬 시간으로 가져옵니다. |
| [getSecond()](#getSecond--) | 이 인스턴스가 나타내는 날짜의 초 구성 요소를 가져옵니다. |
| [getYear()](#getYear--) | 이 인스턴스가 나타내는 날짜의 연도 구성 요소를 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toCalendar()](#toCalendar--) | 현재 DateTime 객체의 값을 Calendar 객체로 변환합니다. |
| [toDate()](#toDate--) | 현재 DateTime 객체의 값을 Date 객체로 변환합니다. |
| [toLocalTime()](#toLocalTime--) | 현재 DateTime 객체의 값을 로컬 시간으로 변환합니다. |
| [toString()](#toString--) | 현재 DateTime 객체의 값을 해당 문자열 표현으로 변환합니다. |
| [toUniversalTime()](#toUniversalTime--) | 현재 DateTime 객체의 값을 협정 세계시(UTC)로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DateTime(int year, int month, int day) {#DateTime-int-int-int-}
```
public DateTime(int year, int month, int day)
```


지정된 연도, 월 및 일로 DateTime 객체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 연도 | int | 연도(1~9999). |
| 월 | int | 월(1~12). |
| 일 | int | 일(1~해당 월의 일 수). |

### DateTime(int year, int month, int day, int hour, int minute, int second) {#DateTime-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second)
```


지정된 연도, 월, 일, 시, 분 및 초로 DateTime 객체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 연도 | int | 연도(1~9999). |
| 월 | int | 월(1~12). |
| 일 | int | 일(1~해당 월의 일 수). |
| 시 | int | 시(0~23). |
| 분 | int | 분(0~59). |
| 초 | int | 초 (0부터 59). |

### DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond) {#DateTime-int-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)
```


지정된 연도, 월, 일, 시, 분, 초 및 밀리초로 DateTime 객체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 연도 | int | 연도(1~9999). |
| 월 | int | 월(1~12). |
| 일 | int | 일(1~해당 월의 일 수). |
| 시 | int | 시(0~23). |
| 분 | int | 분(0~59). |
| 초 | int | 초 (0부터 59). |
| 밀리초 | int | 밀리초 (0부터 999). |

### DateTime(Date date) {#DateTime-java.util.Date-}
```
public DateTime(Date date)
```


지정된 Date 객체로 DateTime 객체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 날짜 | java.util.Date | Date 객체 |

### DateTime(Calendar cld) {#DateTime-java.util.Calendar-}
```
public DateTime(Calendar cld)
```


지정된 Calendar 객체로 DateTime 객체의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cld | java.util.Calendar | Calendar 객체 |

### addDays(double value) {#addDays-double-}
```
public DateTime addDays(double value)
```


이 인스턴스의 값에 지정된 일 수를 더합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 전체 및 소수 부분을 포함한 일 수. value 매개변수는 음수이거나 양수일 수 있습니다. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of days represented by value.
### addHours(double value) {#addHours-double-}
```
public DateTime addHours(double value)
```


이 인스턴스의 값에 지정된 시간 수를 더합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 전체 및 소수 부분을 포함한 시간 수. value 매개변수는 음수이거나 양수일 수 있습니다. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of hours represented by value.
### addMilliseconds(double value) {#addMilliseconds-double-}
```
public DateTime addMilliseconds(double value)
```


이 인스턴스의 값에 지정된 밀리초 수를 더합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 전체 및 소수 부분을 포함한 밀리초 수. value 매개변수는 음수이거나 양수일 수 있습니다. 이 값은 가장 가까운 정수로 반올림된다는 점에 유의하십시오. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of milliseconds represented by value.
### addMinutes(double value) {#addMinutes-double-}
```
public DateTime addMinutes(double value)
```


이 인스턴스의 값에 지정된 분 수를 더합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 전체 및 소수 부분을 포함한 분 수. value 매개변수는 음수이거나 양수일 수 있습니다. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of minutes represented by value.
### addMonths(int months) {#addMonths-int-}
```
public DateTime addMonths(int months)
```


이 인스턴스의 값에 지정된 개월 수를 더합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 개월 | int | 개월 수. months 매개변수는 음수이거나 양수일 수 있습니다. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and months.
### addSeconds(double value) {#addSeconds-double-}
```
public DateTime addSeconds(double value)
```


이 인스턴스의 값에 지정된 초 수를 더합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 전체 및 소수 부분을 포함한 초 수. value 매개변수는 음수이거나 양수일 수 있습니다. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of seconds represented by value.
### addYears(int value) {#addYears-int-}
```
public DateTime addYears(int value)
```


이 인스턴스의 값에 지정된 연 수를 더합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 년 수. value 매개변수는 음수이거나 양수일 수 있습니다. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of years represented by value.
### compareTo(DateTime value) {#compareTo-com.aspose.diagram.DateTime-}
```
public int compareTo(DateTime value)
```


이 인스턴스의 값을 지정된 DateTime 값과 비교하고, 이 인스턴스가 지정된 DateTime 값보다 이전인지, 같은지, 이후인지를 나타내는 정수를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) | 비교할 DateTime 객체. |

**Returns:**
int - 이 인스턴스와 value 매개변수의 상대 값을 나타내는 부호 있는 숫자. Value Description 0보다 작음 이 인스턴스가 value보다 이전입니다. 0 이 인스턴스가 value와 동일합니다. 0보다 큼 이 인스턴스가 value보다 이후입니다.
### compareTo(Object value) {#compareTo-java.lang.Object-}
```
public int compareTo(Object value)
```


이 인스턴스의 값을 지정된 DateTime 값을 포함하는 객체와 비교하고, 이 인스턴스가 지정된 DateTime 값보다 이전인지, 같은지, 이후인지를 나타내는 정수를 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object | 비교할 박싱된 DateTime 객체 또는 null. |

**Returns:**
int - 이 인스턴스와 value의 상대 값을 나타내는 부호 있는 숫자. Value Description 0보다 작음 이 인스턴스가 value보다 이전입니다. 0 이 인스턴스가 value와 동일합니다. 0보다 큼 이 인스턴스가 value보다 이후이거나 value가 null입니다.
### equals(Object value) {#equals-java.lang.Object-}
```
public boolean equals(Object value)
```


이 인스턴스가 지정된 객체와 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object | 이 인스턴스와 비교할 객체. |

**Returns:**
boolean - value가 DateTime 인스턴스이며 이 인스턴스의 값과 동일하면 true; 그렇지 않으면 false.
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


이 인스턴스가 나타내는 월의 일을 가져옵니다.

**Returns:**
int - 1에서 31 사이의 값으로 표현된 일 구성 요소.
### getDayOfWeek() {#getDayOfWeek--}
```
public int getDayOfWeek()
```


이 인스턴스가 나타내는 요일을 가져옵니다.

**Returns:**
int - 이 DateTime 값의 요일.
### getDayOfYear() {#getDayOfYear--}
```
public int getDayOfYear()
```


이 인스턴스가 나타내는 연도의 일을 가져옵니다.

**Returns:**
int - 연도 내의 일, 1에서 366 사이의 값으로 표현됩니다.
### getHour() {#getHour--}
```
public int getHour()
```


이 인스턴스가 나타내는 날짜의 시 구성 요소를 가져옵니다.

**Returns:**
int - 시간 구성 요소, 0에서 23 사이의 값으로 표현됩니다.
### getMillisecond() {#getMillisecond--}
```
public int getMillisecond()
```


이 인스턴스가 나타내는 날짜의 밀리초 구성 요소를 가져옵니다.

**Returns:**
int - 밀리초 구성 요소, 0에서 999 사이의 값으로 표현됩니다.
### getMinute() {#getMinute--}
```
public int getMinute()
```


이 인스턴스가 나타내는 날짜의 분 구성 요소를 가져옵니다.

**Returns:**
int - 분 구성 요소, 0에서 59 사이의 값으로 표현됩니다.
### getMonth() {#getMonth--}
```
public int getMonth()
```


이 인스턴스가 나타내는 날짜의 월 구성 요소를 가져옵니다.

**Returns:**
int - 월 구성 요소, 1에서 12 사이의 값으로 표현됩니다.
### getNow() {#getNow--}
```
public static DateTime getNow()
```


이 컴퓨터의 현재 날짜와 시간으로 설정된 DateTime 객체를 로컬 시간으로 가져옵니다.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the current local date and time.
### getSecond() {#getSecond--}
```
public int getSecond()
```


이 인스턴스가 나타내는 날짜의 초 구성 요소를 가져옵니다.

**Returns:**
int - 초, 0에서 59 사이입니다.
### getYear() {#getYear--}
```
public int getYear()
```


이 인스턴스가 나타내는 날짜의 연도 구성 요소를 가져옵니다.

**Returns:**
int - 연도, 1에서 9999 사이입니다.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드.
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


현재 DateTime 객체의 값을 Calendar 객체로 변환합니다.

**Returns:**
[Calendar](../../java.util/calendar) - Calendar object
### toDate() {#toDate--}
```
public Date toDate()
```


현재 DateTime 객체의 값을 Date 객체로 변환합니다.

**Returns:**
java.util.Date - 날짜 객체
### toLocalTime() {#toLocalTime--}
```
public DateTime toLocalTime()
```


현재 DateTime 객체의 값을 로컬 시간으로 변환합니다.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object of local
### toString() {#toString--}
```
public String toString()
```


현재 DateTime 객체의 값을 해당 문자열 표현으로 변환합니다.

**Returns:**
java.lang.String - 현재 DateTime 객체의 값을 문자열로 표현한 것입니다.
### toUniversalTime() {#toUniversalTime--}
```
public DateTime toUniversalTime()
```


현재 DateTime 객체의 값을 협정 세계시(UTC)로 변환합니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

