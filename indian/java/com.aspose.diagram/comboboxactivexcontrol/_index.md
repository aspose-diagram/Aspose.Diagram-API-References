---
title: ComboBoxActiveXControl
second_title: Aspose.Diagram for Java API Reference
description: एक ComboBox ActiveX कंट्रोल का प्रतिनिधित्व करता है।
type: docs
weight: 55
url: /hi/java/com.aspose.diagram/comboboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ComboBoxActiveXControl extends ActiveXControl
```

एक ComboBox ActiveX कंट्रोल का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | पृष्ठभूमि का ओले रंग। |
| [getBorderOleColor()](#getBorderOleColor--) | पृष्ठभूमि का ओले रंग। |
| [getBorderStyle()](#getBorderStyle--) | नियंत्रण द्वारा उपयोग किए जाने वाले सीमा का प्रकार। |
| [getBoundColumn()](#getBoundColumn--) | यह दर्शाता है कि Value प्रॉपर्टी कैसे निर्धारित की जाती है जब MultiSelect प्रॉपर्टी का मान (fmMultiSelectSingle) हो। |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | यह ComboBox या ListBox में प्रदर्शित करने के लिए कॉलमों की संख्या को दर्शाता है। |
| [getColumnWidths()](#getColumnWidths--) | कॉलम की चौड़ाई। |
| [getData()](#getData--) | नियंत्रण का बाइनरी डेटा। |
| [getDropButtonStyle()](#getDropButtonStyle--) | ड्रॉप बटन पर प्रदर्शित प्रतीक निर्दिष्ट करता है। |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | नियंत्रण में प्रवेश करते समय चयन व्यवहार निर्दिष्ट करता है। |
| [getForeOleColor()](#getForeOleColor--) | अग्रभूमि का ओले रंग। |
| [getHeight()](#getHeight--) | नियंत्रण की ऊँचाई बिंदुओं की इकाई में। |
| [getHideSelection()](#getHideSelection--) | यह दर्शाता है कि नियंत्रण के पास फोकस न होने पर चयनित पाठ हाइलाइट दिखता है या नहीं। |
| [getIMEMode()](#getIMEMode--) | नियंत्रण के फोकस प्राप्त करने पर इनपुट मेथड एडिटर का डिफ़ॉल्ट रन‑टाइम मोड। |
| [getListRows()](#getListRows--) | सूची में प्रदर्शित करने के लिए पंक्तियों की अधिकतम संख्या को दर्शाता है। |
| [getListStyle()](#getListStyle--) | दृश्य रूप। |
| [getListWidth()](#getListWidth--) | बिंदुओं की इकाई में चौड़ाई। |
| [getMatchEntry()](#getMatchEntry--) | बताता है कि उपयोगकर्ता टाइप करने पर ListBox या ComboBox अपनी सूची को कैसे खोजता है। |
| [getMaxLength()](#getMaxLength--) | अधिकतम अक्षरों की संख्या |
| [getMouseIcon()](#getMouseIcon--) | नियंत्रण के लिए माउस पॉइंटर के रूप में प्रदर्शित करने हेतु एक कस्टम आइकन। |
| [getMousePointer()](#getMousePointer--) | नियंत्रण के लिए माउस पॉइंटर के रूप में प्रदर्शित आइकन का प्रकार। |
| [getSelectionMargin()](#getSelectionMargin--) | बताता है कि उपयोगकर्ता टेक्स्ट के बाएँ क्षेत्र पर क्लिक करके टेक्स्ट की पंक्ति चुन सकता है या नहीं। |
| [getShowColumnHeads()](#getShowColumnHeads--) | बताता है कि कॉलम हेडिंग्स प्रदर्शित हैं या नहीं। |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | ड्रॉप बटन पर प्रदर्शित प्रतीक निर्दिष्ट करता है। |
| [getSpecialEffect()](#getSpecialEffect--) | नियंत्रण का विशेष प्रभाव। |
| [getTextColumn()](#getTextColumn--) | ComboBox या ListBox में उपयोगकर्ता को दिखाने के लिए कॉलम को दर्शाता है। |
| [getType()](#getType--) | ActiveX नियंत्रण का प्रकार प्राप्त करता है। |
| [getValue()](#getValue--) | नियंत्रण का मान। |
| [getWidth()](#getWidth--) | बिंदु की इकाई में नियंत्रण की चौड़ाई। |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | बताता है कि नियंत्रण अपने सभी सामग्री को प्रदर्शित करने के लिए स्वचालित रूप से आकार बदल देगा या नहीं। |
| [isAutoWordSelected()](#isAutoWordSelected--) | चयन को विस्तारित करने के लिए उपयोग की जाने वाली मूल इकाई निर्दिष्ट करता है। |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | बताता है कि नियंत्रण के लिए ड्रैग और ड्रॉप सक्षम है या नहीं। |
| [isEditable()](#isEditable--) | बताता है कि उपयोगकर्ता नियंत्रण में टाइप कर सकता है या नहीं। |
| [isEnabled()](#isEnabled--) | बताता है कि नियंत्रण फोकस प्राप्त कर सकता है और उपयोगकर्ता-जनित घटनाओं का जवाब दे सकता है या नहीं। |
| [isLocked()](#isLocked--) | बताता है कि नियंत्रण में डेटा संपादन के लिए लॉक है या नहीं। |
| [isTransparent()](#isTransparent--) | बताता है कि नियंत्रण पारदर्शी है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--) |
| [setBoundColumn(int value)](#setBoundColumn-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--) |
| [setColumnCount(int value)](#setColumnCount-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--) |
| [setColumnWidths(double value)](#setColumnWidths-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setListRows(int value)](#setListRows-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--) |
| [setListStyle(int value)](#setListStyle-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--) |
| [setListWidth(double value)](#setListWidth-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--) |
| [setLocked(boolean value)](#setLocked-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMatchEntry(int value)](#setMatchEntry-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--) |
| [setMaxLength(int value)](#setMaxLength-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setSelectionMargin(boolean value)](#setSelectionMargin-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--) |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--) |
| [setTextColumn(int value)](#setTextColumn-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setValue(String value)](#setValue-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--) |
| [setWidth(double value)](#setWidth-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


पृष्ठभूमि का ओले रंग।

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


पृष्ठभूमि का ओले रंग।

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


नियंत्रण द्वारा उपयोग किए जाने वाले सीमा का प्रकार।

**Returns:**
int
### getBoundColumn() {#getBoundColumn--}
```
public int getBoundColumn()
```


यह दर्शाता है कि Value प्रॉपर्टी कैसे निर्धारित की जाती है जब MultiSelect प्रॉपर्टी का मान (fmMultiSelectSingle) हो।

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnCount() {#getColumnCount--}
```
public int getColumnCount()
```


यह ComboBox या ListBox में प्रदर्शित करने के लिए कॉलमों की संख्या को दर्शाता है।

**Returns:**
int
### getColumnWidths() {#getColumnWidths--}
```
public double getColumnWidths()
```


कॉलम की चौड़ाई।

**Returns:**
डबल
### getData() {#getData--}
```
public byte[] getData()
```


नियंत्रण का बाइनरी डेटा।

**Returns:**
बाइट[]
### getDropButtonStyle() {#getDropButtonStyle--}
```
public int getDropButtonStyle()
```


ड्रॉप बटन पर प्रदर्शित प्रतीक निर्दिष्ट करता है।

**Returns:**
int
### getEnterFieldBehavior() {#getEnterFieldBehavior--}
```
public boolean getEnterFieldBehavior()
```


कंट्रोल में प्रवेश करने पर चयन व्यवहार निर्दिष्ट करता है। true निर्दिष्ट करता है कि चयन पिछले बार कंट्रोल सक्रिय होने से अपरिवर्तित रहता है। false निर्दिष्ट करता है कि कंट्रोल में प्रवेश करने पर सभी टेक्स्ट चयनित हो जाएंगे।

**Returns:**
बूलियन
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


फ़ोरग्राउंड का ओले रंग। इमेज कंट्रोल पर लागू नहीं होता।

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


नियंत्रण की ऊँचाई बिंदुओं की इकाई में।

**Returns:**
डबल
### getHideSelection() {#getHideSelection--}
```
public boolean getHideSelection()
```


यह दर्शाता है कि नियंत्रण के पास फोकस न होने पर चयनित पाठ हाइलाइट दिखता है या नहीं।

**Returns:**
बूलियन
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


नियंत्रण के फोकस प्राप्त करने पर इनपुट मेथड एडिटर का डिफ़ॉल्ट रन‑टाइम मोड।

**Returns:**
int
### getListRows() {#getListRows--}
```
public int getListRows()
```


सूची में प्रदर्शित करने के लिए पंक्तियों की अधिकतम संख्या को दर्शाता है।

**Returns:**
int
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


दृश्य रूप।

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


बिंदुओं की इकाई में चौड़ाई।

**Returns:**
डबल
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


बताता है कि उपयोगकर्ता टाइप करने पर ListBox या ComboBox अपनी सूची को कैसे खोजता है।

**Returns:**
int
### getMaxLength() {#getMaxLength--}
```
public int getMaxLength()
```


अधिकतम अक्षरों की संख्या

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


नियंत्रण के लिए माउस पॉइंटर के रूप में प्रदर्शित करने हेतु एक कस्टम आइकन।

**Returns:**
बाइट[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


नियंत्रण के लिए माउस पॉइंटर के रूप में प्रदर्शित आइकन का प्रकार।

**Returns:**
int
### getSelectionMargin() {#getSelectionMargin--}
```
public boolean getSelectionMargin()
```


बताता है कि उपयोगकर्ता टेक्स्ट के बाएँ क्षेत्र पर क्लिक करके टेक्स्ट की पंक्ति चुन सकता है या नहीं।

**Returns:**
बूलियन
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


बताता है कि कॉलम हेडिंग्स प्रदर्शित हैं या नहीं।

**Returns:**
बूलियन
### getShowDropButtonTypeWhen() {#getShowDropButtonTypeWhen--}
```
public int getShowDropButtonTypeWhen()
```


ड्रॉप बटन पर प्रदर्शित प्रतीक निर्दिष्ट करता है।

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


नियंत्रण का विशेष प्रभाव।

**Returns:**
int
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


ComboBox या ListBox में उपयोगकर्ता को दिखाने के लिए कॉलम को दर्शाता है।

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


ActiveX नियंत्रण का प्रकार प्राप्त करता है।

**Returns:**
int
### getValue() {#getValue--}
```
public String getValue()
```


नियंत्रण का मान।

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public double getWidth()
```


