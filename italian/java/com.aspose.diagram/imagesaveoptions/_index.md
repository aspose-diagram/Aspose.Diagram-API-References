---
title: ImageSaveOptions
second_title: Riferimento API di Aspose.Diagram per Java
description: Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in immagini.
type: docs
weight: 200
url: /it/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in immagini.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | Inizializza una nuova istanza di questa classe che può essere utilizzata per salvare immagini renderizzate nei formati Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat o Aspose.Diagram.SaveFileFormat. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crea un oggetto di opzioni di salvataggio di una classe adatta al formato di salvataggio specificato. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | Specifica il livello di qualità da utilizzare durante il compositing. |
| [getContentZoom()](#getContentZoom--) | Questo parametro è simile alla scala, ma non influisce sulla dimensione dell'immagine generata. |
| [getDefaultFont()](#getDefaultFont--) | Quando i caratteri nel diagramma sono Unicode e non vengono impostati con il valore di carattere corretto o il carattere non è installato localmente, possono apparire come blocchi in PDF, immagine o XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Impostazione per il rendering del metafile Emf. |
| [getEnlargePage()](#getEnlargePage--) | Specifica se ingrandire la pagina. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definisce se è necessario esportare le forme guida o meno. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definisce se è necessario esportare la pagina nascosta o meno. |
| [getImageBrightness()](#getImageBrightness--) | la luminosità per le immagini generate. |
| [getImageColorMode()](#getImageColorMode--) | la modalità colore per le immagini generate. |
| [getImageContrast()](#getImageContrast--) | il contrasto per le immagini generate. |
| [getInterpolationMode()](#getInterpolationMode--) | Specifica l'algoritmo utilizzato quando le immagini vengono scalate o ruotate. |
| [getJpegQuality()](#getJpegQuality--) | un valore che determina la qualità delle immagini JPEG generate. |
| [getPageCount()](#getPageCount--) | il numero di pagine da renderizzare durante il salvataggio in un file TIFF multipagina. |
| [getPageIndex()](#getPageIndex--) | l'indice basato su zero della prima pagina da renderizzare. |
| [getPageSize()](#getPageSize--) | la dimensione della pagina per le immagini generate. |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | un valore che specifica come i pixel sono spostati durante il rendering. |
| [getResolution()](#getResolution--) | la risoluzione per le immagini generate, in punti per pollice. |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | Specifica se l'area di salvataggio è la stessa del PDF. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specifica se tutte le pagine saranno salvate come immagine o solo il primo piano. |
| [getSaveFormat()](#getSaveFormat--) | Specifica il formato in cui le pagine del diagramma renderizzate saranno salvate se viene utilizzato questo oggetto di opzioni di salvataggio. |
| [getScale()](#getScale--) | il fattore di zoom per le immagini generate. |
| [getShapes()](#getShapes--) | forme da renderizzare. |
| [getSmoothingMode()](#getSmoothingMode--) | Specifica se l'anti-aliasing (smussatura) è applicato a linee e curve e ai bordi delle aree riempite. |
| [getTiffCompression()](#getTiffCompression--) | il tipo di compressione da applicare quando si salvano le immagini generate nel formato TIFF. |
| [getWarningCallback()](#getWarningCallback--) | callback di avviso. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definisce se è necessario esportare i commenti o meno. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Per la descrizione di questa proprietà, consultare [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) |
| [setContentZoom(float value)](#setContentZoom-float-) | Per la descrizione di questa proprietà, consultare [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Per la descrizione di questa proprietà, vedere [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Per la descrizione di questa proprietà, vedere [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Per la descrizione di questa proprietà, vedere [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Per la descrizione di questa proprietà, vedere [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Per la descrizione di questa proprietà, consultare [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) |
| [setImageBrightness(float value)](#setImageBrightness-float-) | Per la descrizione di questa proprietà, consultare [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) |
| [setImageColorMode(int value)](#setImageColorMode-int-) | Per la descrizione di questa proprietà, consultare [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) |
| [setImageContrast(float value)](#setImageContrast-float-) | Per la descrizione di questa proprietà, consultare [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Per la descrizione di questa proprietà, consultare [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Per la descrizione di questa proprietà, consultare [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Per la descrizione di questa proprietà, consultare [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Per la descrizione di questa proprietà, consultare [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Per la descrizione di questa proprietà, vedere [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | Per la descrizione di questa proprietà, consultare [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) |
| [setResolution(float value)](#setResolution-float-) | Per la descrizione di questa proprietà, consultare [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | Per la descrizione di questa proprietà, consultare [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Per la descrizione di questa proprietà, consultare [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Per la descrizione di questa proprietà, consultare [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) |
| [setScale(float value)](#setScale-float-) | Per la descrizione di questa proprietà, consultare [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Per la descrizione di questa proprietà, vedere [getShapes()](../../com.aspose.diagram/renderingsaveoptions\\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Per la descrizione di questa proprietà, consultare [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) |
| [setTiffCompression(int value)](#setTiffCompression-int-) | Per la descrizione di questa proprietà, consultare [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


Inizializza una nuova istanza di questa classe che può essere utilizzata per salvare immagini renderizzate nei formati Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat o Aspose.Diagram.SaveFileFormat.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| saveFormat | int | Può essere Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat o Aspose.Diagram.SaveFileFormat. |

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Crea un oggetto di opzioni di salvataggio di una classe adatta al formato di salvataggio specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| saveFormat | int | Il Aspose.Diagram.SaveFileFormat per il quale creare un oggetto di opzioni di salvataggio. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Specifica il livello di qualità da utilizzare durante il compositing. Questa proprietà ha effetto solo quando si salva in formati di immagine raster. Il valore predefinito è Aspose.Diagram.Saving.CompositingQuality.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


Questo parametro è simile a scala, ma non influisce sulla dimensione dell'immagine generata. Il valore predefinito è 1.0. Il valore deve essere maggiore di 0.

**Returns:**
float
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


Quando i caratteri nel diagramma sono Unicode e non sono impostati con il valore di font corretto o il font non è installato localmente, possono apparire come blocchi in PDF, immagine o XPS. Impostare il DefaultFont, ad esempio MingLiu o MS Gothic, per visualizzare questi caratteri.

**Returns:**
java.lang.String
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Impostazione per il rendering dei metafile EMF. I metafile EMF identificati come "EMF+ Dual" possono contenere sia record EMF+ sia record EMF. Entrambi i tipi di record possono essere usati per renderizzare l'immagine, solo record EMF+, o solo record EMF. Quando EmfPlusPrefer è impostato, i record EMF+ verranno analizzati, altrimenti verranno analizzati solo i record EMF. Il valore predefinito è EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


Specifica se ingrandire la pagina. Se true - ingrandire la pagina. Se false - non ingrandire la pagina. Il valore predefinito è true.

**Returns:**
boolean
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


Definisce se è necessario esportare le forme guida o meno. Il valore predefinito è true.

**Returns:**
boolean
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Definisce se è necessario esportare la pagina nascosta o meno. Il valore predefinito è true.

**Returns:**
boolean
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


la luminosità per le immagini generate. Questa proprietà ha effetto solo quando si salva in formati di immagine raster. Il valore predefinito è 0.5. Il valore deve essere compreso nell'intervallo tra 0 e 1.

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


la modalità colore per le immagini generate. Questa proprietà ha effetto solo quando si salva in formati di immagine raster. Il valore predefinito è Aspose.Diagram.Saving.ImageColorMode.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


il contrasto per le immagini generate. Questa proprietà ha effetto solo quando si salva in formati di immagine raster. Il valore predefinito è 0.5. Il valore deve essere compreso nell'intervallo tra 0 e 1.

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Specifica l'algoritmo utilizzato quando le immagini vengono scalate o ruotate. Questa proprietà ha effetto solo quando si salva in formati di immagine raster. Il valore predefinito è Aspose.Diagram.Saving.InterpolationMode.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


un valore che determina la qualità delle immagini JPEG generate. Ha effetto solo quando si salva in JPEG. Usa questa proprietà per ottenere o impostare la qualità delle immagini generate quando si salva in formato JPEG. Il valore può variare da 0 a 100 dove 0 indica la qualità più bassa ma la massima compressione e 100 indica la migliore qualità ma la compressione minima. Il valore predefinito è 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


il numero di pagine da rendere quando si salva in un file TIFF multipagina. Il valore predefinito è MaxValue, che significa che tutte le pagine del diagramma verranno renderizzate.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


L'indice basato su zero della prima pagina da renderizzare. Il valore predefinito è 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


la dimensione della pagina per le immagini generate. Può essere [PageSize](../../com.aspose.diagram/pagesize) o null. Il valore predefinito è null. Se PageSize è null, la dimensione della pagina per l'immagine generata viene ottenuta dal diagramma di origine.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


un valore che specifica come i pixel vengono spostati durante il rendering. Questa proprietà ha effetto solo quando si salva in formati di immagine raster. Il valore predefinito è Aspose.Diagram.Saving.PixelOffsetMode.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


la risoluzione per le immagini generate, in punti per pollice. Questa proprietà ha effetto solo quando si salva in formati di immagine raster. Il valore predefinito è 96.

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


Specifica se l'area di salvataggio è la stessa del PDF. Se vero - l'area renderizzata è la stessa del PDF. Se falso - l'area renderizzata è quella predefinita. Il valore predefinito è false.

**Returns:**
boolean
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Specifica se tutte le pagine saranno salvate in immagine o solo il primo piano. Se true - vengono renderizzate solo le pagine di primo piano (con lo sfondo se presente). Se false - vengono renderizzate le pagine di primo piano (con lo sfondo se presente) seguite da pagine di sfondo vuote. Può restituire true solo quando PageCount > 1. Il valore predefinito è false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Specifica il formato in cui le pagine del diagramma renderizzate saranno salvate se viene utilizzato questo oggetto di opzioni di salvataggio. Può essere Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat o Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


il fattore di zoom per le immagini generate. Il valore predefinito è 1.0. Il valore deve essere maggiore di 0.

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


forme da renderizzare. Il conteggio predefinito è 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Specifica se l'anti-aliasing (smussatura) è applicato a linee e curve e ai bordi delle aree riempite. Questa proprietà ha effetto solo quando si salva in formati di immagine raster. Il valore predefinito è Aspose.Diagram.Saving.SmoothingMode.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


il tipo di compressione da applicare quando si salvano le immagini generate nel formato TIFF. Ha effetto solo quando si salva in TIFF. Il valore predefinito è Aspose.Diagram.Saving.TiffCompression.

**Returns:**
int
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


callback di avviso.

**Returns:**
[IWarningCallback](../../com.aspose.diagram/iwarningcallback)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExportComments() {#isExportComments--}
```
public boolean isExportComments()
```


Definisce se è necessario esportare i commenti o meno. Il valore predefinito è false.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Per la descrizione di questa proprietà, consultare [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


Per la descrizione di questa proprietà, consultare [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Per la descrizione di questa proprietà, vedere [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


Per la descrizione di questa proprietà, vedere [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


Per la descrizione di questa proprietà, vedere [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\\#getEnlargePage--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


Per la descrizione di questa proprietà, vedere [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\\#isExportComments--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


Per la descrizione di questa proprietà, vedere [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\\#getExportGuideShapes--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Per la descrizione di questa proprietà, consultare [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


Per la descrizione di questa proprietà, consultare [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


Per la descrizione di questa proprietà, consultare [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


Per la descrizione di questa proprietà, consultare [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Per la descrizione di questa proprietà, consultare [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Per la descrizione di questa proprietà, consultare [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Per la descrizione di questa proprietà, consultare [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Per la descrizione di questa proprietà, consultare [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Per la descrizione di questa proprietà, vedere [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\\#getPageSize--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


Per la descrizione di questa proprietà, consultare [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Per la descrizione di questa proprietà, consultare [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


Per la descrizione di questa proprietà, consultare [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Per la descrizione di questa proprietà, consultare [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Per la descrizione di questa proprietà, consultare [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


Per la descrizione di questa proprietà, consultare [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Per la descrizione di questa proprietà, vedere [getShapes()](../../com.aspose.diagram/renderingsaveoptions\\#getShapes--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Per la descrizione di questa proprietà, consultare [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


Per la descrizione di questa proprietà, consultare [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.diagram/iwarningcallback) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

