---
title: "Geom Class"
linktitle: "Geom"
articleTitle: "Geom"
second_title: "Aspose.Diagram for Python via Java"
description: "Contains elements that specify the coordinates of the vertices for the lines and arcs that make up the shape."
type: docs
weight: 1390
url: /python-java/asposediagram.api/geom/
---

## Geom class

Contains elements that specify the coordinates of the vertices for the lines and arcs that make up the shape. If the shape has more than one path, there is a Geom element for each path.

```python
Geom()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [IX](./ix/) | int | The zero-based index of the element within its parent element. |
| [Del](./del/) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [CoordinateCol](./coordinatecol/) | CoordinateCollection | Collection of coordinates. It shows sequence of coordinates. |
| [NoFill](./nofill/) | BoolValue | Specifies whether a path can be filled. |
| [NoLine](./noline/) | BoolValue | Specifies whether a line is drawn around the boundary of the path. |
| [NoShow](./noshow/) | BoolValue | Specifies whether a path is displayed on the drawing page. |
| [NoSnap](./nosnap/) | BoolValue | Specifies whether other shapes snap to a path. |
| [NoQuickDrag](./noquickdrag/) | BoolValue | Determines whether a shape can be selected or dragged when the user clicks the filled area defined by the Geometry secti |
| [NextCoordinateIX](./nextcoordinateix/) | int | Returns IX value for next shape's coordinate collection member. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](./deepclone/) | Creates deep copy of this instance. |
