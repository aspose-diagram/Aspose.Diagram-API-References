---
title: "LayerMem"
linktitle: "LayerMem"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains the LayerMember element, which specifies each layer to which the shape is assigned."
type: docs
weight: 1770
url: /python-java/asposediagram.api/layermem/
---

## LayerMem class

Contains the LayerMember element, which specifies each layer to which the shape is assigned.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [LayerMember](#layermember) | Str2Value | Specifies the layer or layers to which the shape is assigned. Layer assignment is specified based on the zero-based inde |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### LayerMem.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### LayerMem.LayerMember property {#layermember}

Specifies the layer or layers to which the shape is assigned. Layer assignment is specified based on the zero-based index of layers for the page. If a shape is assigned to more than one layer, each layer index appears separated by a semicolon.

**Type:** Str2Value

### deepClone() {#deepclone}

Creates deep copy of this instance.
