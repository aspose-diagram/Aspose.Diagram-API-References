---
title: Page class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 1510
url: /python-net/aspose.diagram/page/
is_root: false
---

## Page class

Contains elements that define a page in the document.



The Page type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [Page()](/diagram/python-net/aspose.diagram/page/__init__/#) | Constructor. |
| [Page(id)](/diagram/python-net/aspose.diagram/page/__init__/#int) | Constructor. |


### Properties
| Property | Description |
| :- | :- |
| [pages](/diagram/python-net/aspose.diagram/page/pages) | Page collection. |
| [shapes](/diagram/python-net/aspose.diagram/page/shapes) | Shape collection. |
| [page_sheet](/diagram/python-net/aspose.diagram/page/page_sheet) | Contains elements that define the page sheet for a Page or Master element. |
| [connects](/diagram/python-net/aspose.diagram/page/connects) | Contains a Connect element for each connection between two shapes in a drawing. |
| [id](/diagram/python-net/aspose.diagram/page/id) | The unique ID of the element within its parent element. |
| [name](/diagram/python-net/aspose.diagram/page/name) | The name of the element. |
| [name_u](/diagram/python-net/aspose.diagram/page/name_u) | The universal name of the element. |
| [background](/diagram/python-net/aspose.diagram/page/background) | A flag indicating if the page is a background page. |
| [back_page](/diagram/python-net/aspose.diagram/page/back_page) | The page's background page. |
| [view_scale](/diagram/python-net/aspose.diagram/page/view_scale) | The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150%, and so on. |
| [view_center_x](/diagram/python-net/aspose.diagram/page/view_center_x) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially. |
| [view_center_y](/diagram/python-net/aspose.diagram/page/view_center_y) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially. |
| [reviewer_id](/diagram/python-net/aspose.diagram/page/reviewer_id) | The ID of the reviewer associated with the markup overlay. |
| [associated_page](/diagram/python-net/aspose.diagram/page/associated_page) | The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing. |


### Methods
| Method | Description |
| :- | :- |
| [add_shape(pin_x, pin_y, master_name)](/diagram/python-net/aspose.diagram/page/add_shape/#float-float-str) | Adds shape created by master on page with defined PinX and PinY. |
| [add_shape(pin_x, pin_y, width, height, master_name)](/diagram/python-net/aspose.diagram/page/add_shape/#float-float-float-float-str) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [add_shape(pin_x, pin_y, width, height, image_stream, object_data_stream)](/diagram/python-net/aspose.diagram/page/add_shape/#float-float-float-float-io.RawIOBase-io.RawIOBase) |  |
| [add_shape(pin_x, pin_y, width, height, stream)](/diagram/python-net/aspose.diagram/page/add_shape/#float-float-float-float-io.RawIOBase) |  |
| [add_shape(new_shape, master_name)](/diagram/python-net/aspose.diagram/page/add_shape/#Shape-str) | Adds shape created by master to specific page. |
| [connect_shapes_via_connector(shape_from, place_from, shape_to, place_to, connector)](/diagram/python-net/aspose.diagram/page/connect_shapes_via_connector/#Shape-aspose.diagram.manipulation.ConnectionPointPlace-Shape-aspose.diagram.manipulation.ConnectionPointPlace-Shape) | Connect shapes via connector. |
| [connect_shapes_via_connector(shape_from_id, place_from, shape_to_id, place_to, connector_id)](/diagram/python-net/aspose.diagram/page/connect_shapes_via_connector/#int-aspose.diagram.manipulation.ConnectionPointPlace-int-aspose.diagram.manipulation.ConnectionPointPlace-int) | Connect shapes via connector. |
| [connect_shapes_via_connector(shape_from_id, from_connection_name, shape_to_id, to_connection_name, connector_id)](/diagram/python-net/aspose.diagram/page/connect_shapes_via_connector/#int-str-int-str-int) | Connect shapes via connector. |
| [connect_shapes_via_connector_index(shape_from_id, from_index, shape_to_id, to_index, connector_id)](/diagram/python-net/aspose.diagram/page/connect_shapes_via_connector_index/#int-int-int-int-int) | Connect shapes via connector index. |
| [connect_shapes_via_connector_index(shape_from, from_index, shape_to, to_index, connector)](/diagram/python-net/aspose.diagram/page/connect_shapes_via_connector_index/#Shape-int-Shape-int-Shape) | Connect shapes via connector index. |
| [glue_shapes(shape_from, place_to, shape_to)](/diagram/python-net/aspose.diagram/page/glue_shapes/#Shape-aspose.diagram.manipulation.ConnectionPointPlace-Shape) | Glue shapes. |
| [glue_shapes(shape_from_id, place_to, shape_to_id)](/diagram/python-net/aspose.diagram/page/glue_shapes/#int-aspose.diagram.manipulation.ConnectionPointPlace-int) | Glue shapes |
| [glue_shapes_in_container(shape_from_id, shape_to_begin_connection_name, shape_to_end_connection_name, shape_to_id)](/diagram/python-net/aspose.diagram/page/glue_shapes_in_container/#int-str-str-int) | Glue shapes in container using connection name |
| [glue_shapes_in_container(shape_from_id, shape_to_begin_connection_index, shape_to_end_connection_index, shape_to_id)](/diagram/python-net/aspose.diagram/page/glue_shapes_in_container/#int-int-int-int) | Glue shapes in container |
| [add_comment(shape_id, comment)](/diagram/python-net/aspose.diagram/page/add_comment/#int-str) | Adds comment to a shape with shape's id. |
| [add_comment(shape, comment)](/diagram/python-net/aspose.diagram/page/add_comment/#Shape-str) | Adds comment to a shape. |
| [add_comment(pin_x, pin_y, comment)](/diagram/python-net/aspose.diagram/page/add_comment/#float-float-str) | Adds comment with defined PinX and PinY. |
| [add_text(pin_x, pin_y, width, height, text, font_name, font_color, size)](/diagram/python-net/aspose.diagram/page/add_text/#float-float-float-float-str-str-str-float) | Adds Text with defined PinX and PinY. |
| [add_text(pin_x, pin_y, width, height, text)](/diagram/python-net/aspose.diagram/page/add_text/#float-float-float-float-str) | Adds Text with defined PinX and PinY. |
| [draw_line(begin_x, begin_y, end_x, end_y)](/diagram/python-net/aspose.diagram/page/draw_line/#float-float-float-float) | The process of drawing a single line. |
| [draw_line(pin_x, pin_y, width, height, points)](/diagram/python-net/aspose.diagram/page/draw_line/#float-float-float-float-aspose.pydrawing.PointF[]) | The process of drawing line. |
| [center_drawing()](/diagram/python-net/aspose.diagram/page/center_drawing/#) | Centers a page's shapes with respect to the extent of the page.<br/>Centering shapes does not change their position relative to each other. |
| [copy(source)](/diagram/python-net/aspose.diagram/page/copy/#Page) |  |
| [apply_style(text_style, line_style, fill_style)](/diagram/python-net/aspose.diagram/page/apply_style/#int-int-int) | Applies style for full page. |
| [move_to(index)](/diagram/python-net/aspose.diagram/page/move_to/#int) | Moves the page to another location in the pages. |
| [add_active_x_control(type, pin_x, pin_y, width, height)](/diagram/python-net/aspose.diagram/page/add_active_x_control/#aspose.diagram.activexcontrols.ControlType-float-float-float-float) | Creates an Activex Control. |
| [layout(options)](/diagram/python-net/aspose.diagram/page/layout/#aspose.diagram.autolayout.LayoutOptions) | Lays out the shapes and/or reroutes the connectors for the page. |
| [glue_shape_to_connector_begin_x(shape_from_id, connection_name, connector_id)](/diagram/python-net/aspose.diagram/page/glue_shape_to_connector_begin_x/#int-str-int) | Glue shape to Connector's BeginX |
| [glue_shape_to_connector_end_x(shape_to_id, connection_name, connector_id)](/diagram/python-net/aspose.diagram/page/glue_shape_to_connector_end_x/#int-str-int) | Glue shape to Connector's EndX |
| [glue_shapes_in_container_by_id(shape_from_id, shape_to_begin_connection_id, shape_to_end_connection_id, shape_to_id)](/diagram/python-net/aspose.diagram/page/glue_shapes_in_container_by_id/#int-int-int-int) | Glue shapes by connection id in container |
| [bring_forward(shape_id)](/diagram/python-net/aspose.diagram/page/bring_forward/#int) | Brings a shape,defined by ID, forward one position in the z-order. |
| [send_backward(shape_id)](/diagram/python-net/aspose.diagram/page/send_backward/#int) | Moves a shape,defined by ID, back one position in the z-order. |
| [bring_to_front(shape_id)](/diagram/python-net/aspose.diagram/page/bring_to_front/#int) | Brings a shape,defined by ID, to the front of the z-order. |
| [send_to_back(shape_id)](/diagram/python-net/aspose.diagram/page/send_to_back/#int) | Moves a shape,defined by ID, to the back of the z-order. |
| [auto_space_shapes(shapes, options)](/diagram/python-net/aspose.diagram/page/auto_space_shapes/#ShapeCollection-AutoSpaceOptions) | Auto space shapes |
| [draw_rectangle(pin_x, pin_y, width, height)](/diagram/python-net/aspose.diagram/page/draw_rectangle/#float-float-float-float) | The process of drawing rectangle. |
| [draw_ellipse(pin_x, pin_y, width, height)](/diagram/python-net/aspose.diagram/page/draw_ellipse/#float-float-float-float) | The process of drawing Ellipse. |
| [draw_polyline(pin_x, pin_y, width, height, points)](/diagram/python-net/aspose.diagram/page/draw_polyline/#float-float-float-float-aspose.pydrawing.PointF[]) | The process of drawing polyline. |
| [draw_bezier(pin_x, pin_y, width, height, points)](/diagram/python-net/aspose.diagram/page/draw_bezier/#float-float-float-float-aspose.pydrawing.PointF[]) | The process of drawing bezier.<br/>The length of points should be equal or greater than 3. |
| [draw_spline(pin_x, pin_y, width, height, points)](/diagram/python-net/aspose.diagram/page/draw_spline/#float-float-float-float-aspose.pydrawing.PointF[]) | The process of drawing spline. |


### See Also

* module [aspose.diagram](../)
