---
title: ForeignData
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على كائن BLOB مشفر بتقنية MIME Multipurpose Internet Mail Extensions لبيانات الصورة مثل صورة Windows metafile bitmap أو بيانات OLE.
type: docs
weight: 164
url: /ar/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

يحتوي على BLOB مشفر بتنسيق MIME (Multipurpose Internet Mail Extensions) لبيانات الصورة، مثل ملف ميتافايل Windows أو bitmap أو بيانات OLE.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | هذه السمة لا تكون ذات معنى إلا إذا كانت البيانات الخارجية كائنًا خارجيًا قائمًا على البكسل، مثل ملف DIB أو JPG أو PNG أو TIFF أو GIF. |
| [getCompressionType()](#getCompressionType--) | هذه السمة لا تكون ذات معنى إلا إذا كانت البيانات الخارجية كائنًا خارجيًا قائمًا على البكسل، مثل ملف DIB أو JPG أو PNG أو TIFF أو GIF. |
| [getExtentX()](#getExtentX--) | هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية ملف ميتافايل. |
| [getExtentY()](#getExtentY--) | هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية ملف ميتافايل. |
| [getForeignType()](#getForeignType--) | نوع البيانات. |
| [getImageData()](#getImageData--) | يمثل صورة كائن OLE كمصفوفة بايت. |
| [getMappingMode()](#getMappingMode--) | هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية ملف ميتافايل. |
| [getObjectData()](#getObjectData--) | يمثل بيانات كائن OLE المضمنة كمصفوفة بايت. |
| [getObjectHeight()](#getObjectHeight--) | هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية كائنًا مضمنًا من نوع OLE2. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | يعيد الاسم الكامل للمصدر لملف المصدر الخاص بالكائن OLE المرتبط. |
| [getObjectType()](#getObjectType--) | إذا كان سمة ForeignType هي \"Object\"، يجب أن يحتوي عنصر ForeignData أيضًا على سمة ObjectType. |
| [getObjectWidth()](#getObjectWidth--) | هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية كائنًا مضمنًا من نوع OLE2. |
| [getShowAsIcon()](#getShowAsIcon--) | هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية كائنًا مضمنًا من نوع OLE2. |
| [getValue()](#getValue--) | يحتوي على BLOB مشفر بتنسيق MIME (Multipurpose Internet Mail Extensions) لبيانات الصورة، مثل ملف ميتافايل Windows أو bitmap أو بيانات OLE. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCompressionLevel()](../../com.aspose.diagram/foreigndata\\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCompressionType()](../../com.aspose.diagram/foreigndata\\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExtentX()](../../com.aspose.diagram/foreigndata\\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExtentY()](../../com.aspose.diagram/foreigndata\\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getForeignType()](../../com.aspose.diagram/foreigndata\\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getImageData()](../../com.aspose.diagram/foreigndata\\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMappingMode()](../../com.aspose.diagram/foreigndata\\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getObjectData()](../../com.aspose.diagram/foreigndata\\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getObjectHeight()](../../com.aspose.diagram/foreigndata\\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getObjectType()](../../com.aspose.diagram/foreigndata\\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getObjectWidth()](../../com.aspose.diagram/foreigndata\\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShowAsIcon()](../../com.aspose.diagram/foreigndata\\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getValue()](../../com.aspose.diagram/foreigndata\\#getValue--) |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionLevel() {#getCompressionLevel--}
```
public double getCompressionLevel()
```


هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية كائنًا أجنبيًا قائمًا على البكسل، مثل ملف DIB أو JPG أو PNG أو TIFF أو GIF. القيمة تشير إلى مستوى الضغط المطبق على الملف. يتم قياس مستوى الضغط بمئات النسبة المئوية.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية كائنًا أجنبيًا قائمًا على البكسل، مثل ملف DIB أو JPG أو PNG أو TIFF أو GIF. القيمة تشير إلى نوع الضغط المطبق على الملف.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية ملفًا تعريفًا (metafile). القيمة تشير إلى الامتداد الأفقي للملف التعريفي.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية ملفًا تعريفًا (metafile). القيمة تشير إلى الامتداد العمودي للملف التعريفي.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


نوع البيانات.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


يمثل صورة كائن OLE كمصفوفة بايت.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية ملفًا تعريفًا (metafile). القيمة تشير إلى وضعية رسم الملف التعريفي.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


يمثل بيانات كائن OLE المضمنة كمصفوفة بايت.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية كائنًا مضمنًا من نوع OLE2. القيمة تمثل ارتفاع الكائن بوحدات الصفحة.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


يعيد الاسم الكامل للمصدر لملف المصدر الخاص بالكائن OLE المرتبط. يدعم تعيين الاسم الكامل للمصدر فقط عندما يكون نوع الملف OleFileType.Unknown. مثل ملفات wav أو avi.. إلخ..

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


إذا كان سمة ForeignType هي \"Object\"، يجب أن يحتوي عنصر ForeignData أيضًا على سمة ObjectType.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية كائنًا مضمنًا من نوع OLE2. القيمة تمثل عرض الكائن بوحدات الصفحة.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


هذه الخاصية ذات معنى فقط إذا كانت البيانات الأجنبية كائنًا مضمنًا من نوع OLE2.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


يحتوي على BLOB مشفر بتنسيق MIME (Multipurpose Internet Mail Extensions) لبيانات الصورة، مثل ملف ميتافايل Windows أو bitmap أو بيانات OLE.

**Returns:**
byte[]
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




### setCompressionLevel(double value) {#setCompressionLevel-double-}
```
public void setCompressionLevel(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCompressionLevel()](../../com.aspose.diagram/foreigndata\\#getCompressionLevel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCompressionType()](../../com.aspose.diagram/foreigndata\\#getCompressionType--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExtentX()](../../com.aspose.diagram/foreigndata\\#getExtentX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExtentY()](../../com.aspose.diagram/foreigndata\\#getExtentY--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getForeignType()](../../com.aspose.diagram/foreigndata\\#getForeignType--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getImageData()](../../com.aspose.diagram/foreigndata\\#getImageData--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMappingMode()](../../com.aspose.diagram/foreigndata\\#getMappingMode--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getObjectData()](../../com.aspose.diagram/foreigndata\\#getObjectData--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getObjectHeight()](../../com.aspose.diagram/foreigndata\\#getObjectHeight--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\\#getObjectSourceFullName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getObjectType()](../../com.aspose.diagram/foreigndata\\#getObjectType--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getObjectWidth()](../../com.aspose.diagram/foreigndata\\#getObjectWidth--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShowAsIcon()](../../com.aspose.diagram/foreigndata\\#getShowAsIcon--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getValue()](../../com.aspose.diagram/foreigndata\\#getValue--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte[] |  |

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

