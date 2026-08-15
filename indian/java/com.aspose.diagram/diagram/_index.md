---
title: डायग्राम
second_title: Aspose.Diagram for Java API Reference
description: Visio ऑब्जेक्ट्स पदानुक्रम का मूल तत्व।
type: docs
weight: 117
url: /hi/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Visio ऑब्जेक्ट्स पदानुक्रम का मूल तत्व।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | पब्लिक क्लास कंस्ट्रक्टर, फ़ाइल से डायग्राम लोड करता है। |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | पब्लिक क्लास कंस्ट्रक्टर, स्ट्रीम से डायग्राम लोड करता है। |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | पब्लिक क्लास कंस्ट्रक्टर, पूर्वनिर्धारित फ़ॉर्मेट का उपयोग करके स्ट्रीम से डायग्राम लोड करता है। |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | पब्लिक क्लास कंस्ट्रक्टर, पूर्वनिर्धारित लोड फ़ाइल विकल्पों का उपयोग करके स्ट्रीम से डायग्राम लोड करता है। |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | पब्लिक क्लास कंस्ट्रक्टर, पूर्वनिर्धारित फ़ॉर्मेट का उपयोग करके फ़ाइल से डायग्राम लोड करता है। |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | पब्लिक क्लास कंस्ट्रक्टर, पूर्वनिर्धारित लोड फ़ाइल विकल्पों का उपयोग करके फ़ाइल से डायग्राम लोड करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | मास्टर को स्रोत डायग्राम से उसके नाम या NameU द्वारा डायग्राम में जोड़ता है। |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | टेम्पलेट स्ट्रीम से मास्टर को उसके ID द्वारा डायग्राम में जोड़ता है। |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | टेम्पलेट स्ट्रीम से मास्टर को उसके नाम या NameU द्वारा डायग्राम में जोड़ता है। |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | टेम्पलेट फ़ाइल से मास्टर को उसके ID द्वारा डायग्राम में जोड़ता है। |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | टेम्पलेट फ़ाइल से मास्टर को उसके नाम या NameU द्वारा डायग्राम में जोड़ता है। |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | मास्टर द्वारा निर्मित आकार को विशिष्ट पृष्ठ पर जोड़ता है। |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | परिभाषित PinX, PinY, Width और Height के साथ पृष्ठ पर मास्टर द्वारा निर्मित आकार जोड़ता है। |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | परिभाषित PinX और PinY के साथ पृष्ठ पर मास्टर द्वारा निर्मित आकार जोड़ता है। |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | एक अन्य डायग्राम ऑब्जेक्ट को मिलाता है। |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | स्रोत डायग्राम से थीम कॉपी करता है। |
| [dispose()](#dispose--) | अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित एप्लिकेशन‑परिभाषित कार्यों को निष्पादित करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | vsd स्ट्रीम से डायग्राम को vdw स्ट्रीम फ़ॉर्मेट में एक्सपोर्ट करता है। |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | vsd स्ट्रीम से डायग्राम को *.vdw फ़ाइल फ़ॉर्मेट में एक्सपोर्ट करता है। |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | vsd फ़ाइल से डायग्राम को vdw स्ट्रीम फ़ॉर्मेट में एक्सपोर्ट करता है। |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | vsd से डायग्राम को vdw फ़ॉर्मेट में एक्सपोर्ट करता है। |
| [getActivePage()](#getActivePage--) | सक्रिय पृष्ठ को निर्दिष्ट करता है |
| [getBuildnum()](#getBuildnum--) | दस्तावेज़ बनाने के लिए उपयोग किए गए Visio इंस्टेंस का बिल्ड नंबर। |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | दस्तावेज़ की कलर टेबल को शामिल करता है। |
| [getDataConnections()](#getDataConnections--) | दस्तावेज़ के लिए DataConnection तत्वों को शामिल करता है। |
| [getDataRecordSets()](#getDataRecordSets--) | एक Document ऑब्जेक्ट से जुड़े DataRecordset ऑब्जेक्ट्स का संग्रह। |
| [getDefaultFontDir()](#getDefaultFontDir--) | डिफ़ॉल्ट फ़ॉन्ट्स फ़ोल्डर पथ प्राप्त करें |
| [getDocLangID()](#getDocLangID--) | Microsoft Office 2010 भाषा प्राथमिकताओं में उपयोगकर्ता द्वारा निर्दिष्ट उपयोगकर्ता इंटरफ़ेस भाषा का अद्वितीय ID। |
| [getDocumentProps()](#getDocumentProps--) | दस्तावेज़ के शीर्षक, लेखक आदि जैसे दस्तावेज़ गुण तत्व शामिल हैं। |
| [getDocumentSettings()](#getDocumentSettings--) | दस्तावेज़ सेटिंग्स निर्दिष्ट करने वाले तत्व शामिल हैं। |
| [getDocumentSheet()](#getDocumentSheet--) | दस्तावेज़ की ShapeSheet संरचना निर्दिष्ट करता है। |
| [getEmailRoutingData()](#getEmailRoutingData--) | दस्तावेज़ के लिए MIME (Multipurpose Internet Mail Extensions) एन्कोडेड MAPI ई-मेल रूटिंग स्लिप शामिल है। |
| [getEventItems()](#getEventItems--) | उस वस्तु को जिस प्रत्येक घटना पर प्रतिक्रिया देनी चाहिए, उसके लिए एक EventItem तत्व शामिल है। |
| [getFonts()](#getFonts--) | Font तत्वों का संग्रह शामिल है। |
| [getHeaderFooter()](#getHeaderFooter--) | दस्तावेज़ के हेडर और फुटर के लिए तत्व शामिल करता है। |
| [getInterruptMonitor()](#getInterruptMonitor--) | इंटरप्ट मॉनिटर। |
| [getKey()](#getKey--) | यह दर्शाता है कि क्या दस्तावेज़ Visio के बाहर संशोधित किया गया है। |
| [getMasters()](#getMasters--) | Master वस्तुओं का संग्रह। |
| [getMetric()](#getMetric--) | क्या चित्र में मीट्रिक इकाइयों का उपयोग करना है। |
| [getPages()](#getPages--) | Page वस्तुओं का संग्रह। |
| [getRibbonX()](#getRibbonX--) | Ribbon उपयोगकर्ता इंटरफ़ेस को अनुकूलित करने के लिए दस्तावेज़ को पास किया जाने वाला Ribbon XML स्ट्रिंग। |
| [getSolutionXMLs()](#getSolutionXMLs--) | XML मान। |
| [getStart()](#getStart--) | यह दर्शाता है कि क्या दस्तावेज़ Visio के बाहर संशोधित किया गया है। |
| [getStyleSheets()](#getStyleSheets--) | StyleSheet वस्तुओं का संग्रह। |
| [getUnusedStyles()](#getUnusedStyles--) | अप्रयुक्त शैलियों को प्राप्त करें |
| [getUserCustomUI()](#getUserCustomUI--) | दस्तावेज़ को पास किया जाने वाला Ribbon XML स्ट्रिंग, जो Quick Access टूलबार या Ribbon को अनुकूलित करता है। |
| [getValidation()](#getValidation--) | दस्तावेज़ के लिए आरेख सत्यापन के बारे में जानकारी संग्रहीत करता है। |
| [getVbProjectData()](#getVbProjectData--) | MIME (Multipurpose Internet Mail Extensions) एन्कोडेड फ़ॉर्मेट में Microsoft Visual Basic for Applications प्रोजेक्ट डेटा शामिल है। |
| [getVbaProject()](#getVbaProject--) | प्राप्त करता है VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--). |
| [getVersion()](#getVersion--) | Visio इंस्टेंस का संस्करण संख्या। |
| [getWindows()](#getWindows--) | दस्तावेज़ के लिए Window तत्व शामिल हैं। |
| [hasHiddenInfo()](#hasHiddenInfo--) | यह दर्शाता है कि इस आरेख में छुपी जानकारी है या नहीं। |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | आरेख के सभी पृष्ठों के लिए आकारों को व्यवस्थित करता है और/या कनेक्टरों को पुनः मार्गित करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | निर्दिष्ट प्रिंटर पर पूरे दस्तावेज़ को प्रिंट करें, मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट कंट्रोलर का उपयोग करके। |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | निर्दिष्ट प्रिंटर पर पूरे दस्तावेज़ को प्रिंट करें, मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट कंट्रोलर का उपयोग करके। |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | दस्तावेज़ को प्रिंट करता है, मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट कंट्रोलर और एक दस्तावेज़ नाम का उपयोग करके। |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | दस्तावेज़ को प्रिंट करता है, मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट कंट्रोलर और एक दस्तावेज़ नाम का उपयोग करके। |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | अप्रयुक्त जानकारी हटाएँ |
| [removeMacro()](#removeMacro--) | इस आरेख से VBA/मैक्रो हटाता है। |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | आरेख को स्ट्रीम में सहेजें। |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | आरेख को स्ट्रीम में सहेजें। |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | निर्दिष्ट सहेजने विकल्पों का उपयोग करके दस्तावेज़ को फ़ाइल में सहेजता है। |
| [save(String filename, int format)](#save-java.lang.String-int-) | आरेख डेटा को फ़ाइल में सहेजता है। |
| [setBuildnum(long value)](#setBuildnum-long-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | फ़ॉन्ट्स फ़ोल्डर पथ को दर्शाता है |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getKey()](../../com.aspose.diagram/diagram\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMetric()](../../com.aspose.diagram/diagram\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStart()](../../com.aspose.diagram/diagram\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getVersion()](../../com.aspose.diagram/diagram\#getVersion--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Diagram() {#Diagram--}
```
public Diagram()
```


### Diagram(String filename) {#Diagram-java.lang.String-}
```
public Diagram(String filename)
```


पब्लिक क्लास कंस्ट्रक्टर, फ़ाइल से डायग्राम लोड करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | फ़ाइल नाम। |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


पब्लिक क्लास कंस्ट्रक्टर, स्ट्रीम से डायग्राम लोड करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | डेटा स्ट्रीम। |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


पब्लिक क्लास कंस्ट्रक्टर, पूर्वनिर्धारित फ़ॉर्मेट का उपयोग करके स्ट्रीम से डायग्राम लोड करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | डेटा स्ट्रीम। |
| format | int | डेटा Aspose.Diagram.LoadFileFormat। |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


पब्लिक क्लास कंस्ट्रक्टर, पूर्वनिर्धारित लोड फ़ाइल विकल्पों का उपयोग करके स्ट्रीम से डायग्राम लोड करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | डेटा स्ट्रीम। |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | डेटा [LoadOptions](../../com.aspose.diagram/loadoptions)। |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


पब्लिक क्लास कंस्ट्रक्टर, पूर्वनिर्धारित फ़ॉर्मेट का उपयोग करके फ़ाइल से डायग्राम लोड करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | फ़ाइल नाम। |
| format | int | फ़ाइल फ़ॉर्मेट। |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


पब्लिक क्लास कंस्ट्रक्टर, पूर्वनिर्धारित लोड फ़ाइल विकल्पों का उपयोग करके फ़ाइल से डायग्राम लोड करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | फ़ाइल नाम। |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | डेटा [LoadOptions](../../com.aspose.diagram/loadoptions)। |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


मास्टर को स्रोत डायग्राम से उसके नाम या NameU द्वारा डायग्राम में जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | स्रोत डायग्राम। |
| masterName | java.lang.String | मास्टर का नाम या NameU। |

**Returns:**
int - इस डायग्राम में मास्टर्स संग्रह के भीतर मास्टर का अद्वितीय ID।
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


टेम्पलेट स्ट्रीम से मास्टर को उसके ID द्वारा डायग्राम में जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| टेम्प्लेटस्ट्रीम | java.io.InputStream | टेम्प्लेट स्ट्रीम। |
| मास्टरआईडी | int | टेम्प्लेट में मास्टर्स संग्रह के भीतर मास्टर का अद्वितीय ID। |

**Returns:**
int - इस डायग्राम में मास्टर्स संग्रह के भीतर मास्टर का अद्वितीय ID।
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


टेम्पलेट स्ट्रीम से मास्टर को उसके नाम या NameU द्वारा डायग्राम में जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| टेम्प्लेटस्ट्रीम | java.io.InputStream | टेम्प्लेट स्ट्रीम। |
| masterName | java.lang.String | मास्टर का नाम या NameU। |

**Returns:**
int - इस डायग्राम में मास्टर्स संग्रह के भीतर मास्टर का अद्वितीय ID।
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


टेम्पलेट फ़ाइल से मास्टर को उसके ID द्वारा डायग्राम में जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| templateFilePath | java.lang.String | टेम्पलेट फ़ाइल का पथ (vdx, vst या vsd फ़ॉर्मेट हो सकता है)। |
| मास्टरआईडी | int | टेम्प्लेट में मास्टर्स संग्रह के भीतर मास्टर का अद्वितीय ID। |

**Returns:**
int - इस डायग्राम में मास्टर्स संग्रह के भीतर मास्टर का अद्वितीय ID।
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


टेम्पलेट फ़ाइल से मास्टर को उसके नाम या NameU द्वारा डायग्राम में जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| templateFilePath | java.lang.String | टेम्पलेट फ़ाइल का पथ (vdx, vst या vsd फ़ॉर्मेट हो सकता है)। |
| masterName | java.lang.String | मास्टर का नाम या NameU। |

**Returns:**
int - इस डायग्राम में मास्टर्स संग्रह के भीतर मास्टर का अद्वितीय ID।
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


मास्टर द्वारा निर्मित आकार को विशिष्ट पृष्ठ पर जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | नया आकार ऑब्जेक्ट[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | मास्टर का नाम। |
| pageNumber | int | पृष्ठ का अनुक्रमांक। |

**Returns:**
long - निर्दिष्ट पृष्ठ पर आकारों के संग्रह में आकार की विशिष्ट ID।
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


परिभाषित PinX, PinY, Width और Height के साथ पृष्ठ पर मास्टर द्वारा निर्मित आकार जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| width | डबल | आकार की चौड़ाई इंच में निर्दिष्ट करता है। |
| height | डबल | आकार की ऊँचाई इंच में निर्दिष्ट करता है। |
| masterName | java.lang.String | मास्टर का नाम। |
| pageNumber | int | पृष्ठ का अनुक्रमांक। |

**Returns:**
long - निर्दिष्ट पृष्ठ पर आकारों के संग्रह में आकार की विशिष्ट ID।
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


परिभाषित PinX और PinY के साथ पृष्ठ पर मास्टर द्वारा निर्मित आकार जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| masterName | java.lang.String | मास्टर का नाम। |
| pageNumber | int | पृष्ठ का अनुक्रमांक। |

**Returns:**
long - निर्दिष्ट पृष्ठ पर आकारों के संग्रह में आकार की विशिष्ट ID।
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


एक अन्य डायग्राम ऑब्जेक्ट को मिलाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | एक और डायग्राम ऑब्जेक्ट। |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


स्रोत डायग्राम से थीम कॉपी करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | स्रोत डायग्राम। |

### dispose() {#dispose--}
```
public void dispose()
```


अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित एप्लिकेशन‑परिभाषित कार्यों को निष्पादित करता है।

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
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


vsd स्ट्रीम से vdw स्ट्रीम फ़ॉर्मेट में डायग्राम निर्यात करता है। अभी लागू नहीं किया गया है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| inputVsd | java.io.InputStream | vsd स्ट्रीम। |
| outputVdw | java.io.InputStream | vdw स्ट्रीम। |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


vsd स्ट्रीम से \*.vdw फ़ाइल फ़ॉर्मेट में डायग्राम निर्यात करता है। अभी लागू नहीं किया गया है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| inputVsd | java.io.InputStream | \*.vsd फ़ाइल नाम। |
| outputVdw | java.lang.String | vdw स्ट्रीम। |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


vsd फ़ाइल से vdw स्ट्रीम फ़ॉर्मेट में डायग्राम निर्यात करता है। अभी लागू नहीं किया गया है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd फ़ाइल नाम। |
| outputVdw | java.io.InputStream | vdw स्ट्रीम। |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


vsd से vdw फ़ॉर्मेट में डायग्राम निर्यात करता है। अभी लागू नहीं किया गया है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd फ़ाइल नाम। |
| outputVdw | java.lang.String | \*.vdw फ़ाइल नाम। |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


सक्रिय पृष्ठ को निर्दिष्ट करता है

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


दस्तावेज़ बनाने के लिए उपयोग किए गए Visio इंस्टेंस का बिल्ड नंबर।

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColors() {#getColors--}
```
public ColorEntryCollection getColors()
```


दस्तावेज़ की रंग तालिका शामिल करता है। प्रत्येक दस्तावेज़ में एक ही रंग तालिका होती है, जिसमें 24 मानक रंग सूचीबद्ध होते हैं जो आकार, पाठ, और दस्तावेज़ में लेयर्स जैसी वस्तुओं पर लागू किए जा सकते हैं।

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


दस्तावेज़ के लिए DataConnection तत्वों को शामिल करता है।

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


एक Document ऑब्जेक्ट से जुड़े DataRecordset ऑब्जेक्ट्स का संग्रह।

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


डिफ़ॉल्ट फ़ॉन्ट्स फ़ोल्डर पथ प्राप्त करें

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


Microsoft Office 2010 भाषा प्राथमिकताओं में उपयोगकर्ता द्वारा निर्दिष्ट उपयोगकर्ता इंटरफ़ेस भाषा का अद्वितीय ID।

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


दस्तावेज़ के शीर्षक, लेखक आदि जैसे दस्तावेज़ गुण तत्व शामिल हैं।

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


दस्तावेज़ सेटिंग्स निर्दिष्ट करने वाले तत्व शामिल हैं।

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


दस्तावेज़ की ShapeSheet संरचना निर्दिष्ट करता है।

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


दस्तावेज़ के लिए MIME (Multipurpose Internet Mail Extensions) एन्कोडेड MAPI ई-मेल रूटिंग स्लिप शामिल है।

**Returns:**
बाइट[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


उस वस्तु को जिस प्रत्येक घटना पर प्रतिक्रिया देनी चाहिए, उसके लिए एक EventItem तत्व शामिल है।

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Font तत्वों का संग्रह शामिल है।

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


दस्तावेज़ के हेडर और फुटर के लिए तत्व शामिल करता है।

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


इंटरप्ट मॉनिटर।

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


यह दर्शाता है कि क्या दस्तावेज़ Visio के बाहर संशोधित किया गया है। यदि उपस्थित है, तो Visio फ़ाइल की सामग्री को पूरी तरह से परीक्षण करेगा। Visio के बाहर आप द्वारा बनाई गई फ़ाइलों के लिए इसे छोड़ दें।

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Master वस्तुओं का संग्रह।

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


ड्राइंग में मीट्रिक इकाइयों का उपयोग करना है या नहीं। मीट्रिक इकाइयों के लिए इस गुण को True (1) सेट करें; अंग्रेज़ी इकाइयों के लिए इसे False (0) सेट करें।

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Page वस्तुओं का संग्रह।

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


Ribbon उपयोगकर्ता इंटरफ़ेस को अनुकूलित करने के लिए दस्तावेज़ को पास किया जाने वाला Ribbon XML स्ट्रिंग।

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


XML मान।

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


यह दर्शाता है कि क्या दस्तावेज़ Visio के बाहर संशोधित किया गया है। यदि उपस्थित है, तो Visio फ़ाइल की सामग्री को पूरी तरह से परीक्षण करेगा। Visio के बाहर आप द्वारा बनाई गई फ़ाइलों के लिए इसे छोड़ दें।

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


StyleSheet वस्तुओं का संग्रह।

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


अप्रयुक्त शैलियों को प्राप्त करें

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


दस्तावेज़ को पास किया जाने वाला Ribbon XML स्ट्रिंग, जो Quick Access टूलबार या Ribbon को अनुकूलित करता है।

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


दस्तावेज़ के लिए आरेख सत्यापन के बारे में जानकारी संग्रहीत करता है।

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


MIME (Multipurpose Internet Mail Extensions) एन्कोडेड फ़ॉर्मेट में Microsoft Visual Basic for Applications प्रोजेक्ट डेटा शामिल है।

**Returns:**
बाइट[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


प्राप्त करता है VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--).

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Visio इंस्टेंस का संस्करण संख्या। Microsoft Visio 2010 = 14।

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


दस्तावेज़ के लिए Window तत्व शामिल हैं।

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


यह दर्शाता है कि इस आरेख में छुपी जानकारी है या नहीं।

**Returns:**
बूलियन
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


आरेख के सभी पृष्ठों के लिए आकारों को व्यवस्थित करता है और/या कनेक्टरों को पुनः मार्गित करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | [LayoutOptions](../../com.aspose.diagram/layoutoptions) का उपयोग करके लेआउट के विकल्पों को कॉन्फ़िगर किया जा रहा है। |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### print(String printerName) {#print-java.lang.String-}
```
public void print(String printerName)
```


निर्दिष्ट प्रिंटर पर पूरे दस्तावेज़ को प्रिंट करें, मानक (कोई यूज़र इंटरफ़ेस नहीं) प्रिंट कंट्रोलर का उपयोग करके। यदि printerName Null या खाली है तो डिफ़ॉल्ट प्रिंटर उपयोग किया जाएगा।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| printerName | java.lang.String | प्रिंटर का नाम। Null हो सकता है। |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


निर्दिष्ट प्रिंटर पर पूरे दस्तावेज़ को प्रिंट करें, मानक (कोई यूज़र इंटरफ़ेस नहीं) प्रिंट कंट्रोलर का उपयोग करके। यदि printerName Null या खाली है तो डिफ़ॉल्ट प्रिंटर उपयोग किया जाएगा।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| printerName | java.lang.String | प्रिंटर का नाम। Null हो सकता है। |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | प्रिंट विकल्प। |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


दस्तावेज़ को प्रिंट करता है, मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट कंट्रोलर और एक दस्तावेज़ नाम का उपयोग करके।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| printerName | java.lang.String | प्रिंटर का नाम। Null हो सकता है। |
| documentName | java.lang.String | दस्तावेज़ को प्रिंट करते समय प्रदर्शित करने के लिए दस्तावेज़ नाम (उदाहरण के लिए, प्रिंट स्थिति संवाद बॉक्स या प्रिंटर कतार में)। |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


दस्तावेज़ को प्रिंट करता है, मानक (कोई उपयोगकर्ता इंटरफ़ेस नहीं) प्रिंट कंट्रोलर और एक दस्तावेज़ नाम का उपयोग करके।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| printerName | java.lang.String | प्रिंटर का नाम। Null हो सकता है। |
| documentName | java.lang.String | दस्तावेज़ को प्रिंट करते समय प्रदर्शित करने के लिए दस्तावेज़ नाम (उदाहरण के लिए, प्रिंट स्थिति संवाद बॉक्स या प्रिंटर कतार में)। |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | प्रिंट विकल्प। |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


अप्रयुक्त जानकारी हटाएँ

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| item | int | छिपी जानकारी आइटम हटाएँ। |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


इस आरेख से VBA/मैक्रो हटाता है।

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


आरेख को स्ट्रीम में सहेजें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | फ़ाइल स्ट्रीम। |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | सहेजने के विकल्प। |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


आरेख को स्ट्रीम में सहेजें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | फ़ाइल स्ट्रीम। |
| format | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


निर्दिष्ट सहेजने विकल्पों का उपयोग करके दस्तावेज़ को फ़ाइल में सहेजता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | फ़ाइल नाम। |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) डायग्राम विकल्प सहेजें। |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


आरेख डेटा को फ़ाइल में सहेजता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| फ़ाइलनाम | java.lang.String | फ़ाइल नाम। |
| format | int | Aspose.Diagram.SaveFileFormat फ़ाइल स्वरूप सहेजें। |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बाइट[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


फ़ॉन्ट्स फ़ोल्डर पथ को दर्शाता है

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बाइट[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

