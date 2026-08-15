---
title: XPSSaveOptions
second_title: Aspose.Diagram for Java API リファレンス
description: ダイアグラムページを XPS にレンダリングする際に、追加オプションを指定できます。
type: docs
weight: 453
url: /ja/java/com.aspose.diagram/xpssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XPSSaveOptions extends SaveOptions
```

ダイアグラムページを XPS にレンダリングする際に、追加オプションを指定できます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XPSSaveOptions()](#XPSSaveOptions--) | このクラスの新しいインスタンスを初期化します。このインスタンスは Aspose.Diagram.SaveFileFormat 形式でドキュメントを保存するために使用できます。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 指定された保存形式に適したクラスの保存オプションオブジェクトを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | 図内の文字が Unicode で、正しいフォント値が設定されていない、またはフォントがローカルにインストールされていない場合、pdf、画像、または XPS でブロックとして表示されることがあります。 |
| [getExportHiddenPage()](#getExportHiddenPage--) | 非表示ページをエクスポートするかどうかを定義します。 |
| [getPageCount()](#getPageCount--) | XPS でレンダリングするページ数。 |
| [getPageIndex()](#getPageIndex--) | レンダリングする最初のページの 0 ベースインデックス。 |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | すべてのページを画像として保存するか、前景のみを保存するかを指定します。 |
| [getSaveFormat()](#getSaveFormat--) | この保存オプションオブジェクトが使用された場合、レンダリングされた図ページが保存される形式を指定します。 |
| [getWarningCallback()](#getWarningCallback--) | 警告コールバック。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | このプロパティの説明については、[getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) を参照してください。 |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | このプロパティの説明については、[getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--) を参照してください。 |
| [setPageCount(int value)](#setPageCount-int-) | このプロパティの説明については、[getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--) を参照してください。 |
| [setPageIndex(int value)](#setPageIndex-int-) | このプロパティの説明については、[getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--) を参照してください。 |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | このプロパティの説明については、[getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--) を参照してください。 |
| [setSaveFormat(int value)](#setSaveFormat-int-) | このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--) を参照してください。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XPSSaveOptions() {#XPSSaveOptions--}
```
public XPSSaveOptions()
```


このクラスの新しいインスタンスを初期化します。このインスタンスは Aspose.Diagram.SaveFileFormat 形式でドキュメントを保存するために使用できます。

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
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


非表示ページをエクスポートするかどうかを定義します。デフォルト値は true です。

**Returns:**
boolean
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


XPS でレンダリングするページ数。デフォルトは MaxValue で、これはダイアグラムのすべてのページがレンダリングされることを意味します。

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


レンダリングする最初のページの 0 ベースインデックスです。デフォルトは 0 です。

**Returns:**
int
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


すべてのページを画像として保存するか、前景のみを保存するかを指定します。true の場合、前景ページのみがレンダリングされます（背景が存在すれば含む）。false の場合、前景ページがレンダリングされた後、空の背景ページが続きます。PageCount が 1 より大きい場合にのみ true を返すことができます。デフォルト値は false です。

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


この保存オプションオブジェクトが使用される場合、レンダリングされた図ページが保存される形式を指定します。Aspose.Diagram.SaveFileFormat のみ使用できます。

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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


このプロパティの説明については、[getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


このプロパティの説明については、[getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


このプロパティの説明については、[getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


このプロパティの説明については、[getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--) を参照してください。

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

