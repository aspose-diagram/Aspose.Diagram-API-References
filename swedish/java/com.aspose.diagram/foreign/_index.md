---
title: Främmande
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element som specificerar bredd och höjd på ett objekt från ett annat program som används i ett Microsoft Visio-dokument.
type: docs
weight: 163
url: /sv/java/com.aspose.diagram/foreign/
---

**Inheritance:**
java.lang.Object
```
public class Foreign
```

Innehåller element som specificerar bredd och höjd på ett objekt från ett annat program som används i ett Microsoft Visio-dokument. Inkluderar också element som specificerar avståndet som objektets bild förskjuts inom dess kanter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getImgHeight()](#getImgHeight--) | Bestämmer bildens höjd för objektet inom dess ram. |
| [getImgOffsetX()](#getImgOffsetX--) | Bestämmer avståndet objektet är förskjutet horisontellt från ursprunget för objektets ram. |
| [getImgOffsetY()](#getImgOffsetY--) | Bestämmer avståndet objektet är förskjutet vertikalt från ursprunget för objektets ram. |
| [getImgWidth()](#getImgWidth--) | Bestämmer bildens bredd för objektet inom dess ram. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av den här egenskapen, se [getDel()](../../com.aspose.diagram/foreign\\#getDel--) |
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
### getImgHeight() {#getImgHeight--}
```
public DoubleValue getImgHeight()
```


Bestämmer bildens höjd för objektet inom dess ram. Standardformeln är: F=\"Height\\*1\".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetX() {#getImgOffsetX--}
```
public DoubleValue getImgOffsetX()
```


Bestämmer avståndet som objektet förskjuts horisontellt från ursprunget för objektets ram. Standardvärdet är 0; standardformeln är F=\"ImgWidth\\*0\".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetY() {#getImgOffsetY--}
```
public DoubleValue getImgOffsetY()
```


Bestämmer avståndet som objektet förskjuts vertikalt från ursprunget för objektets ram. Standardvärdet är 0; standardformeln är F=\"ImgHeight\\*0\".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgWidth() {#getImgWidth--}
```
public DoubleValue getImgWidth()
```


Bestämmer bildens bredd för objektet inom dess ram. Standardformeln är: F=\"Width\\*1\".

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


För beskrivningen av den här egenskapen, se [getDel()](../../com.aspose.diagram/foreign\\#getDel--)

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

