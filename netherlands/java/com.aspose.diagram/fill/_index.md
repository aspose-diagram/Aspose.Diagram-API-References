---
title: Fill
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat de huidige opvulopmaakwaarden voor de vorm en de slagschaduw van de vorm, inclusief de voorgrondkleur en achtergrondkleur van het patroon.
type: docs
weight: 153
url: /nl/java/com.aspose.diagram/fill/
---

**Inheritance:**
java.lang.Object
```
public class Fill
```

Bevat de huidige opvulopmaakwaarden voor de vorm en de slagschaduw van de vorm, inclusief patroon, voorgrondkleur en achtergrondkleur.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een diepe kopie van deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getFillBkgnd()](#getFillBkgnd--) | Specificeert de kleur die wordt gebruikt voor de achtergrond van het opvulpatroon van de vorm. |
| [getFillBkgndTrans()](#getFillBkgndTrans--) | Specificeert het transparentieniveau voor de achtergrondkleur (opvulling) van het opvulpatroon van de vorm, van 0 (volledig ondoorzichtig) tot 1 (volledig transparant). |
| [getFillForegnd()](#getFillForegnd--) | Specificeert de kleur die wordt gebruikt voor de voorgrond (lijn) van het opvulpatroon van de vorm. |
| [getFillForegndTrans()](#getFillForegndTrans--) | Specificeert het transparentieniveau voor de voorgrondkleur (opvulling) van het opvulpatroon van de vorm, van 0 (volledig ondoorzichtig) tot 1 (volledig transparant). |
| [getFillPattern()](#getFillPattern--) | Specificeert het opvulpatroon voor de vorm. |
| [getGradientFill()](#getGradientFill--) | Bevat de huidige opmaakwaarden voor gradientvulling van de vorm. |
| [getShapeShdwBlur()](#getShapeShdwBlur--) | Specificeert de vervagingsgrootte van de schaduw van een vorm. |
| [getShapeShdwObliqueAngle()](#getShapeShdwObliqueAngle--) | Specificeert de hoek van de schuine richting van de schaduw van een vorm. |
| [getShapeShdwOffsetX()](#getShapeShdwOffsetX--) | Bepaalt de afstand in paginabereiken waarmee de schaduw van een vorm horizontaal wordt verschoven ten opzichte van de vorm. |
| [getShapeShdwOffsetY()](#getShapeShdwOffsetY--) | Bepaalt de afstand in paginabereiken waarmee de schaduw van een vorm verticaal wordt verschoven ten opzichte van de vorm. |
| [getShapeShdwScaleFactor()](#getShapeShdwScaleFactor--) | Specificeert het percentage waarmee de schaduw van een vorm kan worden vergroot of verkleind. |
| [getShapeShdwShow()](#getShapeShdwShow--) | Specificeert het type schaduw voor een vorm. |
| [getShapeShdwType()](#getShapeShdwType--) | Specificeert het type schaduw voor een vorm. |
| [getShdwBkgnd()](#getShdwBkgnd--) | Specificeert de kleur die wordt gebruikt voor de achtergrond (vulling) van het slagschaduwvullingspatroon van de vorm. |
| [getShdwBkgndTrans()](#getShdwBkgndTrans--) | Specificeert het transparentieniveau voor de achtergrond (vulling) van het slagschaduwvullingspatroon van de vorm, van 0.0 (volledig ondoorzichtig) tot 1.0 (volledig transparant). |
| [getShdwForegnd()](#getShdwForegnd--) | Specificeert de kleur die wordt gebruikt voor de voorgrond (lijn) van het slagschaduwvullingspatroon van de vorm. |
| [getShdwForegndTrans()](#getShdwForegndTrans--) | Specificeert het transparentieniveau voor de voorgrond (lijn) van het slagschaduwvullingspatroon van de vorm, van 0.0 (volledig ondoorzichtig) tot 1.0 (volledig transparant). |
| [getShdwPattern()](#getShdwPattern--) | Specificeert het opvulpatroon voor de schaduw van een vorm. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/fill\#getDel--) |
| [setFillBkgnd(ColorValue value)](#setFillBkgnd-com.aspose.diagram.ColorValue-) | Voor de beschrijving van deze eigenschap, zie [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--) |
| [setFillBkgndTrans(DoubleValue value)](#setFillBkgndTrans-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--) |
| [setFillForegnd(ColorValue value)](#setFillForegnd-com.aspose.diagram.ColorValue-) | Voor de beschrijving van deze eigenschap, zie [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--) |
| [setFillForegndTrans(DoubleValue value)](#setFillForegndTrans-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--) |
| [setFillPattern(IntValue value)](#setFillPattern-com.aspose.diagram.IntValue-) | Voor de beschrijving van deze eigenschap, zie [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--) |
| [setShapeShdwBlur(DoubleValue value)](#setShapeShdwBlur-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--) |
| [setShapeShdwObliqueAngle(DoubleValue value)](#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--) |
| [setShapeShdwOffsetX(DoubleValue value)](#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--) |
| [setShapeShdwOffsetY(DoubleValue value)](#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--) |
| [setShapeShdwScaleFactor(DoubleValue value)](#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--) |
| [setShapeShdwShow(ShapeShdwShow value)](#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-) | Voor de beschrijving van deze eigenschap, zie [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--) |
| [setShapeShdwType(ShapeShdwType value)](#setShapeShdwType-com.aspose.diagram.ShapeShdwType-) | Voor de beschrijving van deze eigenschap, zie [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--) |
| [setShdwBkgnd(ColorValue value)](#setShdwBkgnd-com.aspose.diagram.ColorValue-) | Voor de beschrijving van deze eigenschap, zie [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--) |
| [setShdwBkgndTrans(DoubleValue value)](#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--) |
| [setShdwForegnd(ColorValue value)](#setShdwForegnd-com.aspose.diagram.ColorValue-) | Voor de beschrijving van deze eigenschap, zie [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--) |
| [setShdwForegndTrans(DoubleValue value)](#setShdwForegndTrans-com.aspose.diagram.DoubleValue-) | Voor de beschrijving van deze eigenschap, zie [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--) |
| [setShdwPattern(IntValue value)](#setShdwPattern-com.aspose.diagram.IntValue-) | Voor de beschrijving van deze eigenschap, zie [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Maakt een diepe kopie van deze instantie.

**Returns:**
java.lang.Object -
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
### getDel() {#getDel--}
```
public int getDel()
```


Een vlag die aangeeft of het element lokaal is verwijderd. Een waarde van 1 geeft aan dat het element lokaal is verwijderd.

**Returns:**
int
### getFillBkgnd() {#getFillBkgnd--}
```
public ColorValue getFillBkgnd()
```


Specificeert de kleur die wordt gebruikt voor de achtergrond van het opvulpatroon van de vorm.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillBkgndTrans() {#getFillBkgndTrans--}
```
public DoubleValue getFillBkgndTrans()
```


Specificeert het transparentieniveau voor de achtergrondkleur (opvulling) van het opvulpatroon van de vorm, van 0 (volledig ondoorzichtig) tot 1 (volledig transparant).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillForegnd() {#getFillForegnd--}
```
public ColorValue getFillForegnd()
```


Specificeert de kleur die wordt gebruikt voor de voorgrond (lijn) van het opvulpatroon van de vorm.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillForegndTrans() {#getFillForegndTrans--}
```
public DoubleValue getFillForegndTrans()
```


Specificeert het transparentieniveau voor de voorgrondkleur (opvulling) van het opvulpatroon van de vorm, van 0 (volledig ondoorzichtig) tot 1 (volledig transparant).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillPattern() {#getFillPattern--}
```
public IntValue getFillPattern()
```


Specificeert het opvulpatroon voor de vorm.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getGradientFill() {#getGradientFill--}
```
public GradientFill getGradientFill()
```


Bevat de huidige opmaakwaarden voor gradientvulling van de vorm.

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getShapeShdwBlur() {#getShapeShdwBlur--}
```
public DoubleValue getShapeShdwBlur()
```


Specificeert de vervagingsgrootte van de schaduw van een vorm. kan nu geen vervaging tekenen, maar kan nu wel uit vsdx parseren.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwObliqueAngle() {#getShapeShdwObliqueAngle--}
```
public DoubleValue getShapeShdwObliqueAngle()
```


Specificeert de hoek van de schuine richting van de schaduw van een vorm.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetX() {#getShapeShdwOffsetX--}
```
public DoubleValue getShapeShdwOffsetX()
```


Bepaalt de afstand in paginabereiken waarmee de schaduw van een vorm horizontaal wordt verschoven ten opzichte van de vorm.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetY() {#getShapeShdwOffsetY--}
```
public DoubleValue getShapeShdwOffsetY()
```


Bepaalt de afstand in paginabereiken waarmee de schaduw van een vorm verticaal wordt verschoven ten opzichte van de vorm.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwScaleFactor() {#getShapeShdwScaleFactor--}
```
public DoubleValue getShapeShdwScaleFactor()
```


Specificeert het percentage waarmee de schaduw van een vorm kan worden vergroot of verkleind.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwShow() {#getShapeShdwShow--}
```
public ShapeShdwShow getShapeShdwShow()
```


Specificeert het type schaduw voor een vorm.

**Returns:**
[ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow)
### getShapeShdwType() {#getShapeShdwType--}
```
public ShapeShdwType getShapeShdwType()
```


Specificeert het type schaduw voor een vorm.

**Returns:**
[ShapeShdwType](../../com.aspose.diagram/shapeshdwtype)
### getShdwBkgnd() {#getShdwBkgnd--}
```
public ColorValue getShdwBkgnd()
```


Specificeert de kleur die wordt gebruikt voor de achtergrond (vulling) van het slagschaduwvullingspatroon van de vorm.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwBkgndTrans() {#getShdwBkgndTrans--}
```
public DoubleValue getShdwBkgndTrans()
```


Specificeert het transparentieniveau voor de achtergrond (vulling) van het slagschaduwvullingspatroon van de vorm, van 0.0 (volledig ondoorzichtig) tot 1.0 (volledig transparant).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwForegnd() {#getShdwForegnd--}
```
public ColorValue getShdwForegnd()
```


Specificeert de kleur die wordt gebruikt voor de voorgrond (lijn) van het slagschaduwvullingspatroon van de vorm.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwForegndTrans() {#getShdwForegndTrans--}
```
public DoubleValue getShdwForegndTrans()
```


Specificeert het transparentieniveau voor de voorgrond (lijn) van het slagschaduwvullingspatroon van de vorm, van 0.0 (volledig ondoorzichtig) tot 1.0 (volledig transparant).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwPattern() {#getShdwPattern--}
```
public IntValue getShdwPattern()
```


Specificeert het opvulpatroon voor de schaduw van een vorm.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/fill\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setFillBkgnd(ColorValue value) {#setFillBkgnd-com.aspose.diagram.ColorValue-}
```
public void setFillBkgnd(ColorValue value)
```


Voor de beschrijving van deze eigenschap, zie [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillBkgndTrans(DoubleValue value) {#setFillBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillBkgndTrans(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillForegnd(ColorValue value) {#setFillForegnd-com.aspose.diagram.ColorValue-}
```
public void setFillForegnd(ColorValue value)
```


Voor de beschrijving van deze eigenschap, zie [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillForegndTrans(DoubleValue value) {#setFillForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillForegndTrans(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillPattern(IntValue value) {#setFillPattern-com.aspose.diagram.IntValue-}
```
public void setFillPattern(IntValue value)
```


Voor de beschrijving van deze eigenschap, zie [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setShapeShdwBlur(DoubleValue value) {#setShapeShdwBlur-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwBlur(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwObliqueAngle(DoubleValue value) {#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwObliqueAngle(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetX(DoubleValue value) {#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetX(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetY(DoubleValue value) {#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetY(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwScaleFactor(DoubleValue value) {#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwScaleFactor(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwShow(ShapeShdwShow value) {#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-}
```
public void setShapeShdwShow(ShapeShdwShow value)
```


Voor de beschrijving van deze eigenschap, zie [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow) |  |

### setShapeShdwType(ShapeShdwType value) {#setShapeShdwType-com.aspose.diagram.ShapeShdwType-}
```
public void setShapeShdwType(ShapeShdwType value)
```


Voor de beschrijving van deze eigenschap, zie [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ShapeShdwType](../../com.aspose.diagram/shapeshdwtype) |  |

### setShdwBkgnd(ColorValue value) {#setShdwBkgnd-com.aspose.diagram.ColorValue-}
```
public void setShdwBkgnd(ColorValue value)
```


Voor de beschrijving van deze eigenschap, zie [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwBkgndTrans(DoubleValue value) {#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwBkgndTrans(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwForegnd(ColorValue value) {#setShdwForegnd-com.aspose.diagram.ColorValue-}
```
public void setShdwForegnd(ColorValue value)
```


Voor de beschrijving van deze eigenschap, zie [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwForegndTrans(DoubleValue value) {#setShdwForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwForegndTrans(DoubleValue value)
```


Voor de beschrijving van deze eigenschap, zie [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwPattern(IntValue value) {#setShdwPattern-com.aspose.diagram.IntValue-}
```
public void setShdwPattern(IntValue value)
```


Voor de beschrijving van deze eigenschap, zie [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

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

