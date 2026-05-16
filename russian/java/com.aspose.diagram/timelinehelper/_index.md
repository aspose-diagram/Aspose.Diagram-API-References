---
title: TimeLineHelper
second_title: Справочник API Aspose.Diagram for Java
description: TimeLineHelper для установки свойства формы временной шкалы.
type: docs
weight: 408
url: /ru/java/com.aspose.diagram/timelinehelper/
---

**Inheritance:**
java.lang.Object
```
public class TimeLineHelper
```

TimeLineHelper для установки свойства формы временной шкалы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TimeLineHelper(Shape shape)](#TimeLineHelper-com.aspose.diagram.Shape-) | TimeLineHelper. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDoubleStringFromDateTime(DateTime dateTime)](#getDoubleStringFromDateTime-com.aspose.diagram.DateTime-) | Convert the date time to double value. |
| [getTimePeriodFinish()](#getTimePeriodFinish--) | Time Period for finish of timeline shape |
| [getTimePeriodStart()](#getTimePeriodStart--) | Time Period for start of timeline shape |
| [getTimeScale()](#getTimeScale--) | scale of timeline shape |
| [getWeekEnd(DateTime startDate, int weekStart)](#getWeekEnd-com.aspose.diagram.DateTime-int-) | getweekstart |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshTimeLine()](#refreshTimeLine--) | Refresh time of timeline shapes |
| [setArrowHead(int value)](#setArrowHead-int-) | ArrowHead of timeline shape |
| [setAutoUpdate(boolean value)](#setAutoUpdate-boolean-) | whether to update data for markers (milestones, intervals) as they are moved on timeline |
| [setBeginWeek(int value)](#setBeginWeek-int-) | Begin week of timeline shape |
|  | [setDateFormatForBE(int value)](#setDateFormatForBE-int-) | DateFormat for start and finish of timeline shape /// |

| ----------------------- | ------------------------------- |
| **Value**\\u9286\\u20ac | **Format String**\\u9286\\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
|  | [setDateFormatForIntm(int value)](#setDateFormatForIntm-int-) | DateFormat for Intm of timeline shape /// |

| ----------------------- | ------------------------------- |
| **Value**\\u9286\\u20ac | **Format String**\\u9286\\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
| [setDateFormatStringForBE(String value)](#setDateFormatStringForBE-java.lang.String-) | DateFormat String for start and finish of timeline shape |
| [setDateFormatStringForIntm(String value)](#setDateFormatStringForIntm-java.lang.String-) | DateFormat String for Intm of timeline shape |
| [setDisplayBE(boolean value)](#setDisplayBE-boolean-) | whether to display Begin and End dates on timeline |
| [setDisplayIntm(boolean value)](#setDisplayIntm-boolean-) | whether to display interim date/time ticks on timeline |
| [setDisplayIntmDates(boolean value)](#setDisplayIntmDates-boolean-) | whether to display interim dates on interim ticks |
| [setFiscalStart(DateTime value)](#setFiscalStart-com.aspose.diagram.DateTime-) | First day of fiscal year |
| [setTimeLineType(int value)](#setTimeLineType-int-) | Begin week of timeline shape |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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


Convert the date time to double value.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dateTime | [DateTime](../../com.aspose.diagram/datetime) | Дата и время. |

**Returns:**
java.lang.String -
### getTimePeriodFinish() {#getTimePeriodFinish--}
```
public DateTime getTimePeriodFinish()
```


Time Period for finish of timeline shape

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimePeriodStart() {#getTimePeriodStart--}
```
public DateTime getTimePeriodStart()
```


Time Period for start of timeline shape

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeScale() {#getTimeScale--}
```
public int getTimeScale()
```


scale of timeline shape

**Returns:**
int
### getWeekEnd(DateTime startDate, int weekStart) {#getWeekEnd-com.aspose.diagram.DateTime-int-}
```
public static DateTime getWeekEnd(DateTime startDate, int weekStart)
```


getweekstart

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startDate | [DateTime](../../com.aspose.diagram/datetime) |  |
| weekStart | int | (0воскресенье 1понедельник 2 3 4 5 6) |

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


Refresh time of timeline shapes

### setArrowHead(int value) {#setArrowHead-int-}
```
public void setArrowHead(int value)
```


ArrowHead of timeline shape

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setAutoUpdate(boolean value) {#setAutoUpdate-boolean-}
```
public void setAutoUpdate(boolean value)
```


whether to update data for markers (milestones, intervals) as they are moved on timeline

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setBeginWeek(int value) {#setBeginWeek-int-}
```
public void setBeginWeek(int value)
```


Begin week of timeline shape

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDateFormatForBE(int value) {#setDateFormatForBE-int-}
```
public void setDateFormatForBE(int value)
```


DateFormat for start and finish of timeline shape ///

| ----------------------- | ------------------------------- |
| **Value**\\u9286\\u20ac | **Format String**\\u9286\\u20ac |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDateFormatForIntm(int value) {#setDateFormatForIntm-int-}
```
public void setDateFormatForIntm(int value)
```


DateFormat for Intm of timeline shape ///

| ----------------------- | ------------------------------- |
| **Value**\\u9286\\u20ac | **Format String**\\u9286\\u20ac |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDateFormatStringForBE(String value) {#setDateFormatStringForBE-java.lang.String-}
```
public void setDateFormatStringForBE(String value)
```


DateFormat String for start and finish of timeline shape

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDateFormatStringForIntm(String value) {#setDateFormatStringForIntm-java.lang.String-}
```
public void setDateFormatStringForIntm(String value)
```


DateFormat String for Intm of timeline shape

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDisplayBE(boolean value) {#setDisplayBE-boolean-}
```
public void setDisplayBE(boolean value)
```


whether to display Begin and End dates on timeline

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setDisplayIntm(boolean value) {#setDisplayIntm-boolean-}
```
public void setDisplayIntm(boolean value)
```


whether to display interim date/time ticks on timeline

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setDisplayIntmDates(boolean value) {#setDisplayIntmDates-boolean-}
```
public void setDisplayIntmDates(boolean value)
```


whether to display interim dates on interim ticks

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setFiscalStart(DateTime value) {#setFiscalStart-com.aspose.diagram.DateTime-}
```
public void setFiscalStart(DateTime value)
```


First day of fiscal year

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeLineType(int value) {#setTimeLineType-int-}
```
public void setTimeLineType(int value)
```


Begin week of timeline shape

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTimePeriodFinish(DateTime value) {#setTimePeriodFinish-com.aspose.diagram.DateTime-}
```
public void setTimePeriodFinish(DateTime value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePeriodStart(DateTime value) {#setTimePeriodStart-com.aspose.diagram.DateTime-}
```
public void setTimePeriodStart(DateTime value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeScale(int value) {#setTimeScale-int-}
```
public void setTimeScale(int value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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

