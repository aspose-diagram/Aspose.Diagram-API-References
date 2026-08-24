---
title: PrintSaveOptions
second_title: Riferimento API di Aspose.Diagram per Java
description: Consente di specificare opzioni aggiuntive durante la stampa del diagramma.
type: docs
weight: 308
url: /it/java/com.aspose.diagram/printsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PrintSaveOptions extends RenderingSaveOptions
```

Consente di specificare opzioni aggiuntive durante la stampa del diagramma.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PrintSaveOptions()](#PrintSaveOptions--) | Inizializza una nuova istanza di questa classe |
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
| [getPageCount()](#getPageCount--) | il numero di pagine da renderizzare durante il salvataggio in un file multipagina. |
| [getPageSize()](#getPageSize--) | la dimensione della pagina per le immagini generate. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specifica se tutte le pagine verranno stampate o solo il primo piano. |
| [getSaveFormat()](#getSaveFormat--) | Specifica il formato in cui il documento verrà salvato se viene utilizzato questo oggetto di opzioni di salvataggio. |
| [getShapes()](#getShapes--) | forme da renderizzare. |
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
| [setPageCount(int value)](#setPageCount-int-) | Per la descrizione di questa proprietà, vedere [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Per la descrizione di questa proprietà, vedere [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Per la descrizione di questa proprietà, vedere [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Per la descrizione di questa proprietà, vedere [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Per la descrizione di questa proprietà, vedere [getShapes()](../../com.aspose.diagram/renderingsaveoptions\\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintSaveOptions() {#PrintSaveOptions--}
```
public PrintSaveOptions()
```


Inizializza una nuova istanza di questa classe

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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


il numero di pagine da renderizzare durante il salvataggio in un file multipagina. Il valore predefinito è MaxValue, che significa che tutte le pagine del diagramma verranno stampate.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


la dimensione della pagina per le immagini generate. Può essere [PageSize](../../com.aspose.diagram/pagesize) o null. Il valore predefinito è null. Se PageSize è null, la dimensione della pagina per l'immagine generata viene ottenuta dal diagramma di origine.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Specifica se tutte le pagine verranno stampate o solo il primo piano. Se true - vengono stampate solo le pagine del primo piano (con lo sfondo se presente). Se false - vengono stampate le pagine del primo piano (con lo sfondo se presente) seguite da pagine di sfondo vuote. Può restituire true solo quando PageCount > 1. Il valore predefinito è false.

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

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Per la descrizione di questa proprietà, vedere [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--)

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

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Per la descrizione di questa proprietà, vedere [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--)

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

