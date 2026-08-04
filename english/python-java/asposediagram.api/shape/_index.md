---
title: "Shape Class"
linktitle: "Shape"
articleTitle: "Shape"
second_title: "Aspose.Diagram for Python via Java"
description: "Contains elements that define a shape in a Master, Page, or group shape element."
type: docs
weight: 3030
url: /python-java/asposediagram.api/shape/
---

## Shape class

Contains elements that define a shape in a Master, Page, or group shape element.

```python
Shape()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ID](./id/) | long | The unique ID of the element within its parent element. |
| [Del](./del/) | int | A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. Th |
| [UniqueID](./uniqueid/) | UUID | A GUID (globally unique identifier) assigned to the shape. |
| [Name](./name/) | String | The name of the element. |
| [NameU](./nameu/) | String | The universal name of the element. |
| [Type](./type/) | int | The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. The value of the property i |
| [LineStyle](./linestyle/) | StyleSheet | StyleSheet from which this shape inherits line formatting |
| [FillStyle](./fillstyle/) | StyleSheet | StyleSheet from which this shape inherits fill formatting. |
| [TextStyle](./textstyle/) | StyleSheet | StyleSheet from which this shape inherits text formatting. |
| [Shapes](./shapes/) | ShapeCollection | Contains a collection of Shape elements. |
| [Text](./text/) | Text | Contains the text of a shape. |
| [XForm](./xform/) | XForm | Contains elements specifying general positioning information about a shape. |
| [Line](./line/) | Line | Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine |
| [Fill](./fill/) | Fill | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground col |
| [HasThemeColor](./hasthemecolor/) | boolean | Gets whether the shape has theme color. |
| [InheritChars](./inheritchars/) | CharCollection | Contains the char values for the shape inherit by the master shape. |
| [InheritProps](./inheritprops/) | PropCollection | Contains the props for the shape inherit by the master shape. |
| [InheritFields](./inheritfields/) | FieldCollection | Contains the fields for the shape inherit by the master shape. |
| [InheritActs](./inheritacts/) | ActCollection | Contains the actions for the shape inherit by the master shape. |
| [InheritHyperlinks](./inherithyperlinks/) | HyperlinkCollection | Contains the Hyperlinks for the shape inherit by the master shape. |
| [InheritXForm](./inheritxform/) | XForm |  |
| [InheritXForm1D](./inheritxform1d/) | XForm1D |  |
| [InheritMisc](./inheritmisc/) | Misc | Contains the Misc for the shape inherit by the master shape. |
| [InheritProtection](./inheritprotection/) | Protection | Contains the Protection for the shape inherit by the master shape. |
| [InheritEvent](./inheritevent/) | Event | Contains the Event for the shape inherit by the master shape. |
| [InheritLayerMem](./inheritlayermem/) | LayerMem | Contains the LayerMem for the shape inherit by the master shape. |
| [InheritHelp](./inherithelp/) | Help | Contains the Help for the shape inherit by the master shape. |
| [InheritLayout](./inheritlayout/) | Layout | Contains the Layout for the shape inherit by the master shape. |
| [InheritControls](./inheritcontrols/) | ControlCollection | Contains the controls for the shape inherit by the master shape. |
| [InheritConnections](./inheritconnections/) | ConnectionCollection | Contains the connections for the shape inherit by the master shape. |
| [InheritScratchs](./inheritscratchs/) | ScratchCollection | Contains the scratchs for the shape inherit by the master shape. |
| [InheritGroup](./inheritgroup/) | Group |  |
| [InheritUsers](./inheritusers/) | UserCollection | Contains the users for the shape inherit by the master shape. |
| [InheritTextXForm](./inherittextxform/) | TextXForm | Contains the textxform values for the shape inherit by the parent style and the master shape. |
| [InheritGeoms](./inheritgeoms/) | GeomCollection | Contains the Geoms values for the shape inherit by the master shape. |
| [InheritParas](./inheritparas/) | ParaCollection | Contains the paras for the shape inherit by the parent style and the master shape. |
| [InheritTabs](./inherittabs/) | TabsCollection | Contains the tabs for the shape inherit by the parent style and the master shape. |
| [InheritTextBlock](./inherittextblock/) | TextBlock | Contains the textblock values for the shape inherit by the parent style and the master shape. |
| [InheritLine](./inheritline/) | Line | Contains the line formatting values for the shape inherit by the parent style and the master shape. |
| [InheritFill](./inheritfill/) | Fill | Contains the fill formatting values for the shape inherit by the parent style and the master shape. |
| [XForm1D](./xform1d/) | XForm1D | Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only. |
| [Event](./event/) | Event | Contains elements that specify formulas that control shape events. |
| [LayerMem](./layermem/) | LayerMem | Contains the LayerMember element, which specifies each layer to which the shape is assigned. |
| [Foreign](./foreign/) | Foreign | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document.  |
| [TextBlock](./textblock/) | TextBlock | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [TextXForm](./textxform/) | TextXForm | Contains elements that specify positioning information about a shape's text block. |
| [Align](./align/) | Align | Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. The Align eleme |
| [Protection](./protection/) | Protection | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in oth |
| [Help](./help/) | Help | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Misc](./misc/) | Misc | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Image](./image/) | Image | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [Group](./group/) | Group | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [Layout](./layout/) | Layout | Contains elements that control shape placement and connector routing settings. |
| [Chars](./chars/) | CharCollection | Contains a collection of Char elements. |
| [Paras](./paras/) | ParaCollection | Contains a collection of Para elements. |
| [Scratchs](./scratchs/) | ScratchCollection | Contains a collection of Scratch elements. |
| [Connections](./connections/) | ConnectionCollection | Contains a collection of Connection elements. |
| [ContainerProperties](./containerproperties/) | ContainerProperties | Contains shape's ContainerProperties. |
| [ConnectionABCDs](./connectionabcds/) | ConnectionABCDCollection | Contains a collection of ConnectionABCD elements. |
| [Fields](./fields/) | FieldCollection | Contains a collection of Field elements. |
| [Controls](./controls/) | ControlCollection | Contains a collection of Control elements. |
| [Geoms](./geoms/) | GeomCollection | Contains a collection of Geom elements. |
| [Acts](./acts/) | ActCollection | Contains a collection of Act elements. |
| [Users](./users/) | UserCollection | Contains a collection of User elements. |
| [Props](./props/) | PropCollection | Contains a collection of Prop elements. |
| [Hyperlinks](./hyperlinks/) | HyperlinkCollection | Contains a collection of Hyperlink elements. |
| [SmartTagDefs](./smarttagdefs/) | SmartTagDefCollection | Contains a collection of SmartTagDef elements. |
| [TabsCollection](./tabscollection/) | TabsCollection | Contains a collection of Tab elements. |
| [Data1](./data1/) | String | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Data2](./data2/) | String | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Data3](./data3/) | String | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [ClippingPath](./clippingpath/) | String | Contains Clipping Path string value. |
| [ForeignData](./foreigndata/) | ForeignData | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |
| [MasterShape](./mastershape/) | Shape | This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master |
| [Master](./master/) | Master | The Master from which the shape inherits its data. |
| [ParentShape](./parentshape/) | Shape | Shape's parent. |
| [RootShape](./rootshape/) | Shape | Returns the top-level shape of an instance if this shape is part of a master instance. Read-only. |
| [Diagram](./diagram/) | Diagram | Root element of Visio objects hierarchy. |
| [Page](./page/) | Page | Root element of Visio objects hierarchy. |
| [OneD](./oned/) | boolean | Determines whether the shape behaves as a one-dimensional (1-D) object. Read-only. |
| [TwoD](./twod/) | boolean | Determines whether the shape behaves as a two-dimensional (2-D) object. |
| [ControlData](./controldata/) | byte[] | Gets the data of control. |
| [ActiveXControl](./activexcontrol/) | ActiveXControl | Gets the ActiveX control. |
| [ZOrderIndex](./zorderindex/) | int | Returns the index of a shape in the z-order except the guide shape. |
| [PresetTheme](./presettheme/) | int | Apply a preset theme to this shape The value of the property is PresetThemeValue integer constant. |
| [PresetThemeVariant](./presetthemevariant/) | int | Apply a preset theme variant to this shape The value of the property is PresetThemeVariantValue integer constant. |
| [PresetThemeQuickStyle](./presetthemequickstyle/) | int | Apply a preset theme variant quickstyle to this shape The value of the property is PresetQuickStyleValue integer constan |
| [ThreeDFormat](./threedformat/) | ThreeDFormat | Gets the ThreeDFormat. |

## Methods

| Name | Description |
| --- | --- |
| [convertToGroup](./converttogroup/) | Converts a selection or an object from another application (a linked or embedded object) to a group. |
| [getConnectorsType](./getconnectorstype/) | Get Connectors type |
| [setConnectorJumpValue](./setconnectorjumpvalue/) | Set Jump code value and Jump style value for Connector |
| [setConnectorsType](./setconnectorstype/) | Set Connectors type |
| [getRelationFlag](./getrelationflag/) | Returns RelationFlag that represents the relationship of one shape to another shape. |
| [getRelationShapeCollection](./getrelationshapecollection/) | Returns RelationShapeCollection that represents the relationshapes of one shape. |
| [setPresetThemeStyleMatrics](./setpresetthemestylematrics/) | pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list |
| [copy](./copy/) |  |
| [bringForward](./bringforward/) | Brings the shape forward one position in the z-order. |
| [sendBackward](./sendbackward/) | Moves the shape back one position in the z-order. |
| [bringToFront](./bringtofront/) | Brings the shape to the front of the z-order. |
| [sendToBack](./sendtoback/) | Moves the shape to the back of the z-order. |
| [getConnectorRule](./getconnectorrule/) | Returns a connectorRule that contains the shape id and connecton that are connected to the shape. |
| [connectedShapes](./connectedshapes/) | Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape. |
| [isInGroup](./isingroup/) | Indicates whether this shape is in a group shape. |
| [isContain](./iscontain/) | Indicates whether this shape is contain another shape. |
| [isIntersect](./isintersect/) | Indicates whether this shape is intersect another shape. |
| [isConnected](./isconnected/) | Indicates whether this two shapes are connected. |
| [centerDrawing](./centerdrawing/) | Center the shape with respect to the extent of the page |
| [isGlued](./isglued/) | Indicates whether this two shapes are glued. |
| [refreshData](./refreshdata/) |  |
| [gluedShapes](./gluedshapes/) | Returns an array that contains the identifiers of the shapes that are glued to a shape. |
| [dependsOnShapes](./dependsonshapes/) | Returns an array that contains the identifiers of the shapes that are depends on a shape. |
| [setWidth](./setwidth/) | Sets new width of shape. |
| [setHeight](./setheight/) | Sets new height of shape. |
| [setAngle](./setangle/) | Sets new angle of shape. The angle's unit is radian. |
| [moveTo](./moveto/) | Moves shape on new absolute position on the page. |
| [move](./move/) | Moves shape on the dX and dY inches from current position. |
| [getDisplayText](./getdisplaytext/) | Get the text displayed on the interface |
| [getPureText](./getpuretext/) | Get the text string |
| [ungroup](./ungroup/) | Ungroup Shape |
| [replaceText](./replacetext/) | Replace the text string of a shape . |
| [toPdf](./topdf/) | Saves the shape to a pdf file. |
