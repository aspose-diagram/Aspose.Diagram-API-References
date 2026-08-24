---
title: TimeLineHelper
second_title: Riferimento API di Aspose.Diagram per Java
description: TimeLineHelper per impostare la proprietà della forma della timeline.
type: docs
weight: 408
url: /it/java/com.aspose.diagram/timelinehelper/
---

**Inheritance:**
java.lang.Object
```
public class TimeLineHelper
```

TimeLineHelper per impostare la proprietà della forma della timeline.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TimeLineHelper(Shape shape)](#TimeLineHelper-com.aspose.diagram.Shape-) | TimeLineHelper. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDoubleStringFromDateTime(DateTime dateTime)](#getDoubleStringFromDateTime-com.aspose.diagram.DateTime-) | Converti la data e ora in valore double. |
| [getTimePeriodFinish()](#getTimePeriodFinish--) | Periodo di tempo per il termine della forma timeline |
| [getTimePeriodStart()](#getTimePeriodStart--) | Periodo di tempo per l'inizio della forma timeline |
| [getTimeScale()](#getTimeScale--) | scala della forma timeline |
| [getWeekEnd(DateTime startDate, int weekStart)](#getWeekEnd-com.aspose.diagram.DateTime-int-) | getweekstart |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshTimeLine()](#refreshTimeLine--) | Aggiorna il tempo delle forme timeline |
| [setArrowHead(int value)](#setArrowHead-int-) | Testa della freccia della forma timeline |
| [setAutoUpdate(boolean value)](#setAutoUpdate-boolean-) | se aggiornare i dati per i marcatori (milestones, intervals) mentre vengono spostati sulla timeline |
| [setBeginWeek(int value)](#setBeginWeek-int-) | Settimana di inizio della forma timeline |
|  | [setDateFormatForBE(int value)](#setDateFormatForBE-int-) | DateFormat per l'inizio e la fine della forma timeline /// |

| ----------------------- | ------------------------------- |
| **Value**\u9286\u20ac | **Format String**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
|  | [setDateFormatForIntm(int value)](#setDateFormatForIntm-int-) | DateFormat per Intm della forma timeline /// |

| ----------------------- | ------------------------------- |
| **Value**\u9286\u20ac | **Format String**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
| [setDateFormatStringForBE(String value)](#setDateFormatStringForBE-java.lang.String-) | Stringa DateFormat per l'inizio e la fine della forma timeline |
| [setDateFormatStringForIntm(String value)](#setDateFormatStringForIntm-java.lang.String-) | Stringa DateFormat per Intm della forma timeline |
| [setDisplayBE(boolean value)](#setDisplayBE-boolean-) | se visualizzare le date Begin e End sulla timeline |
| [setDisplayIntm(boolean value)](#setDisplayIntm-boolean-) | se visualizzare i tick interim di data/ora sulla timeline |
| [setDisplayIntmDates(boolean value)](#setDisplayIntmDates-boolean-) | se visualizzare le date interim sui tick interim |
| [setFiscalStart(DateTime value)](#setFiscalStart-com.aspose.diagram.DateTime-) | Primo giorno dell'anno fiscale |
| [setTimeLineType(int value)](#setTimeLineType-int-) | Settimana di inizio della forma timeline |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Converti la data e ora in valore double.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dateTime | [DateTime](../../com.aspose.diagram/datetime) | La data e ora. |

**Returns:**
java.lang.String -
### getTimePeriodFinish() {#getTimePeriodFinish--}
```
public DateTime getTimePeriodFinish()
```


Periodo di tempo per il termine della forma timeline

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimePeriodStart() {#getTimePeriodStart--}
```
public DateTime getTimePeriodStart()
```


Periodo di tempo per l'inizio della forma timeline

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeScale() {#getTimeScale--}
```
public int getTimeScale()
```


scala della forma timeline

**Returns:**
int
### getWeekEnd(DateTime startDate, int weekStart) {#getWeekEnd-com.aspose.diagram.DateTime-int-}
```
public static DateTime getWeekEnd(DateTime startDate, int weekStart)
```


getweekstart

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startDate | [DateTime](../../com.aspose.diagram/datetime) |  |
| weekStart | int | (0domenica 1lunedì 2 3 4 5 6) |

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


Aggiorna il tempo delle forme timeline

### setArrowHead(int value) {#setArrowHead-int-}
```
public void setArrowHead(int value)
```


Testa della freccia della forma timeline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setAutoUpdate(boolean value) {#setAutoUpdate-boolean-}
```
public void setAutoUpdate(boolean value)
```


se aggiornare i dati per i marcatori (milestones, intervals) mentre vengono spostati sulla timeline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setBeginWeek(int value) {#setBeginWeek-int-}
```
public void setBeginWeek(int value)
```


Settimana di inizio della forma timeline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDateFormatForBE(int value) {#setDateFormatForBE-int-}
```
public void setDateFormatForBE(int value)
```


DateFormat per l'inizio e la fine della forma timeline ///

| ----------------------- | ------------------------------- |
| **Value**\u9286\u20ac | **Format String**\u9286\u20ac |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDateFormatForIntm(int value) {#setDateFormatForIntm-int-}
```
public void setDateFormatForIntm(int value)
```


DateFormat per Intm della forma timeline ///

| ----------------------- | ------------------------------- |
| **Value**\u9286\u20ac | **Format String**\u9286\u20ac |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDateFormatStringForBE(String value) {#setDateFormatStringForBE-java.lang.String-}
```
public void setDateFormatStringForBE(String value)
```


Stringa DateFormat per l'inizio e la fine della forma timeline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDateFormatStringForIntm(String value) {#setDateFormatStringForIntm-java.lang.String-}
```
public void setDateFormatStringForIntm(String value)
```


Stringa DateFormat per Intm della forma timeline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDisplayBE(boolean value) {#setDisplayBE-boolean-}
```
public void setDisplayBE(boolean value)
```


se visualizzare le date Begin e End sulla timeline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setDisplayIntm(boolean value) {#setDisplayIntm-boolean-}
```
public void setDisplayIntm(boolean value)
```


se visualizzare i tick interim di data/ora sulla timeline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setDisplayIntmDates(boolean value) {#setDisplayIntmDates-boolean-}
```
public void setDisplayIntmDates(boolean value)
```


se visualizzare le date interim sui tick interim

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setFiscalStart(DateTime value) {#setFiscalStart-com.aspose.diagram.DateTime-}
```
public void setFiscalStart(DateTime value)
```


Primo giorno dell'anno fiscale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeLineType(int value) {#setTimeLineType-int-}
```
public void setTimeLineType(int value)
```


Settimana di inizio della forma timeline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTimePeriodFinish(DateTime value) {#setTimePeriodFinish-com.aspose.diagram.DateTime-}
```
public void setTimePeriodFinish(DateTime value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePeriodStart(DateTime value) {#setTimePeriodStart-com.aspose.diagram.DateTime-}
```
public void setTimePeriodStart(DateTime value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeScale(int value) {#setTimeScale-int-}
```
public void setTimeScale(int value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

