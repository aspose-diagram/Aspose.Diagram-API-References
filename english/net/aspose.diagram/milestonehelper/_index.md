---
title: Class MilestoneHelper
second_title: Aspose.Diagram for .NET API Reference
description: Aspose.Diagram.MilestoneHelper class. MilestoneHelper to set property of milestone shape
type: docs
url: /net/aspose.diagram/milestonehelper/
---
## MilestoneHelper class

MilestoneHelper to set property of milestone shape.

```csharp
public class MilestoneHelper
```

## Constructors

| Name | Description |
| --- | --- |
| [MilestoneHelper](milestonehelper/)(Shape) | MilestoneHelper. |

## Properties

| Name | Description |
| --- | --- |
| [DateFormat](../../aspose.diagram/milestonehelper/dateformat/) { get; set; } | DateFormat of shape (0 - 30) |
| [IsAutoUpdate](../../aspose.diagram/milestonehelper/isautoupdate/) { get; set; } | whether to update data for markers (milestones, intervals) as they are moved on timeline |
| [MilestoneDate](../../aspose.diagram/milestonehelper/milestonedate/) { get; set; } | Milestone date |
| [Type](../../aspose.diagram/milestonehelper/type/) { get; set; } | Type of shape (0 = Circle ... 8 = Pin) |

## Methods

| Name | Description |
| --- | --- |
| [RefreshMilestone](../../aspose.diagram/milestonehelper/refreshmilestone/)(Shape) | Refresh milestone |

## Remarks

Compatibility shell over [`MilestoneProperties`](../milestoneproperties/): the public API is unchanged (plus getters for the previously write-only properties), the cell access is delegated to the properties class, and [`RefreshMilestone`](./refreshmilestone/) is rewritten:

* Children without a master no longer crash the refresh (the old code dereferenced child.MasterShape unconditionally).
* An existing local date field is updated in place; the old code appended a new field on every refresh.
* Positioning reads the timeline's left edge from XForm (the old code read XForm1D.BeginX, which does not exist on a 2-D group shape) and sorts the dated children with two parallel arrays instead of the SortedStringList, which has no Java counterpart.

### See Also

* namespace [Aspose.Diagram](../../aspose.diagram/)
* assembly [Aspose.Diagram](../../)


