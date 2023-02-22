---
title: Page
second_title: .NET API संदर्भ के लिए Aspose.Diagram
description: में वे तत्व शमल हैं ज दस्तवेज़ में एक पृष्ठ क परभषत करते हैं
type: docs
weight: 2490
url: /hi/net/aspose.diagram/page/
---
## Page class

में वे तत्व शामिल हैं जो दस्तावेज़ में एक पृष्ठ को परिभाषित करते हैं।

```csharp
public class Page : IDisposable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Page](page/#constructor)() | कंस्ट्रक्टर. |
| [Page](page/#constructor_1)(int) | कंस्ट्रक्टर. |

## गुण

| नाम | विवरण |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | मूल आरेखण पृष्ठ की आईडी जिसे आरेखण के समीक्षकों द्वारा अलग-अलग मार्कअप ओवरले पर चिह्नित किया गया था. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | एक ध्वज इंगित करता है कि पृष्ठ एक पृष्ठभूमि पृष्ठ है या नहीं। |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | पृष्ठ का पृष्ठभूमि पृष्ठ. |
| [Connects](../../aspose.diagram/page/connects/) { get; } | में ड्राइंग में दो आकृतियों के बीच प्रत्येक कनेक्शन के लिए एक कनेक्ट तत्व होता है। |
| [ID](../../aspose.diagram/page/id/) { get; set; } | इसके मूल तत्व के भीतर तत्व की अनूठी आईडी। |
| [Name](../../aspose.diagram/page/name/) { get; set; } | तत्व का नाम। |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | तत्व का सार्वभौमिक नाम। |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | पृष्ठ संग्रह. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | में ऐसे तत्व शामिल हैं जो पेज या मास्टर तत्व के लिए पेज शीट को परिभाषित करते हैं। |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | इस पेज पर प्रीसेट थीम लागू करें |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | इस पेज पर प्रीसेट थीम वैरिएंट क्विकस्टाइल लागू करें |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | इस पेज पर प्रीसेट थीम प्रकार लागू करें |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | मार्कअप ओवरले से संबद्ध समीक्षक की आईडी. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | आकार संग्रह। |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX और ViewCenterY एक पृष्ठ पर एक केंद्र बिंदु निर्दिष्ट करते हैं जिसे एक नया दृश्य (विंडो) मान लेता है जब इसे प्रारंभ में खोला जाता है। |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX और ViewCenterY एक पृष्ठ पर एक केंद्र बिंदु निर्दिष्ट करते हैं जिसे एक नया दृश्य (विंडो) मान लेता है जब इसे प्रारंभ में खोला जाता है। |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | पृष्ठ का एक नया दृश्य (विंडो) खोले जाने पर उपयोग करने के लिए डिफ़ॉल्ट आवर्धन कारक। उदाहरण के लिए, 1 = 100%; 1.5 = 150%, और इसी तरह. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Activex नियंत्रण बनाता है। |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | आकृति की आईडी के साथ किसी आकृति में टिप्पणी जोड़ता है. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | आकार में टिप्पणी जोड़ता है. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | परिभाषित PinX और PinY. के साथ टिप्पणी जोड़ता है |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | विशिष्ट पृष्ठ पर मास्टर द्वारा बनाई गई आकृति जोड़ता है। |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | परिभाषित PinX और PinY. के साथ पृष्ठ पर मास्टर द्वारा बनाई गई आकृति जोड़ता है |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | परिभाषित पिनएक्स, पिनवाई, चौड़ाई और ऊंचाई के साथ पृष्ठ पर मास्टर द्वारा बनाई गई आकृति जोड़ता है। |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | परिभाषित PinX और PinY. के साथ पाठ जोड़ता है |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | परिभाषित PinX और PinY. के साथ पाठ जोड़ता है |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | पूरे पृष्ठ के लिए शैली लागू करता है। |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | ऑटो स्पेस आकार |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | एक आकार लाता है, आईडी द्वारा परिभाषित, जेड-ऑर्डर में एक स्थिति को आगे बढ़ाता है। |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | जेड-ऑर्डर के सामने आईडी द्वारा परिभाषित आकार लाता है। |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | पृष्ठ की सीमा के संबंध में पृष्ठ के आकार को केंद्रित करता है। केंद्रित आकार एक दूसरे के सापेक्ष अपनी स्थिति नहीं बदलते हैं। |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | आकृतियों को कनेक्टर के माध्यम से कनेक्ट करें. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | आकृतियों को कनेक्टर के माध्यम से कनेक्ट करें. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | आकृतियों को कनेक्टर के माध्यम से कनेक्ट करें. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | कनेक्टर अनुक्रमणिका के माध्यम से आकृतियों को कनेक्ट करें. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | कनेक्टर अनुक्रमणिका के माध्यम से आकृतियों को कनेक्ट करें. |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | मुक्त करने, जारी करने, या अप्रबंधित संसाधनों को रीसेट करने से संबंधित एप्लिकेशन-परिभाषित कार्य करता है। |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | बेज़ियर बनाने की प्रक्रिया. बिंदुओं की लंबाई 3. के बराबर या उससे अधिक होनी चाहिए |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | दीर्घवृत्त बनाने की प्रक्रिया. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | एक रेखा खींचने की प्रक्रिया। |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | रेखा खींचने की प्रक्रिया। |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | रेखा खींचने की प्रक्रिया। |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | पॉलीलाइन बनाने की प्रक्रिया। |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | पॉलीलाइन बनाने की प्रक्रिया. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | आयत बनाने की प्रक्रिया। |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | स्पलाइन बनाने की प्रक्रिया। |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | गोंद के आकार |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | गोंद के आकार। |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | कंटेनर में गोंद के आकार |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | कनेक्शन नाम का उपयोग करके कंटेनर में आकृतियों को गोंद करें |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | कंटेनर में कनेक्शन आईडी द्वारा गोंद आकार |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | कनेक्टर के बिगिनएक्स के लिए गोंद का आकार |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | गोंद आकार कनेक्टर के EndX के लिए |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | पृष्ठ के लिए आकार निर्धारित करता है और/या कनेक्टर्स का मार्ग बदलता है. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | पृष्ठ को पृष्ठों में किसी अन्य स्थान पर ले जाता है. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | एक आकार, आईडी द्वारा परिभाषित, जेड-ऑर्डर में एक स्थान पीछे ले जाता है। |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | आईडी द्वारा परिभाषित आकार को जेड-ऑर्डर के पीछे ले जाता है। |

### यह सभी देखें

* नाम स्थान [Aspose.Diagram](../../aspose.diagram/)
* सभा [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
