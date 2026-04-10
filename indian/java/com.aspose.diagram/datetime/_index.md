---
title: DateTime
second_title: Aspose.Diagram for Java API Reference
description: Represents an instant in time typically expressed as a date and time of day.
type: docs
weight: 115
url: /hi/java/com.aspose.diagram/datetime/
---

**Inheritance:**
java.lang.Object
```
public class DateTime
```

यह समय का एक क्षण दर्शाता है, आमतौर पर इसे तिथि और दिन के समय के रूप में व्यक्त किया जाता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [DateTime(int year, int month, int day)](#DateTime-int-int-int-) | Initializes a new instance of the DateTime object to the specified year, month, and day. |
| [DateTime(int year, int month, int day, int hour, int minute, int second)](#DateTime-int-int-int-int-int-int-) | Initializes a new instance of the DateTime object to the specified year, month, day, hour, minute, and second. |
| [DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)](#DateTime-int-int-int-int-int-int-int-) | Initializes a new instance of the DateTime object to the specified year, month, day, hour, minute, second, and millisecond. |
| [DateTime(Date date)](#DateTime-java.util.Date-) | Initializes a new instance of the DateTime object to the specified Date object |
| [DateTime(Calendar cld)](#DateTime-java.util.Calendar-) | Initializes a new instance of the DateTime object to the specified Calendar object |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addDays(double value)](#addDays-double-) | Adds the specified number of days to the value of this instance. |
| [addHours(double value)](#addHours-double-) | Adds the specified number of hours to the value of this instance. |
| [addMilliseconds(double value)](#addMilliseconds-double-) | Adds the specified number of milliseconds to the value of this instance. |
| [addMinutes(double value)](#addMinutes-double-) | Adds the specified number of minutes to the value of this instance. |
| [addMonths(int months)](#addMonths-int-) | Adds the specified number of months to the value of this instance. |
| [addSeconds(double value)](#addSeconds-double-) | Adds the specified number of seconds to the value of this instance. |
| [addYears(int value)](#addYears-int-) | Adds the specified number of years to the value of this instance. |
| [compareTo(DateTime value)](#compareTo-com.aspose.diagram.DateTime-) | Compares the value of this instance to a specified DateTime value and returns an integer that indicates whether this instance is earlier than, the same as, or later than the specified DateTime value. |
| [compareTo(Object value)](#compareTo-java.lang.Object-) | Compares the value of this instance to a specified object that contains a specified DateTime value, and returns an integer that indicates whether this instance is earlier than, the same as, or later than the specified DateTime value. |
| [equals(Object value)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified object. |
| [getClass()](#getClass--) |  |
| [getDay()](#getDay--) | Gets the day of the month represented by this instance. |
| [getDayOfWeek()](#getDayOfWeek--) | Gets the day of the week represented by this instance. |
| [getDayOfYear()](#getDayOfYear--) | इस उदाहरण द्वारा दर्शाए गए वर्ष का दिन प्राप्त करता है। |
| [getHour()](#getHour--) | इस उदाहरण द्वारा दर्शाए गए तिथि का घंटे घटक प्राप्त करता है। |
| [getMillisecond()](#getMillisecond--) | इस उदाहरण द्वारा दर्शाए गए तिथि का मिलीसेकंड घटक प्राप्त करता है। |
| [getMinute()](#getMinute--) | इस उदाहरण द्वारा दर्शाए गए तिथि का मिनट घटक प्राप्त करता है। |
| [getMonth()](#getMonth--) | इस उदाहरण द्वारा दर्शाए गए तिथि का माह घटक प्राप्त करता है। |
| [getNow()](#getNow--) | एक DateTime ऑब्जेक्ट प्राप्त करता है जो इस कंप्यूटर पर वर्तमान तिथि और समय पर सेट होता है, स्थानीय समय के रूप में व्यक्त किया गया। |
| [getSecond()](#getSecond--) | इस उदाहरण द्वारा दर्शाए गए तिथि का सेकंड घटक प्राप्त करता है। |
| [getYear()](#getYear--) | इस उदाहरण द्वारा दर्शाए गए तिथि का वर्ष घटक प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toCalendar()](#toCalendar--) | वर्तमान DateTime ऑब्जेक्ट के मान को Calendar ऑब्जेक्ट में परिवर्तित करता है। |
| [toDate()](#toDate--) | वर्तमान DateTime ऑब्जेक्ट के मान को Date ऑब्जेक्ट में परिवर्तित करता है। |
| [toLocalTime()](#toLocalTime--) | वर्तमान DateTime ऑब्जेक्ट के मान को स्थानीय समय में परिवर्तित करता है। |
| [toString()](#toString--) | वर्तमान DateTime ऑब्जेक्ट के मान को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| [toUniversalTime()](#toUniversalTime--) | वर्तमान DateTime ऑब्जेक्ट के मान को समन्वित सार्वभौमिक समय (UTC) में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DateTime(int year, int month, int day) {#DateTime-int-int-int-}
```
public DateTime(int year, int month, int day)
```


Initializes a new instance of the DateTime object to the specified year, month, and day.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| वर्ष | int | वर्ष (1 से 9999 तक)। |
| माह | int | माह (1 से 12 तक)। |
| दिन | int | दिन (1 से महीने में दिनों की संख्या तक)। |

### DateTime(int year, int month, int day, int hour, int minute, int second) {#DateTime-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second)
```


Initializes a new instance of the DateTime object to the specified year, month, day, hour, minute, and second.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| वर्ष | int | वर्ष (1 से 9999 तक)। |
| माह | int | माह (1 से 12 तक)। |
| दिन | int | दिन (1 से महीने में दिनों की संख्या तक)। |
| घंटा | int | घंटे (0 से 23 तक)। |
| मिनट | int | मिनट (0 से 59 तक)। |
| सेकंड | int | सेकंड (0 से 59). |

### DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond) {#DateTime-int-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)
```


Initializes a new instance of the DateTime object to the specified year, month, day, hour, minute, second, and millisecond.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| वर्ष | int | वर्ष (1 से 9999 तक)। |
| माह | int | माह (1 से 12 तक)। |
| दिन | int | दिन (1 से महीने में दिनों की संख्या तक)। |
| घंटा | int | घंटे (0 से 23 तक)। |
| मिनट | int | मिनट (0 से 59 तक)। |
| सेकंड | int | सेकंड (0 से 59). |
| मिलीसेकंड | int | मिलीसेकंड (0 से 999). |

### DateTime(Date date) {#DateTime-java.util.Date-}
```
public DateTime(Date date)
```


Initializes a new instance of the DateTime object to the specified Date object

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| तारीख | java.util.Date | Date ऑब्जेक्ट |

### DateTime(Calendar cld) {#DateTime-java.util.Calendar-}
```
public DateTime(Calendar cld)
```


Initializes a new instance of the DateTime object to the specified Calendar object

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| cld | java.util.Calendar | Calendar ऑब्जेक्ट |

### addDays(double value) {#addDays-double-}
```
public DateTime addDays(double value)
```


Adds the specified number of days to the value of this instance.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल | पूरा और अंशात्मक दिनों की संख्या। मान पैरामीटर नकारात्मक या सकारात्मक हो सकता है। |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of days represented by value.
### addHours(double value) {#addHours-double-}
```
public DateTime addHours(double value)
```


Adds the specified number of hours to the value of this instance.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल | पूरा और अंशात्मक घंटों की संख्या। मान पैरामीटर नकारात्मक या सकारात्मक हो सकता है। |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of hours represented by value.
### addMilliseconds(double value) {#addMilliseconds-double-}
```
public DateTime addMilliseconds(double value)
```


Adds the specified number of milliseconds to the value of this instance.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल | पूरा और अंशात्मक मिलीसेकंड की संख्या। मान पैरामीटर नकारात्मक या सकारात्मक हो सकता है। ध्यान दें कि यह मान निकटतम पूर्णांक में गोल किया जाता है। |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of milliseconds represented by value.
### addMinutes(double value) {#addMinutes-double-}
```
public DateTime addMinutes(double value)
```


Adds the specified number of minutes to the value of this instance.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल | पूरा और अंशात्मक मिनटों की संख्या। मान पैरामीटर नकारात्मक या सकारात्मक हो सकता है। |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of minutes represented by value.
### addMonths(int months) {#addMonths-int-}
```
public DateTime addMonths(int months)
```


Adds the specified number of months to the value of this instance.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| महीने | int | महीनों की संख्या। months पैरामीटर नकारात्मक या सकारात्मक हो सकता है। |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and months.
### addSeconds(double value) {#addSeconds-double-}
```
public DateTime addSeconds(double value)
```


Adds the specified number of seconds to the value of this instance.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल | पूरा और अंशात्मक सेकंड की संख्या। मान पैरामीटर नकारात्मक या सकारात्मक हो सकता है। |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of seconds represented by value.
### addYears(int value) {#addYears-int-}
```
public DateTime addYears(int value)
```


Adds the specified number of years to the value of this instance.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int | वर्षों की संख्या। मान पैरामीटर नकारात्मक या सकारात्मक हो सकता है। |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of years represented by value.
### compareTo(DateTime value) {#compareTo-com.aspose.diagram.DateTime-}
```
public int compareTo(DateTime value)
```


Compares the value of this instance to a specified DateTime value and returns an integer that indicates whether this instance is earlier than, the same as, or later than the specified DateTime value.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) | तुलना के लिए DateTime ऑब्जेक्ट। |

**Returns:**
int - इस इंस्टेंस और मान पैरामीटर के सापेक्ष मान दर्शाने वाला एक साइन किया हुआ संख्या। मान विवरण शून्य से कम: यह इंस्टेंस मान से पहले है। शून्य: यह इंस्टेंस मान के समान है। शून्य से अधिक: यह इंस्टेंस मान से बाद में है।
### compareTo(Object value) {#compareTo-java.lang.Object-}
```
public int compareTo(Object value)
```


Compares the value of this instance to a specified object that contains a specified DateTime value, and returns an integer that indicates whether this instance is earlier than, the same as, or later than the specified DateTime value.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object | तुलना के लिए बॉक्स्ड DateTime ऑब्जेक्ट, या null। |

**Returns:**
int - इस इंस्टेंस और मान के सापेक्ष मान दर्शाने वाला एक साइन किया हुआ संख्या। मान विवरण शून्य से कम: यह इंस्टेंस मान से पहले है। शून्य: यह इंस्टेंस मान के समान है। शून्य से अधिक: यह इंस्टेंस मान से बाद में है, या मान null है।
### equals(Object value) {#equals-java.lang.Object-}
```
public boolean equals(Object value)
```


Returns a value indicating whether this instance is equal to a specified object.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए एक ऑब्जेक्ट। |

**Returns:**
boolean - true यदि मान DateTime का इंस्टेंस है और इस इंस्टेंस के मान के बराबर है; अन्यथा false।
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


Gets the day of the month represented by this instance.

**Returns:**
int - दिन घटक, जो 1 से 31 के बीच के मान के रूप में व्यक्त किया गया है।
### getDayOfWeek() {#getDayOfWeek--}
```
public int getDayOfWeek()
```


Gets the day of the week represented by this instance.

**Returns:**
int - इस DateTime मान का सप्ताह का दिन।
### getDayOfYear() {#getDayOfYear--}
```
public int getDayOfYear()
```


इस उदाहरण द्वारा दर्शाए गए वर्ष का दिन प्राप्त करता है।

**Returns:**
int - वर्ष का दिन, जिसे 1 से 366 के बीच मान के रूप में व्यक्त किया जाता है।
### getHour() {#getHour--}
```
public int getHour()
```


इस उदाहरण द्वारा दर्शाए गए तिथि का घंटे घटक प्राप्त करता है।

**Returns:**
int - घंटे का घटक, जिसे 0 से 23 के बीच मान के रूप में व्यक्त किया जाता है।
### getMillisecond() {#getMillisecond--}
```
public int getMillisecond()
```


इस उदाहरण द्वारा दर्शाए गए तिथि का मिलीसेकंड घटक प्राप्त करता है।

**Returns:**
int - मिलीसेकंड का घटक, जिसे 0 से 999 के बीच मान के रूप में व्यक्त किया जाता है।
### getMinute() {#getMinute--}
```
public int getMinute()
```


इस उदाहरण द्वारा दर्शाए गए तिथि का मिनट घटक प्राप्त करता है।

**Returns:**
int - मिनट का घटक, जिसे 0 से 59 के बीच मान के रूप में व्यक्त किया जाता है।
### getMonth() {#getMonth--}
```
public int getMonth()
```


इस उदाहरण द्वारा दर्शाए गए तिथि का माह घटक प्राप्त करता है।

**Returns:**
int - महीने का घटक, जिसे 1 से 12 के बीच मान के रूप में व्यक्त किया जाता है।
### getNow() {#getNow--}
```
public static DateTime getNow()
```


एक DateTime ऑब्जेक्ट प्राप्त करता है जो इस कंप्यूटर पर वर्तमान तिथि और समय पर सेट होता है, स्थानीय समय के रूप में व्यक्त किया गया।

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the current local date and time.
### getSecond() {#getSecond--}
```
public int getSecond()
```


इस उदाहरण द्वारा दर्शाए गए तिथि का सेकंड घटक प्राप्त करता है।

**Returns:**
int - सेकंड, 0 से 59 के बीच।
### getYear() {#getYear--}
```
public int getYear()
```


इस उदाहरण द्वारा दर्शाए गए तिथि का वर्ष घटक प्राप्त करता है।

**Returns:**
int - वर्ष, 1 से 9999 के बीच।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - 32-बिट साइन्ड इंटेजर हैश कोड।
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


वर्तमान DateTime ऑब्जेक्ट के मान को Calendar ऑब्जेक्ट में परिवर्तित करता है।

**Returns:**
[Calendar](../../java.util/calendar) - Calendar object
### toDate() {#toDate--}
```
public Date toDate()
```


वर्तमान DateTime ऑब्जेक्ट के मान को Date ऑब्जेक्ट में परिवर्तित करता है।

**Returns:**
java.util.Date - डेट ऑब्जेक्ट
### toLocalTime() {#toLocalTime--}
```
public DateTime toLocalTime()
```


वर्तमान DateTime ऑब्जेक्ट के मान को स्थानीय समय में परिवर्तित करता है।

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object of local
### toString() {#toString--}
```
public String toString()
```


वर्तमान DateTime ऑब्जेक्ट के मान को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है।

**Returns:**
java.lang.String - वर्तमान DateTime ऑब्जेक्ट के मान का स्ट्रिंग प्रतिनिधित्व।
### toUniversalTime() {#toUniversalTime--}
```
public DateTime toUniversalTime()
```


वर्तमान DateTime ऑब्जेक्ट के मान को समन्वित सार्वभौमिक समय (UTC) में परिवर्तित करता है।

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

