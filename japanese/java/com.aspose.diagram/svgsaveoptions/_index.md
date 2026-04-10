---
title: SVGSaveOptions
second_title: Aspose.Diagram for Java API リファレンス
description: 図ページを SVG にレンダリングする際に追加オプションを指定できます。
type: docs
weight: 347
url: /ja/java/com.aspose.diagram/svgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class SVGSaveOptions extends RenderingSaveOptions
```

図ページを SVG にレンダリングする際に追加オプションを指定できます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SVGSaveOptions()](#SVGSaveOptions--) | このクラスの新しいインスタンスを初期化します。このインスタンスは Aspose.Diagram.SaveFileFormat 形式でドキュメントを保存するために使用できます。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 指定された保存形式に適したクラスの保存オプションオブジェクトを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomImagePath()](#getCustomImagePath--) | 生成された SVG ファイルに保存される画像用のユーザーカスタムパス（URL）。 |
| [getDefaultFont()](#getDefaultFont--) | 図内の文字が Unicode で、正しいフォント値が設定されていない、またはフォントがローカルにインストールされていない場合、pdf、画像、または XPS でブロックとして表示されることがあります。 |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Emf メタファイルのレンダリング設定です。 |
| [getEnlargePage()](#getEnlargePage--) | ページを拡大するかどうかを指定します。 |
| [getExportElementAsRectTag()](#getExportElementAsRectTag--) | 矩形要素を rect タグとしてエクスポートするかどうかを定義します。 |
| [getExportGuideShapes()](#getExportGuideShapes--) | ガイドシェイプをエクスポートするかどうかを定義します。 |
| [getExportHiddenPage()](#getExportHiddenPage--) | 非表示ページをエクスポートするかどうかを定義します。 |
| [getPageIndex()](#getPageIndex--) | レンダリングするページの 0 ベースインデックスです。 |
| [getPageSize()](#getPageSize--) | 生成された画像のページサイズ。 |
| [getQuality()](#getQuality--) | ページを JPEG 形式で保存する際にのみ適用される、生成された画像の品質を決定する値です。 |
| [getSVGFitToViewPort()](#getSVGFitToViewPort--) | このプロパティが true の場合、生成された SVG はビューポートに合わせてサイズが調整されます。 |
| [getSaveFormat()](#getSaveFormat--) | この保存オプションオブジェクトが使用される場合、ドキュメントが保存される形式を指定します。 |
| [getShapes()](#getShapes--) | レンダリングするシェイプ。 |
| [getWarningCallback()](#getWarningCallback--) | 警告コールバック。 |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | コメントをエクスポートするかどうかを定義します。 |
| [isExportScaleInMatrix()](#isExportScaleInMatrix--) | スケールを行列としてエクスポートするかどうかを定義します。 |
| [isSavingCustomLinePattern()](#isSavingCustomLinePattern--) | カスタムラインパターンを保存するかどうかを定義します。 |
| [isSavingImageSeparately()](#isSavingImageSeparately--) | 画像を別々に保存するかどうかを定義します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomImagePath(String value)](#setCustomImagePath-java.lang.String-) | このプロパティの説明については、[getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--) を参照してください |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | このプロパティの説明については、[getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) を参照してください。 |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | このプロパティの説明については、[getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) を参照してください。 |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | このプロパティの説明については、[getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) を参照してください。 |
| [setExportComments(boolean value)](#setExportComments-boolean-) | このプロパティの説明については、[isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) を参照してください。 |
| [setExportElementAsRectTag(boolean value)](#setExportElementAsRectTag-boolean-) | このプロパティの説明については、[getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--) を参照してください |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | このプロパティの説明については、[getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) を参照してください。 |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | このプロパティの説明については、[getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--) を参照してください |
| [setExportScaleInMatrix(boolean value)](#setExportScaleInMatrix-boolean-) | このプロパティの説明については、[isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--) を参照してください |
| [setPageIndex(int value)](#setPageIndex-int-) | このプロパティの説明については、[getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--) を参照してください |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | このプロパティの説明については、[getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) を参照してください。 |
| [setQuality(int value)](#setQuality-int-) | このプロパティの説明については、[getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--) を参照してください |
| [setSVGFitToViewPort(boolean value)](#setSVGFitToViewPort-boolean-) | このプロパティの説明については、[getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--) を参照してください。 |
| [setSaveFormat(int value)](#setSaveFormat-int-) | このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) を参照してください。 |
| [setSavingCustomLinePattern(boolean value)](#setSavingCustomLinePattern-boolean-) | このプロパティの説明については、[isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--) を参照してください。 |
| [setSavingImageSeparately(boolean value)](#setSavingImageSeparately-boolean-) | このプロパティの説明については、[isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--) を参照してください。 |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | このプロパティの説明については、[getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) を参照してください。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SVGSaveOptions() {#SVGSaveOptions--}
```
public SVGSaveOptions()
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
### getCustomImagePath() {#getCustomImagePath--}
```
public String getCustomImagePath()
```


