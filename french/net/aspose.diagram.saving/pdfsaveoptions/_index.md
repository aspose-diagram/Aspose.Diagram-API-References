---
title: PdfSaveOptions
second_title: Référence de l'API Aspose.Diagram pour .NET
description: Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme au format PDF.
type: docs
weight: 3410
url: /fr/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme au format PDF.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer un document dans le[`PDF`](../../aspose.diagram/savefileformat/) format. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Obtient ou définit la zone des formes qui seront enregistrées . |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance/) { get; set; } | Niveau de conformité souhaité pour le document PDF généré. La valeur par défaut estPdf15 . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Lorsque les caractères du diagramme sont Unicode et ne sont pas définis avec la valeur de police correcte ou que la police n'est pas installée localement, ils peuvent apparaître sous forme de bloc dans pdf, image ou XPS. Définissez la police par défaut telle que MingLiu ou MS Gothic pour les afficher caractères. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails/) { get; set; } | Obtient ou définit les détails d'une signature numérique. S'il n'est pas défini, aucune signature ne sera effectuée. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Paramètre pour le rendu du métafichier Emf. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails/) { get; set; } | Obtient ou définit les détails d'un chiffrement. S'il n'est pas défini, aucun chiffrement ne sera effectué. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Spécifie si agrandir la page . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Définit s'il est nécessaire ou non d'exporter les formes de guidage. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage/) { get; set; } | Définit s'il faut exporter la page masquée ou non. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution/) { get; set; } | Obtient ou définit la résolution horizontale des images générées, en points par pouce. Applique la méthode de génération d'image à l'exception des images au format Emf. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Définit s'il faut ou non exporter les commentaires. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality/) { get; set; } | Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée). La valeur par défaut est 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount/) { get; set; } | Obtient ou définit le nombre de pages à rendre en PDF. La valeur par défaut est MaxValue, ce qui signifie que toutes les pages du diagramme seront rendues. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex/) { get; set; } | Obtient ou définit l'index de base 0 de la première page à afficher. La valeur par défaut est 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback/) { get; set; } | Contrôler/Indiquer la progression du processus d'enregistrement de la page. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Obtient ou définit la taille de la page pour les images générées. Peut être[`PageSize`](../pagesize/) ou null. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly/) { get; set; } | Spécifie si toutes les pages seront enregistrées en image ou uniquement au premier plan. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat/) { get; set; } | Spécifie le format dans lequel les pages de diagramme rendues seront enregistrées si cet objet d'options d'enregistrement est utilisé. Peut être[`PDF`](../../aspose.diagram/savefileformat/) seulement. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Obtient ou définit les formes à afficher. Le nombre par défaut est 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages/) { get; set; } | Définit si le diagramme est divisé en plusieurs pages en fonction des paramètres de la page. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression/) { get; set; } | Spécifie le type de compression à utiliser pour tous les flux de contenu à l'exception des images. La valeur par défaut estFlate . |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution/) { get; set; } | Obtient ou définit la résolution verticale des images générées, en points par pouce. Applique la méthode de génération d'image à l'exception de l'image au format Emf. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback/) { get; set; } | Obtient ou définit un rappel d'avertissement. |

### Voir également

* class [RenderingSaveOptions](../renderingsaveoptions/)
* espace de noms [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* Assemblée [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
