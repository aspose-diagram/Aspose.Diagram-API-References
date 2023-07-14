---
title: Class DiagramSaveOptions
second_title: Aspose.Diagram for .NET API Reference
description: Aspose.Diagram.Saving.DiagramSaveOptions class. Can be used to specify additional options when saving a diagram into Visio VDXVSX format
type: docs
url: /net/aspose.diagram.saving/diagramsaveoptions/
---
## DiagramSaveOptions class

Can be used to specify additional options when saving a diagram into Visio (VDX\VSX) format.

```csharp
public class DiagramSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [DiagramSaveOptions](diagramsaveoptions/#constructor)() | Initializes a new instance of this class that can be used to save a diagram in the VDX format. |
| [DiagramSaveOptions](diagramsaveoptions/#constructor_1)(SaveFileFormat) | Initializes a new instance of this class that can be used to save a diagram in the VDX or VSX format. |

## Properties

| Name | Description |
| --- | --- |
| virtual [AutoFitPageToDrawingContent](../../aspose.diagram.saving/diagramsaveoptions/autofitpagetodrawingcontent/) { get; set; } | Defines whether need enlarge page to fit drawing content or not. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| override [SaveFormat](../../aspose.diagram.saving/diagramsaveoptions/saveformat/) { get; set; } | Specifies the format in which the rendered diagram will be saved if this save options object is used. Can be [`VDX`](../../aspose.diagram/savefileformat/) or [`VSX`](../../aspose.diagram/savefileformat/). |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Gets or sets warning callback. |

## Remarks

At the moment provides only the SaveFormat property, but in the future will have other options added.

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* assembly [Aspose.Diagram](../../)


