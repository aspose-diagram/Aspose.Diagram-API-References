---
title: PdfSaveOptions
second_title: Aspose.Diagram for .NET API Reference
description: Allows to specify additional options when rendering diagram pages to PDF.
type: docs
url: /net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Allows to specify additional options when rendering diagram pages to PDF.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | Initializes a new instance of this class that can be used to save a document in the [`Pdf`](../../aspose.diagram/savefileformat) format. |

## Properties

| Name | Description |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area) { get; set; } | Gets or sets the area of the shapes will be saved . |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance) { get; set; } | Desired conformance level for generated PDF document. Default is Pdf15. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails) { get; set; } | Gets or sets a digital signature details. If not set, then no signing will be performed. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting) { get; set; } | Setting for rendering Emf metafile. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails) { get; set; } | Gets or sets a encryption details. If not set, then no encryption will be performed. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage) { get; set; } | Specifies whether enlarge page . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes) { get; set; } | Defines whether need exporting the guide shapes or not. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage) { get; set; } | Defines whether need exporting the hidden page or not. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution) { get; set; } | Gets or sets the horizontal resolution for generated images, in dots per inch. Applies generating image method except Emf format images. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments) { get; set; } | Defines whether need exporting the comments or not. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality) { get; set; } | Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount) { get; set; } | Gets or sets the number of pages to render in PDF. Default is MaxValue which means all pages of the diagram will be rendered. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex) { get; set; } | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback) { get; set; } | Control/Indicate progress of page saving process. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize) { get; set; } | Gets or sets the page size for the generated images. Can be [`PageSize`](../pagesize) or null. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly) { get; set; } | Specifies whether all pages will be saved in image or only foreground. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat) { get; set; } | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be [`PDF`](../../aspose.diagram/savefileformat) only. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes) { get; set; } | Gets or sets shapes to render. Default count is 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages) { get; set; } | Defines whether split diagram to multi pages according to page's setting. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression) { get; set; } | Specifies compression type to be used for all content streams except images. Default is Flate. |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution) { get; set; } | Gets or sets the vertical resolution for generated images, in dots per inch. Applies generating image method except Emf format image. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback) { get; set; } | Gets or sets warning callback. |

### See Also

* class [RenderingSaveOptions](../renderingsaveoptions)
* namespace [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* assembly [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
