---
title: ConValue
second_title: Aspose.Diagram for Java API-Referenz
description: Gibt den Verhaltenstyp der x- oder y-Koordinate des Steuergriffs an, der nach dem Verschieben des Griffs auftritt.
type: docs
weight: 74
url: /de/java/com.aspose.diagram/convalue/
---

**Inheritance:**
java.lang.Object
```
public final class ConValue
```

Gibt den Verhaltenstyp der x- oder y-Koordinate des Steuergriffs an, der nach dem Verschieben des Griffs auftritt.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [OFFSET_FROM_CENTER](#OFFSET-FROM-CENTER) | Versatz vom Zentrum. |
| [OFFSET_FROM_CENTER_HIDDEN](#OFFSET-FROM-CENTER-HIDDEN) | Versatz vom Zentrum, verborgen. |
| [OFFSET_FROM_LEFT_EDGE](#OFFSET-FROM-LEFT-EDGE) | Versatz vom linken Rand. |
| [OFFSET_FROM_LEFT_EDGE_HIDDEN](#OFFSET-FROM-LEFT-EDGE-HIDDEN) | Versatz vom linken Rand, verborgen. |
| [OFFSET_FROM_RIGHT_EDGE](#OFFSET-FROM-RIGHT-EDGE) | Versatz vom rechten Rand. |
| [OFFSET_FROM_RIGHT_EDGE_HIDDEN](#OFFSET-FROM-RIGHT-EDGE-HIDDEN) | Versatz vom rechten Rand, ausgeblendet. |
| [PROPORTIONAL](#PROPORTIONAL) | Proportional. |
| [PROPORTIONAL_HIDDEN](#PROPORTIONAL-HIDDEN) | Proportional, ausgeblendet.Gleich wie 0, aber der Steuergriff ist nicht sichtbar. |
| [PROPORTIONAL_LOCKED](#PROPORTIONAL-LOCKED) | Proportional gesperrt. |
| [PROPORTIONAL_LOCKED_HIDDEN](#PROPORTIONAL-LOCKED-HIDDEN) | Proportional gesperrt, ausgeblendet. |
| [UNDEFINED](#UNDEFINED) | Undefiniert. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OFFSET_FROM_CENTER {#OFFSET-FROM-CENTER}
```
public static final int OFFSET_FROM_CENTER
```


Versatz vom Mittelpunkt. Der Steuergriff ist um einen konstanten Abstand vom Mittelpunkt der Form versetzt.

### OFFSET_FROM_CENTER_HIDDEN {#OFFSET-FROM-CENTER-HIDDEN}
```
public static final int OFFSET_FROM_CENTER_HIDDEN
```


Versatz vom Mittelpunkt, ausgeblendet. Gleich wie 3, aber der Steuergriff ist nicht sichtbar.

### OFFSET_FROM_LEFT_EDGE {#OFFSET-FROM-LEFT-EDGE}
```
public static final int OFFSET_FROM_LEFT_EDGE
```


Versatz vom linken Rand. Der Steuergriff ist um einen konstanten Abstand von der linken Seite der Form versetzt.

### OFFSET_FROM_LEFT_EDGE_HIDDEN {#OFFSET-FROM-LEFT-EDGE-HIDDEN}
```
public static final int OFFSET_FROM_LEFT_EDGE_HIDDEN
```


Versatz vom linken Rand, ausgeblendet. Gleich wie 2, aber der Steuergriff ist nicht sichtbar.

### OFFSET_FROM_RIGHT_EDGE {#OFFSET-FROM-RIGHT-EDGE}
```
public static final int OFFSET_FROM_RIGHT_EDGE
```


Versatz vom rechten Rand. Der Steuergriff ist um einen konstanten Abstand von der rechten Seite der Form versetzt.

### OFFSET_FROM_RIGHT_EDGE_HIDDEN {#OFFSET-FROM-RIGHT-EDGE-HIDDEN}
```
public static final int OFFSET_FROM_RIGHT_EDGE_HIDDEN
```


Versatz vom rechten Rand, ausgeblendet. Gleich wie 4, aber der Steuergriff ist nicht sichtbar.

### PROPORTIONAL {#PROPORTIONAL}
```
public static final int PROPORTIONAL
```


Proportional. Der Steuergriff kann bewegt werden und bewegt sich ebenfalls proportional zur Form, wenn diese gedehnt wird.

### PROPORTIONAL_HIDDEN {#PROPORTIONAL-HIDDEN}
```
public static final int PROPORTIONAL_HIDDEN
```


Proportional, ausgeblendet.Gleich wie 0, aber der Steuergriff ist nicht sichtbar.

### PROPORTIONAL_LOCKED {#PROPORTIONAL-LOCKED}
```
public static final int PROPORTIONAL_LOCKED
```


Proportional gesperrt. Der Steuergriff bewegt sich proportional zur Form, aber der Steuergriff selbst kann nicht bewegt werden.

### PROPORTIONAL_LOCKED_HIDDEN {#PROPORTIONAL-LOCKED-HIDDEN}
```
public static final int PROPORTIONAL_LOCKED_HIDDEN
```


Proportional gesperrt, ausgeblendet. Gleich wie 1, aber der Steuergriff ist nicht sichtbar.

### UNDEFINED {#UNDEFINED}
```
public static final int UNDEFINED
```


Undefiniert.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

