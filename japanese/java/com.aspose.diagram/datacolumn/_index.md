---
title: DataColumn
second_title: Aspose.Diagram for Java API リファレンス
description: Visio ユーザーインターフェイスの外部データウィンドウでデータ列がどのように表示されるかを定義し、データ型と書式設定を定義することで列のデータを限定します。
type: docs
weight: 108
url: /ja/java/com.aspose.diagram/datacolumn/
---

**Inheritance:**
java.lang.Object
```
public class DataColumn
```

Visio ユーザーインターフェイスの外部データウィンドウでデータ列がどのように表示されるかを定義し、データ型と書式設定を定義することで列のデータを限定します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DataColumn()](#DataColumn--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | データ列のカレンダー ID。 |
| [getClass()](#getClass--) |  |
| [getColumnNameID()](#getColumnNameID--) | データ列の外部名。 |
| [getCurrency()](#getCurrency--) | データ列の通貨 ID。 |
| [getDataType()](#getDataType--) | データ列のデータ型。 |
| [getDegree()](#getDegree--) | 単位の次数（べき）を指定します。例: 二乗、三乗。 |
| [getDisplayOrder()](#getDisplayOrder--) | 外部データウィンドウ内でデータ列の表示位置を定義します。左端の列 (0) から右端の列 (最大値) まで。 |
| [getDisplayWidth()](#getDisplayWidth--) | 外部データウィンドウ内のデータ列の幅。 |
| [getHyperlink()](#getHyperlink--) | シェイプがデータにリンクされている場合に、データ列がシェイプ内にハイパーリンクを作成するかどうか。 |
| [getLabel()](#getLabel--) | データ列のラベル。 |
| [getLangID()](#getLangID--) | データ列の言語 ID |
| [getMapped()](#getMapped--) | 外部データウィンドウで列が表示されるかどうかを指定します。 |
| [getName()](#getName--) | データ列の内部名。 |
| [getOrigLabel()](#getOrigLabel--) | 基礎となる ADO インターフェイスによって Visio に返される列ラベルです。 |
| [getUnitType()](#getUnitType--) | データ列のデータの単位タイプです。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCalendar(int value)](#setCalendar-int-) | このプロパティの説明については、以下をご参照ください \{@link DataColumn\#(getCalendar() & 0xFFFF)\} |
| [setColumnNameID(String value)](#setColumnNameID-java.lang.String-) | このプロパティの説明については、[getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--)をご参照ください |
| [setCurrency(int value)](#setCurrency-int-) | このプロパティの説明については、\{@link DataColumn\#(getCurrency() & 0xFFFF)\}をご参照ください |
| [setDataType(int value)](#setDataType-int-) | このプロパティの説明については、\{@link DataColumn\#(getDataType() & 0xFFFF)\}をご参照ください |
| [setDegree(long value)](#setDegree-long-) | このプロパティの説明については、[getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--)をご参照ください |
| [setDisplayOrder(long value)](#setDisplayOrder-long-) | このプロパティの説明については、[getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--)をご参照ください |
| [setDisplayWidth(long value)](#setDisplayWidth-long-) | このプロパティの説明については、[getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--)をご参照ください |
| [setHyperlink(int value)](#setHyperlink-int-) | このプロパティの説明については、[getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--)をご参照ください |
| [setLabel(String value)](#setLabel-java.lang.String-) | このプロパティの説明については、[getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--)をご参照ください |
| [setLangID(long value)](#setLangID-long-) | このプロパティの説明については、[getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--)をご参照ください |
| [setMapped(int value)](#setMapped-int-) | このプロパティの説明については、[getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--)をご参照ください |
| [setName(String value)](#setName-java.lang.String-) | このプロパティの説明については、[getName()](../../com.aspose.diagram/datacolumn\#getName--)をご参照ください |
| [setOrigLabel(String value)](#setOrigLabel-java.lang.String-) | このプロパティの説明については、[getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--)をご参照ください |
| [setUnitType(String value)](#setUnitType-java.lang.String-) | このプロパティの説明については、[getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--)をご参照ください |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataColumn() {#DataColumn--}
```
public DataColumn()
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
### getCalendar() {#getCalendar--}
```
public int getCalendar()
```


データ列のカレンダー ID。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnNameID() {#getColumnNameID--}
```
public String getColumnNameID()
```


データ列の外部名です。外部データウィンドウの見出しやデータ グラフィックのラベルに表示されます。

**Returns:**
java.lang.String
### getCurrency() {#getCurrency--}
```
public int getCurrency()
```


データ列の通貨 ID。

**Returns:**
int
### getDataType() {#getDataType--}
```
public int getDataType()
```


データ列のデータ型。

**Returns:**
int
### getDegree() {#getDegree--}
```
public long getDegree()
```


単位の次数（べき）を指定します。たとえば二乗や三乗です。デフォルト（属性がない場合）は 1 です。

**Returns:**
long
### getDisplayOrder() {#getDisplayOrder--}
```
public long getDisplayOrder()
```


外部データウィンドウ内でデータ列の表示位置を定義します。左端の列 (0) から右端の列 (最大値) まで。

**Returns:**
long
### getDisplayWidth() {#getDisplayWidth--}
```
public long getDisplayWidth()
```


外部データウィンドウ内のデータ列の幅。

**Returns:**
long
### getHyperlink() {#getHyperlink--}
```
public int getHyperlink()
```


シェイプがデータにリンクされている場合に、データ列がシェイプ内にハイパーリンクを作成するかどうか。

**Returns:**
int
### getLabel() {#getLabel--}
```
public String getLabel()
```


データ列のラベル。

**Returns:**
java.lang.String
### getLangID() {#getLangID--}
```
public long getLangID()
```


データ列の言語 ID

**Returns:**
long
### getMapped() {#getMapped--}
```
public int getMapped()
```


列が外部データウィンドウに表示されるかどうかを指定します。表示する場合は true (1)、表示しない場合は false (0) です。デフォルト（属性がない場合）は列が表示される設定です。

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


データ列の内部名です。シェイプがデータ行にリンクされる際にシェイプに追加されるシェイプ データ アイテム（カスタム プロパティ）の行名として使用されます。

**Returns:**
java.lang.String
### getOrigLabel() {#getOrigLabel--}
```
public String getOrigLabel()
```


基礎となる ADO インターフェイスによって Visio に返される列ラベルです。

**Returns:**
java.lang.String
### getUnitType() {#getUnitType--}
```
public String getUnitType()
```


データ列のデータの単位タイプです。

**Returns:**
java.lang.String
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




### setCalendar(int value) {#setCalendar-int-}
```
public void setCalendar(int value)
```


このプロパティの説明については、以下をご参照ください \{@link DataColumn\#(getCalendar() & 0xFFFF)\}

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setColumnNameID(String value) {#setColumnNameID-java.lang.String-}
```
public void setColumnNameID(String value)
```


このプロパティの説明については、[getColumnNameID()](../../com.aspose.diagram/datacolumn\#getColumnNameID--)をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setCurrency(int value) {#setCurrency-int-}
```
public void setCurrency(int value)
```


このプロパティの説明については、\{@link DataColumn\#(getCurrency() & 0xFFFF)\}をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDataType(int value) {#setDataType-int-}
```
public void setDataType(int value)
```


このプロパティの説明については、\{@link DataColumn\#(getDataType() & 0xFFFF)\}をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDegree(long value) {#setDegree-long-}
```
public void setDegree(long value)
```


このプロパティの説明については、[getDegree()](../../com.aspose.diagram/datacolumn\#getDegree--)をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setDisplayOrder(long value) {#setDisplayOrder-long-}
```
public void setDisplayOrder(long value)
```


このプロパティの説明については、[getDisplayOrder()](../../com.aspose.diagram/datacolumn\#getDisplayOrder--)をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setDisplayWidth(long value) {#setDisplayWidth-long-}
```
public void setDisplayWidth(long value)
```


このプロパティの説明については、[getDisplayWidth()](../../com.aspose.diagram/datacolumn\#getDisplayWidth--)をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setHyperlink(int value) {#setHyperlink-int-}
```
public void setHyperlink(int value)
```


このプロパティの説明については、[getHyperlink()](../../com.aspose.diagram/datacolumn\#getHyperlink--)をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setLabel(String value) {#setLabel-java.lang.String-}
```
public void setLabel(String value)
```


このプロパティの説明については、[getLabel()](../../com.aspose.diagram/datacolumn\#getLabel--)をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setLangID(long value) {#setLangID-long-}
```
public void setLangID(long value)
```


このプロパティの説明については、[getLangID()](../../com.aspose.diagram/datacolumn\#getLangID--)をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setMapped(int value) {#setMapped-int-}
```
public void setMapped(int value)
```


このプロパティの説明については、[getMapped()](../../com.aspose.diagram/datacolumn\#getMapped--)をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


このプロパティの説明については、[getName()](../../com.aspose.diagram/datacolumn\#getName--)をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setOrigLabel(String value) {#setOrigLabel-java.lang.String-}
```
public void setOrigLabel(String value)
```


このプロパティの説明については、[getOrigLabel()](../../com.aspose.diagram/datacolumn\#getOrigLabel--)をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setUnitType(String value) {#setUnitType-java.lang.String-}
```
public void setUnitType(String value)
```


このプロパティの説明については、[getUnitType()](../../com.aspose.diagram/datacolumn\#getUnitType--)をご参照ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

