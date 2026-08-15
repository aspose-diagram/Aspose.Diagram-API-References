---
title: PageProps
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des cellules qui contrôlent les attributs de la page tels que la largeur, la hauteur et l'échelle de la page.
type: docs
weight: 268
url: /fr/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

Contient des cellules qui contrôlent les attributs de la page, tels que la largeur, la hauteur et l'échelle de la page.
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getDrawingResizeType()](#getDrawingResizeType--) | Détermine si la page de dessin redimensionne automatiquement pour s'adapter au diagramme. |
| [getDrawingScale()](#getDrawingScale--) | Représente la valeur de l'unité de dessin dans l'échelle de dessin actuelle. |
| [getDrawingScaleType()](#getDrawingScaleType--) | Spécifie le type d'échelle de dessin à utiliser pour une page. |
| [getDrawingSizeType()](#getDrawingSizeType--) | Spécifie la taille du dessin d'une page. |
| [getInhibitSnap()](#getInhibitSnap--) | Spécifie si les formes sur une page de premier plan s'alignent sur d'autres objets de la page et sur les formes de la page d'arrière-plan. |
| [getPageHeight()](#getPageHeight--) | Spécifie la hauteur de la page en unités de dessin. |
| [getPageScale()](#getPageScale--) | Spécifie la valeur de l'unité de page par défaut dans l'échelle de dessin actuelle. |
| [getPageWidth()](#getPageWidth--) | Spécifie la largeur de la page en unités de dessin. |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | Contient un nombre qui spécifie l'angle de direction oblique lorsque le type d'ombre de page par défaut est appliqué. |
| [getShdwOffsetX()](#getShdwOffsetX--) | Spécifie la distance, en unités de page, du décalage horizontal de l'ombre portée d'une forme par rapport à la forme. |
| [getShdwOffsetY()](#getShdwOffsetY--) | Spécifie la distance, en unités de page, du décalage vertical de l'ombre portée d'une forme par rapport à la forme. |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | Spécifie le pourcentage d'agrandissement ou de réduction de l'ombre d'une forme. |
| [getShdwType()](#getShdwType--) | Indique le type d'ombre par défaut pour une page. |
| [getUIVisibility()](#getUIVisibility--) | Détermine si le nom de la page est affiché dans l'interface utilisateur (UI). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/pageprops\\#getDel--) |
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
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


Détermine si la page de dessin redimensionne automatiquement pour s'adapter au diagramme.

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


Représente la valeur de l'unité de dessin dans l'échelle de dessin actuelle. L'échelle de dessin pour la page est le rapport de l'unité de page contenue dans l'élément PageScale à l'unité de dessin. Les unités de cet élément déterminent les unités de longueur par défaut (DL) pour la page.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


Spécifie le type d'échelle de dessin à utiliser pour une page.

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


Spécifie la taille du dessin d'une page.

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


Spécifie si les formes sur une page de premier plan s'alignent sur d'autres objets de la page et sur les formes de la page d'arrière-plan.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


Spécifie la hauteur de la page en unités de dessin.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


Spécifie la valeur de l'unité de page par défaut dans l'échelle de dessin actuelle. L'échelle de dessin pour la page est le rapport de l'unité de page dans l'élément PageScale à l'unité de dessin affichée dans l'élément DrawingScale.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


Spécifie la largeur de la page en unités de dessin.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


Contient un nombre qui spécifie l'angle de direction oblique lorsque le type d'ombre de page par défaut est appliqué.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


Spécifie la distance, en unités de page, du décalage horizontal de l'ombre portée d'une forme par rapport à la forme.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


Spécifie la distance, en unités de page, du décalage vertical de l'ombre portée d'une forme par rapport à la forme.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


Spécifie le pourcentage d'agrandissement ou de réduction de l'ombre d'une forme.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


Indique le type d'ombre par défaut pour une page.

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


Détermine si le nom de la page est affiché dans l'interface utilisateur (UI). Une valeur de un indique que la page n'est pas visible ; une valeur de zéro indique que la page est visible.

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/pageprops\\#getDel--)

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

