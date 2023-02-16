---
title: HTMLSaveOptions
second_title: Aspose.Diagram für .NET-API-Referenz
description: Ermöglicht das Festlegen zusätzlicher Optionen beim Rendern von Diagrammseiten in HTML.
type: docs
weight: 3240
url: /de/net/aspose.diagram.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Ermöglicht das Festlegen zusätzlicher Optionen beim Rendern von Diagrammseiten in HTML.

```csharp
public class HTMLSaveOptions : RenderingSaveOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | Initialisiert eine neue Instanz dieser Klasse, die zum Speichern eines Dokuments im verwendet werden kann[`HTML`](../../aspose.diagram/savefileformat/) format. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Liest oder setzt den Bereich der Formen wird gespeichert . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Wenn die Zeichen im Diagramm Unicode sind und nicht mit dem richtigen Schriftartwert festgelegt werden oder die Schriftart nicht lokal installiert ist, können sie als Block in PDF, Bild oder XPS erscheinen. Legen Sie die Standardschriftart wie MingLiu oder MS Gothic fest, um diese anzuzeigen Zeichen. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Einstellung zum Rendern der EMF-Metadatei. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Gibt an, ob Seite vergrößern . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Definiert, ob die Führungsformen exportiert werden müssen oder nicht. |
| [ExportHiddenPage](../../aspose.diagram.saving/htmlsaveoptions/exporthiddenpage/) { get; set; } | Definiert, ob die verborgene Seite exportiert werden muss oder nicht. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Definiert, ob die Kommentare exportiert werden müssen oder nicht. |
| [PageCount](../../aspose.diagram.saving/htmlsaveoptions/pagecount/) { get; set; } | Ruft die Anzahl der in HTML zu rendernden Seiten ab oder legt sie fest. Der Standardwert ist MaxValue, was bedeutet, dass alle Seiten des Diagramms gerendert werden. |
| [PageIndex](../../aspose.diagram.saving/htmlsaveoptions/pageindex/) { get; set; } | Ruft den 0-basierten Index der ersten zu rendernden Seite ab oder legt ihn fest. Standard ist 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Ruft die Seitengröße für die generierten Bilder ab oder legt sie fest. Kann sein[`PageSize`](../pagesize/) oder null. |
| [Resolution](../../aspose.diagram.saving/htmlsaveoptions/resolution/) { get; set; } | Ruft die Auflösung für das generierte HTML in Punkten pro Zoll ab oder legt sie fest. |
| [SaveAsSingleFile](../../aspose.diagram.saving/htmlsaveoptions/saveassinglefile/) { get; set; } | Gibt an, ob die HTML-Datei als einzelne Datei gespeichert wird. Der Standardwert ist „false“. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/htmlsaveoptions/saveforegroundpagesonly/) { get; set; } | Gibt an, ob alle Seiten im Bild oder nur im Vordergrund gespeichert werden. |
| override [SaveFormat](../../aspose.diagram.saving/htmlsaveoptions/saveformat/) { get; set; } | Gibt das Format an, in dem die gerenderten Diagrammseiten gespeichert werden, wenn dieses Speicheroptionsobjekt verwendet wird. Kann sein[`HTML`](../../aspose.diagram/savefileformat/) nur. |
| [SaveTitle](../../aspose.diagram.saving/htmlsaveoptions/savetitle/) { get; set; } | Definiert, ob der Titel exportiert werden muss oder nicht. |
| [SaveToolBar](../../aspose.diagram.saving/htmlsaveoptions/savetoolbar/) { get; set; } | Gibt an, ob Symbolleiste gespeichert wird Der Standardwert ist wahr. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Ermittelt oder legt zu rendernde Formen fest. Die Standardanzahl ist 0. |
| [StreamProvider](../../aspose.diagram.saving/htmlsaveoptions/streamprovider/) { get; set; } | Ruft den IStreamProvider zum Exportieren von Objekten ab oder setzt ihn. |
| [Title](../../aspose.diagram.saving/htmlsaveoptions/title/) { get; set; } | Ruft den Titel des Diagramms ab oder legt ihn fest, der in HTML wiedergegeben werden soll. Wenn Titel null ist, Diagram.DocumentProperties.Title[`DocumentProperties`](../../aspose.diagram/documentproperties/) wird als Titel verwendet. Wenn Diagram.DocumentProperties.Title null oder leer ist, wird der Dateiname des Diagramms als Titel verwendet. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Ruft Warnrückruf ab oder legt ihn fest. |

### Siehe auch

* class [RenderingSaveOptions](../renderingsaveoptions/)
* namensraum [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* Montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
