---
title: Class DigitalSignature
second_title: Aspose.Diagram for .NET API Reference
description: Aspose.Diagram.DigitalSignatures.DigitalSignature class. Signature in file
type: docs
url: /net/aspose.diagram.digitalsignatures/digitalsignature/
---
## DigitalSignature class

Signature in file.

```csharp
public class DigitalSignature
```

## Constructors

| Name | Description |
| --- | --- |
| [DigitalSignature](digitalsignature/#constructor_1)(X509Certificate2, string, DateTime) | Constructor of digitalSignature. Uses .Net implementation. |
| [DigitalSignature](digitalsignature/#constructor)(byte[], string, string, DateTime) | Constructor of digitalSignature. Uses Bouncy Castle implementation. |

## Properties

| Name | Description |
| --- | --- |
| [Certificate](../../aspose.diagram.digitalsignatures/digitalsignature/certificate/) { get; set; } |  |
| [Comments](../../aspose.diagram.digitalsignatures/digitalsignature/comments/) { get; set; } | The purpose to signature. |
| [Id](../../aspose.diagram.digitalsignatures/digitalsignature/id/) { get; set; } | Specifies a GUID which can be cross-referenced with the GUID of the signature line stored in the document content. Default value is Empty (all zeroes) Guid. |
| [Image](../../aspose.diagram.digitalsignatures/digitalsignature/image/) { get; set; } | Specifies an image for the digital signature. Default value is null. |
| [IsValid](../../aspose.diagram.digitalsignatures/digitalsignature/isvalid/) { get; } | If this digital signature is valid and the document has not been tampered with, this value will be true. |
| [ProviderId](../../aspose.diagram.digitalsignatures/digitalsignature/providerid/) { get; set; } | Specifies the class ID of the signature provider. Default value is Empty (all zeroes) Guid. |
| [SignTime](../../aspose.diagram.digitalsignatures/digitalsignature/signtime/) { get; set; } | The time when the document was signed. |
| [Text](../../aspose.diagram.digitalsignatures/digitalsignature/text/) { get; set; } | Specifies the text of actual signature in the digital signature. Default value is Empty. |
| [XAdESType](../../aspose.diagram.digitalsignatures/digitalsignature/xadestype/) { get; set; } | XAdES type. Default value is None(XAdES is off). |

### See Also

* namespace [Aspose.Diagram.DigitalSignatures](../../aspose.diagram.digitalsignatures/)
* assembly [Aspose.Diagram](../../)


