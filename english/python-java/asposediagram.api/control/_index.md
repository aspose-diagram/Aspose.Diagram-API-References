---
title: "Control Class"
linktitle: "Control"
articleTitle: "Control"
second_title: "Aspose.Diagram for Python via Java"
description: "Contains elements for the x- and y-coordinates of each control handle defined for a shape, and elements that specify the way the control handle should behave."
type: docs
weight: 720
url: /python-java/asposediagram.api/control/
---

## Control class

Contains elements for the x- and y-coordinates of each control handle defined for a shape, and elements that specify the way the control handle should behave.

```python
Control()
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
| [X](./x/) | DoubleValue | The x-coordinate that indicates the location of a shape's control handle. |
| [Y](./y/) | DoubleValue | The y-coordinate that indicates the location of a shape's control handle. |
| [XDyn](./xdyn/) | DoubleValue | Specifies the x-coordinate for a control handle's anchor point in local coordinates. The anchor point is used for rubber |
| [YDyn](./ydyn/) | DoubleValue | Specifies the y-coordinate for a control handle's anchor point in local coordinates. The anchor point is used for rubber |
| [XCon](./xcon/) | ConType | Specifies the type of behavior the x-coordinate of the control handle exhibits after the handle is moved. |
| [YCon](./ycon/) | ConType | Specifies the type of behavior the x-coordinate of the control handle exhibits after the handle is moved. |
| [CanGlue](./canglue/) | BoolValue | Determines whether a control handle can be glued to other shapes. |
| [Prompt](./prompt/) | Str2Value | Prompt element specifies descriptive text that appears as a tool tip when the mouse pointer is paused over a shape's con |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](./deepclone/) | Creates deep copy of this instance. |
