---
title: Master
second_title: Aspose.Diagram for Java API 참조
description: 문서의 마스터를 정의하는 요소를 포함합니다.
type: docs
weight: 240
url: /ko/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

문서에 대한 마스터를 정의하는 요소를 포함합니다. 마스터는 스텐실에 있는 도형으로, 그림을 만들 때 반복해서 사용합니다. 스텐실에서 도형을 그림 페이지로 끌어오면, 해당 도형은 그 마스터의 인스턴스가 되며, 마스터의 로컬 복사본이 문서에 포함됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Master()](#Master--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [dispose()](#dispose--) | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | 스텐실 창에서 마스터의 텍스트가 왼쪽, 오른쪽 또는 가운데 정렬인지 지정합니다. |
| [getBaseID()](#getBaseID--) | 문서 전반에 걸쳐 마스터를 식별하는 GUID(전역 고유 식별자)입니다. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | 그림에서 두 도형 사이의 각 연결에 대한 Connect 요소를 포함합니다. |
| [getHidden()](#getHidden--) | 사용자 인터페이스에서 마스터가 숨겨져 있는지 지정합니다. |
| [getID()](#getID--) | 부모 요소 내에서 해당 요소의 고유 ID입니다. |
| [getIcon()](#getIcon--) | 문서의 Master 또는 MasterShortcut 요소에 대한 MIME(다목적 인터넷 메일 확장) 인코딩된 바이너리 아이콘(.ico 형식)을 지정합니다. |
| [getIconSize()](#getIconSize--) | 요소 아이콘의 크기입니다. |
| [getIconUpdate()](#getIconUpdate--) | 아이콘이 마스터 자체에서 자동으로 생성되는지 여부를 지정합니다. |
| [getMatchByName()](#getMatchByName--) | MatchByName 속성은 마스터 인스턴스를 그림 페이지에 놓을 때 Microsoft Visio가 문서 마스터가 이미 존재하는지를 판단하는 방식을 결정합니다. |
| [getName()](#getName--) | 요소의 이름입니다. |
| [getNameU()](#getNameU--) | 요소의 보편적인 이름입니다. |
| [getPageSheet()](#getPageSheet--) | 페이지 또는 마스터 요소에 대한 페이지 시트를 정의하는 요소를 포함합니다. |
| [getPatternFlags()](#getPatternFlags--) | PatternFlags 속성은 마스터가 사용자 지정 패턴으로 동작하는지를 결정합니다. |
| [getPrompt()](#getPrompt--) | 요소에 대한 상태 표시줄 및 툴팁 프롬프트입니다. |
| [getShapes()](#getShapes--) | Shape 객체들의 컬렉션입니다. |
| [getUniqueID()](#getUniqueID--) | 문서 내에서 마스터를 식별하는 GUID입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | 이 속성에 대한 설명은 [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)을(를) 참조하십시오. |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | 이 속성에 대한 설명은 [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)을(를) 참조하십시오. |
| [setHidden(int value)](#setHidden-int-) | 이 속성에 대한 설명은 [getHidden()](../../com.aspose.diagram/master\#getHidden--)을(를) 참조하십시오. |
| [setID(int value)](#setID-int-) | 이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/master\#getID--)을(를) 참조하십시오. |
| [setIcon(byte[] value)](#setIcon-byte---) | 이 속성에 대한 설명은 [getIcon()](../../com.aspose.diagram/master\#getIcon--)을(를) 참조하십시오. |
| [setIconSize(int value)](#setIconSize-int-) | 이 속성에 대한 설명은 [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)을(를) 참조하십시오. |
| [setIconUpdate(int value)](#setIconUpdate-int-) | 이 속성에 대한 설명은 [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)을(를) 참조하십시오. |
| [setMatchByName(int value)](#setMatchByName-int-) | 이 속성에 대한 설명은 [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)을(를) 참조하십시오. |
| [setName(String value)](#setName-java.lang.String-) | 이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/master\#getName--)을(를) 참조하십시오. |
| [setNameU(String value)](#setNameU-java.lang.String-) | 이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/master\#getNameU--)을(를) 참조하십시오. |
| [setPatternFlags(int value)](#setPatternFlags-int-) | 이 속성에 대한 설명은 [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)을(를) 참조하십시오. |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | 이 속성에 대한 설명은 [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)을(를) 참조하십시오. |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | 이 속성에 대한 설명은 [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


생성자.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


이 인스턴스의 깊은 복사본을 생성합니다.

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


스텐실 창에서 마스터의 텍스트가 왼쪽, 오른쪽 또는 가운데 정렬인지 지정합니다.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


문서 전반에 걸쳐 마스터를 식별하는 GUID(전역 고유 식별자)입니다.

**Returns:**
java.util.UUID
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


그림에서 두 도형 사이의 각 연결에 대한 Connect 요소를 포함합니다.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


사용자 인터페이스에서 마스터가 숨겨져 있는지 지정합니다.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


부모 요소 내에서 해당 요소의 고유 ID입니다.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


문서의 Master 또는 MasterShortcut 요소에 대한 MIME(다목적 인터넷 메일 확장) 인코딩된 바이너리 아이콘(.ico 형식)을 지정합니다.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


요소 아이콘의 크기입니다.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


아이콘이 마스터 자체에서 자동으로 생성되는지 여부를 지정합니다.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


MatchByName 속성은 Microsoft Visio가 마스터 인스턴스를 그리기 페이지에 놓을 때 해당 문서 마스터가 이미 존재하는지를 판단하는 방식을 결정합니다. 이를 통해 문서 마스터에 대한 변경 사항이 새 마스터 인스턴스에도 적용되며, 인스턴스가 독립 스텐실 파일에서 끌어온 경우에도 적용됩니다.

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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


페이지 또는 마스터 요소에 대한 페이지 시트를 정의하는 요소를 포함합니다.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


PatternFlags 속성은 마스터가 사용자 지정 패턴으로 동작하는지를 결정합니다.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


요소에 대한 상태 표시줄 및 툴팁 프롬프트입니다.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Shape 객체들의 컬렉션입니다.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


문서 내에서 마스터를 식별하는 GUID입니다.

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


이 속성에 대한 설명은 [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


이 속성에 대한 설명은 [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


이 속성에 대한 설명은 [getHidden()](../../com.aspose.diagram/master\#getHidden--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/master\#getID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


이 속성에 대한 설명은 [getIcon()](../../com.aspose.diagram/master\#getIcon--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


이 속성에 대한 설명은 [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


이 속성에 대한 설명은 [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


이 속성에 대한 설명은 [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/master\#getName--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/master\#getNameU--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


이 속성에 대한 설명은 [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


이 속성에 대한 설명은 [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


이 속성에 대한 설명은 [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.UUID |  |

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

