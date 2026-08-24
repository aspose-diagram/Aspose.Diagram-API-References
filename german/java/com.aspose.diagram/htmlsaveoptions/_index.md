---
title: HTMLSaveOptions
second_title: Aspose.Diagram for Java API-Referenz
description: Ermöglicht das Angeben zusätzlicher Optionen beim Rendern von Diagrammseiten zu HTML.
type: docs
weight: 187
url: /de/java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

Ermöglicht das Angeben zusätzlicher Optionen beim Rendern von Diagrammseiten zu HTML.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | Initialisiert eine neue Instanz dieser Klasse, die verwendet werden kann, um ein Dokument im Format Aspose.Diagram.SaveFileFormat zu speichern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Erstellt ein Speicheroptionen-Objekt einer Klasse, die für das angegebene Speicherformat geeignet ist. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Wenn Zeichen im Diagramm Unicode sind und nicht mit dem korrekten Schriftwert gesetzt werden oder die Schriftart nicht lokal installiert ist, können sie in PDF, Bild oder XPS als Block erscheinen. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Einstellung zum Rendern von Emf-Metadateien. |
| [getEnlargePage()](#getEnlargePage--) | Gibt an, ob die Seite vergrößert werden soll. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definiert, ob die Leitlinienformen exportiert werden sollen oder nicht. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definiert, ob die versteckte Seite exportiert werden soll oder nicht. |
| [getPageCount()](#getPageCount--) | die Anzahl der Seiten, die in HTML gerendert werden sollen. |
| [getPageIndex()](#getPageIndex--) | der nullbasierte Index der ersten zu rendernden Seite. |
| [getPageSize()](#getPageSize--) | die Seitengröße für die erzeugten Bilder. |
| [getResolution()](#getResolution--) | die Auflösung für das erzeugte HTML, in Punkten pro Zoll. |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | Gibt an, ob das HTML als einzelne Datei gespeichert werden soll. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Gibt an, ob alle Seiten als Bild gespeichert werden oder nur der Vordergrund. |
| [getSaveFormat()](#getSaveFormat--) | Gibt das Format an, in dem die gerenderten Diagrammseiten gespeichert werden, wenn dieses Speicheroptionen-Objekt verwendet wird. |
| [getSaveTitle()](#getSaveTitle--) | Definiert, ob der Titel exportiert werden soll oder nicht. |
| [getSaveToolBar()](#getSaveToolBar--) | Gibt an, ob die Symbolleiste gespeichert wird. Der Standardwert ist true. |
| [getShapes()](#getShapes--) | Formen zum Rendern. |
| [getStreamProvider()](#getStreamProvider--) | der IStreamProvider zum Exportieren von Objekten. |
| [getTitle()](#getTitle--) | der Titel des Diagramms, das in HTML gerendert werden soll. |
| [getWarningCallback()](#getWarningCallback--) | Warnungs-Callback. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definiert, ob Kommentare exportiert werden sollen oder nicht. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultFont()](../../com.aspose.diagram/saveoptions\\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setResolution(int value)](#setResolution-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--) |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--) |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--) |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
```


Initialisiert eine neue Instanz dieser Klasse, die verwendet werden kann, um ein Dokument im Format Aspose.Diagram.SaveFileFormat zu speichern.

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Erstellt ein Speicheroptionen-Objekt einer Klasse, die für das angegebene Speicherformat geeignet ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| saveFormat | int | Das Aspose.Diagram.SaveFileFormat, für das ein Save-Optionen-Objekt erstellt werden soll. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Wenn Zeichen im Diagramm Unicode sind und nicht mit dem korrekten Schriftwert gesetzt werden oder die Schriftart nicht lokal installiert ist, können sie im PDF, Bild oder XPS als Block erscheinen. Setzen Sie die DefaultFont, z. B. MingLiu oder MS Gothic, um diese Zeichen anzuzeigen.

**Returns:**
java.lang.String
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Einstellung für das Rendern von EMF-Metadateien. EMF-Metadateien, die als "EMF+ Dual" identifiziert werden, können sowohl EMF+-Datensätze als auch EMF-Datensätze enthalten. Jeder Datensatztyp kann zum Rendern des Bildes verwendet werden, nur EMF+-Datensätze oder nur EMF-Datensätze. Wenn EmfPlusPrefer gesetzt ist, werden EMF+-Datensätze geparst, andernfalls werden nur EMF-Datensätze geparst. Der Standardwert ist EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


Gibt an, ob die Seite vergrößert werden soll. Wenn true – Seite vergrößern. Wenn false – Seite nicht vergrößern. Der Standardwert ist true.

**Returns:**
boolean
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


Definiert, ob Leitlinienformen exportiert werden sollen oder nicht. Standardwert ist true.

**Returns:**
boolean
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Definiert, ob versteckte Seiten exportiert werden sollen oder nicht. Standardwert ist true.

**Returns:**
boolean
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Die Anzahl der Seiten, die in HTML gerendert werden sollen. Standard ist MaxValue, was bedeutet, dass alle Seiten des Diagramms gerendert werden.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Der nullbasierte Index der ersten zu rendernden Seite. Standard ist 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


die Seitengröße für die erzeugten Bilder. Kann [PageSize](../../com.aspose.diagram/pagesize) oder null sein. Der Standardwert ist null. Wenn PageSize null ist, wird die Seitengröße für das erzeugte Bild aus dem Quell‑Diagramm übernommen.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getResolution() {#getResolution--}
```
public int getResolution()
```


die Auflösung für das erzeugte HTML, in Punkten pro Zoll. Diese Eigenschaft wirkt nur beim Speichern als HTML. Der Standardwert ist 96.

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


Gibt an, ob das HTML als einzelne Datei gespeichert werden soll. Der Standardwert ist false. Wenn mehrere Seiten vorhanden sind, müssen diese Seiten und andere Ressourcen in separaten Dateien gespeichert werden. Für einige Szenarien benötigt der Benutzer möglicherweise nur eine Ergebnisdatei, z. B. zum einfachen Übertragen. In diesem Fall kann der Benutzer diese Eigenschaft auf true setzen.

**Returns:**
boolean
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Legt fest, ob alle Seiten im Bild gespeichert werden oder nur der Vordergrund. Wenn true – werden nur Vordergrundseiten gerendert (mit Hintergrund, falls vorhanden). Wenn false – werden Vordergrundseiten gerendert (mit Hintergrund, falls vorhanden) und danach leere Hintergrundseiten. Kann nur true zurückgeben, wenn PageCount > 1. Der Standardwert ist false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Gibt das Format an, in dem die gerenderten Diagrammseiten gespeichert werden, wenn dieses Speicheroptionsobjekt verwendet wird. Kann nur Aspose.Diagram.SaveFileFormat sein.

**Returns:**
int
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


Legt fest, ob der Titel exportiert werden soll oder nicht. Der Standardwert ist true.

**Returns:**
boolean
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


Gibt an, ob die Symbolleiste gespeichert wird. Der Standardwert ist true.

**Returns:**
boolean
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Zu rendernde Shapes. Standardanzahl ist 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


der IStreamProvider zum Exportieren von Objekten.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


Der Titel des Diagramms, das in HTML gerendert werden soll. Wenn Title null ist, wird Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties) als Titel verwendet. Wenn Diagram.DocumentProperties.Title null oder leer ist, wird der Dateiname des Diagramms als Titel verwendet.

**Returns:**
java.lang.String
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


Warnungs-Callback.

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


Legt fest, ob Kommentare exportiert werden sollen oder nicht. Der Standardwert ist false.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultFont()](../../com.aspose.diagram/saveoptions\\#getDefaultFont--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\\#getEmfRenderSetting--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

