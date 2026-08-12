---
title: "ImageSaveOptions"
linktitle: "ImageSaveOptions"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Allows to specify additional options when rendering diagram pages to images."
type: docs
weight: 1200
url: /nodejs/aspose.diagram/imagesaveoptions/
---

## ImageSaveOptions class

Allows to specify additional options when rendering diagram pages to images.

```js
new ImageSaveOptions(saveFormat)
```

Initializes a new instance of this class that can be used to save rendered images in the SaveFileFormat, SaveFileFormat, SaveFileFormat, SaveFileFormat or SaveFileFormat format.

## Methods

| Name | Description |
| --- | --- |
| [getBookmark()](#getbookmark) |  |
| [getCompositingQuality()](#getcompositingquality) | Specifies the quality level to use during compositing. The value of the property is CompositingQuality integer constant. |
| [getContentZoom()](#getcontentzoom) | This parameter is similar with scale, but not effect the generated image size. The default value is 1.0. The value must  |
| [getDefaultFont()](#getdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [getEmfRenderSetting()](#getemfrendersetting) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [getEnlargePage()](#getenlargepage) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [getExportGuideShapes()](#getexportguideshapes) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [getExportHiddenPage()](#getexporthiddenpage) | Defines whether need exporting the hidden page or not. Default value is true. |
| [getImageBrightness()](#getimagebrightness) | Gets or sets the brightness for the the generated images. This property has effect only when saving to raster image form |
| [getImageColorMode()](#getimagecolormode) | Gets or sets the color mode for the generated images. The value of the property is ImageColorMode integer constant. This |
| [getImageContrast()](#getimagecontrast) | Gets or sets the contrast for the generated images. This property has effect only when saving to raster image formats. T |
| [getInterpolationMode()](#getinterpolationmode) | Specifies the algorithm that is used when images are scaled or rotated. The value of the property is InterpolationMode i |
| [getJpegQuality()](#getjpegquality) | Gets or sets a value determining the quality of the generated JPEG images. Has effect only when saving to JPEG. Use this |
| [getPageCount()](#getpagecount) | Gets or sets the number of pages to render when saving to a multipage TIFF file. Default is MaxValue which means all pag |
| [getPageIndex()](#getpageindex) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [getPageSize()](#getpagesize) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [getPixelOffsetMode()](#getpixeloffsetmode) | Gets or set a value specifying how pixels are offset during rendering. The value of the property is PixelOffsetMode inte |
| [getResolution()](#getresolution) | Gets or sets the resolution for the generated images, in dots per inch. This property has effect only when saving to ras |
| [getSameAsPdfConversionArea()](#getsameaspdfconversionarea) | Specifies whether saving area same as pdf . If true - rendered area same as pdf. If false - rendered area default. The d |
| [getSaveForegroundPagesOnly()](#getsaveforegroundpagesonly) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [getSaveFormat()](#getsaveformat) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [getScale()](#getscale) | Gets or sets the zoom factor for the generated images. The default value is 1.0. The value must be greater than 0. |
| [getShapes()](#getshapes) | Gets or sets shapes to render. Default count is 0. |
| [getSmoothingMode()](#getsmoothingmode) | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. The value of th |
| [getTiffCompression()](#gettiffcompression) | Gets or sets the type of compression to apply when saving generated images to the TIFF format. The value of the property |
| [getWarningCallback()](#getwarningcallback) | Gets or sets warning callback. |
| [isExportComments()](#isexportcomments) | Defines whether need exporting the comments or not. Default value is false. |
| [setBookmark()](#setbookmark) |  |
| [setCompositingQuality()](#setcompositingquality) | Specifies the quality level to use during compositing. The value of the property is CompositingQuality integer constant. |
| [setContentZoom()](#setcontentzoom) | This parameter is similar with scale, but not effect the generated image size. The default value is 1.0. The value must  |
| [setDefaultFont()](#setdefaultfont) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [setEmfRenderSetting()](#setemfrendersetting) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [setEnlargePage()](#setenlargepage) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [setExportComments()](#setexportcomments) | Defines whether need exporting the comments or not. Default value is false. |
| [setExportGuideShapes()](#setexportguideshapes) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [setExportHiddenPage()](#setexporthiddenpage) | Defines whether need exporting the hidden page or not. Default value is true. |
| [setImageBrightness()](#setimagebrightness) | Gets or sets the brightness for the the generated images. This property has effect only when saving to raster image form |
| [setImageColorMode()](#setimagecolormode) | Gets or sets the color mode for the generated images. The value of the property is ImageColorMode integer constant. This |
| [setImageContrast()](#setimagecontrast) | Gets or sets the contrast for the generated images. This property has effect only when saving to raster image formats. T |
| [setInterpolationMode()](#setinterpolationmode) | Specifies the algorithm that is used when images are scaled or rotated. The value of the property is InterpolationMode i |
| [setJpegQuality()](#setjpegquality) | Gets or sets a value determining the quality of the generated JPEG images. Has effect only when saving to JPEG. Use this |
| [setPageCount()](#setpagecount) | Gets or sets the number of pages to render when saving to a multipage TIFF file. Default is MaxValue which means all pag |
| [setPageIndex()](#setpageindex) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [setPageSize()](#setpagesize) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [setPixelOffsetMode()](#setpixeloffsetmode) | Gets or set a value specifying how pixels are offset during rendering. The value of the property is PixelOffsetMode inte |
| [setResolution()](#setresolution) | Gets or sets the resolution for the generated images, in dots per inch. This property has effect only when saving to ras |
| [setSameAsPdfConversionArea()](#setsameaspdfconversionarea) | Specifies whether saving area same as pdf . If true - rendered area same as pdf. If false - rendered area default. The d |
| [setSaveForegroundPagesOnly()](#setsaveforegroundpagesonly) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [setSaveFormat()](#setsaveformat) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [setScale()](#setscale) | Gets or sets the zoom factor for the generated images. The default value is 1.0. The value must be greater than 0. |
| [setShapes()](#setshapes) | Gets or sets shapes to render. Default count is 0. |
| [setSmoothingMode()](#setsmoothingmode) | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. The value of th |
| [setTiffCompression()](#settiffcompression) | Gets or sets the type of compression to apply when saving generated images to the TIFF format. The value of the property |
| [setWarningCallback()](#setwarningcallback) | Gets or sets warning callback. |

### getBookmark() {#getbookmark}

### getCompositingQuality() {#getcompositingquality}

Specifies the quality level to use during compositing. The value of the property is CompositingQuality integer constant. This property has effect only when saving to raster image formats. The default value is CompositingQuality.

### getContentZoom() {#getcontentzoom}

This parameter is similar with scale, but not effect the generated image size. The default value is 1.0. The value must be greater than 0.

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

### getImageBrightness() {#getimagebrightness}

Gets or sets the brightness for the the generated images. This property has effect only when saving to raster image formats. The default value is 0.5. The value must be in the range between 0 and 1.

### getImageColorMode() {#getimagecolormode}

Gets or sets the color mode for the generated images. The value of the property is ImageColorMode integer constant. This property has effect only when saving to raster image formats. The default value is ImageColorMode.

### getImageContrast() {#getimagecontrast}

Gets or sets the contrast for the generated images. This property has effect only when saving to raster image formats. The default value is 0.5. The value must be in the range between 0 and 1.

### getInterpolationMode() {#getinterpolationmode}

Specifies the algorithm that is used when images are scaled or rotated. The value of the property is InterpolationMode integer constant. This property has effect only when saving to raster image formats. The default value is InterpolationMode.

### getJpegQuality() {#getjpegquality}

Gets or sets a value determining the quality of the generated JPEG images. Has effect only when saving to JPEG. Use this property to get or set the quality of generated images when saving in JPEG format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 95.

### getPageCount() {#getpagecount}

Gets or sets the number of pages to render when saving to a multipage TIFF file. Default is MaxValue which means all pages of the diagram will be rendered.

### getPageIndex() {#getpageindex}

Gets or sets the 0-based index of the first page to render. Default is 0.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("ExportPageToImage.vsd");
// Save diagram as PNG
options = new aspose.diagram.ImageSaveOptions(aspose.diagram.SaveFileFormat.PNG);
// Save one page only, by page index
options.setPageIndex(0);
// Save resultant Image file
diagram.save("out-ExportPageToImage.png", options);
```

### getPageSize() {#getpagesize}

Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

### getPixelOffsetMode() {#getpixeloffsetmode}

Gets or set a value specifying how pixels are offset during rendering. The value of the property is PixelOffsetMode integer constant. This property has effect only when saving to raster image formats. The default value is PixelOffsetMode.

### getResolution() {#getresolution}

Gets or sets the resolution for the generated images, in dots per inch. This property has effect only when saving to raster image formats. The default value is 96.

### getSameAsPdfConversionArea() {#getsameaspdfconversionarea}

Specifies whether saving area same as pdf . If true - rendered area same as pdf. If false - rendered area default. The default value is false.

### getSaveForegroundPagesOnly() {#getsaveforegroundpagesonly}

Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with background if present). If false - rendered foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### getSaveFormat() {#getsaveformat}

Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveFileFormat, SaveFileFormat, SaveFileFormat, SaveFileFormat or SaveFileFormat. The value of the property is SaveFileFormat integer constant.

### getScale() {#getscale}

Gets or sets the zoom factor for the generated images. The default value is 1.0. The value must be greater than 0.

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

### getSmoothingMode() {#getsmoothingmode}

Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. The value of the property is SmoothingMode integer constant. This property has effect only when saving to raster image formats. The default value is SmoothingMode.

### getTiffCompression() {#gettiffcompression}

Gets or sets the type of compression to apply when saving generated images to the TIFF format. The value of the property is TiffCompression integer constant. Has effect only when saving to TIFF. The default value is TiffCompression.

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

### setCompositingQuality() {#setcompositingquality}

Specifies the quality level to use during compositing. The value of the property is CompositingQuality integer constant. This property has effect only when saving to raster image formats. The default value is CompositingQuality.

### setContentZoom() {#setcontentzoom}

This parameter is similar with scale, but not effect the generated image size. The default value is 1.0. The value must be greater than 0.

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

### setImageBrightness() {#setimagebrightness}

Gets or sets the brightness for the the generated images. This property has effect only when saving to raster image formats. The default value is 0.5. The value must be in the range between 0 and 1.

### setImageColorMode() {#setimagecolormode}

Gets or sets the color mode for the generated images. The value of the property is ImageColorMode integer constant. This property has effect only when saving to raster image formats. The default value is ImageColorMode.

### setImageContrast() {#setimagecontrast}

Gets or sets the contrast for the generated images. This property has effect only when saving to raster image formats. The default value is 0.5. The value must be in the range between 0 and 1.

### setInterpolationMode() {#setinterpolationmode}

Specifies the algorithm that is used when images are scaled or rotated. The value of the property is InterpolationMode integer constant. This property has effect only when saving to raster image formats. The default value is InterpolationMode.

### setJpegQuality() {#setjpegquality}

Gets or sets a value determining the quality of the generated JPEG images. Has effect only when saving to JPEG. Use this property to get or set the quality of generated images when saving in JPEG format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression. The default value is 95.

### setPageCount() {#setpagecount}

Gets or sets the number of pages to render when saving to a multipage TIFF file. Default is MaxValue which means all pages of the diagram will be rendered.

### setPageIndex() {#setpageindex}

Gets or sets the 0-based index of the first page to render. Default is 0.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("ExportPageToImage.vsd");
// Save diagram as PNG
options = new aspose.diagram.ImageSaveOptions(aspose.diagram.SaveFileFormat.PNG);
// Save one page only, by page index
options.setPageIndex(0);
// Save resultant Image file
diagram.save("out-ExportPageToImage.png", options);
```

### setPageSize() {#setpagesize}

Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is null then page size for generated image is obtained from source diagram.

### setPixelOffsetMode() {#setpixeloffsetmode}

Gets or set a value specifying how pixels are offset during rendering. The value of the property is PixelOffsetMode integer constant. This property has effect only when saving to raster image formats. The default value is PixelOffsetMode.

### setResolution() {#setresolution}

Gets or sets the resolution for the generated images, in dots per inch. This property has effect only when saving to raster image formats. The default value is 96.

### setSameAsPdfConversionArea() {#setsameaspdfconversionarea}

Specifies whether saving area same as pdf . If true - rendered area same as pdf. If false - rendered area default. The default value is false.

### setSaveForegroundPagesOnly() {#setsaveforegroundpagesonly}

Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with background if present). If false - rendered foreground pages(with background if present) after that empty background pages. Can return true only when PageCount > 1. The default value is false.

### setSaveFormat() {#setsaveformat}

Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveFileFormat, SaveFileFormat, SaveFileFormat, SaveFileFormat or SaveFileFormat. The value of the property is SaveFileFormat integer constant.

### setScale() {#setscale}

Gets or sets the zoom factor for the generated images. The default value is 1.0. The value must be greater than 0.

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

### setSmoothingMode() {#setsmoothingmode}

Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. The value of the property is SmoothingMode integer constant. This property has effect only when saving to raster image formats. The default value is SmoothingMode.

### setTiffCompression() {#settiffcompression}

Gets or sets the type of compression to apply when saving generated images to the TIFF format. The value of the property is TiffCompression integer constant. Has effect only when saving to TIFF. The default value is TiffCompression.

### setWarningCallback() {#setwarningcallback}

Gets or sets warning callback.
