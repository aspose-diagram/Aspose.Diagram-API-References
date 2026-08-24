---
title: HTMLSaveOptions
second_title: Riferimento API di Aspose.Diagram per Java
description: Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in HTML.
type: docs
weight: 187
url: /it/java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in HTML.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | Inizializza una nuova istanza di questa classe che può essere utilizzata per salvare un documento nel formato Aspose.Diagram.SaveFileFormat. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crea un oggetto di opzioni di salvataggio di una classe adatta al formato di salvataggio specificato. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Quando i caratteri nel diagramma sono Unicode e non vengono impostati con il valore di carattere corretto o il carattere non è installato localmente, possono apparire come blocchi in PDF, immagine o XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Impostazione per il rendering del metafile Emf. |
| [getEnlargePage()](#getEnlargePage--) | Specifica se ingrandire la pagina. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definisce se è necessario esportare le forme guida o meno. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definisce se è necessario esportare la pagina nascosta o meno. |
| [getPageCount()](#getPageCount--) | il numero di pagine da renderizzare in HTML. |
| [getPageIndex()](#getPageIndex--) | l'indice basato su zero della prima pagina da renderizzare. |
| [getPageSize()](#getPageSize--) | la dimensione della pagina per le immagini generate. |
| [getResolution()](#getResolution--) | la risoluzione per l'HTML generato, in punti per pollice. |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | Indica se salvare l'HTML come file unico. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specifica se tutte le pagine saranno salvate come immagine o solo il primo piano. |
| [getSaveFormat()](#getSaveFormat--) | Specifica il formato in cui le pagine del diagramma renderizzate saranno salvate se viene utilizzato questo oggetto di opzioni di salvataggio. |
| [getSaveTitle()](#getSaveTitle--) | Definisce se è necessario esportare il titolo o meno. |
| [getSaveToolBar()](#getSaveToolBar--) | Specifica se salvare la barra degli strumenti. Il valore predefinito è true. |
| [getShapes()](#getShapes--) | forme da renderizzare. |
| [getStreamProvider()](#getStreamProvider--) | l'IStreamProvider per l'esportazione degli oggetti. |
| [getTitle()](#getTitle--) | il titolo del diagramma da renderizzare in HTML. |
| [getWarningCallback()](#getWarningCallback--) | callback di avviso. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definisce se è necessario esportare i commenti o meno. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Per la descrizione di questa proprietà, vedere [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Per la descrizione di questa proprietà, vedere [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Per la descrizione di questa proprietà, vedere [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Per la descrizione di questa proprietà, vedere [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Per la descrizione di questa proprietà, vedere [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | Per la descrizione di questa proprietà, vedere [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Per la descrizione di questa proprietà, vedere [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Per la descrizione di questa proprietà, vedere [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\\#getPageSize--) |
| [setResolution(int value)](#setResolution-int-) | Per la descrizione di questa proprietà, vedere [getResolution()](../../com.aspose.diagram/htmlsaveoptions\\#getResolution--) |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | Per la descrizione di questa proprietà, vedere [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\\#getSaveAsSingleFile--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Per la descrizione di questa proprietà, vedere [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Per la descrizione di questa proprietà, vedere [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\\#getSaveFormat--) |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | Per la descrizione di questa proprietà, vedere [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\\#getSaveTitle--) |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | Per la descrizione di questa proprietà, vedere [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\\#getSaveToolBar--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Per la descrizione di questa proprietà, vedere [getShapes()](../../com.aspose.diagram/renderingsaveoptions\\#getShapes--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | Per la descrizione di questa proprietà, vedere [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\\#getStreamProvider--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getTitle()](../../com.aspose.diagram/htmlsaveoptions\\#getTitle--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Il numero di pagine da renderizzare in HTML. Il valore predefinito è MaxValue, il che significa che verranno renderizzate tutte le pagine del diagramma.

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
### getResolution() {#getResolution--}
```
public int getResolution()
```


la risoluzione per l'html generato, in punti per pollice. Questa proprietà ha effetto solo durante il salvataggio in html. Il valore predefinito è 96.

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


Indica se salvare l'html come file unico. Il valore predefinito è false. Se ci sono più pagine, quelle pagine e le altre risorse devono essere salvate in file separati. In alcuni scenari, l'utente potrebbe aver bisogno di ottenere un solo file risultante, ad esempio per facilitare il trasferimento. In tal caso, l'utente può impostare questa proprietà su true.

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


Specifica il formato in cui le pagine del diagramma renderizzate saranno salvate se viene utilizzato questo oggetto di opzioni di salvataggio. Può essere solo Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


Definisce se è necessario esportare il titolo o meno. Il valore predefinito è true.

**Returns:**
boolean
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


Specifica se salvare la barra degli strumenti. Il valore predefinito è true.

**Returns:**
boolean
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


forme da renderizzare. Il conteggio predefinito è 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


l'IStreamProvider per l'esportazione degli oggetti.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


il titolo del diagramma da renderizzare in HTML. Se Title è null, verrà utilizzato Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties) come titolo. Se Diagram.DocumentProperties.Title è null o vuoto, verrà utilizzato il nome file del diagramma come titolo.

**Returns:**
java.lang.String
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


Per la descrizione di questa proprietà, vedere [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\\#getExportHiddenPage--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Per la descrizione di questa proprietà, vedere [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\\#getPageCount--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Per la descrizione di questa proprietà, vedere [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\\#getPageIndex--)

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

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


Per la descrizione di questa proprietà, vedere [getResolution()](../../com.aspose.diagram/htmlsaveoptions\\#getResolution--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


Per la descrizione di questa proprietà, vedere [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\\#getSaveAsSingleFile--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Per la descrizione di questa proprietà, vedere [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Per la descrizione di questa proprietà, vedere [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\\#getSaveFormat--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


Per la descrizione di questa proprietà, vedere [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\\#getSaveTitle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


Per la descrizione di questa proprietà, vedere [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\\#getSaveToolBar--)

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

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


Per la descrizione di questa proprietà, vedere [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\\#getStreamProvider--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Per la descrizione di questa proprietà, vedere [getTitle()](../../com.aspose.diagram/htmlsaveoptions\\#getTitle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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