画像の生成された SVG ファイルに保存されるユーザーカスタムパス（URL）。ユーザーが定義しない場合、現在のディレクトリが使用されます。

**Returns:**
java.lang.String
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
### getExportElementAsRectTag() {#getExportElementAsRectTag--}
```
public boolean getExportElementAsRectTag()
```


矩形要素を rect タグとしてエクスポートするかどうかを定義します。デフォルト値は false です。

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
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


レンダリングするページの 0 ベースインデックス。デフォルトは 0 です。

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


生成された画像のページサイズです。 [PageSize](../../com.aspose.diagram/pagesize) または null にできます。デフォルト値は null です。PageSize が null の場合、生成された画像のページサイズはソース図から取得されます。

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getQuality() {#getQuality--}
```
public int getQuality()
```


生成された画像の品質を決定する値で、ページを JPEG 形式で保存する場合にのみ適用されます。デフォルト値は 100 です。JPEG で保存する場合にのみ効果があります。値は 0 から 100 の間でなければなりません。デフォルト値は 100 です。

**Returns:**
int
### getSVGFitToViewPort() {#getSVGFitToViewPort--}
```
public boolean getSVGFitToViewPort()
```


このプロパティが true の場合、生成された SVG はビューポートに合わせてサイズが調整されます。

**Returns:**
boolean
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
### isExportScaleInMatrix() {#isExportScaleInMatrix--}
```
public boolean isExportScaleInMatrix()
```


スケールを行列としてエクスポートするかどうかを定義します。デフォルト値は true です。

**Returns:**
boolean
### isSavingCustomLinePattern() {#isSavingCustomLinePattern--}
```
public boolean isSavingCustomLinePattern()
```


カスタムラインパターンを保存するかどうかを定義します。

**Returns:**
boolean
### isSavingImageSeparately() {#isSavingImageSeparately--}
```
public boolean isSavingImageSeparately()
```


画像を別々に保存するかどうかを定義します。

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




### setCustomImagePath(String value) {#setCustomImagePath-java.lang.String-}
```
public void setCustomImagePath(String value)
```


このプロパティの説明については、[getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

### setExportElementAsRectTag(boolean value) {#setExportElementAsRectTag-boolean-}
```
public void setExportElementAsRectTag(boolean value)
```


このプロパティの説明については、[getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--) を参照してください

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


このプロパティの説明については、[getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setExportScaleInMatrix(boolean value) {#setExportScaleInMatrix-boolean-}
```
public void setExportScaleInMatrix(boolean value)
```


このプロパティの説明については、[isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


このプロパティの説明については、[getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--) を参照してください

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


このプロパティの説明については、[getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--) を参照してください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSVGFitToViewPort(boolean value) {#setSVGFitToViewPort-boolean-}
```
public void setSVGFitToViewPort(boolean value)
```


このプロパティの説明については、[getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSavingCustomLinePattern(boolean value) {#setSavingCustomLinePattern-boolean-}
```
public void setSavingCustomLinePattern(boolean value)
```


このプロパティの説明については、[isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSavingImageSeparately(boolean value) {#setSavingImageSeparately-boolean-}
```
public void setSavingImageSeparately(boolean value)
```


このプロパティの説明については、[isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--) を参照してください。

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

