---
title: 塗りつぶし
second_title: Aspose.Diagram for Java API リファレンス
description: シェイプとシェイプのドロップシャドウの現在の塗りつぶし書式設定値を含み、パターンの前景色と背景色を含みます。
type: docs
weight: 153
url: /ja/java/com.aspose.diagram/fill/
---

**Inheritance:**
java.lang.Object
```
public class Fill
```

シェイプとシェイプのドロップシャドウの現在の塗りつぶし書式設定値を含み、パターン、前景色、背景色が含まれます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getFillBkgnd()](#getFillBkgnd--) | シェイプの塗りつぶしパターンの背景に使用される色を指定します。 |
| [getFillBkgndTrans()](#getFillBkgndTrans--) | シェイプの塗りつぶしパターンの背景（塗り）色の透明度レベルを指定します。0（完全に不透明）から1（完全に透明）までです。 |
| [getFillForegnd()](#getFillForegnd--) | シェイプの塗りつぶしパターンの前景（ストローク）に使用される色を指定します。 |
| [getFillForegndTrans()](#getFillForegndTrans--) | シェイプの塗りつぶしパターンの前景（塗り）色の透明度レベルを指定します。0（完全に不透明）から1（完全に透明）までです。 |
| [getFillPattern()](#getFillPattern--) | シェイプの塗りつぶしパターンを指定します。 |
| [getGradientFill()](#getGradientFill--) | シェイプの現在のグラデーション塗りつぶし書式設定値を含みます。 |
| [getShapeShdwBlur()](#getShapeShdwBlur--) | シェイプの影のぼかしサイズを指定します。 |
| [getShapeShdwObliqueAngle()](#getShapeShdwObliqueAngle--) | シェイプの影の斜め方向の角度を指定します。 |
| [getShapeShdwOffsetX()](#getShapeShdwOffsetX--) | シェイプの影がシェイプから水平方向にオフセットされる距離（ページ単位）を決定します。 |
| [getShapeShdwOffsetY()](#getShapeShdwOffsetY--) | シェイプの影がシェイプから垂直方向にオフセットされる距離（ページ単位）を決定します。 |
| [getShapeShdwScaleFactor()](#getShapeShdwScaleFactor--) | シェイプの影を拡大または縮小できる割合（パーセンテージ）を指定します。 |
| [getShapeShdwShow()](#getShapeShdwShow--) | シェイプの影のタイプを指定します。 |
| [getShapeShdwType()](#getShapeShdwType--) | シェイプの影のタイプを指定します。 |
| [getShdwBkgnd()](#getShdwBkgnd--) | シェイプのドロップシャドウ塗りつぶしパターンの背景（塗り）に使用される色を指定します。 |
| [getShdwBkgndTrans()](#getShdwBkgndTrans--) | シェイプのドロップシャドウ塗りつぶしパターンの背景（塗り）の透明度レベルを指定します。0.0（完全に不透明）から1.0（完全に透明）までです。 |
| [getShdwForegnd()](#getShdwForegnd--) | シェイプのドロップシャドウ塗りつぶしパターンの前景（ストローク）に使用される色を指定します。 |
| [getShdwForegndTrans()](#getShdwForegndTrans--) | シェイプのドロップシャドウ塗りつぶしパターンの前景（ストローク）の透明度レベルを指定します。0.0（完全に不透明）から1.0（完全に透明）までです。 |
| [getShdwPattern()](#getShdwPattern--) | シェイプの影の塗りつぶしパターンを指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/fill\#getDel--)をご覧ください。 |
| [setFillBkgnd(ColorValue value)](#setFillBkgnd-com.aspose.diagram.ColorValue-) | このプロパティの説明については、[getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)をご覧ください。 |
| [setFillBkgndTrans(DoubleValue value)](#setFillBkgndTrans-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)をご覧ください。 |
| [setFillForegnd(ColorValue value)](#setFillForegnd-com.aspose.diagram.ColorValue-) | このプロパティの説明については、[getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)をご覧ください。 |
| [setFillForegndTrans(DoubleValue value)](#setFillForegndTrans-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)をご覧ください。 |
| [setFillPattern(IntValue value)](#setFillPattern-com.aspose.diagram.IntValue-) | このプロパティの説明については、[getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)をご覧ください。 |
| [setShapeShdwBlur(DoubleValue value)](#setShapeShdwBlur-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)をご覧ください。 |
| [setShapeShdwObliqueAngle(DoubleValue value)](#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)をご覧ください。 |
| [setShapeShdwOffsetX(DoubleValue value)](#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--) をご覧ください。 |
| [setShapeShdwOffsetY(DoubleValue value)](#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--) をご覧ください。 |
| [setShapeShdwScaleFactor(DoubleValue value)](#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--) をご覧ください。 |
| [setShapeShdwShow(ShapeShdwShow value)](#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-) | このプロパティの説明については、[getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--) をご覧ください。 |
| [setShapeShdwType(ShapeShdwType value)](#setShapeShdwType-com.aspose.diagram.ShapeShdwType-) | このプロパティの説明については、[getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--) をご覧ください。 |
| [setShdwBkgnd(ColorValue value)](#setShdwBkgnd-com.aspose.diagram.ColorValue-) | このプロパティの説明については、[getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--) をご覧ください。 |
| [setShdwBkgndTrans(DoubleValue value)](#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--) をご覧ください。 |
| [setShdwForegnd(ColorValue value)](#setShdwForegnd-com.aspose.diagram.ColorValue-) | このプロパティの説明については、[getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--) をご覧ください。 |
| [setShdwForegndTrans(DoubleValue value)](#setShdwForegndTrans-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--) をご覧ください。 |
| [setShdwPattern(IntValue value)](#setShdwPattern-com.aspose.diagram.IntValue-) | このプロパティの説明については、[getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--) をご覧ください。 |
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
### getFillBkgnd() {#getFillBkgnd--}
```
public ColorValue getFillBkgnd()
```


シェイプの塗りつぶしパターンの背景に使用される色を指定します。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillBkgndTrans() {#getFillBkgndTrans--}
```
public DoubleValue getFillBkgndTrans()
```


シェイプの塗りつぶしパターンの背景（塗り）色の透明度レベルを指定します。0（完全に不透明）から1（完全に透明）までです。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillForegnd() {#getFillForegnd--}
```
public ColorValue getFillForegnd()
```


シェイプの塗りつぶしパターンの前景（ストローク）に使用される色を指定します。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillForegndTrans() {#getFillForegndTrans--}
```
public DoubleValue getFillForegndTrans()
```


シェイプの塗りつぶしパターンの前景（塗り）色の透明度レベルを指定します。0（完全に不透明）から1（完全に透明）までです。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillPattern() {#getFillPattern--}
```
public IntValue getFillPattern()
```


シェイプの塗りつぶしパターンを指定します。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getGradientFill() {#getGradientFill--}
```
public GradientFill getGradientFill()
```


シェイプの現在のグラデーション塗りつぶし書式設定値を含みます。

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getShapeShdwBlur() {#getShapeShdwBlur--}
```
public DoubleValue getShapeShdwBlur()
```


シェイプの影のぼかしサイズを指定します。現在はぼかしを描画できませんが、vsdx からは解析できます。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwObliqueAngle() {#getShapeShdwObliqueAngle--}
```
public DoubleValue getShapeShdwObliqueAngle()
```


シェイプの影の斜め方向の角度を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetX() {#getShapeShdwOffsetX--}
```
public DoubleValue getShapeShdwOffsetX()
```


シェイプの影がシェイプから水平方向にオフセットされる距離（ページ単位）を決定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetY() {#getShapeShdwOffsetY--}
```
public DoubleValue getShapeShdwOffsetY()
```


シェイプの影がシェイプから垂直方向にオフセットされる距離（ページ単位）を決定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwScaleFactor() {#getShapeShdwScaleFactor--}
```
public DoubleValue getShapeShdwScaleFactor()
```


シェイプの影を拡大または縮小できる割合（パーセンテージ）を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwShow() {#getShapeShdwShow--}
```
public ShapeShdwShow getShapeShdwShow()
```


シェイプの影のタイプを指定します。

**Returns:**
[ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow)
### getShapeShdwType() {#getShapeShdwType--}
```
public ShapeShdwType getShapeShdwType()
```


シェイプの影のタイプを指定します。

**Returns:**
[ShapeShdwType](../../com.aspose.diagram/shapeshdwtype)
### getShdwBkgnd() {#getShdwBkgnd--}
```
public ColorValue getShdwBkgnd()
```


シェイプのドロップシャドウ塗りつぶしパターンの背景（塗り）に使用される色を指定します。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwBkgndTrans() {#getShdwBkgndTrans--}
```
public DoubleValue getShdwBkgndTrans()
```


シェイプのドロップシャドウ塗りつぶしパターンの背景（塗り）の透明度レベルを指定します。0.0（完全に不透明）から1.0（完全に透明）までです。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwForegnd() {#getShdwForegnd--}
```
public ColorValue getShdwForegnd()
```


シェイプのドロップシャドウ塗りつぶしパターンの前景（ストローク）に使用される色を指定します。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwForegndTrans() {#getShdwForegndTrans--}
```
public DoubleValue getShdwForegndTrans()
```


シェイプのドロップシャドウ塗りつぶしパターンの前景（ストローク）の透明度レベルを指定します。0.0（完全に不透明）から1.0（完全に透明）までです。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwPattern() {#getShdwPattern--}
```
public IntValue getShdwPattern()
```


シェイプの影の塗りつぶしパターンを指定します。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


このプロパティの説明については、[getDel()](../../com.aspose.diagram/fill\#getDel--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setFillBkgnd(ColorValue value) {#setFillBkgnd-com.aspose.diagram.ColorValue-}
```
public void setFillBkgnd(ColorValue value)
```


このプロパティの説明については、[getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillBkgndTrans(DoubleValue value) {#setFillBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillBkgndTrans(DoubleValue value)
```


このプロパティの説明については、[getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillForegnd(ColorValue value) {#setFillForegnd-com.aspose.diagram.ColorValue-}
```
public void setFillForegnd(ColorValue value)
```


このプロパティの説明については、[getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillForegndTrans(DoubleValue value) {#setFillForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillForegndTrans(DoubleValue value)
```


このプロパティの説明については、[getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillPattern(IntValue value) {#setFillPattern-com.aspose.diagram.IntValue-}
```
public void setFillPattern(IntValue value)
```


このプロパティの説明については、[getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setShapeShdwBlur(DoubleValue value) {#setShapeShdwBlur-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwBlur(DoubleValue value)
```


このプロパティの説明については、[getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwObliqueAngle(DoubleValue value) {#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwObliqueAngle(DoubleValue value)
```


このプロパティの説明については、[getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetX(DoubleValue value) {#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetX(DoubleValue value)
```


このプロパティの説明については、[getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--) をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetY(DoubleValue value) {#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetY(DoubleValue value)
```


このプロパティの説明については、[getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--) をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwScaleFactor(DoubleValue value) {#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwScaleFactor(DoubleValue value)
```


このプロパティの説明については、[getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--) をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwShow(ShapeShdwShow value) {#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-}
```
public void setShapeShdwShow(ShapeShdwShow value)
```


このプロパティの説明については、[getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--) をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow) |  |

### setShapeShdwType(ShapeShdwType value) {#setShapeShdwType-com.aspose.diagram.ShapeShdwType-}
```
public void setShapeShdwType(ShapeShdwType value)
```


このプロパティの説明については、[getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--) をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ShapeShdwType](../../com.aspose.diagram/shapeshdwtype) |  |

### setShdwBkgnd(ColorValue value) {#setShdwBkgnd-com.aspose.diagram.ColorValue-}
```
public void setShdwBkgnd(ColorValue value)
```


このプロパティの説明については、[getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--) をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwBkgndTrans(DoubleValue value) {#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwBkgndTrans(DoubleValue value)
```


このプロパティの説明については、[getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--) をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwForegnd(ColorValue value) {#setShdwForegnd-com.aspose.diagram.ColorValue-}
```
public void setShdwForegnd(ColorValue value)
```


このプロパティの説明については、[getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--) をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwForegndTrans(DoubleValue value) {#setShdwForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwForegndTrans(DoubleValue value)
```


このプロパティの説明については、[getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--) をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwPattern(IntValue value) {#setShdwPattern-com.aspose.diagram.IntValue-}
```
public void setShdwPattern(IntValue value)
```


このプロパティの説明については、[getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--) をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

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

