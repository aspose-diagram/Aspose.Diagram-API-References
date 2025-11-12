---
title: SVGSaveOptions
second_title: Aspose.Diagram for Java API Reference
description: Allows to specify additional options when rendering diagram pages to SVG.
type: docs
weight: 357
url: /java/com.aspose.diagram/svgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class SVGSaveOptions extends RenderingSaveOptions
```

Allows to specify additional options when rendering diagram pages to SVG.
## Constructors

| Constructor | Description |
| --- | --- |
| [SVGSaveOptions()](#SVGSaveOptions--) | Initializes a new instance of this class that can be used to save a document in the Aspose.Diagram.SaveFileFormat format. |
## Methods

| Method | Description |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Creates a save options object of a class suitable for the specified save format. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomImagePath()](#getCustomImagePath--) | The user custom path(URL) saved in generated svg file for the image. |
| [getDefaultFont()](#getDefaultFont--) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Setting for rendering Emf metafile. |
| [getEnlargePage()](#getEnlargePage--) | Specifies whether enlarge page . |
| [getExportElementAsRectTag()](#getExportElementAsRectTag--) | Defines whether need exporting rectangle elements as rect tag or not. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Defines whether need exporting the guide shapes or not. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Defines whether need exporting the hidden page or not. |
| [getPageIndex()](#getPageIndex--) | the 0-based index of the page to render. |
| [getPageSize()](#getPageSize--) | the page size for the generated images. |
| [getQuality()](#getQuality--) | a value determining the quality of the generated images to apply only when saving pages to the Jpeg format. |
| [getSVGFitToViewPort()](#getSVGFitToViewPort--) | if this property is true, the generated svg will fit to view port. |
| [getSaveFormat()](#getSaveFormat--) | Specifies the format in which the document will be saved if this save options object is used. |
| [getShapes()](#getShapes--) | shapes to render. |
| [getWarningCallback()](#getWarningCallback--) | warning callback. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Defines whether need exporting the comments or not. |
| [isExportScaleInMatrix()](#isExportScaleInMatrix--) | Defines whether need export scale in matrix or not. |
| [isSavingCustomLinePattern()](#isSavingCustomLinePattern--) | Defines whether Saving custom line pattern. |
| [isSavingImageSeparately()](#isSavingImageSeparately--) | Defines whether Saving Image Separately. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomImagePath(String value)](#setCustomImagePath-java.lang.String-) | For the description of this property, please see [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | For the description of this property, please see [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | For the description of this property, please see [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | For the description of this property, please see [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | For the description of this property, please see [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportElementAsRectTag(boolean value)](#setExportElementAsRectTag-boolean-) | For the description of this property, please see [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | For the description of this property, please see [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | For the description of this property, please see [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--) |
| [setExportScaleInMatrix(boolean value)](#setExportScaleInMatrix-boolean-) | For the description of this property, please see [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--) |
| [setPageIndex(int value)](#setPageIndex-int-) | For the description of this property, please see [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | For the description of this property, please see [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setQuality(int value)](#setQuality-int-) | For the description of this property, please see [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--) |
| [setSVGFitToViewPort(boolean value)](#setSVGFitToViewPort-boolean-) | For the description of this property, please see [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | For the description of this property, please see [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setSavingCustomLinePattern(boolean value)](#setSavingCustomLinePattern-boolean-) | For the description of this property, please see [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--) |
| [setSavingImageSeparately(boolean value)](#setSavingImageSeparately-boolean-) | For the description of this property, please see [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | For the description of this property, please see [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SVGSaveOptions() {#SVGSaveOptions--}
```
public SVGSaveOptions()
```


Initializes a new instance of this class that can be used to save a document in the Aspose.Diagram.SaveFileFormat format.

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Creates a save options object of a class suitable for the specified save format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveFormat | int | The Aspose.Diagram.SaveFileFormat for which to create a save options object. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


The user custom path(URL) saved in generated svg file for the image. If not defined by user, Current directory will be used.

**Returns:**
java.lang.String
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

**Returns:**
java.lang.String
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Setting for rendering Emf metafile. EMF metafiles identified as "EMF+ Dual" can contain both EMF+ records and EMF records. Either type of record can be used to render the image, only EMF+ records, or only EMF records. When EmfPlusPrefer is set, then EMF+ records will be parsed , otherwise only EMF records will be parsed. Default value is EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true.

**Returns:**
boolean
### getExportElementAsRectTag() {#getExportElementAsRectTag--}
```
public boolean getExportElementAsRectTag()
```


Defines whether need exporting rectangle elements as rect tag or not. Default value is false.

**Returns:**
boolean
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


Defines whether need exporting the guide shapes or not. Default value is true.

**Returns:**
boolean
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Defines whether need exporting the hidden page or not. Default value is true.

**Returns:**
boolean
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


the 0-based index of the page to render. Default is 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


the page size for the generated images. Can be [PageSize](../../com.aspose.diagram/pagesize) or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getQuality() {#getQuality--}
```
public int getQuality()
```


a value determining the quality of the generated images to apply only when saving pages to the Jpeg format. The default value is 100 Has effect only when saving to JPEG. The value must be between 0 and 100. The default value is 100.

**Returns:**
int
### getSVGFitToViewPort() {#getSVGFitToViewPort--}
```
public boolean getSVGFitToViewPort()
```


if this property is true, the generated svg will fit to view port.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Specifies the format in which the document will be saved if this save options object is used.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


shapes to render. Default count is 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


warning callback.

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


Defines whether need exporting the comments or not. Default value is false.

**Returns:**
boolean
### isExportScaleInMatrix() {#isExportScaleInMatrix--}
```
public boolean isExportScaleInMatrix()
```


Defines whether need export scale in matrix or not. Default value is true.

**Returns:**
boolean
### isSavingCustomLinePattern() {#isSavingCustomLinePattern--}
```
public boolean isSavingCustomLinePattern()
```


Defines whether Saving custom line pattern.

**Returns:**
boolean
### isSavingImageSeparately() {#isSavingImageSeparately--}
```
public boolean isSavingImageSeparately()
```


Defines whether Saving Image Separately.

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


For the description of this property, please see [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


For the description of this property, please see [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


For the description of this property, please see [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


For the description of this property, please see [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


For the description of this property, please see [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setExportElementAsRectTag(boolean value) {#setExportElementAsRectTag-boolean-}
```
public void setExportElementAsRectTag(boolean value)
```


For the description of this property, please see [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


For the description of this property, please see [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


For the description of this property, please see [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setExportScaleInMatrix(boolean value) {#setExportScaleInMatrix-boolean-}
```
public void setExportScaleInMatrix(boolean value)
```


For the description of this property, please see [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


For the description of this property, please see [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


For the description of this property, please see [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


For the description of this property, please see [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSVGFitToViewPort(boolean value) {#setSVGFitToViewPort-boolean-}
```
public void setSVGFitToViewPort(boolean value)
```


For the description of this property, please see [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


For the description of this property, please see [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSavingCustomLinePattern(boolean value) {#setSavingCustomLinePattern-boolean-}
```
public void setSavingCustomLinePattern(boolean value)
```


For the description of this property, please see [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSavingImageSeparately(boolean value) {#setSavingImageSeparately-boolean-}
```
public void setSavingImageSeparately(boolean value)
```


For the description of this property, please see [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


For the description of this property, please see [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

