---
title: CoordinateCollection class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 460
url: /python-net/aspose.diagram/coordinatecollection/
is_root: false
---

## CoordinateCollection class

Coordinate collection.



**Inheritance:** [CoordinateCollection](/diagram/python-net/aspose.diagram/coordinatecollection) → 
[Collection](/diagram/python-net/aspose.diagram/collection)



The CoordinateCollection type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [count](/diagram/python-net/aspose.diagram/coordinatecollection/count) | Gets the number of elements actually contained in the collection. |
| [move_to_col](/diagram/python-net/aspose.diagram/coordinatecollection/move_to_col) | Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vertex after a break in a path. |
| [line_to_col](/diagram/python-net/aspose.diagram/coordinatecollection/line_to_col) | Contains x- and y-coordinates of the ending vertex of a straight line segment. These coordinates are contained in the X and Y elements, respectively. |
| [arc_to_col](/diagram/python-net/aspose.diagram/coordinatecollection/arc_to_col) | Contains the x- and y-coordinates and bow of a circular arc represented respectively by the X, Y, and A elements. |
| [infinite_line_col](/diagram/python-net/aspose.diagram/coordinatecollection/infinite_line_col) | Contains elements specifying the x- and y-coordinates of two points on an infinite line. The X and Y elements specify the x- and y-coordinates of the first point, and the A and B elements specify the x- and y-coordinates of the second point. |
| [ellipse_col](/diagram/python-net/aspose.diagram/coordinatecollection/ellipse_col) | Contains elements specifying the x- and y-coordinates of the ellipse's center point and two points on the ellipse. |
| [elliptical_arc_to_col](/diagram/python-net/aspose.diagram/coordinatecollection/elliptical_arc_to_col) | Contains elements that specify information about an elliptical arc. |
| [spline_start_col](/diagram/python-net/aspose.diagram/coordinatecollection/spline_start_col) | Contains x- and y-coordinates for a spline's second control point, its second knot, its first knot, the last knot, and the degree of the spline. This information is contained in the X, Y, A, B, C, and D elements, respectively. |
| [spline_knot_col](/diagram/python-net/aspose.diagram/coordinatecollection/spline_knot_col) | Contains x- and y-coordinates for a spline's control point and a spline's knot, represented by the X, Y, and A elements, respectively. |
| [polyline_to_col](/diagram/python-net/aspose.diagram/coordinatecollection/polyline_to_col) | Contains x- and y-coordinates of the last point of a polyline and a polyline formula. The coordinates are specified in the X and Y elements, and the formula is specified in the A element. |
| [nurbs_to_col](/diagram/python-net/aspose.diagram/coordinatecollection/nurbs_to_col) | Contains the x- and y-coordinates, position of the second to last knot, position of the last weight, position of the first knot, position of the first weight, and the formula for a nonuniform rational B-spline (NURBS). This information is specified in the X, Y, A, B, C, D, and E elements, respectively. |
| [rel_cub_bez_to_col](/diagram/python-net/aspose.diagram/coordinatecollection/rel_cub_bez_to_col) | Contains x- and y-coordinates for a RelCubBezTo's points.Coordinates are specified as relative coordinates. |
| [rel_quad_bez_to_col](/diagram/python-net/aspose.diagram/coordinatecollection/rel_quad_bez_to_col) | Contains x- and y-coordinates for a RelQuadBezTo's points.Coordinates are specified as relative coordinates. |
| [rel_move_to_col](/diagram/python-net/aspose.diagram/coordinatecollection/rel_move_to_col) | Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vertex after a break in a path.Coordinates are specified as relative coordinates. |
| [rel_line_to_col](/diagram/python-net/aspose.diagram/coordinatecollection/rel_line_to_col) | Contains x- and y-coordinates of the ending vertex of a straight line segment. These coordinates are contained in the X and Y elements, respectively.Coordinates are specified as relative coordinates. |
| [rel_elliptical_arc_to_col](/diagram/python-net/aspose.diagram/coordinatecollection/rel_elliptical_arc_to_col) | Contains elements that specify information about an elliptical arc.Coordinates are specified as relative coordinates. |



Gets the element at the specified index.
### Indexer
| Name | Description |
| :- | :- |
| [index] |  |


### Methods
| Method | Description |
| :- | :- |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#Coordinate) | Add the Coordinate object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#MoveTo) | Add the MoveTo object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#LineTo) | Add the LineTo object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#ArcTo) | Add the ArcTo object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#InfiniteLine) | Add the InfiniteLine object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#Ellipse) | Add the Ellipse object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#EllipticalArcTo) | Add the EllipticalArcTo object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#SplineStart) | Add the SplineStart object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#SplineKnot) | Add the SplineKnot object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#PolylineTo) | Add the PolylineTo object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#NURBSTo) | Add the NURBSTo object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#RelCubBezTo) | Add the RelCubBezTo object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#RelQuadBezTo) | Add the RelQuadBezTo object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#RelMoveTo) | Add the RelMoveTo object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#RelLineTo) | Add the RelLineTo object in the collection. |
| [add(item)](/diagram/python-net/aspose.diagram/coordinatecollection/add/#RelEllipticalArcTo) | Add the RelEllipticalArcTo object in the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#Coordinate) | Remove the Coordinate object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#MoveTo) | Remove the MoveTo object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#LineTo) | Remove the LineTo object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#ArcTo) | Remove the ArcTo object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#InfiniteLine) | Remove the InfiniteLine object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#Ellipse) | Remove the Ellipse object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#EllipticalArcTo) | Remove the EllipticalArcTo object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#SplineStart) | Remove the SplineStart object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#SplineKnot) | Remove the SplineKnot object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#PolylineTo) | Remove the PolylineTo object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#NURBSTo) | Remove the NURBSTo object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#RelCubBezTo) | Remove the RelCubBezTo object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#RelQuadBezTo) | Remove the RelQuadBezTo object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#RelMoveTo) | Remove the RelMoveTo object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#RelLineTo) | Remove the RelLineTo object from the collection. |
| [remove(item)](/diagram/python-net/aspose.diagram/coordinatecollection/remove/#RelEllipticalArcTo) | Remove the RelEllipticalArcTo object from the collection. |
| [is_exist(index)](/diagram/python-net/aspose.diagram/coordinatecollection/is_exist/#int) | Is exist item in the collection. |
| [clear()](/diagram/python-net/aspose.diagram/coordinatecollection/clear/#) | Removes all elements from collection. |


### See Also

* module [aspose.diagram](../)
* class [Collection](/diagram/python-net/aspose.diagram/collection)
