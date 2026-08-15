---
title: TextBlock
second_title: Aspose.Diagram for Java API 참조
description: 도형 텍스트 블록 내 텍스트의 정렬 여백 및 기본 탭 정지 위치를 지정하는 요소를 포함합니다.
type: docs
weight: 400
url: /ko/java/com.aspose.diagram/textblock/
---

**Inheritance:**
java.lang.Object
```
public class TextBlock
```

도형 텍스트 블록의 텍스트 정렬, 여백 및 기본 탭 정지 위치를 지정하는 요소를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | 텍스트 블록의 하단 경계와 포함된 마지막 텍스트 행 사이의 거리를 결정합니다. |
| [getClass()](#getClass--) |  |
| [getDefaultTabStop()](#getDefaultTabStop--) | 텍스트 블록 내 기본 탭 정지 간격을 지정합니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getLeftMargin()](#getLeftMargin--) | 텍스트 블록의 왼쪽 경계와 포함된 텍스트 사이의 거리를 지정합니다. |
| [getRightMargin()](#getRightMargin--) | 텍스트 블록의 오른쪽 경계와 포함된 텍스트 사이의 거리를 지정합니다. |
| [getTextBkgnd()](#getTextBkgnd--) | 도형의 텍스트 배경 색상을 지정합니다. |
| [getTextBkgndTrans()](#getTextBkgndTrans--) | 도형 텍스트 블록 배경 색상의 투명도 수준을 0(완전 불투명)부터 1(완전 투명)까지 지정합니다. |
| [getTextDirection()](#getTextDirection--) | 텍스트 블록 내 문자 방향을 지정합니다. |
| [getTopMargin()](#getTopMargin--) | 텍스트 블록의 상단 경계와 포함된 첫 번째 텍스트 행 사이의 거리를 지정합니다. |
| [getVerticalAlign()](#getVerticalAlign--) | 텍스트 블록 내 텍스트의 수직 정렬을 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBottomMargin(DoubleValue value)](#setBottomMargin-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--)을(를) 참조하십시오. |
| [setDefaultTabStop(DoubleValue value)](#setDefaultTabStop-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--)을(를) 참조하십시오. |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/textblock\#getDel--)을(를) 참조하십시오. |
| [setLeftMargin(DoubleValue value)](#setLeftMargin-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--)을(를) 참조하십시오. |
| [setRightMargin(DoubleValue value)](#setRightMargin-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--)을(를) 참조하십시오. |
| [setTextBkgnd(ColorValue value)](#setTextBkgnd-com.aspose.diagram.ColorValue-) | 이 속성에 대한 설명은 [getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--)을(를) 참조하십시오. |
| [setTextBkgndTrans(DoubleValue value)](#setTextBkgndTrans-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--)을(를) 참조하십시오. |
| [setTextDirection(TextDirection value)](#setTextDirection-com.aspose.diagram.TextDirection-) | 이 속성에 대한 설명은 [getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--)을(를) 참조하십시오. |
| [setTopMargin(DoubleValue value)](#setTopMargin-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--)을(를) 참조하십시오. |
| [setVerticalAlign(VerticalAlign value)](#setVerticalAlign-com.aspose.diagram.VerticalAlign-) | 이 속성에 대한 설명은 [getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBottomMargin() {#getBottomMargin--}
```
public DoubleValue getBottomMargin()
```


텍스트 블록의 하단 경계와 포함된 마지막 텍스트 행 사이의 거리를 결정합니다. 기본값은 4pt입니다. 이 값은 도면의 축척에 영향을 받지 않습니다. 도면이 확대/축소되더라도 하단 여백은 동일하게 유지됩니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultTabStop() {#getDefaultTabStop--}
```
public DoubleValue getDefaultTabStop()
```


텍스트 블록 내 기본 탭 정지 간격을 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getLeftMargin() {#getLeftMargin--}
```
public DoubleValue getLeftMargin()
```


텍스트 블록의 왼쪽 경계와 포함된 텍스트 사이의 거리를 지정합니다. 이 값은 도면의 축척에 영향을 받지 않습니다. 도면이 확대/축소되더라도 왼쪽 여백은 동일하게 유지됩니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRightMargin() {#getRightMargin--}
```
public DoubleValue getRightMargin()
```


텍스트 블록의 오른쪽 경계와 포함된 텍스트 사이의 거리를 지정합니다. 이 값은 도면의 축척에 영향을 받지 않습니다. 도면이 확대/축소되더라도 오른쪽 여백은 동일하게 유지됩니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextBkgnd() {#getTextBkgnd--}
```
public ColorValue getTextBkgnd()
```


도형의 텍스트 배경 색상을 지정합니다.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getTextBkgndTrans() {#getTextBkgndTrans--}
```
public DoubleValue getTextBkgndTrans()
```


도형 텍스트 블록 배경 색상의 투명도 수준을 0(완전 불투명)부터 1(완전 투명)까지 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextDirection() {#getTextDirection--}
```
public TextDirection getTextDirection()
```


텍스트 블록 내 문자 방향을 지정합니다.

**Returns:**
[TextDirection](../../com.aspose.diagram/textdirection)
### getTopMargin() {#getTopMargin--}
```
public DoubleValue getTopMargin()
```


텍스트 블록의 상단 경계와 포함된 첫 번째 텍스트 행 사이의 거리를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getVerticalAlign() {#getVerticalAlign--}
```
public VerticalAlign getVerticalAlign()
```


텍스트 블록 내 텍스트의 수직 정렬을 지정합니다.

**Returns:**
[VerticalAlign](../../com.aspose.diagram/verticalalign)
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




### setBottomMargin(DoubleValue value) {#setBottomMargin-com.aspose.diagram.DoubleValue-}
```
public void setBottomMargin(DoubleValue value)
```


이 속성에 대한 설명은 [getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDefaultTabStop(DoubleValue value) {#setDefaultTabStop-com.aspose.diagram.DoubleValue-}
```
public void setDefaultTabStop(DoubleValue value)
```


이 속성에 대한 설명은 [getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/textblock\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setLeftMargin(DoubleValue value) {#setLeftMargin-com.aspose.diagram.DoubleValue-}
```
public void setLeftMargin(DoubleValue value)
```


이 속성에 대한 설명은 [getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRightMargin(DoubleValue value) {#setRightMargin-com.aspose.diagram.DoubleValue-}
```
public void setRightMargin(DoubleValue value)
```


이 속성에 대한 설명은 [getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextBkgnd(ColorValue value) {#setTextBkgnd-com.aspose.diagram.ColorValue-}
```
public void setTextBkgnd(ColorValue value)
```


이 속성에 대한 설명은 [getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setTextBkgndTrans(DoubleValue value) {#setTextBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setTextBkgndTrans(DoubleValue value)
```


이 속성에 대한 설명은 [getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextDirection(TextDirection value) {#setTextDirection-com.aspose.diagram.TextDirection-}
```
public void setTextDirection(TextDirection value)
```


이 속성에 대한 설명은 [getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextDirection](../../com.aspose.diagram/textdirection) |  |

### setTopMargin(DoubleValue value) {#setTopMargin-com.aspose.diagram.DoubleValue-}
```
public void setTopMargin(DoubleValue value)
```


이 속성에 대한 설명은 [getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setVerticalAlign(VerticalAlign value) {#setVerticalAlign-com.aspose.diagram.VerticalAlign-}
```
public void setVerticalAlign(VerticalAlign value)
```


이 속성에 대한 설명은 [getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [VerticalAlign](../../com.aspose.diagram/verticalalign) |  |

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

