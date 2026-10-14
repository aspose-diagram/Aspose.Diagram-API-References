---
title: Class ContainerProperties
second_title: Aspose.Diagram for .NET API Reference
description: Aspose.Diagram.ContainerProperties class. ContainerProperties for shape
type: docs
url: /net/aspose.diagram/containerproperties/
---
## ContainerProperties class

ContainerProperties for shape.

```csharp
public class ContainerProperties
```

## Constructors

| Name | Description |
| --- | --- |
| [ContainerProperties](containerproperties/)(Shape) | Constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ContainerStyle](../../aspose.diagram/containerproperties/containerstyle/) { get; set; } | ContainerStyle |
| [ContainerType](../../aspose.diagram/containerproperties/containertype/) { get; set; } | ContainerType |
| [HeadingStyle](../../aspose.diagram/containerproperties/headingstyle/) { get; set; } | HeadingStyle |
| [LockMembership](../../aspose.diagram/containerproperties/lockmembership/) { get; set; } | LockMembership |
| [Margin](../../aspose.diagram/containerproperties/margin/) { get; set; } | ContainerMargin |
| [ResizeAsNeeded](../../aspose.diagram/containerproperties/resizeasneeded/) { get; set; } | ResizeAsNeeded |
| [Shape](../../aspose.diagram/containerproperties/shape/) { get; } | Parent shape |

## Methods

| Name | Description |
| --- | --- |
| [AddMember](../../aspose.diagram/containerproperties/addmember/)(Shape) | Add Member to container |
| [ClearMembers](../../aspose.diagram/containerproperties/clearmembers/)() | clear members |
| [GetMemberShapes](../../aspose.diagram/containerproperties/getmembershapes/)() | get member shapes |
| [RemoveMember](../../aspose.diagram/containerproperties/removemember/)(Shape) | RemoveMember |

## Remarks

Implements the Microsoft Visio structured-diagram container model:

* Container identity, style and behavior are stored in User-defined cells: msvStructureType ("Container" / "List"), msvSDContainerStyle, msvSDHeadingStyle, msvSDContainerMargin, msvSDContainerLocked, msvSDContainerResize.
* Membership is stored in the Layout section's Relationships cell, exactly as Microsoft Visio persists it: the container keeps SUM(DEPENDSON(1, Sheet.N!SheetRef(),...)) (category 2 for lists) and each member keeps SUM(DEPENDSON(4, Sheet.N!SheetRef())) pointing back to the container.

### See Also

* namespace [Aspose.Diagram](../../aspose.diagram/)
* assembly [Aspose.Diagram](../../)


