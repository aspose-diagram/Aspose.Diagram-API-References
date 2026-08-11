---
title: "PageProps"
linktitle: "PageProps"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains cells that control page attributes, such as the page width, height, and scale."
type: docs
weight: 2310
url: /python-java/asposediagram.api/pageprops/
---

## PageProps class

Contains cells that control page attributes, such as the page width, height, and scale.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [PageWidth](#pagewidth) | DoubleValue | Specifies the width of the page in drawing units. |
| [PageHeight](#pageheight) | DoubleValue | Specifies the height of the page in drawing units. |
| [ShdwOffsetX](#shdwoffsetx) | DoubleValue | Specifies the distance in page units that a shape's drop shadow is offset horizontally from the shape. |
| [ShdwOffsetY](#shdwoffsety) | DoubleValue | Specifies the distance in page units that a shape's drop shadow is offset vertically from the shape. |
| [PageScale](#pagescale) | DoubleValue | Specifies the value of the default page unit in the current drawing scale. The drawing scale for the page is the ratio o |
| [DrawingScale](#drawingscale) | DoubleValue | Represents the value of the drawing unit in the current drawing scale. The drawing scale for the page is the ratio of th |
| [DrawingSizeType](#drawingsizetype) | DrawingSizeType | Specifies the drawing size of a page. |
| [DrawingScaleType](#drawingscaletype) | DrawingScaleType | Specifies the type of drawing scale to use for a page. |
| [InhibitSnap](#inhibitsnap) | BoolValue | Specifies whether the shapes on a foreground page snap to other objects on the page and shapes on the background page. |
| [UIVisibility](#uivisibility) | UIVisibility | Determines whether the page name is exposed in the user interface (UI). A value of one specifies that the page is not vi |
| [ShdwType](#shdwtype) | ShdwType | Indicates the default shadow type for a page. |
| [ShdwObliqueAngle](#shdwobliqueangle) | DoubleValue | Contains a number that specifies the angle of oblique direction when the default page shadow type is applied. |
| [ShdwScaleFactor](#shdwscalefactor) | DoubleValue | Specifies the percentage to enlarge or reduce a shape's shadow. |
| [DrawingResizeType](#drawingresizetype) | DrawingResizeType | Determines whether the drawing page resizes automatically to fit the diagram. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### PageProps.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### PageProps.PageWidth property {#pagewidth}

Specifies the width of the page in drawing units.

**Type:** DoubleValue

### PageProps.PageHeight property {#pageheight}

Specifies the height of the page in drawing units.

**Type:** DoubleValue

### PageProps.ShdwOffsetX property {#shdwoffsetx}

Specifies the distance in page units that a shape's drop shadow is offset horizontally from the shape.

**Type:** DoubleValue

### PageProps.ShdwOffsetY property {#shdwoffsety}

Specifies the distance in page units that a shape's drop shadow is offset vertically from the shape.

**Type:** DoubleValue

### PageProps.PageScale property {#pagescale}

Specifies the value of the default page unit in the current drawing scale. The drawing scale for the page is the ratio of the page unit in the PageScale element to the drawing unit shown in the DrawingScale element.

**Type:** DoubleValue

### PageProps.DrawingScale property {#drawingscale}

Represents the value of the drawing unit in the current drawing scale. The drawing scale for the page is the ratio of the page unit contained in the PageScale element to the drawing unit. The units of this element determine default length (DL) units for the page.

**Type:** DoubleValue

### PageProps.DrawingSizeType property {#drawingsizetype}

Specifies the drawing size of a page.

**Type:** DrawingSizeType

### PageProps.DrawingScaleType property {#drawingscaletype}

Specifies the type of drawing scale to use for a page.

**Type:** DrawingScaleType

### PageProps.InhibitSnap property {#inhibitsnap}

Specifies whether the shapes on a foreground page snap to other objects on the page and shapes on the background page.

**Type:** BoolValue

### PageProps.UIVisibility property {#uivisibility}

Determines whether the page name is exposed in the user interface (UI). A value of one specifies that the page is not visible; a value of zero specifies the page is visible

**Type:** UIVisibility

### PageProps.ShdwType property {#shdwtype}

Indicates the default shadow type for a page.

**Type:** ShdwType

### PageProps.ShdwObliqueAngle property {#shdwobliqueangle}

Contains a number that specifies the angle of oblique direction when the default page shadow type is applied.

**Type:** DoubleValue

### PageProps.ShdwScaleFactor property {#shdwscalefactor}

Specifies the percentage to enlarge or reduce a shape's shadow.

**Type:** DoubleValue

### PageProps.DrawingResizeType property {#drawingresizetype}

Determines whether the drawing page resizes automatically to fit the diagram.

**Type:** DrawingResizeType

### deepClone() {#deepclone}

Creates deep copy of this instance.
