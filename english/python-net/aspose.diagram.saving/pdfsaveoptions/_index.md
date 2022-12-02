﻿---
title: PdfSaveOptions class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 120
url: /python-net/aspose.diagram.saving/pdfsaveoptions/
is_root: false
---

## PdfSaveOptions class

Allows to specify additional options when rendering diagram pages to PDF.



**Inheritance:** [PdfSaveOptions](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions) → 
[RenderingSaveOptions](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions) → 
[SaveOptions](/diagram/python-net/aspose.diagram.saving/saveoptions)



The PdfSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [PdfSaveOptions()](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/__init__/#) | Initializes a new instance of this class that can be used to save a document in the [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat) format. |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/save_format) | Specifies the format in which the rendered diagram pages will be saved if this save options object is used.
| [default_font](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/default_font) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,
| [warning_callback](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/warning_callback) | Gets or sets warning callback. |
| [page_size](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/page_size) | Gets or sets the page size for the generated images.
| [shapes](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/shapes) | Gets or sets shapes to render. Default count is 0. |
| [area](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/area) | Gets or sets the area of the shapes will be saved . |
| [export_guide_shapes](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/export_guide_shapes) | Defines whether need exporting the guide shapes or not. |
| [is_export_comments](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/is_export_comments) | Defines whether need exporting the comments or not. |
| [enlarge_page](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/enlarge_page) | Specifies whether enlarge page . |
| [emf_render_setting](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/emf_render_setting) | Setting for rendering Emf metafile. |
| [page_count](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/page_count) | Gets or sets the number of pages to render in PDF.
| [page_index](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/page_index) | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [save_foreground_pages_only](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/save_foreground_pages_only) | Specifies whether all pages will be saved in image or only foreground. |
| [compliance](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/compliance) | Desired conformance level for generated PDF document.
| [encryption_details](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/encryption_details) | Gets or sets a encryption details. If not set, then no encryption will be performed. |
| [page_saving_callback](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/page_saving_callback) | Control/Indicate progress of page saving process. |
| [jpeg_quality](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/jpeg_quality) | Specifies the quality of JPEG compression for images (if JPEG compression is used).
| [horizontal_resolution](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/horizontal_resolution) | Gets or sets the horizontal resolution for generated images, in dots per inch.
| [vertical_resolution](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/vertical_resolution) | Gets or sets the vertical  resolution for generated images, in dots per inch.
| [split_multi_pages](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/split_multi_pages) | Defines whether split diagram to multi pages according to page's setting. |
| [export_hidden_page](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/export_hidden_page) | Defines whether need exporting the hidden page or not. |
| [text_compression](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/text_compression) | Specifies compression type to be used for all content streams except images.
| [digital_signature_details](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/digital_signature_details) | Gets or sets a digital signature details. If not set, then no signing will be performed. |


### Methods
| Method | Description |
| :- | :- |
| [create_save_options(save_format)](/diagram/python-net/aspose.diagram.saving/pdfsaveoptions/create_save_options/#SaveFileFormat) | Creates a save options object of a class suitable for the specified save format. |


### See Also

* module [aspose.diagram.saving](../)
* class [RenderingSaveOptions](/diagram/python-net/aspose.diagram.saving/renderingsaveoptions)