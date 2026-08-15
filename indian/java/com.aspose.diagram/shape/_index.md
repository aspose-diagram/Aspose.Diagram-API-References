---
title: Shape
second_title: Aspose.Diagram for Java API Reference
description: मास्टर पेज या समूह आकार तत्व में आकार को परिभाषित करने वाले तत्व शामिल करता है।
type: docs
weight: 355
url: /hi/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

एक मास्टर, पेज, या समूह आकार तत्व में आकार को परिभाषित करने वाले तत्वों को सम्मिलित करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Shape()](#Shape--) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [bringForward()](#bringForward--) | आकार को z-क्रम में एक स्थिति आगे ले जाता है। |
| [bringToFront()](#bringToFront--) | आकार को z-क्रम के सामने ले जाता है। |
| [centerDrawing()](#centerDrawing--) | पृष्ठ के विस्तार के सापेक्ष आकार को केंद्रित करें |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | एक एरे लौटाता है जिसमें उन आकारों के पहचानकर्ता (IDs) होते हैं जो इस आकार से जुड़े होते हैं। |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | एक एरे लौटाता है जिसमें उन आकारों के पहचानकर्ता होते हैं जो किसी आकार पर निर्भर होते हैं। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | ActiveX नियंत्रण प्राप्त करता है। |
| [getActs()](#getActs--) | Act तत्वों का संग्रह शामिल करता है। |
| [getAlign()](#getAlign--) | आकार की गाइड या गाइड पॉइंट के सापेक्ष संरेखण को दर्शाता है, जिससे आकार चिपका हुआ है। |
| [getChars()](#getChars--) | Char तत्वों का संग्रह शामिल करता है। |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | ConnectionABCD तत्वों का संग्रह शामिल करता है। |
| [getConnections()](#getConnections--) | Connection तत्वों का संग्रह शामिल करता है। |
| [getConnectorRule()](#getConnectorRule--) | एक connectorRule लौटाता है जिसमें आकार का ID और कनेक्शन होते हैं जो इस आकार से जुड़े होते हैं। |
| [getConnectorsType()](#getConnectorsType--) | कनेक्टर प्रकार प्राप्त करें |
| [getControlData()](#getControlData--) | नियंत्रण का डेटा प्राप्त करता है। |
| [getControls()](#getControls--) | Control तत्वों का संग्रह शामिल करता है। |
| [getData1()](#getData1--) | एक मनमाना स्ट्रिंग मान शामिल करता है जिसका उपयोग आकार के बारे में अतिरिक्त जानकारी प्रदान करने के लिए किया जाता है। |
| [getData2()](#getData2--) | एक मनमाना स्ट्रिंग मान शामिल करता है जिसका उपयोग आकार के बारे में अतिरिक्त जानकारी प्रदान करने के लिए किया जाता है। |
| [getData3()](#getData3--) | एक मनमाना स्ट्रिंग मान शामिल करता है जिसका उपयोग आकार के बारे में अतिरिक्त जानकारी प्रदान करने के लिए किया जाता है। |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getDiagram()](#getDiagram--) | Visio ऑब्जेक्ट्स पदानुक्रम का मूल तत्व। |
| [getDisplayText()](#getDisplayText--) | इंटरफ़ेस पर प्रदर्शित पाठ प्राप्त करें |
| [getEvent()](#getEvent--) | आकार घटनाओं को नियंत्रित करने वाले सूत्रों को निर्दिष्ट करने वाले तत्व शामिल हैं। |
| [getFields()](#getFields--) | Field तत्वों का संग्रह शामिल करता है। |
| [getFill()](#getFill--) | आकार और उसके ड्रॉप शैडो के लिए वर्तमान भराव फ़ॉर्मेटिंग मानों को शामिल करता है, जिसमें पैटर्न, अग्रभूमि रंग, और पृष्ठभूमि रंग शामिल हैं। |
| [getFillStyle()](#getFillStyle--) | StyleSheet जिससे यह आकार भरने के फॉर्मेटिंग को विरासत में लेता है। |
| [getForeign()](#getForeign--) | Microsoft Visio दस्तावेज़ में उपयोग किए गए किसी अन्य प्रोग्राम के ऑब्जेक्ट की चौड़ाई और ऊँचाई निर्दिष्ट करने वाले तत्वों को शामिल करता है। |
| [getForeignData()](#getForeignData--) | चित्र डेटा का MIME (Multipurpose Internet Mail Extensions) एन्कोडेड BLOB शामिल करता है, जैसे Windows मेटाफाइल, बिटमैप, या OLE डेटा। |
| [getGeoms()](#getGeoms--) | Geom तत्वों का संग्रह शामिल करता है। |
| [getGroup()](#getGroup--) | ऐसे तत्व शामिल हैं जो नियंत्रित करते हैं कि आप समूह में आकार कैसे जोड़ते हैं, समूह के सदस्यों को कैसे स्थानांतरित करते हैं, और समूहों का चयन कैसे करते हैं। |
| [getHelp()](#getHelp--) | Shape तत्व के हेल्प फ़ाइल टॉपिक और कॉपीराइट जानकारी को निर्दिष्ट करने वाले तत्व शामिल करता है। |
| [getHyperlinks()](#getHyperlinks--) | Hyperlink तत्वों का एक संग्रह शामिल करता है। |
| [getID()](#getID--) | तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID। |
| [getImage()](#getImage--) | बिटमैप के लिए गामा, चमक, कंट्रास्ट, ब्लर, शार्पन, डीनॉइज़ और ट्रांसपेरेंसी मानों को शामिल करता है। |
| [getInheritChars()](#getInheritChars--) | मास्टर आकार द्वारा विरासत में लिए गए आकार के लिए char मान शामिल करता है। |
| [getInheritFill()](#getInheritFill--) | पैरेंट स्टाइल और मास्टर आकार द्वारा विरासत में लिए गए आकार के लिए भरने के फॉर्मेटिंग मान शामिल करता है। |
| [getInheritGeoms()](#getInheritGeoms--) | मास्टर शेप द्वारा विरासत में मिले शेप के लिए Geoms मान शामिल हैं। |
| [getInheritLine()](#getInheritLine--) | पैरेंट स्टाइल और मास्टर शेप द्वारा विरासत में मिले शेप के लिए लाइन फ़ॉर्मेटिंग मान शामिल हैं। |
| [getInheritParas()](#getInheritParas--) | पैरेंट स्टाइल और मास्टर शेप द्वारा विरासत में मिले शेप के लिए paras शामिल हैं। |
| [getInheritProps()](#getInheritProps--) | मास्टर शेप द्वारा विरासत में मिले शेप के लिए props शामिल हैं। |
| [getInheritTextBlock()](#getInheritTextBlock--) | पैरेंट स्टाइल और मास्टर शेप द्वारा विरासत में मिले शेप के लिए टेक्स्टब्लॉक मान शामिल हैं। |
| [getInheritUsers()](#getInheritUsers--) | मास्टर शेप द्वारा विरासत में मिले शेप के लिए उपयोगकर्ता शामिल हैं। |
| [getLayerMem()](#getLayerMem--) | LayerMember तत्व शामिल है, जो प्रत्येक लेयर को निर्दिष्ट करता है जिससे आकार असाइन किया गया है। |
| [getLayout()](#getLayout--) | आकार की प्लेसमेंट और कनेक्टर रूटिंग सेटिंग्स को नियंत्रित करने वाले तत्व शामिल हैं। |
| [getLine()](#getLine--) | एक आकार के लिए रेखा गुणों को नियंत्रित करने वाले तत्वों को शामिल करता है, जैसे पैटर्न, वजन और रंग। |
| [getLineStyle()](#getLineStyle--) | यह शेप जिस StyleSheet से लाइन फ़ॉर्मेटिंग विरासत में लेता है। |
| [getMaster()](#getMaster--) | शेप जिस मास्टर से अपना डेटा विरासत में लेता है। |
| [getMasterShape()](#getMasterShape--) | यह एट्रिब्यूट केवल उन शेप्स में मौजूद हो सकता है जो ग्रुप शेप के सदस्य हैं, और ग्रुप एक मास्टर का इंस्टेंस है। |
| [getMisc()](#getMisc--) | Shape तत्व के हेल्प फ़ाइल टॉपिक और कॉपीराइट जानकारी को निर्दिष्ट करने वाले तत्व शामिल करता है। |
| [getName()](#getName--) | तत्व का नाम। |
| [getNameU()](#getNameU--) | तत्व का सार्वभौमिक नाम। |
| [getOneD()](#getOneD--) | निर्धारित करता है कि शेप एक-आयामी (1-D) ऑब्जेक्ट के रूप में व्यवहार करता है या नहीं। |
| [getPage()](#getPage--) | Visio ऑब्जेक्ट्स पदानुक्रम का मूल तत्व। |
| [getParas()](#getParas--) | Para तत्वों का संग्रह शामिल करता है। |
| [getParentShape()](#getParentShape--) | शेप का पैरेंट। |
| [getProps()](#getProps--) | Prop तत्वों का एक संग्रह शामिल करता है। |
| [getProtection()](#getProtection--) | लॉकिंग आकृति में अनजाने परिवर्तन को रोकने में मदद करती है, लेकिन अन्य परिस्थितियों में Microsoft Visio को मान रीसेट करने से नहीं रोकती। |
| [getPureText()](#getPureText--) | टेक्स्ट स्ट्रिंग प्राप्त करें |
| [getRootShape()](#getRootShape--) | यदि यह शेप एक मास्टर इंस्टेंस का हिस्सा है तो इंस्टेंस का टॉप-लेवल शेप लौटाता है। |
| [getScratchs()](#getScratchs--) | Scratch तत्वों का एक संग्रह शामिल करता है। |
| [getShapes()](#getShapes--) | Shape तत्वों का संग्रह शामिल है। |
| [getSmartTagDefs()](#getSmartTagDefs--) | SmartTagDef तत्वों का संग्रह शामिल करता है। |
| [getTabsCollection()](#getTabsCollection--) | Tab तत्वों का संग्रह शामिल करता है। |
| [getText()](#getText--) | एक शेप का टेक्स्ट शामिल करता है। |
| [getTextBlock()](#getTextBlock--) | शेप के टेक्स्ट ब्लॉक में टेक्स्ट की संरेखण, मार्जिन और डिफ़ॉल्ट टैब स्टॉप स्थितियों को निर्दिष्ट करने वाले तत्व शामिल करता है। |
| [getTextStyle()](#getTextStyle--) | यह शेप जिस StyleSheet से टेक्स्ट फ़ॉर्मेटिंग विरासत में लेता है। |
| [getTextXForm()](#getTextXForm--) | शेप के टेक्स्ट ब्लॉक के बारे में स्थिति जानकारी निर्दिष्ट करने वाले तत्व शामिल करता है। |
| [getThreeDFormat()](#getThreeDFormat--) | ThreeDFormat प्राप्त करता है। |
| [getTwoD()](#getTwoD--) | निर्धारित करता है कि शेप दो-आयामी (2-D) ऑब्जेक्ट के रूप में व्यवहार करता है या नहीं। |
| [getType()](#getType--) | एक शेप का प्रकार। |
| [getUniqueID()](#getUniqueID--) | शेप को सौंपा गया GUID (ग्लोबली यूनिक आइडेंटिफायर)। |
| [getUsers()](#getUsers--) | User तत्वों का एक संग्रह शामिल करता है। |
| [getXForm()](#getXForm--) | आकार के बारे में सामान्य पोजिशनिंग जानकारी निर्दिष्ट करने वाले तत्व शामिल हैं। |
| [getXForm1D()](#getXForm1D--) | एक-आयामी आकार के प्रारंभ बिंदु और अंत बिंदु के x- और y-निर्देशांक को शामिल करता है। |
| [getZOrderIndex()](#getZOrderIndex--) | गाइड शेप को छोड़कर z-ऑर्डर में शेप का इंडेक्स लौटाता है। |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | एक एरे लौटाता है जिसमें उन शेप्स के पहचानकर्ता होते हैं जो किसी शेप से चिपके होते हैं। |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | यह दर्शाता है कि ये दो शेप्स जुड़े हैं या नहीं। |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | यह दर्शाता है कि यह शेप किसी अन्य शेप को सम्मिलित करता है या नहीं। |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | यह दर्शाता है कि ये दो शेप्स चिपके हुए हैं या नहीं। |
| [isInGroup()](#isInGroup--) | यह दर्शाता है कि यह शेप एक ग्रुप शेप में है या नहीं। |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | यह दर्शाता है कि यह आकार दूसरे आकार को काटता है या नहीं। |
| [isTextEmpty()](#isTextEmpty--) | यह संकेत करता है कि आकार में टेक्स्ट है और टेक्स्ट खाली है या नहीं। |
| [move(double dX, double dY)](#move-double-double-) | आकार को वर्तमान स्थिति से dX और dY इंच की दूरी पर ले जाता है। |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | आकार को पृष्ठ पर नई निरपेक्ष स्थिति पर ले जाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | आकार के टेक्स्ट या अन्य चीज़ों को बदलते समय xform, कनेक्शन और geom सहित आकार की स्थिति को रीफ़्रेश करता है। |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | एक आकार की टेक्स्ट स्ट्रिंग को बदलें। |
| [sendBackward()](#sendBackward--) | आकार को z-क्रम में एक स्थिति पीछे ले जाता है। |
| [sendToBack()](#sendToBack--) | आकार को z-क्रम के पीछे ले जाता है। |
| [setAngle(double angle)](#setAngle-double-) | आकार का नया कोण सेट करता है। |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | कनेक्टर्स प्रकार सेट करें |
| [setData1(String value)](#setData1-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | आकार की नई ऊँचाई सेट करता है। |
| [setID(long value)](#setID-long-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | इस आकार पर एक प्रीसेट थीम लागू करें |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | इस आकार पर एक प्रीसेट थीम वैरिएंट क्विकस्टाइल लागू करें |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | pply इस आकार पर एक प्रीसेट थीम वैरिएंट क्विकस्टाइल लागू करें, जैसे आकार स्टाइल ड्रॉपडाउन सूची में थीम स्टाइल विकल्प |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | इस आकार पर एक प्रीसेट थीम वैरिएंट लागू करें |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | आकार की नई चौड़ाई सेट करता है। |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | आकार की HTML बनाता है और निर्दिष्ट फॉर्मेट में इसे स्ट्रीम पर सहेजता है। |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | आकार की HTML बनाता है और निर्दिष्ट फॉर्मेट में इसे स्ट्रीम पर सहेजता है। |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | HTML बनाता है और इसे फ़ाइल में सहेजता है। |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | आकार की इमेज बनाता है और निर्दिष्ट फॉर्मेट में इसे स्ट्रीम पर सहेजता है। |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | आकार की इमेज बनाता है और निर्दिष्ट फॉर्मेट में इसे स्ट्रीम पर सहेजता है। |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | आकार की इमेज बनाता है और इसे फ़ाइल में सहेजता है। |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | आकार का PDF बनाता है और इसे स्ट्रीम पर सहेजता है। |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | आकार का PDF बनाता है और इसे स्ट्रीम पर सहेजता है। |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | आकार को PDF फ़ाइल में सहेजता है। |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | आकार को SVG फ़ाइल में सहेजता है। |
| [ungroup()](#ungroup--) | आकार को अनग्रुप करें |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


कंस्ट्रक्टर।

### bringForward() {#bringForward--}
```
public void bringForward()
```


आकार को z-क्रम में एक स्थिति आगे ले जाता है।

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


आकार को z-क्रम के सामने ले जाता है।

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


पृष्ठ के विस्तार के सापेक्ष आकार को केंद्रित करें

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


एक एरे लौटाता है जिसमें उन आकारों के पहचानकर्ता (IDs) होते हैं जो इस आकार से जुड़े होते हैं।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| फ़्लैग | int | कनेक्टर्स की दिशा के आधार पर लौटाए गए आकार IDs की एरे को फ़िल्टर करता है। संभावित मानों के लिए Remarks देखें Aspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | निर्दिष्ट categoryString से मेल खाने वाले आकारों के IDs तक सीमित करके लौटाए गए आकार IDs की array को फ़िल्टर करता है। |

**Returns:**
long[] - IDs सरणीlong.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


एक एरे लौटाता है जिसमें उन आकारों के पहचानकर्ता होते हैं जो किसी आकार पर निर्भर होते हैं।

**Returns:**
long[] - IDs सरणीlong.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
बूलियन
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


ActiveX नियंत्रण प्राप्त करता है।

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Act तत्वों का संग्रह शामिल करता है।

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


एक आकार की गाइड या गाइड बिंदु के सापेक्ष संरेखण को दर्शाता है, जिससे आकार चिपका हुआ है। Align तत्व केवल उन आकारों के लिए दिखाई देता है जो गाइड या गाइड बिंदुओं से चिपके होते हैं।

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Char तत्वों का संग्रह शामिल करता है।

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClippingPath() {#getClippingPath--}
```
public String getClippingPath()
```




**Returns:**
java.lang.String
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


ConnectionABCD तत्वों का संग्रह शामिल करता है।

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Connection तत्वों का संग्रह शामिल करता है।

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


एक connectorRule लौटाता है जिसमें आकार का ID और कनेक्शन होते हैं जो इस आकार से जुड़े होते हैं।

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


कनेक्टर प्रकार प्राप्त करें

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


नियंत्रण का डेटा प्राप्त करता है।

**Returns:**
बाइट[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Control तत्वों का संग्रह शामिल करता है।

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


एक मनमाना स्ट्रिंग मान शामिल करता है जिसका उपयोग आकार के बारे में अतिरिक्त जानकारी प्रदान करने के लिए किया जाता है।

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


एक मनमाना स्ट्रिंग मान शामिल करता है जिसका उपयोग आकार के बारे में अतिरिक्त जानकारी प्रदान करने के लिए किया जाता है।

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


एक मनमाना स्ट्रिंग मान शामिल करता है जिसका उपयोग आकार के बारे में अतिरिक्त जानकारी प्रदान करने के लिए किया जाता है।

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। मान 1 दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है।

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Visio ऑब्जेक्ट्स पदानुक्रम का मूल तत्व।

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


इंटरफ़ेस पर प्रदर्शित पाठ प्राप्त करें

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


आकार घटनाओं को नियंत्रित करने वाले सूत्रों को निर्दिष्ट करने वाले तत्व शामिल हैं।

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Field तत्वों का संग्रह शामिल करता है।

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


आकार और उसके ड्रॉप शैडो के लिए वर्तमान भराव फ़ॉर्मेटिंग मानों को शामिल करता है, जिसमें पैटर्न, अग्रभूमि रंग, और पृष्ठभूमि रंग शामिल हैं।

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet जिससे यह आकार भरने के फॉर्मेटिंग को विरासत में लेता है।

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Microsoft Visio दस्तावेज़ में उपयोग किए गए किसी अन्य प्रोग्राम के ऑब्जेक्ट की चौड़ाई और ऊँचाई निर्दिष्ट करने वाले तत्व शामिल करता है। साथ ही ऐसे तत्व भी शामिल करता है जो ऑब्जेक्ट की छवि के उसके सीमाओं के भीतर ऑफ़सेट दूरी को निर्दिष्ट करते हैं।

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


चित्र डेटा का MIME (Multipurpose Internet Mail Extensions) एन्कोडेड BLOB शामिल करता है, जैसे Windows मेटाफाइल, बिटमैप, या OLE डेटा।

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Geom तत्वों का संग्रह शामिल करता है।

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


ऐसे तत्व शामिल हैं जो नियंत्रित करते हैं कि आप समूह में आकार कैसे जोड़ते हैं, समूह के सदस्यों को कैसे स्थानांतरित करते हैं, और समूहों का चयन कैसे करते हैं।

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Shape तत्व के हेल्प फ़ाइल टॉपिक और कॉपीराइट जानकारी को निर्दिष्ट करने वाले तत्व शामिल करता है।

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Hyperlink तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID।

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


बिटमैप के लिए गामा, चमक, कंट्रास्ट, ब्लर, शार्पन, डीनॉइज़ और ट्रांसपेरेंसी मानों को शामिल करता है।

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


मास्टर आकार द्वारा विरासत में लिए गए आकार के लिए char मान शामिल करता है।

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


पैरेंट स्टाइल और मास्टर आकार द्वारा विरासत में लिए गए आकार के लिए भरने के फॉर्मेटिंग मान शामिल करता है।

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


मास्टर शेप द्वारा विरासत में मिले शेप के लिए Geoms मान शामिल हैं।

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


पैरेंट स्टाइल और मास्टर शेप द्वारा विरासत में मिले शेप के लिए लाइन फ़ॉर्मेटिंग मान शामिल हैं।

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


पैरेंट स्टाइल और मास्टर शेप द्वारा विरासत में मिले शेप के लिए paras शामिल हैं।

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


मास्टर शेप द्वारा विरासत में मिले शेप के लिए props शामिल हैं।

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


पैरेंट स्टाइल और मास्टर शेप द्वारा विरासत में मिले शेप के लिए टेक्स्टब्लॉक मान शामिल हैं।

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


मास्टर शेप द्वारा विरासत में मिले शेप के लिए उपयोगकर्ता शामिल हैं।

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


LayerMember तत्व शामिल है, जो प्रत्येक लेयर को निर्दिष्ट करता है जिससे आकार असाइन किया गया है।

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


आकार की प्लेसमेंट और कनेक्टर रूटिंग सेटिंग्स को नियंत्रित करने वाले तत्व शामिल हैं।

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


एक आकार के लिए रेखा गुणों को नियंत्रित करने वाले तत्व शामिल करता है, जैसे पैटर्न, वजन, और रंग। ये तत्व निर्धारित करते हैं कि क्या रेखा के अंत स्वरूपित हैं (उदाहरण के लिए, तीर के सिर के साथ), रेखा अंत स्वरूपों का आकार, रेखा पर लागू गोलाई वृत्त का त्रिज्या, और रेखा कैप शैली (गोल या वर्ग)।

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


यह शेप जिस StyleSheet से लाइन फ़ॉर्मेटिंग विरासत में लेता है।

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


शेप जिस मास्टर से अपना डेटा विरासत में लेता है।

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


यह विशेषता केवल उन आकारों में मौजूद हो सकती है जो समूह आकार के सदस्य हैं, और समूह एक मास्टर का उदाहरण है। यह विशेषता एक ID रखती है जो मास्टर में संबंधित उप-आकार को संदर्भित करती है।

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Shape तत्व के हेल्प फ़ाइल टॉपिक और कॉपीराइट जानकारी को निर्दिष्ट करने वाले तत्व शामिल करता है।

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


तत्व का नाम।

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


तत्व का सार्वभौमिक नाम।

**Returns:**
java.lang.String
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


निर्धारित करता है कि आकार एक-आयामी (1-D) वस्तु के रूप में व्यवहार करता है या नहीं। केवल-पढ़ने योग्य।

**Returns:**
बूलियन
### getPage() {#getPage--}
```
public Page getPage()
```


Visio ऑब्जेक्ट्स पदानुक्रम का मूल तत्व।

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Para तत्वों का संग्रह शामिल करता है।

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


शेप का पैरेंट।

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Prop तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


लॉकिंग आकृति में अनजाने बदलावों को रोकने में मदद करती है लेकिन यह माइक्रोसॉफ्ट विजियो को अन्य परिस्थितियों में मानों को रीसेट करने से नहीं रोकती। यह ShapeSheet विंडो में किए गए बदलावों से भी सुरक्षा नहीं देती।

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


टेक्स्ट स्ट्रिंग प्राप्त करें

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


यदि यह आकार एक मास्टर उदाहरण का हिस्सा है तो एक उदाहरण का शीर्ष-स्तर आकार लौटाता है। केवल-पढ़ने योग्य।

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Scratch तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Shape तत्वों का संग्रह शामिल है।

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


SmartTagDef तत्वों का संग्रह शामिल करता है।

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Tab तत्वों का संग्रह शामिल करता है।

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


एक शेप का टेक्स्ट शामिल करता है।

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


शेप के टेक्स्ट ब्लॉक में टेक्स्ट की संरेखण, मार्जिन और डिफ़ॉल्ट टैब स्टॉप स्थितियों को निर्दिष्ट करने वाले तत्व शामिल करता है।

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


यह शेप जिस StyleSheet से टेक्स्ट फ़ॉर्मेटिंग विरासत में लेता है।

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


शेप के टेक्स्ट ब्लॉक के बारे में स्थिति जानकारी निर्दिष्ट करने वाले तत्व शामिल करता है।

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


ThreeDFormat प्राप्त करता है।

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


निर्धारित करता है कि शेप दो-आयामी (2-D) ऑब्जेक्ट के रूप में व्यवहार करता है या नहीं।

**Returns:**
बूलियन
### getType() {#getType--}
```
public int getType()
```


एक आकार का प्रकार। यह निम्नलिखित मानों में से एक हो सकता है: Group, Shape, Guide, या Foreign।

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


शेप को सौंपा गया GUID (ग्लोबली यूनिक आइडेंटिफायर)।

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


User तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


आकार के बारे में सामान्य पोजिशनिंग जानकारी निर्दिष्ट करने वाले तत्व शामिल हैं।

**Returns:**
[XForm](../../com.aspose.diagram/xform)
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


1-D आकार के प्रारंभ बिंदु और अंत बिंदु के x- और y-निर्देशांक रखता है। यह तत्व केवल 1-D आकारों के लिए दिखाई देता है।

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


गाइड शेप को छोड़कर z-ऑर्डर में शेप का इंडेक्स लौटाता है।

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


एक एरे लौटाता है जिसमें उन शेप्स के पहचानकर्ता होते हैं जो किसी शेप से चिपके होते हैं।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| फ़्लैग | int | वापस करने के लिए आकारों के कनेक्शन बिंदुओं की आयामिकता और दिशा। संभावित मानों के लिए Remarks देखें Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | निर्दिष्ट categoryString से मेल खाने वाले आकारों के IDs तक सीमित करके लौटाए गए आकार IDs की array को फ़िल्टर करता है। |
| otherShape | [Shape](../../com.aspose.diagram/shape) | वैकल्पिक: अतिरिक्त आकार जिससे लौटाए गए आकारों को भी चिपकाया जाना चाहिए, यह [Shape](../../com.aspose.diagram/shape) या null हो सकता है। |

**Returns:**
long[] - IDs सरणीlong.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isConnected(Shape shape) {#isConnected-com.aspose.diagram.Shape-}
```
public boolean isConnected(Shape shape)
```


यह दर्शाता है कि ये दो शेप्स जुड़े हैं या नहीं।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
बूलियन
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


यह दर्शाता है कि यह शेप किसी अन्य शेप को सम्मिलित करता है या नहीं।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
बूलियन
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


यह दर्शाता है कि ये दो शेप्स चिपके हुए हैं या नहीं।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
बूलियन
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


यह दर्शाता है कि यह शेप एक ग्रुप शेप में है या नहीं।

**Returns:**
बूलियन
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


यह दर्शाता है कि यह आकार दूसरे आकार को काटता है या नहीं।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
बूलियन
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


यह संकेत करता है कि आकार में टेक्स्ट है और टेक्स्ट खाली है या नहीं।

**Returns:**
बूलियन
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


आकार को वर्तमान स्थिति से dX और dY इंच की दूरी पर ले जाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| dX | डबल | X ऑफसेटdouble. |
| dY | डबल | Y ऑफसेटdouble. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


आकार को पृष्ठ पर नई निरपेक्ष स्थिति पर ले जाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newPinX | डबल | आकार के पिन (घूर्णन केंद्र) का नया x-निर्देशांक, उसके पैरेंट के मूल के सापेक्ष।double. |
| newPinY | डबल | आकार के पिन (घूर्णन केंद्र) का नया y-निर्देशांक, उसके पैरेंट के मूल के सापेक्ष।double. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshData() {#refreshData--}
```
public void refreshData()
```


आकार की स्थिति को रीफ़्रेश करता है जिसमें xform, connection और geom शामिल हैं जब आकार के टेक्स्ट या अन्य चीज़ों को बदलते हैं। हम आकार का डेटा जैसे आकार का टेक्स्ट इकट्ठा करेंगे फिर आकार की स्थिति की गणना करेंगे। यह मेथड केवल आकार के डेटा को रीफ़्रेश करने के लिए उपयोग किया जाता है।

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


एक आकार की टेक्स्ट स्ट्रिंग को बदलें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


आकार को z-क्रम में एक स्थिति पीछे ले जाता है।

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


आकार को z-क्रम के पीछे ले जाता है।

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


आकार का नया कोण सेट करता है। कोण की इकाई रेडियन है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| angle | डबल | नया कोण जिसकी इकाई रेडियन है, डिग्री नहीं।double. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


कनेक्टर्स प्रकार सेट करें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


आकार की नई ऊँचाई सेट करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| height | डबल | New heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


इस आकार पर एक प्रीसेट थीम लागू करें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


इस आकार पर एक प्रीसेट थीम वैरिएंट क्विकस्टाइल लागू करें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


pply इस आकार पर एक प्रीसेट थीम वैरिएंट क्विकस्टाइल लागू करें, जैसे आकार स्टाइल ड्रॉपडाउन सूची में थीम स्टाइल विकल्प

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| styleIndex | int | the row of style matrics |
| colorIndex | int | the column of style matrics |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


इस आकार पर एक प्रीसेट थीम वैरिएंट लागू करें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


आकार की नई चौड़ाई सेट करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| width | डबल | New widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


आकार की HTML बनाता है और निर्दिष्ट फॉर्मेट में इसे स्ट्रीम पर सहेजता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


आकार की HTML बनाता है और निर्दिष्ट फॉर्मेट में इसे स्ट्रीम पर सहेजता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


HTML बनाता है और इसे फ़ाइल में सहेजता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html save options |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


आकार की इमेज बनाता है और निर्दिष्ट फॉर्मेट में इसे स्ट्रीम पर सहेजता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


आकार की इमेज बनाता है और निर्दिष्ट फॉर्मेट में इसे स्ट्रीम पर सहेजता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| imageFile | java.lang.String | The image file name with full path. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


आकार का PDF बनाता है और इसे स्ट्रीम पर सहेजता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | The output stream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


आकार का PDF बनाता है और इसे स्ट्रीम पर सहेजता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | The output stream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


आकार को PDF फ़ाइल में सहेजता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | the pdf file name with full path |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toSvg(String imageFile, SVGSaveOptions options) {#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-}
```
public void toSvg(String imageFile, SVGSaveOptions options)
```


आकार को SVG फ़ाइल में सहेजता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


आकार को अनग्रुप करें

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

