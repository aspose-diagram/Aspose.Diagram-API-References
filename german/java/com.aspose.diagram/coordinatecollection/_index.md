---
title: CoordinateCollection
second_title: Aspose.Diagram for Java API-Referenz
description: Koordinatensammlung.
type: docs
weight: 102
url: /de/java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

Koordinatensammlung.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | Fügt das ArcTo-Objekt zur Sammlung hinzu. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | Fügt das Coordinate-Objekt zur Sammlung hinzu. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | Fügt das Ellipse-Objekt zur Sammlung hinzu. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | Fügt das EllipticalArcTo-Objekt zur Sammlung hinzu. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | Fügt das InfiniteLine-Objekt zur Sammlung hinzu. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | Fügt das LineTo-Objekt zur Sammlung hinzu. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | Fügt das MoveTo-Objekt zur Sammlung hinzu. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | Fügt das NURBSTo-Objekt zur Sammlung hinzu. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | Fügt das PolylineTo-Objekt zur Sammlung hinzu. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | Fügt das RelCubBezTo-Objekt zur Sammlung hinzu. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | Füge das RelEllipticalArcTo-Objekt zur Sammlung hinzu. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | Füge das RelLineTo-Objekt zur Sammlung hinzu. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | Füge das RelMoveTo-Objekt zur Sammlung hinzu. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | Füge das RelQuadBezTo-Objekt zur Sammlung hinzu. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | Füge das SplineKnot-Objekt zur Sammlung hinzu. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | Füge das SplineStart-Objekt zur Sammlung hinzu. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Gibt das Element am angegebenen Index zurück. |
| [getArcToCol()](#getArcToCol--) | Enthält die x- und y-Koordinaten sowie die Krümmung eines Kreisbogens, die jeweils durch die Elemente X, Y und A dargestellt werden. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gibt die tatsächlich in der Sammlung enthaltene Elementanzahl zurück. |
| [getEllipseCol()](#getEllipseCol--) | Enthält Elemente, die die x- und y-Koordinaten des Mittelpunktes der Ellipse sowie zwei Punkte auf der Ellipse angeben. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | Enthält Elemente, die Informationen über einen elliptischen Bogen angeben. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | Enthält Elemente, die die x- und y-Koordinaten von zwei Punkten auf einer unendlichen Linie angeben. |
| [getLineToCol()](#getLineToCol--) | Enthält die x- und y-Koordinaten des Endknotens eines geraden Liniensegments. |
| [getMoveToCol()](#getMoveToCol--) | Enthält die x- und y-Koordinaten des ersten Scheitelpunkts einer Form oder die x- und y-Koordinaten des ersten Scheitelpunkts nach einem Pfadunterbruch. |
| [getNURBSToCol()](#getNURBSToCol--) | Enthält die x- und y-Koordinaten, die Position des vorletzten Knoten, die Position des letzten Gewichts, die Position des ersten Knotens, die Position des ersten Gewichts sowie die Formel für einen nicht-uniformen rationalen B-Spline (NURBS). |
| [getPolylineToCol()](#getPolylineToCol--) | Enthält x- und y-Koordinaten des letzten Punktes einer Polylinie und einer Polylinienformel. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | Enthält x- und y-Koordinaten für die Punkte eines RelCubBezTo. Koordinaten werden als relative Koordinaten angegeben. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | Enthält Elemente, die Informationen über einen elliptischen Bogen angeben. Koordinaten werden als relative Koordinaten angegeben. |
| [getRelLineToCol()](#getRelLineToCol--) | Enthält die x- und y-Koordinaten des Endknotens eines geraden Liniensegments. |
| [getRelMoveToCol()](#getRelMoveToCol--) | Enthält die x- und y-Koordinaten des ersten Scheitelpunkts einer Form oder die x- und y-Koordinaten des ersten Scheitelpunkts nach einem Unterbrechung im Pfad. Koordinaten werden als relative Koordinaten angegeben. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | Enthält x- und y-Koordinaten für die Punkte eines RelQuadBezTo. Koordinaten werden als relative Koordinaten angegeben. |
| [getSplineKnotCol()](#getSplineKnotCol--) | Enthält X‑ und Y‑Koordinaten für den Kontrollpunkt einer Spline und den Knoten einer Spline, dargestellt durch die Elemente X, Y bzw. A. |
| [getSplineStartCol()](#getSplineStartCol--) | Enthält X‑ und Y‑Koordinaten für den zweiten Kontrollpunkt einer Spline, ihren zweiten Knoten, ihren ersten Knoten, den letzten Knoten und den Grad der Spline. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Existiert ein Element in der Sammlung. |
| [iterator()](#iterator--) | Unterstützt eine einfache Iteration über eine nicht generische Sammlung. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | Entferne das ArcTo-Objekt aus der Sammlung. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | Entferne das Coordinate-Objekt aus der Sammlung. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | Entferne das Ellipse-Objekt aus der Sammlung. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | Entferne das EllipticalArcTo-Objekt aus der Sammlung. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | Entferne das InfiniteLine-Objekt aus der Sammlung. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | Entferne das LineTo-Objekt aus der Sammlung. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | Entferne das MoveTo-Objekt aus der Sammlung. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | Entferne das NURBSTo-Objekt aus der Sammlung. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | Entferne das PolylineTo-Objekt aus der Sammlung. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | Entferne das RelCubBezTo-Objekt aus der Sammlung. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | Entferne das RelEllipticalArcTo-Objekt aus der Sammlung. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | Entferne das RelLineTo-Objekt aus der Sammlung. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | Entferne das RelMoveTo-Objekt aus der Sammlung. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | Entferne das RelQuadBezTo-Objekt aus der Sammlung. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | Entferne das SplineKnot-Objekt aus der Sammlung. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | Entferne das SplineStart-Objekt aus der Sammlung. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


Fügt das ArcTo-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int -
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


Fügt das Coordinate-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


Fügt das Ellipse-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int -
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


Fügt das EllipticalArcTo-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int -
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


Fügt das InfiniteLine-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int -
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


Fügt das LineTo-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int -
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


Fügt das MoveTo-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int -
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


Fügt das NURBSTo-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int -
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


Fügt das PolylineTo-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int -
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


Fügt das RelCubBezTo-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int -
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


Füge das RelEllipticalArcTo-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int -
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


Füge das RelLineTo-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int -
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


Füge das RelMoveTo-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int -
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


Füge das RelQuadBezTo-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int -
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


Füge das SplineKnot-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int -
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


Füge das SplineStart-Objekt zur Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Entfernt alle Elemente aus der Sammlung.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Gibt das Element am angegebenen Index zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


Enthält die x- und y-Koordinaten sowie die Krümmung eines Kreisbogens, die jeweils durch die Elemente X, Y und A dargestellt werden.

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


Gibt die tatsächlich in der Sammlung enthaltene Elementanzahl zurück.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


Enthält Elemente, die die x- und y-Koordinaten des Mittelpunktes der Ellipse sowie zwei Punkte auf der Ellipse angeben.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


Enthält Elemente, die Informationen über einen elliptischen Bogen angeben.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


Enthält Elemente, die die x- und y-Koordinaten von zwei Punkten auf einer unendlichen Linie angeben. Die X- und Y-Elemente geben die x- und y-Koordinaten des ersten Punktes an, und die A- und B-Elemente geben die x- und y-Koordinaten des zweiten Punktes an.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


Enthält x- und y-Koordinaten des Endknotens eines geraden Liniensegments. Diese Koordinaten sind jeweils in den X- und Y-Elementen enthalten.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


Enthält die x- und y-Koordinaten des ersten Scheitelpunkts einer Form oder die x- und y-Koordinaten des ersten Scheitelpunkts nach einem Pfadunterbruch.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


Enthält die x- und y-Koordinaten, die Position des vorletzten Knotens, die Position des letzten Gewichts, die Position des ersten Knotens, die Position des ersten Gewichts und die Formel für einen nicht-uniform rationalen B-Spline (NURBS). Diese Informationen sind jeweils in den Elementen X, Y, A, B, C, D und E angegeben.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


Enthält x- und y-Koordinaten des letzten Punktes einer Polylinie und eine Polylinien-Formel. Die Koordinaten werden in den X- und Y-Elementen angegeben, und die Formel wird im A-Element angegeben.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


Enthält x- und y-Koordinaten für die Punkte eines RelCubBezTo. Koordinaten werden als relative Koordinaten angegeben.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


Enthält Elemente, die Informationen über einen elliptischen Bogen angeben. Koordinaten werden als relative Koordinaten angegeben.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


Enthält x- und y-Koordinaten des Endknotens eines geraden Liniensegments. Diese Koordinaten sind jeweils in den X- und Y-Elementen enthalten. Koordinaten werden als relative Koordinaten angegeben.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


Enthält die x- und y-Koordinaten des ersten Scheitelpunkts einer Form oder die x- und y-Koordinaten des ersten Scheitelpunkts nach einem Unterbrechung im Pfad. Koordinaten werden als relative Koordinaten angegeben.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


Enthält x- und y-Koordinaten für die Punkte eines RelQuadBezTo. Koordinaten werden als relative Koordinaten angegeben.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


Enthält X‑ und Y‑Koordinaten für den Kontrollpunkt einer Spline und den Knoten einer Spline, dargestellt durch die Elemente X, Y bzw. A.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


Enthält x- und y-Koordinaten für den zweiten Steuerpunkt einer Spline, ihren zweiten Knoten, ihren ersten Knoten, den letzten Knoten und den Grad der Spline. Diese Informationen sind in den Elementen X, Y, A, B, C und D jeweils enthalten.

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


Existiert ein Element in der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Index des Elements. |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Unterstützt eine einfache Iteration über eine nicht generische Sammlung.

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


Entferne das ArcTo-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


Entferne das Coordinate-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


Entferne das Ellipse-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


Entferne das EllipticalArcTo-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


Entferne das InfiniteLine-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


Entferne das LineTo-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


Entferne das MoveTo-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


Entferne das NURBSTo-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


Entferne das PolylineTo-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


Entferne das RelCubBezTo-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


Entferne das RelEllipticalArcTo-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


Entferne das RelLineTo-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


Entferne das RelMoveTo-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


Entferne das RelQuadBezTo-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


Entferne das SplineKnot-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


Entferne das SplineStart-Objekt aus der Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

