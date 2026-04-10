---
title: ImageSaveOptions
second_title: Aspose.Diagram for Java API-Referenz
description: Ermöglicht das Angeben zusätzlicher Optionen beim Rendern von Diagrammseiten zu Bildern.
type: docs
weight: 200
url: /de/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

Ermöglicht das Angeben zusätzlicher Optionen beim Rendern von Diagrammseiten zu Bildern.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | Initialisiert eine neue Instanz dieser Klasse, die zum Speichern gerenderter Bilder im Format Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat oder Aspose.Diagram.SaveFileFormat verwendet werden kann. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Erstellt ein Speicheroptionen-Objekt einer Klasse, die für das angegebene Speicherformat geeignet ist. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | Gibt die Qualitätsstufe an, die beim Compositing verwendet werden soll. |
| [getContentZoom()](#getContentZoom--) | Dieser Parameter ist ähnlich wie scale, wirkt sich jedoch nicht auf die Größe des erzeugten Bildes aus. |
| [getDefaultFont()](#getDefaultFont--) | Wenn Zeichen im Diagramm Unicode sind und nicht mit dem korrekten Schriftwert gesetzt werden oder die Schriftart nicht lokal installiert ist, können sie in PDF, Bild oder XPS als Block erscheinen. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Einstellung zum Rendern von Emf-Metadateien. |
| [getEnlargePage()](#getEnlargePage--) | Gibt an, ob die Seite vergrößert werden soll. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definiert, ob die Leitlinienformen exportiert werden sollen oder nicht. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definiert, ob die versteckte Seite exportiert werden soll oder nicht. |
| [getImageBrightness()](#getImageBrightness--) | die Helligkeit für die erzeugten Bilder. |
| [getImageColorMode()](#getImageColorMode--) | der Farbmodus für die erzeugten Bilder. |
| [getImageContrast()](#getImageContrast--) | der Kontrast für die erzeugten Bilder. |
| [getInterpolationMode()](#getInterpolationMode--) | Gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden. |
| [getJpegQuality()](#getJpegQuality--) | ein Wert, der die Qualität der erzeugten JPEG-Bilder bestimmt. |
| [getPageCount()](#getPageCount--) | die Anzahl der Seiten, die beim Speichern in einer mehrseitigen TIFF-Datei gerendert werden. |
| [getPageIndex()](#getPageIndex--) | der nullbasierte Index der ersten zu rendernden Seite. |
| [getPageSize()](#getPageSize--) | die Seitengröße für die erzeugten Bilder. |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | ein Wert, der angibt, wie Pixel beim Rendern versetzt werden. |
| [getResolution()](#getResolution--) | die Auflösung der erzeugten Bilder, in Punkten pro Zoll. |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | Gibt an, ob der Speicherbereich derselbe wie PDF ist. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Gibt an, ob alle Seiten als Bild gespeichert werden oder nur der Vordergrund. |
| [getSaveFormat()](#getSaveFormat--) | Gibt das Format an, in dem die gerenderten Diagrammseiten gespeichert werden, wenn dieses Speicheroptionen-Objekt verwendet wird. |
| [getScale()](#getScale--) | der Zoomfaktor für die erzeugten Bilder. |
| [getShapes()](#getShapes--) | Formen zum Rendern. |
| [getSmoothingMode()](#getSmoothingMode--) | Gibt an, ob Glättung (Antialiasing) auf Linien und Kurven sowie die Kanten von gefüllten Bereichen angewendet wird. |
| [getTiffCompression()](#getTiffCompression--) | der Kompressionstyp, der beim Speichern der erzeugten Bilder im TIFF-Format angewendet wird. |
| [getWarningCallback()](#getWarningCallback--) | Warnungs-Callback. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definiert, ob Kommentare exportiert werden sollen oder nicht. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Für die Beschreibung dieser Eigenschaft siehe [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) |
| [setContentZoom(float value)](#setContentZoom-float-) | Für die Beschreibung dieser Eigenschaft siehe [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDefaultFont()](../../com.aspose.diagram/saveoptions\\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Für die Beschreibung dieser Eigenschaft siehe [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) |
| [setImageBrightness(float value)](#setImageBrightness-float-) | Für die Beschreibung dieser Eigenschaft siehe [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) |
| [setImageColorMode(int value)](#setImageColorMode-int-) | Für die Beschreibung dieser Eigenschaft siehe [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) |
| [setImageContrast(float value)](#setImageContrast-float-) | Für die Beschreibung dieser Eigenschaft siehe [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Für die Beschreibung dieser Eigenschaft siehe [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Für die Beschreibung dieser Eigenschaft siehe [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Für die Beschreibung dieser Eigenschaft siehe [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Für die Beschreibung dieser Eigenschaft siehe [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | Für die Beschreibung dieser Eigenschaft siehe [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) |
| [setResolution(float value)](#setResolution-float-) | Für die Beschreibung dieser Eigenschaft siehe [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | Für die Beschreibung dieser Eigenschaft siehe [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Für die Beschreibung dieser Eigenschaft siehe [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Für die Beschreibung dieser Eigenschaft siehe [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) |
| [setScale(float value)](#setScale-float-) | Für die Beschreibung dieser Eigenschaft siehe [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Für die Beschreibung dieser Eigenschaft siehe [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) |
| [setTiffCompression(int value)](#setTiffCompression-int-) | Für die Beschreibung dieser Eigenschaft siehe [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


Initialisiert eine neue Instanz dieser Klasse, die zum Speichern gerenderter Bilder im Format Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat oder Aspose.Diagram.SaveFileFormat verwendet werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| saveFormat | int | Kann sein Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat oder Aspose.Diagram.SaveFileFormat. |

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
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Gibt die Qualitätsstufe an, die beim Compositing verwendet werden soll. Diese Eigenschaft wirkt nur beim Speichern in Rasterbildformate. Der Standardwert ist Aspose.Diagram.Saving.CompositingQuality.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


Dieser Parameter ist ähnlich wie scale, beeinflusst jedoch nicht die Größe des erzeugten Bildes. Der Standardwert ist 1,0. Der Wert muss größer als 0 sein.

**Returns:**
float
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
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


Die Helligkeit für die erzeugten Bilder. Diese Eigenschaft wirkt nur beim Speichern in Rasterbildformate. Der Standardwert ist 0,5. Der Wert muss im Bereich zwischen 0 und 1 liegen.

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


Der Farbmodus für die erzeugten Bilder. Diese Eigenschaft wirkt nur beim Speichern in Rasterbildformate. Der Standardwert ist Aspose.Diagram.Saving.ImageColorMode.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


Der Kontrast für die erzeugten Bilder. Diese Eigenschaft wirkt nur beim Speichern in Rasterbildformate. Der Standardwert ist 0,5. Der Wert muss im Bereich zwischen 0 und 1 liegen.

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden. Diese Eigenschaft wirkt nur beim Speichern in Rasterbildformate. Der Standardwert ist Aspose.Diagram.Saving.InterpolationMode.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Ein Wert, der die Qualität der erzeugten JPEG‑Bilder bestimmt. Wirkt nur beim Speichern als JPEG. Verwenden Sie diese Eigenschaft, um die Qualität der erzeugten Bilder beim Speichern im JPEG‑Format zu erhalten oder festzulegen. Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität aber maximale Kompression bedeutet und 100 die beste Qualität aber minimale Kompression. Der Standardwert ist 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Die Anzahl der Seiten, die beim Speichern in einer mehrseitigen TIFF‑Datei gerendert werden sollen. Standard ist MaxValue, was bedeutet, dass alle Seiten des Diagramms gerendert werden.

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
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


Ein Wert, der angibt, wie Pixel beim Rendern versetzt werden. Diese Eigenschaft wirkt nur beim Speichern in Rasterbildformate. Der Standardwert ist Aspose.Diagram.Saving.PixelOffsetMode.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


Die Auflösung für die erzeugten Bilder, in Punkten pro Zoll. Diese Eigenschaft wirkt nur beim Speichern in Rasterbildformate. Der Standardwert ist 96.

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


Gibt an, ob der zu speichernde Bereich dem PDF entspricht. Wenn true – ist der gerenderte Bereich gleich dem PDF. Wenn false – ist der gerenderte Bereich der Standard. Der Standardwert ist false.

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


Gibt das Format an, in dem die gerenderten Diagrammseiten gespeichert werden, wenn dieses Save‑Options‑Objekt verwendet wird. Kann Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat oder Aspose.Diagram.SaveFileFormat sein.

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


Der Zoom‑Faktor für die erzeugten Bilder. Der Standardwert ist 1,0. Der Wert muss größer als 0 sein.

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Zu rendernde Shapes. Standardanzahl ist 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Gibt an, ob Glättung (Antialiasing) auf Linien und Kurven sowie die Kanten gefüllter Flächen angewendet wird. Diese Eigenschaft wirkt nur beim Speichern in Rasterbildformate. Der Standardwert ist Aspose.Diagram.Saving.SmoothingMode.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


Der Kompressionstyp, der beim Speichern erzeugter Bilder im TIFF‑Format angewendet wird. Wirkt nur beim Speichern als TIFF. Der Standardwert ist Aspose.Diagram.Saving.TiffCompression.

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




### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Für die Beschreibung dieser Eigenschaft siehe [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


Für die Beschreibung dieser Eigenschaft siehe [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

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


Für die Beschreibung dieser Eigenschaft siehe [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


Für die Beschreibung dieser Eigenschaft siehe [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


Für die Beschreibung dieser Eigenschaft siehe [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


Für die Beschreibung dieser Eigenschaft siehe [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Für die Beschreibung dieser Eigenschaft siehe [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Für die Beschreibung dieser Eigenschaft siehe [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Für die Beschreibung dieser Eigenschaft siehe [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Für die Beschreibung dieser Eigenschaft siehe [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)

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

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


Für die Beschreibung dieser Eigenschaft siehe [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Für die Beschreibung dieser Eigenschaft siehe [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Für die Beschreibung dieser Eigenschaft siehe [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


Für die Beschreibung dieser Eigenschaft siehe [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Für die Beschreibung dieser Eigenschaft siehe [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


Für die Beschreibung dieser Eigenschaft siehe [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)

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

