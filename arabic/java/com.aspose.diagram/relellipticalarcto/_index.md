---
title: RelEllipticalArcTo
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تحدد معلومات حول قوس إهليلجي. يتم تحديد الإحداثيات كإحداثيات نسبية.
type: docs
weight: 318
url: /ar/java/com.aspose.diagram/relellipticalarcto/
---

**Inheritance:**
java.lang.Object، [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class RelEllipticalArcTo extends Coordinate
```

يحتوي على عناصر تحدد معلومات حول قوس إهليلجي. يتم تحديد الإحداثيات كإحداثيات نسبية.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RelEllipticalArcTo()](#RelEllipticalArcTo--) | ينشئ مثيلاً من الفئة [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | الإحداثي س لنقطة التحكم في القوس. |
| [getB()](#getB--) | الإحداثي ص لنقطة التحكم في القوس. |
| [getC()](#getC--) | زاوية المحور الرئيسي للقوس بالنسبة إلى المحور س للعنصر الأصلي. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | نسبة المحور الرئيسي للقوس إلى محوره الثانوي. |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getIX()](#getIX--) | فهرس العنصر داخل العنصر الأصل بدءًا من الصفر. |
| [getX()](#getX--) | الإحداثي س لرأس النهاية لقوس إهليلجي. |
| [getY()](#getY--) | الإحداثي ص لرأس النهاية لقوس إهليلجي. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--) |
| [setDel(int value)](#setDel-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--) |
| [setIX(int value)](#setIX-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelEllipticalArcTo() {#RelEllipticalArcTo--}
```
public RelEllipticalArcTo()
```


ينشئ مثيلاً من الفئة [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto).

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
### getA() {#getA--}
```
public DoubleValue getA()
```


الإحداثي السيني لنقطة التحكم في القوس. يُفضَّل أن تكون نقطة التحكم موجودة تقريبًا في منتصف المسافة بين رأسَي البداية والنهاية للقوس. وإلا قد ينمو القوس إلى حجم كبير جدًا لتجاوز نقطة التحكم، مما قد يؤدي إلى نتائج غير متوقعة.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


الإحداثي ص لنقطة التحكم في القوس.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


زاوية المحور الرئيسي للقوس بالنسبة إلى المحور س للعنصر الأصلي.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


نسبة المحور الرئيسي للقوس إلى محوره الثانوي. بالرغم من المعنى الشائع لهذه الكلمات، لا يلزم أن يكون المحور الرئيسي أكبر من المحور الثانوي، لذا لا يلزم أن تكون هذه النسبة أكبر من 1. ضبط هذا العنصر على قيمة أقل من أو تساوي 0 أو أكبر من 1000 قد يؤدي إلى نتائج غير متوقعة.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


فهرس العنصر داخل العنصر الأصل بدءًا من الصفر.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


الإحداثي س لرأس النهاية لقوس إهليلجي.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


الإحداثي ص لرأس النهاية لقوس إهليلجي.

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--)

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

