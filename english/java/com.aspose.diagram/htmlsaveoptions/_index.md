---
title: HTMLSaveOptions
second_title: Aspose.Diagram for Java API Reference
description: Allows to specify additional options when rendering diagram pages to HTML.
type: docs
weight: 191
url: /java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

Allows to specify additional options when rendering diagram pages to HTML.
## Constructors

| Constructor | Description |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | Initializes a new instance of this class that can be used to save a document in the Aspose.Diagram.SaveFileFormat format. |
## Methods

| Method | Description |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Creates a save options object of a class suitable for the specified save format. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Setting for rendering Emf metafile. |
| [getEnlargePage()](#getEnlargePage--) | Specifies whether enlarge page . |
| [getExportGuideShapes()](#getExportGuideShapes--) | Defines whether need exporting the guide shapes or not. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Defines whether need exporting the hidden page or not. |
| [getPageCount()](#getPageCount--) | the number of pages to render in HTML. |
| [getPageIndex()](#getPageIndex--) | the 0-based index of the first page to render. |
| [getPageSize()](#getPageSize--) | the page size for the generated images. |
| [getResolution()](#getResolution--) | the resolution for the generated html, in dots per inch. |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | Indicates whether save the html as single file. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Specifies whether all pages will be saved in image or only foreground. |
| [getSaveFormat()](#getSaveFormat--) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. |
| [getSaveTitle()](#getSaveTitle--) | Defines whether need exporting the title or not. |
| [getSaveToolBar()](#getSaveToolBar--) | Specifies whether saving toolbar The default value is true. |
| [getShapes()](#getShapes--) | shapes to render. |
| [getStreamProvider()](#getStreamProvider--) | the IStreamProvider for exporting objects. |
| [getTitle()](#getTitle--) | the title of diagram to render in HTML. |
| [getWarningCallback()](#getWarningCallback--) | warning callback. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Defines whether need exporting the comments or not. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | For the description of this property, please see [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | For the description of this property, please see [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | For the description of this property, please see [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | For the description of this property, please see [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | For the description of this property, please see [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | For the description of this property, please see [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | For the description of this property, please see [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | For the description of this property, please see [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | For the description of this property, please see [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setResolution(int value)](#setResolution-int-) | For the description of this property, please see [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--) |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | For the description of this property, please see [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | For the description of this property, please see [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | For the description of this property, please see [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--) |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | For the description of this property, please see [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--) |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | For the description of this property, please see [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | For the description of this property, please see [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | For the description of this property, please see [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | For the description of this property, please see [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


the number of pages to render in HTML. Default is MaxValue which means all pages of the diagram will be rendered.

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
### getResolution() {#getResolution--}
```
public int getResolution()
```


the resolution for the generated html, in dots per inch. This property has effect only when saving to html. The default value is 96.

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


Indicates whether save the html as single file. The default value is false. If there are multiple pages,those pages and other resources need to be saved into separate files. For some scenarios, user maybe need to get only one resultant file such as for the convenience of transferring. If so, user may set this property as true.

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


Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be Aspose.Diagram.SaveFileFormat only.

**Returns:**
int
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


Defines whether need exporting the title or not. Default value is true.

**Returns:**
boolean
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


Specifies whether saving toolbar The default value is true.

**Returns:**
boolean
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


shapes to render. Default count is 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


the IStreamProvider for exporting objects.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


the title of diagram to render in HTML. If Title is null Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties) will be used as Title. If Diagram.DocumentProperties.Title is null or empty the file name of Diagram will be used as Title.

**Returns:**
java.lang.String
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


For the description of this property, please see [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


For the description of this property, please see [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


For the description of this property, please see [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--)

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

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


For the description of this property, please see [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


For the description of this property, please see [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


For the description of this property, please see [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


For the description of this property, please see [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


For the description of this property, please see [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


For the description of this property, please see [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--)

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

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


For the description of this property, please see [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


For the description of this property, please see [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

