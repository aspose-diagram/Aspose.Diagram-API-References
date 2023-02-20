---
title: ImageSaveOptions
second_title: .NET API संदर्भ के लिए Aspose.Diagram
description: छवयं के लए आरेख पृष्ठं क प्रस्तुत करते समय अतरक्त वकल्प नर्दष्ट करने क अनुमत देत है
type: docs
weight: 3280
url: /hi/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

छवियों के लिए आरेख पृष्ठों को प्रस्तुत करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/)(SaveFileFormat) | इस वर्ग का एक नया उदाहरण प्रारंभ करता है जिसका उपयोग रेंडर की गई छवियों को सहेजने के लिए किया जा सकता है[`मनमुटाव`](../../aspose.diagram/savefileformat/) , [`पीएनजी`](../../aspose.diagram/savefileformat/) ,[`बीएमपी`](../../aspose.diagram/savefileformat/) ,[`ईएमएफ`](../../aspose.diagram/savefileformat/) या[`जेपीईजी`](../../aspose.diagram/savefileformat/) प्रारूप. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | प्राप्त करता है या सेट करता है कि आकृतियों का क्षेत्र सहेजा जाएगा . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality/) { get; set; } | कंपोज़िटिंग के दौरान उपयोग करने के लिए गुणवत्ता स्तर निर्दिष्ट करता है। |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom/) { get; set; } | यह पैरामीटर स्केल के समान है, लेकिन उत्पन्न छवि आकार को प्रभावित नहीं करता है। |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | जब आरेख में वर्ण यूनिकोड होते हैं और सही फ़ॉन्ट मान के साथ सेट नहीं होते हैं या फ़ॉन्ट स्थानीय रूप से स्थापित नहीं होते हैं, वे पीडीएफ, छवि या एक्सपीएस में ब्लॉक के रूप में दिखाई दे सकते हैं। अक्षर. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | EMF मेटाफ़ाइल रेंडर करने के लिए सेटिंग. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | निर्दिष्ट करता है कि क्या पृष्ठ बड़ा करें . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | परिभाषित करता है कि गाइड आकृतियों को निर्यात करने की आवश्यकता है या नहीं। |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage/) { get; set; } | परिभाषित करता है कि छिपे हुए पृष्ठ को निर्यात करने की आवश्यकता है या नहीं। |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness/) { get; set; } | उत्पन्न छवियों के लिए चमक प्राप्त या सेट करता है। |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode/) { get; set; } | उत्पन्न छवियों के लिए रंग मोड प्राप्त या सेट करता है। |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast/) { get; set; } | उत्पन्न छवियों के लिए कंट्रास्ट प्राप्त या सेट करता है। |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode/) { get; set; } | छवियों को स्केल या घुमाए जाने पर उपयोग किए जाने वाले एल्गोरिदम को निर्दिष्ट करता है। |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | परिभाषित करता है कि टिप्पणियों को निर्यात करने की आवश्यकता है या नहीं। |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality/) { get; set; } | उत्पन्न जेपीईजी छवियों की गुणवत्ता निर्धारित करने वाला मान प्राप्त या सेट करता है। |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount/) { get; set; } | बहुपृष्ठ TIFF फ़ाइल में सहेजते समय प्रस्तुत करने के लिए पृष्ठों की संख्या प्राप्त या सेट करता है। डिफ़ॉल्ट MaxValue है जिसका अर्थ है कि आरेख के सभी पृष्ठ प्रस्तुत किए जाएंगे। |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex/) { get; set; } | प्रस्तुत करने के लिए पहले पृष्ठ की 0-आधारित अनुक्रमणिका प्राप्त या सेट करता है। डिफ़ॉल्ट 0. है |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | उत्पन्न छवियों के लिए पृष्ठ आकार प्राप्त या सेट करता है। हो सकता है[`PageSize`](../pagesize/) या शून्य. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode/) { get; set; } | रेंडरिंग के दौरान पिक्सेल को कैसे ऑफ़सेट किया जाता है, यह निर्दिष्ट करने वाला मान प्राप्त या सेट करता है। |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution/) { get; set; } | उत्पन्न छवियों के लिए डॉट्स प्रति इंच में रिज़ॉल्यूशन प्राप्त या सेट करता है। |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea/) { get; set; } | निर्दिष्ट करता है कि बचत क्षेत्र पीडीएफ के समान है या नहीं . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly/) { get; set; } | निर्दिष्ट करता है कि सभी पृष्ठ छवि में सहेजे जाएंगे या केवल अग्रभूमि में सहेजे जाएंगे. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat/) { get; set; } | उस प्रारूप को निर्दिष्ट करता है जिसमें रेंडर किए गए आरेख पृष्ठ सहेजे जाएंगे यदि यह सहेजें विकल्प ऑब्जेक्ट का उपयोग किया जाता है। हो सकता है[`मनमुटाव`](../../aspose.diagram/savefileformat/) ,[`पीएनजी`](../../aspose.diagram/savefileformat/) , [`बीएमपी`](../../aspose.diagram/savefileformat/) ,[`ईएमएफ`](../../aspose.diagram/savefileformat/) या[`जेपीईजी`](../../aspose.diagram/savefileformat/) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale/) { get; set; } | उत्पन्न छवियों के लिए ज़ूम कारक प्राप्त या सेट करता है। |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | रेंडर करने के लिए आकार प्राप्त या सेट करता है। डिफ़ॉल्ट गणना 0. है |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode/) { get; set; } | निर्दिष्ट करता है कि क्या स्मूथिंग (एंटीएलियासिंग) लाइनों और वक्रों और भरे हुए क्षेत्रों के किनारों पर लागू किया जाता है। |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression/) { get; set; } | टीआईएफएफ प्रारूप में जेनरेट की गई छवियों को सहेजते समय लागू होने वाले संपीड़न के प्रकार को प्राप्त या सेट करता है। |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | चेतावनी कॉलबैक प्राप्त या सेट करता है। |

### यह सभी देखें

* class [RenderingSaveOptions](../renderingsaveoptions/)
* नाम स्थान [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* सभा [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
