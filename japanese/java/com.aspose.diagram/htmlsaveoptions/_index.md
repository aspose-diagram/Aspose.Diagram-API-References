---
title: HTMLSaveOptions
second_title: Aspose.Diagram for Java API リファレンス
description: ダイアグラムページを HTML にレンダリングする際に、追加オプションを指定できます。
type: docs
weight: 187
url: /ja/java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

ダイアグラムページを HTML にレンダリングする際に、追加オプションを指定できます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | このクラスの新しいインスタンスを初期化します。このインスタンスは Aspose.Diagram.SaveFileFormat 形式でドキュメントを保存するために使用できます。 |
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
| [getExportHiddenPage()](#getExportHiddenPage--) | 非表示ページをエクスポートするかどうかを定義します。 |
| [getPageCount()](#getPageCount--) | HTML にレンダリングするページ数。 |
| [getPageIndex()](#getPageIndex--) | レンダリングする最初のページの 0 ベースインデックス。 |
| [getPageSize()](#getPageSize--) | 生成された画像のページサイズ。 |
| [getResolution()](#getResolution--) | 生成された HTML の解像度（dpi 単位）。 |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | HTML を単一ファイルとして保存するかどうかを示します。 |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | すべてのページを画像として保存するか、前景のみを保存するかを指定します。 |
| [getSaveFormat()](#getSaveFormat--) | この保存オプションオブジェクトが使用された場合、レンダリングされた図ページが保存される形式を指定します。 |
| [getSaveTitle()](#getSaveTitle--) | タイトルをエクスポートするかどうかを定義します。 |
| [getSaveToolBar()](#getSaveToolBar--) | ツールバーを保存するかどうかを指定します。デフォルト値は true です。 |
| [getShapes()](#getShapes--) | レンダリングするシェイプ。 |
| [getStreamProvider()](#getStreamProvider--) | オブジェクトをエクスポートするための IStreamProvider。 |
| [getTitle()](#getTitle--) | HTML にレンダリングする図のタイトル。 |
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
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | このプロパティの説明については、[getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--) を参照してください。 |
| [setPageCount(int value)](#setPageCount-int-) | このプロパティの説明については、[getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--) を参照してください。 |
| [setPageIndex(int value)](#setPageIndex-int-) | このプロパティの説明については、[getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--) を参照してください。 |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | このプロパティの説明については、[getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) を参照してください。 |
| [setResolution(int value)](#setResolution-int-) | このプロパティの説明については、[getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--) を参照してください。 |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | このプロパティの説明については、[getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--) を参照してください。 |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | このプロパティの説明については、[getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--) を参照してください。 |
| [setSaveFormat(int value)](#setSaveFormat-int-) | このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--) を参照してください。 |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | このプロパティの説明については、[getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--) を参照してください。 |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | このプロパティの説明については、[getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--) を参照してください。 |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | このプロパティの説明については、[getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) を参照してください。 |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | このプロパティの説明については、[getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--) を参照してください。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | このプロパティの説明については、[getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--) を参照してください。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
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


HTML でレンダリングするページ数です。デフォルトは MaxValue で、これはダイアグラムのすべてのページがレンダリングされることを意味します。

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


レンダリングする最初のページの 0 ベースインデックスです。デフォルトは 0 です。

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


生成された画像のページサイズです。 [PageSize](../../com.aspose.diagram/pagesize) または null にできます。デフォルト値は null です。PageSize が null の場合、生成された画像のページサイズはソース図から取得されます。

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getResolution() {#getResolution--}
```
public int getResolution()
```


生成された HTML の解像度（dpi）です。このプロパティは HTML に保存する場合にのみ効果があります。デフォルト値は 96 です。

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


HTML を単一ファイルとして保存するかどうかを示します。デフォルト値は false です。複数ページがある場合、これらのページとその他のリソースは別々のファイルに保存する必要があります。シナリオによっては、転送の便利さのために結果ファイルを1つだけ取得したい場合があります。その場合、ユーザーはこのプロパティを true に設定できます。

**Returns:**
boolean
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
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


タイトルをエクスポートするかどうかを定義します。デフォルト値は true です。

**Returns:**
boolean
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


ツールバーを保存するかどうかを指定します。デフォルト値は true です。

**Returns:**
boolean
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


レンダリングするシェイプです。デフォルトのカウントは 0 です。

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


オブジェクトをエクスポートするための IStreamProvider。

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


HTML にレンダリングする図のタイトルです。Title が null の場合、Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties) がタイトルとして使用されます。Diagram.DocumentProperties.Title が null または空の場合、Diagram のファイル名がタイトルとして使用されます。

**Returns:**
java.lang.String
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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


このプロパティの説明については、[getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


このプロパティの説明については、[getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


このプロパティの説明については、[getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


このプロパティの説明については、[getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


このプロパティの説明については、[getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


このプロパティの説明については、[getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


このプロパティの説明については、[getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


このプロパティの説明については、[getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


このプロパティの説明については、[getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


このプロパティの説明については、[getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


このプロパティの説明については、[getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


このプロパティの説明については、[getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

