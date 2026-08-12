---
title: "Act"
linktitle: "Act"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Defines custom command names that appear on an object's shortcut menu and specifies the actions that the commands take."
type: docs
weight: 20
url: /python-java/asposediagram.api/act/
---

## Act class

Defines custom command names that appear on an object's shortcut menu and specifies the actions that the commands take.

## Constructors

| Name | Description |
| --- | --- |
| [Act](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Name](#name) | String | The name of the element. |
| [NameU](#nameu) | String | The universal name of the element. |
| [ID](#id) | int | The unique ID of the element within its parent element. |
| [IX](#ix) | int | The zero-based index of the element within its parent element. |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [Menu](#menu) | Str2Value | Specifies the name of the command that appears on the shortcut menu for a shape or page. |
| [Action](#action) | DoubleValue | Contains the formula to execute when a user clicks the command name defined in the corresponding Menu element. |
| [Checked](#checked) | BoolValue | Determines whether a check mark is displayed beside the command name on a shape's shortcut menu. |
| [Disabled](#disabled) | BoolValue | Disabled element determines whether the command name is displayed on the shortcut menu. |
| [ReadOnly](#readonly) | BoolValue | Determines whether the action on a smart tag or shortcut menu is read-only. |
| [Invisible](#invisible) | BoolValue | Invisible element indicates whether the action is visible on the smart tag or shortcut menu. |
| [BeginGroup](#begingroup) | BoolValue | Indicates whether a separator is inserted into the menu above this action. |
| [FlyoutChild](#flyoutchild) | BoolValue | Determines whether the action row is a child flyout menu of the last row above it that is not a flyout child. |
| [TagName](#tagname) | Str2Value | It contains the name of the smart tag that the action is associated with. |
| [ButtonFace](#buttonface) | Str2Value | It identifies the icon that appears next to an item on a shortcut menu. |
| [SortKey](#sortkey) | Str2Value | It specifies a number that determines the order of actions that appear on a shortcut or smart tag menu. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### Act() {#constructor}

Constructor.

### Act.Name property {#name}

The name of the element.

**Type:** String

### Act.NameU property {#nameu}

The universal name of the element.

**Type:** String

### Act.ID property {#id}

The unique ID of the element within its parent element.

**Type:** int

### Act.IX property {#ix}

The zero-based index of the element within its parent element.

**Type:** int

### Act.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### Act.Menu property {#menu}

Specifies the name of the command that appears on the shortcut menu for a shape or page.

**Type:** Str2Value

### Act.Action property {#action}

Contains the formula to execute when a user clicks the command name defined in the corresponding Menu element.

**Type:** DoubleValue

### Act.Checked property {#checked}

Determines whether a check mark is displayed beside the command name on a shape's shortcut menu.

**Type:** BoolValue

### Act.Disabled property {#disabled}

Disabled element determines whether the command name is displayed on the shortcut menu.

**Type:** BoolValue

### Act.ReadOnly property {#readonly}

Determines whether the action on a smart tag or shortcut menu is read-only.

**Type:** BoolValue

### Act.Invisible property {#invisible}

Invisible element indicates whether the action is visible on the smart tag or shortcut menu.

**Type:** BoolValue

### Act.BeginGroup property {#begingroup}

Indicates whether a separator is inserted into the menu above this action.

**Type:** BoolValue

### Act.FlyoutChild property {#flyoutchild}

Determines whether the action row is a child flyout menu of the last row above it that is not a flyout child.

**Type:** BoolValue

### Act.TagName property {#tagname}

It contains the name of the smart tag that the action is associated with.

**Type:** Str2Value

### Act.ButtonFace property {#buttonface}

It identifies the icon that appears next to an item on a shortcut menu.

**Type:** Str2Value

### Act.SortKey property {#sortkey}

It specifies a number that determines the order of actions that appear on a shortcut or smart tag menu.

**Type:** Str2Value

### deepClone() {#deepclone}

Creates deep copy of this instance.
