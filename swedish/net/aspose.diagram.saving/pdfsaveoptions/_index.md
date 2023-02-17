---
title: PdfSaveOptions
second_title: Aspose.Diagram för .NET API-referens
description: Gör det möjligt att ange ytterligare alternativ när diagramsidor renderas till PDF.
type: docs
weight: 3410
url: /sv/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Gör det möjligt att ange ytterligare alternativ när diagramsidor renderas till PDF.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Initierar en ny instans av denna klass som kan användas för att spara ett dokument i[`Pdf`](../../aspose.diagram/savefileformat/) format. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Hämtar eller ställer in området för formerna kommer att sparas . |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance/) { get; set; } | Önskad överensstämmelsenivå för genererat PDF-dokument. Standard ärPdf15 . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | När tecknen i diagrammet är unicode och inte är inställda med korrekt teckensnittsvärde eller typsnittet inte är installerat lokalt, kan de visas som block i pdf, bild eller XPS. Ställ in standardfont som MingLiu eller MS Gothic för att visa dessa tecken. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails/) { get; set; } | Hämtar eller ställer in information om en digital signatur. Om inte inställt kommer ingen signering att utföras. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Inställning för rendering av Emf-metafil. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails/) { get; set; } | Hämtar eller ställer in en krypteringsinformation. Om inte inställt kommer ingen kryptering att utföras. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Anger om förstora sidan . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Definierar om du behöver exportera guideformerna eller inte. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage/) { get; set; } | Definierar om den dolda sidan behöver exporteras eller inte. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution/) { get; set; } | Hämtar eller ställer in den horisontella upplösningen för genererade bilder, i punkter per tum. Använder genererande bildmetoden förutom bilder i EMF-format. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Definierar om kommentarerna behöver exporteras eller inte. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality/) { get; set; } | Anger kvaliteten på JPEG-komprimering för bilder (om JPEG-komprimering används). Standard är 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount/) { get; set; } | Hämtar eller ställer in antalet sidor som ska renderas i PDF. Standard är MaxValue vilket innebär att alla sidor i diagrammet kommer att renderas. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex/) { get; set; } | Hämtar eller ställer in det 0-baserade indexet för den första sidan som ska renderas. Standard är 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback/) { get; set; } | Kontrollera/indikera framsteg för sidsparprocessen. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Hämtar eller ställer in sidstorleken för de genererade bilderna. Kan vara[`PageSize`](../pagesize/) eller null. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly/) { get; set; } | Anger om alla sidor ska sparas i bild eller endast i förgrunden. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat/) { get; set; } | Anger formatet som de renderade diagramsidorna kommer att sparas i om detta sparaalternativ-objekt används. Kan vara[`PDF`](../../aspose.diagram/savefileformat/) endast. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Hämtar eller ställer in former att rendera. Standardantalet är 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages/) { get; set; } | Definierar om delat diagram till flera sidor enligt sidans inställning. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression/) { get; set; } | Anger komprimeringstyp som ska användas för alla innehållsströmmar utom bilder. Standard ärFlate . |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution/) { get; set; } | Hämtar eller ställer in den vertikala upplösningen för genererade bilder, i punkter per tum. Tillämpar genererande bildmetoden förutom Emf-formatbild. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback/) { get; set; } | Får eller ställer in varningsåteruppringning. |

### Se även

* class [RenderingSaveOptions](../renderingsaveoptions/)
* namnutrymme [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* hopsättning [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
