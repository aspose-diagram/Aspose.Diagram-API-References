---
title: ImageSaveOptions
second_title: Aspose.Diagram för Java API-referens
description: Tillåter att ange ytterligare alternativ när diagramssidor renderas till bilder.
type: docs
weight: 200
url: /sv/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

Tillåter att ange ytterligare alternativ när diagramssidor renderas till bilder.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | Initierar en ny instans av denna klass som kan användas för att spara renderade bilder i formatet Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat eller Aspose.Diagram.SaveFileFormat. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Skapar ett sparaalternativobjekt av en klass som är lämplig för det angivna sparformatet. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | Anger kvalitetsnivån som ska användas vid sammansättning. |
| [getContentZoom()](#getContentZoom--) | Denna parameter liknar skala, men påverkar inte den genererade bildens storlek. |
| [getDefaultFont()](#getDefaultFont--) | När tecken i diagrammet är Unicode och inte har ställts in med korrekt teckensnittsvärde eller teckensnittet inte är installerat lokalt, kan de visas som block i PDF, bild eller XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Inställning för rendering av Emf-metafil. |
| [getEnlargePage()](#getEnlargePage--) | Anger om sidan ska förstoras. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definierar om guideformer ska exporteras eller inte. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definierar om dolda sidor ska exporteras eller inte. |
| [getImageBrightness()](#getImageBrightness--) | ljusstyrkan för de genererade bilderna. |
| [getImageColorMode()](#getImageColorMode--) | färgläget för de genererade bilderna. |
| [getImageContrast()](#getImageContrast--) | kontrasten för de genererade bilderna. |
| [getInterpolationMode()](#getInterpolationMode--) | Anger den algoritm som används när bilder skalas eller roteras. |
| [getJpegQuality()](#getJpegQuality--) | ett värde som bestämmer kvaliteten på de genererade JPEG-bilderna. |
| [getPageCount()](#getPageCount--) | antalet sidor som ska renderas när du sparar till en flersidig TIFF-fil. |
| [getPageIndex()](#getPageIndex--) | det nollbaserade indexet för den första sidan som ska renderas. |
| [getPageSize()](#getPageSize--) | sidstorleken för de genererade bilderna. |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | ett värde som specificerar hur pixlar förskjuts under rendering. |
| [getResolution()](#getResolution--) | upplösningen för de genererade bilderna, i punkter per tum. |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | Anger om sparningsområdet är samma som PDF. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Anger om alla sidor ska sparas som bild eller endast förgrunden. |
| [getSaveFormat()](#getSaveFormat--) | Anger formatet som de renderade diagrammetsidorna kommer att sparas i om detta sparaalternativobjekt används. |
| [getScale()](#getScale--) | zoomfaktorn för de genererade bilderna. |
| [getShapes()](#getShapes--) | former att rendera. |
| [getSmoothingMode()](#getSmoothingMode--) | Specificerar om jämning (antialiasing) tillämpas på linjer och kurvor samt kanterna på fyllda områden. |
| [getTiffCompression()](#getTiffCompression--) | kompressionstypen som ska tillämpas när genererade bilder sparas i TIFF-format. |
| [getWarningCallback()](#getWarningCallback--) | varnings‑återanrop. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definierar om kommentarer ska exporteras eller inte. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | För beskrivning av denna egenskap, se [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) |
| [setContentZoom(float value)](#setContentZoom-float-) | För beskrivning av denna egenskap, se [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | För beskrivningen av denna egenskap, se [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | För beskrivningen av denna egenskap, se [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | För beskrivningen av den här egenskapen, se [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | För beskrivningen av den här egenskapen, se [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | För beskrivningen av den här egenskapen, se [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | För beskrivning av denna egenskap, se [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) |
| [setImageBrightness(float value)](#setImageBrightness-float-) | För beskrivning av denna egenskap, se [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) |
| [setImageColorMode(int value)](#setImageColorMode-int-) | För beskrivning av denna egenskap, se [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) |
| [setImageContrast(float value)](#setImageContrast-float-) | För beskrivning av denna egenskap, se [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | För beskrivning av denna egenskap, se [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | För beskrivning av denna egenskap, se [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | För beskrivning av denna egenskap, se [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | För beskrivning av denna egenskap, se [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | För beskrivningen av den här egenskapen, se [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | För beskrivning av denna egenskap, se [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) |
| [setResolution(float value)](#setResolution-float-) | För beskrivning av denna egenskap, se [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | För beskrivning av denna egenskap, se [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | För beskrivning av denna egenskap, se [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | För beskrivning av denna egenskap, se [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) |
| [setScale(float value)](#setScale-float-) | För beskrivning av denna egenskap, se [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | För beskrivningen av den här egenskapen, se [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | För beskrivning av denna egenskap, se [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) |
| [setTiffCompression(int value)](#setTiffCompression-int-) | För beskrivning av denna egenskap, se [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


Initierar en ny instans av denna klass som kan användas för att spara renderade bilder i formatet Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat eller Aspose.Diagram.SaveFileFormat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| saveFormat | int | Kan vara Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat eller Aspose.Diagram.SaveFileFormat. |

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
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Anger kvalitetsnivån som ska användas under sammanslagning. Denna egenskap har effekt endast vid sparande till rasterbildformat. Standardvärdet är Aspose.Diagram.Saving.CompositingQuality.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


Denna parameter liknar skala, men påverkar inte den genererade bildens storlek. Standardvärdet är 1.0. Värdet måste vara större än 0.

**Returns:**
float
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
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


Ljusstyrkan för de genererade bilderna. Denna egenskap har effekt endast vid sparande till rasterbildformat. Standardvärdet är 0.5. Värdet måste ligga i intervallet mellan 0 och 1.

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


Färgläget för de genererade bilderna. Denna egenskap har effekt endast vid sparande till rasterbildformat. Standardvärdet är Aspose.Diagram.Saving.ImageColorMode.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


Kontrasten för de genererade bilderna. Denna egenskap har effekt endast vid sparande till rasterbildformat. Standardvärdet är 0.5. Värdet måste ligga i intervallet mellan 0 och 1.

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Anger algoritmen som används när bilder skalas eller roteras. Denna egenskap har effekt endast vid sparande till rasterbildformat. Standardvärdet är Aspose.Diagram.Saving.InterpolationMode.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Ett värde som bestämmer kvaliteten på de genererade JPEG-bilderna. Har effekt endast vid sparande till JPEG. Använd denna egenskap för att hämta eller ange kvaliteten på genererade bilder när du sparar i JPEG-format. Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal komprimering och 100 betyder bästa kvalitet men minimal komprimering. Standardvärdet är 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Antalet sidor som ska renderas vid sparande till en flersidig TIFF-fil. Standard är MaxValue vilket betyder att alla diagramsidors renderas.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


det 0-baserade indexet för den första sidan som ska renderas. Standard är 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


sidstorleken för de genererade bilderna. Kan vara [PageSize](../../com.aspose.diagram/pagesize) eller null. Standardvärdet är null. Om PageSize är null hämtas sidstorleken för den genererade bilden från källdiagrammet.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


Ett värde som specificerar hur pixlar förskjuts under rendering. Denna egenskap har effekt endast vid sparande till rasterbildformat. Standardvärdet är Aspose.Diagram.Saving.PixelOffsetMode.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


Upplösningen för de genererade bilderna, i punkter per tum. Denna egenskap har effekt endast vid sparande till rasterbildformat. Standardvärdet är 96.

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


Anger om sparningsområdet ska vara samma som PDF. Om true – renderat område är samma som PDF. Om false – renderat område är standard. Standardvärdet är false.

**Returns:**
boolean
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Anger om alla sidor ska sparas i bilden eller bara förgrunden. Om true – renderas endast förgrundssidor (med bakgrund om den finns). Om false – renderas förgrundssidor (med bakgrund om den finns) följt av tomma bakgrundssidor. Kan returnera true endast när PageCount > 1. Standardvärdet är false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Anger formatet som de renderade diagrammen ska sparas i om detta sparaalternativobjekt används. Kan vara Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat eller Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


Zoomfaktorn för de genererade bilderna. Standardvärdet är 1.0. Värdet måste vara större än 0.

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


former att rendera. Standardantalet är 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Anger om jämning (kantutjämning) tillämpas på linjer och kurvor samt kanterna på fyllda områden. Denna egenskap har effekt endast vid sparande till rasterbildformat. Standardvärdet är Aspose.Diagram.Saving.SmoothingMode.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


Kompressionstypen som ska tillämpas när genererade bilder sparas i TIFF-format. Har effekt endast vid sparande till TIFF. Standardvärdet är Aspose.Diagram.Saving.TiffCompression.

**Returns:**
int
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


För beskrivning av denna egenskap, se [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


För beskrivning av denna egenskap, se [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

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


För beskrivning av denna egenskap, se [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


För beskrivning av denna egenskap, se [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


För beskrivning av denna egenskap, se [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


För beskrivning av denna egenskap, se [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


För beskrivning av denna egenskap, se [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


För beskrivning av denna egenskap, se [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


För beskrivning av denna egenskap, se [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


För beskrivning av denna egenskap, se [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)

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

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


För beskrivning av denna egenskap, se [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


För beskrivning av denna egenskap, se [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


För beskrivning av denna egenskap, se [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


För beskrivning av denna egenskap, se [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


För beskrivning av denna egenskap, se [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


För beskrivning av denna egenskap, se [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


För beskrivningen av den här egenskapen, se [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


För beskrivning av denna egenskap, se [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


För beskrivning av denna egenskap, se [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

