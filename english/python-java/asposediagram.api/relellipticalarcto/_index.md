---
title: "RelEllipticalArcTo"
linktitle: "RelEllipticalArcTo"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that specify information about an elliptical arc.Coordinates are specified as relative coordinates."
type: docs
weight: 2670
url: /python-java/asposediagram.api/relellipticalarcto/
---

## RelEllipticalArcTo class

Contains elements that specify information about an elliptical arc.Coordinates are specified as relative coordinates.

## Constructors

| Name | Description |
| --- | --- |
| [RelEllipticalArcTo](#constructor) | Creates an instance of the EllipticalArcTo class. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [IX](#ix) | int | The zero-based index of the element within its parent element. |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [X](#x) | DoubleValue | The x-coordinate of the ending vertex of an elliptical arc. |
| [Y](#y) | DoubleValue | The y-coordinate of the ending vertex of an elliptical arc. |
| [A](#a) | DoubleValue | The x-coordinate of the arc's control point. The control point is best located about halfway between the beginning and e |
| [B](#b) | DoubleValue | The y-coordinate of an arc's control point. |
| [C](#c) | DoubleValue | The angle of an arc's major axis relative to the x-axis of its parent. |
| [D](#d) | DoubleValue | The ratio of an arc's major axis to its minor axis. Despite the usual meaning of these words, the major axis does not ha |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### RelEllipticalArcTo() {#constructor}

Creates an instance of the EllipticalArcTo class.

### RelEllipticalArcTo.IX property {#ix}

The zero-based index of the element within its parent element.

**Type:** int

### RelEllipticalArcTo.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### RelEllipticalArcTo.X property {#x}

The x-coordinate of the ending vertex of an elliptical arc.

**Type:** DoubleValue

### RelEllipticalArcTo.Y property {#y}

The y-coordinate of the ending vertex of an elliptical arc.

**Type:** DoubleValue

### RelEllipticalArcTo.A property {#a}

The x-coordinate of the arc's control point. The control point is best located about halfway between the beginning and ending vertices of the arc. Otherwise, the arc may grow to an extreme size in order to pass through the control point, with unpredictable results.

**Type:** DoubleValue

### RelEllipticalArcTo.B property {#b}

The y-coordinate of an arc's control point.

**Type:** DoubleValue

### RelEllipticalArcTo.C property {#c}

The angle of an arc's major axis relative to the x-axis of its parent.

**Type:** DoubleValue

### RelEllipticalArcTo.D property {#d}

The ratio of an arc's major axis to its minor axis. Despite the usual meaning of these words, the major axis does not have to be greater than the minor axis, so this ratio does not have to be greater than 1. Setting this element to a value less than or equal to 0 or greater than 1000 can lead to unpredictable results.

**Type:** DoubleValue

### deepClone() {#deepclone}

Creates deep copy of this instance.
