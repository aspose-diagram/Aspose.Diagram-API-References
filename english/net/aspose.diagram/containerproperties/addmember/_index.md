---
title: ContainerProperties.AddMember
second_title: Aspose.Diagram for .NET API Reference
description: ContainerProperties method. Add Member to container
type: docs
url: /net/aspose.diagram/containerproperties/addmember/
---
## ContainerProperties.AddMember method

Add Member to container

```csharp
public void AddMember(Shape shape)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | shape to add |

## Remarks

Writes the same Relationships cells Microsoft Visio writes when a shape is dropped onto a container: DEPENDSON(4, Sheet.N!SheetRef()) on the member and DEPENDSON(1, Sheet.N!SheetRef()) on the container (DEPENDSON(2,...) for lists). A shape belongs to a single container in Visio, so existing container membership is removed first, unless the previous container is locked.

### See Also

* class [Shape](../../shape/)
* class [ContainerProperties](../)
* namespace [Aspose.Diagram](../../containerproperties/)
* assembly [Aspose.Diagram](../../../)


