---
title: Para
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient les éléments de mise en forme des paragraphes pour le texte des formes, tels que les retraits, l'espacement des lignes, les puces et l'alignement horizontal des paragraphes.
type: docs
weight: 274
url: /fr/java/com.aspose.diagram/para/
---

**Inheritance:**
java.lang.Object
```
public class Para
```

Contient les éléments de mise en forme de paragraphe pour le texte de la forme, tels que les retraits, l'espacement des lignes, les puces et l'alignement horizontal des paragraphes.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Para()](#Para--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBullet()](#getBullet--) | Détermine le style de puce. |
| [getBulletFont()](#getBulletFont--) | Représente le numéro de la police utilisée pour formater le texte lorsqu'une chaîne de puce personnalisée est spécifiée et que la valeur de l'élément Bullet est différente de zéro. |
| [getBulletFontSize()](#getBulletFontSize--) | Spécifie la taille d'une puce. |
| [getBulletStr()](#getBulletStr--) | "Utilisé pour créer un style de puce personnalisé. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getFlags()](#getFlags--) | Indique si la direction du texte est de gauche à droite ou de droite à gauche. |
| [getHorzAlign()](#getHorzAlign--) | Spécifie l’alignement horizontal du texte dans le bloc de texte de la forme. |
| [getIX()](#getIX--) | L'indice basé sur zéro de l'élément au sein de son élément parent. |
| [getIndFirst()](#getIndFirst--) | Spécifie la distance à laquelle la première ligne de chaque paragraphe dans le bloc de texte de la forme est indentée par rapport au retrait gauche du paragraphe. |
| [getIndLeft()](#getIndLeft--) | Spécifie la distance à laquelle toutes les lignes de texte d'un paragraphe sont indentées par rapport à la marge gauche du bloc de texte. |
| [getIndRight()](#getIndRight--) | Spécifie la distance à laquelle toutes les lignes de texte d'un paragraphe sont indentées depuis la marge droite du bloc de texte. |
| [getLocalizeBulletFont()](#getLocalizeBulletFont--) | Spécifie si la police du puce doit être localisée (traduit dans une autre langue). |
| [getSpAfter()](#getSpAfter--) | Spécifie la quantité d'espace insérée après chaque paragraphe dans le bloc de texte de la forme. |
| [getSpBefore()](#getSpBefore--) | Spécifie la quantité d'espace insérée avant chaque paragraphe dans le bloc de texte de la forme. |
| [getSpLine()](#getSpLine--) | Spécifie la distance entre une ligne de texte et la suivante, où 100 % correspond à la hauteur d'une ligne de texte. |
| [getTextPosAfterBullet()](#getTextPosAfterBullet--) | Représente la distance entre la première ligne du paragraphe et la puce. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBullet(Bullet value)](#setBullet-com.aspose.diagram.Bullet-) | Pour la description de cette propriété, veuillez consulter [getBullet()](../../com.aspose.diagram/para\#getBullet--) |
| [setBulletFont(IntValue value)](#setBulletFont-com.aspose.diagram.IntValue-) | Pour la description de cette propriété, veuillez consulter [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--) |
| [setBulletFontSize(DoubleValue value)](#setBulletFontSize-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--) |
| [setBulletStr(Str2Value value)](#setBulletStr-com.aspose.diagram.Str2Value-) | Pour la description de cette propriété, veuillez consulter [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--) |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/para\#getDel--) |
| [setFlags(BoolValue value)](#setFlags-com.aspose.diagram.BoolValue-) | Pour la description de cette propriété, veuillez consulter [getFlags()](../../com.aspose.diagram/para\#getFlags--) |
| [setHorzAlign(HorzAlign value)](#setHorzAlign-com.aspose.diagram.HorzAlign-) | Pour la description de cette propriété, veuillez consulter [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--) |
| [setIX(int value)](#setIX-int-) | Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/para\#getIX--) |
| [setIndFirst(DoubleValue value)](#setIndFirst-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--) |
| [setIndLeft(DoubleValue value)](#setIndLeft-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--) |
| [setIndRight(DoubleValue value)](#setIndRight-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getIndRight()](../../com.aspose.diagram/para\#getIndRight--) |
| [setLocalizeBulletFont(LocalizeFont value)](#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-) | Pour la description de cette propriété, veuillez consulter [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--) |
| [setSpAfter(DoubleValue value)](#setSpAfter-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--) |
| [setSpBefore(DoubleValue value)](#setSpBefore-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--) |
| [setSpLine(DoubleValue value)](#setSpLine-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getSpLine()](../../com.aspose.diagram/para\#getSpLine--) |
| [setTextPosAfterBullet(DoubleValue value)](#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-) | Pour la description de cette propriété, veuillez consulter [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Para() {#Para--}
```
public Para()
```


Constructeur.

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
### getBullet() {#getBullet--}
```
public Bullet getBullet()
```


Détermine le style de puce.

**Returns:**
[Bullet](../../com.aspose.diagram/bullet)
### getBulletFont() {#getBulletFont--}
```
public IntValue getBulletFont()
```


Représente le numéro de la police utilisée pour formater le texte lorsqu'une chaîne de puce personnalisée est spécifiée et que la valeur de l'élément Bullet est différente de zéro.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBulletFontSize() {#getBulletFontSize--}
```
public DoubleValue getBulletFontSize()
```


Spécifie la taille d'une puce.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBulletStr() {#getBulletStr--}
```
public Str2Value getBulletStr()
```


"Utilisé pour créer un style de puce personnalisé. Saisissez le style sous forme de chaîne (entre guillemets). Par exemple, vous pourriez saisir la chaîne, ""ooo."""

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getFlags() {#getFlags--}
```
public BoolValue getFlags()
```


Indique si la direction du texte est de gauche à droite ou de droite à gauche.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHorzAlign() {#getHorzAlign--}
```
public HorzAlign getHorzAlign()
```


Spécifie l’alignement horizontal du texte dans le bloc de texte de la forme.

**Returns:**
[HorzAlign](../../com.aspose.diagram/horzalign)
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basé sur zéro de l'élément au sein de son élément parent.

**Returns:**
int
### getIndFirst() {#getIndFirst--}
```
public DoubleValue getIndFirst()
```


Spécifie la distance à laquelle la première ligne de chaque paragraphe dans le bloc de texte de la forme est indentée depuis le retrait gauche du paragraphe. Cette valeur est indépendante de l'échelle du dessin. Si le dessin est mis à l'échelle, le retrait de la première ligne reste le même.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndLeft() {#getIndLeft--}
```
public DoubleValue getIndLeft()
```


Spécifie la distance à laquelle toutes les lignes de texte d'un paragraphe sont indentées depuis la marge gauche du bloc de texte. Cette valeur est indépendante de l'échelle du dessin. Si le dessin est mis à l'échelle, le retrait gauche reste le même.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndRight() {#getIndRight--}
```
public DoubleValue getIndRight()
```


Spécifie la distance à laquelle toutes les lignes de texte d'un paragraphe sont indentées depuis la marge droite du bloc de texte. Cette valeur est indépendante de l'échelle du dessin. Si le dessin est mis à l'échelle, l'indentation droite reste la même.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocalizeBulletFont() {#getLocalizeBulletFont--}
```
public LocalizeFont getLocalizeBulletFont()
```


Spécifie si la police du puce doit être localisée (traduit dans une autre langue).

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getSpAfter() {#getSpAfter--}
```
public DoubleValue getSpAfter()
```


Spécifie la quantité d'espace insérée après chaque paragraphe dans le bloc de texte de la forme.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpBefore() {#getSpBefore--}
```
public DoubleValue getSpBefore()
```


Spécifie la quantité d'espace insérée avant chaque paragraphe dans le bloc de texte de la forme.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpLine() {#getSpLine--}
```
public DoubleValue getSpLine()
```


Spécifie la distance entre une ligne de texte et la suivante, où 100 % correspond à la hauteur d'une ligne de texte.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextPosAfterBullet() {#getTextPosAfterBullet--}
```
public DoubleValue getTextPosAfterBullet()
```


Représente la distance entre la première ligne du paragraphe et la puce.

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




### setBullet(Bullet value) {#setBullet-com.aspose.diagram.Bullet-}
```
public void setBullet(Bullet value)
```


Pour la description de cette propriété, veuillez consulter [getBullet()](../../com.aspose.diagram/para\#getBullet--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Bullet](../../com.aspose.diagram/bullet) |  |

### setBulletFont(IntValue value) {#setBulletFont-com.aspose.diagram.IntValue-}
```
public void setBulletFont(IntValue value)
```


Pour la description de cette propriété, veuillez consulter [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBulletFontSize(DoubleValue value) {#setBulletFontSize-com.aspose.diagram.DoubleValue-}
```
public void setBulletFontSize(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBulletStr(Str2Value value) {#setBulletStr-com.aspose.diagram.Str2Value-}
```
public void setBulletStr(Str2Value value)
```


Pour la description de cette propriété, veuillez consulter [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/para\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setFlags(BoolValue value) {#setFlags-com.aspose.diagram.BoolValue-}
```
public void setFlags(BoolValue value)
```


Pour la description de cette propriété, veuillez consulter [getFlags()](../../com.aspose.diagram/para\#getFlags--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHorzAlign(HorzAlign value) {#setHorzAlign-com.aspose.diagram.HorzAlign-}
```
public void setHorzAlign(HorzAlign value)
```


Pour la description de cette propriété, veuillez consulter [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [HorzAlign](../../com.aspose.diagram/horzalign) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/para\#getIX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setIndFirst(DoubleValue value) {#setIndFirst-com.aspose.diagram.DoubleValue-}
```
public void setIndFirst(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndLeft(DoubleValue value) {#setIndLeft-com.aspose.diagram.DoubleValue-}
```
public void setIndLeft(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndRight(DoubleValue value) {#setIndRight-com.aspose.diagram.DoubleValue-}
```
public void setIndRight(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getIndRight()](../../com.aspose.diagram/para\#getIndRight--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocalizeBulletFont(LocalizeFont value) {#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeBulletFont(LocalizeFont value)
```


Pour la description de cette propriété, veuillez consulter [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setSpAfter(DoubleValue value) {#setSpAfter-com.aspose.diagram.DoubleValue-}
```
public void setSpAfter(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpBefore(DoubleValue value) {#setSpBefore-com.aspose.diagram.DoubleValue-}
```
public void setSpBefore(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpLine(DoubleValue value) {#setSpLine-com.aspose.diagram.DoubleValue-}
```
public void setSpLine(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getSpLine()](../../com.aspose.diagram/para\#getSpLine--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextPosAfterBullet(DoubleValue value) {#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-}
```
public void setTextPosAfterBullet(DoubleValue value)
```


Pour la description de cette propriété, veuillez consulter [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--)

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

