---
title: ImageSaveOptions
second_title: Aspose.Diagram for .NET API Reference
description: Allows to specify additional options when rendering diagram pages to images.
type: docs
weight: 3280
url: /net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

Allows to specify additional options when rendering diagram pages to images.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions)(SaveFileFormat) | Initializes a new instance of this class that can be used to save rendered images in the [`Tiff`](../../aspose.diagram/savefileformat), [`Png`](../../aspose.diagram/savefileformat), [`Bmp`](../../aspose.diagram/savefileformat), [`Emf`](../../aspose.diagram/savefileformat) or [`Jpeg`](../../aspose.diagram/savefileformat) format. |

## Properties

| Name | Description |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area) { get; set; } | Gets or sets the area of the shapes will be saved . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality) { get; set; } | Specifies the quality level to use during compositing. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom) { get; set; } | This parameter is similar with scale, but not effect the generated image size. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting) { get; set; } | Setting for rendering Emf metafile. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage) { get; set; } | Specifies whether enlarge page . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes) { get; set; } | Defines whether need exporting the guide shapes or not. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage) { get; set; } | Defines whether need exporting the hidden page or not. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness) { get; set; } | Gets or sets the brightness for the the generated images. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode) { get; set; } | Gets or sets the color mode for the generated images. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast) { get; set; } | Gets or sets the contrast for the generated images. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode) { get; set; } | Specifies the algorithm that is used when images are scaled or rotated. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments) { get; set; } | Defines whether need exporting the comments or not. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality) { get; set; } | Gets or sets a value determining the quality of the generated JPEG images. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount) { get; set; } | Gets or sets the number of pages to render when saving to a multipage TIFF file. Default is MaxValue which means all pages of the diagram will be rendered. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex) { get; set; } | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize) { get; set; } | Gets or sets the page size for the generated images. Can be [`PageSize`](../pagesize) or null. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode) { get; set; } | Gets or set a value specifying how pixels are offset during rendering. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution) { get; set; } | Gets or sets the resolution for the generated images, in dots per inch. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea) { get; set; } | Specifies whether saving area same as pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly) { get; set; } | Specifies whether all pages will be saved in image or only foreground. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat) { get; set; } | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be [`Tiff`](../../aspose.diagram/savefileformat), [`Png`](../../aspose.diagram/savefileformat), [`Bmp`](../../aspose.diagram/savefileformat), [`Emf`](../../aspose.diagram/savefileformat) or [`Jpeg`](../../aspose.diagram/savefileformat). |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale) { get; set; } | Gets or sets the zoom factor for the generated images. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes) { get; set; } | Gets or sets shapes to render. Default count is 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode) { get; set; } | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression) { get; set; } | Gets or sets the type of compression to apply when saving generated images to the TIFF format. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | Gets or sets warning callback. |

### See Also

* class [RenderingSaveOptions](../renderingsaveoptions)
* namespace [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* assembly [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
