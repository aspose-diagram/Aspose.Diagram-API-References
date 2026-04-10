---
title: SVGSaveOptions
second_title: Aspose.Diagram for Java API 参考
description: 允许在将图表页面渲染为 SVG 时指定其他选项。
type: docs
weight: 347
url: /zh/java/com.aspose.diagram/svgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class SVGSaveOptions extends RenderingSaveOptions
```

允许在将图表页面渲染为 SVG 时指定其他选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SVGSaveOptions()](#SVGSaveOptions--) | 初始化此类的新实例，可用于将文档保存为 Aspose.Diagram.SaveFileFormat 格式。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 创建一个适用于指定保存格式的类的保存选项对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomImagePath()](#getCustomImagePath--) | 用户自定义路径（URL），保存在生成的 SVG 文件中用于图像。 |
| [getDefaultFont()](#getDefaultFont--) | 当图表中的字符是 Unicode 且未设置正确的字体值或本地未安装该字体时，它们可能在 PDF、图像或 XPS 中显示为方块。 |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | 用于渲染 Emf 元文件的设置。 |
| [getEnlargePage()](#getEnlargePage--) | 指定是否放大页面。 |
| [getExportElementAsRectTag()](#getExportElementAsRectTag--) | 定义是否需要将矩形元素导出为 rect 标记。 |
| [getExportGuideShapes()](#getExportGuideShapes--) | 定义是否需要导出参考线形状。 |
| [getExportHiddenPage()](#getExportHiddenPage--) | 定义是否需要导出隐藏页面。 |
| [getPageIndex()](#getPageIndex--) | 要渲染的页面的从 0 开始的索引。 |
| [getPageSize()](#getPageSize--) | 生成图像的页面尺寸。 |
| [getQuality()](#getQuality--) | 一个值，用于确定生成图像的质量，仅在将页面保存为 JPEG 格式时应用。 |
| [getSVGFitToViewPort()](#getSVGFitToViewPort--) | 如果此属性为 true，生成的 SVG 将适应视口。 |
| [getSaveFormat()](#getSaveFormat--) | 指定在使用此保存选项对象时文档将被保存的格式。 |
| [getShapes()](#getShapes--) | 要渲染的形状。 |
| [getWarningCallback()](#getWarningCallback--) | 警告回调。 |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | 定义是否需要导出注释。 |
| [isExportScaleInMatrix()](#isExportScaleInMatrix--) | 定义是否需要以矩阵形式导出比例。 |
| [isSavingCustomLinePattern()](#isSavingCustomLinePattern--) | 定义是否保存自定义线型模式。 |
| [isSavingImageSeparately()](#isSavingImageSeparately--) | 定义是否单独保存图像。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomImagePath(String value)](#setCustomImagePath-java.lang.String-) | 有关此属性的描述，请参阅 [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | 有关此属性的描述，请参阅 [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | 有关此属性的描述，请参阅 [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | 有关此属性的描述，请参阅 [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | 有关此属性的描述，请参阅 [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportElementAsRectTag(boolean value)](#setExportElementAsRectTag-boolean-) | 有关此属性的描述，请参阅 [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | 有关此属性的描述，请参阅 [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | 有关此属性的描述，请参阅 [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--) |
| [setExportScaleInMatrix(boolean value)](#setExportScaleInMatrix-boolean-) | 有关此属性的描述，请参阅 [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--) |
| [setPageIndex(int value)](#setPageIndex-int-) | 有关此属性的描述，请参阅 [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | 有关此属性的描述，请参阅 [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setQuality(int value)](#setQuality-int-) | 有关此属性的描述，请参阅 [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--) |
| [setSVGFitToViewPort(boolean value)](#setSVGFitToViewPort-boolean-) | 有关此属性的描述，请参阅 [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | 有关此属性的描述，请参阅 [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setSavingCustomLinePattern(boolean value)](#setSavingCustomLinePattern-boolean-) | 有关此属性的描述，请参阅 [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--) |
| [setSavingImageSeparately(boolean value)](#setSavingImageSeparately-boolean-) | 有关此属性的描述，请参阅 [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | 有关此属性的描述，请参阅 [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SVGSaveOptions() {#SVGSaveOptions--}
```
public SVGSaveOptions()
```


初始化此类的新实例，可用于将文档保存为 Aspose.Diagram.SaveFileFormat 格式。

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
### getCustomImagePath() {#getCustomImagePath--}
```
public String getCustomImagePath()
```


用户自定义的路径（URL）已保存到生成的 SVG 文件中用于该图像。如果用户未定义，将使用当前目录。

**Returns:**
java.lang.String
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
### getExportElementAsRectTag() {#getExportElementAsRectTag--}
```
public boolean getExportElementAsRectTag()
```


定义是否需要将矩形元素导出为 rect 标记。默认值为 false。

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
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


要渲染的页面的基于 0 的索引。默认值为 0。

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


生成图像的页面大小。可以是 [PageSize](../../com.aspose.diagram/pagesize) 或 null。默认值为 null。如果 PageSize 为 null，则生成图像的页面大小将从源图表获取。

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getQuality() {#getQuality--}
```
public int getQuality()
```


用于确定生成图像质量的值，仅在将页面保存为 JPEG 格式时适用。默认值为 100，仅在保存为 JPEG 时生效。该值必须在 0 到 100 之间。默认值为 100。

**Returns:**
int
### getSVGFitToViewPort() {#getSVGFitToViewPort--}
```
public boolean getSVGFitToViewPort()
```


如果此属性为 true，生成的 SVG 将适应视口。

**Returns:**
布尔
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


指定在使用此保存选项对象时文档将被保存的格式。

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


要渲染的形状。默认计数为 0。

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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
### isExportScaleInMatrix() {#isExportScaleInMatrix--}
```
public boolean isExportScaleInMatrix()
```


定义是否需要在矩阵中导出比例。默认值为 true。

**Returns:**
布尔
### isSavingCustomLinePattern() {#isSavingCustomLinePattern--}
```
public boolean isSavingCustomLinePattern()
```


定义是否保存自定义线型模式。

**Returns:**
布尔
### isSavingImageSeparately() {#isSavingImageSeparately--}
```
public boolean isSavingImageSeparately()
```


定义是否单独保存图像。

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




### setCustomImagePath(String value) {#setCustomImagePath-java.lang.String-}
```
public void setCustomImagePath(String value)
```


有关此属性的描述，请参阅 [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

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

### setExportElementAsRectTag(boolean value) {#setExportElementAsRectTag-boolean-}
```
public void setExportElementAsRectTag(boolean value)
```


有关此属性的描述，请参阅 [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--)

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


有关此属性的描述，请参阅 [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setExportScaleInMatrix(boolean value) {#setExportScaleInMatrix-boolean-}
```
public void setExportScaleInMatrix(boolean value)
```


有关此属性的描述，请参阅 [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


有关此属性的描述，请参阅 [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--)

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


有关此属性的描述，请参阅 [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSVGFitToViewPort(boolean value) {#setSVGFitToViewPort-boolean-}
```
public void setSVGFitToViewPort(boolean value)
```


有关此属性的描述，请参阅 [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


有关此属性的描述，请参阅 [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSavingCustomLinePattern(boolean value) {#setSavingCustomLinePattern-boolean-}
```
public void setSavingCustomLinePattern(boolean value)
```


有关此属性的描述，请参阅 [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setSavingImageSeparately(boolean value) {#setSavingImageSeparately-boolean-}
```
public void setSavingImageSeparately(boolean value)
```


有关此属性的描述，请参阅 [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


有关此属性的描述，请参阅 [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

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

