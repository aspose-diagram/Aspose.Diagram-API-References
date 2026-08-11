---
title: "TextXForm"
linktitle: "TextXForm"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that specify positioning information about a shape's text block."
type: docs
weight: 3480
url: /python-java/asposediagram.api/textxform/
---

## TextXForm class

Contains elements that specify positioning information about a shape's text block.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [TxtPinX](#txtpinx) | DoubleValue | Specifies the x-coordinate of the text block's center of rotation in relation to the origin of the shape. The default fo |
| [TxtPinY](#txtpiny) | DoubleValue | Specifies the y-coordinate of the text block's center of rotation in relation to the origin of the shape. The default fo |
| [TxtWidth](#txtwidth) | DoubleValue | Specifies the width of the text block. The default formula, which evaluates to the width of the shape, is F="Width*1". |
| [TxtHeight](#txtheight) | DoubleValue | Specifies the height of the text block. The default formula, which evaluates to the height of the shape, is F="Height*1" |
| [TxtLocPinX](#txtlocpinx) | DoubleValue | Specifies the x-coordinate of the text block's center of rotation in relation to the origin of the text block. The defau |
| [TxtLocPinY](#txtlocpiny) | DoubleValue | Specifies the y-coordinate of the text block's center of rotation relative to the origin of the text block. The default  |
| [TxtAngle](#txtangle) | DoubleValue | Specifies the text block's current angle of rotation in relation to the x-axis of the shape. The default is 0 degrees. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### TextXForm.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### TextXForm.TxtPinX property {#txtpinx}

Specifies the x-coordinate of the text block's center of rotation in relation to the origin of the shape. The default formula, which evaluates to the horizontal center of the shape, is F="Width*0.5".

**Type:** DoubleValue

### TextXForm.TxtPinY property {#txtpiny}

Specifies the y-coordinate of the text block's center of rotation in relation to the origin of the shape. The default formula, which evaluates to the vertical center of the shape, is F="Height*0.5".

**Type:** DoubleValue

### TextXForm.TxtWidth property {#txtwidth}

Specifies the width of the text block. The default formula, which evaluates to the width of the shape, is F="Width*1".

**Type:** DoubleValue

### TextXForm.TxtHeight property {#txtheight}

Specifies the height of the text block. The default formula, which evaluates to the height of the shape, is F="Height*1".

**Type:** DoubleValue

### TextXForm.TxtLocPinX property {#txtlocpinx}

Specifies the x-coordinate of the text block's center of rotation in relation to the origin of the text block. The default formula, which evaluates to the horizontal center of the text block, is F="TxtWidth*0.5".

**Type:** DoubleValue

### TextXForm.TxtLocPinY property {#txtlocpiny}

Specifies the y-coordinate of the text block's center of rotation relative to the origin of the text block. The default formula, which evaluates to the vertical center of the text block, is F="TxtHeight*0.5".

**Type:** DoubleValue

### TextXForm.TxtAngle property {#txtangle}

Specifies the text block's current angle of rotation in relation to the x-axis of the shape. The default is 0 degrees.

**Type:** DoubleValue

### deepClone() {#deepclone}

Creates deep copy of this instance.
