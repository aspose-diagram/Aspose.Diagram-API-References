---
title: 제어
second_title: Aspose.Diagram for Java API 참조
description: 도형에 정의된 각 제어 핸들의 x 및 y 좌표 요소와 제어 핸들의 동작 방식을 지정하는 요소를 포함합니다.
type: docs
weight: 87
url: /ko/java/com.aspose.diagram/control/
---

**Inheritance:**
java.lang.Object
```
public class Control
```

도형에 정의된 각 컨트롤 핸들의 x 및 y 좌표에 대한 요소와 컨트롤 핸들의 동작 방식을 지정하는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Control()](#Control--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [canGlue()](#canGlue--) | 제어 핸들을 다른 도형에 붙일 수 있는지 여부를 결정합니다. |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getID()](#getID--) | 부모 요소 내에서 해당 요소의 고유 ID입니다. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getName()](#getName--) | 요소의 이름입니다. |
| [getNameU()](#getNameU--) | 요소의 보편적인 이름입니다. |
| [getPrompt()](#getPrompt--) | 프롬프트 요소는 마우스 포인터가 도형의 제어 핸들 위에 멈출 때 툴팁으로 표시되는 설명 텍스트를 지정합니다. |
| [getX()](#getX--) | 도형의 제어 핸들 위치를 나타내는 x 좌표입니다. |
| [getXCon()](#getXCon--) | 핸들을 이동한 후 제어 핸들의 x 좌표가 나타내는 동작 유형을 지정합니다. |
| [getXDyn()](#getXDyn--) | 제어 핸들의 기준점에 대한 x 좌표를 로컬 좌표계로 지정합니다. |
| [getY()](#getY--) | 도형의 제어 핸들 위치를 나타내는 y 좌표입니다. |
| [getYCon()](#getYCon--) | 핸들을 이동한 후 제어 핸들의 x 좌표가 나타내는 동작 유형을 지정합니다. |
| [getYDyn()](#getYDyn--) | 제어 핸들의 기준점에 대한 y 좌표를 로컬 좌표계로 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCanGlue(BoolValue value)](#setCanGlue-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [canGlue()](../../com.aspose.diagram/control\#canGlue--)을(를) 참조하십시오. |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/control\#getDel--)을(를) 참조하십시오. |
| [setID(int value)](#setID-int-) | 이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/control\#getID--)을(를) 참조하십시오. |
| [setIX(int value)](#setIX-int-) | 이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/control\#getIX--)을(를) 참조하십시오. |
| [setName(String value)](#setName-java.lang.String-) | 이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/control\#getName--)을(를) 참조하십시오. |
| [setNameU(String value)](#setNameU-java.lang.String-) | 이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/control\#getNameU--)을(를) 참조하십시오. |
| [setPrompt(Str2Value value)](#setPrompt-com.aspose.diagram.Str2Value-) | 이 속성에 대한 설명은 [getPrompt()](../../com.aspose.diagram/control\#getPrompt--)을(를) 참조하십시오. |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getX()](../../com.aspose.diagram/control\#getX--)을(를) 참조하십시오. |
| [setXCon(ConType value)](#setXCon-com.aspose.diagram.ConType-) | 이 속성에 대한 설명은 [getXCon()](../../com.aspose.diagram/control\#getXCon--)을(를) 참조하십시오. |
| [setXDyn(DoubleValue value)](#setXDyn-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getXDyn()](../../com.aspose.diagram/control\#getXDyn--)을(를) 참조하십시오. |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getY()](../../com.aspose.diagram/control\#getY--)을(를) 참조하십시오. |
| [setYCon(ConType value)](#setYCon-com.aspose.diagram.ConType-) | 이 속성에 대한 설명은 [getYCon()](../../com.aspose.diagram/control\#getYCon--)을(를) 참조하십시오. |
| [setYDyn(DoubleValue value)](#setYDyn-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getYDyn()](../../com.aspose.diagram/control\#getYDyn--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Control() {#Control--}
```
public Control()
```


생성자.

### canGlue() {#canGlue--}
```
public BoolValue canGlue()
```


제어 핸들을 다른 도형에 붙일 수 있는지 여부를 결정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


프롬프트 요소는 마우스 포인터가 도형의 제어 핸들 위에 멈출 때 툴팁으로 표시되는 설명 텍스트를 지정합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getX() {#getX--}
```
public DoubleValue getX()
```


도형의 제어 핸들 위치를 나타내는 x 좌표입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getXCon() {#getXCon--}
```
public ConType getXCon()
```


핸들을 이동한 후 제어 핸들의 x 좌표가 나타내는 동작 유형을 지정합니다.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getXDyn() {#getXDyn--}
```
public DoubleValue getXDyn()
```


제어 핸들의 앵커 포인트에 대한 x 좌표를 로컬 좌표계에서 지정합니다. 앵커 포인트는 동적 처리 중 고무 밴딩에 사용됩니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


도형의 제어 핸들 위치를 나타내는 y 좌표입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getYCon() {#getYCon--}
```
public ConType getYCon()
```


핸들을 이동한 후 제어 핸들의 x 좌표가 나타내는 동작 유형을 지정합니다.

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getYDyn() {#getYDyn--}
```
public DoubleValue getYDyn()
```


제어 핸들의 앵커 포인트에 대한 y 좌표를 로컬 좌표계에서 지정합니다. 앵커 포인트는 동적 처리 중 고무 밴딩에 사용됩니다.

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




### setCanGlue(BoolValue value) {#setCanGlue-com.aspose.diagram.BoolValue-}
```
public void setCanGlue(BoolValue value)
```


이 속성에 대한 설명은 [canGlue()](../../com.aspose.diagram/control\#canGlue--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/control\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/control\#getID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/control\#getIX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/control\#getName--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/control\#getNameU--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPrompt(Str2Value value) {#setPrompt-com.aspose.diagram.Str2Value-}
```
public void setPrompt(Str2Value value)
```


이 속성에 대한 설명은 [getPrompt()](../../com.aspose.diagram/control\#getPrompt--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


이 속성에 대한 설명은 [getX()](../../com.aspose.diagram/control\#getX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setXCon(ConType value) {#setXCon-com.aspose.diagram.ConType-}
```
public void setXCon(ConType value)
```


이 속성에 대한 설명은 [getXCon()](../../com.aspose.diagram/control\#getXCon--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setXDyn(DoubleValue value) {#setXDyn-com.aspose.diagram.DoubleValue-}
```
public void setXDyn(DoubleValue value)
```


이 속성에 대한 설명은 [getXDyn()](../../com.aspose.diagram/control\#getXDyn--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


이 속성에 대한 설명은 [getY()](../../com.aspose.diagram/control\#getY--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setYCon(ConType value) {#setYCon-com.aspose.diagram.ConType-}
```
public void setYCon(ConType value)
```


이 속성에 대한 설명은 [getYCon()](../../com.aspose.diagram/control\#getYCon--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setYDyn(DoubleValue value) {#setYDyn-com.aspose.diagram.DoubleValue-}
```
public void setYDyn(DoubleValue value)
```


이 속성에 대한 설명은 [getYDyn()](../../com.aspose.diagram/control\#getYDyn--)을(를) 참조하십시오.

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

