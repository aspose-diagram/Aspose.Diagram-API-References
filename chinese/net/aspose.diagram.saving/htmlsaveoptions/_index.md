---
title: HTMLSaveOptions
second_title: Aspose.Diagram for .NET API 参考
description: 允许在将图表页面呈现为 HTML 时指定其他选项
type: docs
weight: 3230
url: /zh/net/aspose.diagram.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

允许在将图表页面呈现为 HTML 时指定其他选项。

```csharp
public class HTMLSaveOptions : RenderingSaveOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions)() | 初始化此类的新实例，该实例可用于将文档保存在[`HTML`](../../aspose.diagram/savefileformat) 格式。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area) { get; set; } | 获取或设置要保存的形状区域。 |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | 当图中的字符是 unicode 并且没有设置正确的字体值或本地没有安装字体时， 它们可能会显示为块pdf、图像或 XPS 格式。 设置默认字体如 MingLiu 或 MS Gothic 以显示这些字符。 |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting) { get; set; } | 渲染 Emf 图元文件的设置。 |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage) { get; set; } | 指定是否放大页面。 |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes) { get; set; } | 定义是否需要导出导向形状。 |
| [ExportHiddenPage](../../aspose.diagram.saving/htmlsaveoptions/exporthiddenpage) { get; set; } | 定义是否需要导出隐藏页面。 |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments) { get; set; } | 定义是否需要导出评论。 |
| [PageCount](../../aspose.diagram.saving/htmlsaveoptions/pagecount) { get; set; } | 获取或设置要在 HTML 中呈现的页面数。 默认为 MaxValue，这意味着将呈现图表的所有页面。 |
| [PageIndex](../../aspose.diagram.saving/htmlsaveoptions/pageindex) { get; set; } | 获取或设置要呈现的第一页的从 0 开始的索引。默认值为 0。 |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize) { get; set; } | 获取或设置生成图像的页面大小。 可以是[`PageSize`](../pagesize) 或 null。 |
| [Resolution](../../aspose.diagram.saving/htmlsaveoptions/resolution) { get; set; } | 获取或设置生成的 html 的分辨率，以每英寸点数为单位。 |
| [SaveAsSingleFile](../../aspose.diagram.saving/htmlsaveoptions/saveassinglefile) { get; set; } | 表示是否将html保存为单个文件。 默认值为假。 |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/htmlsaveoptions/saveforegroundpagesonly) { get; set; } | 指定所有页面将保存在图像中还是仅在前景中。 |
| override [SaveFormat](../../aspose.diagram.saving/htmlsaveoptions/saveformat) { get; set; } | 如果使用此保存选项对象，则指定保存渲染图表页面的格式。 只能是[`HTML`](../../aspose.diagram/savefileformat) 。 |
| [SaveTitle](../../aspose.diagram.saving/htmlsaveoptions/savetitle) { get; set; } | 定义是否需要导出标题。 |
| [SaveToolBar](../../aspose.diagram.saving/htmlsaveoptions/savetoolbar) { get; set; } | 指定是否保存工具栏 默认值为true。 |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes) { get; set; } | 获取或设置要渲染的形状。默认计数为 0。 |
| [StreamProvider](../../aspose.diagram.saving/htmlsaveoptions/streamprovider) { get; set; } | 获取或设置用于导出对象的 IStreamProvider。 |
| [Title](../../aspose.diagram.saving/htmlsaveoptions/title) { get; set; } | 获取或设置要在 HTML 中呈现的图表的标题。 如果 Title 为空 Diagram.DocumentProperties.Title[`DocumentProperties`](../../aspose.diagram/documentproperties)将用作标题。 如果 Diagram.DocumentProperties.Title 为 null 或为空，Diagram 的文件名将用作 Title。 |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | 获取或设置警告回调。 |

### 也可以看看

* class [RenderingSaveOptions](../renderingsaveoptions)
* 命名空间 [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* 部件 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
