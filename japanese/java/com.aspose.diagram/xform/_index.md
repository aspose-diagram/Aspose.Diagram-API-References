---
title: XForm
second_title: Aspose.Diagram for Java API リファレンス
description: パターンの太さや色など、シェイプの線属性を制御する要素を含みます。
type: docs
weight: 449
url: /ja/java/com.aspose.diagram/xform/
---

**Inheritance:**
java.lang.Object
```
public class XForm
```

シェイプの線属性（パターン、太さ、色など）を制御する要素が含まれます。これらの要素は、線端が書式設定されているか（例: 矢じり）、線端書式のサイズ、線に適用される丸みの円の半径、そして線のキャップスタイル（丸形または四角形）を決定します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | シェイプの親に対する現在の回転角度を表します。 |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getFlipX()](#getFlipX--) | シェイプが水平方向に反転されているかどうかを示します |
| [getFlipY()](#getFlipY--) | シェイプが垂直方向に反転されているかどうかを示します。 |
| [getHeight()](#getHeight--) | シェイプの高さを描画単位で指定します。 |
| [getLocPinX()](#getLocPinX--) | シェイプの原点に対するシェイプのピン（回転中心）の x 座標を指定します。 |
| [getLocPinY()](#getLocPinY--) | シェイプの原点に対するシェイプのピン（回転中心）の y 座標を指定します。 |
| [getPinPos()](#getPinPos--) | シェイプのピン位置を指定します |
| [getPinX()](#getPinX--) | 親の原点に対するシェイプのピン（回転中心）の x 座標を指定します。 |
| [getPinY()](#getPinY--) | 親の原点に対するシェイプのピン（回転中心）の y 座標を指定します。 |
| [getResizeMode()](#getResizeMode--) | グループ内に含まれる形状の現在のリサイズ動作設定を指定します。 |
| [getWidth()](#getWidth--) | 関連するシェイプの幅を描画単位で含みます。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(DoubleValue value)](#setAngle-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getAngle()](../../com.aspose.diagram/xform\#getAngle--) を参照してください |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/xform\#getDel--) を参照してください |
| [setFlipX(BoolValue value)](#setFlipX-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getFlipX()](../../com.aspose.diagram/xform\#getFlipX--) を参照してください |
| [setFlipY(BoolValue value)](#setFlipY-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getFlipY()](../../com.aspose.diagram/xform\#getFlipY--) を参照してください |
| [setHeight(DoubleValue value)](#setHeight-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getHeight()](../../com.aspose.diagram/xform\#getHeight--) を参照してください |
| [setLocPinX(DoubleValue value)](#setLocPinX-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--) を参照してください |
| [setLocPinY(DoubleValue value)](#setLocPinY-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--) を参照してください |
| [setPinPos(int value)](#setPinPos-int-) | このプロパティの説明については、[getPinPos()](../../com.aspose.diagram/xform\#getPinPos--) を参照してください |
| [setPinX(DoubleValue value)](#setPinX-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getPinX()](../../com.aspose.diagram/xform\#getPinX--) を参照してください |
| [setPinY(DoubleValue value)](#setPinY-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getPinY()](../../com.aspose.diagram/xform\#getPinY--) を参照してください |
| [setResizeMode(ResizeMode value)](#setResizeMode-com.aspose.diagram.ResizeMode-) | このプロパティの説明については、[getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--) を参照してください |
| [setWidth(DoubleValue value)](#setWidth-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getWidth()](../../com.aspose.diagram/xform\#getWidth--) を参照してください |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAngle() {#getAngle--}
```
public DoubleValue getAngle()
```


シェイプの親に対する現在の回転角度を表します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getFlipX() {#getFlipX--}
```
public BoolValue getFlipX()
```


シェイプが水平方向に反転されているかどうかを示します

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlipY() {#getFlipY--}
```
public BoolValue getFlipY()
```


シェイプが垂直方向に反転されているかどうかを示します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHeight() {#getHeight--}
```
public DoubleValue getHeight()
```


シェイプの高さを描画単位で指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinX() {#getLocPinX--}
```
public DoubleValue getLocPinX()
```


シェイプの原点に対するシェイプのピン（回転中心）の x 座標を指定します。LocPinX を決定するデフォルトの式は次のとおりです: F='Width\* 0.5'。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinY() {#getLocPinY--}
```
public DoubleValue getLocPinY()
```


シェイプの原点に対するシェイプのピン（回転中心）の y 座標を指定します。LocPinY を決定するデフォルトの式は次のとおりです: F='Height \* 0.5'。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinPos() {#getPinPos--}
```
public int getPinPos()
```


シェイプのピン位置を指定します

**Returns:**
int
### getPinX() {#getPinX--}
```
public DoubleValue getPinX()
```


親の原点に対するシェイプのピン（回転中心）の x 座標を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinY() {#getPinY--}
```
public DoubleValue getPinY()
```


親の原点に対するシェイプのピン（回転中心）の y 座標を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getResizeMode() {#getResizeMode--}
```
public ResizeMode getResizeMode()
```


グループ内に含まれる形状の現在のリサイズ動作設定を指定します。

**Returns:**
[ResizeMode](../../com.aspose.diagram/resizemode)
### getWidth() {#getWidth--}
```
public DoubleValue getWidth()
```


関連するシェイプの幅を描画単位で含みます。

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




### setAngle(DoubleValue value) {#setAngle-com.aspose.diagram.DoubleValue-}
```
public void setAngle(DoubleValue value)
```


このプロパティの説明については、[getAngle()](../../com.aspose.diagram/xform\#getAngle--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel()](../../com.aspose.diagram/xform\#getDel--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setFlipX(BoolValue value) {#setFlipX-com.aspose.diagram.BoolValue-}
```
public void setFlipX(BoolValue value)
```


このプロパティの説明については、[getFlipX()](../../com.aspose.diagram/xform\#getFlipX--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFlipY(BoolValue value) {#setFlipY-com.aspose.diagram.BoolValue-}
```
public void setFlipY(BoolValue value)
```


このプロパティの説明については、[getFlipY()](../../com.aspose.diagram/xform\#getFlipY--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHeight(DoubleValue value) {#setHeight-com.aspose.diagram.DoubleValue-}
```
public void setHeight(DoubleValue value)
```


このプロパティの説明については、[getHeight()](../../com.aspose.diagram/xform\#getHeight--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinX(DoubleValue value) {#setLocPinX-com.aspose.diagram.DoubleValue-}
```
public void setLocPinX(DoubleValue value)
```


このプロパティの説明については、[getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinY(DoubleValue value) {#setLocPinY-com.aspose.diagram.DoubleValue-}
```
public void setLocPinY(DoubleValue value)
```


このプロパティの説明については、[getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinPos(int value) {#setPinPos-int-}
```
public void setPinPos(int value)
```


このプロパティの説明については、[getPinPos()](../../com.aspose.diagram/xform\#getPinPos--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPinX(DoubleValue value) {#setPinX-com.aspose.diagram.DoubleValue-}
```
public void setPinX(DoubleValue value)
```


このプロパティの説明については、[getPinX()](../../com.aspose.diagram/xform\#getPinX--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinY(DoubleValue value) {#setPinY-com.aspose.diagram.DoubleValue-}
```
public void setPinY(DoubleValue value)
```


このプロパティの説明については、[getPinY()](../../com.aspose.diagram/xform\#getPinY--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setResizeMode(ResizeMode value) {#setResizeMode-com.aspose.diagram.ResizeMode-}
```
public void setResizeMode(ResizeMode value)
```


このプロパティの説明については、[getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ResizeMode](../../com.aspose.diagram/resizemode) |  |

### setWidth(DoubleValue value) {#setWidth-com.aspose.diagram.DoubleValue-}
```
public void setWidth(DoubleValue value)
```


このプロパティの説明については、[getWidth()](../../com.aspose.diagram/xform\#getWidth--) を参照してください

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

