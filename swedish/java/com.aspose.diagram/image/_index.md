---
title: Bild
second_title: Aspose.Diagram för Java API-referens
description: Innehåller gamma, ljusstyrka, kontrast, oskärpa, skärpning, brusreducering och transparensvärden för en bitmap.
type: docs
weight: 196
url: /sv/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

Innehåller gamma-, ljus-, kontrast-, oskärpe-, skärpe-, brusreducerings- och transparensvärden för en bitmap.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | Gör en bitmap‑bild suddig eller mjukare. |
| [getBrightness()](#getBrightness--) | Justera ljusstyrkan för en bitmap‑bild. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Anger kontrasten för en bitmap‑bild. |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getDenoise()](#getDenoise--) | Tar bort brus (pixlar som har slumpmässigt fördelade färgnivåer) från en bitmap‑bild. |
| [getGamma()](#getGamma--) | Justera eller korrigera intensiteten för en bild för en viss utmatningsenhet, såsom en bildskärm eller skanner. |
| [getSharpen()](#getSharpen--) | Anger mängden skärpning för en bitmap‑bild. |
| [getTransparency()](#getTransparency--) | Anger transparensnivån för ett lagerfärg, från 0 (opak) till 1 (helt genomskinlig). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/image\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


Gör en bitmap‑bild suddig eller mjukare. Blur‑elementet innehåller ett värde mellan 0 och 1; standardvärdet är 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


Justera ljusstyrkan för en bitmap‑bild. Brightness‑elementet innehåller ett värde mellan 0 och 1; standardvärdet är 0.5.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public DoubleValue getContrast()
```


Anger kontrasten för en bitmap‑bild. Contrast‑elementet innehåller ett värde mellan 0 och 1.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


Tar bort brus (pixlar som har slumpmässigt fördelade färgnivåer) från en bitmap‑bild.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


Justera eller korrigera intensiteten för en bild för en viss utmatningsenhet, såsom en bildskärm eller skanner. Standardvärdet är 1 (ingen korrigering).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


Anger mängden skärpning för en bitmap‑bild. Skärpning av en bild fokuserar den genom att öka kontrasten mellan intilliggande pixlar.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


Anger transparensnivån för ett lagerfärg, från 0 (opak) till 1 (helt genomskinlig).

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


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/image\#getDel--)

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

