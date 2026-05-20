---
title: Issue
second_title: Aspose.Diagram for Java API リファレンス
description: ドキュメント内の単一の検証問題を表します。
type: docs
weight: 208
url: /ja/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

ドキュメント内の単一の検証問題を表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Issue()](#Issue--) | コンストラクタ |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | 検証問題の一意の識別子を指定します。 |
| [getIgnored()](#getIgnored--) | 検証問題が現在無視されているかどうかを指定します。 |
| [getIssueTarget()](#getIssueTarget--) | 親検証問題の対象に応じて、親検証問題が関連付けられるページ、またはページとシェイプの両方を指定します。 |
| [getRuleInfo()](#getRuleInfo--) | 親の検証問題が関連する検証ルールに関する情報を指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | このプロパティの説明については、[getID()](../../com.aspose.diagram/issue\#getID--) をご覧ください。 |
| [setIgnored(int value)](#setIgnored-int-) | このプロパティの説明については、[getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) をご覧ください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


コンストラクタ

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
### getID() {#getID--}
```
public long getID()
```


検証問題の一意の識別子を指定します。

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


検証問題が現在無視されているかどうかを指定します。デフォルトは False です。

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


親検証問題の対象に応じて、ページ、またはページとシェイプの両方を指定します。親検証問題の対象がドキュメントの場合、IssueTarget はページもシェイプも指定しません。

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


親の検証問題が関連する検証ルールに関する情報を指定します。

**Returns:**
[RuleInfo](../../com.aspose.diagram/ruleinfo)
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




### setID(long value) {#setID-long-}
```
public void setID(long value)
```


このプロパティの説明については、[getID()](../../com.aspose.diagram/issue\#getID--) をご覧ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


このプロパティの説明については、[getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) をご覧ください。

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

