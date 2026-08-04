---
title: "TimeLineHelper.refreshTimeLine"
linktitle: "refreshTimeLine"
articleTitle: "refreshTimeLine"
second_title: "Aspose.Diagram for Python via Java"
description: "Refresh time of timeline shapes"
type: docs
weight: 10
url: /python-java/asposediagram.api/timelinehelper/refreshtimeline/
---

## refreshTimeLine() {#refreshtimeline}

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
