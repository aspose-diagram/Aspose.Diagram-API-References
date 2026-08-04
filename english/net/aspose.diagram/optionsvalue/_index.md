---
title: Enum OptionsValue
second_title: Aspose.Diagram for .NET API Reference
description: Aspose.Diagram.OptionsValue enum. Optional unsigned integer. Options to apply to the data recordset. Possible values can be any combination of one or more of those shown in the following table
type: docs
url: /net/aspose.diagram/optionsvalue/
---
## OptionsValue enumeration

Optional unsigned integer. Options to apply to the data recordset. Possible values can be any combination of one or more of those shown in the following table.

```csharp
[Flags]
public enum OptionsValue
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NoExternalDataUI | `1` | Prevents data in the data recordset from being displayed in the External Data window. |
| NoAdvConfig | `4` | Limits the control users have of how the data recordset is refreshed in the Configure Refresh dialog box for the data recordset. In particular, users cannot change the primary key or specify when shape data should be overwritten; however, users can set the refresh interval and can change the data source. |
| NoRefreshUI | `2` | Prevents the data recordset from being displayed in the Refresh Data dialog box. |
| NoLinkOnPaste | `10` | Does not copy shape-data links to the Clipboard when shapes are copied or cut. |
| DelayQuery | `8` | Does not execute the command-string query until the next time the data recordset is refreshed. |
| Undefined | `FFFFFFFF80000000` | Undefined. |

### See Also

* namespace [Aspose.Diagram](../../aspose.diagram/)
* assembly [Aspose.Diagram](../../)


