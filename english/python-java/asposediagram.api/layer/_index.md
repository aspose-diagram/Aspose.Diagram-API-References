---
title: "Layer"
linktitle: "Layer"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that define a single layer and its properties for a page."
type: docs
weight: 1750
url: /python-java/asposediagram.api/layer/
---

## Layer class

Contains elements that define a single layer and its properties for a page.

## Constructors

| Name | Description |
| --- | --- |
| [Layer](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [IX](#ix) | int | The zero-based index of the element within its parent element. |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [Name](#name) | Str2Value | Name element specifies the name of a layer. |
| [Color](#color) | ColorValue | The index of the color in the color table used toThe index of the color in the color table used to display the layer or  |
| [IsColorChecked](#iscolorchecked) | int | A flag indicating whether the element has been checked locally. A value of 1 indicates that the element was checked loca |
| [Status](#status) | BoolValue | Specifies whether the layer is a valid layer for a document. |
| [Visible](#visible) | BoolValue | Specifies whether shapes belonging to the layer are visible on the drawing page. |
| [Print](#print) | BoolValue | Specifies whether shapes belonging to the layer are printed when the drawing is printed. |
| [Active](#active) | BoolValue | Specifies whether a layer is active. Shapes that are not preassigned to layers are assigned to the active layer(s) when  |
| [Lock](#lock) | BoolValue | Specifies whether shapes belonging to the layer are locked against being selected or edited. |
| [Snap](#snap) | BoolValue | Specifies whether other shapes can snap to shapes assigned to the layer. Shapes assigned to the layer can snap to other  |
| [Glue](#glue) | BoolValue | Specifies whether shapes belonging to the layer can be glued to. |
| [NameUniv](#nameuniv) | Str2Value | Specifies the universal name of a layer. |
| [ColorTrans](#colortrans) | DoubleValue | Determines the degree of transparency for a layer or shape's text color, from 0 (completely opaque) to 1 (completely tra |

### Layer() {#constructor}

Constructor.

### Layer.IX property {#ix}

The zero-based index of the element within its parent element.

**Type:** int

### Layer.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### Layer.Name property {#name}

Name element specifies the name of a layer.

**Type:** Str2Value

### Layer.Color property {#color}

The index of the color in the color table used toThe index of the color in the color table used to display the layer or An RGB value specifying a custom color not in the color table (for example, #ff9900 ). display the layer

**Type:** ColorValue

### Layer.IsColorChecked property {#iscolorchecked}

A flag indicating whether the element has been checked locally. A value of 1 indicates that the element was checked locally. The value of the property is BOOL integer constant.

**Type:** int

### Layer.Status property {#status}

Specifies whether the layer is a valid layer for a document.

**Type:** BoolValue

### Layer.Visible property {#visible}

Specifies whether shapes belonging to the layer are visible on the drawing page.

**Type:** BoolValue

### Layer.Print property {#print}

Specifies whether shapes belonging to the layer are printed when the drawing is printed.

**Type:** BoolValue

### Layer.Active property {#active}

Specifies whether a layer is active. Shapes that are not preassigned to layers are assigned to the active layer(s) when dropped on the drawing page.

**Type:** BoolValue

### Layer.Lock property {#lock}

Specifies whether shapes belonging to the layer are locked against being selected or edited.

**Type:** BoolValue

### Layer.Snap property {#snap}

Specifies whether other shapes can snap to shapes assigned to the layer. Shapes assigned to the layer can snap to other shapes, but other shapes cannot snap to them.

**Type:** BoolValue

### Layer.Glue property {#glue}

Specifies whether shapes belonging to the layer can be glued to.

**Type:** BoolValue

### Layer.NameUniv property {#nameuniv}

Specifies the universal name of a layer.

**Type:** Str2Value

### Layer.ColorTrans property {#colortrans}

Determines the degree of transparency for a layer or shape's text color, from 0 (completely opaque) to 1 (completely transparent).

**Type:** DoubleValue
