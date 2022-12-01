---
title: Shape
second_title: Aspose.Diagram for .NET API Reference
description: Contains elements that define a shape in a Master Page or group shape element.
type: docs
weight: 3570
url: /net/aspose.diagram/shape/
---
## Shape class

Contains elements that define a shape in a Master, Page, or group shape element.

```csharp
public class Shape
```

## Constructors

| Name | Description |
| --- | --- |
| [Shape](shape)() | Constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ActiveXControl](../../aspose.diagram/shape/activexcontrol) { get; } | Gets the ActiveX control. |
| [Acts](../../aspose.diagram/shape/acts) { get; } | Contains a collection of Act elements. |
| [Align](../../aspose.diagram/shape/align) { get; } | Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. The Align element appears only for shapes that are glued to guides or guide points. |
| [Chars](../../aspose.diagram/shape/chars) { get; } | Contains a collection of Char elements. |
| [ClippingPath](../../aspose.diagram/shape/clippingpath) { get; set; } |  |
| [ConnectionABCDs](../../aspose.diagram/shape/connectionabcds) { get; } | Contains a collection of ConnectionABCD elements. |
| [Connections](../../aspose.diagram/shape/connections) { get; } | Contains a collection of Connection elements. |
| [ControlData](../../aspose.diagram/shape/controldata) { get; } | Gets the data of control. |
| [Controls](../../aspose.diagram/shape/controls) { get; } | Contains a collection of Control elements. |
| [Data1](../../aspose.diagram/shape/data1) { get; set; } | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Data2](../../aspose.diagram/shape/data2) { get; set; } | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Data3](../../aspose.diagram/shape/data3) { get; set; } | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Del](../../aspose.diagram/shape/del) { get; set; } | A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. |
| [Diagram](../../aspose.diagram/shape/diagram) { get; set; } | Root element of Visio objects hierarchy. |
| [Event](../../aspose.diagram/shape/event) { get; set; } | Contains elements that specify formulas that control shape events. |
| [Fields](../../aspose.diagram/shape/fields) { get; } | Contains a collection of Field elements. |
| [Fill](../../aspose.diagram/shape/fill) { get; } | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color. |
| [FillStyle](../../aspose.diagram/shape/fillstyle) { get; set; } | StyleSheet from which this shape inherits fill formatting. |
| [Foreign](../../aspose.diagram/shape/foreign) { get; } | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders. |
| [ForeignData](../../aspose.diagram/shape/foreigndata) { get; } | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data. |
| [Geoms](../../aspose.diagram/shape/geoms) { get; } | Contains a collection of Geom elements. |
| [Group](../../aspose.diagram/shape/group) { get; } | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [Help](../../aspose.diagram/shape/help) { get; } | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Hyperlinks](../../aspose.diagram/shape/hyperlinks) { get; } | Contains a collection of Hyperlink elements. |
| [ID](../../aspose.diagram/shape/id) { get; set; } | The unique ID of the element within its parent element. |
| [Image](../../aspose.diagram/shape/image) { get; } | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [InheritChars](../../aspose.diagram/shape/inheritchars) { get; } | Contains the char values for the shape inherit by the master shape. |
| [InheritFill](../../aspose.diagram/shape/inheritfill) { get; } | Contains the fill formatting values for the shape inherit by the parent style and the master shape. |
| [InheritGeoms](../../aspose.diagram/shape/inheritgeoms) { get; } | Contains the Geoms values for the shape inherit by the master shape. |
| [InheritLine](../../aspose.diagram/shape/inheritline) { get; } | Contains the line formatting values for the shape inherit by the parent style and the master shape. |
| [InheritParas](../../aspose.diagram/shape/inheritparas) { get; } | Contains the paras for the shape inherit by the parent style and the master shape. |
| [InheritProps](../../aspose.diagram/shape/inheritprops) { get; } | Contains the props for the shape inherit by the master shape. |
| [InheritTextBlock](../../aspose.diagram/shape/inherittextblock) { get; } | Contains the textblock values for the shape inherit by the parent style and the master shape. |
| [InheritUsers](../../aspose.diagram/shape/inheritusers) { get; } | Contains the users for the shape inherit by the master shape. |
| [IsTextEmpty](../../aspose.diagram/shape/istextempty) { get; } | Indicate the shape has text and the text is empty or not. |
| [LayerMem](../../aspose.diagram/shape/layermem) { get; } | Contains the LayerMember element, which specifies each layer to which the shape is assigned. |
| [Layout](../../aspose.diagram/shape/layout) { get; } | Contains elements that control shape placement and connector routing settings. |
| [Line](../../aspose.diagram/shape/line) { get; } | Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine whether the line ends are formatted (for example, with an arrowhead), the size of line end formats, radius of the rounding circle applied to the line, and line cap style (round or square). |
| [LineStyle](../../aspose.diagram/shape/linestyle) { get; set; } | StyleSheet from which this shape inherits line formatting |
| [Master](../../aspose.diagram/shape/master) { get; set; } | The Master from which the shape inherits its data. |
| [MasterShape](../../aspose.diagram/shape/mastershape) { get; set; } | This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master. The attribute contains an ID that references the corresponding sub-shape in the master. |
| [Misc](../../aspose.diagram/shape/misc) { get; } | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Name](../../aspose.diagram/shape/name) { get; set; } | The name of the element. |
| [NameU](../../aspose.diagram/shape/nameu) { get; set; } | The universal name of the element. |
| [OneD](../../aspose.diagram/shape/oned) { get; } | Determines whether the shape behaves as a one-dimensional (1-D) object. Read-only. |
| [Page](../../aspose.diagram/shape/page) { get; set; } | Root element of Visio objects hierarchy. |
| [Paras](../../aspose.diagram/shape/paras) { get; } | Contains a collection of Para elements. |
| [ParentShape](../../aspose.diagram/shape/parentshape) { get; set; } | Shape's parent. |
| [PresetTheme](../../aspose.diagram/shape/presettheme) { set; } | Apply a preset theme to this shape |
| [PresetThemeQuickStyle](../../aspose.diagram/shape/presetthemequickstyle) { set; } | Apply a preset theme variant quickstyle to this shape |
| [PresetThemeVariant](../../aspose.diagram/shape/presetthemevariant) { set; } | Apply a preset theme variant to this shape |
| [Props](../../aspose.diagram/shape/props) { get; set; } | Contains a collection of Prop elements. |
| [Protection](../../aspose.diagram/shape/protection) { get; } | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances. It also does not protect against changes made in the ShapeSheet window. |
| [RootShape](../../aspose.diagram/shape/rootshape) { get; } | Returns the top-level shape of an instance if this shape is part of a master instance. Read-only. |
| [Scratchs](../../aspose.diagram/shape/scratchs) { get; } | Contains a collection of Scratch elements. |
| [Shapes](../../aspose.diagram/shape/shapes) { get; } | Contains a collection of Shape elements. |
| [SmartTagDefs](../../aspose.diagram/shape/smarttagdefs) { get; } | Contains a collection of SmartTagDef elements. |
| [TabsCollection](../../aspose.diagram/shape/tabscollection) { get; } | Contains a collection of Tab elements. |
| [Text](../../aspose.diagram/shape/text) { get; set; } | Contains the text of a shape. |
| [TextBlock](../../aspose.diagram/shape/textblock) { get; } | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [TextStyle](../../aspose.diagram/shape/textstyle) { get; set; } | StyleSheet from which this shape inherits text formatting. |
| [TextXForm](../../aspose.diagram/shape/textxform) { get; } | Contains elements that specify positioning information about a shape's text block. |
| [ThreeDFormat](../../aspose.diagram/shape/threedformat) { get; } | Gets the ThreeDFormat. |
| [TwoD](../../aspose.diagram/shape/twod) { get; set; } | Determines whether the shape behaves as a two-dimensional (2-D) object. |
| [Type](../../aspose.diagram/shape/type) { get; set; } | The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. |
| [UniqueID](../../aspose.diagram/shape/uniqueid) { get; set; } | A GUID (globally unique identifier) assigned to the shape. |
| [Users](../../aspose.diagram/shape/users) { get; } | Contains a collection of User elements. |
| [XForm](../../aspose.diagram/shape/xform) { get; set; } | Contains elements specifying general positioning information about a shape. |
| [XForm1D](../../aspose.diagram/shape/xform1d) { get; set; } | Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only. |
| [ZOrderIndex](../../aspose.diagram/shape/zorderindex) { get; } | Returns the index of a shape in the z-order except the guide shape. |

