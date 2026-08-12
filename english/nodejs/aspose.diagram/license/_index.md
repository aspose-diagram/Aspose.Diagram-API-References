---
title: "License"
linktitle: "License"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Provides methods to license the component."
type: docs
weight: 1350
url: /nodejs/aspose.diagram/license/
---

## License class

Provides methods to license the component.

```js
new License()
```

Initializes a new instance of this class.

## Methods

| Name | Description |
| --- | --- |
| [setLicenseFromStream(license, stream, callback)](#setlicensefromstream) *(static)* | Licenses the component. Use this method to load a license from a stream. |
| [setLicense()](#setlicense) | Licenses the component. Tries to find the license in the following locations:1. Explicit path.2. The folder of the compo |

### setLicenseFromStream(license, stream, callback) (static) {#setlicensefromstream}

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

### setLicense() {#setlicense}

Licenses the component. Tries to find the license in the following locations:1. Explicit path.2. The folder of the component jar file.
