---
title: イベント
second_title: Aspose.Diagram for Java API リファレンス
description: シェイプ イベントを制御する数式を指定する要素を含みます。
type: docs
weight: 144
url: /ja/java/com.aspose.diagram/event/
---

**Inheritance:**
java.lang.Object
```
public class Event
```

シェイプ イベントを制御する数式を指定する要素を含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | このインスタンスのディープコピーを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getEventDblClick()](#getEventDblClick--) | シェイプがダブルクリックされたときに評価されるイベント要素です。 |
| [getEventDrop()](#getEventDrop--) | シェイプが描画ページにドロップされたとき（インスタンスとして、またはシェイプが複製または貼り付けされたとき）に評価されるイベント要素です。 |
| [getEventMultiDrop()](#getEventMultiDrop--) | EventMultiDrop。 |
| [getEventXFMod()](#getEventXFMod--) | ページ上でシェイプの位置または向きが変換されたときに評価されるイベント要素です。 |
| [getTheData()](#getTheData--) | 将来の使用のために予約されています。 |
| [getTheText()](#getTheText--) | シェイプのテキストまたはテキスト構成が変更されたときに評価されるイベント要素です。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/event\#getDel--) を参照してください。 |
| [setEventDblClick(DoubleValue value)](#setEventDblClick-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getEventDblClick()](../../com.aspose.diagram/event\#getEventDblClick--) を参照してください。 |
| [setEventDrop(DoubleValue value)](#setEventDrop-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getEventDrop()](../../com.aspose.diagram/event\#getEventDrop--) を参照してください。 |
| [setEventMultiDrop(DoubleValue value)](#setEventMultiDrop-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getEventMultiDrop()](../../com.aspose.diagram/event\#getEventMultiDrop--) を参照してください。 |
| [setEventXFMod(DoubleValue value)](#setEventXFMod-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getEventXFMod()](../../com.aspose.diagram/event\#getEventXFMod--) を参照してください。 |
| [setTheData(DoubleValue value)](#setTheData-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getTheData()](../../com.aspose.diagram/event\#getTheData--) を参照してください。 |
| [setTheText(DoubleValue value)](#setTheText-com.aspose.diagram.DoubleValue-) | このプロパティの説明については、[getTheText()](../../com.aspose.diagram/event\#getTheText--) を参照してください。 |
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
### getEventDblClick() {#getEventDblClick--}
```
public DoubleValue getEventDblClick()
```


シェイプがダブルクリックされたときに評価されるイベント要素です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getEventDrop() {#getEventDrop--}
```
public DoubleValue getEventDrop()
```


シェイプが描画ページにドロップされたとき（インスタンスとして、またはシェイプが複製または貼り付けされたとき）に評価されるイベント要素です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getEventMultiDrop() {#getEventMultiDrop--}
```
public DoubleValue getEventMultiDrop()
```


EventMultiDrop。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getEventXFMod() {#getEventXFMod--}
```
public DoubleValue getEventXFMod()
```


ページ上でシェイプの位置または向きが変換されたときに評価されるイベント要素です。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTheData() {#getTheData--}
```
public DoubleValue getTheData()
```


将来の使用のために予約されています。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTheText() {#getTheText--}
```
public DoubleValue getTheText()
```


シェイプのテキストまたはテキスト構成が変更されたときに評価されるイベント要素です。

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


このプロパティの説明については、[getDel()](../../com.aspose.diagram/event\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEventDblClick(DoubleValue value) {#setEventDblClick-com.aspose.diagram.DoubleValue-}
```
public void setEventDblClick(DoubleValue value)
```


このプロパティの説明については、[getEventDblClick()](../../com.aspose.diagram/event\#getEventDblClick--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setEventDrop(DoubleValue value) {#setEventDrop-com.aspose.diagram.DoubleValue-}
```
public void setEventDrop(DoubleValue value)
```


このプロパティの説明については、[getEventDrop()](../../com.aspose.diagram/event\#getEventDrop--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setEventMultiDrop(DoubleValue value) {#setEventMultiDrop-com.aspose.diagram.DoubleValue-}
```
public void setEventMultiDrop(DoubleValue value)
```


このプロパティの説明については、[getEventMultiDrop()](../../com.aspose.diagram/event\#getEventMultiDrop--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setEventXFMod(DoubleValue value) {#setEventXFMod-com.aspose.diagram.DoubleValue-}
```
public void setEventXFMod(DoubleValue value)
```


このプロパティの説明については、[getEventXFMod()](../../com.aspose.diagram/event\#getEventXFMod--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTheData(DoubleValue value) {#setTheData-com.aspose.diagram.DoubleValue-}
```
public void setTheData(DoubleValue value)
```


このプロパティの説明については、[getTheData()](../../com.aspose.diagram/event\#getTheData--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTheText(DoubleValue value) {#setTheText-com.aspose.diagram.DoubleValue-}
```
public void setTheText(DoubleValue value)
```


このプロパティの説明については、[getTheText()](../../com.aspose.diagram/event\#getTheText--) を参照してください。

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

