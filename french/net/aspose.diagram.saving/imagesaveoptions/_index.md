---
title: ImageSaveOptions
second_title: Référence de l'API Aspose.Diagram pour .NET
description: Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en images.
type: docs
weight: 3270
url: /fr/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

Permet de spécifier des options supplémentaires lors du rendu des pages de diagramme en images.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions)(SaveFileFormat) | Initialise une nouvelle instance de cette classe qui peut être utilisée pour enregistrer les images rendues dans le[`Tif`](../../aspose.diagram/savefileformat) , [`PNG`](../../aspose.diagram/savefileformat) ,[`bmp`](../../aspose.diagram/savefileformat) ,[`CEM`](../../aspose.diagram/savefileformat) ou[`JPEG`](../../aspose.diagram/savefileformat)format. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area) { get; set; } | Obtient ou définit la zone des formes qui seront enregistrées . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality) { get; set; } | Spécifie le niveau de qualité à utiliser lors de la composition. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom) { get; set; } | Ce paramètre est similaire à l'échelle, mais n'affecte pas la taille de l'image générée. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | Lorsque les caractères du diagramme sont Unicode et ne sont pas définis avec la valeur de police correcte ou que la police n'est pas installée localement, ils peuvent apparaître sous forme de bloc dans pdf, image ou XPS. Définissez la police par défaut telle que MingLiu ou MS Gothic pour les afficher caractères. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting) { get; set; } | Paramètre pour le rendu du métafichier Emf. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage) { get; set; } | Spécifie si agrandir la page . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes) { get; set; } | Définit s'il est nécessaire ou non d'exporter les formes de guidage. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage) { get; set; } | Définit s'il faut exporter la page masquée ou non. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness) { get; set; } | Obtient ou définit la luminosité des images générées. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode) { get; set; } | Obtient ou définit le mode de couleur pour les images générées. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast) { get; set; } | Obtient ou définit le contraste des images générées. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode) { get; set; } | Spécifie l'algorithme utilisé lorsque les images sont mises à l'échelle ou pivotées. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments) { get; set; } | Définit s'il faut ou non exporter les commentaires. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality) { get; set; } | Obtient ou définit une valeur déterminant la qualité des images JPEG générées. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount) { get; set; } | Obtient ou définit le nombre de pages à rendre lors de l'enregistrement dans un fichier TIFF multipage. La valeur par défaut est MaxValue, ce qui signifie que toutes les pages du diagramme seront rendues. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex) { get; set; } | Obtient ou définit l'index de base 0 de la première page à afficher. La valeur par défaut est 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize) { get; set; } | Obtient ou définit la taille de la page pour les images générées. Peut être[`PageSize`](../pagesize) ou null. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode) { get; set; } | Obtient ou définit une valeur spécifiant comment les pixels sont décalés pendant le rendu. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution) { get; set; } | Obtient ou définit la résolution des images générées, en points par pouce. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea) { get; set; } | Spécifie si la zone d'enregistrement est identique à pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly) { get; set; } | Spécifie si toutes les pages seront enregistrées en image ou uniquement au premier plan. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat) { get; set; } | Spécifie le format dans lequel les pages de diagramme rendues seront enregistrées si cet objet d'options d'enregistrement est utilisé. Peut être[`Tif`](../../aspose.diagram/savefileformat) ,[`PNG`](../../aspose.diagram/savefileformat) , [`bmp`](../../aspose.diagram/savefileformat) ,[`CEM`](../../aspose.diagram/savefileformat) ou[`JPEG`](../../aspose.diagram/savefileformat). |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale) { get; set; } | Obtient ou définit le facteur de zoom pour les images générées. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes) { get; set; } | Obtient ou définit les formes à afficher. Le nombre par défaut est 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode) { get; set; } | Spécifie si le lissage (anticrénelage) est appliqué aux lignes et aux courbes et aux bords des zones remplies. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression) { get; set; } | Obtient ou définit le type de compression à appliquer lors de l'enregistrement des images générées au format TIFF. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | Obtient ou définit un rappel d'avertissement. |

### Voir également

* class [RenderingSaveOptions](../renderingsaveoptions)
* espace de noms [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* Assemblée [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
