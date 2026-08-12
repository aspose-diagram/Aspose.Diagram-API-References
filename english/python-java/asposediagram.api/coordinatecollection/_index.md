---
title: "CoordinateCollection"
linktitle: "CoordinateCollection"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Coordinate collection."
type: docs
weight: 750
url: /python-java/asposediagram.api/coordinatecollection/
---

## CoordinateCollection class

Coordinate collection.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [MoveToCol](#movetocol) | MoveToCollection | Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vert |
| [LineToCol](#linetocol) | LineToCollection | Contains x- and y-coordinates of the ending vertex of a straight line segment. These coordinates are contained in the X  |
| [ArcToCol](#arctocol) | ArcToCollection | Contains the x- and y-coordinates and bow of a circular arc represented respectively by the X, Y, and A elements. |
| [InfiniteLineCol](#infinitelinecol) | InfiniteLineCollection | Contains elements specifying the x- and y-coordinates of two points on an infinite line. The X and Y elements specify th |
| [EllipseCol](#ellipsecol) | EllipseCollection | Contains elements specifying the x- and y-coordinates of the ellipse's center point and two points on the ellipse. |
| [EllipticalArcToCol](#ellipticalarctocol) | EllipticalArcToCollection | Contains elements that specify information about an elliptical arc. |
| [SplineStartCol](#splinestartcol) | SplineStartCollection | Contains x- and y-coordinates for a spline's second control point, its second knot, its first knot, the last knot, and t |
| [SplineKnotCol](#splineknotcol) | SplineKnotCollection | Contains x- and y-coordinates for a spline's control point and a spline's knot, represented by the X, Y, and A elements, |
| [PolylineToCol](#polylinetocol) | PolylineToCollection | Contains x- and y-coordinates of the last point of a polyline and a polyline formula. The coordinates are specified in t |
| [NURBSToCol](#nurbstocol) | NURBSToCollection | Contains the x- and y-coordinates, position of the second to last knot, position of the last weight, position of the fir |
| [RelCubBezToCol](#relcubbeztocol) | RelCubBezToCollection | Contains x- and y-coordinates for a RelCubBezTo's points.Coordinates are specified as relative coordinates. |
| [RelQuadBezToCol](#relquadbeztocol) | RelQuadBezToCollection | Contains x- and y-coordinates for a RelQuadBezTo's points.Coordinates are specified as relative coordinates. |
| [RelMoveToCol](#relmovetocol) | RelMoveToCollection | Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vert |
| [RelLineToCol](#rellinetocol) | RelLineToCollection | Contains x- and y-coordinates of the ending vertex of a straight line segment. These coordinates are contained in the X  |
| [RelEllipticalArcToCol](#relellipticalarctocol) | RelEllipticalArcToCollection | Contains elements that specify information about an elliptical arc.Coordinates are specified as relative coordinates. |
| [Count](#count) | int |  |
| [Item (int)](#itemint) | Coordinate |  |

## Methods

| Name | Description |
| --- | --- |
| [add](#add) | Add the Coordinate object in the collection. |
| [remove](#remove) | Remove the Coordinate object from the collection. |
| [clear](#clear) |  |
| [removeAt](#removeat) |  |
| [iterator](#iterator) | Reserved for internal use. |

### CoordinateCollection.MoveToCol property {#movetocol}

Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vertex after a break in a path.

**Type:** MoveToCollection

### CoordinateCollection.LineToCol property {#linetocol}

Contains x- and y-coordinates of the ending vertex of a straight line segment. These coordinates are contained in the X and Y elements, respectively.

**Type:** LineToCollection

### CoordinateCollection.ArcToCol property {#arctocol}

Contains the x- and y-coordinates and bow of a circular arc represented respectively by the X, Y, and A elements.

**Type:** ArcToCollection

### CoordinateCollection.InfiniteLineCol property {#infinitelinecol}

Contains elements specifying the x- and y-coordinates of two points on an infinite line. The X and Y elements specify the x- and y-coordinates of the first point, and the A and B elements specify the x- and y-coordinates of the second point.

**Type:** InfiniteLineCollection

### CoordinateCollection.EllipseCol property {#ellipsecol}

Contains elements specifying the x- and y-coordinates of the ellipse's center point and two points on the ellipse.

**Type:** EllipseCollection

### CoordinateCollection.EllipticalArcToCol property {#ellipticalarctocol}

Contains elements that specify information about an elliptical arc.

**Type:** EllipticalArcToCollection

### CoordinateCollection.SplineStartCol property {#splinestartcol}

Contains x- and y-coordinates for a spline's second control point, its second knot, its first knot, the last knot, and the degree of the spline. This information is contained in the X, Y, A, B, C, and D elements, respectively.

**Type:** SplineStartCollection

### CoordinateCollection.SplineKnotCol property {#splineknotcol}

Contains x- and y-coordinates for a spline's control point and a spline's knot, represented by the X, Y, and A elements, respectively.

**Type:** SplineKnotCollection

### CoordinateCollection.PolylineToCol property {#polylinetocol}

Contains x- and y-coordinates of the last point of a polyline and a polyline formula. The coordinates are specified in the X and Y elements, and the formula is specified in the A element.

**Type:** PolylineToCollection

### CoordinateCollection.NURBSToCol property {#nurbstocol}

Contains the x- and y-coordinates, position of the second to last knot, position of the last weight, position of the first knot, position of the first weight, and the formula for a nonuniform rational B-spline (NURBS). This information is specified in the X, Y, A, B, C, D, and E elements, respectively.

**Type:** NURBSToCollection

### CoordinateCollection.RelCubBezToCol property {#relcubbeztocol}

Contains x- and y-coordinates for a RelCubBezTo's points.Coordinates are specified as relative coordinates.

**Type:** RelCubBezToCollection

### CoordinateCollection.RelQuadBezToCol property {#relquadbeztocol}

Contains x- and y-coordinates for a RelQuadBezTo's points.Coordinates are specified as relative coordinates.

**Type:** RelQuadBezToCollection

### CoordinateCollection.RelMoveToCol property {#relmovetocol}

Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vertex after a break in a path.Coordinates are specified as relative coordinates.

**Type:** RelMoveToCollection

### CoordinateCollection.RelLineToCol property {#rellinetocol}

Contains x- and y-coordinates of the ending vertex of a straight line segment. These coordinates are contained in the X and Y elements, respectively.Coordinates are specified as relative coordinates.

**Type:** RelLineToCollection

### CoordinateCollection.RelEllipticalArcToCol property {#relellipticalarctocol}

Contains elements that specify information about an elliptical arc.Coordinates are specified as relative coordinates.

**Type:** RelEllipticalArcToCollection

### CoordinateCollection.Count property {#count}

**Type:** int

### CoordinateCollection.Item (int) property {#itemint}

**Type:** Coordinate

### add(item) (1 of 16) {#add}

Add the Coordinate object in the collection.

---

### add(item) (2 of 16) {#add-1}

Add the MoveTo object in the collection.

---

### add(item) (3 of 16) {#add-2}

Add the LineTo object in the collection.

---

### add(item) (4 of 16) {#add-3}

Add the ArcTo object in the collection.

---

### add(item) (5 of 16) {#add-4}

Add the InfiniteLine object in the collection.

---

### add(item) (6 of 16) {#add-5}

Add the Ellipse object in the collection.

---

### add(item) (7 of 16) {#add-6}

Add the EllipticalArcTo object in the collection.

---

### add(item) (8 of 16) {#add-7}

Add the SplineStart object in the collection.

---

### add(item) (9 of 16) {#add-8}

Add the SplineKnot object in the collection.

---

### add(item) (10 of 16) {#add-9}

Add the PolylineTo object in the collection.

---

### add(item) (11 of 16) {#add-10}

Add the NURBSTo object in the collection.

---

### add(item) (12 of 16) {#add-11}

Add the RelCubBezTo object in the collection.

---

### add(item) (13 of 16) {#add-12}

Add the RelQuadBezTo object in the collection.

---

### add(item) (14 of 16) {#add-13}

Add the RelMoveTo object in the collection.

---

### add(item) (15 of 16) {#add-14}

Add the RelLineTo object in the collection.

---

### add(item) (16 of 16) {#add-15}

Add the RelEllipticalArcTo object in the collection.

### remove(item) (1 of 16) {#remove}

Remove the Coordinate object from the collection.

---

### remove(item) (2 of 16) {#remove-1}

Remove the MoveTo object from the collection.

---

### remove(item) (3 of 16) {#remove-2}

Remove the LineTo object from the collection.

---

### remove(item) (4 of 16) {#remove-3}

Remove the ArcTo object from the collection.

---

### remove(item) (5 of 16) {#remove-4}

Remove the InfiniteLine object from the collection.

---

### remove(item) (6 of 16) {#remove-5}

Remove the Ellipse object from the collection.

---

### remove(item) (7 of 16) {#remove-6}

Remove the EllipticalArcTo object from the collection.

---

### remove(item) (8 of 16) {#remove-7}

Remove the SplineStart object from the collection.

---

### remove(item) (9 of 16) {#remove-8}

Remove the SplineKnot object from the collection.

---

### remove(item) (10 of 16) {#remove-9}

Remove the PolylineTo object from the collection.

---

### remove(item) (11 of 16) {#remove-10}

Remove the NURBSTo object from the collection.

---

### remove(item) (12 of 16) {#remove-11}

Remove the RelCubBezTo object from the collection.

---

### remove(item) (13 of 16) {#remove-12}

Remove the RelQuadBezTo object from the collection.

---

### remove(item) (14 of 16) {#remove-13}

Remove the RelMoveTo object from the collection.

---

### remove(item) (15 of 16) {#remove-14}

Remove the RelLineTo object from the collection.

---

### remove(item) (16 of 16) {#remove-15}

Remove the RelEllipticalArcTo object from the collection.

### clear() {#clear}

### removeAt(index) {#removeat}

### iterator() {#iterator}

Reserved for internal use.
