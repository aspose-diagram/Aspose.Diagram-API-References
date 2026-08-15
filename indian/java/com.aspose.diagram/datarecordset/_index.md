---
title: DataRecordSet
second_title: Aspose.Diagram for Java API Reference
description: Microsoft Visio में डेटाबेस से क्वेरी किए गए डेटा को संग्रहीत, रीफ़्रेश और उजागर करता है।
type: docs
weight: 113
url: /hi/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Microsoft Visio में डेटाबेस से प्राप्त डेटा को संग्रहीत, स्वरूपित, रीफ़्रेश और उजागर करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | ADO रिकॉर्डसेट के लिए ADO क्लासिक XML स्कीमा के अनुरूप XML सम्मिलित करता है और डेटा रिकॉर्डसेट में डेटा का वर्णन करता है। |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | एक नियम परिभाषित करता है जो पैरेंट DataRecordset तत्व में कॉलम की तुलना उपयोगकर्ता इंटरफ़ेस में किए गए अंतिम सफल स्वचालित लिंकिंग क्रिया से प्राप्त शैप डेटा आइटम से करता है। |
| [getChecksum()](#getChecksum--) | Visio द्वारा उत्पन्न एक चेकसम मान, जो डेटा-रिकॉर्डसेट गुणों पर आधारित है। |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | डेटा स्रोत से डेटा क्वेरी करने के लिए उपयोग की जाने वाली कमांड स्ट्रिंग। |
| [getConnectionID()](#getConnectionID--) | संबंधित **DataConnection** ऑब्जेक्ट के लिए कनेक्शन आईडी। |
| [getDataColumns()](#getDataColumns--) | डेटा रिकॉर्डसेट में सभी **DataColumn** तत्वों को सम्मिलित करता है। |
| [getID()](#getID--) | दस्तावेज़ के भीतर अद्वितीय डेटा रिकॉर्डसेट आईडी। |
| [getName()](#getName--) | डेटा रिकॉर्डसेट का डिस्प्ले (या \"फ्रेंडली\") नाम। |
| [getNextRowID()](#getNextRowID--) | अगला उपलब्ध Visio पंक्ति आईडी। |
| [getOptions()](#getOptions--) | डेटा रिकॉर्डसेट पर लागू करने के विकल्प। |
| [getPrimaryKeys()](#getPrimaryKeys--) | डेटा रिकॉर्डसेट में एक या अधिक प्राइमरी-की कॉलम की पहचान करता है। |
| [getRefreshConflicts()](#getRefreshConflicts--) | डेटा रिकॉर्डसेट रीफ़्रेश होने के बाद संघर्ष में रहने वाले आकार से जुड़ी पंक्ति को दर्शाता है। |
| [getRefreshInterval()](#getRefreshInterval--) | Visio डेटा रिकॉर्डसेट को स्वचालित रूप से कितनी बार (मिनटों में) रीफ़्रेश करता है। |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | क्या डेटा-रिकंसिलिएशन उपयोगकर्ता इंटरफ़ेस को निष्क्रिय किया जाना चाहिए। |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | डेटा रिकॉर्डसेट रीफ़्रेश होने पर डेटा से जुड़े आकारों में शैप डेटा आइटम्स में उपयोगकर्ता परिवर्तन को ओवरराइट करना चाहिए या नहीं। |
| [getReplaceLinks()](#getReplaceLinks--) | जब आकारों को कॉपी या कट किया जाता है तो शैप-डेटा लिंक कैसे संभाले जाते हैं, इसे परिभाषित करता है। लक्ष्य आकार में मौजूदा लिंक को बदलने के लिए 1। लक्ष्य आकार में मौजूदा लिंक को बनाए रखने के लिए 0। |
| [getRowMaps()](#getRowMaps--) | डेटा-रिकॉर्डसेट पंक्ति को एक आकार से मैप करता है। |
| [getRowOrder()](#getRowOrder--) | क्या डेटा रिकॉर्डसेट में पंक्तियों के क्रम को प्राइमरी की के रूप में उपयोग करना है। |
| [getTimeRefreshed()](#getTimeRefreshed--) | डेटा रिकॉर्डसेट के अंतिम रीफ़्रेश की तिथि और समय। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | कनेक्टेड (गैर-XML-आधारित) **DataRecordSet** से जुड़ी क्वेरी स्ट्रिंग को निष्पादित करता है और क्वेरी द्वारा लौटाए गए डेटा स्रोत से नए डेटा के साथ जुड़े आकारों को अपडेट करता है। |
| [setADOData(String value)](#setADOData-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | इस गुण का विवरण देखने के लिए, कृपया देखें \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | इस गुण का विवरण देखने के लिए, कृपया देखें \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
```


कंस्ट्रक्टर।

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
### getADOData() {#getADOData--}
```
public String getADOData()
```


ADO रिकॉर्डसेट के लिए ADO क्लासिक XML स्कीमा के अनुरूप XML सम्मिलित करता है और डेटा रिकॉर्डसेट में डेटा का वर्णन करता है।

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


एक नियम परिभाषित करता है जो पैरेंट DataRecordset तत्व में कॉलम की तुलना उपयोगकर्ता इंटरफ़ेस में किए गए अंतिम सफल स्वचालित लिंकिंग क्रिया से प्राप्त शैप डेटा आइटम से करता है।

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


Visio द्वारा उत्पन्न एक चेकसम मान, जो डेटा-रिकॉर्डसेट गुणों पर आधारित है। इस विशेषता को 0 पर सेट करें; Visio रनटाइम पर इस मान की पुनः गणना करता है।

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCommand() {#getCommand--}
```
public String getCommand()
```


डेटा स्रोत से डेटा क्वेरी करने के लिए उपयोग की जाने वाली कमांड स्ट्रिंग।

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


संबंधित DataConnection ऑब्जेक्ट के लिए कनेक्शन ID। XML डेटा स्रोतों के लिए यह मौजूद नहीं होता।

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


डेटा रिकॉर्डसेट में सभी **DataColumn** तत्वों को सम्मिलित करता है।

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


दस्तावेज़ के भीतर अद्वितीय डेटा रिकॉर्डसेट आईडी।

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


डेटा रिकॉर्डसेट का डिस्प्ले (या \"फ्रेंडली\") नाम।

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


अगला उपलब्ध Visio पंक्ति आईडी।

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


डेटा रिकॉर्डसेट पर लागू करने के विकल्प। संभावित मान नीचे दी गई तालिका में दिखाए गए एक या अधिक मानों के किसी भी संयोजन हो सकते हैं।

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


डेटा रिकॉर्डसेट में एक या अधिक प्राइमरी-की कॉलम की पहचान करता है।

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


डेटा रिकॉर्डसेट में एक पंक्ति को दर्शाता है जो डेटा रिकॉर्डसेट को रीफ़्रेश करने के बाद किसी आकार (shape) से जुड़ी है और संघर्ष में है। RowID - डेटा रिकॉर्डसेट में एक पंक्ति को दर्शाता है जो डेटा रिकॉर्डसेट को रीफ़्रेश करने के बाद किसी आकार से जुड़ी है और संघर्ष में है। ShapeID - संघर्ष में शामिल आकार की Shape ID। PageID - संघर्ष में शामिल आकार की Page ID।

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


Visio कितनी बार (मिनटों में) डेटा रिकॉर्डसेट को स्वचालित रूप से रीफ़्रेश करता है। यह मान 1 या उससे बड़ा होना चाहिए।

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


डेटा-सहमति उपयोगकर्ता इंटरफ़ेस को निष्क्रिय किया जाना चाहिए या नहीं। उपयोगकर्ता इंटरफ़ेस (UI) को निष्क्रिय करने के लिए True (1)। UI को सक्रिय करने के लिए False (0)।

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


डेटा रिकॉर्डसेट रीफ़्रेश होने पर डेटा से जुड़े आकारों में शैप डेटा आइटम्स में उपयोगकर्ता परिवर्तन को ओवरराइट करना चाहिए या नहीं।

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


जब आकारों को कॉपी या कट किया जाता है तो shape-data लिंक कैसे संभाले जाते हैं, इसे परिभाषित करता है। लक्ष्य आकार में मौजूदा लिंक को बदलने के लिए 1। लक्ष्य आकार में मौजूदा लिंक को बनाए रखने के लिए 0। यदि यह विशेषता अनुपस्थित है, तो Visio उपयोगकर्ता से पूछता है कि कॉपी या कट पर लिंक बदलें या नहीं।

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


डेटा-रिकॉर्डसेट पंक्ति को एक आकार से मैप करता है। RowID - डेटा रिकॉर्डसेट के भीतर पंक्ति की अनूठी Row ID। ShapeID - RowID द्वारा पहचानी गई डेटा-रिकॉर्डसेट पंक्ति में डेटा से जुड़ा आकार की Shape ID। PageID - RowID द्वारा पहचानी गई डेटा-रिकॉर्डसेट पंक्ति में डेटा से जुड़ा आकार की Page ID।

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


डेटा रिकॉर्डसेट में पंक्तियों के क्रम को प्राथमिक कुंजी के रूप में उपयोग करना है या नहीं। यदि पंक्ति IDs क्रम द्वारा निर्धारित होते हैं तो True (1)। यदि पंक्ति IDs डेटा रिकॉर्डसेट के प्राथमिक कुंजी कॉलम(ों) के मानों द्वारा निर्धारित होते हैं तो False (0)।

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


डेटा रिकॉर्डसेट के अंतिम रीफ़्रेश की तिथि और समय।

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refresh(int connectionType) {#refresh-int-}
```
public void refresh(int connectionType)
```


कनेक्टेड (गैर-XML-आधारित) **DataRecordSet** से जुड़ी क्वेरी स्ट्रिंग को निष्पादित करता है और क्वेरी द्वारा लौटाए गए डेटा स्रोत से नए डेटा के साथ जुड़े आकारों को अपडेट करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| connectionType | int | कनेक्शन के लिए उपयोग किया जाने वाला प्रदाता प्रकार Aspose.Diagram.Manipulation.DataConnectionType। |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

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

