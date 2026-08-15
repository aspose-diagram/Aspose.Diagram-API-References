---
title: LabelActiveXControl
second_title: Aspose.Diagram لـ Java API Reference
description: يمثل عنصر التحكم ActiveX للملصق.
type: docs
weight: 211
url: /ar/java/com.aspose.diagram/labelactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class LabelActiveXControl extends ActiveXControl
```

يمثل عنصر التحكم ActiveX للملصق.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccelerator()](#getAccelerator--) | مفتاح الاختصار للعنصر. |
| [getBackOleColor()](#getBackOleColor--) | لون ole الخلفية. |
| [getBorderOleColor()](#getBorderOleColor--) | لون ole الخلفية. |
| [getBorderStyle()](#getBorderStyle--) | نوع الحدود المستخدمة في التحكم. |
| [getCaption()](#getCaption--) | النص الوصفي الذي يظهر على العنصر. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | البيانات الثنائية للتحكم. |
| [getForeOleColor()](#getForeOleColor--) | لون ole المقدمة. |
| [getHeight()](#getHeight--) | ارتفاع التحكم بوحدة النقاط. |
| [getIMEMode()](#getIMEMode--) | وضع التشغيل الافتراضي لمحرر طريقة الإدخال للتحكم عند استلامه للتركيز. |
| [getMouseIcon()](#getMouseIcon--) | أيقونة مخصصة لعرضها كمؤشر الفأرة للعنصر. |
| [getMousePointer()](#getMousePointer--) | نوع الأيقونة المعروضة كمؤشر الفأرة للعنصر. |
| [getPicture()](#getPicture--) | بيانات الصورة. |
| [getPicturePosition()](#getPicturePosition--) | موقع صورة التحكم بالنسبة إلى التسمية التوضيحية. |
| [getSpecialEffect()](#getSpecialEffect--) | التأثير الخاص للعنصر. |
| [getType()](#getType--) | يحصل على نوع عنصر ActiveX. |
| [getWidth()](#getWidth--) | عرض العنصر بوحدة النقطة. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | يحدد ما إذا كان العنصر سيعيد حجمه تلقائيًا لعرض محتوياته بالكامل. |
| [isEnabled()](#isEnabled--) | يحدد ما إذا كان العنصر يمكنه استلام التركيز والاستجابة للأحداث التي يولدها المستخدم. |
| [isLocked()](#isLocked--) | يحدد ما إذا كانت البيانات في العنصر مقفلة للتعديل. |
| [isTransparent()](#isTransparent--) | يحدد ما إذا كان العنصر شفافًا. |
| [isWordWrapped()](#isWordWrapped--) | يشير إلى ما إذا كان محتوى التحكم يلتف تلقائيًا في نهاية السطر. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccelerator(char value)](#setAccelerator-char-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAccelerator()](../../com.aspose.diagram/labelactivexcontrol\#getAccelerator--) |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | لوصف هذه الخاصية، يرجى الاطلاع على [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBorderOleColor()](../../com.aspose.diagram/labelactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBorderStyle()](../../com.aspose.diagram/labelactivexcontrol\#getBorderStyle--) |
| [setCaption(String value)](#setCaption-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCaption()](../../com.aspose.diagram/labelactivexcontrol\#getCaption--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPicture()](../../com.aspose.diagram/labelactivexcontrol\#getPicture--) |
| [setPicturePosition(int value)](#setPicturePosition-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPicturePosition()](../../com.aspose.diagram/labelactivexcontrol\#getPicturePosition--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpecialEffect()](../../com.aspose.diagram/labelactivexcontrol\#getSpecialEffect--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isWordWrapped()](../../com.aspose.diagram/labelactivexcontrol\#isWordWrapped--) |
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
### getAccelerator() {#getAccelerator--}
```
public char getAccelerator()
```


مفتاح الاختصار للعنصر.

**Returns:**
char
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


لون ole الخلفية.

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


لون ole الخلفية.

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


نوع الحدود المستخدمة في التحكم.

**Returns:**
int
### getCaption() {#getCaption--}
```
public String getCaption()
```


النص الوصفي الذي يظهر على العنصر.

**Returns:**
java.lang.String
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
### getPicture() {#getPicture--}
```
public byte[] getPicture()
```


بيانات الصورة.

**Returns:**
byte[]
### getPicturePosition() {#getPicturePosition--}
```
public int getPicturePosition()
```


موقع صورة التحكم بالنسبة إلى التسمية التوضيحية.

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


التأثير الخاص للعنصر.

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
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


يشير إلى ما إذا كان محتوى التحكم يلتف تلقائيًا في نهاية السطر.

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




### setAccelerator(char value) {#setAccelerator-char-}
```
public void setAccelerator(char value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAccelerator()](../../com.aspose.diagram/labelactivexcontrol\#getAccelerator--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | char |  |

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

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBorderOleColor()](../../com.aspose.diagram/labelactivexcontrol\#getBorderOleColor--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBorderStyle()](../../com.aspose.diagram/labelactivexcontrol\#getBorderStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setCaption(String value) {#setCaption-java.lang.String-}
```
public void setCaption(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCaption()](../../com.aspose.diagram/labelactivexcontrol\#getCaption--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

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

### setPicture(byte[] value) {#setPicture-byte---}
```
public void setPicture(byte[] value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPicture()](../../com.aspose.diagram/labelactivexcontrol\#getPicture--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte[] |  |

### setPicturePosition(int value) {#setPicturePosition-int-}
```
public void setPicturePosition(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPicturePosition()](../../com.aspose.diagram/labelactivexcontrol\#getPicturePosition--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpecialEffect()](../../com.aspose.diagram/labelactivexcontrol\#getSpecialEffect--)

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

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isWordWrapped()](../../com.aspose.diagram/labelactivexcontrol\#isWordWrapped--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

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

