---
title: RenderingSaveOptions
second_title: Aspose.Diagram voor .NET API-referentie
description: Dit is een abstracte basisklasse voor klassen waarmee de gebruiker aanvullende opties kan specificeren bij het opslaan van een diagram in een bepaald formaat.
type: docs
weight: 3450
url: /nl/net/aspose.diagram.saving/renderingsaveoptions/
---
## RenderingSaveOptions class

Dit is een abstracte basisklasse voor klassen waarmee de gebruiker aanvullende opties kan specificeren bij het opslaan van een diagram in een bepaald formaat.

```csharp
public abstract class RenderingSaveOptions : SaveOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Hiermee wordt het gebied van de vormen opgehaald of ingesteld. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Wanneer tekens in het diagram unicode zijn en niet zijn ingesteld met de juiste lettertypewaarde of het lettertype niet lokaal is geïnstalleerd, kunnen ze verschijnen als blok in pdf, afbeelding of XPS. Stel het standaardlettertype in, zoals MingLiu of MS Gothic om deze weer te geven karakters. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Instelling voor het weergeven van Emf-metabestand. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Geeft aan of pagina vergroten . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Definieert of de gidsvormen moeten worden geëxporteerd of niet. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Definieert of de opmerkingen moeten worden geëxporteerd of niet. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Haalt of stelt de paginagrootte in voor de gegenereerde afbeeldingen. Kan[`PageSize`](../pagesize/) of null. |
| virtual [SaveFormat](../../aspose.diagram.saving/saveoptions/saveformat/) { get; set; } | Specificeert de indeling waarin het document wordt opgeslagen als dit object met opslagopties wordt gebruikt. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Krijgt of stelt vormen in om te renderen. Standaardtelling is 0. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Krijgt of stelt waarschuwing callback in. |

### Zie ook

* class [SaveOptions](../saveoptions/)
* naamruimte [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->