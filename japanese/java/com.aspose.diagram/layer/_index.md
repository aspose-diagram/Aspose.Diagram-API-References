---
title: Layer
second_title: Aspose.Diagram for Java API リファレンス
description: ページ用の単一レイヤーとそのプロパティを定義する要素を含みます。
type: docs
weight: 212
url: /ja/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

ページ用の単一レイヤーとそのプロパティを定義する要素を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Layer()](#Layer--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | レイヤーがアクティブかどうかを指定します。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | レイヤーの表示に使用されるカラーテーブル内の色のインデックス、またはカラーテーブルにないカスタムカラーを指定する RGB 値（例: \#ff9900）。 |
| [getColorTrans()](#getColorTrans--) | レイヤーまたはシェイプのテキストカラーの透明度を決定します。0（完全に不透明）から 1（完全に透明）までの範囲です。 |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getGlue()](#getGlue--) | レイヤーに属するシェイプを接着できるかどうかを指定します。 |
| [getIX()](#getIX--) | 親要素内の要素のゼロベースインデックスです。 |
| [getLock()](#getLock--) | レイヤーに属するシェイプが選択または編集できないようにロックされているかどうかを指定します。 |
| [getName()](#getName--) | Name 要素はレイヤーの名前を指定します。 |
| [getNameUniv()](#getNameUniv--) | レイヤーのユニバーサル名を指定します。 |
| [getPrint()](#getPrint--) | 図面が印刷される際に、レイヤーに属するシェイプが印刷されるかどうかを指定します。 |
| [getSnap()](#getSnap--) | 他のシェイプがレイヤーに割り当てられたシェイプにスナップできるかどうかを指定します。 |
| [getStatus()](#getStatus--) | レイヤーがドキュメントに対して有効なレイヤーかどうかを指定します。 |
| [getVisible()](#getVisible--) | レイヤーに属するシェイプが図面ページ上で表示されるかどうかを指定します。 |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | 要素がローカルでチェックされたかどうかを示すフラグです。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | このプロパティの説明については、[isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) を参照してください。 |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/layer\#getDel--) を参照してください。 |
| [setIX(int value)](#setIX-int-) | このプロパティの説明については、[getIX()](../../com.aspose.diagram/layer\#getIX--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


レイヤーがアクティブかどうかを指定します。事前にレイヤーに割り当てられていないシェイプは、図面ページにドロップされたときにアクティブなレイヤーに割り当てられます。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


レイヤーの表示に使用されるカラーテーブル内の色のインデックス、またはカラーテーブルにないカスタムカラーを指定する RGB 値（例: \#ff9900）。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


レイヤーまたはシェイプのテキストカラーの透明度を決定します。0（完全に不透明）から 1（完全に透明）までの範囲です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


レイヤーに属するシェイプを接着できるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


親要素内の要素のゼロベースインデックスです。

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


レイヤーに属するシェイプが選択または編集できないようにロックされているかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


Name 要素はレイヤーの名前を指定します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


レイヤーのユニバーサル名を指定します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


図面が印刷される際に、レイヤーに属するシェイプが印刷されるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


他のシェイプがレイヤーに割り当てられたシェイプにスナップできるかどうかを指定します。レイヤーに割り当てられたシェイプは他のシェイプにスナップできますが、他のシェイプはそれらにスナップできません。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


レイヤーがドキュメントに対して有効なレイヤーかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


レイヤーに属するシェイプが図面ページ上で表示されるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


要素がローカルでチェックされたかどうかを示すフラグです。値が 1 の場合、要素がローカルでチェックされたことを示します。

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


このプロパティの説明については、[isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel()](../../com.aspose.diagram/layer\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


このプロパティの説明については、[getIX()](../../com.aspose.diagram/layer\#getIX--) を参照してください。

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

