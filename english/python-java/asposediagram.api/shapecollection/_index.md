---
title: "ShapeCollection"
linktitle: "ShapeCollection"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Collection of Shapes."
type: docs
weight: 3040
url: /python-java/asposediagram.api/shapecollection/
---

## ShapeCollection class

Collection of Shapes.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Count](#count) | int |  |
| [Item (int)](#itemint) | Shape |  |

## Methods

| Name | Description |
| --- | --- |
| [add](#add) | Add the shape in the collection. |
| [remove](#remove) | Remove the shape from the collection. |
| [removeDependsOn](#removedependson) | Remove the shapes including DEPENDSON shapes from the collection. |
| [unGroup](#ungroup) | UnGroup the shape. |
| [group](#group) | Group the shapes.

The shape in the groupItems should not be grouped. The shape must be in this Shapes collection. |
| [getShape](#getshape) | Gets the element at the specified name. |
| [getShapeIncludingChild](#getshapeincludingchild) | Gets the element including it's child shape at the specified name. |
| [clear](#clear) |  |
| [removeAt](#removeat) |  |
| [iterator](#iterator) | Reserved for internal use. |

### ShapeCollection.Count property {#count}

**Type:** int

### ShapeCollection.Item (int) property {#itemint}

**Type:** Shape

### add(item) {#add}

Add the shape in the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| item | Shape |  |

**Returns:** ID

### remove(item) {#remove}

Remove the shape from the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| item | Shape | Shape |

### removeDependsOn(item) {#removedependson}

Remove the shapes including DEPENDSON shapes from the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| item | Shape | Shape |

### unGroup(groupShape) {#ungroup}

UnGroup the shape.

| Parameter | Type | Description |
| --- | --- | --- |
| groupShape | Shape | the group shape. |

### group(groupItems) {#group}

Group the shapes.

The shape in the groupItems should not be grouped. The shape must be in this Shapes collection.

| Parameter | Type | Description |
| --- | --- | --- |
| groupItems | Shape[] | the group items. |

**Returns:** Return the group shape.

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var java = require("java");

diagram = new aspose.diagram.Diagram("GroupShapes.vsdx");

// get page by name
page = diagram.getPages().getPage("Page-3");

ss = new Array(3);
// extract and assign shapes to the array
ss[0] = page.getShapes().getShape(15);
ss[1] = page.getShapes().getShape(16);
ss[2] = page.getShapes().getShape(17);

// Initialize an array of shapes
jss = java.newArray('com.aspose.diagram.Shape', ss);
// mark array shapes as group
page.getShapes().group(jss);

diagram.save("out-GroupShapes.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### getShape(name) (1 of 2) {#getshape}

Gets the element at the specified name.

| Parameter | Type | Description |
| --- | --- | --- |
| name | String |  |

---

### getShape(ID) (2 of 2) {#getshape-1}

Gets the element at the specified ID.

| Parameter | Type | Description |
| --- | --- | --- |
| ID | long |  |

### getShapeIncludingChild(name) (1 of 2) {#getshapeincludingchild}

Gets the element including it's child shape at the specified name.

| Parameter | Type | Description |
| --- | --- | --- |
| name | String |  |

---

### getShapeIncludingChild(id) (2 of 2) {#getshapeincludingchild-1}

Gets the element including it's child shape at the specified id.

| Parameter | Type | Description |
| --- | --- | --- |
| id | int |  |

### clear() {#clear}

### removeAt(index) {#removeat}

### iterator() {#iterator}

Reserved for internal use.
