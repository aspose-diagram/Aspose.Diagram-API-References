---
title: PdfSaveOptions
second_title: .NET API संदर्भ के लिए Aspose.Diagram
description: आरेख पृष्ठं क PDF में रेंडर करते समय अतरक्त वकल्प नर्दष्ट करने क अनुमत देत है
type: docs
weight: 3410
url: /hi/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

आरेख पृष्ठों को PDF में रेंडर करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | इस वर्ग का एक नया उदाहरण प्रारंभ करता है जिसका उपयोग किसी दस्तावेज़ को सहेजने के लिए किया जा सकता है[`पीडीएफ`](../../aspose.diagram/savefileformat/) प्रारूप. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | प्राप्त करता है या सेट करता है कि आकृतियों का क्षेत्र सहेजा जाएगा . |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance/) { get; set; } | जनरेट किए गए PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर. डिफ़ॉल्ट हैPdf15 . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | जब आरेख में वर्ण यूनिकोड होते हैं और सही फ़ॉन्ट मान के साथ सेट नहीं होते हैं या फ़ॉन्ट स्थानीय रूप से स्थापित नहीं होते हैं, वे पीडीएफ, छवि या एक्सपीएस में ब्लॉक के रूप में दिखाई दे सकते हैं। अक्षर. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails/) { get; set; } | डिजिटल हस्ताक्षर विवरण प्राप्त या सेट करता है। यदि सेट नहीं किया गया है, तो कोई हस्ताक्षर नहीं किया जाएगा. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | EMF मेटाफ़ाइल रेंडर करने के लिए सेटिंग. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails/) { get; set; } | एन्क्रिप्शन विवरण प्राप्त या सेट करता है। यदि सेट नहीं है, तो कोई एन्क्रिप्शन नहीं किया जाएगा. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | निर्दिष्ट करता है कि क्या पृष्ठ बड़ा करें . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | परिभाषित करता है कि गाइड आकृतियों को निर्यात करने की आवश्यकता है या नहीं। |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage/) { get; set; } | परिभाषित करता है कि छिपे हुए पृष्ठ को निर्यात करने की आवश्यकता है या नहीं। |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution/) { get; set; } | उत्पन्न छवियों के लिए डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन प्राप्त या सेट करता है। ईएमएफ प्रारूप छवियों को छोड़कर छवि विधि उत्पन्न करता है। |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | परिभाषित करता है कि टिप्पणियों को निर्यात करने की आवश्यकता है या नहीं। |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality/) { get; set; } | छवियों के लिए जेपीईजी संपीड़न की गुणवत्ता निर्दिष्ट करता है (यदि जेपीईजी संपीड़न का उपयोग किया जाता है)। डिफ़ॉल्ट 95 है। |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount/) { get; set; } | PDF में प्रस्तुत करने के लिए पृष्ठों की संख्या प्राप्त या सेट करता है। डिफ़ॉल्ट MaxValue है जिसका अर्थ है कि आरेख के सभी पृष्ठ प्रस्तुत किए जाएंगे। |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex/) { get; set; } | प्रस्तुत करने के लिए पहले पृष्ठ की 0-आधारित अनुक्रमणिका प्राप्त या सेट करता है। डिफ़ॉल्ट 0. है |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback/) { get; set; } | पृष्ठ सहेजने की प्रक्रिया की प्रगति को नियंत्रित/इंगित करें। |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | उत्पन्न छवियों के लिए पृष्ठ आकार प्राप्त या सेट करता है। हो सकता है[`PageSize`](../pagesize/) या शून्य. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly/) { get; set; } | निर्दिष्ट करता है कि सभी पृष्ठ छवि में सहेजे जाएंगे या केवल अग्रभूमि में सहेजे जाएंगे. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat/) { get; set; } | उस प्रारूप को निर्दिष्ट करता है जिसमें रेंडर किए गए आरेख पृष्ठ सहेजे जाएंगे यदि यह सहेजें विकल्प ऑब्जेक्ट का उपयोग किया जाता है। हो सकता है[`पीडीएफ`](../../aspose.diagram/savefileformat/) केवल. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | रेंडर करने के लिए आकार प्राप्त या सेट करता है। डिफ़ॉल्ट गणना 0. है |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages/) { get; set; } | परिभाषित करता है कि पृष्ठ की सेटिंग के अनुसार आरेख को बहु पृष्ठों में विभाजित करें या नहीं। |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression/) { get; set; } | छवियों को छोड़कर सभी सामग्री धाराओं के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। डिफ़ॉल्ट हैFlate . |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution/) { get; set; } | डॉट्स प्रति इंच में उत्पन्न छवियों के लिए लंबवत रिज़ॉल्यूशन प्राप्त या सेट करता है। ईएमएफ प्रारूप छवि को छोड़कर छवि विधि उत्पन्न करता है। |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback/) { get; set; } | चेतावनी कॉलबैक प्राप्त या सेट करता है। |

### यह सभी देखें

* class [RenderingSaveOptions](../renderingsaveoptions/)
* नाम स्थान [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* सभा [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
