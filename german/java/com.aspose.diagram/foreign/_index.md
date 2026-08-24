---
title: Fremd
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die die Breite und Höhe eines Objekts aus einem anderen Programm angeben, das in einem Microsoft Visio-Dokument verwendet wird.
type: docs
weight: 163
url: /de/java/com.aspose.diagram/foreign/
---

**Inheritance:**
java.lang.Object
```
public class Foreign
```

Enthält Elemente, die die Breite und Höhe eines aus einem anderen Programm stammenden Objekts in einem Microsoft Visio-Dokument angeben. Außerdem enthält es Elemente, die den Abstand angeben, um den das Bild des Objekts innerhalb seiner Ränder versetzt ist.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getImgHeight()](#getImgHeight--) | Bestimmt die Höhe des Bildes des Objekts innerhalb seiner Grenze. |
| [getImgOffsetX()](#getImgOffsetX--) | Bestimmt den horizontalen Abstand, um den das Objekt vom Ursprung seiner Grenze versetzt ist. |
| [getImgOffsetY()](#getImgOffsetY--) | Bestimmt den vertikalen Abstand, um den das Objekt vom Ursprung seiner Grenze versetzt ist. |
| [getImgWidth()](#getImgWidth--) | Bestimmt die Breite des Bildes des Objekts innerhalb seiner Grenze. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/foreign\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt eine tiefe Kopie dieser Instanz.

**Returns:**
java.lang.Object -
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


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getImgHeight() {#getImgHeight--}
```
public DoubleValue getImgHeight()
```


Bestimmt die Höhe des Bildes des Objekts innerhalb seiner Begrenzung. Die Standardformel lautet: F="Height\*1".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetX() {#getImgOffsetX--}
```
public DoubleValue getImgOffsetX()
```


Bestimmt den Abstand, um den das Objekt horizontal vom Ursprung seiner Begrenzung verschoben ist. Der Standardwert ist 0; die Standardformel lautet F="ImgWidth\*0".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetY() {#getImgOffsetY--}
```
public DoubleValue getImgOffsetY()
```


Bestimmt den Abstand, um den das Objekt vertikal vom Ursprung seiner Begrenzung verschoben ist. Der Standardwert ist 0; die Standardformel lautet F="ImgHeight\*0".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgWidth() {#getImgWidth--}
```
public DoubleValue getImgWidth()
```


Bestimmt die Breite des Bildes des Objekts innerhalb seiner Begrenzung. Die Standardformel lautet: F="Width\*1".

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/foreign\#getDel--)

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

