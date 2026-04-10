---
title: Layer
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element som definierar ett enskilt lager och dess egenskaper för en sida.
type: docs
weight: 212
url: /sv/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

Innehåller element som definierar ett enskilt lager och dess egenskaper för en sida.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Layer()](#Layer--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | Anger om ett lager är aktivt. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Indexet för färgen i färgtabellen som används för att visa lagret eller ett RGB‑värde som specificerar en anpassad färg som inte finns i färgtabellen (till exempel \#ff9900). |
| [getColorTrans()](#getColorTrans--) | Bestämmer graden av transparens för ett lager eller en figurs textfärg, från 0 (helt ogenomskinlig) till 1 (helt genomskinlig). |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getGlue()](#getGlue--) | Anger om former som tillhör lagret kan limmas på. |
| [getIX()](#getIX--) | Det nollbaserade indexet för elementet inom dess föräldraelement. |
| [getLock()](#getLock--) | Anger om former som tillhör lagret är låsta för att inte kunna väljas eller redigeras. |
| [getName()](#getName--) | Name-elementet specificerar namnet på ett lager. |
| [getNameUniv()](#getNameUniv--) | Anger det universella namnet på ett lager. |
| [getPrint()](#getPrint--) | Anger om former som tillhör lagret skrivs ut när ritningen skrivs ut. |
| [getSnap()](#getSnap--) | Anger om andra former kan fästa sig på former som tilldelats lagret. |
| [getStatus()](#getStatus--) | Anger om lagret är ett giltigt lager för ett dokument. |
| [getVisible()](#getVisible--) | Anger om former som tillhör lagret är synliga på ritningssidan. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | En flagga som indikerar om elementet har kontrollerats lokalt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | För beskrivningen av denna egenskap, se [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
```


Konstruktor.

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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


Anger om ett lager är aktivt. Former som inte är förhandsassignerade till lager tilldelas det aktiva lagret/lagren när de släpps på ritningssidan.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


Indexet för färgen i färgtabellen som används för att visa lagret eller ett RGB‑värde som specificerar en anpassad färg som inte finns i färgtabellen (till exempel \#ff9900).

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Bestämmer graden av transparens för ett lager eller en figurs textfärg, från 0 (helt ogenomskinlig) till 1 (helt genomskinlig).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


Anger om former som tillhör lagret kan limmas på.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


Det nollbaserade indexet för elementet inom dess föräldraelement.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


Anger om former som tillhör lagret är låsta för att inte kunna väljas eller redigeras.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


Name-elementet specificerar namnet på ett lager.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


Anger det universella namnet på ett lager.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


Anger om former som tillhör lagret skrivs ut när ritningen skrivs ut.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


Anger om andra former kan fästa sig på former som tilldelats lagret. Former som tilldelats lagret kan fästa sig på andra former, men andra former kan inte fästa sig på dem.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


Anger om lagret är ett giltigt lager för ett dokument.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


Anger om former som tillhör lagret är synliga på ritningssidan.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


En flagga som indikerar om elementet har kontrollerats lokalt. Värdet 1 indikerar att elementet kontrollerades lokalt.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


För beskrivningen av denna egenskap, se [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/layer\#getIX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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

