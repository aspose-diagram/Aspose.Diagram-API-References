---
title: PdfSaveOptions
second_title: Aspose.Diagram voor Java API-referentie
description: Staat toe om extra opties op te geven bij het renderen van diagrampagina's naar PDF.
type: docs
weight: 281
url: /nl/java/com.aspose.diagram/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PdfSaveOptions extends RenderingSaveOptions
```

Staat toe om extra opties op te geven bij het renderen van diagrampagina's naar PDF.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Initialiseert een nieuw exemplaar van deze klasse dat kan worden gebruikt om een document op te slaan in het Aspose.Diagram.SaveFileFormat-formaat. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Maakt een opslaanopties-object van een klasse die geschikt is voor het opgegeven opslagformaat. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompliance()](#getCompliance--) | Gewenst conformiteitsniveau voor het gegenereerde PDF‑document. |
| [getDefaultFont()](#getDefaultFont--) | Wanneer tekens in het diagram Unicode zijn en niet zijn ingesteld met de juiste lettertypewaarde of het lettertype niet lokaal is geïnstalleerd, kunnen ze als blok verschijnen in pdf, afbeelding of XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Instelling voor het renderen van een Emf-metabestand. |
| [getEncryptionDetails()](#getEncryptionDetails--) | een encryptiedetails. |
| [getEnlargePage()](#getEnlargePage--) | Specificeert of de pagina moet worden vergroot. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definieert of de gidsvormen geëxporteerd moeten worden of niet. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definieert of de verborgen pagina geëxporteerd moet worden of niet. |
| [getHorizontalResolution()](#getHorizontalResolution--) | de horizontale resolutie voor gegenereerde afbeeldingen, in dots per inch. |
| [getJpegQuality()](#getJpegQuality--) | Specificeert de kwaliteit van JPEG-compressie voor afbeeldingen (als JPEG-compressie wordt gebruikt). |
| [getPageCount()](#getPageCount--) | het aantal pagina's om te renderen in PDF. |
| [getPageIndex()](#getPageIndex--) | de 0-gebaseerde index van de eerste pagina die moet worden gerenderd. |
| [getPageSavingCallback()](#getPageSavingCallback--) | Beheer/Geef de voortgang van het opslaan van pagina's aan. |
| [getPageSize()](#getPageSize--) | de paginagrootte voor de gegenereerde afbeeldingen. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specificeert of alle pagina's worden opgeslagen als afbeelding of alleen de voorgrond. |
| [getSaveFormat()](#getSaveFormat--) | Specificeert het formaat waarin de gerenderde diagrampagina's worden opgeslagen als dit opslaanopties-object wordt gebruikt. |
| [getShapes()](#getShapes--) | vormen om te renderen. |
| [getSplitMultiPages()](#getSplitMultiPages--) | Definieert of het diagram wordt opgesplitst in meerdere pagina's volgens de paginainstelling. |
| [getTextCompression()](#getTextCompression--) | Specificeert het compressietype dat moet worden gebruikt voor alle contentstreams, behalve afbeeldingen. |
| [getVerticalResolution()](#getVerticalResolution--) | de verticale resolutie voor gegenereerde afbeeldingen, in dots per inch. |
| [getWarningCallback()](#getWarningCallback--) | waarschuwingscallback. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definieert of de opmerkingen geëxporteerd moeten worden of niet. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompliance(int value)](#setCompliance-int-) | Voor de beschrijving van deze eigenschap, zie [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Voor de beschrijving van deze eigenschap, zie [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEncryptionDetails(PdfEncryptionDetails value)](#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-) | Voor de beschrijving van deze eigenschap, zie [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Voor de beschrijving van deze eigenschap, zie [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Voor de beschrijving van deze eigenschap, zie [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Voor de beschrijving van deze eigenschap, zie [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Voor de beschrijving van deze eigenschap, zie [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--) |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Voor de beschrijving van deze eigenschap, zie [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Voor de beschrijving van deze eigenschap, zie [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Voor de beschrijving van deze eigenschap, zie [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Voor de beschrijving van deze eigenschap, zie [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--) |
| [setPageSavingCallback(IPageSavingCallback value)](#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-) | Voor de beschrijving van deze eigenschap, zie [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Voor de beschrijving van deze eigenschap, zie [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Voor de beschrijving van deze eigenschap, zie [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Voor de beschrijving van deze eigenschap, zie [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSplitMultiPages(boolean value)](#setSplitMultiPages-boolean-) | Voor de beschrijving van deze eigenschap, zie [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--) |
| [setTextCompression(int value)](#setTextCompression-int-) | Voor de beschrijving van deze eigenschap, zie [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--) |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | Voor de beschrijving van deze eigenschap, zie [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Initialiseert een nieuw exemplaar van deze klasse dat kan worden gebruikt om een document op te slaan in het Aspose.Diagram.SaveFileFormat-formaat.

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
### getCompliance() {#getCompliance--}
```
public int getCompliance()
```


Gewenst conformiteitsniveau voor gegenereerd PDF-document. Standaard is PdfCompliance.PDF\_15.

**Returns:**
int
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
### getEncryptionDetails() {#getEncryptionDetails--}
```
public PdfEncryptionDetails getEncryptionDetails()
```


een encryptiedetails. Als deze niet is ingesteld, wordt er geen encryptie uitgevoerd.

**Returns:**
[PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails)
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
### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


de horizontale resolutie voor gegenereerde afbeeldingen, in dots per inch. Geldt voor de afbeeldinggeneratiemethode, behalve EMF-formaat afbeeldingen. De standaardwaarde is 96.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Specificeert de kwaliteit van JPEG-compressie voor afbeeldingen (als JPEG-compressie wordt gebruikt). Standaard is 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


het aantal pagina's om te renderen in PDF. Standaard is MaxValue, wat betekent dat alle pagina's van het diagram worden gerenderd.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


de 0-gebaseerde index van de eerste pagina die moet worden gerenderd. Standaard is 0.

**Returns:**
int
### getPageSavingCallback() {#getPageSavingCallback--}
```
public IPageSavingCallback getPageSavingCallback()
```


Beheer/Geef de voortgang van het opslaan van pagina's aan.

**Returns:**
[IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback)
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


de paginagrootte voor de gegenereerde afbeeldingen. Kan [PageSize](../../com.aspose.diagram/pagesize) of null zijn. De standaardwaarde is null. Als PageSize null is, wordt de paginagrootte voor de gegenereerde afbeelding verkregen uit het bron diagram.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
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


Specificeert het formaat waarin de gerenderde diagrampagina's worden opgeslagen wanneer dit opslaanopties-object wordt gebruikt. Kan alleen Aspose.Diagram.SaveFileFormat zijn.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


vormen om te renderen. Standaard aantal is 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSplitMultiPages() {#getSplitMultiPages--}
```
public boolean getSplitMultiPages()
```


Definieert of het diagram wordt opgesplitst in meerdere pagina's volgens de paginainstelling. Standaardwaarde is false.

**Returns:**
boolean
### getTextCompression() {#getTextCompression--}
```
public int getTextCompression()
```


Specificeert het compressietype dat moet worden gebruikt voor alle contentstreams, behalve afbeeldingen. Standaard is PdfTextCompression.FLATE.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


de verticale resolutie voor gegenereerde afbeeldingen, in dots per inch. Van toepassing op de methode voor het genereren van afbeeldingen, behalve Emf-formaat afbeeldingen. De standaardwaarde is 96.

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




### setCompliance(int value) {#setCompliance-int-}
```
public void setCompliance(int value)
```


Voor de beschrijving van deze eigenschap, zie [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

### setEncryptionDetails(PdfEncryptionDetails value) {#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-}
```
public void setEncryptionDetails(PdfEncryptionDetails value)
```


Voor de beschrijving van deze eigenschap, zie [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails) |  |

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


Voor de beschrijving van deze eigenschap, zie [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int value)
```


Voor de beschrijving van deze eigenschap, zie [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Voor de beschrijving van deze eigenschap, zie [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPageSavingCallback(IPageSavingCallback value) {#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-}
```
public void setPageSavingCallback(IPageSavingCallback value)
```


Voor de beschrijving van deze eigenschap, zie [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback) |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Voor de beschrijving van deze eigenschap, zie [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Voor de beschrijving van deze eigenschap, zie [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSplitMultiPages(boolean value) {#setSplitMultiPages-boolean-}
```
public void setSplitMultiPages(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setTextCompression(int value) {#setTextCompression-int-}
```
public void setTextCompression(int value)
```


Voor de beschrijving van deze eigenschap, zie [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int value)
```


Voor de beschrijving van deze eigenschap, zie [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--)

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

