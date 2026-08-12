---
title: "Para"
linktitle: "Para"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains the paragraph formatting elements for the shape's text, such as indents, line spacing, bullets, and horizontal alignment of paragraphs."
type: docs
weight: 2330
url: /python-java/asposediagram.api/para/
---

## Para class

Contains the paragraph formatting elements for the shape's text, such as indents, line spacing, bullets, and horizontal alignment of paragraphs.

## Constructors

| Name | Description |
| --- | --- |
| [Para](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [IX](#ix) | int | The zero-based index of the element within its parent element. |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [IndFirst](#indfirst) | DoubleValue | Specifies the distance the first line of each paragraph in the shape's text block is indented from the left indent of th |
| [IndLeft](#indleft) | DoubleValue | Specifies the distance all lines of text in a paragraph are indented from the left margin of the text block. This value  |
| [IndRight](#indright) | DoubleValue | Specifies the distance all lines of text in a paragraph are indented from the right margin of the text block. This value |
| [SpLine](#spline) | DoubleValue | Specifies the distance between one line of text and the next, where 100% is the height of a text line. |
| [SpBefore](#spbefore) | DoubleValue | Specifies the amount of space inserted before each paragraph in the shape's text block. |
| [SpAfter](#spafter) | DoubleValue | Specifies the amount of space inserted after each paragraph in the shape's text block. |
| [HorzAlign](#horzalign) | HorzAlign | Specifies the horizontal alignment of text in the shape's text block. |
| [Bullet](#bullet) | Bullet | Determines the bullet style. |
| [BulletStr](#bulletstr) | Str2Value | "Used to create a custom bullet style. Enter the style as a string (within quotation marks). For example, you could ente |
| [BulletFont](#bulletfont) | IntValue | Represents the number of the font used to format the text when a custom bullet string is specified and the value in the  |
| [LocalizeBulletFont](#localizebulletfont) | LocalizeFont | Specifies whether the bullet font should be localized (translated into another language). |
| [BulletFontSize](#bulletfontsize) | DoubleValue | Specifies the size of a bullet. |
| [TextPosAfterBullet](#textposafterbullet) | DoubleValue | Represents the distance between the first line of the paragraph and the bullet. |
| [Flags](#flags) | BoolValue | Indicates whether the text direction is left to right or right to left. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### Para() {#constructor}

Constructor.

### Para.IX property {#ix}

The zero-based index of the element within its parent element.

**Type:** int

### Para.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### Para.IndFirst property {#indfirst}

Specifies the distance the first line of each paragraph in the shape's text block is indented from the left indent of the paragraph. This value is independent of the scale of the drawing. If the drawing is scaled, the first line indent remains the same.

**Type:** DoubleValue

### Para.IndLeft property {#indleft}

Specifies the distance all lines of text in a paragraph are indented from the left margin of the text block. This value is independent of the scale of the drawing. If the drawing is scaled, the left indent remains the same.

**Type:** DoubleValue

### Para.IndRight property {#indright}

Specifies the distance all lines of text in a paragraph are indented from the right margin of the text block. This value is independent of the scale of the drawing. If the drawing is scaled, the right indent remains the same.

**Type:** DoubleValue

### Para.SpLine property {#spline}

Specifies the distance between one line of text and the next, where 100% is the height of a text line.

**Type:** DoubleValue

### Para.SpBefore property {#spbefore}

Specifies the amount of space inserted before each paragraph in the shape's text block.

**Type:** DoubleValue

### Para.SpAfter property {#spafter}

Specifies the amount of space inserted after each paragraph in the shape's text block.

**Type:** DoubleValue

### Para.HorzAlign property {#horzalign}

Specifies the horizontal alignment of text in the shape's text block.

**Type:** HorzAlign

### Para.Bullet property {#bullet}

Determines the bullet style.

**Type:** Bullet

### Para.BulletStr property {#bulletstr}

"Used to create a custom bullet style. Enter the style as a string (within quotation marks). For example, you could enter the string, ""ooo."""

**Type:** Str2Value

### Para.BulletFont property {#bulletfont}

Represents the number of the font used to format the text when a custom bullet string is specified and the value in the Bullet element is non-zero.

**Type:** IntValue

### Para.LocalizeBulletFont property {#localizebulletfont}

Specifies whether the bullet font should be localized (translated into another language).

**Type:** LocalizeFont

### Para.BulletFontSize property {#bulletfontsize}

Specifies the size of a bullet.

**Type:** DoubleValue

### Para.TextPosAfterBullet property {#textposafterbullet}

Represents the distance between the first line of the paragraph and the bullet.

**Type:** DoubleValue

### Para.Flags property {#flags}

Indicates whether the text direction is left to right or right to left.

**Type:** BoolValue

### deepClone() {#deepclone}

Creates deep copy of this instance.
