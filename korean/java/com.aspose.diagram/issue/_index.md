---
title: Issue
second_title: Aspose.Diagram for Java API 참조
description: 문서의 단일 검증 문제를 나타냅니다.
type: docs
weight: 208
url: /ko/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

문서의 단일 검증 문제를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Issue()](#Issue--) | 생성자 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | 검증 문제의 고유 식별자를 지정합니다. |
| [getIgnored()](#getIgnored--) | 검증 문제가 현재 무시되는지 여부를 지정합니다. |
| [getIssueTarget()](#getIssueTarget--) | 상위 검증 문제의 대상에 따라, 상위 검증 문제가 연결된 페이지 또는 페이지와 도형을 모두 지정합니다. |
| [getRuleInfo()](#getRuleInfo--) | 상위 검증 이슈와 관련된 검증 규칙에 대한 정보를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | 이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/issue\#getID--)을(를) 참조하십시오. |
| [setIgnored(int value)](#setIgnored-int-) | 이 속성에 대한 설명은 [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


생성자

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
### getID() {#getID--}
```
public long getID()
```


검증 문제의 고유 식별자를 지정합니다.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


검증 문제가 현재 무시되는지 여부를 지정합니다. 기본값은 False입니다.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


부모 검증 문제의 대상에 따라 해당 문제와 연관된 페이지 또는 페이지와 도형 모두를 지정합니다. 부모 검증 문제의 대상이 문서인 경우, IssueTarget은 페이지도 도형도 지정하지 않습니다.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


상위 검증 이슈와 관련된 검증 규칙에 대한 정보를 지정합니다.

**Returns:**
[RuleInfo](../../com.aspose.diagram/ruleinfo)
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




### setID(long value) {#setID-long-}
```
public void setID(long value)
```


이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/issue\#getID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


이 속성에 대한 설명은 [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)을(를) 참조하십시오.

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

