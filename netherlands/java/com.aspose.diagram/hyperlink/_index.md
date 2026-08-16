---
title: Hyperlink
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen voor het maken van meerdere sprongen tussen een vorm of tekentabel en een andere tekentabel, een ander bestand of een website.
type: docs
weight: 193
url: /nl/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

Bevat elementen voor het maken van meerdere sprongen tussen een vorm of tekentabel en een andere tekentabel, een ander bestand of een website.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | Constructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een diepe kopie van deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | Specificeert een URL-adres, DOS-bestandsnaam of UNC-pad om naartoe te springen. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Specificeert de standaardhyperlink voor een vorm of pagina. |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getDescription()](#getDescription--) | Beschrijvingselement bevat een tekenreeks die de hyperlink beschrijft. |
| [getExtraInfo()](#getExtraInfo--) | Bevat informatie die gebruikt wordt bij het oplossen van een URL, zoals de coördinaten van een afbeeldingsmap. |
| [getFrame()](#getFrame--) | Bevat de naam van een frame om te targeten wanneer Microsoft Visio geopend is als een actief document in een containerapplicatie. |
| [getID()](#getID--) | De unieke ID van het element binnen het bovenliggende element. |
| [getInvisible()](#getInvisible--) | Onzichtbaar element geeft aan of een hyperlink verschijnt in het snelmenu voor een vorm of pagina. |
| [getName()](#getName--) | De naam van het element. |
| [getNameU()](#getNameU--) | De universele naam van het element. |
| [getNewWindow()](#getNewWindow--) | Specificeert of Microsoft Visio een venster op een nieuwe locatie opent wanneer het een hyperlink volgt om een webpagina of een ander Visio‑document te openen. |
| [getSortKey()](#getSortKey--) | Onzichtbaar element geeft aan of een hyperlink verschijnt in het snelmenu voor een vorm of pagina. |
| [getSubAddress()](#getSubAddress--) | Specificeert een locatie binnen het doeldocument waarnaar gelinkt wordt. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/hyperlink\#getDel--) |
| [setID(int value)](#setID-int-) | Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/hyperlink\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/hyperlink\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
```


Constructor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een diepe kopie van deze instantie.

**Returns:**
java.lang.Object -
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


Specificeert een URL-adres, DOS-bestandsnaam of UNC-pad om naartoe te springen.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public BoolValue getDefault()
```


Specificeert de standaardhyperlink voor een vorm of pagina.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Een vlag die aangeeft of het element lokaal is verwijderd. Een waarde van 1 geeft aan dat het element lokaal is verwijderd.

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


Beschrijvingselement bevat een tekenreeks die de hyperlink beschrijft.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


Bevat informatie die gebruikt wordt bij het oplossen van een URL, zoals de coördinaten van een afbeeldingsmap. Bijvoorbeeld, x=41 y=7 zou de coördinaten van een afbeeldingsmap specificeren.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


Bevat de naam van een frame om te targeten wanneer Microsoft Visio geopend is als een actief document in een containerapplicatie. Standaard is een lege tekenreeks.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


De unieke ID van het element binnen het bovenliggende element.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Onzichtbaar element geeft aan of een hyperlink verschijnt in het snelmenu voor een vorm of pagina.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public String getName()
```


De naam van het element.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


De universele naam van het element.

**Returns:**
java.lang.String
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


Specificeert of Microsoft Visio een venster op een nieuwe locatie opent wanneer het een hyperlink volgt om een webpagina of een ander Visio‑document te openen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Onzichtbaar element geeft aan of een hyperlink verschijnt in het snelmenu voor een vorm of pagina.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


Specificeert een locatie binnen het doeldocument waarnaar gelinkt wordt.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/hyperlink\#getID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/hyperlink\#getName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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

