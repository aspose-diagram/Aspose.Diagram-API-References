---
title: 보호
second_title: Aspose.Diagram for Java API 참조
description: 잠금은 도형에 대한 실수로 인한 변경을 방지하는 데 도움이 되지만 다른 상황에서 Microsoft Visio가 값을 재설정하는 것을 방지하지는 않습니다.
type: docs
weight: 312
url: /ko/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

잠금은 모양에 대한 의도치 않은 변경을 방지하는 데 도움이 되지만, 다른 상황에서 Microsoft Visio가 값을 재설정하는 것을 방지하지는 않습니다. 또한 ShapeSheet 창에서 이루어지는 변경으로부터 보호하지도 않습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getLockAspect()](#getLockAspect--) | 도형의 가로세로 비율이 잠겨 있는지 여부를 지정합니다. |
| [getLockBegin()](#getLockBegin--) | 1차원 도형의 시작점이 특정 위치에 고정되어 있는지 여부를 지정합니다. |
| [getLockCalcWH()](#getLockCalcWH--) | 도형의 선택 사각형이 잠겨 있어 정점이 편집되거나 Geom 요소에서 요소 유형이 변경될 때 재계산되지 않도록 지정합니다. |
| [getLockCrop()](#getLockCrop--) | Microsoft Visio의 자르기 도구로 외부 객체가 잘려지는 것을 방지하도록 잠겨 있는지 여부를 지정합니다. |
| [getLockCustProp()](#getLockCustProp--) | 사용자가 정의된 사용자 속성 대화 상자를 사용하여 UI에서 사용자 정의 속성을 추가, 삭제 또는 수정할 수 있는지 여부를 결정합니다. |
| [getLockDelete()](#getLockDelete--) | 도형이 삭제되는 것을 방지하도록 잠겨 있는지 여부를 지정합니다. |
| [getLockEnd()](#getLockEnd--) | 1차원 도형의 끝점이 특정 위치에 고정되어 있는지 여부를 지정합니다. |
| [getLockFormat()](#getLockFormat--) | 도형의 서식이 잠겨 있어 변경할 수 없는지 여부를 지정합니다. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Visio 사용자 인터페이스에서 상위 그룹 도형에 적용되는 서식 변경이 하위 도형에 의해 차단되도록 허용하며, 그렇지 않으면 개별 그룹 도형으로 전파됩니다. |
| [getLockGroup()](#getLockGroup--) | 그룹이 잠겨 있어 그룹 해제가 불가능하도록 지정합니다. |
| [getLockHeight()](#getLockHeight--) | 도형의 높이가 잠겨 있는지 여부를 지정합니다. |
| [getLockMoveX()](#getLockMoveX--) | 도형의 가로 위치가 잠겨 있어 수평으로 이동할 수 없는지 여부를 지정합니다. |
| [getLockMoveY()](#getLockMoveY--) | 도형의 세로 위치가 잠겨 있어 수직으로 이동할 수 없는지 여부를 지정합니다. |
| [getLockRotate()](#getLockRotate--) | Microsoft Visio의 회전 도구 또는 왼쪽 회전/오른쪽 회전 명령으로 도형이 회전되는 것을 방지하도록 잠겨 있는지 여부를 지정합니다. |
| [getLockSelect()](#getLockSelect--) | 도형의 선택 사각형이 잠겨 있어 정점이 편집되거나 Geom 요소에서 요소 유형이 변경될 때 재계산되지 않도록 지정합니다. |
| [getLockTextEdit()](#getLockTextEdit--) | 도형의 텍스트가 잠겨 있어 편집할 수 없는지 여부를 지정합니다. |
| [getLockThemeColors()](#getLockThemeColors--) | 사용자가 도형에 테마 색상을 적용하는 것을 방지합니다. |
| [getLockThemeEffects()](#getLockThemeEffects--) | 사용자가 모양에 테마 효과를 적용하는 것을 방지합니다. |
| [getLockVtxEdit()](#getLockVtxEdit--) | 모양의 정점이 잠겨 있어 도구 모음의 어떤 도구로도 편집할 수 없는지 여부를 지정합니다. |
| [getLockWidth()](#getLockWidth--) | 모양의 너비가 잠겨 있어 크기를 조정할 때 변경되지 않는지 여부를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/protection\#getDel--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


모양의 종횡비가 잠겨 있는지 여부를 지정합니다. 잠겨 있으면 모양을 비례적으로만 크기 조정할 수 있으며, 단일 차원으로는 크기 조정할 수 없습니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


1차원 도형의 시작점이 특정 위치에 고정되어 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


도형의 선택 사각형이 잠겨 있어 정점이 편집되거나 Geom 요소에서 요소 유형이 변경될 때 재계산되지 않도록 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


Microsoft Visio의 자르기 도구로 외부 객체가 잘려지는 것을 방지하도록 잠겨 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


사용자가 정의된 사용자 속성 대화 상자를 사용하여 UI에서 사용자 정의 속성을 추가, 삭제 또는 수정할 수 있는지 여부를 결정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


도형이 삭제되는 것을 방지하도록 잠겨 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


1차원 도형의 끝점이 특정 위치에 고정되어 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


모양의 서식이 잠겨 있어 변경할 수 없는지 여부를 지정합니다. 구체적으로, 이 요소는 텍스트, 선, 채우기 서식 변경이나 모양이 상속받는 Style 요소 변경을 방지합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Visio 사용자 인터페이스에서 상위 그룹 도형에 적용되는 서식 변경이 하위 도형에 의해 차단되도록 허용하며, 그렇지 않으면 개별 그룹 도형으로 전파됩니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


그룹이 잠겨 있어 그룹 해제가 불가능하도록 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


모양의 높이가 잠겨 있는지 여부를 지정합니다. 잠겨 있으면 모양을 크기 조정할 때 높이가 변경되지 않습니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


도형의 가로 위치가 잠겨 있어 수평으로 이동할 수 없는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


도형의 세로 위치가 잠겨 있어 수직으로 이동할 수 없는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


Microsoft Visio의 회전 도구 또는 왼쪽 회전/오른쪽 회전 명령으로 도형이 회전되는 것을 방지하도록 잠겨 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


도형의 선택 사각형이 잠겨 있어 정점이 편집되거나 Geom 요소에서 요소 유형이 변경될 때 재계산되지 않도록 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


모양의 텍스트가 잠겨 있어 편집할 수 없는지 여부를 지정합니다. 그러나 텍스트는 스타일을 적용하거나 텍스트 대화 상자의 글꼴 탭에 있는 Style 옵션을 사용하여 서식은 적용할 수 있습니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


사용자가 도형에 테마 색상을 적용하는 것을 방지합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


사용자가 모양에 테마 효과를 적용하는 것을 방지합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


모양의 정점이 잠겨 있어 도구 모음의 어떤 도구로도 편집할 수 없는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


모양의 너비가 잠겨 있어 크기를 조정할 때 변경되지 않는지 여부를 지정합니다.

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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/protection\#getDel--)을(를) 참조하십시오.

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

