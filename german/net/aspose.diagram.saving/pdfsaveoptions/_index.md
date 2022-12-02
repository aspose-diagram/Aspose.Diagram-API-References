---
title: PdfSaveOptions
second_title: Aspose.Diagram für .NET-API-Referenz
description: Ermöglicht das Festlegen zusätzlicher Optionen beim Rendern von Diagrammseiten in PDF.
type: docs
weight: 3400
url: /de/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Ermöglicht das Festlegen zusätzlicher Optionen beim Rendern von Diagrammseiten in PDF.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | Initialisiert eine neue Instanz dieser Klasse, die zum Speichern eines Dokuments im verwendet werden kann[`Pdf`](../../aspose.diagram/savefileformat)format. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area) { get; set; } | Liest oder setzt den Bereich der Formen wird gespeichert . |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance) { get; set; } | Gewünschte Konformitätsstufe für generiertes PDF-Dokument. Standard istPdf15. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | Wenn die Zeichen im Diagramm Unicode sind und nicht mit dem richtigen Schriftartwert festgelegt werden oder die Schriftart nicht lokal installiert ist, können sie als Block in PDF, Bild oder XPS erscheinen. Legen Sie die Standardschriftart wie MingLiu oder MS Gothic fest, um diese anzuzeigen Zeichen. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails) { get; set; } | Ruft Details einer digitalen Signatur ab oder legt sie fest. Wenn nicht gesetzt, wird keine Signierung durchgeführt. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting) { get; set; } | Einstellung zum Rendern der EMF-Metadatei. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails) { get; set; } | Ruft Verschlüsselungsdetails ab oder legt sie fest. Wenn nicht gesetzt, wird keine Verschlüsselung durchgeführt. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage) { get; set; } | Gibt an, ob Seite vergrößern . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes) { get; set; } | Definiert, ob die Führungsformen exportiert werden müssen oder nicht. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage) { get; set; } | Definiert, ob die verborgene Seite exportiert werden muss oder nicht. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution) { get; set; } | Ruft die horizontale Auflösung für generierte Bilder in Punkten pro Zoll ab oder legt sie fest. Wendet die Bildgenerierungsmethode mit Ausnahme von Bildern im EMF-Format an. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments) { get; set; } | Definiert, ob die Kommentare exportiert werden müssen oder nicht. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality) { get; set; } | Gibt die Qualität der JPEG-Komprimierung für Bilder an (falls JPEG-Komprimierung verwendet wird). Standard ist 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount) { get; set; } | Ruft die Anzahl der Seiten ab, die in PDF gerendert werden sollen, oder legt sie fest. Der Standardwert ist MaxValue, was bedeutet, dass alle Seiten des Diagramms gerendert werden. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex) { get; set; } | Ruft den 0-basierten Index der ersten zu rendernden Seite ab oder legt ihn fest. Standard ist 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback) { get; set; } | Steuerung/Fortschritt des Seitenspeichervorgangs anzeigen. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize) { get; set; } | Ruft die Seitengröße für die generierten Bilder ab oder legt sie fest. Kann sein[`PageSize`](../pagesize) oder null. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly) { get; set; } | Gibt an, ob alle Seiten im Bild oder nur im Vordergrund gespeichert werden. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat) { get; set; } | Gibt das Format an, in dem die gerenderten Diagrammseiten gespeichert werden, wenn dieses Speicheroptionsobjekt verwendet wird. Kann sein[`Pdf`](../../aspose.diagram/savefileformat) nur. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes) { get; set; } | Ermittelt oder legt zu rendernde Formen fest. Die Standardanzahl ist 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages) { get; set; } | Legt fest, ob das Diagramm je nach Seiteneinstellung auf mehrere Seiten aufgeteilt wird. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression) { get; set; } | Gibt den Komprimierungstyp an, der für alle Inhaltsströme außer Bildern verwendet werden soll. Standard ist!:PdfTextCompressionCore.Flate. |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution) { get; set; } | Ruft die vertikale Auflösung für generierte Bilder in Punkten pro Zoll ab oder legt sie fest. Wendet die Bildgenerierungsmethode mit Ausnahme von Bildern im EMF-Format an. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback) { get; set; } | Ruft Warnrückruf ab oder legt ihn fest. |

### Siehe auch

* class [RenderingSaveOptions](../renderingsaveoptions)
* namensraum [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* Montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
