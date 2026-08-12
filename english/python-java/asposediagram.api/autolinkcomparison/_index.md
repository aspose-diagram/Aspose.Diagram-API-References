---
title: "AutoLinkComparison"
linktitle: "AutoLinkComparison"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Defines a rule that compares a column in the parent DataRecordset element with a shape data item from the last successful automatic linking action performed in "
type: docs
weight: 140
url: /python-java/asposediagram.api/autolinkcomparison/
---

## AutoLinkComparison class

Defines a rule that compares a column in the parent DataRecordset element with a shape data item from the last successful automatic linking action performed in the user interface.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ColumnName](#columnname) | String | Corresponds to a column name in the ADO recordset. |
| [ContextType](#contexttype) | int | Specifies properties of the group or shape to use for the comparison. Possible values are shown in the following table.  |
| [ContextTypeLabel](#contexttypelabel) | String | If the ContextType value is 2 or 3, this attribute is required to define a comparison. For ContextType = 2, ContextTypeL |

### AutoLinkComparison.ColumnName property {#columnname}

Corresponds to a column name in the ADO recordset.

**Type:** String

### AutoLinkComparison.ContextType property {#contexttype}

Specifies properties of the group or shape to use for the comparison. Possible values are shown in the following table. The value of the property is ContextTypeValue integer constant.

**Type:** int

### AutoLinkComparison.ContextTypeLabel property {#contexttypelabel}

If the ContextType value is 2 or 3, this attribute is required to define a comparison. For ContextType = 2, ContextTypeLabel must be the shape data item label, and if ContextType = 3, ContextTypeLabel must be the local row name.

**Type:** String
