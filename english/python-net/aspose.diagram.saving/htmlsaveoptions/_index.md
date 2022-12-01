---
title: HTMLSaveOptions class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.diagram.saving/htmlsaveoptions/
is_root: false
---

## HTMLSaveOptions class

Allows to specify additional options when rendering diagram pages to HTML.



**Inheritance:** [HTMLSaveOptions](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions) → 
[RenderingSaveOptions](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions) → 
[SaveOptions](/diagram/python-net/aspose.diagram.saving/saveoptions)



The HTMLSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [HTMLSaveOptions()](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/__init__/#) | Initializes a new instance of this class that can be used to save a document in the [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat) format. |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/save_format) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used.<br/>Can be [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat) only. |
| [default_font](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/default_font) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,<br/>they may appear as block in pdf, image or XPS.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [warning_callback](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/warning_callback) | Gets or sets warning callback. |
| [page_size](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/page_size) | Gets or sets the page size for the generated images.<br/>Can be [PageSize](/diagram/python-net/aspose.diagram.saving/pagesize) or null. |
| [shapes](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/shapes) | Gets or sets shapes to render. Default count is 0. |
| [area](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/area) | Gets or sets the area of the shapes will be saved . |
| [export_guide_shapes](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/export_guide_shapes) | Defines whether need exporting the guide shapes or not. |
| [is_export_comments](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/is_export_comments) | Defines whether need exporting the comments or not. |
| [enlarge_page](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/enlarge_page) | Specifies whether enlarge page . |
| [emf_render_setting](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/emf_render_setting) | Setting for rendering Emf metafile. |
| [title](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/title) | Gets or sets the title of diagram to render in HTML.<br/>If Title is null Diagram.DocumentProperties.Title [DocumentProperties](/diagram/python-net/aspose.diagram/documentproperties) will be  used as Title.<br/>If Diagram.DocumentProperties.Title is null or empty the file name of Diagram will be used as Title. |
| [page_count](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/page_count) | Gets or sets the number of pages to render in HTML.<br/>Default is MaxValue which means all pages of the diagram will be rendered. |
| [save_tool_bar](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/save_tool_bar) | Specifies whether saving toolbar<br/>The default value is true. |
| [page_index](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/page_index) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [export_hidden_page](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/export_hidden_page) | Defines whether need exporting the hidden page or not. |
| [save_title](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/save_title) | Defines whether need exporting the title or not. |
| [save_foreground_pages_only](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/save_foreground_pages_only) | Specifies whether all pages will be saved in image or only foreground. |
| [stream_provider](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/stream_provider) | Gets or sets the IStreamProvider for exporting objects. |
| [save_as_single_file](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/save_as_single_file) | Indicates whether save the html as single file.<br/>The default value is false. |
| [resolution](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/resolution) | Gets or sets the resolution for the generated html, in dots per inch. |


### Methods
| Method | Description |
| :- | :- |
| [create_save_options(save_format)](/diagram/python-net/aspose.diagram.saving/htmlsaveoptions/create_save_options/#SaveFileFormat) | Creates a save options object of a class suitable for the specified save format. |


### See Also

* module [aspose.diagram.saving](../)
* class [RenderingSaveOptions](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions)
