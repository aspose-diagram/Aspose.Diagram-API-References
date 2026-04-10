---
title: RelEllipticalArcTo
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des éléments qui spécifient des informations sur un arc elliptique.Les coordonnées sont spécifiées comme coordonnées relatives.
type: docs
weight: 318
url: /fr/java/com.aspose.diagram/relellipticalarcto/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class RelEllipticalArcTo extends Coordinate
```

Contient des éléments qui spécifient des informations sur un arc elliptique.Les coordonnées sont spécifiées comme coordonnées relatives.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RelEllipticalArcTo()](#RelEllipticalArcTo--) | Crée une instance de la classe [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | La coordonnée x du point de contrôle de l'arc. |
| [getB()](#getB--) | La coordonnée y du point de contrôle d'un arc. |
| [getC()](#getC--) | L'angle de l'axe majeur d'un arc par rapport à l'axe x de son parent. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | Le rapport de l'axe majeur d'un arc à son axe mineur. |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getIX()](#getIX--) | L'indice basé sur zéro de l'élément au sein de son élément parent. |
| [getX()](#getX--) | La coordonnée x du sommet final d'un arc elliptique. |
| [getY()](#getY--) | La coordonnée y du sommet final d'un arc elliptique. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--) |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--) |
| [setIX(int value)](#setIX-int-) | Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelEllipticalArcTo() {#RelEllipticalArcTo--}
```
public RelEllipticalArcTo()
```


Crée une instance de la classe [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto).

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
### getA() {#getA--}
```
public DoubleValue getA()
```


La coordonnée x du point de contrôle de l'arc. Le point de contrôle est idéalement situé à mi-chemin entre les sommets de départ et d'arrivée de l'arc. Sinon, l'arc peut s'étendre à une taille extrême afin de passer par le point de contrôle, avec des résultats imprévisibles.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


La coordonnée y du point de contrôle d'un arc.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


L'angle de l'axe majeur d'un arc par rapport à l'axe x de son parent.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


Le rapport entre l'axe majeur et l'axe mineur d'un arc. Malgré le sens habituel de ces mots, l'axe majeur n'a pas besoin d'être plus grand que l'axe mineur, donc ce rapport n'a pas besoin d'être supérieur à 1. Définir cet élément à une valeur inférieure ou égale à 0 ou supérieure à 1000 peut entraîner des résultats imprévisibles.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Un indicateur indiquant si l'élément a été supprimé localement. Une valeur de 1 indique que l'élément a été supprimé localement.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basé sur zéro de l'élément au sein de son élément parent.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


La coordonnée x du sommet final d'un arc elliptique.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


La coordonnée y du sommet final d'un arc elliptique.

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--)

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

