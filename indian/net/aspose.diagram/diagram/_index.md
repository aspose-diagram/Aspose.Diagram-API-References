---
title: Diagram
second_title: .NET API संदर्भ के लिए Aspose.Diagram
description: Visio ऑब्जेक्ट पदनुक्रम क मूल तत्व.
type: docs
weight: 1170
url: /hi/net/aspose.diagram/diagram/
---
## Diagram class

Visio ऑब्जेक्ट पदानुक्रम का मूल तत्व.

```csharp
public class Diagram : IDisposable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Diagram](diagram/#constructor)() | डिफ़ॉल्ट कंस्ट्रक्टर। |
| [Diagram](diagram/#constructor_1)(Stream) | पब्लिक क्लास कंस्ट्रक्टर, आरेख को स्ट्रीम से लोड करता है। |
| [Diagram](diagram/#constructor_4)(string) | पब्लिक क्लास कंस्ट्रक्टर, फ़ाइल से आरेख लोड करता है। |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | पब्लिक क्लास कंस्ट्रक्टर, आरेख को पूर्वनिर्धारित प्रारूप का उपयोग करके स्ट्रीम से लोड करता है। |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | पब्लिक क्लास कंस्ट्रक्टर, आरेख को पूर्वनिर्धारित लोड फ़ाइल विकल्पों का उपयोग करके स्ट्रीम से लोड करता है। |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | पब्लिक क्लास कंस्ट्रक्टर, पूर्वनिर्धारित प्रारूप का उपयोग करके फ़ाइल से आरेख लोड करता है। |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | पब्लिक क्लास कंस्ट्रक्टर, पूर्वनिर्धारित लोड फ़ाइल विकल्पों का उपयोग करके फ़ाइल से आरेख लोड करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | सक्रिय पृष्ठ निर्दिष्ट करता है |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | दस्तावेज़ बनाने के लिए प्रयुक्त Visio उदाहरण की बिल्ड संख्या। |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | में दस्तावेज़ की रंग तालिका शामिल है। प्रत्येक दस्तावेज़ में एक रंग तालिका होती है, जो उन 24 मानक रंगों को सूचीबद्ध करती है जो ऑब्जेक्ट पर लागू करने के लिए उपलब्ध हैं, जैसे दस्तावेज़ में आकार, पाठ और परतें। |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | में दस्तावेज़ के लिए डेटाकनेक्शन तत्व शामिल हैं। |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | दस्तावेज़ ऑब्जेक्ट से संबद्ध DataRecordset ऑब्जेक्ट का संग्रह. |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | उपयोगकर्ता-इंटरफ़ेस भाषा की विशिष्ट आईडी जिसे उपयोगकर्ता ने Microsoft Office 2010 भाषा प्राथमिकताओं में निर्दिष्ट किया है। |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | में दस्तावेज़ संपत्ति तत्व शामिल हैं जैसे दस्तावेज़ का शीर्षक, लेखक, और इसी तरह। |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | में दस्तावेज़ सेटिंग निर्दिष्ट करने वाले तत्व शामिल हैं। |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | दस्तावेज़ की शेपशीट संरचना निर्दिष्ट करता है. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | दस्तावेज़ के लिए एक MIME (बहुउद्देशीय इंटरनेट मेल एक्सटेंशन) एन्कोडेड MAPI ई-मेल रूटिंग स्लिप शामिल है। |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | में प्रत्येक ईवेंट के लिए एक EventItem तत्व होता है जिसका ऑब्जेक्ट को जवाब देना चाहिए। |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | फ़ॉन्ट फ़ोल्डर पथ को इंगित करता है |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | में फ़ॉन्ट तत्वों का संग्रह है |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | में दस्तावेज़ के शीर्षलेख और पादलेख के लिए तत्व शामिल हैं। |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | इंटरप्ट मॉनिटर प्राप्त करता है और सेट करता है। |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | इंगित करता है कि दस्तावेज़ को Visio के बाहर संशोधित किया गया है या नहीं। यदि मौजूद है, तो Visio फ़ाइल की सामग्री का पूरी तरह से परीक्षण करेगा। आपके द्वारा Visio. के बाहर बनाई गई फ़ाइलों को छोड़ दें |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | संग्रह मास्टर ऑब्जेक्ट. |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | ड्राइंग में मीट्रिक इकाइयों का उपयोग करना है या नहीं। मीट्रिक इकाइयों का उपयोग करने के लिए इस विशेषता को True (1) पर सेट करें; अंग्रेजी इकाइयों का उपयोग करने के लिए इसे गलत (0) पर सेट करें। |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | संग्रह पृष्ठ ऑब्जेक्ट. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | रिबन XML स्ट्रिंग जो रिबन यूजर इंटरफेस को अनुकूलित करने के लिए दस्तावेज़ को पास की जाती है। |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | एक्सएमएल मान. |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | इंगित करता है कि दस्तावेज़ को Visio के बाहर संशोधित किया गया है या नहीं। यदि मौजूद है, तो Visio फ़ाइल की सामग्री का पूरी तरह से परीक्षण करेगा। आपके द्वारा Visio. के बाहर बनाई गई फ़ाइलों को छोड़ दें |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | संग्रह स्टाइलशीट ऑब्जेक्ट. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | रिबन XML स्ट्रिंग जो क्विक एक्सेस टूलबार या रिबन को अनुकूलित करने के लिए दस्तावेज़ को पास की जाती है। |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | दस्तावेज़ के आरेख सत्यापन के बारे में जानकारी संग्रहीत करता है। |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | VbaProject प्राप्त करता है[`VbaProject`](./vbaproject/) . |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | MIME (बहुउद्देशीय इंटरनेट मेल एक्सटेंशन) एन्कोडेड प्रारूप में एप्लिकेशन प्रोजेक्ट डेटा के लिए Microsoft Visual Basic शामिल है। |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Visio उदाहरण की संस्करण संख्या। Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | में दस्तावेज़ के लिए विंडो तत्व शामिल हैं। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | मास्टर के नाम या NameU. द्वारा स्रोत आरेख से आरेख में मास्टर जोड़ता है |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | मास्टर आईडी द्वारा टेम्प्लेट स्ट्रीम से आरेख में मास्टर जोड़ता है। |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | मास्टर के नाम या NameU. द्वारा टेम्प्लेट स्ट्रीम से आरेख में मास्टर जोड़ता है |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | मास्टर की आईडी द्वारा टेम्प्लेट फ़ाइल से आरेख में मास्टर जोड़ता है। |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | मास्टर के नाम या NameU. द्वारा टेम्प्लेट फ़ाइल से आरेख में मास्टर जोड़ता है |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | विशिष्ट पृष्ठ पर मास्टर द्वारा बनाई गई आकृति जोड़ता है। |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | परिभाषित PinX और PinY. के साथ पृष्ठ पर मास्टर द्वारा बनाई गई आकृति जोड़ता है |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | परिभाषित पिनएक्स, पिनवाई, चौड़ाई और ऊंचाई के साथ पृष्ठ पर मास्टर द्वारा बनाई गई आकृति जोड़ता है। |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | अन्य आरेख वस्तु को जोड़ता है। |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | किसी स्रोत आरेख से थीम की प्रतिलिपि बनाता है. |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | मुक्त करने, जारी करने, या अप्रबंधित संसाधनों को रीसेट करने से संबंधित एप्लिकेशन-परिभाषित कार्य करता है। |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | डिफ़ॉल्ट फ़ॉन्ट्स फ़ोल्डर पथ प्राप्त करें |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | अप्रयुक्त शैलियाँ प्राप्त करें |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | इंगित करता है कि क्या इस आरेख में छिपी हुई जानकारी है। |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | आरेख के सभी पृष्ठों के लिए आकृतियाँ निर्धारित करता है और/या कनेक्टर्स का मार्ग बदलता है। |
| [Print](../../aspose.diagram/diagram/print/#print)() | पूरे दस्तावेज़ को डिफ़ॉल्ट प्रिंटर पर प्रिंट करता है। |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट नियंत्रक का उपयोग करके निर्दिष्ट प्रिंटर सेटिंग्स के अनुसार दस्तावेज़ को प्रिंट करता है। |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | पूरे दस्तावेज़ को डिफ़ॉल्ट प्रिंटर पर प्रिंट करता है। |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | पूरे दस्तावेज़ को निर्दिष्ट प्रिंटर पर प्रिंट करें, मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट नियंत्रक का उपयोग करके। |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट नियंत्रक का उपयोग करके निर्दिष्ट प्रिंटर सेटिंग्स के अनुसार दस्तावेज़ को प्रिंट करता है। |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट नियंत्रक और एक दस्तावेज़ नाम का उपयोग करके, निर्दिष्ट प्रिंटर सेटिंग्स के अनुसार दस्तावेज़ को प्रिंट करता है। |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | पूरे दस्तावेज़ को निर्दिष्ट प्रिंटर पर प्रिंट करें, मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट नियंत्रक का उपयोग करके। |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट नियंत्रक और एक दस्तावेज़ नाम का उपयोग करके दस्तावेज़ को प्रिंट करता है। |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट नियंत्रक और एक दस्तावेज़ नाम का उपयोग करके, निर्दिष्ट प्रिंटर सेटिंग्स के अनुसार दस्तावेज़ को प्रिंट करता है। |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट नियंत्रक और एक दस्तावेज़ नाम का उपयोग करके दस्तावेज़ को प्रिंट करता है। |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | आरेख में सभी DataRecordSet के लिए रीफ्रेश विधि को आमंत्रित करता है। |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | अप्रयुक्त जानकारी निकालें |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | इस डायग्राम से VBA/मैक्रो को हटाता है। |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | आरेख डेटा को स्ट्रीम में सहेजता है। |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | निर्दिष्ट सहेजें विकल्पों का उपयोग करके आरेख को स्ट्रीम में सहेजता है। |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | आरेख डेटा को फ़ाइल में सहेजता है। |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | निर्दिष्ट सहेज विकल्पों का उपयोग करके दस्तावेज़ को एक फ़ाइल में सहेजता है। |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | आरेख को वीएसडी स्ट्रीम से वीडीडब्ल्यू स्ट्रीम प्रारूप में निर्यात करता है। अभी तक लागू नहीं किया गया. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | आरेख को वीएसडी स्ट्रीम से *.vdw फ़ाइल स्वरूप में निर्यात करता है। अभी तक लागू नहीं किया गया. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | आरेख को वीएसडी फ़ाइल से वीडीडब्ल्यू स्ट्रीम प्रारूप में निर्यात करता है। अभी तक लागू नहीं किया गया. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | आरेख को वीएसडी से वीडीडब्ल्यू प्रारूप में निर्यात करता है। अभी तक लागू नहीं किया गया. |

### यह सभी देखें

* नाम स्थान [Aspose.Diagram](../../aspose.diagram/)
* सभा [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
