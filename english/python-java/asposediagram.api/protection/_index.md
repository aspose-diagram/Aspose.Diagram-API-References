---
title: "Protection"
linktitle: "Protection"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances."
type: docs
weight: 2620
url: /python-java/asposediagram.api/protection/
---

## Protection class

Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances. It also does not protect against changes made in the ShapeSheet window.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [LockWidth](#lockwidth) | BoolValue | Specifies whether the width of the shape is locked so that it remains unchanged when the shape is resized. |
| [LockHeight](#lockheight) | BoolValue | Specifies whether the height of the shape is locked. If locked, its height remains unchanged when the shape is resized. |
| [LockMoveX](#lockmovex) | BoolValue | Specifies whether the horizontal position of the shape is locked so that it cannot be moved horizontally. |
| [LockMoveY](#lockmovey) | BoolValue | Specifies whether the vertical position of the shape is locked so that it cannot be moved vertically. |
| [LockAspect](#lockaspect) | BoolValue | Specifies whether the aspect ratio of the shape is locked. If locked, the shape can only be sized proportionally; it can |
| [LockDelete](#lockdelete) | BoolValue | Specifies whether a shape is locked against being deleted. |
| [LockBegin](#lockbegin) | BoolValue | Specifies whether the begin point of a 1-D shape is locked to a specific location. |
| [LockEnd](#lockend) | BoolValue | Specifies whether the end point of a 1-D shape is locked to a specific location. |
| [LockRotate](#lockrotate) | BoolValue | Specifies whether the shape is locked against being rotated with the Rotation tool or the Rotate Left or Rotate Right co |
| [LockCrop](#lockcrop) | BoolValue | Specifies whether a foreign object is locked against being cropped with the Crop tool in Microsoft Visio. |
| [LockVtxEdit](#lockvtxedit) | BoolValue | Specifies whether the vertices of a shape are locked so that they cannot be edited with any tools on the toolbar. |
| [LockTextEdit](#locktextedit) | BoolValue | Specifies whether the text of a shape is locked so that it cannot be edited. However, the text may still be formatted by |
| [LockFormat](#lockformat) | BoolValue | Specifies whether the formatting of a shape is locked so it cannot be changed. Specifically, this element protects again |
| [LockGroup](#lockgroup) | BoolValue | Specifies whether a group is locked so that it cannot be ungrouped. |
| [LockCalcWH](#lockcalcwh) | BoolValue | Specifies whether a shape's selection rectangle is locked so it cannot be recalculated when a vertex is edited or an ele |
| [LockSelect](#lockselect) | BoolValue | Specifies whether a shape's selection rectangle is locked so it cannot be recalculated when a vertex is edited or an ele |
| [LockCustProp](#lockcustprop) | BoolValue | Determines whether the user can add, delete, or modify custom properties in the user interface (UI) by using the Define  |
| [LockFromGroupFormat](#lockfromgroupformat) | BoolValue | Allows a subshape to block formatting changes that get applied to a parent group shape in the Visio user interface and w |
| [LockThemeColors](#lockthemecolors) | BoolValue | Prevents users from applying theme colors to the shape. |
| [LockThemeEffects](#lockthemeeffects) | BoolValue | Prevents users from applying theme effects to the shape. |

### Protection.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### Protection.LockWidth property {#lockwidth}

Specifies whether the width of the shape is locked so that it remains unchanged when the shape is resized.

**Type:** BoolValue

### Protection.LockHeight property {#lockheight}

Specifies whether the height of the shape is locked. If locked, its height remains unchanged when the shape is resized.

**Type:** BoolValue

### Protection.LockMoveX property {#lockmovex}

Specifies whether the horizontal position of the shape is locked so that it cannot be moved horizontally.

**Type:** BoolValue

### Protection.LockMoveY property {#lockmovey}

Specifies whether the vertical position of the shape is locked so that it cannot be moved vertically.

**Type:** BoolValue

### Protection.LockAspect property {#lockaspect}

Specifies whether the aspect ratio of the shape is locked. If locked, the shape can only be sized proportionally; it cannot be sized in a single dimension.

**Type:** BoolValue

### Protection.LockDelete property {#lockdelete}

Specifies whether a shape is locked against being deleted.

**Type:** BoolValue

### Protection.LockBegin property {#lockbegin}

Specifies whether the begin point of a 1-D shape is locked to a specific location.

**Type:** BoolValue

### Protection.LockEnd property {#lockend}

Specifies whether the end point of a 1-D shape is locked to a specific location.

**Type:** BoolValue

### Protection.LockRotate property {#lockrotate}

Specifies whether the shape is locked against being rotated with the Rotation tool or the Rotate Left or Rotate Right commands in Microsoft Visio.

**Type:** BoolValue

### Protection.LockCrop property {#lockcrop}

Specifies whether a foreign object is locked against being cropped with the Crop tool in Microsoft Visio.

**Type:** BoolValue

### Protection.LockVtxEdit property {#lockvtxedit}

Specifies whether the vertices of a shape are locked so that they cannot be edited with any tools on the toolbar.

**Type:** BoolValue

### Protection.LockTextEdit property {#locktextedit}

Specifies whether the text of a shape is locked so that it cannot be edited. However, the text may still be formatted by applying a style, using the Style options on the Font tab of the Text dialog box.

**Type:** BoolValue

### Protection.LockFormat property {#lockformat}

Specifies whether the formatting of a shape is locked so it cannot be changed. Specifically, this element protects against changing text, line, and fill formatting, or changing which Style element the shape inherits from.

**Type:** BoolValue

### Protection.LockGroup property {#lockgroup}

Specifies whether a group is locked so that it cannot be ungrouped.

**Type:** BoolValue

### Protection.LockCalcWH property {#lockcalcwh}

Specifies whether a shape's selection rectangle is locked so it cannot be recalculated when a vertex is edited or an element type is changed in the Geom element.

**Type:** BoolValue

### Protection.LockSelect property {#lockselect}

Specifies whether a shape's selection rectangle is locked so it cannot be recalculated when a vertex is edited or an element type is changed in the Geom element.

**Type:** BoolValue

### Protection.LockCustProp property {#lockcustprop}

Determines whether the user can add, delete, or modify custom properties in the user interface (UI) by using the Define Custom Properties dialog box.

**Type:** BoolValue

### Protection.LockFromGroupFormat property {#lockfromgroupformat}

Allows a subshape to block formatting changes that get applied to a parent group shape in the Visio user interface and would otherwise cascade down to individual group shapes.

**Type:** BoolValue

### Protection.LockThemeColors property {#lockthemecolors}

Prevents users from applying theme colors to the shape.

**Type:** BoolValue

### Protection.LockThemeEffects property {#lockthemeeffects}

Prevents users from applying theme effects to the shape.

**Type:** BoolValue
