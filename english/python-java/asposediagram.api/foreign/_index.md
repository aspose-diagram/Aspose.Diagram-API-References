---
title: "Foreign"
linktitle: "Foreign"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document."
type: docs
weight: 1330
url: /python-java/asposediagram.api/foreign/
---

## Foreign class

Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [ImgOffsetX](#imgoffsetx) | DoubleValue | Determines the distance the object is offset horizontally from the origin of the object's border. The default value is 0 |
| [ImgOffsetY](#imgoffsety) | DoubleValue | Determines the distance the object is offset vertically from the origin of the object's border. The default value is 0;  |
| [ImgWidth](#imgwidth) | DoubleValue | Determines the width of the object's image within its border. The default formula is: F="Width*1". |
| [ImgHeight](#imgheight) | DoubleValue | Determines the height of the object's image within its border. The default formula is: F="Height*1". |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### Foreign.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### Foreign.ImgOffsetX property {#imgoffsetx}

Determines the distance the object is offset horizontally from the origin of the object's border. The default value is 0; the default formula is F="ImgWidth*0".

**Type:** DoubleValue

### Foreign.ImgOffsetY property {#imgoffsety}

Determines the distance the object is offset vertically from the origin of the object's border. The default value is 0; the default formula is F="ImgHeight*0".

**Type:** DoubleValue

### Foreign.ImgWidth property {#imgwidth}

Determines the width of the object's image within its border. The default formula is: F="Width*1".

**Type:** DoubleValue

### Foreign.ImgHeight property {#imgheight}

Determines the height of the object's image within its border. The default formula is: F="Height*1".

**Type:** DoubleValue

### deepClone() {#deepclone}

Creates deep copy of this instance.
