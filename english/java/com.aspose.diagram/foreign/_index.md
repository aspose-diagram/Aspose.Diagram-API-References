---
title: Foreign
second_title: Aspose.Diagram for Java API Reference
description: Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document.
type: docs
weight: 167
url: /java/com.aspose.diagram/foreign/
---

**Inheritance:**
java.lang.Object
```
public class Foreign
```

Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders.
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates deep copy of this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getImgHeight()](#getImgHeight--) | Determines the height of the object's image within its border. |
| [getImgOffsetX()](#getImgOffsetX--) | Determines the distance the object is offset horizontally from the origin of the object's border. |
| [getImgOffsetY()](#getImgOffsetY--) | Determines the distance the object is offset vertically from the origin of the object's border. |
| [getImgWidth()](#getImgWidth--) | Determines the width of the object's image within its border. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/foreign\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getImgHeight() {#getImgHeight--}
```
public DoubleValue getImgHeight()
```


Determines the height of the object's image within its border. The default formula is: F="Height\*1".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetX() {#getImgOffsetX--}
```
public DoubleValue getImgOffsetX()
```


Determines the distance the object is offset horizontally from the origin of the object's border. The default value is 0; the default formula is F="ImgWidth\*0".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetY() {#getImgOffsetY--}
```
public DoubleValue getImgOffsetY()
```


Determines the distance the object is offset vertically from the origin of the object's border. The default value is 0; the default formula is F="ImgHeight\*0".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgWidth() {#getImgWidth--}
```
public DoubleValue getImgWidth()
```


Determines the width of the object's image within its border. The default formula is: F="Width\*1".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
public void setDel(int value)
```


For the description of this property, please see [getDel()](../../com.aspose.diagram/foreign\#getDel--)

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

