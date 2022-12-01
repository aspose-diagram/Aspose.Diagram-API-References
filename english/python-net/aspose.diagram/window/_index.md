---
title: Window class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 2520
url: /python-net/aspose.diagram/window/
is_root: false
---

## Window class

Represents an open window in a Microsoft Visio instance. This element contains information necessary to exactly re-create a user interface window in the application workspace when the DatadiagramML file is initially opened by Visio.



The Window type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [Window()](/diagram/python-net/aspose.diagram/window/__init__/#) | Constructor. |


### Properties
| Property | Description |
| :- | :- |
| [stencil_group](/diagram/python-net/aspose.diagram/window/stencil_group) | Specifies the group of merged stencil windows of which the window is a member. This attribute is relevant only for Window elements whose WindowType attribute is Stencil, and only if the stencil window is part of a merged group of stencil windows. All stencil windows that are part of the same merged group have the same StencilGroup element value. |
| [stencil_group_pos](/diagram/python-net/aspose.diagram/window/stencil_group_pos) | Contains an integer that specifies the relative position of a stencil within a group in a window. |
| [show_rulers](/diagram/python-net/aspose.diagram/window/show_rulers) | Specifies whether rulers are shown in the drawing window. |
| [show_grid](/diagram/python-net/aspose.diagram/window/show_grid) | Specifies whether a grid is shown in the drawing window. |
| [show_page_breaks](/diagram/python-net/aspose.diagram/window/show_page_breaks) | Specifies whether page breaks are shown in a window. |
| [show_guides](/diagram/python-net/aspose.diagram/window/show_guides) | Specifies whether guides are shown in the drawing window. |
| [show_connection_points](/diagram/python-net/aspose.diagram/window/show_connection_points) | Specifies whether connection points are shown in a window. |
| [glue_settings](/diagram/python-net/aspose.diagram/window/glue_settings) | Specifies the objects that shapes glue to when glue is enabled in the document. |
| [snap_settings](/diagram/python-net/aspose.diagram/window/snap_settings) | Specifies the objects that shapes snap to when snap is active in the window. The value may be a sum of the values in the following table. |
| [snap_extensions](/diagram/python-net/aspose.diagram/window/snap_extensions) | Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value can be a sum of the values in the following table. |
| [snap_angles](/diagram/python-net/aspose.diagram/window/snap_angles) | Contains a collection of SnapAngle elements. |
| [dynamic_grid_enabled](/diagram/python-net/aspose.diagram/window/dynamic_grid_enabled) | Specifies whether the dynamic grid feature is enabled for a document or window. |
| [tab_splitter_pos](/diagram/python-net/aspose.diagram/window/tab_splitter_pos) | Specifies the width of the page tab control of a drawing window (as a fraction of the total width of the drawing window). |
| [id](/diagram/python-net/aspose.diagram/window/id) | The unique ID of the element within its parent element. |
| [window_type](/diagram/python-net/aspose.diagram/window/window_type) | An enumerated value that may be one of the following: Drawing, Sheet, Stencil, or Icon.A Window element of WindowType='Stencil' must appear after its parent drawing window (WindowType='Drawing') and before any other drawing window elements. |
| [window_state](/diagram/python-net/aspose.diagram/window/window_state) | This attribute can be a sum of the following values. |
| [document](/diagram/python-net/aspose.diagram/window/document) | File path of the document displayed in this window. This attribute is relevant for windows whose WindowType is specified as Stencil. |
| [window_left](/diagram/python-net/aspose.diagram/window/window_left) | Left coordinate of the window rectangle. |
| [window_top](/diagram/python-net/aspose.diagram/window/window_top) | Top coordinate of the window rectangle. |
| [window_width](/diagram/python-net/aspose.diagram/window/window_width) | Width of the window rectangle. |
| [window_height](/diagram/python-net/aspose.diagram/window/window_height) | Height of the window rectangle. |
| [master](/diagram/python-net/aspose.diagram/window/master) | Master ID if this window is displaying a master. |
| [container_type](/diagram/python-net/aspose.diagram/window/container_type) | May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or Sheet. |
| [container](/diagram/python-net/aspose.diagram/window/container) | ID of container: Page, Sheet, or Master. Only relevant and necessary if ContainerType is specified. |
| [sheet](/diagram/python-net/aspose.diagram/window/sheet) | ID of sheet in container. Relevant only when Container is specified as Sheet. |
| [read_only](/diagram/python-net/aspose.diagram/window/read_only) | Read-only flag if this stencil is not a document stencil. |
| [parent_window](/diagram/python-net/aspose.diagram/window/parent_window) | ID of window in which this stencil window is contained. Relevant only when WindowType is specified as Stencil. |
| [page](/diagram/python-net/aspose.diagram/window/page) | Page ID if this window is displaying a page. Relevant only when WindowType is specified as Drawing and ContainerType is specified as Page. |
| [view_scale](/diagram/python-net/aspose.diagram/window/view_scale) | Optional double. |
| [view_center_x](/diagram/python-net/aspose.diagram/window/view_center_x) | Optional double. |
| [view_center_y](/diagram/python-net/aspose.diagram/window/view_center_y) | Optional double. |


### See Also

* module [aspose.diagram](../)
