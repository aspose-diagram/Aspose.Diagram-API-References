---
title: ImageActiveXControl
second_title: Aspose.Diagram لـ Java API Reference
description: يمثل عنصر التحكم في الصورة.
type: docs
weight: 197
url: /ar/java/com.aspose.diagram/imageactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ImageActiveXControl extends ActiveXControl
```

يمثل عنصر التحكم في الصورة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | لون ole الخلفية. |
| [getBorderOleColor()](#getBorderOleColor--) | لون ole الخلفية. |
| [getBorderStyle()](#getBorderStyle--) | نوع الحدود المستخدمة في التحكم. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | البيانات الثنائية للتحكم. |
| [getForeOleColor()](#getForeOleColor--) | لون ole المقدمة. |
| [getHeight()](#getHeight--) | ارتفاع التحكم بوحدة النقاط. |
| [getIMEMode()](#getIMEMode--) | وضع التشغيل الافتراضي لمحرر طريقة الإدخال للتحكم عند استلامه للتركيز. |
| [getMouseIcon()](#getMouseIcon--) | أيقونة مخصصة لعرضها كمؤشر الفأرة للعنصر. |
| [getMousePointer()](#getMousePointer--) | نوع الأيقونة المعروضة كمؤشر الفأرة للعنصر. |
| [getPicture()](#getPicture--) | بيانات الصورة. |
| [getPictureAlignment()](#getPictureAlignment--) | محاذاة الصورة داخل النموذج أو الصورة. |
| [getPictureSizeMode()](#getPictureSizeMode--) | كيفية عرض الصورة. |
| [getSpecialEffect()](#getSpecialEffect--) | التأثير الخاص للعنصر. |
| [getType()](#getType--) | يحصل على نوع عنصر ActiveX. |
| [getWidth()](#getWidth--) | عرض العنصر بوحدة النقطة. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | يحدد ما إذا كان العنصر سيعيد حجمه تلقائيًا لعرض محتوياته بالكامل. |
| [isEnabled()](#isEnabled--) | يحدد ما إذا كان العنصر يمكنه استلام التركيز والاستجابة للأحداث التي يولدها المستخدم. |
| [isLocked()](#isLocked--) | يحدد ما إذا كانت البيانات في العنصر مقفلة للتعديل. |
| [isTiled()](#isTiled--) | يشير إلى ما إذا كانت الصورة مكررة عبر الخلفية. |
| [isTransparent()](#isTransparent--) | يحدد ما إذا كان العنصر شفافًا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | لوصف هذه الخاصية، يرجى الاطلاع على [isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\#getBorderStyle--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | لوصف هذه الخاصية، يرجى الاطلاع على [getPicture()](../../com.aspose.diagram/imageactivexcontrol\#getPicture--) |
| [setPictureAlignment(int value)](#setPictureAlignment-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--) |
| [setPictureSizeMode(int value)](#setPictureSizeMode-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--) |
| [setTiled(boolean value)](#setTiled-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--) |
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
### getPictureAlignment() {#getPictureAlignment--}
```
public int getPictureAlignment()
```


محاذاة الصورة داخل النموذج أو الصورة.

**Returns:**
int
### getPictureSizeMode() {#getPictureSizeMode--}
```
public int getPictureSizeMode()
```


كيفية عرض الصورة.

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
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


يشير إلى ما إذا كانت الصورة مكررة عبر الخلفية.

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


لوصف هذه الخاصية، يرجى الاطلاع على [isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\#isAutoSize--)

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


لوصف هذه الخاصية، يرجى الاطلاع على [getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\#getBorderOleColor--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\#getBorderStyle--)

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


لوصف هذه الخاصية، يرجى الاطلاع على [getPicture()](../../com.aspose.diagram/imageactivexcontrol\#getPicture--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte[] |  |

### setPictureAlignment(int value) {#setPictureAlignment-int-}
```
public void setPictureAlignment(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPictureSizeMode(int value) {#setPictureSizeMode-int-}
```
public void setPictureSizeMode(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setTiled(boolean value) {#setTiled-boolean-}
```
public void setTiled(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

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

