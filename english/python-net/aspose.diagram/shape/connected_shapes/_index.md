---
title: connected_shapes method
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/aspose.diagram/shape/connected_shapes/
is_root: false
---

## connected_shapes(flag, category_filter) {#ConnectedShapesFlags-str}

Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape.

### Returns 


IDs arrayInt64.


```python
def connected_shapes(self, flag, category_filter):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| flag | [ConnectedShapesFlags](/diagram/python-net/aspose.diagram/connectedshapesflags) | Filters the array of returned shape IDs by the directionality of the connectors. See Remarks for possible values[ConnectedShapesFlags](/diagram/python-net/aspose.diagram/connectedshapesflags). |
| category_filter | str | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified categoryString. |



### See Also
* module [aspose.diagram](../../)
* class [Shape](/diagram/python-net/aspose.diagram/shape)
