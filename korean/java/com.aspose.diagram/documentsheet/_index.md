---
title: DocumentSheet
second_title: Aspose.Diagram for Java API 참조
description: 문서의 ShapeSheet 구조를 지정합니다.
type: docs
weight: 127
url: /ko/java/com.aspose.diagram/documentsheet/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSheet
```

문서의 ShapeSheet 구조를 지정합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnnotations()](#getAnnotations--) | 문서 페이지에 삽입된 주석에 대한 정보를 포함하는 요소를 포함합니다. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | ConnectionABCD 요소의 컬렉션을 포함합니다. |
| [getConnections()](#getConnections--) | Connection 요소의 컬렉션을 포함합니다. |
| [getDocProps()](#getDocProps--) | 문서의 미리보기 품질, 범위 및 출력 형식을 제어하는 요소를 포함합니다. |
| [getFillStyle()](#getFillStyle--) | 이 스타일이 채우기 서식을 상속받는 StyleSheet 요소입니다. |
| [getForeign()](#getForeign--) | Microsoft Visio 문서에서 사용되는 다른 프로그램의 객체 너비와 높이를 지정하는 요소를 포함합니다. |
| [getForeignData()](#getForeignData--) | Windows 메타파일, 비트맵 또는 OLE 데이터와 같은 그림 데이터의 MIME(다목적 인터넷 메일 확장) 인코딩 BLOB을 포함합니다. |
| [getHyperlinks()](#getHyperlinks--) | Hyperlink 요소들의 컬렉션을 포함합니다. |
| [getLineStyle()](#getLineStyle--) | 이 스타일이 선 서식을 상속받는 StyleSheet 요소입니다. |
| [getName()](#getName--) | 요소의 이름입니다. |
| [getNameU()](#getNameU--) | 요소의 보편적인 이름입니다. |
| [getProps()](#getProps--) | Prop 요소들의 컬렉션을 포함합니다. |
| [getReviewers()](#getReviewers--) | 문서 검토자에 대한 식별 정보를 포함하는 요소를 포함합니다. |
| [getScratchs()](#getScratchs--) | Scratch 요소의 컬렉션을 포함합니다. |
| [getTextStyle()](#getTextStyle--) | 이 스타일이 텍스트 서식을 상속받는 StyleSheet 요소입니다. |
| [getUniqueID()](#getUniqueID--) | 도형을 식별하는 GUID(전역 고유 식별자)입니다. |
| [getUsers()](#getUsers--) | User 요소의 컬렉션을 포함합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | 이 속성에 대한 설명은 [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--)을(를) 확인하십시오. |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | 이 속성에 대한 설명은 [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--)을(를) 확인하십시오. |
| [setName(String value)](#setName-java.lang.String-) | 이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/documentsheet\#getName--)을(를) 확인하십시오. |
| [setNameU(String value)](#setNameU-java.lang.String-) | 이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--)을(를) 확인하십시오. |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | 이 속성에 대한 설명은 [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--)을(를) 확인하십시오. |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | 이 속성에 대한 설명은 [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--)을(를) 확인하십시오. |
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
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


문서 페이지에 삽입된 주석에 대한 정보를 포함하는 요소를 포함합니다.

**Returns:**
[AnnotationCollection](../../com.aspose.diagram/annotationcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


ConnectionABCD 요소의 컬렉션을 포함합니다.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Connection 요소의 컬렉션을 포함합니다.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getDocProps() {#getDocProps--}
```
public DocProps getDocProps()
```


문서의 미리보기 품질, 범위 및 출력 형식을 제어하는 요소를 포함합니다.

**Returns:**
[DocProps](../../com.aspose.diagram/docprops)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


이 스타일이 채우기 서식을 상속받는 StyleSheet 요소입니다.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Microsoft Visio 문서에서 사용되는 다른 프로그램의 객체의 너비와 높이를 지정하는 요소를 포함합니다. 또한 객체 이미지가 경계 내에서 오프셋되는 거리를 지정하는 요소도 포함합니다.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Windows 메타파일, 비트맵 또는 OLE 데이터와 같은 그림 데이터의 MIME(다목적 인터넷 메일 확장) 인코딩 BLOB을 포함합니다.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Hyperlink 요소들의 컬렉션을 포함합니다.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


이 스타일이 선 서식을 상속받는 StyleSheet 요소입니다.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
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
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Prop 요소들의 컬렉션을 포함합니다.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getReviewers() {#getReviewers--}
```
public ReviewerCollection getReviewers()
```


문서 검토자에 대한 식별 정보를 포함하는 요소를 포함합니다.

**Returns:**
[ReviewerCollection](../../com.aspose.diagram/reviewercollection)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Scratch 요소의 컬렉션을 포함합니다.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


이 스타일이 텍스트 서식을 상속받는 StyleSheet 요소입니다.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


도형을 식별하는 GUID(전역 고유 식별자)입니다.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


User 요소의 컬렉션을 포함합니다.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
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




### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


이 속성에 대한 설명은 [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--)을(를) 확인하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


이 속성에 대한 설명은 [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--)을(를) 확인하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/documentsheet\#getName--)을(를) 확인하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--)을(를) 확인하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


이 속성에 대한 설명은 [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--)을(를) 확인하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


이 속성에 대한 설명은 [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--)을(를) 확인하십시오.

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

