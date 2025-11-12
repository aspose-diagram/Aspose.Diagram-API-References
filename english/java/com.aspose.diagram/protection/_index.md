---
title: Protection
second_title: Aspose.Diagram for Java API Reference
description: Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances.
type: docs
weight: 319
url: /java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances. It also does not protect against changes made in the ShapeSheet window.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getLockAspect()](#getLockAspect--) | Specifies whether the aspect ratio of the shape is locked. |
| [getLockBegin()](#getLockBegin--) | Specifies whether the begin point of a 1-D shape is locked to a specific location. |
| [getLockCalcWH()](#getLockCalcWH--) | Specifies whether a shape's selection rectangle is locked so it cannot be recalculated when a vertex is edited or an element type is changed in the Geom element. |
| [getLockCrop()](#getLockCrop--) | Specifies whether a foreign object is locked against being cropped with the Crop tool in Microsoft Visio. |
| [getLockCustProp()](#getLockCustProp--) | Determines whether the user can add, delete, or modify custom properties in the user interface (UI) by using the Define Custom Properties dialog box. |
| [getLockDelete()](#getLockDelete--) | Specifies whether a shape is locked against being deleted. |
| [getLockEnd()](#getLockEnd--) | Specifies whether the end point of a 1-D shape is locked to a specific location. |
| [getLockFormat()](#getLockFormat--) | Specifies whether the formatting of a shape is locked so it cannot be changed. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Allows a subshape to block formatting changes that get applied to a parent group shape in the Visio user interface and would otherwise cascade down to individual group shapes. |
| [getLockGroup()](#getLockGroup--) | Specifies whether a group is locked so that it cannot be ungrouped. |
| [getLockHeight()](#getLockHeight--) | Specifies whether the height of the shape is locked. |
| [getLockMoveX()](#getLockMoveX--) | Specifies whether the horizontal position of the shape is locked so that it cannot be moved horizontally. |
| [getLockMoveY()](#getLockMoveY--) | Specifies whether the vertical position of the shape is locked so that it cannot be moved vertically. |
| [getLockRotate()](#getLockRotate--) | Specifies whether the shape is locked against being rotated with the Rotation tool or the Rotate Left or Rotate Right commands in Microsoft Visio. |
| [getLockSelect()](#getLockSelect--) | Specifies whether a shape's selection rectangle is locked so it cannot be recalculated when a vertex is edited or an element type is changed in the Geom element. |
| [getLockTextEdit()](#getLockTextEdit--) | Specifies whether the text of a shape is locked so that it cannot be edited. |
| [getLockThemeColors()](#getLockThemeColors--) | Prevents users from applying theme colors to the shape. |
| [getLockThemeEffects()](#getLockThemeEffects--) | Prevents users from applying theme effects to the shape. |
| [getLockVtxEdit()](#getLockVtxEdit--) | Specifies whether the vertices of a shape are locked so that they cannot be edited with any tools on the toolbar. |
| [getLockWidth()](#getLockWidth--) | Specifies whether the width of the shape is locked so that it remains unchanged when the shape is resized. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/protection\#getDel--) |
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
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


Specifies whether the aspect ratio of the shape is locked. If locked, the shape can only be sized proportionally; it cannot be sized in a single dimension.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


Specifies whether the begin point of a 1-D shape is locked to a specific location.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


Specifies whether a shape's selection rectangle is locked so it cannot be recalculated when a vertex is edited or an element type is changed in the Geom element.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Specifies whether a foreign object is locked against being cropped with the Crop tool in Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


Determines whether the user can add, delete, or modify custom properties in the user interface (UI) by using the Define Custom Properties dialog box.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


Specifies whether a shape is locked against being deleted.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


Specifies whether the end point of a 1-D shape is locked to a specific location.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


Specifies whether the formatting of a shape is locked so it cannot be changed. Specifically, this element protects against changing text, line, and fill formatting, or changing which Style element the shape inherits from.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Allows a subshape to block formatting changes that get applied to a parent group shape in the Visio user interface and would otherwise cascade down to individual group shapes.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


Specifies whether a group is locked so that it cannot be ungrouped.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


Specifies whether the height of the shape is locked. If locked, its height remains unchanged when the shape is resized.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


Specifies whether the horizontal position of the shape is locked so that it cannot be moved horizontally.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


Specifies whether the vertical position of the shape is locked so that it cannot be moved vertically.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Specifies whether the shape is locked against being rotated with the Rotation tool or the Rotate Left or Rotate Right commands in Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


Specifies whether a shape's selection rectangle is locked so it cannot be recalculated when a vertex is edited or an element type is changed in the Geom element.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


Specifies whether the text of a shape is locked so that it cannot be edited. However, the text may still be formatted by applying a style, using the Style options on the Font tab of the Text dialog box.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


Prevents users from applying theme colors to the shape.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


Prevents users from applying theme effects to the shape.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


Specifies whether the vertices of a shape are locked so that they cannot be edited with any tools on the toolbar.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


Specifies whether the width of the shape is locked so that it remains unchanged when the shape is resized.

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


For the description of this property, please see [getDel()](../../com.aspose.diagram/protection\#getDel--)

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

