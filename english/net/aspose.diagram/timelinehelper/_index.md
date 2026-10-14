---
title: Class TimeLineHelper
second_title: Aspose.Diagram for .NET API Reference
description: Aspose.Diagram.TimeLineHelper class. TimeLineHelper to set property of timeline shape
type: docs
url: /net/aspose.diagram/timelinehelper/
---
## TimeLineHelper class

TimeLineHelper to set property of timeline shape.

```csharp
public class TimeLineHelper
```

## Constructors

| Name | Description |
| --- | --- |
| [TimeLineHelper](timelinehelper/)(Shape) | TimeLineHelper. |

## Properties

| Name | Description |
| --- | --- |
| [ArrowHead](../../aspose.diagram/timelinehelper/arrowhead/) { get; set; } | ArrowHead of timeline shape |
| [BeginWeek](../../aspose.diagram/timelinehelper/beginweek/) { get; set; } | Begin week of timeline shape |
| [DateFormatForBE](../../aspose.diagram/timelinehelper/dateformatforbe/) { get; set; } | DateFormat for start and finish of timeline shape |
| [DateFormatForIntm](../../aspose.diagram/timelinehelper/dateformatforintm/) { get; set; } | DateFormat for Intm of timeline shape |
| [DateFormatStringForBE](../../aspose.diagram/timelinehelper/dateformatstringforbe/) { get; set; } | DateFormat String for start and finish of timeline shape |
| [DateFormatStringForIntm](../../aspose.diagram/timelinehelper/dateformatstringforintm/) { get; set; } | DateFormat String for Intm of timeline shape |
| [FiscalStart](../../aspose.diagram/timelinehelper/fiscalstart/) { get; set; } | First day of fiscal year |
| [IsAutoUpdate](../../aspose.diagram/timelinehelper/isautoupdate/) { get; set; } | whether to update data for markers (milestones, intervals) as they are moved on timeline |
| [IsDisplayBE](../../aspose.diagram/timelinehelper/isdisplaybe/) { get; set; } | whether to display Begin and End dates on timeline |
| [IsDisplayIntm](../../aspose.diagram/timelinehelper/isdisplayintm/) { get; set; } | whether to display interim date/time ticks on timeline |
| [IsDisplayIntmDates](../../aspose.diagram/timelinehelper/isdisplayintmdates/) { get; set; } | whether to display interim dates on interim ticks |
| [TimeLineType](../../aspose.diagram/timelinehelper/timelinetype/) { get; set; } | Begin week of timeline shape |
| [TimePeriodFinish](../../aspose.diagram/timelinehelper/timeperiodfinish/) { get; set; } | Time Period for finish of timeline shape |
| [TimePeriodStart](../../aspose.diagram/timelinehelper/timeperiodstart/) { get; set; } | Time Period for start of timeline shape |
| [TimeScale](../../aspose.diagram/timelinehelper/timescale/) { get; set; } | scale of timeline shape |

## Methods

| Name | Description |
| --- | --- |
| [RefreshTimeLine](../../aspose.diagram/timelinehelper/refreshtimeline/)() | Refresh time of timeline shapes |
| static [GetDoubleStringFromDateTime](../../aspose.diagram/timelinehelper/getdoublestringfromdatetime/)(DateTime) | Convert the date time to double value. |
| static [GetWeekEnd](../../aspose.diagram/timelinehelper/getweekend/)(DateTime, int) | getweekstart |

## Remarks

Compatibility shell over [`TimeLineProperties`](../timelineproperties/): the public API is unchanged (plus getters for the previously write-only properties), the cell access is delegated to the properties class, and [`RefreshTimeLine`](./refreshtimeline/) is rewritten:

* The begin/end date text shapes are updated by position without skipping the last child, so the end-date text shape is updated as well.
* Master-instance markers (milestones, intervals) inside the period keep their field — the old code overwrote every master-instance child field with the start date. Out-of-range markers are deleted instead.
* Previously generated interim ticks are removed and regenerated with the interim User cells (visTLShape, visInterimType) that real timeline ticks carry, so they render as timeline ticks in Visio.
* Year-scale ticks land on January 1 boundaries, so ranges that cross a year boundary are no longer empty for spans under one year.

The internal SetDateFormat of the old implementation is gone; the format table lives in TimelineFormats (TimeLineProperties.cs) and is shared with MilestoneProperties.

### See Also

* namespace [Aspose.Diagram](../../aspose.diagram/)
* assembly [Aspose.Diagram](../../)


