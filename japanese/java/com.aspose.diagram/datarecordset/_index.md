---
title: DataRecordSet
second_title: Aspose.Diagram for Java API リファレンス
description: Microsoft Visio でデータベースからクエリされたデータを保存し、形式を更新し、公開します。
type: docs
weight: 113
url: /ja/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Microsoft Visio でデータベースから取得したデータを保存、書式設定、更新、公開します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | ADO レコードセット用のクラシック XML スキーマに準拠し、データレコードセットのデータを記述する XML を含みます。 |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | 親 DataRecordset 要素の列と、ユーザーインターフェイスで最後に成功した自動リンク操作から取得されたシェイプ データ項目を比較するルールを定義します。 |
| [getChecksum()](#getChecksum--) | Visio が生成し、データレコードセットのプロパティに基づくチェックサム値です。 |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | データ ソースからデータをクエリするために使用されるコマンド文字列です。 |
| [getConnectionID()](#getConnectionID--) | 関連する DataConnection オブジェクトの接続 ID です。 |
| [getDataColumns()](#getDataColumns--) | データレコードセット内のすべての DataColumn 要素を含みます。 |
| [getID()](#getID--) | ドキュメント内で一意のデータレコードセット ID です。 |
| [getName()](#getName--) | データレコードセットの表示名（または「フレンドリー」名）です。 |
| [getNextRowID()](#getNextRowID--) | 次に利用可能な Visio 行 ID です。 |
| [getOptions()](#getOptions--) | データレコードセットに適用するオプションです。 |
| [getPrimaryKeys()](#getPrimaryKeys--) | データレコードセット内の 1 つ以上の主キー列を識別します。 |
| [getRefreshConflicts()](#getRefreshConflicts--) | データレコードセットが更新された後、競合状態にあるシェイプにリンクされたデータレコードセット内の行を示します。 |
| [getRefreshInterval()](#getRefreshInterval--) | Visio がデータレコードセットを自動的に更新する頻度（分単位）です。 |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | データ調整ユーザーインターフェイスを無効にするかどうかです。 |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | データレコードセットが更新されたときに、データにリンクされたシェイプのシェイプ データ項目に対するユーザーの変更を上書きするかどうかです。 |
| [getReplaceLinks()](#getReplaceLinks--) | シェイプがコピーまたは切り取られたときにシェイプ データ リンクがどのように扱われるかを定義します。1 は対象シェイプの既存リンクを置き換え、0 は対象シェイプの既存リンクを維持します。 |
| [getRowMaps()](#getRowMaps--) | データレコードセットの行をシェイプにマッピングします。 |
| [getRowOrder()](#getRowOrder--) | データレコードセットの行順序を主キーとして使用するかどうかです。 |
| [getTimeRefreshed()](#getTimeRefreshed--) | データレコードセットが最後に更新された日時です。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | 接続された（XML 以外の）DataRecordset に関連付けられたクエリ文字列を実行し、クエリで返されたデータソースからの新しいデータでリンクされたシェイプを更新します。 |
| [setADOData(String value)](#setADOData-java.lang.String-) | このプロパティの説明については、[getADOData()](../../com.aspose.diagram/datarecordset\\#getADOData--) を参照してください。 |
| [setChecksum(long value)](#setChecksum-long-) | このプロパティの説明については、\\{@link DataRecordSet\\#(getChecksum() & 0xFFFFFFFFL)\\} を参照してください。 |
| [setCommand(String value)](#setCommand-java.lang.String-) | このプロパティの説明については、[getCommand()](../../com.aspose.diagram/datarecordset\\#getCommand--) を参照してください。 |
| [setConnectionID(long value)](#setConnectionID-long-) | このプロパティの説明については、\\{@link DataRecordSet\\#(getConnectionID() & 0xFFFFFFFFL)\\} を参照してください。 |
| [setID(long value)](#setID-long-) | このプロパティの説明については、\\{@link DataRecordSet\\#(getID() & 0xFFFFFFFFL)\\} を参照してください。 |
| [setName(String value)](#setName-java.lang.String-) | このプロパティの説明については、[getName()](../../com.aspose.diagram/datarecordset\#getName--)をご覧ください。 |
| [setNextRowID(long value)](#setNextRowID-long-) | このプロパティの説明については、\{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}をご参照ください。 |
| [setOptions(int value)](#setOptions-int-) | このプロパティの説明については、[getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)をご覧ください。 |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | このプロパティの説明については、\{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}をご参照ください。 |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | このプロパティの説明については、[getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)をご覧ください。 |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | このプロパティの説明については、[getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)をご覧ください。 |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | このプロパティの説明については、[getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)をご覧ください。 |
| [setRowOrder(int value)](#setRowOrder-int-) | このプロパティの説明については、[getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)をご覧ください。 |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | このプロパティの説明については、[getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)をご覧ください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
```


コンストラクタ。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getADOData() {#getADOData--}
```
public String getADOData()
```


ADO レコードセット用のクラシック XML スキーマに準拠し、データレコードセットのデータを記述する XML を含みます。

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


親 DataRecordset 要素の列と、ユーザーインターフェイスで最後に成功した自動リンク操作から取得されたシェイプ データ項目を比較するルールを定義します。

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


Visio が生成し、data-recordset のプロパティに基づくチェックサム値です。この属性を 0 に設定してください。Visio は実行時にこの値を再計算します。

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


データ ソースからデータをクエリするために使用されるコマンド文字列です。

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


関連付けられた DataConnection オブジェクトの接続 ID です。XML データ ソースには存在しません。

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


データレコードセット内のすべての DataColumn 要素を含みます。

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


ドキュメント内で一意のデータレコードセット ID です。

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


データレコードセットの表示名（または「フレンドリー」名）です。

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


次に利用可能な Visio 行 ID です。

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


データ レコードセットに適用するオプションです。可能な値は、以下の表に示すものの 1 つ以上の組み合わせです。

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


データレコードセット内の 1 つ以上の主キー列を識別します。

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


データ レコードセットが更新された後、競合状態にあるシェイプにリンクされたレコードセットの行を示します。RowID - データ レコードセットが更新された後、競合状態にあるシェイプにリンクされたレコードセットの行を示します。ShapeID - 競合に関与するシェイプのシェイプ ID。PageID - 競合に関与するシェイプのページ ID。

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


Visio がデータ レコードセットを自動的に更新する頻度（分単位）です。この値は 1 以上でなければなりません。

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


データ 照合ユーザー インターフェイスを無効にするかどうかです。True (1) は UI を無効にし、False (0) は UI を有効にします。

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


データレコードセットが更新されたときに、データにリンクされたシェイプのシェイプ データ項目に対するユーザーの変更を上書きするかどうかです。

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


シェイプがコピーまたは切り取りされる際の shape-data リンクの扱いを定義します。1 は対象シェイプの既存リンクを置き換え、0 は既存リンクを維持します。この属性が存在しない場合、Visio はコピーまたは切り取り時にリンクを置き換えるかどうかユーザーに問い合わせます。

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


データ レコードセットの行をシェイプにマッピングします。RowID - データ レコードセット内で一意の行 ID。ShapeID - RowID で識別されたデータ レコードセットの行にリンクされたシェイプのシェイプ ID。PageID - RowID で識別されたデータ レコードセットの行にリンクされたシェイプのページ ID。

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


データ レコードセットの行順序を主キーとして使用するかどうかです。行 ID が行順序で決定される場合は True (1)、データ レコードセットの主キー列の値で決定される場合は False (0) です。

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


データレコードセットが最後に更新された日時です。

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


接続された（XML 以外の）DataRecordset に関連付けられたクエリ文字列を実行し、クエリで返されたデータソースからの新しいデータでリンクされたシェイプを更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| connectionType | int | 接続に使用されるプロバイダーのタイプです Aspose.Diagram.Manipulation.DataConnectionType。 |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


このプロパティの説明については、[getADOData()](../../com.aspose.diagram/datarecordset\\#getADOData--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


このプロパティの説明については、\\{@link DataRecordSet\\#(getChecksum() & 0xFFFFFFFFL)\\} を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


このプロパティの説明については、[getCommand()](../../com.aspose.diagram/datarecordset\\#getCommand--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


このプロパティの説明については、\\{@link DataRecordSet\\#(getConnectionID() & 0xFFFFFFFFL)\\} を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


このプロパティの説明については、\\{@link DataRecordSet\\#(getID() & 0xFFFFFFFFL)\\} を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


このプロパティの説明については、[getName()](../../com.aspose.diagram/datarecordset\#getName--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


このプロパティの説明については、\{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


このプロパティの説明については、[getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


このプロパティの説明については、\{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


このプロパティの説明については、[getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


このプロパティの説明については、[getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


このプロパティの説明については、[getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


このプロパティの説明については、[getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


このプロパティの説明については、[getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

