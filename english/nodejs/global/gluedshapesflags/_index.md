---
title: "GluedShapesFlags"
linktitle: "GluedShapesFlags"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Utility class containing constants."
type: docs
weight: 620
url: /nodejs/global/gluedshapesflags/
---

## GluedShapesFlags

Utility class containing constants. Specifies constants that identify which shapes to return, based on the dimensionality and directionality of the connection points that are glued to a particular shape; passed to the Shape.GluedShapes method.

## Values

| Name | Description |
| --- | --- |
| GLUED_SHAPES_ALL_1_D | Return IDs of all 1-D shapes that are glued to this shape. |
| GLUED_SHAPES_INCOMING_1_D | Return IDs of 1-D shapes whose end points are glued to this shape. |
| GLUED_SHAPES_OUTGOING_1_D | Return IDs of 1-D shapes whose begin points are glued to this shape. |
| GLUED_SHAPES_ALL_2_D | Return all 2-D shapes that are glued to this shape and all 2-D shapes to which this shape is glued. |
| GLUED_SHAPES_INCOMING_2_D | If the source object is a 1-D shape, return IDs of 2-D shape to which the begin point is glued. If the source object is a 2-D shape, return IDs of 2-D shapes that are glued to this shape. |
| GLUED_SHAPES_OUTGOING_2_D | If the source object is a 1-D shape, return IDs of 2-D shape to which the end point is glued. If the source object is a 2-D shape, return IDs of 2-D shapes to which this shape is glued. |
