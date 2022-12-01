---
title: CoordinateCollection
second_title: Aspose.Diagram for Java API Reference
description: Coordinate collection.
type: docs
weight: 102
url: /java/com.aspose.diagram/coordinatecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class CoordinateCollection extends Collection
```

Coordinate collection.
## Methods

| Method | Description |
| --- | --- |
| [add(ArcTo item)](#add-com.aspose.diagram.ArcTo-) | Add the ArcTo object in the collection. |
| [add(Coordinate item)](#add-com.aspose.diagram.Coordinate-) | Add the Coordinate object in the collection. |
| [add(Ellipse item)](#add-com.aspose.diagram.Ellipse-) | Add the Ellipse object in the collection. |
| [add(EllipticalArcTo item)](#add-com.aspose.diagram.EllipticalArcTo-) | Add the EllipticalArcTo object in the collection. |
| [add(InfiniteLine item)](#add-com.aspose.diagram.InfiniteLine-) | Add the InfiniteLine object in the collection. |
| [add(LineTo item)](#add-com.aspose.diagram.LineTo-) | Add the LineTo object in the collection. |
| [add(MoveTo item)](#add-com.aspose.diagram.MoveTo-) | Add the MoveTo object in the collection. |
| [add(NURBSTo item)](#add-com.aspose.diagram.NURBSTo-) | Add the NURBSTo object in the collection. |
| [add(PolylineTo item)](#add-com.aspose.diagram.PolylineTo-) | Add the PolylineTo object in the collection. |
| [add(RelCubBezTo item)](#add-com.aspose.diagram.RelCubBezTo-) | Add the RelCubBezTo object in the collection. |
| [add(RelEllipticalArcTo item)](#add-com.aspose.diagram.RelEllipticalArcTo-) | Add the RelEllipticalArcTo object in the collection. |
| [add(RelLineTo item)](#add-com.aspose.diagram.RelLineTo-) | Add the RelLineTo object in the collection. |
| [add(RelMoveTo item)](#add-com.aspose.diagram.RelMoveTo-) | Add the RelMoveTo object in the collection. |
| [add(RelQuadBezTo item)](#add-com.aspose.diagram.RelQuadBezTo-) | Add the RelQuadBezTo object in the collection. |
| [add(SplineKnot item)](#add-com.aspose.diagram.SplineKnot-) | Add the SplineKnot object in the collection. |
| [add(SplineStart item)](#add-com.aspose.diagram.SplineStart-) | Add the SplineStart object in the collection. |
| [clear()](#clear--) | Removes all elements from collection. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Gets the element at the specified index. |
| [getArcToCol()](#getArcToCol--) | Contains the x- and y-coordinates and bow of a circular arc represented respectively by the X, Y, and A elements. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [getEllipseCol()](#getEllipseCol--) | Contains elements specifying the x- and y-coordinates of the ellipse's center point and two points on the ellipse. |
| [getEllipticalArcToCol()](#getEllipticalArcToCol--) | Contains elements that specify information about an elliptical arc. |
| [getInfiniteLineCol()](#getInfiniteLineCol--) | Contains elements specifying the x- and y-coordinates of two points on an infinite line. |
| [getLineToCol()](#getLineToCol--) | Contains x- and y-coordinates of the ending vertex of a straight line segment. |
| [getMoveToCol()](#getMoveToCol--) | Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vertex after a break in a path. |
| [getNURBSToCol()](#getNURBSToCol--) | Contains the x- and y-coordinates, position of the second to last knot, position of the last weight, position of the first knot, position of the first weight, and the formula for a nonuniform rational B-spline (NURBS). |
| [getPolylineToCol()](#getPolylineToCol--) | Contains x- and y-coordinates of the last point of a polyline and a polyline formula. |
| [getRelCubBezToCol()](#getRelCubBezToCol--) | Contains x- and y-coordinates for a RelCubBezTo's points.Coordinates are specified as relative coordinates. |
| [getRelEllipticalArcToCol()](#getRelEllipticalArcToCol--) | Contains elements that specify information about an elliptical arc.Coordinates are specified as relative coordinates. |
| [getRelLineToCol()](#getRelLineToCol--) | Contains x- and y-coordinates of the ending vertex of a straight line segment. |
| [getRelMoveToCol()](#getRelMoveToCol--) | Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vertex after a break in a path.Coordinates are specified as relative coordinates. |
| [getRelQuadBezToCol()](#getRelQuadBezToCol--) | Contains x- and y-coordinates for a RelQuadBezTo's points.Coordinates are specified as relative coordinates. |
| [getSplineKnotCol()](#getSplineKnotCol--) | Contains x- and y-coordinates for a spline's control point and a spline's knot, represented by the X, Y, and A elements, respectively. |
| [getSplineStartCol()](#getSplineStartCol--) | Contains x- and y-coordinates for a spline's second control point, its second knot, its first knot, the last knot, and the degree of the spline. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Is exist item in the collection. |
| [iterator()](#iterator--) | Supports a simple iteration over a nongeneric collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(ArcTo item)](#remove-com.aspose.diagram.ArcTo-) | Remove the ArcTo object from the collection. |
| [remove(Coordinate item)](#remove-com.aspose.diagram.Coordinate-) | Remove the Coordinate object from the collection. |
| [remove(Ellipse item)](#remove-com.aspose.diagram.Ellipse-) | Remove the Ellipse object from the collection. |
| [remove(EllipticalArcTo item)](#remove-com.aspose.diagram.EllipticalArcTo-) | Remove the EllipticalArcTo object from the collection. |
| [remove(InfiniteLine item)](#remove-com.aspose.diagram.InfiniteLine-) | Remove the InfiniteLine object from the collection. |
| [remove(LineTo item)](#remove-com.aspose.diagram.LineTo-) | Remove the LineTo object from the collection. |
| [remove(MoveTo item)](#remove-com.aspose.diagram.MoveTo-) | Remove the MoveTo object from the collection. |
| [remove(NURBSTo item)](#remove-com.aspose.diagram.NURBSTo-) | Remove the NURBSTo object from the collection. |
| [remove(PolylineTo item)](#remove-com.aspose.diagram.PolylineTo-) | Remove the PolylineTo object from the collection. |
| [remove(RelCubBezTo item)](#remove-com.aspose.diagram.RelCubBezTo-) | Remove the RelCubBezTo object from the collection. |
| [remove(RelEllipticalArcTo item)](#remove-com.aspose.diagram.RelEllipticalArcTo-) | Remove the RelEllipticalArcTo object from the collection. |
| [remove(RelLineTo item)](#remove-com.aspose.diagram.RelLineTo-) | Remove the RelLineTo object from the collection. |
| [remove(RelMoveTo item)](#remove-com.aspose.diagram.RelMoveTo-) | Remove the RelMoveTo object from the collection. |
| [remove(RelQuadBezTo item)](#remove-com.aspose.diagram.RelQuadBezTo-) | Remove the RelQuadBezTo object from the collection. |
| [remove(SplineKnot item)](#remove-com.aspose.diagram.SplineKnot-) | Remove the SplineKnot object from the collection. |
| [remove(SplineStart item)](#remove-com.aspose.diagram.SplineStart-) | Remove the SplineStart object from the collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(ArcTo item) {#add-com.aspose.diagram.ArcTo-}
```
public int add(ArcTo item)
```


Add the ArcTo object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

**Returns:**
int - 
### add(Coordinate item) {#add-com.aspose.diagram.Coordinate-}
```
public int add(Coordinate item)
```


Add the Coordinate object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

**Returns:**
int
### add(Ellipse item) {#add-com.aspose.diagram.Ellipse-}
```
public int add(Ellipse item)
```


Add the Ellipse object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

**Returns:**
int - 
### add(EllipticalArcTo item) {#add-com.aspose.diagram.EllipticalArcTo-}
```
public int add(EllipticalArcTo item)
```


Add the EllipticalArcTo object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

**Returns:**
int - 
### add(InfiniteLine item) {#add-com.aspose.diagram.InfiniteLine-}
```
public int add(InfiniteLine item)
```


Add the InfiniteLine object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

**Returns:**
int - 
### add(LineTo item) {#add-com.aspose.diagram.LineTo-}
```
public int add(LineTo item)
```


Add the LineTo object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

**Returns:**
int - 
### add(MoveTo item) {#add-com.aspose.diagram.MoveTo-}
```
public int add(MoveTo item)
```


Add the MoveTo object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

**Returns:**
int - 
### add(NURBSTo item) {#add-com.aspose.diagram.NURBSTo-}
```
public int add(NURBSTo item)
```


Add the NURBSTo object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

**Returns:**
int - 
### add(PolylineTo item) {#add-com.aspose.diagram.PolylineTo-}
```
public int add(PolylineTo item)
```


Add the PolylineTo object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

**Returns:**
int - 
### add(RelCubBezTo item) {#add-com.aspose.diagram.RelCubBezTo-}
```
public int add(RelCubBezTo item)
```


Add the RelCubBezTo object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

**Returns:**
int - 
### add(RelEllipticalArcTo item) {#add-com.aspose.diagram.RelEllipticalArcTo-}
```
public int add(RelEllipticalArcTo item)
```


Add the RelEllipticalArcTo object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

**Returns:**
int - 
### add(RelLineTo item) {#add-com.aspose.diagram.RelLineTo-}
```
public int add(RelLineTo item)
```


Add the RelLineTo object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

**Returns:**
int - 
### add(RelMoveTo item) {#add-com.aspose.diagram.RelMoveTo-}
```
public int add(RelMoveTo item)
```


Add the RelMoveTo object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

**Returns:**
int - 
### add(RelQuadBezTo item) {#add-com.aspose.diagram.RelQuadBezTo-}
```
public int add(RelQuadBezTo item)
```


Add the RelQuadBezTo object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

**Returns:**
int - 
### add(SplineKnot item) {#add-com.aspose.diagram.SplineKnot-}
```
public int add(SplineKnot item)
```


Add the SplineKnot object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

**Returns:**
int - 
### add(SplineStart item) {#add-com.aspose.diagram.SplineStart-}
```
public int add(SplineStart item)
```


Add the SplineStart object in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [SplineStart](../../com.aspose.diagram/splinestart) |  |

**Returns:**
int - 
### clear() {#clear--}
```
public void clear()
```


Removes all elements from collection.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int-}
```
public Coordinate get(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[Coordinate](../../com.aspose.diagram/coordinate) - 
### getArcToCol() {#getArcToCol--}
```
public ArcToCollection getArcToCol()
```


Contains the x- and y-coordinates and bow of a circular arc represented respectively by the X, Y, and A elements.

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


Gets the number of elements actually contained in the collection.

**Returns:**
int
### getEllipseCol() {#getEllipseCol--}
```
public EllipseCollection getEllipseCol()
```


Contains elements specifying the x- and y-coordinates of the ellipse's center point and two points on the ellipse.

**Returns:**
[EllipseCollection](../../com.aspose.diagram/ellipsecollection)
### getEllipticalArcToCol() {#getEllipticalArcToCol--}
```
public EllipticalArcToCollection getEllipticalArcToCol()
```


Contains elements that specify information about an elliptical arc.

**Returns:**
[EllipticalArcToCollection](../../com.aspose.diagram/ellipticalarctocollection)
### getInfiniteLineCol() {#getInfiniteLineCol--}
```
public InfiniteLineCollection getInfiniteLineCol()
```


Contains elements specifying the x- and y-coordinates of two points on an infinite line. The X and Y elements specify the x- and y-coordinates of the first point, and the A and B elements specify the x- and y-coordinates of the second point.

**Returns:**
[InfiniteLineCollection](../../com.aspose.diagram/infinitelinecollection)
### getLineToCol() {#getLineToCol--}
```
public LineToCollection getLineToCol()
```


Contains x- and y-coordinates of the ending vertex of a straight line segment. These coordinates are contained in the X and Y elements, respectively.

**Returns:**
[LineToCollection](../../com.aspose.diagram/linetocollection)
### getMoveToCol() {#getMoveToCol--}
```
public MoveToCollection getMoveToCol()
```


Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vertex after a break in a path.

**Returns:**
[MoveToCollection](../../com.aspose.diagram/movetocollection)
### getNURBSToCol() {#getNURBSToCol--}
```
public NURBSToCollection getNURBSToCol()
```


Contains the x- and y-coordinates, position of the second to last knot, position of the last weight, position of the first knot, position of the first weight, and the formula for a nonuniform rational B-spline (NURBS). This information is specified in the X, Y, A, B, C, D, and E elements, respectively.

**Returns:**
[NURBSToCollection](../../com.aspose.diagram/nurbstocollection)
### getPolylineToCol() {#getPolylineToCol--}
```
public PolylineToCollection getPolylineToCol()
```


Contains x- and y-coordinates of the last point of a polyline and a polyline formula. The coordinates are specified in the X and Y elements, and the formula is specified in the A element.

**Returns:**
[PolylineToCollection](../../com.aspose.diagram/polylinetocollection)
### getRelCubBezToCol() {#getRelCubBezToCol--}
```
public RelCubBezToCollection getRelCubBezToCol()
```


Contains x- and y-coordinates for a RelCubBezTo's points.Coordinates are specified as relative coordinates.

**Returns:**
[RelCubBezToCollection](../../com.aspose.diagram/relcubbeztocollection)
### getRelEllipticalArcToCol() {#getRelEllipticalArcToCol--}
```
public RelEllipticalArcToCollection getRelEllipticalArcToCol()
```


Contains elements that specify information about an elliptical arc.Coordinates are specified as relative coordinates.

**Returns:**
[RelEllipticalArcToCollection](../../com.aspose.diagram/relellipticalarctocollection)
### getRelLineToCol() {#getRelLineToCol--}
```
public RelLineToCollection getRelLineToCol()
```


Contains x- and y-coordinates of the ending vertex of a straight line segment. These coordinates are contained in the X and Y elements, respectively.Coordinates are specified as relative coordinates.

**Returns:**
[RelLineToCollection](../../com.aspose.diagram/rellinetocollection)
### getRelMoveToCol() {#getRelMoveToCol--}
```
public RelMoveToCollection getRelMoveToCol()
```


Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vertex after a break in a path.Coordinates are specified as relative coordinates.

**Returns:**
[RelMoveToCollection](../../com.aspose.diagram/relmovetocollection)
### getRelQuadBezToCol() {#getRelQuadBezToCol--}
```
public RelQuadBezToCollection getRelQuadBezToCol()
```


Contains x- and y-coordinates for a RelQuadBezTo's points.Coordinates are specified as relative coordinates.

**Returns:**
[RelQuadBezToCollection](../../com.aspose.diagram/relquadbeztocollection)
### getSplineKnotCol() {#getSplineKnotCol--}
```
public SplineKnotCollection getSplineKnotCol()
```


Contains x- and y-coordinates for a spline's control point and a spline's knot, represented by the X, Y, and A elements, respectively.

**Returns:**
[SplineKnotCollection](../../com.aspose.diagram/splineknotcollection)
### getSplineStartCol() {#getSplineStartCol--}
```
public SplineStartCollection getSplineStartCol()
```


Contains x- and y-coordinates for a spline's second control point, its second knot, its first knot, the last knot, and the degree of the spline. This information is contained in the X, Y, A, B, C, and D elements, respectively.

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


Is exist item in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | index of element. |

**Returns:**
boolean - 
### iterator() {#iterator--}
```
public Iterator iterator()
```


Supports a simple iteration over a nongeneric collection.

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


Remove the ArcTo object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ArcTo](../../com.aspose.diagram/arcto) |  |

