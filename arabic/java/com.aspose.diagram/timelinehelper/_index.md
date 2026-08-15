---
title: TimeLineHelper
second_title: Aspose.Diagram لـ Java API Reference
description: TimeLineHelper لتعيين خاصية شكل الخط الزمني.
type: docs
weight: 408
url: /ar/java/com.aspose.diagram/timelinehelper/
---

**Inheritance:**
java.lang.Object
```
public class TimeLineHelper
```

TimeLineHelper لتعيين خاصية شكل الخط الزمني.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TimeLineHelper(Shape shape)](#TimeLineHelper-com.aspose.diagram.Shape-) | TimeLineHelper. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDoubleStringFromDateTime(DateTime dateTime)](#getDoubleStringFromDateTime-com.aspose.diagram.DateTime-) | تحويل التاريخ والوقت إلى قيمة مزدوجة. |
| [getTimePeriodFinish()](#getTimePeriodFinish--) | فترة الوقت لإنهاء شكل المخطط الزمني |
| [getTimePeriodStart()](#getTimePeriodStart--) | فترة الوقت لبدء شكل المخطط الزمني |
| [getTimeScale()](#getTimeScale--) | مقياس شكل المخطط الزمني |
| [getWeekEnd(DateTime startDate, int weekStart)](#getWeekEnd-com.aspose.diagram.DateTime-int-) | getweekstart |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshTimeLine()](#refreshTimeLine--) | تحديث وقت أشكال المخطط الزمني |
| [setArrowHead(int value)](#setArrowHead-int-) | رأس السهم لشكل المخطط الزمني |
| [setAutoUpdate(boolean value)](#setAutoUpdate-boolean-) | ما إذا كان سيتم تحديث البيانات للعلامات (المعالم، الفواصل) عند تحريكها على المخطط الزمني |
| [setBeginWeek(int value)](#setBeginWeek-int-) | الأسبوع الأول لشكل المخطط الزمني |
|  | [setDateFormatForBE(int value)](#setDateFormatForBE-int-) | تنسيق التاريخ للبدء والانتهاء من شكل المخطط الزمني /// |

| ----------------------- | ------------------------------- |
| **القيمة**\u9286\u20ac | **سلسلة التنسيق**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
|  | [setDateFormatForIntm(int value)](#setDateFormatForIntm-int-) | تنسيق التاريخ للـ Intm في شكل المخطط الزمني /// |

| ----------------------- | ------------------------------- |
| **القيمة**\u9286\u20ac | **سلسلة التنسيق**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
| [setDateFormatStringForBE(String value)](#setDateFormatStringForBE-java.lang.String-) | سلسلة تنسيق التاريخ للبدء والانتهاء من شكل المخطط الزمني |
| [setDateFormatStringForIntm(String value)](#setDateFormatStringForIntm-java.lang.String-) | سلسلة تنسيق التاريخ للـ Intm في شكل المخطط الزمني |
| [setDisplayBE(boolean value)](#setDisplayBE-boolean-) | ما إذا كان سيتم عرض تواريخ البداية والنهاية على المخطط الزمني |
| [setDisplayIntm(boolean value)](#setDisplayIntm-boolean-) | ما إذا كان سيتم عرض علامات الوقت/التاريخ المؤقتة على المخطط الزمني |
| [setDisplayIntmDates(boolean value)](#setDisplayIntmDates-boolean-) | ما إذا كان سيتم عرض التواريخ المؤقتة على العلامات المؤقتة |
| [setFiscalStart(DateTime value)](#setFiscalStart-com.aspose.diagram.DateTime-) | اليوم الأول من السنة المالية |
| [setTimeLineType(int value)](#setTimeLineType-int-) | الأسبوع الأول لشكل المخطط الزمني |
| [setTimePeriodFinish(DateTime value)](#setTimePeriodFinish-com.aspose.diagram.DateTime-) |  |
| [setTimePeriodStart(DateTime value)](#setTimePeriodStart-com.aspose.diagram.DateTime-) |  |
| [setTimeScale(int value)](#setTimeScale-int-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TimeLineHelper(Shape shape) {#TimeLineHelper-com.aspose.diagram.Shape-}
```
public TimeLineHelper(Shape shape)
```


TimeLineHelper.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
منطقي
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDoubleStringFromDateTime(DateTime dateTime) {#getDoubleStringFromDateTime-com.aspose.diagram.DateTime-}
```
public static String getDoubleStringFromDateTime(DateTime dateTime)
```


تحويل التاريخ والوقت إلى قيمة مزدوجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dateTime | [DateTime](../../com.aspose.diagram/datetime) | التاريخ والوقت. |

**Returns:**
java.lang.String -
### getTimePeriodFinish() {#getTimePeriodFinish--}
```
public DateTime getTimePeriodFinish()
```


فترة الوقت لإنهاء شكل المخطط الزمني

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimePeriodStart() {#getTimePeriodStart--}
```
public DateTime getTimePeriodStart()
```


فترة الوقت لبدء شكل المخطط الزمني

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeScale() {#getTimeScale--}
```
public int getTimeScale()
```


مقياس شكل المخطط الزمني

**Returns:**
int
### getWeekEnd(DateTime startDate, int weekStart) {#getWeekEnd-com.aspose.diagram.DateTime-int-}
```
public static DateTime getWeekEnd(DateTime startDate, int weekStart)
```


getweekstart

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startDate | [DateTime](../../com.aspose.diagram/datetime) |  |
| بداية الأسبوع | int | (0الأحد 1الإثنين 2 3 4 5 6) |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - 
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshTimeLine() {#refreshTimeLine--}
```
public void refreshTimeLine()
```


تحديث وقت أشكال المخطط الزمني

### setArrowHead(int value) {#setArrowHead-int-}
```
public void setArrowHead(int value)
```


رأس السهم لشكل المخطط الزمني

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setAutoUpdate(boolean value) {#setAutoUpdate-boolean-}
```
public void setAutoUpdate(boolean value)
```


ما إذا كان سيتم تحديث البيانات للعلامات (المعالم، الفواصل) عند تحريكها على المخطط الزمني

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setBeginWeek(int value) {#setBeginWeek-int-}
```
public void setBeginWeek(int value)
```


الأسبوع الأول لشكل المخطط الزمني

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setDateFormatForBE(int value) {#setDateFormatForBE-int-}
```
public void setDateFormatForBE(int value)
```


تنسيق التاريخ للبدء والانتهاء من شكل المخطط الزمني ///

| ----------------------- | ------------------------------- |
| **القيمة**\u9286\u20ac | **سلسلة التنسيق**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.-d                       |
| 5                       | d MMMM yyyy                     |
| 6                       | yy-M                            |
| 7                       | MMM-yy                          |
| 8                       | MMMM d, yyyy                    |
| 9                       | MMM d, yyyy                     |
| 10                      | M-d-yy                          |
| 11                      | M-d                             |
| 12                      | d MMMM, yyyy                    |
| 13                      | d MMM, yyyy                     |
| 14                      | d-M-yy                          |
| 15                      | d-M                             |
| 16                      | yy-M-d                          |
| 17                      | yyyy-M-d                        |
| 18                      | M-yy                            |
| 19                      | M-yyyy                          |
| 20                      | MMMM yyyy                       |
| 21                      | MMMM yy                         |
| 22                      | MMM yyyy                        |
| 23                      | MMM yy                          |
| 24                      | yy                              |
| 25                      | yyyy                            |
| 26                      | d                               |
| 27                      | MMMM                            |
| 28                      | MMM                             |
| 29                      | M                               |
| 30                      | MM/dd/yyyy                      |

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setDateFormatForIntm(int value) {#setDateFormatForIntm-int-}
```
public void setDateFormatForIntm(int value)
```


تنسيق التاريخ للـ Intm في شكل المخطط الزمني ///

| ----------------------- | ------------------------------- |
| **القيمة**\u9286\u20ac | **سلسلة التنسيق**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.-d                       |
| 5                       | d MMMM yyyy                     |
| 6                       | yy-M                            |
| 7                       | MMM-yy                          |
| 8                       | MMMM d, yyyy                    |
| 9                       | MMM d, yyyy                     |
| 10                      | M-d-yy                          |
| 11                      | M-d                             |
| 12                      | d MMMM, yyyy                    |
| 13                      | d MMM, yyyy                     |
| 14                      | d-M-yy                          |
| 15                      | d-M                             |
| 16                      | yy-M-d                          |
| 17                      | yyyy-M-d                        |
| 18                      | M-yy                            |
| 19                      | M-yyyy                          |
| 20                      | MMMM yyyy                       |
| 21                      | MMMM yy                         |
| 22                      | MMM yyyy                        |
| 23                      | MMM yy                          |
| 24                      | yy                              |
| 25                      | yyyy                            |
| 26                      | d                               |
| 27                      | MMMM                            |
| 28                      | MMM                             |
| 29                      | M                               |
| 30                      | MM/dd/yyyy                      |

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setDateFormatStringForBE(String value) {#setDateFormatStringForBE-java.lang.String-}
```
public void setDateFormatStringForBE(String value)
```


سلسلة تنسيق التاريخ للبدء والانتهاء من شكل المخطط الزمني

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setDateFormatStringForIntm(String value) {#setDateFormatStringForIntm-java.lang.String-}
```
public void setDateFormatStringForIntm(String value)
```


سلسلة تنسيق التاريخ للـ Intm في شكل المخطط الزمني

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setDisplayBE(boolean value) {#setDisplayBE-boolean-}
```
public void setDisplayBE(boolean value)
```


ما إذا كان سيتم عرض تواريخ البداية والنهاية على المخطط الزمني

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setDisplayIntm(boolean value) {#setDisplayIntm-boolean-}
```
public void setDisplayIntm(boolean value)
```


ما إذا كان سيتم عرض علامات الوقت/التاريخ المؤقتة على المخطط الزمني

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setDisplayIntmDates(boolean value) {#setDisplayIntmDates-boolean-}
```
public void setDisplayIntmDates(boolean value)
```


ما إذا كان سيتم عرض التواريخ المؤقتة على العلامات المؤقتة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setFiscalStart(DateTime value) {#setFiscalStart-com.aspose.diagram.DateTime-}
```
public void setFiscalStart(DateTime value)
```


اليوم الأول من السنة المالية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeLineType(int value) {#setTimeLineType-int-}
```
public void setTimeLineType(int value)
```


الأسبوع الأول لشكل المخطط الزمني

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setTimePeriodFinish(DateTime value) {#setTimePeriodFinish-com.aspose.diagram.DateTime-}
```
public void setTimePeriodFinish(DateTime value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePeriodStart(DateTime value) {#setTimePeriodStart-com.aspose.diagram.DateTime-}
```
public void setTimePeriodStart(DateTime value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeScale(int value) {#setTimeScale-int-}
```
public void setTimeScale(int value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

