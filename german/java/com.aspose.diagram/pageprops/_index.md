---
title: PageProps
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Zellen, die Seitenattribute wie Seitenbreite, -höhe und Maßstab steuern.
type: docs
weight: 268
url: /de/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

Enthält Zellen, die Seitenattribute steuern, wie Seitenbreite, -höhe und Maßstab.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getDrawingResizeType()](#getDrawingResizeType--) | Bestimmt, ob die Zeichenfläche automatisch an das Diagramm angepasst wird. |
| [getDrawingScale()](#getDrawingScale--) | Stellt den Wert der Zeicheneinheit im aktuellen Zeichnungsmaßstab dar. |
| [getDrawingScaleType()](#getDrawingScaleType--) | Gibt den Typ der Zeichenmaßstabes an, der für eine Seite verwendet werden soll. |
| [getDrawingSizeType()](#getDrawingSizeType--) | Gibt die Zeichenflächegröße einer Seite an. |
| [getInhibitSnap()](#getInhibitSnap--) | Gibt an, ob die Formen auf einer Vordergrundseite an anderen Objekten auf der Seite und an Formen auf der Hintergrundseite einrasten. |
| [getPageHeight()](#getPageHeight--) | Gibt die Höhe der Seite in Zeicheneinheiten an. |
| [getPageScale()](#getPageScale--) | Gibt den Wert der Standardseiteneinheit im aktuellen Zeichnungsmaßstab an. |
| [getPageWidth()](#getPageWidth--) | Gibt die Breite der Seite in Zeicheneinheiten an. |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | Enthält eine Zahl, die den Winkel der schrägen Richtung angibt, wenn der Standard-Seiten-Schatten-Typ angewendet wird. |
| [getShdwOffsetX()](#getShdwOffsetX--) | Gibt den Abstand in Seiteneinheiten an, um den der Abwurfschatten einer Form horizontal von der Form versetzt ist. |
| [getShdwOffsetY()](#getShdwOffsetY--) | Gibt den Abstand in Seiteneinheiten an, um den der Abwurfschatten einer Form vertikal von der Form versetzt ist. |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | Gibt den Prozentsatz an, um den ein Formschatten vergrößert oder verkleinert wird. |
| [getShdwType()](#getShdwType--) | Zeigt den Standard‑Schattentyp für eine Seite an. |
| [getUIVisibility()](#getUIVisibility--) | Bestimmt, ob der Seitenname in der Benutzeroberfläche (UI) angezeigt wird. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/pageprops\\#getDel--) |
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
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


Bestimmt, ob die Zeichenfläche automatisch an das Diagramm angepasst wird.

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


Stellt den Wert der Zeicheneinheit im aktuellen Zeichnungsmaßstab dar. Der Zeichnungsmaßstab für die Seite ist das Verhältnis der im PageScale-Element enthaltenen Seiteneinheit zur Zeicheneinheit. Die Einheiten dieses Elements bestimmen die Standard-Längeneinheiten (DL) für die Seite.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


Gibt den Typ der Zeichenmaßstabes an, der für eine Seite verwendet werden soll.

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


Gibt die Zeichenflächegröße einer Seite an.

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


Gibt an, ob die Formen auf einer Vordergrundseite an anderen Objekten auf der Seite und an Formen auf der Hintergrundseite einrasten.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


Gibt die Höhe der Seite in Zeicheneinheiten an.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


Gibt den Wert der Standard-Seiteneinheit im aktuellen Zeichnungsmaßstab an. Der Zeichnungsmaßstab für die Seite ist das Verhältnis der Seiteneinheit im PageScale-Element zur im DrawingScale-Element dargestellten Zeicheneinheit.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


Gibt die Breite der Seite in Zeicheneinheiten an.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


Enthält eine Zahl, die den Winkel der schrägen Richtung angibt, wenn der Standard-Seiten-Schatten-Typ angewendet wird.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


Gibt den Abstand in Seiteneinheiten an, um den der Abwurfschatten einer Form horizontal von der Form versetzt ist.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


Gibt den Abstand in Seiteneinheiten an, um den der Abwurfschatten einer Form vertikal von der Form versetzt ist.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


Gibt den Prozentsatz an, um den ein Formschatten vergrößert oder verkleinert wird.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


Zeigt den Standard‑Schattentyp für eine Seite an.

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


Bestimmt, ob der Seitenname in der Benutzeroberfläche (UI) angezeigt wird. Ein Wert von eins gibt an, dass die Seite nicht sichtbar ist; ein Wert von null gibt an, dass die Seite sichtbar ist.

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/pageprops\\#getDel--)

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

