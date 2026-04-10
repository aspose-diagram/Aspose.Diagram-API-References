---
title: Layer
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des éléments qui définissent une couche unique et ses propriétés pour une page.
type: docs
weight: 212
url: /fr/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

Contient des éléments qui définissent une couche unique et ses propriétés pour une page.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Layer()](#Layer--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | Spécifie si une couche est active. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | L'index de la couleur dans la table des couleurs utilisé pour afficher la couche ou une valeur RVB spécifiant une couleur personnalisée qui n'est pas dans la table des couleurs (par exemple, \#ff9900). |
| [getColorTrans()](#getColorTrans--) | Détermine le degré de transparence de la couleur du texte d'un calque ou d'une forme, de 0 (complètement opaque) à 1 (complètement transparent). |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getGlue()](#getGlue--) | Spécifie si les formes appartenant à la couche peuvent être collées. |
| [getIX()](#getIX--) | L'indice basé sur zéro de l'élément au sein de son élément parent. |
| [getLock()](#getLock--) | Spécifie si les formes appartenant à la couche sont verrouillées contre la sélection ou la modification. |
| [getName()](#getName--) | L'élément Name spécifie le nom d'une couche. |
| [getNameUniv()](#getNameUniv--) | Spécifie le nom universel d'une couche. |
| [getPrint()](#getPrint--) | Spécifie si les formes appartenant à la couche sont imprimées lorsque le dessin est imprimé. |
| [getSnap()](#getSnap--) | Spécifie si d'autres formes peuvent s'accrocher aux formes assignées à la couche. |
| [getStatus()](#getStatus--) | Spécifie si la couche est une couche valide pour un document. |
| [getVisible()](#getVisible--) | Spécifie si les formes appartenant à la couche sont visibles sur la page du dessin. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | Un indicateur indiquant si l'élément a été vérifié localement. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | Pour la description de cette propriété, veuillez consulter [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
```


Constructeur.

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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


Spécifie si une couche est active. Les formes qui ne sont pas préassignées à des couches sont assignées à la ou les couches actives lorsqu'elles sont déposées sur la page du dessin.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


L'index de la couleur dans la table des couleurs utilisé pour afficher la couche ou une valeur RVB spécifiant une couleur personnalisée qui n'est pas dans la table des couleurs (par exemple, \#ff9900).

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


Détermine le degré de transparence de la couleur du texte d'un calque ou d'une forme, de 0 (complètement opaque) à 1 (complètement transparent).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


Un indicateur indiquant si l'élément a été supprimé localement. Une valeur de 1 indique que l'élément a été supprimé localement.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


Spécifie si les formes appartenant à la couche peuvent être collées.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basé sur zéro de l'élément au sein de son élément parent.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


Spécifie si les formes appartenant à la couche sont verrouillées contre la sélection ou la modification.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


L'élément Name spécifie le nom d'une couche.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


Spécifie le nom universel d'une couche.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


Spécifie si les formes appartenant à la couche sont imprimées lorsque le dessin est imprimé.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


Spécifie si d'autres formes peuvent s'accrocher aux formes assignées à la couche. Les formes assignées à la couche peuvent s'accrocher à d'autres formes, mais les autres formes ne peuvent pas s'y accrocher.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


Spécifie si la couche est une couche valide pour un document.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


Spécifie si les formes appartenant à la couche sont visibles sur la page du dessin.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


Un indicateur indiquant si l'élément a été vérifié localement. Une valeur de 1 indique que l'élément a été vérifié localement.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


Pour la description de cette propriété, veuillez consulter [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/layer\#getIX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

