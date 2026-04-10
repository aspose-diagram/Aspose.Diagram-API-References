---
title: 接続
second_title: Aspose.Diagram for Java API リファレンス
description: シェイプに定義された 1 つの接続点の要素を含みます。
type: docs
weight: 78
url: /ja/java/com.aspose.diagram/connection/
---

**Inheritance:**
java.lang.Object
```
public class Connection
```

シェイプに定義された 1 つの接続点の要素を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Connection()](#Connection--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoGen()](#getAutoGen--) | 接続ポイントが自動的に生成されるかどうかを指定します。 |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getDirX()](#getDirX--) | 一致する接続ポイントの必要な整列ベクトルの x 成分を指定します。 |
| [getDirY()](#getDirY--) | 一致する接続ポイントの必要な整列ベクトルの y 成分を指定します。 |
| [getID()](#getID--) | 要素の親要素内における一意の ID。 |
| [getIX()](#getIX--) | 親要素内の要素のゼロベースインデックスです。 |
| [getName()](#getName--) | 要素の名前。 |
| [getNameU()](#getNameU--) | 要素のユニバーサル名。 |
| [getPrompt()](#getPrompt--) | 含まれる要素に基づいて、さまざまなプロンプト情報を含みます。 |
| [getType()](#getType--) | 含まれる要素に基づいてさまざまなタイプを指定します。 |
| [getX()](#getX--) | ローカル座標系でシェイプ上の x 座標を指定します。 |
| [getY()](#getY--) | ローカル座標系でシェイプ上の y 座標を指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/connection\#getDel--) を参照してください。 |
| [setID(int value)](#setID-int-) | このプロパティの説明については、[getID()](../../com.aspose.diagram/connection\#getID--) を参照してください。 |
| [setIX(int value)](#setIX-int-) | このプロパティの説明については、[getIX()](../../com.aspose.diagram/connection\#getIX--) を参照してください。 |
| [setName(String value)](#setName-java.lang.String-) | このプロパティの説明については、[getName()](../../com.aspose.diagram/connection\#getName--) を参照してください。 |
| [setNameU(String value)](#setNameU-java.lang.String-) | このプロパティの説明については、[getNameU()](../../com.aspose.diagram/connection\#getNameU--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Connection() {#Connection--}
```
public Connection()
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
### getAutoGen() {#getAutoGen--}
```
public BoolValue getAutoGen()
```


接続ポイントが自動的に生成されるかどうかを指定します。値が 1 の場合、接続ポイントが自動的に生成されることを示します。

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
### getDirX() {#getDirX--}
```
public DoubleValue getDirX()
```


一致する接続ポイントの必要な整列ベクトルの x 成分を指定します。DirX 要素は、動的コネクタの接続された脚を向けるためにも使用されます。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDirY() {#getDirY--}
```
public DoubleValue getDirY()
```


一致する接続ポイントの必要な整列ベクトルの y 成分を指定します。DirY 要素は、動的コネクタの接続された脚を向けるためにも使用されます。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


含まれる要素に基づいて、さまざまなプロンプト情報を含みます。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeConnection getType()
```


含まれる要素に基づいてさまざまなタイプを指定します。

**Returns:**
[TypeConnection](../../com.aspose.diagram/typeconnection)
### getX() {#getX--}
```
public DoubleValue getX()
```


ローカル座標系でシェイプ上の x 座標を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


ローカル座標系でシェイプ上の y 座標を指定します。ローカル座標系とは、ページではなくシェイプを基準とした座標系です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


このプロパティの説明については、[getDel()](../../com.aspose.diagram/connection\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


このプロパティの説明については、[getID()](../../com.aspose.diagram/connection\#getID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


このプロパティの説明については、[getIX()](../../com.aspose.diagram/connection\#getIX--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


このプロパティの説明については、[getName()](../../com.aspose.diagram/connection\#getName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


このプロパティの説明については、[getNameU()](../../com.aspose.diagram/connection\#getNameU--) を参照してください。

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

