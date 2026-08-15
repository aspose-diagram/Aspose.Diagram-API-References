---
title: PdfPermissions
second_title: Aspose.Diagram لـ Java API Reference
description: يحدد أذونات المستخدم لمستند PDF.
type: docs
weight: 280
url: /ar/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

يحدد أذونات المستخدم لمستند PDF.
## الحقول

| حقل | الوصف |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | يسمح بجميع العمليات على مستند PDF. |
| [CONTENT_COPY](#CONTENT-COPY) | يسمح بنسخ أو استخراج النص والرسومات من المستند، بما في ذلك الاستخراج لأغراض إمكانية الوصول. |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | يسمح باستخراج النص والرسومات لدعم إمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى. |
| [DISALLOW_ALL](#DISALLOW-ALL) | يمنع جميع العمليات على مستند PDF. |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | يسمح بتجميع المستند: إدراج، تدوير، أو حذف الصفحات وإنشاء عناصر تنقل مثل العلامات المرجعية أو صور المصغرات. |
| [FILL_IN](#FILL-IN) | يسمح بملء النماذج وتوقيع المستند. |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | يسمح بطباعة المستند بأعلى دقة ممكنة. عند استخدام تشفير RC4 40‑بت، يتم تجاهل هذا الخيار ويسمح بطباعة عالية الدقة عندما يتم ضبط Printing. |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | يسمح بإضافة أو تعديل تعليقات النص. |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | يسمح بتعديل محتويات المستند\u9225\u6a9a. |
| [PRINTING](#PRINTING) | يسمح بطباعة المستند. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


يسمح بجميع العمليات على مستند PDF.

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


يسمح بنسخ أو استخراج النص والرسومات من المستند، بما في ذلك الاستخراج لأغراض إمكانية الوصول.

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


يسمح باستخراج النص والرسومات لدعم إمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى. عند استخدام تشفير RC4 40‑بت، يتم تجاهل هذا الخيار وتُسمح إمكانية الوصول كلما تم تعيين ContentCopy.

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


يمنع جميع العمليات على مستند PDF. هذه هي القيمة الافتراضية.

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


يسمح بتجميع المستند: إدراج أو تدوير أو حذف الصفحات وإنشاء عناصر تنقل مثل العلامات المرجعية أو صور المصغرات. عند استخدام تشفير RC4 40‑بت، يتم تجاهل هذا الخيار ويُسمح بتجميع المستند كلما تم تعيين ModifyContents.

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


يسمح بملء النماذج وتوقيع المستند. عند استخدام تشفير RC4 40‑بت، يتم تجاهل هذا الخيار ويُسمح بملء النموذج كلما تم تعيين ModifyAnnotations.

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


يسمح بطباعة المستند بأعلى دقة ممكنة. عند استخدام تشفير RC4 40‑بت، يتم تجاهل هذا الخيار ويسمح بطباعة عالية الدقة عندما يتم ضبط Printing.

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


يسمح بإضافة أو تعديل تعليقات النص. عند استخدام تشفير RC4 40‑بت، يسمح هذا الخيار أيضًا بملء حقول النموذج.

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


يسمح بتعديل محتويات المستند\u9225\u6a9a.

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


يسمح بطباعة المستند.

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

