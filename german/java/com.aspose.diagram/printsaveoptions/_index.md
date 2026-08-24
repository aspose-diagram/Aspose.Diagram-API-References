---
title: PrintSaveOptions
second_title: Aspose.Diagram for Java API-Referenz
description: Ermöglicht das Angeben zusätzlicher Optionen beim Drucken des Diagramms.
type: docs
weight: 308
url: /de/java/com.aspose.diagram/printsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PrintSaveOptions extends RenderingSaveOptions
```

Ermöglicht das Angeben zusätzlicher Optionen beim Drucken des Diagramms.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PrintSaveOptions()](#PrintSaveOptions--) | Initialisiert eine neue Instanz dieser Klasse |
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
| [getPageCount()](#getPageCount--) | Die Anzahl der Seiten, die beim Speichern in einer mehrseitigen Datei gerendert werden. |
| [getPageSize()](#getPageSize--) | die Seitengröße für die erzeugten Bilder. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Gibt an, ob alle Seiten gedruckt werden oder nur der Vordergrund. |
| [getSaveFormat()](#getSaveFormat--) | Gibt das Format an, in dem das Dokument gespeichert wird, wenn dieses SaveOptions‑Objekt verwendet wird. |
| [getShapes()](#getShapes--) | Formen zum Rendern. |
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
| [setPageCount(int value)](#setPageCount-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintSaveOptions() {#PrintSaveOptions--}
```
public PrintSaveOptions()
```


Initialisiert eine neue Instanz dieser Klasse

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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Die Anzahl der Seiten, die beim Speichern in einer mehrseitigen Datei gerendert werden. Standard ist MaxValue, was bedeutet, dass alle Seiten des Diagramms gedruckt werden.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


die Seitengröße für die erzeugten Bilder. Kann [PageSize](../../com.aspose.diagram/pagesize) oder null sein. Der Standardwert ist null. Wenn PageSize null ist, wird die Seitengröße für das erzeugte Bild aus dem Quell‑Diagramm übernommen.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Gibt an, ob alle Seiten gedruckt werden oder nur der Vordergrund. Wenn true – werden nur Vordergrundseiten gedruckt (mit Hintergrund, falls vorhanden). Wenn false – werden Vordergrundseiten gedruckt (mit Hintergrund, falls vorhanden), danach leere Hintergrundseiten. Kann nur true zurückgeben, wenn PageCount > 1. Der Standardwert ist false.

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

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--)

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

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--)

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

