---
title: 필드
second_title: Aspose.Diagram for Java API 참조
description: 도형 텍스트에 삽입된 함수와 수식을 지정하는 요소를 포함합니다.
type: docs
weight: 147
url: /ko/java/com.aspose.diagram/field/
---

**Inheritance:**
java.lang.Object
```
public class Field
```

도형 텍스트에 삽입된 함수와 수식을 지정하는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Field()](#Field--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | 사용자 지정 속성, 텍스트 필드 및 요소 수식에 사용되는 달력을 결정합니다. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getDisplayValue()](#getDisplayValue--) | 이 필드의 서식이 지정된 문자열 값을 가져옵니다. |
| [getEditMode()](#getEditMode--) | 향후 사용을 위해 예약되었습니다. |
| [getFormat()](#getFormat--) | 서식 요소는 문자열, 숫자, 날짜 또는 시간, 기간, 통화인 텍스트 필드의 서식을 지정합니다. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getObjectKind()](#getObjectKind--) | 텍스트 필드 유형을 나타냅니다. |
| [getType()](#getType--) | Type은 텍스트 필드 값의 데이터 유형을 지정합니다. |
| [getUICat()](#getUICat--) | Visio 2000 이전 버전의 Microsoft Visio에서 삽입된 필드의 범주를 지정합니다. |
| [getUICod()](#getUICod--) | Visio 2000 이전 버전의 Microsoft Visio에서 삽입된 필드의 코드를 지정합니다. |
| [getUIFmt()](#getUIFmt--) | Visio 2000 이전 버전의 Microsoft Visio에서 삽입된 필드의 형식을 지정합니다. |
| [getValue()](#getValue--) | 텍스트 필드의 값을 포함합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/field\#getDel--)을 참조하십시오. |
| [setIX(int value)](#setIX-int-) | 이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/field\#getIX--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Field() {#Field--}
```
public Field()
```


생성자.

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
### getDisplayValue() {#getDisplayValue--}
```
public String getDisplayValue()
```


이 필드의 서식이 지정된 문자열 값을 가져옵니다.

**Returns:**
java.lang.String
### getEditMode() {#getEditMode--}
```
public DoubleValue getEditMode()
```


향후 사용을 위해 예약되었습니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFormat() {#getFormat--}
```
public Value getFormat()
```


Format 요소는 문자열, 숫자, 날짜 또는 시간, 기간, 통화인 텍스트 필드의 서식을 지정합니다. 텍스트 필드 유형은 해당 Type 요소에서 지정됩니다.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getIX() {#getIX--}
```
public int getIX()
```


부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스.

**Returns:**
int
### getObjectKind() {#getObjectKind--}
```
public ObjectKind getObjectKind()
```


텍스트 필드 유형을 나타냅니다.

**Returns:**
[ObjectKind](../../com.aspose.diagram/objectkind)
### getType() {#getType--}
```
public TypeField getType()
```


Type은 텍스트 필드 값의 데이터 유형을 지정합니다.

**Returns:**
[TypeField](../../com.aspose.diagram/typefield)
### getUICat() {#getUICat--}
```
public DoubleValue getUICat()
```


Visio 2000 이전 버전의 Microsoft Visio에서 삽입된 필드의 범주를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUICod() {#getUICod--}
```
public DoubleValue getUICod()
```


Visio 2000 이전 버전의 Microsoft Visio에서 삽입된 필드의 코드를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUIFmt() {#getUIFmt--}
```
public DoubleValue getUIFmt()
```


Visio 2000 이전 버전의 Microsoft Visio에서 삽입된 필드의 형식을 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getValue() {#getValue--}
```
public Value getValue()
```


텍스트 필드의 값을 포함합니다.

**Returns:**
[Value](../../com.aspose.diagram/value)
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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/field\#getDel--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/field\#getIX--)을(를) 참조하십시오.

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