### remove(Coordinate item) {#remove-com.aspose.diagram.Coordinate-}
```
public void remove(Coordinate item)
```


Remove the Coordinate object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Coordinate](../../com.aspose.diagram/coordinate) |  |

### remove(Ellipse item) {#remove-com.aspose.diagram.Ellipse-}
```
public void remove(Ellipse item)
```


Remove the Ellipse object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Ellipse](../../com.aspose.diagram/ellipse) |  |

### remove(EllipticalArcTo item) {#remove-com.aspose.diagram.EllipticalArcTo-}
```
public void remove(EllipticalArcTo item)
```


Remove the EllipticalArcTo object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) |  |

### remove(InfiniteLine item) {#remove-com.aspose.diagram.InfiniteLine-}
```
public void remove(InfiniteLine item)
```


Remove the InfiniteLine object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [InfiniteLine](../../com.aspose.diagram/infiniteline) |  |

### remove(LineTo item) {#remove-com.aspose.diagram.LineTo-}
```
public void remove(LineTo item)
```


Remove the LineTo object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [LineTo](../../com.aspose.diagram/lineto) |  |

### remove(MoveTo item) {#remove-com.aspose.diagram.MoveTo-}
```
public void remove(MoveTo item)
```


Remove the MoveTo object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [MoveTo](../../com.aspose.diagram/moveto) |  |

