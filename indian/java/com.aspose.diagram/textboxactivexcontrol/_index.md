---
title: TextBoxActiveXControl
second_title: Aspose.Diagram for Java API Reference
description: टेक्स्ट बॉक्स ActiveX नियंत्रण का प्रतिनिधित्व करता है।
type: docs
weight: 401
url: /hi/java/com.aspose.diagram/textboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class TextBoxActiveXControl extends ActiveXControl
```

टेक्स्ट बॉक्स ActiveX नियंत्रण का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | पृष्ठभूमि का ओले रंग। |
| [getBorderOleColor()](#getBorderOleColor--) | पृष्ठभूमि का ओले रंग। |
| [getBorderStyle()](#getBorderStyle--) | नियंत्रण द्वारा उपयोग किए जाने वाले सीमा का प्रकार। |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | नियंत्रण का बाइनरी डेटा। |
| [getDropButtonStyle()](#getDropButtonStyle--) | ड्रॉप बटन पर प्रदर्शित प्रतीक निर्दिष्ट करता है। |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | नियंत्रण में प्रवेश करते समय चयन व्यवहार निर्दिष्ट करता है। |
| [getEnterKeyBehavior()](#getEnterKeyBehavior--) | ENTER कुंजी के व्यवहार को निर्दिष्ट करता है। |
| [getForeOleColor()](#getForeOleColor--) | अग्रभूमि का ओले रंग। |
| [getHeight()](#getHeight--) | नियंत्रण की ऊँचाई बिंदुओं की इकाई में। |
| [getHideSelection()](#getHideSelection--) | यह दर्शाता है कि नियंत्रण के पास फोकस न होने पर चयनित पाठ हाइलाइट दिखता है या नहीं। |
| [getIMEMode()](#getIMEMode--) | नियंत्रण के फोकस प्राप्त करने पर इनपुट मेथड एडिटर का डिफ़ॉल्ट रन‑टाइम मोड। |
| [getIntegralHeight()](#getIntegralHeight--) | निर्देशित करता है कि नियंत्रण केवल पूर्ण पंक्तियों का पाठ दिखाएगा या कोई आंशिक पंक्तियाँ नहीं दिखाएगा। |
| [getMaxLength()](#getMaxLength--) | अधिकतम अक्षरों की संख्या |
| [getMouseIcon()](#getMouseIcon--) | नियंत्रण के लिए माउस पॉइंटर के रूप में प्रदर्शित करने हेतु एक कस्टम आइकन। |
| [getMousePointer()](#getMousePointer--) | नियंत्रण के लिए माउस पॉइंटर के रूप में प्रदर्शित आइकन का प्रकार। |
| [getPasswordChar()](#getPasswordChar--) | दर्ज किए गए अक्षरों के स्थान पर प्रदर्शित होने वाला एक अक्षर। |
| [getScrollBars()](#getScrollBars--) | निर्देशित करता है कि नियंत्रण में लंबवत स्क्रॉल बार, क्षैतिज स्क्रॉल बार, दोनों या कोई नहीं हैं। |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | ड्रॉप बटन पर प्रदर्शित प्रतीक निर्दिष्ट करता है। |
| [getSpecialEffect()](#getSpecialEffect--) | नियंत्रण का विशेष प्रभाव। |
| [getTabKeyBehavior()](#getTabKeyBehavior--) | निर्देशित करता है कि नियंत्रण के पाठ में टैब अक्षर अनुमति हैं या नहीं। |
| [getText()](#getText--) | नियंत्रण का पाठ। |
| [getType()](#getType--) | ActiveX नियंत्रण का प्रकार प्राप्त करता है। |
| [getWidth()](#getWidth--) | बिंदु की इकाई में नियंत्रण की चौड़ाई। |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | बताता है कि नियंत्रण अपने सभी सामग्री को प्रदर्शित करने के लिए स्वचालित रूप से आकार बदल देगा या नहीं। |
| [isAutoTab()](#isAutoTab--) | यह संकेत करता है कि उपयोगकर्ता अधिकतम अक्षर संख्या दर्ज करने पर फोकस स्वचालित रूप से अगले नियंत्रण पर जाएगा। |
| [isAutoWordSelected()](#isAutoWordSelected--) | चयन को विस्तारित करने के लिए उपयोग की जाने वाली मूल इकाई निर्दिष्ट करता है। |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | बताता है कि नियंत्रण के लिए ड्रैग और ड्रॉप सक्षम है या नहीं। |
| [isEditable()](#isEditable--) | बताता है कि उपयोगकर्ता नियंत्रण में टाइप कर सकता है या नहीं। |
| [isEnabled()](#isEnabled--) | बताता है कि नियंत्रण फोकस प्राप्त कर सकता है और उपयोगकर्ता-जनित घटनाओं का जवाब दे सकता है या नहीं। |
| [isLocked()](#isLocked--) | बताता है कि नियंत्रण में डेटा संपादन के लिए लॉक है या नहीं। |
| [isMultiLine()](#isMultiLine--) | यह संकेत करता है कि नियंत्रण एक से अधिक पंक्तियों का पाठ प्रदर्शित कर सकता है। |
| [isTransparent()](#isTransparent--) | बताता है कि नियंत्रण पारदर्शी है या नहीं। |
| [isWordWrapped()](#isWordWrapped--) | निर्देशित करता है कि नियंत्रण की सामग्री स्वचालित रूप से पंक्ति के अंत में रैप होगी या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoTab(boolean value)](#setAutoTab-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--) |
| [setEnterKeyBehavior(boolean value)](#setEnterKeyBehavior-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--) |
| [setLocked(boolean value)](#setLocked-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMaxLength(int value)](#setMaxLength-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setMultiLine(boolean value)](#setMultiLine-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--) |
| [setPasswordChar(char value)](#setPasswordChar-char-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--) |
| [setScrollBars(int value)](#setScrollBars-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--) |
| [setTabKeyBehavior(boolean value)](#setTabKeyBehavior-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--) |
| [setText(String value)](#setText-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--) |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getEnterKeyBehavior() {#getEnterKeyBehavior--}
```
public boolean getEnterKeyBehavior()
```


ENTER कुंजी के व्यवहार को निर्दिष्ट करता है। True यह दर्शाता है कि ENTER दबाने पर नई पंक्ति बनती है। False यह दर्शाता है कि ENTER दबाने पर फोकस टैब क्रम में अगले ऑब्जेक्ट पर चला जाता है।

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
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


निर्देशित करता है कि नियंत्रण केवल पूर्ण पंक्तियों का पाठ दिखाएगा या कोई आंशिक पंक्तियाँ नहीं दिखाएगा।

**Returns:**
बूलियन
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
### getPasswordChar() {#getPasswordChar--}
```
public char getPasswordChar()
```


दर्ज किए गए अक्षरों के स्थान पर प्रदर्शित होने वाला एक अक्षर।

**Returns:**
char
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


निर्देशित करता है कि नियंत्रण में लंबवत स्क्रॉल बार, क्षैतिज स्क्रॉल बार, दोनों या कोई नहीं हैं।

**Returns:**
int
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
### getTabKeyBehavior() {#getTabKeyBehavior--}
```
public boolean getTabKeyBehavior()
```


निर्देशित करता है कि नियंत्रण के पाठ में टैब अक्षर अनुमति हैं या नहीं।

**Returns:**
बूलियन
### getText() {#getText--}
```
public String getText()
```


नियंत्रण का पाठ।

**Returns:**
java.lang.String
### getType() {#getType--}
```
public int getType()
```


ActiveX नियंत्रण का प्रकार प्राप्त करता है।

**Returns:**
int
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
### isAutoTab() {#isAutoTab--}
```
public boolean isAutoTab()
```


यह संकेत करता है कि उपयोगकर्ता अधिकतम अक्षर संख्या दर्ज करने पर फोकस स्वचालित रूप से अगले नियंत्रण पर जाएगा।

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
### isMultiLine() {#isMultiLine--}
```
public boolean isMultiLine()
```


यह संकेत करता है कि नियंत्रण एक से अधिक पंक्तियों का पाठ प्रदर्शित कर सकता है।

**Returns:**
बूलियन
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


बताता है कि नियंत्रण पारदर्शी है या नहीं।

**Returns:**
बूलियन
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


निर्देशित करता है कि नियंत्रण की सामग्री स्वचालित रूप से पंक्ति के अंत में रैप होगी या नहीं।

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

### setAutoTab(boolean value) {#setAutoTab-boolean-}
```
public void setAutoTab(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--)

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


इस गुण का विवरण देखने के लिए, कृपया देखें [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--)

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


इस गुण का विवरण देखने के लिए, कृपया देखें [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setEnterKeyBehavior(boolean value) {#setEnterKeyBehavior-boolean-}
```
public void setEnterKeyBehavior(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--)

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


इस गुण का विवरण देखने के लिए, कृपया देखें [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--)

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

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--)

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

### setMultiLine(boolean value) {#setMultiLine-boolean-}
```
public void setMultiLine(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setPasswordChar(char value) {#setPasswordChar-char-}
```
public void setPasswordChar(char value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | char |  |

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTabKeyBehavior(boolean value) {#setTabKeyBehavior-boolean-}
```
public void setTabKeyBehavior(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

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

