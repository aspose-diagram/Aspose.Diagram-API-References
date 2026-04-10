---
title: Line
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des éléments spécifiant les informations de positionnement général d'une forme.
type: docs
weight: 221
url: /fr/java/com.aspose.diagram/line/
---

**Inheritance:**
java.lang.Object
```
public class Line
```

Contient des éléments spécifiant les informations de positionnement général d'une forme.
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginArrow()](#getBeginArrow--) | Indique si une ligne possède une pointe de flèche ou un autre format d'extrémité de ligne à son premier sommet. |
| [getBeginArrowSize()](#getBeginArrowSize--) | Détermine la taille de la pointe de flèche au début de la ligne. |
| [getClass()](#getClass--) |  |
| [getCompoundType()](#getCompoundType--) | Spécifie le CompoundType de ligne de la forme. |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getEndArrow()](#getEndArrow--) | Indique si une ligne possède une pointe de flèche ou un autre format d'extrémité de ligne à son dernier sommet. |
| [getEndArrowSize()](#getEndArrowSize--) | Spécifie la taille de la pointe de flèche à la fin de la ligne. |
| [getGradientLine()](#getGradientLine--) | Contient les valeurs actuelles de formatage de ligne en dégradé pour la forme |
| [getLineCap()](#getLineCap--) | Spécifie si une ligne a des extrémités arrondies ou carrées. |
| [getLineColor()](#getLineColor--) | Spécifie la couleur de ligne de la forme. |
| [getLineColorTrans()](#getLineColorTrans--) | Spécifie le niveau de transparence de la couleur de ligne d'une forme, de 0 (opaque) à 1 (complètement transparent). |
| [getLinePattern()](#getLinePattern--) | Spécifie le motif de ligne de la forme |
| [getLineWeight()](#getLineWeight--) | Spécifie le poids de ligne d'une forme. |
| [getRounding()](#getRounding--) | Spécifie le rayon de l'arc d'arrondi appliqué là où deux segments contigus d'un chemin se rejoignent. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBeginArrow(IntValue value)](#setBeginArrow-com.aspose.diagram.IntValue-) | Pour la description de cette propriété, veuillez consulter [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--) |
| [setBeginArrowSize(ArrowSize value)](#setBeginArrowSize-com.aspose.diagram.ArrowSize-) | Pour la description de cette propriété, veuillez consulter [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--) |
| [setCompoundType(CompoundType value)](#setCompoundType-com.aspose.diagram.CompoundType-) | Pour la description de cette propriété, veuillez consulter [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--) |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/line\#getDel--) |
| [setEndArrow(IntValue value)](#setEndArrow-com.aspose.diagram.IntValue-) | Pour la description de cette propriété, veuillez consulter [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--) |
| [setEndArrowSize(ArrowSize value)](#setEndArrowSize-com.aspose.diagram.ArrowSize-) | Pour la description de cette propriété, veuillez consulter [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--) |
| [setLineCap(BoolValue value)](#setLineCap-com.aspose.diagram.BoolValue-) | Pour la description de cette propriété, veuillez consulter [getLineCap()](../../com.aspose.diagram/line\#getLineCap--) |
| [setLineColor(ColorValue value)](#setLineColor-com.aspose.diagram.ColorValue-) | Pour la description de cette propriété, veuillez consulter [getLineColor()](../../com.aspose.diagram/line\#getLineColor--) |
| [setLineColorTrans(DoubleValue value)](#setLineColorTrans-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--) |
| [setLinePattern(IntValue value)](#setLinePattern-com.aspose.diagram.IntValue-) | Pour la description de cette propriété, veuillez consulter [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--) |
| [setLineWeight(DoubleValue value)](#setLineWeight-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--) |
| [setRounding(DoubleValue value)](#setRounding-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getRounding()](../../com.aspose.diagram/line\#getRounding--) |
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
### getBeginArrow() {#getBeginArrow--}
```
public IntValue getBeginArrow()
```


Indique si une ligne possède une pointe de flèche ou un autre format d'extrémité de ligne à son premier sommet. Saisissez un nombre de 0 à 45 ou la fonction USE avec le nom d'une extrémité de ligne personnalisée.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBeginArrowSize() {#getBeginArrowSize--}
```
public ArrowSize getBeginArrowSize()
```


Détermine la taille de la pointe de flèche au début de la ligne. Saisissez un nombre de 0 à 6.

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


Spécifie le CompoundType de ligne de la forme.

**Returns:**
[CompoundType](../../com.aspose.diagram/compoundtype)
### getDel() {#getDel--}
```
public int getDel()
```


Un indicateur indiquant si l'élément a été supprimé localement. Une valeur de 1 indique que l'élément a été supprimé localement.

**Returns:**
int
### getEndArrow() {#getEndArrow--}
```
public IntValue getEndArrow()
```


Indique si une ligne possède une pointe de flèche ou un autre format d'extrémité de ligne à son dernier sommet.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getEndArrowSize() {#getEndArrowSize--}
```
public ArrowSize getEndArrowSize()
```


Spécifie la taille de la pointe de flèche à la fin de la ligne.

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getGradientLine() {#getGradientLine--}
```
public GradientFill getGradientLine()
```


Contient les valeurs actuelles de formatage de ligne en dégradé pour la forme

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getLineCap() {#getLineCap--}
```
public BoolValue getLineCap()
```


Spécifie si une ligne a des extrémités arrondies ou carrées.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineColor() {#getLineColor--}
```
public ColorValue getLineColor()
```


Spécifie la couleur de ligne de la forme.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getLineColorTrans() {#getLineColorTrans--}
```
public DoubleValue getLineColorTrans()
```


Spécifie le niveau de transparence de la couleur de ligne d'une forme, de 0 (opaque) à 1 (complètement transparent). La valeur par défaut est 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLinePattern() {#getLinePattern--}
```
public IntValue getLinePattern()
```


Spécifie le motif de ligne de la forme

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLineWeight() {#getLineWeight--}
```
public DoubleValue getLineWeight()
```


Spécifie l'épaisseur de ligne d'une forme. L'épaisseur de ligne est indépendante de l'échelle du dessin. Si le dessin est mis à l'échelle, l'épaisseur de ligne reste la même.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRounding() {#getRounding--}
```
public DoubleValue getRounding()
```


Spécifie le rayon de l'arc d'arrondi appliqué là où deux segments contigus d'un chemin se rejoignent. Par exemple, l'arrondi peut être utilisé pour donner à un rectangle des coins arrondis.

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


Pour la description de cette propriété, veuillez consulter [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBeginArrowSize(ArrowSize value) {#setBeginArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setBeginArrowSize(ArrowSize value)
```


Pour la description de cette propriété, veuillez consulter [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setCompoundType(CompoundType value) {#setCompoundType-com.aspose.diagram.CompoundType-}
```
public void setCompoundType(CompoundType value)
```


Pour la description de cette propriété, veuillez consulter [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CompoundType](../../com.aspose.diagram/compoundtype) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/line\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEndArrow(IntValue value) {#setEndArrow-com.aspose.diagram.IntValue-}
```
public void setEndArrow(IntValue value)
```


Pour la description de cette propriété, veuillez consulter [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setEndArrowSize(ArrowSize value) {#setEndArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setEndArrowSize(ArrowSize value)
```


Pour la description de cette propriété, veuillez consulter [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setLineCap(BoolValue value) {#setLineCap-com.aspose.diagram.BoolValue-}
```
public void setLineCap(BoolValue value)
```


Pour la description de cette propriété, veuillez consulter [getLineCap()](../../com.aspose.diagram/line\#getLineCap--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setLineColor(ColorValue value) {#setLineColor-com.aspose.diagram.ColorValue-}
```
public void setLineColor(ColorValue value)
```


Pour la description de cette propriété, veuillez consulter [getLineColor()](../../com.aspose.diagram/line\#getLineColor--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setLineColorTrans(DoubleValue value) {#setLineColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setLineColorTrans(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLinePattern(IntValue value) {#setLinePattern-com.aspose.diagram.IntValue-}
```
public void setLinePattern(IntValue value)
```


Pour la description de cette propriété, veuillez consulter [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLineWeight(DoubleValue value) {#setLineWeight-com.aspose.diagram.DoubleValue-}
```
public void setLineWeight(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRounding(DoubleValue value) {#setRounding-com.aspose.diagram.DoubleValue-}
```
public void setRounding(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getRounding()](../../com.aspose.diagram/line\#getRounding--)

**Parameters:**
| Paramètre | Type | Description |
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

