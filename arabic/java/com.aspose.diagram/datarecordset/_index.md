---
title: DataRecordSet
second_title: Aspose.Diagram لـ Java API Reference
description: يخزن التنسيقات ويُحدّثها ويعرض البيانات المستخرجة من قاعدة بيانات في Microsoft Visio.
type: docs
weight: 113
url: /ar/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

يخزن ويُنسق ويُحدّث ويكشف البيانات المستخرجة من قاعدة بيانات في Microsoft Visio.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | يحتوي على XML يتوافق مع مخطط XML الكلاسيكي لـ ADO لمجموعة سجلات ADO ويصف البيانات في مجموعة السجلات. |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | يحدد قاعدة تقارن عمودًا في عنصر DataRecordset الأب مع عنصر بيانات شكل من آخر عملية ربط تلقائي ناجحة تم تنفيذها في واجهة المستخدم. |
| [getChecksum()](#getChecksum--) | قيمة المجموع الاختباري (checksum) التي يولدها Visio وتستند إلى خصائص مجموعة السجلات. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | سلسلة الأمر المستخدمة لاستعلام البيانات من مصدر البيانات. |
| [getConnectionID()](#getConnectionID--) | معرّف الاتصال (Connection ID) لكائن DataConnection المرتبط. |
| [getDataColumns()](#getDataColumns--) | يحتوي على جميع عناصر DataColumn في مجموعة سجلات البيانات. |
| [getID()](#getID--) | معرّف مجموعة سجلات البيانات، فريد داخل المستند. |
| [getName()](#getName--) | اسم العرض (أو "الاسم الودي") لمجموعة سجلات البيانات. |
| [getNextRowID()](#getNextRowID--) | معرّف الصف التالي المتاح في Visio. |
| [getOptions()](#getOptions--) | الخيارات التي تُطبق على مجموعة سجلات البيانات. |
| [getPrimaryKeys()](#getPrimaryKeys--) | يحدد عمودًا أو أكثر كمفتاح أساسي في مجموعة سجلات البيانات. |
| [getRefreshConflicts()](#getRefreshConflicts--) | يشير إلى صف في مجموعة سجلات البيانات مرتبط بشكِلٍ يتعارض بعد تحديث مجموعة السجلات. |
| [getRefreshInterval()](#getRefreshInterval--) | عدد المرات (بالدقائق) التي يقوم فيها Visio بتحديث مجموعة سجلات البيانات تلقائيًا. |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | ما إذا كان يجب تعطيل واجهة مستخدم تسوية البيانات. |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | ما إذا كان يجب استبدال تغييرات المستخدم لعناصر بيانات الشكل في الأشكال المرتبطة بالبيانات عند تحديث مجموعة سجلات البيانات. |
| [getReplaceLinks()](#getReplaceLinks--) | يحدد كيفية معالجة روابط بيانات الشكل عند نسخ أو قص الأشكال. 1 لاستبدال الروابط الموجودة في الشكل الهدف. 0 للحفاظ على الروابط الموجودة في الشكل الهدف. |
| [getRowMaps()](#getRowMaps--) | يربط صفًا من مجموعة سجلات البيانات بشكِل. |
| [getRowOrder()](#getRowOrder--) | ما إذا كان يجب استخدام ترتيب الصفوف في مجموعة سجلات البيانات كمفتاح أساسي. |
| [getTimeRefreshed()](#getTimeRefreshed--) | التاريخ والوقت الذي تم فيه آخر تحديث لمجموعة سجلات البيانات. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | ينفّذ سلسلة الاستعلام المرتبطة بـ DataRecordset المتصل (غير القائم على XML) ويحدّث الأشكال المرتبطة ببيانات جديدة من مصدر البيانات الذي تُرجعه الاستعلام. |
| [setADOData(String value)](#setADOData-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
```


منشئ.

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
### getADOData() {#getADOData--}
```
public String getADOData()
```


يحتوي على XML يتوافق مع مخطط XML الكلاسيكي لـ ADO لمجموعة سجلات ADO ويصف البيانات في مجموعة السجلات.

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


يحدد قاعدة تقارن عمودًا في عنصر DataRecordset الأب مع عنصر بيانات شكل من آخر عملية ربط تلقائي ناجحة تم تنفيذها في واجهة المستخدم.

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


قيمة تجميع (checksum) تم إنشاؤها بواسطة Visio، وتعتمد على خصائص مجموعة البيانات. اضبط هذه السمة على 0؛ يقوم Visio بإعادة حساب هذه القيمة أثناء التشغيل.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCommand() {#getCommand--}
```
public String getCommand()
```


سلسلة الأمر المستخدمة لاستعلام البيانات من مصدر البيانات.

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


معرف الاتصال لكائن DataConnection المرتبط. لا يوجد لهذا المعرف في مصادر البيانات XML.

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


يحتوي على جميع عناصر DataColumn في مجموعة سجلات البيانات.

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


معرّف مجموعة سجلات البيانات، فريد داخل المستند.

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


اسم العرض (أو "الاسم الودي") لمجموعة سجلات البيانات.

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


معرّف الصف التالي المتاح في Visio.

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


الخيارات التي تُطبق على مجموعة البيانات. القيم الممكنة يمكن أن تكون أي تركيبة من واحدة أو أكثر من القيم المعروضة في الجدول التالي.

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


يحدد عمودًا أو أكثر كمفتاح أساسي في مجموعة سجلات البيانات.

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


يشير إلى صف في مجموعة البيانات مرتبط بشكل يتعارض بعد تحديث مجموعة البيانات. RowID - يشير إلى صف في مجموعة البيانات مرتبط بشكل يتعارض بعد تحديث مجموعة البيانات. ShapeID - معرف الشكل (Shape ID) للشكل المتورط في التعارض. PageID - معرف الصفحة (Page ID) للشكل المتورط في التعارض.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


عدد المرات (بالدقائق) التي يقوم فيها Visio بتحديث مجموعة البيانات تلقائيًا. يجب أن تكون هذه القيمة 1 أو أكثر.

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


ما إذا كان يجب تعطيل واجهة مستخدم تسوية البيانات. True (1) لتعطيل واجهة المستخدم (UI). False (0) لتمكين الواجهة.

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


ما إذا كان يجب استبدال تغييرات المستخدم لعناصر بيانات الشكل في الأشكال المرتبطة بالبيانات عند تحديث مجموعة سجلات البيانات.

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


يحدد كيفية معالجة روابط بيانات الشكل عند نسخ أو قص الأشكال. 1 لاستبدال الروابط الموجودة في الشكل الهدف. 0 للحفاظ على الروابط الموجودة في الشكل الهدف. إذا كانت هذه السمة غير موجودة، يطلب Visio من المستخدم ما إذا كان سيستبدل الروابط عند النسخ أو القص.

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


يربط صفًا من مجموعة البيانات بشكل. RowID - معرف الصف (Row ID) الفريد داخل مجموعة البيانات. ShapeID - معرف الشكل (Shape ID) للشكل المرتبط بالبيانات في صف مجموعة البيانات المحدد بـ RowID. PageID - معرف الصفحة (Page ID) للشكل المرتبط بالبيانات في صف مجموعة البيانات المحدد بـ RowID.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


ما إذا كان سيتم استخدام ترتيب الصفوف في مجموعة البيانات كمفتاح أساسي. True (1) إذا تم تحديد معرفات الصفوف بناءً على ترتيب الصفوف. False (0) إذا تم تحديد معرفات الصفوف بناءً على القيم في عمود (أعمدة) المفتاح الأساسي لمجموعة البيانات.

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


التاريخ والوقت الذي تم فيه آخر تحديث لمجموعة سجلات البيانات.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
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




### refresh(int connectionType) {#refresh-int-}
```
public void refresh(int connectionType)
```


ينفّذ سلسلة الاستعلام المرتبطة بـ DataRecordset المتصل (غير القائم على XML) ويحدّث الأشكال المرتبطة ببيانات جديدة من مصدر البيانات الذي تُرجعه الاستعلام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| connectionType | int | نوع الموفر الذي سيُستخدم للاتصال Aspose.Diagram.Manipulation.DataConnectionType. |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

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

