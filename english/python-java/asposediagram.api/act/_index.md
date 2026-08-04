---
title: "Act Class"
linktitle: "Act"
articleTitle: "Act"
second_title: "Aspose.Diagram for Python via Java"
description: "Defines custom command names that appear on an object's shortcut menu and specifies the actions that the commands take."
type: docs
weight: 20
url: /python-java/asposediagram.api/act/
---

## Act class

Defines custom command names that appear on an object's shortcut menu and specifies the actions that the commands take.

```python
Act()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Name](./name/) | String | The name of the element. |
| [NameU](./nameu/) | String | The universal name of the element. |
| [ID](./id/) | int | The unique ID of the element within its parent element. |
| [IX](./ix/) | int | The zero-based index of the element within its parent element. |
| [Del](./del/) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [Menu](./menu/) | Str2Value | Specifies the name of the command that appears on the shortcut menu for a shape or page. |
| [Action](./action/) | DoubleValue | Contains the formula to execute when a user clicks the command name defined in the corresponding Menu element. |
| [Checked](./checked/) | BoolValue | Determines whether a check mark is displayed beside the command name on a shape's shortcut menu. |
| [Disabled](./disabled/) | BoolValue | Disabled element determines whether the command name is displayed on the shortcut menu. |
| [ReadOnly](./readonly/) | BoolValue | Determines whether the action on a smart tag or shortcut menu is read-only. |
| [Invisible](./invisible/) | BoolValue | Invisible element indicates whether the action is visible on the smart tag or shortcut menu. |
| [BeginGroup](./begingroup/) | BoolValue | Indicates whether a separator is inserted into the menu above this action. |
| [FlyoutChild](./flyoutchild/) | BoolValue | Determines whether the action row is a child flyout menu of the last row above it that is not a flyout child. |
| [TagName](./tagname/) | Str2Value | It contains the name of the smart tag that the action is associated with. |
| [ButtonFace](./buttonface/) | Str2Value | It identifies the icon that appears next to an item on a shortcut menu. |
| [SortKey](./sortkey/) | Str2Value | It specifies a number that determines the order of actions that appear on a shortcut or smart tag menu. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](./deepclone/) | Creates deep copy of this instance. |
