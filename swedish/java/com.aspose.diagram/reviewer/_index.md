---
title: Granskare
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element som innehåller identifierande information om en dokumentgranskare.
type: docs
weight: 330
url: /sv/java/com.aspose.diagram/reviewer/
---

**Inheritance:**
java.lang.Object
```
public class Reviewer
```

Innehåller element som innehåller identifierande information om en dokumentgranskare.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Reviewer()](#Reviewer--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Färgelementet anger ett RGB‑värde som representerar färgen som tilldelas en dokumentgranskares markering. |
| [getCurrentIndex()](#getCurrentIndex--) | Anger värdet för MarkerIndex‑elementet som kommer att läggas till när den aktuella granskaren lägger till en annan kommentar i dokumentet. |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getIX()](#getIX--) | Det nollbaserade indexet för elementet inom dess föräldraelement. |
| [getInitials()](#getInitials--) | Innehåller initialerna för en dokumentgranskare. |
| [getName()](#getName--) | Name‑elementet anger namnet på en dokumentgranskare. |
| [getReviewerID()](#getReviewerID--) | Innehåller ID‑numret för granskaren som lägger till markup i dokumentet. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/reviewer\#getDel--) |
| [setIX(int value)](#setIX-int-) | För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/reviewer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Reviewer() {#Reviewer--}
```
public Reviewer()
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


Färgelementet anger ett RGB‑värde som representerar färgen som tilldelas en dokumentgranskares markering.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getCurrentIndex() {#getCurrentIndex--}
```
public IntValue getCurrentIndex()
```


Anger värdet för MarkerIndex‑elementet som kommer att läggas till när den aktuella granskaren lägger till en annan kommentar i dokumentet.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Det nollbaserade indexet för elementet inom dess föräldraelement.

**Returns:**
int
### getInitials() {#getInitials--}
```
public Str2Value getInitials()
```


Innehåller initialerna för en dokumentgranskare.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getName() {#getName--}
```
public Str2Value getName()
```


Name‑elementet anger namnet på en dokumentgranskare.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getReviewerID() {#getReviewerID--}
```
public IntValue getReviewerID()
```


Innehåller ID‑numret för granskaren som lägger till markup i dokumentet.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/reviewer\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/reviewer\#getIX--)

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

