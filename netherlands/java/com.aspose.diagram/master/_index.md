---
title: Master
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen die een master voor het document definiëren.
type: docs
weight: 240
url: /nl/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

Bevat elementen die een master voor het document definiëren. Een master is een vorm op een sjabloon die je herhaaldelijk gebruikt om tekeningen te maken. Wanneer je een vorm van een sjabloon naar de tekenpagina sleept, wordt de vorm een instantie van die master, en wordt een lokale kopie van de master in het document opgenomen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Master()](#Master--) | Constructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een diepe kopie van deze instantie. |
| [dispose()](#dispose--) | Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | Specificeert of de tekst van de master in het sjabloonvenster links, rechts of gecentreerd is uitgelijnd. |
| [getBaseID()](#getBaseID--) | Een GUID (globaal unieke identifier) die de master over documenten heen identificeert. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Bevat een Connect-element voor elke verbinding tussen twee vormen in een tekening. |
| [getHidden()](#getHidden--) | Specificeert of de master verborgen is in de gebruikersinterface. |
| [getID()](#getID--) | De unieke ID van het element binnen het bovenliggende element. |
| [getIcon()](#getIcon--) | Specificeert een MIME (Multipurpose Internet Mail Extensions) gecodeerd binair pictogram (in .ico-formaat) voor een Master- of MasterShortcut-element in een document. |
| [getIconSize()](#getIconSize--) | De grootte van het pictogram van het element. |
| [getIconUpdate()](#getIconUpdate--) | Specificeert of het pictogram automatisch wordt gegenereerd vanuit de master zelf. |
| [getMatchByName()](#getMatchByName--) | Het MatchByName-attribuut bepaalt hoe Microsoft Visio beslist of een documentmaster al aanwezig is wanneer een instantie van een master op de tekenpagina wordt geplaatst. |
| [getName()](#getName--) | De naam van het element. |
| [getNameU()](#getNameU--) | De universele naam van het element. |
| [getPageSheet()](#getPageSheet--) | Bevat elementen die het paginablad definiëren voor een Pagina- of Master-element. |
| [getPatternFlags()](#getPatternFlags--) | Het PatternFlags-attribuut bepaalt of een master zich gedraagt als een aangepast patroon. |
| [getPrompt()](#getPrompt--) | De statusbalk en tooltip-prompt voor het element. |
| [getShapes()](#getShapes--) | Collectie van Shape-objecten. |
| [getUniqueID()](#getUniqueID--) | Een GUID die de master binnen het document identificeert. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | Voor de beschrijving van deze eigenschap, zie [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | Voor de beschrijving van deze eigenschap, zie [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | Voor de beschrijving van deze eigenschap, zie [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | Voor de beschrijving van deze eigenschap, zie [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | Voor de beschrijving van deze eigenschap, zie [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | Voor de beschrijving van deze eigenschap, zie [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | Voor de beschrijving van deze eigenschap, zie [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | Voor de beschrijving van deze eigenschap, zie [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Voor de beschrijving van deze eigenschap, zie [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


Constructor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een diepe kopie van deze instantie.

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


Specificeert of de tekst van de master in het sjabloonvenster links, rechts of gecentreerd is uitgelijnd.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


Een GUID (globaal unieke identifier) die de master over documenten heen identificeert.

**Returns:**
java.util.UUID
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


Bevat een Connect-element voor elke verbinding tussen twee vormen in een tekening.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


Specificeert of de master verborgen is in de gebruikersinterface.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


De unieke ID van het element binnen het bovenliggende element.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


Specificeert een MIME (Multipurpose Internet Mail Extensions) gecodeerd binair pictogram (in .ico-formaat) voor een Master- of MasterShortcut-element in een document.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


De grootte van het pictogram van het element.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


Specificeert of het pictogram automatisch wordt gegenereerd vanuit de master zelf.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


Het MatchByName-attribuut bepaalt hoe Microsoft Visio beslist of een document‑master al aanwezig is wanneer een instantie van een master op de tekenpagina wordt geplaatst. Het zorgt ervoor dat wijzigingen die in een document‑master worden aangebracht, worden toegepast op nieuwe instanties van de master, zelfs als de instanties worden versleept vanuit een losstaand stencil‑bestand.

**Returns:**
int
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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Bevat elementen die het paginablad definiëren voor een Pagina- of Master-element.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


Het PatternFlags-attribuut bepaalt of een master zich gedraagt als een aangepast patroon.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


De statusbalk en tooltip-prompt voor het element.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Collectie van Shape-objecten.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Een GUID die de master binnen het document identificeert.

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


Voor de beschrijving van deze eigenschap, zie [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


Voor de beschrijving van deze eigenschap, zie [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


Voor de beschrijving van deze eigenschap, zie [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


Voor de beschrijving van deze eigenschap, zie [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


Voor de beschrijving van deze eigenschap, zie [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


Voor de beschrijving van deze eigenschap, zie [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


Voor de beschrijving van deze eigenschap, zie [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


Voor de beschrijving van deze eigenschap, zie [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


Voor de beschrijving van deze eigenschap, zie [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Voor de beschrijving van deze eigenschap, zie [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.UUID |  |

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

