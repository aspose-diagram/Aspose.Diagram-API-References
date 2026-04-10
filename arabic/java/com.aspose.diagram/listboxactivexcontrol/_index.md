---
title: ListBoxActiveXControl
second_title: Aspose.Diagram لـ Java API Reference
description: يمثل عنصر تحكم ListBox ActiveX.
type: docs
weight: 234
url: /ar/java/com.aspose.diagram/listboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ListBoxActiveXControl extends ActiveXControl
```

يمثل عنصر تحكم ListBox ActiveX.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | لون ole الخلفية. |
| [getBorderOleColor()](#getBorderOleColor--) | لون ole الخلفية. |
| [getBorderStyle()](#getBorderStyle--) | نوع الحدود المستخدمة في التحكم. |
| [getBoundColumn()](#getBoundColumn--) | يمثل كيفية تحديد خاصية Value لـ ComboBox أو ListBox عندما تكون قيمة خاصية MultiSelect هي (fmMultiSelectSingle). |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | يمثل عدد الأعمدة التي يتم عرضها في ComboBox أو ListBox. |
| [getColumnWidths()](#getColumnWidths--) | عرض العمود. |
| [getData()](#getData--) | البيانات الثنائية للتحكم. |
| [getForeOleColor()](#getForeOleColor--) | لون ole المقدمة. |
| [getHeight()](#getHeight--) | ارتفاع التحكم بوحدة النقاط. |
| [getIMEMode()](#getIMEMode--) | وضع التشغيل الافتراضي لمحرر طريقة الإدخال للتحكم عند استلامه للتركيز. |
| [getIntegralHeight()](#getIntegralHeight--) | يشير إلى ما إذا كان التحكم سيظهر فقط الأسطر الكاملة للنص دون إظهار أي أسطر جزئية. |
| [getListStyle()](#getListStyle--) | المظهر البصري. |
| [getListWidth()](#getListWidth--) | العرض بوحدة النقاط. |
| [getMatchEntry()](#getMatchEntry--) | يحدد كيفية بحث ListBox أو ComboBox في قائمته أثناء كتابة المستخدم. |
| [getMouseIcon()](#getMouseIcon--) | أيقونة مخصصة لعرضها كمؤشر الفأرة للعنصر. |
| [getMousePointer()](#getMousePointer--) | نوع الأيقونة المعروضة كمؤشر الفأرة للعنصر. |
| [getScrollBars()](#getScrollBars--) | يشير إلى ما إذا كان التحكم يحتوي على أشرطة تمرير عمودية أو أشرطة تمرير أفقية أو كليهما أو لا شيء. |
| [getShowColumnHeads()](#getShowColumnHeads--) | يحدد ما إذا كانت عناوين الأعمدة معروضة. |
| [getSpecialEffect()](#getSpecialEffect--) | التأثير الخاص للعنصر. |
| [getTextColumn()](#getTextColumn--) | يمثل العمود في ComboBox أو ListBox الذي يتم عرضه للمستخدم. |
| [getType()](#getType--) | يحصل على نوع عنصر ActiveX. |
| [getValue()](#getValue--) | قيمة العنصر. |
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
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--) |
| [setBoundColumn(int value)](#setBoundColumn-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--) |
| [setColumnCount(int value)](#setColumnCount-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--) |
| [setColumnWidths(double value)](#setColumnWidths-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--) |
| [setListStyle(int value)](#setListStyle-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--) |
| [setListWidth(double value)](#setListWidth-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--) |
| [setLocked(boolean value)](#setLocked-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMatchEntry(int value)](#setMatchEntry-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setScrollBars(int value)](#setScrollBars-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--) |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--) |
| [setTextColumn(int value)](#setTextColumn-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setValue(String value)](#setValue-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--) |
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
### getBoundColumn() {#getBoundColumn--}
```
public int getBoundColumn()
```


يمثل كيفية تحديد خاصية Value لـ ComboBox أو ListBox عندما تكون قيمة خاصية MultiSelect هي (fmMultiSelectSingle).

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnCount() {#getColumnCount--}
```
public int getColumnCount()
```


يمثل عدد الأعمدة التي يتم عرضها في ComboBox أو ListBox.

**Returns:**
int
### getColumnWidths() {#getColumnWidths--}
```
public double getColumnWidths()
```


عرض العمود.

**Returns:**
double
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
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


يشير إلى ما إذا كان التحكم سيظهر فقط الأسطر الكاملة للنص دون إظهار أي أسطر جزئية.

**Returns:**
منطقي
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


المظهر البصري.

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


العرض بوحدة النقاط.

**Returns:**
double
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


يحدد كيفية بحث ListBox أو ComboBox في قائمته أثناء كتابة المستخدم.

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
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


يشير إلى ما إذا كان التحكم يحتوي على أشرطة تمرير عمودية أو أشرطة تمرير أفقية أو كليهما أو لا شيء.

**Returns:**
int
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


يحدد ما إذا كانت عناوين الأعمدة معروضة.

**Returns:**
منطقي
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


التأثير الخاص للعنصر.

**Returns:**
int
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


يمثل العمود في ComboBox أو ListBox الذي يتم عرضه للمستخدم.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


يحصل على نوع عنصر ActiveX.

**Returns:**
int
### getValue() {#getValue--}
```
public String getValue()
```


قيمة العنصر.

**Returns:**
java.lang.String
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

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getBoundColumn--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnCount--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\#getColumnWidths--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

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

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\#getIntegralHeight--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--)

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

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--)

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

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

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

