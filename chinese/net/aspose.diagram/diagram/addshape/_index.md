---
title: AddShape
second_title: Aspose.Diagram for .NET API 参考
description: 将 master 创建的形状添加到特定页面
type: docs
weight: 320
url: /zh/net/aspose.diagram/diagram/addshape/
---
## AddShape(Shape, string, int) {#addshape}

将 master 创建的形状添加到特定页面。

```csharp
public long AddShape(Shape newShape, string masterName, int pageNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newShape | Shape | 新形状对象[`Shape`](../../shape/). |
| masterName | String | 大师之名。 |
| pageNumber | Int32 | 页面索引。 |

### 返回值

指定页面上形状集合中形状的唯一 ID。

### 也可以看看

* class [Shape](../../shape/)
* class [Diagram](../)
* 命名空间 [Aspose.Diagram](../../diagram/)
* 部件 [Aspose.Diagram](../../../)

---

## AddShape(double, double, string, int) {#addshape_2}

在具有定义的 PinX 和 PinY 的页面上添加由 master 创建的形状。

```csharp
public long AddShape(double pinX, double pinY, string masterName, int pageNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pinX | Double | 指定形状的图钉（旋转中心）相对于页面的 x 坐标。 |
| pinY | Double | 指定形状图钉（旋转中心）相对于页面的 y 坐标。 |
| masterName | String | 大师之名。 |
| pageNumber | Int32 | 页面索引。 |

### 返回值

指定页面上形状集合中形状的唯一 ID。

### 也可以看看

* class [Diagram](../)
* 命名空间 [Aspose.Diagram](../../diagram/)
* 部件 [Aspose.Diagram](../../../)

---

## AddShape(double, double, double, double, string, int) {#addshape_1}

添加由 master 在页面上创建的具有定义的 PinX、PinY、宽度和高度的形状。

```csharp
public long AddShape(double pinX, double pinY, double width, double height, string masterName, 
    int pageNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pinX | Double | 指定形状的图钉（旋转中心）相对于页面的 x 坐标。 |
| pinY | Double | 指定形状图钉（旋转中心）相对于页面的 y 坐标。 |
| width | Double | 以英寸为单位指定形状的宽度。 |
| height | Double | 以英寸为单位指定形状的高度。 |
| masterName | String | 大师之名。 |
| pageNumber | Int32 | 页面索引。 |

### 返回值

指定页面上形状集合中形状的唯一 ID。

### 也可以看看

* class [Diagram](../)
* 命名空间 [Aspose.Diagram](../../diagram/)
* 部件 [Aspose.Diagram](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
