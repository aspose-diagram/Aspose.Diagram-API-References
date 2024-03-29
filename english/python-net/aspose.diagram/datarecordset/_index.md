﻿---
title: DataRecordSet class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 550
url: /python-net/aspose.diagram/datarecordset/
is_root: false
---

## DataRecordSet class

Stores, formats, refreshes, and exposes data queried from a database in Microsoft Visio.



The DataRecordSet type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [DataRecordSet()](/diagram/python-net/aspose.diagram/datarecordset/__init__/#) | Constructor. |


### Properties
| Property | Description |
| :- | :- |
| [id](/diagram/python-net/aspose.diagram/datarecordset/id) | The data recordset ID, unique within the document. |
| [connection_id](/diagram/python-net/aspose.diagram/datarecordset/connection_id) | The connection ID for the associated DataConnection object. Does not exist for XML data sources. |
| [command](/diagram/python-net/aspose.diagram/datarecordset/command) | The command string used to query data from the data source. |
| [options](/diagram/python-net/aspose.diagram/datarecordset/options) | Options to apply to the data recordset. Possible values can be any combination of one or more of those shown in the following table. |
| [time_refreshed](/diagram/python-net/aspose.diagram/datarecordset/time_refreshed) | The date and time the data recordset was last refreshed. |
| [next_row_id](/diagram/python-net/aspose.diagram/datarecordset/next_row_id) | The next available Visio row ID. |
| [name](/diagram/python-net/aspose.diagram/datarecordset/name) | The display (or "friendly") name of the data recordset. |
| [row_order](/diagram/python-net/aspose.diagram/datarecordset/row_order) | Whether to use the order of the rows in the data recordset as the primary key. True (1) if row IDs are determined by row order. False (0) if row IDs are determined by values in the primary key column(s) of the data recordset. |
| [refresh_overwrite_all](/diagram/python-net/aspose.diagram/datarecordset/refresh_overwrite_all) | Whether to overwrite user changes to shape data items in shapes linked to data when the data recordset is refreshed. |
| [refresh_no_reconciliation_ui](/diagram/python-net/aspose.diagram/datarecordset/refresh_no_reconciliation_ui) | Whether the data-reconciliation user interface should be disabled. True (1) to disable the user interface (UI). False (0) to enable the UI. |
| [refresh_interval](/diagram/python-net/aspose.diagram/datarecordset/refresh_interval) | How often (in minutes) Visio refreshes the data recordset automatically. This value must be 1 or larger. |
| [replace_links](/diagram/python-net/aspose.diagram/datarecordset/replace_links) | Defines how shape-data links are treated when shapes are copied or cut. 1 to replace existing links in the target shape. 0 to maintain existing links in the target shape. If this attribute is absent, Visio asks the user whether to replace links on copy or cut. |
| [checksum](/diagram/python-net/aspose.diagram/datarecordset/checksum) | A checksum value, generated by Visio, and based on data-recordset properties. Set this attribute to 0; Visio recalculates this value at runtime. |
| [ado_data](/diagram/python-net/aspose.diagram/datarecordset/ado_data) | Contains XML that conforms to the ADO classic XML schema for an ADO recordset and that describes the data in the data recordset. |
| [refresh_conflicts](/diagram/python-net/aspose.diagram/datarecordset/refresh_conflicts) | Indicates a row in the data recordset linked to a shape that is in conflict after the data recordset is refreshed.<br/>RowID - Indicates a row in the data recordset linked to a shape that is in conflict after the data recordset is refreshed.<br/>ShapeID - Shape ID of the shape involved in the conflict.<br/>PageID - Page ID of the shape involved in the conflict. |
| [row_maps](/diagram/python-net/aspose.diagram/datarecordset/row_maps) | Maps a data-recordset row to a shape.<br/>RowID - Row ID of the row, unique within the data recordset.<br/>ShapeID - Shape ID of the shape linked to data in the data-recordset row identified by RowID.<br/>PageID - Page ID of the shape linked to data in the data-recordset row identified by RowID. |
| [auto_link_comparison](/diagram/python-net/aspose.diagram/datarecordset/auto_link_comparison) | Defines a rule that compares a column in the parent DataRecordset element with a shape data item from the last successful automatic linking action performed in the user interface. |
| [data_columns](/diagram/python-net/aspose.diagram/datarecordset/data_columns) | Contains all the DataColumn elements in a data recordset. |


### Methods
| Method | Description |
| :- | :- |
| [refresh()](/diagram/python-net/aspose.diagram/datarecordset/refresh/#) | Executes the query string associated with the connected (non-XML-based) DataRecordset and updates linked shapes with new data from the data source returned by the query. |
| [refresh(connection_type)](/diagram/python-net/aspose.diagram/datarecordset/refresh/#aspose.diagram.manipulation.DataConnectionType) | Executes the query string associated with the connected (non-XML-based) DataRecordset and updates linked shapes with new data from the data source returned by the query. |


### See Also

* module [aspose.diagram](../)
