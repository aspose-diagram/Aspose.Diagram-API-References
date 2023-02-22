---
title: Protection
second_title: .NET API संदर्भ के लिए Aspose.Diagram
description: लकंग आकर में अनजने में परवर्तन क रकने में मदद करत है लेकन Microsoft Visio क अन्य परस्थतयं में मन रसेट करने से नहं रकत है यह शेपशट वंड में कए गए परवर्तनं से भ सुरक्ष नहं करत है
type: docs
weight: 2880
url: /hi/net/aspose.diagram/protection/
---
## Protection class

लॉकिंग आकार में अनजाने में परिवर्तन को रोकने में मदद करता है लेकिन Microsoft Visio को अन्य परिस्थितियों में मान रीसेट करने से नहीं रोकता है। यह शेपशीट विंडो में किए गए परिवर्तनों से भी सुरक्षा नहीं करता है।

```csharp
public class Protection
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Del](../../aspose.diagram/protection/del/) { get; set; } | एक ध्वज इंगित करता है कि तत्व को स्थानीय रूप से हटा दिया गया है या नहीं। 1 का मान इंगित करता है कि तत्व को स्थानीय रूप से हटा दिया गया था। |
| [LockAspect](../../aspose.diagram/protection/lockaspect/) { get; } | निर्दिष्ट करता है कि आकार का पहलू अनुपात लॉक है या नहीं। यदि लॉक किया गया है, तो आकृति को केवल आनुपातिक रूप से आकार दिया जा सकता है; इसे एक आयाम में आकार नहीं दिया जा सकता है। |
| [LockBegin](../../aspose.diagram/protection/lockbegin/) { get; } | निर्दिष्ट करता है कि 1-डी आकार का प्रारंभ बिंदु किसी विशिष्ट स्थान पर लॉक है या नहीं। |
| [LockCalcWH](../../aspose.diagram/protection/lockcalcwh/) { get; } | निर्दिष्ट करता है कि क्या किसी आकृति का चयन आयत लॉक है, इसलिए किसी वर्टेक्स को संपादित किए जाने पर या जियोम तत्व में किसी तत्व प्रकार को बदलने पर इसकी पुनर्गणना नहीं की जा सकती है। |
| [LockCrop](../../aspose.diagram/protection/lockcrop/) { get; } | निर्दिष्ट करता है कि Microsoft Visio. में क्रॉप टूल के साथ क्रॉप होने के विरुद्ध कोई बाहरी ऑब्जेक्ट लॉक है या नहीं |
| [LockCustProp](../../aspose.diagram/protection/lockcustprop/) { get; } | यह निर्धारित करता है कि उपयोगकर्ता कस्टम गुण परिभाषित करें संवाद बॉक्स का उपयोग करके उपयोगकर्ता इंटरफ़ेस (UI) में कस्टम गुणों को जोड़, हटा या संशोधित कर सकता है या नहीं। |
| [LockDelete](../../aspose.diagram/protection/lockdelete/) { get; } | निर्दिष्ट करता है कि कोई आकृति हटाए जाने के विरुद्ध लॉक है या नहीं. |
| [LockEnd](../../aspose.diagram/protection/lockend/) { get; } | निर्दिष्ट करता है कि 1-डी आकार का अंतिम बिंदु किसी विशिष्ट स्थान पर लॉक है या नहीं। |
| [LockFormat](../../aspose.diagram/protection/lockformat/) { get; } | निर्दिष्ट करता है कि किसी आकृति का स्वरूपण लॉक है या नहीं इसलिए इसे बदला नहीं जा सकता। विशेष रूप से, यह तत्व पाठ, रेखा और भरण स्वरूपण को बदलने से बचाता है, या यह बदलता है कि कौन सा शैली तत्व आकार से प्राप्त होता है। |
| [LockFromGroupFormat](../../aspose.diagram/protection/lockfromgroupformat/) { get; } | एक उप-आकृति को उन स्वरूपण परिवर्तनों को अवरुद्ध करने की अनुमति देता है जो Visio उपयोगकर्ता इंटरफ़ेस में पैरेंट समूह आकार पर लागू होते हैं और अन्यथा अलग-अलग समूह आकृतियों में कैस्केड हो जाते हैं। |
| [LockGroup](../../aspose.diagram/protection/lockgroup/) { get; } | निर्दिष्ट करता है कि क्या कोई समूह लॉक किया गया है ताकि इसे असमूहीकृत नहीं किया जा सके। |
| [LockHeight](../../aspose.diagram/protection/lockheight/) { get; } | निर्दिष्ट करता है कि आकृति की ऊंचाई लॉक है या नहीं। अगर लॉक किया गया है, आकार बदलने पर इसकी ऊंचाई अपरिवर्तित रहती है. |
| [LockMoveX](../../aspose.diagram/protection/lockmovex/) { get; } | निर्दिष्ट करता है कि क्या आकृति की क्षैतिज स्थिति लॉक है ताकि इसे क्षैतिज रूप से स्थानांतरित नहीं किया जा सके। |
| [LockMoveY](../../aspose.diagram/protection/lockmovey/) { get; } | निर्दिष्ट करता है कि क्या आकृति की ऊर्ध्वाधर स्थिति लॉक है ताकि इसे लंबवत रूप से स्थानांतरित नहीं किया जा सके। |
| [LockRotate](../../aspose.diagram/protection/lockrotate/) { get; } | निर्दिष्ट करता है कि क्या आकृति घुमाए जाने के विरुद्ध Microsoft Visio में रोटेशन टूल या रोटेट लेफ्ट या रोटेट राइट कमांड के साथ लॉक है। |
| [LockSelect](../../aspose.diagram/protection/lockselect/) { get; } | निर्दिष्ट करता है कि क्या किसी आकृति का चयन आयत लॉक है, इसलिए किसी वर्टेक्स को संपादित किए जाने पर या जियोम तत्व में किसी तत्व प्रकार को बदलने पर इसकी पुनर्गणना नहीं की जा सकती है। |
| [LockTextEdit](../../aspose.diagram/protection/locktextedit/) { get; } | निर्दिष्ट करता है कि किसी आकृति का पाठ लॉक किया गया है ताकि इसे संपादित नहीं किया जा सके। हालाँकि, पाठ संवाद बॉक्स के फ़ॉन्ट टैब पर शैली विकल्पों का उपयोग करके, शैली को लागू करके पाठ को अभी भी स्वरूपित किया जा सकता है। |
| [LockThemeColors](../../aspose.diagram/protection/lockthemecolors/) { get; } | उपयोगकर्ताओं को आकार में थीम रंग लगाने से रोकता है. |
| [LockThemeEffects](../../aspose.diagram/protection/lockthemeeffects/) { get; } | उपयोगकर्ताओं को आकार पर थीम प्रभाव लागू करने से रोकता है. |
| [LockVtxEdit](../../aspose.diagram/protection/lockvtxedit/) { get; } | निर्दिष्ट करता है कि किसी आकृति के कोने लॉक हैं या नहीं ताकि उन्हें टूलबार पर किसी भी टूल से संपादित नहीं किया जा सके. |
| [LockWidth](../../aspose.diagram/protection/lockwidth/) { get; } | निर्दिष्ट करता है कि क्या आकृति की चौड़ाई लॉक है ताकि आकृति का आकार बदलने पर यह अपरिवर्तित रहे। |

### यह सभी देखें

* नाम स्थान [Aspose.Diagram](../../aspose.diagram/)
* सभा [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
