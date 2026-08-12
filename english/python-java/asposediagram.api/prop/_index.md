---
title: "Prop"
linktitle: "Prop"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements for defining custom properties and elements for associating data with a shape."
type: docs
weight: 2590
url: /python-java/asposediagram.api/prop/
---

## Prop class

Contains elements for defining custom properties and elements for associating data with a shape.

## Constructors

| Name | Description |
| --- | --- |
| [Prop](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Value](#value) | Value | Contains solution-specific, well-formed XML data that is prefixed in an explicit namespace and is stored with a document |
| [Name](#name) | String | The name of the element. |
| [NameU](#nameu) | String | The universal name of the element. |
| [IX](#ix) | int | The zero-based index of the element within its parent element. |
| [ID](#id) | int | The unique ID of the element within its parent element. |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [Prompt](#prompt) | Str2Value | Prompt element specifies descriptive or instructional text that appears to users in the Custom Properties dialog box whe |
| [Label](#label) | Str2Value | Specifies the label that appears to users in the Custom Properties dialog box. |
| [Format](#format) | StrValue | Format element specifies the formatting of a custom property that is a string, fixed list, number, variable list, date o |
| [SortKey](#sortkey) | Str2Value | It specifies a key that determines the order in which custom properties are listed in the application's user interface. |
| [Type](#type) | TypeProp | Type specifies a data type for the custom property value. |
| [Invisible](#invisible) | BoolValue | Invisible element specifies whether the custom property is visible in the Custom Properties dialog box in Microsoft Visi |
| [Verify](#verify) | BoolValue | Specifies whether the user is queried to enter custom property information for a shape when an instance is created or th |
| [LangID](#langid) | IntValue | Indicates the locale ID (LCID) of the language in which the cell formula, text, custom property, or comment was entered. |
| [Calendar](#calendar) | Calendar | Determines the calendar that is used for custom properties, text fields, and element formulas. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### Prop() {#constructor}

Constructor.

### Prop.Value property {#value}

Contains solution-specific, well-formed XML data that is prefixed in an explicit namespace and is stored with a document.

**Type:** Value

### Prop.Name property {#name}

The name of the element.

**Type:** String

### Prop.NameU property {#nameu}

The universal name of the element.

**Type:** String

### Prop.IX property {#ix}

The zero-based index of the element within its parent element.

**Type:** int

### Prop.ID property {#id}

The unique ID of the element within its parent element.

**Type:** int

### Prop.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### Prop.Prompt property {#prompt}

Prompt element specifies descriptive or instructional text that appears to users in the Custom Properties dialog box when the property is selected. This text also appears as a tool tip when the mouse pointer is paused over the property in the Custom Properties window.

**Type:** Str2Value

### Prop.Label property {#label}

Specifies the label that appears to users in the Custom Properties dialog box.

**Type:** Str2Value

### Prop.Format property {#format}

Format element specifies the formatting of a custom property that is a string, fixed list, number, variable list, date or time, duration, or currency. The custom property type is specified in the corresponding Type element.

**Type:** StrValue

### Prop.SortKey property {#sortkey}

It specifies a key that determines the order in which custom properties are listed in the application's user interface.

**Type:** Str2Value

### Prop.Type property {#type}

Type specifies a data type for the custom property value.

**Type:** TypeProp

### Prop.Invisible property {#invisible}

Invisible element specifies whether the custom property is visible in the Custom Properties dialog box in Microsoft Visio.

**Type:** BoolValue

### Prop.Verify property {#verify}

Specifies whether the user is queried to enter custom property information for a shape when an instance is created or the shape is duplicated or copied.

**Type:** BoolValue

### Prop.LangID property {#langid}

Indicates the locale ID (LCID) of the language in which the cell formula, text, custom property, or comment was entered.

**Type:** IntValue

### Prop.Calendar property {#calendar}

Determines the calendar that is used for custom properties, text fields, and element formulas.

**Type:** Calendar

### deepClone() {#deepclone}

Creates deep copy of this instance.
