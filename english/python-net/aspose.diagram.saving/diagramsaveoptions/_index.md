---
title: DiagramSaveOptions class
second_title: Aspose.Diagram for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/aspose.diagram.saving/diagramsaveoptions/
is_root: false
---

## DiagramSaveOptions class

Can be used to specify additional options when saving a diagram into Visio (VDX\VSX) format.



**Inheritance:** [DiagramSaveOptions](/diagram/python-net/aspose.diagram.saving/diagramsaveoptions) → 
[SaveOptions](/diagram/python-net/aspose.diagram.saving/saveoptions)



The DiagramSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [DiagramSaveOptions()](/diagram/python-net/aspose.diagram.saving/diagramsaveoptions/__init__/#) | Initializes a new instance of this class that can be used to save a diagram in the VDX format. |
| [DiagramSaveOptions(save_format)](/diagram/python-net/aspose.diagram.saving/diagramsaveoptions/__init__/#SaveFileFormat) | Initializes a new instance of this class that can be used to save a diagram in the VDX or VSX format. |


### Properties
| Property | Description |
| :- | :- |
| [save_format](/diagram/python-net/aspose.diagram.saving/diagramsaveoptions/save_format) | Specifies the format in which the rendered diagram will be saved if this save options object is used.<br/>Can be [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat) or [SaveFileFormat](/diagram/python-net/aspose.diagram/savefileformat). |
| [default_font](/diagram/python-net/aspose.diagram.saving/diagramsaveoptions/default_font) | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally,<br/>they may appear as block in pdf, image or XPS.<br/>Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [warning_callback](/diagram/python-net/aspose.diagram.saving/diagramsaveoptions/warning_callback) | Gets or sets warning callback. |
| [auto_fit_page_to_drawing_content](/diagram/python-net/aspose.diagram.saving/diagramsaveoptions/auto_fit_page_to_drawing_content) | Defines whether need enlarge page to fit drawing content or not. |


### Methods
| Method | Description |
| :- | :- |
| [create_save_options(save_format)](/diagram/python-net/aspose.diagram.saving/diagramsaveoptions/create_save_options/#SaveFileFormat) | Creates a save options object of a class suitable for the specified save format. |


### Remarks 


At the moment provides only the SaveFormat property, but in the future will have other options added.
### See Also

* module [aspose.diagram.saving](../)
* class [SaveOptions](/diagram/python-net/aspose.diagram.saving/saveoptions)
