---
title: PageLayout
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des cellules qui contrôlent les paramètres de mise en page de la page pour les formes et les connecteurs, tels que l'espacement entre toutes les formes sur la page, l'espacement entre tous les connecteurs sur la page et le style de routage pour tous les connecteurs sur la page.
type: docs
weight: 263
url: /fr/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

Contient des cellules qui contrôlent les paramètres de mise en page de la page pour les formes et les connecteurs, tels que l'espacement entre toutes les formes sur la page, l'espacement entre tous les connecteurs sur la page et le style de routage pour tous les connecteurs sur la page.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | Détermine la quantité d'espace vertical entre les formes sur la page de dessin lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin. |
| [getAvenueSizeY()](#getAvenueSizeY--) | Détermine la quantité d'espace vertical entre les formes sur la page de dessin lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin. |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | Spécifie comment les formes sont placées sur la page lorsque les formes sont disposées après que l'utilisateur a sélectionné Disposer les formes (menu Forme). |
| [getBlockSizeX()](#getBlockSizeX--) | Détermine la taille du bloc vertical, la zone dans laquelle chacune de vos formes doit s'insérer sur la page de dessin lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin. |
| [getBlockSizeY()](#getBlockSizeY--) | Détermine la quantité d'espace horizontal entre les formes sur la page de dessin lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin. |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | Détermine quelle forme est le parent lors de l'utilisation des formes par les poignées de contrôle. |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getDynamicsOff()](#getDynamicsOff--) | Spécifie si les formes placables se déplacent et si les connecteurs sont reroutés autour des autres formes et connecteurs sur la page de dessin. |
| [getEnableGrid()](#getEnableGrid--) | Spécifie si Microsoft Visio dispose les formes en fonction d'une grille interne de la page lorsque l'utilisateur sélectionne Lay Out Shapes (menu Shape). |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | Spécifie quels connecteurs dynamiques espacer s'ils sont routés les uns sur les autres. |
| [getLineAdjustTo()](#getLineAdjustTo--) | Spécifie quels connecteurs dynamiques aligner les uns sur les autres s'ils sont routés les uns sur les autres. |
| [getLineJumpCode()](#getLineJumpCode--) | Spécifie le style de saut de ligne pour tous les connecteurs de la page de dessin qui n'ont pas de style de saut de ligne local. |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | Spécifie la taille des sauts de ligne sur les segments horizontaux des connecteurs dynamiques sur la page, en pourcentage de la valeur de l'élément LineToLineX (qui spécifie l'écart horizontal entre tous les connecteurs sur la page de dessin). |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | Spécifie la taille des sauts de ligne sur les segments verticaux des connecteurs dynamiques sur la page, en pourcentage de la valeur de l'élément LineToLineY (qui spécifie l'écart vertical entre tous les connecteurs sur la page de dessin). |
| [getLineJumpStyle()](#getLineJumpStyle--) | Spécifie la direction des sauts de ligne sur les segments horizontaux des connecteurs dynamiques sur la page de dessin pour lesquels vous n'avez pas appliqué de direction de saut locale. |
| [getLineRouteExt()](#getLineRouteExt--) | Spécifie l'apparence par défaut de tous les connecteurs sur une page. |
| [getLineToLineX()](#getLineToLineX--) | Spécifie l'écart horizontal minimum entre les connecteurs dynamiques sur la page de dessin. |
| [getLineToLineY()](#getLineToLineY--) | Spécifie l'écart vertical minimum entre les connecteurs dynamiques sur la page de dessin. |
| [getLineToNodeX()](#getLineToNodeX--) | Spécifie l'écart vertical minimum entre les connecteurs dynamiques et les formes sur la page de dessin. |
| [getLineToNodeY()](#getLineToNodeY--) | Détermine la taille du bloc horizontal, la zone dans laquelle chacune de vos formes doit s'insérer sur la page de dessin lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin. |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | Spécifie la direction des sauts de ligne sur les connecteurs dynamiques verticaux sur la page de dessin pour lesquels vous n'avez pas appliqué de direction de saut locale. |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | Spécifie l'écart horizontal minimum entre les connecteurs dynamiques et les formes sur la page de dessin. |
| [getPageShapeSplit()](#getPageShapeSplit--) | Indique si les formes sur la page peuvent être séparées automatiquement. |
| [getPlaceDepth()](#getPlaceDepth--) | Spécifie si les formes placables s'éloignent lorsque l'utilisateur fait glisser une forme placable près d'une autre forme placable sur la page de dessin. |
| [getPlaceFlip()](#getPlaceFlip--) | Spécifie comment les formes placables sont retournées et/ou pivotées sur une page lorsque les formes sont disposées à l'aide de la commande Disposer les formes dans Microsoft Visio. |
| [getPlaceStyle()](#getPlaceStyle--) | Spécifie le style de routage et la direction pour tous les connecteurs dynamiques sur la page de dessin qui n’ont pas de style de routage local. |
| [getPlowCode()](#getPlowCode--) | Détermine les connecteurs dynamiques auxquels vous souhaitez ajouter des sauts. |
| [getResizePage()](#getResizePage--) | Spécifie s'il faut agrandir la page pour englober le dessin après que l'utilisateur ait sélectionné Lay Out Shapes (menu Shapes). |
| [getRouteStyle()](#getRouteStyle--) | Pour un dessin disposé automatiquement, spécifie la méthode selon laquelle le dessin est analysé avant de créer la mise en page et détermine le type de mise en page. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/pagelayout\#getDel--) |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


Détermine la quantité d'espace vertical entre les formes sur la page de dessin lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


Détermine la quantité d'espace vertical entre les formes sur la page de dessin lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


Spécifie comment les formes sont placées sur la page lorsque les formes sont disposées après que l'utilisateur a sélectionné Disposer les formes (menu Forme).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


Détermine la taille du bloc vertical, la zone dans laquelle chacune de vos formes doit s'insérer sur la page de dessin lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


Détermine la quantité d'espace horizontal entre les formes sur la page de dessin lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


Détermine quelle forme est le parent lors de l'utilisation des formes par les poignées de contrôle. Cet élément définit le comportement de toutes les formes sur la page de dessin.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Un indicateur indiquant si l'élément a été supprimé localement. Une valeur de 1 indique que l'élément a été supprimé localement.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


Spécifie si les formes placables se déplacent et si les connecteurs sont reroutés autour des autres formes et connecteurs sur la page de dessin.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


Spécifie si Microsoft Visio dispose les formes en fonction d'une grille interne de la page lorsque l'utilisateur sélectionne Lay Out Shapes (menu Shape).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


Spécifie quels connecteurs dynamiques espacer s'ils sont routés les uns sur les autres.

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


Spécifie quels connecteurs dynamiques aligner les uns sur les autres s'ils sont routés les uns sur les autres.

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


Spécifie le style de saut de ligne pour tous les connecteurs de la page de dessin qui n'ont pas de style de saut de ligne local.

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


Spécifie la taille des sauts de ligne sur les segments horizontaux des connecteurs dynamiques sur la page, en pourcentage de la valeur de l'élément LineToLineX (qui spécifie l'écart horizontal entre tous les connecteurs sur la page de dessin). La valeur de cet élément varie de 0 à 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


Spécifie la taille des sauts de ligne sur les segments verticaux des connecteurs dynamiques sur la page, en pourcentage de la valeur de l'élément LineToLineY (qui spécifie l'écart vertical entre tous les connecteurs sur la page de dessin). Cet élément peut contenir une valeur de 0 à 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


Spécifie la direction des sauts de ligne sur les segments horizontaux des connecteurs dynamiques sur la page de dessin pour lesquels vous n'avez pas appliqué de direction de saut locale.

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


Spécifie l'apparence par défaut de tous les connecteurs sur une page.

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


Spécifie l'écart horizontal minimum entre les connecteurs dynamiques sur la page de dessin.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


Spécifie l'écart vertical minimum entre les connecteurs dynamiques sur la page de dessin.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


Spécifie l'écart vertical minimum entre les connecteurs dynamiques et les formes sur la page de dessin.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


Détermine la taille du bloc horizontal, la zone dans laquelle chacune de vos formes doit s'insérer sur la page de dessin lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


Spécifie la direction des sauts de ligne sur les connecteurs dynamiques verticaux sur la page de dessin pour lesquels vous n'avez pas appliqué de direction de saut locale.

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


Spécifie l'écart horizontal minimum entre les connecteurs dynamiques et les formes sur la page de dessin.

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


Indique si les formes sur la page peuvent être séparées automatiquement.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


Spécifie si les formes placables s'éloignent lorsque l'utilisateur fait glisser une forme placable près d'une autre forme placable sur la page de dessin.

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


Spécifie comment les formes placables sont retournées et/ou pivotées sur une page lorsque les formes sont disposées à l'aide de la commande Lay Out Shapes dans Microsoft Visio. Les valeurs hexadécimales suivantes sont autorisées.

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


Spécifie le style de routage et la direction pour tous les connecteurs dynamiques sur la page de dessin qui n’ont pas de style de routage local.

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


Détermine les connecteurs dynamiques auxquels vous souhaitez ajouter des sauts.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


Spécifie s'il faut agrandir la page pour englober le dessin après que l'utilisateur ait sélectionné Lay Out Shapes (menu Shapes).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


Pour un dessin disposé automatiquement, spécifie la méthode selon laquelle le dessin est analysé avant de créer la mise en page et détermine le type de mise en page.

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/pagelayout\#getDel--)

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

