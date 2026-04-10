---
title: GluedShapesFlags
second_title: Aspose.Diagram for Java API Reference
description: Shape.GluedShapes मेथड को पास किए गए किसी विशेष आकार से जुड़े कनेक्शन पॉइंट्स की आयामिकता और दिशा के आधार पर कौन से आकार लौटाने हैं, इसे पहचानने वाले स्थिरांक को निर्दिष्ट करता है।
type: docs
weight: 176
url: /hi/java/com.aspose.diagram/gluedshapesflags/
---

**Inheritance:**
java.lang.Object
```
public final class GluedShapesFlags
```

स्थिरांक को निर्दिष्ट करता है जो यह पहचानते हैं कि किन आकारों को लौटाना है, यह विशेष आकार से जुड़े कनेक्शन पॉइंट्स की आयामिकता और दिशा पर आधारित है; इसे Shape.GluedShapes मेथड को पास किया जाता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [GLUED_SHAPES_ALL_1_D](#GLUED-SHAPES-ALL-1-D) | इस आकार से जुड़े सभी 1-D आकारों के IDs लौटाएँ। |
| [GLUED_SHAPES_ALL_2_D](#GLUED-SHAPES-ALL-2-D) | इस आकार से जुड़े सभी 2-D आकारों और उन सभी 2-D आकारों को लौटाएँ जिनसे यह आकार जुड़ा है। |
| [GLUED_SHAPES_INCOMING_1_D](#GLUED-SHAPES-INCOMING-1-D) | जिसके अंत बिंदु इस आकार से जुड़े हैं, ऐसे 1-D आकारों के IDs लौटाएँ। |
| [GLUED_SHAPES_INCOMING_2_D](#GLUED-SHAPES-INCOMING-2-D) | यदि स्रोत ऑब्जेक्ट एक 1-D आकार है, तो शुरुआती बिंदु जिस 2-D आकार से जुड़ा है, उसके IDs लौटाएँ। |
| [GLUED_SHAPES_OUTGOING_1_D](#GLUED-SHAPES-OUTGOING-1-D) | इस आकार से जुड़े प्रारम्भ बिंदुओं वाले 1-D आकारों के IDs लौटाएँ। |
| [GLUED_SHAPES_OUTGOING_2_D](#GLUED-SHAPES-OUTGOING-2-D) | यदि स्रोत वस्तु 1-D आकार है, तो अंत बिंदु से जुड़ी 2-D आकार के IDs लौटाएँ। |
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
### GLUED_SHAPES_ALL_1_D {#GLUED-SHAPES-ALL-1-D}
```
public static final int GLUED_SHAPES_ALL_1_D
```


इस आकार से जुड़े सभी 1-D आकारों के IDs लौटाएँ।

### GLUED_SHAPES_ALL_2_D {#GLUED-SHAPES-ALL-2-D}
```
public static final int GLUED_SHAPES_ALL_2_D
```


इस आकार से जुड़े सभी 2-D आकारों और उन सभी 2-D आकारों को लौटाएँ जिनसे यह आकार जुड़ा है।

### GLUED_SHAPES_INCOMING_1_D {#GLUED-SHAPES-INCOMING-1-D}
```
public static final int GLUED_SHAPES_INCOMING_1_D
```


जिसके अंत बिंदु इस आकार से जुड़े हैं, ऐसे 1-D आकारों के IDs लौटाएँ।

### GLUED_SHAPES_INCOMING_2_D {#GLUED-SHAPES-INCOMING-2-D}
```
public static final int GLUED_SHAPES_INCOMING_2_D
```


यदि स्रोत वस्तु 1-D आकार है, तो प्रारम्भ बिंदु से जुड़ी 2-D आकार के IDs लौटाएँ। यदि स्रोत वस्तु 2-D आकार है, तो इस आकार से जुड़े 2-D आकारों के IDs लौटाएँ।

### GLUED_SHAPES_OUTGOING_1_D {#GLUED-SHAPES-OUTGOING-1-D}
```
public static final int GLUED_SHAPES_OUTGOING_1_D
```


इस आकार से जुड़े प्रारम्भ बिंदुओं वाले 1-D आकारों के IDs लौटाएँ।

### GLUED_SHAPES_OUTGOING_2_D {#GLUED-SHAPES-OUTGOING-2-D}
```
public static final int GLUED_SHAPES_OUTGOING_2_D
```


यदि स्रोत वस्तु 1-D आकार है, तो अंत बिंदु से जुड़ी 2-D आकार के IDs लौटाएँ। यदि स्रोत वस्तु 2-D आकार है, तो इस आकार से जुड़े 2-D आकारों के IDs लौटाएँ।

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

