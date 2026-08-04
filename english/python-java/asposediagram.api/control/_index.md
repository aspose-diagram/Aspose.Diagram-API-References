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
| [Name](/python-java/asposediagram.api/control/name/) | String | The name of the element. |
| [NameU](/python-java/asposediagram.api/control/nameu/) | String | The universal name of the element. |
| [ID](/python-java/asposediagram.api/control/id/) | int | The unique ID of the element within its parent element. |
| [IX](/python-java/asposediagram.api/control/ix/) | int | The zero-based index of the element within its parent element. |
| [Del](/python-java/asposediagram.api/control/del/) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [X](/python-java/asposediagram.api/control/x/) | DoubleValue | The x-coordinate that indicates the location of a shape's control handle. |
| [Y](/python-java/asposediagram.api/control/y/) | DoubleValue | The y-coordinate that indicates the location of a shape's control handle. |
| [XDyn](/python-java/asposediagram.api/control/xdyn/) | DoubleValue | Specifies the x-coordinate for a control handle's anchor point in local coordinates. The anchor point is used for rubber |
| [YDyn](/python-java/asposediagram.api/control/ydyn/) | DoubleValue | Specifies the y-coordinate for a control handle's anchor point in local coordinates. The anchor point is used for rubber |
| [XCon](/python-java/asposediagram.api/control/xcon/) | ConType | Specifies the type of behavior the x-coordinate of the control handle exhibits after the handle is moved. |
| [YCon](/python-java/asposediagram.api/control/ycon/) | ConType | Specifies the type of behavior the x-coordinate of the control handle exhibits after the handle is moved. |
| [CanGlue](/python-java/asposediagram.api/control/canglue/) | BoolValue | Determines whether a control handle can be glued to other shapes. |
| [Prompt](/python-java/asposediagram.api/control/prompt/) | Str2Value | Prompt element specifies descriptive text that appears as a tool tip when the mouse pointer is paused over a shape's con |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](/python-java/asposediagram.api/control/deepclone/) | Creates deep copy of this instance. |
