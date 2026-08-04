---
title: "License.setLicenseFromStream"
linktitle: "setLicenseFromStream"
articleTitle: "setLicenseFromStream"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Licenses the component."
type: docs
weight: 20
url: /nodejs/aspose.diagram/license/setlicensefromstream/
---

## setLicenseFromStream(license, stream, callback) (static)

Licenses the component. Use this method to load a license from a stream.

| Parameter | Type | Description |
| --- | --- | --- |
| license | License | The license object |
| stream | ReadableStream | The stream |
| callback | Callback | The callback function |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var licenseStream = fs.createReadStream("Aspose.Diagram.lic");
var license = new aspose.diagram.License();
aspose.diagram.License.setLicenseFromStream(license, licenseStream,
function(err) {
if (err) {
console.log("license error");
return;
}
var diagram = new aspose.diagram.Diagram();
diagram.save("output.vsdx", aspose.diagram.SaveFileFormat.VSDX);
});
```
