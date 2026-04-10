---
title: InterpolationMode
second_title: Aspose.Diagram for Java API 참조
description: InterpolationMode 열거형은 이미지가 확대되거나 회전될 때 사용되는 알고리즘을 지정합니다.
type: docs
weight: 206
url: /ko/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

InterpolationMode 열거형은 이미지가 확대되거나 회전될 때 사용되는 알고리즘을 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [BICUBIC](#BICUBIC) | 양입방 보간을 지정합니다. |
| [BILINEAR](#BILINEAR) | 양선형 보간을 지정합니다. |
| [DEFAULT](#DEFAULT) | 기본 모드를 지정합니다. |
| [HIGH](#HIGH) | 고품질 보간을 지정합니다. |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | 고품질 양입방 보간을 지정합니다. |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | 고품질 양선형 보간을 지정합니다. |
| [INVALID](#INVALID) | QualityMode 열거형의 Invalid 요소와 동일합니다. |
| [LOW](#LOW) | 저품질 보간을 지정합니다. |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | 최근접 이웃 보간을 지정합니다. |
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
### BICUBIC {#BICUBIC}
```
public static final int BICUBIC
```


양입방 보간을 지정합니다. 사전 필터링이 수행되지 않습니다. 이 모드는 이미지 크기를 원본 크기의 25% 이하로 축소하는 데 적합하지 않습니다.

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


양선형 보간을 지정합니다. 사전 필터링이 수행되지 않습니다. 이 모드는 이미지 크기를 원본 크기의 50% 이하로 축소하는 데 적합하지 않습니다.

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


기본 모드를 지정합니다.

### HIGH {#HIGH}
```
public static final int HIGH
```


고품질 보간을 지정합니다.

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


고품질 양입방 보간을 지정합니다. 고품질 축소를 보장하기 위해 사전 필터링이 수행됩니다. 이 모드는 가장 높은 품질의 변환된 이미지를 생성합니다.

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


고품질 양선형 보간을 지정합니다. 고품질 축소를 보장하기 위해 사전 필터링이 수행됩니다.

### INVALID {#INVALID}
```
public static final int INVALID
```


QualityMode 열거형의 Invalid 요소와 동일합니다.

### LOW {#LOW}
```
public static final int LOW
```


저품질 보간을 지정합니다.

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


최근접 이웃 보간을 지정합니다.

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

