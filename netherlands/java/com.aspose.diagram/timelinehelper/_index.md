---
title: TimeLineHelper
second_title: Aspose.Diagram voor Java API-referentie
description: TimeLineHelper om de eigenschap van een tijdlijnvorm in te stellen.
type: docs
weight: 408
url: /nl/java/com.aspose.diagram/timelinehelper/
---

**Inheritance:**
java.lang.Object
```
public class TimeLineHelper
```

TimeLineHelper om de eigenschap van een tijdlijnvorm in te stellen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TimeLineHelper(Shape shape)](#TimeLineHelper-com.aspose.diagram.Shape-) | TimeLineHelper. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDoubleStringFromDateTime(DateTime dateTime)](#getDoubleStringFromDateTime-com.aspose.diagram.DateTime-) | Converteer de datum en tijd naar een double-waarde. |
| [getTimePeriodFinish()](#getTimePeriodFinish--) | Tijdperiode voor het einde van de tijdlijnvorm |
| [getTimePeriodStart()](#getTimePeriodStart--) | Tijdperiode voor het begin van de tijdlijnvorm |
| [getTimeScale()](#getTimeScale--) | schaal van de tijdlijnvorm |
| [getWeekEnd(DateTime startDate, int weekStart)](#getWeekEnd-com.aspose.diagram.DateTime-int-) | getweekstart |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshTimeLine()](#refreshTimeLine--) | Ververs tijd van tijdlijnvormen |
| [setArrowHead(int value)](#setArrowHead-int-) | Pijlpunt van tijdlijnvorm |
| [setAutoUpdate(boolean value)](#setAutoUpdate-boolean-) | of de gegevens voor markeringen (mijlpalen, intervallen) moeten worden bijgewerkt terwijl ze op de tijdlijn worden verplaatst |
| [setBeginWeek(int value)](#setBeginWeek-int-) | Beginweek van tijdlijnvorm |
|  | [setDateFormatForBE(int value)](#setDateFormatForBE-int-) | Datumnotatie voor begin en einde van tijdlijnvorm /// |

| ----------------------- | ------------------------------- |
| **Waarde**\u9286\u20ac | **Opmaakreeks**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
|  | [setDateFormatForIntm(int value)](#setDateFormatForIntm-int-) | Datumnotatie voor tussentijd van tijdlijnvorm /// |

| ----------------------- | ------------------------------- |
| **Waarde**\u9286\u20ac | **Opmaakreeks**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
| [setDateFormatStringForBE(String value)](#setDateFormatStringForBE-java.lang.String-) | Datumnotatie-reeks voor begin en einde van tijdlijnvorm |
| [setDateFormatStringForIntm(String value)](#setDateFormatStringForIntm-java.lang.String-) | Datumnotatie-reeks voor tussentijd van tijdlijnvorm |
| [setDisplayBE(boolean value)](#setDisplayBE-boolean-) | of Begin- en Einddatums op de tijdlijn moeten worden weergegeven |
| [setDisplayIntm(boolean value)](#setDisplayIntm-boolean-) | of tussentijdse datum/tijd-markeringen op de tijdlijn moeten worden weergegeven |
| [setDisplayIntmDates(boolean value)](#setDisplayIntmDates-boolean-) | of tussentijdse datums op tussentijdse markeringen moeten worden weergegeven |
| [setFiscalStart(DateTime value)](#setFiscalStart-com.aspose.diagram.DateTime-) | Eerste dag van het fiscale jaar |
| [setTimeLineType(int value)](#setTimeLineType-int-) | Beginweek van tijdlijnvorm |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Converteer de datum en tijd naar een double-waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dateTime | [DateTime](../../com.aspose.diagram/datetime) | De datumtijd. |

**Returns:**
java.lang.String -
### getTimePeriodFinish() {#getTimePeriodFinish--}
```
public DateTime getTimePeriodFinish()
```


Tijdperiode voor het einde van de tijdlijnvorm

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimePeriodStart() {#getTimePeriodStart--}
```
public DateTime getTimePeriodStart()
```


Tijdperiode voor het begin van de tijdlijnvorm

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeScale() {#getTimeScale--}
```
public int getTimeScale()
```


schaal van de tijdlijnvorm

**Returns:**
int
### getWeekEnd(DateTime startDate, int weekStart) {#getWeekEnd-com.aspose.diagram.DateTime-int-}
```
public static DateTime getWeekEnd(DateTime startDate, int weekStart)
```


getweekstart

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startDate | [DateTime](../../com.aspose.diagram/datetime) |  |
| weekStart | int | (0zondag 1maandag 2 3 4 5 6) |

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


Ververs tijd van tijdlijnvormen

### setArrowHead(int value) {#setArrowHead-int-}
```
public void setArrowHead(int value)
```


Pijlpunt van tijdlijnvorm

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setAutoUpdate(boolean value) {#setAutoUpdate-boolean-}
```
public void setAutoUpdate(boolean value)
```


of de gegevens voor markeringen (mijlpalen, intervallen) moeten worden bijgewerkt terwijl ze op de tijdlijn worden verplaatst

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setBeginWeek(int value) {#setBeginWeek-int-}
```
public void setBeginWeek(int value)
```


Beginweek van tijdlijnvorm

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setDateFormatForBE(int value) {#setDateFormatForBE-int-}
```
public void setDateFormatForBE(int value)
```


Datumnotatie voor begin en einde van tijdlijnvorm ///

| ----------------------- | ------------------------------- |
| **Waarde**\u9286\u20ac | **Opmaakreeks**\u9286\u20ac |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setDateFormatForIntm(int value) {#setDateFormatForIntm-int-}
```
public void setDateFormatForIntm(int value)
```


Datumnotatie voor tussentijd van tijdlijnvorm ///

| ----------------------- | ------------------------------- |
| **Waarde**\u9286\u20ac | **Opmaakreeks**\u9286\u20ac |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setDateFormatStringForBE(String value) {#setDateFormatStringForBE-java.lang.String-}
```
public void setDateFormatStringForBE(String value)
```


Datumnotatie-reeks voor begin en einde van tijdlijnvorm

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setDateFormatStringForIntm(String value) {#setDateFormatStringForIntm-java.lang.String-}
```
public void setDateFormatStringForIntm(String value)
```


Datumnotatie-reeks voor tussentijd van tijdlijnvorm

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setDisplayBE(boolean value) {#setDisplayBE-boolean-}
```
public void setDisplayBE(boolean value)
```


of Begin- en Einddatums op de tijdlijn moeten worden weergegeven

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setDisplayIntm(boolean value) {#setDisplayIntm-boolean-}
```
public void setDisplayIntm(boolean value)
```


of tussentijdse datum/tijd-markeringen op de tijdlijn moeten worden weergegeven

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setDisplayIntmDates(boolean value) {#setDisplayIntmDates-boolean-}
```
public void setDisplayIntmDates(boolean value)
```


of tussentijdse datums op tussentijdse markeringen moeten worden weergegeven

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setFiscalStart(DateTime value) {#setFiscalStart-com.aspose.diagram.DateTime-}
```
public void setFiscalStart(DateTime value)
```


Eerste dag van het fiscale jaar

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeLineType(int value) {#setTimeLineType-int-}
```
public void setTimeLineType(int value)
```


Beginweek van tijdlijnvorm

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTimePeriodFinish(DateTime value) {#setTimePeriodFinish-com.aspose.diagram.DateTime-}
```
public void setTimePeriodFinish(DateTime value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePeriodStart(DateTime value) {#setTimePeriodStart-com.aspose.diagram.DateTime-}
```
public void setTimePeriodStart(DateTime value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeScale(int value) {#setTimeScale-int-}
```
public void setTimeScale(int value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

