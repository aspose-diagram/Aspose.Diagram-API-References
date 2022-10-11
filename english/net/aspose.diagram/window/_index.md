---
title: Window
second_title: Aspose.Diagram for .NET API Reference
description: Represents an open window in a Microsoft Visio instance. This element contains information necessary to exactly recreate a user interface window in the application workspace when the DatadiagramML file is initially opened by Visio.
type: docs
weight: 4380
url: /net/aspose.diagram/window/
---
## Window class

Represents an open window in a Microsoft Visio instance. This element contains information necessary to exactly re-create a user interface window in the application workspace when the DatadiagramML file is initially opened by Visio.

```csharp
public class Window
```

## Constructors

| Name | Description |
| --- | --- |
| [Window](window)() | Constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Container](../../aspose.diagram/window/container) { get; set; } | ID of container: Page, Sheet, or Master. Only relevant and necessary if ContainerType is specified. |
| [ContainerType](../../aspose.diagram/window/containertype) { get; set; } | May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or Sheet. |
| [Document](../../aspose.diagram/window/document) { get; set; } | File path of the document displayed in this window. This attribute is relevant for windows whose WindowType is specified as Stencil. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled) { get; set; } | Specifies whether the dynamic grid feature is enabled for a document or window. |
| [GlueSettings](../../aspose.diagram/window/gluesettings) { get; set; } | Specifies the objects that shapes glue to when glue is enabled in the document. |
| [ID](../../aspose.diagram/window/id) { get; set; } | The unique ID of the element within its parent element. |
| [Master](../../aspose.diagram/window/master) { get; set; } | Master ID if this window is displaying a master. |
| [Page](../../aspose.diagram/window/page) { get; set; } | Page ID if this window is displaying a page. Relevant only when WindowType is specified as Drawing and ContainerType is specified as Page. |
| [ParentWindow](../../aspose.diagram/window/parentwindow) { get; set; } | ID of window in which this stencil window is contained. Relevant only when WindowType is specified as Stencil. |
| [ReadOnly](../../aspose.diagram/window/readonly) { get; set; } | Read-only flag if this stencil is not a document stencil. |
| [Sheet](../../aspose.diagram/window/sheet) { get; set; } | ID of sheet in container. Relevant only when Container is specified as Sheet. |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints) { get; set; } | Specifies whether connection points are shown in a window. |
| [ShowGrid](../../aspose.diagram/window/showgrid) { get; set; } | Specifies whether a grid is shown in the drawing window. |
| [ShowGuides](../../aspose.diagram/window/showguides) { get; set; } | Specifies whether guides are shown in the drawing window. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks) { get; set; } | Specifies whether page breaks are shown in a window. |
| [ShowRulers](../../aspose.diagram/window/showrulers) { get; set; } | Specifies whether rulers are shown in the drawing window. |
| [SnapAngles](../../aspose.diagram/window/snapangles) { get; } | Contains a collection of SnapAngle elements. |
| [SnapExtensions](../../aspose.diagram/window/snapextensions) { get; set; } | Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value can be a sum of the values in the following table. |
| [SnapSettings](../../aspose.diagram/window/snapsettings) { get; set; } | Specifies the objects that shapes snap to when snap is active in the window. The value may be a sum of the values in the following table. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup) { get; set; } | Specifies the group of merged stencil windows of which the window is a member. This attribute is relevant only for Window elements whose WindowType attribute is Stencil, and only if the stencil window is part of a merged group of stencil windows. All stencil windows that are part of the same merged group have the same StencilGroup element value. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos) { get; set; } | Contains an integer that specifies the relative position of a stencil within a group in a window. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos) { get; set; } | Specifies the width of the page tab control of a drawing window (as a fraction of the total width of the drawing window). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx) { get; set; } | Optional double. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery) { get; set; } | Optional double. |
| [ViewScale](../../aspose.diagram/window/viewscale) { get; set; } | Optional double. |
| [WindowHeight](../../aspose.diagram/window/windowheight) { get; set; } | Height of the window rectangle. |
| [WindowLeft](../../aspose.diagram/window/windowleft) { get; set; } | Left coordinate of the window rectangle. |
| [WindowState](../../aspose.diagram/window/windowstate) { get; set; } | This attribute can be a sum of the following values. |
| [WindowTop](../../aspose.diagram/window/windowtop) { get; set; } | Top coordinate of the window rectangle. |
| [WindowType](../../aspose.diagram/window/windowtype) { get; set; } | An enumerated value that may be one of the following: Drawing, Sheet, Stencil, or Icon.A Window element of WindowType='Stencil' must appear after its parent drawing window (WindowType='Drawing') and before any other drawing window elements. |
| [WindowWidth](../../aspose.diagram/window/windowwidth) { get; set; } | Width of the window rectangle. |

### See Also

* namespace [Aspose.Diagram](../../aspose.diagram)
* assembly [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
