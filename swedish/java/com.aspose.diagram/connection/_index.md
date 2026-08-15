---
title: Anslutning
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element för en anslutningspunkt som definierats för formen.
type: docs
weight: 78
url: /sv/java/com.aspose.diagram/connection/
---

**Inheritance:**
java.lang.Object
```
public class Connection
```

Innehåller element för en anslutningspunkt som definierats för formen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Connection()](#Connection--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoGen()](#getAutoGen--) | Anger om anslutningspunkten genereras automatiskt. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getDirX()](#getDirX--) | Anger x-komponenten för den erforderliga justeringsvektorn för en matchande anslutningspunkt. |
| [getDirY()](#getDirY--) | Anger y-komponenten för den erforderliga justeringsvektorn för en matchande anslutningspunkt. |
| [getID()](#getID--) | Det unika ID:t för elementet inom dess överordnade element. |
| [getIX()](#getIX--) | Det nollbaserade indexet för elementet inom dess föräldraelement. |
| [getName()](#getName--) | Elementets namn. |
| [getNameU()](#getNameU--) | Det universella namnet för elementet. |
| [getPrompt()](#getPrompt--) | Innehåller varierande promptinformation, baserat på elementet där den finns. |
| [getType()](#getType--) | Anger olika typer, baserat på elementet som den finns i. |
| [getX()](#getX--) | Anger en x‑koordinat på en form i lokala koordinater. |
| [getY()](#getY--) | Anger en y‑koordinat på en form i lokala koordinater. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/connection\#getDel--) |
| [setID(int value)](#setID-int-) | För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/connection\#getID--) |
| [setIX(int value)](#setIX-int-) | För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/connection\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/connection\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/connection\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Connection() {#Connection--}
```
public Connection()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en djup kopia av denna instans.

**Returns:**
java.lang.Object -
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
### getAutoGen() {#getAutoGen--}
```
public BoolValue getAutoGen()
```


Anger om anslutningspunkten genereras automatiskt. Ett värde på 1 indikerar att anslutningspunkten genereras automatiskt.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getDirX() {#getDirX--}
```
public DoubleValue getDirX()
```


Anger x-komponenten för den erforderliga justeringsvektorn för en matchande anslutningspunkt. DirX-elementet används också för att orientera den fästa benet på en dynamisk anslutning.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDirY() {#getDirY--}
```
public DoubleValue getDirY()
```


Anger y-komponenten för den erforderliga justeringsvektorn för en matchande anslutningspunkt. DirY-elementet används också för att orientera den fästa benet på en dynamisk anslutning.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getID() {#getID--}
```
public int getID()
```


Det unika ID:t för elementet inom dess överordnade element.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Det nollbaserade indexet för elementet inom dess föräldraelement.

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
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Innehåller varierande promptinformation, baserat på elementet där den finns.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeConnection getType()
```


Anger olika typer, baserat på elementet som den finns i.

**Returns:**
[TypeConnection](../../com.aspose.diagram/typeconnection)
### getX() {#getX--}
```
public DoubleValue getX()
```


Anger en x‑koordinat på en form i lokala koordinater.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


Anger en y-koordinat på en form i lokala koordinater. Lokala koordinater är de vars referensram är formen, istället för sidan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/connection\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/connection\#getID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/connection\#getIX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/connection\#getName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/connection\#getNameU--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

