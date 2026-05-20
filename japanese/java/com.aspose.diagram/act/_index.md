---
title: Act
second_title: Aspose.Diagram for Java API リファレンス
description: オブジェクトのショートカットメニューに表示されるカスタムコマンド名を定義し、コマンドが実行するアクションを指定します。
type: docs
weight: 11
url: /ja/java/com.aspose.diagram/act/
---

**Inheritance:**
java.lang.Object
```
public class Act
```

オブジェクトのショートカットメニューに表示されるカスタムコマンド名を定義し、コマンドが実行するアクションを指定します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Act()](#Act--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | 対応する Menu 要素で定義されたコマンド名がユーザーによってクリックされたときに実行される数式を含みます。 |
| [getBeginGroup()](#getBeginGroup--) | このアクションの上のメニューに区切り線が挿入されるかどうかを示します。 |
| [getButtonFace()](#getButtonFace--) | ショートカットメニューの項目の横に表示されるアイコンを識別します。 |
| [getChecked()](#getChecked--) | シェイプのショートカットメニューでコマンド名の横にチェックマークが表示されるかどうかを決定します。 |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getDisabled()](#getDisabled--) | 無効化された要素は、ショートカットメニューにコマンド名が表示されるかどうかを決定します。 |
| [getFlyoutChild()](#getFlyoutChild--) | アクション行が、上方の最後の行でフライアウト子ではない行の子フライアウトメニューであるかどうかを決定します。 |
| [getID()](#getID--) | 要素の親要素内における一意の ID。 |
| [getIX()](#getIX--) | 親要素内の要素のゼロベースインデックスです。 |
| [getInvisible()](#getInvisible--) | 不可視要素は、スマートタグまたはショートカットメニュー上でアクションが表示されるかどうかを示します。 |
| [getMenu()](#getMenu--) | シェイプまたはページのショートカットメニューに表示されるコマンド名を指定します。 |
| [getName()](#getName--) | 要素の名前。 |
| [getNameU()](#getNameU--) | 要素のユニバーサル名。 |
| [getReadOnly()](#getReadOnly--) | スマートタグまたはショートカットメニュー上のアクションが読み取り専用かどうかを決定します。 |
| [getSortKey()](#getSortKey--) | ショートカットまたはスマートタグメニューに表示されるアクションの順序を決定する番号を指定します。 |
| [getTagName()](#getTagName--) | このアクションに関連付けられたスマートタグの名前が含まれています。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/act\#getDel--) を参照してください。 |
| [setID(int value)](#setID-int-) | このプロパティの説明については、[getID()](../../com.aspose.diagram/act\#getID--) を参照してください。 |
| [setIX(int value)](#setIX-int-) | このプロパティの説明については、[getIX()](../../com.aspose.diagram/act\#getIX--) を参照してください。 |
| [setName(String value)](#setName-java.lang.String-) | このプロパティの説明については、[getName()](../../com.aspose.diagram/act\#getName--) を参照してください。 |
| [setNameU(String value)](#setNameU-java.lang.String-) | このプロパティの説明については、[getNameU()](../../com.aspose.diagram/act\#getNameU--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Act() {#Act--}
```
public Act()
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
### getAction() {#getAction--}
```
public DoubleValue getAction()
```


対応する Menu 要素で定義されたコマンド名がユーザーによってクリックされたときに実行される数式を含みます。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBeginGroup() {#getBeginGroup--}
```
public BoolValue getBeginGroup()
```


このアクションの上のメニューに区切り線が挿入されるかどうかを示します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getButtonFace() {#getButtonFace--}
```
public Str2Value getButtonFace()
```


ショートカットメニューの項目の横に表示されるアイコンを識別します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getChecked() {#getChecked--}
```
public BoolValue getChecked()
```


シェイプのショートカットメニューでコマンド名の横にチェックマークが表示されるかどうかを決定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getDisabled() {#getDisabled--}
```
public BoolValue getDisabled()
```


無効化された要素は、ショートカットメニューにコマンド名が表示されるかどうかを決定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlyoutChild() {#getFlyoutChild--}
```
public BoolValue getFlyoutChild()
```


アクション行が、上方の最後の行でフライアウト子ではない行の子フライアウトメニューであるかどうかを決定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


不可視要素は、スマートタグまたはショートカットメニュー上でアクションが表示されるかどうかを示します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getMenu() {#getMenu--}
```
public Str2Value getMenu()
```


シェイプまたはページのショートカットメニューに表示されるコマンド名を指定します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getReadOnly() {#getReadOnly--}
```
public BoolValue getReadOnly()
```


スマートタグまたはショートカットメニュー上のアクションが読み取り専用かどうかを決定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


ショートカットまたはスマートタグメニューに表示されるアクションの順序を決定する番号を指定します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getTagName() {#getTagName--}
```
public Str2Value getTagName()
```


このアクションに関連付けられたスマートタグの名前が含まれています。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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


このプロパティの説明については、[getDel()](../../com.aspose.diagram/act\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


このプロパティの説明については、[getID()](../../com.aspose.diagram/act\#getID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


このプロパティの説明については、[getIX()](../../com.aspose.diagram/act\#getIX--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


このプロパティの説明については、[getName()](../../com.aspose.diagram/act\#getName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


このプロパティの説明については、[getNameU()](../../com.aspose.diagram/act\#getNameU--) を参照してください。

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

