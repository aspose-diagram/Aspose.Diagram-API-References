---
title: PageLayout
second_title: Aspose.Diagram for Java API Reference
description: Contains cells that control the page layout settings for shapes and connectors such as spacing between all shapes on the page spacing between all connectors on the page and routing style for all connectors on the page.
type: docs
weight: 263
url: /java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

Contains cells that control the page layout settings for shapes and connectors, such as spacing between all shapes on the page, spacing between all connectors on the page, and routing style for all connectors on the page.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | Determines the amount of vertical space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page. |
| [getAvenueSizeY()](#getAvenueSizeY--) | Determines the amount of vertical space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page. |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | Specifies how shapes are placed on the page when shapes are laid out when a user selects Lay Out Shapes (Shape menu). |
| [getBlockSizeX()](#getBlockSizeX--) | Determines the vertical block size, the area in which each of your shapes must fit on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page. |
| [getBlockSizeY()](#getBlockSizeY--) | Determines the amount of horizontal space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page. |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | Determines which shape is the parent when using shapes by control handles. |
| [getDel()](#getDel--) | A flag indicating whether the element has been deleted locally. |
| [getDynamicsOff()](#getDynamicsOff--) | Specifies whether placeable shapes move and connectors reroute around other shapes and connectors on the drawing page. |
| [getEnableGrid()](#getEnableGrid--) | Specifies whether Microsoft Visio lays out shapes based on an internal page grid when the user selects Lay Out Shapes (Shape menu). |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | Specifies which dynamic connectors to space apart if they route on top of each other. |
| [getLineAdjustTo()](#getLineAdjustTo--) | Specifies which dynamic connectors to line up on top of one another if they route on top of each other. |
| [getLineJumpCode()](#getLineJumpCode--) | Specifies the line jump style for all connectors on the drawing page that don't have a local line jump style. |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | Specifies the size of line jumps on horizontal segments of dynamic connectors on the page, as a percentage of the value of the LineToLineX element (which specifies the horizontal clearance between all connectors on the drawing page). |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | Specifies the size of line jumps on vertical segments of dynamic connectors on the page, as a percentage of the value of the LineToLineY element (which specifies the vertical clearance between all connectors on the drawing page). |
| [getLineJumpStyle()](#getLineJumpStyle--) | Specifies the direction of line jumps on horizontal segments of dynamic connectors on the drawing page for which you haven't applied a local jump direction. |
| [getLineRouteExt()](#getLineRouteExt--) | Specifies the default appearance for all connectors on a page. |
| [getLineToLineX()](#getLineToLineX--) | Specifies the minimum horizontal clearance between dynamic connectors on the drawing page. |
| [getLineToLineY()](#getLineToLineY--) | Specifies the minimum vertical clearance between dynamic connectors on the drawing page. |
| [getLineToNodeX()](#getLineToNodeX--) | Specifies the minimum vertical clearance between dynamic connectors and shapes on the drawing page. |
| [getLineToNodeY()](#getLineToNodeY--) | Determines the horizontal block size, the area in which each of your shapes must fit on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page. |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | Specifies the direction of line jumps on vertical dynamic connectors on the drawing page for which you haven't applied a local jump direction. |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | Specifies the minimum horizontal clearance between dynamic connectors and shapes on the drawing page. |
| [getPageShapeSplit()](#getPageShapeSplit--) | Indicates whether shapes on the page can be split automatically. |
| [getPlaceDepth()](#getPlaceDepth--) | Specifies whether placeable shapes move away when the user drags a placeable shape near another placeable shape on the drawing page. |
| [getPlaceFlip()](#getPlaceFlip--) | Specifies how placeable shapes flip and/or rotate on a page when shapes are laid out using the Lay Out Shapes command in Microsoft Visio. |
| [getPlaceStyle()](#getPlaceStyle--) | Specifies the routing style and direction for all dynamic connectors on the drawing page that don't have a local routing style. |
| [getPlowCode()](#getPlowCode--) | Determines the dynamic connectors to which you want to add jumps. |
| [getResizePage()](#getResizePage--) | Specifies whether to enlarge the page to enclose the drawing after a user selects Lay Out Shapes (Shapes menu). |
| [getRouteStyle()](#getRouteStyle--) | For a drawing that is laid out automatically, specifies the method by which the drawing is analyzed before creating the layout and determines the type of layout. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/pagelayout\#getDel--) |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


Determines the amount of vertical space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


Determines the amount of vertical space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


Specifies how shapes are placed on the page when shapes are laid out when a user selects Lay Out Shapes (Shape menu).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


Determines the vertical block size, the area in which each of your shapes must fit on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


Determines the amount of horizontal space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


Determines which shape is the parent when using shapes by control handles. This element sets the behavior for all the shapes on the drawing page.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


Specifies whether placeable shapes move and connectors reroute around other shapes and connectors on the drawing page.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


Specifies whether Microsoft Visio lays out shapes based on an internal page grid when the user selects Lay Out Shapes (Shape menu).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


Specifies which dynamic connectors to space apart if they route on top of each other.

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


Specifies which dynamic connectors to line up on top of one another if they route on top of each other.

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


Specifies the line jump style for all connectors on the drawing page that don't have a local line jump style.

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


Specifies the size of line jumps on horizontal segments of dynamic connectors on the page, as a percentage of the value of the LineToLineX element (which specifies the horizontal clearance between all connectors on the drawing page). The value of this element ranges from 0 to 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


Specifies the size of line jumps on vertical segments of dynamic connectors on the page, as a percentage of the value of the LineToLineY element (which specifies the vertical clearance between all connectors on the drawing page). This element can contain a value from 0 to 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


Specifies the direction of line jumps on horizontal segments of dynamic connectors on the drawing page for which you haven't applied a local jump direction.

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


Specifies the default appearance for all connectors on a page.

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


Specifies the minimum horizontal clearance between dynamic connectors on the drawing page.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


Specifies the minimum vertical clearance between dynamic connectors on the drawing page.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


Specifies the minimum vertical clearance between dynamic connectors and shapes on the drawing page.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


Determines the horizontal block size, the area in which each of your shapes must fit on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


Specifies the direction of line jumps on vertical dynamic connectors on the drawing page for which you haven't applied a local jump direction.

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


Specifies the minimum horizontal clearance between dynamic connectors and shapes on the drawing page.

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


Indicates whether shapes on the page can be split automatically.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


Specifies whether placeable shapes move away when the user drags a placeable shape near another placeable shape on the drawing page.

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


Specifies how placeable shapes flip and/or rotate on a page when shapes are laid out using the Lay Out Shapes command in Microsoft Visio. The following hexadecimal values are allowed.

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


Specifies the routing style and direction for all dynamic connectors on the drawing page that don't have a local routing style.

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


Determines the dynamic connectors to which you want to add jumps.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


Specifies whether to enlarge the page to enclose the drawing after a user selects Lay Out Shapes (Shapes menu).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


For a drawing that is laid out automatically, specifies the method by which the drawing is analyzed before creating the layout and determines the type of layout.

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


For the description of this property, please see [getDel()](../../com.aspose.diagram/pagelayout\#getDel--)

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

