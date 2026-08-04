---
title: "Page.addComment"
linktitle: "addComment"
articleTitle: "addComment"
second_title: "Aspose.Diagram for Python via Java"
description: "Adds comment to a shape with shape's id."
type: docs
weight: 170
url: /python-java/asposediagram.api/page/addcomment/
---

## addComment(shapeID, comment) (1 of 3) {#addcomment}

Adds comment to a shape with shape's id.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeID | long | The ID of shape which is adding comment. |
| comment | String | Comment's string. |

---

## addComment(shape, comment) (2 of 3) {#addcomment_1}

Adds comment to a shape.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | Specifies the shape which is adding comment . |
| comment | String | Comment's string. |

---

## addComment(pinX, pinY, comment) (3 of 3) {#addcomment_2}

Adds comment with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the comment's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the comment's pin (center of rotation) in relation to the page. |
| comment | String | Comment's string. |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

var diagram = new aspose.diagram.Diagram("Drawing1.vsdx");
// Add comment
diagram.getPages().getPage(0).addComment(7.205905511811023, 3.880708661417323, "test@");
// Save diagram
diagram.save("out-AddPageLevelCommentInVisio.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
