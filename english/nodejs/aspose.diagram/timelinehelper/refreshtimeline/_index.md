---
title: "TimeLineHelper.refreshTimeLine"
linktitle: "refreshTimeLine"
articleTitle: "refreshTimeLine"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Refresh time of timeline shapes"
type: docs
weight: 50
url: /nodejs/aspose.diagram/timelinehelper/refreshtimeline/
---

## refreshTimeLine()

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