### remove(NURBSTo item) {#remove-com.aspose.diagram.NURBSTo-}
```
public void remove(NURBSTo item)
```


Remove the NURBSTo object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [NURBSTo](../../com.aspose.diagram/nurbsto) |  |

### remove(PolylineTo item) {#remove-com.aspose.diagram.PolylineTo-}
```
public void remove(PolylineTo item)
```


Remove the PolylineTo object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [PolylineTo](../../com.aspose.diagram/polylineto) |  |

### remove(RelCubBezTo item) {#remove-com.aspose.diagram.RelCubBezTo-}
```
public void remove(RelCubBezTo item)
```


Remove the RelCubBezTo object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [RelCubBezTo](../../com.aspose.diagram/relcubbezto) |  |

### remove(RelEllipticalArcTo item) {#remove-com.aspose.diagram.RelEllipticalArcTo-}
```
public void remove(RelEllipticalArcTo item)
```


Remove the RelEllipticalArcTo object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [RelEllipticalArcTo](../../com.aspose.diagram/relellipticalarcto) |  |

### remove(RelLineTo item) {#remove-com.aspose.diagram.RelLineTo-}
```
public void remove(RelLineTo item)
```


Remove the RelLineTo object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [RelLineTo](../../com.aspose.diagram/rellineto) |  |

### remove(RelMoveTo item) {#remove-com.aspose.diagram.RelMoveTo-}
```
public void remove(RelMoveTo item)
```


Remove the RelMoveTo object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [RelMoveTo](../../com.aspose.diagram/relmoveto) |  |

### remove(RelQuadBezTo item) {#remove-com.aspose.diagram.RelQuadBezTo-}
```
public void remove(RelQuadBezTo item)
```


Remove the RelQuadBezTo object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [RelQuadBezTo](../../com.aspose.diagram/relquadbezto) |  |

### remove(SplineKnot item) {#remove-com.aspose.diagram.SplineKnot-}
```
public void remove(SplineKnot item)
```


Remove the SplineKnot object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [SplineKnot](../../com.aspose.diagram/splineknot) |  |

### remove(SplineStart item) {#remove-com.aspose.diagram.SplineStart-}
```
public void remove(SplineStart item)
```


Remove the SplineStart object from the collection.

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

