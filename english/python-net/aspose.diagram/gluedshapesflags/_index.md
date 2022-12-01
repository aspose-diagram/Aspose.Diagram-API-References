---
title: GluedShapesFlags enumeration
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 2980
url: /python-net/aspose.diagram/gluedshapesflags/
is_root: false
---

## GluedShapesFlags enumeration

Specifies constants that identify which shapes to return, based on the dimensionality and directionality of the connection points that are glued to a particular shape; passed to the Shape.GluedShapes method.



The GluedShapesFlags type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| GLUED_SHAPES_ALL_1D | Return IDs of all 1-D shapes that are glued to this shape. |
| GLUED_SHAPES_INCOMING_1D | Return IDs of 1-D shapes whose end points are glued to this shape. |
| GLUED_SHAPES_OUTGOING_1D | Return IDs of 1-D shapes whose begin points are glued to this shape. |
| GLUED_SHAPES_ALL_2D | Return all 2-D shapes that are glued to this shape and all 2-D shapes to which this shape is glued. |
| GLUED_SHAPES_INCOMING_2D | If the source object is a 1-D shape, return IDs of 2-D shape to which the begin point is glued. <br/>If the source object is a 2-D shape, return IDs of 2-D shapes that are glued to this shape. |
| GLUED_SHAPES_OUTGOING_2D | If the source object is a 1-D shape, return IDs of 2-D shape to which the end point is glued. <br/>If the source object is a 2-D shape, return IDs of 2-D shapes to which this shape is glued. |


### See Also

* module [aspose.diagram](../)
