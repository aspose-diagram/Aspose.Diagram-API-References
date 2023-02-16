---
title: Page
second_title: Aspose.Diagram for .NET API 参考
description: 包含定义文档中页面的元素
type: docs
weight: 2490
url: /zh/net/aspose.diagram/page/
---
## Page class

包含定义文档中页面的元素。

```csharp
public class Page : IDisposable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Page](page/#constructor)() | 构造函数. |
| [Page](page/#constructor_1)(int) | 构造函数. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | 原始绘图页的 ID，由绘图审阅者标记在单独的标记叠加层上。 |
| [Background](../../aspose.diagram/page/background/) { get; set; } | 指示页面是否为背景页面的标志。 |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | 页面的背景页面。 |
| [Connects](../../aspose.diagram/page/connects/) { get; } | 为绘图中两个形状之间的每个连接包含一个连接元素。 |
| [ID](../../aspose.diagram/page/id/) { get; set; } | 元素在其父元素中的唯一 ID。 |
| [Name](../../aspose.diagram/page/name/) { get; set; } | 元素的名称。 |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | 元素的通用名称。 |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | 页面集合. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | 包含为 Page 或 Master 元素定义页表的元素。 |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | 将预设主题应用于此页面 |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | 将预设主题变体 quickstyle 应用到此页面 |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | 将预设主题变体应用于此页面 |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | 与标记覆盖关联的审阅者的 ID。 |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | 形状集合. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX 和 ViewCenterY 指定页面上的中心点，新视图（窗口）最初打开时采用该中心点。 |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX 和 ViewCenterY 指定页面上的中心点，新视图（窗口）最初打开时采用该中心点。 |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | 打开页面的新视图（窗口）时使用的默认放大系数。例如，1 = 100%； 1.5 = 150%，依此类推。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | 创建一个 Activex 控件。 |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | 向具有形状 ID 的形状添加注释。 |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | 向形状添加注释。 |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | 添加带有定义的 PinX 和 PinY 的注释。 |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | 将 master 创建的形状添加到特定页面。 |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | 在具有定义的 PinX 和 PinY 的页面上添加由 master 创建的形状。 |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | 添加由 master 在页面上创建的具有定义的 PinX、PinY、宽度和高度的形状。 |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | 添加具有定义的 PinX 和 PinY 的文本。 |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | 添加具有定义的 PinX 和 PinY 的文本。 |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | 为整页应用样式。 |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | 自动空间形状 |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | 带来一个由 ID 定义的形状，在 z 顺序中向前移动一个位置。 |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | 将由 ID 定义的形状带到 z 顺序的前面。 |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | 使页面的形状相对于页面的范围居中。 使形状居中不会改变它们相对于彼此的位置。 |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | 通过连接器连接形状。 |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | 通过连接器连接形状。 |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | 通过连接器连接形状。 |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | 通过连接器索引连接形状。 |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | 通过连接器索引连接形状。 |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | 执行与释放、释放或 重置非托管资源相关的应用程序定义的任务。 |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | 绘制贝塞尔曲线的过程。 点的长度要等于或大于3. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | 画椭圆的过程。 |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | 画单线的过程。 |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | 画线的过程。 |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | 画线的过程。 |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | 绘制Polyline的过程。 |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | 绘制折线的过程。 |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | 绘制矩形的过程。 |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | 绘制spline的过程。 |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | 胶水形状 |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | 胶水形状. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | 容器中的胶水形状 |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | 使用连接名称 在容器中粘贴形状 |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | 通过连接 id 在 container 中粘合形状 |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | 将形状粘附到连接器的 BeginX |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | 将形状粘贴到连接器的 EndX |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | 布置形状和/或重新布置页面的连接器。 |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | 将页面移动到页面中的另一个位置。 |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | 将由 ID 定义的形状移回 z 顺序中的一个位置。 |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | 将由 ID 定义的形状移动到 z 顺序的后面。 |

### 也可以看看

* 命名空间 [Aspose.Diagram](../../aspose.diagram/)
* 部件 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
