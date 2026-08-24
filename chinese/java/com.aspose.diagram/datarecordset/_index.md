---
title: DataRecordSet
second_title: Aspose.Diagram for Java API 参考
description: 存储、格式化、刷新并公开从数据库查询的数据，位于 Microsoft Visio 中。
type: docs
weight: 113
url: /zh/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

在 Microsoft Visio 中存储、格式化、刷新并公开从数据库查询的数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | 包含符合 ADO 经典 XML 架构的 XML，用于 ADO 记录集，并描述数据记录集中的数据。 |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | 定义一条规则，将父 DataRecordset 元素中的列与用户界面中上一次成功的自动链接操作产生的形状数据项进行比较。 |
| [getChecksum()](#getChecksum--) | 由 Visio 生成的校验和值，基于 data-recordset 属性。 |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | 用于从数据源查询数据的命令字符串。 |
| [getConnectionID()](#getConnectionID--) | 关联的 DataConnection 对象的连接 ID。 |
| [getDataColumns()](#getDataColumns--) | 包含数据记录集中的所有 DataColumn 元素。 |
| [getID()](#getID--) | 数据记录集 ID，在文档中唯一。 |
| [getName()](#getName--) | 数据记录集的显示（或"友好"）名称。 |
| [getNextRowID()](#getNextRowID--) | 下一个可用的 Visio 行 ID。 |
| [getOptions()](#getOptions--) | 应用于数据记录集的选项。 |
| [getPrimaryKeys()](#getPrimaryKeys--) | 标识数据记录集中的一个或多个主键列。 |
| [getRefreshConflicts()](#getRefreshConflicts--) | 指示在数据记录集刷新后，与形状关联且出现冲突的记录集行。 |
| [getRefreshInterval()](#getRefreshInterval--) | Visio 自动刷新数据记录集的频率（以分钟为单位）。 |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | 是否应禁用数据对账用户界面。 |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | 在数据记录集刷新时，是否覆盖链接到数据的形状中形状数据项的用户更改。 |
| [getReplaceLinks()](#getReplaceLinks--) | 定义在复制或剪切形状时形状数据链接的处理方式。1 表示替换目标形状中已有的链接。0 表示保留目标形状中已有的链接。 |
| [getRowMaps()](#getRowMaps--) | 将 data-recordset 行映射到形状。 |
| [getRowOrder()](#getRowOrder--) | 是否使用数据记录集行的顺序作为主键。 |
| [getTimeRefreshed()](#getTimeRefreshed--) | 数据记录集上次刷新的日期和时间。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | 执行与已连接（非基于 XML）的 DataRecordset 关联的查询字符串，并使用查询返回的数据源中的新数据更新已链接的形状。 |
| [setADOData(String value)](#setADOData-java.lang.String-) | 有关此属性的描述，请参阅 [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | 有关此属性的描述，请参阅 \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | 有关此属性的描述，请参阅 [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | 有关此属性的描述，请参阅 \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | 有关此属性的描述，请参阅 \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | 有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | 有关此属性的描述，请参阅 \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | 有关此属性的描述，请参阅 [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | 有关此属性的描述，请参阅 \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | 有关此属性的描述，请参阅 [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | 有关此属性的描述，请参阅 [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | 有关此属性的描述，请参阅 [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | 有关此属性的描述，请参阅 [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | 有关此属性的描述，请参阅 [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
```


构造函数。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getADOData() {#getADOData--}
```
public String getADOData()
```


包含符合 ADO 经典 XML 架构的 XML，用于 ADO 记录集，并描述数据记录集中的数据。

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


定义一条规则，将父 DataRecordset 元素中的列与用户界面中上一次成功的自动链接操作产生的形状数据项进行比较。

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


由 Visio 生成的校验和值，基于 data-recordset 属性。将此属性设置为 0；Visio 在运行时重新计算此值。

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCommand() {#getCommand--}
```
public String getCommand()
```


用于从数据源查询数据的命令字符串。

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


关联的 DataConnection 对象的连接 ID。XML 数据源不存在此项。

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


包含数据记录集中的所有 DataColumn 元素。

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


数据记录集 ID，在文档中唯一。

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


数据记录集的显示（或"友好"）名称。

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


下一个可用的 Visio 行 ID。

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


应用于 data recordset 的选项。可能的取值可以是下表中显示的一个或多个组合。

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


标识数据记录集中的一个或多个主键列。

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


指示在 data recordset 中与形状关联的行，该形状在 data recordset 刷新后出现冲突。RowID - 指示在 data recordset 中与形状关联的行，该形状在 data recordset 刷新后出现冲突。ShapeID - 发生冲突的形状的 Shape ID。PageID - 发生冲突的形状的 Page ID。

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


Visio 自动刷新 data recordset 的频率（以分钟为单位）。此值必须大于等于 1。

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


是否应禁用数据调和用户界面。True (1) 表示禁用用户界面 (UI)。False (0) 表示启用 UI。

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


在数据记录集刷新时，是否覆盖链接到数据的形状中形状数据项的用户更改。

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


定义在复制或剪切形状时 shape-data 链接的处理方式。1 表示替换目标形状中已有的链接。0 表示保留目标形状中已有的链接。如果此属性缺失，Visio 会询问用户在复制或剪切时是否替换链接。

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


将 data-recordset 行映射到形状。RowID - 行的 Row ID，在 data recordset 中唯一。ShapeID - 与由 RowID 标识的 data-recordset 行中的数据关联的形状的 Shape ID。PageID - 与由 RowID 标识的 data-recordset 行中的数据关联的形状的 Page ID。

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


是否使用 data recordset 中行的顺序作为主键。如果行 ID 由行顺序决定，则为 True (1)；如果行 ID 由 data recordset 主键列的值决定，则为 False (0)。

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


数据记录集上次刷新的日期和时间。

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refresh(int connectionType) {#refresh-int-}
```
public void refresh(int connectionType)
```


执行与已连接（非基于 XML）的 DataRecordset 关联的查询字符串，并使用查询返回的数据源中的新数据更新已链接的形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| connectionType | int | 将用于 connectionAspose.Diagram.Manipulation.DataConnectionType 的提供程序类型。 |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


有关此属性的描述，请参阅 [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


有关此属性的描述，请参阅 \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


有关此属性的描述，请参阅 [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


有关此属性的描述，请参阅 \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


有关此属性的描述，请参阅 \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


有关此属性的描述，请参阅 \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


有关此属性的描述，请参阅 [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


有关此属性的描述，请参阅 \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


有关此属性的描述，请参阅 [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


有关此属性的描述，请参阅 [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


有关此属性的描述，请参阅 [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


有关此属性的描述，请参阅 [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


有关此属性的描述，请参阅 [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

