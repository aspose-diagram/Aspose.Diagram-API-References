---
title: 外部
second_title: Aspose.Diagram for Java API リファレンス
description: Microsoft Visio ドキュメントで使用される別のプログラムからのオブジェクトの幅と高さを指定する要素を含みます。
type: docs
weight: 163
url: /ja/java/com.aspose.diagram/foreign/
---

**Inheritance:**
java.lang.Object
```
public class Foreign
```

Microsoft Visio ドキュメントで使用される他のプログラムからのオブジェクトの幅と高さを指定する要素を含みます。また、オブジェクトの画像が境界内でオフセットされる距離を指定する要素も含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getImgHeight()](#getImgHeight--) | オブジェクトの境界内における画像の高さを決定します。 |
| [getImgOffsetX()](#getImgOffsetX--) | オブジェクトの境界の原点から水平方向にオフセットされる距離を決定します。 |
| [getImgOffsetY()](#getImgOffsetY--) | オブジェクトの境界の原点から垂直方向にオフセットされる距離を決定します。 |
| [getImgWidth()](#getImgWidth--) | オブジェクトの境界内における画像の幅を決定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/foreign\#getDel--)をご覧ください |
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
### getImgHeight() {#getImgHeight--}
```
public DoubleValue getImgHeight()
```


オブジェクトの境界内にある画像の高さを決定します。デフォルトの数式は: F=\"Height\\*1\"です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetX() {#getImgOffsetX--}
```
public DoubleValue getImgOffsetX()
```


オブジェクトの境界の原点から水平方向にオフセットされる距離を決定します。デフォルト値は 0 で、デフォルトの数式は F=\"ImgWidth\\*0\"です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetY() {#getImgOffsetY--}
```
public DoubleValue getImgOffsetY()
```


オブジェクトの境界の原点から垂直方向にオフセットされる距離を決定します。デフォルト値は 0 で、デフォルトの数式は F=\"ImgHeight\\*0\"です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgWidth() {#getImgWidth--}
```
public DoubleValue getImgWidth()
```


オブジェクトの境界内にある画像の幅を決定します。デフォルトの数式は: F=\"Width\\*1\"です。

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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


このプロパティの説明については、[getDel()](../../com.aspose.diagram/foreign\#getDel--)をご覧ください

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

