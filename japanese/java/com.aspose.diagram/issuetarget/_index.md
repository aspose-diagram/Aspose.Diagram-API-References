---
title: IssueTarget
second_title: Aspose.Diagram for Java API リファレンス
description: 親検証問題の対象に応じて、ページ、またはページとシェイプの両方を指定します。
type: docs
weight: 210
url: /ja/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

親検証問題の対象に応じて、ページ、またはページとシェイプの両方を指定します。親検証問題の対象がドキュメントの場合、IssueTarget はページもシェイプも指定しません。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | 親検証問題に関連付けられたページの一意識別子を指定します。 |
| [getShapeId()](#getShapeId--) | 親検証問題に関連付けられたシェイプの一意識別子を指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | このプロパティの説明については、[getPageId()](../../com.aspose.diagram/issuetarget\\#getPageId--) を参照してください。 |
| [setShapeId(long value)](#setShapeId-long-) | このプロパティの説明については、[getShapeId()](../../com.aspose.diagram/issuetarget\\#getShapeId--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IssueTarget(long pageID, long shapeID) {#IssueTarget-long-long-}
```
public IssueTarget(long pageID, long shapeID)
```


コンストラクタ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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
### getPageId() {#getPageId--}
```
public long getPageId()
```


親検証問題に関連付けられたページの一意識別子を指定します。対象がドキュメントの場合、PageID の値は 0xFFFFFFFF にできます。

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


親検証問題に関連付けられたシェイプの一意識別子を指定します。対象がドキュメントまたはページの場合、ShapeID の値は 0xFFFFFFFF にできます。

**Returns:**
long
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




### setPageId(long value) {#setPageId-long-}
```
public void setPageId(long value)
```


このプロパティの説明については、[getPageId()](../../com.aspose.diagram/issuetarget\\#getPageId--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


このプロパティの説明については、[getShapeId()](../../com.aspose.diagram/issuetarget\\#getShapeId--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

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

