---
title: Shape
second_title: Aspose.Diagram for .NET API Reference
description: 
type: docs
weight: 3560
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
| [ActiveXControl](activexcontrol) { get; } | Gets the ActiveX control. |
| [Acts](acts) { get; } | Contains a collection of Act elements. |
| [Align](align) { get; } | Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. The Align element appears only for shapes that are glued to guides or guide points. |
| [Chars](chars) { get; } | Contains a collection of Char elements. |
| [ClippingPath](clippingpath) { get; set; } |  |
| [ConnectionABCDs](connectionabcds) { get; } | Contains a collection of ConnectionABCD elements. |
| [Connections](connections) { get; } | Contains a collection of Connection elements. |
| [ControlData](controldata) { get; } | Gets the data of control. |
| [Controls](controls) { get; } | Contains a collection of Control elements. |
| [Data1](data1) { get; set; } | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Data2](data2) { get; set; } | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Data3](data3) { get; set; } | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Del](del) { get; set; } | A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. |
| [Diagram](diagram) { get; set; } | Root element of Visio objects hierarchy. |
| [Event](event) { get; set; } | Contains elements that specify formulas that control shape events. |
| [Fields](fields) { get; } | Contains a collection of Field elements. |
| [Fill](fill) { get; } | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color. |
| [FillStyle](fillstyle) { get; set; } | StyleSheet from which this shape inherits fill formatting. |
| [Foreign](foreign) { get; } | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders. |
| [ForeignData](foreigndata) { get; } | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data. |
| [Geoms](geoms) { get; } | Contains a collection of Geom elements. |
| [Group](group) { get; } | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [Help](help) { get; } | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Hyperlinks](hyperlinks) { get; } | Contains a collection of Hyperlink elements. |
| [ID](id) { get; set; } | The unique ID of the element within its parent element. |
| [Image](image) { get; } | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [InheritChars](inheritchars) { get; } | Contains the char values for the shape inherit by the master shape. |
| [InheritFill](inheritfill) { get; } | Contains the fill formatting values for the shape inherit by the parent style and the master shape. |
| [InheritLine](inheritline) { get; } | Contains the line formatting values for the shape inherit by the parent style and the master shape. |
| [InheritParas](inheritparas) { get; } | Contains the paras for the shape inherit by the parent style and the master shape. |
| [InheritProps](inheritprops) { get; } | Contains the props for the shape inherit by the master shape. |
| [InheritTextBlock](inherittextblock) { get; } | Contains the textblock values for the shape inherit by the parent style and the master shape. |
| [InheritUsers](inheritusers) { get; } | Contains the users for the shape inherit by the master shape. |
| [IsTextEmpty](istextempty) { get; } | Indicate the shape has text and the text is empty or not. |
| [LayerMem](layermem) { get; } | Contains the LayerMember element, which specifies each layer to which the shape is assigned. |
| [Layout](layout) { get; } | Contains elements that control shape placement and connector routing settings. |
| [Line](line) { get; } | Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine whether the line ends are formatted (for example, with an arrowhead), the size of line end formats, radius of the rounding circle applied to the line, and line cap style (round or square). |
| [LineStyle](linestyle) { get; set; } | StyleSheet from which this shape inherits line formatting |
| [Master](master) { get; set; } | The Master from which the shape inherits its data. |
| [MasterShape](mastershape) { get; set; } | This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master. The attribute contains an ID that references the corresponding sub-shape in the master. |
| [Misc](misc) { get; } | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Name](name) { get; set; } | The name of the element. |
| [NameU](nameu) { get; set; } | The universal name of the element. |
| [OneD](oned) { get; } | Determines whether the shape behaves as a one-dimensional (1-D) object. Read-only. |
| [Page](page) { get; set; } | Root element of Visio objects hierarchy. |
| [Paras](paras) { get; } | Contains a collection of Para elements. |
| [ParentShape](parentshape) { get; set; } | Shape's parent. |
| [PresetTheme](presettheme) { set; } | Apply a preset theme to this shape |
| [PresetThemeQuickStyle](presetthemequickstyle) { set; } | Apply a preset theme variant quickstyle to this shape |
| [PresetThemeVariant](presetthemevariant) { set; } | Apply a preset theme variant to this shape |
| [Props](props) { get; set; } | Contains a collection of Prop elements. |
| [Protection](protection) { get; } | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances. It also does not protect against changes made in the ShapeSheet window. |
| [Scratchs](scratchs) { get; } | Contains a collection of Scratch elements. |
| [Shapes](shapes) { get; } | Contains a collection of Shape elements. |
| [SmartTagDefs](smarttagdefs) { get; } | Contains a collection of SmartTagDef elements. |
| [TabsCollection](tabscollection) { get; } | Contains a collection of Tab elements. |
| [Text](text) { get; set; } | Contains the text of a shape. |
| [TextBlock](textblock) { get; } | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [TextStyle](textstyle) { get; set; } | StyleSheet from which this shape inherits text formatting. |
| [TextXForm](textxform) { get; } | Contains elements that specify positioning information about a shape's text block. |
| [ThreeDFormat](threedformat) { get; } | Gets the ThreeDFormat. |
| [TwoD](twod) { get; set; } | Determines whether the shape behaves as a two-dimensional (2-D) object. |
| [Type](type) { get; set; } | The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. |
| [UniqueID](uniqueid) { get; set; } | A GUID (globally unique identifier) assigned to the shape. |
| [Users](users) { get; } | Contains a collection of User elements. |
| [XForm](xform) { get; set; } | Contains elements specifying general positioning information about a shape. |
| [XForm1D](xform1d) { get; set; } | Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only. |
| [ZOrderIndex](zorderindex) { get; } | Returns the index of a shape in the z-order except the guide shape. |

