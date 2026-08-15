---
title: ConValue
second_title: Aspose.Diagram for Java API Reference
description: हैंडल को स्थानांतरित करने के बाद नियंत्रण हैंडल के x या y-निर्देशांक द्वारा प्रदर्शित व्यवहार के प्रकार को निर्दिष्ट करता है।
type: docs
weight: 74
url: /hi/java/com.aspose.diagram/convalue/
---

**Inheritance:**
java.lang.Object
```
public final class ConValue
```

हैंडल को स्थानांतरित करने के बाद नियंत्रण हैंडल के x या y-निर्देशांक द्वारा प्रदर्शित व्यवहार के प्रकार को निर्दिष्ट करता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [OFFSET_FROM_CENTER](#OFFSET-FROM-CENTER) | केंद्र से ऑफसेट। |
| [OFFSET_FROM_CENTER_HIDDEN](#OFFSET-FROM-CENTER-HIDDEN) | केंद्र से ऑफसेट, छिपा हुआ। |
| [OFFSET_FROM_LEFT_EDGE](#OFFSET-FROM-LEFT-EDGE) | बाएँ किनारे से ऑफसेट। |
| [OFFSET_FROM_LEFT_EDGE_HIDDEN](#OFFSET-FROM-LEFT-EDGE-HIDDEN) | बाएँ किनारे से ऑफसेट, छिपा हुआ। |
| [OFFSET_FROM_RIGHT_EDGE](#OFFSET-FROM-RIGHT-EDGE) | दाएँ किनारे से ऑफसेट। |
| [OFFSET_FROM_RIGHT_EDGE_HIDDEN](#OFFSET-FROM-RIGHT-EDGE-HIDDEN) | दाएँ किनारे से ऑफ़सेट, छिपा हुआ। |
| [PROPORTIONAL](#PROPORTIONAL) | अनुपाती। |
| [PROPORTIONAL_HIDDEN](#PROPORTIONAL-HIDDEN) | अनुपाती, छिपा हुआ। 0 के समान, लेकिन नियंत्रण हैंडल दिखाई नहीं देता। |
| [PROPORTIONAL_LOCKED](#PROPORTIONAL-LOCKED) | अनुपाती लॉक्ड। |
| [PROPORTIONAL_LOCKED_HIDDEN](#PROPORTIONAL-LOCKED-HIDDEN) | अनुपाती लॉक्ड, छिपा हुआ। |
| [UNDEFINED](#UNDEFINED) | अपरिभाषित। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OFFSET_FROM_CENTER {#OFFSET-FROM-CENTER}
```
public static final int OFFSET_FROM_CENTER
```


केंद्र से ऑफ़सेट। नियंत्रण हैंडल आकार के केंद्र से एक स्थिर दूरी पर ऑफ़सेट किया गया है।

### OFFSET_FROM_CENTER_HIDDEN {#OFFSET-FROM-CENTER-HIDDEN}
```
public static final int OFFSET_FROM_CENTER_HIDDEN
```


केंद्र से ऑफ़सेट, छिपा हुआ। 3 के समान, लेकिन नियंत्रण हैंडल दिखाई नहीं देता।

### OFFSET_FROM_LEFT_EDGE {#OFFSET-FROM-LEFT-EDGE}
```
public static final int OFFSET_FROM_LEFT_EDGE
```


बाएँ किनारे से ऑफ़सेट। नियंत्रण हैंडल आकार के बाएँ पक्ष से एक स्थिर दूरी पर ऑफ़सेट किया गया है।

### OFFSET_FROM_LEFT_EDGE_HIDDEN {#OFFSET-FROM-LEFT-EDGE-HIDDEN}
```
public static final int OFFSET_FROM_LEFT_EDGE_HIDDEN
```


बाएँ किनारे से ऑफ़सेट, छिपा हुआ। 2 के समान, लेकिन नियंत्रण हैंडल दिखाई नहीं देता।

### OFFSET_FROM_RIGHT_EDGE {#OFFSET-FROM-RIGHT-EDGE}
```
public static final int OFFSET_FROM_RIGHT_EDGE
```


दाएँ किनारे से ऑफ़सेट। नियंत्रण हैंडल आकार के दाएँ पक्ष से एक स्थिर दूरी पर ऑफ़सेट किया गया है।

### OFFSET_FROM_RIGHT_EDGE_HIDDEN {#OFFSET-FROM-RIGHT-EDGE-HIDDEN}
```
public static final int OFFSET_FROM_RIGHT_EDGE_HIDDEN
```


दाएँ किनारे से ऑफ़सेट, छिपा हुआ। 4 के समान, लेकिन नियंत्रण हैंडल दिखाई नहीं देता।

### PROPORTIONAL {#PROPORTIONAL}
```
public static final int PROPORTIONAL
```


अनुपाती। नियंत्रण हैंडल को स्थानांतरित किया जा सकता है, और यह आकार को खींचे जाने पर अनुपात में भी चलता है।

### PROPORTIONAL_HIDDEN {#PROPORTIONAL-HIDDEN}
```
public static final int PROPORTIONAL_HIDDEN
```


अनुपाती, छिपा हुआ। 0 के समान, लेकिन नियंत्रण हैंडल दिखाई नहीं देता।

### PROPORTIONAL_LOCKED {#PROPORTIONAL-LOCKED}
```
public static final int PROPORTIONAL_LOCKED
```


अनुपाती लॉक्ड। नियंत्रण हैंडल आकार के साथ अनुपात में चलता है, लेकिन स्वयं नियंत्रण हैंडल को स्थानांतरित नहीं किया जा सकता।

### PROPORTIONAL_LOCKED_HIDDEN {#PROPORTIONAL-LOCKED-HIDDEN}
```
public static final int PROPORTIONAL_LOCKED_HIDDEN
```


अनुपाती लॉक्ड, छिपा हुआ। 1 के समान, लेकिन नियंत्रण हैंडल दिखाई नहीं देता।

### UNDEFINED {#UNDEFINED}
```
public static final int UNDEFINED
```


अपरिभाषित।

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

