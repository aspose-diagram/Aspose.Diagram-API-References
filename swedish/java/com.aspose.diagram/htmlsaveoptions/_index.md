---
title: HTMLSaveOptions
second_title: Aspose.Diagram för Java API-referens
description: Tillåter att ange ytterligare alternativ när diagramssidor renderas till HTML.
type: docs
weight: 187
url: /sv/java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

Tillåter att ange ytterligare alternativ när diagramssidor renderas till HTML.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | Initierar en ny instans av den här klassen som kan användas för att spara ett dokument i formatet Aspose.Diagram.SaveFileFormat. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Skapar ett sparaalternativobjekt av en klass som är lämplig för det angivna sparformatet. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | När tecken i diagrammet är Unicode och inte har ställts in med korrekt teckensnittsvärde eller teckensnittet inte är installerat lokalt, kan de visas som block i PDF, bild eller XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Inställning för rendering av Emf-metafil. |
| [getEnlargePage()](#getEnlargePage--) | Anger om sidan ska förstoras. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Definierar om guideformer ska exporteras eller inte. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definierar om dolda sidor ska exporteras eller inte. |
| [getPageCount()](#getPageCount--) | antalet sidor som ska renderas i HTML. |
| [getPageIndex()](#getPageIndex--) | det nollbaserade indexet för den första sidan som ska renderas. |
| [getPageSize()](#getPageSize--) | sidstorleken för de genererade bilderna. |
| [getResolution()](#getResolution--) | upplösningen för den genererade HTML:n, i punkter per tum. |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | Indikerar om HTML ska sparas som en enda fil. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Anger om alla sidor ska sparas som bild eller endast förgrunden. |
| [getSaveFormat()](#getSaveFormat--) | Anger formatet som de renderade diagrammetsidorna kommer att sparas i om detta sparaalternativobjekt används. |
| [getSaveTitle()](#getSaveTitle--) | Definierar om titeln ska exporteras eller inte. |
| [getSaveToolBar()](#getSaveToolBar--) | Anger om verktygsfältet ska sparas. Standardvärdet är true. |
| [getShapes()](#getShapes--) | former att rendera. |
| [getStreamProvider()](#getStreamProvider--) | IStreamProvider för att exportera objekt. |
| [getTitle()](#getTitle--) | titeln på diagrammet som ska renderas i HTML. |
| [getWarningCallback()](#getWarningCallback--) | varnings‑återanrop. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Definierar om kommentarer ska exporteras eller inte. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | För beskrivningen av denna egenskap, se [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | För beskrivningen av denna egenskap, se [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | För beskrivningen av den här egenskapen, se [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | För beskrivningen av den här egenskapen, se [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | För beskrivningen av den här egenskapen, se [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | För beskrivningen av den här egenskapen, se [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | För beskrivningen av den här egenskapen, se [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | För beskrivningen av den här egenskapen, se [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | För beskrivningen av den här egenskapen, se [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setResolution(int value)](#setResolution-int-) | För beskrivningen av den här egenskapen, se [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--) |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | För beskrivningen av den här egenskapen, se [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | För beskrivningen av den här egenskapen, se [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | För beskrivningen av den här egenskapen, se [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--) |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | För beskrivningen av den här egenskapen, se [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--) |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | För beskrivningen av den här egenskapen, se [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | För beskrivningen av den här egenskapen, se [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | För beskrivningen av den här egenskapen, se [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | För beskrivningen av den här egenskapen, se [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


antalet sidor som ska renderas i HTML. Standard är MaxValue vilket betyder att alla diagramssidor kommer att renderas.

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
### getResolution() {#getResolution--}
```
public int getResolution()
```


upplösningen för den genererade html, i punkter per tum. Denna egenskap har endast effekt vid sparande till html. Standardvärdet är 96.

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


Anger om html ska sparas som en enda fil. Standardvärdet är false. Om det finns flera sidor, måste dessa sidor och andra resurser sparas i separata filer. I vissa scenarier kan användaren behöva bara en resulterande fil, till exempel för att underlätta överföring. I så fall kan användaren sätta denna egenskap till true.

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


Anger det format i vilket de renderade diagrammenyerna ska sparas om detta spara-alternativobjekt används. Kan endast vara Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


Definierar om titeln ska exporteras eller inte. Standardvärdet är true.

**Returns:**
boolean
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


Anger om verktygsfältet ska sparas. Standardvärdet är true.

**Returns:**
boolean
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


former att rendera. Standardantalet är 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


IStreamProvider för att exportera objekt.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


titeln på diagrammet som ska renderas i HTML. Om Title är null kommer Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties) att användas som Title. Om Diagram.DocumentProperties.Title är null eller tomt används diagramfilens namn som Title.

**Returns:**
java.lang.String
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


För beskrivningen av den här egenskapen, se [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


För beskrivningen av den här egenskapen, se [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


För beskrivningen av den här egenskapen, se [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--)

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

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


För beskrivningen av den här egenskapen, se [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


För beskrivningen av den här egenskapen, se [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


För beskrivningen av den här egenskapen, se [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


För beskrivningen av den här egenskapen, se [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


För beskrivningen av den här egenskapen, se [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


För beskrivningen av den här egenskapen, se [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--)

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

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


För beskrivningen av den här egenskapen, se [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


För beskrivningen av den här egenskapen, se [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

