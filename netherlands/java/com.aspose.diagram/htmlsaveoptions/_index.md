---
title: HTMLSaveOptions
second_title: Aspose.Diagram voor Java API-referentie
description: Staat toe extra opties op te geven bij het renderen van diagrampagina's naar HTML.
type: docs
weight: 187
url: /nl/java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

Staat toe extra opties op te geven bij het renderen van diagrampagina's naar HTML.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | Initialiseert een nieuw exemplaar van deze klasse dat kan worden gebruikt om een document op te slaan in het Aspose.Diagram.SaveFileFormat-formaat. |
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
| [getExportHiddenPage()](#getExportHiddenPage--) | Definieert of de verborgen pagina geëxporteerd moet worden of niet. |
| [getPageCount()](#getPageCount--) | het aantal pagina's dat moet worden gerenderd in HTML. |
| [getPageIndex()](#getPageIndex--) | de 0-gebaseerde index van de eerste pagina die moet worden gerenderd. |
| [getPageSize()](#getPageSize--) | de paginagrootte voor de gegenereerde afbeeldingen. |
| [getResolution()](#getResolution--) | de resolutie voor de gegenereerde html, in punten per inch. |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | Geeft aan of de html als één enkel bestand moet worden opgeslagen. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specificeert of alle pagina's worden opgeslagen als afbeelding of alleen de voorgrond. |
| [getSaveFormat()](#getSaveFormat--) | Specificeert het formaat waarin de gerenderde diagrampagina's worden opgeslagen als dit opslaanopties-object wordt gebruikt. |
| [getSaveTitle()](#getSaveTitle--) | Definieert of de titel geëxporteerd moet worden of niet. |
| [getSaveToolBar()](#getSaveToolBar--) | Specificeert of de werkbalk wordt opgeslagen. De standaardwaarde is true. |
| [getShapes()](#getShapes--) | vormen om te renderen. |
| [getStreamProvider()](#getStreamProvider--) | de IStreamProvider voor het exporteren van objecten. |
| [getTitle()](#getTitle--) | de titel van het diagram om te renderen in HTML. |
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
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Voor de beschrijving van deze eigenschap, zie [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | Voor de beschrijving van deze eigenschap, zie [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Voor de beschrijving van deze eigenschap, zie [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Voor de beschrijving van deze eigenschap, zie [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setResolution(int value)](#setResolution-int-) | Voor de beschrijving van deze eigenschap, zie [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--) |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | Voor de beschrijving van deze eigenschap, zie [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Voor de beschrijving van deze eigenschap, zie [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--) |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | Voor de beschrijving van deze eigenschap, zie [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--) |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | Voor de beschrijving van deze eigenschap, zie [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Voor de beschrijving van deze eigenschap, zie [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | Voor de beschrijving van deze eigenschap, zie [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


het aantal pagina's dat moet worden gerenderd in HTML. Standaard is MaxValue, wat betekent dat alle pagina's van het diagram worden gerenderd.

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
### getResolution() {#getResolution--}
```
public int getResolution()
```


de resolutie voor de gegenereerde html, in dots per inch. Deze eigenschap heeft alleen effect bij het opslaan als html. De standaardwaarde is 96.

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


Geeft aan of de html als één enkel bestand moet worden opgeslagen. De standaardwaarde is false. Als er meerdere pagina's zijn, moeten die pagina's en andere bronnen in afzonderlijke bestanden worden opgeslagen. Voor sommige scenario's heeft de gebruiker mogelijk slechts één resultaatbestand nodig, bijvoorbeeld voor het gemak van overdracht. In dat geval kan de gebruiker deze eigenschap op true zetten.

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


Specificeert het formaat waarin de gerenderde diagrampagina's worden opgeslagen wanneer dit opslaanopties-object wordt gebruikt. Kan alleen Aspose.Diagram.SaveFileFormat zijn.

**Returns:**
int
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


Definieert of de titel geëxporteerd moet worden of niet. Standaardwaarde is true.

**Returns:**
boolean
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


Specificeert of de werkbalk wordt opgeslagen. De standaardwaarde is true.

**Returns:**
boolean
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


vormen om te renderen. Standaard aantal is 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


de IStreamProvider voor het exporteren van objecten.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


de titel van het diagram om in HTML te renderen. Als Title null is, wordt Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties) gebruikt als titel. Als Diagram.DocumentProperties.Title null of leeg is, wordt de bestandsnaam van het diagram gebruikt als titel.

**Returns:**
java.lang.String
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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--)

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

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


Voor de beschrijving van deze eigenschap, zie [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Voor de beschrijving van deze eigenschap, zie [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


Voor de beschrijving van deze eigenschap, zie [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Voor de beschrijving van deze eigenschap, zie [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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

