---
title: RelEllipticalArcTo
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die Informationen über einen elliptischen Bogen angeben. Koordinaten werden als relative Koordinaten angegeben.
type: docs
weight: 318
url: /de/java/com.aspose.diagram/relellipticalarcto/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class RelEllipticalArcTo extends Coordinate
```

Enthält Elemente, die Informationen über einen elliptischen Bogen angeben. Koordinaten werden als relative Koordinaten angegeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RelEllipticalArcTo()](#RelEllipticalArcTo--) | Erstellt eine Instanz der Klasse [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | Die x‑Koordinate des Kontrollpunkts des Bogens. |
| [getB()](#getB--) | Die y‑Koordinate des Kontrollpunkts eines Bogens. |
| [getC()](#getC--) | Der Winkel der Hauptachse des Bogens relativ zur x‑Achse seines übergeordneten Elements. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | Das Verhältnis der Hauptachse des Bogens zur Nebenachse. |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getIX()](#getIX--) | Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements. |
| [getX()](#getX--) | Die x‑Koordinate des Endknotens eines elliptischen Bogens. |
| [getY()](#getY--) | Die y‑Koordinate des Endknotens eines elliptischen Bogens. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--) |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--) |
| [setIX(int value)](#setIX-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelEllipticalArcTo() {#RelEllipticalArcTo--}
```
public RelEllipticalArcTo()
```


Erstellt eine Instanz der Klasse [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto).

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
### getA() {#getA--}
```
public DoubleValue getA()
```


Der x‑Koordinate des Kontrollpunkts des Bogens. Der Kontrollpunkt ist am besten etwa halbwegs zwischen dem Anfangs‑ und Endpunkt des Bogens positioniert. Andernfalls kann der Bogen zu einer extremen Größe anwachsen, um durch den Kontrollpunkt zu verlaufen, mit unvorhersehbaren Ergebnissen.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


Die y‑Koordinate des Kontrollpunkts eines Bogens.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


Der Winkel der Hauptachse des Bogens relativ zur x‑Achse seines übergeordneten Elements.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


Das Verhältnis der Hauptachse eines Bogens zu seiner Nebenachse. Trotz der üblichen Bedeutung dieser Wörter muss die Hauptachse nicht größer sein als die Nebenachse, sodass dieses Verhältnis nicht größer als 1 sein muss. Das Setzen dieses Elements auf einen Wert kleiner oder gleich 0 oder größer als 1000 kann zu unvorhersehbaren Ergebnissen führen.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


Die x‑Koordinate des Endknotens eines elliptischen Bogens.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


Die y‑Koordinate des Endknotens eines elliptischen Bogens.

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--)

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

