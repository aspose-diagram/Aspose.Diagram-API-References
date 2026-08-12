---
title: "Geom"
linktitle: "Geom"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that specify the coordinates of the vertices for the lines and arcs that make up the shape."
type: docs
weight: 1390
url: /python-java/asposediagram.api/geom/
---

## Geom class

Contains elements that specify the coordinates of the vertices for the lines and arcs that make up the shape. If the shape has more than one path, there is a Geom element for each path.

## Constructors

| Name | Description |
| --- | --- |
| [Geom](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [IX](#ix) | int | The zero-based index of the element within its parent element. |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [CoordinateCol](#coordinatecol) | CoordinateCollection | Collection of coordinates. It shows sequence of coordinates. |
| [NoFill](#nofill) | BoolValue | Specifies whether a path can be filled. |
| [NoLine](#noline) | BoolValue | Specifies whether a line is drawn around the boundary of the path. |
| [NoShow](#noshow) | BoolValue | Specifies whether a path is displayed on the drawing page. |
| [NoSnap](#nosnap) | BoolValue | Specifies whether other shapes snap to a path. |
| [NoQuickDrag](#noquickdrag) | BoolValue | Determines whether a shape can be selected or dragged when the user clicks the filled area defined by the Geometry secti |
| [NextCoordinateIX](#nextcoordinateix) | int | Returns IX value for next shape's coordinate collection member. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### Geom() {#constructor}

Constructor.

### Geom.IX property {#ix}

The zero-based index of the element within its parent element.

**Type:** int

### Geom.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### Geom.CoordinateCol property {#coordinatecol}

Collection of coordinates. It shows sequence of coordinates.

**Type:** CoordinateCollection

### Geom.NoFill property {#nofill}

Specifies whether a path can be filled.

**Type:** BoolValue

### Geom.NoLine property {#noline}

Specifies whether a line is drawn around the boundary of the path.

**Type:** BoolValue

### Geom.NoShow property {#noshow}

Specifies whether a path is displayed on the drawing page.

**Type:** BoolValue

### Geom.NoSnap property {#nosnap}

Specifies whether other shapes snap to a path.

**Type:** BoolValue

### Geom.NoQuickDrag property {#noquickdrag}

Determines whether a shape can be selected or dragged when the user clicks the filled area defined by the Geometry section.

**Type:** BoolValue

### Geom.NextCoordinateIX property {#nextcoordinateix}

Returns IX value for next shape's coordinate collection member.

**Type:** int

### deepClone() {#deepclone}

Creates deep copy of this instance.
