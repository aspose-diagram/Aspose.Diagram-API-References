---
title: ImageSaveOptions
second_title: Aspose.Diagram for Java API 参考
description: 允许在将图表页面渲染为图像时指定其他选项。
type: docs
weight: 200
url: /zh/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

允许在将图表页面渲染为图像时指定其他选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | 初始化此类的新实例，可用于将渲染的图像保存为 Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat 或 Aspose.Diagram.SaveFileFormat 格式。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 创建一个适用于指定保存格式的类的保存选项对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | 指定合成过程中使用的质量级别。 |
| [getContentZoom()](#getContentZoom--) | 此参数类似于 scale，但不影响生成的图像大小。 |
| [getDefaultFont()](#getDefaultFont--) | 当图表中的字符是 Unicode 且未设置正确的字体值或本地未安装该字体时，它们可能在 PDF、图像或 XPS 中显示为方块。 |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | 用于渲染 Emf 元文件的设置。 |
| [getEnlargePage()](#getEnlargePage--) | 指定是否放大页面。 |
| [getExportGuideShapes()](#getExportGuideShapes--) | 定义是否需要导出参考线形状。 |
| [getExportHiddenPage()](#getExportHiddenPage--) | 定义是否需要导出隐藏页面。 |
| [getImageBrightness()](#getImageBrightness--) | 生成图像的亮度。 |
| [getImageColorMode()](#getImageColorMode--) | 生成图像的颜色模式。 |
| [getImageContrast()](#getImageContrast--) | 生成图像的对比度。 |
| [getInterpolationMode()](#getInterpolationMode--) | 指定在对图像进行缩放或旋转时使用的算法。 |
| [getJpegQuality()](#getJpegQuality--) | 确定生成的 JPEG 图像质量的值。 |
| [getPageCount()](#getPageCount--) | 在保存为多页 TIFF 文件时要渲染的页数。 |
| [getPageIndex()](#getPageIndex--) | 要渲染的第一页的 0 基索引。 |
| [getPageSize()](#getPageSize--) | 生成图像的页面尺寸。 |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | 指定渲染过程中像素偏移方式的值。 |
| [getResolution()](#getResolution--) | 生成图像的分辨率（每英寸点数）。 |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | 指定保存区域是否与 PDF 相同。 |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | 指定是将所有页面保存为图像还是仅保存前景。 |
| [getSaveFormat()](#getSaveFormat--) | 指定使用此保存选项对象时，渲染的图表页面将保存为何种格式。 |
| [getScale()](#getScale--) | 生成图像的缩放因子。 |
| [getShapes()](#getShapes--) | 要渲染的形状。 |
| [getSmoothingMode()](#getSmoothingMode--) | 指定是否对线条、曲线以及填充区域的边缘应用平滑（抗锯齿）。 |
| [getTiffCompression()](#getTiffCompression--) | 将生成的图像保存为 TIFF 格式时要使用的压缩类型。 |
| [getWarningCallback()](#getWarningCallback--) | 警告回调。 |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | 定义是否需要导出注释。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | 有关此属性的描述，请参阅 [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)。 |
| [setContentZoom(float value)](#setContentZoom-float-) | 有关此属性的描述，请参阅 [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)。 |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | 有关此属性的描述，请参阅 [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | 有关此属性的描述，请参阅 [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | 有关此属性的描述，请参阅 [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | 有关此属性的描述，请参阅 [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | 有关此属性的描述，请参阅 [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | 有关此属性的描述，请参阅 [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)。 |
| [setImageBrightness(float value)](#setImageBrightness-float-) | 有关此属性的描述，请参阅 [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)。 |
| [setImageColorMode(int value)](#setImageColorMode-int-) | 有关此属性的描述，请参阅 [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)。 |
| [setImageContrast(float value)](#setImageContrast-float-) | 有关此属性的描述，请参阅 [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)。 |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | 有关此属性的描述，请参阅 [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 有关此属性的描述，请参阅 [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)。 |
| [setPageCount(int value)](#setPageCount-int-) | 有关此属性的描述，请参阅 [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)。 |
| [setPageIndex(int value)](#setPageIndex-int-) | 有关此属性的描述，请参阅 [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)。 |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | 有关此属性的描述，请参阅 [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | 有关此属性的描述，请参阅 [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)。 |
| [setResolution(float value)](#setResolution-float-) | 有关此属性的描述，请参阅 [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)。 |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | 有关此属性的描述，请参阅 [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)。 |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | 有关此属性的描述，请参阅 [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)。 |
| [setSaveFormat(int value)](#setSaveFormat-int-) | 有关此属性的描述，请参阅 [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)。 |
| [setScale(float value)](#setScale-float-) | 有关此属性的描述，请参阅 [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)。 |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | 有关此属性的描述，请参阅 [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | 有关此属性的描述，请参阅 [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)。 |
| [setTiffCompression(int value)](#setTiffCompression-int-) | 有关此属性的描述，请参阅 [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)。 |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


初始化此类的新实例，可用于将渲染的图像保存为 Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat 或 Aspose.Diagram.SaveFileFormat 格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| saveFormat | int | 可以是 Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat 或 Aspose.Diagram.SaveFileFormat。 |

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


创建一个适用于指定保存格式的类的保存选项对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| saveFormat | int | 用于创建保存选项对象的 Aspose.Diagram.SaveFileFormat。 |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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


指定在合成过程中使用的质量级别。此属性仅在保存为光栅图像格式时生效。默认值为 Aspose.Diagram.Saving.CompositingQuality。

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


此参数类似于 scale，但不影响生成图像的尺寸。默认值为 1.0。该值必须大于 0。

**Returns:**
float
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


当图表中的字符是 Unicode 且未设置正确的字体值，或本地未安装该字体时，它们可能在 PDF、图像或 XPS 中显示为方块。请将 DefaultFont 设置为如 MingLiu 或 MS Gothic 等，以显示这些字符。

**Returns:**
java.lang.String
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


用于渲染 EMF 元文件的设置。标识为 \"EMF+ Dual\" 的 EMF 元文件可以同时包含 EMF+ 记录和 EMF 记录。可以使用任一类型的记录来渲染图像，仅使用 EMF+ 记录，或仅使用 EMF 记录。当设置 EmfPlusPrefer 时，将解析 EMF+ 记录，否则仅解析 EMF 记录。默认值为 EmfOnly\"/>。

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


指定是否放大页面。如果为 true - 放大页面；如果为 false - 不放大页面。默认值为 true。

**Returns:**
布尔
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


定义是否需要导出参考线形状。默认值为 true。

**Returns:**
布尔
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


定义是否需要导出隐藏页面。默认值为 true。

**Returns:**
布尔
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


生成图像的亮度。此属性仅在保存为光栅图像格式时生效。默认值为 0.5。该值必须在 0 到 1 的范围内。

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


生成图像的颜色模式。此属性仅在保存为光栅图像格式时生效。默认值为 Aspose.Diagram.Saving.ImageColorMode。

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


生成图像的对比度。此属性仅在保存为光栅图像格式时生效。默认值为 0.5。该值必须在 0 到 1 的范围内。

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


指定在图像缩放或旋转时使用的算法。此属性仅在保存为光栅图像格式时生效。默认值为 Aspose.Diagram.Saving.InterpolationMode。

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


用于确定生成的 JPEG 图像质量的值。仅在保存为 JPEG 时生效。使用此属性可获取或设置以 JPEG 格式保存时生成图像的质量。该值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。默认值为 95。

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


保存为多页 TIFF 文件时要渲染的页数。默认值为 MaxValue，表示将渲染图表的所有页面。

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


要渲染的第一页的基于 0 的索引。默认值为 0。

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


生成图像的页面大小。可以是 [PageSize](../../com.aspose.diagram/pagesize) 或 null。默认值为 null。如果 PageSize 为 null，则生成图像的页面大小将从源图表获取。

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


指定渲染过程中像素偏移方式的值。此属性仅在保存为光栅图像格式时生效。默认值为 Aspose.Diagram.Saving.PixelOffsetMode。

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


生成图像的分辨率（每英寸点数）。此属性仅在保存为光栅图像格式时生效。默认值为 96。

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


指定保存区域是否与 PDF 相同。若为 true，则渲染区域与 PDF 相同；若为 false，则使用默认渲染区域。默认值为 false。

**Returns:**
布尔
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


指定是保存所有页面的图像还是仅保存前景。若为 true，则仅渲染前景页面（如果存在背景则包含）。若为 false，则渲染前景页面（如果存在背景则包含），随后渲染空白的背景页面。仅当 PageCount > 1 时才可能返回 true。默认值为 false。

**Returns:**
布尔
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


指定在使用此保存选项对象时渲染的图表页面将保存的格式。可以是 Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat、Aspose.Diagram.SaveFileFormat 或 Aspose.Diagram.SaveFileFormat。

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


生成图像的缩放因子。默认值为 1.0。该值必须大于 0。

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


要渲染的形状。默认计数为 0。

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


指定是否对线条、曲线以及填充区域的边缘应用平滑（抗锯齿）。此属性仅在保存为光栅图像格式时生效。默认值为 Aspose.Diagram.Saving.SmoothingMode。

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


保存生成的图像为 TIFF 格式时使用的压缩类型。仅在保存为 TIFF 时生效。默认值为 Aspose.Diagram.Saving.TiffCompression。

**Returns:**
int
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


警告回调。

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


定义是否需要导出注释。默认值为 false。

**Returns:**
布尔
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


有关此属性的描述，请参阅 [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


有关此属性的描述，请参阅 [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


有关此属性的描述，请参阅 [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


有关此属性的描述，请参阅 [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


有关此属性的描述，请参阅 [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


有关此属性的描述，请参阅 [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


有关此属性的描述，请参阅 [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


有关此属性的描述，请参阅 [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


有关此属性的描述，请参阅 [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


有关此属性的描述，请参阅 [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


有关此属性的描述，请参阅 [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


有关此属性的描述，请参阅 [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


有关此属性的描述，请参阅 [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


有关此属性的描述，请参阅 [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


有关此属性的描述，请参阅 [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


有关此属性的描述，请参阅 [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


有关此属性的描述，请参阅 [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


有关此属性的描述，请参阅 [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


有关此属性的描述，请参阅 [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


有关此属性的描述，请参阅 [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


有关此属性的描述，请参阅 [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


有关此属性的描述，请参阅 [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


有关此属性的描述，请参阅 [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


有关此属性的描述，请参阅 [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


有关此属性的描述，请参阅 [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

