---
title: コントロール
second_title: Aspose.Diagram for Java API リファレンス
description: シェイプに定義された各コントロールハンドルの x および y 座標の要素と、コントロールハンドルの動作方法を指定する要素を含みます。
type: docs
weight: 87
url: /ja/java/com.aspose.diagram/control/
---

**Inheritance:**
java.lang.Object
```
public class Control
```

シェイプに定義された各コントロールハンドルの x および y 座標の要素と、コントロールハンドルの動作方法を指定する要素を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Control()](#Control--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [canGlue()](#canGlue--) | コントロールハンドルを他のシェイプに貼り付けできるかどうかを決定します。 |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getID()](#getID--) | 要素の親要素内における一意の ID。 |
| [getIX()](#getIX--) | 親要素内の要素のゼロベースインデックスです。 |
| [getName()](#getName--) | 要素の名前。 |
| [getNameU()](#getNameU--) | 要素のユニバーサル名。 |
| [getPrompt()](#getPrompt--) | プロンプト要素は、マウスポインタがシェイプのコントロールハンドル上に停止したときにツールチップとして表示される説明テキストを指定します。 |
| [getX()](#getX--) | シェイプのコントロールハンドルの位置を示す x 座標です。 |
| [getXCon()](#getXCon--) | ハンドルが移動した後のコントロールハンドルの x 座標が示す動作の種類を指定します。 |
| [getXDyn()](#getXDyn--) | ローカル座標系でのコントロールハンドルのアンカーポイントの x 座標を指定します。 |
| [getY()](#getY--) | シェイプのコントロールハンドルの位置を示す y 座標です。 |
| [getYCon()](#getYCon--) | ハンドルが移動した後のコントロールハンドルの x 座標が示す動作の種類を指定します。 |
| [getYDyn()](#getYDyn--) | ローカル座標系でのコントロールハンドルのアンカーポイントの y 座標を指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCanGlue(BoolValue value)](#setCanGlue-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[canGlue()](../../com.aspose.diagram/control\#canGlue--) を参照してください。 |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/control\#getDel--) を参照してください。 |
| [setID(int value)](#setID-int-) | このプロパティの説明については、[getID()](../../com.aspose.diagram/control\#getID--) を参照してください。 |
| [setIX(int value)](#setIX-int-) | このプロパティの説明については、[getIX()](../../com.aspose.diagram/control\#getIX--) を参照してください。 |
| [setName(String value)](#setName-java.lang.String-) | このプロパティの説明については、[getName()](../../com.aspose.diagram/control\#getName--) を参照してください。 |
| [setNameU(String value)](#setNameU-java.lang.String-) | このプロパティの説明については、[getNameU()](../../com.aspose.diagram/control\#getNameU--) を参照してください。 |
| [setPrompt(Str2Value value)](#setPrompt-com.aspose.diagram.Str2Value-) | このプロパティの説明については、[getPrompt()](../../com.aspose.diagram/control\#getPrompt--) を参照してください。 |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getX()](../../com.aspose.diagram/control\#getX--) を参照してください。 |
| [setXCon(ConType value)](#setXCon-com.aspose.diagram.ConType-) | このプロパティの説明については、[getXCon()](../../com.aspose.diagram/control\#getXCon--) を参照してください。 |
| [setXDyn(DoubleValue value)](#setXDyn-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getXDyn()](../../com.aspose.diagram/control\#getXDyn--) を参照してください。 |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getY()](../../com.aspose.diagram/control\#getY--) を参照してください。 |
| [setYCon(ConType value)](#setYCon-com.aspose.diagram.ConType-) | このプロパティの説明については、[getYCon()](../../com.aspose.diagram/control\#getYCon--) を参照してください。 |
| [setYDyn(DoubleValue value)](#setYDyn-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getYDyn()](../../com.aspose.diagram/control\#getYDyn--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Control() {#Control--}
```
public Control()
```


コンストラクタ。

### canGlue() {#canGlue--}
```
public BoolValue canGlue()
```


コントロールハンドルを他のシェイプに貼り付けできるかどうかを決定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


プロンプト要素は、マウスポインタがシェイプのコントロールハンドル上に停止したときにツールチップとして表示される説明テキストを指定します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getX() {#getX--}
```
public DoubleValue getX()
```


シェイプのコントロールハンドルの位置を示す x 座標です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getXCon() {#getXCon--}
```
public ConType getXCon()
```


ハンドルが移動した後のコントロールハンドルの x 座標が示す動作の種類を指定します。

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getXDyn() {#getXDyn--}
```
public DoubleValue getXDyn()
```


ローカル座標系におけるコントロールハンドルのアンカーポイントの x 座標を指定します。アンカーポイントは動的処理中のラバーバンドに使用されます。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


シェイプのコントロールハンドルの位置を示す y 座標です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getYCon() {#getYCon--}
```
public ConType getYCon()
```


ハンドルが移動した後のコントロールハンドルの x 座標が示す動作の種類を指定します。

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getYDyn() {#getYDyn--}
```
public DoubleValue getYDyn()
```


ローカル座標系におけるコントロールハンドルのアンカーポイントの y 座標を指定します。アンカーポイントは動的処理中のラバーバンドに使用されます。

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




### setCanGlue(BoolValue value) {#setCanGlue-com.aspose.diagram.BoolValue-}
```
public void setCanGlue(BoolValue value)
```


このプロパティの説明については、[canGlue()](../../com.aspose.diagram/control\#canGlue--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel()](../../com.aspose.diagram/control\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


このプロパティの説明については、[getID()](../../com.aspose.diagram/control\#getID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


このプロパティの説明については、[getIX()](../../com.aspose.diagram/control\#getIX--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


このプロパティの説明については、[getName()](../../com.aspose.diagram/control\#getName--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


このプロパティの説明については、[getNameU()](../../com.aspose.diagram/control\#getNameU--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPrompt(Str2Value value) {#setPrompt-com.aspose.diagram.Str2Value-}
```
public void setPrompt(Str2Value value)
```


このプロパティの説明については、[getPrompt()](../../com.aspose.diagram/control\#getPrompt--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


このプロパティの説明については、[getX()](../../com.aspose.diagram/control\#getX--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setXCon(ConType value) {#setXCon-com.aspose.diagram.ConType-}
```
public void setXCon(ConType value)
```


このプロパティの説明については、[getXCon()](../../com.aspose.diagram/control\#getXCon--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setXDyn(DoubleValue value) {#setXDyn-com.aspose.diagram.DoubleValue-}
```
public void setXDyn(DoubleValue value)
```


このプロパティの説明については、[getXDyn()](../../com.aspose.diagram/control\#getXDyn--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


このプロパティの説明については、[getY()](../../com.aspose.diagram/control\#getY--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setYCon(ConType value) {#setYCon-com.aspose.diagram.ConType-}
```
public void setYCon(ConType value)
```


このプロパティの説明については、[getYCon()](../../com.aspose.diagram/control\#getYCon--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setYDyn(DoubleValue value) {#setYDyn-com.aspose.diagram.DoubleValue-}
```
public void setYDyn(DoubleValue value)
```


このプロパティの説明については、[getYDyn()](../../com.aspose.diagram/control\#getYDyn--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

