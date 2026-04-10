---
title: 외부
second_title: Aspose.Diagram for Java API 참조
description: Microsoft Visio 문서에서 사용되는 다른 프로그램의 객체 너비와 높이를 지정하는 요소를 포함합니다.
type: docs
weight: 163
url: /ko/java/com.aspose.diagram/foreign/
---

**Inheritance:**
java.lang.Object
```
public class Foreign
```

Microsoft Visio 문서에서 사용되는 다른 프로그램의 객체의 너비와 높이를 지정하는 요소를 포함합니다. 또한 객체 이미지가 경계 내에서 오프셋되는 거리를 지정하는 요소도 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getImgHeight()](#getImgHeight--) | 객체 경계 내에서 객체 이미지의 높이를 결정합니다. |
| [getImgOffsetX()](#getImgOffsetX--) | 객체 경계 원점으로부터 객체가 수평으로 오프셋되는 거리를 결정합니다. |
| [getImgOffsetY()](#getImgOffsetY--) | 객체 경계 원점으로부터 객체가 수직으로 오프셋되는 거리를 결정합니다. |
| [getImgWidth()](#getImgWidth--) | 객체 경계 내에서 객체 이미지의 너비를 결정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/foreign\#getDel--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


이 인스턴스의 깊은 복사본을 생성합니다.

**Returns:**
java.lang.Object -
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
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getImgHeight() {#getImgHeight--}
```
public DoubleValue getImgHeight()
```


객체 경계 내 이미지의 높이를 결정합니다. 기본 수식은: F="Height\*1".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetX() {#getImgOffsetX--}
```
public DoubleValue getImgOffsetX()
```


객체 경계 원점으로부터 객체가 수평으로 오프셋되는 거리를 결정합니다. 기본값은 0이며, 기본 수식은 F="ImgWidth\*0"입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgOffsetY() {#getImgOffsetY--}
```
public DoubleValue getImgOffsetY()
```


객체 경계 원점으로부터 객체가 수직으로 오프셋되는 거리를 결정합니다. 기본값은 0이며, 기본 수식은 F="ImgHeight\*0"입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getImgWidth() {#getImgWidth--}
```
public DoubleValue getImgWidth()
```


객체 경계 내 이미지의 너비를 결정합니다. 기본 수식은: F="Width\*1".

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/foreign\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

