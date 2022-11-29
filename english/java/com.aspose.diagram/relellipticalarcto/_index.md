---
title: RelEllipticalArcTo
second_title: Aspose.Diagram for Java API Reference
description: Contains elements that specify information about an elliptical arc.Coordinates are specified as relative coordinates.
type: docs
weight: 318
url: /java/com.aspose.diagram/relellipticalarcto/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class RelEllipticalArcTo extends Coordinate
```

Contains elements that specify information about an elliptical arc.Coordinates are specified as relative coordinates.
## Constructors

| Constructor | Description |
| --- | --- |
| [RelEllipticalArcTo()](#RelEllipticalArcTo--) | Creates an instance of the [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates deep copy of this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | The x-coordinate of the arc's control point. |
| [getB()](#getB--) | The y-coordinate of an arc's control point. |
| [getC()](#getC--) | The angle of an arc's major axis relative to the x-axis of its parent. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | The ratio of an arc's major axis to its minor axis. |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getIX()](#getIX--) | The zero-based index of the element within its parent element. |
| [getX()](#getX--) | The x-coordinate of the ending vertex of an elliptical arc. |
| [getY()](#getY--) | The y-coordinate of the ending vertex of an elliptical arc. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--) |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--) |
| [setIX(int value)](#setIX-int-) | For the description of this property, please see [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | For the description of this property, please see [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelEllipticalArcTo() {#RelEllipticalArcTo--}
```
public RelEllipticalArcTo()
```


Creates an instance of the [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) class.

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
### getA() {#getA--}
```
public DoubleValue getA()
```


The x-coordinate of the arc's control point. The control point is best located about halfway between the beginning and ending vertices of the arc. Otherwise, the arc may grow to an extreme size in order to pass through the control point, with unpredictable results.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


The y-coordinate of an arc's control point.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


The angle of an arc's major axis relative to the x-axis of its parent.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


The ratio of an arc's major axis to its minor axis. Despite the usual meaning of these words, the major axis does not have to be greater than the minor axis, so this ratio does not have to be greater than 1. Setting this element to a value less than or equal to 0 or greater than 1000 can lead to unpredictable results.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


The zero-based index of the element within its parent element.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


The x-coordinate of the ending vertex of an elliptical arc.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


The y-coordinate of the ending vertex of an elliptical arc.

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


For the description of this property, please see [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


For the description of this property, please see [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


For the description of this property, please see [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


For the description of this property, please see [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


For the description of this property, please see [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


For the description of this property, please see [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


For the description of this property, please see [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


For the description of this property, please see [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--)

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

