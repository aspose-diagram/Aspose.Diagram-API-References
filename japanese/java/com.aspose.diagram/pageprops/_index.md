---
title: PageProps
second_title: Aspose.Diagram for Java API リファレンス
description: ページ幅、ページ高さ、スケールなどのページ属性を制御するセルを含みます。
type: docs
weight: 268
url: /ja/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

ページ幅、ページ高さ、スケールなど、ページ属性を制御するセルを含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getDrawingResizeType()](#getDrawingResizeType--) | 図に合わせて描画ページが自動的にサイズ変更されるかどうかを決定します。 |
| [getDrawingScale()](#getDrawingScale--) | 現在の描画スケールにおける描画単位の値を表します。 |
| [getDrawingScaleType()](#getDrawingScaleType--) | ページに使用する描画スケールのタイプを指定します。 |
| [getDrawingSizeType()](#getDrawingSizeType--) | ページの描画サイズを指定します。 |
| [getInhibitSnap()](#getInhibitSnap--) | 前景ページ上のシェイプがページ上の他のオブジェクトや背景ページ上のシェイプにスナップするかどうかを指定します。 |
| [getPageHeight()](#getPageHeight--) | ページの高さを描画単位で指定します。 |
| [getPageScale()](#getPageScale--) | 現在の描画スケールにおけるデフォルトページ単位の値を指定します。 |
| [getPageWidth()](#getPageWidth--) | ページの幅を描画単位で指定します。 |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | デフォルトのページ影タイプが適用される際の斜め方向の角度を指定する数値を含みます。 |
| [getShdwOffsetX()](#getShdwOffsetX--) | シェイプのドロップシャドウがシェイプから水平方向にオフセットされる距離（ページ単位）を指定します。 |
| [getShdwOffsetY()](#getShdwOffsetY--) | シェイプのドロップシャドウがシェイプから垂直方向にオフセットされる距離（ページ単位）を指定します。 |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | シェイプのシャドウを拡大または縮小する割合を指定します。 |
| [getShdwType()](#getShdwType--) | ページのデフォルトの影タイプを示します。 |
| [getUIVisibility()](#getUIVisibility--) | ページ名がユーザーインターフェイス (UI) に表示されるかどうかを決定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/pageprops\#getDel--) を参照してください。 |
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
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


図に合わせて描画ページが自動的にサイズ変更されるかどうかを決定します。

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


現在の描画スケールにおける描画単位の値を表します。ページの描画スケールは、PageScale 要素に含まれるページ単位と描画単位との比率です。この要素の単位は、ページのデフォルト長さ (DL) 単位を決定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


ページに使用する描画スケールのタイプを指定します。

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


ページの描画サイズを指定します。

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


前景ページ上のシェイプがページ上の他のオブジェクトや背景ページ上のシェイプにスナップするかどうかを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


ページの高さを描画単位で指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


現在の描画スケールにおけるデフォルトページ単位の値を指定します。ページの描画スケールは、PageScale 要素のページ単位と DrawingScale 要素に示された描画単位との比率です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


ページの幅を描画単位で指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


デフォルトのページ影タイプが適用される際の斜め方向の角度を指定する数値を含みます。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


シェイプのドロップシャドウがシェイプから水平方向にオフセットされる距離（ページ単位）を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


シェイプのドロップシャドウがシェイプから垂直方向にオフセットされる距離（ページ単位）を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


シェイプのシャドウを拡大または縮小する割合を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


ページのデフォルトの影タイプを示します。

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


ページ名がユーザーインターフェイス (UI) に表示されるかどうかを決定します。値が 1 の場合はページが非表示であることを示し、値が 0 の場合はページが表示されることを示します。

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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


このプロパティの説明については、[getDel()](../../com.aspose.diagram/pageprops\#getDel--) を参照してください。

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

