---
title: glued_shapes method
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 120
url: /python-net/aspose.diagram/shape/glued_shapes/
is_root: false
---

## glued_shapes(flag, category_filter, other_shape) {#GluedShapesFlags-str-Shape}

Returns an array that contains the identifiers of the shapes that are glued to a shape.

### Returns 


IDs arrayInt64.


```python
def glued_shapes(self, flag, category_filter, other_shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| flag | [GluedShapesFlags](/diagram/python-net/aspose.diagram/gluedshapesflags) | The dimensionality and directionality of the connection points of the shapes to return.See Remarks for possible values[GluedShapesFlags](/diagram/python-net/aspose.diagram/gluedshapesflags). |
| category_filter | str | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified categoryString. |
| other_shape | [Shape](/diagram/python-net/aspose.diagram/shape) | Optional: additional shape to which returned shapes must also be glued, can be [Shape](/diagram/python-net/aspose.diagram/shape) or null. |



### See Also
* module [aspose.diagram](../../)
* class [Shape](/diagram/python-net/aspose.diagram/shape)
