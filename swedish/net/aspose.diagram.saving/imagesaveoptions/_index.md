---
title: ImageSaveOptions
second_title: Aspose.Diagram för .NET API-referens
description: Gör det möjligt att ange ytterligare alternativ när diagramsidor renderas till bilder.
type: docs
weight: 3280
url: /sv/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

Gör det möjligt att ange ytterligare alternativ när diagramsidor renderas till bilder.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/)(SaveFileFormat) | Initierar en ny instans av denna klass som kan användas för att spara renderade bilder i[`Tiff`](../../aspose.diagram/savefileformat/) , [`Png`](../../aspose.diagram/savefileformat/) ,[`Bmp`](../../aspose.diagram/savefileformat/) ,[`Emf`](../../aspose.diagram/savefileformat/) eller[`Jpeg`](../../aspose.diagram/savefileformat/) format. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Hämtar eller ställer in området för formerna kommer att sparas . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality/) { get; set; } | Anger den kvalitetsnivå som ska användas under sammansättningen. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom/) { get; set; } | Den här parametern liknar skalan, men påverkar inte den genererade bildstorleken. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | När tecknen i diagrammet är unicode och inte är inställda med korrekt teckensnittsvärde eller typsnittet inte är installerat lokalt, kan de visas som block i pdf, bild eller XPS. Ställ in standardfont som MingLiu eller MS Gothic för att visa dessa tecken. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Inställning för rendering av Emf-metafil. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Anger om förstora sidan . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Definierar om du behöver exportera guideformerna eller inte. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage/) { get; set; } | Definierar om den dolda sidan behöver exporteras eller inte. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness/) { get; set; } | Hämtar eller ställer in ljusstyrkan för de genererade bilderna. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode/) { get; set; } | Hämtar eller ställer in färgläget för de genererade bilderna. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast/) { get; set; } | Hämtar eller ställer in kontrasten för de genererade bilderna. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode/) { get; set; } | Anger algoritmen som används när bilder skalas eller roteras. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Definierar om kommentarerna behöver exporteras eller inte. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality/) { get; set; } | Hämtar eller ställer in ett värde som bestämmer kvaliteten på de genererade JPEG-bilderna. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount/) { get; set; } | Hämtar eller ställer in antalet sidor som ska renderas när du sparar till en flersidig TIFF-fil. Standard är MaxValue vilket innebär att alla sidor i diagrammet kommer att renderas. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex/) { get; set; } | Hämtar eller ställer in det 0-baserade indexet för den första sidan som ska renderas. Standard är 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Hämtar eller ställer in sidstorleken för de genererade bilderna. Kan vara[`PageSize`](../pagesize/) eller null. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode/) { get; set; } | Hämtar eller ställer in ett värde som anger hur pixlar förskjuts under rendering. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution/) { get; set; } | Hämtar eller ställer in upplösningen för de genererade bilderna, i punkter per tum. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea/) { get; set; } | Anger om sparområdet är samma som pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly/) { get; set; } | Anger om alla sidor ska sparas i bild eller endast i förgrunden. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat/) { get; set; } | Anger formatet som de renderade diagramsidorna kommer att sparas i om detta sparaalternativ-objekt används. Kan vara[`Tiff`](../../aspose.diagram/savefileformat/) ,[`Png`](../../aspose.diagram/savefileformat/) , [`Bmp`](../../aspose.diagram/savefileformat/) ,[`Emf`](../../aspose.diagram/savefileformat/) eller[`Jpeg`](../../aspose.diagram/savefileformat/) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale/) { get; set; } | Hämtar eller ställer in zoomfaktorn för de genererade bilderna. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Hämtar eller ställer in former att rendera. Standardantalet är 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode/) { get; set; } | Anger om utjämning (kantutjämning) tillämpas på linjer och kurvor och kanterna på fyllda områden. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression/) { get; set; } | Hämtar eller ställer in vilken typ av komprimering som ska tillämpas när genererade bilder sparas i TIFF-formatet. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Får eller ställer in varningsåteruppringning. |

### Se även

* class [RenderingSaveOptions](../renderingsaveoptions/)
* namnutrymme [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* hopsättning [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
