---
title: "Fill"
linktitle: "Fill"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color."
type: docs
weight: 1230
url: /python-java/asposediagram.api/fill/
---

## Fill class

Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [FillForegnd](#fillforegnd) | ColorValue | Specifies the color used for the foreground (stroke) of the shape's fill pattern. |
| [GradientFill](#gradientfill) | GradientFill | Contains the current gradient fill formatting values for the shape |
| [FillBkgnd](#fillbkgnd) | ColorValue | Specifies the color used for the background of the shape's fill pattern. |
| [FillPattern](#fillpattern) | IntValue | Specifies the fill pattern for the shape. |
| [ShdwForegnd](#shdwforegnd) | ColorValue | Specifies the color used for the foreground (stroke) of the shape's drop shadow fill pattern. |
| [ShdwBkgnd](#shdwbkgnd) | ColorValue | Specifies the color used for the background (fill) of the shape's drop shadow fill pattern. |
| [ShdwPattern](#shdwpattern) | IntValue | Specifies the fill pattern for a shape's shadow. |
| [FillForegndTrans](#fillforegndtrans) | DoubleValue | Specifies the transparency level for the foreground (fill) color of the shape's fill pattern, from 0 (completely opaque) |
| [FillBkgndTrans](#fillbkgndtrans) | DoubleValue | Specifies the transparency level for the background (fill) color of the shape's fill pattern, from 0 (completely opaque) |
| [ShdwForegndTrans](#shdwforegndtrans) | DoubleValue | Specifies transparency level for the foreground (stroke) of the shape's drop shadow fill pattern, from 0.0 (completely o |
| [ShdwBkgndTrans](#shdwbkgndtrans) | DoubleValue | Specifies transparency level for the background (fill) of the shape's drop shadow fill pattern, from 0.0 (completely opa |
| [ShapeShdwType](#shapeshdwtype) | ShapeShdwType | Specifies the type of shadow for a shape. |
| [ShapeShdwShow](#shapeshdwshow) | ShapeShdwShow | Specifies the type of shadow for a shape. |
| [ShapeShdwOffsetX](#shapeshdwoffsetx) | DoubleValue | Determines the distance in page units that a shape's shadow is offset horizontally from the shape. |
| [ShapeShdwOffsetY](#shapeshdwoffsety) | DoubleValue | Determines the distance in page units that a shape's shadow is offset vertically from the shape. |
| [ShapeShdwObliqueAngle](#shapeshdwobliqueangle) | DoubleValue | Specifies the angle of oblique direction of a shape's shadow. |
| [ShapeShdwScaleFactor](#shapeshdwscalefactor) | DoubleValue | Specifies the percentage by which the shadow of a shape can be enlarged or reduced. |
| [ShapeShdwBlur](#shapeshdwblur) | DoubleValue | Specifies the shadow blur size of a shape. cannot draw blur now, but can parse from vsdx now. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### Fill.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### Fill.FillForegnd property {#fillforegnd}

Specifies the color used for the foreground (stroke) of the shape's fill pattern.

**Type:** ColorValue

### Fill.GradientFill property {#gradientfill}

Contains the current gradient fill formatting values for the shape

**Type:** GradientFill

### Fill.FillBkgnd property {#fillbkgnd}

Specifies the color used for the background of the shape's fill pattern.

**Type:** ColorValue

### Fill.FillPattern property {#fillpattern}

Specifies the fill pattern for the shape.

**Type:** IntValue

### Fill.ShdwForegnd property {#shdwforegnd}

Specifies the color used for the foreground (stroke) of the shape's drop shadow fill pattern.

**Type:** ColorValue

### Fill.ShdwBkgnd property {#shdwbkgnd}

Specifies the color used for the background (fill) of the shape's drop shadow fill pattern.

**Type:** ColorValue

### Fill.ShdwPattern property {#shdwpattern}

Specifies the fill pattern for a shape's shadow.

**Type:** IntValue

### Fill.FillForegndTrans property {#fillforegndtrans}

Specifies the transparency level for the foreground (fill) color of the shape's fill pattern, from 0 (completely opaque) to 1 (completely transparent).

**Type:** DoubleValue

### Fill.FillBkgndTrans property {#fillbkgndtrans}

Specifies the transparency level for the background (fill) color of the shape's fill pattern, from 0 (completely opaque) to 1 (completely transparent).

**Type:** DoubleValue

### Fill.ShdwForegndTrans property {#shdwforegndtrans}

Specifies transparency level for the foreground (stroke) of the shape's drop shadow fill pattern, from 0.0 (completely opaque) to 1.0 (completely transparent).

**Type:** DoubleValue

### Fill.ShdwBkgndTrans property {#shdwbkgndtrans}

Specifies transparency level for the background (fill) of the shape's drop shadow fill pattern, from 0.0 (completely opaque) to 1.0 (completely transparent).

**Type:** DoubleValue

### Fill.ShapeShdwType property {#shapeshdwtype}

Specifies the type of shadow for a shape.

**Type:** ShapeShdwType

### Fill.ShapeShdwShow property {#shapeshdwshow}

Specifies the type of shadow for a shape.

**Type:** ShapeShdwShow

### Fill.ShapeShdwOffsetX property {#shapeshdwoffsetx}

Determines the distance in page units that a shape's shadow is offset horizontally from the shape.

**Type:** DoubleValue

### Fill.ShapeShdwOffsetY property {#shapeshdwoffsety}

Determines the distance in page units that a shape's shadow is offset vertically from the shape.

**Type:** DoubleValue

### Fill.ShapeShdwObliqueAngle property {#shapeshdwobliqueangle}

Specifies the angle of oblique direction of a shape's shadow.

**Type:** DoubleValue

### Fill.ShapeShdwScaleFactor property {#shapeshdwscalefactor}

Specifies the percentage by which the shadow of a shape can be enlarged or reduced.

**Type:** DoubleValue

### Fill.ShapeShdwBlur property {#shapeshdwblur}

Specifies the shadow blur size of a shape. cannot draw blur now, but can parse from vsdx now.

**Type:** DoubleValue

### deepClone() {#deepclone}

Creates deep copy of this instance.
