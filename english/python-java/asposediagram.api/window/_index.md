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
| [StencilGroup](./stencilgroup/) | String | Specifies the group of merged stencil windows of which the window is a member. This attribute is relevant only for Windo |
| [StencilGroupPos](./stencilgrouppos/) | int | Contains an integer that specifies the relative position of a stencil within a group in a window. |
| [ShowRulers](./showrulers/) | int | Specifies whether rulers are shown in the drawing window. The value of the property is BOOL integer constant. |
| [ShowGrid](./showgrid/) | int | Specifies whether a grid is shown in the drawing window. The value of the property is BOOL integer constant. |
| [ShowPageBreaks](./showpagebreaks/) | int | Specifies whether page breaks are shown in a window. The value of the property is BOOL integer constant. |
| [ShowGuides](./showguides/) | int | Specifies whether guides are shown in the drawing window. The value of the property is BOOL integer constant. |
| [ShowConnectionPoints](./showconnectionpoints/) | int | Specifies whether connection points are shown in a window. The value of the property is BOOL integer constant. |
| [GlueSettings](./gluesettings/) | int | Specifies the objects that shapes glue to when glue is enabled in the document. The value of the property is GlueSetting |
| [SnapSettings](./snapsettings/) | int | Specifies the objects that shapes snap to when snap is active in the window. The value may be a sum of the values in the |
| [SnapExtensions](./snapextensions/) | int | Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value can be a sum |
| [SnapAngles](./snapangles/) | FloatPointNumCollection | Contains a collection of SnapAngle elements. |
| [DynamicGridEnabled](./dynamicgridenabled/) | int | Specifies whether the dynamic grid feature is enabled for a document or window. The value of the property is BOOL intege |
| [TabSplitterPos](./tabsplitterpos/) | float | Specifies the width of the page tab control of a drawing window (as a fraction of the total width of the drawing window) |
| [ID](./id/) | int | The unique ID of the element within its parent element. |
| [WindowType](./windowtype/) | int | An enumerated value that may be one of the following: Drawing, Sheet, Stencil, or Icon.A Window element of WindowType='S |
| [WindowState](./windowstate/) | int | This attribute can be a sum of the following values. The value of the property is WindowStateValue integer constant. |
| [Document](./document/) | String | File path of the document displayed in this window. This attribute is relevant for windows whose WindowType is specified |
| [WindowLeft](./windowleft/) | int | Left coordinate of the window rectangle. |
| [WindowTop](./windowtop/) | int | Top coordinate of the window rectangle. |
| [WindowWidth](./windowwidth/) | long | Width of the window rectangle. |
| [WindowHeight](./windowheight/) | long | Height of the window rectangle. |
| [Master](./master/) | Master | Master ID if this window is displaying a master. |
| [ContainerType](./containertype/) | int | May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or  |
| [Container](./container/) | int | ID of container: Page, Sheet, or Master. Only relevant and necessary if ContainerType is specified. |
| [Sheet](./sheet/) | int | ID of sheet in container. Relevant only when Container is specified as Sheet. |
| [ReadOnly](./readonly/) | int | Read-only flag if this stencil is not a document stencil. The value of the property is BOOL integer constant. |
| [ParentWindow](./parentwindow/) | int | ID of window in which this stencil window is contained. Relevant only when WindowType is specified as Stencil. |
| [Page](./page/) | Page | Page ID if this window is displaying a page. Relevant only when WindowType is specified as Drawing and ContainerType is  |
| [ViewScale](./viewscale/) | float | Optional double. |
| [ViewCenterX](./viewcenterx/) | float | Optional double. |
| [ViewCenterY](./viewcentery/) | float | Optional double. |
