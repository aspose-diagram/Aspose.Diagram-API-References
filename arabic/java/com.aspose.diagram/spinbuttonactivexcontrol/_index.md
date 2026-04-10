---
title: SpinButtonActiveXControl
second_title: Aspose.Diagram لـ Java API Reference
description: يمثل عنصر التحكم SpinButton.
type: docs
weight: 383
url: /ar/java/com.aspose.diagram/spinbuttonactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class SpinButtonActiveXControl extends ActiveXControl
```

يمثل عنصر التحكم SpinButton.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | لون ole الخلفية. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | البيانات الثنائية للتحكم. |
| [getForeOleColor()](#getForeOleColor--) | لون ole المقدمة. |
| [getHeight()](#getHeight--) | ارتفاع التحكم بوحدة النقاط. |
| [getIMEMode()](#getIMEMode--) | وضع التشغيل الافتراضي لمحرر طريقة الإدخال للتحكم عند استلامه للتركيز. |
| [getMax()](#getMax--) | القيمة القصوى المقبولة. |
| [getMin()](#getMin--) | القيمة الدنيا المقبولة. |
| [getMouseIcon()](#getMouseIcon--) | أيقونة مخصصة لعرضها كمؤشر الفأرة للعنصر. |
| [getMousePointer()](#getMousePointer--) | نوع الأيقونة المعروضة كمؤشر الفأرة للعنصر. |
| [getOrientation()](#getOrientation--) | ما إذا كان SpinButton أو ScrollBar موجهًا عموديًا أو أفقيًا. |
| [getPosition()](#getPosition--) | القيمة. |
| [getSmallChange()](#getSmallChange--) | المقدار الذي تتغيّر به خاصية Position |
| [getType()](#getType--) | يحصل على نوع عنصر ActiveX. |
| [getWidth()](#getWidth--) | عرض العنصر بوحدة النقطة. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | يحدد ما إذا كان العنصر سيعيد حجمه تلقائيًا لعرض محتوياته بالكامل. |
| [isEnabled()](#isEnabled--) | يحدد ما إذا كان العنصر يمكنه استلام التركيز والاستجابة للأحداث التي يولدها المستخدم. |
| [isLocked()](#isLocked--) | يحدد ما إذا كانت البيانات في العنصر مقفلة للتعديل. |
| [isTransparent()](#isTransparent--) | يحدد ما إذا كان العنصر شفافًا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | لوصف هذه الخاصية، يرجى الاطلاع على [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMax(int value)](#setMax-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMax()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMax--) |
| [setMin(int value)](#setMin-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMin()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMin--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setOrientation(int value)](#setOrientation-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getOrientation()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getOrientation--) |
| [setPosition(int value)](#setPosition-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPosition()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getPosition--) |
| [setSmallChange(int value)](#setSmallChange-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSmallChange()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getSmallChange--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


لون ole الخلفية.

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


البيانات الثنائية للتحكم.

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


لون OLE للواجهة الأمامية. لا ينطبق على التحكم Image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


ارتفاع التحكم بوحدة النقاط.

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


وضع التشغيل الافتراضي لمحرر طريقة الإدخال للتحكم عند استلامه للتركيز.

**Returns:**
int
### getMax() {#getMax--}
```
public int getMax()
```


القيمة القصوى المقبولة.

**Returns:**
int
### getMin() {#getMin--}
```
public int getMin()
```


القيمة الدنيا المقبولة.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


أيقونة مخصصة لعرضها كمؤشر الفأرة للعنصر.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


نوع الأيقونة المعروضة كمؤشر الفأرة للعنصر.

**Returns:**
int
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


ما إذا كان SpinButton أو ScrollBar موجهًا عموديًا أو أفقيًا.

**Returns:**
int
### getPosition() {#getPosition--}
```
public int getPosition()
```


القيمة.

**Returns:**
int
### getSmallChange() {#getSmallChange--}
```
public int getSmallChange()
```


المقدار الذي تتغيّر به خاصية Position

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


يحصل على نوع عنصر ActiveX.

**Returns:**
int
### getWidth() {#getWidth--}
```
public double getWidth()
```


عرض العنصر بوحدة النقطة.

**Returns:**
double
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


يحدد ما إذا كان العنصر سيعيد حجمه تلقائيًا لعرض محتوياته بالكامل.

**Returns:**
منطقي
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


يحدد ما إذا كان العنصر يمكنه استلام التركيز والاستجابة للأحداث التي يولدها المستخدم.

**Returns:**
منطقي
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


يحدد ما إذا كانت البيانات في العنصر مقفلة للتعديل.

**Returns:**
منطقي
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


يحدد ما إذا كان العنصر شفافًا.

**Returns:**
منطقي
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


لوصف هذه الخاصية، يرجى الاطلاع على [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setMax(int value) {#setMax-int-}
```
public void setMax(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMax()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMax--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setMin(int value) {#setMin-int-}
```
public void setMin(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMin()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getMin--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getOrientation()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getOrientation--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPosition(int value) {#setPosition-int-}
```
public void setPosition(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPosition()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getPosition--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setSmallChange(int value) {#setSmallChange-int-}
```
public void setSmallChange(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSmallChange()](../../com.aspose.diagram/spinbuttonactivexcontrol\#getSmallChange--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

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

