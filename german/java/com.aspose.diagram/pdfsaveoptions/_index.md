---
title: PdfSaveOptions
second_title: Aspose.Diagram for Java API-Referenz
description: Ermöglicht das Angeben zusätzlicher Optionen beim Rendern von Diagrammseiten zu PDF.
type: docs
weight: 281
url: /de/java/com.aspose.diagram/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PdfSaveOptions extends RenderingSaveOptions
```

Ermöglicht das Angeben zusätzlicher Optionen beim Rendern von Diagrammseiten zu PDF.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Initialisiert eine neue Instanz dieser Klasse, die verwendet werden kann, um ein Dokument im Format Aspose.Diagram.SaveFileFormat zu speichern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Erstellt ein Speicheroptionen-Objekt einer Klasse, die für das angegebene Speicherformat geeignet ist. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompliance()](#getCompliance--) | Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. |
| [getDefaultFont()](#getDefaultFont--) | Wenn Zeichen im Diagramm Unicode sind und nicht mit dem korrekten Schriftwert gesetzt werden oder die Schriftart nicht lokal installiert ist, können sie in PDF, Bild oder XPS als Block erscheinen. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Einstellung zum Rendern von Emf-Metadateien. |
| [getEncryptionDetails()](#getEncryptionDetails--) | Ein Verschlüsselungsdetail. |
| [getEnlargePage()](#getEnlargePage--) | Gibt an, ob die Seite vergrößert werden soll. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definiert, ob die Leitlinienformen exportiert werden sollen oder nicht. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definiert, ob die versteckte Seite exportiert werden soll oder nicht. |
| [getHorizontalResolution()](#getHorizontalResolution--) | die horizontale Auflösung für erzeugte Bilder, in Punkten pro Zoll. |
| [getJpegQuality()](#getJpegQuality--) | Gibt die Qualität der JPEG-Kompression für Bilder an (falls JPEG-Kompression verwendet wird). |
| [getPageCount()](#getPageCount--) | die Anzahl der Seiten, die im PDF gerendert werden sollen. |
| [getPageIndex()](#getPageIndex--) | der nullbasierte Index der ersten zu rendernden Seite. |
| [getPageSavingCallback()](#getPageSavingCallback--) | Steuert/zeigt den Fortschritt des Seiten‑Speichervorgangs an. |
| [getPageSize()](#getPageSize--) | die Seitengröße für die erzeugten Bilder. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Gibt an, ob alle Seiten als Bild gespeichert werden oder nur der Vordergrund. |
| [getSaveFormat()](#getSaveFormat--) | Gibt das Format an, in dem die gerenderten Diagrammseiten gespeichert werden, wenn dieses Speicheroptionen-Objekt verwendet wird. |
| [getShapes()](#getShapes--) | Formen zum Rendern. |
| [getSplitMultiPages()](#getSplitMultiPages--) | Definiert, ob das Diagramm gemäß den Seiteneinstellungen in mehrere Seiten aufgeteilt wird. |
| [getTextCompression()](#getTextCompression--) | Gibt den Kompressionstyp an, der für alle Inhaltsströme außer Bildern verwendet wird. |
| [getVerticalResolution()](#getVerticalResolution--) | die vertikale Auflösung für erzeugte Bilder, in Punkten pro Zoll. |
| [getWarningCallback()](#getWarningCallback--) | Warnungs-Callback. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definiert, ob Kommentare exportiert werden sollen oder nicht. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompliance(int value)](#setCompliance-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultFont()](../../com.aspose.diagram/saveoptions\\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\\#getEmfRenderSetting--) |
| [setEncryptionDetails(PdfEncryptionDetails value)](#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--) |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--) |
| [setPageSavingCallback(IPageSavingCallback value)](#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSplitMultiPages(boolean value)](#setSplitMultiPages-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--) |
| [setTextCompression(int value)](#setTextCompression-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--) |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
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
### getCompliance() {#getCompliance--}
```
public int getCompliance()
```


Gewünschtes Konformitätsniveau für das erzeugte PDF-Dokument. Standard ist PdfCompliance.PDF\_15.

**Returns:**
int
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
### getEncryptionDetails() {#getEncryptionDetails--}
```
public PdfEncryptionDetails getEncryptionDetails()
```


Ein Verschlüsselungsdetail. Wenn nicht gesetzt, wird keine Verschlüsselung durchgeführt.

**Returns:**
[PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails)
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
### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


die horizontale Auflösung für erzeugte Bilder, in Punkten pro Zoll. Gilt für die Bildgenerierungsmethode, außer bei EMF-Formatbildern. Der Standardwert ist 96.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Gibt die Qualität der JPEG-Kompression für Bilder an (falls JPEG-Kompression verwendet wird). Standard ist 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


die Anzahl der Seiten, die im PDF gerendert werden sollen. Standard ist MaxValue, was bedeutet, dass alle Seiten des Diagramms gerendert werden.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Der nullbasierte Index der ersten zu rendernden Seite. Standard ist 0.

**Returns:**
int
### getPageSavingCallback() {#getPageSavingCallback--}
```
public IPageSavingCallback getPageSavingCallback()
```


Steuert/zeigt den Fortschritt des Seiten‑Speichervorgangs an.

**Returns:**
[IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback)
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
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Zu rendernde Shapes. Standardanzahl ist 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSplitMultiPages() {#getSplitMultiPages--}
```
public boolean getSplitMultiPages()
```


Definiert, ob das Diagramm gemäß den Seiteneinstellungen in mehrere Seiten aufgeteilt wird. Standardwert ist false.

**Returns:**
boolean
### getTextCompression() {#getTextCompression--}
```
public int getTextCompression()
```


Gibt den Kompressionstyp an, der für alle Inhaltsströme außer Bildern verwendet wird. Standard ist PdfTextCompression.FLATE.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Die vertikale Auflösung für erzeugte Bilder, in Punkten pro Zoll. Gilt für die Bildgenerierungsmethode, außer für Emf-Formatbilder. Der Standardwert ist 96.

**Returns:**
int
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




### setCompliance(int value) {#setCompliance-int-}
```
public void setCompliance(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

### setEncryptionDetails(PdfEncryptionDetails value) {#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-}
```
public void setEncryptionDetails(PdfEncryptionDetails value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails) |  |

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPageSavingCallback(IPageSavingCallback value) {#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-}
```
public void setPageSavingCallback(IPageSavingCallback value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback) |  |

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--)

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

### setSplitMultiPages(boolean value) {#setSplitMultiPages-boolean-}
```
public void setSplitMultiPages(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setTextCompression(int value) {#setTextCompression-int-}
```
public void setTextCompression(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

