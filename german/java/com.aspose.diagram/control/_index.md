---
title: Steuerung
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente für die x- und y-Koordinaten jedes für eine Form definierten Steuerungspunkts sowie Elemente, die die Art und Weise festlegen, wie sich der Steuerungspunkt verhalten soll.
type: docs
weight: 87
url: /de/java/com.aspose.diagram/control/
---

**Inheritance:**
java.lang.Object
```
public class Control
```

Enthält Elemente für die x‑ und y‑Koordinaten jedes für eine Form definierten Steuergriffs sowie Elemente, die angeben, wie sich der Steuergriff verhalten soll.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Control()](#Control--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canGlue()](#canGlue--) | Bestimmt, ob ein Steuerungspunkt an andere Formen angeheftet werden kann. |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getID()](#getID--) | Die eindeutige ID des Elements innerhalb seines übergeordneten Elements. |
| [getIX()](#getIX--) | Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements. |
| [getName()](#getName--) | Der Name des Elements. |
| [getNameU()](#getNameU--) | Der universelle Name des Elements. |
| [getPrompt()](#getPrompt--) | Das Prompt-Element gibt den beschreibenden Text an, der als Tooltip angezeigt wird, wenn der Mauszeiger über dem Steuerungspunkt einer Form verweilt. |
| [getX()](#getX--) | Die x-Koordinate, die den Ort des Steuerungspunkts einer Form angibt. |
| [getXCon()](#getXCon--) | Gibt den Verhaltenstyp an, den die x-Koordinate des Steuerungspunkts nach dem Verschieben des Punktes zeigt. |
| [getXDyn()](#getXDyn--) | Gibt die x-Koordinate des Ankerpunkts eines Steuerungspunkts in lokalen Koordinaten an. |
| [getY()](#getY--) | Die y-Koordinate, die den Ort des Steuerungspunkts einer Form angibt. |
| [getYCon()](#getYCon--) | Gibt den Verhaltenstyp an, den die x-Koordinate des Steuerungspunkts nach dem Verschieben des Punktes zeigt. |
| [getYDyn()](#getYDyn--) | Gibt die y-Koordinate des Ankerpunkts eines Steuerungspunkts in lokalen Koordinaten an. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCanGlue(BoolValue value)](#setCanGlue-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [canGlue()](../../com.aspose.diagram/control\#canGlue--) |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/control\#getDel--) |
| [setID(int value)](#setID-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/control\#getID--) |
| [setIX(int value)](#setIX-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/control\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/control\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/control\#getNameU--) |
| [setPrompt(Str2Value value)](#setPrompt-com.aspose.diagram.Str2Value-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPrompt()](../../com.aspose.diagram/control\#getPrompt--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getX()](../../com.aspose.diagram/control\#getX--) |
| [setXCon(ConType value)](#setXCon-com.aspose.diagram.ConType-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getXCon()](../../com.aspose.diagram/control\#getXCon--) |
| [setXDyn(DoubleValue value)](#setXDyn-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getXDyn()](../../com.aspose.diagram/control\#getXDyn--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getY()](../../com.aspose.diagram/control\#getY--) |
| [setYCon(ConType value)](#setYCon-com.aspose.diagram.ConType-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getYCon()](../../com.aspose.diagram/control\#getYCon--) |
| [setYDyn(DoubleValue value)](#setYDyn-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getYDyn()](../../com.aspose.diagram/control\#getYDyn--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Control() {#Control--}
```
public Control()
```


Konstruktor.

### canGlue() {#canGlue--}
```
public BoolValue canGlue()
```


Bestimmt, ob ein Steuerungspunkt an andere Formen angeheftet werden kann.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getID() {#getID--}
```
public int getID()
```


Die eindeutige ID des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Der Name des Elements.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Der universelle Name des Elements.

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Das Prompt-Element gibt den beschreibenden Text an, der als Tooltip angezeigt wird, wenn der Mauszeiger über dem Steuerungspunkt einer Form verweilt.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getX() {#getX--}
```
public DoubleValue getX()
```


Die x-Koordinate, die den Ort des Steuerungspunkts einer Form angibt.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getXCon() {#getXCon--}
```
public ConType getXCon()
```


Gibt den Verhaltenstyp an, den die x-Koordinate des Steuerungspunkts nach dem Verschieben des Punktes zeigt.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getXDyn() {#getXDyn--}
```
public DoubleValue getXDyn()
```


Gibt die x‑Koordinate des Ankerpunkts eines Steuerungshandgriffs in lokalen Koordinaten an. Der Ankerpunkt wird für das Rubber‑Banding während der Dynamik verwendet.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


Die y-Koordinate, die den Ort des Steuerungspunkts einer Form angibt.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getYCon() {#getYCon--}
```
public ConType getYCon()
```


Gibt den Verhaltenstyp an, den die x-Koordinate des Steuerungspunkts nach dem Verschieben des Punktes zeigt.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getYDyn() {#getYDyn--}
```
public DoubleValue getYDyn()
```


Gibt die y‑Koordinate des Ankerpunkts eines Steuerungshandgriffs in lokalen Koordinaten an. Der Ankerpunkt wird für das Rubber‑Banding während der Dynamik verwendet.

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




### setCanGlue(BoolValue value) {#setCanGlue-com.aspose.diagram.BoolValue-}
```
public void setCanGlue(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [canGlue()](../../com.aspose.diagram/control\#canGlue--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/control\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/control\#getID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/control\#getIX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/control\#getName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/control\#getNameU--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPrompt(Str2Value value) {#setPrompt-com.aspose.diagram.Str2Value-}
```
public void setPrompt(Str2Value value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPrompt()](../../com.aspose.diagram/control\#getPrompt--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getX()](../../com.aspose.diagram/control\#getX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setXCon(ConType value) {#setXCon-com.aspose.diagram.ConType-}
```
public void setXCon(ConType value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getXCon()](../../com.aspose.diagram/control\#getXCon--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setXDyn(DoubleValue value) {#setXDyn-com.aspose.diagram.DoubleValue-}
```
public void setXDyn(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getXDyn()](../../com.aspose.diagram/control\#getXDyn--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getY()](../../com.aspose.diagram/control\#getY--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setYCon(ConType value) {#setYCon-com.aspose.diagram.ConType-}
```
public void setYCon(ConType value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getYCon()](../../com.aspose.diagram/control\#getYCon--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setYDyn(DoubleValue value) {#setYDyn-com.aspose.diagram.DoubleValue-}
```
public void setYDyn(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getYDyn()](../../com.aspose.diagram/control\#getYDyn--)

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

