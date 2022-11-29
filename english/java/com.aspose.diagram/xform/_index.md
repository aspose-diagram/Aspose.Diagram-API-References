---
title: XForm
second_title: Aspose.Diagram for Java API Reference
description: Contains elements that control line attributes for a shape such as pattern weight and color.
type: docs
weight: 449
url: /java/com.aspose.diagram/xform/
---

**Inheritance:**
java.lang.Object
```
public class XForm
```

Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine whether the line ends are formatted (for example, with an arrowhead), the size of line end formats, radius of the rounding circle applied to the line, and line cap style (round or square).
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates deep copy of this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Represents the shape's current angle of rotation in relation to its parent. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getFlipX()](#getFlipX--) | Indicates whether the shape has been flipped horizontally |
| [getFlipY()](#getFlipY--) | Indicates whether the shape has been flipped vertically. |
| [getHeight()](#getHeight--) | Specifies the height of the shape in drawing units. |
| [getLocPinX()](#getLocPinX--) | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the origin of the shape. |
| [getLocPinY()](#getLocPinY--) | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the origin of the shape. |
| [getPinPos()](#getPinPos--) | Specifies the pin position of the shape |
| [getPinX()](#getPinX--) | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent. |
| [getPinY()](#getPinY--) | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent. |
| [getResizeMode()](#getResizeMode--) | Specifies the current resize behavior setting for the shape when contained in a group. |
| [getWidth()](#getWidth--) | Contains the width of the associated shape in drawing units. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(DoubleValue value)](#setAngle-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getAngle()](../../com.aspose.diagram/xform\#getAngle--) |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/xform\#getDel--) |
| [setFlipX(BoolValue value)](#setFlipX-com.aspose.diagram.BoolValue-) | For the description of this property, please see [getFlipX()](../../com.aspose.diagram/xform\#getFlipX--) |
| [setFlipY(BoolValue value)](#setFlipY-com.aspose.diagram.BoolValue-) | For the description of this property, please see [getFlipY()](../../com.aspose.diagram/xform\#getFlipY--) |
| [setHeight(DoubleValue value)](#setHeight-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getHeight()](../../com.aspose.diagram/xform\#getHeight--) |
| [setLocPinX(DoubleValue value)](#setLocPinX-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--) |
| [setLocPinY(DoubleValue value)](#setLocPinY-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--) |
| [setPinPos(int value)](#setPinPos-int-) | For the description of this property, please see [getPinPos()](../../com.aspose.diagram/xform\#getPinPos--) |
| [setPinX(DoubleValue value)](#setPinX-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getPinX()](../../com.aspose.diagram/xform\#getPinX--) |
| [setPinY(DoubleValue value)](#setPinY-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getPinY()](../../com.aspose.diagram/xform\#getPinY--) |
| [setResizeMode(ResizeMode value)](#setResizeMode-com.aspose.diagram.ResizeMode-) | For the description of this property, please see [getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--) |
| [setWidth(DoubleValue value)](#setWidth-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getWidth()](../../com.aspose.diagram/xform\#getWidth--) |
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
### getAngle() {#getAngle--}
```
public DoubleValue getAngle()
```


Represents the shape's current angle of rotation in relation to its parent.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getFlipX() {#getFlipX--}
```
public BoolValue getFlipX()
```


Indicates whether the shape has been flipped horizontally

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlipY() {#getFlipY--}
```
public BoolValue getFlipY()
```


Indicates whether the shape has been flipped vertically.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHeight() {#getHeight--}
```
public DoubleValue getHeight()
```


Specifies the height of the shape in drawing units.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinX() {#getLocPinX--}
```
public DoubleValue getLocPinX()
```


Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the origin of the shape. The default formula for determining LocPinX is: F='Width\* 0.5'.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinY() {#getLocPinY--}
```
public DoubleValue getLocPinY()
```


Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the origin of the shape. The default formula for determining LocPinY is: F='Height \* 0.5'.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinPos() {#getPinPos--}
```
public int getPinPos()
```


Specifies the pin position of the shape

**Returns:**
int
### getPinX() {#getPinX--}
```
public DoubleValue getPinX()
```


Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinY() {#getPinY--}
```
public DoubleValue getPinY()
```


Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getResizeMode() {#getResizeMode--}
```
public ResizeMode getResizeMode()
```


Specifies the current resize behavior setting for the shape when contained in a group.

**Returns:**
[ResizeMode](../../com.aspose.diagram/resizemode)
### getWidth() {#getWidth--}
```
public DoubleValue getWidth()
```


Contains the width of the associated shape in drawing units.

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




### setAngle(DoubleValue value) {#setAngle-com.aspose.diagram.DoubleValue-}
```
public void setAngle(DoubleValue value)
```


For the description of this property, please see [getAngle()](../../com.aspose.diagram/xform\#getAngle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


For the description of this property, please see [getDel()](../../com.aspose.diagram/xform\#getDel--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFlipX(BoolValue value) {#setFlipX-com.aspose.diagram.BoolValue-}
```
public void setFlipX(BoolValue value)
```


For the description of this property, please see [getFlipX()](../../com.aspose.diagram/xform\#getFlipX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFlipY(BoolValue value) {#setFlipY-com.aspose.diagram.BoolValue-}
```
public void setFlipY(BoolValue value)
```


For the description of this property, please see [getFlipY()](../../com.aspose.diagram/xform\#getFlipY--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHeight(DoubleValue value) {#setHeight-com.aspose.diagram.DoubleValue-}
```
public void setHeight(DoubleValue value)
```


For the description of this property, please see [getHeight()](../../com.aspose.diagram/xform\#getHeight--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinX(DoubleValue value) {#setLocPinX-com.aspose.diagram.DoubleValue-}
```
public void setLocPinX(DoubleValue value)
```


For the description of this property, please see [getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinY(DoubleValue value) {#setLocPinY-com.aspose.diagram.DoubleValue-}
```
public void setLocPinY(DoubleValue value)
```


For the description of this property, please see [getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinPos(int value) {#setPinPos-int-}
```
public void setPinPos(int value)
```


For the description of this property, please see [getPinPos()](../../com.aspose.diagram/xform\#getPinPos--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPinX(DoubleValue value) {#setPinX-com.aspose.diagram.DoubleValue-}
```
public void setPinX(DoubleValue value)
```


For the description of this property, please see [getPinX()](../../com.aspose.diagram/xform\#getPinX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinY(DoubleValue value) {#setPinY-com.aspose.diagram.DoubleValue-}
```
public void setPinY(DoubleValue value)
```


For the description of this property, please see [getPinY()](../../com.aspose.diagram/xform\#getPinY--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setResizeMode(ResizeMode value) {#setResizeMode-com.aspose.diagram.ResizeMode-}
```
public void setResizeMode(ResizeMode value)
```


For the description of this property, please see [getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ResizeMode](../../com.aspose.diagram/resizemode) |  |

### setWidth(DoubleValue value) {#setWidth-com.aspose.diagram.DoubleValue-}
```
public void setWidth(DoubleValue value)
```


For the description of this property, please see [getWidth()](../../com.aspose.diagram/xform\#getWidth--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

