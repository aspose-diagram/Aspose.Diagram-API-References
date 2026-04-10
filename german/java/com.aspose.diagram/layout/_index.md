---
title: Layout
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die die Platzierung von Formen und die Routing‑Einstellungen von Verbindern steuern.
type: docs
weight: 215
url: /de/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

Enthält Elemente, die die Platzierung von Formen und die Routing‑Einstellungen von Verbindern steuern.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | Bestimmt, wann ein Connector umgeleitet wird. |
| [getConLineJumpCode()](#getConLineJumpCode--) | Bestimmt, ob ein Verbinder springt, wenn zwei Verbinder sich kreuzen, |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | Bestimmt die Sprungrichtung für Linien, die auf einem horizontalen Segment eines dynamischen Connectors auftreten. |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | Bestimmt die Sprungrichtung für Linien, die auf einem vertikalen Segment eines dynamischen Connectors auftreten. |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | Bestimmt den Sprungstil für Linien auf einem dynamischen Connector. |
| [getConLineRouteExt()](#getConLineRouteExt--) | Bestimmt das Erscheinungsbild eines Connectors. |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getDisplayLevel()](#getDisplayLevel--) | Bestimmt das Anzeigeebenenband (den relativen Bereich der Z-Order-Gruppierung) für das Shape. |
| [getRelationships()](#getRelationships--) | Speichert die Beziehungen zwischen Containern, Listen, Callouts und Shapes. |
| [getShapeFixedCode()](#getShapeFixedCode--) | Gibt das Platzierungsverhalten für eine platzierbare Form an. |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | Gibt an, ob platzierbare Shapes über einem Shape platziert werden können, wenn ein Benutzer „Lay Out Shapes“ (Shapes‑Menü) auswählt. |
| [getShapePermeableX()](#getShapePermeableX--) | Gibt an, ob ein Verbinder horizontal durch ein Shape führen kann. |
| [getShapePermeableY()](#getShapePermeableY--) | Gibt an, ob ein Verbinder vertikal durch ein Shape führen kann. |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | Gibt an, wie eine platzierbare Form auf der Seite gedreht und/oder gespiegelt wird, wenn ein Benutzer Lay Out Shapes (Shapes‑Menü) auswählt. |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | Bestimmt den Platzierungsstil für untergeordnete Elemente. |
| [getShapePlowCode()](#getShapePlowCode--) | Gibt an, ob sich eine platzierbare Form entfernt, wenn Sie eine andere platzierbare Form in die Nähe der Form auf der Zeichenfläche ziehen. |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | Gibt den Routing‑Stil und die Richtung für einen Verbinder auf der Zeichenfläche an. |
| [getShapeSplit()](#getShapeSplit--) | Bestimmt, ob dieses Shape teilbare Shapes teilen kann. |
| [getShapeSplittable()](#getShapeSplittable--) | Bestimmt, ob dieses 1‑D‑Shape geteilt werden kann. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | Für die Beschreibung dieser Eigenschaft, bitte siehe [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


Bestimmt, wann ein Connector umgeleitet wird.

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


Bestimmt, ob ein Verbinder springt, wenn zwei Verbinder sich kreuzen,

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


Bestimmt die Sprungrichtung für Linien, die auf einem horizontalen Segment eines dynamischen Connectors auftreten.

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


Bestimmt die Sprungrichtung für Linien, die auf einem vertikalen Segment eines dynamischen Connectors auftreten.

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


Bestimmt den Sprungstil für Linien auf einem dynamischen Connector.

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


Bestimmt das Erscheinungsbild eines Connectors.

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


Bestimmt das Anzeigeebenenband (den relativen Bereich der Z-Order-Gruppierung) für das Shape.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


Speichert die Beziehungen zwischen Containern, Listen, Callouts und Shapes.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


Gibt das Platzierungsverhalten für eine platzierbare Form an.

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


Gibt an, ob platzierbare Shapes über einem Shape platziert werden können, wenn ein Benutzer „Lay Out Shapes“ (Shapes‑Menü) auswählt.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


Gibt an, ob ein Verbinder horizontal durch ein Shape führen kann.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


Gibt an, ob ein Verbinder vertikal durch ein Shape führen kann.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


Gibt an, wie eine platzierbare Form auf der Seite gedreht und/oder gespiegelt wird, wenn ein Benutzer Lay Out Shapes (Shapes‑Menü) auswählt.

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


Bestimmt den Platzierungsstil für untergeordnete Elemente.

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


Gibt an, ob sich eine platzierbare Form entfernt, wenn Sie eine andere platzierbare Form in die Nähe der Form auf der Zeichenfläche ziehen.

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


Gibt den Routing‑Stil und die Richtung für einen Verbinder auf der Zeichenfläche an.

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


Bestimmt, ob dieses Shape teilbare Shapes teilen kann.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


Bestimmt, ob dieses 1‑D‑Shape geteilt werden kann.

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


Für die Beschreibung dieser Eigenschaft, bitte siehe [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


Für die Beschreibung dieser Eigenschaft, bitte siehe [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle) |  |

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

