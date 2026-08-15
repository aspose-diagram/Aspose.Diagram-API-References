---
title: Geom
second_title: Aspose.Diagram for Java API 참조
description: 도형을 구성하는 선과 호의 정점 좌표를 지정하는 요소를 포함합니다.
type: docs
weight: 169
url: /ko/java/com.aspose.diagram/geom/
---

**Inheritance:**
java.lang.Object
```
public class Geom
```

도형을 구성하는 선과 호의 정점 좌표를 지정하는 요소를 포함합니다. 도형에 경로가 여러 개 있는 경우 각 경로마다 Geom 요소가 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Geom()](#Geom--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateCol()](#getCoordinateCol--) | 좌표 컬렉션입니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getNextCoordinateIX()](#getNextCoordinateIX--) | 다음 도형의 좌표 컬렉션 멤버에 대한 IX 값을 반환합니다. |
| [getNoFill()](#getNoFill--) | 경로를 채울 수 있는지 여부를 지정합니다. |
| [getNoLine()](#getNoLine--) | 경로 경계 주변에 선이 그려지는지 여부를 지정합니다. |
| [getNoQuickDrag()](#getNoQuickDrag--) | 사용자가 Geometry 섹션에 정의된 채워진 영역을 클릭할 때 도형을 선택하거나 끌 수 있는지를 결정합니다. |
| [getNoShow()](#getNoShow--) | 경로가 도면 페이지에 표시되는지 여부를 지정합니다. |
| [getNoSnap()](#getNoSnap--) | 다른 도형이 경로에 스냅되는지 여부를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/geom\#getDel--)을(를) 참조하십시오. |
| [setIX(int value)](#setIX-int-) | 이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/geom\#getIX--)을(를) 참조하십시오. |
| [setNoFill(BoolValue value)](#setNoFill-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--)을(를) 참조하십시오. |
| [setNoLine(BoolValue value)](#setNoLine-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--)을(를) 참조하십시오. |
| [setNoQuickDrag(BoolValue value)](#setNoQuickDrag-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--)을(를) 참조하십시오. |
| [setNoShow(BoolValue value)](#setNoShow-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--)을(를) 참조하십시오. |
| [setNoSnap(BoolValue value)](#setNoSnap-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geom() {#Geom--}
```
public Geom()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateCol() {#getCoordinateCol--}
```
public CoordinateCollection getCoordinateCol()
```


좌표 컬렉션. 좌표 순서를 표시합니다.

**Returns:**
[CoordinateCollection](../../com.aspose.diagram/coordinatecollection)
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
### getNextCoordinateIX() {#getNextCoordinateIX--}
```
public int getNextCoordinateIX()
```


다음 도형의 좌표 컬렉션 멤버에 대한 IX 값을 반환합니다.

**Returns:**
int
### getNoFill() {#getNoFill--}
```
public BoolValue getNoFill()
```


경로를 채울 수 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLine() {#getNoLine--}
```
public BoolValue getNoLine()
```


경로 경계 주변에 선이 그려지는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoQuickDrag() {#getNoQuickDrag--}
```
public BoolValue getNoQuickDrag()
```


사용자가 Geometry 섹션에 정의된 채워진 영역을 클릭할 때 도형을 선택하거나 끌 수 있는지를 결정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoShow() {#getNoShow--}
```
public BoolValue getNoShow()
```


경로가 도면 페이지에 표시되는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoSnap() {#getNoSnap--}
```
public BoolValue getNoSnap()
```


다른 도형이 경로에 스냅되는지 여부를 지정합니다.

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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/geom\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/geom\#getIX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setNoFill(BoolValue value) {#setNoFill-com.aspose.diagram.BoolValue-}
```
public void setNoFill(BoolValue value)
```


이 속성에 대한 설명은 [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoLine(BoolValue value) {#setNoLine-com.aspose.diagram.BoolValue-}
```
public void setNoLine(BoolValue value)
```


이 속성에 대한 설명은 [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoQuickDrag(BoolValue value) {#setNoQuickDrag-com.aspose.diagram.BoolValue-}
```
public void setNoQuickDrag(BoolValue value)
```


이 속성에 대한 설명은 [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoShow(BoolValue value) {#setNoShow-com.aspose.diagram.BoolValue-}
```
public void setNoShow(BoolValue value)
```


이 속성에 대한 설명은 [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoSnap(BoolValue value) {#setNoSnap-com.aspose.diagram.BoolValue-}
```
public void setNoSnap(BoolValue value)
```


이 속성에 대한 설명은 [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

