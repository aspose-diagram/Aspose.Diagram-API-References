---
title: Remplissage
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient les valeurs actuelles de formatage de remplissage pour la forme et l'ombre portée de la forme, y compris la couleur de premier plan du motif et la couleur d'arrière-plan.
type: docs
weight: 153
url: /fr/java/com.aspose.diagram/fill/
---

**Inheritance:**
java.lang.Object
```
public class Fill
```

Contient les valeurs actuelles de format de remplissage pour la forme et son ombre portée, y compris le motif, la couleur de premier plan et la couleur d'arrière-plan.
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getFillBkgnd()](#getFillBkgnd--) | Spécifie la couleur utilisée pour l'arrière-plan du motif de remplissage de la forme. |
| [getFillBkgndTrans()](#getFillBkgndTrans--) | Spécifie le niveau de transparence de la couleur d'arrière-plan (remplissage) du motif de remplissage de la forme, de 0 (complètement opaque) à 1 (complètement transparent). |
| [getFillForegnd()](#getFillForegnd--) | Spécifie la couleur utilisée pour le premier plan (trait) du motif de remplissage de la forme. |
| [getFillForegndTrans()](#getFillForegndTrans--) | Spécifie le niveau de transparence de la couleur de premier plan (remplissage) du motif de remplissage de la forme, de 0 (complètement opaque) à 1 (complètement transparent). |
| [getFillPattern()](#getFillPattern--) | Spécifie le motif de remplissage pour la forme. |
| [getGradientFill()](#getGradientFill--) | Contient les valeurs actuelles de formatage du remplissage en dégradé pour la forme |
| [getShapeShdwBlur()](#getShapeShdwBlur--) | Spécifie la taille du flou de l'ombre d'une forme. |
| [getShapeShdwObliqueAngle()](#getShapeShdwObliqueAngle--) | Spécifie l'angle de direction oblique de l'ombre d'une forme. |
| [getShapeShdwOffsetX()](#getShapeShdwOffsetX--) | Détermine la distance, en unités de page, à laquelle l'ombre d'une forme est décalée horizontalement par rapport à la forme. |
| [getShapeShdwOffsetY()](#getShapeShdwOffsetY--) | Détermine la distance, en unités de page, à laquelle l'ombre d'une forme est décalée verticalement par rapport à la forme. |
| [getShapeShdwScaleFactor()](#getShapeShdwScaleFactor--) | Spécifie le pourcentage selon lequel l'ombre d'une forme peut être agrandie ou réduite. |
| [getShapeShdwShow()](#getShapeShdwShow--) | Spécifie le type d'ombre pour une forme. |
| [getShapeShdwType()](#getShapeShdwType--) | Spécifie le type d'ombre pour une forme. |
| [getShdwBkgnd()](#getShdwBkgnd--) | Spécifie la couleur utilisée pour l'arrière-plan (remplissage) du motif de remplissage de l'ombre portée de la forme. |
| [getShdwBkgndTrans()](#getShdwBkgndTrans--) | Spécifie le niveau de transparence de l'arrière-plan (remplissage) du motif de remplissage de l'ombre portée de la forme, de 0,0 (complètement opaque) à 1,0 (complètement transparent). |
| [getShdwForegnd()](#getShdwForegnd--) | Spécifie la couleur utilisée pour le premier plan (trait) du motif de remplissage de l'ombre portée de la forme. |
| [getShdwForegndTrans()](#getShdwForegndTrans--) | Spécifie le niveau de transparence du premier plan (trait) du motif de remplissage de l'ombre portée de la forme, de 0,0 (complètement opaque) à 1,0 (complètement transparent). |
| [getShdwPattern()](#getShdwPattern--) | Spécifie le motif de remplissage pour l'ombre d'une forme. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/fill\#getDel--) |
| [setFillBkgnd(ColorValue value)](#setFillBkgnd-com.aspose.diagram.ColorValue-) | Pour la description de cette propriété, veuillez consulter [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--) |
| [setFillBkgndTrans(DoubleValue value)](#setFillBkgndTrans-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--) |
| [setFillForegnd(ColorValue value)](#setFillForegnd-com.aspose.diagram.ColorValue-) | Pour la description de cette propriété, veuillez consulter [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--) |
| [setFillForegndTrans(DoubleValue value)](#setFillForegndTrans-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--) |
| [setFillPattern(IntValue value)](#setFillPattern-com.aspose.diagram.IntValue-) | Pour la description de cette propriété, veuillez consulter [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--) |
| [setShapeShdwBlur(DoubleValue value)](#setShapeShdwBlur-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--) |
| [setShapeShdwObliqueAngle(DoubleValue value)](#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--) |
| [setShapeShdwOffsetX(DoubleValue value)](#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--) |
| [setShapeShdwOffsetY(DoubleValue value)](#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--) |
| [setShapeShdwScaleFactor(DoubleValue value)](#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--) |
| [setShapeShdwShow(ShapeShdwShow value)](#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-) | Pour la description de cette propriété, veuillez consulter [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--) |
| [setShapeShdwType(ShapeShdwType value)](#setShapeShdwType-com.aspose.diagram.ShapeShdwType-) | Pour la description de cette propriété, veuillez consulter [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--) |
| [setShdwBkgnd(ColorValue value)](#setShdwBkgnd-com.aspose.diagram.ColorValue-) | Pour la description de cette propriété, veuillez consulter [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--) |
| [setShdwBkgndTrans(DoubleValue value)](#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--) |
| [setShdwForegnd(ColorValue value)](#setShdwForegnd-com.aspose.diagram.ColorValue-) | Pour la description de cette propriété, veuillez consulter [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--) |
| [setShdwForegndTrans(DoubleValue value)](#setShdwForegndTrans-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--) |
| [setShdwPattern(IntValue value)](#setShdwPattern-com.aspose.diagram.IntValue-) | Pour la description de cette propriété, veuillez consulter [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée une copie profonde de cette instance.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Un indicateur indiquant si l'élément a été supprimé localement. Une valeur de 1 indique que l'élément a été supprimé localement.

**Returns:**
int
### getFillBkgnd() {#getFillBkgnd--}
```
public ColorValue getFillBkgnd()
```


Spécifie la couleur utilisée pour l'arrière-plan du motif de remplissage de la forme.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillBkgndTrans() {#getFillBkgndTrans--}
```
public DoubleValue getFillBkgndTrans()
```


Spécifie le niveau de transparence de la couleur d'arrière-plan (remplissage) du motif de remplissage de la forme, de 0 (complètement opaque) à 1 (complètement transparent).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillForegnd() {#getFillForegnd--}
```
public ColorValue getFillForegnd()
```


Spécifie la couleur utilisée pour le premier plan (trait) du motif de remplissage de la forme.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillForegndTrans() {#getFillForegndTrans--}
```
public DoubleValue getFillForegndTrans()
```


Spécifie le niveau de transparence de la couleur de premier plan (remplissage) du motif de remplissage de la forme, de 0 (complètement opaque) à 1 (complètement transparent).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillPattern() {#getFillPattern--}
```
public IntValue getFillPattern()
```


Spécifie le motif de remplissage pour la forme.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getGradientFill() {#getGradientFill--}
```
public GradientFill getGradientFill()
```


Contient les valeurs actuelles de formatage du remplissage en dégradé pour la forme

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getShapeShdwBlur() {#getShapeShdwBlur--}
```
public DoubleValue getShapeShdwBlur()
```


Spécifie la taille du flou d'ombre d'une forme. Impossible de dessiner le flou pour le moment, mais il est possible d'analyser le fichier vsdx maintenant.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwObliqueAngle() {#getShapeShdwObliqueAngle--}
```
public DoubleValue getShapeShdwObliqueAngle()
```


Spécifie l'angle de direction oblique de l'ombre d'une forme.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetX() {#getShapeShdwOffsetX--}
```
public DoubleValue getShapeShdwOffsetX()
```


Détermine la distance, en unités de page, à laquelle l'ombre d'une forme est décalée horizontalement par rapport à la forme.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetY() {#getShapeShdwOffsetY--}
```
public DoubleValue getShapeShdwOffsetY()
```


Détermine la distance, en unités de page, à laquelle l'ombre d'une forme est décalée verticalement par rapport à la forme.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwScaleFactor() {#getShapeShdwScaleFactor--}
```
public DoubleValue getShapeShdwScaleFactor()
```


Spécifie le pourcentage selon lequel l'ombre d'une forme peut être agrandie ou réduite.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwShow() {#getShapeShdwShow--}
```
public ShapeShdwShow getShapeShdwShow()
```


Spécifie le type d'ombre pour une forme.

**Returns:**
[ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow)
### getShapeShdwType() {#getShapeShdwType--}
```
public ShapeShdwType getShapeShdwType()
```


Spécifie le type d'ombre pour une forme.

**Returns:**
[ShapeShdwType](../../com.aspose.diagram/shapeshdwtype)
### getShdwBkgnd() {#getShdwBkgnd--}
```
public ColorValue getShdwBkgnd()
```


Spécifie la couleur utilisée pour l'arrière-plan (remplissage) du motif de remplissage de l'ombre portée de la forme.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwBkgndTrans() {#getShdwBkgndTrans--}
```
public DoubleValue getShdwBkgndTrans()
```


Spécifie le niveau de transparence de l'arrière-plan (remplissage) du motif de remplissage de l'ombre portée de la forme, de 0,0 (complètement opaque) à 1,0 (complètement transparent).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwForegnd() {#getShdwForegnd--}
```
public ColorValue getShdwForegnd()
```


Spécifie la couleur utilisée pour le premier plan (trait) du motif de remplissage de l'ombre portée de la forme.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwForegndTrans() {#getShdwForegndTrans--}
```
public DoubleValue getShdwForegndTrans()
```


Spécifie le niveau de transparence du premier plan (trait) du motif de remplissage de l'ombre portée de la forme, de 0,0 (complètement opaque) à 1,0 (complètement transparent).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwPattern() {#getShdwPattern--}
```
public IntValue getShdwPattern()
```


Spécifie le motif de remplissage pour l'ombre d'une forme.

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


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/fill\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setFillBkgnd(ColorValue value) {#setFillBkgnd-com.aspose.diagram.ColorValue-}
```
public void setFillBkgnd(ColorValue value)
```


Pour la description de cette propriété, veuillez consulter [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillBkgndTrans(DoubleValue value) {#setFillBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillBkgndTrans(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillForegnd(ColorValue value) {#setFillForegnd-com.aspose.diagram.ColorValue-}
```
public void setFillForegnd(ColorValue value)
```


Pour la description de cette propriété, veuillez consulter [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillForegndTrans(DoubleValue value) {#setFillForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillForegndTrans(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillPattern(IntValue value) {#setFillPattern-com.aspose.diagram.IntValue-}
```
public void setFillPattern(IntValue value)
```


Pour la description de cette propriété, veuillez consulter [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setShapeShdwBlur(DoubleValue value) {#setShapeShdwBlur-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwBlur(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwObliqueAngle(DoubleValue value) {#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwObliqueAngle(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetX(DoubleValue value) {#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetX(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetY(DoubleValue value) {#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetY(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwScaleFactor(DoubleValue value) {#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwScaleFactor(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwShow(ShapeShdwShow value) {#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-}
```
public void setShapeShdwShow(ShapeShdwShow value)
```


Pour la description de cette propriété, veuillez consulter [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow) |  |

### setShapeShdwType(ShapeShdwType value) {#setShapeShdwType-com.aspose.diagram.ShapeShdwType-}
```
public void setShapeShdwType(ShapeShdwType value)
```


Pour la description de cette propriété, veuillez consulter [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ShapeShdwType](../../com.aspose.diagram/shapeshdwtype) |  |

### setShdwBkgnd(ColorValue value) {#setShdwBkgnd-com.aspose.diagram.ColorValue-}
```
public void setShdwBkgnd(ColorValue value)
```


Pour la description de cette propriété, veuillez consulter [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwBkgndTrans(DoubleValue value) {#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwBkgndTrans(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwForegnd(ColorValue value) {#setShdwForegnd-com.aspose.diagram.ColorValue-}
```
public void setShdwForegnd(ColorValue value)
```


Pour la description de cette propriété, veuillez consulter [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwForegndTrans(DoubleValue value) {#setShdwForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwForegndTrans(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwPattern(IntValue value) {#setShdwPattern-com.aspose.diagram.IntValue-}
```
public void setShdwPattern(IntValue value)
```


Pour la description de cette propriété, veuillez consulter [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--)

**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

