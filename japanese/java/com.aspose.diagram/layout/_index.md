---
title: レイアウト
second_title: Aspose.Diagram for Java API リファレンス
description: シェイプの配置とコネクタのルーティング設定を制御する要素を含みます。
type: docs
weight: 215
url: /ja/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

シェイプの配置とコネクタのルーティング設定を制御する要素を含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | コネクタが再ルーティングするタイミングを決定します。 |
| [getConLineJumpCode()](#getConLineJumpCode--) | 2つのコネクタが交差したときにコネクタがジャンプするかどうかを決定します、 |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | 動的コネクタの水平セグメントで発生するラインジャンプの方向を決定します。 |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | 動的コネクタの垂直セグメントで発生するラインジャンプの方向を決定します。 |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | 動的コネクタ上のラインジャンプのスタイルを決定します。 |
| [getConLineRouteExt()](#getConLineRouteExt--) | コネクタの外観を決定します。 |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getDisplayLevel()](#getDisplayLevel--) | シェイプの表示レベルバンド（Z オーダー グループ化の相対範囲）を決定します。 |
| [getRelationships()](#getRelationships--) | コンテナ、リスト、コールアウト、およびシェイプ間の関係を保存します。 |
| [getShapeFixedCode()](#getShapeFixedCode--) | 配置可能なシェイプの配置動作を指定します。 |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | ユーザーが [Lay Out Shapes]（Shapes メニュー）を選択したときに、配置可能なシェイプを別のシェイプの上に配置できるかどうかを指定します。 |
| [getShapePermeableX()](#getShapePermeableX--) | コネクタがシェイプを横方向に通過できるかどうかを指定します。 |
| [getShapePermeableY()](#getShapePermeableY--) | コネクタがシェイプを縦方向に通過できるかどうかを指定します。 |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | ユーザーが「Lay Out Shapes」（シェイプ メニュー）を選択したときに、配置可能なシェイプがページ上で反転または回転する方法を指定します。 |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | 子要素の配置スタイルを決定します。 |
| [getShapePlowCode()](#getShapePlowCode--) | 描画ページ上で別の配置可能なシェイプを対象シェイプの近くにドラッグしたときに、対象シェイプが離れるかどうかを指定します。 |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | 描画ページ上のコネクタのルーティング スタイルと方向を指定します。 |
| [getShapeSplit()](#getShapeSplit--) | このシェイプが分割可能なシェイプを分割できるかどうかを決定します。 |
| [getShapeSplittable()](#getShapeSplittable--) | この 1 次元シェイプが分割できるかどうかを決定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/layout\#getDel--) を参照してください |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | このプロパティの説明については、[getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) を参照してください |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


コネクタが再ルーティングするタイミングを決定します。

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


2つのコネクタが交差したときにコネクタがジャンプするかどうかを決定します、

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


動的コネクタの水平セグメントで発生するラインジャンプの方向を決定します。

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


動的コネクタの垂直セグメントで発生するラインジャンプの方向を決定します。

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


動的コネクタ上のラインジャンプのスタイルを決定します。

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


コネクタの外観を決定します。

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


シェイプの表示レベルバンド（Z オーダー グループ化の相対範囲）を決定します。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


コンテナ、リスト、コールアウト、およびシェイプ間の関係を保存します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


配置可能なシェイプの配置動作を指定します。

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


ユーザーが [Lay Out Shapes]（Shapes メニュー）を選択したときに、配置可能なシェイプを別のシェイプの上に配置できるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


コネクタがシェイプを横方向に通過できるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


コネクタがシェイプを縦方向に通過できるかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


ユーザーが「Lay Out Shapes」（シェイプ メニュー）を選択したときに、配置可能なシェイプがページ上で反転または回転する方法を指定します。

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


子要素の配置スタイルを決定します。

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


描画ページ上で別の配置可能なシェイプを対象シェイプの近くにドラッグしたときに、対象シェイプが離れるかどうかを指定します。

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


描画ページ上のコネクタのルーティング スタイルと方向を指定します。

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


このシェイプが分割可能なシェイプを分割できるかどうかを決定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


この 1 次元シェイプが分割できるかどうかを決定します。

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


このプロパティの説明については、[getDel()](../../com.aspose.diagram/layout\#getDel--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


このプロパティの説明については、[getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle) |  |

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

