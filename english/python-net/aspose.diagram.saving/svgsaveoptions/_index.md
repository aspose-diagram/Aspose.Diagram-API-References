---
title: SVGSaveOptions class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 150
url: /python-net/aspose.diagram.saving/svgsaveoptions/
is_root: false
---

## SVGSaveOptions class

Allows to specify additional options when rendering diagram pages to SVG.



**Inheritance:** [SVGSaveOptions](/diagram/python-net/aspose.diagram.saving/svgsaveoptions) → 
[RenderingSaveOptions](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions) → 
[SaveOptions](/diagram/python-net/aspose.diagram.saving/saveoptions)



The SVGSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [SVGSaveOptions()](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/__init__/#) | Initializes a new instance of this class that can be used to save a document in the [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat) format. |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/save_format) | Specifies the format in which the document will be saved if this save options object is used. |
| [default_font](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/default_font) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,<br/>they may appear as block in pdf, image or XPS.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [warning_callback](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/warning_callback) | Gets or sets warning callback. |
| [page_size](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/page_size) | Gets or sets the page size for the generated images.<br/>Can be [PageSize](/diagram/python-net/aspose.diagram.saving/pagesize) or null. |
| [shapes](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/shapes) | Gets or sets shapes to render. Default count is 0. |
| [area](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/area) | Gets or sets the area of the shapes will be saved . |
| [export_guide_shapes](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/export_guide_shapes) | Defines whether need exporting the guide shapes or not. |
| [is_export_comments](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/is_export_comments) | Defines whether need exporting the comments or not. |
| [enlarge_page](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/enlarge_page) | Specifies whether enlarge page . |
| [emf_render_setting](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/emf_render_setting) | Setting for rendering Emf metafile. |
| [page_index](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/page_index) | Gets or sets the 0-based index of the page to render. Default is 0. |
| [export_hidden_page](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/export_hidden_page) | Defines whether need exporting the hidden page or not. |
| [quality](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/quality) | Gets or sets a value determining the quality of the generated  images<br/>to apply only when saving pages to the `Jpeg` format. The default value is 100 |
| [svg_fit_to_view_port](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/svg_fit_to_view_port) | if this property is true, the generated svg will fit to view port. |
| [export_element_as_rect_tag](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/export_element_as_rect_tag) | Defines whether need exporting rectangle elements as rect tag or not. |
| [is_export_scale_in_matrix](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/is_export_scale_in_matrix) | Defines whether need export scale in matrix or not. |
| [is_saving_image_separately](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/is_saving_image_separately) | Defines whether Saving Image Separately. |
| [is_saving_custom_line_pattern](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/is_saving_custom_line_pattern) | Defines whether Saving custom line pattern. |
| [custom_image_path](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/custom_image_path) | The user custom path(URL) saved in generated svg file for the image. If not defined by user, Current directory will be used. |


### Methods
| Method | Description |
| :- | :- |
| [create_save_options(save_format)](/diagram/python-net/aspose.diagram.saving/svgsaveoptions/create_save_options/#SaveFileFormat) | Creates a save options object of a class suitable for the specified save format. |


### See Also

* module [aspose.diagram.saving](../)
* class [RenderingSaveOptions](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions)
