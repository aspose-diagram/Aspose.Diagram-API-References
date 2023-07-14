---
title: Diagram.AddShape
second_title: Aspose.Diagram for .NET API Reference
description: Diagram method. Adds shape created by master to specific page
type: docs
url: /net/aspose.diagram/diagram/addshape/
---
## AddShape(Shape, string, int) {#addshape}

Adds shape created by master to specific page.

```csharp
public long AddShape(Shape newShape, string masterName, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newShape | Shape | New shape object[`Shape`](../../shape/). |
| masterName | String | Master's name. |
| pageNumber | Int32 | Index of page. |

### Return Value

The unique ID of the shape within shapes collection on the specified page.

### See Also

* class [Shape](../../shape/)
* class [Diagram](../)
* namespace [Aspose.Diagram](../../diagram/)
* assembly [Aspose.Diagram](../../../)

---

## AddShape(double, double, string, int) {#addshape_2}

Adds shape created by master on page with defined PinX and PinY.

```csharp
public long AddShape(double pinX, double pinY, string masterName, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Double | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Double | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| masterName | String | Master's name. |
| pageNumber | Int32 | Index of page. |

### Return Value

The unique ID of the shape within shapes collection on the specified page.

### See Also

* class [Diagram](../)
* namespace [Aspose.Diagram](../../diagram/)
* assembly [Aspose.Diagram](../../../)

---

## AddShape(double, double, double, double, string, int) {#addshape_1}

Adds shape created by master on page with defined PinX,PinY,Width and Height.

```csharp
public long AddShape(double pinX, double pinY, double width, double height, string masterName, 
    int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Double | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Double | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | Double | Specifies the width of the shape in inches. |
| height | Double | Specifies the height of the shape in inches. |
| masterName | String | Master's name. |
| pageNumber | Int32 | Index of page. |

### Return Value

The unique ID of the shape within shapes collection on the specified page.

### See Also

* class [Diagram](../)
* namespace [Aspose.Diagram](../../diagram/)
* assembly [Aspose.Diagram](../../../)


