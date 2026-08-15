---
title: Hyperlink
second_title: Aspose.Diagram for Java API 참조
description: 도형 또는 도면 페이지와 다른 도면 페이지, 다른 파일 또는 웹 사이트 간에 여러 번 점프를 만들기 위한 요소를 포함합니다.
type: docs
weight: 193
url: /ko/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

도형 또는 그리기 페이지와 다른 그리기 페이지, 다른 파일, 또는 웹 사이트 간에 여러 번 점프를 생성하는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | 점프할 URL 주소, DOS 파일 이름 또는 UNC 경로를 지정합니다. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | 도형 또는 페이지에 대한 기본 하이퍼링크를 지정합니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getDescription()](#getDescription--) | Description 요소는 하이퍼링크를 설명하는 텍스트 문자열을 포함합니다. |
| [getExtraInfo()](#getExtraInfo--) | 이미지 맵의 좌표와 같은 URL을 해석하는 데 사용할 정보를 포함합니다. |
| [getFrame()](#getFrame--) | Microsoft Visio가 컨테이너 애플리케이션에서 활성 문서로 열릴 때 대상이 되는 프레임 이름을 포함합니다. |
| [getID()](#getID--) | 부모 요소 내에서 해당 요소의 고유 ID입니다. |
| [getInvisible()](#getInvisible--) | Invisible 요소는 도형 또는 페이지의 바로 가기 메뉴에 하이퍼링크가 표시되는지 여부를 나타냅니다. |
| [getName()](#getName--) | 요소의 이름입니다. |
| [getNameU()](#getNameU--) | 요소의 보편적인 이름입니다. |
| [getNewWindow()](#getNewWindow--) | Microsoft Visio가 하이퍼링크를 따라 웹 페이지 또는 다른 Visio 문서를 열 때 새 위치에 창을 열지 여부를 지정합니다. |
| [getSortKey()](#getSortKey--) | Invisible 요소는 도형 또는 페이지의 바로 가기 메뉴에 하이퍼링크가 표시되는지 여부를 나타냅니다. |
| [getSubAddress()](#getSubAddress--) | 대상 문서 내에서 연결할 위치를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)을(를) 참조하십시오. |
| [setID(int value)](#setID-int-) | 이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/hyperlink\#getID--)을(를) 참조하십시오. |
| [setName(String value)](#setName-java.lang.String-) | 이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/hyperlink\#getName--)을(를) 참조하십시오. |
| [setNameU(String value)](#setNameU-java.lang.String-) | 이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


점프할 URL 주소, DOS 파일 이름 또는 UNC 경로를 지정합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public BoolValue getDefault()
```


도형 또는 페이지에 대한 기본 하이퍼링크를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


Description 요소는 하이퍼링크를 설명하는 텍스트 문자열을 포함합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


이미지 맵의 좌표와 같은 URL을 해석하는 데 사용할 정보를 포함합니다. 예를 들어, x=41 y=7은 이미지 맵의 좌표를 지정합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


Microsoft Visio가 컨테이너 애플리케이션에서 활성 문서로 열릴 때 대상이 되는 프레임 이름을 포함합니다. 기본값은 빈 문자열입니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


부모 요소 내에서 해당 요소의 고유 ID입니다.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Invisible 요소는 도형 또는 페이지의 바로 가기 메뉴에 하이퍼링크가 표시되는지 여부를 나타냅니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


Microsoft Visio가 하이퍼링크를 따라 웹 페이지 또는 다른 Visio 문서를 열 때 새 위치에 창을 열지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Invisible 요소는 도형 또는 페이지의 바로 가기 메뉴에 하이퍼링크가 표시되는지 여부를 나타냅니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


대상 문서 내에서 연결할 위치를 지정합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/hyperlink\#getID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/hyperlink\#getName--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)을(를) 참조하십시오.

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

