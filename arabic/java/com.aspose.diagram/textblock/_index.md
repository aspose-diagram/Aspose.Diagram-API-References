---
title: TextBlock
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تحدد هوامش المحاذاة ومواقع إيقاف التبويب الافتراضية للنص في كتلة نص الشكل.
type: docs
weight: 400
url: /ar/java/com.aspose.diagram/textblock/
---

**Inheritance:**
java.lang.Object
```
public class TextBlock
```

يحتوي على عناصر تحدد محاذاة وهوامش ومواقع إيقاف التبويب الافتراضية للنص في كتلة النص الخاصة بالشكل.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | يحدد المسافة بين الحد السفلي لكتلة النص وآخر سطر نص تحتويه. |
| [getClass()](#getClass--) |  |
| [getDefaultTabStop()](#getDefaultTabStop--) | يحدد الفاصل بين إيقافات التبويب الافتراضية في كتلة النص. |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getLeftMargin()](#getLeftMargin--) | يحدد المسافة بين الحد الأيسر لكتلة النص والنص الذي تحتويه. |
| [getRightMargin()](#getRightMargin--) | يحدد المسافة بين الحد الأيمن لكتلة النص والنص الذي تحتويه. |
| [getTextBkgnd()](#getTextBkgnd--) | يحدد لون خلفية النص لشكل. |
| [getTextBkgndTrans()](#getTextBkgndTrans--) | يحدد مستوى الشفافية للون خلفية كتلة نص الشكل، من 0 (معتم تمامًا) إلى 1 (شفاف تمامًا). |
| [getTextDirection()](#getTextDirection--) | يحدد اتجاه الأحرف في كتلة النص. |
| [getTopMargin()](#getTopMargin--) | يحدد المسافة بين الحد العلوي لكتلة النص وأول سطر نص تحتويه. |
| [getVerticalAlign()](#getVerticalAlign--) | يحدد المحاذاة العمودية للنص داخل كتلة النص. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBottomMargin(DoubleValue value)](#setBottomMargin-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--) |
| [setDefaultTabStop(DoubleValue value)](#setDefaultTabStop-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--) |
| [setDel(int value)](#setDel-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/textblock\#getDel--) |
| [setLeftMargin(DoubleValue value)](#setLeftMargin-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--) |
| [setRightMargin(DoubleValue value)](#setRightMargin-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--) |
| [setTextBkgnd(ColorValue value)](#setTextBkgnd-com.aspose.diagram.ColorValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--) |
| [setTextBkgndTrans(DoubleValue value)](#setTextBkgndTrans-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--) |
| [setTextDirection(TextDirection value)](#setTextDirection-com.aspose.diagram.TextDirection-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--) |
| [setTopMargin(DoubleValue value)](#setTopMargin-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--) |
| [setVerticalAlign(VerticalAlign value)](#setVerticalAlign-com.aspose.diagram.VerticalAlign-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBottomMargin() {#getBottomMargin--}
```
public DoubleValue getBottomMargin()
```


يحدد المسافة بين الحد السفلي لكتلة النص وآخر سطر نص تحتويه. القيمة الافتراضية هي 4 نقاط. هذه القيمة مستقلة عن مقياس الرسم. إذا تم تحجيم الرسم، يبقى الهامش السفلي كما هو.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultTabStop() {#getDefaultTabStop--}
```
public DoubleValue getDefaultTabStop()
```


يحدد الفاصل بين إيقافات التبويب الافتراضية في كتلة النص.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getLeftMargin() {#getLeftMargin--}
```
public DoubleValue getLeftMargin()
```


يحدد المسافة بين الحد الأيسر لكتلة النص والنص الذي تحتويه. هذه القيمة مستقلة عن مقياس الرسم. إذا تم تحجيم الرسم، يبقى الهامش الأيسر كما هو.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRightMargin() {#getRightMargin--}
```
public DoubleValue getRightMargin()
```


يحدد المسافة بين الحد الأيمن لكتلة النص والنص الذي تحتويه. هذه القيمة مستقلة عن مقياس الرسم. إذا تم تحجيم الرسم، يبقى الهامش الأيمن كما هو.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextBkgnd() {#getTextBkgnd--}
```
public ColorValue getTextBkgnd()
```


يحدد لون خلفية النص لشكل.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getTextBkgndTrans() {#getTextBkgndTrans--}
```
public DoubleValue getTextBkgndTrans()
```


يحدد مستوى الشفافية للون خلفية كتلة نص الشكل، من 0 (معتم تمامًا) إلى 1 (شفاف تمامًا).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextDirection() {#getTextDirection--}
```
public TextDirection getTextDirection()
```


يحدد اتجاه الأحرف في كتلة النص.

**Returns:**
[TextDirection](../../com.aspose.diagram/textdirection)
### getTopMargin() {#getTopMargin--}
```
public DoubleValue getTopMargin()
```


يحدد المسافة بين الحد العلوي لكتلة النص وأول سطر نص تحتويه.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getVerticalAlign() {#getVerticalAlign--}
```
public VerticalAlign getVerticalAlign()
```


يحدد المحاذاة العمودية للنص داخل كتلة النص.

**Returns:**
[VerticalAlign](../../com.aspose.diagram/verticalalign)
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




### setBottomMargin(DoubleValue value) {#setBottomMargin-com.aspose.diagram.DoubleValue-}
```
public void setBottomMargin(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDefaultTabStop(DoubleValue value) {#setDefaultTabStop-com.aspose.diagram.DoubleValue-}
```
public void setDefaultTabStop(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/textblock\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setLeftMargin(DoubleValue value) {#setLeftMargin-com.aspose.diagram.DoubleValue-}
```
public void setLeftMargin(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRightMargin(DoubleValue value) {#setRightMargin-com.aspose.diagram.DoubleValue-}
```
public void setRightMargin(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextBkgnd(ColorValue value) {#setTextBkgnd-com.aspose.diagram.ColorValue-}
```
public void setTextBkgnd(ColorValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setTextBkgndTrans(DoubleValue value) {#setTextBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setTextBkgndTrans(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextDirection(TextDirection value) {#setTextDirection-com.aspose.diagram.TextDirection-}
```
public void setTextDirection(TextDirection value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextDirection](../../com.aspose.diagram/textdirection) |  |

### setTopMargin(DoubleValue value) {#setTopMargin-com.aspose.diagram.DoubleValue-}
```
public void setTopMargin(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setVerticalAlign(VerticalAlign value) {#setVerticalAlign-com.aspose.diagram.VerticalAlign-}
```
public void setVerticalAlign(VerticalAlign value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [VerticalAlign](../../com.aspose.diagram/verticalalign) |  |

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

