---
title: ImageSaveOptions
second_title: Aspose.Diagram voor .NET API-referentie
description: Maakt het mogelijk om extra opties te specificeren bij het renderen van diagrampaginas naar afbeeldingen.
type: docs
weight: 3280
url: /nl/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

Maakt het mogelijk om extra opties te specificeren bij het renderen van diagrampagina's naar afbeeldingen.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/)(SaveFileFormat) | Initialiseert een nieuwe instantie van deze klasse die kan worden gebruikt om gerenderde afbeeldingen op te slaan in de[`Tiff`](../../aspose.diagram/savefileformat/) , [`png`](../../aspose.diagram/savefileformat/) ,[`Bmp`](../../aspose.diagram/savefileformat/) ,[`Emf`](../../aspose.diagram/savefileformat/) of[`jpeg`](../../aspose.diagram/savefileformat/) formaat. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Hiermee wordt het gebied van de vormen opgehaald of ingesteld. |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality/) { get; set; } | Specificeert het kwaliteitsniveau dat moet worden gebruikt tijdens het samenstellen. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom/) { get; set; } | Deze parameter is vergelijkbaar met schaal, maar heeft geen invloed op de gegenereerde afbeeldingsgrootte. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Wanneer tekens in het diagram unicode zijn en niet zijn ingesteld met de juiste lettertypewaarde of het lettertype niet lokaal is geïnstalleerd, kunnen ze verschijnen als blok in pdf, afbeelding of XPS. Stel het standaardlettertype in, zoals MingLiu of MS Gothic om deze weer te geven karakters. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Instelling voor het weergeven van Emf-metabestand. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Geeft aan of pagina vergroten . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Definieert of de gidsvormen moeten worden geëxporteerd of niet. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage/) { get; set; } | Bepaalt of de verborgen pagina moet worden geëxporteerd of niet. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness/) { get; set; } | Haalt de helderheid voor de gegenereerde afbeeldingen op of stelt deze in. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode/) { get; set; } | Hiermee wordt de kleurmodus voor de gegenereerde afbeeldingen opgehaald of ingesteld. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast/) { get; set; } | Hiermee wordt het contrast voor de gegenereerde afbeeldingen opgehaald of ingesteld. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode/) { get; set; } | Specificeert het algoritme dat wordt gebruikt wanneer afbeeldingen worden geschaald of geroteerd. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Definieert of de opmerkingen moeten worden geëxporteerd of niet. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality/) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die de kwaliteit van de gegenereerde JPEG-afbeeldingen bepaalt. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount/) { get; set; } | Hiermee wordt het aantal te renderen pagina's opgehaald of ingesteld bij het opslaan in een TIFF-bestand met meerdere pagina's. Standaard is MaxValue, wat betekent dat alle pagina's van het diagram worden weergegeven. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex/) { get; set; } | Haalt de op 0 gebaseerde index op of stelt deze in van de eerste pagina die moet worden weergegeven. Standaard is 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Haalt of stelt de paginagrootte in voor de gegenereerde afbeeldingen. Kan[`PageSize`](../pagesize/) of null. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode/) { get; set; } | Haalt een waarde op of stelt een waarde in die specificeert hoe pixels worden verschoven tijdens het renderen. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution/) { get; set; } | Hiermee wordt de resolutie voor de gegenereerde afbeeldingen opgehaald of ingesteld, in dots per inch. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea/) { get; set; } | Geeft aan of het opslaggebied hetzelfde is als pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly/) { get; set; } | Geeft aan of alle pagina's in afbeelding of alleen op de voorgrond worden opgeslagen. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat/) { get; set; } | Specificeert de indeling waarin de gerenderde diagrampagina's worden opgeslagen als dit object voor opslagopties wordt gebruikt. Kan[`Tiff`](../../aspose.diagram/savefileformat/) ,[`png`](../../aspose.diagram/savefileformat/) , [`Bmp`](../../aspose.diagram/savefileformat/) ,[`Emf`](../../aspose.diagram/savefileformat/) of[`jpeg`](../../aspose.diagram/savefileformat/) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale/) { get; set; } | Haalt of stelt de zoomfactor in voor de gegenereerde afbeeldingen. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Krijgt of stelt vormen in om te renderen. Standaardtelling is 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode/) { get; set; } | Specificeert of vloeiend maken (antialiasing) wordt toegepast op lijnen en curven en de randen van gevulde gebieden. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression/) { get; set; } | Hiermee wordt het type compressie opgehaald of ingesteld dat moet worden toegepast bij het opslaan van gegenereerde afbeeldingen in de TIFF-indeling. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Krijgt of stelt waarschuwing callback in. |

### Zie ook

* class [RenderingSaveOptions](../renderingsaveoptions/)
* naamruimte [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
