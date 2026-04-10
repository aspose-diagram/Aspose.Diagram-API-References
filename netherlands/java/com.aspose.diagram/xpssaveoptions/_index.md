---
title: XPSSaveOptions
second_title: Aspose.Diagram voor Java API-referentie
description: Staat toe om extra opties op te geven bij het renderen van diagrampagina's naar XPS.
type: docs
weight: 453
url: /nl/java/com.aspose.diagram/xpssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XPSSaveOptions extends SaveOptions
```

Staat toe om extra opties op te geven bij het renderen van diagrampagina's naar XPS.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XPSSaveOptions()](#XPSSaveOptions--) | Initialiseert een nieuw exemplaar van deze klasse dat kan worden gebruikt om een document op te slaan in het Aspose.Diagram.SaveFileFormat-formaat. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Maakt een opslaanopties-object van een klasse die geschikt is voor het opgegeven opslagformaat. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Wanneer tekens in het diagram Unicode zijn en niet zijn ingesteld met de juiste lettertypewaarde of het lettertype niet lokaal is geïnstalleerd, kunnen ze als blok verschijnen in pdf, afbeelding of XPS. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Definieert of de verborgen pagina geëxporteerd moet worden of niet. |
| [getPageCount()](#getPageCount--) | het aantal pagina's om te renderen in XPS. |
| [getPageIndex()](#getPageIndex--) | de 0-gebaseerde index van de eerste pagina die moet worden gerenderd. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specificeert of alle pagina's worden opgeslagen als afbeelding of alleen de voorgrond. |
| [getSaveFormat()](#getSaveFormat--) | Specificeert het formaat waarin de gerenderde diagrampagina's worden opgeslagen als dit opslaanopties-object wordt gebruikt. |
| [getWarningCallback()](#getWarningCallback--) | waarschuwingscallback. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Voor de beschrijving van deze eigenschap, zie [getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | Voor de beschrijving van deze eigenschap, zie [getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Voor de beschrijving van deze eigenschap, zie [getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Voor de beschrijving van deze eigenschap, zie [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XPSSaveOptions() {#XPSSaveOptions--}
```
public XPSSaveOptions()
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


het aantal pagina's om te renderen in XPS. Standaard is MaxValue, wat betekent dat alle pagina's van het diagram worden gerenderd.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


de 0-gebaseerde index van de eerste pagina die moet worden gerenderd. Standaard is 0.

**Returns:**
int
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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--)

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

