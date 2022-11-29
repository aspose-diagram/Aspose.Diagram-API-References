---
title: PdfSaveOptions
second_title: Aspose.Diagram for Java API Reference
description: Allows to specify additional options when rendering diagram pages to PDF.
type: docs
weight: 281
url: /java/com.aspose.diagram/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PdfSaveOptions extends RenderingSaveOptions
```

Allows to specify additional options when rendering diagram pages to PDF.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Initializes a new instance of this class that can be used to save a document in the Aspose.Diagram.SaveFileFormat format. |
## Methods

| Method | Description |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Creates a save options object of a class suitable for the specified save format. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompliance()](#getCompliance--) | Desired conformance level for generated PDF document. |
| [getDefaultFont()](#getDefaultFont--) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Setting for rendering Emf metafile. |
| [getEncryptionDetails()](#getEncryptionDetails--) | a encryption details. |
| [getEnlargePage()](#getEnlargePage--) | Specifies whether enlarge page . |
| [getExportGuideShapes()](#getExportGuideShapes--) | Defines whether need exporting the guide shapes or not. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Defines whether need exporting the hidden page or not. |
| [getHorizontalResolution()](#getHorizontalResolution--) | the horizontal resolution for generated images, in dots per inch. |
| [getJpegQuality()](#getJpegQuality--) | Specifies the quality of JPEG compression for images (if JPEG compression is used). |
| [getPageCount()](#getPageCount--) | the number of pages to render in PDF. |
| [getPageIndex()](#getPageIndex--) | the 0-based index of the first page to render. |
| [getPageSavingCallback()](#getPageSavingCallback--) | Control/Indicate progress of page saving process. |
| [getPageSize()](#getPageSize--) | the page size for the generated images. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specifies whether all pages will be saved in image or only foreground. |
| [getSaveFormat()](#getSaveFormat--) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. |
| [getShapes()](#getShapes--) | shapes to render. |
| [getSplitMultiPages()](#getSplitMultiPages--) | Defines whether split diagram to multi pages according to page's setting. |
| [getTextCompression()](#getTextCompression--) | Specifies compression type to be used for all content streams except images. |
| [getVerticalResolution()](#getVerticalResolution--) | the vertical resolution for generated images, in dots per inch. |
| [getWarningCallback()](#getWarningCallback--) | warning callback. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Defines whether need exporting the comments or not. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompliance(int value)](#setCompliance-int-) | For the description of this property, please see [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | For the description of this property, please see [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | For the description of this property, please see [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEncryptionDetails(PdfEncryptionDetails value)](#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-) | For the description of this property, please see [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | For the description of this property, please see [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | For the description of this property, please see [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | For the description of this property, please see [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | For the description of this property, please see [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--) |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | For the description of this property, please see [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | For the description of this property, please see [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | For the description of this property, please see [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | For the description of this property, please see [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--) |
| [setPageSavingCallback(IPageSavingCallback value)](#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-) | For the description of this property, please see [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | For the description of this property, please see [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | For the description of this property, please see [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | For the description of this property, please see [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | For the description of this property, please see [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSplitMultiPages(boolean value)](#setSplitMultiPages-boolean-) | For the description of this property, please see [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--) |
| [setTextCompression(int value)](#setTextCompression-int-) | For the description of this property, please see [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--) |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | For the description of this property, please see [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
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
### getCompliance() {#getCompliance--}
```
public int getCompliance()
```


Desired conformance level for generated PDF document. Default is PdfCompliance.PDF\_15.

**Returns:**
int
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


Setting for rendering Emf metafile. EMF metafiles identified as "EMF+ Dual" can contain both EMF+ records and EMF records. Either type of record can be used to render the image, only EMF+ records, or only EMF records. When EmfRenderSetting.EMF\_PLUS\_PREFER is set, then EMF+ records will be parsed , otherwise only EMF records will be parsed. Default value is EmfRenderSetting.EMF\_ONLY.

**Returns:**
int
### getEncryptionDetails() {#getEncryptionDetails--}
```
public PdfEncryptionDetails getEncryptionDetails()
```


a encryption details. If not set, then no encryption will be performed.

**Returns:**
[PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails)
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
### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


the horizontal resolution for generated images, in dots per inch. Applies generating image method except Emf format images. The default value is 96.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


the number of pages to render in PDF. Default is MaxValue which means all pages of the diagram will be rendered.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


the 0-based index of the first page to render. Default is 0.

**Returns:**
int
### getPageSavingCallback() {#getPageSavingCallback--}
```
public IPageSavingCallback getPageSavingCallback()
```


Control/Indicate progress of page saving process.

**Returns:**
[IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback)
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


the page size for the generated images. Can be [PageSize](../../com.aspose.diagram/pagesize) or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
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


Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be Aspose.Diagram.SaveFileFormat only.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


shapes to render. Default count is 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSplitMultiPages() {#getSplitMultiPages--}
```
public boolean getSplitMultiPages()
```


Defines whether split diagram to multi pages according to page's setting. Default value is false.

**Returns:**
boolean
### getTextCompression() {#getTextCompression--}
```
public int getTextCompression()
```


Specifies compression type to be used for all content streams except images. Default is PdfTextCompression.FLATE.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


the vertical resolution for generated images, in dots per inch. Applies generating image method except Emf format image. The default value is 96.

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




### setCompliance(int value) {#setCompliance-int-}
```
public void setCompliance(int value)
```


For the description of this property, please see [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

### setEncryptionDetails(PdfEncryptionDetails value) {#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-}
```
public void setEncryptionDetails(PdfEncryptionDetails value)
```


For the description of this property, please see [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails) |  |

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


For the description of this property, please see [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int value)
```


For the description of this property, please see [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


For the description of this property, please see [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


For the description of this property, please see [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


For the description of this property, please see [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPageSavingCallback(IPageSavingCallback value) {#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-}
```
public void setPageSavingCallback(IPageSavingCallback value)
```


For the description of this property, please see [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback) |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


For the description of this property, please see [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


For the description of this property, please see [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


For the description of this property, please see [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


For the description of this property, please see [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSplitMultiPages(boolean value) {#setSplitMultiPages-boolean-}
```
public void setSplitMultiPages(boolean value)
```


For the description of this property, please see [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTextCompression(int value) {#setTextCompression-int-}
```
public void setTextCompression(int value)
```


For the description of this property, please see [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int value)
```


For the description of this property, please see [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--)

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

