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
| [IX](/python-java/asposediagram.api/geom/ix/) | int | The zero-based index of the element within its parent element. |
| [Del](/python-java/asposediagram.api/geom/del/) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [CoordinateCol](/python-java/asposediagram.api/geom/coordinatecol/) | CoordinateCollection | Collection of coordinates. It shows sequence of coordinates. |
| [NoFill](/python-java/asposediagram.api/geom/nofill/) | BoolValue | Specifies whether a path can be filled. |
| [NoLine](/python-java/asposediagram.api/geom/noline/) | BoolValue | Specifies whether a line is drawn around the boundary of the path. |
| [NoShow](/python-java/asposediagram.api/geom/noshow/) | BoolValue | Specifies whether a path is displayed on the drawing page. |
| [NoSnap](/python-java/asposediagram.api/geom/nosnap/) | BoolValue | Specifies whether other shapes snap to a path. |
| [NoQuickDrag](/python-java/asposediagram.api/geom/noquickdrag/) | BoolValue | Determines whether a shape can be selected or dragged when the user clicks the filled area defined by the Geometry secti |
| [NextCoordinateIX](/python-java/asposediagram.api/geom/nextcoordinateix/) | int | Returns IX value for next shape's coordinate collection member. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](/python-java/asposediagram.api/geom/deepclone/) | Creates deep copy of this instance. |
