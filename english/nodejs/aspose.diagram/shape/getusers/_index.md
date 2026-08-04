---
title: "Shape.getUsers"
linktitle: "getUsers"
articleTitle: "getUsers"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains a collection of User elements."
type: docs
weight: 970
url: /nodejs/aspose.diagram/shape/getusers/
---

## getUsers()

Contains a collection of User elements.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("TextBoxes.vsdx");
// get page by name
page = diagram.getPages().getPage("Page-1");
// get shape by id
shape = page.getShapes().getShape(2);
// extract user defined cells of the shape
for (it = shape.getUsers().iterator(); it.hasNext();) {
user = it.next();
console.log(user.getName() + ": " + user.getValue().getVal());
}
```
