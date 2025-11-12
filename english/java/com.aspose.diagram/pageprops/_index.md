---
title: PageProps
second_title: Aspose.Diagram for Java API Reference
description: Contains cells that control page attributes such as the page width height and scale.
type: docs
weight: 275
url: /java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

Contains cells that control page attributes, such as the page width, height, and scale.
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Creates deep copy of this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getDrawingResizeType()](#getDrawingResizeType--) | Determines whether the drawing page resizes automatically to fit the diagram. |
| [getDrawingScale()](#getDrawingScale--) | Represents the value of the drawing unit in the current drawing scale. |
| [getDrawingScaleType()](#getDrawingScaleType--) | Specifies the type of drawing scale to use for a page. |
| [getDrawingSizeType()](#getDrawingSizeType--) | Specifies the drawing size of a page. |
| [getInhibitSnap()](#getInhibitSnap--) | Specifies whether the shapes on a foreground page snap to other objects on the page and shapes on the background page. |
| [getPageHeight()](#getPageHeight--) | Specifies the height of the page in drawing units. |
| [getPageScale()](#getPageScale--) | Specifies the value of the default page unit in the current drawing scale. |
| [getPageWidth()](#getPageWidth--) | Specifies the width of the page in drawing units. |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | Contains a number that specifies the angle of oblique direction when the default page shadow type is applied. |
| [getShdwOffsetX()](#getShdwOffsetX--) | Specifies the distance in page units that a shape's drop shadow is offset horizontally from the shape. |
| [getShdwOffsetY()](#getShdwOffsetY--) | Specifies the distance in page units that a shape's drop shadow is offset vertically from the shape. |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | Specifies the percentage to enlarge or reduce a shape's shadow. |
| [getShdwType()](#getShdwType--) | Indicates the default shadow type for a page. |
| [getUIVisibility()](#getUIVisibility--) | Determines whether the page name is exposed in the user interface (UI). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/pageprops\#getDel--) |
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
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


Determines whether the drawing page resizes automatically to fit the diagram.

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


Represents the value of the drawing unit in the current drawing scale. The drawing scale for the page is the ratio of the page unit contained in the PageScale element to the drawing unit. The units of this element determine default length (DL) units for the page.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


Specifies the type of drawing scale to use for a page.

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


Specifies the drawing size of a page.

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


Specifies whether the shapes on a foreground page snap to other objects on the page and shapes on the background page.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


Specifies the height of the page in drawing units.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


Specifies the value of the default page unit in the current drawing scale. The drawing scale for the page is the ratio of the page unit in the PageScale element to the drawing unit shown in the DrawingScale element.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


Specifies the width of the page in drawing units.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


Contains a number that specifies the angle of oblique direction when the default page shadow type is applied.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


Specifies the distance in page units that a shape's drop shadow is offset horizontally from the shape.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


Specifies the distance in page units that a shape's drop shadow is offset vertically from the shape.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


Specifies the percentage to enlarge or reduce a shape's shadow.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


Indicates the default shadow type for a page.

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


Determines whether the page name is exposed in the user interface (UI). A value of one specifies that the page is not visible; a value of zero specifies the page is visible

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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


For the description of this property, please see [getDel()](../../com.aspose.diagram/pageprops\#getDel--)

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

