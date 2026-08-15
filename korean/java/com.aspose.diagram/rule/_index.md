---
title: Rule
second_title: Aspose.Diagram for Java API 참조
description: 다이어그램 검증 규칙 집합에서 단일 검증 규칙을 나타냅니다.
type: docs
weight: 338
url: /ko/java/com.aspose.diagram/rule/
---

**Inheritance:**
java.lang.Object
```
public class Rule
```

다이어그램 검증 규칙 집합에서 단일 검증 규칙을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Rule()](#Rule--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategory()](#getCategory--) | Issues 창의 Category 열에 표시되는 텍스트를 지정합니다. |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 사용자 인터페이스에 표시되는 검증 규칙의 설명. |
| [getID()](#getID--) | 검증 규칙의 고유 식별자를 지정합니다. |
| [getIgnored()](#getIgnored--) | 검증 규칙이 현재 무시되는지 여부를 지정합니다. |
| [getNameU()](#getNameU--) | 검증 규칙의 보편적인 이름을 지정합니다. |
| [getRuleFilter()](#getRuleFilter--) | 검증 규칙을 대상 객체에 적용할지 여부를 결정하는 논리식을 지정합니다. |
| [getRuleTarget()](#getRuleTarget--) | 검증 규칙이 적용되는 객체 유형을 지정합니다. |
| [getRuleTest()](#getRuleTest--) | 대상 객체가 검증 규칙을 만족하는지 여부를 결정하는 논리식을 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCategory(String value)](#setCategory-java.lang.String-) | 이 속성에 대한 설명은 [getCategory()](../../com.aspose.diagram/rule\#getCategory--)을(를) 참조하십시오. |
| [setDescription(String value)](#setDescription-java.lang.String-) | 이 속성에 대한 설명은 [getDescription()](../../com.aspose.diagram/rule\#getDescription--)을(를) 참조하십시오. |
| [setID(long value)](#setID-long-) | 이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/rule\#getID--)을(를) 참조하십시오. |
| [setIgnored(int value)](#setIgnored-int-) | 이 속성에 대한 설명은 [getIgnored()](../../com.aspose.diagram/rule\#getIgnored--)을(를) 참조하십시오. |
| [setNameU(String value)](#setNameU-java.lang.String-) | 이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/rule\#getNameU--)을(를) 참조하십시오. |
| [setRuleFilter(RuleValue value)](#setRuleFilter-com.aspose.diagram.RuleValue-) | 이 속성에 대한 설명은 [getRuleFilter()](../../com.aspose.diagram/rule\#getRuleFilter--)을(를) 참조하십시오. |
| [setRuleTarget(int value)](#setRuleTarget-int-) | 이 속성에 대한 설명은 [getRuleTarget()](../../com.aspose.diagram/rule\#getRuleTarget--)을(를) 참조하십시오. |
| [setRuleTest(RuleValue value)](#setRuleTest-com.aspose.diagram.RuleValue-) | 이 속성에 대한 설명은 [getRuleTest()](../../com.aspose.diagram/rule\#getRuleTest--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rule() {#Rule--}
```
public Rule()
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
### getCategory() {#getCategory--}
```
public String getCategory()
```


Issues 창의 Category 열에 표시되는 텍스트를 지정합니다. 기본값은 빈 문자열입니다.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public String getDescription()
```


사용자 인터페이스에 표시되는 검증 규칙의 설명입니다. 기본값은 "Unknown"입니다.

**Returns:**
java.lang.String
### getID() {#getID--}
```
public long getID()
```


검증 규칙의 고유 식별자를 지정합니다.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


검증 규칙이 현재 무시되는지 여부를 지정합니다. 기본값은 False입니다.

**Returns:**
int
### getNameU() {#getNameU--}
```
public String getNameU()
```


검증 규칙의 보편적인 이름을 지정합니다.

**Returns:**
java.lang.String
### getRuleFilter() {#getRuleFilter--}
```
public RuleValue getRuleFilter()
```


검증 규칙을 대상 객체에 적용할지 여부를 결정하는 논리식을 지정합니다.

**Returns:**
[RuleValue](../../com.aspose.diagram/rulevalue)
### getRuleTarget() {#getRuleTarget--}
```
public int getRuleTarget()
```


검증 규칙이 적용되는 객체 유형을 지정합니다.

**Returns:**
int
### getRuleTest() {#getRuleTest--}
```
public RuleValue getRuleTest()
```


대상 객체가 검증 규칙을 만족하는지 여부를 결정하는 논리식을 지정합니다.

**Returns:**
[RuleValue](../../com.aspose.diagram/rulevalue)
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




### setCategory(String value) {#setCategory-java.lang.String-}
```
public void setCategory(String value)
```


이 속성에 대한 설명은 [getCategory()](../../com.aspose.diagram/rule\#getCategory--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


이 속성에 대한 설명은 [getDescription()](../../com.aspose.diagram/rule\#getDescription--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/rule\#getID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


이 속성에 대한 설명은 [getIgnored()](../../com.aspose.diagram/rule\#getIgnored--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/rule\#getNameU--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setRuleFilter(RuleValue value) {#setRuleFilter-com.aspose.diagram.RuleValue-}
```
public void setRuleFilter(RuleValue value)
```


이 속성에 대한 설명은 [getRuleFilter()](../../com.aspose.diagram/rule\#getRuleFilter--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RuleValue](../../com.aspose.diagram/rulevalue) |  |

### setRuleTarget(int value) {#setRuleTarget-int-}
```
public void setRuleTarget(int value)
```


이 속성에 대한 설명은 [getRuleTarget()](../../com.aspose.diagram/rule\#getRuleTarget--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRuleTest(RuleValue value) {#setRuleTest-com.aspose.diagram.RuleValue-}
```
public void setRuleTest(RuleValue value)
```


이 속성에 대한 설명은 [getRuleTest()](../../com.aspose.diagram/rule\#getRuleTest--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RuleValue](../../com.aspose.diagram/rulevalue) |  |

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

