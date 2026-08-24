---
title: Geom
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die die Koordinaten der Scheitelpunkte für die Linien und Bögen angeben, aus denen die Form besteht.
type: docs
weight: 169
url: /de/java/com.aspose.diagram/geom/
---

**Inheritance:**
java.lang.Object
```
public class Geom
```

Enthält Elemente, die die Koordinaten der Scheitelpunkte für die Linien und Bögen, aus denen die Form besteht, angeben. Hat die Form mehr als einen Pfad, gibt es für jeden Pfad ein Geom-Element.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Geom()](#Geom--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateCol()](#getCoordinateCol--) | Sammlung von Koordinaten. |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getIX()](#getIX--) | Der nullbasierte Index des Elements innerhalb seines übergeordneten Elements. |
| [getNextCoordinateIX()](#getNextCoordinateIX--) | Gibt den IX-Wert für das nächste Koordinatensammlungsmitglied der Form zurück. |
| [getNoFill()](#getNoFill--) | Gibt an, ob ein Pfad gefüllt werden kann. |
| [getNoLine()](#getNoLine--) | Gibt an, ob eine Linie um die Begrenzung des Pfades gezeichnet wird. |
| [getNoQuickDrag()](#getNoQuickDrag--) | Bestimmt, ob eine Form ausgewählt oder gezogen werden kann, wenn der Benutzer den durch den Geometry-Abschnitt definierten gefüllten Bereich anklickt. |
| [getNoShow()](#getNoShow--) | Gibt an, ob ein Pfad auf der Zeichenfläche angezeigt wird. |
| [getNoSnap()](#getNoSnap--) | Gibt an, ob andere Formen an einem Pfad einrasten. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe [getDel()](../../com.aspose.diagram/geom\#getDel--) |
| [setIX(int value)](#setIX-int-) | Für die Beschreibung dieser Eigenschaft siehe [getIX()](../../com.aspose.diagram/geom\#getIX--) |
| [setNoFill(BoolValue value)](#setNoFill-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--) |
| [setNoLine(BoolValue value)](#setNoLine-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--) |
| [setNoQuickDrag(BoolValue value)](#setNoQuickDrag-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--) |
| [setNoShow(BoolValue value)](#setNoShow-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--) |
| [setNoSnap(BoolValue value)](#setNoSnap-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geom() {#Geom--}
```
public Geom()
```


Konstruktor.

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
### getCoordinateCol() {#getCoordinateCol--}
```
public CoordinateCollection getCoordinateCol()
```


Sammlung von Koordinaten. Sie zeigt die Reihenfolge der Koordinaten.

**Returns:**
[CoordinateCollection](../../com.aspose.diagram/coordinatecollection)
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
### getNextCoordinateIX() {#getNextCoordinateIX--}
```
public int getNextCoordinateIX()
```


Gibt den IX-Wert für das nächste Koordinatensammlungsmitglied der Form zurück.

**Returns:**
int
### getNoFill() {#getNoFill--}
```
public BoolValue getNoFill()
```


Gibt an, ob ein Pfad gefüllt werden kann.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLine() {#getNoLine--}
```
public BoolValue getNoLine()
```


Gibt an, ob eine Linie um die Begrenzung des Pfades gezeichnet wird.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoQuickDrag() {#getNoQuickDrag--}
```
public BoolValue getNoQuickDrag()
```


Bestimmt, ob eine Form ausgewählt oder gezogen werden kann, wenn der Benutzer den durch den Geometry-Abschnitt definierten gefüllten Bereich anklickt.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoShow() {#getNoShow--}
```
public BoolValue getNoShow()
```


Gibt an, ob ein Pfad auf der Zeichenfläche angezeigt wird.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoSnap() {#getNoSnap--}
```
public BoolValue getNoSnap()
```


Gibt an, ob andere Formen an einem Pfad einrasten.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Für die Beschreibung dieser Eigenschaft siehe [getDel()](../../com.aspose.diagram/geom\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Für die Beschreibung dieser Eigenschaft siehe [getIX()](../../com.aspose.diagram/geom\#getIX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setNoFill(BoolValue value) {#setNoFill-com.aspose.diagram.BoolValue-}
```
public void setNoFill(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoLine(BoolValue value) {#setNoLine-com.aspose.diagram.BoolValue-}
```
public void setNoLine(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoQuickDrag(BoolValue value) {#setNoQuickDrag-com.aspose.diagram.BoolValue-}
```
public void setNoQuickDrag(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoShow(BoolValue value) {#setNoShow-com.aspose.diagram.BoolValue-}
```
public void setNoShow(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoSnap(BoolValue value) {#setNoSnap-com.aspose.diagram.BoolValue-}
```
public void setNoSnap(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

