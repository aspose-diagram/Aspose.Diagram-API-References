---
title: Bild
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält die Gamma-, Helligkeits-, Kontrast-, Weichzeichnungs-, Schärfungs-, Rauschunterdrückungs- und Transparenzwerte für ein Bitmap.
type: docs
weight: 196
url: /de/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

Enthält die Gamma-, Helligkeits-, Kontrast-, Unschärfe-, Schärfungs-, Rauschunterdrückungs- und Transparenzwerte für ein Bitmap.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | Weichzeichnet oder glättet ein Bitmap-Bild. |
| [getBrightness()](#getBrightness--) | Passt die Helligkeit eines Bitmap-Bildes an. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Gibt den Kontrast eines Bitmap-Bildes an. |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getDenoise()](#getDenoise--) | Entfernt Rauschen (Pixel, die zufällig verteilte Farbwerte haben) aus einem Bitmap-Bild. |
| [getGamma()](#getGamma--) | Passt die Intensität eines Bildes für ein bestimmtes Ausgabegerät an oder korrigiert sie, z. B. einen Monitor oder Scanner. |
| [getSharpen()](#getSharpen--) | Gibt den Betrag an, um ein Bitmap-Bild zu schärfen. |
| [getTransparency()](#getTransparency--) | Gibt den Transparenzgrad für eine Ebenenfarbe an, von 0 (undurchsichtig) bis 1 (vollständig transparent). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/image\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


Weichzeichnet oder glättet ein Bitmap-Bild. Das Blur-Element enthält einen Wert zwischen 0 und 1; der Standardwert ist 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


Passt die Helligkeit eines Bitmap-Bildes an. Das Brightness-Element enthält einen Wert zwischen 0 und 1; der Standardwert ist 0,5.

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


Gibt den Kontrast eines Bitmap-Bildes an. Das Contrast-Element enthält einen Wert zwischen 0 und 1.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


Entfernt Rauschen (Pixel, die zufällig verteilte Farbwerte haben) aus einem Bitmap-Bild.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


Passt die Intensität eines Bildes für ein bestimmtes Ausgabegerät an oder korrigiert sie, z. B. einen Monitor oder Scanner. Der Standardwert ist 1 (keine Korrektur).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


Gibt den Betrag an, um ein Bitmap-Bild zu schärfen. Das Schärfen eines Bildes fokussiert es, indem der Kontrast benachbarter Pixel erhöht wird.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


Gibt den Transparenzgrad für eine Ebenenfarbe an, von 0 (undurchsichtig) bis 1 (vollständig transparent).

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/image\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

