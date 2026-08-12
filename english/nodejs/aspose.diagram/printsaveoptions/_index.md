---
title: "PrintSaveOptions"
linktitle: "PrintSaveOptions"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Allows to specify additional options when printing diagram."
type: docs
weight: 1910
url: /nodejs/aspose.diagram/printsaveoptions/
---

## PrintSaveOptions class

Allows to specify additional options when printing diagram.

```js
new PrintSaveOptions()
```

Initializes a new instance of this class

## Methods

| Name | Description |
| --- | --- |
| [getBookmark()](#getbookmark) |  |
| [getDefaultFont()](#getdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [getEmfRenderSetting()](#getemfrendersetting) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [getEnlargePage()](#getenlargepage) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [getExportGuideShapes()](#getexportguideshapes) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [getPageCount()](#getpagecount) | Gets or sets the number of pages to render when saving to a multipage file. Default is MaxValue which means all pages of |
| [getPageSize()](#getpagesize) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [getSaveForegroundPagesOnly()](#getsaveforegroundpagesonly) | Specifies whether all pages will be printed or only foreground. If true - printed only foreground pages(with background  |
| [getSaveFormat()](#getsaveformat) | Specifies the format in which the document will be saved if this save options object is used. The value of the property  |
| [getShapes()](#getshapes) | Gets or sets shapes to render. Default count is 0. |
| [getWarningCallback()](#getwarningcallback) | Gets or sets warning callback. |
| [isExportComments()](#isexportcomments) | Defines whether need exporting the comments or not. Default value is false. |
| [setBookmark()](#setbookmark) |  |
| [setDefaultFont()](#setdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [setEmfRenderSetting()](#setemfrendersetting) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [setEnlargePage()](#setenlargepage) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [setExportComments()](#setexportcomments) | Defines whether need exporting the comments or not. Default value is false. |
| [setExportGuideShapes()](#setexportguideshapes) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [setPageCount()](#setpagecount) | Gets or sets the number of pages to render when saving to a multipage file. Default is MaxValue which means all pages of |
| [setPageSize()](#setpagesize) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [setSaveForegroundPagesOnly()](#setsaveforegroundpagesonly) | Specifies whether all pages will be printed or only foreground. If true - printed only foreground pages(with background  |
| [setSaveFormat()](#setsaveformat) | Specifies the format in which the document will be saved if this save options object is used. The value of the property  |
| [setShapes()](#setshapes) | Gets or sets shapes to render. Default count is 0. |
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

### getPageCount() {#getpagecount}

Gets or sets the number of pages to render when saving to a multipage file. Default is MaxValue which means all pages of the diagram will be printed.

### getPageSize() {#getpagesize}

Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

### getSaveForegroundPagesOnly() {#getsaveforegroundpagesonly}

Specifies whether all pages will be printed or only foreground. If true - printed only foreground pages(with background if present). If false - printed foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### getSaveFormat() {#getsaveformat}

Specifies the format in which the document will be saved if this save options object is used. The value of the property is SaveFileFormat integer constant.

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

### setPageCount() {#setpagecount}

Gets or sets the number of pages to render when saving to a multipage file. Default is MaxValue which means all pages of the diagram will be printed.

### setPageSize() {#setpagesize}

Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

### setSaveForegroundPagesOnly() {#setsaveforegroundpagesonly}

Specifies whether all pages will be printed or only foreground. If true - printed only foreground pages(with background if present). If false - printed foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### setSaveFormat() {#setsaveformat}

Specifies the format in which the document will be saved if this save options object is used. The value of the property is SaveFileFormat integer constant.

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

### setWarningCallback() {#setwarningcallback}

Gets or sets warning callback.
