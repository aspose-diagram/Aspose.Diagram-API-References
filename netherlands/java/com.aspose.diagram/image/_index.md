---
title: Afbeelding
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat de gamma, helderheid, contrast, vervaging, verscherping, ruisonderdrukking en transparantiewaarden voor een bitmap.
type: docs
weight: 196
url: /nl/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

Bevat de gamma-, helderheids-, contrast-, onscherpheids-, verscherpings-, ruisverwijderings- en transparantiewaarden voor een bitmap.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | Vervaagt of verzacht een bitmap-afbeelding. |
| [getBrightness()](#getBrightness--) | Past de helderheid van een bitmap-afbeelding aan. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | Specificeert het contrast van een bitmap-afbeelding. |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getDenoise()](#getDenoise--) | Verwijdert ruis (pixels met willekeurig verdeelde kleurniveaus) van een bitmap-afbeelding. |
| [getGamma()](#getGamma--) | Past de intensiteit van een afbeelding aan of corrigeert deze voor een specifiek uitvoerapparaat, zoals een monitor of scanner. |
| [getSharpen()](#getSharpen--) | Specificeert de mate van verscherping van een bitmap-afbeelding. |
| [getTransparency()](#getTransparency--) | Specificeert het transparantieniveau voor een laagkleur, van 0 (ondoorzichtig) tot 1 (volledig transparant). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/image\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


Vervaagt of verzacht een bitmap-afbeelding. Het Blur-element bevat een waarde tussen 0 en 1; de standaardwaarde is 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


Past de helderheid van een bitmap-afbeelding aan. Het Brightness-element bevat een waarde tussen 0 en 1; de standaardwaarde is 0.5.

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


Specificeert het contrast van een bitmap-afbeelding. Het Contrast-element bevat een waarde tussen 0 en 1.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Een vlag die aangeeft of het element lokaal is verwijderd. Een waarde van 1 geeft aan dat het element lokaal is verwijderd.

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


Verwijdert ruis (pixels met willekeurig verdeelde kleurniveaus) van een bitmap-afbeelding.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


Past de intensiteit van een afbeelding aan of corrigeert deze voor een specifiek uitvoerapparaat, zoals een monitor of scanner. De standaardwaarde is 1 (geen correctie.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


Specificeert de mate van verscherping van een bitmap-afbeelding. Het verscherpen van een afbeelding maakt deze scherper door het contrast van aangrenzende pixels te verhogen.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


Specificeert het transparantieniveau voor een laagkleur, van 0 (ondoorzichtig) tot 1 (volledig transparant).

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


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/image\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

