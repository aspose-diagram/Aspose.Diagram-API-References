---
title: "SVGSaveOptions"
linktitle: "SVGSaveOptions"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Allows to specify additional options when rendering diagram pages to SVG."
type: docs
weight: 2240
url: /nodejs/aspose.diagram/svgsaveoptions/
---

## SVGSaveOptions class

Allows to specify additional options when rendering diagram pages to SVG.

```js
new SVGSaveOptions()
```

Initializes a new instance of this class that can be used to save a document in the SaveFileFormat format.

## Methods

| Name | Description |
| --- | --- |
| [getBookmark()](#getbookmark) |  |
| [getCustomImagePath()](#getcustomimagepath) | The user custom path(URL) saved in generated svg file for the image. If not defined by user, Current directory will be u |
| [getDefaultFont()](#getdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [getEmfRenderSetting()](#getemfrendersetting) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [getEnlargePage()](#getenlargepage) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [getExportElementAsRectTag()](#getexportelementasrecttag) | Defines whether need exporting rectangle elements as rect tag or not. Default value is false. |
| [getExportGuideShapes()](#getexportguideshapes) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [getExportHiddenPage()](#getexporthiddenpage) | Defines whether need exporting the hidden page or not. Default value is true. |
| [getPageIndex()](#getpageindex) | Gets or sets the 0-based index of the page to render. Default is 0. |
| [getPageSize()](#getpagesize) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [getQuality()](#getquality) | Gets or sets a value determining the quality of the generated images to apply only when saving pages to the Jpeg format. |
| [getSaveFormat()](#getsaveformat) | Specifies the format in which the document will be saved if this save options object is used. The value of the property  |
| [getShapes()](#getshapes) | Gets or sets shapes to render. Default count is 0. |
| [getSVGFitToViewPort()](#getsvgfittoviewport) | if this property is true, the generated svg will fit to view port. |
| [getWarningCallback()](#getwarningcallback) | Gets or sets warning callback. |
| [isExportComments()](#isexportcomments) | Defines whether need exporting the comments or not. Default value is false. |
| [isExportScaleInMatrix()](#isexportscaleinmatrix) | Defines whether need export scale in matrix or not. Default value is true. |
| [isSavingCustomLinePattern()](#issavingcustomlinepattern) | Defines whether Saving custom line pattern. |
| [isSavingImageSeparately()](#issavingimageseparately) | Defines whether Saving Image Separately. |
| [setBookmark()](#setbookmark) |  |
| [setCustomImagePath()](#setcustomimagepath) | The user custom path(URL) saved in generated svg file for the image. If not defined by user, Current directory will be u |
| [setDefaultFont()](#setdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [setEmfRenderSetting()](#setemfrendersetting) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [setEnlargePage()](#setenlargepage) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [setExportComments()](#setexportcomments) | Defines whether need exporting the comments or not. Default value is false. |
| [setExportElementAsRectTag()](#setexportelementasrecttag) | Defines whether need exporting rectangle elements as rect tag or not. Default value is false. |
| [setExportGuideShapes()](#setexportguideshapes) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [setExportHiddenPage()](#setexporthiddenpage) | Defines whether need exporting the hidden page or not. Default value is true. |
| [setExportScaleInMatrix()](#setexportscaleinmatrix) | Defines whether need export scale in matrix or not. Default value is true. |
| [setPageIndex()](#setpageindex) | Gets or sets the 0-based index of the page to render. Default is 0. |
| [setPageSize()](#setpagesize) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [setQuality()](#setquality) | Gets or sets a value determining the quality of the generated images to apply only when saving pages to the Jpeg format. |
| [setSaveFormat()](#setsaveformat) | Specifies the format in which the document will be saved if this save options object is used. The value of the property  |
| [setSavingCustomLinePattern()](#setsavingcustomlinepattern) | Defines whether Saving custom line pattern. |
| [setSavingImageSeparately()](#setsavingimageseparately) | Defines whether Saving Image Separately. |
| [setShapes()](#setshapes) | Gets or sets shapes to render. Default count is 0. |
| [setSVGFitToViewPort()](#setsvgfittoviewport) | if this property is true, the generated svg will fit to view port. |
| [setWarningCallback()](#setwarningcallback) | Gets or sets warning callback. |

### getBookmark() {#getbookmark}

### getCustomImagePath() {#getcustomimagepath}

The user custom path(URL) saved in generated svg file for the image. If not defined by user, Current directory will be used.

### getDefaultFont() {#getdefaultfont}

When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters.

### getEmfRenderSetting() {#getemfrendersetting}

Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identified as "EMF+ Dual" can contain both EMF+ records and EMF records. Either type of record can be used to render the image, only EMF+ records, or only EMF records. When EmfPlusPrefer is set, then EMF+ records will be parsed , otherwise only EMF records will be parsed. Default value is EmfOnly"/>.

### getEnlargePage() {#getenlargepage}

Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true.

### getExportElementAsRectTag() {#getexportelementasrecttag}

Defines whether need exporting rectangle elements as rect tag or not. Default value is false.

### getExportGuideShapes() {#getexportguideshapes}

Defines whether need exporting the guide shapes or not. Default value is true.

### getExportHiddenPage() {#getexporthiddenpage}

Defines whether need exporting the hidden page or not. Default value is true.

### getPageIndex() {#getpageindex}

Gets or sets the 0-based index of the page to render. Default is 0.

### getPageSize() {#getpagesize}

Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

### getQuality() {#getquality}

Gets or sets a value determining the quality of the generated images to apply only when saving pages to the Jpeg format. The default value is 100 Has effect only when saving to JPEG. The value must be between 0 and 100. The default value is 100.

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

### getSVGFitToViewPort() {#getsvgfittoviewport}

if this property is true, the generated svg will fit to view port.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Pages.vsdx");
// get a particular page
page = diagram.getPages().getPage("Flow 2");
// set Visio page visiblity
page.getPageSheet().getPageProps().getUIVisibility().setValue(aspose.diagram.BOOL.TRUE);
// initialize SVG save options
options = new aspose.diagram.SVGSaveOptions();
// set export option of hidden Visio pages
options.setExportHiddenPage(false);
// Set SVG fit to view port
options.setSVGFitToViewPort(true);
// Set export element as Rectangle
options.setExportElementAsRectTag(true);
diagram.save("out-ExportOfHiddenVisioPagesToSVG.svg", options);
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

### isExportScaleInMatrix() {#isexportscaleinmatrix}

Defines whether need export scale in matrix or not. Default value is true.

### isSavingCustomLinePattern() {#issavingcustomlinepattern}

Defines whether Saving custom line pattern.

### isSavingImageSeparately() {#issavingimageseparately}

Defines whether Saving Image Separately.

### setBookmark() {#setbookmark}

### setCustomImagePath() {#setcustomimagepath}

The user custom path(URL) saved in generated svg file for the image. If not defined by user, Current directory will be used.

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

### setExportElementAsRectTag() {#setexportelementasrecttag}

Defines whether need exporting rectangle elements as rect tag or not. Default value is false.

### setExportGuideShapes() {#setexportguideshapes}

Defines whether need exporting the guide shapes or not. Default value is true.

### setExportHiddenPage() {#setexporthiddenpage}

Defines whether need exporting the hidden page or not. Default value is true.

### setExportScaleInMatrix() {#setexportscaleinmatrix}

Defines whether need export scale in matrix or not. Default value is true.

### setPageIndex() {#setpageindex}

Gets or sets the 0-based index of the page to render. Default is 0.

### setPageSize() {#setpagesize}

Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

### setQuality() {#setquality}

Gets or sets a value determining the quality of the generated images to apply only when saving pages to the Jpeg format. The default value is 100 Has effect only when saving to JPEG. The value must be between 0 and 100. The default value is 100.

### setSaveFormat() {#setsaveformat}

Specifies the format in which the document will be saved if this save options object is used. The value of the property is SaveFileFormat integer constant.

### setSavingCustomLinePattern() {#setsavingcustomlinepattern}

Defines whether Saving custom line pattern.

### setSavingImageSeparately() {#setsavingimageseparately}

Defines whether Saving Image Separately.

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

### setSVGFitToViewPort() {#setsvgfittoviewport}

if this property is true, the generated svg will fit to view port.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Pages.vsdx");
// get a particular page
page = diagram.getPages().getPage("Flow 2");
// set Visio page visiblity
page.getPageSheet().getPageProps().getUIVisibility().setValue(aspose.diagram.BOOL.TRUE);
// initialize SVG save options
options = new aspose.diagram.SVGSaveOptions();
// set export option of hidden Visio pages
options.setExportHiddenPage(false);
// Set SVG fit to view port
options.setSVGFitToViewPort(true);
// Set export element as Rectangle
options.setExportElementAsRectTag(true);
diagram.save("out-ExportOfHiddenVisioPagesToSVG.svg", options);
```

### setWarningCallback() {#setwarningcallback}

Gets or sets warning callback.
