---
title: "Line"
linktitle: "Line"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements specifying general positioning information about a shape."
type: docs
weight: 1810
url: /python-java/asposediagram.api/line/
---

## Line class

Contains elements specifying general positioning information about a shape.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [LineWeight](#lineweight) | DoubleValue | Specifies the line weight of a shape. Line weight is independent of the scale of the drawing. If the drawing is scaled,  |
| [GradientLine](#gradientline) | GradientFill | Contains the current gradient line formatting values for the shape |
| [LineColor](#linecolor) | ColorValue | Specifies the line color of the shape. |
| [CompoundType](#compoundtype) | CompoundType | Specifies the line CompoundType of the shape. |
| [LinePattern](#linepattern) | LinePattern | Specifies the line pattern of the shape |
| [Rounding](#rounding) | DoubleValue | Specifies the radius of the rounding arc applied where two contiguous segments of a path meet. For example, rounding can |
| [EndArrowSize](#endarrowsize) | ArrowSize | Specifies the size of the arrowhead at the end of the line. |
| [BeginArrow](#beginarrow) | IntValue | Indicates whether a line has an arrowhead or other line end format at its first vertex. Enter a number from 0 to 45 or t |
| [EndArrow](#endarrow) | IntValue | Indicates whether a line has an arrowhead or other line-end format at its last vertex. |
| [LineCap](#linecap) | BoolValue | Specifies whether a line has rounded or square line ends. |
| [BeginArrowSize](#beginarrowsize) | ArrowSize | Determines the size of the arrowhead at the beginning of the line. Enter a number from 0 to 6. |
| [LineColorTrans](#linecolortrans) | DoubleValue | Specifies the transparency level of a shape's line color, from 0 (opaque) to 1 (completely transparent). The default is  |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### Line.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### Line.LineWeight property {#lineweight}

Specifies the line weight of a shape. Line weight is independent of the scale of the drawing. If the drawing is scaled, the line weight remains the same.

**Type:** DoubleValue

### Line.GradientLine property {#gradientline}

Contains the current gradient line formatting values for the shape

**Type:** GradientFill

### Line.LineColor property {#linecolor}

Specifies the line color of the shape.

**Type:** ColorValue

### Line.CompoundType property {#compoundtype}

Specifies the line CompoundType of the shape.

**Type:** CompoundType

### Line.LinePattern property {#linepattern}

Specifies the line pattern of the shape

**Type:** LinePattern

### Line.Rounding property {#rounding}

Specifies the radius of the rounding arc applied where two contiguous segments of a path meet. For example, rounding can be used to give a rectangle rounded corners.

**Type:** DoubleValue

### Line.EndArrowSize property {#endarrowsize}

Specifies the size of the arrowhead at the end of the line.

**Type:** ArrowSize

### Line.BeginArrow property {#beginarrow}

Indicates whether a line has an arrowhead or other line end format at its first vertex. Enter a number from 0 to 45 or the USE function with the name of a custom line end.

**Type:** IntValue

### Line.EndArrow property {#endarrow}

Indicates whether a line has an arrowhead or other line-end format at its last vertex.

**Type:** IntValue

### Line.LineCap property {#linecap}

Specifies whether a line has rounded or square line ends.

**Type:** BoolValue

### Line.BeginArrowSize property {#beginarrowsize}

Determines the size of the arrowhead at the beginning of the line. Enter a number from 0 to 6.

**Type:** ArrowSize

### Line.LineColorTrans property {#linecolortrans}

Specifies the transparency level of a shape's line color, from 0 (opaque) to 1 (completely transparent). The default is 0.

**Type:** DoubleValue

### deepClone() {#deepclone}

Creates deep copy of this instance.
