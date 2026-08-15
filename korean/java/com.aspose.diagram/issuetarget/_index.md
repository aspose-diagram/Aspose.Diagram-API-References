---
title: IssueTarget
second_title: Aspose.Diagram for Java API 참조
description: 부모 검증 문제의 대상에 따라 해당 문제와 연관된 페이지 또는 페이지와 도형 모두를 지정합니다.
type: docs
weight: 210
url: /ko/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

부모 검증 문제의 대상에 따라 해당 문제와 연관된 페이지 또는 페이지와 도형 모두를 지정합니다. 부모 검증 문제의 대상이 문서인 경우, IssueTarget은 페이지도 도형도 지정하지 않습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | 부모 검증 문제와 연관된 페이지의 고유 식별자를 지정합니다. |
| [getShapeId()](#getShapeId--) | 부모 검증 문제와 연관된 도형의 고유 식별자를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | 이 속성에 대한 설명은 [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)을(를) 참조하십시오. |
| [setShapeId(long value)](#setShapeId-long-) | 이 속성에 대한 설명은 [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IssueTarget(long pageID, long shapeID) {#IssueTarget-long-long-}
```
public IssueTarget(long pageID, long shapeID)
```


생성자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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
### getPageId() {#getPageId--}
```
public long getPageId()
```


부모 검증 문제와 연관된 페이지의 고유 식별자를 지정합니다. 대상이 문서인 경우, PageID 값은 0xFFFFFFFF가 될 수 있습니다.

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


부모 검증 문제와 연관된 도형의 고유 식별자를 지정합니다. 대상이 문서이거나 페이지인 경우, ShapeID 값은 0xFFFFFFFF가 될 수 있습니다.

**Returns:**
long
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




### setPageId(long value) {#setPageId-long-}
```
public void setPageId(long value)
```


이 속성에 대한 설명은 [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


이 속성에 대한 설명은 [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

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

