---
title: PrintSaveOptions class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 130
url: /python-net/aspose.diagram.saving/printsaveoptions/
is_root: false
---

## PrintSaveOptions class

Allows to specify additional options when printing diagram.



**Inheritance:** [PrintSaveOptions](/diagram/python-net/aspose.diagram.saving/printsaveoptions) → 
[RenderingSaveOptions](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions) → 
[SaveOptions](/diagram/python-net/aspose.diagram.saving/saveoptions)



The PrintSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [PrintSaveOptions()](/diagram/python-net/aspose.diagram.saving/printsaveoptions/__init__/#) | Initializes a new instance of this class |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/diagram/python-net/aspose.diagram.saving/printsaveoptions/save_format) | Specifies the format in which the document will be saved if this save options object is used. |
| [default_font](/diagram/python-net/aspose.diagram.saving/printsaveoptions/default_font) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,<br/>they may appear as block in pdf, image or XPS.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [warning_callback](/diagram/python-net/aspose.diagram.saving/printsaveoptions/warning_callback) | Gets or sets warning callback. |
| [page_size](/diagram/python-net/aspose.diagram.saving/printsaveoptions/page_size) | Gets or sets the page size for the generated images.<br/>Can be [PageSize](/diagram/python-net/aspose.diagram.saving/pagesize) or null. |
| [shapes](/diagram/python-net/aspose.diagram.saving/printsaveoptions/shapes) | Gets or sets shapes to render. Default count is 0. |
| [area](/diagram/python-net/aspose.diagram.saving/printsaveoptions/area) | Gets or sets the area of the shapes will be saved . |
| [export_guide_shapes](/diagram/python-net/aspose.diagram.saving/printsaveoptions/export_guide_shapes) | Defines whether need exporting the guide shapes or not. |
| [is_export_comments](/diagram/python-net/aspose.diagram.saving/printsaveoptions/is_export_comments) | Defines whether need exporting the comments or not. |
| [enlarge_page](/diagram/python-net/aspose.diagram.saving/printsaveoptions/enlarge_page) | Specifies whether enlarge page . |
| [emf_render_setting](/diagram/python-net/aspose.diagram.saving/printsaveoptions/emf_render_setting) | Setting for rendering Emf metafile. |
| [page_count](/diagram/python-net/aspose.diagram.saving/printsaveoptions/page_count) | Gets or sets the number of pages to render when saving to a multipage file.<br/>Default is MaxValue which means all pages of the diagram will be printed. |
| [save_foreground_pages_only](/diagram/python-net/aspose.diagram.saving/printsaveoptions/save_foreground_pages_only) | Specifies whether all pages will be printed or only foreground. |


### Methods
| Method | Description |
| :- | :- |
| [create_save_options(save_format)](/diagram/python-net/aspose.diagram.saving/printsaveoptions/create_save_options/#SaveFileFormat) | Creates a save options object of a class suitable for the specified save format. |


### See Also

* module [aspose.diagram.saving](../)
* class [RenderingSaveOptions](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions)
