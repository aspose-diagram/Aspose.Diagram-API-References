---
title: CoordinateCollection
second_title: Référence API d'Aspose.Diagram pour Java
description: Collection de coordonnées.
type: docs
weight: 102
url: /fr/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

Collection de coordonnées.
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | Ajoute l'objet ArcTo dans la collection. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | Ajoute l'objet Coordinate dans la collection. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | Ajoute l'objet Ellipse dans la collection. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | Ajoute l'objet EllipticalArcTo dans la collection. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | Ajoute l'objet InfiniteLine dans la collection. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | Ajoute l'objet LineTo dans la collection. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | Ajoute l'objet MoveTo dans la collection. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | Ajoute l'objet NURBSTo dans la collection. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | Ajoute l'objet PolylineTo dans la collection. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | Ajoute l'objet RelCubBezTo dans la collection. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | Ajoutez l'objet RelEllipticalArcTo à la collection. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | Ajoutez l'objet RelLineTo à la collection. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | Ajoutez l'objet RelMoveTo à la collection. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | Ajoutez l'objet RelQuadBezTo à la collection. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | Ajoutez l'objet SplineKnot à la collection. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | Ajoutez l'objet SplineStart à la collection. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Obtient l'élément à l'index spécifié. |
| [getArcToCol()](#getArcToCol--) | Contient les coordonnées x et y ainsi que la flèche d'un arc circulaire représentés respectivement par les éléments X, Y et A. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [getEllipseCol()](#getEllipseCol--) | Contient des éléments spécifiant les coordonnées x et y du point central de l'ellipse ainsi que deux points sur l'ellipse. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | Contient des éléments qui spécifient des informations sur un arc elliptique. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | Contient des éléments spécifiant les coordonnées x et y de deux points sur une ligne infinie. |
| [getLineToCol()](#getLineToCol--) | Contient les coordonnées x et y du sommet final d'un segment de ligne droite. |
| [getMoveToCol()](#getMoveToCol--) | Contient les coordonnées x et y du premier sommet d'une forme, ou les coordonnées x et y du premier sommet après une interruption dans un chemin. |
| [getNURBSToCol()](#getNURBSToCol--) | Contient les coordonnées x et y, la position du nœud avant‑dernier, la position du dernier poids, la position du premier nœud, la position du premier poids, ainsi que la formule d'une B‑spline rationnelle non uniforme (NURBS). |
| [getPolylineToCol()](#getPolylineToCol--) | Contient les coordonnées x et y du dernier point d'une polyligne et la formule de la polyligne. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | Contient les coordonnées x et y des points d'un RelCubBezTo. Les coordonnées sont spécifiées comme coordonnées relatives. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | Contient des éléments qui spécifient des informations sur un arc elliptique.Les coordonnées sont spécifiées comme coordonnées relatives. |
| [getRelLineToCol()](#getRelLineToCol--) | Contient les coordonnées x et y du sommet final d'un segment de ligne droite. |
| [getRelMoveToCol()](#getRelMoveToCol--) | Contient les coordonnées x et y du premier sommet d’une forme, ou les coordonnées x et y du premier sommet après une interruption dans un chemin. Les coordonnées sont spécifiées comme des coordonnées relatives. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | Contient les coordonnées x et y des points d'un RelQuadBezTo. Les coordonnées sont spécifiées comme coordonnées relatives. |
| [getSplineKnotCol()](#getSplineKnotCol--) | Contient les coordonnées x et y d'un point de contrôle d'une spline et d'un nœud de spline, représentées respectivement par les éléments X, Y et A. |
| [getSplineStartCol()](#getSplineStartCol--) | Contient les coordonnées x et y du deuxième point de contrôle d'une spline, de son deuxième nœud, de son premier nœud, du dernier nœud et du degré de la spline. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Existe un élément dans la collection. |
| [iterator()](#iterator--) | Prend en charge une itération simple sur une collection non générique. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | Supprimez l'objet ArcTo de la collection. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | Supprimez l'objet Coordinate de la collection. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | Supprimez l'objet Ellipse de la collection. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | Supprimez l'objet EllipticalArcTo de la collection. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | Supprimez l'objet InfiniteLine de la collection. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | Supprimez l'objet LineTo de la collection. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | Supprimez l'objet MoveTo de la collection. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | Supprimez l'objet NURBSTo de la collection. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | Supprimez l'objet PolylineTo de la collection. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | Supprimez l'objet RelCubBezTo de la collection. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | Supprimez l'objet RelEllipticalArcTo de la collection. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | Supprimez l'objet RelLineTo de la collection. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | Supprimez l'objet RelMoveTo de la collection. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | Supprimez l'objet RelQuadBezTo de la collection. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | Supprimez l'objet SplineKnot de la collection. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | Supprimez l'objet SplineStart de la collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


Ajoute l'objet ArcTo dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


Ajoute l'objet Coordinate dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


Ajoute l'objet Ellipse dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


Ajoute l'objet EllipticalArcTo dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


Ajoute l'objet InfiniteLine dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


Ajoute l'objet LineTo dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


Ajoute l'objet MoveTo dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


Ajoute l'objet NURBSTo dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


Ajoute l'objet PolylineTo dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


Ajoute l'objet RelCubBezTo dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


Ajoutez l'objet RelEllipticalArcTo à la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


Ajoutez l'objet RelLineTo à la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


Ajoutez l'objet RelMoveTo à la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


Ajoutez l'objet RelQuadBezTo à la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


Ajoutez l'objet SplineKnot à la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


Ajoutez l'objet SplineStart à la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Supprime tous les éléments de la collection.

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
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Obtient l'élément à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


Contient les coordonnées x et y ainsi que la flèche d'un arc circulaire représentés respectivement par les éléments X, Y et A.

**Returns:**
[ArcToCollection](../../com.aspose.diagram/arctocollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Obtient le nombre d'éléments réellement contenus dans la collection.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


Contient des éléments spécifiant les coordonnées x et y du point central de l'ellipse ainsi que deux points sur l'ellipse.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


Contient des éléments qui spécifient des informations sur un arc elliptique.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


Contient des éléments spécifiant les coordonnées x et y de deux points sur une ligne infinie. Les éléments X et Y spécifient les coordonnées x et y du premier point, et les éléments A et B spécifient les coordonnées x et y du deuxième point.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


Contient les coordonnées x et y du sommet final d'un segment de ligne droite. Ces coordonnées sont contenues respectivement dans les éléments X et Y.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


Contient les coordonnées x et y du premier sommet d'une forme, ou les coordonnées x et y du premier sommet après une interruption dans un chemin.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


Contient les coordonnées x et y, la position du deuxième nœud avant le dernier, la position du dernier poids, la position du premier nœud, la position du premier poids, ainsi que la formule d'une B-spline rationnelle non uniforme (NURBS). Ces informations sont spécifiées respectivement dans les éléments X, Y, A, B, C, D et E.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


Contient les coordonnées x et y du dernier point d'une polyligne ainsi que la formule de la polyligne. Les coordonnées sont spécifiées dans les éléments X et Y, et la formule est spécifiée dans l'élément A.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


Contient les coordonnées x et y des points d'un RelCubBezTo. Les coordonnées sont spécifiées comme coordonnées relatives.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


Contient des éléments qui spécifient des informations sur un arc elliptique.Les coordonnées sont spécifiées comme coordonnées relatives.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


Contient les coordonnées x et y du sommet final d'un segment de ligne droite. Ces coordonnées sont contenues respectivement dans les éléments X et Y.Les coordonnées sont spécifiées comme coordonnées relatives.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


Contient les coordonnées x et y du premier sommet d’une forme, ou les coordonnées x et y du premier sommet après une interruption dans un chemin. Les coordonnées sont spécifiées comme des coordonnées relatives.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


Contient les coordonnées x et y des points d'un RelQuadBezTo. Les coordonnées sont spécifiées comme coordonnées relatives.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


Contient les coordonnées x et y d'un point de contrôle d'une spline et d'un nœud de spline, représentées respectivement par les éléments X, Y et A.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


Contient les coordonnées x et y du deuxième point de contrôle d'une spline, de son deuxième nœud, de son premier nœud, du dernier nœud et du degré de la spline. Ces informations sont contenues respectivement dans les éléments X, Y, A, B, C et D.

**Returns:**
[SplineStartCollection](../../com.aspose.diagram/splinestartcollection)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExist(int index) {#isExist-int-}
```
public boolean isExist(int index)
```


Existe un élément dans la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | indice de l'élément. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Prend en charge une itération simple sur une collection non générique.

**Returns:**
java.util.Iterator -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(ArcTo item) {#remove-com.aspose.diagram.ArcTo-}
```
public void remove(ArcTo item)
```


Supprimez l'objet ArcTo de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


Supprimez l'objet Coordinate de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


Supprimez l'objet Ellipse de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


Supprimez l'objet EllipticalArcTo de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


Supprimez l'objet InfiniteLine de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


Supprimez l'objet LineTo de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


Supprimez l'objet MoveTo de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


Supprimez l'objet NURBSTo de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


Supprimez l'objet PolylineTo de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


Supprimez l'objet RelCubBezTo de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


Supprimez l'objet RelEllipticalArcTo de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


Supprimez l'objet RelLineTo de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


Supprimez l'objet RelMoveTo de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


Supprimez l'objet RelQuadBezTo de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


Supprimez l'objet SplineKnot de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


Supprimez l'objet SplineStart de la collection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

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

