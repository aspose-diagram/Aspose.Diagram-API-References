---
title: Line
second_title: Aspose.Diagram for Java API リファレンス
description: シェイプに関する一般的な位置情報を指定する要素を含みます。
type: docs
weight: 221
url: /ja/java/com.aspose.diagram/line/
---

**Inheritance:**
java.lang.Object
```
public class Line
```

シェイプに関する一般的な位置情報を指定する要素を含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginArrow()](#getBeginArrow--) | 線の最初の頂点に矢じりまたはその他の線端形式があるかどうかを示します。 |
| [getBeginArrowSize()](#getBeginArrowSize--) | 線の始点における矢じりのサイズを決定します。 |
| [getClass()](#getClass--) |  |
| [getCompoundType()](#getCompoundType--) | 図形の線のCompoundTypeを指定します。 |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getEndArrow()](#getEndArrow--) | 線の最後の頂点に矢じりまたはその他の線端形式があるかどうかを示します。 |
| [getEndArrowSize()](#getEndArrowSize--) | 線の終点における矢じりのサイズを指定します。 |
| [getGradientLine()](#getGradientLine--) | 図形の現在のグラデーション線書式設定値を含みます |
| [getLineCap()](#getLineCap--) | 線が丸みのある端か四角い端かを指定します。 |
| [getLineColor()](#getLineColor--) | 図形の線の色を指定します。 |
| [getLineColorTrans()](#getLineColorTrans--) | 図形の線の色の透明度レベルを指定します。0（不透明）から1（完全に透明）までです。 |
| [getLinePattern()](#getLinePattern--) | 図形の線パターンを指定します |
| [getLineWeight()](#getLineWeight--) | 図形の線の太さを指定します。 |
| [getRounding()](#getRounding--) | パスの連続する2つのセグメントが接続する箇所に適用される丸みアークの半径を指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBeginArrow(IntValue value)](#setBeginArrow-com.aspose.diagram.IntValue-) | このプロパティの説明については、[getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--) を参照してください |
| [setBeginArrowSize(ArrowSize value)](#setBeginArrowSize-com.aspose.diagram.ArrowSize-) | このプロパティの説明については、[getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--) を参照してください |
| [setCompoundType(CompoundType value)](#setCompoundType-com.aspose.diagram.CompoundType-) | このプロパティの説明については、[getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--) を参照してください |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/line\#getDel--) を参照してください |
| [setEndArrow(IntValue value)](#setEndArrow-com.aspose.diagram.IntValue-) | このプロパティの説明については、[getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--) を参照してください |
| [setEndArrowSize(ArrowSize value)](#setEndArrowSize-com.aspose.diagram.ArrowSize-) | このプロパティの説明については、[getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--) を参照してください |
| [setLineCap(BoolValue value)](#setLineCap-com.aspose.diagram.BoolValue-) | このプロパティの説明については、[getLineCap()](../../com.aspose.diagram/line\#getLineCap--) を参照してください |
| [setLineColor(ColorValue value)](#setLineColor-com.aspose.diagram.ColorValue-) | このプロパティの説明については、[getLineColor()](../../com.aspose.diagram/line\#getLineColor--) を参照してください |
| [setLineColorTrans(DoubleValue value)](#setLineColorTrans-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--) を参照してください |
| [setLinePattern(IntValue value)](#setLinePattern-com.aspose.diagram.IntValue-) | このプロパティの説明については、[getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--) を参照してください |
| [setLineWeight(DoubleValue value)](#setLineWeight-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--) を参照してください |
| [setRounding(DoubleValue value)](#setRounding-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getRounding()](../../com.aspose.diagram/line\#getRounding--) を参照してください |
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
### getBeginArrow() {#getBeginArrow--}
```
public IntValue getBeginArrow()
```


線の最初の頂点に矢じりまたはその他の線端形式があるかどうかを示します。0 から 45 の数値、またはカスタム線端の名前を使用した USE 関数を入力してください。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBeginArrowSize() {#getBeginArrowSize--}
```
public ArrowSize getBeginArrowSize()
```


線の始点にある矢じりのサイズを決定します。0 から 6 の数値を入力してください。

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompoundType() {#getCompoundType--}
```
public CompoundType getCompoundType()
```


図形の線のCompoundTypeを指定します。

**Returns:**
[CompoundType](../../com.aspose.diagram/compoundtype)
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally.

**Returns:**
int
### getEndArrow() {#getEndArrow--}
```
public IntValue getEndArrow()
```


線の最後の頂点に矢じりまたはその他の線端形式があるかどうかを示します。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getEndArrowSize() {#getEndArrowSize--}
```
public ArrowSize getEndArrowSize()
```


線の終点における矢じりのサイズを指定します。

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getGradientLine() {#getGradientLine--}
```
public GradientFill getGradientLine()
```


図形の現在のグラデーション線書式設定値を含みます

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getLineCap() {#getLineCap--}
```
public BoolValue getLineCap()
```


線が丸みのある端か四角い端かを指定します。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineColor() {#getLineColor--}
```
public ColorValue getLineColor()
```


図形の線の色を指定します。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getLineColorTrans() {#getLineColorTrans--}
```
public DoubleValue getLineColorTrans()
```


図形の線の色の透明度レベルを指定します。0（不透明）から 1（完全に透明）までです。デフォルトは 0 です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLinePattern() {#getLinePattern--}
```
public IntValue getLinePattern()
```


図形の線パターンを指定します

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLineWeight() {#getLineWeight--}
```
public DoubleValue getLineWeight()
```


図形の線幅を指定します。線幅は図面のスケールに依存しません。図面が拡大縮小されても、線幅は変わりません。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRounding() {#getRounding--}
```
public DoubleValue getRounding()
```


パスの連続する2つのセグメントが接続する箇所に適用される丸み弧の半径を指定します。例えば、矩形に丸みを持たせる際に使用できます。

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




### setBeginArrow(IntValue value) {#setBeginArrow-com.aspose.diagram.IntValue-}
```
public void setBeginArrow(IntValue value)
```


このプロパティの説明については、[getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBeginArrowSize(ArrowSize value) {#setBeginArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setBeginArrowSize(ArrowSize value)
```


このプロパティの説明については、[getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setCompoundType(CompoundType value) {#setCompoundType-com.aspose.diagram.CompoundType-}
```
public void setCompoundType(CompoundType value)
```


このプロパティの説明については、[getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [CompoundType](../../com.aspose.diagram/compoundtype) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel()](../../com.aspose.diagram/line\#getDel--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEndArrow(IntValue value) {#setEndArrow-com.aspose.diagram.IntValue-}
```
public void setEndArrow(IntValue value)
```


このプロパティの説明については、[getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setEndArrowSize(ArrowSize value) {#setEndArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setEndArrowSize(ArrowSize value)
```


このプロパティの説明については、[getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setLineCap(BoolValue value) {#setLineCap-com.aspose.diagram.BoolValue-}
```
public void setLineCap(BoolValue value)
```


このプロパティの説明については、[getLineCap()](../../com.aspose.diagram/line\#getLineCap--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setLineColor(ColorValue value) {#setLineColor-com.aspose.diagram.ColorValue-}
```
public void setLineColor(ColorValue value)
```


このプロパティの説明については、[getLineColor()](../../com.aspose.diagram/line\#getLineColor--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setLineColorTrans(DoubleValue value) {#setLineColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setLineColorTrans(DoubleValue value)
```


このプロパティの説明については、[getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLinePattern(IntValue value) {#setLinePattern-com.aspose.diagram.IntValue-}
```
public void setLinePattern(IntValue value)
```


このプロパティの説明については、[getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLineWeight(DoubleValue value) {#setLineWeight-com.aspose.diagram.DoubleValue-}
```
public void setLineWeight(DoubleValue value)
```


このプロパティの説明については、[getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRounding(DoubleValue value) {#setRounding-com.aspose.diagram.DoubleValue-}
```
public void setRounding(DoubleValue value)
```


このプロパティの説明については、[getRounding()](../../com.aspose.diagram/line\#getRounding--) を参照してください

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

