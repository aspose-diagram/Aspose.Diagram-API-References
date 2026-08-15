---
title: Master
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element som definierar en master för dokumentet.
type: docs
weight: 240
url: /sv/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

Innehåller element som definierar en master för dokumentet. En master är en form på en mall som du använder upprepade gånger för att skapa ritningar. När du drar en form från en mall till ritningssidan blir formen en instans av den mastern, och en lokal kopia av mastern inkluderas i dokumentet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Master()](#Master--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [dispose()](#dispose--) | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | Anger om masterns text i mallfönstret är vänsterjusterad, högerjusterad eller centrerad. |
| [getBaseID()](#getBaseID--) | En GUID (globalt unik identifierare) som identifierar mastern över dokument. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Innehåller ett Connect-element för varje anslutning mellan två former i en ritning. |
| [getHidden()](#getHidden--) | Anger om mastern är dold i användargränssnittet. |
| [getID()](#getID--) | Det unika ID:t för elementet inom dess överordnade element. |
| [getIcon()](#getIcon--) | Anger en MIME (Multipurpose Internet Mail Extensions) kodad binär ikon (i .ico-format) för ett Master- eller MasterShortcut-element i ett dokument. |
| [getIconSize()](#getIconSize--) | Storleken på elementets ikon. |
| [getIconUpdate()](#getIconUpdate--) | Anger om ikonen genereras automatiskt från mastern själv. |
| [getMatchByName()](#getMatchByName--) | MatchByName-attributet bestämmer hur Microsoft Visio avgör om ett dokumentmaster redan finns när en instans av en master släpps på ritningssidan. |
| [getName()](#getName--) | Elementets namn. |
| [getNameU()](#getNameU--) | Det universella namnet för elementet. |
| [getPageSheet()](#getPageSheet--) | Innehåller element som definierar sidbladet för ett Page- eller Master-element. |
| [getPatternFlags()](#getPatternFlags--) | PatternFlags-attributet bestämmer om en master beter sig som ett anpassat mönster. |
| [getPrompt()](#getPrompt--) | Statusfältet och verktygstipset visar en uppmaning för elementet. |
| [getShapes()](#getShapes--) | Samling av Shape-objekt. |
| [getUniqueID()](#getUniqueID--) | En GUID som identifierar mastern i dokumentet. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | För beskrivningen av denna egenskap, se [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | För beskrivningen av denna egenskap, se [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | För beskrivningen av denna egenskap, se [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | För beskrivningen av denna egenskap, se [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | För beskrivningen av denna egenskap, se [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | För beskrivningen av denna egenskap, se [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | För beskrivningen av denna egenskap, se [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | För beskrivningen av denna egenskap, se [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | För beskrivningen av denna egenskap, se [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | För beskrivningen av denna egenskap, se [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en djup kopia av denna instans.

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


Anger om masterns text i mallfönstret är vänsterjusterad, högerjusterad eller centrerad.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


En GUID (globalt unik identifierare) som identifierar mastern över dokument.

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


Innehåller ett Connect-element för varje anslutning mellan två former i en ritning.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


Anger om mastern är dold i användargränssnittet.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Det unika ID:t för elementet inom dess överordnade element.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


Anger en MIME (Multipurpose Internet Mail Extensions) kodad binär ikon (i .ico-format) för ett Master- eller MasterShortcut-element i ett dokument.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


Storleken på elementets ikon.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


Anger om ikonen genereras automatiskt från mastern själv.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


MatchByName-attributet bestämmer hur Microsoft Visio avgör om ett dokumentmaster redan finns när en instans av en master släpps på ritningssidan. Det gör att ändringar som görs i ett dokumentmaster tillämpas på nya instanser av mastern, även om instanserna dras från en fristående stencilfil.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Elementets namn.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Det universella namnet för elementet.

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Innehåller element som definierar sidbladet för ett Page- eller Master-element.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


PatternFlags-attributet bestämmer om en master beter sig som ett anpassat mönster.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


Statusfältet och verktygstipset visar en uppmaning för elementet.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Samling av Shape-objekt.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


En GUID som identifierar mastern i dokumentet.

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


För beskrivningen av denna egenskap, se [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


För beskrivningen av denna egenskap, se [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


För beskrivningen av denna egenskap, se [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


För beskrivningen av denna egenskap, se [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


För beskrivningen av denna egenskap, se [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


För beskrivningen av denna egenskap, se [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


För beskrivningen av denna egenskap, se [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


För beskrivningen av denna egenskap, se [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


För beskrivningen av denna egenskap, se [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


För beskrivningen av denna egenskap, se [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID |  |

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