बिंदु की इकाई में नियंत्रण की चौड़ाई।

**Returns:**
डबल
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoSize() {#isAutoSize--}
```
public boolean isAutoSize()
```


बताता है कि नियंत्रण अपने सभी सामग्री को प्रदर्शित करने के लिए स्वचालित रूप से आकार बदल देगा या नहीं।

**Returns:**
बूलियन
### isAutoWordSelected() {#isAutoWordSelected--}
```
public boolean isAutoWordSelected()
```


चयन को विस्तारित करने के लिए उपयोग की जाने बुनियादी इकाई निर्दिष्ट करता है। true निर्दिष्ट करता है कि बुनियादी इकाई एक एकल अक्षर है। false निर्दिष्ट करता है कि बुनियादी इकाई एक पूरा शब्द है।

**Returns:**
बूलियन
### isDragBehaviorEnabled() {#isDragBehaviorEnabled--}
```
public boolean isDragBehaviorEnabled()
```


बताता है कि नियंत्रण के लिए ड्रैग और ड्रॉप सक्षम है या नहीं।

**Returns:**
बूलियन
### isEditable() {#isEditable--}
```
public boolean isEditable()
```


बताता है कि उपयोगकर्ता नियंत्रण में टाइप कर सकता है या नहीं।

**Returns:**
बूलियन
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


बताता है कि नियंत्रण फोकस प्राप्त कर सकता है और उपयोगकर्ता-जनित घटनाओं का जवाब दे सकता है या नहीं।

**Returns:**
बूलियन
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


बताता है कि नियंत्रण में डेटा संपादन के लिए लॉक है या नहीं।

**Returns:**
बूलियन
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


बताता है कि नियंत्रण पारदर्शी है या नहीं।

**Returns:**
बूलियन
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setEnterFieldBehavior(boolean value) {#setEnterFieldBehavior-boolean-}
```
public void setEnterFieldBehavior(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setHideSelection(boolean value) {#setHideSelection-boolean-}
```
public void setHideSelection(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setListRows(int value) {#setListRows-int-}
```
public void setListRows(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बाइट[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSelectionMargin(boolean value) {#setSelectionMargin-boolean-}
```
public void setSelectionMargin(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

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

