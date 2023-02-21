---
title: SaveOptions
second_title: .NET API संदर्भ के लिए Aspose.Diagram
description: यह उन वर्गं के लए एक सर आधर वर्ग है ज उपयगकर्त क आरेख क कस वशेष प्ररूप में सहेजते समय अतरक्त वकल्प नर्दष्ट करने क अनुमत देत है
type: docs
weight: 3480
url: /hi/net/aspose.diagram.saving/saveoptions/
---
## SaveOptions class

यह उन वर्गों के लिए एक सार आधार वर्ग है जो उपयोगकर्ता को आरेख को किसी विशेष प्रारूप में सहेजते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।

```csharp
public abstract class SaveOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | जब आरेख में वर्ण यूनिकोड होते हैं और सही फ़ॉन्ट मान के साथ सेट नहीं होते हैं या फ़ॉन्ट स्थानीय रूप से स्थापित नहीं होते हैं, वे पीडीएफ, छवि या एक्सपीएस में ब्लॉक के रूप में दिखाई दे सकते हैं। अक्षर. |
| virtual [SaveFormat](../../aspose.diagram.saving/saveoptions/saveformat/) { get; set; } | उस प्रारूप को निर्दिष्ट करता है जिसमें दस्तावेज़ सहेजा जाएगा यदि यह सहेजें विकल्प ऑब्जेक्ट का उपयोग किया जाता है। |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | चेतावनी कॉलबैक प्राप्त या सेट करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [CreateSaveOptions](../../aspose.diagram.saving/saveoptions/createsaveoptions/)(SaveFileFormat) | निर्दिष्ट सेव फॉर्मेट के लिए उपयुक्त वर्ग का एक सेव ऑप्शन ऑब्जेक्ट बनाता है। |

### टिप्पणियों

सेवऑप्शन क्लास या किसी भी व्युत्पन्न वर्ग का एक उदाहरण स्ट्रीम सेव या स्ट्रिंग सेव ओवरलोड्स को पास किया जाता है ताकि उपयोगकर्ता दस्तावेज़ को सहेजते समय कस्टम विकल्पों को परिभाषित कर सके।

### यह सभी देखें

* नाम स्थान [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* सभा [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->