---
title: Window
second_title: Aspose.Diagram for Java API Reference
description: Represents an open window in a Microsoft Visio instance.
type: docs
weight: 451
url: /java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Represents an open window in a Microsoft Visio instance. This element contains information necessary to exactly re-create a user interface window in the application workspace when the DatadiagramML file is initially opened by Visio.
## Constructors

| Constructor | Description |
| --- | --- |
| [Window()](#Window--) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | ID of container: Page, Sheet, or Master. |
| [getContainerType()](#getContainerType--) | May be one of the following values: Document, Page, or Master. |
| [getDocument()](#getDocument--) | File path of the document displayed in this window. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Specifies whether the dynamic grid feature is enabled for a document or window. |
| [getGlueSettings()](#getGlueSettings--) | Specifies the objects that shapes glue to when glue is enabled in the document. |
| [getID()](#getID--) | The unique ID of the element within its parent element. |
| [getMaster()](#getMaster--) | Master ID if this window is displaying a master. |
| [getPage()](#getPage--) | Page ID if this window is displaying a page. |
| [getParentWindow()](#getParentWindow--) | ID of window in which this stencil window is contained. |
| [getReadOnly()](#getReadOnly--) | Read-only flag if this stencil is not a document stencil. |
| [getSheet()](#getSheet--) | ID of sheet in container. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | Specifies whether connection points are shown in a window. |
| [getShowGrid()](#getShowGrid--) | Specifies whether a grid is shown in the drawing window. |
| [getShowGuides()](#getShowGuides--) | Specifies whether guides are shown in the drawing window. |
| [getShowPageBreaks()](#getShowPageBreaks--) | Specifies whether page breaks are shown in a window. |
| [getShowRulers()](#getShowRulers--) | Specifies whether rulers are shown in the drawing window. |
| [getSnapAngles()](#getSnapAngles--) | Contains a collection of SnapAngle elements. |
| [getSnapExtensions()](#getSnapExtensions--) | Specifies whether a specific snap extension setting is enabled or disabled for the active window. |
| [getSnapSettings()](#getSnapSettings--) | Specifies the objects that shapes snap to when snap is active in the window. |
| [getStencilGroup()](#getStencilGroup--) | Specifies the group of merged stencil windows of which the window is a member. |
| [getStencilGroupPos()](#getStencilGroupPos--) | Contains an integer that specifies the relative position of a stencil within a group in a window. |
| [getTabSplitterPos()](#getTabSplitterPos--) | Specifies the width of the page tab control of a drawing window (as a fraction of the total width of the drawing window). |
| [getViewCenterX()](#getViewCenterX--) | Optional double. |
| [getViewCenterY()](#getViewCenterY--) | Optional double. |
| [getViewScale()](#getViewScale--) | Optional double. |
| [getWindowHeight()](#getWindowHeight--) | Height of the window rectangle. |
| [getWindowLeft()](#getWindowLeft--) | Left coordinate of the window rectangle. |
| [getWindowState()](#getWindowState--) | This attribute can be a sum of the following values. |
| [getWindowTop()](#getWindowTop--) | Top coordinate of the window rectangle. |
| [getWindowType()](#getWindowType--) | An enumerated value that may be one of the following: Drawing, Sheet, Stencil, or Icon.A Window element of WindowType='Stencil' must appear after its parent drawing window (WindowType='Drawing') and before any other drawing window elements. |
| [getWindowWidth()](#getWindowWidth--) | Width of the window rectangle. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | For the description of this property, please see [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | For the description of this property, please see [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | For the description of this property, please see [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | For the description of this property, please see [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | For the description of this property, please see [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | For the description of this property, please see [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | For the description of this property, please see [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | For the description of this property, please see [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | For the description of this property, please see [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | For the description of this property, please see [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | For the description of this property, please see [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | For the description of this property, please see [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | For the description of this property, please see [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | For the description of this property, please see [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | For the description of this property, please see [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | For the description of this property, please see [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | For the description of this property, please see [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | For the description of this property, please see [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | For the description of this property, please see [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | For the description of this property, please see [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | For the description of this property, please see [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | For the description of this property, please see [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | For the description of this property, please see [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | For the description of this property, please see [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | For the description of this property, please see [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | For the description of this property, please see [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | For the description of this property, please see [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | For the description of this property, please see [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | For the description of this property, please see [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | For the description of this property, please see [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public int getContainer()
```


ID of container: Page, Sheet, or Master. Only relevant and necessary if ContainerType is specified.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


File path of the document displayed in this window. This attribute is relevant for windows whose WindowType is specified as Stencil.

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


Specifies whether the dynamic grid feature is enabled for a document or window.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


Specifies the objects that shapes glue to when glue is enabled in the document.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


The unique ID of the element within its parent element.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Master ID if this window is displaying a master.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


Page ID if this window is displaying a page. Relevant only when WindowType is specified as Drawing and ContainerType is specified as Page.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


ID of window in which this stencil window is contained. Relevant only when WindowType is specified as Stencil.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


Read-only flag if this stencil is not a document stencil.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


ID of sheet in container. Relevant only when Container is specified as Sheet.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


Specifies whether connection points are shown in a window.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


Specifies whether a grid is shown in the drawing window.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


Specifies whether guides are shown in the drawing window.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


Specifies whether page breaks are shown in a window.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


Specifies whether rulers are shown in the drawing window.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


Contains a collection of SnapAngle elements.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value can be a sum of the values in the following table.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Specifies the objects that shapes snap to when snap is active in the window. The value may be a sum of the values in the following table.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


Specifies the group of merged stencil windows of which the window is a member. This attribute is relevant only for Window elements whose WindowType attribute is Stencil, and only if the stencil window is part of a merged group of stencil windows. All stencil windows that are part of the same merged group have the same StencilGroup element value.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


Contains an integer that specifies the relative position of a stencil within a group in a window.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


Specifies the width of the page tab control of a drawing window (as a fraction of the total width of the drawing window).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


Optional double.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


Optional double.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Optional double.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


Height of the window rectangle.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


Left coordinate of the window rectangle.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


This attribute can be a sum of the following values.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


Top coordinate of the window rectangle.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


An enumerated value that may be one of the following: Drawing, Sheet, Stencil, or Icon.A Window element of WindowType='Stencil' must appear after its parent drawing window (WindowType='Drawing') and before any other drawing window elements.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


Width of the window rectangle.

**Returns:**
long
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




### setContainer(int value) {#setContainer-int-}
```
public void setContainer(int value)
```


For the description of this property, please see [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


For the description of this property, please see [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


For the description of this property, please see [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


For the description of this property, please see [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


For the description of this property, please see [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


For the description of this property, please see [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


For the description of this property, please see [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


For the description of this property, please see [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


For the description of this property, please see [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


For the description of this property, please see [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


For the description of this property, please see [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


For the description of this property, please see [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


For the description of this property, please see [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


For the description of this property, please see [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


For the description of this property, please see [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


For the description of this property, please see [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


For the description of this property, please see [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


For the description of this property, please see [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


For the description of this property, please see [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


For the description of this property, please see [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


For the description of this property, please see [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


For the description of this property, please see [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


For the description of this property, please see [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


For the description of this property, please see [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


For the description of this property, please see [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


For the description of this property, please see [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


For the description of this property, please see [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


For the description of this property, please see [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


For the description of this property, please see [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


For the description of this property, please see [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

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

