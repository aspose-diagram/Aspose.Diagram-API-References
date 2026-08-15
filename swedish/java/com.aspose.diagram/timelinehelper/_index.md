---
title: TimeLineHelper
second_title: Aspose.Diagram för Java API-referens
description: TimeLineHelper för att sätta egenskap på tidslinjefigur.
type: docs
weight: 408
url: /sv/java/com.aspose.diagram/timelinehelper/
---

**Inheritance:**
java.lang.Object
```
public class TimeLineHelper
```

TimeLineHelper för att sätta egenskap på tidslinjefigur.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TimeLineHelper(Shape shape)](#TimeLineHelper-com.aspose.diagram.Shape-) | TimeLineHelper. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDoubleStringFromDateTime(DateTime dateTime)](#getDoubleStringFromDateTime-com.aspose.diagram.DateTime-) | Konvertera datumtiden till ett dubbelvärde. |
| [getTimePeriodFinish()](#getTimePeriodFinish--) | Tidsperiod för slutet av tidslinjeformen |
| [getTimePeriodStart()](#getTimePeriodStart--) | Tidsperiod för start av tidslinjeformen |
| [getTimeScale()](#getTimeScale--) | Skala för tidslinjeformen |
| [getWeekEnd(DateTime startDate, int weekStart)](#getWeekEnd-com.aspose.diagram.DateTime-int-) | getweekstart |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshTimeLine()](#refreshTimeLine--) | Uppdatera tiden för tidslinjeformer |
| [setArrowHead(int value)](#setArrowHead-int-) | Pilspets för tidslinjeformen |
| [setAutoUpdate(boolean value)](#setAutoUpdate-boolean-) | om data för markörer (milstenar, intervaller) ska uppdateras när de flyttas på tidslinjen |
| [setBeginWeek(int value)](#setBeginWeek-int-) | Startvecka för tidslinjeformen |
|  | [setDateFormatForBE(int value)](#setDateFormatForBE-int-) | Datumformat för start och slut av tidslinjeformen /// |

| ----------------------- | ------------------------------- |
| **Värde**\u9286\u20ac | **Formatsträng**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
|  | [setDateFormatForIntm(int value)](#setDateFormatForIntm-int-) | Datumformat för mellanliggande tid för tidslinjeformen /// |

| ----------------------- | ------------------------------- |
| **Värde**\u9286\u20ac | **Formatsträng**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
| [setDateFormatStringForBE(String value)](#setDateFormatStringForBE-java.lang.String-) | Datumformatsträng för start och slut av tidslinjeformen |
| [setDateFormatStringForIntm(String value)](#setDateFormatStringForIntm-java.lang.String-) | Datumformatsträng för mellanliggande tid för tidslinjeformen |
| [setDisplayBE(boolean value)](#setDisplayBE-boolean-) | om start- och slutdatum ska visas på tidslinjen |
| [setDisplayIntm(boolean value)](#setDisplayIntm-boolean-) | om interim datum/tid-markeringar ska visas på tidslinjen |
| [setDisplayIntmDates(boolean value)](#setDisplayIntmDates-boolean-) | om interimdatum ska visas på interimmarkeringar |
| [setFiscalStart(DateTime value)](#setFiscalStart-com.aspose.diagram.DateTime-) | Första dagen i räkenskapsåret |
| [setTimeLineType(int value)](#setTimeLineType-int-) | Startvecka för tidslinjeformen |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Konvertera datumtiden till ett dubbelvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dateTime | [DateTime](../../com.aspose.diagram/datetime) | Datum och tid. |

**Returns:**
java.lang.String -
### getTimePeriodFinish() {#getTimePeriodFinish--}
```
public DateTime getTimePeriodFinish()
```


Tidsperiod för slutet av tidslinjeformen

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimePeriodStart() {#getTimePeriodStart--}
```
public DateTime getTimePeriodStart()
```


Tidsperiod för start av tidslinjeformen

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeScale() {#getTimeScale--}
```
public int getTimeScale()
```


Skala för tidslinjeformen

**Returns:**
int
### getWeekEnd(DateTime startDate, int weekStart) {#getWeekEnd-com.aspose.diagram.DateTime-int-}
```
public static DateTime getWeekEnd(DateTime startDate, int weekStart)
```


getweekstart

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startDate | [DateTime](../../com.aspose.diagram/datetime) |  |
| veckostart | int | (0söndag 1måndag 2 3 4 5 6) |

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


Uppdatera tiden för tidslinjeformer

### setArrowHead(int value) {#setArrowHead-int-}
```
public void setArrowHead(int value)
```


Pilspets för tidslinjeformen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setAutoUpdate(boolean value) {#setAutoUpdate-boolean-}
```
public void setAutoUpdate(boolean value)
```


om data för markörer (milstenar, intervaller) ska uppdateras när de flyttas på tidslinjen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setBeginWeek(int value) {#setBeginWeek-int-}
```
public void setBeginWeek(int value)
```


Startvecka för tidslinjeformen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDateFormatForBE(int value) {#setDateFormatForBE-int-}
```
public void setDateFormatForBE(int value)
```


Datumformat för start och slut av tidslinjeformen ///

| ----------------------- | ------------------------------- |
| **Värde**\u9286\u20ac | **Formatsträng**\u9286\u20ac |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDateFormatForIntm(int value) {#setDateFormatForIntm-int-}
```
public void setDateFormatForIntm(int value)
```


Datumformat för mellanliggande tid för tidslinjeformen ///

| ----------------------- | ------------------------------- |
| **Värde**\u9286\u20ac | **Formatsträng**\u9286\u20ac |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDateFormatStringForBE(String value) {#setDateFormatStringForBE-java.lang.String-}
```
public void setDateFormatStringForBE(String value)
```


Datumformatsträng för start och slut av tidslinjeformen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDateFormatStringForIntm(String value) {#setDateFormatStringForIntm-java.lang.String-}
```
public void setDateFormatStringForIntm(String value)
```


Datumformatsträng för mellanliggande tid för tidslinjeformen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDisplayBE(boolean value) {#setDisplayBE-boolean-}
```
public void setDisplayBE(boolean value)
```


om start- och slutdatum ska visas på tidslinjen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setDisplayIntm(boolean value) {#setDisplayIntm-boolean-}
```
public void setDisplayIntm(boolean value)
```


om interim datum/tid-markeringar ska visas på tidslinjen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setDisplayIntmDates(boolean value) {#setDisplayIntmDates-boolean-}
```
public void setDisplayIntmDates(boolean value)
```


om interimdatum ska visas på interimmarkeringar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setFiscalStart(DateTime value) {#setFiscalStart-com.aspose.diagram.DateTime-}
```
public void setFiscalStart(DateTime value)
```


Första dagen i räkenskapsåret

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeLineType(int value) {#setTimeLineType-int-}
```
public void setTimeLineType(int value)
```


Startvecka för tidslinjeformen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTimePeriodFinish(DateTime value) {#setTimePeriodFinish-com.aspose.diagram.DateTime-}
```
public void setTimePeriodFinish(DateTime value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePeriodStart(DateTime value) {#setTimePeriodStart-com.aspose.diagram.DateTime-}
```
public void setTimePeriodStart(DateTime value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeScale(int value) {#setTimeScale-int-}
```
public void setTimeScale(int value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

