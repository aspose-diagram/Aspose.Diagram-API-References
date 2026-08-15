---
title: TextBlock
second_title: Aspose.Diagram for Java API リファレンス
description: シェイプのテキストブロック内のテキストの配置余白とデフォルトタブ位置を指定する要素を含みます。
type: docs
weight: 400
url: /ja/java/com.aspose.diagram/textblock/
---

**Inheritance:**
java.lang.Object
```
public class TextBlock
```

シェイプのテキスト ブロック内のテキストの配置、余白、デフォルトのタブ位置を指定する要素を含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | テキストブロックの下端と含まれる最後のテキスト行との距離を決定します。 |
| [getClass()](#getClass--) |  |
| [getDefaultTabStop()](#getDefaultTabStop--) | テキストブロック内のデフォルトタブストップの間隔を指定します。 |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getLeftMargin()](#getLeftMargin--) | テキストブロックの左端と含まれるテキストとの距離を指定します。 |
| [getRightMargin()](#getRightMargin--) | テキストブロックの右端と含まれるテキストとの距離を指定します。 |
| [getTextBkgnd()](#getTextBkgnd--) | シェイプのテキスト背景色を指定します。 |
| [getTextBkgndTrans()](#getTextBkgndTrans--) | シェイプのテキストブロックの背景色の透明度レベルを、0（完全に不透明）から1（完全に透明）まで指定します。 |
| [getTextDirection()](#getTextDirection--) | テキスト ブロック内の文字の方向を指定します。 |
| [getTopMargin()](#getTopMargin--) | テキストブロックの上端と含まれる最初のテキスト行との距離を指定します。 |
| [getVerticalAlign()](#getVerticalAlign--) | テキストブロック内のテキストの垂直配置を指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBottomMargin(DoubleValue value)](#setBottomMargin-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--) を参照してください。 |
| [setDefaultTabStop(DoubleValue value)](#setDefaultTabStop-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--) を参照してください。 |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/textblock\#getDel--) を参照してください。 |
| [setLeftMargin(DoubleValue value)](#setLeftMargin-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--) を参照してください。 |
| [setRightMargin(DoubleValue value)](#setRightMargin-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--) を参照してください。 |
| [setTextBkgnd(ColorValue value)](#setTextBkgnd-com.aspose.diagram.ColorValue-) | このプロパティの説明については、[getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--) を参照してください。 |
| [setTextBkgndTrans(DoubleValue value)](#setTextBkgndTrans-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--) を参照してください。 |
| [setTextDirection(TextDirection value)](#setTextDirection-com.aspose.diagram.TextDirection-) | このプロパティの説明については、[getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--) を参照してください。 |
| [setTopMargin(DoubleValue value)](#setTopMargin-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--) を参照してください。 |
| [setVerticalAlign(VerticalAlign value)](#setVerticalAlign-com.aspose.diagram.VerticalAlign-) | このプロパティの説明については、[getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--) を参照してください。 |
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
### getBottomMargin() {#getBottomMargin--}
```
public DoubleValue getBottomMargin()
```


テキストブロックの下端と含まれる最後のテキスト行との間の距離を決定します。デフォルトは 4 pt です。この値は図のスケールに依存しません。図が拡大縮小されても、下余白は同じままです。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultTabStop() {#getDefaultTabStop--}
```
public DoubleValue getDefaultTabStop()
```


テキストブロック内のデフォルトタブストップの間隔を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getLeftMargin() {#getLeftMargin--}
```
public DoubleValue getLeftMargin()
```


テキストブロックの左端と含まれるテキストとの間の距離を指定します。この値は図のスケールに依存しません。図が拡大縮小されても、左余白は同じままです。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRightMargin() {#getRightMargin--}
```
public DoubleValue getRightMargin()
```


テキストブロックの右端と含まれるテキストとの間の距離を指定します。この値は図のスケールに依存しません。図が拡大縮小されても、右余白は同じままです。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextBkgnd() {#getTextBkgnd--}
```
public ColorValue getTextBkgnd()
```


シェイプのテキスト背景色を指定します。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getTextBkgndTrans() {#getTextBkgndTrans--}
```
public DoubleValue getTextBkgndTrans()
```


シェイプのテキストブロックの背景色の透明度レベルを、0（完全に不透明）から1（完全に透明）まで指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextDirection() {#getTextDirection--}
```
public TextDirection getTextDirection()
```


テキスト ブロック内の文字の方向を指定します。

**Returns:**
[TextDirection](../../com.aspose.diagram/textdirection)
### getTopMargin() {#getTopMargin--}
```
public DoubleValue getTopMargin()
```


テキストブロックの上端と含まれる最初のテキスト行との距離を指定します。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getVerticalAlign() {#getVerticalAlign--}
```
public VerticalAlign getVerticalAlign()
```


テキストブロック内のテキストの垂直配置を指定します。

**Returns:**
[VerticalAlign](../../com.aspose.diagram/verticalalign)
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




### setBottomMargin(DoubleValue value) {#setBottomMargin-com.aspose.diagram.DoubleValue-}
```
public void setBottomMargin(DoubleValue value)
```


このプロパティの説明については、[getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDefaultTabStop(DoubleValue value) {#setDefaultTabStop-com.aspose.diagram.DoubleValue-}
```
public void setDefaultTabStop(DoubleValue value)
```


このプロパティの説明については、[getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel()](../../com.aspose.diagram/textblock\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setLeftMargin(DoubleValue value) {#setLeftMargin-com.aspose.diagram.DoubleValue-}
```
public void setLeftMargin(DoubleValue value)
```


このプロパティの説明については、[getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRightMargin(DoubleValue value) {#setRightMargin-com.aspose.diagram.DoubleValue-}
```
public void setRightMargin(DoubleValue value)
```


このプロパティの説明については、[getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextBkgnd(ColorValue value) {#setTextBkgnd-com.aspose.diagram.ColorValue-}
```
public void setTextBkgnd(ColorValue value)
```


このプロパティの説明については、[getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setTextBkgndTrans(DoubleValue value) {#setTextBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setTextBkgndTrans(DoubleValue value)
```


このプロパティの説明については、[getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextDirection(TextDirection value) {#setTextDirection-com.aspose.diagram.TextDirection-}
```
public void setTextDirection(TextDirection value)
```


このプロパティの説明については、[getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TextDirection](../../com.aspose.diagram/textdirection) |  |

### setTopMargin(DoubleValue value) {#setTopMargin-com.aspose.diagram.DoubleValue-}
```
public void setTopMargin(DoubleValue value)
```


このプロパティの説明については、[getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setVerticalAlign(VerticalAlign value) {#setVerticalAlign-com.aspose.diagram.VerticalAlign-}
```
public void setVerticalAlign(VerticalAlign value)
```


このプロパティの説明については、[getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [VerticalAlign](../../com.aspose.diagram/verticalalign) |  |

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

