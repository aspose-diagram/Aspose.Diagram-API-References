---
title: PrintSaveOptions
second_title: Aspose.Diagram for .NET API 参考
description: 允许在打印图表时指定附加选项
type: docs
weight: 3430
url: /zh/net/aspose.diagram.saving/printsaveoptions/
---
## PrintSaveOptions class

允许在打印图表时指定附加选项。

```csharp
public class PrintSaveOptions : RenderingSaveOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PrintSaveOptions](printsaveoptions)() | 初始化此类的新实例 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area) { get; set; } | 获取或设置要保存的形状区域。 |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | 当图中的字符是 unicode 并且没有设置正确的字体值或本地没有安装字体时， 它们可能会显示为块pdf、图像或 XPS 格式。 设置默认字体如 MingLiu 或 MS Gothic 以显示这些字符。 |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting) { get; set; } | 渲染 Emf 图元文件的设置。 |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage) { get; set; } | 指定是否放大页面。 |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes) { get; set; } | 定义是否需要导出导向形状。 |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments) { get; set; } | 定义是否需要导出评论。 |
| [PageCount](../../aspose.diagram.saving/printsaveoptions/pagecount) { get; set; } | 获取或设置保存到多页文件时要呈现的页数。 默认为 MaxValue，这意味着将打印图表的所有页面。 |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize) { get; set; } | 获取或设置生成图像的页面大小。 可以是[`PageSize`](../pagesize) 或 null。 |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/printsaveoptions/saveforegroundpagesonly) { get; set; } | 指定是打印所有页面还是仅打印前景。 |
| virtual [SaveFormat](../../aspose.diagram.saving/saveoptions/saveformat) { get; set; } | 如果使用此保存选项对象，则指定保存文档的格式。 |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes) { get; set; } | 获取或设置要渲染的形状。默认计数为 0。 |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | 获取或设置警告回调。 |

### 也可以看看

* class [RenderingSaveOptions](../renderingsaveoptions)
* 命名空间 [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* 部件 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
