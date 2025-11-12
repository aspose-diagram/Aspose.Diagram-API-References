---
title: ImageSaveOptions
second_title: Aspose.Diagram for Java API Reference
description: Allows to specify additional options when rendering diagram pages to images.
type: docs
weight: 204
url: /java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

Allows to specify additional options when rendering diagram pages to images.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | Initializes a new instance of this class that can be used to save rendered images in the Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat or Aspose.Diagram.SaveFileFormat format. |
## Methods

| Method | Description |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Creates a save options object of a class suitable for the specified save format. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | Specifies the quality level to use during compositing. |
| [getContentZoom()](#getContentZoom--) | This parameter is similar with scale, but not effect the generated image size. |
| [getDefaultFont()](#getDefaultFont--) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Setting for rendering Emf metafile. |
| [getEnlargePage()](#getEnlargePage--) | Specifies whether enlarge page . |
| [getExportGuideShapes()](#getExportGuideShapes--) | Defines whether need exporting the guide shapes or not. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Defines whether need exporting the hidden page or not. |
| [getImageBrightness()](#getImageBrightness--) | the brightness for the the generated images. |
| [getImageColorMode()](#getImageColorMode--) | the color mode for the generated images. |
| [getImageContrast()](#getImageContrast--) | the contrast for the generated images. |
| [getInterpolationMode()](#getInterpolationMode--) | Specifies the algorithm that is used when images are scaled or rotated. |
| [getJpegQuality()](#getJpegQuality--) | a value determining the quality of the generated JPEG images. |
| [getPageCount()](#getPageCount--) | the number of pages to render when saving to a multipage TIFF file. |
| [getPageIndex()](#getPageIndex--) | the 0-based index of the first page to render. |
| [getPageSize()](#getPageSize--) | the page size for the generated images. |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | a value specifying how pixels are offset during rendering. |
| [getResolution()](#getResolution--) | the resolution for the generated images, in dots per inch. |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | Specifies whether saving area same as pdf . |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specifies whether all pages will be saved in image or only foreground. |
| [getSaveFormat()](#getSaveFormat--) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. |
| [getScale()](#getScale--) | the zoom factor for the generated images. |
| [getShapes()](#getShapes--) | shapes to render. |
| [getSmoothingMode()](#getSmoothingMode--) | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. |
| [getTiffCompression()](#getTiffCompression--) | the type of compression to apply when saving generated images to the TIFF format. |
| [getWarningCallback()](#getWarningCallback--) | warning callback. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Defines whether need exporting the comments or not. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | For the description of this property, please see [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) |
| [setContentZoom(float value)](#setContentZoom-float-) | For the description of this property, please see [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | For the description of this property, please see [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | For the description of this property, please see [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | For the description of this property, please see [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | For the description of this property, please see [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | For the description of this property, please see [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | For the description of this property, please see [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) |
| [setImageBrightness(float value)](#setImageBrightness-float-) | For the description of this property, please see [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) |
| [setImageColorMode(int value)](#setImageColorMode-int-) | For the description of this property, please see [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) |
| [setImageContrast(float value)](#setImageContrast-float-) | For the description of this property, please see [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | For the description of this property, please see [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | For the description of this property, please see [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | For the description of this property, please see [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | For the description of this property, please see [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | For the description of this property, please see [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | For the description of this property, please see [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) |
| [setResolution(float value)](#setResolution-float-) | For the description of this property, please see [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | For the description of this property, please see [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | For the description of this property, please see [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | For the description of this property, please see [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) |
| [setScale(float value)](#setScale-float-) | For the description of this property, please see [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | For the description of this property, please see [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | For the description of this property, please see [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) |
| [setTiffCompression(int value)](#setTiffCompression-int-) | For the description of this property, please see [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


Initializes a new instance of this class that can be used to save rendered images in the Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat or Aspose.Diagram.SaveFileFormat format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveFormat | int | Can be Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat or Aspose.Diagram.SaveFileFormat. |

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
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Specifies the quality level to use during compositing. This property has effect only when saving to raster image formats. The default value is Aspose.Diagram.Saving.CompositingQuality.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


This parameter is similar with scale, but not effect the generated image size. The default value is 1.0. The value must be greater than 0.

**Returns:**
float
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
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


the brightness for the the generated images. This property has effect only when saving to raster image formats. The default value is 0.5. The value must be in the range between 0 and 1.

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


the color mode for the generated images. This property has effect only when saving to raster image formats. The default value is Aspose.Diagram.Saving.ImageColorMode.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


the contrast for the generated images. This property has effect only when saving to raster image formats. The default value is 0.5. The value must be in the range between 0 and 1.

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Specifies the algorithm that is used when images are scaled or rotated. This property has effect only when saving to raster image formats. The default value is Aspose.Diagram.Saving.InterpolationMode.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


a value determining the quality of the generated JPEG images. Has effect only when saving to JPEG. Use this property to get or set the quality of generated images when saving in JPEG format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


the number of pages to render when saving to a multipage TIFF file. Default is MaxValue which means all pages of the diagram will be rendered.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


the 0-based index of the first page to render. Default is 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


the page size for the generated images. Can be [PageSize](../../com.aspose.diagram/pagesize) or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


a value specifying how pixels are offset during rendering. This property has effect only when saving to raster image formats. The default value is Aspose.Diagram.Saving.PixelOffsetMode.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


the resolution for the generated images, in dots per inch. This property has effect only when saving to raster image formats. The default value is 96.

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


Specifies whether saving area same as pdf . If true - rendered area same as pdf. If false - rendered area default. The default value is false.

**Returns:**
boolean
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with background if present). If false - rendered foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat or Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


the zoom factor for the generated images. The default value is 1.0. The value must be greater than 0.

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


shapes to render. Default count is 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. This property has effect only when saving to raster image formats. The default value is Aspose.Diagram.Saving.SmoothingMode.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


the type of compression to apply when saving generated images to the TIFF format. Has effect only when saving to TIFF. The default value is Aspose.Diagram.Saving.TiffCompression.

**Returns:**
int
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


For the description of this property, please see [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


For the description of this property, please see [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

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


For the description of this property, please see [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


For the description of this property, please see [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


For the description of this property, please see [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


For the description of this property, please see [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


For the description of this property, please see [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


For the description of this property, please see [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


For the description of this property, please see [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


For the description of this property, please see [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)

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

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


For the description of this property, please see [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


For the description of this property, please see [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


For the description of this property, please see [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


For the description of this property, please see [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


For the description of this property, please see [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


For the description of this property, please see [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


For the description of this property, please see [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


For the description of this property, please see [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


For the description of this property, please see [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

