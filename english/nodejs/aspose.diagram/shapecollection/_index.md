---
title: "ShapeCollection"
linktitle: "ShapeCollection"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Collection of Shapes."
type: docs
weight: 2310
url: /nodejs/aspose.diagram/shapecollection/
---

## ShapeCollection class

Collection of Shapes.

## Methods

| Name | Description |
| --- | --- |
| [add(item)](#add) | Add the shape in the collection. |
| [clear()](#clear) |  |
| [get()](#get) |  |
| [getCount()](#getcount) |  |
| [getShape(name)](#getshape) | Gets the element at the specified name. |
| [getShape(ID)](#getshape-1) | Gets the element at the specified ID. |
| [getShapeIncludingChild(name)](#getshapeincludingchild) | Gets the element including it's child shape at the specified name. |
| [getShapeIncludingChild(id)](#getshapeincludingchild-1) | Gets the element including it's child shape at the specified id. |
| [group(groupItems)](#group) | Group the shapes. The shape in the groupItems should not be grouped. The shape must be in this Shapes collection. |
| [iterator()](#iterator) | Reserved for internal use. |
| [remove(item)](#remove) | Remove the shape from the collection. |
| [removeAt()](#removeat) |  |
| [removeDependsOn(item)](#removedependson) | Remove the shapes including DEPENDSON shapes from the collection. |
| [unGroup(groupShape)](#ungroup) | UnGroup the shape. |

### add(item) {#add}

Add the shape in the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| item | Shape |  |

**Returns:** Number — `Number` ID

### clear() {#clear}

### get() {#get}

### getCount() {#getcount}

### getShape(name) {#getshape}

Gets the element at the specified name.

| Parameter | Type | Description |
| --- | --- | --- |
| name | String |  |

**Returns:** Shape — `Shape`

### getShape(ID) {#getshape-1}

Gets the element at the specified ID.

| Parameter | Type | Description |
| --- | --- | --- |
| ID | long |  |

**Returns:** Shape — `Shape`

### getShapeIncludingChild(name) {#getshapeincludingchild}

Gets the element including it's child shape at the specified name.

| Parameter | Type | Description |
| --- | --- | --- |
| name | String |  |

**Returns:** Shape — `Shape`

### getShapeIncludingChild(id) {#getshapeincludingchild-1}

Gets the element including it's child shape at the specified id.

| Parameter | Type | Description |
| --- | --- | --- |
| id | Number |  |

**Returns:** Shape — `Shape`

### group(groupItems) {#group}

Group the shapes. The shape in the groupItems should not be grouped. The shape must be in this Shapes collection.

| Parameter | Type | Description |
| --- | --- | --- |
| groupItems | Array ofShape | the group items. |

**Returns:** Shape — `Shape` Return the group shape.

**Example:**

```js
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

### iterator() {#iterator}

Reserved for internal use.

### remove(item) {#remove}

Remove the shape from the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| item | Shape | Shape |

### removeAt() {#removeat}

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
