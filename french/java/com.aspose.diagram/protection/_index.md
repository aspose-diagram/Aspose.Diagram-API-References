---
title: Protection
second_title: Référence API d'Aspose.Diagram pour Java
description: Le verrouillage aide à prévenir les modifications involontaires de la forme mais n'empêche pas Microsoft Visio de réinitialiser les valeurs dans d'autres circonstances.
type: docs
weight: 312
url: /fr/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

Le verrouillage aide à prévenir les modifications involontaires de la forme, mais n’empêche pas Microsoft Visio de réinitialiser les valeurs dans d’autres circonstances. Il ne protège pas non plus contre les modifications effectuées dans la fenêtre ShapeSheet.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getLockAspect()](#getLockAspect--) | Spécifie si le ratio d'aspect de la forme est verrouillé. |
| [getLockBegin()](#getLockBegin--) | Spécifie si le point de départ d'une forme 1-D est verrouillé à un emplacement spécifique. |
| [getLockCalcWH()](#getLockCalcWH--) | Spécifie si le rectangle de sélection d'une forme est verrouillé de sorte qu'il ne puisse pas être recalculé lorsqu'un sommet est modifié ou qu'un type d'élément est changé dans l'élément Geom. |
| [getLockCrop()](#getLockCrop--) | Spécifie si un objet externe est verrouillé contre le rognage avec l'outil Crop dans Microsoft Visio. |
| [getLockCustProp()](#getLockCustProp--) | Détermine si l'utilisateur peut ajouter, supprimer ou modifier des propriétés personnalisées dans l'interface utilisateur (UI) en utilisant la boîte de dialogue Définir des propriétés personnalisées. |
| [getLockDelete()](#getLockDelete--) | Spécifie si une forme est verrouillée contre la suppression. |
| [getLockEnd()](#getLockEnd--) | Spécifie si le point final d'une forme 1-D est verrouillé à un emplacement spécifique. |
| [getLockFormat()](#getLockFormat--) | Spécifie si le formatage d'une forme est verrouillé de sorte qu'il ne puisse pas être modifié. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Autorise une sous-forme à bloquer les changements de formatage appliqués à une forme de groupe parent dans l'interface utilisateur de Visio et qui, autrement, se répercuteraient sur les formes de groupe individuelles. |
| [getLockGroup()](#getLockGroup--) | Spécifie si un groupe est verrouillé de sorte qu'il ne puisse pas être dissocié. |
| [getLockHeight()](#getLockHeight--) | Spécifie si la hauteur de la forme est verrouillée. |
| [getLockMoveX()](#getLockMoveX--) | Spécifie si la position horizontale de la forme est verrouillée de sorte qu'elle ne puisse pas être déplacée horizontalement. |
| [getLockMoveY()](#getLockMoveY--) | Spécifie si la position verticale de la forme est verrouillée de sorte qu'elle ne puisse pas être déplacée verticalement. |
| [getLockRotate()](#getLockRotate--) | Spécifie si la forme est verrouillée contre la rotation avec l'outil Rotation ou les commandes Rotation à gauche ou Rotation à droite dans Microsoft Visio. |
| [getLockSelect()](#getLockSelect--) | Spécifie si le rectangle de sélection d'une forme est verrouillé de sorte qu'il ne puisse pas être recalculé lorsqu'un sommet est modifié ou qu'un type d'élément est changé dans l'élément Geom. |
| [getLockTextEdit()](#getLockTextEdit--) | Spécifie si le texte d'une forme est verrouillé de sorte qu'il ne puisse pas être modifié. |
| [getLockThemeColors()](#getLockThemeColors--) | Empêche les utilisateurs d'appliquer des couleurs de thème à la forme. |
| [getLockThemeEffects()](#getLockThemeEffects--) | Empêche les utilisateurs d'appliquer des effets de thème à la forme. |
| [getLockVtxEdit()](#getLockVtxEdit--) | Spécifie si les sommets d'une forme sont verrouillés de sorte qu'ils ne puissent pas être modifiés avec les outils de la barre d'outils. |
| [getLockWidth()](#getLockWidth--) | Spécifie si la largeur de la forme est verrouillée afin qu'elle reste inchangée lorsque la forme est redimensionnée. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/protection\#getDel--) |
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
### getDel() {#getDel--}
```
public int getDel()
```


Un indicateur indiquant si l'élément a été supprimé localement. Une valeur de 1 indique que l'élément a été supprimé localement.

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


Spécifie si le rapport d'aspect de la forme est verrouillé. Si verrouillé, la forme ne peut être redimensionnée que proportionnellement ; elle ne peut pas être redimensionnée dans une seule dimension.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


Spécifie si le point de départ d'une forme 1-D est verrouillé à un emplacement spécifique.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


Spécifie si le rectangle de sélection d'une forme est verrouillé de sorte qu'il ne puisse pas être recalculé lorsqu'un sommet est modifié ou qu'un type d'élément est changé dans l'élément Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Spécifie si un objet externe est verrouillé contre le rognage avec l'outil Crop dans Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


Détermine si l'utilisateur peut ajouter, supprimer ou modifier des propriétés personnalisées dans l'interface utilisateur (UI) en utilisant la boîte de dialogue Définir des propriétés personnalisées.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


Spécifie si une forme est verrouillée contre la suppression.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


Spécifie si le point final d'une forme 1-D est verrouillé à un emplacement spécifique.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


Spécifie si le formatage d'une forme est verrouillé afin qu'il ne puisse pas être modifié. Plus précisément, cet élément protège contre la modification du texte, du trait et du remplissage, ou contre le changement de l'élément Style dont la forme hérite.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Autorise une sous-forme à bloquer les changements de formatage appliqués à une forme de groupe parent dans l'interface utilisateur de Visio et qui, autrement, se répercuteraient sur les formes de groupe individuelles.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


Spécifie si un groupe est verrouillé de sorte qu'il ne puisse pas être dissocié.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


Spécifie si la hauteur de la forme est verrouillée. Si verrouillée, sa hauteur reste inchangée lorsque la forme est redimensionnée.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


Spécifie si la position horizontale de la forme est verrouillée de sorte qu'elle ne puisse pas être déplacée horizontalement.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


Spécifie si la position verticale de la forme est verrouillée de sorte qu'elle ne puisse pas être déplacée verticalement.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Spécifie si la forme est verrouillée contre la rotation avec l'outil Rotation ou les commandes Rotation à gauche ou Rotation à droite dans Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


Spécifie si le rectangle de sélection d'une forme est verrouillé de sorte qu'il ne puisse pas être recalculé lorsqu'un sommet est modifié ou qu'un type d'élément est changé dans l'élément Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


Spécifie si le texte d'une forme est verrouillé de sorte qu'il ne puisse pas être modifié. Cependant, le texte peut toujours être formaté en appliquant un style, en utilisant les options Style dans l'onglet Police de la boîte de dialogue Texte.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


Empêche les utilisateurs d'appliquer des couleurs de thème à la forme.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


Empêche les utilisateurs d'appliquer des effets de thème à la forme.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


Spécifie si les sommets d'une forme sont verrouillés de sorte qu'ils ne puissent pas être modifiés avec les outils de la barre d'outils.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


Spécifie si la largeur de la forme est verrouillée afin qu'elle reste inchangée lorsque la forme est redimensionnée.

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


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/protection\#getDel--)

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

