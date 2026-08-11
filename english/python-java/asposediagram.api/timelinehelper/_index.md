---
title: "TimeLineHelper"
linktitle: "TimeLineHelper"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "TimeLineHelper to set property of timeline shape."
type: docs
weight: 3500
url: /python-java/asposediagram.api/timelinehelper/
---

## TimeLineHelper class

TimeLineHelper to set property of timeline shape.

## Constructors

| Name | Description |
| --- | --- |
| [TimeLineHelper](#constructor) | TimeLineHelper. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [FiscalStart](#fiscalstart) | DateTime | First day of fiscal year |
| [TimePeriodStart](#timeperiodstart) | DateTime | Time Period for start of timeline shape |
| [TimePeriodFinish](#timeperiodfinish) | DateTime | Time Period for finish of timeline shape |
| [TimeScale](#timescale) | int | scale of timeline shape |
| [ArrowHead](#arrowhead) | int | ArrowHead of timeline shape |
| [BeginWeek](#beginweek) | int | Begin week of timeline shape |
| [TimeLineType](#timelinetype) | int | Begin week of timeline shape |
| [IsDisplayBE](#isdisplaybe) | boolean | whether to display Begin and End dates on timeline |
| [IsDisplayIntm](#isdisplayintm) | boolean | whether to display interim date/time ticks on timeline |
| [IsDisplayIntmDates](#isdisplayintmdates) | boolean | whether to display interim dates on interim ticks |
| [IsAutoUpdate](#isautoupdate) | boolean | whether to update data for markers (milestones, intervals) as they are moved on timeline |
| [DateFormatForIntm](#dateformatforintm) | int | DateFormat for Intm of timeline shape Value Format String 0 dddd, yyyy-M-d 1 yyyy-MM-dd 2 yy-MMM-d 3 yyyy/M/d 4 yy-MMM.- |
| [DateFormatStringForIntm](#dateformatstringforintm) | String | DateFormat String for Intm of timeline shape |
| [DateFormatForBE](#dateformatforbe) | int | DateFormat for start and finish of timeline shape Value Format String 0 dddd, yyyy-M-d 1 yyyy-MM-dd 2 yy-MMM-d 3 yyyy/M/ |
| [DateFormatStringForBE](#dateformatstringforbe) | String | DateFormat String for start and finish of timeline shape |

## Methods

| Name | Description |
| --- | --- |
| [refreshTimeLine](#refreshtimeline) | Refresh time of timeline shapes |
| [getWeekEnd](#getweekend) | getweekstart |
| [getDoubleStringFromDateTime](#getdoublestringfromdatetime) | Convert the date time to double value. |

### TimeLineHelper(shape) {#constructor}

TimeLineHelper.

### TimeLineHelper.FiscalStart property {#fiscalstart}

First day of fiscal year

**Type:** DateTime

### TimeLineHelper.TimePeriodStart property {#timeperiodstart}

Time Period for start of timeline shape

**Type:** DateTime

### TimeLineHelper.TimePeriodFinish property {#timeperiodfinish}

Time Period for finish of timeline shape

**Type:** DateTime

### TimeLineHelper.TimeScale property {#timescale}

scale of timeline shape

**Type:** int

### TimeLineHelper.ArrowHead property {#arrowhead}

ArrowHead of timeline shape

**Type:** int

### TimeLineHelper.BeginWeek property {#beginweek}

Begin week of timeline shape

**Type:** int

### TimeLineHelper.TimeLineType property {#timelinetype}

Begin week of timeline shape

**Type:** int

### TimeLineHelper.IsDisplayBE property {#isdisplaybe}

whether to display Begin and End dates on timeline

**Type:** boolean

### TimeLineHelper.IsDisplayIntm property {#isdisplayintm}

whether to display interim date/time ticks on timeline

**Type:** boolean

### TimeLineHelper.IsDisplayIntmDates property {#isdisplayintmdates}

whether to display interim dates on interim ticks

**Type:** boolean

### TimeLineHelper.IsAutoUpdate property {#isautoupdate}

whether to update data for markers (milestones, intervals) as they are moved on timeline

**Type:** boolean

### TimeLineHelper.DateFormatForIntm property {#dateformatforintm}

DateFormat for Intm of timeline shape Value Format String 0 dddd, yyyy-M-d 1 yyyy-MM-dd 2 yy-MMM-d 3 yyyy/M/d 4 yy-MMM.-d 5 d MMMM yyyy 6 yy-M 7 MMM-yy 8 MMMM d, yyyy 9 MMM d, yyyy 10 M-d-yy 11 M-d 12 d MMMM, yyyy 13 d MMM, yyyy 14 d-M-yy 15 d-M 16 yy-M-d 17 yyyy-M-d 18 M-yy 19 M-yyyy 20 MMMM yyyy 21 MMMM yy 22 MMM yyyy 23 MMM yy 24 yy 25 yyyy 26 d 27 MMMM 28 MMM 29 M 30 MM/dd/yyyy

**Type:** int

### TimeLineHelper.DateFormatStringForIntm property {#dateformatstringforintm}

DateFormat String for Intm of timeline shape

**Type:** String

### TimeLineHelper.DateFormatForBE property {#dateformatforbe}

DateFormat for start and finish of timeline shape Value Format String 0 dddd, yyyy-M-d 1 yyyy-MM-dd 2 yy-MMM-d 3 yyyy/M/d 4 yy-MMM.-d 5 d MMMM yyyy 6 yy-M 7 MMM-yy 8 MMMM d, yyyy 9 MMM d, yyyy 10 M-d-yy 11 M-d 12 d MMMM, yyyy 13 d MMM, yyyy 14 d-M-yy 15 d-M 16 yy-M-d 17 yyyy-M-d 18 M-yy 19 M-yyyy 20 MMMM yyyy 21 MMMM yy 22 MMM yyyy 23 MMM yy 24 yy 25 yyyy 26 d 27 MMMM 28 MMM 29 M 30 MM/dd/yyyy

**Type:** int

### TimeLineHelper.DateFormatStringForBE property {#dateformatstringforbe}

DateFormat String for start and finish of timeline shape

**Type:** String

### refreshTimeLine() {#refreshtimeline}

Refresh time of timeline shapes

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("DrawingTimeLine.vsdx");

shapeid = 1;
// Get timeline shape
timeline = diagram.getPages().getPage("Page-1").getShapes().getShape(shapeid);

// Initialize TimeLineHlper object
timelineHelper = new aspose.diagram.TimeLineHelper(timeline);

// Set start time
timelineHelper.setTimePeriodStart(new aspose.diagram.DateTime(2014, 12, 21));
// Set end time
timelineHelper.setTimePeriodFinish(new aspose.diagram.DateTime(2015, 2, 19));

// Set date format
timelineHelper.setDateFormatForBE(21);

// revive milestones on the timeline
timelineHelper.refreshTimeLine();

diagram.save("out-RefreshTimeLine.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### getWeekEnd(startDate, weekStart) {#getweekend}

getweekstart

| Parameter | Type | Description |
| --- | --- | --- |
| startDate | DateTime |  |
| weekStart | int | (0sunday 1monday 2 3 4 5 6) |

### getDoubleStringFromDateTime(dateTime) {#getdoublestringfromdatetime}

Convert the date time to double value.

| Parameter | Type | Description |
| --- | --- | --- |
| dateTime | DateTime | The date time. |
