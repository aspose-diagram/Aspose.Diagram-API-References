---
title: InterpolationMode
second_title: Aspose.Diagram لـ Java API Reference
description: تحدد تعداد InterpolationMode الخوارزمية المستخدمة عند تكبير أو تدوير الصور.
type: docs
weight: 206
url: /ar/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

تحدد تعداد InterpolationMode الخوارزمية المستخدمة عند تكبير أو تدوير الصور.
## الحقول

| حقل | الوصف |
| --- | --- |
| [BICUBIC](#BICUBIC) | يحدد الاستيفاء البيكوبك. |
| [BILINEAR](#BILINEAR) | يحدد الاستيفاء الثنائي الخطّي. |
| [DEFAULT](#DEFAULT) | يحدد الوضع الافتراضي. |
| [HIGH](#HIGH) | يحدد استيفاء عالي الجودة. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | يحدد استيفاء عالي الجودة، بيكوبك. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | يحدد استيفاء عالي الجودة، ثنائي الخطّي. |
| [INVALID](#INVALID) | ما يعادل العنصر Invalid في تعداد QualityMode. |
| [LOW](#LOW) | يحدد استيفاء منخفض الجودة. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | يحدد استيفاء أقرب جار. |
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
### BICUBIC {#BICUBIC}
```
public static final int BICUBIC
```


يحدد استيفاء بيكوبك. لا يتم إجراء ما قبل الترشيح. هذا الوضع غير مناسب لتصغير صورة إلى أقل من 25٪ من حجمها الأصلي.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


يحدد استيفاء ثنائي الخطّي. لا يتم إجراء ما قبل الترشيح. هذا الوضع غير مناسب لتصغير صورة إلى أقل من 50٪ من حجمها الأصلي.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


يحدد الوضع الافتراضي.

### HIGH {#HIGH}
```
public static final int HIGH
```


يحدد استيفاء عالي الجودة.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


يحدد استيفاء عالي الجودة، بيكوبك. يتم إجراء ما قبل الترشيح لضمان تصغير عالي الجودة. هذا الوضع ينتج أعلى جودة للصور المحوَّلة.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


يحدد استيفاء عالي الجودة، ثنائي الخطّي. يتم إجراء ما قبل الترشيح لضمان تصغير عالي الجودة.

### INVALID {#INVALID}
```
public static final int INVALID
```


ما يعادل العنصر Invalid في تعداد QualityMode.

### LOW {#LOW}
```
public static final int LOW
```


يحدد استيفاء منخفض الجودة.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


يحدد استيفاء أقرب جار.

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

