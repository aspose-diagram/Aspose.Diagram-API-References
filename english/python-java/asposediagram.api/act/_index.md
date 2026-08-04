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
| [Name](/python-java/asposediagram.api/act/name/) | String | The name of the element. |
| [NameU](/python-java/asposediagram.api/act/nameu/) | String | The universal name of the element. |
| [ID](/python-java/asposediagram.api/act/id/) | int | The unique ID of the element within its parent element. |
| [IX](/python-java/asposediagram.api/act/ix/) | int | The zero-based index of the element within its parent element. |
| [Del](/python-java/asposediagram.api/act/del/) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [Menu](/python-java/asposediagram.api/act/menu/) | Str2Value | Specifies the name of the command that appears on the shortcut menu for a shape or page. |
| [Action](/python-java/asposediagram.api/act/action/) | DoubleValue | Contains the formula to execute when a user clicks the command name defined in the corresponding Menu element. |
| [Checked](/python-java/asposediagram.api/act/checked/) | BoolValue | Determines whether a check mark is displayed beside the command name on a shape's shortcut menu. |
| [Disabled](/python-java/asposediagram.api/act/disabled/) | BoolValue | Disabled element determines whether the command name is displayed on the shortcut menu. |
| [ReadOnly](/python-java/asposediagram.api/act/readonly/) | BoolValue | Determines whether the action on a smart tag or shortcut menu is read-only. |
| [Invisible](/python-java/asposediagram.api/act/invisible/) | BoolValue | Invisible element indicates whether the action is visible on the smart tag or shortcut menu. |
| [BeginGroup](/python-java/asposediagram.api/act/begingroup/) | BoolValue | Indicates whether a separator is inserted into the menu above this action. |
| [FlyoutChild](/python-java/asposediagram.api/act/flyoutchild/) | BoolValue | Determines whether the action row is a child flyout menu of the last row above it that is not a flyout child. |
| [TagName](/python-java/asposediagram.api/act/tagname/) | Str2Value | It contains the name of the smart tag that the action is associated with. |
| [ButtonFace](/python-java/asposediagram.api/act/buttonface/) | Str2Value | It identifies the icon that appears next to an item on a shortcut menu. |
| [SortKey](/python-java/asposediagram.api/act/sortkey/) | Str2Value | It specifies a number that determines the order of actions that appear on a shortcut or smart tag menu. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](/python-java/asposediagram.api/act/deepclone/) | Creates deep copy of this instance. |
