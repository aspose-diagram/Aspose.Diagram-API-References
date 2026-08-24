---
title: XAMLSaveOptions
second_title: Riferimento API di Aspose.Diagram per Java
description: Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in XAML.
type: docs
weight: 448
url: /it/java/com.aspose.diagram/xamlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XAMLSaveOptions extends SaveOptions
```

Consente di specificare opzioni aggiuntive durante il rendering delle pagine del diagramma in XAML.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XAMLSaveOptions()](#XAMLSaveOptions--) | Inizializza una nuova istanza di questa classe che può essere utilizzata per salvare un documento nel formato Aspose.Diagram.SaveFileFormat. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Crea un oggetto di opzioni di salvataggio di una classe adatta al formato di salvataggio specificato. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Quando i caratteri nel diagramma sono Unicode e non vengono impostati con il valore di carattere corretto o il carattere non è installato localmente, possono apparire come blocchi in PDF, immagine o XPS. |
| [getPageCount()](#getPageCount--) | il numero di pagine da renderizzare in XAML. |
| [getPageIndex()](#getPageIndex--) | l'indice basato su zero della prima pagina da renderizzare. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specifica se tutte le pagine saranno salvate come immagine o solo il primo piano. |
| [getSaveFormat()](#getSaveFormat--) | Specifica il formato in cui le pagine del diagramma renderizzate saranno salvate se viene utilizzato questo oggetto di opzioni di salvataggio. |
| [getStreamProvider()](#getStreamProvider--) | l'IStreamProvider per l'esportazione degli oggetti. |
| [getWarningCallback()](#getWarningCallback--) | callback di avviso. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setPageCount(int value)](#setPageCount-int-) | Per la descrizione di questa proprietà, vedere [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Per la descrizione di questa proprietà, vedere [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Per la descrizione di questa proprietà, vedere [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Per la descrizione di questa proprietà, vedere [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | Per la descrizione di questa proprietà, vedere [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XAMLSaveOptions() {#XAMLSaveOptions--}
```
public XAMLSaveOptions()
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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Il numero di pagine da renderizzare in XAML. Il valore predefinito è MaxValue, il che significa che tutte le pagine del diagramma verranno renderizzate.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


L'indice basato su zero della prima pagina da renderizzare. Il valore predefinito è 0.

**Returns:**
int
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
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


l'IStreamProvider per l'esportazione degli oggetti.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
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

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Per la descrizione di questa proprietà, vedere [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Per la descrizione di questa proprietà, vedere [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Per la descrizione di questa proprietà, vedere [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Per la descrizione di questa proprietà, vedere [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


Per la descrizione di questa proprietà, vedere [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

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

