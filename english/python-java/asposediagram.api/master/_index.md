---
title: "Master"
linktitle: "Master"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that define a master for the document."
type: docs
weight: 2030
url: /python-java/asposediagram.api/master/
---

## Master class

Contains elements that define a master for the document. A master is a shape on a stencil that you use repeatedly to create drawings. When you drag a shape from a stencil onto the drawing page, the shape becomes an instance of that master, and a local copy of the master is included in the document.

## Constructors

| Name | Description |
| --- | --- |
| [Master](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ID](#id) | int | The unique ID of the element within its parent element. |
| [BaseID](#baseid) | UUID | A GUID (globally unique identifier) that identifies the master across documents. |
| [UniqueID](#uniqueid) | UUID | A GUID that identifies the master within the document. |
| [MatchByName](#matchbyname) | int | The MatchByName attribute determines how Microsoft Visio decides if a document master is already present when an instanc |
| [Name](#name) | String | The name of the element. |
| [NameU](#nameu) | String | The universal name of the element. |
| [IconSize](#iconsize) | int | The size of the element's icon. The value of the property is IconSizeValue integer constant. |
| [PatternFlags](#patternflags) | int | The PatternFlags attribute determines whether a master behaves as a custom pattern. |
| [Prompt](#prompt) | String | The status bar and tool tip prompt for the element. |
| [Hidden](#hidden) | int | Specifies whether the master is hidden in the user interface. The value of the property is BOOL integer constant. |
| [IconUpdate](#iconupdate) | int | Specifies whether the icon is automatically generated from the master itself. The value of the property is BOOL integer  |
| [AlignName](#alignname) | int | Specifies whether the master's text in the stencil window is aligned left, right, or center. The value of the property i |
| [Shapes](#shapes) | ShapeCollection | Collection of Shape objects. |
| [Connects](#connects) | ConnectCollection | Contains a Connect element for each connection between two shapes in a drawing. |
| [Icon](#icon) | byte[] | Specifies a MIME (Multipurpose Internet Mail Extensions) encoded binary icon (in .ico format) for a Master or MasterShor |
| [PageSheet](#pagesheet) | PageSheet | Contains elements that define the page sheet for a Page or Master element. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](#dispose) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### Master() {#constructor}

Constructor.

### Master.ID property {#id}

The unique ID of the element within its parent element.

**Type:** int

### Master.BaseID property {#baseid}

A GUID (globally unique identifier) that identifies the master across documents.

**Type:** UUID

### Master.UniqueID property {#uniqueid}

A GUID that identifies the master within the document.

**Type:** UUID

### Master.MatchByName property {#matchbyname}

The MatchByName attribute determines how Microsoft Visio decides if a document master is already present when an instance of a master is dropped on the drawing page. It allows changes made to a document master to apply to new instances of the master, even if the instances are dragged from a stand-alone stencil file. The value of the property is BOOL integer constant.

**Type:** int

### Master.Name property {#name}

The name of the element.

**Type:** String

### Master.NameU property {#nameu}

The universal name of the element.

**Type:** String

### Master.IconSize property {#iconsize}

The size of the element's icon. The value of the property is IconSizeValue integer constant.

**Type:** int

### Master.PatternFlags property {#patternflags}

The PatternFlags attribute determines whether a master behaves as a custom pattern.

**Type:** int

### Master.Prompt property {#prompt}

The status bar and tool tip prompt for the element.

**Type:** String

### Master.Hidden property {#hidden}

Specifies whether the master is hidden in the user interface. The value of the property is BOOL integer constant.

**Type:** int

### Master.IconUpdate property {#iconupdate}

Specifies whether the icon is automatically generated from the master itself. The value of the property is BOOL integer constant.

**Type:** int

### Master.AlignName property {#alignname}

Specifies whether the master's text in the stencil window is aligned left, right, or center. The value of the property is AlignNameValue integer constant.

**Type:** int

### Master.Shapes property {#shapes}

Collection of Shape objects.

**Type:** ShapeCollection

### Master.Connects property {#connects}

Contains a Connect element for each connection between two shapes in a drawing.

**Type:** ConnectCollection

### Master.Icon property {#icon}

Specifies a MIME (Multipurpose Internet Mail Extensions) encoded binary icon (in .ico format) for a Master or MasterShortcut element in a document.

**Type:** byte[]

### Master.PageSheet property {#pagesheet}

Contains elements that define the page sheet for a Page or Master element.

**Type:** PageSheet

### dispose() {#dispose}

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### deepClone() {#deepclone}

Creates deep copy of this instance.
