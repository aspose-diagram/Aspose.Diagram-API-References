---
title: Window
second_title: .NET API संदर्भ के लिए Aspose.Diagram
description: मइक्रसफ्ट वसय उदहरण में एक खुल खड़क क प्रतनधत्व करत है जब DatadiagramML फ़इल क Visio. द्वर प्ररंभ में खल जत है त इस तत्व में एप्लकेशन वर्कस्पेस में उपयगकर्त इंटरफ़ेस वंड क सटक रूप से फर से बनने के लए आवश्यक जनकर हत है
type: docs
weight: 4390
url: /hi/net/aspose.diagram/window/
---
## Window class

माइक्रोसॉफ्ट विसियो उदाहरण में एक खुली खिड़की का प्रतिनिधित्व करता है। जब DatadiagramML फ़ाइल को Visio. द्वारा प्रारंभ में खोला जाता है, तो इस तत्व में एप्लिकेशन वर्कस्पेस में उपयोगकर्ता इंटरफ़ेस विंडो को सटीक रूप से फिर से बनाने के लिए आवश्यक जानकारी होती है।

```csharp
public class Window
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Window](window/)() | कंस्ट्रक्टर. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Container](../../aspose.diagram/window/container/) { get; set; } | कंटेनर की आईडी: पेज, शीट या मास्टर। कंटेनर प्रकार निर्दिष्ट होने पर ही प्रासंगिक और आवश्यक है। |
| [ContainerType](../../aspose.diagram/window/containertype/) { get; set; } | निम्न मानों में से एक हो सकता है: दस्तावेज़, पृष्ठ या मास्टर। केवल तभी प्रासंगिक है जब WindowType को आरेखण या शीट के रूप में निर्दिष्ट किया गया हो. |
| [Document](../../aspose.diagram/window/document/) { get; set; } | इस विंडो में प्रदर्शित दस्तावेज़ का फ़ाइल पथ। यह विशेषता उन विंडो के लिए प्रासंगिक है जिनके विंडो टाइप को स्टेंसिल के रूप में निर्दिष्ट किया गया है। |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled/) { get; set; } | निर्दिष्ट करता है कि डायनेमिक ग्रिड सुविधा किसी दस्तावेज़ या विंडो के लिए सक्षम है या नहीं। |
| [GlueSettings](../../aspose.diagram/window/gluesettings/) { get; set; } | उन वस्तुओं को निर्दिष्ट करता है जो दस्तावेज़ में गोंद सक्षम होने पर गोंद को आकार देती हैं। |
| [ID](../../aspose.diagram/window/id/) { get; set; } | इसके मूल तत्व के भीतर तत्व की अनूठी आईडी। |
| [Master](../../aspose.diagram/window/master/) { get; set; } | मास्टर आईडी अगर यह विंडो मास्टर प्रदर्शित कर रही है। |
| [Page](../../aspose.diagram/window/page/) { get; set; } | पृष्ठ आईडी यदि यह विंडो एक पृष्ठ प्रदर्शित कर रही है। केवल तभी प्रासंगिक है जब WindowType को आरेखण के रूप में निर्दिष्ट किया गया हो और कंटेनर प्रकार को Page. के रूप में निर्दिष्ट किया गया हो |
| [ParentWindow](../../aspose.diagram/window/parentwindow/) { get; set; } | उस विंडो की आईडी जिसमें यह स्टैंसिल विंडो समाहित है। केवल तभी प्रासंगिक जब WindowType को स्टैंसिल के रूप में निर्दिष्ट किया गया हो. |
| [ReadOnly](../../aspose.diagram/window/readonly/) { get; set; } | रीड-ओनली फ़्लैग अगर यह स्टैंसिल दस्तावेज़ स्टैंसिल नहीं है. |
| [Sheet](../../aspose.diagram/window/sheet/) { get; set; } | कंटेनर में शीट की आईडी। केवल तभी प्रासंगिक है जब कंटेनर को शीट के रूप में निर्दिष्ट किया गया हो. |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints/) { get; set; } | निर्दिष्ट करता है कि कनेक्शन बिंदु विंडो में दिखाए जाते हैं या नहीं। |
| [ShowGrid](../../aspose.diagram/window/showgrid/) { get; set; } | निर्दिष्ट करता है कि ड्राइंग विंडो में ग्रिड दिखाया गया है या नहीं। |
| [ShowGuides](../../aspose.diagram/window/showguides/) { get; set; } | निर्दिष्ट करता है कि क्या मार्गदर्शिकाएँ आरेखण विंडो में दिखाई जाती हैं. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks/) { get; set; } | निर्दिष्ट करता है कि पृष्ठ विराम विंडो में दिखाए जाते हैं या नहीं। |
| [ShowRulers](../../aspose.diagram/window/showrulers/) { get; set; } | निर्दिष्ट करता है कि आरेखण विंडो में रूलर दिखाए गए हैं या नहीं. |
| [SnapAngles](../../aspose.diagram/window/snapangles/) { get; } | में SnapAngle तत्वों का संग्रह है। |
| [SnapExtensions](../../aspose.diagram/window/snapextensions/) { get; set; } | निर्दिष्ट करता है कि सक्रिय विंडो के लिए एक विशिष्ट स्नैप एक्सटेंशन सेटिंग सक्षम या अक्षम है या नहीं। मान निम्न तालिका में मानों का योग हो सकता है. |
| [SnapSettings](../../aspose.diagram/window/snapsettings/) { get; set; } | उन वस्तुओं को निर्दिष्ट करता है जो विंडो में स्नैप सक्रिय होने पर स्नैप को आकार देती हैं। मान निम्न तालिका में मानों का योग हो सकता है। |
| [StencilGroup](../../aspose.diagram/window/stencilgroup/) { get; set; } | मर्ज किए गए स्टैंसिल विंडो के समूह को निर्दिष्ट करता है जिसमें विंडो एक सदस्य है। यह विशेषता केवल उन विंडो तत्वों के लिए प्रासंगिक है जिनकी विंडो टाइप विशेषता स्टैंसिल है, और केवल तभी जब स्टैंसिल विंडो स्टैंसिल विंडो के मर्ज किए गए समूह का हिस्सा हो। सभी स्टैंसिल विंडो जो एक ही मर्ज किए गए समूह का हिस्सा हैं, एक ही स्टैंसिल समूह तत्व मान हैं। |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos/) { get; set; } | में एक पूर्णांक होता है जो विंडो में एक समूह के भीतर स्टैंसिल की सापेक्ष स्थिति को निर्दिष्ट करता है। |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos/) { get; set; } | आरेखण विंडो के पृष्ठ टैब नियंत्रण की चौड़ाई निर्दिष्ट करता है (आरेखण विंडो की कुल चौड़ाई के अंश के रूप में). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx/) { get; set; } | वैकल्पिक डबल. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery/) { get; set; } | वैकल्पिक डबल. |
| [ViewScale](../../aspose.diagram/window/viewscale/) { get; set; } | वैकल्पिक डबल. |
| [WindowHeight](../../aspose.diagram/window/windowheight/) { get; set; } | विंडो आयत की ऊँचाई। |
| [WindowLeft](../../aspose.diagram/window/windowleft/) { get; set; } | विंडो आयत का बायाँ समन्वय। |
| [WindowState](../../aspose.diagram/window/windowstate/) { get; set; } | यह विशेषता निम्नलिखित मानों का योग हो सकती है। |
| [WindowTop](../../aspose.diagram/window/windowtop/) { get; set; } | विंडो आयत का शीर्ष समन्वय। |
| [WindowType](../../aspose.diagram/window/windowtype/) { get; set; } | एक प्रगणित मान जो निम्न में से एक हो सकता है: ड्रॉइंग, शीट, स्टेंसिल, या आइकन। WindowType='Stencil' का विंडो एलिमेंट उसकी पैरेंट ड्रॉइंग विंडो (WindowType='Drawing') के बाद और किसी भी अन्य ड्रॉइंग विंडो से पहले दिखाई देना चाहिए तत्व. |
| [WindowWidth](../../aspose.diagram/window/windowwidth/) { get; set; } | विंडो आयत की चौड़ाई. |

### यह सभी देखें

* नाम स्थान [Aspose.Diagram](../../aspose.diagram/)
* सभा [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
