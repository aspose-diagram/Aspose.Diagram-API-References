---
title: "Window Class"
linktitle: "Window"
articleTitle: "Window"
second_title: "Aspose.Diagram for Python via Java"
description: "Represents an open window in a Microsoft Visio instance."
type: docs
weight: 3840
url: /python-java/asposediagram.api/window/
---

## Window class

Represents an open window in a Microsoft Visio instance. This element contains information necessary to exactly re-create a user interface window in the application workspace when the DatadiagramML file is initially opened by Visio.

```python
Window()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [StencilGroup](/python-java/asposediagram.api/window/stencilgroup/) | String | Specifies the group of merged stencil windows of which the window is a member. This attribute is relevant only for Windo |
| [StencilGroupPos](/python-java/asposediagram.api/window/stencilgrouppos/) | int | Contains an integer that specifies the relative position of a stencil within a group in a window. |
| [ShowRulers](/python-java/asposediagram.api/window/showrulers/) | int | Specifies whether rulers are shown in the drawing window. The value of the property is BOOL integer constant. |
| [ShowGrid](/python-java/asposediagram.api/window/showgrid/) | int | Specifies whether a grid is shown in the drawing window. The value of the property is BOOL integer constant. |
| [ShowPageBreaks](/python-java/asposediagram.api/window/showpagebreaks/) | int | Specifies whether page breaks are shown in a window. The value of the property is BOOL integer constant. |
| [ShowGuides](/python-java/asposediagram.api/window/showguides/) | int | Specifies whether guides are shown in the drawing window. The value of the property is BOOL integer constant. |
| [ShowConnectionPoints](/python-java/asposediagram.api/window/showconnectionpoints/) | int | Specifies whether connection points are shown in a window. The value of the property is BOOL integer constant. |
| [GlueSettings](/python-java/asposediagram.api/window/gluesettings/) | int | Specifies the objects that shapes glue to when glue is enabled in the document. The value of the property is GlueSetting |
| [SnapSettings](/python-java/asposediagram.api/window/snapsettings/) | int | Specifies the objects that shapes snap to when snap is active in the window. The value may be a sum of the values in the |
| [SnapExtensions](/python-java/asposediagram.api/window/snapextensions/) | int | Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value can be a sum |
| [SnapAngles](/python-java/asposediagram.api/window/snapangles/) | FloatPointNumCollection | Contains a collection of SnapAngle elements. |
| [DynamicGridEnabled](/python-java/asposediagram.api/window/dynamicgridenabled/) | int | Specifies whether the dynamic grid feature is enabled for a document or window. The value of the property is BOOL intege |
| [TabSplitterPos](/python-java/asposediagram.api/window/tabsplitterpos/) | float | Specifies the width of the page tab control of a drawing window (as a fraction of the total width of the drawing window) |
| [ID](/python-java/asposediagram.api/window/id/) | int | The unique ID of the element within its parent element. |
| [WindowType](/python-java/asposediagram.api/window/windowtype/) | int | An enumerated value that may be one of the following: Drawing, Sheet, Stencil, or Icon.A Window element of WindowType='S |
| [WindowState](/python-java/asposediagram.api/window/windowstate/) | int | This attribute can be a sum of the following values. The value of the property is WindowStateValue integer constant. |
| [Document](/python-java/asposediagram.api/window/document/) | String | File path of the document displayed in this window. This attribute is relevant for windows whose WindowType is specified |
| [WindowLeft](/python-java/asposediagram.api/window/windowleft/) | int | Left coordinate of the window rectangle. |
| [WindowTop](/python-java/asposediagram.api/window/windowtop/) | int | Top coordinate of the window rectangle. |
| [WindowWidth](/python-java/asposediagram.api/window/windowwidth/) | long | Width of the window rectangle. |
| [WindowHeight](/python-java/asposediagram.api/window/windowheight/) | long | Height of the window rectangle. |
| [Master](/python-java/asposediagram.api/window/master/) | Master | Master ID if this window is displaying a master. |
| [ContainerType](/python-java/asposediagram.api/window/containertype/) | int | May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or  |
| [Container](/python-java/asposediagram.api/window/container/) | int | ID of container: Page, Sheet, or Master. Only relevant and necessary if ContainerType is specified. |
| [Sheet](/python-java/asposediagram.api/window/sheet/) | int | ID of sheet in container. Relevant only when Container is specified as Sheet. |
| [ReadOnly](/python-java/asposediagram.api/window/readonly/) | int | Read-only flag if this stencil is not a document stencil. The value of the property is BOOL integer constant. |
| [ParentWindow](/python-java/asposediagram.api/window/parentwindow/) | int | ID of window in which this stencil window is contained. Relevant only when WindowType is specified as Stencil. |
| [Page](/python-java/asposediagram.api/window/page/) | Page | Page ID if this window is displaying a page. Relevant only when WindowType is specified as Drawing and ContainerType is  |
| [ViewScale](/python-java/asposediagram.api/window/viewscale/) | float | Optional double. |
| [ViewCenterX](/python-java/asposediagram.api/window/viewcenterx/) | float | Optional double. |
| [ViewCenterY](/python-java/asposediagram.api/window/viewcentery/) | float | Optional double. |
