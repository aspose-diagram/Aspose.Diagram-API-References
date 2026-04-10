---
title: Line
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die allgemeine Positionsinformationen zu einer Form angeben.
type: docs
weight: 221
url: /de/java/com.aspose.diagram/line/
---

**Inheritance:**
java.lang.Object
```
public class Line
```

Enthält Elemente, die allgemeine Positionsinformationen zu einer Form angeben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone()](#deepClone--) | Erstellt eine tiefe Kopie dieser Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginArrow()](#getBeginArrow--) | Gibt an, ob eine Linie an ihrem ersten Scheitelpunkt einen Pfeilkopf oder ein anderes Linienende-Format hat. |
| [getBeginArrowSize()](#getBeginArrowSize--) | Bestimmt die Größe des Pfeilkopfes am Anfang der Linie. |
| [getClass()](#getClass--) |  |
| [getCompoundType()](#getCompoundType--) | Gibt den Linien-CompoundType der Form an. |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getEndArrow()](#getEndArrow--) | Gibt an, ob eine Linie an ihrem letzten Scheitelpunkt einen Pfeilkopf oder ein anderes Linienende-Format hat. |
| [getEndArrowSize()](#getEndArrowSize--) | Gibt die Größe des Pfeilkopfes am Ende der Linie an. |
| [getGradientLine()](#getGradientLine--) | Enthält die aktuellen Farbverlaufs-Linienformatierungswerte für die Form |
| [getLineCap()](#getLineCap--) | Gibt an, ob eine Linie abgerundete oder eckige Linienenden hat. |
| [getLineColor()](#getLineColor--) | Gibt die Linienfarbe der Form an. |
| [getLineColorTrans()](#getLineColorTrans--) | Gibt den Transparenzgrad der Linienfarbe einer Form an, von 0 (undurchsichtig) bis 1 (vollständig transparent). |
| [getLinePattern()](#getLinePattern--) | Gibt das Linienmuster der Form an |
| [getLineWeight()](#getLineWeight--) | Gibt die Linienstärke einer Form an. |
| [getRounding()](#getRounding--) | Gibt den Radius des Abrundungsbogens an, der dort angewendet wird, wo zwei zusammenhängende Segmente eines Pfades aufeinandertreffen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBeginArrow(IntValue value)](#setBeginArrow-com.aspose.diagram.IntValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--) |
| [setBeginArrowSize(ArrowSize value)](#setBeginArrowSize-com.aspose.diagram.ArrowSize-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--) |
| [setCompoundType(CompoundType value)](#setCompoundType-com.aspose.diagram.CompoundType-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--) |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/line\#getDel--) |
| [setEndArrow(IntValue value)](#setEndArrow-com.aspose.diagram.IntValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--) |
| [setEndArrowSize(ArrowSize value)](#setEndArrowSize-com.aspose.diagram.ArrowSize-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--) |
| [setLineCap(BoolValue value)](#setLineCap-com.aspose.diagram.BoolValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getLineCap()](../../com.aspose.diagram/line\#getLineCap--) |
| [setLineColor(ColorValue value)](#setLineColor-com.aspose.diagram.ColorValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getLineColor()](../../com.aspose.diagram/line\#getLineColor--) |
| [setLineColorTrans(DoubleValue value)](#setLineColorTrans-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--) |
| [setLinePattern(IntValue value)](#setLinePattern-com.aspose.diagram.IntValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--) |
| [setLineWeight(DoubleValue value)](#setLineWeight-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--) |
| [setRounding(DoubleValue value)](#setRounding-com.aspose.diagram.DoubleValue-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getRounding()](../../com.aspose.diagram/line\#getRounding--) |
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
### getBeginArrow() {#getBeginArrow--}
```
public IntValue getBeginArrow()
```


Gibt an, ob eine Linie an ihrem ersten Scheitelpunkt einen Pfeilkopf oder ein anderes Linienende-Format hat. Geben Sie eine Zahl von 0 bis 45 ein oder die USE‑Funktion mit dem Namen eines benutzerdefinierten Linienendes.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBeginArrowSize() {#getBeginArrowSize--}
```
public ArrowSize getBeginArrowSize()
```


Bestimmt die Größe der Pfeilspitze am Anfang der Linie. Geben Sie eine Zahl von 0 bis 6 ein.

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompoundType() {#getCompoundType--}
```
public CompoundType getCompoundType()
```


Gibt den Linien-CompoundType der Form an.

**Returns:**
[CompoundType](../../com.aspose.diagram/compoundtype)
### getDel() {#getDel--}
```
public int getDel()
```


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Ein Wert von 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getEndArrow() {#getEndArrow--}
```
public IntValue getEndArrow()
```


Gibt an, ob eine Linie an ihrem letzten Scheitelpunkt einen Pfeilkopf oder ein anderes Linienende-Format hat.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getEndArrowSize() {#getEndArrowSize--}
```
public ArrowSize getEndArrowSize()
```


Gibt die Größe des Pfeilkopfes am Ende der Linie an.

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getGradientLine() {#getGradientLine--}
```
public GradientFill getGradientLine()
```


Enthält die aktuellen Farbverlaufs-Linienformatierungswerte für die Form

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getLineCap() {#getLineCap--}
```
public BoolValue getLineCap()
```


Gibt an, ob eine Linie abgerundete oder eckige Linienenden hat.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineColor() {#getLineColor--}
```
public ColorValue getLineColor()
```


Gibt die Linienfarbe der Form an.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getLineColorTrans() {#getLineColorTrans--}
```
public DoubleValue getLineColorTrans()
```


Gibt den Transparenzgrad der Linienfarbe einer Form an, von 0 (undurchsichtig) bis 1 (vollständig transparent). Der Standardwert ist 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLinePattern() {#getLinePattern--}
```
public IntValue getLinePattern()
```


Gibt das Linienmuster der Form an

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLineWeight() {#getLineWeight--}
```
public DoubleValue getLineWeight()
```


Gibt die Linienstärke einer Form an. Die Linienstärke ist unabhängig vom Maßstab der Zeichnung. Wird die Zeichnung skaliert, bleibt die Linienstärke unverändert.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRounding() {#getRounding--}
```
public DoubleValue getRounding()
```


Gibt den Radius des Abrundungsbogens an, der dort angewendet wird, wo zwei zusammenhängende Segmente eines Pfades aufeinandertreffen. Beispielsweise kann die Abrundung verwendet werden, um einem Rechteck abgerundete Ecken zu geben.

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




### setBeginArrow(IntValue value) {#setBeginArrow-com.aspose.diagram.IntValue-}
```
public void setBeginArrow(IntValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBeginArrowSize(ArrowSize value) {#setBeginArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setBeginArrowSize(ArrowSize value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setCompoundType(CompoundType value) {#setCompoundType-com.aspose.diagram.CompoundType-}
```
public void setCompoundType(CompoundType value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [CompoundType](../../com.aspose.diagram/compoundtype) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/line\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEndArrow(IntValue value) {#setEndArrow-com.aspose.diagram.IntValue-}
```
public void setEndArrow(IntValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setEndArrowSize(ArrowSize value) {#setEndArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setEndArrowSize(ArrowSize value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setLineCap(BoolValue value) {#setLineCap-com.aspose.diagram.BoolValue-}
```
public void setLineCap(BoolValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getLineCap()](../../com.aspose.diagram/line\#getLineCap--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setLineColor(ColorValue value) {#setLineColor-com.aspose.diagram.ColorValue-}
```
public void setLineColor(ColorValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getLineColor()](../../com.aspose.diagram/line\#getLineColor--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setLineColorTrans(DoubleValue value) {#setLineColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setLineColorTrans(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLinePattern(IntValue value) {#setLinePattern-com.aspose.diagram.IntValue-}
```
public void setLinePattern(IntValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLineWeight(DoubleValue value) {#setLineWeight-com.aspose.diagram.DoubleValue-}
```
public void setLineWeight(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRounding(DoubleValue value) {#setRounding-com.aspose.diagram.DoubleValue-}
```
public void setRounding(DoubleValue value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getRounding()](../../com.aspose.diagram/line\#getRounding--)

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

