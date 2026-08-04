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
| [ID](/python-java/asposediagram.api/shape/id/) | long | The unique ID of the element within its parent element. |
| [Del](/python-java/asposediagram.api/shape/del/) | int | A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. Th |
| [UniqueID](/python-java/asposediagram.api/shape/uniqueid/) | UUID | A GUID (globally unique identifier) assigned to the shape. |
| [Name](/python-java/asposediagram.api/shape/name/) | String | The name of the element. |
| [NameU](/python-java/asposediagram.api/shape/nameu/) | String | The universal name of the element. |
| [Type](/python-java/asposediagram.api/shape/type/) | int | The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. The value of the property i |
| [LineStyle](/python-java/asposediagram.api/shape/linestyle/) | StyleSheet | StyleSheet from which this shape inherits line formatting |
| [FillStyle](/python-java/asposediagram.api/shape/fillstyle/) | StyleSheet | StyleSheet from which this shape inherits fill formatting. |
| [TextStyle](/python-java/asposediagram.api/shape/textstyle/) | StyleSheet | StyleSheet from which this shape inherits text formatting. |
| [Shapes](/python-java/asposediagram.api/shape/shapes/) | ShapeCollection | Contains a collection of Shape elements. |
| [Text](/python-java/asposediagram.api/shape/text/) | Text | Contains the text of a shape. |
| [XForm](/python-java/asposediagram.api/shape/xform/) | XForm | Contains elements specifying general positioning information about a shape. |
| [Line](/python-java/asposediagram.api/shape/line/) | Line | Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine |
| [Fill](/python-java/asposediagram.api/shape/fill/) | Fill | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground col |
| [HasThemeColor](/python-java/asposediagram.api/shape/hasthemecolor/) | boolean | Gets whether the shape has theme color. |
| [InheritChars](/python-java/asposediagram.api/shape/inheritchars/) | CharCollection | Contains the char values for the shape inherit by the master shape. |
| [InheritProps](/python-java/asposediagram.api/shape/inheritprops/) | PropCollection | Contains the props for the shape inherit by the master shape. |
| [InheritFields](/python-java/asposediagram.api/shape/inheritfields/) | FieldCollection | Contains the fields for the shape inherit by the master shape. |
| [InheritActs](/python-java/asposediagram.api/shape/inheritacts/) | ActCollection | Contains the actions for the shape inherit by the master shape. |
| [InheritHyperlinks](/python-java/asposediagram.api/shape/inherithyperlinks/) | HyperlinkCollection | Contains the Hyperlinks for the shape inherit by the master shape. |
| [InheritXForm](/python-java/asposediagram.api/shape/inheritxform/) | XForm |  |
| [InheritXForm1D](/python-java/asposediagram.api/shape/inheritxform1d/) | XForm1D |  |
| [InheritMisc](/python-java/asposediagram.api/shape/inheritmisc/) | Misc | Contains the Misc for the shape inherit by the master shape. |
| [InheritProtection](/python-java/asposediagram.api/shape/inheritprotection/) | Protection | Contains the Protection for the shape inherit by the master shape. |
| [InheritEvent](/python-java/asposediagram.api/shape/inheritevent/) | Event | Contains the Event for the shape inherit by the master shape. |
| [InheritLayerMem](/python-java/asposediagram.api/shape/inheritlayermem/) | LayerMem | Contains the LayerMem for the shape inherit by the master shape. |
| [InheritHelp](/python-java/asposediagram.api/shape/inherithelp/) | Help | Contains the Help for the shape inherit by the master shape. |
| [InheritLayout](/python-java/asposediagram.api/shape/inheritlayout/) | Layout | Contains the Layout for the shape inherit by the master shape. |
| [InheritControls](/python-java/asposediagram.api/shape/inheritcontrols/) | ControlCollection | Contains the controls for the shape inherit by the master shape. |
| [InheritConnections](/python-java/asposediagram.api/shape/inheritconnections/) | ConnectionCollection | Contains the connections for the shape inherit by the master shape. |
| [InheritScratchs](/python-java/asposediagram.api/shape/inheritscratchs/) | ScratchCollection | Contains the scratchs for the shape inherit by the master shape. |
| [InheritGroup](/python-java/asposediagram.api/shape/inheritgroup/) | Group |  |
| [InheritUsers](/python-java/asposediagram.api/shape/inheritusers/) | UserCollection | Contains the users for the shape inherit by the master shape. |
| [InheritTextXForm](/python-java/asposediagram.api/shape/inherittextxform/) | TextXForm | Contains the textxform values for the shape inherit by the parent style and the master shape. |
| [InheritGeoms](/python-java/asposediagram.api/shape/inheritgeoms/) | GeomCollection | Contains the Geoms values for the shape inherit by the master shape. |
| [InheritParas](/python-java/asposediagram.api/shape/inheritparas/) | ParaCollection | Contains the paras for the shape inherit by the parent style and the master shape. |
| [InheritTabs](/python-java/asposediagram.api/shape/inherittabs/) | TabsCollection | Contains the tabs for the shape inherit by the parent style and the master shape. |
| [InheritTextBlock](/python-java/asposediagram.api/shape/inherittextblock/) | TextBlock | Contains the textblock values for the shape inherit by the parent style and the master shape. |
| [InheritLine](/python-java/asposediagram.api/shape/inheritline/) | Line | Contains the line formatting values for the shape inherit by the parent style and the master shape. |
| [InheritFill](/python-java/asposediagram.api/shape/inheritfill/) | Fill | Contains the fill formatting values for the shape inherit by the parent style and the master shape. |
| [XForm1D](/python-java/asposediagram.api/shape/xform1d/) | XForm1D | Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only. |
| [Event](/python-java/asposediagram.api/shape/event/) | Event | Contains elements that specify formulas that control shape events. |
| [LayerMem](/python-java/asposediagram.api/shape/layermem/) | LayerMem | Contains the LayerMember element, which specifies each layer to which the shape is assigned. |
| [Foreign](/python-java/asposediagram.api/shape/foreign/) | Foreign | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document.  |
| [TextBlock](/python-java/asposediagram.api/shape/textblock/) | TextBlock | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [TextXForm](/python-java/asposediagram.api/shape/textxform/) | TextXForm | Contains elements that specify positioning information about a shape's text block. |
| [Align](/python-java/asposediagram.api/shape/align/) | Align | Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. The Align eleme |
| [Protection](/python-java/asposediagram.api/shape/protection/) | Protection | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in oth |
| [Help](/python-java/asposediagram.api/shape/help/) | Help | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Misc](/python-java/asposediagram.api/shape/misc/) | Misc | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Image](/python-java/asposediagram.api/shape/image/) | Image | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [Group](/python-java/asposediagram.api/shape/group/) | Group | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [Layout](/python-java/asposediagram.api/shape/layout/) | Layout | Contains elements that control shape placement and connector routing settings. |
| [Chars](/python-java/asposediagram.api/shape/chars/) | CharCollection | Contains a collection of Char elements. |
| [Paras](/python-java/asposediagram.api/shape/paras/) | ParaCollection | Contains a collection of Para elements. |
| [Scratchs](/python-java/asposediagram.api/shape/scratchs/) | ScratchCollection | Contains a collection of Scratch elements. |
| [Connections](/python-java/asposediagram.api/shape/connections/) | ConnectionCollection | Contains a collection of Connection elements. |
| [ContainerProperties](/python-java/asposediagram.api/shape/containerproperties/) | ContainerProperties | Contains shape's ContainerProperties. |
| [ConnectionABCDs](/python-java/asposediagram.api/shape/connectionabcds/) | ConnectionABCDCollection | Contains a collection of ConnectionABCD elements. |
| [Fields](/python-java/asposediagram.api/shape/fields/) | FieldCollection | Contains a collection of Field elements. |
| [Controls](/python-java/asposediagram.api/shape/controls/) | ControlCollection | Contains a collection of Control elements. |
| [Geoms](/python-java/asposediagram.api/shape/geoms/) | GeomCollection | Contains a collection of Geom elements. |
| [Acts](/python-java/asposediagram.api/shape/acts/) | ActCollection | Contains a collection of Act elements. |
| [Users](/python-java/asposediagram.api/shape/users/) | UserCollection | Contains a collection of User elements. |
| [Props](/python-java/asposediagram.api/shape/props/) | PropCollection | Contains a collection of Prop elements. |
| [Hyperlinks](/python-java/asposediagram.api/shape/hyperlinks/) | HyperlinkCollection | Contains a collection of Hyperlink elements. |
| [SmartTagDefs](/python-java/asposediagram.api/shape/smarttagdefs/) | SmartTagDefCollection | Contains a collection of SmartTagDef elements. |
| [TabsCollection](/python-java/asposediagram.api/shape/tabscollection/) | TabsCollection | Contains a collection of Tab elements. |
| [Data1](/python-java/asposediagram.api/shape/data1/) | String | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Data2](/python-java/asposediagram.api/shape/data2/) | String | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Data3](/python-java/asposediagram.api/shape/data3/) | String | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [ClippingPath](/python-java/asposediagram.api/shape/clippingpath/) | String | Contains Clipping Path string value. |
| [ForeignData](/python-java/asposediagram.api/shape/foreigndata/) | ForeignData | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |
| [MasterShape](/python-java/asposediagram.api/shape/mastershape/) | Shape | This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master |
| [Master](/python-java/asposediagram.api/shape/master/) | Master | The Master from which the shape inherits its data. |
| [ParentShape](/python-java/asposediagram.api/shape/parentshape/) | Shape | Shape's parent. |
| [RootShape](/python-java/asposediagram.api/shape/rootshape/) | Shape | Returns the top-level shape of an instance if this shape is part of a master instance. Read-only. |
| [Diagram](/python-java/asposediagram.api/shape/diagram/) | Diagram | Root element of Visio objects hierarchy. |
| [Page](/python-java/asposediagram.api/shape/page/) | Page | Root element of Visio objects hierarchy. |
| [OneD](/python-java/asposediagram.api/shape/oned/) | boolean | Determines whether the shape behaves as a one-dimensional (1-D) object. Read-only. |
| [TwoD](/python-java/asposediagram.api/shape/twod/) | boolean | Determines whether the shape behaves as a two-dimensional (2-D) object. |
| [ControlData](/python-java/asposediagram.api/shape/controldata/) | byte[] | Gets the data of control. |
| [ActiveXControl](/python-java/asposediagram.api/shape/activexcontrol/) | ActiveXControl | Gets the ActiveX control. |
| [ZOrderIndex](/python-java/asposediagram.api/shape/zorderindex/) | int | Returns the index of a shape in the z-order except the guide shape. |
| [PresetTheme](/python-java/asposediagram.api/shape/presettheme/) | int | Apply a preset theme to this shape The value of the property is PresetThemeValue integer constant. |
| [PresetThemeVariant](/python-java/asposediagram.api/shape/presetthemevariant/) | int | Apply a preset theme variant to this shape The value of the property is PresetThemeVariantValue integer constant. |
| [PresetThemeQuickStyle](/python-java/asposediagram.api/shape/presetthemequickstyle/) | int | Apply a preset theme variant quickstyle to this shape The value of the property is PresetQuickStyleValue integer constan |
| [ThreeDFormat](/python-java/asposediagram.api/shape/threedformat/) | ThreeDFormat | Gets the ThreeDFormat. |

