---
title: Diagram
second_title: Aspose.Diagram for .NET API 参考
description: Visio 对象层次结构的根元素
type: docs
weight: 1170
url: /zh/net/aspose.diagram/diagram/
---
## Diagram class

Visio 对象层次结构的根元素。

```csharp
public class Diagram : IDisposable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Diagram](diagram/#constructor)() | 默认构造函数。 |
| [Diagram](diagram/#constructor_1)(Stream) | 公共类构造函数， 从流中加载图表。 |
| [Diagram](diagram/#constructor_4)(string) | 公共类构造函数， 从文件加载图表。 |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | 公共类构造函数， 使用预定义格式从流中加载图表。 |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | 公共类构造函数， 使用预定义的加载文件选项从流中加载图表。 |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | 公共类构造函数， 使用预定义格式从文件中加载图表。 |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | 公共类构造函数， 使用预定义的加载文件选项从文件加载图表。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | 指定活动页面 |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | 用于创建文档的 Visio 实例的内部版本号。 |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | 包含文档的颜色表。每个文档都包含一个颜色表 ，其中列出了可应用于对象 （例如文档中的形状、文本和图层）的 24 种标准颜色。 |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | 包含文档的 DataConnection 元素。 |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | 与 Document 对象关联的 DataRecordset 对象的集合。 |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | 用户在 Microsoft Office 2010 语言首选项中指定的用户界面语言的唯一 ID。 |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | 包含文档属性元素，例如文档的标题、作者等。 |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | 包含指定文档设置的元素。 |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | 指定文档的 ShapeSheet 结构。 |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | 包含文档的 MIME（多用途 Internet 邮件扩展）编码的 MAPI 电子邮件路由单。 |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | 包含对象应响应的每个事件的 EventItem 元素。 |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | 表示字体文件夹路径 |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | 包含字体元素的集合 |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | 包含文档页眉和页脚的元素。 |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | 获取和设置中断监视器。 |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | 指示文档是否已在 Visio 之外修改。如果存在，Visio 将完全测试文件的内容。省略在 Visio 之外创建的文件。 |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | 集合主对象。 |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | 绘图中是否使用公制单位。将此属性设置为 True (1) 以使用公制单位；将其设置为 False (0) 以使用英制单位。 |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | 集合页面对象。 |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | 传递给文档以自定义功能区用户界面的功能区 XML 字符串。 |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | XML 值。 |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | 指示文档是否已在 Visio 之外修改。 如果存在，Visio 将完全测试文件的内容。省略在 Visio 之外创建的文件。 |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | 集合样式表对象。 |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | 传递给文档以自定义快速访问工具栏或功能区的功能区 XML 字符串。 |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | 存储有关文档图表验证的信息。 |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | 获取 VbaProject[`VbaProject`](./vbaproject/). |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | 包含 MIME（多用途 Internet 邮件扩展）编码格式的 Microsoft Visual Basic for Applications 项目数据。 |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Visio 实例的版本号。微软 Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | 包含文档的 Window 元素。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | 通过 master 的名称或 NameU. 从源图添加 master 到图 |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | 通过 master 的 ID 从模板流将 master 添加到图中。 |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | 通过 master 的名称或 NameU. 从模板流将 master 添加到图表 |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | 通过 master 的 ID 从模板文件将 master 添加到图中。 |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | 通过 master 的名称或 NameU. 从模板文件将 master 添加到图表 |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | 将 master 创建的形状添加到特定页面。 |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | 在具有定义的 PinX 和 PinY 的页面上添加由 master 创建的形状。 |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | 添加由 master 在页面上创建的具有定义的 PinX、PinY、宽度和高度的形状。 |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | 组合另一个 Diagram 对象。 |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | 从源图中复制主题。 |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | 执行与释放、释放或 重置非托管资源相关的应用程序定义的任务。 |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | 获取默认字体文件夹路径 |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | 获取未使用的 Styles |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | 表示这张图是否有隐藏信息。 |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | 布置形状和/或重新布置图表所有页面的连接器。 |
| [Print](../../aspose.diagram/diagram/print/#print)() | 将整个文档打印到默认打印机。 |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | 根据指定的打印机设置打印文档，使用标准（无用户界面）打印控制器。 |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | 将整个文档打印到默认打印机。 |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | 将整个文档打印到指定打印机，使用标准（无用户界面）打印控制器。 |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | 根据指定的打印机设置打印文档，使用标准（无用户界面）打印控制器。 |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | 根据指定的打印机设置打印文档，使用标准（无用户界面）打印控制器和文档名称。 |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | 将整个文档打印到指定打印机，使用标准（无用户界面）打印控制器。 |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | 使用标准（无用户界面）打印控制器和文档名称打印文档。 |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | 根据指定的打印机设置打印文档，使用标准（无用户界面）打印控制器和文档名称。 |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | 使用标准（无用户界面）打印控制器和文档名称打印文档。 |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | 为 Diagram 中的所有 DataRecordSet 调用 Refresh 方法。 |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | 删除未使用的信息 |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | 从此图中删除 VBA/宏。 |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | 将图表数据保存到流中。 |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | 使用指定的保存选项将图表保存到流中。 |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | 将图表数据保存到文件中。 |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | 使用指定的保存选项将文档保存到文件。 |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | 将图表从 vsd 流导出为 vdw 流格式。尚未实施。 |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | 将图表从 vsd 流导出为 *.vdw 文件格式。尚未实施。 |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | 将图表从 vsd 文件导出为 vdw 流格式。尚未实施。 |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | 将图表从 vsd 导出为 vdw 格式。尚未实施。 |

### 也可以看看

* 命名空间 [Aspose.Diagram](../../aspose.diagram/)
* 部件 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
