---
title: "Connection Class"
linktitle: "Connection"
articleTitle: "Connection"
second_title: "Aspose.Diagram for Python via Java"
description: "Contains elements for one connection point defined for the shape."
type: docs
weight: 610
url: /python-java/asposediagram.api/connection/
---

## Connection class

Contains elements for one connection point defined for the shape.

```python
Connection()
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
| [X](./x/) | DoubleValue | Specifies an x-coordinate on a shape in local coordinates. |
| [Y](./y/) | DoubleValue | Specifies a y-coordinate on a shape in local coordinates. Local coordinates are those whose frame of reference is the sh |
| [DirX](./dirx/) | DoubleValue | Specifies the x-component for the required alignment vector of a matching connection point. The DirX element is also use |
| [DirY](./diry/) | DoubleValue | Specifies the y-component for the required alignment vector of a matching connection point. The DirY element is also use |
| [Type](./type/) | TypeConnection | Specifies various types, based on the element in which it is contained. |
| [AutoGen](./autogen/) | BoolValue | Specifies if the connection point is generated automatically. A value of 1 indicates that the connection point is genera |
| [Prompt](./prompt/) | Str2Value | Contains varying prompt information, based on the element in which it is contained. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](./deepclone/) | Creates deep copy of this instance. |
