---
title: تحكم
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر لإحداثيات x و y لكل مقبض تحكم معرف لشكل وعناصر تحدد طريقة سلوك مقبض التحكم.
type: docs
weight: 87
url: /ar/java/com.aspose.diagram/control/
---

**Inheritance:**
java.lang.Object
```
public class Control
```

يحتوي على عناصر لإحداثيات x و y لكل مقبض تحكم معرف لشكل، وعناصر تحدد الطريقة التي يجب أن يتصرف بها مقبض التحكم.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Control()](#Control--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canGlue()](#canGlue--) | يحدد ما إذا كان يمكن لصق مقبض التحكم بأشكال أخرى. |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getID()](#getID--) | المعرّف الفريد للعنصر داخل العنصر الأب. |
| [getIX()](#getIX--) | فهرس العنصر داخل العنصر الأصل بدءًا من الصفر. |
| [getName()](#getName--) | اسم العنصر. |
| [getNameU()](#getNameU--) | الاسم العام للعنصر. |
| [getPrompt()](#getPrompt--) | عنصر Prompt يحدد النص الوصفي الذي يظهر كأداة تلميح عندما يتوقف مؤشر الفأرة فوق مقبض التحكم الخاص بالشكل. |
| [getX()](#getX--) | الإحداثي x الذي يشير إلى موقع مقبض التحكم الخاص بالشكل. |
| [getXCon()](#getXCon--) | يحدد نوع السلوك الذي يظهره الإحداثي x لمقبض التحكم بعد تحريك المقبض. |
| [getXDyn()](#getXDyn--) | يحدد الإحداثي x لنقطة ارتكاز مقبض التحكم في الإحداثيات المحلية. |
| [getY()](#getY--) | الإحداثي y الذي يشير إلى موقع مقبض التحكم الخاص بالشكل. |
| [getYCon()](#getYCon--) | يحدد نوع السلوك الذي يظهره الإحداثي x لمقبض التحكم بعد تحريك المقبض. |
| [getYDyn()](#getYDyn--) | يحدد الإحداثي y لنقطة ارتكاز مقبض التحكم في الإحداثيات المحلية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCanGlue(BoolValue value)](#setCanGlue-com.aspose.diagram.BoolValue-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [canGlue()](../../com.aspose.diagram/control\#canGlue--) |
| [setDel(int value)](#setDel-int-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/control\#getDel--) |
| [setID(int value)](#setID-int-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/control\#getID--) |
| [setIX(int value)](#setIX-int-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/control\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/control\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/control\#getNameU--) |
| [setPrompt(Str2Value value)](#setPrompt-com.aspose.diagram.Str2Value-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getPrompt()](../../com.aspose.diagram/control\#getPrompt--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getX()](../../com.aspose.diagram/control\#getX--) |
| [setXCon(ConType value)](#setXCon-com.aspose.diagram.ConType-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getXCon()](../../com.aspose.diagram/control\#getXCon--) |
| [setXDyn(DoubleValue value)](#setXDyn-com.aspose.diagram.DoubleValue-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getXDyn()](../../com.aspose.diagram/control\#getXDyn--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getY()](../../com.aspose.diagram/control\#getY--) |
| [setYCon(ConType value)](#setYCon-com.aspose.diagram.ConType-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getYCon()](../../com.aspose.diagram/control\#getYCon--) |
| [setYDyn(DoubleValue value)](#setYDyn-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getYDyn()](../../com.aspose.diagram/control\#getYDyn--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Control() {#Control--}
```
public Control()
```


منشئ.

### canGlue() {#canGlue--}
```
public BoolValue canGlue()
```


يحدد ما إذا كان يمكن لصق مقبض التحكم بأشكال أخرى.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ نسخة عميقة من هذه المثيلة.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
منطقي
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


المعرّف الفريد للعنصر داخل العنصر الأب.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


فهرس العنصر داخل العنصر الأصل بدءًا من الصفر.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


اسم العنصر.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


الاسم العام للعنصر.

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


عنصر Prompt يحدد النص الوصفي الذي يظهر كأداة تلميح عندما يتوقف مؤشر الفأرة فوق مقبض التحكم الخاص بالشكل.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getX() {#getX--}
```
public DoubleValue getX()
```


الإحداثي x الذي يشير إلى موقع مقبض التحكم الخاص بالشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getXCon() {#getXCon--}
```
public ConType getXCon()
```


يحدد نوع السلوك الذي يظهره الإحداثي x لمقبض التحكم بعد تحريك المقبض.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getXDyn() {#getXDyn--}
```
public DoubleValue getXDyn()
```


يحدد إحداثي x لنقطة تثبيت مقبض التحكم في الإحداثيات المحلية. تُستخدم نقطة التثبيت للربط المرن أثناء الديناميكيات.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


الإحداثي y الذي يشير إلى موقع مقبض التحكم الخاص بالشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getYCon() {#getYCon--}
```
public ConType getYCon()
```


يحدد نوع السلوك الذي يظهره الإحداثي x لمقبض التحكم بعد تحريك المقبض.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getYDyn() {#getYDyn--}
```
public DoubleValue getYDyn()
```


يحدد إحداثي y لنقطة تثبيت مقبض التحكم في الإحداثيات المحلية. تُستخدم نقطة التثبيت للربط المرن أثناء الديناميكيات.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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




### setCanGlue(BoolValue value) {#setCanGlue-com.aspose.diagram.BoolValue-}
```
public void setCanGlue(BoolValue value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [canGlue()](../../com.aspose.diagram/control\#canGlue--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/control\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/control\#getID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/control\#getIX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/control\#getName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/control\#getNameU--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setPrompt(Str2Value value) {#setPrompt-com.aspose.diagram.Str2Value-}
```
public void setPrompt(Str2Value value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getPrompt()](../../com.aspose.diagram/control\#getPrompt--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getX()](../../com.aspose.diagram/control\#getX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setXCon(ConType value) {#setXCon-com.aspose.diagram.ConType-}
```
public void setXCon(ConType value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getXCon()](../../com.aspose.diagram/control\#getXCon--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setXDyn(DoubleValue value) {#setXDyn-com.aspose.diagram.DoubleValue-}
```
public void setXDyn(DoubleValue value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getXDyn()](../../com.aspose.diagram/control\#getXDyn--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getY()](../../com.aspose.diagram/control\#getY--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setYCon(ConType value) {#setYCon-com.aspose.diagram.ConType-}
```
public void setYCon(ConType value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getYCon()](../../com.aspose.diagram/control\#getYCon--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setYDyn(DoubleValue value) {#setYDyn-com.aspose.diagram.DoubleValue-}
```
public void setYDyn(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getYDyn()](../../com.aspose.diagram/control\#getYDyn--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

