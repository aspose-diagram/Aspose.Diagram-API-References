---
title: 주석
second_title: Aspose.Diagram for Java API 참조
description: 문서 페이지에 삽입된 주석에 대한 정보를 포함하는 요소를 포함합니다.
type: docs
weight: 20
url: /ko/java/com.aspose.diagram/annotation/
---

**Inheritance:**
java.lang.Object
```
public class Annotation
```

문서 페이지에 삽입된 주석에 대한 정보를 포함하는 요소를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | 도형에 대한 주석 텍스트를 문자열 형식으로 포함합니다. |
| [getDate()](#getDate--) | 주석이 생성된 시점을 지정합니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getEditDate()](#getEditDate--) | 주석이 마지막으로 변경된 시점을 지정합니다. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getLangID()](#getLangID--) | 셀 수식, 텍스트, 사용자 정의 속성 또는 주석이 입력된 언어의 로케일 ID(LCID)를 나타냅니다. |
| [getMarkerIndex()](#getMarkerIndex--) | 주석 마커에 할당된 인덱스 번호를 지정합니다. |
| [getReviewerID()](#getReviewerID--) | 문서에 마크업을 추가하는 검토자의 ID 번호를 포함합니다. |
| [getShapeID()](#getShapeID--) | 주석의 도형 ID. |
| [getX()](#getX--) | 페이지 좌표계에서 주석 마커의 x좌표. |
| [getY()](#getY--) | 페이지 좌표계에서 주석 마커의 y좌표. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/annotation\#getDel--)을 참조하십시오. |
| [setIX(int value)](#setIX-int-) | 이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/annotation\#getIX--)을 참조하십시오. |
| [setShapeID(int value)](#setShapeID-int-) | 이 속성에 대한 설명은 [getShapeID()](../../com.aspose.diagram/annotation\#getShapeID--)을 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getComment() {#getComment--}
```
public Str2Value getComment()
```


도형에 대한 주석 텍스트를 문자열 형식으로 포함합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDate() {#getDate--}
```
public DateValue getDate()
```


주석이 생성된 시점을 지정합니다.

**Returns:**
[DateValue](../../com.aspose.diagram/datevalue)
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getEditDate() {#getEditDate--}
```
public DateValue getEditDate()
```


주석이 마지막으로 변경된 시점을 지정합니다.

**Returns:**
[DateValue](../../com.aspose.diagram/datevalue)
### getIX() {#getIX--}
```
public int getIX()
```


부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스.

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


셀 수식, 텍스트, 사용자 정의 속성 또는 주석이 입력된 언어의 로케일 ID(LCID)를 나타냅니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getMarkerIndex() {#getMarkerIndex--}
```
public IntValue getMarkerIndex()
```


주석 마커에 할당된 인덱스 번호를 지정합니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getReviewerID() {#getReviewerID--}
```
public IntValue getReviewerID()
```


문서에 마크업을 추가하는 검토자의 ID 번호를 포함합니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getShapeID() {#getShapeID--}
```
public int getShapeID()
```


주석의 도형 ID.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


페이지 좌표계에서 주석 마커의 x좌표.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


페이지 좌표계에서 주석 마커의 y좌표.

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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/annotation\#getDel--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/annotation\#getIX--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShapeID(int value) {#setShapeID-int-}
```
public void setShapeID(int value)
```


이 속성에 대한 설명은 [getShapeID()](../../com.aspose.diagram/annotation\#getShapeID--)을 참조하십시오.

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

