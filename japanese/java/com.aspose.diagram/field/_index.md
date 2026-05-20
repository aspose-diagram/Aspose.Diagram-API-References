---
title: Field
second_title: Aspose.Diagram for Java API リファレンス
description: シェイプのテキストに挿入された関数や数式を指定する要素を含みます。
type: docs
weight: 147
url: /ja/java/com.aspose.diagram/field/
---

**Inheritance:**
java.lang.Object
```
public class Field
```

シェイプのテキストに挿入された関数と数式を指定する要素を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Field()](#Field--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | カスタム プロパティ、テキスト フィールド、要素の数式に使用されるカレンダーを決定します。 |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getDisplayValue()](#getDisplayValue--) | このフィールドの書式設定された文字列値を取得します。 |
| [getEditMode()](#getEditMode--) | 将来の使用のために予約されています。 |
| [getFormat()](#getFormat--) | Format 要素は、文字列、数値、日付または時刻、期間、通貨のテキスト フィールドの書式設定を指定します。 |
| [getIX()](#getIX--) | 親要素内の要素のゼロベースインデックスです。 |
| [getObjectKind()](#getObjectKind--) | テキスト フィールドのタイプを示します。 |
| [getType()](#getType--) | Type はテキスト フィールドの値のデータ型を指定します。 |
| [getUICat()](#getUICat--) | Visio 2000 より前の Microsoft Visio バージョンで挿入されたフィールドのカテゴリを指定します。 |
| [getUICod()](#getUICod--) | Visio 2000 より前の Microsoft Visio バージョンで挿入されたフィールドのコードを指定します。 |
| [getUIFmt()](#getUIFmt--) | Visio 2000 より前の Microsoft Visio バージョンで挿入されたフィールドの書式を指定します。 |
| [getValue()](#getValue--) | テキスト フィールドの値を含みます。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/field\#getDel--) を参照してください。 |
| [setIX(int value)](#setIX-int-) | このプロパティの説明については、[getIX()](../../com.aspose.diagram/field\#getIX--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Field() {#Field--}
```
public Field()
```


コンストラクタ。

### deepClone() {#deepClone--}
```
public Object deepClone()
```


このインスタンスのディープコピーを作成します。

**Returns:**
java.lang.Object -
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
public Calendar getCalendar()
```


カスタム プロパティ、テキスト フィールド、要素の数式に使用されるカレンダーを決定します。

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getDisplayValue() {#getDisplayValue--}
```
public String getDisplayValue()
```


このフィールドの書式設定された文字列値を取得します。

**Returns:**
java.lang.String
### getEditMode() {#getEditMode--}
```
public DoubleValue getEditMode()
```


将来の使用のために予約されています。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFormat() {#getFormat--}
```
public Value getFormat()
```


Format 要素は、文字列、数値、日付または時刻、期間、または通貨であるテキストフィールドの書式設定を指定します。テキストフィールドのタイプは、対応する Type 要素で指定されます。

**Returns:**
[Value](../../com.aspose.diagram/value)
### getIX() {#getIX--}
```
public int getIX()
```


親要素内の要素のゼロベースインデックスです。

**Returns:**
int
### getObjectKind() {#getObjectKind--}
```
public ObjectKind getObjectKind()
```


テキスト フィールドのタイプを示します。

**Returns:**
[ObjectKind](../../com.aspose.diagram/objectkind)
### getType() {#getType--}
```
public TypeField getType()
```


Type はテキスト フィールドの値のデータ型を指定します。

**Returns:**
[TypeField](../../com.aspose.diagram/typefield)
### getUICat() {#getUICat--}
```
public DoubleValue getUICat()
```


Visio 2000 より前の Microsoft Visio バージョンで挿入されたフィールドのカテゴリを指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUICod() {#getUICod--}
```
public DoubleValue getUICod()
```


Visio 2000 より前の Microsoft Visio バージョンで挿入されたフィールドのコードを指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUIFmt() {#getUIFmt--}
```
public DoubleValue getUIFmt()
```


Visio 2000 より前の Microsoft Visio バージョンで挿入されたフィールドの書式を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getValue() {#getValue--}
```
public Value getValue()
```


テキスト フィールドの値を含みます。

**Returns:**
[Value](../../com.aspose.diagram/value)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel()](../../com.aspose.diagram/field\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


このプロパティの説明については、[getIX()](../../com.aspose.diagram/field\#getIX--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

