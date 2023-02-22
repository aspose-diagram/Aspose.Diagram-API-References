---
title: PdfSaveOptions
second_title: Aspose.Diagram voor .NET API-referentie
description: Maakt het mogelijk om extra opties te specificeren bij het renderen van diagrampaginas naar PDF.
type: docs
weight: 3410
url: /nl/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Maakt het mogelijk om extra opties te specificeren bij het renderen van diagrampagina's naar PDF.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Initialiseert een nieuwe instantie van deze klasse die kan worden gebruikt om een document op te slaan in het[`Pdf`](../../aspose.diagram/savefileformat/) formaat. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Hiermee wordt het gebied van de vormen opgehaald of ingesteld. |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance/) { get; set; } | Gewenst conformiteitsniveau voor gegenereerd PDF-document. Standaard isPdf15 . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Wanneer tekens in het diagram unicode zijn en niet zijn ingesteld met de juiste lettertypewaarde of het lettertype niet lokaal is geïnstalleerd, kunnen ze verschijnen als blok in pdf, afbeelding of XPS. Stel het standaardlettertype in, zoals MingLiu of MS Gothic om deze weer te geven karakters. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails/) { get; set; } | Haalt of stelt een digitale handtekening in. Indien niet ingesteld, wordt er niet ondertekend. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Instelling voor het weergeven van Emf-metabestand. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails/) { get; set; } | Verkrijgt of stelt coderingsdetails in. Indien niet ingesteld, wordt er geen codering uitgevoerd. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Geeft aan of pagina vergroten . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Definieert of de gidsvormen moeten worden geëxporteerd of niet. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage/) { get; set; } | Bepaalt of de verborgen pagina moet worden geëxporteerd of niet. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution/) { get; set; } | Hiermee wordt de horizontale resolutie voor gegenereerde afbeeldingen opgehaald of ingesteld, in dots per inch. Past de methode voor het genereren van afbeeldingen toe, behalve afbeeldingen in Emf-indeling. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Definieert of de opmerkingen moeten worden geëxporteerd of niet. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality/) { get; set; } | Specificeert de kwaliteit van JPEG-compressie voor afbeeldingen (als JPEG-compressie wordt gebruikt). Standaard is 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount/) { get; set; } | Haalt het aantal te renderen pagina's in PDF op of stelt het in. Standaard is MaxValue, wat betekent dat alle pagina's van het diagram worden gerenderd. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex/) { get; set; } | Haalt de op 0 gebaseerde index op of stelt deze in van de eerste pagina die moet worden weergegeven. Standaard is 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback/) { get; set; } | Voortgang van het opslaan van pagina's controleren/aangeven. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Haalt of stelt de paginagrootte in voor de gegenereerde afbeeldingen. Kan[`PageSize`](../pagesize/) of null. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly/) { get; set; } | Geeft aan of alle pagina's in afbeelding of alleen op de voorgrond worden opgeslagen. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat/) { get; set; } | Specificeert de indeling waarin de gerenderde diagrampagina's worden opgeslagen als dit object voor opslagopties wordt gebruikt. Kan[`Pdf`](../../aspose.diagram/savefileformat/) alleen. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Krijgt of stelt vormen in om te renderen. Standaardtelling is 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages/) { get; set; } | Definieert of het diagram wordt gesplitst naar meerdere pagina's volgens de pagina-instelling. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression/) { get; set; } | Specificeert het compressietype dat moet worden gebruikt voor alle inhoudsstromen behalve afbeeldingen. Standaard isFlate . |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution/) { get; set; } | Hiermee wordt de verticale resolutie voor gegenereerde afbeeldingen opgehaald of ingesteld, in dots per inch. Past de methode voor het genereren van afbeeldingen toe, behalve afbeelding in Emf-indeling. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback/) { get; set; } | Krijgt of stelt waarschuwing callback in. |

### Zie ook

* class [RenderingSaveOptions](../renderingsaveoptions/)
* naamruimte [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
