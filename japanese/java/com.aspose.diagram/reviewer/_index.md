---
title: レビュアー
second_title: Aspose.Diagram for Java API リファレンス
description: 文書レビュアーに関する識別情報を含む要素を含みます。
type: docs
weight: 330
url: /ja/java/com.aspose.diagram/reviewer/
---

**Inheritance:**
java.lang.Object
```
public class Reviewer
```

文書レビュアーに関する識別情報を含む要素を含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Reviewer()](#Reviewer--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Color 要素は、文書レビュアーのマークアップに割り当てられた色を表す RGB 値を指定します。 |
| [getCurrentIndex()](#getCurrentIndex--) | 現在のレビュアーが文書に別のコメントを追加するときに追加される MarkerIndex 要素の値を示します。 |
| [getDel()](#getDel--) | 要素がローカルで削除されたかどうかを示すフラグです。 |
| [getIX()](#getIX--) | 親要素内の要素のゼロベースインデックスです。 |
| [getInitials()](#getInitials--) | 文書レビュアーのイニシャルが含まれます。 |
| [getName()](#getName--) | Name 要素は、文書レビュアーの名前を指定します。 |
| [getReviewerID()](#getReviewerID--) | ドキュメントにマークアップを追加したレビュアーの ID 番号を含みます。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | このプロパティの説明については、[getDel()](../../com.aspose.diagram/reviewer\#getDel--) を参照してください。 |
| [setIX(int value)](#setIX-int-) | このプロパティの説明については、[getIX()](../../com.aspose.diagram/reviewer\#getIX--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Reviewer() {#Reviewer--}
```
public Reviewer()
```


コンストラクタ。

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
### getColor() {#getColor--}
```
public ColorValue getColor()
```


Color 要素は、文書レビュアーのマークアップに割り当てられた色を表す RGB 値を指定します。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getCurrentIndex() {#getCurrentIndex--}
```
public IntValue getCurrentIndex()
```


現在のレビュアーが文書に別のコメントを追加するときに追加される MarkerIndex 要素の値を示します。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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
### getInitials() {#getInitials--}
```
public Str2Value getInitials()
```


文書レビュアーのイニシャルが含まれます。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getName() {#getName--}
```
public Str2Value getName()
```


Name 要素は、文書レビュアーの名前を指定します。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getReviewerID() {#getReviewerID--}
```
public IntValue getReviewerID()
```


ドキュメントにマークアップを追加したレビュアーの ID 番号を含みます。

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


このプロパティの説明については、[getDel()](../../com.aspose.diagram/reviewer\#getDel--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


このプロパティの説明については、[getIX()](../../com.aspose.diagram/reviewer\#getIX--) を参照してください。

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

