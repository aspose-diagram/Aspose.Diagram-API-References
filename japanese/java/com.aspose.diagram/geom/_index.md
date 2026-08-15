---
title: Geom
second_title: Aspose.Diagram for Java API リファレンス
description: シェイプを構成する線と円弧の頂点座標を指定する要素を含みます。
type: docs
weight: 169
url: /ja/java/com.aspose.diagram/geom/
---

**Inheritance:**
java.lang.Object
```
public class Geom
```

形状を構成する線や弧の頂点座標を指定する要素を含みます。形状に複数のパスがある場合、各パスに対して Geom 要素が存在します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Geom()](#Geom--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateCol()](#getCoordinateCol--) | 座標のコレクションです。 |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getIX()](#getIX--) | 親要素内の要素のゼロベースインデックスです。 |
| [getNextCoordinateIX()](#getNextCoordinateIX--) | 次のシェイプの座標コレクションメンバーの IX 値を返します。 |
| [getNoFill()](#getNoFill--) | パスを塗りつぶすかどうかを指定します。 |
| [getNoLine()](#getNoLine--) | パスの境界線の周囲に線を描画するかどうかを指定します。 |
| [getNoQuickDrag()](#getNoQuickDrag--) | ユーザーが Geometry セクションで定義された塗りつぶし領域をクリックしたときに、シェイプを選択またはドラッグできるかどうかを決定します。 |
| [getNoShow()](#getNoShow--) | パスが描画ページに表示されるかどうかを指定します。 |
| [getNoSnap()](#getNoSnap--) | 他のシェイプがパスにスナップするかどうかを指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/geom\#getDel--) を参照してください。 |
| [setIX(int value)](#setIX-int-) | このプロパティの説明については、[getIX()](../../com.aspose.diagram/geom\#getIX--) を参照してください。 |
| [setNoFill(BoolValue value)](#setNoFill-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getNoFill()](../../com.aspose.diagram/geom\#getNoFill--) を参照してください。 |
| [setNoLine(BoolValue value)](#setNoLine-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getNoLine()](../../com.aspose.diagram/geom\#getNoLine--) を参照してください。 |
| [setNoQuickDrag(BoolValue value)](#setNoQuickDrag-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--) を参照してください。 |
| [setNoShow(BoolValue value)](#setNoShow-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getNoShow()](../../com.aspose.diagram/geom\#getNoShow--) を参照してください。 |
| [setNoSnap(BoolValue value)](#setNoSnap-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geom() {#Geom--}
```
public Geom()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateCol() {#getCoordinateCol--}
```
public CoordinateCollection getCoordinateCol()
```


座標のコレクションです。座標のシーケンスを示します。

**Returns:**
[CoordinateCollection](../../com.aspose.diagram/coordinatecollection)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


親要素内の要素のゼロベースインデックスです。

**Returns:**
int
### getNextCoordinateIX() {#getNextCoordinateIX--}
```
public int getNextCoordinateIX()
```


次のシェイプの座標コレクションメンバーの IX 値を返します。

**Returns:**
int
### getNoFill() {#getNoFill--}
```
public BoolValue getNoFill()
```


パスを塗りつぶすかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLine() {#getNoLine--}
```
public BoolValue getNoLine()
```


パスの境界線の周囲に線を描画するかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoQuickDrag() {#getNoQuickDrag--}
```
public BoolValue getNoQuickDrag()
```


ユーザーが Geometry セクションで定義された塗りつぶし領域をクリックしたときに、シェイプを選択またはドラッグできるかどうかを決定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoShow() {#getNoShow--}
```
public BoolValue getNoShow()
```


パスが描画ページに表示されるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoSnap() {#getNoSnap--}
```
public BoolValue getNoSnap()
```


他のシェイプがパスにスナップするかどうかを指定します。

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


このプロパティの説明については、[getDel()](../../com.aspose.diagram/geom\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


このプロパティの説明については、[getIX()](../../com.aspose.diagram/geom\#getIX--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setNoFill(BoolValue value) {#setNoFill-com.aspose.diagram.BoolValue-}
```
public void setNoFill(BoolValue value)
```


このプロパティの説明については、[getNoFill()](../../com.aspose.diagram/geom\#getNoFill--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoLine(BoolValue value) {#setNoLine-com.aspose.diagram.BoolValue-}
```
public void setNoLine(BoolValue value)
```


このプロパティの説明については、[getNoLine()](../../com.aspose.diagram/geom\#getNoLine--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoQuickDrag(BoolValue value) {#setNoQuickDrag-com.aspose.diagram.BoolValue-}
```
public void setNoQuickDrag(BoolValue value)
```


このプロパティの説明については、[getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoShow(BoolValue value) {#setNoShow-com.aspose.diagram.BoolValue-}
```
public void setNoShow(BoolValue value)
```


このプロパティの説明については、[getNoShow()](../../com.aspose.diagram/geom\#getNoShow--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoSnap(BoolValue value) {#setNoSnap-com.aspose.diagram.BoolValue-}
```
public void setNoSnap(BoolValue value)
```


このプロパティの説明については、[getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

