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
| [ID](/python-java/asposediagram.api/master/id/) | int | The unique ID of the element within its parent element. |
| [BaseID](/python-java/asposediagram.api/master/baseid/) | UUID | A GUID (globally unique identifier) that identifies the master across documents. |
| [UniqueID](/python-java/asposediagram.api/master/uniqueid/) | UUID | A GUID that identifies the master within the document. |
| [MatchByName](/python-java/asposediagram.api/master/matchbyname/) | int | The MatchByName attribute determines how Microsoft Visio decides if a document master is already present when an instanc |
| [Name](/python-java/asposediagram.api/master/name/) | String | The name of the element. |
| [NameU](/python-java/asposediagram.api/master/nameu/) | String | The universal name of the element. |
| [IconSize](/python-java/asposediagram.api/master/iconsize/) | int | The size of the element's icon. The value of the property is IconSizeValue integer constant. |
| [PatternFlags](/python-java/asposediagram.api/master/patternflags/) | int | The PatternFlags attribute determines whether a master behaves as a custom pattern. |
| [Prompt](/python-java/asposediagram.api/master/prompt/) | String | The status bar and tool tip prompt for the element. |
| [Hidden](/python-java/asposediagram.api/master/hidden/) | int | Specifies whether the master is hidden in the user interface. The value of the property is BOOL integer constant. |
| [IconUpdate](/python-java/asposediagram.api/master/iconupdate/) | int | Specifies whether the icon is automatically generated from the master itself. The value of the property is BOOL integer  |
| [AlignName](/python-java/asposediagram.api/master/alignname/) | int | Specifies whether the master's text in the stencil window is aligned left, right, or center. The value of the property i |
| [Shapes](/python-java/asposediagram.api/master/shapes/) | ShapeCollection | Collection of Shape objects. |
| [Connects](/python-java/asposediagram.api/master/connects/) | ConnectCollection | Contains a Connect element for each connection between two shapes in a drawing. |
| [Icon](/python-java/asposediagram.api/master/icon/) | byte[] | Specifies a MIME (Multipurpose Internet Mail Extensions) encoded binary icon (in .ico format) for a Master or MasterShor |
| [PageSheet](/python-java/asposediagram.api/master/pagesheet/) | PageSheet | Contains elements that define the page sheet for a Page or Master element. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](/python-java/asposediagram.api/master/dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [deepClone](/python-java/asposediagram.api/master/deepclone/) | Creates deep copy of this instance. |
