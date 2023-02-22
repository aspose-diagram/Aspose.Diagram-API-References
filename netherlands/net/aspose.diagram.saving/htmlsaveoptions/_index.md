---
title: HTMLSaveOptions
second_title: Aspose.Diagram voor .NET API-referentie
description: Maakt het mogelijk om extra opties te specificeren bij het renderen van diagrampaginas naar HTML.
type: docs
weight: 3240
url: /nl/net/aspose.diagram.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Maakt het mogelijk om extra opties te specificeren bij het renderen van diagrampagina's naar HTML.

```csharp
public class HTMLSaveOptions : RenderingSaveOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | Initialiseert een nieuwe instantie van deze klasse die kan worden gebruikt om een document op te slaan in het[`HTML`](../../aspose.diagram/savefileformat/) formaat. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Hiermee wordt het gebied van de vormen opgehaald of ingesteld. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Wanneer tekens in het diagram unicode zijn en niet zijn ingesteld met de juiste lettertypewaarde of het lettertype niet lokaal is geïnstalleerd, kunnen ze verschijnen als blok in pdf, afbeelding of XPS. Stel het standaardlettertype in, zoals MingLiu of MS Gothic om deze weer te geven karakters. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Instelling voor het weergeven van Emf-metabestand. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Geeft aan of pagina vergroten . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Definieert of de gidsvormen moeten worden geëxporteerd of niet. |
| [ExportHiddenPage](../../aspose.diagram.saving/htmlsaveoptions/exporthiddenpage/) { get; set; } | Bepaalt of de verborgen pagina moet worden geëxporteerd of niet. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Definieert of de opmerkingen moeten worden geëxporteerd of niet. |
| [PageCount](../../aspose.diagram.saving/htmlsaveoptions/pagecount/) { get; set; } | Hiermee wordt het aantal pagina's dat moet worden weergegeven in HTML opgehaald of ingesteld. Standaard is MaxValue, wat betekent dat alle pagina's van het diagram worden weergegeven. |
| [PageIndex](../../aspose.diagram.saving/htmlsaveoptions/pageindex/) { get; set; } | Haalt de op 0 gebaseerde index op of stelt deze in van de eerste pagina die moet worden weergegeven. Standaard is 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Haalt of stelt de paginagrootte in voor de gegenereerde afbeeldingen. Kan[`PageSize`](../pagesize/) of null. |
| [Resolution](../../aspose.diagram.saving/htmlsaveoptions/resolution/) { get; set; } | Haalt de resolutie voor de gegenereerde html op of stelt deze in, in dots per inch. |
| [SaveAsSingleFile](../../aspose.diagram.saving/htmlsaveoptions/saveassinglefile/) { get; set; } | Geeft aan of de html als enkel bestand moet worden opgeslagen. De standaardwaarde is false. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/htmlsaveoptions/saveforegroundpagesonly/) { get; set; } | Geeft aan of alle pagina's in afbeelding of alleen op de voorgrond worden opgeslagen. |
| override [SaveFormat](../../aspose.diagram.saving/htmlsaveoptions/saveformat/) { get; set; } | Specificeert de indeling waarin de gerenderde diagrampagina's worden opgeslagen als dit object voor opslagopties wordt gebruikt. Kan[`HTML`](../../aspose.diagram/savefileformat/) alleen. |
| [SaveTitle](../../aspose.diagram.saving/htmlsaveoptions/savetitle/) { get; set; } | Definieert of de titel moet worden geëxporteerd of niet. |
| [SaveToolBar](../../aspose.diagram.saving/htmlsaveoptions/savetoolbar/) { get; set; } | Specificeert of werkbalk opslaan De standaardwaarde is waar. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Krijgt of stelt vormen in om te renderen. Standaardtelling is 0. |
| [StreamProvider](../../aspose.diagram.saving/htmlsaveoptions/streamprovider/) { get; set; } | Haalt de IStreamProvider op of stelt deze in voor het exporteren van objecten. |
| [Title](../../aspose.diagram.saving/htmlsaveoptions/title/) { get; set; } | Haalt de titel van het diagram op of stelt deze in om weer te geven in HTML. Als Titel null is Diagram.DocumentProperties.Title[`DocumentProperties`](../../aspose.diagram/documentproperties/) wordt gebruikt als Title. Als Diagram.DocumentProperties.Title null of leeg is, wordt de bestandsnaam van Diagram gebruikt als Title. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Krijgt of stelt waarschuwing callback in. |

### Zie ook

* class [RenderingSaveOptions](../renderingsaveoptions/)
* naamruimte [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
