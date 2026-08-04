---
title: "DataColumn Class"
linktitle: "DataColumn"
articleTitle: "DataColumn"
second_title: "Aspose.Diagram for Python via Java"
description: "Defines how a data column appears in the External Data window in the Visio user interface and qualifies the data in the column by defining its data type and for"
type: docs
weight: 810
url: /python-java/asposediagram.api/datacolumn/
---

## DataColumn class

Defines how a data column appears in the External Data window in the Visio user interface and qualifies the data in the column by defining its data type and formatting.

```python
DataColumn()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ColumnNameID](./columnnameid/) | String | External name of the data column. Appears in the headings in the External Data window and in labels in data graphics. |
| [Name](./name/) | String | Internal name of the data column. Used as the row name for the shape-data item (custom property) added to a shape when t |
| [Label](./label/) | String | Label of the data column. |
| [OrigLabel](./origlabel/) | String | Column label returned to Visio by the underlying ADO interface. |
| [LangID](./langid/) | long | The language ID of the data column |
| [Calendar](./calendar/) | int | Calendar ID of the data column. |
| [DataType](./datatype/) | int | Type of the data in the data column. |
| [UnitType](./unittype/) | String | Unit type of the data in the data column. |
| [Currency](./currency/) | int | Currency ID of the data column. |
| [Degree](./degree/) | long | Specifies the degree (power) of the units, for example squared, or cubed. The default (attribute absent) is 1. |
| [DisplayWidth](./displaywidth/) | long | Width of the data column in the External Data window. |
| [DisplayOrder](./displayorder/) | long | Defines the display position of the data column in the External Data window, from the left-most column (0) to the right- |
| [Mapped](./mapped/) | int | Specifies whether the column is visible in the External Data window. True (1) for the column to be visible; false (0) fo |
| [Hyperlink](./hyperlink/) | int | Whether the data column creates a hyperlink in a shape when the shape is linked to data. The value of the property is BO |
