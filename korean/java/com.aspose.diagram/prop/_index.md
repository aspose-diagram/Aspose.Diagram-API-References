---
title: 속성
second_title: Aspose.Diagram for Java API 참조
description: 사용자 지정 속성을 정의하는 요소와 도형에 데이터를 연결하는 요소를 포함합니다.
type: docs
weight: 309
url: /ko/java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

사용자 지정 속성을 정의하는 요소와 도형에 데이터를 연결하는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Prop()](#Prop--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | 사용자 지정 속성, 텍스트 필드 및 요소 수식에 사용되는 달력을 결정합니다. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getFormat()](#getFormat--) | Format 요소는 문자열, 고정 목록, 숫자, 가변 목록, 날짜 또는 시간, 기간, 통화인 사용자 정의 속성의 서식을 지정합니다. |
| [getID()](#getID--) | 부모 요소 내에서 해당 요소의 고유 ID입니다. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getInvisible()](#getInvisible--) | Invisible 요소는 Microsoft Visio의 사용자 정의 속성 대화 상자에서 사용자 정의 속성이 표시되는지 여부를 지정합니다. |
| [getLabel()](#getLabel--) | 사용자 정의 속성 대화 상자에 사용자에게 표시되는 레이블을 지정합니다. |
| [getLangID()](#getLangID--) | 셀 수식, 텍스트, 사용자 정의 속성 또는 주석이 입력된 언어의 로케일 ID(LCID)를 나타냅니다. |
| [getName()](#getName--) | 요소의 이름입니다. |
| [getNameU()](#getNameU--) | 요소의 보편적인 이름입니다. |
| [getPrompt()](#getPrompt--) | Prompt 요소는 속성이 선택될 때 사용자 정의 속성 대화 상자에 사용자에게 표시되는 설명 또는 안내 텍스트를 지정합니다. |
| [getSortKey()](#getSortKey--) | 이것은 애플리케이션 UI에 사용자 정의 속성이 나열되는 순서를 결정하는 키를 지정합니다. |
| [getType()](#getType--) | Type은 사용자 지정 속성 값의 데이터 유형을 지정합니다. |
| [getValue()](#getValue--) | 명시적 네임스페이스에 접두사가 붙은 솔루션별 잘 형성된 XML 데이터를 포함하며 문서와 함께 저장됩니다. |
| [getVerify()](#getVerify--) | 인스턴스가 생성되거나 도형이 복제·복사될 때 사용자가 도형에 대한 사용자 정의 속성 정보를 입력하도록 요청받는지 여부를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/prop\#getDel--)을(를) 참조하십시오 |
| [setID(int value)](#setID-int-) | 이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/prop\#getID--)을(를) 참조하십시오 |
| [setIX(int value)](#setIX-int-) | 이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/prop\#getIX--)을(를) 참조하십시오 |
| [setName(String value)](#setName-java.lang.String-) | 이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/prop\#getName--)을(를) 참조하십시오 |
| [setNameU(String value)](#setNameU-java.lang.String-) | 이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/prop\#getNameU--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


생성자.

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


이 인스턴스의 깊은 복사본을 생성합니다.

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


사용자 지정 속성, 텍스트 필드 및 요소 수식에 사용되는 달력을 결정합니다.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
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
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


Format 요소는 문자열, 고정 목록, 숫자, 가변 목록, 날짜 또는 시간, 기간, 통화인 사용자 정의 속성의 형식을 지정합니다. 사용자 정의 속성 유형은 해당 Type 요소에 지정됩니다.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getID() {#getID--}
```
public int getID()
```


부모 요소 내에서 해당 요소의 고유 ID입니다.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Invisible 요소는 Microsoft Visio의 사용자 정의 속성 대화 상자에서 사용자 정의 속성이 표시되는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


사용자 정의 속성 대화 상자에 사용자에게 표시되는 레이블을 지정합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


셀 수식, 텍스트, 사용자 정의 속성 또는 주석이 입력된 언어의 로케일 ID(LCID)를 나타냅니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getName() {#getName--}
```
public String getName()
```


요소의 이름입니다.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


요소의 보편적인 이름입니다.

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Prompt 요소는 속성이 선택될 때 사용자에게 Custom Properties 대화 상자에 표시되는 설명 또는 안내 텍스트를 지정합니다. 이 텍스트는 Custom Properties 창에서 마우스 포인터를 속성 위에 올려 놓을 때 툴팁으로도 표시됩니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


이것은 애플리케이션 UI에 사용자 정의 속성이 나열되는 순서를 결정하는 키를 지정합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Type은 사용자 지정 속성 값의 데이터 유형을 지정합니다.

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


명시적 네임스페이스에 접두사가 붙은 솔루션별 잘 형성된 XML 데이터를 포함하며 문서와 함께 저장됩니다.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


인스턴스가 생성되거나 도형이 복제·복사될 때 사용자가 도형에 대한 사용자 정의 속성 정보를 입력하도록 요청받는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/prop\#getDel--)을(를) 참조하십시오

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/prop\#getID--)을(를) 참조하십시오

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/prop\#getIX--)을(를) 참조하십시오

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/prop\#getName--)을(를) 참조하십시오

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/prop\#getNameU--)을(를) 참조하십시오.

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

