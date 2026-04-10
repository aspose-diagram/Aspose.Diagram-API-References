---
title: SVGSaveOptions
second_title: Aspose.Diagram för Java API-referens
description: Tillåter att ange ytterligare alternativ när diagramssidor renderas till SVG.
type: docs
weight: 347
url: /sv/java/com.aspose.diagram/svgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class SVGSaveOptions extends RenderingSaveOptions
```

Tillåter att ange ytterligare alternativ när diagramssidor renderas till SVG.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SVGSaveOptions()](#SVGSaveOptions--) | Initierar en ny instans av den här klassen som kan användas för att spara ett dokument i formatet Aspose.Diagram.SaveFileFormat. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Skapar ett sparaalternativobjekt av en klass som är lämplig för det angivna sparformatet. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomImagePath()](#getCustomImagePath--) | Den anpassade sökvägen (URL) som sparas i den genererade SVG-filen för bilden. |
| [getDefaultFont()](#getDefaultFont--) | När tecken i diagrammet är Unicode och inte har ställts in med korrekt teckensnittsvärde eller teckensnittet inte är installerat lokalt, kan de visas som block i PDF, bild eller XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Inställning för rendering av Emf-metafil. |
| [getEnlargePage()](#getEnlargePage--) | Anger om sidan ska förstoras. |
| [getExportElementAsRectTag()](#getExportElementAsRectTag--) | Definierar om rektangel-element ska exporteras som rect-tag eller inte. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definierar om guideformer ska exporteras eller inte. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definierar om dolda sidor ska exporteras eller inte. |
| [getPageIndex()](#getPageIndex--) | det 0-baserade indexet för sidan som ska renderas. |
| [getPageSize()](#getPageSize--) | sidstorleken för de genererade bilderna. |
| [getQuality()](#getQuality--) | ett värde som bestämmer kvaliteten på de genererade bilderna och endast tillämpas när sidor sparas i JPEG-format. |
| [getSVGFitToViewPort()](#getSVGFitToViewPort--) | om denna egenskap är sann, kommer den genererade SVG:n att anpassas till visningsporten. |
| [getSaveFormat()](#getSaveFormat--) | Anger det format i vilket dokumentet kommer att sparas om detta SaveOptions‑objekt används. |
| [getShapes()](#getShapes--) | former att rendera. |
| [getWarningCallback()](#getWarningCallback--) | varnings‑återanrop. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definierar om kommentarer ska exporteras eller inte. |
| [isExportScaleInMatrix()](#isExportScaleInMatrix--) | Definierar om exportskala ska vara i matris eller inte. |
| [isSavingCustomLinePattern()](#isSavingCustomLinePattern--) | Definierar om anpassat linjemönster ska sparas. |
| [isSavingImageSeparately()](#isSavingImageSeparately--) | Definierar om bilden ska sparas separat. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomImagePath(String value)](#setCustomImagePath-java.lang.String-) | För beskrivningen av den här egenskapen, se [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | För beskrivningen av denna egenskap, se [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | För beskrivningen av denna egenskap, se [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | För beskrivningen av den här egenskapen, se [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | För beskrivningen av den här egenskapen, se [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportElementAsRectTag(boolean value)](#setExportElementAsRectTag-boolean-) | För beskrivningen av den här egenskapen, se [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | För beskrivningen av den här egenskapen, se [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | För beskrivningen av den här egenskapen, se [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--) |
| [setExportScaleInMatrix(boolean value)](#setExportScaleInMatrix-boolean-) | För beskrivningen av den här egenskapen, se [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--) |
| [setPageIndex(int value)](#setPageIndex-int-) | För beskrivningen av den här egenskapen, se [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | För beskrivningen av den här egenskapen, se [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setQuality(int value)](#setQuality-int-) | För beskrivningen av den här egenskapen, se [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--) |
| [setSVGFitToViewPort(boolean value)](#setSVGFitToViewPort-boolean-) | För beskrivningen av den här egenskapen, se [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | För beskrivningen av denna egenskap, se [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setSavingCustomLinePattern(boolean value)](#setSavingCustomLinePattern-boolean-) | För beskrivningen av den här egenskapen, se [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--) |
| [setSavingImageSeparately(boolean value)](#setSavingImageSeparately-boolean-) | För beskrivningen av den här egenskapen, se [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | För beskrivningen av den här egenskapen, se [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SVGSaveOptions() {#SVGSaveOptions--}
```
public SVGSaveOptions()
```


Initierar en ny instans av den här klassen som kan användas för att spara ett dokument i formatet Aspose.Diagram.SaveFileFormat.

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Skapar ett sparaalternativobjekt av en klass som är lämplig för det angivna sparformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| saveFormat | int | Den Aspose.Diagram.SaveFileFormat som ska användas för att skapa ett save options-objekt. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Den användardefinierade sökvägen (URL) som sparas i den genererade svg-filen för bilden. Om den inte definieras av användaren används aktuell katalog.

**Returns:**
java.lang.String
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


När tecken i diagrammet är Unicode och inte har ställts in med korrekt teckensnittsvärde eller teckensnittet inte är installerat lokalt, kan de visas som block i PDF, bild eller XPS. Ställ in DefaultFont, t.ex. MingLiu eller MS Gothic, för att visa dessa tecken.

**Returns:**
java.lang.String
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Inställning för rendering av EMF-metafil. EMF-metafiler identifierade som "EMF+ Dual" kan innehålla både EMF+-poster och EMF-poster. Båda typerna av poster kan användas för att rendera bilden, endast EMF+-poster, eller endast EMF-poster. När EmfPlusPrefer är satt, kommer EMF+-poster att parsas, annars kommer endast EMF-poster att parsas. Standardvärdet är EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


Anger om sidan ska förstoras. Om true - förstora sidan. Om false - förstora inte sidan. Standardvärdet är true.

**Returns:**
boolean
### getExportElementAsRectTag() {#getExportElementAsRectTag--}
```
public boolean getExportElementAsRectTag()
```


Definierar om rektangel-element ska exporteras som rect-tag eller inte. Standardvärdet är falskt.

**Returns:**
boolean
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


Definierar om guideformer ska exporteras eller inte. Standardvärdet är true.

**Returns:**
boolean
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Definierar om dolda sidor ska exporteras eller inte. Standardvärdet är true.

**Returns:**
boolean
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Det 0-baserade indexet för sidan som ska renderas. Standard är 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


sidstorleken för de genererade bilderna. Kan vara [PageSize](../../com.aspose.diagram/pagesize) eller null. Standardvärdet är null. Om PageSize är null hämtas sidstorleken för den genererade bilden från källdiagrammet.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getQuality() {#getQuality--}
```
public int getQuality()
```


Ett värde som bestämmer kvaliteten på de genererade bilderna och endast tillämpas när sidor sparas i JPEG-format. Standardvärdet är 100. Påverkar endast vid sparande till JPEG. Värdet måste vara mellan 0 och 100. Standardvärdet är 100.

**Returns:**
int
### getSVGFitToViewPort() {#getSVGFitToViewPort--}
```
public boolean getSVGFitToViewPort()
```


om denna egenskap är sann, kommer den genererade SVG:n att anpassas till visningsporten.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Anger det format i vilket dokumentet kommer att sparas om detta SaveOptions‑objekt används.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


former att rendera. Standardantalet är 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


varnings‑återanrop.

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


Definierar om kommentarer ska exporteras eller inte. Standardvärdet är false.

**Returns:**
boolean
### isExportScaleInMatrix() {#isExportScaleInMatrix--}
```
public boolean isExportScaleInMatrix()
```


Definierar om exportskala ska inkluderas i matrisen eller inte. Standardvärdet är sant.

**Returns:**
boolean
### isSavingCustomLinePattern() {#isSavingCustomLinePattern--}
```
public boolean isSavingCustomLinePattern()
```


Definierar om anpassat linjemönster ska sparas.

**Returns:**
boolean
### isSavingImageSeparately() {#isSavingImageSeparately--}
```
public boolean isSavingImageSeparately()
```


Definierar om bilden ska sparas separat.

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


För beskrivningen av den här egenskapen, se [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


För beskrivningen av denna egenskap, se [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


För beskrivningen av denna egenskap, se [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


För beskrivningen av den här egenskapen, se [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


För beskrivningen av den här egenskapen, se [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setExportElementAsRectTag(boolean value) {#setExportElementAsRectTag-boolean-}
```
public void setExportElementAsRectTag(boolean value)
```


För beskrivningen av den här egenskapen, se [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


För beskrivningen av den här egenskapen, se [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


För beskrivningen av den här egenskapen, se [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setExportScaleInMatrix(boolean value) {#setExportScaleInMatrix-boolean-}
```
public void setExportScaleInMatrix(boolean value)
```


För beskrivningen av den här egenskapen, se [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


För beskrivningen av den här egenskapen, se [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


För beskrivningen av den här egenskapen, se [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


För beskrivningen av den här egenskapen, se [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSVGFitToViewPort(boolean value) {#setSVGFitToViewPort-boolean-}
```
public void setSVGFitToViewPort(boolean value)
```


För beskrivningen av den här egenskapen, se [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


För beskrivningen av denna egenskap, se [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSavingCustomLinePattern(boolean value) {#setSavingCustomLinePattern-boolean-}
```
public void setSavingCustomLinePattern(boolean value)
```


För beskrivningen av den här egenskapen, se [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setSavingImageSeparately(boolean value) {#setSavingImageSeparately-boolean-}
```
public void setSavingImageSeparately(boolean value)
```


För beskrivningen av den här egenskapen, se [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


För beskrivningen av den här egenskapen, se [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

