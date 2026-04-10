---
title: SaveOptions
second_title: Aspose.Diagram for Java API リファレンス
description: これは、ユーザーが図を特定の形式で保存する際に追加オプションを指定できるクラスのための抽象基底クラスです。
type: docs
weight: 349
url: /ja/java/com.aspose.diagram/saveoptions/
---

**Inheritance:**
java.lang.Object
```
public abstract class SaveOptions
```

これは、特定の形式で図を保存する際に、ユーザーが追加オプションを指定できるようにするクラスの抽象基底クラスです。SaveOptions クラスまたはその派生クラスのインスタンスは、ストリーム Save または文字列 Save のオーバーロードに渡され、ドキュメントを保存する際のカスタムオプションを定義できるようにします。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 指定された保存形式に適したクラスの保存オプションオブジェクトを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | 図内の文字が Unicode で、正しいフォント値が設定されていない、またはフォントがローカルにインストールされていない場合、pdf、画像、または XPS でブロックとして表示されることがあります。 |
| [getSaveFormat()](#getSaveFormat--) | この保存オプションオブジェクトが使用される場合、ドキュメントが保存される形式を指定します。 |
| [getWarningCallback()](#getWarningCallback--) | 警告コールバック。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | このプロパティの説明については、[getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) を参照してください。 |
| [setSaveFormat(int value)](#setSaveFormat-int-) | このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) を参照してください。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


指定された保存形式に適したクラスの保存オプションオブジェクトを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| saveFormat | int | 保存オプションオブジェクトを作成するための Aspose.Diagram.SaveFileFormat です。 |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
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
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


ダイアグラム内の文字が Unicode で、正しいフォントが設定されていない、またはフォントがローカルにインストールされていない場合、PDF、画像、または XPS で文字がブロックとして表示されることがあります。MingLiu や MS Gothic などの DefaultFont を設定して、これらの文字を表示してください。

**Returns:**
java.lang.String
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


この保存オプションオブジェクトが使用される場合、ドキュメントが保存される形式を指定します。

**Returns:**
int
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


警告コールバック。

**Returns:**
[IWarningCallback](../../com.aspose.diagram/iwarningcallback)
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




### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


このプロパティの説明については、[getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.diagram/iwarningcallback) |  |

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

