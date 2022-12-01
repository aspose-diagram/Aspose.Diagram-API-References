---
title: ImageSaveOptions class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 50
url: /python-net/aspose.diagram.saving/imagesaveoptions/
is_root: false
---

## ImageSaveOptions class

Allows to specify additional options when rendering diagram pages to images.



**Inheritance:** [ImageSaveOptions](/diagram/python-net/aspose.diagram.saving/imagesaveoptions) → 
[RenderingSaveOptions](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions) → 
[SaveOptions](/diagram/python-net/aspose.diagram.saving/saveoptions)



The ImageSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [ImageSaveOptions(save_format)](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/__init__/#SaveFileFormat) | Initializes a new instance of this class that can be used to save rendered images in the [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat),<br/>[SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat), [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat), [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat)<br/>or [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat) format. |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/save_format) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used.<br/>Can be [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat), [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat),<br/>[SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat), [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat) or [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat). |
| [default_font](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/default_font) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,<br/>they may appear as block in pdf, image or XPS.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [warning_callback](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/warning_callback) | Gets or sets warning callback. |
| [page_size](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/page_size) | Gets or sets the page size for the generated images.<br/>Can be [PageSize](/diagram/python-net/aspose.diagram.saving/pagesize) or null. |
| [shapes](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/shapes) | Gets or sets shapes to render. Default count is 0. |
| [area](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/area) | Gets or sets the area of the shapes will be saved . |
| [export_guide_shapes](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/export_guide_shapes) | Defines whether need exporting the guide shapes or not. |
| [is_export_comments](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/is_export_comments) | Defines whether need exporting the comments or not. |
| [enlarge_page](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/enlarge_page) | Specifies whether enlarge page . |
| [emf_render_setting](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/emf_render_setting) | Setting for rendering Emf metafile. |
| [image_brightness](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/image_brightness) | Gets or sets the brightness for the the generated images. |
| [image_color_mode](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/image_color_mode) | Gets or sets the color mode for the generated images. |
| [image_contrast](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/image_contrast) | Gets or sets the contrast for the generated images. |
| [jpeg_quality](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/jpeg_quality) | Gets or sets a value determining the quality of the generated JPEG images. |
| [page_count](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/page_count) | Gets or sets the number of pages to render when saving to a multipage TIFF file.<br/>Default is MaxValue which means all pages of the diagram will be rendered. |
| [page_index](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/page_index) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [export_hidden_page](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/export_hidden_page) | Defines whether need exporting the hidden page or not. |
| [resolution](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/resolution) | Gets or sets the resolution for the generated images, in dots per inch. |
| [scale](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/scale) | Gets or sets the zoom factor for the generated images. |
| [content_zoom](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/content_zoom) | This parameter is similar with scale, but not effect the generated image size. |
| [tiff_compression](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/tiff_compression) | Gets or sets the type of compression to apply when saving generated images to the TIFF format. |
| [save_foreground_pages_only](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/save_foreground_pages_only) | Specifies whether all pages will be saved in image or only foreground. |
| [same_as_pdf_conversion_area](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/same_as_pdf_conversion_area) | Specifies whether saving area same as pdf . |
| [pixel_offset_mode](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/pixel_offset_mode) | Gets or set a value specifying how pixels are offset during rendering. |
| [smoothing_mode](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/smoothing_mode) | Specifies whether smoothing (antialiasing) is applied to lines and curves and the edges of filled areas. |
| [compositing_quality](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/compositing_quality) | Specifies the quality level to use during compositing. |
| [interpolation_mode](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/interpolation_mode) | Specifies the algorithm that is used when images are scaled or rotated. |


### Methods
| Method | Description |
| :- | :- |
| [create_save_options(save_format)](/diagram/python-net/aspose.diagram.saving/imagesaveoptions/create_save_options/#SaveFileFormat) | Creates a save options object of a class suitable for the specified save format. |


### See Also

* module [aspose.diagram.saving](../)
* class [RenderingSaveOptions](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions)
