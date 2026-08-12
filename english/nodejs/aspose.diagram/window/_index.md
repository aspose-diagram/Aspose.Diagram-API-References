---
title: "Window"
linktitle: "Window"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Represents an open window in a Microsoft Visio instance."
type: docs
weight: 2900
url: /nodejs/aspose.diagram/window/
---

## Window class

Represents an open window in a Microsoft Visio instance. This element contains information necessary to exactly re-create a user interface window in the application workspace when the DatadiagramML file is initially opened by Visio.

```js
new Window()
```

Constructor.

## Methods

| Name | Description |
| --- | --- |
| [getContainer()](#getcontainer) | ID of container: Page, Sheet, or Master. Only relevant and necessary if ContainerType is specified. |
| [getContainerType()](#getcontainertype) | May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or  |
| [getDocument()](#getdocument) | File path of the document displayed in this window. This attribute is relevant for windows whose WindowType is specified |
| [getDynamicGridEnabled()](#getdynamicgridenabled) | Specifies whether the dynamic grid feature is enabled for a document or window. The value of the property is BOOL intege |
| [getGlueSettings()](#getgluesettings) | Specifies the objects that shapes glue to when glue is enabled in the document. The value of the property is GlueSetting |
| [getID()](#getid) | The unique ID of the element within its parent element. |
| [getMaster()](#getmaster) | Master ID if this window is displaying a master. |
| [getPage()](#getpage) | Page ID if this window is displaying a page. Relevant only when WindowType is specified as Drawing and ContainerType is  |
| [getParentWindow()](#getparentwindow) | ID of window in which this stencil window is contained. Relevant only when WindowType is specified as Stencil. |
| [getReadOnly()](#getreadonly) | Read-only flag if this stencil is not a document stencil. The value of the property is BOOL integer constant. |
| [getSheet()](#getsheet) | ID of sheet in container. Relevant only when Container is specified as Sheet. |
| [getShowConnectionPoints()](#getshowconnectionpoints) | Specifies whether connection points are shown in a window. The value of the property is BOOL integer constant. |
| [getShowGrid()](#getshowgrid) | Specifies whether a grid is shown in the drawing window. The value of the property is BOOL integer constant. |
| [getShowGuides()](#getshowguides) | Specifies whether guides are shown in the drawing window. The value of the property is BOOL integer constant. |
| [getShowPageBreaks()](#getshowpagebreaks) | Specifies whether page breaks are shown in a window. The value of the property is BOOL integer constant. |
| [getShowRulers()](#getshowrulers) | Specifies whether rulers are shown in the drawing window. The value of the property is BOOL integer constant. |
| [getSnapAngles()](#getsnapangles) | Contains a collection of SnapAngle elements. |
| [getSnapExtensions()](#getsnapextensions) | Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value can be a sum |
| [getSnapSettings()](#getsnapsettings) | Specifies the objects that shapes snap to when snap is active in the window. The value may be a sum of the values in the |
| [getStencilGroup()](#getstencilgroup) | Specifies the group of merged stencil windows of which the window is a member. This attribute is relevant only for Windo |
| [getStencilGroupPos()](#getstencilgrouppos) | Contains an integer that specifies the relative position of a stencil within a group in a window. |
| [getTabSplitterPos()](#gettabsplitterpos) | Specifies the width of the page tab control of a drawing window (as a fraction of the total width of the drawing window) |
| [getViewCenterX()](#getviewcenterx) | Optional double. |
| [getViewCenterY()](#getviewcentery) | Optional double. |
| [getViewScale()](#getviewscale) | Optional double. |
| [getWindowHeight()](#getwindowheight) | Height of the window rectangle. |
| [getWindowLeft()](#getwindowleft) | Left coordinate of the window rectangle. |
| [getWindowState()](#getwindowstate) | This attribute can be a sum of the following values. The value of the property is WindowStateValue integer constant. |
| [getWindowTop()](#getwindowtop) | Top coordinate of the window rectangle. |
| [getWindowType()](#getwindowtype) | An enumerated value that may be one of the following: Drawing, Sheet, Stencil, or Icon.A Window element of WindowType='S |
| [getWindowWidth()](#getwindowwidth) | Width of the window rectangle. |
| [setContainer()](#setcontainer) | ID of container: Page, Sheet, or Master. Only relevant and necessary if ContainerType is specified. |
| [setContainerType()](#setcontainertype) | May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or  |
| [setDocument()](#setdocument) | File path of the document displayed in this window. This attribute is relevant for windows whose WindowType is specified |
| [setDynamicGridEnabled()](#setdynamicgridenabled) | Specifies whether the dynamic grid feature is enabled for a document or window. The value of the property is BOOL intege |
| [setGlueSettings()](#setgluesettings) | Specifies the objects that shapes glue to when glue is enabled in the document. The value of the property is GlueSetting |
| [setID()](#setid) | The unique ID of the element within its parent element. |
| [setMaster()](#setmaster) | Master ID if this window is displaying a master. |
| [setPage()](#setpage) | Page ID if this window is displaying a page. Relevant only when WindowType is specified as Drawing and ContainerType is  |
| [setParentWindow()](#setparentwindow) | ID of window in which this stencil window is contained. Relevant only when WindowType is specified as Stencil. |
| [setReadOnly()](#setreadonly) | Read-only flag if this stencil is not a document stencil. The value of the property is BOOL integer constant. |
| [setSheet()](#setsheet) | ID of sheet in container. Relevant only when Container is specified as Sheet. |
| [setShowConnectionPoints()](#setshowconnectionpoints) | Specifies whether connection points are shown in a window. The value of the property is BOOL integer constant. |
| [setShowGrid()](#setshowgrid) | Specifies whether a grid is shown in the drawing window. The value of the property is BOOL integer constant. |
| [setShowGuides()](#setshowguides) | Specifies whether guides are shown in the drawing window. The value of the property is BOOL integer constant. |
| [setShowPageBreaks()](#setshowpagebreaks) | Specifies whether page breaks are shown in a window. The value of the property is BOOL integer constant. |
| [setShowRulers()](#setshowrulers) | Specifies whether rulers are shown in the drawing window. The value of the property is BOOL integer constant. |
| [setSnapExtensions()](#setsnapextensions) | Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value can be a sum |
| [setSnapSettings()](#setsnapsettings) | Specifies the objects that shapes snap to when snap is active in the window. The value may be a sum of the values in the |
| [setStencilGroup()](#setstencilgroup) | Specifies the group of merged stencil windows of which the window is a member. This attribute is relevant only for Windo |
| [setStencilGroupPos()](#setstencilgrouppos) | Contains an integer that specifies the relative position of a stencil within a group in a window. |
| [setTabSplitterPos()](#settabsplitterpos) | Specifies the width of the page tab control of a drawing window (as a fraction of the total width of the drawing window) |
| [setViewCenterX()](#setviewcenterx) | Optional double. |
| [setViewCenterY()](#setviewcentery) | Optional double. |
| [setViewScale()](#setviewscale) | Optional double. |
| [setWindowHeight()](#setwindowheight) | Height of the window rectangle. |
| [setWindowLeft()](#setwindowleft) | Left coordinate of the window rectangle. |
| [setWindowState()](#setwindowstate) | This attribute can be a sum of the following values. The value of the property is WindowStateValue integer constant. |
| [setWindowTop()](#setwindowtop) | Top coordinate of the window rectangle. |
| [setWindowType()](#setwindowtype) | An enumerated value that may be one of the following: Drawing, Sheet, Stencil, or Icon.A Window element of WindowType='S |
| [setWindowWidth()](#setwindowwidth) | Width of the window rectangle. |

### getContainer() {#getcontainer}

ID of container: Page, Sheet, or Master. Only relevant and necessary if ContainerType is specified.

### getContainerType() {#getcontainertype}

May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or Sheet. The value of the property is ContainerTypeValue integer constant.

### getDocument() {#getdocument}

File path of the document displayed in this window. This attribute is relevant for windows whose WindowType is specified as Stencil.

### getDynamicGridEnabled() {#getdynamicgridenabled}

Specifies whether the dynamic grid feature is enabled for a document or window. The value of the property is BOOL integer constant.

### getGlueSettings() {#getgluesettings}

Specifies the objects that shapes glue to when glue is enabled in the document. The value of the property is GlueSettingsValue integer constant.

### getID() {#getid}

The unique ID of the element within its parent element.

### getMaster() {#getmaster}

Master ID if this window is displaying a master.

### getPage() {#getpage}

Page ID if this window is displaying a page. Relevant only when WindowType is specified as Drawing and ContainerType is specified as Page.

### getParentWindow() {#getparentwindow}

ID of window in which this stencil window is contained. Relevant only when WindowType is specified as Stencil.

### getReadOnly() {#getreadonly}

Read-only flag if this stencil is not a document stencil. The value of the property is BOOL integer constant.

### getSheet() {#getsheet}

ID of sheet in container. Relevant only when Container is specified as Sheet.

### getShowConnectionPoints() {#getshowconnectionpoints}

Specifies whether connection points are shown in a window. The value of the property is BOOL integer constant.

### getShowGrid() {#getshowgrid}

Specifies whether a grid is shown in the drawing window. The value of the property is BOOL integer constant.

### getShowGuides() {#getshowguides}

Specifies whether guides are shown in the drawing window. The value of the property is BOOL integer constant.

### getShowPageBreaks() {#getshowpagebreaks}

Specifies whether page breaks are shown in a window. The value of the property is BOOL integer constant.

### getShowRulers() {#getshowrulers}

Specifies whether rulers are shown in the drawing window. The value of the property is BOOL integer constant.

### getSnapAngles() {#getsnapangles}

Contains a collection of SnapAngle elements.

### getSnapExtensions() {#getsnapextensions}

Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value can be a sum of the values in the following table. The value of the property is SnapExtensionsValue integer constant.

### getSnapSettings() {#getsnapsettings}

Specifies the objects that shapes snap to when snap is active in the window. The value may be a sum of the values in the following table. The value of the property is SnapSettingsValue integer constant.

### getStencilGroup() {#getstencilgroup}

Specifies the group of merged stencil windows of which the window is a member. This attribute is relevant only for Window elements whose WindowType attribute is Stencil, and only if the stencil window is part of a merged group of stencil windows. All stencil windows that are part of the same merged group have the same StencilGroup element value.

### getStencilGroupPos() {#getstencilgrouppos}

Contains an integer that specifies the relative position of a stencil within a group in a window.

### getTabSplitterPos() {#gettabsplitterpos}

Specifies the width of the page tab control of a drawing window (as a fraction of the total width of the drawing window).

### getViewCenterX() {#getviewcenterx}

Optional double.

### getViewCenterY() {#getviewcentery}

Optional double.

### getViewScale() {#getviewscale}

Optional double.

### getWindowHeight() {#getwindowheight}

Height of the window rectangle.

### getWindowLeft() {#getwindowleft}

Left coordinate of the window rectangle.

### getWindowState() {#getwindowstate}

This attribute can be a sum of the following values. The value of the property is WindowStateValue integer constant.

### getWindowTop() {#getwindowtop}

Top coordinate of the window rectangle.

### getWindowType() {#getwindowtype}

An enumerated value that may be one of the following: Drawing, Sheet, Stencil, or Icon.A Window element of WindowType='Stencil' must appear after its parent drawing window (WindowType='Drawing') and before any other drawing window elements. The value of the property is WindowTypeValue integer constant.

### getWindowWidth() {#getwindowwidth}

Width of the window rectangle.

### setContainer() {#setcontainer}

ID of container: Page, Sheet, or Master. Only relevant and necessary if ContainerType is specified.

### setContainerType() {#setcontainertype}

May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or Sheet. The value of the property is ContainerTypeValue integer constant.

### setDocument() {#setdocument}

File path of the document displayed in this window. This attribute is relevant for windows whose WindowType is specified as Stencil.

### setDynamicGridEnabled() {#setdynamicgridenabled}

Specifies whether the dynamic grid feature is enabled for a document or window. The value of the property is BOOL integer constant.

### setGlueSettings() {#setgluesettings}

Specifies the objects that shapes glue to when glue is enabled in the document. The value of the property is GlueSettingsValue integer constant.

### setID() {#setid}

The unique ID of the element within its parent element.

### setMaster() {#setmaster}

Master ID if this window is displaying a master.

### setPage() {#setpage}

Page ID if this window is displaying a page. Relevant only when WindowType is specified as Drawing and ContainerType is specified as Page.

### setParentWindow() {#setparentwindow}

ID of window in which this stencil window is contained. Relevant only when WindowType is specified as Stencil.

### setReadOnly() {#setreadonly}

Read-only flag if this stencil is not a document stencil. The value of the property is BOOL integer constant.

### setSheet() {#setsheet}

ID of sheet in container. Relevant only when Container is specified as Sheet.

### setShowConnectionPoints() {#setshowconnectionpoints}

Specifies whether connection points are shown in a window. The value of the property is BOOL integer constant.

### setShowGrid() {#setshowgrid}

Specifies whether a grid is shown in the drawing window. The value of the property is BOOL integer constant.

### setShowGuides() {#setshowguides}

Specifies whether guides are shown in the drawing window. The value of the property is BOOL integer constant.

### setShowPageBreaks() {#setshowpagebreaks}

Specifies whether page breaks are shown in a window. The value of the property is BOOL integer constant.

### setShowRulers() {#setshowrulers}

Specifies whether rulers are shown in the drawing window. The value of the property is BOOL integer constant.

### setSnapExtensions() {#setsnapextensions}

Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value can be a sum of the values in the following table. The value of the property is SnapExtensionsValue integer constant.

### setSnapSettings() {#setsnapsettings}

Specifies the objects that shapes snap to when snap is active in the window. The value may be a sum of the values in the following table. The value of the property is SnapSettingsValue integer constant.

### setStencilGroup() {#setstencilgroup}

Specifies the group of merged stencil windows of which the window is a member. This attribute is relevant only for Window elements whose WindowType attribute is Stencil, and only if the stencil window is part of a merged group of stencil windows. All stencil windows that are part of the same merged group have the same StencilGroup element value.

### setStencilGroupPos() {#setstencilgrouppos}

Contains an integer that specifies the relative position of a stencil within a group in a window.

### setTabSplitterPos() {#settabsplitterpos}

Specifies the width of the page tab control of a drawing window (as a fraction of the total width of the drawing window).

### setViewCenterX() {#setviewcenterx}

Optional double.

### setViewCenterY() {#setviewcentery}

Optional double.

### setViewScale() {#setviewscale}

Optional double.

### setWindowHeight() {#setwindowheight}

Height of the window rectangle.

### setWindowLeft() {#setwindowleft}

Left coordinate of the window rectangle.

### setWindowState() {#setwindowstate}

This attribute can be a sum of the following values. The value of the property is WindowStateValue integer constant.

### setWindowTop() {#setwindowtop}

Top coordinate of the window rectangle.

### setWindowType() {#setwindowtype}

An enumerated value that may be one of the following: Drawing, Sheet, Stencil, or Icon.A Window element of WindowType='Stencil' must appear after its parent drawing window (WindowType='Drawing') and before any other drawing window elements. The value of the property is WindowTypeValue integer constant.

### setWindowWidth() {#setwindowwidth}

Width of the window rectangle.
