---
title: Page
second_title: Aspose.Diagram voor .NET API-referentie
description: Bevat elementen die een pagina in het document definiëren.
type: docs
weight: 2490
url: /nl/net/aspose.diagram/page/
---
## Page class

Bevat elementen die een pagina in het document definiëren.

```csharp
public class Page : IDisposable
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Page](page/#constructor)() | Aannemer. |
| [Page](page/#constructor_1)(int) | Aannemer. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | De ID van de oorspronkelijke tekenpagina die is gemarkeerd op afzonderlijke opmaakoverlays door revisoren van de tekening. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | Een vlag die aangeeft of de pagina een achtergrondpagina is. |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | De achtergrondpagina van de pagina. |
| [Connects](../../aspose.diagram/page/connects/) { get; } | Bevat een Connect-element voor elke verbinding tussen twee vormen in een tekening. |
| [ID](../../aspose.diagram/page/id/) { get; set; } | De unieke ID van het element binnen het bovenliggende element. |
| [Name](../../aspose.diagram/page/name/) { get; set; } | De naam van het element. |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | De universele naam van het element. |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | Paginaverzameling. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | Bevat elementen die het paginablad definiëren voor een Page- of Master-element. |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | Pas een vooraf ingesteld thema toe op deze pagina |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | Pas een vooraf ingestelde quickstyle themavariant toe op deze pagina |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | Pas een vooraf ingestelde themavariant toe op deze pagina |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | De ID van de revisor die is gekoppeld aan de markup-overlay. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | Vormverzameling. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX en ViewCenterY specificeren een middelpunt op een pagina dat een nieuwe weergave (venster) aanneemt wanneer deze voor het eerst wordt geopend. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX en ViewCenterY specificeren een middelpunt op een pagina dat een nieuwe weergave (venster) aanneemt wanneer deze voor het eerst wordt geopend. |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | De standaard vergrotingsfactor die moet worden gebruikt wanneer een nieuwe weergave (venster) van de pagina wordt geopend. Bijvoorbeeld: 1 = 100%; 1,5 = 150%, enzovoort. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Creëert een Activex-besturingselement. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | Voegt commentaar toe aan een vorm met vorm-id. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | Voegt commentaar toe aan een vorm. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | Voegt commentaar toe met gedefinieerde PinX en PinY. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | Voegt door master gemaakte vorm toe aan specifieke pagina. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | Voegt vorm toe gemaakt door master op pagina met gedefinieerde PinX en PinY. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | Voegt een door de master gemaakte vorm toe aan de pagina met gedefinieerde PinX,PinY,Width en Height. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | Voegt tekst toe met gedefinieerde PinX en PinY. |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | Voegt tekst toe met gedefinieerde PinX en PinY. |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | Past stijl toe op volledige pagina. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | Automatische ruimtevormen |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | Brengt een vorm, gedefinieerd door ID, één positie vooruit in de z-volgorde. |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | Brengt een vorm, gedefinieerd door ID, naar de voorkant van de z-orde. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | Centreert de vormen van een pagina ten opzichte van de omvang van de pagina. Centreren van vormen verandert hun positie ten opzichte van elkaar niet. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Vormen verbinden via connector. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | Vormen verbinden via connector. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Vormen verbinden via connector. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | Vormen verbinden via connectorindex. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Vormen verbinden via connectorindex. |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | Voert door de toepassing gedefinieerde taken uit die verband houden met het vrijmaken, vrijgeven of resetten van onbeheerde bronnen. |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | Het proces van het tekenen van bezier. De lengte van punten moet gelijk zijn aan of groter zijn dan 3. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | Het proces van het tekenen van Ellipse. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | Het proces van het tekenen van een enkele lijn. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | Het proces van het tekenen van lijnen. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | Het proces van het tekenen van lijnen. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | Het proces van het tekenen van Polyline. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | Het proces van het tekenen van een polylijn. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | Het proces van het tekenen van een rechthoek. |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | Het proces van het tekenen van spline. |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | Lijmvormen |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | Vormen lijmen. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | Vormen in container lijmen |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | Vormen in container lijmen met verbindingsnaam |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | Lijm vormen op verbindings-ID in container |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | Lijm vorm op Connector's BeginX |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | Lijm vorm aan Connector's EndX |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | Legt de vormen uit en/of herleidt de connectoren voor de pagina. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | Verplaatst de pagina naar een andere locatie in de pagina's. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | Verplaatst een vorm, gedefinieerd door ID, één positie terug in de z-volgorde. |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | Verplaatst een vorm, gedefinieerd door ID, naar de achterkant van de z-orde. |

### Zie ook

* naamruimte [Aspose.Diagram](../../aspose.diagram/)
* montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
