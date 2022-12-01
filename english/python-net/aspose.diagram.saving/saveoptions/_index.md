---
title: SaveOptions class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 170
url: /python-net/aspose.diagram.saving/saveoptions/
is_root: false
---

## SaveOptions class

This is an abstract base class for classes that allow the user to specify additional options when saving a diagram
into a particular format.



The SaveOptions type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [save_format](/diagram/python-net/aspose.diagram.saving/saveoptions/save_format) | Specifies the format in which the document will be saved if this save options object is used. |
| [default_font](/diagram/python-net/aspose.diagram.saving/saveoptions/default_font) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,<br/>they may appear as block in pdf, image or XPS.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [warning_callback](/diagram/python-net/aspose.diagram.saving/saveoptions/warning_callback) | Gets or sets warning callback. |


### Methods
| Method | Description |
| :- | :- |
| [create_save_options(save_format)](/diagram/python-net/aspose.diagram.saving/saveoptions/create_save_options/#SaveFileFormat) |  |


### Remarks 


An instance of the SaveOptions class or any derived class is passed to the stream Save or string Save overloads
for the user to define custom options when saving a document.
### See Also

* module [aspose.diagram.saving](../)
