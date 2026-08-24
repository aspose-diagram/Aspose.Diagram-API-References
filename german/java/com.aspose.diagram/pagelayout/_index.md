---
title: PageLayout
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Zellen, die die Seitengestaltungseinstellungen für Formen und Verbinder steuern, wie z. B. den Abstand zwischen allen Formen auf der Seite, den Abstand zwischen allen Verbindern auf der Seite und den Routing‑Stil für alle Verbinder auf der Seite.
type: docs
weight: 263
url: /de/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

Enthält Zellen, die die Seitengestaltungseinstellungen für Formen und Verbinder steuern, wie z. B. den Abstand zwischen allen Formen auf der Seite, den Abstand zwischen allen Verbindern auf der Seite und den Routing‑Stil für alle Verbinder auf der Seite.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | Bestimmt den vertikalen Abstand zwischen Formen auf der Zeichenfläche, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden. |
| [getAvenueSizeY()](#getAvenueSizeY--) | Bestimmt den vertikalen Abstand zwischen Formen auf der Zeichenfläche, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden. |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | Gibt an, wie Formen auf der Seite platziert werden, wenn Formen angeordnet werden, nachdem ein Benutzer „Formen anordnen“ (Form‑Menü) auswählt. |
| [getBlockSizeX()](#getBlockSizeX--) | Bestimmt die vertikale Blockgröße, den Bereich, in den jede Ihrer Formen auf der Zeichenfläche passen muss, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden. |
| [getBlockSizeY()](#getBlockSizeY--) | Bestimmt den horizontalen Abstand zwischen Formen auf der Zeichenfläche, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden. |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | Bestimmt, welche Form das übergeordnete Element ist, wenn Formen über Steuergriffe verwendet werden. |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getDynamicsOff()](#getDynamicsOff--) | Gibt an, ob platzierbare Formen verschoben werden und Verbinder um andere Formen und Verbinder auf der Zeichenfläche herum umgeleitet werden. |
| [getEnableGrid()](#getEnableGrid--) | Gibt an, ob Microsoft Visio Formen anhand eines internen Seitengitters anordnet, wenn der Benutzer Lay Out Shapes (Shape‑Menü) auswählt. |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | Gibt an, welche dynamischen Verbinder auseinandergezogen werden sollen, wenn sie übereinander geroutet werden. |
| [getLineAdjustTo()](#getLineAdjustTo--) | Gibt an, welche dynamischen Verbinder übereinander ausgerichtet werden sollen, wenn sie übereinander geroutet werden. |
| [getLineJumpCode()](#getLineJumpCode--) | Gibt den Linien‑Sprungstil für alle Verbinder auf der Zeichen‑Seite an, die keinen lokalen Linien‑Sprungstil haben. |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | Gibt die Größe von Liniensprüngen auf horizontalen Segmenten dynamischer Verbinder auf der Seite an, als Prozentsatz des Werts des Elements LineToLineX (das den horizontalen Abstand zwischen allen Verbindern auf der Zeichenfläche festlegt). |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | Gibt die Größe von Liniensprüngen auf vertikalen Segmenten dynamischer Verbinder auf der Seite an, als Prozentsatz des Werts des Elements LineToLineY (das den vertikalen Abstand zwischen allen Verbindern auf der Zeichenfläche festlegt). |
| [getLineJumpStyle()](#getLineJumpStyle--) | Gibt die Richtung von Liniensprüngen auf horizontalen Segmenten dynamischer Verbinder auf der Zeichenfläche an, für die keine lokale Sprungrichtung festgelegt wurde. |
| [getLineRouteExt()](#getLineRouteExt--) | Gibt das Standard‑Aussehen für alle Verbinder auf einer Seite an. |
| [getLineToLineX()](#getLineToLineX--) | Gibt den minimalen horizontalen Abstand zwischen dynamischen Verbindern auf der Zeichenfläche an. |
| [getLineToLineY()](#getLineToLineY--) | Gibt den minimalen vertikalen Abstand zwischen dynamischen Verbindern auf der Zeichenfläche an. |
| [getLineToNodeX()](#getLineToNodeX--) | Gibt den minimalen vertikalen Abstand zwischen dynamischen Verbindern und Formen auf der Zeichenfläche an. |
| [getLineToNodeY()](#getLineToNodeY--) | Bestimmt die horizontale Blockgröße, den Bereich, in den jede Ihrer Formen auf der Zeichenfläche passen muss, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden. |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | Gibt die Richtung von Liniensprüngen auf vertikalen dynamischen Verbindern auf der Zeichenfläche an, für die keine lokale Sprungrichtung festgelegt wurde. |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | Gibt den minimalen horizontalen Abstand zwischen dynamischen Verbindern und Formen auf der Zeichenfläche an. |
| [getPageShapeSplit()](#getPageShapeSplit--) | Gibt an, ob Formen auf der Seite automatisch aufgeteilt werden können. |
| [getPlaceDepth()](#getPlaceDepth--) | Gibt an, ob platzierbare Formen weggeschoben werden, wenn der Benutzer eine platzierbare Form in die Nähe einer anderen platzierbaren Form auf der Zeichenfläche zieht. |
| [getPlaceFlip()](#getPlaceFlip--) | Gibt an, wie platzierbare Formen auf einer Seite gedreht und/oder gespiegelt werden, wenn Formen mit dem Befehl „Formen anordnen“ in Microsoft Visio angeordnet werden. |
| [getPlaceStyle()](#getPlaceStyle--) | Gibt den Routing‑Stil und die Richtung für alle dynamischen Verbinder auf der Zeichenfläche an, die keinen lokalen Routing‑Stil haben. |
| [getPlowCode()](#getPlowCode--) | Bestimmt die dynamischen Verbinder, zu denen Sprünge hinzugefügt werden sollen. |
| [getResizePage()](#getResizePage--) | Gibt an, ob die Seite vergrößert werden soll, um die Zeichnung zu umfassen, nachdem ein Benutzer Lay Out Shapes (Shapes‑Menü) ausgewählt hat. |
| [getRouteStyle()](#getRouteStyle--) | Für eine automatisch angeordnete Zeichnung gibt die Methode an, mit der die Zeichnung vor der Erstellung des Layouts analysiert wird, und bestimmt den Layouttyp. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/pagelayout\\#getDel--) |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


Bestimmt den vertikalen Abstand zwischen Formen auf der Zeichenfläche, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


Bestimmt den vertikalen Abstand zwischen Formen auf der Zeichenfläche, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


Gibt an, wie Formen auf der Seite platziert werden, wenn Formen angeordnet werden, nachdem ein Benutzer „Formen anordnen“ (Form‑Menü) auswählt.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


Bestimmt die vertikale Blockgröße, den Bereich, in den jede Ihrer Formen auf der Zeichenfläche passen muss, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


Bestimmt den horizontalen Abstand zwischen Formen auf der Zeichenfläche, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


Bestimmt, welche Form das übergeordnete Element ist, wenn Formen über Steuergriffe verwendet werden. Dieses Element legt das Verhalten aller Formen auf der Zeichenfläche fest.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


Gibt an, ob platzierbare Formen verschoben werden und Verbinder um andere Formen und Verbinder auf der Zeichenfläche herum umgeleitet werden.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


Gibt an, ob Microsoft Visio Formen anhand eines internen Seitengitters anordnet, wenn der Benutzer Lay Out Shapes (Shape‑Menü) auswählt.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


Gibt an, welche dynamischen Verbinder auseinandergezogen werden sollen, wenn sie übereinander geroutet werden.

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


Gibt an, welche dynamischen Verbinder übereinander ausgerichtet werden sollen, wenn sie übereinander geroutet werden.

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


Gibt den Linien‑Sprungstil für alle Verbinder auf der Zeichen‑Seite an, die keinen lokalen Linien‑Sprungstil haben.

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


Gibt die Größe von Liniensprüngen auf horizontalen Segmenten dynamischer Verbinder auf der Seite an, als Prozentsatz des Werts des Elements LineToLineX (das den horizontalen Abstand zwischen allen Verbindern auf der Zeichenfläche festlegt). Der Wert dieses Elements liegt zwischen 0 und 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


Gibt die Größe von Liniensprüngen auf vertikalen Segmenten dynamischer Verbinder auf der Seite an, als Prozentsatz des Werts des Elements LineToLineY (das den vertikalen Abstand zwischen allen Verbindern auf der Zeichenfläche festlegt). Dieses Element kann einen Wert von 0 bis 10 enthalten.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


Gibt die Richtung von Liniensprüngen auf horizontalen Segmenten dynamischer Verbinder auf der Zeichenfläche an, für die keine lokale Sprungrichtung festgelegt wurde.

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


Gibt das Standard‑Aussehen für alle Verbinder auf einer Seite an.

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


Gibt den minimalen horizontalen Abstand zwischen dynamischen Verbindern auf der Zeichenfläche an.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


Gibt den minimalen vertikalen Abstand zwischen dynamischen Verbindern auf der Zeichenfläche an.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


Gibt den minimalen vertikalen Abstand zwischen dynamischen Verbindern und Formen auf der Zeichenfläche an.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


Bestimmt die horizontale Blockgröße, den Bereich, in den jede Ihrer Formen auf der Zeichenfläche passen muss, wenn Sie Microsoft Visio zum Anordnen von Formen auf der Zeichenfläche verwenden.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


Gibt die Richtung von Liniensprüngen auf vertikalen dynamischen Verbindern auf der Zeichenfläche an, für die keine lokale Sprungrichtung festgelegt wurde.

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


Gibt den minimalen horizontalen Abstand zwischen dynamischen Verbindern und Formen auf der Zeichenfläche an.

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


Gibt an, ob Formen auf der Seite automatisch aufgeteilt werden können.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


Gibt an, ob platzierbare Formen weggeschoben werden, wenn der Benutzer eine platzierbare Form in die Nähe einer anderen platzierbaren Form auf der Zeichenfläche zieht.

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


Gibt an, wie platzierbare Formen auf einer Seite gedreht und/oder rotiert werden, wenn Formen mit dem Befehl „Lay Out Shapes“ in Microsoft Visio angeordnet werden. Die folgenden hexadezimalen Werte sind zulässig.

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


Gibt den Routing‑Stil und die Richtung für alle dynamischen Verbinder auf der Zeichenfläche an, die keinen lokalen Routing‑Stil haben.

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


Bestimmt die dynamischen Verbinder, zu denen Sprünge hinzugefügt werden sollen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


Gibt an, ob die Seite vergrößert werden soll, um die Zeichnung zu umfassen, nachdem ein Benutzer Lay Out Shapes (Shapes‑Menü) ausgewählt hat.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


Für eine automatisch angeordnete Zeichnung gibt die Methode an, mit der die Zeichnung vor der Erstellung des Layouts analysiert wird, und bestimmt den Layouttyp.

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/pagelayout\\#getDel--)

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