## Methods

| Name | Description |
| --- | --- |
| [BringForward](../../aspose.diagram/shape/bringforward)() | Brings the shape forward one position in the z-order. |
| [BringToFront](../../aspose.diagram/shape/bringtofront)() | Brings the shape to the front of the z-order. |
| [CenterDrawing](../../aspose.diagram/shape/centerdrawing)() | Center the shape with respect to the extent of the page |
| [ConnectedShapes](../../aspose.diagram/shape/connectedshapes)(ConnectedShapesFlags, string) | Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape. |
| [Copy](../../aspose.diagram/shape/copy)(Shape) |  |
| [DependsOnShapes](../../aspose.diagram/shape/dependsonshapes)() | Returns an array that contains the identifiers of the shapes that are depends on a shape. |
| [GetConnectorRule](../../aspose.diagram/shape/getconnectorrule)() | Returns a connectorRule that contains the shape id and connecton that are connected to the shape. |
| [GetConnectorsType](../../aspose.diagram/shape/getconnectorstype)() | Get Connectors type |
| [GetDisplayText](../../aspose.diagram/shape/getdisplaytext)() | Get the text displayed on the interface |
| [GetPureText](../../aspose.diagram/shape/getpuretext)() | Get the text string |
| [GluedShapes](../../aspose.diagram/shape/gluedshapes)(GluedShapesFlags, string, Shape) | Returns an array that contains the identifiers of the shapes that are glued to a shape. |
| [IsConnected](../../aspose.diagram/shape/isconnected)(Shape) | Indicates whether this two shapes are connected. |
| [IsContain](../../aspose.diagram/shape/iscontain)(Shape) | Indicates whether this shape is contain another shape. |
| [IsGlued](../../aspose.diagram/shape/isglued)(Shape) | Indicates whether this two shapes are glued. |
| [IsInGroup](../../aspose.diagram/shape/isingroup)() | Indicates whether this shape is in a group shape. |
| [IsIntersect](../../aspose.diagram/shape/isintersect)(Shape) | Indicates whether this shape is intersect another shape. |
| [Move](../../aspose.diagram/shape/move)(double, double) | Moves shape on the dX and dY inches from current position. |
| [MoveTo](../../aspose.diagram/shape/moveto)(double, double) | Moves shape on new absolute position on the page. |
| [RefreshData](../../aspose.diagram/shape/refreshdata)() | Refreshes shape's position including xform ,connection and geom when changing shape's text or other's . |
| [ReplaceText](../../aspose.diagram/shape/replacetext)(string, string) | Replace the text string of a shape . |
| [SendBackward](../../aspose.diagram/shape/sendbackward)() | Moves the shape back one position in the z-order. |
| [SendToBack](../../aspose.diagram/shape/sendtoback)() | Moves the shape to the back of the z-order. |
| [SetAngle](../../aspose.diagram/shape/setangle)(double) | Sets new angle of shape. The angle's unit is radian. |
| [SetConnectorsType](../../aspose.diagram/shape/setconnectorstype)(ConnectorsTypeValue) | Set Connectors type |
| [SetHeight](../../aspose.diagram/shape/setheight)(double) | Sets new height of shape. |
| [SetPresetThemeStyleMatrics](../../aspose.diagram/shape/setpresetthemestylematrics)(PresetStyleMatricsValue, PresetColorMatricsValue) | pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list |
| [SetWidth](../../aspose.diagram/shape/setwidth)(double) | Sets new width of shape. |
| [ToHTML](../../aspose.diagram/shape/tohtml#tohtml)(Stream, HTMLSaveOptions) | Creates the shape html and saves it to a stream in the specified format. |
| [ToHTML](../../aspose.diagram/shape/tohtml#tohtml_1)(string, HTMLSaveOptions) | Creates the html and saves it to a file. |
| [ToImage](../../aspose.diagram/shape/toimage#toimage)(Stream, ImageSaveOptions) | Creates the shape image and saves it to a stream in the specified format. |
| [ToImage](../../aspose.diagram/shape/toimage#toimage_1)(string, ImageSaveOptions) | Creates the shape image and saves it to a file. The extension of the file name determines the format of the image. |
| [ToPdf](../../aspose.diagram/shape/topdf#topdf)(Stream) | Creates the shape pdf and saves it to a stream. |
| [ToPdf](../../aspose.diagram/shape/topdf#topdf_1)(string) | Saves the shape to a pdf file. |
| [ToSvg](../../aspose.diagram/shape/tosvg)(string, SVGSaveOptions) | Saves the shape to a svg file. |

### See Also

* namespace [Aspose.Diagram](../../aspose.diagram)
* assembly [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
