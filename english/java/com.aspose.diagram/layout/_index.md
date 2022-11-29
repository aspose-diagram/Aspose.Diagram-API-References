---
title: Layout
second_title: Aspose.Diagram for Java API Reference
description: Contains elements that control shape placement and connector routing settings.
type: docs
weight: 215
url: /java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

Contains elements that control shape placement and connector routing settings.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | Determines when a connector reroutes. |
| [getConLineJumpCode()](#getConLineJumpCode--) | Determines whether a connector jumps when two connectors cross, |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | Determines the line jump direction for line jumps occurring on a horizontal segment of a dynamic connector. |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | Determines the line jump direction for line jumps occurring on a vertical segment of a dynamic connector. |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | Determines the line jump style for line jumps on a dynamic connector. |
| [getConLineRouteExt()](#getConLineRouteExt--) | Determines the appearance of a connector. |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getDisplayLevel()](#getDisplayLevel--) | Determines the display level band (the relative range of Z-order grouping) for the shape. |
| [getRelationships()](#getRelationships--) | Stores the relationships between containers, lists, callouts, and shapes. |
| [getShapeFixedCode()](#getShapeFixedCode--) | Specifies placement behavior for a placeable shape. |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | Specifies whether placeable shapes can be placed on top of a shape when a user selects Lay Out Shapes (Shapes menu). |
| [getShapePermeableX()](#getShapePermeableX--) | Specifies whether a connector can route horizontally through a shape. |
| [getShapePermeableY()](#getShapePermeableY--) | Specifies whether a connector can route vertically through a shape. |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | Specifies how a placeable shape flips and/or rotates on the page when a user selects Lay Out Shapes (Shapes menu). |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | Determines the placement style for children. |
| [getShapePlowCode()](#getShapePlowCode--) | Specifies whether a placeable shape moves away when you drag another placeable shape near the shape on the drawing page. |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | Specifies the routing style and direction for a connector on the drawing page. |
| [getShapeSplit()](#getShapeSplit--) | Determines whether this shape can split shapes that are splittable. |
| [getShapeSplittable()](#getShapeSplittable--) | Determines whether this 1-D shape can be split. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | For the description of this property, please see [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


Determines when a connector reroutes.

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


Determines whether a connector jumps when two connectors cross,

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


Determines the line jump direction for line jumps occurring on a horizontal segment of a dynamic connector.

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


Determines the line jump direction for line jumps occurring on a vertical segment of a dynamic connector.

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


Determines the line jump style for line jumps on a dynamic connector.

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


Determines the appearance of a connector.

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


Determines the display level band (the relative range of Z-order grouping) for the shape.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


Stores the relationships between containers, lists, callouts, and shapes.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


Specifies placement behavior for a placeable shape.

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


Specifies whether placeable shapes can be placed on top of a shape when a user selects Lay Out Shapes (Shapes menu).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


Specifies whether a connector can route horizontally through a shape.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


Specifies whether a connector can route vertically through a shape.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


Specifies how a placeable shape flips and/or rotates on the page when a user selects Lay Out Shapes (Shapes menu).

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


Determines the placement style for children.

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


Specifies whether a placeable shape moves away when you drag another placeable shape near the shape on the drawing page.

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


Specifies the routing style and direction for a connector on the drawing page.

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


Determines whether this shape can split shapes that are splittable.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


Determines whether this 1-D shape can be split.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


For the description of this property, please see [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


For the description of this property, please see [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle) |  |

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

