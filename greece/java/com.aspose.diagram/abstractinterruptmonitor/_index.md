---
title: AbstractInterruptMonitor
second_title: Αναφορά API του Aspose.Diagram για Java
description: Παρακολούθηση αιτημάτων διακοπής σε όλες τις χρονοβόρες λειτουργίες.
type: docs
weight: 10
url: /el/java/com.aspose.diagram/abstractinterruptmonitor/
---

**Inheritance:**
java.lang.Object
```
public abstract class AbstractInterruptMonitor
```

Παρακολούθηση αιτημάτων διακοπής σε όλες τις χρονοβόρες λειτουργίες.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [AbstractInterruptMonitor()](#AbstractInterruptMonitor--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isInterruptionRequested()](#isInterruptionRequested--) | Δείχνει εάν έχει ζητηθεί διακοπή για την τρέχουσα λειτουργία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AbstractInterruptMonitor() {#AbstractInterruptMonitor--}
```
public AbstractInterruptMonitor()
```


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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Δείχνει εάν έχει ζητηθεί διακοπή για την τρέχουσα λειτουργία. Εάν είναι true, τότε η τρέχουσα λειτουργία θα διακοπεί.

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

