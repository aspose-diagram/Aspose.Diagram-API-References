---
title: Window
second_title: Aspose.Diagram für .NET-API-Referenz
description: Repräsentiert ein geöffnetes Fenster in einer Microsoft VisioInstanz. Dieses Element enthält Informationen die erforderlich sind um ein Benutzeroberflächenfenster im Anwendungsarbeitsbereich genau neu zu erstellen wenn die DatadiagramMLDatei zum ersten Mal von Visio geöffnet wird.
type: docs
weight: 4380
url: /de/net/aspose.diagram/window/
---
## Window class

Repräsentiert ein geöffnetes Fenster in einer Microsoft Visio-Instanz. Dieses Element enthält Informationen, die erforderlich sind, um ein Benutzeroberflächenfenster im Anwendungsarbeitsbereich genau neu zu erstellen, wenn die DatadiagramML-Datei zum ersten Mal von Visio geöffnet wird.

```csharp
public class Window
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Window](window)() | Konstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Container](../../aspose.diagram/window/container) { get; set; } | Container-ID: Seite, Blatt oder Master. Nur relevant und notwendig, wenn ContainerType angegeben ist. |
| [ContainerType](../../aspose.diagram/window/containertype) { get; set; } | Kann einer der folgenden Werte sein: Dokument, Seite oder Master. Nur relevant, wenn WindowType als Drawing oder Sheet angegeben ist. |
| [Document](../../aspose.diagram/window/document) { get; set; } | Dateipfad des in diesem Fenster angezeigten Dokuments. Dieses Attribut ist relevant für Fenster, deren WindowType als Stencil. angegeben ist. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled) { get; set; } | Gibt an, ob die dynamische Rasterfunktion für ein Dokument oder Fenster aktiviert ist. |
| [GlueSettings](../../aspose.diagram/window/gluesettings) { get; set; } | Gibt die Objekte an, auf die Formen kleben, wenn Kleben im Dokument aktiviert ist. |
| [ID](../../aspose.diagram/window/id) { get; set; } | Die eindeutige ID des Elements innerhalb seines übergeordneten Elements. |
| [Master](../../aspose.diagram/window/master) { get; set; } | Master-ID, wenn dieses Fenster einen Master anzeigt. |
| [Page](../../aspose.diagram/window/page) { get; set; } | Seiten-ID, wenn dieses Fenster eine Seite anzeigt. Nur relevant, wenn WindowType als Drawing und ContainerType als Page. angegeben ist. |
| [ParentWindow](../../aspose.diagram/window/parentwindow) { get; set; } | ID des Fensters, in dem dieses Stencil-Fenster enthalten ist. Nur relevant, wenn WindowType als Stencil. angegeben ist |
| [ReadOnly](../../aspose.diagram/window/readonly) { get; set; } | Schreibgeschütztes Flag, wenn diese Schablone keine Dokumentschablone ist. |
| [Sheet](../../aspose.diagram/window/sheet) { get; set; } | ID des Blatts im Container. Nur relevant, wenn Container als Sheet. angegeben ist |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints) { get; set; } | Legt fest, ob Verbindungspunkte in einem Fenster angezeigt werden. |
| [ShowGrid](../../aspose.diagram/window/showgrid) { get; set; } | Gibt an, ob im Zeichenfenster ein Raster angezeigt wird. |
| [ShowGuides](../../aspose.diagram/window/showguides) { get; set; } | Gibt an, ob Hilfslinien im Zeichenfenster angezeigt werden. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks) { get; set; } | Gibt an, ob Seitenumbrüche in einem Fenster angezeigt werden. |
| [ShowRulers](../../aspose.diagram/window/showrulers) { get; set; } | Gibt an, ob Lineale im Zeichenfenster angezeigt werden. |
| [SnapAngles](../../aspose.diagram/window/snapangles) { get; } | Enthält eine Sammlung von SnapAngle-Elementen. |
| [SnapExtensions](../../aspose.diagram/window/snapextensions) { get; set; } | Gibt an, ob eine bestimmte Snap-Erweiterungseinstellung für das aktive Fenster aktiviert oder deaktiviert ist. Der Wert kann eine Summe der Werte in der folgenden Tabelle sein. |
| [SnapSettings](../../aspose.diagram/window/snapsettings) { get; set; } | Gibt die Objekte an, an denen Formen einrasten, wenn das Einrasten im Fenster aktiv ist. Der Wert kann eine Summe der Werte in der folgenden Tabelle sein. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup) { get; set; } | Gibt die Gruppe der zusammengeführten Schablonenfenster an, zu denen das Fenster gehört. Dieses Attribut ist nur für Window-Elemente relevant, deren WindowType-Attribut Stencil ist, und nur dann, wenn das Schablonenfenster Teil einer zusammengeführten Gruppe von Schablonenfenstern ist. Alle Schablonenfenster, die Teil derselben zusammengeführten Gruppe sind, haben denselben StencilGroup-Elementwert. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos) { get; set; } | Enthält eine ganze Zahl, die die relative Position einer Schablone innerhalb einer Gruppe in einem Fenster angibt. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos) { get; set; } | Gibt die Breite des Seitenregistersteuerelements eines Zeichnungsfensters an (als Bruchteil der Gesamtbreite des Zeichnungsfensters). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx) { get; set; } | Optional doppelt. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery) { get; set; } | Optional doppelt. |
| [ViewScale](../../aspose.diagram/window/viewscale) { get; set; } | Optional doppelt. |
| [WindowHeight](../../aspose.diagram/window/windowheight) { get; set; } | Höhe des Fensterrechtecks. |
| [WindowLeft](../../aspose.diagram/window/windowleft) { get; set; } | Linke Koordinate des Fensterrechtecks. |
| [WindowState](../../aspose.diagram/window/windowstate) { get; set; } | Dieses Attribut kann eine Summe der folgenden Werte sein. |
| [WindowTop](../../aspose.diagram/window/windowtop) { get; set; } | Obere Koordinate des Fensterrechtecks. |
| [WindowType](../../aspose.diagram/window/windowtype) { get; set; } | Ein Aufzählungswert, der einer der folgenden sein kann: Drawing, Sheet, Stencil oder Icon. Ein Window-Element von WindowType='Stencil' muss nach seinem übergeordneten Zeichenfenster (WindowType='Drawing') und vor jedem anderen Zeichenfenster erscheinen Elemente. |
| [WindowWidth](../../aspose.diagram/window/windowwidth) { get; set; } | Breite des Fensterrechtecks. |

### Siehe auch

* namensraum [Aspose.Diagram](../../aspose.diagram)
* Montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
