---
title: "VbaProject"
linktitle: "VbaProject"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Represents the VBA project."
type: docs
weight: 2840
url: /nodejs/aspose.diagram/vbaproject/
---

## VbaProject class

Represents the VBA project.

## Methods

| Name | Description |
| --- | --- |
| [getModules()](#getmodules) | Gets all VbaModule objects. |
| [getName()](#getname) | Gets and sets the name of the VBA project. |
| [getReferences()](#getreferences) | Gets all references of VBA project. |
| [isProtected()](#isprotected) | Indicates whether this VBA project is protected. |
| [isSigned()](#issigned) | Indicates whether VBAcode is signed or not. |
| [protect(islockedForViewing, password)](#protect) | Protects or unprotects this VBA project. If islockedForViewing is true, the password could not be null. |
| [setName()](#setname) | Gets and sets the name of the VBA project. |
| [validatePassword(password)](#validatepassword) | Validates protection password. |

### getModules() {#getmodules}

Gets all VbaModule objects.

### getName() {#getname}

Gets and sets the name of the VBA project.

### getReferences() {#getreferences}

Gets all references of VBA project.

### isProtected() {#isprotected}

Indicates whether this VBA project is protected.

### isSigned() {#issigned}

Indicates whether VBAcode is signed or not.

### protect(islockedForViewing, password) {#protect}

Protects or unprotects this VBA project. If islockedForViewing is true, the password could not be null.

| Parameter | Type | Description |
| --- | --- | --- |
| islockedForViewing | boolean | indicates whether locks project for viewing. |
| password | String | If the value is null, unprotects this VBA project, otherwise protect this VBA project. |

### setName() {#setname}

Gets and sets the name of the VBA project.

### validatePassword(password) {#validatepassword}

Validates protection password.

| Parameter | Type | Description |
| --- | --- | --- |
| password | String | the password |

**Returns:** boolean — `boolean` Whether password is the protection password of this VBA project
