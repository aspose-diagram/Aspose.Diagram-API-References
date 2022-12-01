---
title: RenderingSaveOptions class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 140
url: /python-net/aspose.diagram.saving/renderingsaveoptions/
is_root: false
---

## RenderingSaveOptions class

This is an abstract base class for classes that allow the user to specify additional options when saving a diagram
into a particular format.



**Inheritance:** [RenderingSaveOptions](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions) → 
[SaveOptions](/diagram/python-net/aspose.diagram.saving/saveoptions)



The RenderingSaveOptions type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [save_format](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions/save_format) | Specifies the format in which the document will be saved if this save options object is used. |
| [default_font](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions/default_font) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,<br/>they may appear as block in pdf, image or XPS.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [warning_callback](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions/warning_callback) | Gets or sets warning callback. |
| [page_size](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions/page_size) | Gets or sets the page size for the generated images.<br/>Can be [PageSize](/diagram/python-net/aspose.diagram.saving/pagesize) or null. |
| [shapes](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions/shapes) | Gets or sets shapes to render. Default count is 0. |
| [area](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions/area) | Gets or sets the area of the shapes will be saved . |
| [export_guide_shapes](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions/export_guide_shapes) | Defines whether need exporting the guide shapes or not. |
| [is_export_comments](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions/is_export_comments) | Defines whether need exporting the comments or not. |
| [enlarge_page](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions/enlarge_page) | Specifies whether enlarge page . |
| [emf_render_setting](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions/emf_render_setting) | Setting for rendering Emf metafile. |


### Methods
| Method | Description |
| :- | :- |
| [create_save_options(save_format)](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions/create_save_options/#SaveFileFormat) | Creates a save options object of a class suitable for the specified save format. |


### See Also

* module [aspose.diagram.saving](../)
* class [SaveOptions](/diagram/python-net/aspose.diagram.saving/saveoptions)
