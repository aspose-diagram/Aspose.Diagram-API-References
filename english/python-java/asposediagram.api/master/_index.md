---
title: "Master Class"
linktitle: "Master"
articleTitle: "Master"
second_title: "Aspose.Diagram for Python via Java"
description: "Contains elements that define a master for the document."
type: docs
weight: 2030
url: /python-java/asposediagram.api/master/
---

## Master class

Contains elements that define a master for the document. A master is a shape on a stencil that you use repeatedly to create drawings. When you drag a shape from a stencil onto the drawing page, the shape becomes an instance of that master, and a local copy of the master is included in the document.

```python
Master()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ID](./id/) | int | The unique ID of the element within its parent element. |
| [BaseID](./baseid/) | UUID | A GUID (globally unique identifier) that identifies the master across documents. |
| [UniqueID](./uniqueid/) | UUID | A GUID that identifies the master within the document. |
| [MatchByName](./matchbyname/) | int | The MatchByName attribute determines how Microsoft Visio decides if a document master is already present when an instanc |
| [Name](./name/) | String | The name of the element. |
| [NameU](./nameu/) | String | The universal name of the element. |
| [IconSize](./iconsize/) | int | The size of the element's icon. The value of the property is IconSizeValue integer constant. |
| [PatternFlags](./patternflags/) | int | The PatternFlags attribute determines whether a master behaves as a custom pattern. |
| [Prompt](./prompt/) | String | The status bar and tool tip prompt for the element. |
| [Hidden](./hidden/) | int | Specifies whether the master is hidden in the user interface. The value of the property is BOOL integer constant. |
| [IconUpdate](./iconupdate/) | int | Specifies whether the icon is automatically generated from the master itself. The value of the property is BOOL integer  |
| [AlignName](./alignname/) | int | Specifies whether the master's text in the stencil window is aligned left, right, or center. The value of the property i |
| [Shapes](./shapes/) | ShapeCollection | Collection of Shape objects. |
| [Connects](./connects/) | ConnectCollection | Contains a Connect element for each connection between two shapes in a drawing. |
| [Icon](./icon/) | byte[] | Specifies a MIME (Multipurpose Internet Mail Extensions) encoded binary icon (in .ico format) for a Master or MasterShor |
| [PageSheet](./pagesheet/) | PageSheet | Contains elements that define the page sheet for a Page or Master element. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](./dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [deepClone](./deepclone/) | Creates deep copy of this instance. |