## Methods

| Name | Description |
| --- | --- |
| [convertToGroup](/python-java/asposediagram.api/shape/converttogroup/) | Converts a selection or an object from another application (a linked or embedded object) to a group. |
| [getConnectorsType](/python-java/asposediagram.api/shape/getconnectorstype/) | Get Connectors type |
| [setConnectorJumpValue](/python-java/asposediagram.api/shape/setconnectorjumpvalue/) | Set Jump code value and Jump style value for Connector |
| [setConnectorsType](/python-java/asposediagram.api/shape/setconnectorstype/) | Set Connectors type |
| [getRelationFlag](/python-java/asposediagram.api/shape/getrelationflag/) | Returns RelationFlag that represents the relationship of one shape to another shape. |
| [getRelationShapeCollection](/python-java/asposediagram.api/shape/getrelationshapecollection/) | Returns RelationShapeCollection that represents the relationshapes of one shape. |
| [setPresetThemeStyleMatrics](/python-java/asposediagram.api/shape/setpresetthemestylematrics/) | pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list |
| [copy](/python-java/asposediagram.api/shape/copy/) |  |
| [bringForward](/python-java/asposediagram.api/shape/bringforward/) | Brings the shape forward one position in the z-order. |
| [sendBackward](/python-java/asposediagram.api/shape/sendbackward/) | Moves the shape back one position in the z-order. |
| [bringToFront](/python-java/asposediagram.api/shape/bringtofront/) | Brings the shape to the front of the z-order. |
| [sendToBack](/python-java/asposediagram.api/shape/sendtoback/) | Moves the shape to the back of the z-order. |
| [getConnectorRule](/python-java/asposediagram.api/shape/getconnectorrule/) | Returns a connectorRule that contains the shape id and connecton that are connected to the shape. |
| [connectedShapes](/python-java/asposediagram.api/shape/connectedshapes/) | Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape. |
| [isInGroup](/python-java/asposediagram.api/shape/isingroup/) | Indicates whether this shape is in a group shape. |
| [isContain](/python-java/asposediagram.api/shape/iscontain/) | Indicates whether this shape is contain another shape. |
| [isIntersect](/python-java/asposediagram.api/shape/isintersect/) | Indicates whether this shape is intersect another shape. |
| [isConnected](/python-java/asposediagram.api/shape/isconnected/) | Indicates whether this two shapes are connected. |
| [centerDrawing](/python-java/asposediagram.api/shape/centerdrawing/) | Center the shape with respect to the extent of the page |
| [isGlued](/python-java/asposediagram.api/shape/isglued/) | Indicates whether this two shapes are glued. |
| [refreshData](/python-java/asposediagram.api/shape/refreshdata/) |  |
| [gluedShapes](/python-java/asposediagram.api/shape/gluedshapes/) | Returns an array that contains the identifiers of the shapes that are glued to a shape. |
| [dependsOnShapes](/python-java/asposediagram.api/shape/dependsonshapes/) | Returns an array that contains the identifiers of the shapes that are depends on a shape. |
| [setWidth](/python-java/asposediagram.api/shape/setwidth/) | Sets new width of shape. |
| [setHeight](/python-java/asposediagram.api/shape/setheight/) | Sets new height of shape. |
| [setAngle](/python-java/asposediagram.api/shape/setangle/) | Sets new angle of shape. The angle's unit is radian. |
| [moveTo](/python-java/asposediagram.api/shape/moveto/) | Moves shape on new absolute position on the page. |
| [move](/python-java/asposediagram.api/shape/move/) | Moves shape on the dX and dY inches from current position. |
| [getDisplayText](/python-java/asposediagram.api/shape/getdisplaytext/) | Get the text displayed on the interface |
| [getPureText](/python-java/asposediagram.api/shape/getpuretext/) | Get the text string |
| [ungroup](/python-java/asposediagram.api/shape/ungroup/) | Ungroup Shape |
| [replaceText](/python-java/asposediagram.api/shape/replacetext/) | Replace the text string of a shape . |
| [toPdf](/python-java/asposediagram.api/shape/topdf/) | Saves the shape to a pdf file. |
