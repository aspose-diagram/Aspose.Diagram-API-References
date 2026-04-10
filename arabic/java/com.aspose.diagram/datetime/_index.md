---
title: DateTime
second_title: Aspose.Diagram لـ Java API Reference
description: يمثل لحظة في الزمن عادةً ما تُعبّر عنها كتاريخ ووقت اليوم.
type: docs
weight: 115
url: /ar/java/com.aspose.diagram/datetime/
---

**Inheritance:**
java.lang.Object
```
public class DateTime
```

يمثل لحظة زمنية، عادةً ما تُعبّر عنها كتاريخ ووقت اليوم.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DateTime(int year, int month, int day)](#DateTime-int-int-int-) | يُنشئ نسخة جديدة من كائن DateTime للسنة والشهر واليوم المحددين. |
| [DateTime(int year, int month, int day, int hour, int minute, int second)](#DateTime-int-int-int-int-int-int-) | يُنشئ نسخة جديدة من كائن DateTime للسنة والشهر واليوم والساعة والدقيقة والثانية المحددين. |
| [DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)](#DateTime-int-int-int-int-int-int-int-) | يُنشئ نسخة جديدة من كائن DateTime للسنة والشهر واليوم والساعة والدقيقة والثانية والمللي ثانية المحددين. |
| [DateTime(Date date)](#DateTime-java.util.Date-) | يُنشئ نسخة جديدة من كائن DateTime لكائن Date المحدد |
| [DateTime(Calendar cld)](#DateTime-java.util.Calendar-) | يُنشئ نسخة جديدة من كائن DateTime لكائن Calendar المحدد |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addDays(double value)](#addDays-double-) | يضيف عدد الأيام المحدد إلى قيمة هذه النسخة. |
| [addHours(double value)](#addHours-double-) | يضيف عدد الساعات المحدد إلى قيمة هذه النسخة. |
| [addMilliseconds(double value)](#addMilliseconds-double-) | يضيف عدد المللي ثانية المحدد إلى قيمة هذه النسخة. |
| [addMinutes(double value)](#addMinutes-double-) | يضيف عدد الدقائق المحدد إلى قيمة هذه النسخة. |
| [addMonths(int months)](#addMonths-int-) | يضيف عدد الأشهر المحدد إلى قيمة هذه النسخة. |
| [addSeconds(double value)](#addSeconds-double-) | يضيف عدد الثواني المحدد إلى قيمة هذه النسخة. |
| [addYears(int value)](#addYears-int-) | يضيف عدد السنوات المحدد إلى قيمة هذه النسخة. |
| [compareTo(DateTime value)](#compareTo-com.aspose.diagram.DateTime-) | يقارن قيمة هذه النسخة بقيمة DateTime محددة ويعيد عددًا صحيحًا يُشير إلى ما إذا كانت هذه النسخة أسبق، أو مساوية، أو لاحقة لقيمة DateTime المحددة. |
| [compareTo(Object value)](#compareTo-java.lang.Object-) | يقارن قيمة هذه النسخة بكائن محدد يحتوي على قيمة DateTime محددة، ويعيد عددًا صحيحًا يُشير إلى ما إذا كانت هذه النسخة أسبق، أو مساوية، أو لاحقة لقيمة DateTime المحددة. |
| [equals(Object value)](#equals-java.lang.Object-) | يعيد قيمة تُشير إلى ما إذا كانت هذه النسخة مساوية لكائن محدد. |
| [getClass()](#getClass--) |  |
| [getDay()](#getDay--) | يحصل على يوم الشهر الممثّل بهذه النسخة. |
| [getDayOfWeek()](#getDayOfWeek--) | يحصل على يوم الأسبوع الممثّل بهذه النسخة. |
| [getDayOfYear()](#getDayOfYear--) | يحصل على اليوم من السنة الممثَّل بهذا الكائن. |
| [getHour()](#getHour--) | يحصل على مكوّن الساعة من التاريخ الممثَّل بهذا الكائن. |
| [getMillisecond()](#getMillisecond--) | يحصل على مكوّن المللي ثانية من التاريخ الممثَّل بهذا الكائن. |
| [getMinute()](#getMinute--) | يحصل على مكوّن الدقيقة من التاريخ الممثَّل بهذا الكائن. |
| [getMonth()](#getMonth--) | يحصل على مكوّن الشهر من التاريخ الممثَّل بهذا الكائن. |
| [getNow()](#getNow--) | يحصل على كائن DateTime يتم ضبطه على التاريخ والوقت الحاليين على هذا الحاسوب، معبَّرًا عنه كوقت محلي. |
| [getSecond()](#getSecond--) | يحصل على مكوّن الثواني من التاريخ الممثَّل بهذا الكائن. |
| [getYear()](#getYear--) | يحصل على مكوّن السنة من التاريخ الممثَّل بهذا الكائن. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toCalendar()](#toCalendar--) | يحوّل قيمة كائن DateTime الحالي إلى كائن Calendar. |
| [toDate()](#toDate--) | يحوّل قيمة كائن DateTime الحالي إلى كائن Date. |
| [toLocalTime()](#toLocalTime--) | يحوّل قيمة كائن DateTime الحالي إلى الوقت المحلي. |
| [toString()](#toString--) | يحوّل قيمة كائن DateTime الحالي إلى تمثيله النصي المكافئ. |
| [toUniversalTime()](#toUniversalTime--) | يحوّل قيمة كائن DateTime الحالي إلى التوقيت العالمي المنسق (UTC). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DateTime(int year, int month, int day) {#DateTime-int-int-int-}
```
public DateTime(int year, int month, int day)
```


يُنشئ نسخة جديدة من كائن DateTime للسنة والشهر واليوم المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السنة | int | السنة (من 1 إلى 9999). |
| الشهر | int | الشهر (من 1 إلى 12). |
| اليوم | int | اليوم (من 1 إلى عدد الأيام في الشهر). |

### DateTime(int year, int month, int day, int hour, int minute, int second) {#DateTime-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second)
```


يُنشئ نسخة جديدة من كائن DateTime للسنة والشهر واليوم والساعة والدقيقة والثانية المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السنة | int | السنة (من 1 إلى 9999). |
| الشهر | int | الشهر (من 1 إلى 12). |
| اليوم | int | اليوم (من 1 إلى عدد الأيام في الشهر). |
| الساعة | int | الساعات (من 0 إلى 23). |
| الدقيقة | int | الدقائق (من 0 إلى 59). |
| الثانية | int | الثواني (0 إلى 59). |

### DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond) {#DateTime-int-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)
```


يُنشئ نسخة جديدة من كائن DateTime للسنة والشهر واليوم والساعة والدقيقة والثانية والمللي ثانية المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السنة | int | السنة (من 1 إلى 9999). |
| الشهر | int | الشهر (من 1 إلى 12). |
| اليوم | int | اليوم (من 1 إلى عدد الأيام في الشهر). |
| الساعة | int | الساعات (من 0 إلى 23). |
| الدقيقة | int | الدقائق (من 0 إلى 59). |
| الثانية | int | الثواني (0 إلى 59). |
| مللي ثانية | int | الميليثواني (0 إلى 999). |

### DateTime(Date date) {#DateTime-java.util.Date-}
```
public DateTime(Date date)
```


يُنشئ نسخة جديدة من كائن DateTime لكائن Date المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تاريخ | java.util.Date | كائن Date |

### DateTime(Calendar cld) {#DateTime-java.util.Calendar-}
```
public DateTime(Calendar cld)
```


يُنشئ نسخة جديدة من كائن DateTime لكائن Calendar المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cld | java.util.Calendar | كائن Calendar |

### addDays(double value) {#addDays-double-}
```
public DateTime addDays(double value)
```


يضيف عدد الأيام المحدد إلى قيمة هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | عدد من الأيام الكاملة والجزئية. يمكن أن يكون معامل القيمة سالبًا أو موجبًا. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of days represented by value.
### addHours(double value) {#addHours-double-}
```
public DateTime addHours(double value)
```


يضيف عدد الساعات المحدد إلى قيمة هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | عدد من الساعات الكاملة والجزئية. يمكن أن يكون معامل القيمة سالبًا أو موجبًا. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of hours represented by value.
### addMilliseconds(double value) {#addMilliseconds-double-}
```
public DateTime addMilliseconds(double value)
```


يضيف عدد المللي ثانية المحدد إلى قيمة هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | عدد من الميليثواني الكاملة والجزئية. يمكن أن يكون معامل القيمة سالبًا أو موجبًا. لاحظ أن هذه القيمة تُقرب إلى أقرب عدد صحيح. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of milliseconds represented by value.
### addMinutes(double value) {#addMinutes-double-}
```
public DateTime addMinutes(double value)
```


يضيف عدد الدقائق المحدد إلى قيمة هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | عدد من الدقائق الكاملة والجزئية. يمكن أن يكون معامل القيمة سالبًا أو موجبًا. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of minutes represented by value.
### addMonths(int months) {#addMonths-int-}
```
public DateTime addMonths(int months)
```


يضيف عدد الأشهر المحدد إلى قيمة هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| أشهر | int | عدد من الأشهر. يمكن أن يكون معامل الأشهر سالبًا أو موجبًا. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and months.
### addSeconds(double value) {#addSeconds-double-}
```
public DateTime addSeconds(double value)
```


يضيف عدد الثواني المحدد إلى قيمة هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | عدد من الثواني الكاملة والجزئية. يمكن أن يكون معامل القيمة سالبًا أو موجبًا. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of seconds represented by value.
### addYears(int value) {#addYears-int-}
```
public DateTime addYears(int value)
```


يضيف عدد السنوات المحدد إلى قيمة هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int | عدد من السنوات. يمكن أن يكون معامل القيمة سالبًا أو موجبًا. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of years represented by value.
### compareTo(DateTime value) {#compareTo-com.aspose.diagram.DateTime-}
```
public int compareTo(DateTime value)
```


يقارن قيمة هذه النسخة بقيمة DateTime محددة ويعيد عددًا صحيحًا يُشير إلى ما إذا كانت هذه النسخة أسبق، أو مساوية، أو لاحقة لقيمة DateTime المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) | كائن DateTime للمقارنة. |

**Returns:**
int - رقم موقع يشير إلى القيم النسبية لهذا الكائن ومعامل القيمة. الوصف: القيمة. أقل من الصفر: هذا الكائن أسبق القيمة. صفر: هذا الكائن يساوي القيمة. أكبر من الصفر: هذا الكائن لاحق القيمة.
### compareTo(Object value) {#compareTo-java.lang.Object-}
```
public int compareTo(Object value)
```


يقارن قيمة هذه النسخة بكائن محدد يحتوي على قيمة DateTime محددة، ويعيد عددًا صحيحًا يُشير إلى ما إذا كانت هذه النسخة أسبق، أو مساوية، أو لاحقة لقيمة DateTime المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object | كائن DateTime مُغلف للمقارنة، أو null. |

**Returns:**
int - رقم موقع يشير إلى القيم النسبية لهذا الكائن وvalue. الوصف: القيمة. أقل من الصفر: هذا الكائن أسبق القيمة. صفر: هذا الكائن يساوي القيمة. أكبر من الصفر: هذا الكائن لاحق القيمة، أو value هو null.
### equals(Object value) {#equals-java.lang.Object-}
```
public boolean equals(Object value)
```


يعيد قيمة تُشير إلى ما إذا كانت هذه النسخة مساوية لكائن محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object | كائن للمقارنة مع هذا الكائن. |

**Returns:**
boolean - true إذا كان value كائنًا من نوع DateTime ويساوي قيمة هذا الكائن؛ وإلا false.
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


يحصل على يوم الشهر الممثّل بهذه النسخة.

**Returns:**
int - مكوّن اليوم، معبرًا عنه كقيمة بين 1 و 31.
### getDayOfWeek() {#getDayOfWeek--}
```
public int getDayOfWeek()
```


يحصل على يوم الأسبوع الممثّل بهذه النسخة.

**Returns:**
int - يوم الأسبوع لهذا القيمة DateTime.
### getDayOfYear() {#getDayOfYear--}
```
public int getDayOfYear()
```


يحصل على اليوم من السنة الممثَّل بهذا الكائن.

**Returns:**
int - اليوم من السنة، معبرًا عنه كقيمة بين 1 و 366.
### getHour() {#getHour--}
```
public int getHour()
```


يحصل على مكوّن الساعة من التاريخ الممثَّل بهذا الكائن.

**Returns:**
int - مكوّن الساعة، معبرًا عنه كقيمة بين 0 و 23.
### getMillisecond() {#getMillisecond--}
```
public int getMillisecond()
```


يحصل على مكوّن المللي ثانية من التاريخ الممثَّل بهذا الكائن.

**Returns:**
int - مكوّن الميللي ثانية، معبرًا عنه كقيمة بين 0 و 999.
### getMinute() {#getMinute--}
```
public int getMinute()
```


يحصل على مكوّن الدقيقة من التاريخ الممثَّل بهذا الكائن.

**Returns:**
int - مكوّن الدقيقة، معبرًا عنه كقيمة بين 0 و 59.
### getMonth() {#getMonth--}
```
public int getMonth()
```


يحصل على مكوّن الشهر من التاريخ الممثَّل بهذا الكائن.

**Returns:**
int - مكوّن الشهر، معبرًا عنه كقيمة بين 1 و 12.
### getNow() {#getNow--}
```
public static DateTime getNow()
```


يحصل على كائن DateTime يتم ضبطه على التاريخ والوقت الحاليين على هذا الحاسوب، معبَّرًا عنه كوقت محلي.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the current local date and time.
### getSecond() {#getSecond--}
```
public int getSecond()
```


يحصل على مكوّن الثواني من التاريخ الممثَّل بهذا الكائن.

**Returns:**
int - الثواني، بين 0 و 59.
### getYear() {#getYear--}
```
public int getYear()
```


يحصل على مكوّن السنة من التاريخ الممثَّل بهذا الكائن.

**Returns:**
int - السنة، بين 1 و 9999.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز التجزئة لهذا الكائن.

**Returns:**
int - رمز تجزئة صحيح موقّع 32-بت.
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


يحوّل قيمة كائن DateTime الحالي إلى كائن Calendar.

**Returns:**
[Calendar](../../java.util/calendar) - Calendar object
### toDate() {#toDate--}
```
public Date toDate()
```


يحوّل قيمة كائن DateTime الحالي إلى كائن Date.

**Returns:**
java.util.Date - كائن تاريخ
### toLocalTime() {#toLocalTime--}
```
public DateTime toLocalTime()
```


يحوّل قيمة كائن DateTime الحالي إلى الوقت المحلي.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object of local
### toString() {#toString--}
```
public String toString()
```


يحوّل قيمة كائن DateTime الحالي إلى تمثيله النصي المكافئ.

**Returns:**
java.lang.String - تمثيل نصي لقيمة كائن DateTime الحالي.
### toUniversalTime() {#toUniversalTime--}
```
public DateTime toUniversalTime()
```


يحوّل قيمة كائن DateTime الحالي إلى التوقيت العالمي المنسق (UTC).

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

