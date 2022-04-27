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
| [AssociatedPage](associatedpage) { get; set; } | The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing. |
| [Background](background) { get; set; } | A flag indicating if the page is a background page. |
| [BackPage](backpage) { get; set; } | The page's background page. |
| [Connects](connects) { get; } | Contains a Connect element for each connection between two shapes in a drawing. |
| [ID](id) { get; set; } | The unique ID of the element within its parent element. |
| [Name](name) { get; set; } | The name of the element. |
| [NameU](nameu) { get; set; } | The universal name of the element. |
| [Pages](pages) { get; set; } | Page collection. |
| [PageSheet](pagesheet) { get; } | Contains elements that define the page sheet for a Page or Master element. |
| [PresetTheme](presettheme) { set; } | Apply a preset theme to this page |
| [PresetThemeQuickStyle](presetthemequickstyle) { set; } | Apply a preset theme variant quickstyle to this page |
| [PresetThemeVariant](presetthemevariant) { set; } | Apply a preset theme variant to this page |
| [ReviewerID](reviewerid) { get; set; } | The ID of the reviewer associated with the markup overlay. |
| [Shapes](shapes) { get; } | Shape collection. |
| [ViewCenterX](viewcenterx) { get; set; } | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially. |
| [ViewCenterY](viewcentery) { get; set; } | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially. |
| [ViewScale](viewscale) { get; set; } | The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150%, and so on. |

## Methods

| Name | Description |
| --- | --- |
| [AddActiveXControl](addactivexcontrol)(ControlType, double, double, double, double) | Creates an Activex Control. |
| [AddComment](addcomment)(long, string) | Adds comment to a shape with shape's id. |
| [AddComment](addcomment)(Shape, string) | Adds comment to a shape. |
| [AddComment](addcomment)(double, double, string) | Adds comment with defined PinX and PinY. |
| [AddShape](addshape)(Shape, string) | Adds shape created by master to specific page. |
| [AddShape](addshape)(double, double, string) | Adds shape created by master on page with defined PinX and PinY. |
| [AddShape](addshape)(double, double, double, double, Stream) |  |
| [AddShape](addshape)(double, double, double, double, string) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [AddShape](addshape)(double, double, double, double, Stream, Stream) |  |
| [AddText](addtext)(double, double, double, double, string) | Adds Text with defined PinX and PinY. |
| [AddText](addtext)(double, double, double, double, string, string, string, double) | Adds Text with defined PinX and PinY. |
| [ApplyStyle](applystyle)(int, int, int) | Applies style for full page. |
| [AutoSpaceShapes](autospaceshapes)(ShapeCollection, AutoSpaceOptions) | Auto space shapes |
| [BringForward](bringforward)(long) | Brings a shape,defined by ID, forward one position in the z-order. |
| [BringToFront](bringtofront)(long) | Brings a shape,defined by ID, to the front of the z-order. |
| [CenterDrawing](centerdrawing)() | Centers a page's shapes with respect to the extent of the page. Centering shapes does not change their position relative to each other. |
| [ConnectShapesViaConnector](connectshapesviaconnector)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Connect shapes via connector. |
| [ConnectShapesViaConnector](connectshapesviaconnector)(long, string, long, string, long) | Connect shapes via connector. |
| [ConnectShapesViaConnector](connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Connect shapes via connector. |
| [ConnectShapesViaConnectorIndex](connectshapesviaconnectorindex)(long, int, long, int, long) | Connect shapes via connector index. |
| [ConnectShapesViaConnectorIndex](connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Connect shapes via connector index. |
| [Copy](copy)(Page) |  |
| [Dispose](dispose)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [DrawBezier](drawbezier)(double, double, double, double, PointF[]) | The process of drawing bezier. The length of points should be equal or greater than 3. |
| [DrawEllipse](drawellipse)(double, double, double, double) | The process of drawing Ellipse. |
| [DrawLine](drawline)(double, double, double, double) | The process of drawing a single line. |
| [DrawLine](drawline)(double, double, double, double, PointF[]) | The process of drawing line. |
| [DrawPolyline](drawpolyline)(double, double, double, double, PointF[]) | The process of drawing polyline. |
| [DrawRectangle](drawrectangle)(double, double, double, double) | The process of drawing rectangle. |
| [DrawSpline](drawspline)(double, double, double, double, PointF[]) | The process of drawing spline. |
| [GlueShapes](glueshapes)(long, ConnectionPointPlace, long) | Glue shapes |
| [GlueShapes](glueshapes)(Shape, ConnectionPointPlace, Shape) | Glue shapes. |
| [GlueShapesInContainer](glueshapesincontainer)(long, int, int, long) | Glue shapes in container |
| [GlueShapesInContainer](glueshapesincontainer)(long, string, string, long) | Glue shapes in container using connection name |
| [GlueShapesInContainerByID](glueshapesincontainerbyid)(long, int, int, long) | Glue shapes by connection id in container |
| [GlueShapeToConnectorBeginX](glueshapetoconnectorbeginx)(long, string, long) | Glue shape to Connector's BeginX |
| [GlueShapeToConnectorEndX](glueshapetoconnectorendx)(long, string, long) | Glue shape to Connector's EndX |
| [Layout](layout)(LayoutOptions) | Lays out the shapes and/or reroutes the connectors for the page. |
| [MoveTo](moveto)(int) | Moves the page to another location in the pages. |
| [SendBackward](sendbackward)(long) | Moves a shape,defined by ID, back one position in the z-order. |
| [SendToBack](sendtoback)(long) | Moves a shape,defined by ID, to the back of the z-order. |

### See Also

* namespace [Aspose.Diagram](../../aspose.diagram)
* assembly [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
