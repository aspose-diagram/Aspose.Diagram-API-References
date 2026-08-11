---
title: "TimeLineHelper"
linktitle: "TimeLineHelper"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "TimeLineHelper to set property of timeline shape."
type: docs
weight: 2650
url: /nodejs/aspose.diagram/timelinehelper/
---

## TimeLineHelper class

TimeLineHelper to set property of timeline shape.

```js
new TimeLineHelper()
```

TimeLineHelper.

## Methods

| Name | Description |
| --- | --- |
| [getTimePeriodFinish()](#gettimeperiodfinish) | Time Period for finish of timeline shape |
| [getTimePeriodStart()](#gettimeperiodstart) | Time Period for start of timeline shape |
| [getTimeScale()](#gettimescale) | scale of timeline shape |
| [refreshTimeLine()](#refreshtimeline) | Refresh time of timeline shapes |
| [setArrowHead()](#setarrowhead) | ArrowHead of timeline shape |
| [setAutoUpdate()](#setautoupdate) | whether to update data for markers (milestones, intervals) as they are moved on timeline |
| [setBeginWeek()](#setbeginweek) | Begin week of timeline shape |
| [setDateFormatForBE()](#setdateformatforbe) | DateFormat for start and finish of timeline shape Value Format String 0dddd, yyyy-M-d1yyyy-MM-dd2yy-MMM-d3yyyy/M/d4yy-MM |
| [setDateFormatForIntm()](#setdateformatforintm) | DateFormat for Intm of timeline shape Value Format String 0dddd, yyyy-M-d1yyyy-MM-dd2yy-MMM-d3yyyy/M/d4yy-MMM.-d5d MMMM  |
| [setDateFormatStringForBE()](#setdateformatstringforbe) | DateFormat String for start and finish of timeline shape |
| [setDateFormatStringForIntm()](#setdateformatstringforintm) | DateFormat String for Intm of timeline shape |
| [setDisplayBE()](#setdisplaybe) | whether to display Begin and End dates on timeline |
| [setDisplayIntm()](#setdisplayintm) | whether to display interim date/time ticks on timeline |
| [setDisplayIntmDates()](#setdisplayintmdates) | whether to display interim dates on interim ticks |
| [setTimeLineType()](#settimelinetype) | Begin week of timeline shape |
| [setTimeScale()](#settimescale) | scale of timeline shape |

### getTimePeriodFinish() {#gettimeperiodfinish}

Time Period for finish of timeline shape

### getTimePeriodStart() {#gettimeperiodstart}

Time Period for start of timeline shape

### getTimeScale() {#gettimescale}

scale of timeline shape

### refreshTimeLine() {#refreshtimeline}

Refresh time of timeline shapes

**Example:**

```js
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

### setArrowHead() {#setarrowhead}

ArrowHead of timeline shape

### setAutoUpdate() {#setautoupdate}

whether to update data for markers (milestones, intervals) as they are moved on timeline

### setBeginWeek() {#setbeginweek}

Begin week of timeline shape

### setDateFormatForBE() {#setdateformatforbe}

DateFormat for start and finish of timeline shape Value Format String 0dddd, yyyy-M-d1yyyy-MM-dd2yy-MMM-d3yyyy/M/d4yy-MMM.-d5d MMMM yyyy6yy-M7MMM-yy8MMMM d, yyyy9MMM d, yyyy10M-d-yy11M-d12d MMMM, yyyy13d MMM, yyyy14d-M-yy15d-M16yy-M-d17yyyy-M-d18M-yy19M-yyyy20MMMM yyyy21MMMM yy22MMM yyyy23MMM yy24yy25yyyy26d27MMMM28MMM29M30MM/dd/yyyy

### setDateFormatForIntm() {#setdateformatforintm}

DateFormat for Intm of timeline shape Value Format String 0dddd, yyyy-M-d1yyyy-MM-dd2yy-MMM-d3yyyy/M/d4yy-MMM.-d5d MMMM yyyy6yy-M7MMM-yy8MMMM d, yyyy9MMM d, yyyy10M-d-yy11M-d12d MMMM, yyyy13d MMM, yyyy14d-M-yy15d-M16yy-M-d17yyyy-M-d18M-yy19M-yyyy20MMMM yyyy21MMMM yy22MMM yyyy23MMM yy24yy25yyyy26d27MMMM28MMM29M30MM/dd/yyyy

### setDateFormatStringForBE() {#setdateformatstringforbe}

DateFormat String for start and finish of timeline shape

### setDateFormatStringForIntm() {#setdateformatstringforintm}

DateFormat String for Intm of timeline shape

### setDisplayBE() {#setdisplaybe}

whether to display Begin and End dates on timeline

### setDisplayIntm() {#setdisplayintm}

whether to display interim date/time ticks on timeline

### setDisplayIntmDates() {#setdisplayintmdates}

whether to display interim dates on interim ticks

### setTimeLineType() {#settimelinetype}

Begin week of timeline shape

### setTimeScale() {#settimescale}

scale of timeline shape
