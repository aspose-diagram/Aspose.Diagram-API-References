---
title: ImageSaveOptions
second_title: Aspose.Diagram per riferimento API .NET
description: Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in immagini.
type: docs
weight: 3280
url: /it/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in immagini.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/)(SaveFileFormat) | Inizializza una nuova istanza di questa classe che può essere utilizzata per salvare le immagini renderizzate in[`TIFF`](../../aspose.diagram/savefileformat/) , [`PNG`](../../aspose.diagram/savefileformat/) ,[`Bmp`](../../aspose.diagram/savefileformat/) ,[`Fem`](../../aspose.diagram/savefileformat/) o[`JPEG`](../../aspose.diagram/savefileformat/) formato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Ottiene o imposta l'area delle forme che verranno salvate . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality/) { get; set; } | Specifica il livello di qualità da utilizzare durante la composizione. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom/) { get; set; } | Questo parametro è simile alla scala, ma non influisce sulla dimensione dell'immagine generata. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Quando i caratteri nel diagramma sono Unicode e non devono essere impostati con il valore del font corretto o il font non è installato localmente, possono apparire come blocchi in pdf, immagine o XPS. Imposta il DefaultFont come MingLiu o MS Gothic per mostrarli caratteri. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Impostazione per il rendering del metafile Emf. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Specifica se ingrandire la pagina . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Definisce se è necessario esportare o meno le forme guida. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage/) { get; set; } | Definisce se è necessario esportare o meno la pagina nascosta. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness/) { get; set; } | Ottiene o imposta la luminosità per le immagini generate. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode/) { get; set; } | Ottiene o imposta la modalità colore per le immagini generate. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast/) { get; set; } | Ottiene o imposta il contrasto per le immagini generate. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode/) { get; set; } | Specifica l'algoritmo utilizzato quando le immagini vengono ridimensionate o ruotate. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Definisce se è necessario esportare o meno i commenti. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality/) { get; set; } | Ottiene o imposta un valore che determina la qualità delle immagini JPEG generate. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount/) { get; set; } | Ottiene o imposta il numero di pagine di cui eseguire il rendering durante il salvataggio in un file TIFF multipagina. L'impostazione predefinita è MaxValue, il che significa che verrà eseguito il rendering di tutte le pagine del diagramma. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex/) { get; set; } | Ottiene o imposta l'indice in base 0 della prima pagina di cui eseguire il rendering. Il valore predefinito è 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Ottiene o imposta la dimensione della pagina per le immagini generate. Può essere[`PageSize`](../pagesize/) o nullo. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode/) { get; set; } | Ottiene o imposta un valore che specifica la modalità di offset dei pixel durante il rendering. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution/) { get; set; } | Ottiene o imposta la risoluzione per le immagini generate, in punti per pollice. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea/) { get; set; } | Specifica se l'area di salvataggio è uguale a pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly/) { get; set; } | Specifica se tutte le pagine verranno salvate nell'immagine o solo in primo piano. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat/) { get; set; } | Specifica il formato in cui verranno salvate le pagine del diagramma renderizzate se viene utilizzato questo oggetto delle opzioni di salvataggio. Può essere[`TIFF`](../../aspose.diagram/savefileformat/) ,[`PNG`](../../aspose.diagram/savefileformat/) , [`Bmp`](../../aspose.diagram/savefileformat/) ,[`Fem`](../../aspose.diagram/savefileformat/) O[`JPEG`](../../aspose.diagram/savefileformat/) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale/) { get; set; } | Ottiene o imposta il fattore di zoom per le immagini generate. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Ottiene o imposta le forme di cui eseguire il rendering. Il conteggio predefinito è 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode/) { get; set; } | Specifica se l'attenuazione (antialiasing) viene applicata a linee e curve e ai bordi delle aree piene. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression/) { get; set; } | Ottiene o imposta il tipo di compressione da applicare quando si salvano le immagini generate nel formato TIFF. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Ottiene o imposta la richiamata di avviso. |

### Guarda anche

* class [RenderingSaveOptions](../renderingsaveoptions/)
* spazio dei nomi [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* assemblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
