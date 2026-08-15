---
title: GluedShapesFlags
second_title: Aspose.Diagram لـ Java API Reference
description: Specifies constants that identify which shapes to return based on the dimensionality and directionality of the connection points that are glued to a particular shape passed to the Shape.GluedShapes method.
type: docs
weight: 176
url: /ar/java/com.aspose.diagram/gluedshapesflags/
---

**Inheritance:**
java.lang.Object
```
public final class GluedShapesFlags
```

يحدد الثوابت التي تحدد أي الأشكال يجب إرجاعها، بناءً على البُعد والاتجاه لنقاط الاتصال الملصوقة إلى شكل معين؛ تُمرَّر إلى طريقة Shape.GluedShapes.
## الحقول

| حقل | الوصف |
| --- | --- |
| [GLUED_SHAPES_ALL_1_D](#GLUED-SHAPES-ALL-1-D) | Return IDs of all 1-D shapes that are glued to this shape. |
| [GLUED_SHAPES_ALL_2_D](#GLUED-SHAPES-ALL-2-D) | Return all 2-D shapes that are glued to this shape and all 2-D shapes to which this shape is glued. |
| [GLUED_SHAPES_INCOMING_1_D](#GLUED-SHAPES-INCOMING-1-D) | Return IDs of 1-D shapes whose end points are glued to this shape. |
| [GLUED_SHAPES_INCOMING_2_D](#GLUED-SHAPES-INCOMING-2-D) | If the source object is a 1-D shape, return IDs of 2-D shape to which the begin point is glued. |
| [GLUED_SHAPES_OUTGOING_1_D](#GLUED-SHAPES-OUTGOING-1-D) | إرجاع IDs للأشكال ذات البُعد الواحد التي تُلصق نقاط البداية بها إلى هذا الشكل. |
| [GLUED_SHAPES_OUTGOING_2_D](#GLUED-SHAPES-OUTGOING-2-D) | إذا كان الكائن المصدر شكلًا ذات‑البُعد الواحد، إرجاع IDs للشكل ذو البُعد الثنائي الذي تُلصق به نقطة النهاية. |
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
### GLUED_SHAPES_ALL_1_D {#GLUED-SHAPES-ALL-1-D}
```
public static final int GLUED_SHAPES_ALL_1_D
```


Return IDs of all 1-D shapes that are glued to this shape.

### GLUED_SHAPES_ALL_2_D {#GLUED-SHAPES-ALL-2-D}
```
public static final int GLUED_SHAPES_ALL_2_D
```


Return all 2-D shapes that are glued to this shape and all 2-D shapes to which this shape is glued.

### GLUED_SHAPES_INCOMING_1_D {#GLUED-SHAPES-INCOMING-1-D}
```
public static final int GLUED_SHAPES_INCOMING_1_D
```


Return IDs of 1-D shapes whose end points are glued to this shape.

### GLUED_SHAPES_INCOMING_2_D {#GLUED-SHAPES-INCOMING-2-D}
```
public static final int GLUED_SHAPES_INCOMING_2_D
```


إذا كان الكائن المصدر شكلًا ذات‑البُعد الواحد، إرجاع IDs للشكل ذو البُعد الثنائي الذي تُلصق به نقطة البداية. إذا كان الكائن المصدر شكلًا ذو البُعد الثنائي، إرجاع IDs للأشكال ذات البُعد الثنائي التي تُلصق بهذا الشكل.

### GLUED_SHAPES_OUTGOING_1_D {#GLUED-SHAPES-OUTGOING-1-D}
```
public static final int GLUED_SHAPES_OUTGOING_1_D
```


إرجاع IDs للأشكال ذات البُعد الواحد التي تُلصق نقاط البداية بها إلى هذا الشكل.

### GLUED_SHAPES_OUTGOING_2_D {#GLUED-SHAPES-OUTGOING-2-D}
```
public static final int GLUED_SHAPES_OUTGOING_2_D
```


إذا كان الكائن المصدر شكلًا ذات‑البُعد الواحد، إرجاع IDs للشكل ذو البُعد الثنائي الذي تُلصق به نقطة النهاية. إذا كان الكائن المصدر شكلًا ذو البُعد الثنائي، إرجاع IDs للأشكال ذات البُعد الثنائي التي يُلصق بها هذا الشكل.

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

