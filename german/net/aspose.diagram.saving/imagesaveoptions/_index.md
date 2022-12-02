---
title: ImageSaveOptions
second_title: Aspose.Diagram für .NET-API-Referenz
description: Ermöglicht das Festlegen zusätzlicher Optionen beim Rendern von Diagrammseiten in Bilder.
type: docs
weight: 3270
url: /de/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

Ermöglicht das Festlegen zusätzlicher Optionen beim Rendern von Diagrammseiten in Bilder.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions)(SaveFileFormat) | Initialisiert eine neue Instanz dieser Klasse, die verwendet werden kann, um gerenderte Bilder in der zu speichern[`Tiff`](../../aspose.diagram/savefileformat) , [`Png`](../../aspose.diagram/savefileformat) ,[`Bmp`](../../aspose.diagram/savefileformat) ,[`Emf`](../../aspose.diagram/savefileformat) oder[`JPEG`](../../aspose.diagram/savefileformat)format. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area) { get; set; } | Liest oder setzt den Bereich der Formen wird gespeichert . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality) { get; set; } | Gibt die beim Compositing zu verwendende Qualitätsstufe an. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom) { get; set; } | Dieser Parameter ist ähnlich wie bei der Skalierung, wirkt sich aber nicht auf die generierte Bildgröße aus. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | Wenn die Zeichen im Diagramm Unicode sind und nicht mit dem richtigen Schriftartwert festgelegt werden oder die Schriftart nicht lokal installiert ist, können sie als Block in PDF, Bild oder XPS erscheinen. Legen Sie die Standardschriftart wie MingLiu oder MS Gothic fest, um diese anzuzeigen Zeichen. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting) { get; set; } | Einstellung zum Rendern der EMF-Metadatei. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage) { get; set; } | Gibt an, ob Seite vergrößern . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes) { get; set; } | Definiert, ob die Führungsformen exportiert werden müssen oder nicht. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage) { get; set; } | Definiert, ob die verborgene Seite exportiert werden muss oder nicht. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness) { get; set; } | Holt oder setzt die Helligkeit für die generierten Bilder. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode) { get; set; } | Ruft den Farbmodus für die generierten Bilder ab oder legt ihn fest. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast) { get; set; } | Ruft den Kontrast für die generierten Bilder ab oder setzt ihn. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode) { get; set; } | Gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder gedreht werden. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments) { get; set; } | Definiert, ob die Kommentare exportiert werden müssen oder nicht. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der die Qualität der generierten JPEG-Bilder bestimmt. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount) { get; set; } | Ruft die Anzahl der zu rendernden Seiten beim Speichern in einer mehrseitigen TIFF-Datei ab oder legt sie fest. Der Standardwert ist MaxValue, was bedeutet, dass alle Seiten des Diagramms gerendert werden. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex) { get; set; } | Ruft den 0-basierten Index der ersten zu rendernden Seite ab oder legt ihn fest. Standard ist 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize) { get; set; } | Ruft die Seitengröße für die generierten Bilder ab oder legt sie fest. Kann sein[`PageSize`](../pagesize) oder null. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, wie Pixel während des Renderns versetzt werden. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution) { get; set; } | Ruft die Auflösung für die generierten Bilder in Punkten pro Zoll ab oder legt sie fest. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea) { get; set; } | Gibt an, ob der Speicherbereich derselbe ist wie bei pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly) { get; set; } | Gibt an, ob alle Seiten im Bild oder nur im Vordergrund gespeichert werden. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat) { get; set; } | Gibt das Format an, in dem die gerenderten Diagrammseiten gespeichert werden, wenn dieses Speicheroptionsobjekt verwendet wird. Kann sein[`Tiff`](../../aspose.diagram/savefileformat) ,[`Png`](../../aspose.diagram/savefileformat) , [`Bmp`](../../aspose.diagram/savefileformat) ,[`Emf`](../../aspose.diagram/savefileformat) oder[`JPEG`](../../aspose.diagram/savefileformat). |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale) { get; set; } | Liest oder setzt den Zoomfaktor für die generierten Bilder. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes) { get; set; } | Ermittelt oder legt zu rendernde Formen fest. Die Standardanzahl ist 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode) { get; set; } | Gibt an, ob Glättung (Antialiasing) auf Linien und Kurven und die Kanten gefüllter Bereiche angewendet wird. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression) { get; set; } | Ruft den Komprimierungstyp ab oder legt ihn fest, der angewendet werden soll, wenn generierte Bilder im TIFF-Format gespeichert werden. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | Ruft Warnrückruf ab oder legt ihn fest. |

### Siehe auch

* class [RenderingSaveOptions](../renderingsaveoptions)
* namensraum [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* Montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
