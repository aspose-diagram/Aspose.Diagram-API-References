---
title: "ImageSaveOptions Class"
linktitle: "ImageSaveOptions"
articleTitle: "ImageSaveOptions"
second_title: "Aspose.Diagram for Node.js via Java"
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
| [getBookmark()](./getbookmark/) |  |
| [getCompositingQuality()](./getcompositingquality/) | Specifies the quality level to use during compositing. The value of the property is CompositingQuality integer constant. |
| [getContentZoom()](./getcontentzoom/) | This parameter is similar with scale, but not effect the generated image size. The default value is 1.0. The value must  |
| [getDefaultFont()](./getdefaultfont/) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [getEmfRenderSetting()](./getemfrendersetting/) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [getEnlargePage()](./getenlargepage/) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [getExportGuideShapes()](./getexportguideshapes/) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [getExportHiddenPage()](./getexporthiddenpage/) | Defines whether need exporting the hidden page or not. Default value is true. |
| [getImageBrightness()](./getimagebrightness/) | Gets or sets the brightness for the the generated images. This property has effect only when saving to raster image form |
| [getImageColorMode()](./getimagecolormode/) | Gets or sets the color mode for the generated images. The value of the property is ImageColorMode integer constant. This |
| [getImageContrast()](./getimagecontrast/) | Gets or sets the contrast for the generated images. This property has effect only when saving to raster image formats. T |
| [getInterpolationMode()](./getinterpolationmode/) | Specifies the algorithm that is used when images are scaled or rotated. The value of the property is InterpolationMode i |
| [getJpegQuality()](./getjpegquality/) | Gets or sets a value determining the quality of the generated JPEG images. Has effect only when saving to JPEG. Use this |
| [getPageCount()](./getpagecount/) | Gets or sets the number of pages to render when saving to a multipage TIFF file. Default is MaxValue which means all pag |
| [getPageIndex()](./getpageindex/) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [getPageSize()](./getpagesize/) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [getPixelOffsetMode()](./getpixeloffsetmode/) | Gets or set a value specifying how pixels are offset during rendering. The value of the property is PixelOffsetMode inte |
| [getResolution()](./getresolution/) | Gets or sets the resolution for the generated images, in dots per inch. This property has effect only when saving to ras |
| [getSameAsPdfConversionArea()](./getsameaspdfconversionarea/) | Specifies whether saving area same as pdf . If true - rendered area same as pdf. If false - rendered area default. The d |
| [getSaveForegroundPagesOnly()](./getsaveforegroundpagesonly/) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [getSaveFormat()](./getsaveformat/) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [getScale()](./getscale/) | Gets or sets the zoom factor for the generated images. The default value is 1.0. The value must be greater than 0. |
| [getShapes()](./getshapes/) | Gets or sets shapes to render. Default count is 0. |
| [getSmoothingMode()](./getsmoothingmode/) | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. The value of th |
| [getTiffCompression()](./gettiffcompression/) | Gets or sets the type of compression to apply when saving generated images to the TIFF format. The value of the property |
| [getWarningCallback()](./getwarningcallback/) | Gets or sets warning callback. |
| [isExportComments()](./isexportcomments/) | Defines whether need exporting the comments or not. Default value is false. |
| [setBookmark()](./setbookmark/) |  |
| [setCompositingQuality()](./setcompositingquality/) | Specifies the quality level to use during compositing. The value of the property is CompositingQuality integer constant. |
| [setContentZoom()](./setcontentzoom/) | This parameter is similar with scale, but not effect the generated image size. The default value is 1.0. The value must  |
| [setDefaultFont()](./setdefaultfont/) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,  |
| [setEmfRenderSetting()](./setemfrendersetting/) | Setting for rendering Emf metafile. The value of the property is EmfRenderSetting integer constant. EMF metafiles identi |
| [setEnlargePage()](./setenlargepage/) | Specifies whether enlarge page . If true - enlarge page. If false - not enlarge page. The default value is true. |
| [setExportComments()](./setexportcomments/) | Defines whether need exporting the comments or not. Default value is false. |
| [setExportGuideShapes()](./setexportguideshapes/) | Defines whether need exporting the guide shapes or not. Default value is true. |
| [setExportHiddenPage()](./setexporthiddenpage/) | Defines whether need exporting the hidden page or not. Default value is true. |
| [setImageBrightness()](./setimagebrightness/) | Gets or sets the brightness for the the generated images. This property has effect only when saving to raster image form |
| [setImageColorMode()](./setimagecolormode/) | Gets or sets the color mode for the generated images. The value of the property is ImageColorMode integer constant. This |
| [setImageContrast()](./setimagecontrast/) | Gets or sets the contrast for the generated images. This property has effect only when saving to raster image formats. T |
| [setInterpolationMode()](./setinterpolationmode/) | Specifies the algorithm that is used when images are scaled or rotated. The value of the property is InterpolationMode i |
| [setJpegQuality()](./setjpegquality/) | Gets or sets a value determining the quality of the generated JPEG images. Has effect only when saving to JPEG. Use this |
| [setPageCount()](./setpagecount/) | Gets or sets the number of pages to render when saving to a multipage TIFF file. Default is MaxValue which means all pag |
| [setPageIndex()](./setpageindex/) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [setPageSize()](./setpagesize/) | Gets or sets the page size for the generated images. Can be PageSize or null. The default value is null. If PageSize is  |
| [setPixelOffsetMode()](./setpixeloffsetmode/) | Gets or set a value specifying how pixels are offset during rendering. The value of the property is PixelOffsetMode inte |
| [setResolution()](./setresolution/) | Gets or sets the resolution for the generated images, in dots per inch. This property has effect only when saving to ras |
| [setSameAsPdfConversionArea()](./setsameaspdfconversionarea/) | Specifies whether saving area same as pdf . If true - rendered area same as pdf. If false - rendered area default. The d |
| [setSaveForegroundPagesOnly()](./setsaveforegroundpagesonly/) | Specifies whether all pages will be saved in image or only foreground. If true - rendered only foreground pages(with bac |
| [setSaveFormat()](./setsaveformat/) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be SaveF |
| [setScale()](./setscale/) | Gets or sets the zoom factor for the generated images. The default value is 1.0. The value must be greater than 0. |
| [setShapes()](./setshapes/) | Gets or sets shapes to render. Default count is 0. |
| [setSmoothingMode()](./setsmoothingmode/) | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. The value of th |
| [setTiffCompression()](./settiffcompression/) | Gets or sets the type of compression to apply when saving generated images to the TIFF format. The value of the property |
| [setWarningCallback()](./setwarningcallback/) | Gets or sets warning callback. |
