---
title: "VbaProject"
linktitle: "VbaProject"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Represents the VBA project."
type: docs
weight: 3730
url: /python-java/asposediagram.api/vbaproject/
---

## VbaProject class

Represents the VBA project.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Name](#name) | String | Gets and sets the name of the VBA project. |
| [IsSigned](#issigned) | boolean | Indicates whether VBAcode is signed or not. |
| [IsProtected](#isprotected) | boolean | Indicates whether this VBA project is protected. |
| [Modules](#modules) | VbaModuleCollection | Gets all VbaModule objects. |
| [References](#references) | VbaProjectReferenceCollection | Gets all references of VBA project. |

## Methods

| Name | Description |
| --- | --- |
| [protect](#protect) | Protects or unprotects this VBA project.

If islockedForViewing is true, the password could not be null. |
| [validatePassword](#validatepassword) | Validates protection password. |

### VbaProject.Name property {#name}

Gets and sets the name of the VBA project.

**Type:** String

### VbaProject.IsSigned property {#issigned}

Indicates whether VBAcode is signed or not.

**Type:** boolean

### VbaProject.IsProtected property {#isprotected}

Indicates whether this VBA project is protected.

**Type:** boolean

### VbaProject.Modules property {#modules}

Gets all VbaModule objects.

**Type:** VbaModuleCollection

### VbaProject.References property {#references}

Gets all references of VBA project.

**Type:** VbaProjectReferenceCollection

### protect(islockedForViewing, password) {#protect}

Protects or unprotects this VBA project.

If islockedForViewing is true, the password could not be null.

| Parameter | Type | Description |
| --- | --- | --- |
| islockedForViewing | boolean | indicates whether locks project for viewing. |
| password | String | If the value is null, unprotects this VBA project, otherwise protect this VBA project. |

### validatePassword(password) {#validatepassword}

Validates protection password.

| Parameter | Type | Description |
| --- | --- | --- |
| password | String | the password |

**Returns:** Whether password is the protection password of this VBA project
