---
title: DiagramSaveOptions
second_title: Aspose.Diagram för Java API-referens
description: Kan användas för att ange ytterligare alternativ när ett diagram sparas i Visio VDXVSX-format.
type: docs
weight: 119
url: /sv/java/com.aspose.diagram/diagramsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class DiagramSaveOptions extends SaveOptions
```

Kan användas för att ange ytterligare alternativ när ett diagram sparas i Visio (VDX\\VSX)-format. För närvarande tillhandahåller den endast egenskapen SaveFormat, men i framtiden kommer fler alternativ att läggas till.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DiagramSaveOptions()](#DiagramSaveOptions--) | Initierar en ny instans av denna klass som kan användas för att spara ett diagram i VDX-format. |
| [DiagramSaveOptions(int saveFormat)](#DiagramSaveOptions-int-) | Initierar en ny instans av den här klassen som kan användas för att spara ett diagram i VDX- eller VSX-formatet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Skapar ett sparaalternativobjekt av en klass som är lämplig för det angivna sparformatet. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoFitPageToDrawingContent()](#getAutoFitPageToDrawingContent--) | Definierar om sidan behöver förstoras för att passa ritningsinnehållet eller inte. |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | När tecken i diagrammet är Unicode och inte har ställts in med korrekt teckensnittsvärde eller teckensnittet inte är installerat lokalt, kan de visas som block i PDF, bild eller XPS. |
| [getSaveFormat()](#getSaveFormat--) | Anger det format i vilket det renderade diagrammet kommer att sparas om detta spara-alternativobjekt används. |
| [getWarningCallback()](#getWarningCallback--) | varnings‑återanrop. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoFitPageToDrawingContent(boolean value)](#setAutoFitPageToDrawingContent-boolean-) | För beskrivningen av den här egenskapen, se [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | För beskrivningen av denna egenskap, se [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | För beskrivningen av den här egenskapen, se [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DiagramSaveOptions() {#DiagramSaveOptions--}
```
public DiagramSaveOptions()
```


Initierar en ny instans av denna klass som kan användas för att spara ett diagram i VDX-format.

### DiagramSaveOptions(int saveFormat) {#DiagramSaveOptions-int-}
```
public DiagramSaveOptions(int saveFormat)
```


Initierar en ny instans av den här klassen som kan användas för att spara ett diagram i VDX- eller VSX-formatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| saveFormat | int |  |

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
### getAutoFitPageToDrawingContent() {#getAutoFitPageToDrawingContent--}
```
public boolean getAutoFitPageToDrawingContent()
```


Definierar om sidan behöver förstoras för att passa ritningsinnehållet eller inte. Standardvärdet är falskt.

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
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Anger det format i vilket det renderade diagrammet kommer att sparas om detta spara-alternativobjekt används. Kan vara Aspose.Diagram.SaveFileFormat eller Aspose.Diagram.SaveFileFormat.

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


För beskrivningen av den här egenskapen, se [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


För beskrivningen av denna egenskap, se [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


För beskrivningen av den här egenskapen, se [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--)

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

