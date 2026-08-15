---
title: EventItem
second_title: Aspose.Diagram for Java API 참조
description: 이벤트 코드를 캡슐화합니다.
type: docs
weight: 145
url: /ko/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

이벤트 코드를 캡슐화합니다. EventItem 요소는 두 가지 종류의 동작을 트리거할 수 있습니다: 애드온을 실행하거나, 이벤트에 대한 알림을 호출 프로그램에 보낼 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EventItem()](#EventItem--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | 상위 EventItem 요소의 동작 코드를 지정합니다. EventItem 요소가 DatadiagramML 파일에 저장되려면 지속 가능해야 합니다. |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | 이벤트가 활성화되었는지 비활성화되었는지를 나타내는 플래그를 나타냅니다. |
| [getEventCode()](#getEventCode--) | 애드온을 트리거하는 이벤트를 나타내는 코드입니다. |
| [getID()](#getID--) | 이벤트의 ID입니다. |
| [getTarget()](#getTarget--) | 이벤트의 대상(target)을 지정합니다. |
| [getTargetArgs()](#getTargetArgs--) | 이벤트 대상에 전달될 인수를 포함하는 문자열을 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | 이 속성에 대한 설명은 [getAction()](../../com.aspose.diagram/eventitem\#getAction--)을(를) 참조하십시오. |
| [setEnabled(int value)](#setEnabled-int-) | 이 속성에 대한 설명은 [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)을(를) 참조하십시오. |
| [setEventCode(int value)](#setEventCode-int-) | 이 속성에 대한 설명은 [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)을(를) 참조하십시오. |
| [setID(int value)](#setID-int-) | 이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/eventitem\#getID--)을(를) 참조하십시오. |
| [setTarget(String value)](#setTarget-java.lang.String-) | 이 속성에 대한 설명은 [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)을(를) 참조하십시오. |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | 이 속성에 대한 설명은 [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
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
### getAction() {#getAction--}
```
public int getAction()
```


상위 EventItem 요소의 동작 코드를 지정합니다. EventItem 요소가 DatadiagramML 파일에 저장되려면 지속 가능해야 합니다. 현재, 지속 가능한 이벤트가 가질 수 있는 유효한 동작 코드는 1 (ONEVENT_ACT_RUNADDON) 하나뿐입니다.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnabled() {#getEnabled--}
```
public int getEnabled()
```


이벤트가 활성화되었는지 비활성화되었는지를 나타내는 플래그를 나타냅니다.

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


애드온을 트리거하는 이벤트를 나타내는 코드입니다. 이벤트 코드에 대한 자세한 내용은 Microsoft Visio 2007 Automation Reference의 Event Codes를 참조하십시오.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


이벤트의 ID입니다.

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


이벤트의 대상(target)을 지정합니다.

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


이벤트 대상에 전달될 인수를 포함하는 문자열을 지정합니다.

**Returns:**
java.lang.String
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




### setAction(int value) {#setAction-int-}
```
public void setAction(int value)
```


이 속성에 대한 설명은 [getAction()](../../com.aspose.diagram/eventitem\#getAction--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


이 속성에 대한 설명은 [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


이 속성에 대한 설명은 [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/eventitem\#getID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


이 속성에 대한 설명은 [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


이 속성에 대한 설명은 [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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

