---
title: DiagramSaveOptions
second_title: Aspose.Diagram voor Java API-referentie
description: Kan worden gebruikt om extra opties op te geven bij het opslaan van een diagram in Visio VDXVSX-formaat.
type: docs
weight: 119
url: /nl/java/com.aspose.diagram/diagramsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class DiagramSaveOptions extends SaveOptions
```

Kan worden gebruikt om extra opties op te geven bij het opslaan van een diagram in Visio (VDX\\VSX)-formaat. Op dit moment biedt alleen de eigenschap SaveFormat, maar in de toekomst zullen er andere opties worden toegevoegd.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DiagramSaveOptions()](#DiagramSaveOptions--) | Initialiseert een nieuw exemplaar van deze klasse die kan worden gebruikt om een diagram op te slaan in het VDX-formaat. |
| [DiagramSaveOptions(int saveFormat)](#DiagramSaveOptions-int-) | Initialiseert een nieuw exemplaar van deze klasse dat kan worden gebruikt om een diagram op te slaan in het VDX- of VSX-formaat. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Maakt een opslaanopties-object van een klasse die geschikt is voor het opgegeven opslagformaat. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoFitPageToDrawingContent()](#getAutoFitPageToDrawingContent--) | Definieert of de pagina moet worden vergroot om de tekeninhoud te passen of niet. |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Wanneer tekens in het diagram Unicode zijn en niet zijn ingesteld met de juiste lettertypewaarde of het lettertype niet lokaal is geïnstalleerd, kunnen ze als blok verschijnen in pdf, afbeelding of XPS. |
| [getSaveFormat()](#getSaveFormat--) | Specificeert het formaat waarin het gerenderde diagram wordt opgeslagen als dit opslaanopties‑object wordt gebruikt. |
| [getWarningCallback()](#getWarningCallback--) | waarschuwingscallback. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoFitPageToDrawingContent(boolean value)](#setAutoFitPageToDrawingContent-boolean-) | Voor de beschrijving van deze eigenschap, zie [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DiagramSaveOptions() {#DiagramSaveOptions--}
```
public DiagramSaveOptions()
```


Initialiseert een nieuw exemplaar van deze klasse die kan worden gebruikt om een diagram op te slaan in het VDX-formaat.

### DiagramSaveOptions(int saveFormat) {#DiagramSaveOptions-int-}
```
public DiagramSaveOptions(int saveFormat)
```


Initialiseert een nieuw exemplaar van deze klasse dat kan worden gebruikt om een diagram op te slaan in het VDX- of VSX-formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| saveFormat | int |  |

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
### getAutoFitPageToDrawingContent() {#getAutoFitPageToDrawingContent--}
```
public boolean getAutoFitPageToDrawingContent()
```


Definieert of de pagina moet worden vergroot om de tekeninhoud te passen of niet. Standaardwaarde is false.

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
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Specificeert het formaat waarin het gerenderde diagram wordt opgeslagen als dit opslaanopties‑object wordt gebruikt. Kan Aspose.Diagram.SaveFileFormat of Aspose.Diagram.SaveFileFormat zijn.

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




### setAutoFitPageToDrawingContent(boolean value) {#setAutoFitPageToDrawingContent-boolean-}
```
public void setAutoFitPageToDrawingContent(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Voor de beschrijving van deze eigenschap, zie [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--)

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

