---
title: SVGSaveOptions
second_title: Aspose.Diagram for Java API-Referenz
description: Ermöglicht das Angeben zusätzlicher Optionen beim Rendern von Diagrammseiten zu SVG.
type: docs
weight: 347
url: /de/java/com.aspose.diagram/svgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class SVGSaveOptions extends RenderingSaveOptions
```

Ermöglicht das Angeben zusätzlicher Optionen beim Rendern von Diagrammseiten zu SVG.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SVGSaveOptions()](#SVGSaveOptions--) | Initialisiert eine neue Instanz dieser Klasse, die verwendet werden kann, um ein Dokument im Format Aspose.Diagram.SaveFileFormat zu speichern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Erstellt ein Speicheroptionen-Objekt einer Klasse, die für das angegebene Speicherformat geeignet ist. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomImagePath()](#getCustomImagePath--) | Der benutzerdefinierte Pfad (URL), der in der erzeugten SVG-Datei für das Bild gespeichert wird. |
| [getDefaultFont()](#getDefaultFont--) | Wenn Zeichen im Diagramm Unicode sind und nicht mit dem korrekten Schriftwert gesetzt werden oder die Schriftart nicht lokal installiert ist, können sie in PDF, Bild oder XPS als Block erscheinen. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Einstellung zum Rendern von Emf-Metadateien. |
| [getEnlargePage()](#getEnlargePage--) | Gibt an, ob die Seite vergrößert werden soll. |
| [getExportElementAsRectTag()](#getExportElementAsRectTag--) | Definiert, ob Rechteck-Elemente als <rect>-Tag exportiert werden sollen oder nicht. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definiert, ob die Leitlinienformen exportiert werden sollen oder nicht. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definiert, ob die versteckte Seite exportiert werden soll oder nicht. |
| [getPageIndex()](#getPageIndex--) | Der nullbasierte Index der zu rendernden Seite. |
| [getPageSize()](#getPageSize--) | die Seitengröße für die erzeugten Bilder. |
| [getQuality()](#getQuality--) | Ein Wert, der die Qualität der erzeugten Bilder bestimmt und nur beim Speichern von Seiten im JPEG-Format angewendet wird. |
| [getSVGFitToViewPort()](#getSVGFitToViewPort--) | Wenn diese Eigenschaft wahr ist, passt das erzeugte SVG zum Ansichtsfenster. |
| [getSaveFormat()](#getSaveFormat--) | Gibt das Format an, in dem das Dokument gespeichert wird, wenn dieses SaveOptions‑Objekt verwendet wird. |
| [getShapes()](#getShapes--) | Formen zum Rendern. |
| [getWarningCallback()](#getWarningCallback--) | Warnungs-Callback. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definiert, ob Kommentare exportiert werden sollen oder nicht. |
| [isExportScaleInMatrix()](#isExportScaleInMatrix--) | Definiert, ob die Export-Skala in einer Matrix benötigt wird oder nicht. |
| [isSavingCustomLinePattern()](#isSavingCustomLinePattern--) | Definiert, ob ein benutzerdefiniertes Linienmuster gespeichert wird. |
| [isSavingImageSeparately()](#isSavingImageSeparately--) | Definiert, ob das Bild separat gespeichert wird. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomImagePath(String value)](#setCustomImagePath-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultFont()](../../com.aspose.diagram/saveoptions\\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportElementAsRectTag(boolean value)](#setExportElementAsRectTag-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--) |
| [setExportScaleInMatrix(boolean value)](#setExportScaleInMatrix-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setQuality(int value)](#setQuality-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--) |
| [setSVGFitToViewPort(boolean value)](#setSVGFitToViewPort-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setSavingCustomLinePattern(boolean value)](#setSavingCustomLinePattern-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--) |
| [setSavingImageSeparately(boolean value)](#setSavingImageSeparately-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SVGSaveOptions() {#SVGSaveOptions--}
```
public SVGSaveOptions()
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
### getCustomImagePath() {#getCustomImagePath--}
```
public String getCustomImagePath()
```


Der vom Benutzer benutzerdefinierte Pfad (URL), der in der erzeugten SVG-Datei für das Bild gespeichert wird. Wenn er nicht vom Benutzer definiert wird, wird das aktuelle Verzeichnis verwendet.

**Returns:**
java.lang.String
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
### getExportElementAsRectTag() {#getExportElementAsRectTag--}
```
public boolean getExportElementAsRectTag()
```


Definiert, ob Rechteck-Elemente als rect-Tag exportiert werden sollen oder nicht. Der Standardwert ist false.

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
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Der nullbasierte Index der zu rendernden Seite. Standardwert ist 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


die Seitengröße für die erzeugten Bilder. Kann [PageSize](../../com.aspose.diagram/pagesize) oder null sein. Der Standardwert ist null. Wenn PageSize null ist, wird die Seitengröße für das erzeugte Bild aus dem Quell‑Diagramm übernommen.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getQuality() {#getQuality--}
```
public int getQuality()
```


Ein Wert, der die Qualität der erzeugten Bilder bestimmt und nur beim Speichern von Seiten im JPEG-Format angewendet wird. Der Standardwert ist 100. Wirkt nur beim Speichern als JPEG. Der Wert muss zwischen 0 und 100 liegen. Der Standardwert ist 100.

**Returns:**
int
### getSVGFitToViewPort() {#getSVGFitToViewPort--}
```
public boolean getSVGFitToViewPort()
```


Wenn diese Eigenschaft wahr ist, passt das erzeugte SVG zum Ansichtsfenster.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Gibt das Format an, in dem das Dokument gespeichert wird, wenn dieses SaveOptions‑Objekt verwendet wird.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Zu rendernde Shapes. Standardanzahl ist 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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
### isExportScaleInMatrix() {#isExportScaleInMatrix--}
```
public boolean isExportScaleInMatrix()
```


Definiert, ob die Export‑Skala in einer Matrix benötigt wird oder nicht. Der Standardwert ist true.

**Returns:**
boolean
### isSavingCustomLinePattern() {#isSavingCustomLinePattern--}
```
public boolean isSavingCustomLinePattern()
```


Definiert, ob ein benutzerdefiniertes Linienmuster gespeichert wird.

**Returns:**
boolean
### isSavingImageSeparately() {#isSavingImageSeparately--}
```
public boolean isSavingImageSeparately()
```


Definiert, ob das Bild separat gespeichert wird.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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

### setExportElementAsRectTag(boolean value) {#setExportElementAsRectTag-boolean-}
```
public void setExportElementAsRectTag(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--)

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setExportScaleInMatrix(boolean value) {#setExportScaleInMatrix-boolean-}
```
public void setExportScaleInMatrix(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--)

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSVGFitToViewPort(boolean value) {#setSVGFitToViewPort-boolean-}
```
public void setSVGFitToViewPort(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSavingCustomLinePattern(boolean value) {#setSavingCustomLinePattern-boolean-}
```
public void setSavingCustomLinePattern(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSavingImageSeparately(boolean value) {#setSavingImageSeparately-boolean-}
```
public void setSavingImageSeparately(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--)

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

