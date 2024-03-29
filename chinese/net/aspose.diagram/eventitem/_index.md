---
title: EventItem
second_title: Aspose.Diagram for .NET API 参考
description: 封装事件代码 EventItem 元素可以触发两种操作它可以运行附加组件或者它可以向调用程序发送事件通知
type: docs
weight: 1420
url: /zh/net/aspose.diagram/eventitem/
---
## EventItem class

封装事件代码。 EventItem 元素可以触发两种操作：它可以运行附加组件，或者它可以向调用程序发送事件通知。

```csharp
public class EventItem
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EventItem](eventitem/)() | 构造函数. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Action](../../aspose.diagram/eventitem/action/) { get; set; } | 指定父 EventItem 元素的操作代码。对于要保存在 DatadiagramML 文件中的 EventItem 元素，它必须是持久的。目前，持久化事件可以拥有的唯一有效操作代码是 1 (ONEVENT_ACT_RUNADDON). |
| [Enabled](../../aspose.diagram/eventitem/enabled/) { get; set; } | 表示一个标志，指示事件是启用还是禁用。 |
| [EventCode](../../aspose.diagram/eventitem/eventcode/) { get; set; } | 指示触发附加组件的事件的代码。有关事件代码的详细信息，请参阅 Microsoft Visio 2007 自动化参考中的事件代码。 |
| [ID](../../aspose.diagram/eventitem/id/) { get; set; } | 事件的 ID。 |
| [Target](../../aspose.diagram/eventitem/target/) { get; set; } | 指定事件的目标。 |
| [TargetArgs](../../aspose.diagram/eventitem/targetargs/) { get; set; } | 指定包含要发送到事件目标的参数的字符串。 |

### 也可以看看

* 命名空间 [Aspose.Diagram](../../aspose.diagram/)
* 部件 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