## Methods

| Name | Description |
| --- | --- |
| [BringForward](bringforward)() | Brings the shape forward one position in the z-order. |
| [BringToFront](bringtofront)() | Brings the shape to the front of the z-order. |
| [CenterDrawing](centerdrawing)() | Center the shape with respect to the extent of the page |
| [ConnectedShapes](connectedshapes)(ConnectedShapesFlags, string) | Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape. |
| [Copy](copy)(Shape) |  |
| [DependsOnShapes](dependsonshapes)() | Returns an array that contains the identifiers of the shapes that are depends on a shape. |
| [GetConnectorsType](getconnectorstype)() | Get Connectors type |
| [GetPureText](getpuretext)() | Get the text string of a shape. |
| [GluedShapes](gluedshapes)(GluedShapesFlags, string, Shape) | Returns an array that contains the identifiers of the shapes that are glued to a shape. |
| [IsConnected](isconnected)(Shape) | Indicates whether this two shapes are connected. |
| [IsContain](iscontain)(Shape) | Indicates whether this shape is contain another shape. |
| [IsGlued](isglued)(Shape) | Indicates whether this two shapes are glued. |
| [IsInGroup](isingroup)() | Indicates whether this shape is in a group shape. |
| [IsIntersect](isintersect)(Shape) | Indicates whether this shape is intersect another shape. |
| [Move](move)(double, double) | Moves shape on the dX and dY inches from current position. |
| [MoveTo](moveto)(double, double) | Moves shape on new absolute position on the page. |
| [RefreshData](refreshdata)() | Refreshes shape's position including xform ,connection and geom when changing shape's text or other's . |
| [ReplaceText](replacetext)(string, string) | Replace the text string of a shape . |
| [SendBackward](sendbackward)() | Moves the shape back one position in the z-order. |
| [SendToBack](sendtoback)() | Moves the shape to the back of the z-order. |
| [SetAngle](setangle)(double) | Sets new angle of shape. The angle's unit is radian. |
| [SetConnectorsType](setconnectorstype)(ConnectorsTypeValue) | Set Connectors type |
| [SetHeight](setheight)(double) | Sets new height of shape. |
| [SetPresetThemeStyleMatrics](setpresetthemestylematrics)(PresetStyleMatricsValue, PresetColorMatricsValue) | pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list |
| [SetWidth](setwidth)(double) | Sets new width of shape. |
| [ToHTML](tohtml)(Stream, HTMLSaveOptions) | Creates the shape html and saves it to a stream in the specified format. |
| [ToHTML](tohtml)(string, HTMLSaveOptions) | Creates the html and saves it to a file. |
| [ToImage](toimage)(Stream, ImageSaveOptions) | Creates the shape image and saves it to a stream in the specified format. |
| [ToImage](toimage)(string, ImageSaveOptions) | Creates the shape image and saves it to a file. The extension of the file name determines the format of the image. |
| [ToPdf](topdf)(Stream) | Creates the shape pdf and saves it to a stream. |
| [ToPdf](topdf)(string) | Saves the shape to a pdf file. |
| [ToSvg](tosvg)(string, SVGSaveOptions) | Saves the shape to a svg file. |

### See Also

* namespace [Aspose.Diagram](../../aspose.diagram)
* assembly [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
