---
title: TextXForm
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die Positionsinformationen zu einem Textblock einer Form angeben.
type: docs
weight: 405
url: /de/java/com.aspose.diagram/textxform/
---

**Inheritance:**
java.lang.Object
```
public class TextXForm
```

Enthält Elemente, die Positionsinformationen zum Textblock einer Form angeben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getTxtAngle()](#getTxtAngle--) | Gibt den aktuellen Rotationswinkel des Textblocks in Bezug auf die x-Achse der Form an. |
| [getTxtHeight()](#getTxtHeight--) | Gibt die Höhe des Textblocks an. |
| [getTxtLocPinX()](#getTxtLocPinX--) | Gibt die x-Koordinate des Rotationszentrums des Textblocks in Bezug auf den Ursprung des Textblocks an. |
| [getTxtLocPinY()](#getTxtLocPinY--) | Gibt die y-Koordinate des Rotationszentrums des Textblocks relativ zum Ursprung des Textblocks an. |
| [getTxtPinX()](#getTxtPinX--) | Gibt die x-Koordinate des Rotationszentrums des Textblocks in Bezug auf den Ursprung der Form an. |
| [getTxtPinY()](#getTxtPinY--) | Gibt die y-Koordinate des Rotationszentrums des Textblocks in Bezug auf den Ursprung der Form an. |
| [getTxtWidth()](#getTxtWidth--) | Gibt die Breite des Textblocks an. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/textxform\#getDel--) |
| [setTxtAngle(DoubleValue value)](#setTxtAngle-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtAngle()](../../com.aspose.diagram/textxform\#getTxtAngle--) |
| [setTxtHeight(DoubleValue value)](#setTxtHeight-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtHeight()](../../com.aspose.diagram/textxform\#getTxtHeight--) |
| [setTxtLocPinX(DoubleValue value)](#setTxtLocPinX-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtLocPinX()](../../com.aspose.diagram/textxform\#getTxtLocPinX--) |
| [setTxtLocPinY(DoubleValue value)](#setTxtLocPinY-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtLocPinY()](../../com.aspose.diagram/textxform\#getTxtLocPinY--) |
| [setTxtPinX(DoubleValue value)](#setTxtPinX-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtPinX()](../../com.aspose.diagram/textxform\#getTxtPinX--) |
| [setTxtPinY(DoubleValue value)](#setTxtPinY-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtPinY()](../../com.aspose.diagram/textxform\#getTxtPinY--) |
| [setTxtWidth(DoubleValue value)](#setTxtWidth-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtWidth()](../../com.aspose.diagram/textxform\#getTxtWidth--) |
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
### getTxtAngle() {#getTxtAngle--}
```
public DoubleValue getTxtAngle()
```


Gibt den aktuellen Rotationswinkel des Textblocks in Bezug auf die x-Achse der Form an. Der Standardwert ist 0 Grad.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtHeight() {#getTxtHeight--}
```
public DoubleValue getTxtHeight()
```


Gibt die Höhe des Textblocks an. Die Standardformel, die der Höhe der Form entspricht, ist F="Height\*1".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtLocPinX() {#getTxtLocPinX--}
```
public DoubleValue getTxtLocPinX()
```


Gibt die x-Koordinate des Rotationszentrums des Textblocks in Bezug auf den Ursprung des Textblocks an. Die Standardformel, die dem horizontalen Zentrum des Textblocks entspricht, ist F="TxtWidth\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtLocPinY() {#getTxtLocPinY--}
```
public DoubleValue getTxtLocPinY()
```


Gibt die y-Koordinate des Rotationszentrums des Textblocks relativ zum Ursprung des Textblocks an. Die Standardformel, die dem vertikalen Zentrum des Textblocks entspricht, ist F="TxtHeight\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtPinX() {#getTxtPinX--}
```
public DoubleValue getTxtPinX()
```


Gibt die x-Koordinate des Rotationszentrums des Textblocks in Bezug auf den Ursprung der Form an. Die Standardformel, die dem horizontalen Zentrum der Form entspricht, ist F="Width\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtPinY() {#getTxtPinY--}
```
public DoubleValue getTxtPinY()
```


Gibt die y-Koordinate des Rotationszentrums des Textblocks in Bezug auf den Ursprung der Form an. Die Standardformel, die dem vertikalen Zentrum der Form entspricht, ist F="Height\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtWidth() {#getTxtWidth--}
```
public DoubleValue getTxtWidth()
```


Gibt die Breite des Textblocks an. Die Standardformel, die der Breite der Form entspricht, ist F="Width\*1".

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/textxform\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTxtAngle(DoubleValue value) {#setTxtAngle-com.aspose.diagram.DoubleValue-}
```
public void setTxtAngle(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtAngle()](../../com.aspose.diagram/textxform\#getTxtAngle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtHeight(DoubleValue value) {#setTxtHeight-com.aspose.diagram.DoubleValue-}
```
public void setTxtHeight(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtHeight()](../../com.aspose.diagram/textxform\#getTxtHeight--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtLocPinX(DoubleValue value) {#setTxtLocPinX-com.aspose.diagram.DoubleValue-}
```
public void setTxtLocPinX(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtLocPinX()](../../com.aspose.diagram/textxform\#getTxtLocPinX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtLocPinY(DoubleValue value) {#setTxtLocPinY-com.aspose.diagram.DoubleValue-}
```
public void setTxtLocPinY(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtLocPinY()](../../com.aspose.diagram/textxform\#getTxtLocPinY--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtPinX(DoubleValue value) {#setTxtPinX-com.aspose.diagram.DoubleValue-}
```
public void setTxtPinX(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtPinX()](../../com.aspose.diagram/textxform\#getTxtPinX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtPinY(DoubleValue value) {#setTxtPinY-com.aspose.diagram.DoubleValue-}
```
public void setTxtPinY(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtPinY()](../../com.aspose.diagram/textxform\#getTxtPinY--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtWidth(DoubleValue value) {#setTxtWidth-com.aspose.diagram.DoubleValue-}
```
public void setTxtWidth(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTxtWidth()](../../com.aspose.diagram/textxform\#getTxtWidth--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

