---
title: "Hyperlink Class"
linktitle: "Hyperlink"
articleTitle: "Hyperlink"
second_title: "Aspose.Diagram for Python via Java"
description: "Contains elements for creating multiple jumps between a shape or drawing page and another drawing page, another file, or a Web site."
type: docs
weight: 1620
url: /python-java/asposediagram.api/hyperlink/
---

## Hyperlink class

Contains elements for creating multiple jumps between a shape or drawing page and another drawing page, another file, or a Web site.

```python
Hyperlink()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Name](./name/) | String | The name of the element. |
| [NameU](./nameu/) | String | The universal name of the element. |
| [ID](./id/) | int | The unique ID of the element within its parent element. |
| [Del](./del/) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [Description](./description/) | Str2Value | Description element contains a text string that describes the hyperlink. |
| [Address](./address/) | Str2Value | Specifies a URL address, DOS file name, or UNC path to jump to. |
| [SubAddress](./subaddress/) | Str2Value | Specifies a location within the target document to link to. |
| [ExtraInfo](./extrainfo/) | Str2Value | Contains information to be used in resolving a URL, such as the coordinates of an image map. For example, x=41 y=7 would |
| [Frame](./frame/) | Str2Value | Contains the name of a frame to target when Microsoft Visio is open as an active document in a container application. Th |
| [NewWindow](./newwindow/) | BoolValue | Specifies whether Microsoft Visio opens a window in a new location when it follows a hyperlink to open a Web page or ano |
| [Default](./default/) | BoolValue | Specifies the default hyperlink for a shape or page. |
| [Invisible](./invisible/) | BoolValue | Invisible element indicates whether a hyperlink appears on the shortcut menu for a shape or page. |
| [SortKey](./sortkey/) | Str2Value | Invisible element indicates whether a hyperlink appears on the shortcut menu for a shape or page. |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](./deepclone/) | Creates deep copy of this instance. |
