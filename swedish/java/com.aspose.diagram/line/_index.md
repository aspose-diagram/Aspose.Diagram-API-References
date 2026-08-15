---
title: Line
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element som specificerar generell placeringsinformation om en form.
type: docs
weight: 221
url: /sv/java/com.aspose.diagram/line/
---

**Inheritance:**
java.lang.Object
```
public class Line
```

Innehåller element som specificerar generell placeringsinformation om en form.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginArrow()](#getBeginArrow--) | Anger om en linje har en pilspets eller annat linjeändformat vid dess första hörn. |
| [getBeginArrowSize()](#getBeginArrowSize--) | Bestämmer storleken på pilspetsen i början av linjen. |
| [getClass()](#getClass--) |  |
| [getCompoundType()](#getCompoundType--) | Anger linjens CompoundType för formen. |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getEndArrow()](#getEndArrow--) | Anger om en linje har en pilspets eller annat linjeändformat vid dess sista hörn. |
| [getEndArrowSize()](#getEndArrowSize--) | Anger storleken på pilspetsen i slutet av linjen. |
| [getGradientLine()](#getGradientLine--) | Innehåller de aktuella gradientlinjeformateringsvärdena för formen |
| [getLineCap()](#getLineCap--) | Anger om en linje har rundade eller fyrkantiga linjeändar. |
| [getLineColor()](#getLineColor--) | Anger linjens färg för formen. |
| [getLineColorTrans()](#getLineColorTrans--) | Anger transparensnivån för en formes linjefärg, från 0 (opak) till 1 (helt transparent). |
| [getLinePattern()](#getLinePattern--) | Anger linjemönstret för formen |
| [getLineWeight()](#getLineWeight--) | Anger linjens tjocklek för en form. |
| [getRounding()](#getRounding--) | Anger radien på den avrundningsbåge som tillämpas där två sammanhängande segment av en bana möts. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBeginArrow(IntValue value)](#setBeginArrow-com.aspose.diagram.IntValue-) | För beskrivningen av denna egenskap, se [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--) |
| [setBeginArrowSize(ArrowSize value)](#setBeginArrowSize-com.aspose.diagram.ArrowSize-) | För beskrivningen av denna egenskap, se [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--) |
| [setCompoundType(CompoundType value)](#setCompoundType-com.aspose.diagram.CompoundType-) | För beskrivningen av denna egenskap, se [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--) |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/line\#getDel--) |
| [setEndArrow(IntValue value)](#setEndArrow-com.aspose.diagram.IntValue-) | För beskrivningen av denna egenskap, se [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--) |
| [setEndArrowSize(ArrowSize value)](#setEndArrowSize-com.aspose.diagram.ArrowSize-) | För beskrivningen av denna egenskap, se [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--) |
| [setLineCap(BoolValue value)](#setLineCap-com.aspose.diagram.BoolValue-) | För beskrivningen av denna egenskap, se [getLineCap()](../../com.aspose.diagram/line\#getLineCap--) |
| [setLineColor(ColorValue value)](#setLineColor-com.aspose.diagram.ColorValue-) | För beskrivningen av denna egenskap, se [getLineColor()](../../com.aspose.diagram/line\#getLineColor--) |
| [setLineColorTrans(DoubleValue value)](#setLineColorTrans-com.aspose.diagram.DoubleValue-) | För beskrivningen av denna egenskap, se [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--) |
| [setLinePattern(IntValue value)](#setLinePattern-com.aspose.diagram.IntValue-) | För beskrivningen av denna egenskap, se [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--) |
| [setLineWeight(DoubleValue value)](#setLineWeight-com.aspose.diagram.DoubleValue-) | För beskrivningen av denna egenskap, se [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--) |
| [setRounding(DoubleValue value)](#setRounding-com.aspose.diagram.DoubleValue-) | För beskrivningen av denna egenskap, se [getRounding()](../../com.aspose.diagram/line\#getRounding--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en djup kopia av denna instans.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBeginArrow() {#getBeginArrow--}
```
public IntValue getBeginArrow()
```


Anger om en linje har en pilspets eller annat linjeändformat vid dess första hörn. Ange ett tal från 0 till 45 eller USE-funktionen med namnet på en anpassad linjeände.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBeginArrowSize() {#getBeginArrowSize--}
```
public ArrowSize getBeginArrowSize()
```


Bestämmer storleken på pilspetsen i början av linjen. Ange ett tal mellan 0 och 6.

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


Anger linjens CompoundType för formen.

**Returns:**
[CompoundType](../../com.aspose.diagram/compoundtype)
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getEndArrow() {#getEndArrow--}
```
public IntValue getEndArrow()
```


Anger om en linje har en pilspets eller annat linjeändformat vid dess sista hörn.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getEndArrowSize() {#getEndArrowSize--}
```
public ArrowSize getEndArrowSize()
```


Anger storleken på pilspetsen i slutet av linjen.

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getGradientLine() {#getGradientLine--}
```
public GradientFill getGradientLine()
```


Innehåller de aktuella gradientlinjeformateringsvärdena för formen

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getLineCap() {#getLineCap--}
```
public BoolValue getLineCap()
```


Anger om en linje har rundade eller fyrkantiga linjeändar.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineColor() {#getLineColor--}
```
public ColorValue getLineColor()
```


Anger linjens färg för formen.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getLineColorTrans() {#getLineColorTrans--}
```
public DoubleValue getLineColorTrans()
```


Anger genomskinlighetsnivån för en formes linjefärg, från 0 (opak) till 1 (helt genomskinlig). Standardvärdet är 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLinePattern() {#getLinePattern--}
```
public IntValue getLinePattern()
```


Anger linjemönstret för formen

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLineWeight() {#getLineWeight--}
```
public DoubleValue getLineWeight()
```


Anger linjebredden för en form. Linjebredden är oberoende av ritningens skala. Om ritningen skalas förblir linjebredden densamma.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRounding() {#getRounding--}
```
public DoubleValue getRounding()
```


Anger radien på den avrundningsbåge som tillämpas där två sammanhängande segment av en bana möts. Till exempel kan avrundning användas för att ge en rektangel rundade hörn.

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


För beskrivningen av denna egenskap, se [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBeginArrowSize(ArrowSize value) {#setBeginArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setBeginArrowSize(ArrowSize value)
```


För beskrivningen av denna egenskap, se [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setCompoundType(CompoundType value) {#setCompoundType-com.aspose.diagram.CompoundType-}
```
public void setCompoundType(CompoundType value)
```


För beskrivningen av denna egenskap, se [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CompoundType](../../com.aspose.diagram/compoundtype) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/line\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEndArrow(IntValue value) {#setEndArrow-com.aspose.diagram.IntValue-}
```
public void setEndArrow(IntValue value)
```


För beskrivningen av denna egenskap, se [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setEndArrowSize(ArrowSize value) {#setEndArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setEndArrowSize(ArrowSize value)
```


För beskrivningen av denna egenskap, se [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setLineCap(BoolValue value) {#setLineCap-com.aspose.diagram.BoolValue-}
```
public void setLineCap(BoolValue value)
```


För beskrivningen av denna egenskap, se [getLineCap()](../../com.aspose.diagram/line\#getLineCap--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setLineColor(ColorValue value) {#setLineColor-com.aspose.diagram.ColorValue-}
```
public void setLineColor(ColorValue value)
```


För beskrivningen av denna egenskap, se [getLineColor()](../../com.aspose.diagram/line\#getLineColor--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setLineColorTrans(DoubleValue value) {#setLineColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setLineColorTrans(DoubleValue value)
```


För beskrivningen av denna egenskap, se [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLinePattern(IntValue value) {#setLinePattern-com.aspose.diagram.IntValue-}
```
public void setLinePattern(IntValue value)
```


För beskrivningen av denna egenskap, se [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLineWeight(DoubleValue value) {#setLineWeight-com.aspose.diagram.DoubleValue-}
```
public void setLineWeight(DoubleValue value)
```


För beskrivningen av denna egenskap, se [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRounding(DoubleValue value) {#setRounding-com.aspose.diagram.DoubleValue-}
```
public void setRounding(DoubleValue value)
```


För beskrivningen av denna egenskap, se [getRounding()](../../com.aspose.diagram/line\#getRounding--)

**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

