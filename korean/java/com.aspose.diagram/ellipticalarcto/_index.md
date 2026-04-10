---
title: EllipticalArcTo
second_title: Aspose.Diagram for Java API 참조
description: 타원 호에 대한 정보를 지정하는 요소를 포함합니다.
type: docs
weight: 140
url: /ko/java/com.aspose.diagram/ellipticalarcto/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class EllipticalArcTo extends Coordinate
```

타원 호에 대한 정보를 지정하는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EllipticalArcTo()](#EllipticalArcTo--) | 다음 [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) 클래스의 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | 호의 제어점 x좌표. |
| [getB()](#getB--) | 호의 제어점 y좌표. |
| [getC()](#getC--) | 부모의 x축에 대한 호의 장축 각도. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | 호의 장축과 단축의 비율. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getX()](#getX--) | 타원형 호 끝 정점의 x좌표. |
| [getY()](#getY--) | 타원형 호 끝 정점의 y좌표. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--)을(를) 참조하십시오. |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--)을(를) 참조하십시오. |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--)을(를) 참조하십시오. |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--)을(를) 참조하십시오. |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--)을(를) 참조하십시오. |
| [setIX(int value)](#setIX-int-) | 이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--)을(를) 참조하십시오. |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--)을(를) 참조하십시오. |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은, [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--) 를 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EllipticalArcTo() {#EllipticalArcTo--}
```
public EllipticalArcTo()
```


다음 [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) 클래스의 인스턴스를 생성합니다.

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
public DoubleValue getA()
```


호의 제어점의 x좌표입니다. 제어점은 호의 시작 정점과 끝 정점 사이 중간 정도에 위치하는 것이 가장 좋습니다. 그렇지 않으면 제어점을 통과하기 위해 호가 극도로 커질 수 있으며, 예측할 수 없는 결과가 발생할 수 있습니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


호의 제어점 y좌표.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


부모의 x축에 대한 호의 장축 각도.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


호의 장축과 단축의 비율입니다. 일반적인 의미와 달리 장축이 단축보다 크지 않아도 되므로 이 비율이 1보다 커야 할 필요는 없습니다. 이 요소를 0 이하 또는 1000 초과 값으로 설정하면 예측할 수 없는 결과가 발생할 수 있습니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


타원형 호 끝 정점의 x좌표.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


타원형 호 끝 정점의 y좌표.

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


이 속성에 대한 설명은 [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


이 속성에 대한 설명은 [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


이 속성에 대한 설명은 [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


이 속성에 대한 설명은 [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


이 속성에 대한 설명은 [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


이 속성에 대한 설명은, [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--) 를 참조하십시오.

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

