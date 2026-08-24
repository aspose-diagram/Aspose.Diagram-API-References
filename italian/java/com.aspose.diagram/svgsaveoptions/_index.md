---
title: SVGSaveOptions
second_title: Riferimento API di Aspose.Diagram per Java
description: Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in SVG.
type: docs
weight: 347
url: /it/java/com.aspose.diagram/svgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class SVGSaveOptions extends RenderingSaveOptions
```

Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in SVG.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SVGSaveOptions()](#SVGSaveOptions--) | Inizializza una nuova istanza di questa classe che può essere utilizzata per salvare un documento nel formato Aspose.Diagram.SaveFileFormat. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crea un oggetto di opzioni di salvataggio di una classe adatta al formato di salvataggio specificato. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomImagePath()](#getCustomImagePath--) | Il percorso personalizzato dell'utente (URL) salvato nel file SVG generato per l'immagine. |
| [getDefaultFont()](#getDefaultFont--) | Quando i caratteri nel diagramma sono Unicode e non vengono impostati con il valore di carattere corretto o il carattere non è installato localmente, possono apparire come blocchi in PDF, immagine o XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Impostazione per il rendering del metafile Emf. |
| [getEnlargePage()](#getEnlargePage--) | Specifica se ingrandire la pagina. |
| [getExportElementAsRectTag()](#getExportElementAsRectTag--) | Definisce se è necessario esportare gli elementi rettangolo come tag rect o meno. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definisce se è necessario esportare le forme guida o meno. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definisce se è necessario esportare la pagina nascosta o meno. |
| [getPageIndex()](#getPageIndex--) | l'indice basato su zero della pagina da renderizzare. |
| [getPageSize()](#getPageSize--) | la dimensione della pagina per le immagini generate. |
| [getQuality()](#getQuality--) | un valore che determina la qualità delle immagini generate da applicare solo quando si salvano le pagine nel formato JPEG. |
| [getSVGFitToViewPort()](#getSVGFitToViewPort--) | se questa proprietà è vera, l'SVG generato si adatterà alla viewport. |
| [getSaveFormat()](#getSaveFormat--) | Specifica il formato in cui il documento verrà salvato se viene utilizzato questo oggetto di opzioni di salvataggio. |
| [getShapes()](#getShapes--) | forme da renderizzare. |
| [getWarningCallback()](#getWarningCallback--) | callback di avviso. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definisce se è necessario esportare i commenti o meno. |
| [isExportScaleInMatrix()](#isExportScaleInMatrix--) | Definisce se è necessario esportare la scala in matrice o meno. |
| [isSavingCustomLinePattern()](#isSavingCustomLinePattern--) | Definisce se salvare il modello di linea personalizzato. |
| [isSavingImageSeparately()](#isSavingImageSeparately--) | Definisce se salvare l'immagine separatamente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomImagePath(String value)](#setCustomImagePath-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Per la descrizione di questa proprietà, vedere [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Per la descrizione di questa proprietà, vedere [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Per la descrizione di questa proprietà, vedere [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\\#isExportComments--) |
| [setExportElementAsRectTag(boolean value)](#setExportElementAsRectTag-boolean-) | Per la descrizione di questa proprietà, vedere [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Per la descrizione di questa proprietà, vedere [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Per la descrizione di questa proprietà, vedere [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--) |
| [setExportScaleInMatrix(boolean value)](#setExportScaleInMatrix-boolean-) | Per la descrizione di questa proprietà, vedere [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Per la descrizione di questa proprietà, vedere [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Per la descrizione di questa proprietà, vedere [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\\#getPageSize--) |
| [setQuality(int value)](#setQuality-int-) | Per la descrizione di questa proprietà, vedere [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--) |
| [setSVGFitToViewPort(boolean value)](#setSVGFitToViewPort-boolean-) | Per la descrizione di questa proprietà, vedere [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Per la descrizione di questa proprietà, vedere [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setSavingCustomLinePattern(boolean value)](#setSavingCustomLinePattern-boolean-) | Per la descrizione di questa proprietà, vedere [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--) |
| [setSavingImageSeparately(boolean value)](#setSavingImageSeparately-boolean-) | Per la descrizione di questa proprietà, vedere [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Per la descrizione di questa proprietà, vedere [getShapes()](../../com.aspose.diagram/renderingsaveoptions\\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SVGSaveOptions() {#SVGSaveOptions--}
```
public SVGSaveOptions()
```


Inizializza una nuova istanza di questa classe che può essere utilizzata per salvare un documento nel formato Aspose.Diagram.SaveFileFormat.

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
### getCustomImagePath() {#getCustomImagePath--}
```
public String getCustomImagePath()
```


Il percorso personalizzato dell'utente (URL) salvato nel file SVG generato per l'immagine. Se non definito dall'utente, verrà utilizzata la directory corrente.

**Returns:**
java.lang.String
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
### getExportElementAsRectTag() {#getExportElementAsRectTag--}
```
public boolean getExportElementAsRectTag()
```


Definisce se è necessario esportare gli elementi rettangolo come tag rect o meno. Il valore predefinito è false.

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
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


l'indice basato su zero della pagina da renderizzare. Il valore predefinito è 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


la dimensione della pagina per le immagini generate. Può essere [PageSize](../../com.aspose.diagram/pagesize) o null. Il valore predefinito è null. Se PageSize è null, la dimensione della pagina per l'immagine generata viene ottenuta dal diagramma di origine.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getQuality() {#getQuality--}
```
public int getQuality()
```


un valore che determina la qualità delle immagini generate da applicare solo quando si salvano le pagine nel formato Jpeg. Il valore predefinito è 100. Ha effetto solo quando si salva in JPEG. Il valore deve essere compreso tra 0 e 100. Il valore predefinito è 100.

**Returns:**
int
### getSVGFitToViewPort() {#getSVGFitToViewPort--}
```
public boolean getSVGFitToViewPort()
```


se questa proprietà è vera, l'SVG generato si adatterà alla viewport.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Specifica il formato in cui il documento verrà salvato se viene utilizzato questo oggetto di opzioni di salvataggio.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


forme da renderizzare. Il conteggio predefinito è 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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
### isExportScaleInMatrix() {#isExportScaleInMatrix--}
```
public boolean isExportScaleInMatrix()
```


Definisce se è necessario esportare la scala in una matrice o meno. Il valore predefinito è true.

**Returns:**
boolean
### isSavingCustomLinePattern() {#isSavingCustomLinePattern--}
```
public boolean isSavingCustomLinePattern()
```


Definisce se salvare il modello di linea personalizzato.

**Returns:**
boolean
### isSavingImageSeparately() {#isSavingImageSeparately--}
```
public boolean isSavingImageSeparately()
```


Definisce se salvare l'immagine separatamente.

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




### setCustomImagePath(String value) {#setCustomImagePath-java.lang.String-}
```
public void setCustomImagePath(String value)
```


Per la descrizione di questa proprietà, vedere [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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

### setExportElementAsRectTag(boolean value) {#setExportElementAsRectTag-boolean-}
```
public void setExportElementAsRectTag(boolean value)
```


Per la descrizione di questa proprietà, vedere [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--)

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


Per la descrizione di questa proprietà, vedere [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setExportScaleInMatrix(boolean value) {#setExportScaleInMatrix-boolean-}
```
public void setExportScaleInMatrix(boolean value)
```


Per la descrizione di questa proprietà, vedere [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Per la descrizione di questa proprietà, vedere [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--)

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Per la descrizione di questa proprietà, vedere [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSVGFitToViewPort(boolean value) {#setSVGFitToViewPort-boolean-}
```
public void setSVGFitToViewPort(boolean value)
```


Per la descrizione di questa proprietà, vedere [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Per la descrizione di questa proprietà, vedere [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSavingCustomLinePattern(boolean value) {#setSavingCustomLinePattern-boolean-}
```
public void setSavingCustomLinePattern(boolean value)
```


Per la descrizione di questa proprietà, vedere [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSavingImageSeparately(boolean value) {#setSavingImageSeparately-boolean-}
```
public void setSavingImageSeparately(boolean value)
```


Per la descrizione di questa proprietà, vedere [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Per la descrizione di questa proprietà, vedere [getShapes()](../../com.aspose.diagram/renderingsaveoptions\\#getShapes--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

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

