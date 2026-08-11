---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Allows to specify additional options when loading a diagram into a Diagram object."
type: docs
weight: 1990
url: /python-java/asposediagram.api/loadoptions/
---

## LoadOptions class

Allows to specify additional options when loading a diagram into a Diagram object.

## Constructors

| Name | Description |
| --- | --- |
| [LoadOptions](#constructor) | Initializes a new instance of this class with default values. Default file format is set as LoadFileFormat . |
| [LoadOptions](#constructor) | Initializes a new instance of this class with the format specified. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [LoadFormat](#loadformat) | int | Specifies the format of the diagram to be loaded. Default is LoadFileFormat . Read/write LoadFileFormat . The value of t |
| [Pages](#pages) | ArrayList | Specifies the index of the pages to be loaded. |
| [LoadFilter](#loadfilter) | LoadFilter | The filter to denote how to load data. |
| [InterruptMonitor](#interruptmonitor) | AbstractInterruptMonitor | Gets and sets the interrupt monitor. |
| [FontConfigs](#fontconfigs) | IndividualFontConfigs | Gets and sets individual font configs. Only works for the Diagram which uses this LoadOptions to load. |
| [Locale](#locale) | Locale | Gets and sets the Locale used for diagram at the time the file was loaded. |

### LoadOptions() (1 of 2) {#constructor}

Initializes a new instance of this class with default values. Default file format is set as LoadFileFormat .

---

### LoadOptions(format) (2 of 2) {#constructor-1}

Initializes a new instance of this class with the format specified.

| Parameter | Type | Description |
| --- | --- | --- |
| format | int | A LoadFileFormat value. LoadFileFormat load file format. |

### LoadOptions.LoadFormat property {#loadformat}

Specifies the format of the diagram to be loaded. Default is LoadFileFormat . Read/write LoadFileFormat . The value of the property is LoadFileFormat integer constant.

**Type:** int

### LoadOptions.Pages property {#pages}

Specifies the index of the pages to be loaded.

**Type:** ArrayList

### LoadOptions.LoadFilter property {#loadfilter}

The filter to denote how to load data.

**Type:** LoadFilter

### LoadOptions.InterruptMonitor property {#interruptmonitor}

Gets and sets the interrupt monitor.

**Type:** AbstractInterruptMonitor

### LoadOptions.FontConfigs property {#fontconfigs}

Gets and sets individual font configs. Only works for the Diagram which uses this LoadOptions to load.

**Type:** IndividualFontConfigs

### LoadOptions.Locale property {#locale}

Gets and sets the Locale used for diagram at the time the file was loaded.

**Type:** Locale
