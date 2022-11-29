---
title: Layer
second_title: Aspose.Diagram for Java API Reference
description: Contains elements that define a single layer and its properties for a page.
type: docs
weight: 212
url: /java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

Contains elements that define a single layer and its properties for a page.
## Constructors

| Constructor | Description |
| --- | --- |
| [Layer()](#Layer--) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | Specifies whether a layer is active. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | The index of the color in the color table used toThe index of the color in the color table used to display the layer or An RGB value specifying a custom color not in the color table (for example, \#ff9900 ). display the layer |
| [getColorTrans()](#getColorTrans--) | Determines the degree of transparency for a layer or shape's text color, from 0 (completely opaque) to 1 (completely transparent). |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getGlue()](#getGlue--) | Specifies whether shapes belonging to the layer can be glued to. |
| [getIX()](#getIX--) | The zero-based index of the element within its parent element. |
| [getLock()](#getLock--) | Specifies whether shapes belonging to the layer are locked against being selected or edited. |
| [getName()](#getName--) | Name element specifies the name of a layer. |
| [getNameUniv()](#getNameUniv--) | Specifies the universal name of a layer. |
| [getPrint()](#getPrint--) | Specifies whether shapes belonging to the layer are printed when the drawing is printed. |
| [getSnap()](#getSnap--) | Specifies whether other shapes can snap to shapes assigned to the layer. |
| [getStatus()](#getStatus--) | Specifies whether the layer is a valid layer for a document. |
| [getVisible()](#getVisible--) | Specifies whether shapes belonging to the layer are visible on the drawing page. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | A flag indicating whether the element has been checked locally. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | For the description of this property, please see [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | For the description of this property, please see [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
```


Constructor.

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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


Specifies whether a layer is active. Shapes that are not preassigned to layers are assigned to the active layer(s) when dropped on the drawing page.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


The index of the color in the color table used toThe index of the color in the color table used to display the layer or An RGB value specifying a custom color not in the color table (for example, \#ff9900 ). display the layer

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Determines the degree of transparency for a layer or shape's text color, from 0 (completely opaque) to 1 (completely transparent).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


Specifies whether shapes belonging to the layer can be glued to.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


The zero-based index of the element within its parent element.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


Specifies whether shapes belonging to the layer are locked against being selected or edited.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


Name element specifies the name of a layer.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


Specifies the universal name of a layer.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


Specifies whether shapes belonging to the layer are printed when the drawing is printed.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


Specifies whether other shapes can snap to shapes assigned to the layer. Shapes assigned to the layer can snap to other shapes, but other shapes cannot snap to them.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


Specifies whether the layer is a valid layer for a document.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


Specifies whether shapes belonging to the layer are visible on the drawing page.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


A flag indicating whether the element has been checked locally. A value of 1 indicates that the element was checked locally.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


For the description of this property, please see [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


For the description of this property, please see [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


For the description of this property, please see [getIX()](../../com.aspose.diagram/layer\#getIX--)

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

