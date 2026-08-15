---
title: 연결
second_title: Aspose.Diagram for Java API 참조
description: 도형에 정의된 하나의 연결 지점에 대한 요소를 포함합니다.
type: docs
weight: 78
url: /ko/java/com.aspose.diagram/connection/
---

**Inheritance:**
java.lang.Object
```
public class Connection
```

도형에 정의된 하나의 연결 지점에 대한 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Connection()](#Connection--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | 이 인스턴스의 깊은 복사본을 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoGen()](#getAutoGen--) | 연결 지점이 자동으로 생성되는지 지정합니다. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getDirX()](#getDirX--) | 일치하는 연결 지점의 필요한 정렬 벡터에 대한 x-성분을 지정합니다. |
| [getDirY()](#getDirY--) | 일치하는 연결 지점의 필요한 정렬 벡터에 대한 y-성분을 지정합니다. |
| [getID()](#getID--) | 부모 요소 내에서 해당 요소의 고유 ID입니다. |
| [getIX()](#getIX--) | 부모 요소 내에서 해당 요소의 0부터 시작하는 인덱스. |
| [getName()](#getName--) | 요소의 이름입니다. |
| [getNameU()](#getNameU--) | 요소의 보편적인 이름입니다. |
| [getPrompt()](#getPrompt--) | 포함된 요소에 따라 다양한 프롬프트 정보를 포함합니다. |
| [getType()](#getType--) | 포함된 요소에 따라 다양한 유형을 지정합니다. |
| [getX()](#getX--) | 로컬 좌표계에서 모양의 x좌표를 지정합니다. |
| [getY()](#getY--) | 로컬 좌표계에서 모양의 y좌표를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/connection\#getDel--)을(를) 참조하십시오. |
| [setID(int value)](#setID-int-) | 이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/connection\#getID--)을(를) 참조하십시오. |
| [setIX(int value)](#setIX-int-) | 이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/connection\#getIX--)을(를) 참조하십시오. |
| [setName(String value)](#setName-java.lang.String-) | 이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/connection\#getName--)을(를) 참조하십시오. |
| [setNameU(String value)](#setNameU-java.lang.String-) | 이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/connection\#getNameU--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Connection() {#Connection--}
```
public Connection()
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
### getAutoGen() {#getAutoGen--}
```
public BoolValue getAutoGen()
```


연결 지점이 자동으로 생성되는지 지정합니다. 값 1은 연결 지점이 자동으로 생성됨을 나타냅니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getDirX() {#getDirX--}
```
public DoubleValue getDirX()
```


일치하는 연결 지점의 필요한 정렬 벡터에 대한 x-성분을 지정합니다. DirX 요소는 동적 커넥터의 연결된 다리를 방향 지정하는 데에도 사용됩니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDirY() {#getDirY--}
```
public DoubleValue getDirY()
```


일치하는 연결 지점의 필요한 정렬 벡터에 대한 y-성분을 지정합니다. DirY 요소는 동적 커넥터의 연결된 다리를 방향 지정하는 데에도 사용됩니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


포함된 요소에 따라 다양한 프롬프트 정보를 포함합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeConnection getType()
```


포함된 요소에 따라 다양한 유형을 지정합니다.

**Returns:**
[TypeConnection](../../com.aspose.diagram/typeconnection)
### getX() {#getX--}
```
public DoubleValue getX()
```


로컬 좌표계에서 모양의 x좌표를 지정합니다.

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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/connection\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/connection\#getID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


이 속성에 대한 설명은 [getIX()](../../com.aspose.diagram/connection\#getIX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/connection\#getName--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/connection\#getNameU--)을(를) 참조하십시오.

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

