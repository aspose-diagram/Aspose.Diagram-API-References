---
title: RelEllipticalArcTo
second_title: Aspose.Diagram for Java API リファレンス
description: 楕円弧に関する情報を指定する要素を含みます。座標は相対座標として指定されます。
type: docs
weight: 318
url: /ja/java/com.aspose.diagram/relellipticalarcto/
---

**Inheritance:**
java.lang.Object、[com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class RelEllipticalArcTo extends Coordinate
```

楕円弧に関する情報を指定する要素を含みます。座標は相対座標として指定されます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RelEllipticalArcTo()](#RelEllipticalArcTo--) | [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) クラスのインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | 円弧の制御点の x 座標。 |
| [getB()](#getB--) | 円弧の制御点の y 座標。 |
| [getC()](#getC--) | 円弧の主軸が親の x 軸に対してなす角度。 |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | 円弧の主軸と副軸の比率。 |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getIX()](#getIX--) | 親要素内の要素のゼロベースインデックスです。 |
| [getX()](#getX--) | 楕円弧の終端頂点の x 座標。 |
| [getY()](#getY--) | 楕円弧の終端頂点の y 座標。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getA()](../../com.aspose.diagram/relellipticalarcto\#getA--) を参照してください。 |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getB()](../../com.aspose.diagram/relellipticalarcto\#getB--) を参照してください。 |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getC()](../../com.aspose.diagram/relellipticalarcto\#getC--) を参照してください。 |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getD()](../../com.aspose.diagram/relellipticalarcto\#getD--) を参照してください。 |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--) を参照してください。 |
| [setIX(int value)](#setIX-int-) | このプロパティの説明については、[getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--) を参照してください。 |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getX()](../../com.aspose.diagram/relellipticalarcto\#getX--) を参照してください。 |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getY()](../../com.aspose.diagram/relellipticalarcto\#getY--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelEllipticalArcTo() {#RelEllipticalArcTo--}
```
public RelEllipticalArcTo()
```


[EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) クラスのインスタンスを作成します。

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
### getA() {#getA--}
```
public DoubleValue getA()
```


円弧の制御点の x 座標です。制御点は円弧の開始点と終了点の中間付近に配置するのが最適です。そうしないと、円弧は制御点を通過させるために極端に大きくなる可能性があり、予測できない結果を招くことがあります。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


円弧の制御点の y 座標。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


円弧の主軸が親の x 軸に対してなす角度。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


円弧の長軸と短軸の比率です。これらの語の通常の意味にもかかわらず、長軸が短軸より大きい必要はなく、したがってこの比率が 1 より大きい必要もありません。この要素を 0 以下または 1000 超の値に設定すると、予測できない結果になる可能性があります。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getX() {#getX--}
```
public DoubleValue getX()
```


楕円弧の終端頂点の x 座標。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


楕円弧の終端頂点の y 座標。

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


このプロパティの説明については、[getA()](../../com.aspose.diagram/relellipticalarcto\#getA--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


このプロパティの説明については、[getB()](../../com.aspose.diagram/relellipticalarcto\#getB--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


このプロパティの説明については、[getC()](../../com.aspose.diagram/relellipticalarcto\#getC--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


このプロパティの説明については、[getD()](../../com.aspose.diagram/relellipticalarcto\#getD--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


このプロパティの説明については、[getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


このプロパティの説明については、[getX()](../../com.aspose.diagram/relellipticalarcto\#getX--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


このプロパティの説明については、[getY()](../../com.aspose.diagram/relellipticalarcto\#getY--) を参照してください。

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

