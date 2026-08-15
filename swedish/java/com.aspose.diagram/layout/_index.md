---
title: Layout
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element som styr formplacering och inställningar för anslutningsruttning.
type: docs
weight: 215
url: /sv/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

Innehåller element som styr formplacering och inställningar för anslutningsruttning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | Bestämmer när en anslutning omdirigeras. |
| [getConLineJumpCode()](#getConLineJumpCode--) | Bestämmer om en anslutning hoppar när två anslutningar korsar, |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | Bestämmer linjesprångens riktning för linjesprång som uppstår på ett horisontellt segment av en dynamisk anslutning. |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | Bestämmer linjesprångens riktning för linjesprång som uppstår på ett vertikalt segment av en dynamisk anslutning. |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | Bestämmer linjesprångens stil för linjesprång på en dynamisk anslutning. |
| [getConLineRouteExt()](#getConLineRouteExt--) | Bestämmer utseendet på en anslutning. |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getDisplayLevel()](#getDisplayLevel--) | Bestämmer visningsnivåbandet (det relativa intervallet för Z-ordningsgruppering) för formen. |
| [getRelationships()](#getRelationships--) | Lagrar relationerna mellan behållare, listor, anmärkningar och former. |
| [getShapeFixedCode()](#getShapeFixedCode--) | Specificerar placeringsbeteende för en placerbar form. |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | Anger om placerbara former kan placeras ovanpå en form när en användare väljer Lay Out Shapes (Shapes menu). |
| [getShapePermeableX()](#getShapePermeableX--) | Anger om en anslutning kan routas horisontellt genom en form. |
| [getShapePermeableY()](#getShapePermeableY--) | Anger om en anslutning kan routas vertikalt genom en form. |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | Specificerar hur en placerbar form vänds och/eller roteras på sidan när en användare väljer Lay Out Shapes (Shapes-menyn). |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | Bestämmer placeringsstil för underordnade. |
| [getShapePlowCode()](#getShapePlowCode--) | Specificerar om en placerbar form flyttar sig när du drar en annan placerbar form nära formen på ritningssidan. |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | Specificerar routningsstil och riktning för en anslutning på ritningssidan. |
| [getShapeSplit()](#getShapeSplit--) | Bestämmer om denna form kan dela former som kan delas. |
| [getShapeSplittable()](#getShapeSplittable--) | Bestämmer om denna 1‑D‑form kan delas. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av den här egenskapen, se [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | För beskrivningen av den här egenskapen, se [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Bestämmer när en anslutning omdirigeras.

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


Bestämmer om en anslutning hoppar när två anslutningar korsar,

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


Bestämmer linjesprångens riktning för linjesprång som uppstår på ett horisontellt segment av en dynamisk anslutning.

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


Bestämmer linjesprångens riktning för linjesprång som uppstår på ett vertikalt segment av en dynamisk anslutning.

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


Bestämmer linjesprångens stil för linjesprång på en dynamisk anslutning.

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


Bestämmer utseendet på en anslutning.

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


Bestämmer visningsnivåbandet (det relativa intervallet för Z-ordningsgruppering) för formen.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


Lagrar relationerna mellan behållare, listor, anmärkningar och former.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


Specificerar placeringsbeteende för en placerbar form.

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


Anger om placerbara former kan placeras ovanpå en form när en användare väljer Lay Out Shapes (Shapes menu).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


Anger om en anslutning kan routas horisontellt genom en form.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


Anger om en anslutning kan routas vertikalt genom en form.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


Specificerar hur en placerbar form vänds och/eller roteras på sidan när en användare väljer Lay Out Shapes (Shapes-menyn).

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


Bestämmer placeringsstil för underordnade.

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


Specificerar om en placerbar form flyttar sig när du drar en annan placerbar form nära formen på ritningssidan.

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


Specificerar routningsstil och riktning för en anslutning på ritningssidan.

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


Bestämmer om denna form kan dela former som kan delas.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


Bestämmer om denna 1‑D‑form kan delas.

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


För beskrivningen av den här egenskapen, se [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


För beskrivningen av den här egenskapen, se [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
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

