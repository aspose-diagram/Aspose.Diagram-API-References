---
title: SaveOptions
second_title: Aspose.Diagram for .NET API 参考
description: 这是类的抽象基类允许用户在将图表 保存为特定格式时指定其他选项
type: docs
weight: 3470
url: /zh/net/aspose.diagram.saving/saveoptions/
---
## SaveOptions class

这是类的抽象基类，允许用户在将图表 保存为特定格式时指定其他选项。

```csharp
public abstract class SaveOptions
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | 当图中的字符是 unicode 并且没有设置正确的字体值或本地没有安装字体时， 它们可能会显示为块pdf、图像或 XPS 格式。 设置默认字体如 MingLiu 或 MS Gothic 以显示这些字符。 |
| virtual [SaveFormat](../../aspose.diagram.saving/saveoptions/saveformat) { get; set; } | 如果使用此保存选项对象，则指定保存文档的格式。 |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | 获取或设置警告回调。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [CreateSaveOptions](../../aspose.diagram.saving/saveoptions/createsaveoptions)(SaveFileFormat) | 创建适合指定保存格式的类的保存选项对象。 |

### 评论

SaveOptions 类或任何派生类的实例被传递到流 Save 或 string Save 重载 供用户在保存文档时定义自定义选项。

### 也可以看看

* 命名空间 [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* 部件 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
