---
title: "Field"
linktitle: "Field"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that specify functions and formulas inserted in the shape's text."
type: docs
weight: 1170
url: /python-java/asposediagram.api/field/
---

## Field class

Contains elements that specify functions and formulas inserted in the shape's text.

## Constructors

| Name | Description |
| --- | --- |
| [Field](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [IX](#ix) | int | The zero-based index of the element within its parent element. |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [Value](#value) | Value | It contains the value for a text field. |
| [DisplayValue](#displayvalue) | String | Gets the formatted string value of this field . |
| [EditMode](#editmode) | DoubleValue | Reserved for future use. |
| [Format](#format) | Value | Format element specifies the formatting for a text field that is a string, number, date or time, duration, or currency.  |
| [Type](#type) | TypeField | Type specifies a data type for the text field value. |
| [UICat](#uicat) | DoubleValue | Specifies the category of an inserted field in versions of Microsoft Visio earlier than Visio 2000. |
| [UICod](#uicod) | DoubleValue | Specifies the code of an inserted field in versions of Microsoft Visio earlier than Visio 2000. |
| [UIFmt](#uifmt) | DoubleValue | Specifies the format of an inserted field in versions of Microsoft Visio earlier than Visio 2000. |
| [Calendar](#calendar) | Calendar | Determines the calendar that is used for custom properties, text fields, and element formulas. |
| [ObjectKind](#objectkind) | ObjectKind | Indicates the type of text field. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### Field() {#constructor}

Constructor.

### Field.IX property {#ix}

The zero-based index of the element within its parent element.

**Type:** int

### Field.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### Field.Value property {#value}

It contains the value for a text field.

**Type:** Value

### Field.DisplayValue property {#displayvalue}

Gets the formatted string value of this field .

**Type:** String

### Field.EditMode property {#editmode}

Reserved for future use.

**Type:** DoubleValue

### Field.Format property {#format}

Format element specifies the formatting for a text field that is a string, number, date or time, duration, or currency. The text field type is specified in the corresponding Type element.

**Type:** Value

### Field.Type property {#type}

Type specifies a data type for the text field value.

**Type:** TypeField

### Field.UICat property {#uicat}

Specifies the category of an inserted field in versions of Microsoft Visio earlier than Visio 2000.

**Type:** DoubleValue

### Field.UICod property {#uicod}

Specifies the code of an inserted field in versions of Microsoft Visio earlier than Visio 2000.

**Type:** DoubleValue

### Field.UIFmt property {#uifmt}

Specifies the format of an inserted field in versions of Microsoft Visio earlier than Visio 2000.

**Type:** DoubleValue

### Field.Calendar property {#calendar}

Determines the calendar that is used for custom properties, text fields, and element formulas.

**Type:** Calendar

### Field.ObjectKind property {#objectkind}

Indicates the type of text field.

**Type:** ObjectKind

### deepClone() {#deepclone}

Creates deep copy of this instance.
