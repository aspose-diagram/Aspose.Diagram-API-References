---
title: Page
second_title: Aspose.Diagram für .NET-API-Referenz
description: Enthält Elemente die eine Seite im Dokument definieren.
type: docs
weight: 2480
url: /de/net/aspose.diagram/page/
---
## Page class

Enthält Elemente, die eine Seite im Dokument definieren.

```csharp
public class Page : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Page](page#constructor)() | Konstruktor. |
| [Page](page#constructor_1)(int) | Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage) { get; set; } | Die ID der ursprünglichen Zeichnungsseite, die von Prüfern der Zeichnung auf separaten Markup-Overlays markiert wurde. |
| [Background](../../aspose.diagram/page/background) { get; set; } | Ein Flag, das angibt, ob die Seite eine Hintergrundseite ist. |
| [BackPage](../../aspose.diagram/page/backpage) { get; set; } | Die Hintergrundseite der Seite. |
| [Connects](../../aspose.diagram/page/connects) { get; } | Enthält ein Verbindungselement für jede Verbindung zwischen zwei Shapes in einer Zeichnung. |
| [ID](../../aspose.diagram/page/id) { get; set; } | Die eindeutige ID des Elements innerhalb seines übergeordneten Elements. |
| [Name](../../aspose.diagram/page/name) { get; set; } | Der Name des Elements. |
| [NameU](../../aspose.diagram/page/nameu) { get; set; } | Der universelle Name des Elements. |
| [Pages](../../aspose.diagram/page/pages) { get; set; } | Seitensammlung. |
| [PageSheet](../../aspose.diagram/page/pagesheet) { get; } | Enthält Elemente, die das Seitenblatt für ein Seiten- oder Masterelement definieren. |
| [PresetTheme](../../aspose.diagram/page/presettheme) { set; } | Voreingestelltes Design auf diese Seite anwenden |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle) { set; } | Wenden Sie eine voreingestellte Designvariante Quickstyle auf diese Seite an |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant) { set; } | Eine voreingestellte Designvariante auf diese Seite anwenden |
| [ReviewerID](../../aspose.diagram/page/reviewerid) { get; set; } | Die ID des Prüfers, der mit der Markup-Überlagerung verknüpft ist. |
| [Shapes](../../aspose.diagram/page/shapes) { get; } | Formensammlung. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx) { get; set; } | ViewCenterX und ViewCenterY geben einen Mittelpunkt auf einer Seite an, den eine neue Ansicht (Fenster) beim ersten Öffnen einnimmt. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery) { get; set; } | ViewCenterX und ViewCenterY geben einen Mittelpunkt auf einer Seite an, den eine neue Ansicht (Fenster) beim ersten Öffnen einnimmt. |
| [ViewScale](../../aspose.diagram/page/viewscale) { get; set; } | Der standardmäßige Vergrößerungsfaktor, der verwendet wird, wenn eine neue Ansicht (Fenster) der Seite geöffnet wird. Beispiel: 1 = 100 %; 1,5 = 150 % usw. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol)(ControlType, double, double, double, double) | Erstellt ein Activex-Steuerelement. |
| [AddComment](../../aspose.diagram/page/addcomment#addcomment_2)(long, string) | Fügt einen Kommentar zu einer Form mit der Form-ID hinzu. |
| [AddComment](../../aspose.diagram/page/addcomment#addcomment)(Shape, string) | Fügt einer Form einen Kommentar hinzu. |
| [AddComment](../../aspose.diagram/page/addcomment#addcomment_1)(double, double, string) | Fügt einen Kommentar mit definiertem PinX und PinY hinzu. |
| [AddShape](../../aspose.diagram/page/addshape#addshape)(Shape, string) | Fügt eine vom Master erstellte Form zu einer bestimmten Seite hinzu. |
| [AddShape](../../aspose.diagram/page/addshape#addshape_4)(double, double, string) | Fügt eine vom Master erstellte Form auf der Seite mit definiertem PinX und PinY hinzu. |
| [AddShape](../../aspose.diagram/page/addshape#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape#addshape_3)(double, double, double, double, string) | Fügt eine vom Master erstellte Form auf der Seite mit definierten PinX, PinY, Breite und Höhe hinzu. |
| [AddShape](../../aspose.diagram/page/addshape#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext#addtext)(double, double, double, double, string) | Fügt Text mit definiertem PinX und PinY hinzu. |
| [AddText](../../aspose.diagram/page/addtext#addtext_1)(double, double, double, double, string, string, string, double) | Fügt Text mit definiertem PinX und PinY hinzu. |
| [ApplyStyle](../../aspose.diagram/page/applystyle)(int, int, int) | Wendet Stil für ganze Seite an. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes)(ShapeCollection, AutoSpaceOptions) | Automatische Leerzeichenformen |
| [BringForward](../../aspose.diagram/page/bringforward)(long) | Bringt eine durch ID definierte Form in der z-Reihenfolge um eine Position nach vorn. |
| [BringToFront](../../aspose.diagram/page/bringtofront)(long) | Bringt eine durch ID definierte Form an den Anfang der Z-Reihenfolge. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing)() | Zentriert die Shapes einer Seite in Bezug auf die Ausdehnung der Seite. Durch das Zentrieren von Shapes wird ihre Position relativ zueinander nicht geändert. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Formen über Verbinder verbinden. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector#connectshapesviaconnector_2)(long, string, long, string, long) | Formen über Verbinder verbinden. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Formen über Verbinder verbinden. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex#connectshapesviaconnectorindex_1)(long, int, long, int, long) | Formen über Verbinderindex verbinden. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Formen über Verbinderindex verbinden. |
| [Copy](../../aspose.diagram/page/copy)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [DrawBezier](../../aspose.diagram/page/drawbezier)(double, double, double, double, PointF[]) | Der Vorgang des Bezier-Zeichnens. Die Länge der Punkte sollte gleich oder größer als 3 sein. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse)(double, double, double, double) | Der Prozess des Zeichnens einer Ellipse. |
| [DrawLine](../../aspose.diagram/page/drawline#drawline)(double, double, double, double) | Der Prozess des Zeichnens einer einzelnen Linie. |
| [DrawLine](../../aspose.diagram/page/drawline#drawline_1)(double, double, double, double, PointF[]) | Der Prozess des Linienzeichnens. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline)(double, double, double, double, PointF[]) | Der Prozess des Zeichnens von Polylinien. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle)(double, double, double, double) | Der Prozess des Zeichnens von Rechtecken. |
| [DrawSpline](../../aspose.diagram/page/drawspline)(double, double, double, double, PointF[]) | Der Vorgang zum Zeichnen von Splines. |
| [GlueShapes](../../aspose.diagram/page/glueshapes#glueshapes_1)(long, ConnectionPointPlace, long) | Klebeformen |
| [GlueShapes](../../aspose.diagram/page/glueshapes#glueshapes)(Shape, ConnectionPointPlace, Shape) | Formen kleben. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer#glueshapesincontainer)(long, int, int, long) | Formen in Behälter kleben |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer#glueshapesincontainer_1)(long, string, string, long) | Leimformen im Container mit Verbindungsname |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid)(long, int, int, long) | Formen nach Verbindungs-ID in container kleben |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx)(long, string, long) | Form an den Anfang des Verbinders klebenX |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx)(long, string, long) | Form auf das Ende des Verbinders klebenX |
| [Layout](../../aspose.diagram/page/layout)(LayoutOptions) | Legt die Formen fest und/oder leitet die Verbinder für die Seite um. |
| [MoveTo](../../aspose.diagram/page/moveto)(int) | Verschiebt die Seite an eine andere Position innerhalb der Seiten. |
| [SendBackward](../../aspose.diagram/page/sendbackward)(long) | Verschiebt eine durch ID definierte Form um eine Position in der Z-Reihenfolge zurück. |
| [SendToBack](../../aspose.diagram/page/sendtoback)(long) | Verschiebt eine durch ID definierte Form an das Ende der Z-Reihenfolge. |

### Siehe auch

* namensraum [Aspose.Diagram](../../aspose.diagram)
* Montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
