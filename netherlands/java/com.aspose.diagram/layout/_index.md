---
title: Indeling
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen die de plaatsing van vormen en de routeringsinstellingen van connectoren regelen.
type: docs
weight: 215
url: /nl/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

Bevat elementen die de plaatsing van vormen en de routeringsinstellingen van connectoren regelen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | Bepaalt wanneer een connector een omleiding maakt. |
| [getConLineJumpCode()](#getConLineJumpCode--) | Bepaalt of een connector springt wanneer twee connectoren elkaar kruisen, |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | Bepaalt de richting van de lijnsprong voor lijnsprongen die optreden op een horizontaal segment van een dynamische connector. |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | Bepaalt de richting van de lijnsprong voor lijnsprongen die optreden op een verticaal segment van een dynamische connector. |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | Bepaalt de stijl van de lijnsprong voor lijnsprongen op een dynamische connector. |
| [getConLineRouteExt()](#getConLineRouteExt--) | Bepaalt het uiterlijk van een connector. |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getDisplayLevel()](#getDisplayLevel--) | Bepaalt de weergaveniveauband (het relatieve bereik van Z-ordeninggroepering) voor de vorm. |
| [getRelationships()](#getRelationships--) | Slaat de relaties op tussen containers, lijsten, bijschriften en vormen. |
| [getShapeFixedCode()](#getShapeFixedCode--) | Specificeert het plaatsingsgedrag voor een plaatsbare vorm. |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | Specificeert of plaatsbare vormen bovenop een vorm kunnen worden geplaatst wanneer een gebruiker Lay Out Shapes selecteert (Shapes-menu). |
| [getShapePermeableX()](#getShapePermeableX--) | Specificeert of een connector horizontaal door een vorm kan worden gerouteerd. |
| [getShapePermeableY()](#getShapePermeableY--) | Specificeert of een connector verticaal door een vorm kan worden gerouteerd. |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | Specificeert hoe een plaatsbare vorm draait en/of roteert op de pagina wanneer een gebruiker 'Lay Out Shapes' (Shapes-menu) selecteert. |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | Bepaalt de plaatsingsstijl voor onderliggende elementen. |
| [getShapePlowCode()](#getShapePlowCode--) | Specificeert of een plaatsbare vorm weggaat wanneer je een andere plaatsbare vorm dicht bij de vorm op de tekentabel sleept. |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | Specificeert de routeringsstijl en -richting voor een connector op de tekentabel. |
| [getShapeSplit()](#getShapeSplit--) | Bepaalt of deze vorm vormen die splitsbaar zijn kan splitsen. |
| [getShapeSplittable()](#getShapeSplittable--) | Bepaalt of deze 1-D vorm kan worden gesplitst. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | Voor de beschrijving van deze eigenschap, zie [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


Bepaalt wanneer een connector een omleiding maakt.

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


Bepaalt of een connector springt wanneer twee connectoren elkaar kruisen,

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


Bepaalt de richting van de lijnsprong voor lijnsprongen die optreden op een horizontaal segment van een dynamische connector.

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


Bepaalt de richting van de lijnsprong voor lijnsprongen die optreden op een verticaal segment van een dynamische connector.

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


Bepaalt de stijl van de lijnsprong voor lijnsprongen op een dynamische connector.

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


Bepaalt het uiterlijk van een connector.

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


Een vlag die aangeeft of het element lokaal is verwijderd. Een waarde van 1 geeft aan dat het element lokaal is verwijderd.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


Bepaalt de weergaveniveauband (het relatieve bereik van Z-ordeninggroepering) voor de vorm.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


Slaat de relaties op tussen containers, lijsten, bijschriften en vormen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


Specificeert het plaatsingsgedrag voor een plaatsbare vorm.

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


Specificeert of plaatsbare vormen bovenop een vorm kunnen worden geplaatst wanneer een gebruiker Lay Out Shapes selecteert (Shapes-menu).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


Specificeert of een connector horizontaal door een vorm kan worden gerouteerd.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


Specificeert of een connector verticaal door een vorm kan worden gerouteerd.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


Specificeert hoe een plaatsbare vorm draait en/of roteert op de pagina wanneer een gebruiker 'Lay Out Shapes' (Shapes-menu) selecteert.

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


Bepaalt de plaatsingsstijl voor onderliggende elementen.

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


Specificeert of een plaatsbare vorm weggaat wanneer je een andere plaatsbare vorm dicht bij de vorm op de tekentabel sleept.

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


Specificeert de routeringsstijl en -richting voor een connector op de tekentabel.

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


Bepaalt of deze vorm vormen die splitsbaar zijn kan splitsen.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


Bepaalt of deze 1-D vorm kan worden gesplitst.

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


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


Voor de beschrijving van deze eigenschap, zie [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
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

