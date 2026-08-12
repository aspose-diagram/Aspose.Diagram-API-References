---
title: "XForm"
linktitle: "XForm"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that control line attributes for a shape, such as pattern, weight, and color."
type: docs
weight: 3880
url: /python-java/asposediagram.api/xform/
---

## XForm class

Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine whether the line ends are formatted (for example, with an arrowhead), the size of line end formats, radius of the rounding circle applied to the line, and line cap style (round or square).

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [PinPos](#pinpos) | int | Specifies the pin position of the shape The value of the property is PinPosValue integer constant. |
| [PinX](#pinx) | DoubleValue | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent. |
| [PinY](#piny) | DoubleValue | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent. |
| [Width](#width) | DoubleValue | Contains the width of the associated shape in drawing units. |
| [Height](#height) | DoubleValue | Specifies the height of the shape in drawing units. |
| [LocPinX](#locpinx) | DoubleValue | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the origin of the shape. The default f |
| [LocPinY](#locpiny) | DoubleValue | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the origin of the shape. The default f |
| [Angle](#angle) | DoubleValue | Represents the shape's current angle of rotation in relation to its parent. |
| [FlipX](#flipx) | BoolValue | Indicates whether the shape has been flipped horizontally |
| [FlipY](#flipy) | BoolValue | Indicates whether the shape has been flipped vertically. |
| [ResizeMode](#resizemode) | ResizeMode | Specifies the current resize behavior setting for the shape when contained in a group. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### XForm.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### XForm.PinPos property {#pinpos}

Specifies the pin position of the shape The value of the property is PinPosValue integer constant.

**Type:** int

### XForm.PinX property {#pinx}

Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent.

**Type:** DoubleValue

### XForm.PinY property {#piny}

Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent.

**Type:** DoubleValue

### XForm.Width property {#width}

Contains the width of the associated shape in drawing units.

**Type:** DoubleValue

### XForm.Height property {#height}

Specifies the height of the shape in drawing units.

**Type:** DoubleValue

### XForm.LocPinX property {#locpinx}

Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the origin of the shape. The default formula for determining LocPinX is: F='Width* 0.5'.

**Type:** DoubleValue

### XForm.LocPinY property {#locpiny}

Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the origin of the shape. The default formula for determining LocPinY is: F='Height * 0.5'.

**Type:** DoubleValue

### XForm.Angle property {#angle}

Represents the shape's current angle of rotation in relation to its parent.

**Type:** DoubleValue

### XForm.FlipX property {#flipx}

Indicates whether the shape has been flipped horizontally

**Type:** BoolValue

### XForm.FlipY property {#flipy}

Indicates whether the shape has been flipped vertically.

**Type:** BoolValue

### XForm.ResizeMode property {#resizemode}

Specifies the current resize behavior setting for the shape when contained in a group.

**Type:** ResizeMode

### deepClone() {#deepclone}

Creates deep copy of this instance.
