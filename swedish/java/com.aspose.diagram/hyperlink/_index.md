---
title: Hyperlänk
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element för att skapa flera hopp mellan en form eller ritningssida och en annan ritningssida, en annan fil eller en webbplats.
type: docs
weight: 193
url: /sv/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

Innehåller element för att skapa flera hopp mellan en form eller ritningssida och en annan ritningssida, en annan fil eller en webbplats.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | Anger en URL-adress, DOS-filnamn eller UNC-sökväg att hoppa till. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Anger standardhyperlänken för en form eller sida. |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getDescription()](#getDescription--) | Beskrivningselementet innehåller en textsträng som beskriver hyperlänken. |
| [getExtraInfo()](#getExtraInfo--) | Innehåller information som ska användas för att lösa en URL, såsom koordinaterna för en bildkarta. |
| [getFrame()](#getFrame--) | Innehåller namnet på en ram att rikta mot när Microsoft Visio är öppet som ett aktivt dokument i en behållarapplikation. |
| [getID()](#getID--) | Det unika ID:t för elementet inom dess överordnade element. |
| [getInvisible()](#getInvisible--) | Osynligt element indikerar om en hyperlänk visas i snabbmenyn för en form eller sida. |
| [getName()](#getName--) | Elementets namn. |
| [getNameU()](#getNameU--) | Det universella namnet för elementet. |
| [getNewWindow()](#getNewWindow--) | Anger om Microsoft Visio öppnar ett fönster på en ny plats när den följer en hyperlänk för att öppna en webbsida eller ett annat Visio-dokument. |
| [getSortKey()](#getSortKey--) | Osynligt element indikerar om en hyperlänk visas i snabbmenyn för en form eller sida. |
| [getSubAddress()](#getSubAddress--) | Anger en plats inom måldokumentet att länka till. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/hyperlink\#getDel--) |
| [setID(int value)](#setID-int-) | För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/hyperlink\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/hyperlink\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


Anger en URL-adress, DOS-filnamn eller UNC-sökväg att hoppa till.

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


Anger standardhyperlänken för en form eller sida.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


Beskrivningselementet innehåller en textsträng som beskriver hyperlänken.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


Innehåller information som ska användas för att lösa en URL, såsom koordinaterna för en bildkarta. Till exempel, x=41 y=7 skulle ange koordinaterna för en bildkarta.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


Innehåller namnet på en ram att rikta mot när Microsoft Visio är öppet som ett aktivt dokument i en behållarapplikation. Standardvärdet är en tom sträng.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


Det unika ID:t för elementet inom dess överordnade element.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Osynligt element indikerar om en hyperlänk visas i snabbmenyn för en form eller sida.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


Anger om Microsoft Visio öppnar ett fönster på en ny plats när den följer en hyperlänk för att öppna en webbsida eller ett annat Visio-dokument.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Osynligt element indikerar om en hyperlänk visas i snabbmenyn för en form eller sida.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


Anger en plats inom måldokumentet att länka till.

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


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/hyperlink\#getID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/hyperlink\#getName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)

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

