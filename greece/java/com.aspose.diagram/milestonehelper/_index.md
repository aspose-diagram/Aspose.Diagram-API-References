---
title: MilestoneHelper
second_title: Αναφορά API του Aspose.Diagram για Java
description: MilestoneHelper για ορισμό ιδιότητας του σχήματος ορόσημου.
type: docs
weight: 246
url: /el/java/com.aspose.diagram/milestonehelper/
---

**Inheritance:**
java.lang.Object
```
public class MilestoneHelper
```

MilestoneHelper για ορισμό ιδιότητας του σχήματος ορόσημου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MilestoneHelper(Shape shape)](#MilestoneHelper-com.aspose.diagram.Shape-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMilestoneDate()](#getMilestoneDate--) | Ημερομηνία ορόσημου |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshMilestone(Shape timeline)](#refreshMilestone-com.aspose.diagram.Shape-) | Ανανέωση ορόσημου |
| [setAutoUpdate(boolean value)](#setAutoUpdate-boolean-) | αν ενημερώνονται τα δεδομένα για τους δείκτες (ορόσημα, διαστήματα) καθώς μετακινούνται στη χρονογραμμή |
|  | [setDateFormat(int value)](#setDateFormat-int-) | DateFormat του σχήματος /// |

| ----------------------- | ------------------------------- |
| **Τιμή**\u9286\u20ac | **Μορφή Συμβολοσειράς**\u9286\u20ac |
| 0                       | dddd, yyyy-M-d                  |
| 1                       | yyyy-MM-dd                      |
| 2                       | yy-MMM-d                        |
| 3                       | yyyy/M/d                        |
| 4                       | yy-MMM.                         | |
| [setDateFormatString(String value)](#setDateFormatString-java.lang.String-) | DateFormat string του σχήματος |
| [setMilestoneDate(DateTime value)](#setMilestoneDate-com.aspose.diagram.DateTime-) |  |
| [setType(int value)](#setType-int-) | Τύπος του σχήματος |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MilestoneHelper(Shape shape) {#MilestoneHelper-com.aspose.diagram.Shape-}
```
public MilestoneHelper(Shape shape)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
### getMilestoneDate() {#getMilestoneDate--}
```
public DateTime getMilestoneDate()
```


Ημερομηνία ορόσημου

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
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




### refreshMilestone(Shape timeline) {#refreshMilestone-com.aspose.diagram.Shape-}
```
public void refreshMilestone(Shape timeline)
```


Ανανέωση ορόσημου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| timeline | [Shape](../../com.aspose.diagram/shape) |  |

### setAutoUpdate(boolean value) {#setAutoUpdate-boolean-}
```
public void setAutoUpdate(boolean value)
```


αν ενημερώνονται τα δεδομένα για τους δείκτες (ορόσημα, διαστήματα) καθώς μετακινούνται στη χρονογραμμή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setDateFormat(int value) {#setDateFormat-int-}
```
public void setDateFormat(int value)
```


DateFormat του σχήματος ///

| ----------------------- | ------------------------------- |
| **Τιμή**\u9286\u20ac | **Μορφή Συμβολοσειράς**\u9286\u20ac |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDateFormatString(String value) {#setDateFormatString-java.lang.String-}
```
public void setDateFormatString(String value)
```


DateFormat string του σχήματος

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setMilestoneDate(DateTime value) {#setMilestoneDate-com.aspose.diagram.DateTime-}
```
public void setMilestoneDate(DateTime value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Τύπος του σχήματος

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

