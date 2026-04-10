---
title: ImageSaveOptions
second_title: Aspose.Diagram voor Java API-referentie
description: Staat toe extra opties op te geven bij het renderen van diagrampagina's naar afbeeldingen.
type: docs
weight: 200
url: /nl/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

Staat toe extra opties op te geven bij het renderen van diagrampagina's naar afbeeldingen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | Initialiseert een nieuw exemplaar van deze klasse die kan worden gebruikt om gerenderde afbeeldingen op te slaan in het Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat of Aspose.Diagram.SaveFileFormat-formaat. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Maakt een opslaanopties-object van een klasse die geschikt is voor het opgegeven opslagformaat. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | Specificeert het kwaliteitsniveau dat tijdens compositing moet worden gebruikt. |
| [getContentZoom()](#getContentZoom--) | Deze parameter is vergelijkbaar met schaal, maar heeft geen invloed op de grootte van de gegenereerde afbeelding. |
| [getDefaultFont()](#getDefaultFont--) | Wanneer tekens in het diagram Unicode zijn en niet zijn ingesteld met de juiste lettertypewaarde of het lettertype niet lokaal is geïnstalleerd, kunnen ze als blok verschijnen in pdf, afbeelding of XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Instelling voor het renderen van een Emf-metabestand. |
| [getEnlargePage()](#getEnlargePage--) | Specificeert of de pagina moet worden vergroot. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definieert of de gidsvormen geëxporteerd moeten worden of niet. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definieert of de verborgen pagina geëxporteerd moet worden of niet. |
| [getImageBrightness()](#getImageBrightness--) | de helderheid voor de gegenereerde afbeeldingen. |
| [getImageColorMode()](#getImageColorMode--) | de kleurmodus voor de gegenereerde afbeeldingen. |
| [getImageContrast()](#getImageContrast--) | het contrast voor de gegenereerde afbeeldingen. |
| [getInterpolationMode()](#getInterpolationMode--) | Specificeert het algoritme dat wordt gebruikt wanneer afbeeldingen worden geschaald of geroteerd. |
| [getJpegQuality()](#getJpegQuality--) | een waarde die de kwaliteit van de gegenereerde JPEG‑afbeeldingen bepaalt. |
| [getPageCount()](#getPageCount--) | het aantal pagina's dat moet worden gerenderd bij het opslaan naar een multipagina-TIFF-bestand. |
| [getPageIndex()](#getPageIndex--) | de 0-gebaseerde index van de eerste pagina die moet worden gerenderd. |
| [getPageSize()](#getPageSize--) | de paginagrootte voor de gegenereerde afbeeldingen. |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | een waarde die aangeeft hoe pixels worden verschoven tijdens het renderen. |
| [getResolution()](#getResolution--) | de resolutie voor de gegenereerde afbeeldingen, in punten per inch. |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | Specificeert of het opslaan van het gebied hetzelfde is als pdf. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specificeert of alle pagina's worden opgeslagen als afbeelding of alleen de voorgrond. |
| [getSaveFormat()](#getSaveFormat--) | Specificeert het formaat waarin de gerenderde diagrampagina's worden opgeslagen als dit opslaanopties-object wordt gebruikt. |
| [getScale()](#getScale--) | de zoomfactor voor de gegenereerde afbeeldingen. |
| [getShapes()](#getShapes--) | vormen om te renderen. |
| [getSmoothingMode()](#getSmoothingMode--) | Specificeert of gladstrijken (antialiasing) wordt toegepast op lijnen en krommen en op de randen van gevulde gebieden. |
| [getTiffCompression()](#getTiffCompression--) | het type compressie dat moet worden toegepast bij het opslaan van gegenereerde afbeeldingen in het TIFF-formaat. |
| [getWarningCallback()](#getWarningCallback--) | waarschuwingscallback. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definieert of de opmerkingen geëxporteerd moeten worden of niet. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Voor de beschrijving van deze eigenschap, zie [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) |
| [setContentZoom(float value)](#setContentZoom-float-) | Voor de beschrijving van deze eigenschap, zie [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Voor de beschrijving van deze eigenschap, zie [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Voor de beschrijving van deze eigenschap, zie [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Voor de beschrijving van deze eigenschap, zie [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Voor de beschrijving van deze eigenschap, zie [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Voor de beschrijving van deze eigenschap, zie [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) |
| [setImageBrightness(float value)](#setImageBrightness-float-) | Voor de beschrijving van deze eigenschap, zie [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) |
| [setImageColorMode(int value)](#setImageColorMode-int-) | Voor de beschrijving van deze eigenschap, zie [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) |
| [setImageContrast(float value)](#setImageContrast-float-) | Voor de beschrijving van deze eigenschap, zie [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Voor de beschrijving van deze eigenschap, zie [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Voor de beschrijving van deze eigenschap, zie [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Voor de beschrijving van deze eigenschap, zie [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Voor de beschrijving van deze eigenschap, zie [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Voor de beschrijving van deze eigenschap, zie [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | Voor de beschrijving van deze eigenschap, zie [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) |
| [setResolution(float value)](#setResolution-float-) | Voor de beschrijving van deze eigenschap, zie [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | Voor de beschrijving van deze eigenschap, zie [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Voor de beschrijving van deze eigenschap, zie [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) |
| [setScale(float value)](#setScale-float-) | Voor de beschrijving van deze eigenschap, zie [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Voor de beschrijving van deze eigenschap, zie [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Voor de beschrijving van deze eigenschap, zie [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) |
| [setTiffCompression(int value)](#setTiffCompression-int-) | Voor de beschrijving van deze eigenschap, zie [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


Initialiseert een nieuw exemplaar van deze klasse die kan worden gebruikt om gerenderde afbeeldingen op te slaan in het Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat of Aspose.Diagram.SaveFileFormat-formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| saveFormat | int | Kan Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat of Aspose.Diagram.SaveFileFormat zijn. |

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Maakt een opslaanopties-object van een klasse die geschikt is voor het opgegeven opslagformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| saveFormat | int | De Aspose.Diagram.SaveFileFormat waarvoor een opslaanopties-object moet worden gemaakt. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Specificeert het kwaliteitsniveau dat tijdens compositing moet worden gebruikt. Deze eigenschap heeft alleen effect bij het opslaan naar rasterafbeeldingsformaten. De standaardwaarde is Aspose.Diagram.Saving.CompositingQuality.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


Deze parameter is vergelijkbaar met schaal, maar heeft geen effect op de grootte van de gegenereerde afbeelding. De standaardwaarde is 1.0. De waarde moet groter zijn dan 0.

**Returns:**
float
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


Wanneer tekens in het diagram Unicode zijn en niet met de juiste lettertypewaarde zijn ingesteld of het lettertype niet lokaal is geïnstalleerd, kunnen ze als blokken verschijnen in pdf, afbeelding of XPS. Stel het DefaultFont in, zoals MingLiu of MS Gothic, om deze tekens weer te geven.

**Returns:**
java.lang.String
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Instelling voor het renderen van een Emf-metabestand. EMF-metabestanden geïdentificeerd als "EMF+ Dual" kunnen zowel EMF+ records als EMF records bevatten. Elk type record kan worden gebruikt om de afbeelding te renderen, alleen EMF+ records, of alleen EMF records. Wanneer EmfPlusPrefer is ingesteld, worden EMF+ records geparseerd, anders worden alleen EMF records geparseerd. Standaardwaarde is EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


Specificeert of de pagina moet worden vergroot. Als true - pagina vergroten. Als false - pagina niet vergroten. De standaardwaarde is true.

**Returns:**
boolean
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


Definieert of de gidsvormen geëxporteerd moeten worden of niet. Standaardwaarde is true.

**Returns:**
boolean
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Definieert of de verborgen pagina geëxporteerd moet worden of niet. Standaardwaarde is true.

**Returns:**
boolean
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


de helderheid voor de gegenereerde afbeeldingen. Deze eigenschap heeft alleen effect bij het opslaan naar rasterafbeeldingsformaten. De standaardwaarde is 0.5. De waarde moet binnen het bereik tussen 0 en 1 liggen.

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


de kleurmodus voor de gegenereerde afbeeldingen. Deze eigenschap heeft alleen effect bij het opslaan naar rasterafbeeldingsformaten. De standaardwaarde is Aspose.Diagram.Saving.ImageColorMode.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


het contrast voor de gegenereerde afbeeldingen. Deze eigenschap heeft alleen effect bij het opslaan naar rasterafbeeldingsformaten. De standaardwaarde is 0.5. De waarde moet binnen het bereik tussen 0 en 1 liggen.

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Specificeert het algoritme dat wordt gebruikt wanneer afbeeldingen worden geschaald of geroteerd. Deze eigenschap heeft alleen effect bij het opslaan naar rasterafbeeldingsformaten. De standaardwaarde is Aspose.Diagram.Saving.InterpolationMode.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


een waarde die de kwaliteit van de gegenereerde JPEG-afbeeldingen bepaalt. Heeft alleen effect bij het opslaan naar JPEG. Gebruik deze eigenschap om de kwaliteit van gegenereerde afbeeldingen in te stellen of op te vragen bij het opslaan in JPEG-formaat. De waarde kan variëren van 0 tot 100, waarbij 0 de slechtste kwaliteit maar maximale compressie betekent en 100 de beste kwaliteit maar minimale compressie. De standaardwaarde is 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


het aantal pagina's dat moet worden gerenderd bij het opslaan naar een multipage TIFF-bestand. Standaard is MaxValue, wat betekent dat alle pagina's van het diagram worden gerenderd.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


de 0-gebaseerde index van de eerste pagina die moet worden gerenderd. Standaard is 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


de paginagrootte voor de gegenereerde afbeeldingen. Kan [PageSize](../../com.aspose.diagram/pagesize) of null zijn. De standaardwaarde is null. Als PageSize null is, wordt de paginagrootte voor de gegenereerde afbeelding verkregen uit het bron diagram.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


een waarde die aangeeft hoe pixels worden verschoven tijdens het renderen. Deze eigenschap heeft alleen effect bij het opslaan naar rasterafbeeldingsformaten. De standaardwaarde is Aspose.Diagram.Saving.PixelOffsetMode.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


de resolutie voor de gegenereerde afbeeldingen, in dots per inch. Deze eigenschap heeft alleen effect bij het opslaan naar rasterafbeeldingsformaten. De standaardwaarde is 96.

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


Specificeert of het opslaan van het gebied gelijk is aan pdf. Indien true - gerenderd gebied gelijk aan pdf. Indien false - gerenderd gebied standaard. De standaardwaarde is false.

**Returns:**
boolean
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Specificeert of alle pagina's in de afbeelding worden opgeslagen of alleen de voorgrond. Als true - worden alleen voorgrondpagina's gerenderd (met achtergrond indien aanwezig). Als false - worden voorgrondpagina's gerenderd (met achtergrond indien aanwezig) waarna lege achtergrondpagina's volgen. Kan alleen true retourneren wanneer PageCount > 1. De standaardwaarde is false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Specificeert het formaat waarin de gerenderde diagrampagina's worden opgeslagen als dit save‑options‑object wordt gebruikt. Kan een van de volgende zijn: Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat of Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


de zoomfactor voor de gegenereerde afbeeldingen. De standaardwaarde is 1.0. De waarde moet groter zijn dan 0.

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


vormen om te renderen. Standaard aantal is 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Specificeert of smoothing (antialiasing) wordt toegepast op lijnen en krommen en de randen van gevulde gebieden. Deze eigenschap heeft alleen effect bij het opslaan naar rasterafbeeldingsformaten. De standaardwaarde is Aspose.Diagram.Saving.SmoothingMode.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


het type compressie dat moet worden toegepast bij het opslaan van gegenereerde afbeeldingen naar het TIFF-formaat. Heeft alleen effect bij het opslaan naar TIFF. De standaardwaarde is Aspose.Diagram.Saving.TiffCompression.

**Returns:**
int
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


waarschuwingscallback.

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


Definieert of de opmerkingen geëxporteerd moeten worden of niet. Standaardwaarde is false.

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


Voor de beschrijving van deze eigenschap, zie [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


Voor de beschrijving van deze eigenschap, zie [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Voor de beschrijving van deze eigenschap, zie [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


Voor de beschrijving van deze eigenschap, zie [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


Voor de beschrijving van deze eigenschap, zie [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


Voor de beschrijving van deze eigenschap, zie [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


Voor de beschrijving van deze eigenschap, zie [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Voor de beschrijving van deze eigenschap, zie [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Voor de beschrijving van deze eigenschap, zie [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Voor de beschrijving van deze eigenschap, zie [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Voor de beschrijving van deze eigenschap, zie [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


Voor de beschrijving van deze eigenschap, zie [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Voor de beschrijving van deze eigenschap, zie [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


Voor de beschrijving van deze eigenschap, zie [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

