---
title: "Page.addComment"
linktitle: "addComment"
articleTitle: "addComment"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Adds comment with defined PinX and PinY."
type: docs
weight: 50
url: /nodejs/aspose.diagram/page/addcomment-2/
---

## addComment(pinX, pinY, comment)

Adds comment with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the comment's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the comment's pin (center of rotation) in relation to the page. |
| comment | String | Comment's string. |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var diagram = new aspose.diagram.Diagram("Drawing1.vsdx");
// Add comment
diagram.getPages().getPage(0).addComment(7.205905511811023, 3.880708661417323, "test@");
// Save diagram
diagram.save("out-AddPageLevelCommentInVisio.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
