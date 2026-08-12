---
title: "HTMLSaveOptions"
linktitle: "HTMLSaveOptions"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Allows to specify additional options when rendering diagram pages to HTML."
type: docs
weight: 1110
url: /nodejs/aspose.diagram/htmlsaveoptions/
---

## HTMLSaveOptions class

Allows to specify additional options when rendering diagram pages to HTML.

```js
new HTMLSaveOptions()
```

Initializes a new instance of this class that can be used to save a document in the SaveFileFormat format.

## Methods

| Name | Description |
| --- | --- |
| [getBookmark()](#getbookmark) |  |
| [getDefaultFont()](#getdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [getEmfRenderSetting()](#getemfrendersetting) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [getEnlargePage()](#getenlargepage) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [getExportGuideShapes()](#getexportguideshapes) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [getExportHiddenPage()](#getexporthiddenpage) | Defines whether need exporting the hidden page or not. Default value is true. |
| [getPageCount()](#getpagecount) | Gets or sets the number of pages to render in HTML. Default is MaxValue which means all pages of the diagram will be ren |
| [getPageIndex()](#getpageindex) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [getPageSize()](#getpagesize) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [getResolution()](#getresolution) | Gets or sets the resolution for the generated html, in dots per inch. This property has effect only when saving to html. |
| [getSaveAsSingleFile()](#getsaveassinglefile) | Indicates whether save the html as single file. The default value is false. If there are multiple pages,those pages and  |
| [getSaveForegroundPagesOnly()](#getsaveforegroundpagesonly) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [getSaveFormat()](#getsaveformat) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [getSaveTitle()](#getsavetitle) | Defines whether need exporting the title or not. Default value is true. |
| [getSaveToolBar()](#getsavetoolbar) | Specifies whether saving toolbar The default value is true. |
| [getShapes()](#getshapes) | Gets or sets shapes to render. Default count is 0. |
| [getStreamProvider()](#getstreamprovider) | Gets or sets the IStreamProvider for exporting objects. |
| [getTitle()](#gettitle) | Gets or sets the title of diagram to render in HTML. If Title is null Diagram.DocumentProperties.Title DocumentPropertie |
| [getWarningCallback()](#getwarningcallback) | Gets or sets warning callback. |
| [isExportComments()](#isexportcomments) | Defines whether need exporting the comments or not. Default value is false. |
| [setBookmark()](#setbookmark) |  |
| [setDefaultFont()](#setdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [setEmfRenderSetting()](#setemfrendersetting) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [setEnlargePage()](#setenlargepage) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [setExportComments()](#setexportcomments) | Defines whether need exporting the comments or not. Default value is false. |
| [setExportGuideShapes()](#setexportguideshapes) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [setExportHiddenPage()](#setexporthiddenpage) | Defines whether need exporting the hidden page or not. Default value is true. |
| [setPageCount()](#setpagecount) | Gets or sets the number of pages to render in HTML. Default is MaxValue which means all pages of the diagram will be ren |
| [setPageIndex()](#setpageindex) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [setPageSize()](#setpagesize) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [setResolution()](#setresolution) | Gets or sets the resolution for the generated html, in dots per inch. This property has effect only when saving to html. |
| [setSaveAsSingleFile()](#setsaveassinglefile) | Indicates whether save the html as single file. The default value is false. If there are multiple pages,those pages and  |
| [setSaveForegroundPagesOnly()](#setsaveforegroundpagesonly) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [setSaveFormat()](#setsaveformat) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [setSaveTitle()](#setsavetitle) | Defines whether need exporting the title or not. Default value is true. |
| [setSaveToolBar()](#setsavetoolbar) | Specifies whether saving toolbar The default value is true. |
| [setShapes()](#setshapes) | Gets or sets shapes to render. Default count is 0. |
| [setStreamProvider()](#setstreamprovider) | Gets or sets the IStreamProvider for exporting objects. |
| [setTitle()](#settitle) | Gets or sets the title of diagram to render in HTML. If Title is null Diagram.DocumentProperties.Title DocumentPropertie |
| [setWarningCallback()](#setwarningcallback) | Gets or sets warning callback. |

### getBookmark() {#getbookmark}

### getDefaultFont() {#getdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### getEmfRenderSetting() {#getemfrendersetting}

Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identified as "EMF+ Dual" can contain both EMF+ records and EMF records. Either type of record can be used to render the image, only EMF+ records, or only EMF records. When EmfPlusPrefer is set, then EMF+ records will be parsed , otherwise only EMF records will be parsed. Default value is EmfOnly"/>.

### getEnlargePage() {#getenlargepage}

Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true.

### getExportGuideShapes() {#getexportguideshapes}

Defines whether need exporting the guide shapes or not. Default value is true.

### getExportHiddenPage() {#getexporthiddenpage}

Defines whether need exporting the hidden page or not. Default value is true.

### getPageCount() {#getpagecount}

Gets or sets the number of pages to render in HTML. Default is MaxValue which means all pages of the diagram will be rendered.

### getPageIndex() {#getpageindex}

Gets or sets the 0-based index of the first page to render. Default is 0.

### getPageSize() {#getpagesize}

Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

### getResolution() {#getresolution}

Gets or sets the resolution for the generated html, in dots per inch. This property has effect only when saving to html. The default value is 96.

### getSaveAsSingleFile() {#getsaveassinglefile}

Indicates whether save the html as single file. The default value is false. If there are multiple pages,those pages and other resources need to be saved into separate files. For some scenarios, user maybe need to get only one resultant file such as for the convenience of transferring. If so, user may set this property as true.

### getSaveForegroundPagesOnly() {#getsaveforegroundpagesonly}

Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with background if present). If false - rendered foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### getSaveFormat() {#getsaveformat}

Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveFileFormat only. The value of the property is SaveFileFormat integer constant.

### getSaveTitle() {#getsavetitle}

Defines whether need exporting the title or not. Default value is true.

### getSaveToolBar() {#getsavetoolbar}

Specifies whether saving toolbar The default value is true.

### getShapes() {#getshapes}

Gets or sets shapes to render. Default count is 0.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("LoadSaveConvert.vsdx");
// create an instance SVG save options class
options = new aspose.diagram.SVGSaveOptions();
shapes = options.getShapes();
// get shapes by page index and shape ID, and then add in the shape collection object
shapes.add(diagram.getPages().get(0).getShapes().getShape(1));
shapes.add(diagram.getPages().get(0).getShapes().getShape(2));
// save Visio drawing
diagram.save("out-SelectiveShapes_out.svg", options);
```

### getStreamProvider() {#getstreamprovider}

Gets or sets the IStreamProvider for exporting objects.

### getTitle() {#gettitle}

Gets or sets the title of diagram to render in HTML. If Title is null Diagram.DocumentProperties.Title DocumentProperties will be used as Title. If Diagram.DocumentProperties.Title is null or empty the file name of Diagram will be used as Title.

### getWarningCallback() {#getwarningcallback}

Gets or sets warning callback.

### isExportComments() {#isexportcomments}

Defines whether need exporting the comments or not. Default value is false.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Pages.vsdx");
// get a particular page
page = diagram.getPages().getPage("Flow 2");
// set Visio page visiblity
page.getPageSheet().getPageProps().getUIVisibility().setValue(aspose.diagram.BOOL.TRUE);
// initialize Image save options
options = new aspose.diagram.ImageSaveOptions(aspose.diagram.SaveFileFormat.JPEG);
// set export option of hidden Visio pages
options.setExportHiddenPage(false);
// set export option of comments
options.setExportComments(false);
diagram.save("out-ExportOfHiddenVisioPagesToImage.jpeg", options);
```

### setBookmark() {#setbookmark}

### setDefaultFont() {#setdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### setEmfRenderSetting() {#setemfrendersetting}

Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identified as "EMF+ Dual" can contain both EMF+ records and EMF records. Either type of record can be used to render the image, only EMF+ records, or only EMF records. When EmfPlusPrefer is set, then EMF+ records will be parsed , otherwise only EMF records will be parsed. Default value is EmfOnly"/>.

### setEnlargePage() {#setenlargepage}

Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true.

### setExportComments() {#setexportcomments}

Defines whether need exporting the comments or not. Default value is false.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Pages.vsdx");
// get a particular page
page = diagram.getPages().getPage("Flow 2");
// set Visio page visiblity
page.getPageSheet().getPageProps().getUIVisibility().setValue(aspose.diagram.BOOL.TRUE);
// initialize Image save options
options = new aspose.diagram.ImageSaveOptions(aspose.diagram.SaveFileFormat.JPEG);
// set export option of hidden Visio pages
options.setExportHiddenPage(false);
// set export option of comments
options.setExportComments(false);
diagram.save("out-ExportOfHiddenVisioPagesToImage.jpeg", options);
```

### setExportGuideShapes() {#setexportguideshapes}

Defines whether need exporting the guide shapes or not. Default value is true.

### setExportHiddenPage() {#setexporthiddenpage}

Defines whether need exporting the hidden page or not. Default value is true.

### setPageCount() {#setpagecount}

Gets or sets the number of pages to render in HTML. Default is MaxValue which means all pages of the diagram will be rendered.

### setPageIndex() {#setpageindex}

Gets or sets the 0-based index of the first page to render. Default is 0.

### setPageSize() {#setpagesize}

Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

### setResolution() {#setresolution}

Gets or sets the resolution for the generated html, in dots per inch. This property has effect only when saving to html. The default value is 96.

### setSaveAsSingleFile() {#setsaveassinglefile}

Indicates whether save the html as single file. The default value is false. If there are multiple pages,those pages and other resources need to be saved into separate files. For some scenarios, user maybe need to get only one resultant file such as for the convenience of transferring. If so, user may set this property as true.

### setSaveForegroundPagesOnly() {#setsaveforegroundpagesonly}

Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with background if present). If false - rendered foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### setSaveFormat() {#setsaveformat}

Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveFileFormat only. The value of the property is SaveFileFormat integer constant.

### setSaveTitle() {#setsavetitle}

Defines whether need exporting the title or not. Default value is true.

### setSaveToolBar() {#setsavetoolbar}

Specifies whether saving toolbar The default value is true.

### setShapes() {#setshapes}

Gets or sets shapes to render. Default count is 0.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("LoadSaveConvert.vsdx");
// create an instance SVG save options class
options = new aspose.diagram.SVGSaveOptions();
shapes = options.getShapes();
// get shapes by page index and shape ID, and then add in the shape collection object
shapes.add(diagram.getPages().get(0).getShapes().getShape(1));
shapes.add(diagram.getPages().get(0).getShapes().getShape(2));
// save Visio drawing
diagram.save("out-SelectiveShapes_out.svg", options);
```

### setStreamProvider() {#setstreamprovider}

Gets or sets the IStreamProvider for exporting objects.

### setTitle() {#settitle}

Gets or sets the title of diagram to render in HTML. If Title is null Diagram.DocumentProperties.Title DocumentProperties will be used as Title. If Diagram.DocumentProperties.Title is null or empty the file name of Diagram will be used as Title.

### setWarningCallback() {#setwarningcallback}

Gets or sets warning callback.
