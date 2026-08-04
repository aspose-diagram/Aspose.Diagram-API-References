---
title: "DataConnection Class"
linktitle: "DataConnection"
articleTitle: "DataConnection"
second_title: "Aspose.Diagram for Python via Java"
description: "Abstracts communication between one or more DataRecordset elements and a non-XML data source."
type: docs
weight: 830
url: /python-java/asposediagram.api/dataconnection/
---

## DataConnection class

Abstracts communication between one or more DataRecordset elements and a non-XML data source.

```python
DataConnection()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ID](./id/) | long | The ID assigned by Visio for a given connection, unique within the document. |
| [FileName](./filename/) | String | The name of the connection file. See Remarks for more information. |
| [ConnectionString](./connectionstring/) | String | The connection string that defines the parameters necessary to connect to a data source. |
| [Command](./command/) | String | The command string used to query the data source. |
| [Timeout](./timeout/) | long | wait time in minutes while trying to establish a connection before terminating the attempt. |
| [AlwaysUseConnectionFile](./alwaysuseconnectionfile/) | int | The default value is false. See Remarks for more information. The value of the property is BOOL integer constant. |
