---
title: Reviewer
second_title: Aspose.Diagram for Java API 참조
description: 문서 검토자에 대한 식별 정보를 포함하는 요소를 포함합니다.
type: docs
weight: 330
url: /ko/java/com.aspose.diagram/reviewer/
---

**Inheritance:**
java.lang.Object
```
public class Reviewer
```

문서 검토자에 대한 식별 정보를 포함하는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Reviewer()](#Reviewer--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Color element specifies an RGB value representing the color assigned to a document reviewer's markup. |
| [getCurrentIndex()](#getCurrentIndex--) | Indicates the value of the MarkerIndex element that will be added when the current reviewer adds another comment to the document. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getInitials()](#getInitials--) | Contains the initials of a document reviewer. |
| [getName()](#getName--) | Name element specifies the name of a document reviewer. |
| [getReviewerID()](#getReviewerID--) | 문서에 마크업을 추가하는 검토자의 ID 번호를 포함합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/reviewer\#getDel--) |
| [setIX(int value)](#setIX-int-) | For the description of this property, please see [getIX()](../../com.aspose.diagram/reviewer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Reviewer() {#Reviewer--}
```
public Reviewer()
```


생성자.

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
### getColor() {#getColor--}
```
public ColorValue getColor()
```


Color element specifies an RGB value representing the color assigned to a document reviewer's markup.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getCurrentIndex() {#getCurrentIndex--}
```
public IntValue getCurrentIndex()
```


Indicates the value of the MarkerIndex element that will be added when the current reviewer adds another comment to the document.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스.

**Returns:**
int
### getInitials() {#getInitials--}
```
public Str2Value getInitials()
```


Contains the initials of a document reviewer.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getName() {#getName--}
```
public Str2Value getName()
```


Name element specifies the name of a document reviewer.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getReviewerID() {#getReviewerID--}
```
public IntValue getReviewerID()
```


문서에 마크업을 추가하는 검토자의 ID 번호를 포함합니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


For the description of this property, please see [getDel()](../../com.aspose.diagram/reviewer\#getDel--)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


For the description of this property, please see [getIX()](../../com.aspose.diagram/reviewer\#getIX--)

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

