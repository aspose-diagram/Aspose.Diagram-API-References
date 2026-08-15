---
title: PrintSaveOptions
second_title: Aspose.Diagram för Java API-referens
description: Tillåter att ange ytterligare alternativ vid utskrift av diagram.
type: docs
weight: 308
url: /sv/java/com.aspose.diagram/printsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PrintSaveOptions extends RenderingSaveOptions
```

Tillåter att ange ytterligare alternativ vid utskrift av diagram.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PrintSaveOptions()](#PrintSaveOptions--) | Initierar en ny instans av denna klass |
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
| [getPageCount()](#getPageCount--) | antalet sidor som ska renderas när du sparar till en flersidig fil. |
| [getPageSize()](#getPageSize--) | sidstorleken för de genererade bilderna. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Anger om alla sidor ska skrivas ut eller endast förgrunden. |
| [getSaveFormat()](#getSaveFormat--) | Anger det format i vilket dokumentet kommer att sparas om detta SaveOptions‑objekt används. |
| [getShapes()](#getShapes--) | former att rendera. |
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
| [setPageCount(int value)](#setPageCount-int-) | För beskrivningen av denna egenskap, se [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | För beskrivningen av den här egenskapen, se [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | För beskrivningen av denna egenskap, se [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | För beskrivningen av denna egenskap, se [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | För beskrivningen av den här egenskapen, se [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintSaveOptions() {#PrintSaveOptions--}
```
public PrintSaveOptions()
```


Initierar en ny instans av denna klass

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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


antalet sidor som ska renderas när du sparar till en flersidig fil. Standard är MaxValue vilket betyder att alla diagrammets sidor kommer att skrivas ut.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


sidstorleken för de genererade bilderna. Kan vara [PageSize](../../com.aspose.diagram/pagesize) eller null. Standardvärdet är null. Om PageSize är null hämtas sidstorleken för den genererade bilden från källdiagrammet.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Anger om alla sidor ska skrivas ut eller endast förgrunden. Om true - skrivs endast förgrundssidor (med bakgrund om den finns). Om false - skrivs förgrundssidor (med bakgrund om den finns) följt av tomma bakgrundssidor. Kan returnera true endast när PageCount > 1. Standardvärdet är false.

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

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


För beskrivningen av denna egenskap, se [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--)

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

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


För beskrivningen av denna egenskap, se [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--)

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

