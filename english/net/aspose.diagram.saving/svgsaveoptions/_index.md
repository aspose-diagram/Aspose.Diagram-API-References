---
title: SVGSaveOptions
second_title: Aspose.Diagram for .NET API Reference
description: 
type: docs
weight: 3450
url: /net/aspose.diagram.saving/svgsaveoptions/
---
## SVGSaveOptions class

Allows to specify additional options when rendering diagram pages to SVG.

```csharp
public class SVGSaveOptions : RenderingSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SVGSaveOptions](svgsaveoptions)() | Initializes a new instance of this class that can be used to save a document in the [`XPS`](../../aspose.diagram/savefileformat) format. |

## Properties

| Name | Description |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area) { get; set; } | Gets or sets the area of the shapes will be saved . |
| [CustomImagePath](../../aspose.diagram.saving/svgsaveoptions/customimagepath) { get; set; } | The user custom path(URL) saved in generated svg file for the image. If not defined by user, Current directory will be used. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting) { get; set; } | Setting for rendering Emf metafile. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage) { get; set; } | Specifies whether enlarge page . |
| [ExportElementAsRectTag](../../aspose.diagram.saving/svgsaveoptions/exportelementasrecttag) { get; set; } | Defines whether need exporting rectangle elements as rect tag or not. |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes) { get; set; } | Defines whether need exporting the guide shapes or not. |
| [ExportHiddenPage](../../aspose.diagram.saving/svgsaveoptions/exporthiddenpage) { get; set; } | Defines whether need exporting the hidden page or not. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments) { get; set; } | Defines whether need exporting the comments or not. |
| [IsExportScaleInMatrix](../../aspose.diagram.saving/svgsaveoptions/isexportscaleinmatrix) { get; set; } | Defines whether need export scale in matrix or not. |
| [IsSavingImageSeparately](../../aspose.diagram.saving/svgsaveoptions/issavingimageseparately) { get; set; } | Defines whether Saving Image Separately. |
| [PageIndex](../../aspose.diagram.saving/svgsaveoptions/pageindex) { get; set; } | Gets or sets the 0-based index of the page to render. Default is 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize) { get; set; } | Gets or sets the page size for the generated images. Can be [`PageSize`](../pagesize) or null. |
| [Quality](../../aspose.diagram.saving/svgsaveoptions/quality) { get; set; } | Gets or sets a value determining the quality of the generated images to apply only when saving pages to the `Jpeg` format. The default value is 100 |
| virtual [SaveFormat](../../aspose.diagram.saving/saveoptions/saveformat) { get; set; } | Specifies the format in which the document will be saved if this save options object is used. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes) { get; set; } | Gets or sets shapes to render. Default count is 0. |
| [SVGFitToViewPort](../../aspose.diagram.saving/svgsaveoptions/svgfittoviewport) { get; set; } | if this property is true, the generated svg will fit to view port. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | Gets or sets warning callback. |

### See Also

* class [RenderingSaveOptions](../renderingsaveoptions)
* namespace [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* assembly [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->