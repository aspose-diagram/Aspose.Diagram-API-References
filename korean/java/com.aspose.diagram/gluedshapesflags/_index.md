---
title: GluedShapesFlags
second_title: Aspose.Diagram for Java API 참조
description: Specifies constants that identify which shapes to return based on the dimensionality and directionality of the connection points that are glued to a particular shape passed to the Shape.GluedShapes method.
type: docs
weight: 176
url: /ko/java/com.aspose.diagram/gluedshapesflags/
---

**Inheritance:**
java.lang.Object
```
public final class GluedShapesFlags
```

특정 도형에 접착된 연결 지점의 차원 및 방향성을 기반으로 반환할 도형을 식별하는 상수를 지정합니다; Shape.GluedShapes 메서드에 전달됩니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [GLUED_SHAPES_ALL_1_D](#GLUED-SHAPES-ALL-1-D) | Return IDs of all 1-D shapes that are glued to this shape. |
| [GLUED_SHAPES_ALL_2_D](#GLUED-SHAPES-ALL-2-D) | Return all 2-D shapes that are glued to this shape and all 2-D shapes to which this shape is glued. |
| [GLUED_SHAPES_INCOMING_1_D](#GLUED-SHAPES-INCOMING-1-D) | Return IDs of 1-D shapes whose end points are glued to this shape. |
| [GLUED_SHAPES_INCOMING_2_D](#GLUED-SHAPES-INCOMING-2-D) | If the source object is a 1-D shape, return IDs of 2-D shape to which the begin point is glued. |
| [GLUED_SHAPES_OUTGOING_1_D](#GLUED-SHAPES-OUTGOING-1-D) | 이 도형에 시작점이 붙어 있는 1-D 도형들의 ID를 반환합니다. |
| [GLUED_SHAPES_OUTGOING_2_D](#GLUED-SHAPES-OUTGOING-2-D) | 소스 객체가 1-D 도형인 경우, 끝점이 붙어 있는 2-D 도형의 ID를 반환합니다. |
## 메서드

| 메서드 | 설명 |
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


소스 객체가 1-D 도형인 경우, 시작점이 붙어 있는 2-D 도형의 ID를 반환합니다. 소스 객체가 2-D 도형인 경우, 이 도형에 붙어 있는 2-D 도형들의 ID를 반환합니다.

### GLUED_SHAPES_OUTGOING_1_D {#GLUED-SHAPES-OUTGOING-1-D}
```
public static final int GLUED_SHAPES_OUTGOING_1_D
```


이 도형에 시작점이 붙어 있는 1-D 도형들의 ID를 반환합니다.

### GLUED_SHAPES_OUTGOING_2_D {#GLUED-SHAPES-OUTGOING-2-D}
```
public static final int GLUED_SHAPES_OUTGOING_2_D
```


소스 객체가 1-D 도형인 경우, 끝점이 붙어 있는 2-D 도형의 ID를 반환합니다. 소스 객체가 2-D 도형인 경우, 이 도형에 붙어 있는 2-D 도형들의 ID를 반환합니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

