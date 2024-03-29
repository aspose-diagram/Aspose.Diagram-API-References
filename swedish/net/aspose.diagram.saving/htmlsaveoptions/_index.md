---
title: HTMLSaveOptions
second_title: Aspose.Diagram för .NET API-referens
description: Gör det möjligt att ange ytterligare alternativ när diagramsidor renderas till HTML.
type: docs
weight: 3240
url: /sv/net/aspose.diagram.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Gör det möjligt att ange ytterligare alternativ när diagramsidor renderas till HTML.

```csharp
public class HTMLSaveOptions : RenderingSaveOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | Initierar en ny instans av denna klass som kan användas för att spara ett dokument i[`HTML`](../../aspose.diagram/savefileformat/) format. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Hämtar eller ställer in området för formerna kommer att sparas . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | När tecknen i diagrammet är unicode och inte är inställda med korrekt teckensnittsvärde eller typsnittet inte är installerat lokalt, kan de visas som block i pdf, bild eller XPS. Ställ in standardfont som MingLiu eller MS Gothic för att visa dessa tecken. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Inställning för rendering av Emf-metafil. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Anger om förstora sidan . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Definierar om du behöver exportera guideformerna eller inte. |
| [ExportHiddenPage](../../aspose.diagram.saving/htmlsaveoptions/exporthiddenpage/) { get; set; } | Definierar om den dolda sidan behöver exporteras eller inte. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Definierar om kommentarerna behöver exporteras eller inte. |
| [PageCount](../../aspose.diagram.saving/htmlsaveoptions/pagecount/) { get; set; } | Hämtar eller ställer in antalet sidor som ska renderas i HTML. Standard är MaxValue vilket innebär att alla sidor i diagrammet kommer att renderas. |
| [PageIndex](../../aspose.diagram.saving/htmlsaveoptions/pageindex/) { get; set; } | Hämtar eller ställer in det 0-baserade indexet för den första sidan som ska renderas. Standard är 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Hämtar eller ställer in sidstorleken för de genererade bilderna. Kan vara[`PageSize`](../pagesize/) eller null. |
| [Resolution](../../aspose.diagram.saving/htmlsaveoptions/resolution/) { get; set; } | Hämtar eller ställer in upplösningen för den genererade HTML-koden, i punkter per tum. |
| [SaveAsSingleFile](../../aspose.diagram.saving/htmlsaveoptions/saveassinglefile/) { get; set; } | Indikerar om HTML-filen sparas som en enda fil. Standardvärdet är false. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/htmlsaveoptions/saveforegroundpagesonly/) { get; set; } | Anger om alla sidor ska sparas i bild eller endast i förgrunden. |
| override [SaveFormat](../../aspose.diagram.saving/htmlsaveoptions/saveformat/) { get; set; } | Anger formatet som de renderade diagramsidorna kommer att sparas i om detta sparaalternativ-objekt används. Kan vara[`HTML`](../../aspose.diagram/savefileformat/) endast. |
| [SaveTitle](../../aspose.diagram.saving/htmlsaveoptions/savetitle/) { get; set; } | Definierar om titeln behöver exporteras eller inte. |
| [SaveToolBar](../../aspose.diagram.saving/htmlsaveoptions/savetoolbar/) { get; set; } | Anger om verktygsfält sparas Standardvärdet är sant. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Hämtar eller ställer in former att rendera. Standardantalet är 0. |
| [StreamProvider](../../aspose.diagram.saving/htmlsaveoptions/streamprovider/) { get; set; } | Hämtar eller ställer in IStreamProvider för export av objekt. |
| [Title](../../aspose.diagram.saving/htmlsaveoptions/title/) { get; set; } | Hämtar eller ställer in diagrammets titel för att rendera i HTML. Om Titel är null Diagram.DocumentProperties.Title[`DocumentProperties`](../../aspose.diagram/documentproperties/) kommer att användas som Title. Om Diagram.DocumentProperties.Title är null eller tom kommer filnamnet för Diagram att användas som Title. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Får eller ställer in varningsåteruppringning. |

### Se även

* class [RenderingSaveOptions](../renderingsaveoptions/)
* namnutrymme [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* hopsättning [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
