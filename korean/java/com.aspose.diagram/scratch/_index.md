---
title: Scratch
second_title: Aspose.Diagram for Java API 참조
description: 다른 요소가 참조하는 수식을 입력하고 테스트할 수 있는 작업 영역을 포함합니다.
type: docs
weight: 350
url: /ko/java/com.aspose.diagram/scratch/
---

**Inheritance:**
java.lang.Object
```
public class Scratch
```

다른 요소에서 참조하는 수식을 입력하고 테스트할 수 있는 작업 영역을 포함합니다. 이 요소는 일반적으로 반복되는 복잡한 계산을 분리하는 데 사용됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Scratch()](#Scratch--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | 범용 요소입니다. |
| [getB()](#getB--) | 범용 스크래치 요소입니다. |
| [getC()](#getC--) | 범용 요소입니다. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | 범용 요소입니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getX()](#getX--) | 로컬 좌표계에서 모양의 x좌표를 지정합니다. |
| [getY()](#getY--) | 로컬 좌표계에서 모양의 y좌표를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(Value value)](#setA-com.aspose.diagram.Value-) | 이 속성에 대한 설명은 [getA()](../../com.aspose.diagram/scratch\#getA--)을(를) 참조하십시오. |
| [setB(Value value)](#setB-com.aspose.diagram.Value-) | 이 속성에 대한 설명은 [getB()](../../com.aspose.diagram/scratch\#getB--)을(를) 참조하십시오. |
| [setC(Value value)](#setC-com.aspose.diagram.Value-) | 이 속성에 대한 설명은 [getC()](../../com.aspose.diagram/scratch\#getC--)을(를) 참조하십시오. |
| [setD(Value value)](#setD-com.aspose.diagram.Value-) | 이 속성에 대한 설명은 [getD()](../../com.aspose.diagram/scratch\#getD--)을(를) 참조하십시오. |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/scratch\#getDel--)을(를) 참조하십시오. |
| [setIX(int value)](#setIX-int-) | 이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/scratch\#getIX--)을(를) 참조하십시오. |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getX()](../../com.aspose.diagram/scratch\#getX--)을(를) 참조하십시오. |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getY()](../../com.aspose.diagram/scratch\#getY--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scratch() {#Scratch--}
```
public Scratch()
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
### getA() {#getA--}
```
public Value getA()
```


범용 요소입니다.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getB() {#getB--}
```
public Value getB()
```


범용 스크래치 요소입니다.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getC() {#getC--}
```
public Value getC()
```


범용 요소입니다.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public Value getD()
```


범용 요소입니다.

**Returns:**
[Value](../../com.aspose.diagram/value)
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
### getX() {#getX--}
```
public DoubleValue getX()
```


로컬 좌표계에서 도형의 x 좌표를 지정합니다. 다음 표는 이를 포함하는 요소를 기준으로 X 요소를 설명합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


로컬 좌표계에서 도형의 y 좌표를 지정합니다. 로컬 좌표계는 페이지가 아니라 도형을 기준으로 하는 좌표계입니다.

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




### setA(Value value) {#setA-com.aspose.diagram.Value-}
```
public void setA(Value value)
```


이 속성에 대한 설명은 [getA()](../../com.aspose.diagram/scratch\#getA--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Value](../../com.aspose.diagram/value) |  |

### setB(Value value) {#setB-com.aspose.diagram.Value-}
```
public void setB(Value value)
```


이 속성에 대한 설명은 [getB()](../../com.aspose.diagram/scratch\#getB--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Value](../../com.aspose.diagram/value) |  |

### setC(Value value) {#setC-com.aspose.diagram.Value-}
```
public void setC(Value value)
```


이 속성에 대한 설명은 [getC()](../../com.aspose.diagram/scratch\#getC--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Value](../../com.aspose.diagram/value) |  |

### setD(Value value) {#setD-com.aspose.diagram.Value-}
```
public void setD(Value value)
```


이 속성에 대한 설명은 [getD()](../../com.aspose.diagram/scratch\#getD--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Value](../../com.aspose.diagram/value) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/scratch\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/scratch\#getIX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


이 속성에 대한 설명은 [getX()](../../com.aspose.diagram/scratch\#getX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


이 속성에 대한 설명은 [getY()](../../com.aspose.diagram/scratch\#getY--)을(를) 참조하십시오.

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

