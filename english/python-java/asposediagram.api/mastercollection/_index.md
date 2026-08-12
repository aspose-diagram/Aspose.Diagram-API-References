---
title: "MasterCollection"
linktitle: "MasterCollection"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Master collection."
type: docs
weight: 2040
url: /python-java/asposediagram.api/mastercollection/
---

## MasterCollection class

Master collection.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [MasterShortcuts](#mastershortcuts) | MasterShortcutCollection | MasterShortcut collection. |
| [Count](#count) | int |  |
| [Item (int)](#itemint) | Master |  |

## Methods

| Name | Description |
| --- | --- |
| [add](#add) | Add the Master object in the collection. |
| [remove](#remove) | Remove the Master object from the collection. |
| [getMaster](#getmaster) | Gets the element at the specified ID. |
| [getMasterByName](#getmasterbyname) | Get master by name. |
| [getMaxRelID](#getmaxrelid) | get the max rel id in the collection. |
| [isExistRelId](#isexistrelid) | Is exist master rel id in the collection. |
| [isExist](#isexist) | Is exist master in the collection. |
| [clear](#clear) |  |
| [removeAt](#removeat) |  |
| [iterator](#iterator) | Reserved for internal use. |

### MasterCollection.MasterShortcuts property {#mastershortcuts}

MasterShortcut collection.

**Type:** MasterShortcutCollection

### MasterCollection.Count property {#count}

**Type:** int

### MasterCollection.Item (int) property {#itemint}

**Type:** Master

### add(master) {#add}

Add the Master object in the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| master | Master |  |

### remove(master) {#remove}

Remove the Master object from the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| master | Master |  |

### getMaster(ID) {#getmaster}

Gets the element at the specified ID.

| Parameter | Type | Description |
| --- | --- | --- |
| ID | int |  |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("RetrieveMasterInfo.vdx");

// Get master object by id
master = diagram.getMasters().getMaster(2);
console.log("Master ID : " + master.getID());
console.log("Master Name : " + master.getName());
console.log("Master Name : " + master.getUniqueID());
```

### getMasterByName(name) {#getmasterbyname}

Get master by name.

| Parameter | Type | Description |
| --- | --- | --- |
| name | String |  |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("BasicShapes.vss");

// Get master object by name
master = diagram.getMasters().getMasterByName("Circle");
console.log("Master ID : " + master.getID());
console.log("Master Name : " + master.getName());
console.log("Master Name : " + master.getUniqueID());
```

### getMaxRelID() {#getmaxrelid}

get the max rel id in the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| name |  |  |

### isExistRelId(relID) {#isexistrelid}

Is exist master rel id in the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| name |  |  |

### isExist(name) {#isexist}

Is exist master in the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| name | String |  |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("BasicShapes.vss");

// check master object by name
isPresent = diagram.getMasters().isExist("60 degree single");

console.log("Master Presence : " + isPresent);
```

### clear() {#clear}

### removeAt(index) {#removeat}

### iterator() {#iterator}

Reserved for internal use.
