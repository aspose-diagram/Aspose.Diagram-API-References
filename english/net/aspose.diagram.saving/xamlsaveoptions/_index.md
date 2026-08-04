---
title: Class XAMLSaveOptions
second_title: Aspose.Diagram for .NET API Reference
description: Aspose.Diagram.Saving.XAMLSaveOptions class. Allows to specify additional options when rendering diagram pages to XAML
type: docs
url: /net/aspose.diagram.saving/xamlsaveoptions/
---
## XAMLSaveOptions class

Allows to specify additional options when rendering diagram pages to XAML.

```csharp
public class XAMLSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XAMLSaveOptions](xamlsaveoptions/)() | Initializes a new instance of this class that can be used to save a document in the [`XAML`](../../aspose.diagram/savefileformat/) format. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | When characters in the diagram are unicode and not be set with correct font value or the font is not installed locally, they may appear as block in pdf, image or XPS. Set the DefaultFont such as MingLiu or MS Gothic to show these characters. |
| [PageCount](../../aspose.diagram.saving/xamlsaveoptions/pagecount/) { get; set; } | Gets or sets the number of pages to render in XAML. Default is MaxValue which means all pages of the diagram will be rendered. |
| [PageIndex](../../aspose.diagram.saving/xamlsaveoptions/pageindex/) { get; set; } | Gets or sets the 0-based index of the first page to render. Default is 0. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/xamlsaveoptions/saveforegroundpagesonly/) { get; set; } | Specifies whether all pages will be saved in image or only foreground. |
| override [SaveFormat](../../aspose.diagram.saving/xamlsaveoptions/saveformat/) { get; set; } | Specifies the format in which the rendered diagram pages will be saved if this save options object is used. Can be [`XAML`](../../aspose.diagram/savefileformat/) only. |
| [StreamProvider](../../aspose.diagram.saving/xamlsaveoptions/streamprovider/) { get; set; } | Gets or sets the IStreamProvider for exporting objects. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Gets or sets warning callback. |

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* assembly [Aspose.Diagram](../../)


