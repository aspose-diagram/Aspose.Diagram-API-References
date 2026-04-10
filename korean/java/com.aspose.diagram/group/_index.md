---
title: Group
second_title: Aspose.Diagram for Java API 참조
description: 그룹에 도형을 추가하고 그룹의 구성원을 이동하며 그룹을 선택하는 방법을 제어하는 요소를 포함합니다.
type: docs
weight: 186
url: /ko/java/com.aspose.diagram/group/
---

**Inheritance:**
java.lang.Object
```
public class Group
```

그룹에 도형을 추가하고, 그룹 구성원을 이동하며, 그룹을 선택하는 방식을 제어하는 요소를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getDisplayMode()](#getDisplayMode--) | Group 요소에 포함될 경우, DisplayMode 요소는 그룹 도형 및 그 구성원이 어떻게 표시되는지를 지정합니다. |
| [getDontMoveChildren()](#getDontMoveChildren--) | 마우스를 사용하여 그룹 내 도형을 끌 수 있는지 여부를 지정합니다. |
| [getSelectMode()](#getSelectMode--) | 사용자가 그룹 도형 및 해당 구성원을 선택하는 방식을 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [isDropTarget()](#isDropTarget--) | 도형을 그룹에 놓을 때 그룹에 도형을 추가하도록 허용하는지 여부를 지정합니다. |
| [isSnapTarget()](#isSnapTarget--) | 그룹 또는 그룹 내 도형에 스냅이 활성화되는지 여부를 지정합니다. |
| [isTextEditTarget()](#isTextEditTarget--) | 그룹에 텍스트를 할당하는 방법을 지정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/group\#getDel--)을(를) 참조하십시오. |
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
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getDisplayMode() {#getDisplayMode--}
```
public DisplayMode getDisplayMode()
```


Group 요소에 포함될 경우, DisplayMode 요소는 그룹 도형 및 그 구성원이 어떻게 표시되는지를 지정합니다.

**Returns:**
[DisplayMode](../../com.aspose.diagram/displaymode)
### getDontMoveChildren() {#getDontMoveChildren--}
```
public BoolValue getDontMoveChildren()
```


마우스를 사용하여 그룹 내 도형을 끌 수 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSelectMode() {#getSelectMode--}
```
public SelectMode getSelectMode()
```


사용자가 그룹 도형 및 해당 구성원을 선택하는 방식을 지정합니다.

**Returns:**
[SelectMode](../../com.aspose.diagram/selectmode)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropTarget() {#isDropTarget--}
```
public BoolValue isDropTarget()
```


도형을 그룹에 놓을 때 그룹에 도형을 추가하도록 허용하는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isSnapTarget() {#isSnapTarget--}
```
public BoolValue isSnapTarget()
```


그룹 또는 그룹 내 도형에 스냅이 활성화되는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isTextEditTarget() {#isTextEditTarget--}
```
public BoolValue isTextEditTarget()
```


그룹에 텍스트를 할당하는 방법을 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/group\#getDel--)을(를) 참조하십시오.

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

