---
title: PageLayout
second_title: Aspose.Diagram for Java API リファレンス
description: ページ上の図形やコネクタのレイアウト設定を制御するセルを含みます。例えば、ページ上のすべての図形間の間隔、すべてのコネクタ間の間隔、すべてのコネクタのルーティングスタイルなどです。
type: docs
weight: 263
url: /ja/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

ページ上の図形やコネクタのレイアウト設定を制御するセルを含みます。例えば、ページ上のすべての図形間の間隔、すべてのコネクタ間の間隔、そしてすべてのコネクタのルーティングスタイルなどです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | Microsoft Visioで図面ページ上の図形を配置する際の、図形間の垂直方向のスペース量を決定します。 |
| [getAvenueSizeY()](#getAvenueSizeY--) | Microsoft Visioで図面ページ上の図形を配置する際の、図形間の垂直方向のスペース量を決定します。 |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | ユーザーが「図形の配置」（図形メニュー）を選択して図形を配置する際、図形がページ上に配置される方法を指定します。 |
| [getBlockSizeX()](#getBlockSizeX--) | Microsoft Visioで図面ページ上の図形を配置する際に、各図形が収まる必要がある垂直方向のブロックサイズ（領域）を決定します。 |
| [getBlockSizeY()](#getBlockSizeY--) | Microsoft Visioで図面ページ上の図形を配置する際の、図形間の水平方向のスペース量を決定します。 |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | コントロールハンドルで図形を使用する場合、どの図形が親になるかを決定します。 |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getDynamicsOff()](#getDynamicsOff--) | 配置可能な図形が移動し、コネクタが図面ページ上の他の図形やコネクタの周りを再ルーティングするかどうかを指定します。 |
| [getEnableGrid()](#getEnableGrid--) | ユーザーが「図形の配置」（Shape メニュー）を選択したとき、Microsoft Visio が内部ページグリッドに基づいて図形を配置するかどうかを指定します。 |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | 動的コネクタが互いに重なる場合に、どのコネクタを間隔を空けるかを指定します。 |
| [getLineAdjustTo()](#getLineAdjustTo--) | 動的コネクタが互いに重なる場合に、どのコネクタを重ねて配置するかを指定します。 |
| [getLineJumpCode()](#getLineJumpCode--) | ローカルのラインジャンプスタイルが設定されていない描画ページ上のすべてのコネクタのラインジャンプスタイルを指定します。 |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | ページ上の動的コネクタの水平セグメントにおけるラインジャンプのサイズを、LineToLineX 要素の値（ページ上のすべてのコネクタ間の水平間隔を指定）に対するパーセンテージで指定します。 |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | ページ上の動的コネクタの垂直セグメントにおけるラインジャンプのサイズを、LineToLineY 要素の値（ページ上のすべてのコネクタ間の垂直間隔を指定）に対するパーセンテージで指定します。 |
| [getLineJumpStyle()](#getLineJumpStyle--) | 描画ページ上の動的コネクタの水平セグメントにおいて、ローカルなジャンプ方向が設定されていない場合のラインジャンプの方向を指定します。 |
| [getLineRouteExt()](#getLineRouteExt--) | ページ上のすべてのコネクタのデフォルト外観を指定します。 |
| [getLineToLineX()](#getLineToLineX--) | 図面ページ上の動的コネクタ間の最小水平間隔を指定します。 |
| [getLineToLineY()](#getLineToLineY--) | 図面ページ上の動的コネクタ間の最小垂直間隔を指定します。 |
| [getLineToNodeX()](#getLineToNodeX--) | 図面ページ上の動的コネクタと図形間の最小垂直間隔を指定します。 |
| [getLineToNodeY()](#getLineToNodeY--) | Microsoft Visioで図面ページ上の図形を配置する際に、各図形が収まる必要がある水平方向のブロックサイズ（領域）を決定します。 |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | 描画ページ上の垂直動的コネクタにおいて、ローカルなジャンプ方向が設定されていない場合のラインジャンプの方向を指定します。 |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | 図面ページ上の動的コネクタと図形間の最小水平間隔を指定します。 |
| [getPageShapeSplit()](#getPageShapeSplit--) | ページ上の図形が自動的に分割できるかどうかを示します。 |
| [getPlaceDepth()](#getPlaceDepth--) | ユーザーが配置可能な図形を別の配置可能な図形の近くへドラッグしたとき、配置可能な図形が離れるかどうかを指定します。 |
| [getPlaceFlip()](#getPlaceFlip--) | Microsoft Visio の「図形の配置」コマンドを使用して図形を配置する際、ページ上の配置可能な図形が反転または回転する方法を指定します。 |
| [getPlaceStyle()](#getPlaceStyle--) | ローカルのルーティングスタイルが設定されていない描画ページ上のすべての動的コネクタのルーティングスタイルと方向を指定します。 |
| [getPlowCode()](#getPlowCode--) | ジャンプを追加したい動的コネクタを決定します。 |
| [getResizePage()](#getResizePage--) | ユーザーが「図形の配置」（Shapes メニュー）を選択した後、図面を囲むようにページを拡大するかどうかを指定します。 |
| [getRouteStyle()](#getRouteStyle--) | 自動的にレイアウトされる図面について、レイアウト作成前に図面を解析する方法とレイアウトのタイプを決定する方法を指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/pagelayout\#getDel--) を参照してください。 |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


Microsoft Visioで図面ページ上の図形を配置する際の、図形間の垂直方向のスペース量を決定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


Microsoft Visioで図面ページ上の図形を配置する際の、図形間の垂直方向のスペース量を決定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


ユーザーが「図形の配置」（図形メニュー）を選択して図形を配置する際、図形がページ上に配置される方法を指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


Microsoft Visioで図面ページ上の図形を配置する際に、各図形が収まる必要がある垂直方向のブロックサイズ（領域）を決定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


Microsoft Visioで図面ページ上の図形を配置する際の、図形間の水平方向のスペース量を決定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


コントロールハンドルで図形を使用する場合、どの図形が親になるかを決定します。この要素は図面ページ上のすべての図形の動作を設定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


配置可能な図形が移動し、コネクタが図面ページ上の他の図形やコネクタの周りを再ルーティングするかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


ユーザーが「図形の配置」（Shape メニュー）を選択したとき、Microsoft Visio が内部ページグリッドに基づいて図形を配置するかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


動的コネクタが互いに重なる場合に、どのコネクタを間隔を空けるかを指定します。

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


動的コネクタが互いに重なる場合に、どのコネクタを重ねて配置するかを指定します。

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


ローカルのラインジャンプスタイルが設定されていない描画ページ上のすべてのコネクタのラインジャンプスタイルを指定します。

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


ページ上の動的コネクタの水平セグメントにおけるラインジャンプのサイズを、LineToLineX 要素の値（ページ上のすべてのコネクタ間の水平間隔を指定）に対するパーセンテージで指定します。この要素の値は 0 から 10 の範囲です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


ページ上の動的コネクタの垂直セグメントにおけるラインジャンプのサイズを、LineToLineY 要素の値（ページ上のすべてのコネクタ間の垂直間隔を指定）に対するパーセンテージで指定します。この要素は 0 から 10 の値を含めることができます。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


描画ページ上の動的コネクタの水平セグメントにおいて、ローカルなジャンプ方向が設定されていない場合のラインジャンプの方向を指定します。

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


ページ上のすべてのコネクタのデフォルト外観を指定します。

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


図面ページ上の動的コネクタ間の最小水平間隔を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


図面ページ上の動的コネクタ間の最小垂直間隔を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


図面ページ上の動的コネクタと図形間の最小垂直間隔を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


Microsoft Visioで図面ページ上の図形を配置する際に、各図形が収まる必要がある水平方向のブロックサイズ（領域）を決定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


描画ページ上の垂直動的コネクタにおいて、ローカルなジャンプ方向が設定されていない場合のラインジャンプの方向を指定します。

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


図面ページ上の動的コネクタと図形間の最小水平間隔を指定します。

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


ページ上の図形が自動的に分割できるかどうかを示します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


ユーザーが配置可能な図形を別の配置可能な図形の近くへドラッグしたとき、配置可能な図形が離れるかどうかを指定します。

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


Microsoft Visio の「Lay Out Shapes」コマンドを使用してシェイプを配置する際に、ページ上で配置可能なシェイプがどのように反転または回転するかを指定します。以下の十六進値が使用可能です。

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


ローカルのルーティングスタイルが設定されていない描画ページ上のすべての動的コネクタのルーティングスタイルと方向を指定します。

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


ジャンプを追加したい動的コネクタを決定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


ユーザーが「図形の配置」（Shapes メニュー）を選択した後、図面を囲むようにページを拡大するかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


自動的にレイアウトされる図面について、レイアウト作成前に図面を解析する方法とレイアウトのタイプを決定する方法を指定します。

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


このプロパティの説明については、[getDel()](../../com.aspose.diagram/pagelayout\#getDel--) を参照してください。

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

