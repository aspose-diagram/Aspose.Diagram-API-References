---
title: Para
second_title: Aspose.Diagram for Java API 참조
description: 도형 텍스트의 들여쓰기, 줄 간격, 글머리표 및 단락의 수평 정렬과 같은 단락 서식 요소를 포함합니다.
type: docs
weight: 274
url: /ko/java/com.aspose.diagram/para/
---

**Inheritance:**
java.lang.Object
```
public class Para
```

도형 텍스트에 대한 단락 서식 요소를 포함합니다. 예: 들여쓰기, 행 간격, 글머리표, 단락의 가로 정렬 등.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Para()](#Para--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBullet()](#getBullet--) | 글머리표 스타일을 결정합니다. |
| [getBulletFont()](#getBulletFont--) | 사용자 정의 글머리표 문자열이 지정되고 Bullet 요소의 값이 0이 아닌 경우 텍스트 서식에 사용되는 글꼴 번호를 나타냅니다. |
| [getBulletFontSize()](#getBulletFontSize--) | 글머리표의 크기를 지정합니다. |
| [getBulletStr()](#getBulletStr--) | "사용자 정의 글머리표 스타일을 만드는 데 사용됩니다. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getFlags()](#getFlags--) | 텍스트 방향이 왼쪽에서 오른쪽인지 오른쪽에서 왼쪽인지 나타냅니다. |
| [getHorzAlign()](#getHorzAlign--) | 도형 텍스트 블록 내 텍스트의 가로 정렬을 지정합니다. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getIndFirst()](#getIndFirst--) | 도형 텍스트 블록에서 각 단락의 첫 번째 줄이 단락의 왼쪽 들여쓰기에서 얼마나 떨어져 있는지를 지정합니다. |
| [getIndLeft()](#getIndLeft--) | 단락의 모든 텍스트 줄이 텍스트 블록의 왼쪽 여백에서 얼마나 떨어져 있는지를 지정합니다. |
| [getIndRight()](#getIndRight--) | 문단의 모든 텍스트 줄이 텍스트 블록의 오른쪽 여백으로부터 들여쓰기되는 거리를 지정합니다. |
| [getLocalizeBulletFont()](#getLocalizeBulletFont--) | 글머리 기호 폰트를 현지화(다른 언어로 번역)해야 하는지 여부를 지정합니다. |
| [getSpAfter()](#getSpAfter--) | 도형의 텍스트 블록에서 각 문단 뒤에 삽입되는 공간의 양을 지정합니다. |
| [getSpBefore()](#getSpBefore--) | 도형의 텍스트 블록에서 각 문단 앞에 삽입되는 공간의 양을 지정합니다. |
| [getSpLine()](#getSpLine--) | 텍스트 한 줄과 다음 줄 사이의 거리를 지정합니다. 여기서 100%는 텍스트 줄의 높이입니다. |
| [getTextPosAfterBullet()](#getTextPosAfterBullet--) | 문단의 첫 번째 줄과 글머리 기호 사이의 거리를 나타냅니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBullet(Bullet value)](#setBullet-com.aspose.diagram.Bullet-) | 이 속성에 대한 설명은 [getBullet()](../../com.aspose.diagram/para\#getBullet--)을(를) 참조하십시오. |
| [setBulletFont(IntValue value)](#setBulletFont-com.aspose.diagram.IntValue-) | 이 속성에 대한 설명은 [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--)을(를) 참조하십시오. |
| [setBulletFontSize(DoubleValue value)](#setBulletFontSize-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--)을(를) 참조하십시오. |
| [setBulletStr(Str2Value value)](#setBulletStr-com.aspose.diagram.Str2Value-) | 이 속성에 대한 설명은 [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--)을(를) 참조하십시오. |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/para\#getDel--)을(를) 참조하십시오. |
| [setFlags(BoolValue value)](#setFlags-com.aspose.diagram.BoolValue-) | 이 속성에 대한 설명은 [getFlags()](../../com.aspose.diagram/para\#getFlags--)을(를) 참조하십시오. |
| [setHorzAlign(HorzAlign value)](#setHorzAlign-com.aspose.diagram.HorzAlign-) | 이 속성에 대한 설명은 [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--)을(를) 참조하십시오. |
| [setIX(int value)](#setIX-int-) | 이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/para\#getIX--)을(를) 참조하십시오. |
| [setIndFirst(DoubleValue value)](#setIndFirst-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--)을(를) 참조하십시오. |
| [setIndLeft(DoubleValue value)](#setIndLeft-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--)을(를) 참조하십시오. |
| [setIndRight(DoubleValue value)](#setIndRight-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getIndRight()](../../com.aspose.diagram/para\#getIndRight--)을(를) 참조하십시오. |
| [setLocalizeBulletFont(LocalizeFont value)](#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-) | 이 속성에 대한 설명은 [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--)을(를) 참조하십시오. |
| [setSpAfter(DoubleValue value)](#setSpAfter-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--)을(를) 참조하십시오. |
| [setSpBefore(DoubleValue value)](#setSpBefore-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--)을(를) 참조하십시오. |
| [setSpLine(DoubleValue value)](#setSpLine-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getSpLine()](../../com.aspose.diagram/para\#getSpLine--)을(를) 참조하십시오. |
| [setTextPosAfterBullet(DoubleValue value)](#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-) | 이 속성에 대한 설명은 [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Para() {#Para--}
```
public Para()
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
### getBullet() {#getBullet--}
```
public Bullet getBullet()
```


글머리표 스타일을 결정합니다.

**Returns:**
[Bullet](../../com.aspose.diagram/bullet)
### getBulletFont() {#getBulletFont--}
```
public IntValue getBulletFont()
```


사용자 정의 글머리표 문자열이 지정되고 Bullet 요소의 값이 0이 아닌 경우 텍스트 서식에 사용되는 글꼴 번호를 나타냅니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBulletFontSize() {#getBulletFontSize--}
```
public DoubleValue getBulletFontSize()
```


글머리표의 크기를 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBulletStr() {#getBulletStr--}
```
public Str2Value getBulletStr()
```


"사용자 정의 글머리 기호 스타일을 만들 때 사용됩니다. 스타일을 문자열(따옴표 안)로 입력하십시오. 예를 들어, 문자열 \"\"ooo.\"\"을(를) 입력할 수 있습니다."

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getFlags() {#getFlags--}
```
public BoolValue getFlags()
```


텍스트 방향이 왼쪽에서 오른쪽인지 오른쪽에서 왼쪽인지 나타냅니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHorzAlign() {#getHorzAlign--}
```
public HorzAlign getHorzAlign()
```


도형 텍스트 블록 내 텍스트의 가로 정렬을 지정합니다.

**Returns:**
[HorzAlign](../../com.aspose.diagram/horzalign)
### getIX() {#getIX--}
```
public int getIX()
```


부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스.

**Returns:**
int
### getIndFirst() {#getIndFirst--}
```
public DoubleValue getIndFirst()
```


도형의 텍스트 블록에서 각 문단의 첫 번째 줄이 문단의 왼쪽 들여쓰기에서 떨어진 거리를 지정합니다. 이 값은 도면의 축척에 영향을 받지 않습니다. 도면이 축척될 경우에도 첫 번째 줄 들여쓰기는 동일하게 유지됩니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndLeft() {#getIndLeft--}
```
public DoubleValue getIndLeft()
```


문단의 모든 텍스트 줄이 텍스트 블록의 왼쪽 여백으로부터 들여쓰기되는 거리를 지정합니다. 이 값은 도면의 축척에 영향을 받지 않습니다. 도면이 축척될 경우에도 왼쪽 들여쓰기는 동일하게 유지됩니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndRight() {#getIndRight--}
```
public DoubleValue getIndRight()
```


문단의 모든 텍스트 줄이 텍스트 블록의 오른쪽 여백에서 들여쓰기되는 거리를 지정합니다. 이 값은 도면의 축척과 무관합니다. 도면이 축척되더라도 오른쪽 들여쓰기는 동일하게 유지됩니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocalizeBulletFont() {#getLocalizeBulletFont--}
```
public LocalizeFont getLocalizeBulletFont()
```


글머리 기호 폰트를 현지화(다른 언어로 번역)해야 하는지 여부를 지정합니다.

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getSpAfter() {#getSpAfter--}
```
public DoubleValue getSpAfter()
```


도형의 텍스트 블록에서 각 문단 뒤에 삽입되는 공간의 양을 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpBefore() {#getSpBefore--}
```
public DoubleValue getSpBefore()
```


도형의 텍스트 블록에서 각 문단 앞에 삽입되는 공간의 양을 지정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpLine() {#getSpLine--}
```
public DoubleValue getSpLine()
```


텍스트 한 줄과 다음 줄 사이의 거리를 지정합니다. 여기서 100%는 텍스트 줄의 높이입니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextPosAfterBullet() {#getTextPosAfterBullet--}
```
public DoubleValue getTextPosAfterBullet()
```


문단의 첫 번째 줄과 글머리 기호 사이의 거리를 나타냅니다.

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




### setBullet(Bullet value) {#setBullet-com.aspose.diagram.Bullet-}
```
public void setBullet(Bullet value)
```


이 속성에 대한 설명은 [getBullet()](../../com.aspose.diagram/para\#getBullet--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Bullet](../../com.aspose.diagram/bullet) |  |

### setBulletFont(IntValue value) {#setBulletFont-com.aspose.diagram.IntValue-}
```
public void setBulletFont(IntValue value)
```


이 속성에 대한 설명은 [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBulletFontSize(DoubleValue value) {#setBulletFontSize-com.aspose.diagram.DoubleValue-}
```
public void setBulletFontSize(DoubleValue value)
```


이 속성에 대한 설명은 [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBulletStr(Str2Value value) {#setBulletStr-com.aspose.diagram.Str2Value-}
```
public void setBulletStr(Str2Value value)
```


이 속성에 대한 설명은 [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/para\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setFlags(BoolValue value) {#setFlags-com.aspose.diagram.BoolValue-}
```
public void setFlags(BoolValue value)
```


이 속성에 대한 설명은 [getFlags()](../../com.aspose.diagram/para\#getFlags--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHorzAlign(HorzAlign value) {#setHorzAlign-com.aspose.diagram.HorzAlign-}
```
public void setHorzAlign(HorzAlign value)
```


이 속성에 대한 설명은 [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [HorzAlign](../../com.aspose.diagram/horzalign) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/para\#getIX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIndFirst(DoubleValue value) {#setIndFirst-com.aspose.diagram.DoubleValue-}
```
public void setIndFirst(DoubleValue value)
```


이 속성에 대한 설명은 [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndLeft(DoubleValue value) {#setIndLeft-com.aspose.diagram.DoubleValue-}
```
public void setIndLeft(DoubleValue value)
```


이 속성에 대한 설명은 [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndRight(DoubleValue value) {#setIndRight-com.aspose.diagram.DoubleValue-}
```
public void setIndRight(DoubleValue value)
```


이 속성에 대한 설명은 [getIndRight()](../../com.aspose.diagram/para\#getIndRight--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocalizeBulletFont(LocalizeFont value) {#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeBulletFont(LocalizeFont value)
```


이 속성에 대한 설명은 [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setSpAfter(DoubleValue value) {#setSpAfter-com.aspose.diagram.DoubleValue-}
```
public void setSpAfter(DoubleValue value)
```


이 속성에 대한 설명은 [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpBefore(DoubleValue value) {#setSpBefore-com.aspose.diagram.DoubleValue-}
```
public void setSpBefore(DoubleValue value)
```


이 속성에 대한 설명은 [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpLine(DoubleValue value) {#setSpLine-com.aspose.diagram.DoubleValue-}
```
public void setSpLine(DoubleValue value)
```


이 속성에 대한 설명은 [getSpLine()](../../com.aspose.diagram/para\#getSpLine--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextPosAfterBullet(DoubleValue value) {#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-}
```
public void setTextPosAfterBullet(DoubleValue value)
```


이 속성에 대한 설명은 [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--)을(를) 참조하십시오.

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

