---
title: Page
second_title: Aspose.Diagram för .NET API-referens
description: Innehåller element som definierar en sida i dokumentet.
type: docs
weight: 2490
url: /sv/net/aspose.diagram/page/
---
## Page class

Innehåller element som definierar en sida i dokumentet.

```csharp
public class Page : IDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Page](page/#constructor)() | Konstruktör. |
| [Page](page/#constructor_1)(int) | Konstruktör. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | ID för den ursprungliga ritningssidan som markerades på separata markeringar av granskare av ritningen. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | En flagga som indikerar om sidan är en bakgrundssida. |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | Sidans bakgrundssida. |
| [Connects](../../aspose.diagram/page/connects/) { get; } | Innehåller ett Connect-element för varje anslutning mellan två former i en ritning. |
| [ID](../../aspose.diagram/page/id/) { get; set; } | Elementets unika ID i dess överordnade element. |
| [Name](../../aspose.diagram/page/name/) { get; set; } | Namnet på elementet. |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | Det universella namnet på elementet. |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | Sidsamling. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | Innehåller element som definierar sidbladet för ett sida- eller masterelement. |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | Tillämpa ett förinställt tema på den här sidan |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | Tillämpa en förinställd temavariant quickstyle på den här sidan |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | Tillämpa en förinställd temavariant på den här sidan |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | Id för granskaren som är kopplad till uppmärkningsöverlagringen. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | Formsamling. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX och ViewCenterY anger en mittpunkt på en sida som en ny vy (fönster) antar när den öppnas initialt. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX och ViewCenterY anger en mittpunkt på en sida som en ny vy (fönster) antar när den öppnas initialt. |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | Standardförstoringsfaktorn som ska användas när en ny vy (fönster) på sidan öppnas. Till exempel, 1 = 100 %; 1,5 = 150 % och så vidare. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Skapar en Activex-kontroll. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | Lägger till kommentar till en form med formens id. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | Lägger till kommentar till en form. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | Lägger till kommentar med definierade PinX och PinY. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | Lägger till form skapad av master till specifik sida. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | Lägger till form skapad av master på sidan med definierade PinX och PinY. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | Lägger till form skapad av master på sidan med definierade PinX, PinY, Width och Height. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | Lägger till text med definierade PinX och PinY. |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | Lägger till text med definierade PinX och PinY. |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | Tillämpar stil för hela sidan. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | Auto space shapes |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | Tar en form, definierad av ID, framåt en position i z-ordningen. |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | Tar en form, definierad av ID, till framsidan av z-ordningen. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | Centrerar en sidas former i förhållande till sidans omfattning. Centrering av former ändrar inte deras position i förhållande till varandra. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Anslut former via kontakten. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | Anslut former via kontakten. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Anslut former via kontakten. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | Anslut former via kopplingsindex. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Anslut former via kopplingsindex. |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | Processen att rita bezier. Längden på punkterna ska vara lika med eller större än 3. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | Processen att rita Ellipse. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | Processen att rita en enda linje. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | Processen att rita linje. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | Processen att rita linje. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | Processen att rita Polyline. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | Processen att rita polylinje. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | Processen att rita rektangel. |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | Processen att rita spline. |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | Limformer |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | Limformer. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | Limma former i container |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | Limma fast former i behållaren med anslutningsnamn |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | Limma former efter anslutnings-id i container |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | Limma form på Connector's BeginX |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | Limma formen på kontaktens ändeX |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | Lägger ut formerna och/eller dirigerar om kopplingarna för sidan. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | Flyttar sidan till en annan plats på sidorna. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | Flyttar en form, definierad av ID, tillbaka en position i z-ordningen. |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | Flyttar en form, definierad av ID, till baksidan av z-ordningen. |

### Se även

* namnutrymme [Aspose.Diagram](../../aspose.diagram/)
* hopsättning [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
