---
title: PrintSaveOptions
second_title: Aspose.Diagram voor Java API-referentie
description: Staat toe om extra opties op te geven bij het afdrukken van een diagram.
type: docs
weight: 308
url: /nl/java/com.aspose.diagram/printsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PrintSaveOptions extends RenderingSaveOptions
```

Staat toe om extra opties op te geven bij het afdrukken van een diagram.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PrintSaveOptions()](#PrintSaveOptions--) | Initialiseert een nieuw exemplaar van deze klasse |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Maakt een opslaanopties-object van een klasse die geschikt is voor het opgegeven opslagformaat. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Wanneer tekens in het diagram Unicode zijn en niet zijn ingesteld met de juiste lettertypewaarde of het lettertype niet lokaal is geïnstalleerd, kunnen ze als blok verschijnen in pdf, afbeelding of XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Instelling voor het renderen van een Emf-metabestand. |
| [getEnlargePage()](#getEnlargePage--) | Specificeert of de pagina moet worden vergroot. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definieert of de gidsvormen geëxporteerd moeten worden of niet. |
| [getPageCount()](#getPageCount--) | het aantal pagina's dat moet worden gerenderd bij het opslaan naar een meerpagina-bestand. |
| [getPageSize()](#getPageSize--) | de paginagrootte voor de gegenereerde afbeeldingen. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specificeert of alle pagina's worden afgedrukt of alleen de voorgrond. |
| [getSaveFormat()](#getSaveFormat--) | Specificeert het formaat waarin het document wordt opgeslagen als dit save‑options‑object wordt gebruikt. |
| [getShapes()](#getShapes--) | vormen om te renderen. |
| [getWarningCallback()](#getWarningCallback--) | waarschuwingscallback. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definieert of de opmerkingen geëxporteerd moeten worden of niet. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Voor de beschrijving van deze eigenschap, zie [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Voor de beschrijving van deze eigenschap, zie [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Voor de beschrijving van deze eigenschap, zie [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Voor de beschrijving van deze eigenschap, zie [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setPageCount(int value)](#setPageCount-int-) | Voor de beschrijving van deze eigenschap, zie [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Voor de beschrijving van deze eigenschap, zie [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Voor de beschrijving van deze eigenschap, zie [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Voor de beschrijving van deze eigenschap, zie [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintSaveOptions() {#PrintSaveOptions--}
```
public PrintSaveOptions()
```


Initialiseert een nieuw exemplaar van deze klasse

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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


het aantal pagina's dat moet worden gerenderd bij het opslaan naar een meerpagina-bestand. Standaard is MaxValue, wat betekent dat alle pagina's van het diagram worden afgedrukt.

**Returns:**
int
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


Specificeert of alle pagina's worden afgedrukt of alleen de voorgrond. Als true - worden alleen voorgrondpagina's afgedrukt (met achtergrond indien aanwezig). Als false - worden voorgrondpagina's afgedrukt (met achtergrond indien aanwezig) waarna lege achtergrondpagina's. Kan alleen true retourneren wanneer PageCount > 1. De standaardwaarde is false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Specificeert het formaat waarin het document wordt opgeslagen als dit save‑options‑object wordt gebruikt.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


vormen om te renderen. Standaard aantal is 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--)

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

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

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

