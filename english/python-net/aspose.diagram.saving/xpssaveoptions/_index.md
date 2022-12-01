---
title: XPSSaveOptions class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 190
url: /python-net/aspose.diagram.saving/xpssaveoptions/
is_root: false
---

## XPSSaveOptions class

Allows to specify additional options when rendering diagram pages to XPS.



**Inheritance:** [XPSSaveOptions](/diagram/python-net/aspose.diagram.saving/xpssaveoptions) → 
[SaveOptions](/diagram/python-net/aspose.diagram.saving/saveoptions)



The XPSSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [XPSSaveOptions()](/diagram/python-net/aspose.diagram.saving/xpssaveoptions/__init__/#) | Initializes a new instance of this class that can be used to save a document in the [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat) format. |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/diagram/python-net/aspose.diagram.saving/xpssaveoptions/save_format) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used.<br/>Can be [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat) only. |
| [default_font](/diagram/python-net/aspose.diagram.saving/xpssaveoptions/default_font) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,<br/>they may appear as block in pdf, image or XPS.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [warning_callback](/diagram/python-net/aspose.diagram.saving/xpssaveoptions/warning_callback) | Gets or sets warning callback. |
| [page_count](/diagram/python-net/aspose.diagram.saving/xpssaveoptions/page_count) | Gets or sets the number of pages to render in XPS.<br/>Default is MaxValue which means all pages of the diagram will be rendered. |
| [page_index](/diagram/python-net/aspose.diagram.saving/xpssaveoptions/page_index) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [save_foreground_pages_only](/diagram/python-net/aspose.diagram.saving/xpssaveoptions/save_foreground_pages_only) | Specifies whether all pages will be saved in image or only foreground. |
| [export_hidden_page](/diagram/python-net/aspose.diagram.saving/xpssaveoptions/export_hidden_page) | Defines whether need exporting the hidden page or not. |


### Methods
| Method | Description |
| :- | :- |
| [create_save_options(save_format)](/diagram/python-net/aspose.diagram.saving/xpssaveoptions/create_save_options/#SaveFileFormat) | Creates a save options object of a class suitable for the specified save format. |


### See Also

* module [aspose.diagram.saving](../)
* class [SaveOptions](/diagram/python-net/aspose.diagram.saving/saveoptions)
