---
title: 이벤트
second_title: Aspose.Diagram for Java API 참조
description: 도형 이벤트를 제어하는 수식을 지정하는 요소를 포함합니다.
type: docs
weight: 144
url: /ko/java/com.aspose.diagram/event/
---

**Inheritance:**
java.lang.Object
```
public class Event
```

도형 이벤트를 제어하는 수식을 지정하는 요소를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getEventDblClick()](#getEventDblClick--) | 도형을 더블 클릭할 때 평가되는 이벤트 요소입니다. |
| [getEventDrop()](#getEventDrop--) | 도형이 인스턴스로 또는 복제·붙여넣기된 형태로 그리기 페이지에 놓일 때 평가되는 이벤트 요소입니다. |
| [getEventMultiDrop()](#getEventMultiDrop--) | EventMultiDrop. |
| [getEventXFMod()](#getEventXFMod--) | 도형의 페이지 상 위치 또는 방향이 변환될 때 평가되는 이벤트 요소입니다. |
| [getTheData()](#getTheData--) | 향후 사용을 위해 예약되었습니다. |
| [getTheText()](#getTheText--) | 도형의 텍스트 또는 텍스트 구성이 변경될 때 평가되는 이벤트 요소입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/event\#getDel--)을 참조하십시오. |
| [setEventDblClick(DoubleValue value)](#setEventDblClick-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getEventDblClick()](../../com.aspose.diagram/event\#getEventDblClick--)을 참조하십시오. |
| [setEventDrop(DoubleValue value)](#setEventDrop-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getEventDrop()](../../com.aspose.diagram/event\#getEventDrop--)을 참조하십시오. |
| [setEventMultiDrop(DoubleValue value)](#setEventMultiDrop-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getEventMultiDrop()](../../com.aspose.diagram/event\#getEventMultiDrop--)을 참조하십시오. |
| [setEventXFMod(DoubleValue value)](#setEventXFMod-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getEventXFMod()](../../com.aspose.diagram/event\#getEventXFMod--)을 참조하십시오. |
| [setTheData(DoubleValue value)](#setTheData-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getTheData()](../../com.aspose.diagram/event\#getTheData--)을 참조하십시오. |
| [setTheText(DoubleValue value)](#setTheText-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getTheText()](../../com.aspose.diagram/event\#getTheText--)을 참조하십시오. |
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
### getEventDblClick() {#getEventDblClick--}
```
public DoubleValue getEventDblClick()
```


도형을 더블 클릭할 때 평가되는 이벤트 요소입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getEventDrop() {#getEventDrop--}
```
public DoubleValue getEventDrop()
```


도형이 인스턴스로 또는 복제·붙여넣기된 형태로 그리기 페이지에 놓일 때 평가되는 이벤트 요소입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getEventMultiDrop() {#getEventMultiDrop--}
```
public DoubleValue getEventMultiDrop()
```


EventMultiDrop.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getEventXFMod() {#getEventXFMod--}
```
public DoubleValue getEventXFMod()
```


도형의 페이지 상 위치 또는 방향이 변환될 때 평가되는 이벤트 요소입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTheData() {#getTheData--}
```
public DoubleValue getTheData()
```


향후 사용을 위해 예약되었습니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTheText() {#getTheText--}
```
public DoubleValue getTheText()
```


도형의 텍스트 또는 텍스트 구성이 변경될 때 평가되는 이벤트 요소입니다.

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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/event\#getDel--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEventDblClick(DoubleValue value) {#setEventDblClick-com.aspose.diagram.DoubleValue-}
```
public void setEventDblClick(DoubleValue value)
```


이 속성에 대한 설명은 [getEventDblClick()](../../com.aspose.diagram/event\#getEventDblClick--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setEventDrop(DoubleValue value) {#setEventDrop-com.aspose.diagram.DoubleValue-}
```
public void setEventDrop(DoubleValue value)
```


이 속성에 대한 설명은 [getEventDrop()](../../com.aspose.diagram/event\#getEventDrop--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setEventMultiDrop(DoubleValue value) {#setEventMultiDrop-com.aspose.diagram.DoubleValue-}
```
public void setEventMultiDrop(DoubleValue value)
```


이 속성에 대한 설명은 [getEventMultiDrop()](../../com.aspose.diagram/event\#getEventMultiDrop--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setEventXFMod(DoubleValue value) {#setEventXFMod-com.aspose.diagram.DoubleValue-}
```
public void setEventXFMod(DoubleValue value)
```


이 속성에 대한 설명은 [getEventXFMod()](../../com.aspose.diagram/event\#getEventXFMod--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTheData(DoubleValue value) {#setTheData-com.aspose.diagram.DoubleValue-}
```
public void setTheData(DoubleValue value)
```


이 속성에 대한 설명은 [getTheData()](../../com.aspose.diagram/event\#getTheData--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTheText(DoubleValue value) {#setTheText-com.aspose.diagram.DoubleValue-}
```
public void setTheText(DoubleValue value)
```


이 속성에 대한 설명은 [getTheText()](../../com.aspose.diagram/event\#getTheText--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

