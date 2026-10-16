---
title: TimeLineHelper
second_title: Aspose.Diagram for Java API Reference
description: TimeLineHelper to set property of timeline shape.
type: docs
weight: 434
url: /java/com.aspose.diagram/timelinehelper/
---

**Inheritance:**
java.lang.Object
```
public class TimeLineHelper
```

TimeLineHelper to set property of timeline shape. Compatibility shell over [TimeLineProperties](../../com.aspose.diagram/timelineproperties): the public API is unchanged (plus getters for the previously write-only properties), the cell access is delegated to the properties class, and [refreshTimeLine()](../../com.aspose.diagram/timelinehelper\#refreshTimeLine--) is rewritten:

    | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | /// The begin/end date text shapes are updated by position without skipping the last /// child, so the end-date text shape is updated as well. ///                                                                                 |
    | /// Master-instance markers (milestones, intervals) inside the period keep their /// field \\u9225?the old code overwrote every master-instance child field with the start /// date. Out-of-range markers are deleted instead. /// |
    | /// Previously generated interim ticks are removed and regenerated with the interim /// User cells (visTLShape, visInterimType) that real timeline ticks carry, so they /// render as timeline ticks in Visio. ///                 |
    | /// Year-scale ticks land on January 1 boundaries, so ranges that cross a year /// boundary are no longer empty for spans under one year. ///                                                                                      |

    |
## Constructors

| Constructor | Description |
| --- | --- |
| [TimeLineHelper(Shape shape)](#TimeLineHelper-com.aspose.diagram.Shape-) | TimeLineHelper. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArrowHead()](#getArrowHead--) | ArrowHead of timeline shape |
| [getBeginWeek()](#getBeginWeek--) | Begin week of timeline shape |
| [getClass()](#getClass--) |  |
| [getDateFormatForBE()](#getDateFormatForBE--) | DateFormat for start and finish of timeline shape |
| [getDateFormatForIntm()](#getDateFormatForIntm--) | DateFormat for Intm of timeline shape |
| [getDateFormatStringForBE()](#getDateFormatStringForBE--) | DateFormat String for start and finish of timeline shape |
| [getDateFormatStringForIntm()](#getDateFormatStringForIntm--) | DateFormat String for Intm of timeline shape |
| [getDoubleStringFromDateTime(DateTime dateTime)](#getDoubleStringFromDateTime-com.aspose.diagram.DateTime-) | Convert the date time to double value. |
| [getFiscalStart()](#getFiscalStart--) | First day of fiscal year |
| [getTimeLineType()](#getTimeLineType--) | Begin week of timeline shape |
| [getTimePeriodFinish()](#getTimePeriodFinish--) | Time Period for finish of timeline shape |
| [getTimePeriodStart()](#getTimePeriodStart--) | Time Period for start of timeline shape |
| [getTimeScale()](#getTimeScale--) | scale of timeline shape |
| [getWeekEnd(DateTime startDate, int weekStart)](#getWeekEnd-com.aspose.diagram.DateTime-int-) | getweekstart |
| [hashCode()](#hashCode--) |  |
| [isAutoUpdate()](#isAutoUpdate--) | whether to update data for markers (milestones, intervals) as they are moved on timeline |
| [isDisplayBE()](#isDisplayBE--) | whether to display Begin and End dates on timeline |
| [isDisplayIntm()](#isDisplayIntm--) | whether to display interim date/time ticks on timeline |
| [isDisplayIntmDates()](#isDisplayIntmDates--) | whether to display interim dates on interim ticks |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshTimeLine()](#refreshTimeLine--) | Refresh time of timeline shapes |
| [setArrowHead(int value)](#setArrowHead-int-) | For the description of this property, please see [getArrowHead()](../../com.aspose.diagram/timelinehelper\#getArrowHead--) |
| [setAutoUpdate(boolean value)](#setAutoUpdate-boolean-) | For the description of this property, please see [isAutoUpdate()](../../com.aspose.diagram/timelinehelper\#isAutoUpdate--) |
| [setBeginWeek(int value)](#setBeginWeek-int-) | For the description of this property, please see [getBeginWeek()](../../com.aspose.diagram/timelinehelper\#getBeginWeek--) |
| [setDateFormatForBE(int value)](#setDateFormatForBE-int-) | For the description of this property, please see [getDateFormatForBE()](../../com.aspose.diagram/timelinehelper\#getDateFormatForBE--) |
| [setDateFormatForIntm(int value)](#setDateFormatForIntm-int-) | For the description of this property, please see [getDateFormatForIntm()](../../com.aspose.diagram/timelinehelper\#getDateFormatForIntm--) |
| [setDateFormatStringForBE(String value)](#setDateFormatStringForBE-java.lang.String-) | For the description of this property, please see [getDateFormatStringForBE()](../../com.aspose.diagram/timelinehelper\#getDateFormatStringForBE--) |
| [setDateFormatStringForIntm(String value)](#setDateFormatStringForIntm-java.lang.String-) | For the description of this property, please see [getDateFormatStringForIntm()](../../com.aspose.diagram/timelinehelper\#getDateFormatStringForIntm--) |
| [setDisplayBE(boolean value)](#setDisplayBE-boolean-) | For the description of this property, please see [isDisplayBE()](../../com.aspose.diagram/timelinehelper\#isDisplayBE--) |
| [setDisplayIntm(boolean value)](#setDisplayIntm-boolean-) | For the description of this property, please see [isDisplayIntm()](../../com.aspose.diagram/timelinehelper\#isDisplayIntm--) |
| [setDisplayIntmDates(boolean value)](#setDisplayIntmDates-boolean-) | For the description of this property, please see [isDisplayIntmDates()](../../com.aspose.diagram/timelinehelper\#isDisplayIntmDates--) |
| [setFiscalStart(DateTime value)](#setFiscalStart-com.aspose.diagram.DateTime-) | For the description of this property, please see [getFiscalStart()](../../com.aspose.diagram/timelinehelper\#getFiscalStart--) |
| [setTimeLineType(int value)](#setTimeLineType-int-) | For the description of this property, please see [getTimeLineType()](../../com.aspose.diagram/timelinehelper\#getTimeLineType--) |
| [setTimePeriodFinish(DateTime value)](#setTimePeriodFinish-com.aspose.diagram.DateTime-) | For the description of this property, please see [getTimePeriodFinish()](../../com.aspose.diagram/timelinehelper\#getTimePeriodFinish--) |
| [setTimePeriodStart(DateTime value)](#setTimePeriodStart-com.aspose.diagram.DateTime-) | For the description of this property, please see [getTimePeriodStart()](../../com.aspose.diagram/timelinehelper\#getTimePeriodStart--) |
| [setTimeScale(int value)](#setTimeScale-int-) | For the description of this property, please see [getTimeScale()](../../com.aspose.diagram/timelinehelper\#getTimeScale--) |
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
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArrowHead() {#getArrowHead--}
```
public int getArrowHead()
```


ArrowHead of timeline shape

**Returns:**
int
### getBeginWeek() {#getBeginWeek--}
```
public int getBeginWeek()
```


Begin week of timeline shape

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateFormatForBE() {#getDateFormatForBE--}
```
public int getDateFormatForBE()
```


DateFormat for start and finish of timeline shape

**Returns:**
int
### getDateFormatForIntm() {#getDateFormatForIntm--}
```
public int getDateFormatForIntm()
```


DateFormat for Intm of timeline shape

**Returns:**
int
### getDateFormatStringForBE() {#getDateFormatStringForBE--}
```
public String getDateFormatStringForBE()
```


DateFormat String for start and finish of timeline shape

**Returns:**
java.lang.String
### getDateFormatStringForIntm() {#getDateFormatStringForIntm--}
```
public String getDateFormatStringForIntm()
```


DateFormat String for Intm of timeline shape

**Returns:**
java.lang.String
### getDoubleStringFromDateTime(DateTime dateTime) {#getDoubleStringFromDateTime-com.aspose.diagram.DateTime-}
```
public static String getDoubleStringFromDateTime(DateTime dateTime)
```


Convert the date time to double value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateTime | [DateTime](../../com.aspose.diagram/datetime) | The date time. |

**Returns:**
java.lang.String - 
### getFiscalStart() {#getFiscalStart--}
```
public DateTime getFiscalStart()
```


First day of fiscal year

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeLineType() {#getTimeLineType--}
```
public int getTimeLineType()
```


Begin week of timeline shape

**Returns:**
int
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
| Parameter | Type | Description |
| --- | --- | --- |
| startDate | [DateTime](../../com.aspose.diagram/datetime) |  |
| weekStart | int | (0sunday 1monday 2 3 4 5 6) |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - 
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoUpdate() {#isAutoUpdate--}
```
public boolean isAutoUpdate()
```


whether to update data for markers (milestones, intervals) as they are moved on timeline

**Returns:**
boolean
### isDisplayBE() {#isDisplayBE--}
```
public boolean isDisplayBE()
```


whether to display Begin and End dates on timeline

**Returns:**
boolean
### isDisplayIntm() {#isDisplayIntm--}
```
public boolean isDisplayIntm()
```


whether to display interim date/time ticks on timeline

**Returns:**
boolean
### isDisplayIntmDates() {#isDisplayIntmDates--}
```
public boolean isDisplayIntmDates()
```


whether to display interim dates on interim ticks

**Returns:**
boolean
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


For the description of this property, please see [getArrowHead()](../../com.aspose.diagram/timelinehelper\#getArrowHead--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setAutoUpdate(boolean value) {#setAutoUpdate-boolean-}
```
public void setAutoUpdate(boolean value)
```


For the description of this property, please see [isAutoUpdate()](../../com.aspose.diagram/timelinehelper\#isAutoUpdate--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setBeginWeek(int value) {#setBeginWeek-int-}
```
public void setBeginWeek(int value)
```


For the description of this property, please see [getBeginWeek()](../../com.aspose.diagram/timelinehelper\#getBeginWeek--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDateFormatForBE(int value) {#setDateFormatForBE-int-}
```
public void setDateFormatForBE(int value)
```


For the description of this property, please see [getDateFormatForBE()](../../com.aspose.diagram/timelinehelper\#getDateFormatForBE--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDateFormatForIntm(int value) {#setDateFormatForIntm-int-}
```
public void setDateFormatForIntm(int value)
```


For the description of this property, please see [getDateFormatForIntm()](../../com.aspose.diagram/timelinehelper\#getDateFormatForIntm--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDateFormatStringForBE(String value) {#setDateFormatStringForBE-java.lang.String-}
```
public void setDateFormatStringForBE(String value)
```


For the description of this property, please see [getDateFormatStringForBE()](../../com.aspose.diagram/timelinehelper\#getDateFormatStringForBE--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDateFormatStringForIntm(String value) {#setDateFormatStringForIntm-java.lang.String-}
```
public void setDateFormatStringForIntm(String value)
```


For the description of this property, please see [getDateFormatStringForIntm()](../../com.aspose.diagram/timelinehelper\#getDateFormatStringForIntm--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDisplayBE(boolean value) {#setDisplayBE-boolean-}
```
public void setDisplayBE(boolean value)
```


For the description of this property, please see [isDisplayBE()](../../com.aspose.diagram/timelinehelper\#isDisplayBE--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDisplayIntm(boolean value) {#setDisplayIntm-boolean-}
```
public void setDisplayIntm(boolean value)
```


For the description of this property, please see [isDisplayIntm()](../../com.aspose.diagram/timelinehelper\#isDisplayIntm--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setDisplayIntmDates(boolean value) {#setDisplayIntmDates-boolean-}
```
public void setDisplayIntmDates(boolean value)
```


For the description of this property, please see [isDisplayIntmDates()](../../com.aspose.diagram/timelinehelper\#isDisplayIntmDates--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFiscalStart(DateTime value) {#setFiscalStart-com.aspose.diagram.DateTime-}
```
public void setFiscalStart(DateTime value)
```


For the description of this property, please see [getFiscalStart()](../../com.aspose.diagram/timelinehelper\#getFiscalStart--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeLineType(int value) {#setTimeLineType-int-}
```
public void setTimeLineType(int value)
```


For the description of this property, please see [getTimeLineType()](../../com.aspose.diagram/timelinehelper\#getTimeLineType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTimePeriodFinish(DateTime value) {#setTimePeriodFinish-com.aspose.diagram.DateTime-}
```
public void setTimePeriodFinish(DateTime value)
```


For the description of this property, please see [getTimePeriodFinish()](../../com.aspose.diagram/timelinehelper\#getTimePeriodFinish--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePeriodStart(DateTime value) {#setTimePeriodStart-com.aspose.diagram.DateTime-}
```
public void setTimePeriodStart(DateTime value)
```


For the description of this property, please see [getTimePeriodStart()](../../com.aspose.diagram/timelinehelper\#getTimePeriodStart--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeScale(int value) {#setTimeScale-int-}
```
public void setTimeScale(int value)
```


For the description of this property, please see [getTimeScale()](../../com.aspose.diagram/timelinehelper\#getTimeScale--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

