---
title: ConValue
second_title: Aspose.Diagram for Java API 참조
description: 핸들을 이동한 후 컨트롤 핸들의 x 또는 y 좌표가 나타내는 동작 유형을 지정합니다.
type: docs
weight: 74
url: /ko/java/com.aspose.diagram/convalue/
---

**Inheritance:**
java.lang.Object
```
public final class ConValue
```

핸들을 이동한 후 컨트롤 핸들의 x 또는 y 좌표가 나타내는 동작 유형을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [OFFSET_FROM_CENTER](#OFFSET-FROM-CENTER) | 중심으로부터의 오프셋. |
| [OFFSET_FROM_CENTER_HIDDEN](#OFFSET-FROM-CENTER-HIDDEN) | 중심으로부터의 오프셋, 숨김. |
| [OFFSET_FROM_LEFT_EDGE](#OFFSET-FROM-LEFT-EDGE) | 왼쪽 가장자리로부터의 오프셋. |
| [OFFSET_FROM_LEFT_EDGE_HIDDEN](#OFFSET-FROM-LEFT-EDGE-HIDDEN) | 왼쪽 가장자리로부터의 오프셋, 숨김. |
| [OFFSET_FROM_RIGHT_EDGE](#OFFSET-FROM-RIGHT-EDGE) | 오른쪽 가장자리로부터의 오프셋. |
| [OFFSET_FROM_RIGHT_EDGE_HIDDEN](#OFFSET-FROM-RIGHT-EDGE-HIDDEN) | 오른쪽 가장자리에서 오프셋, 숨김. |
| [PROPORTIONAL](#PROPORTIONAL) | 비례. |
| [PROPORTIONAL_HIDDEN](#PROPORTIONAL-HIDDEN) | 비례, 숨김. 0과 동일하지만 제어 핸들이 보이지 않습니다. |
| [PROPORTIONAL_LOCKED](#PROPORTIONAL-LOCKED) | 비례 잠김. |
| [PROPORTIONAL_LOCKED_HIDDEN](#PROPORTIONAL-LOCKED-HIDDEN) | 비례 잠김, 숨김. |
| [UNDEFINED](#UNDEFINED) | 정의되지 않음. |
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
### OFFSET_FROM_CENTER {#OFFSET-FROM-CENTER}
```
public static final int OFFSET_FROM_CENTER
```


중심에서 오프셋. 제어 핸들은 도형의 중심에서 일정 거리만큼 오프셋됩니다.

### OFFSET_FROM_CENTER_HIDDEN {#OFFSET-FROM-CENTER-HIDDEN}
```
public static final int OFFSET_FROM_CENTER_HIDDEN
```


중심에서 오프셋, 숨김. 3과 동일하지만 제어 핸들이 보이지 않습니다.

### OFFSET_FROM_LEFT_EDGE {#OFFSET-FROM-LEFT-EDGE}
```
public static final int OFFSET_FROM_LEFT_EDGE
```


왼쪽 가장자리에서 오프셋. 제어 핸들은 도형의 왼쪽 측면에서 일정 거리만큼 오프셋됩니다.

### OFFSET_FROM_LEFT_EDGE_HIDDEN {#OFFSET-FROM-LEFT-EDGE-HIDDEN}
```
public static final int OFFSET_FROM_LEFT_EDGE_HIDDEN
```


왼쪽 가장자리에서 오프셋, 숨김. 2와 동일하지만 제어 핸들이 보이지 않습니다.

### OFFSET_FROM_RIGHT_EDGE {#OFFSET-FROM-RIGHT-EDGE}
```
public static final int OFFSET_FROM_RIGHT_EDGE
```


오른쪽 가장자리에서 오프셋. 제어 핸들은 도형의 오른쪽 측면에서 일정 거리만큼 오프셋됩니다.

### OFFSET_FROM_RIGHT_EDGE_HIDDEN {#OFFSET-FROM-RIGHT-EDGE-HIDDEN}
```
public static final int OFFSET_FROM_RIGHT_EDGE_HIDDEN
```


오른쪽 가장자리에서 오프셋, 숨김. 4와 동일하지만 제어 핸들이 보이지 않습니다.

### PROPORTIONAL {#PROPORTIONAL}
```
public static final int PROPORTIONAL
```


비례. 제어 핸들을 이동할 수 있으며, 도형이 늘어날 때 도형과 비례하여 움직입니다.

### PROPORTIONAL_HIDDEN {#PROPORTIONAL-HIDDEN}
```
public static final int PROPORTIONAL_HIDDEN
```


비례, 숨김. 0과 동일하지만 제어 핸들이 보이지 않습니다.

### PROPORTIONAL_LOCKED {#PROPORTIONAL-LOCKED}
```
public static final int PROPORTIONAL_LOCKED
```


비례 잠김. 제어 핸들은 도형과 비례하여 움직이지만, 제어 핸들 자체는 이동할 수 없습니다.

### PROPORTIONAL_LOCKED_HIDDEN {#PROPORTIONAL-LOCKED-HIDDEN}
```
public static final int PROPORTIONAL_LOCKED_HIDDEN
```


비례 잠김, 숨김. 1과 동일하지만 제어 핸들이 보이지 않습니다.

### UNDEFINED {#UNDEFINED}
```
public static final int UNDEFINED
```


정의되지 않음.

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

