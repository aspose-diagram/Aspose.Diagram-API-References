---
title: Layer
second_title: Aspose.Diagram for Java API 참조
description: 페이지에 대한 단일 레이어와 그 속성을 정의하는 요소를 포함합니다.
type: docs
weight: 212
url: /ko/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

페이지에 대한 단일 레이어와 그 속성을 정의하는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Layer()](#Layer--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | 레이어가 활성 상태인지 여부를 지정합니다. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 레이어를 표시하는 데 사용되는 색상표의 색상 인덱스 또는 색상표에 없는 사용자 정의 색상을 지정하는 RGB 값(예: \#ff9900). |
| [getColorTrans()](#getColorTrans--) | 레이어 또는 도형 텍스트 색상의 투명도 정도를 0(완전히 불투명)에서 1(완전히 투명)까지 결정합니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getGlue()](#getGlue--) | 레이어에 속한 도형을 접착할 수 있는지 여부를 지정합니다. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getLock()](#getLock--) | 레이어에 속한 도형이 선택되거나 편집되는 것을 방지하도록 잠겨 있는지 여부를 지정합니다. |
| [getName()](#getName--) | Name 요소는 레이어의 이름을 지정합니다. |
| [getNameUniv()](#getNameUniv--) | 레이어의 전역 이름을 지정합니다. |
| [getPrint()](#getPrint--) | 도면을 인쇄할 때 레이어에 속한 도형이 인쇄되는지 여부를 지정합니다. |
| [getSnap()](#getSnap--) | 다른 도형이 레이어에 할당된 도형에 스냅될 수 있는지 여부를 지정합니다. |
| [getStatus()](#getStatus--) | 레이어가 문서에 대한 유효한 레이어인지 여부를 지정합니다. |
| [getVisible()](#getVisible--) | 레이어에 속한 도형이 도면 페이지에 표시되는지 여부를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | 요소가 로컬에서 확인되었는지 여부를 나타내는 플래그입니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | 이 속성에 대한 설명은 [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)을(를) 참조하십시오. |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/layer\#getDel--)을(를) 참조하십시오. |
| [setIX(int value)](#setIX-int-) | 이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/layer\#getIX--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


레이어가 활성 상태인지 여부를 지정합니다. 레이어에 미리 할당되지 않은 도형은 도면 페이지에 놓일 때 활성 레이어에 할당됩니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


레이어를 표시하는 데 사용되는 색상표의 색상 인덱스 또는 색상표에 없는 사용자 정의 색상을 지정하는 RGB 값(예: \#ff9900).

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


레이어 또는 도형 텍스트 색상의 투명도 정도를 0(완전히 불투명)에서 1(완전히 투명)까지 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


레이어에 속한 도형을 접착할 수 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


레이어에 속한 도형이 선택되거나 편집되는 것을 방지하도록 잠겨 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


Name 요소는 레이어의 이름을 지정합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


레이어의 전역 이름을 지정합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


도면을 인쇄할 때 레이어에 속한 도형이 인쇄되는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


다른 도형이 레이어에 할당된 도형에 스냅될 수 있는지 여부를 지정합니다. 레이어에 할당된 도형은 다른 도형에 스냅될 수 있지만, 다른 도형은 해당 도형에 스냅될 수 없습니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


레이어가 문서에 대한 유효한 레이어인지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


레이어에 속한 도형이 도면 페이지에 표시되는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


요소가 로컬에서 확인되었는지 여부를 나타내는 플래그입니다. 값이 1이면 요소가 로컬에서 확인된 것을 의미합니다.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


이 속성에 대한 설명은 [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/layer\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/layer\#getIX--)을(를) 참조하십시오.

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

