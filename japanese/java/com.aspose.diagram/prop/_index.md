---
title: プロパティ
second_title: Aspose.Diagram for Java API リファレンス
description: カスタム プロパティを定義する要素と、データをシェイプに関連付ける要素を含みます。
type: docs
weight: 309
url: /ja/java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

カスタム プロパティを定義する要素と、データをシェイプに関連付ける要素を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Prop()](#Prop--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | カスタム プロパティ、テキスト フィールド、要素の数式に使用されるカレンダーを決定します。 |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getFormat()](#getFormat--) | Format 要素は、文字列、固定リスト、数値、可変リスト、日付または時刻、期間、または通貨であるカスタム プロパティの書式設定を指定します。 |
| [getID()](#getID--) | 要素の親要素内における一意の ID。 |
| [getIX()](#getIX--) | 親要素内の要素のゼロベースインデックスです。 |
| [getInvisible()](#getInvisible--) | Invisible 要素は、Microsoft Visio のカスタム プロパティ ダイアログ ボックスでカスタム プロパティが表示されるかどうかを指定します。 |
| [getLabel()](#getLabel--) | カスタム プロパティ ダイアログ ボックスにユーザーに表示されるラベルを指定します。 |
| [getLangID()](#getLangID--) | セルの数式、テキスト、カスタムプロパティ、またはコメントが入力された言語のロケール ID (LCID) を示します。 |
| [getName()](#getName--) | 要素の名前。 |
| [getNameU()](#getNameU--) | 要素のユニバーサル名。 |
| [getPrompt()](#getPrompt--) | Prompt 要素は、プロパティが選択されたときにカスタム プロパティ ダイアログ ボックスにユーザーに表示される説明的または指示的なテキストを指定します。 |
| [getSortKey()](#getSortKey--) | カスタム プロパティがアプリケーションのユーザー インターフェイスに一覧表示される順序を決定するキーを指定します。 |
| [getType()](#getType--) | Type はカスタム プロパティの値のデータ型を指定します。 |
| [getValue()](#getValue--) | 明示的な名前空間でプレフィックスが付けられ、ドキュメントに保存される、ソリューション固有の整形式 XML データを含みます。 |
| [getVerify()](#getVerify--) | インスタンスが作成されたとき、またはシェイプが複製またはコピーされたときに、ユーザーにシェイプのカスタム プロパティ情報の入力を求めるかどうかを指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/prop\#getDel--) を参照してください。 |
| [setID(int value)](#setID-int-) | このプロパティの説明については、[getID()](../../com.aspose.diagram/prop\#getID--) を参照してください。 |
| [setIX(int value)](#setIX-int-) | このプロパティの説明については、[getIX()](../../com.aspose.diagram/prop\#getIX--) を参照してください。 |
| [setName(String value)](#setName-java.lang.String-) | このプロパティの説明については、[getName()](../../com.aspose.diagram/prop\#getName--) を参照してください。 |
| [setNameU(String value)](#setNameU-java.lang.String-) | このプロパティの説明については、[getNameU()](../../com.aspose.diagram/prop\#getNameU--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


コンストラクタ。

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


このインスタンスのディープコピーを作成します。

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


Format 要素は、文字列、固定リスト、数値、可変リスト、日付または時刻、期間、または通貨であるカスタム プロパティの書式設定を指定します。カスタム プロパティのタイプは、対応する Type 要素で指定されます。

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getID() {#getID--}
```
public int getID()
```


要素の親要素内における一意の ID。

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


親要素内の要素のゼロベースインデックスです。

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Invisible 要素は、Microsoft Visio のカスタム プロパティ ダイアログ ボックスでカスタム プロパティが表示されるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


カスタム プロパティ ダイアログ ボックスにユーザーに表示されるラベルを指定します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


セルの数式、テキスト、カスタムプロパティ、またはコメントが入力された言語のロケール ID (LCID) を示します。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getName() {#getName--}
```
public String getName()
```


要素の名前。

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


要素のユニバーサル名。

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Prompt 要素は、プロパティが選択されたときにカスタム プロパティ ダイアログ ボックスにユーザーに表示される説明または指示テキストを指定します。このテキストは、カスタム プロパティ ウィンドウでプロパティ上にマウス ポインタを停止させたときのツールチップとしても表示されます。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


カスタム プロパティがアプリケーションのユーザー インターフェイスに一覧表示される順序を決定するキーを指定します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Type はカスタム プロパティの値のデータ型を指定します。

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


明示的な名前空間でプレフィックスが付けられ、ドキュメントに保存される、ソリューション固有の整形式 XML データを含みます。

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


インスタンスが作成されたとき、またはシェイプが複製またはコピーされたときに、ユーザーにシェイプのカスタム プロパティ情報の入力を求めるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


このプロパティの説明については、[getDel()](../../com.aspose.diagram/prop\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


このプロパティの説明については、[getID()](../../com.aspose.diagram/prop\#getID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


このプロパティの説明については、[getIX()](../../com.aspose.diagram/prop\#getIX--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


このプロパティの説明については、[getName()](../../com.aspose.diagram/prop\#getName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


このプロパティの説明については、[getNameU()](../../com.aspose.diagram/prop\#getNameU--) を参照してください。

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

