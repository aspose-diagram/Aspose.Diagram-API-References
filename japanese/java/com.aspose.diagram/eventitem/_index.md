---
title: EventItem
second_title: Aspose.Diagram for Java API リファレンス
description: イベント コードをカプセル化します。
type: docs
weight: 145
url: /ja/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

イベントコードをカプセル化します。EventItem 要素は 2 種類のアクションをトリガーできます：アドオンを実行するか、イベントの通知を呼び出し元プログラムに送信するかです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EventItem()](#EventItem--) | コンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | 親の EventItem 要素のアクションコードを指定します。EventItem 要素を DatadiagramML ファイルに保存するには、永続可能である必要があります。 |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | イベントが有効か無効かを示すフラグを表します。 |
| [getEventCode()](#getEventCode--) | アドオンをトリガーするイベントを示すコードです。 |
| [getID()](#getID--) | イベントの ID です。 |
| [getTarget()](#getTarget--) | イベントの対象を指定します。 |
| [getTargetArgs()](#getTargetArgs--) | イベントの対象に送信される引数を含む文字列を指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | このプロパティの説明については、[getAction()](../../com.aspose.diagram/eventitem\#getAction--) を参照してください。 |
| [setEnabled(int value)](#setEnabled-int-) | このプロパティの説明については、[getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) を参照してください。 |
| [setEventCode(int value)](#setEventCode-int-) | このプロパティの説明については、[getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) を参照してください。 |
| [setID(int value)](#setID-int-) | このプロパティの説明については、[getID()](../../com.aspose.diagram/eventitem\#getID--) を参照してください。 |
| [setTarget(String value)](#setTarget-java.lang.String-) | このプロパティの説明については、[getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) を参照してください。 |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | このプロパティの説明については、[getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) を参照してください。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
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
### getAction() {#getAction--}
```
public int getAction()
```


親の EventItem 要素のアクションコードを指定します。EventItem 要素を DatadiagramML ファイルに保存するには、永続可能である必要があります。現在、永続可能なイベントが持つことができる唯一の有効なアクションコードは 1（ONEVENT_ACT_RUNADDON）です。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnabled() {#getEnabled--}
```
public int getEnabled()
```


イベントが有効か無効かを示すフラグを表します。

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


アドオンをトリガーするイベントを示すコードです。イベントコードの詳細については、Microsoft Visio 2007 Automation Reference の Event Codes を参照してください。

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


イベントの ID です。

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


イベントの対象を指定します。

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


イベントの対象に送信される引数を含む文字列を指定します。

**Returns:**
java.lang.String
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




### setAction(int value) {#setAction-int-}
```
public void setAction(int value)
```


このプロパティの説明については、[getAction()](../../com.aspose.diagram/eventitem\#getAction--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


このプロパティの説明については、[getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


このプロパティの説明については、[getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


このプロパティの説明については、[getID()](../../com.aspose.diagram/eventitem\#getID--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


このプロパティの説明については、[getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


このプロパティの説明については、[getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

