---
title: صورة
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على قيم الجاما والسطوع والتباين والطمس والحدّة وإزالة الضوضاء والشفافية لملف bitmap.
type: docs
weight: 196
url: /ar/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

يحتوي على قيم الجاما، السطوع، التباين، الضبابية، الشحذ، إزالة الضوضاء، والشفافية لملف bitmap.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | يموّج أو ينعّم صورة bitmap. |
| [getBrightness()](#getBrightness--) | يضبط سطوع صورة bitmap. |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | يحدد تباين صورة bitmap. |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getDenoise()](#getDenoise--) | يزيل الضوضاء (البكسلات التي لها مستويات ألوان موزعة عشوائياً) من صورة bitmap. |
| [getGamma()](#getGamma--) | يضبط أو يصحح شدة الصورة لجهاز إخراج معين، مثل الشاشة أو الماسح الضوئي. |
| [getSharpen()](#getSharpen--) | يحدد مقدار حدة صورة bitmap. |
| [getTransparency()](#getTransparency--) | يحدد مستوى الشفافية للون الطبقة، من 0 (معتم) إلى 1 (شفاف تماماً). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/image\#getDel--) |
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
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


يموّج أو ينعّم صورة bitmap. يحتوي عنصر Blur على قيمة بين 0 و 1؛ القيمة الافتراضية هي 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


يضبط سطوع صورة bitmap. يحتوي عنصر Brightness على قيمة بين 0 و 1؛ القيمة الافتراضية هي 0.5.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public DoubleValue getContrast()
```


يحدد تباين صورة bitmap. يحتوي عنصر Contrast على قيمة بين 0 و 1.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


يزيل الضوضاء (البكسلات التي لها مستويات ألوان موزعة عشوائياً) من صورة bitmap.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


يضبط أو يصحح شدة الصورة لجهاز إخراج معين، مثل الشاشة أو الماسح الضوئي. القيمة الافتراضية هي 1 (بدون تصحيح).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


يحدد مقدار حدة صورة bitmap. يركز حدة الصورة بزيادة تباين البكسلات المتجاورة.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


يحدد مستوى الشفافية للون الطبقة، من 0 (معتم) إلى 1 (شفاف تماماً).

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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/image\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

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

