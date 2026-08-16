---
title: TextXForm
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen die positioneringsinformatie over een tekstblok van een vorm specificeren.
type: docs
weight: 405
url: /nl/java/com.aspose.diagram/textxform/
---

**Inheritance:**
java.lang.Object
```
public class TextXForm
```

Bevat elementen die positioneringsinformatie over het tekstblok van een vorm specificeren.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een diepe kopie van deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getTxtAngle()](#getTxtAngle--) | Specificeert de huidige rotatiehoek van het tekstblok ten opzichte van de x-as van de vorm. |
| [getTxtHeight()](#getTxtHeight--) | Specificeert de hoogte van het tekstblok. |
| [getTxtLocPinX()](#getTxtLocPinX--) | Specificeert de x-coördinaat van het rotatiecentrum van het tekstblok ten opzichte van de oorsprong van het tekstblok. |
| [getTxtLocPinY()](#getTxtLocPinY--) | Specificeert de y-coördinaat van het rotatiecentrum van het tekstblok ten opzichte van de oorsprong van het tekstblok. |
| [getTxtPinX()](#getTxtPinX--) | Specificeert de x-coördinaat van het rotatiecentrum van het tekstblok ten opzichte van de oorsprong van de vorm. |
| [getTxtPinY()](#getTxtPinY--) | Specificeert de y-coördinaat van het rotatiecentrum van het tekstblok ten opzichte van de oorsprong van de vorm. |
| [getTxtWidth()](#getTxtWidth--) | Specificeert de breedte van het tekstblok. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/textxform\#getDel--) |
| [setTxtAngle(DoubleValue value)](#setTxtAngle-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getTxtAngle()](../../com.aspose.diagram/textxform\#getTxtAngle--) |
| [setTxtHeight(DoubleValue value)](#setTxtHeight-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getTxtHeight()](../../com.aspose.diagram/textxform\#getTxtHeight--) |
| [setTxtLocPinX(DoubleValue value)](#setTxtLocPinX-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getTxtLocPinX()](../../com.aspose.diagram/textxform\#getTxtLocPinX--) |
| [setTxtLocPinY(DoubleValue value)](#setTxtLocPinY-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getTxtLocPinY()](../../com.aspose.diagram/textxform\#getTxtLocPinY--) |
| [setTxtPinX(DoubleValue value)](#setTxtPinX-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getTxtPinX()](../../com.aspose.diagram/textxform\#getTxtPinX--) |
| [setTxtPinY(DoubleValue value)](#setTxtPinY-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getTxtPinY()](../../com.aspose.diagram/textxform\#getTxtPinY--) |
| [setTxtWidth(DoubleValue value)](#setTxtWidth-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getTxtWidth()](../../com.aspose.diagram/textxform\#getTxtWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een diepe kopie van deze instantie.

**Returns:**
java.lang.Object -
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


Een vlag die aangeeft of het element lokaal is verwijderd. Een waarde van 1 geeft aan dat het element lokaal is verwijderd.

**Returns:**
int
### getTxtAngle() {#getTxtAngle--}
```
public DoubleValue getTxtAngle()
```


Specificeert de huidige rotatiehoek van het tekstblok ten opzichte van de x-as van de vorm. Standaard is 0 graden.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtHeight() {#getTxtHeight--}
```
public DoubleValue getTxtHeight()
```


Specificeert de hoogte van het tekstblok. De standaardformule, die de hoogte van de vorm oplevert, is F="Height\*1".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtLocPinX() {#getTxtLocPinX--}
```
public DoubleValue getTxtLocPinX()
```


Specificeert de x-coördinaat van het rotatiecentrum van het tekstblok ten opzichte van de oorsprong van het tekstblok. De standaardformule, die het horizontale midden van het tekstblok oplevert, is F="TxtWidth\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtLocPinY() {#getTxtLocPinY--}
```
public DoubleValue getTxtLocPinY()
```


Specificeert de y-coördinaat van het rotatiecentrum van het tekstblok ten opzichte van de oorsprong van het tekstblok. De standaardformule, die het verticale midden van het tekstblok oplevert, is F="TxtHeight\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtPinX() {#getTxtPinX--}
```
public DoubleValue getTxtPinX()
```


Specificeert de x-coördinaat van het rotatiecentrum van het tekstblok ten opzichte van de oorsprong van de vorm. De standaardformule, die het horizontale midden van de vorm oplevert, is F="Width\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtPinY() {#getTxtPinY--}
```
public DoubleValue getTxtPinY()
```


Specificeert de y-coördinaat van het rotatiecentrum van het tekstblok ten opzichte van de oorsprong van de vorm. De standaardformule, die het verticale midden van de vorm oplevert, is F="Height\*0.5".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtWidth() {#getTxtWidth--}
```
public DoubleValue getTxtWidth()
```


Specificeert de breedte van het tekstblok. De standaardformule, die de breedte van de vorm oplevert, is F="Width\*1".

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


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/textxform\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTxtAngle(DoubleValue value) {#setTxtAngle-com.aspose.diagram.DoubleValue-}
```
public void setTxtAngle(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getTxtAngle()](../../com.aspose.diagram/textxform\#getTxtAngle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtHeight(DoubleValue value) {#setTxtHeight-com.aspose.diagram.DoubleValue-}
```
public void setTxtHeight(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getTxtHeight()](../../com.aspose.diagram/textxform\#getTxtHeight--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtLocPinX(DoubleValue value) {#setTxtLocPinX-com.aspose.diagram.DoubleValue-}
```
public void setTxtLocPinX(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getTxtLocPinX()](../../com.aspose.diagram/textxform\#getTxtLocPinX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtLocPinY(DoubleValue value) {#setTxtLocPinY-com.aspose.diagram.DoubleValue-}
```
public void setTxtLocPinY(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getTxtLocPinY()](../../com.aspose.diagram/textxform\#getTxtLocPinY--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtPinX(DoubleValue value) {#setTxtPinX-com.aspose.diagram.DoubleValue-}
```
public void setTxtPinX(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getTxtPinX()](../../com.aspose.diagram/textxform\#getTxtPinX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtPinY(DoubleValue value) {#setTxtPinY-com.aspose.diagram.DoubleValue-}
```
public void setTxtPinY(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getTxtPinY()](../../com.aspose.diagram/textxform\#getTxtPinY--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtWidth(DoubleValue value) {#setTxtWidth-com.aspose.diagram.DoubleValue-}
```
public void setTxtWidth(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getTxtWidth()](../../com.aspose.diagram/textxform\#getTxtWidth--)

**Parameters:**
| Parameter | Type | Beschrijving |
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

