---
title: "MasterCollection"
linktitle: "MasterCollection"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Master collection."
type: docs
weight: 1510
url: /nodejs/aspose.diagram/mastercollection/
---

## MasterCollection class

Master collection.

## Methods

| Name | Description |
| --- | --- |
| [add(master)](#add) | Add the Master object in the collection. |
| [clear()](#clear) |  |
| [get()](#get) |  |
| [getCount()](#getcount) |  |
| [getMaster(ID)](#getmaster) | Gets the element at the specified ID. |
| [getMasterByName(name)](#getmasterbyname) | Get master by name. |
| [getMasterShortcuts()](#getmastershortcuts) | MasterShortcut collection. |
| [getMaxRelID()](#getmaxrelid) | get the max rel id in the collection. Parameters:name - @return {Number} |
| [isExist(name)](#isexist) | Is exist master in the collection. |
| [isExistRelId(name)](#isexistrelid) | Is exist master rel id in the collection. |
| [iterator()](#iterator) | Reserved for internal use. |
| [remove(master)](#remove) | Remove the Master object from the collection. |
| [removeAt()](#removeat) |  |

### add(master) {#add}

Add the Master object in the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| master | Master |  |

**Returns:** Number — `Number`

### clear() {#clear}

### get() {#get}

### getCount() {#getcount}

### getMaster(ID) {#getmaster}

Gets the element at the specified ID.

| Parameter | Type | Description |
| --- | --- | --- |
| ID | Number |  |

**Returns:** Master — `Master`

**Example:**

```js
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

**Returns:** Master — `Master`

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("BasicShapes.vss");
// Get master object by name
master = diagram.getMasters().getMasterByName("Circle");
console.log("Master ID : " + master.getID());
console.log("Master Name : " + master.getName());
console.log("Master Name : " + master.getUniqueID());
```

### getMasterShortcuts() {#getmastershortcuts}

MasterShortcut collection.

### getMaxRelID() {#getmaxrelid}

get the max rel id in the collection. Parameters:name - @return {Number}

### isExist(name) {#isexist}

Is exist master in the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| name | String |  |

**Returns:** boolean — `boolean`

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("BasicShapes.vss");
// check master object by name
isPresent = diagram.getMasters().isExist("60 degree single");
console.log("Master Presence : " + isPresent);
```

### isExistRelId(name) {#isexistrelid}

Is exist master rel id in the collection.

| Parameter | Description |
| --- | --- |
| name |  |

**Returns:** boolean — `boolean`

### iterator() {#iterator}

Reserved for internal use.

### remove(master) {#remove}

Remove the Master object from the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| master | Master |  |

### removeAt() {#removeat}
