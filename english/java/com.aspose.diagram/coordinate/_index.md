---
title: Coordinate
second_title: Aspose.Diagram for Java API Reference
description: Abstract class for the x- and y-coordinates.
type: docs
weight: 101
url: /java/com.aspose.diagram/coordinate/
---

**Inheritance:**
java.lang.Object
```
public abstract class Coordinate
```

Abstract class for the x- and y-coordinates.
## Constructors

| Constructor | Description |
| --- | --- |
| [Coordinate()](#Coordinate--) |  |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates deep copy of this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getIX()](#getIX--) | The zero-based index of the element within its parent element. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see @PREF1\_ |
| [setIX(int value)](#setIX-int-) | For the description of this property, please see @PREF0\_ |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Coordinate() {#Coordinate--}
```
public Coordinate()
```


### deepClone() {#deepClone--}
```
public Object deepClone()
```


Creates deep copy of this instance.

**Returns:**
java.lang.Object - 
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public abstract int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getIX() {#getIX--}
```
public abstract int getIX()
```


The zero-based index of the element within its parent element.

**Returns:**
int
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




### setDel(int value) {#setDel-int-}
```
public abstract void setDel(int value)
```


For the description of this property, please see @PREF1\_

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setIX(int value) {#setIX-int-}
```
public abstract void setIX(int value)
```


For the description of this property, please see @PREF0\_

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

