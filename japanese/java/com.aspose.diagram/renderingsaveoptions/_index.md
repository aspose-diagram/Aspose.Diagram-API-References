---
title: RenderingSaveOptions
second_title: Aspose.Diagram for Java API リファレンス
description: これは、ユーザーが図を特定の形式で保存する際に追加オプションを指定できるクラスのための抽象基底クラスです。
type: docs
weight: 327
url: /ja/java/com.aspose.diagram/renderingsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public abstract class RenderingSaveOptions extends SaveOptions
```

これは、ユーザーが図を特定の形式で保存する際に追加オプションを指定できるクラスのための抽象基底クラスです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 指定された保存形式に適したクラスの保存オプションオブジェクトを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | 図内の文字が Unicode で、正しいフォント値が設定されていない、またはフォントがローカルにインストールされていない場合、pdf、画像、または XPS でブロックとして表示されることがあります。 |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Emf メタファイルのレンダリング設定です。 |
| [getEnlargePage()](#getEnlargePage--) | ページを拡大するかどうかを指定します。 |
| [getExportGuideShapes()](#getExportGuideShapes--) | ガイドシェイプをエクスポートするかどうかを定義します。 |
| [getPageSize()](#getPageSize--) | 生成された画像のページサイズ。 |
| [getSaveFormat()](#getSaveFormat--) | この保存オプションオブジェクトが使用される場合、ドキュメントが保存される形式を指定します。 |
| [getShapes()](#getShapes--) | レンダリングするシェイプ。 |
| [getWarningCallback()](#getWarningCallback--) | 警告コールバック。 |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | コメントをエクスポートするかどうかを定義します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | このプロパティの説明については、[getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) を参照してください。 |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | このプロパティの説明については、[getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) を参照してください。 |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | このプロパティの説明については、[getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) を参照してください。 |
| [setExportComments(boolean value)](#setExportComments-boolean-) | このプロパティの説明については、[isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) を参照してください。 |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | このプロパティの説明については、[getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) を参照してください。 |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | このプロパティの説明については、[getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) を参照してください。 |
| [setSaveFormat(int value)](#setSaveFormat-int-) | このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) を参照してください。 |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | このプロパティの説明については、[getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) を参照してください。 |
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
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Emf メタファイルのレンダリング設定です。\"EMF+ Dual\" と識別される EMF メタファイルは、EMF+ レコードと EMF レコードの両方を含むことができます。画像のレンダリングには、どちらのレコードタイプも使用でき、EMF+ レコードのみ、または EMF レコードのみを使用することもできます。EmfPlusPrefer が設定されている場合は EMF+ レコードが解析され、設定されていない場合は EMF レコードのみが解析されます。デフォルト値は EmfOnly です。

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


ページを拡大するかどうかを指定します。true の場合はページを拡大し、false の場合は拡大しません。デフォルト値は true です。

**Returns:**
boolean
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


ガイドシェイプをエクスポートするかどうかを定義します。デフォルト値は true です。

**Returns:**
boolean
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


生成された画像のページサイズです。 [PageSize](../../com.aspose.diagram/pagesize) または null にできます。デフォルト値は null です。PageSize が null の場合、生成された画像のページサイズはソース図から取得されます。

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


この保存オプションオブジェクトが使用される場合、ドキュメントが保存される形式を指定します。

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


レンダリングするシェイプです。デフォルトのカウントは 0 です。

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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
### isExportComments() {#isExportComments--}
```
public boolean isExportComments()
```


コメントをエクスポートするかどうかを定義します。デフォルト値は false です。

**Returns:**
boolean
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

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


このプロパティの説明については、[getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


このプロパティの説明については、[getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


このプロパティの説明については、[isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


このプロパティの説明については、[getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


このプロパティの説明については、[getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


このプロパティの説明については、[getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

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

