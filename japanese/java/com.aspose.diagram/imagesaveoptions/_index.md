---
title: ImageSaveOptions
second_title: Aspose.Diagram for Java API リファレンス
description: ダイアグラムページを画像にレンダリングする際に、追加オプションを指定できます。
type: docs
weight: 200
url: /ja/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

ダイアグラムページを画像にレンダリングする際に、追加オプションを指定できます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | このクラスの新しいインスタンスを初期化します。このインスタンスは、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、または Aspose.Diagram.SaveFileFormat 形式でレンダリングされた画像を保存するために使用できます。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 指定された保存形式に適したクラスの保存オプションオブジェクトを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | 合成時に使用する品質レベルを指定します。 |
| [getContentZoom()](#getContentZoom--) | このパラメーターはスケールに似ていますが、生成された画像サイズには影響しません。 |
| [getDefaultFont()](#getDefaultFont--) | 図内の文字が Unicode で、正しいフォント値が設定されていない、またはフォントがローカルにインストールされていない場合、pdf、画像、または XPS でブロックとして表示されることがあります。 |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Emf メタファイルのレンダリング設定です。 |
| [getEnlargePage()](#getEnlargePage--) | ページを拡大するかどうかを指定します。 |
| [getExportGuideShapes()](#getExportGuideShapes--) | ガイドシェイプをエクスポートするかどうかを定義します。 |
| [getExportHiddenPage()](#getExportHiddenPage--) | 非表示ページをエクスポートするかどうかを定義します。 |
| [getImageBrightness()](#getImageBrightness--) | 生成された画像の明るさ。 |
| [getImageColorMode()](#getImageColorMode--) | 生成された画像のカラーモード。 |
| [getImageContrast()](#getImageContrast--) | 生成された画像のコントラスト。 |
| [getInterpolationMode()](#getInterpolationMode--) | 画像が拡大縮小または回転される際に使用されるアルゴリズムを指定します。 |
| [getJpegQuality()](#getJpegQuality--) | 生成された JPEG 画像の品質を決定する値。 |
| [getPageCount()](#getPageCount--) | マルチページTIFFファイルに保存する際にレンダリングするページ数です。 |
| [getPageIndex()](#getPageIndex--) | レンダリングする最初のページの 0 ベースインデックス。 |
| [getPageSize()](#getPageSize--) | 生成された画像のページサイズ。 |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | レンダリング中にピクセルがどのようにオフセットされるかを指定する値です。 |
| [getResolution()](#getResolution--) | 生成された画像の解像度（ドット毎インチ）です。 |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | 保存領域がPDFと同じかどうかを指定します。 |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | すべてのページを画像として保存するか、前景のみを保存するかを指定します。 |
| [getSaveFormat()](#getSaveFormat--) | この保存オプションオブジェクトが使用された場合、レンダリングされた図ページが保存される形式を指定します。 |
| [getScale()](#getScale--) | 生成された画像のズーム倍率です。 |
| [getShapes()](#getShapes--) | レンダリングするシェイプ。 |
| [getSmoothingMode()](#getSmoothingMode--) | 線や曲線、塗りつぶし領域のエッジに平滑化（アンチエイリアス）が適用されるかどうかを指定します。 |
| [getTiffCompression()](#getTiffCompression--) | 生成された画像をTIFF形式で保存する際に適用する圧縮タイプです。 |
| [getWarningCallback()](#getWarningCallback--) | 警告コールバック。 |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | コメントをエクスポートするかどうかを定義します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | このプロパティの説明については、[getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) をご参照ください。 |
| [setContentZoom(float value)](#setContentZoom-float-) | このプロパティの説明については、[getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) をご参照ください。 |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | このプロパティの説明については、[getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) を参照してください。 |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | このプロパティの説明については、[getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) を参照してください。 |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | このプロパティの説明については、[getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) を参照してください。 |
| [setExportComments(boolean value)](#setExportComments-boolean-) | このプロパティの説明については、[isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) を参照してください。 |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | このプロパティの説明については、[getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) を参照してください。 |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | このプロパティの説明については、[getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) をご参照ください。 |
| [setImageBrightness(float value)](#setImageBrightness-float-) | このプロパティの説明については、[getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) をご参照ください。 |
| [setImageColorMode(int value)](#setImageColorMode-int-) | このプロパティの説明については、[getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) をご参照ください。 |
| [setImageContrast(float value)](#setImageContrast-float-) | このプロパティの説明については、[getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) をご参照ください。 |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | このプロパティの説明については、[getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) をご参照ください。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | このプロパティの説明については、[getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) をご参照ください。 |
| [setPageCount(int value)](#setPageCount-int-) | このプロパティの説明については、[getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) をご参照ください。 |
| [setPageIndex(int value)](#setPageIndex-int-) | このプロパティの説明については、[getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) をご参照ください。 |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | このプロパティの説明については、[getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) を参照してください。 |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | このプロパティの説明については、[getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) をご参照ください。 |
| [setResolution(float value)](#setResolution-float-) | このプロパティの説明については、[getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) をご参照ください。 |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | このプロパティの説明については、[getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) をご参照ください。 |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | このプロパティの説明については、[getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) をご参照ください。 |
| [setSaveFormat(int value)](#setSaveFormat-int-) | このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) をご参照ください。 |
| [setScale(float value)](#setScale-float-) | このプロパティの説明については、[getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) をご参照ください。 |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | このプロパティの説明については、[getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) を参照してください。 |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | このプロパティの説明については、[getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) をご参照ください。 |
| [setTiffCompression(int value)](#setTiffCompression-int-) | このプロパティの説明については、[getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) をご参照ください。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


このクラスの新しいインスタンスを初期化します。このインスタンスは、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、または Aspose.Diagram.SaveFileFormat 形式でレンダリングされた画像を保存するために使用できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| saveFormat | int | Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、または Aspose.Diagram.SaveFileFormat にできます。 |

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
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


合成時に使用する品質レベルを指定します。このプロパティはラスタ画像形式で保存する場合にのみ有効です。デフォルト値は Aspose.Diagram.Saving.CompositingQuality です。

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


このパラメータはスケールに似ていますが、生成される画像サイズには影響しません。デフォルト値は 1.0 です。値は 0 より大きくなければなりません。

**Returns:**
float
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
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


生成された画像の明るさです。このプロパティはラスタ画像形式で保存する場合にのみ有効です。デフォルト値は 0.5 です。値は 0 から 1 の範囲でなければなりません。

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


生成された画像のカラーモードです。このプロパティはラスタ画像形式で保存する場合にのみ有効です。デフォルト値は Aspose.Diagram.Saving.ImageColorMode です。

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


生成された画像のコントラストです。このプロパティはラスタ画像形式で保存する場合にのみ有効です。デフォルト値は 0.5 です。値は 0 から 1 の範囲でなければなりません。

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


画像が拡大縮小または回転される際に使用されるアルゴリズムを指定します。このプロパティはラスタ画像形式で保存する場合にのみ有効です。デフォルト値は Aspose.Diagram.Saving.InterpolationMode です。

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


生成された JPEG 画像の品質を決定する値です。JPEG で保存する場合にのみ有効です。このプロパティを使用して JPEG 形式で保存する際の画像品質を取得または設定します。値は 0 から 100 の範囲で、0 は最低品質で最大圧縮、100 は最高品質で最小圧縮を意味します。デフォルト値は 95 です。

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


マルチページ TIFF ファイルに保存する際にレンダリングするページ数です。デフォルトは MaxValue で、これは図のすべてのページがレンダリングされることを意味します。

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
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


レンダリング中のピクセルオフセット方法を指定する値です。このプロパティはラスタ画像形式で保存する場合にのみ有効です。デフォルト値は Aspose.Diagram.Saving.PixelOffsetMode です。

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


生成された画像の解像度（dpi）です。このプロパティはラスタ画像形式で保存する場合にのみ有効です。デフォルト値は 96 です。

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


保存領域が PDF と同じかどうかを指定します。true の場合、レンダリング領域は PDF と同じになります。false の場合、レンダリング領域はデフォルトになります。デフォルト値は false です。

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


この保存オプションオブジェクトが使用される場合、レンダリングされた図ページが保存される形式を指定します。Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、または Aspose.Diagram.SaveFileFormat のいずれかを指定できます。

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


生成された画像のズーム倍率です。デフォルト値は 1.0 です。値は 0 より大きくなければなりません。

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


レンダリングするシェイプです。デフォルトのカウントは 0 です。

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


線や曲線、塗りつぶし領域のエッジにスムージング（アンチエイリアス）が適用されるかどうかを指定します。このプロパティはラスタ画像形式で保存する場合にのみ有効です。デフォルト値は Aspose.Diagram.Saving.SmoothingMode です。

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


生成された画像を TIFF 形式で保存する際に適用する圧縮タイプです。TIFF で保存する場合にのみ有効です。デフォルト値は Aspose.Diagram.Saving.TiffCompression です。

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




### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


このプロパティの説明については、[getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


このプロパティの説明については、[getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

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


このプロパティの説明については、[getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


このプロパティの説明については、[getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


このプロパティの説明については、[getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


このプロパティの説明については、[getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


このプロパティの説明については、[getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


このプロパティの説明については、[getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


このプロパティの説明については、[getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


このプロパティの説明については、[getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) をご参照ください。

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

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


このプロパティの説明については、[getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


このプロパティの説明については、[getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


このプロパティの説明については、[getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


このプロパティの説明については、[getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


このプロパティの説明については、[getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


このプロパティの説明については、[getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


このプロパティの説明については、[getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) を参照してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


このプロパティの説明については、[getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) をご参照ください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


このプロパティの説明については、[getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) をご参照ください。

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

