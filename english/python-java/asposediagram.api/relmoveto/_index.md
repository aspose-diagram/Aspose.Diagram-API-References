---
title: "RelMoveTo"
linktitle: "RelMoveTo"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vertex after a break in a path.Coordinates a"
type: docs
weight: 2710
url: /python-java/asposediagram.api/relmoveto/
---

## RelMoveTo class

Contains the x- and y-coordinates of the first vertex of a shape, or contains the x- and y-coordinates of the first vertex after a break in a path.Coordinates are specified as relative coordinates.

## Constructors

| Name | Description |
| --- | --- |
| [RelMoveTo](#constructor) | Creates an instance of the MoveTo class. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [IX](#ix) | int | The zero-based index of the element within its parent element. |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [X](#x) | DoubleValue | X element represents the x-coordinate of the first vertex of a path. If the MoveTo element appears between two elements, |
| [Y](#y) | DoubleValue | Y element represents the y-coordinate of the first vertex of a path. If the MoveTo element appears between two elements, |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### RelMoveTo() {#constructor}

Creates an instance of the MoveTo class.

### RelMoveTo.IX property {#ix}

The zero-based index of the element within its parent element.

**Type:** int

### RelMoveTo.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### RelMoveTo.X property {#x}

X element represents the x-coordinate of the first vertex of a path. If the MoveTo element appears between two elements, the X element represents the x-coordinate of the first vertex after the break in the path

**Type:** DoubleValue

### RelMoveTo.Y property {#y}

Y element represents the y-coordinate of the first vertex of a path. If the MoveTo element appears between two elements, the Y element represents the y-coordinate of the first vertex after the break in the path.

**Type:** DoubleValue

### deepClone() {#deepclone}

Creates deep copy of this instance.
