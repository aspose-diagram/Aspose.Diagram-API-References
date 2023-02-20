---
title: DataRecordSet
second_title: .NET API संदर्भ के लिए Aspose.Diagram
description: Microsoft Visio. में डेटबेस से क्वेर कए गए डेट क स्टर फ़र्मेट रफ़्रेश और एक्सपज़ करत है
type: docs
weight: 1140
url: /hi/net/aspose.diagram/datarecordset/
---
## DataRecordSet class

Microsoft Visio. में डेटाबेस से क्वेरी किए गए डेटा को स्टोर, फ़ॉर्मेट, रीफ़्रेश और एक्सपोज़ करता है

```csharp
public class DataRecordSet
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DataRecordSet](datarecordset/)() | कंस्ट्रक्टर. |

## गुण

| नाम | विवरण |
| --- | --- |
| [ADOData](../../aspose.diagram/datarecordset/adodata/) { get; set; } | में वह XML शामिल है जो ADO रिकॉर्डसेट के लिए ADO क्लासिक XML स्कीमा के अनुरूप है और जो डेटा रिकॉर्डसेट में डेटा का वर्णन करता है। |
| [AutoLinkComparison](../../aspose.diagram/datarecordset/autolinkcomparison/) { get; } | एक नियम को परिभाषित करता है जो मूल DataRecordset तत्व में एक कॉलम की तुलना उपयोगकर्ता इंटरफ़ेस में की गई अंतिम सफल स्वचालित लिंकिंग क्रिया से आकार डेटा आइटम के साथ करता है। |
| [Checksum](../../aspose.diagram/datarecordset/checksum/) { get; set; } | एक चेकसम मान, जो Visio द्वारा जनरेट किया गया है, और डेटा-रिकॉर्डसेट गुणों पर आधारित है। इस विशेषता को 0 पर सेट करें; Visio रनटाइम पर इस मान की पुनर्गणना करता है. |
| [Command](../../aspose.diagram/datarecordset/command/) { get; set; } | कमांड स्ट्रिंग का उपयोग डेटा स्रोत से डेटा क्वेरी करने के लिए किया जाता है। |
| [ConnectionID](../../aspose.diagram/datarecordset/connectionid/) { get; set; } | संबंधित डेटाकनेक्शन ऑब्जेक्ट के लिए कनेक्शन आईडी। XML डेटा स्रोतों के लिए मौजूद नहीं है. |
| [DataColumns](../../aspose.diagram/datarecordset/datacolumns/) { get; } | में डेटा रिकॉर्डसेट में सभी डेटाकॉलम तत्व शामिल हैं। |
| [ID](../../aspose.diagram/datarecordset/id/) { get; set; } | डेटा रिकॉर्डसेट आईडी, दस्तावेज़ के भीतर अद्वितीय। |
| [Name](../../aspose.diagram/datarecordset/name/) { get; set; } | डेटा रिकॉर्डसेट का प्रदर्शन (या "दोस्ताना") नाम। |
| [NextRowID](../../aspose.diagram/datarecordset/nextrowid/) { get; set; } | अगली उपलब्ध Visio पंक्ति ID. |
| [Options](../../aspose.diagram/datarecordset/options/) { get; set; } | विकल्प डेटा रिकॉर्डसेट पर लागू करने के लिए। संभावित मान निम्नलिखित तालिका में दिखाए गए एक या अधिक का कोई भी संयोजन हो सकते हैं। |
| [PrimaryKeys](../../aspose.diagram/datarecordset/primarykeys/) { get; } | डेटा रिकॉर्डसेट में एक या अधिक प्राथमिक-कुंजी कॉलम की पहचान करता है। |
| [RefreshConflicts](../../aspose.diagram/datarecordset/refreshconflicts/) { get; } | डेटा रिकॉर्डसेट में एक पंक्ति को इंगित करता है जो डेटा रिकॉर्डसेट के रीफ्रेश होने के बाद विरोध में है। - विरोध में शामिल आकृति का आकार आईडी. पृष्ठआईडी - विरोध में शामिल आकार का पृष्ठ आईडी. |
| [RefreshInterval](../../aspose.diagram/datarecordset/refreshinterval/) { get; set; } | Visio डेटा रिकॉर्डसेट को स्वचालित रूप से कितनी बार (मिनटों में) ताज़ा करता है। यह मान 1 या अधिक होना चाहिए. |
| [RefreshNoReconciliationUI](../../aspose.diagram/datarecordset/refreshnoreconciliationui/) { get; set; } | क्या डेटा-सामंजस्य यूजर इंटरफेस को अक्षम किया जाना चाहिए। ट्रू (1) यूजर इंटरफेस (यूआई) को निष्क्रिय करने के लिए। असत्य (0) UI. को सक्षम करने के लिए |
| [RefreshOverwriteAll](../../aspose.diagram/datarecordset/refreshoverwriteall/) { get; set; } | जब डेटा रिकॉर्डसेट को ताज़ा किया जाता है तो डेटा से जुड़े आकार में डेटा आइटम को आकार देने के लिए उपयोगकर्ता परिवर्तन को अधिलेखित करना है या नहीं। |
| [ReplaceLinks](../../aspose.diagram/datarecordset/replacelinks/) { get; set; } | परिभाषित करता है कि आकृति-डेटा लिंक को कैसे संसाधित किया जाता है जब आकार कॉपी या कट जाते हैं। 1 मौजूदा लिंक को लक्ष्य आकार में बदलने के लिए। लक्ष्य आकार में मौजूदा लिंक बनाए रखने के लिए 0। यदि यह विशेषता अनुपस्थित है, तो Visio उपयोगकर्ता से कॉपी या कट पर लिंक बदलने के लिए कहता है। |
| [RowMaps](../../aspose.diagram/datarecordset/rowmaps/) { get; } | डेटा-रिकॉर्डसेट पंक्ति को आकार में मैप करता है। पंक्ति आईडी - पंक्ति की पंक्ति आईडी, डेटा रिकॉर्डसेट के भीतर अद्वितीय। आकार आईडी - पंक्ति आईडी द्वारा पहचानी गई डेटा-रिकॉर्डसेट पंक्ति में डेटा से जुड़ी आकृति की आकार आईडी। पेजआईडी - RowID. द्वारा पहचानी गई डेटा-रिकॉर्डसेट पंक्ति में डेटा से लिंक की गई आकृति का पृष्ठ आईडी |
| [RowOrder](../../aspose.diagram/datarecordset/roworder/) { get; set; } | प्राथमिक कुंजी के रूप में डेटा रिकॉर्डसेट में पंक्तियों के क्रम का उपयोग करना है या नहीं। सही (1) यदि पंक्ति आईडी पंक्ति क्रम द्वारा निर्धारित की जाती है। असत्य (0) यदि पंक्ति आईडी डेटा रिकॉर्डसेट के प्राथमिक कुंजी कॉलम में मानों द्वारा निर्धारित की जाती है। |
| [TimeRefreshed](../../aspose.diagram/datarecordset/timerefreshed/) { get; set; } | वह दिनांक और समय जब डेटा रिकॉर्डसेट अंतिम बार रीफ्रेश किया गया था। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh)() | कनेक्टेड (गैर-XML-आधारित) DataRecordset से जुड़े क्वेरी स्ट्रिंग को निष्पादित करता है और क्वेरी द्वारा लौटाए गए डेटा स्रोत से नए डेटा के साथ लिंक किए गए आकृतियों को अपडेट करता है। |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh_1)(DataConnectionType) | कनेक्टेड (गैर-XML-आधारित) DataRecordset से जुड़े क्वेरी स्ट्रिंग को निष्पादित करता है और क्वेरी द्वारा लौटाए गए डेटा स्रोत से नए डेटा के साथ लिंक किए गए आकृतियों को अपडेट करता है। |

### यह सभी देखें

* नाम स्थान [Aspose.Diagram](../../aspose.diagram/)
* सभा [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
