---
title: FontConfigs
second_title: Aspose.Diagram for Java API Reference
description: फ़ॉन्ट सेटिंग्स निर्दिष्ट करता है
type: docs
weight: 160
url: /hi/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

फ़ॉन्ट सेटिंग्स निर्दिष्ट करता है
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | डिफ़ॉल्ट फ़ॉन्ट नाम। |
| [getFontSources()](#getFontSources--) | ऐरे की एक कॉपी प्राप्त करता है जिसमें स्रोतों की सूची होती है |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | ऐरे लौटाता है जिसमें फ़ॉन्ट प्रतिस्थापन नाम होते हैं जिन्हें मूल फ़ॉन्ट उपलब्ध न होने पर उपयोग किया जाता है। |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | यह संकेत देता है कि जब फ़ॉन्ट उपलब्ध नहीं हो और इस फ़ॉन्ट का प्रतिस्थापन सेट न हो, तो सिस्टम फ़ॉन्ट प्रतिस्थापनों को पहले उपयोग करना है या नहीं। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | फ़ॉन्ट फ़ोल्डर सेट करता है |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | फ़ॉन्ट फ़ोल्डरों को सेट करता है |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | फ़ॉन्ट स्रोतों को सेट करता है। |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | दिए गए मूल फ़ॉन्ट नाम के लिए फ़ॉन्ट प्रतिस्थापन नाम। |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontConfigs() {#FontConfigs--}
```
public FontConfigs()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


डिफ़ॉल्ट फ़ॉन्ट नाम।

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


ऐरे की एक कॉपी प्राप्त करता है जिसमें स्रोतों की सूची होती है

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


ऐरे लौटाता है जिसमें फ़ॉन्ट प्रतिस्थापन नाम होते हैं जिन्हें मूल फ़ॉन्ट उपलब्ध न होने पर उपयोग किया जाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - मूल फ़ॉन्ट उपलब्ध नहीं होने पर उपयोग किए जाने वाले फ़ॉन्ट प्रतिस्थापन नामों की एक सरणी।
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


जब फ़ॉन्ट उपलब्ध नहीं हो और उसके प्रतिस्थापन सेट न हो, तो सिस्टम फ़ॉन्ट प्रतिस्थापन को पहले उपयोग करना है या नहीं, यह संकेत दें। उदाहरण के लिए, Ubuntu पर \"Arial\" फ़ॉन्ट आमतौर पर \"Liberation Sans\" द्वारा प्रतिस्थापित किया जाता है। डिफ़ॉल्ट मान false है।

**Returns:**
बूलियन
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




### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


फ़ॉन्ट फ़ोल्डर सेट करता है

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontFolder | java.lang.String | वह फ़ोल्डर जिसमें TrueType फ़ॉन्ट्स होते हैं। |
| recursive | बूलियन | निर्धारित करता है कि उपफ़ोल्डर स्कैन किए जाएँ या नहीं। |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


फ़ॉन्ट फ़ोल्डरों को सेट करता है

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fontFolders | java.lang.String[] | वह फ़ोल्डर जो TrueType फ़ॉन्ट्स को शामिल करते हैं। |
| recursive | बूलियन | निर्धारित करता है कि उपफ़ोल्डर स्कैन किए जाएँ या नहीं। |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


फ़ॉन्ट स्रोतों को सेट करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | TrueType फ़ॉन्ट्स को शामिल करने वाले स्रोतों की एक सरणी। |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


दिए गए मूल फ़ॉन्ट नाम के लिए फ़ॉन्ट प्रतिस्थापन नाम।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| originalFontName | java.lang.String | मूल फ़ॉन्ट नाम। |
| substituteFontNames | java.lang.String[] | मूल फ़ॉन्ट उपलब्ध न होने पर उपयोग किए जाने वाले फ़ॉन्ट प्रतिस्थापन नामों की सूची। |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)

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

