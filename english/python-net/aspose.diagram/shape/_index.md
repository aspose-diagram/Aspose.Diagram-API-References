---
title: Shape class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 2010
url: /python-net/aspose.diagram/shape/
is_root: false
---

## Shape class

Contains elements that define a shape in a Master, Page, or group shape element.



The Shape type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [Shape()](/diagram/python-net/aspose.diagram/shape/__init__/#) | Constructor. |


### Properties
| Property | Description |
| :- | :- |
| [id](/diagram/python-net/aspose.diagram/shape/id) | The unique ID of the element within its parent element. |
| [unique_id](/diagram/python-net/aspose.diagram/shape/unique_id) | A GUID (globally unique identifier) assigned to the shape. |
| [name](/diagram/python-net/aspose.diagram/shape/name) | The name of the element. |
| [name_u](/diagram/python-net/aspose.diagram/shape/name_u) | The universal name of the element. |
| [type](/diagram/python-net/aspose.diagram/shape/type) | The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. |
| [line_style](/diagram/python-net/aspose.diagram/shape/line_style) | StyleSheet from which this shape inherits line formatting |
| [fill_style](/diagram/python-net/aspose.diagram/shape/fill_style) | StyleSheet from which this shape inherits fill formatting. |
| [text_style](/diagram/python-net/aspose.diagram/shape/text_style) | StyleSheet from which this shape inherits text formatting. |
| [shapes](/diagram/python-net/aspose.diagram/shape/shapes) | Contains a collection of Shape elements. |
| [text](/diagram/python-net/aspose.diagram/shape/text) | Contains the text of a shape. |
| [x_form](/diagram/python-net/aspose.diagram/shape/x_form) | Contains elements specifying general positioning information about a shape. |
| [line](/diagram/python-net/aspose.diagram/shape/line) | Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine whether the line ends are formatted (for example, with an arrowhead), the size of line end formats, radius of the rounding circle applied to the line, and line cap style (round or square). |
| [fill](/diagram/python-net/aspose.diagram/shape/fill) | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color. |
| [inherit_chars](/diagram/python-net/aspose.diagram/shape/inherit_chars) | Contains the  char values for the shape inherit by the master shape. |
| [inherit_props](/diagram/python-net/aspose.diagram/shape/inherit_props) | Contains the  props for the shape inherit by the master shape. |
| [inherit_users](/diagram/python-net/aspose.diagram/shape/inherit_users) | Contains the  users for the shape inherit by the master shape. |
| [inherit_geoms](/diagram/python-net/aspose.diagram/shape/inherit_geoms) | Contains the  Geoms values for the shape inherit by the master shape. |
| [inherit_paras](/diagram/python-net/aspose.diagram/shape/inherit_paras) | Contains the paras for the shape inherit by the parent style and the master shape. |
| [inherit_text_block](/diagram/python-net/aspose.diagram/shape/inherit_text_block) | Contains the  textblock values for the shape inherit by the parent style and the master shape. |
| [inherit_line](/diagram/python-net/aspose.diagram/shape/inherit_line) | Contains the  line formatting values for the shape inherit by the parent style and the master shape. |
| [inherit_fill](/diagram/python-net/aspose.diagram/shape/inherit_fill) | Contains the  fill formatting values for the shape inherit by the parent style and the master shape. |
| [x_form_1d](/diagram/python-net/aspose.diagram/shape/x_form_1d) | Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only. |
| [event](/diagram/python-net/aspose.diagram/shape/event) | Contains elements that specify formulas that control shape events. |
| [layer_mem](/diagram/python-net/aspose.diagram/shape/layer_mem) | Contains the LayerMember element, which specifies each layer to which the shape is assigned. |
| [foreign](/diagram/python-net/aspose.diagram/shape/foreign) | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders. |
| [text_block](/diagram/python-net/aspose.diagram/shape/text_block) | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [text_x_form](/diagram/python-net/aspose.diagram/shape/text_x_form) | Contains elements that specify positioning information about a shape's text block. |
| [align](/diagram/python-net/aspose.diagram/shape/align) | Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. The Align element appears only for shapes that are glued to guides or guide points. |
| [protection](/diagram/python-net/aspose.diagram/shape/protection) | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances. It also does not protect against changes made in the ShapeSheet window. |
| [help](/diagram/python-net/aspose.diagram/shape/help) | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [misc](/diagram/python-net/aspose.diagram/shape/misc) | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [image](/diagram/python-net/aspose.diagram/shape/image) | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [group](/diagram/python-net/aspose.diagram/shape/group) | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [layout](/diagram/python-net/aspose.diagram/shape/layout) | Contains elements that control shape placement and connector routing settings. |
| [chars](/diagram/python-net/aspose.diagram/shape/chars) | Contains a collection of Char elements. |
| [paras](/diagram/python-net/aspose.diagram/shape/paras) | Contains a collection of Para elements. |
| [scratchs](/diagram/python-net/aspose.diagram/shape/scratchs) | Contains a collection of Scratch elements. |
| [connections](/diagram/python-net/aspose.diagram/shape/connections) | Contains a collection of Connection elements. |
| [connection_abc_ds](/diagram/python-net/aspose.diagram/shape/connection_abc_ds) | Contains a collection of ConnectionABCD elements. |
| [fields](/diagram/python-net/aspose.diagram/shape/fields) | Contains a collection of Field elements. |
| [controls](/diagram/python-net/aspose.diagram/shape/controls) | Contains a collection of Control elements. |
| [geoms](/diagram/python-net/aspose.diagram/shape/geoms) | Contains a collection of Geom elements. |
| [acts](/diagram/python-net/aspose.diagram/shape/acts) | Contains a collection of Act elements. |
| [users](/diagram/python-net/aspose.diagram/shape/users) | Contains a collection of User elements. |
| [props](/diagram/python-net/aspose.diagram/shape/props) | Contains a collection of Prop elements. |
| [hyperlinks](/diagram/python-net/aspose.diagram/shape/hyperlinks) | Contains a collection of Hyperlink elements. |
| [smart_tag_defs](/diagram/python-net/aspose.diagram/shape/smart_tag_defs) | Contains a collection of SmartTagDef elements. |
| [tabs_collection](/diagram/python-net/aspose.diagram/shape/tabs_collection) | Contains a collection of Tab elements. |
| [data1](/diagram/python-net/aspose.diagram/shape/data1) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [data2](/diagram/python-net/aspose.diagram/shape/data2) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [data3](/diagram/python-net/aspose.diagram/shape/data3) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [clipping_path](/diagram/python-net/aspose.diagram/shape/clipping_path) |  |
| [foreign_data](/diagram/python-net/aspose.diagram/shape/foreign_data) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data. |
| [master_shape](/diagram/python-net/aspose.diagram/shape/master_shape) | This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master. The attribute contains an ID that references the corresponding sub-shape in the master. |
| [master](/diagram/python-net/aspose.diagram/shape/master) | The Master from which the shape inherits its data. |
| [parent_shape](/diagram/python-net/aspose.diagram/shape/parent_shape) | Shape's parent. |
| [root_shape](/diagram/python-net/aspose.diagram/shape/root_shape) | Returns the top-level shape of an instance if this shape is part of a master instance. Read-only. |
| [diagram](/diagram/python-net/aspose.diagram/shape/diagram) | Root element of Visio objects hierarchy. |
| [page](/diagram/python-net/aspose.diagram/shape/page) | Root element of Visio objects hierarchy. |
| [one_d](/diagram/python-net/aspose.diagram/shape/one_d) | Determines whether the shape behaves as a one-dimensional (1-D) object. Read-only. |
| [two_d](/diagram/python-net/aspose.diagram/shape/two_d) | Determines whether the shape behaves as a two-dimensional (2-D) object. |
| [is_text_empty](/diagram/python-net/aspose.diagram/shape/is_text_empty) | Indicate the shape has text and the text is empty or not. |
| [control_data](/diagram/python-net/aspose.diagram/shape/control_data) | Gets the data of control. |
| [active_x_control](/diagram/python-net/aspose.diagram/shape/active_x_control) | Gets the ActiveX control. |
| [z_order_index](/diagram/python-net/aspose.diagram/shape/z_order_index) | Returns the index of a shape in the z-order except the guide shape. |
| [three_d_format](/diagram/python-net/aspose.diagram/shape/three_d_format) | Gets the ThreeDFormat. |


### Methods
| Method | Description |
| :- | :- |
| [to_pdf(file_name)](/diagram/python-net/aspose.diagram/shape/to_pdf/#str) | Saves the shape to a pdf file. |
| [to_pdf(stream)](/diagram/python-net/aspose.diagram/shape/to_pdf/#io.RawIOBase) | Creates the shape pdf and saves it to a stream. |
| [to_image(image_file, options)](/diagram/python-net/aspose.diagram/shape/to_image/#str-aspose.diagram.saving.ImageSaveOptions) | Creates the shape image and saves it to a file.<br/>The extension of the file name determines the format of the image. |
| [to_image(stream, options)](/diagram/python-net/aspose.diagram/shape/to_image/#io.RawIOBase-aspose.diagram.saving.ImageSaveOptions) | Creates the shape image and saves it to a stream in the specified format. |
| [to_html(file_name, options)](/diagram/python-net/aspose.diagram/shape/to_html/#str-aspose.diagram.saving.HTMLSaveOptions) | Creates the html and saves it to a file. |
| [to_html(stream, options)](/diagram/python-net/aspose.diagram/shape/to_html/#io.RawIOBase-aspose.diagram.saving.HTMLSaveOptions) | Creates the shape html and saves it to a stream in the specified format. |
| [get_connectors_type()](/diagram/python-net/aspose.diagram/shape/get_connectors_type/#) | Get Connectors type |
| [set_connectors_type(type)](/diagram/python-net/aspose.diagram/shape/set_connectors_type/#ConnectorsTypeValue) | Set Connectors type |
| [set_preset_theme_style_matrics(style_index, color_index)](/diagram/python-net/aspose.diagram/shape/set_preset_theme_style_matrics/#PresetStyleMatricsValue-PresetColorMatricsValue) | pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list |
| [copy(source)](/diagram/python-net/aspose.diagram/shape/copy/#Shape) |  |
| [bring_forward()](/diagram/python-net/aspose.diagram/shape/bring_forward/#) | Brings the shape forward one position in the z-order. |
| [send_backward()](/diagram/python-net/aspose.diagram/shape/send_backward/#) | Moves the shape back one position in the z-order. |
| [bring_to_front()](/diagram/python-net/aspose.diagram/shape/bring_to_front/#) | Brings the shape to the front of the z-order. |
| [send_to_back()](/diagram/python-net/aspose.diagram/shape/send_to_back/#) | Moves the shape to the back of the z-order. |
| [get_connector_rule()](/diagram/python-net/aspose.diagram/shape/get_connector_rule/#) | Returns a connectorRule that contains the shape id and connecton that are connected to the shape. |
| [connected_shapes(flag, category_filter)](/diagram/python-net/aspose.diagram/shape/connected_shapes/#ConnectedShapesFlags-str) |  |
| [is_in_group()](/diagram/python-net/aspose.diagram/shape/is_in_group/#) | Indicates whether this shape is in a group shape. |
| [is_contain(shape)](/diagram/python-net/aspose.diagram/shape/is_contain/#Shape) |  |
| [is_intersect(shape)](/diagram/python-net/aspose.diagram/shape/is_intersect/#Shape) |  |
| [is_connected(shape)](/diagram/python-net/aspose.diagram/shape/is_connected/#Shape) |  |
| [center_drawing()](/diagram/python-net/aspose.diagram/shape/center_drawing/#) | Center the shape with respect to the extent of the page |
| [is_glued(shape)](/diagram/python-net/aspose.diagram/shape/is_glued/#Shape) |  |
| [refresh_data()](/diagram/python-net/aspose.diagram/shape/refresh_data/#) | Refreshes shape's position including xform ,connection and geom when changing shape's text or other's . |
| [glued_shapes(flag, category_filter, other_shape)](/diagram/python-net/aspose.diagram/shape/glued_shapes/#GluedShapesFlags-str-Shape) |  |
| [depends_on_shapes()](/diagram/python-net/aspose.diagram/shape/depends_on_shapes/#) |  |
| [set_width(width)](/diagram/python-net/aspose.diagram/shape/set_width/#float) | Sets new width of shape. |
| [set_height(height)](/diagram/python-net/aspose.diagram/shape/set_height/#float) | Sets new height of shape. |
| [set_angle(angle)](/diagram/python-net/aspose.diagram/shape/set_angle/#float) | Sets new angle of shape.<br/>The angle's unit is radian. |
| [move_to(new_pin_x, new_pin_y)](/diagram/python-net/aspose.diagram/shape/move_to/#float-float) | Moves shape on new absolute position on the page. |
| [move(d_x, d_y)](/diagram/python-net/aspose.diagram/shape/move/#float-float) | Moves shape on the dX and dY inches from current position. |
| [get_display_text()](/diagram/python-net/aspose.diagram/shape/get_display_text/#) | Get the text displayed on the interface |
| [get_pure_text()](/diagram/python-net/aspose.diagram/shape/get_pure_text/#) | Get the text string |
| [ungroup()](/diagram/python-net/aspose.diagram/shape/ungroup/#) | Ungroup Shape |
| [replace_text(text, replace_text)](/diagram/python-net/aspose.diagram/shape/replace_text/#str-str) | Replace the text string of a shape . |
| [to_svg(image_file, options)](/diagram/python-net/aspose.diagram/shape/to_svg/#str-aspose.diagram.saving.SVGSaveOptions) | Saves the shape to a svg file. |


### See Also

* module [aspose.diagram](../)
