---
title: PageProps
second_title: Aspose.Diagram för Java API-referens
description: Innehåller celler som styr sidattribut såsom sidans bredd, höjd och skala.
type: docs
weight: 268
url: /sv/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

Innehåller celler som styr sidattribut, såsom sidbredd, höjd och skala.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getDrawingResizeType()](#getDrawingResizeType--) | Bestämmer om ritningssidan automatiskt ändrar storlek för att passa diagrammet. |
| [getDrawingScale()](#getDrawingScale--) | Representerar värdet för ritningsenheten i den aktuella ritningsskalan. |
| [getDrawingScaleType()](#getDrawingScaleType--) | Anger vilken typ av ritningsskala som ska användas för en sida. |
| [getDrawingSizeType()](#getDrawingSizeType--) | Anger ritningsstorleken för en sida. |
| [getInhibitSnap()](#getInhibitSnap--) | Anger om formerna på en förgrundssida fästs till andra objekt på sidan och former på bakgrundssidan. |
| [getPageHeight()](#getPageHeight--) | Anger sidans höjd i ritningsenheter. |
| [getPageScale()](#getPageScale--) | Anger värdet för standardsidans enhet i den aktuella ritningsskalan. |
| [getPageWidth()](#getPageWidth--) | Anger sidans bredd i ritningsenheter. |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | Innehåller ett tal som anger vinkeln för sned riktning när standard sidskuggtyp tillämpas. |
| [getShdwOffsetX()](#getShdwOffsetX--) | Anger avståndet i sid-enheter som en formes skugga förskjuts horisontellt från formen. |
| [getShdwOffsetY()](#getShdwOffsetY--) | Anger avståndet i sid-enheter som en formes skugga förskjuts vertikalt från formen. |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | Anger procentandelen för att förstora eller minska en formes skugga. |
| [getShdwType()](#getShdwType--) | Anger standardskuggtyp för en sida. |
| [getUIVisibility()](#getUIVisibility--) | Bestämmer om sidnamnet visas i användargränssnittet (UI). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/pageprops\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


Bestämmer om ritningssidan automatiskt ändrar storlek för att passa diagrammet.

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


Representerar värdet för ritningsenheten i den aktuella ritningsskalan. Ritningsskalan för sidan är förhållandet mellan sidans enhet som finns i PageScale‑elementet och ritningsenheten. Enheterna i detta element bestämmer standardlängden (DL) för sidan.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


Anger vilken typ av ritningsskala som ska användas för en sida.

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


Anger ritningsstorleken för en sida.

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


Anger om formerna på en förgrundssida fästs till andra objekt på sidan och former på bakgrundssidan.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


Anger sidans höjd i ritningsenheter.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


Anger värdet för standard sidans enhet i den aktuella ritningsskalan. Ritningsskalan för sidan är förhållandet mellan sidans enhet i PageScale‑elementet och ritningsenheten som visas i DrawingScale‑elementet.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


Anger sidans bredd i ritningsenheter.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


Innehåller ett tal som anger vinkeln för sned riktning när standard sidskuggtyp tillämpas.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


Anger avståndet i sid-enheter som en formes skugga förskjuts horisontellt från formen.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


Anger avståndet i sid-enheter som en formes skugga förskjuts vertikalt från formen.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


Anger procentandelen för att förstora eller minska en formes skugga.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


Anger standardskuggtyp för en sida.

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


Bestämmer om sidnamnet visas i användargränssnittet (UI). Ett värde på ett anger att sidan inte är synlig; ett värde på noll anger att sidan är synlig.

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/pageprops\#getDel--)

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

