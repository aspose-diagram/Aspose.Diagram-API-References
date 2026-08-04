---
title: "LoadOptions Class"
linktitle: "LoadOptions"
articleTitle: "LoadOptions"
second_title: "Aspose.Diagram for Python via Java"
description: "Allows to specify additional options when loading a diagram into a Diagram object."
type: docs
weight: 1990
url: /python-java/asposediagram.api/loadoptions/
---

## LoadOptions class

Allows to specify additional options when loading a diagram into a Diagram object.

```python
LoadOptions()
```

Initializes a new instance of this class with default values. Default file format is set as LoadFileFormat .

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [LoadFormat](./loadformat/) | int | Specifies the format of the diagram to be loaded. Default is LoadFileFormat . Read/write LoadFileFormat . The value of t |
| [Pages](./pages/) | ArrayList | Specifies the index of the pages to be loaded. |
| [LoadFilter](./loadfilter/) | LoadFilter | The filter to denote how to load data. |
| [InterruptMonitor](./interruptmonitor/) | AbstractInterruptMonitor | Gets and sets the interrupt monitor. |
| [FontConfigs](./fontconfigs/) | IndividualFontConfigs | Gets and sets individual font configs. Only works for the Diagram which uses this LoadOptions to load. |
| [Locale](./locale/) | Locale | Gets and sets the Locale used for diagram at the time the file was loaded. |
