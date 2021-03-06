---
title: Page
second_title: Aspose.Diagram for .NET API Reference
description: 
type: docs
weight: 2480
url: /net/aspose.diagram/page/
---
## Page class

Contains elements that define a page in the document.

```csharp
public class Page : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Page](page)() | Constructor. |
| [Page](page)(int) | Constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage) { get; set; } | The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing. |
| [Background](../../aspose.diagram/page/background) { get; set; } | A flag indicating if the page is a background page. |
| [BackPage](../../aspose.diagram/page/backpage) { get; set; } | The page's background page. |
| [Connects](../../aspose.diagram/page/connects) { get; } | Contains a Connect element for each connection between two shapes in a drawing. |
| [ID](../../aspose.diagram/page/id) { get; set; } | The unique ID of the element within its parent element. |
| [Name](../../aspose.diagram/page/name) { get; set; } | The name of the element. |
| [NameU](../../aspose.diagram/page/nameu) { get; set; } | The universal name of the element. |
| [Pages](../../aspose.diagram/page/pages) { get; set; } | Page collection. |
| [PageSheet](../../aspose.diagram/page/pagesheet) { get; } | Contains elements that define the page sheet for a Page or Master element. |
| [PresetTheme](../../aspose.diagram/page/presettheme) { set; } | Apply a preset theme to this page |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle) { set; } | Apply a preset theme variant quickstyle to this page |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant) { set; } | Apply a preset theme variant to this page |
| [ReviewerID](../../aspose.diagram/page/reviewerid) { get; set; } | The ID of the reviewer associated with the markup overlay. |
| [Shapes](../../aspose.diagram/page/shapes) { get; } | Shape collection. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx) { get; set; } | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery) { get; set; } | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially. |
| [ViewScale](../../aspose.diagram/page/viewscale) { get; set; } | The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150%, and so on. |

## Methods

| Name | Description |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol)(ControlType, double, double, double, double) | Creates an Activex Control. |
| [AddComment](../../aspose.diagram/page/addcomment)(long, string) | Adds comment to a shape with shape's id. |
| [AddComment](../../aspose.diagram/page/addcomment)(Shape, string) | Adds comment to a shape. |
| [AddComment](../../aspose.diagram/page/addcomment)(double, double, string) | Adds comment with defined PinX and PinY. |
| [AddShape](../../aspose.diagram/page/addshape)(Shape, string) | Adds shape created by master to specific page. |
| [AddShape](../../aspose.diagram/page/addshape)(double, double, string) | Adds shape created by master on page with defined PinX and PinY. |
| [AddShape](../../aspose.diagram/page/addshape)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape)(double, double, double, double, string) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [AddShape](../../aspose.diagram/page/addshape)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext)(double, double, double, double, string) | Adds Text with defined PinX and PinY. |
| [AddText](../../aspose.diagram/page/addtext)(double, double, double, double, string, string, string, double) | Adds Text with defined PinX and PinY. |
| [ApplyStyle](../../aspose.diagram/page/applystyle)(int, int, int) | Applies style for full page. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes)(ShapeCollection, AutoSpaceOptions) | Auto space shapes |
| [BringForward](../../aspose.diagram/page/bringforward)(long) | Brings a shape,defined by ID, forward one position in the z-order. |
| [BringToFront](../../aspose.diagram/page/bringtofront)(long) | Brings a shape,defined by ID, to the front of the z-order. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing)() | Centers a page's shapes with respect to the extent of the page. Centering shapes does not change their position relative to each other. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Connect shapes via connector. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector)(long, string, long, string, long) | Connect shapes via connector. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Connect shapes via connector. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex)(long, int, long, int, long) | Connect shapes via connector index. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Connect shapes via connector index. |
| [Copy](../../aspose.diagram/page/copy)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [DrawBezier](../../aspose.diagram/page/drawbezier)(double, double, double, double, PointF[]) | The process of drawing bezier. The length of points should be equal or greater than 3. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse)(double, double, double, double) | The process of drawing Ellipse. |
| [DrawLine](../../aspose.diagram/page/drawline)(double, double, double, double) | The process of drawing a single line. |
| [DrawLine](../../aspose.diagram/page/drawline)(double, double, double, double, PointF[]) | The process of drawing line. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline)(double, double, double, double, PointF[]) | The process of drawing polyline. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle)(double, double, double, double) | The process of drawing rectangle. |
| [DrawSpline](../../aspose.diagram/page/drawspline)(double, double, double, double, PointF[]) | The process of drawing spline. |
| [GlueShapes](../../aspose.diagram/page/glueshapes)(long, ConnectionPointPlace, long) | Glue shapes |
| [GlueShapes](../../aspose.diagram/page/glueshapes)(Shape, ConnectionPointPlace, Shape) | Glue shapes. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer)(long, int, int, long) | Glue shapes in container |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer)(long, string, string, long) | Glue shapes in container using connection name |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid)(long, int, int, long) | Glue shapes by connection id in container |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx)(long, string, long) | Glue shape to Connector's BeginX |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx)(long, string, long) | Glue shape to Connector's EndX |
| [Layout](../../aspose.diagram/page/layout)(LayoutOptions) | Lays out the shapes and/or reroutes the connectors for the page. |
| [MoveTo](../../aspose.diagram/page/moveto)(int) | Moves the page to another location in the pages. |
| [SendBackward](../../aspose.diagram/page/sendbackward)(long) | Moves a shape,defined by ID, back one position in the z-order. |
| [SendToBack](../../aspose.diagram/page/sendtoback)(long) | Moves a shape,defined by ID, to the back of the z-order. |

### See Also

* namespace [Aspose.Diagram](../../aspose.diagram)
* assembly [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
