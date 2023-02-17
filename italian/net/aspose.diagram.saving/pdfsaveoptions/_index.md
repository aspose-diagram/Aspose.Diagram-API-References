---
title: PdfSaveOptions
second_title: Aspose.Diagram per riferimento API .NET
description: Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in PDF.
type: docs
weight: 3410
url: /it/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in PDF.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Inizializza una nuova istanza di questa classe che può essere utilizzata per salvare un documento in[`PDF`](../../aspose.diagram/savefileformat/) formato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Ottiene o imposta l'area delle forme che verranno salvate . |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance/) { get; set; } | Livello di conformità desiderato per il documento PDF generato. L'impostazione predefinita èPdf15 . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Quando i caratteri nel diagramma sono Unicode e non devono essere impostati con il valore del font corretto o il font non è installato localmente, possono apparire come blocchi in pdf, immagine o XPS. Imposta il DefaultFont come MingLiu o MS Gothic per mostrarli caratteri. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails/) { get; set; } | Ottiene o imposta i dettagli di una firma digitale. Se non impostato, non verrà eseguita alcuna firma. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Impostazione per il rendering del metafile Emf. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails/) { get; set; } | Ottiene o imposta i dettagli di crittografia. Se non impostato, non verrà eseguita alcuna crittografia. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Specifica se ingrandire la pagina . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Definisce se è necessario esportare o meno le forme guida. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage/) { get; set; } | Definisce se è necessario esportare o meno la pagina nascosta. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution/) { get; set; } | Ottiene o imposta la risoluzione orizzontale per le immagini generate, in punti per pollice. Applica il metodo di generazione dell'immagine tranne le immagini in formato Emf. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Definisce se è necessario esportare o meno i commenti. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality/) { get; set; } | Specifica la qualità della compressione JPEG per le immagini (se viene utilizzata la compressione JPEG). Il valore predefinito è 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount/) { get; set; } | Ottiene o imposta il numero di pagine di cui eseguire il rendering in PDF. L'impostazione predefinita è MaxValue, il che significa che verranno visualizzate tutte le pagine del diagramma. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex/) { get; set; } | Ottiene o imposta l'indice in base 0 della prima pagina di cui eseguire il rendering. Il valore predefinito è 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback/) { get; set; } | Controlla/Indica l'avanzamento del processo di salvataggio della pagina. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Ottiene o imposta la dimensione della pagina per le immagini generate. Può essere[`PageSize`](../pagesize/) o nullo. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly/) { get; set; } | Specifica se tutte le pagine verranno salvate nell'immagine o solo in primo piano. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat/) { get; set; } | Specifica il formato in cui verranno salvate le pagine del diagramma renderizzate se viene utilizzato questo oggetto delle opzioni di salvataggio. Può essere[`PDF`](../../aspose.diagram/savefileformat/) solo. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Ottiene o imposta le forme di cui eseguire il rendering. Il conteggio predefinito è 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages/) { get; set; } | Definisce se suddividere il diagramma in più pagine in base all'impostazione della pagina. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression/) { get; set; } | Specifica il tipo di compressione da utilizzare per tutti i flussi di contenuto tranne le immagini. L'impostazione predefinita èFlate . |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution/) { get; set; } | Ottiene o imposta la risoluzione verticale per le immagini generate, in punti per pollice. Applica il metodo di generazione dell'immagine tranne l'immagine in formato Emf. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback/) { get; set; } | Ottiene o imposta la richiamata di avviso. |

### Guarda anche

* class [RenderingSaveOptions](../renderingsaveoptions/)
* spazio dei nomi [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* assemblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
