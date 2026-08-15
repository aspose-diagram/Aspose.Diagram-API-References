---
title: Disposition
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des éléments qui contrôlent le placement des formes et les paramètres de routage des connecteurs.
type: docs
weight: 215
url: /fr/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

Contient des éléments qui contrôlent le placement des formes et les paramètres de routage des connecteurs.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | Détermine quand un connecteur redirige. |
| [getConLineJumpCode()](#getConLineJumpCode--) | Détermine si un connecteur saute lorsque deux connecteurs se croisent, |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | Détermine la direction du saut de ligne pour les sauts de ligne se produisant sur un segment horizontal d'un connecteur dynamique. |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | Détermine la direction du saut de ligne pour les sauts de ligne se produisant sur un segment vertical d'un connecteur dynamique. |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | Détermine le style du saut de ligne pour les sauts de ligne sur un connecteur dynamique. |
| [getConLineRouteExt()](#getConLineRouteExt--) | Détermine l'apparence d'un connecteur. |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getDisplayLevel()](#getDisplayLevel--) | Détermine la bande de niveau d'affichage (l'intervalle relatif du groupement Z-order) de la forme. |
| [getRelationships()](#getRelationships--) | Stocke les relations entre les conteneurs, les listes, les légendes et les formes. |
| [getShapeFixedCode()](#getShapeFixedCode--) | Spécifie le comportement de placement pour une forme positionnable. |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | Spécifie si les formes placables peuvent être placées au-dessus d'une forme lorsqu'un utilisateur sélectionne Disposer les formes (menu Formes). |
| [getShapePermeableX()](#getShapePermeableX--) | Spécifie si un connecteur peut être acheminé horizontalement à travers une forme. |
| [getShapePermeableY()](#getShapePermeableY--) | Spécifie si un connecteur peut être acheminé verticalement à travers une forme. |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | Spécifie comment une forme positionnable se retourne et/ou pivote sur la page lorsqu'un utilisateur sélectionne Disposer les formes (menu Formes). |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | Détermine le style de placement pour les enfants. |
| [getShapePlowCode()](#getShapePlowCode--) | Spécifie si une forme positionnable s'éloigne lorsque vous faites glisser une autre forme positionnable près de la forme sur la page de dessin. |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | Spécifie le style de routage et la direction d'un connecteur sur la page de dessin. |
| [getShapeSplit()](#getShapeSplit--) | Détermine si cette forme peut diviser les formes qui sont divisibles. |
| [getShapeSplittable()](#getShapeSplittable--) | Détermine si cette forme 1-D peut être divisée. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | Pour la description de cette propriété, veuillez consulter [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


Détermine quand un connecteur redirige.

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


Détermine si un connecteur saute lorsque deux connecteurs se croisent,

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


Détermine la direction du saut de ligne pour les sauts de ligne se produisant sur un segment horizontal d'un connecteur dynamique.

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


Détermine la direction du saut de ligne pour les sauts de ligne se produisant sur un segment vertical d'un connecteur dynamique.

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


Détermine le style du saut de ligne pour les sauts de ligne sur un connecteur dynamique.

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


Détermine l'apparence d'un connecteur.

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


Un indicateur indiquant si l'élément a été supprimé localement. Une valeur de 1 indique que l'élément a été supprimé localement.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


Détermine la bande de niveau d'affichage (l'intervalle relatif du groupement Z-order) de la forme.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


Stocke les relations entre les conteneurs, les listes, les légendes et les formes.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


Spécifie le comportement de placement pour une forme positionnable.

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


Spécifie si les formes placables peuvent être placées au-dessus d'une forme lorsqu'un utilisateur sélectionne Disposer les formes (menu Formes).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


Spécifie si un connecteur peut être acheminé horizontalement à travers une forme.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


Spécifie si un connecteur peut être acheminé verticalement à travers une forme.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


Spécifie comment une forme positionnable se retourne et/ou pivote sur la page lorsqu'un utilisateur sélectionne Disposer les formes (menu Formes).

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


Détermine le style de placement pour les enfants.

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


Spécifie si une forme positionnable s'éloigne lorsque vous faites glisser une autre forme positionnable près de la forme sur la page de dessin.

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


Spécifie le style de routage et la direction d'un connecteur sur la page de dessin.

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


Détermine si cette forme peut diviser les formes qui sont divisibles.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


Détermine si cette forme 1-D peut être divisée.

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


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


Pour la description de cette propriété, veuillez consulter [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| Paramètre | Type | Description |
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

