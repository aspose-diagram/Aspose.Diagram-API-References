---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Allows to specify additional options when rendering diagram pages to PDF."
type: docs
weight: 1800
url: /nodejs/aspose.diagram/pdfsaveoptions/
---

## PdfSaveOptions class

Allows to specify additional options when rendering diagram pages to PDF.

```js
new PdfSaveOptions()
```

Initializes a new instance of this class that can be used to save a document in the SaveFileFormat format.

## Methods

| Name | Description |
| --- | --- |
| [getBookmark()](#getbookmark) | Gets and sets the PdfBookmarkEntry object. |
| [getCompliance()](#getcompliance) | Desired conformance level for generated PDF document. Default is PdfCompliance.PDF_15. The value of the property is PdfC |
| [getDefaultFont()](#getdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [getEmfRenderSetting()](#getemfrendersetting) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [getEncryptionDetails()](#getencryptiondetails) | Gets or sets a encryption details. If not set, then no encryption will be performed. |
| [getEnlargePage()](#getenlargepage) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [getExportGuideShapes()](#getexportguideshapes) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [getExportHiddenPage()](#getexporthiddenpage) | Defines whether need exporting the hidden page or not. Default value is true. |
| [getHorizontalResolution()](#gethorizontalresolution) | Gets or sets the horizontal resolution for generated images, in dots per inch. Applies generating image method except Em |
| [getJpegQuality()](#getjpegquality) | Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageCount()](#getpagecount) | Gets or sets the number of pages to render in PDF. Default is MaxValue which means all pages of the diagram will be rend |
| [getPageIndex()](#getpageindex) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [getPageSavingCallback()](#getpagesavingcallback) | Control/Indicate progress of page saving process. |
| [getPageSize()](#getpagesize) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [getSaveForegroundPagesOnly()](#getsaveforegroundpagesonly) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [getSaveFormat()](#getsaveformat) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [getShapes()](#getshapes) | Gets or sets shapes to render. Default count is 0. |
| [getSplitMultiPages()](#getsplitmultipages) | Defines whether split diagram to multi pages according to page's setting. Default value is false. |
| [getTextCompression()](#gettextcompression) | Specifies compression type to be used for all content streams except images. Default is PdfTextCompression.FLATE. The va |
| [getVerticalResolution()](#getverticalresolution) | Gets or sets the vertical resolution for generated images, in dots per inch. Applies generating image method except Emf  |
| [getWarningCallback()](#getwarningcallback) | Gets or sets warning callback. |
| [isExportComments()](#isexportcomments) | Defines whether need exporting the comments or not. Default value is false. |
| [setBookmark()](#setbookmark) | Gets and sets the PdfBookmarkEntry object. |
| [setCompliance()](#setcompliance) | Desired conformance level for generated PDF document. Default is PdfCompliance.PDF_15. The value of the property is PdfC |
| [setDefaultFont()](#setdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [setEmfRenderSetting()](#setemfrendersetting) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [setEncryptionDetails()](#setencryptiondetails) | Gets or sets a encryption details. If not set, then no encryption will be performed. |
| [setEnlargePage()](#setenlargepage) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [setExportComments()](#setexportcomments) | Defines whether need exporting the comments or not. Default value is false. |
| [setExportGuideShapes()](#setexportguideshapes) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [setExportHiddenPage()](#setexporthiddenpage) | Defines whether need exporting the hidden page or not. Default value is true. |
| [setHorizontalResolution()](#sethorizontalresolution) | Gets or sets the horizontal resolution for generated images, in dots per inch. Applies generating image method except Em |
| [setJpegQuality()](#setjpegquality) | Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [setPageCount()](#setpagecount) | Gets or sets the number of pages to render in PDF. Default is MaxValue which means all pages of the diagram will be rend |
| [setPageIndex()](#setpageindex) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [setPageSavingCallback()](#setpagesavingcallback) | Control/Indicate progress of page saving process. |
| [setPageSize()](#setpagesize) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [setSaveForegroundPagesOnly()](#setsaveforegroundpagesonly) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [setSaveFormat()](#setsaveformat) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [setShapes()](#setshapes) | Gets or sets shapes to render. Default count is 0. |
| [setSplitMultiPages()](#setsplitmultipages) | Defines whether split diagram to multi pages according to page's setting. Default value is false. |
| [setTextCompression()](#settextcompression) | Specifies compression type to be used for all content streams except images. Default is PdfTextCompression.FLATE. The va |
| [setVerticalResolution()](#setverticalresolution) | Gets or sets the vertical resolution for generated images, in dots per inch. Applies generating image method except Emf  |
| [setWarningCallback()](#setwarningcallback) | Gets or sets warning callback. |

### getBookmark() {#getbookmark}

Gets and sets the PdfBookmarkEntry object.

### getCompliance() {#getcompliance}

Desired conformance level for generated PDF document. Default is PdfCompliance.PDF_15. The value of the property is PdfCompliance integer constant.

### getDefaultFont() {#getdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### getEmfRenderSetting() {#getemfrendersetting}

Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identified as "EMF+ Dual" can contain both EMF+ records and EMF records. Either type of record can be used to render the image, only EMF+ records, or only EMF records. When EmfPlusPrefer is set, then EMF+ records will be parsed , otherwise only EMF records will be parsed. Default value is EmfOnly"/>.

### getEncryptionDetails() {#getencryptiondetails}

Gets or sets a encryption details. If not set, then no encryption will be performed.

### getEnlargePage() {#getenlargepage}

Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true.

### getExportGuideShapes() {#getexportguideshapes}

Defines whether need exporting the guide shapes or not. Default value is true.

### getExportHiddenPage() {#getexporthiddenpage}

Defines whether need exporting the hidden page or not. Default value is true.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Pages.vsdx");
// get a particular page
page = diagram.getPages().getPage("Flow 2");
// set Visio page visiblity
page.getPageSheet().getPageProps().getUIVisibility().setValue(aspose.diagram.BOOL.TRUE);
// initialize PDF save options
options = new aspose.diagram.PdfSaveOptions();
// set export option of hidden Visio pages
options.setExportHiddenPage(false);
diagram.save("out-ExportOfHiddenVisioPagesToPDF.pdf", options);
```

### getHorizontalResolution() {#gethorizontalresolution}

Gets or sets the horizontal resolution for generated images, in dots per inch. Applies generating image method except Emf format images. The default value is 96.

### getJpegQuality() {#getjpegquality}

Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95.

### getPageCount() {#getpagecount}

Gets or sets the number of pages to render in PDF. Default is MaxValue which means all pages of the diagram will be rendered.

### getPageIndex() {#getpageindex}

Gets or sets the 0-based index of the first page to render. Default is 0.

### getPageSavingCallback() {#getpagesavingcallback}

Control/Indicate progress of page saving process.

### getPageSize() {#getpagesize}

Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

### getSaveForegroundPagesOnly() {#getsaveforegroundpagesonly}

Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with background if present). If false - rendered foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### getSaveFormat() {#getsaveformat}

Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveFileFormat only. The value of the property is SaveFileFormat integer constant.

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

### getSplitMultiPages() {#getsplitmultipages}

Defines whether split diagram to multi pages according to page's setting. Default value is false.

### getTextCompression() {#gettextcompression}

Specifies compression type to be used for all content streams except images. Default is PdfTextCompression.FLATE. The value of the property is PdfTextCompression integer constant.

### getVerticalResolution() {#getverticalresolution}

Gets or sets the vertical resolution for generated images, in dots per inch. Applies generating image method except Emf format image. The default value is 96.

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

Gets and sets the PdfBookmarkEntry object.

### setCompliance() {#setcompliance}

Desired conformance level for generated PDF document. Default is PdfCompliance.PDF_15. The value of the property is PdfCompliance integer constant.

### setDefaultFont() {#setdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### setEmfRenderSetting() {#setemfrendersetting}

Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identified as "EMF+ Dual" can contain both EMF+ records and EMF records. Either type of record can be used to render the image, only EMF+ records, or only EMF records. When EmfPlusPrefer is set, then EMF+ records will be parsed , otherwise only EMF records will be parsed. Default value is EmfOnly"/>.

### setEncryptionDetails() {#setencryptiondetails}

Gets or sets a encryption details. If not set, then no encryption will be performed.

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

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Pages.vsdx");
// get a particular page
page = diagram.getPages().getPage("Flow 2");
// set Visio page visiblity
page.getPageSheet().getPageProps().getUIVisibility().setValue(aspose.diagram.BOOL.TRUE);
// initialize PDF save options
options = new aspose.diagram.PdfSaveOptions();
// set export option of hidden Visio pages
options.setExportHiddenPage(false);
diagram.save("out-ExportOfHiddenVisioPagesToPDF.pdf", options);
```

### setHorizontalResolution() {#sethorizontalresolution}

Gets or sets the horizontal resolution for generated images, in dots per inch. Applies generating image method except Emf format images. The default value is 96.

### setJpegQuality() {#setjpegquality}

Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95.

### setPageCount() {#setpagecount}

Gets or sets the number of pages to render in PDF. Default is MaxValue which means all pages of the diagram will be rendered.

### setPageIndex() {#setpageindex}

Gets or sets the 0-based index of the first page to render. Default is 0.

### setPageSavingCallback() {#setpagesavingcallback}

Control/Indicate progress of page saving process.

### setPageSize() {#setpagesize}

Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

### setSaveForegroundPagesOnly() {#setsaveforegroundpagesonly}

Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with background if present). If false - rendered foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### setSaveFormat() {#setsaveformat}

Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveFileFormat only. The value of the property is SaveFileFormat integer constant.

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

### setSplitMultiPages() {#setsplitmultipages}

Defines whether split diagram to multi pages according to page's setting. Default value is false.

### setTextCompression() {#settextcompression}

Specifies compression type to be used for all content streams except images. Default is PdfTextCompression.FLATE. The value of the property is PdfTextCompression integer constant.

### setVerticalResolution() {#setverticalresolution}

Gets or sets the vertical resolution for generated images, in dots per inch. Applies generating image method except Emf format image. The default value is 96.

### setWarningCallback() {#setwarningcallback}

Gets or sets warning callback.
