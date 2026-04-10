---
title: DocumentProperties
second_title: Aspose.Diagram for Java API 참조
description: 문서 제목, 저자 등과 같은 문서 속성 요소를 포함합니다.
type: docs
weight: 125
url: /ko/java/com.aspose.diagram/documentproperties/
---

**Inheritance:**
java.lang.Object
```
public class DocumentProperties
```

문서의 제목, 작성자 등과 같은 문서 속성 요소를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlternateNames()](#getAlternateNames--) | 문서에 대한 대체 이름을 지정합니다. |
| [getBuildNumberCreated()](#getBuildNumberCreated--) | 문서를 생성하는 데 사용된 인스턴스의 전체 빌드 번호를 포함합니다. |
| [getBuildNumberEdited()](#getBuildNumberEdited--) | 문서를 마지막으로 편집한 인스턴스의 빌드 번호를 포함합니다. |
| [getCategory()](#getCategory--) | 플로우차트 또는 사무실 레이아웃과 같은 도면 유형에 대한 설명 텍스트를 지정합니다. |
| [getClass()](#getClass--) |  |
| [getCompany()](#getCompany--) | 도면을 만든 회사 또는 도면이 제작되는 회사를 식별하는 사용자가 입력한 정보를 포함합니다. |
| [getCreator()](#getCreator--) | 파일을 만든 사람 또는 마지막으로 업데이트한 사람을 식별합니다. |
| [getCustomProps()](#getCustomProps--) | CustomProp 컬렉션. |
| [getDesc()](#getDesc--) | 문서에 대한 설명 텍스트 문자열을 포함합니다. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Microsoft Visio 다이어그램과의 관계로 연결된 파일 위치가 설명되는 상대 하이퍼링크에 사용할 경로를 포함합니다 (연결된 파일 위치가 Microsoft Visio 다이어그램과의 관계로 설명되는 상대 하이퍼링크). |
| [getKeywords()](#getKeywords--) | 프로젝트 이름, 클라이언트 이름 또는 버전 번호와 같이 파일에 대한 주제 또는 기타 중요한 정보를 식별하는 텍스트 문자열을 포함합니다. |
| [getLanguage()](#getLanguage--) | 언어를 지정합니다. |
| [getManager()](#getManager--) | 프로젝트 또는 부서의 담당자를 식별하는 사용자가 입력한 텍스트 문자열을 포함합니다. |
| [getPreviewPicture()](#getPreviewPicture--) | 문서의 미리보기 역할을 하는 메타파일 스트림을 포함합니다. |
| [getSubject()](#getSubject--) | 문서의 내용을 설명하는 사용자 정의 �스트 문자열을 포함합니다. |
| [getTemplate()](#getTemplate--) | 문서가 생성된 템플릿의 파일 이름을 지정하는 문자열 값을 포함합니다. |
| [getTimeCreated()](#getTimeCreated--) | 문서가 생성된 시점을 나타내는 날짜 및 시간 값을 포함합니다. |
| [getTimeEdited()](#getTimeEdited--) | 문서가 마지막으로 편집된 시점을 나타내는 날짜 및 시간 값을 포함합니다. |
| [getTimePrinted()](#getTimePrinted--) | 문서가 마지막으로 인쇄된 시점을 나타내는 날짜 및 시간 값을 포함합니다. |
| [getTimeSaved()](#getTimeSaved--) | 문서가 마지막으로 저장된 시점을 나타내는 날짜 및 시간 값을 포함합니다. |
| [getTitle()](#getTitle--) | 문서에 대한 설명적 제목으로 사용되는 사용자 정의 텍스트 문자열을 포함합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlternateNames(String value)](#setAlternateNames-java.lang.String-) | 이 속성에 대한 설명은 [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--)을(를) 참조하십시오. |
| [setBuildNumberCreated(String value)](#setBuildNumberCreated-java.lang.String-) | 이 속성에 대한 설명은 [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--)을(를) 참조하십시오. |
| [setBuildNumberEdited(String value)](#setBuildNumberEdited-java.lang.String-) | 이 속성에 대한 설명은 [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--)을(를) 참조하십시오. |
| [setCategory(String value)](#setCategory-java.lang.String-) | 이 속성에 대한 설명은 [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--)을(를) 참조하십시오. |
| [setCompany(String value)](#setCompany-java.lang.String-) | 이 속성에 대한 설명은 [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--)을(를) 참조하십시오. |
| [setCreator(String value)](#setCreator-java.lang.String-) | 이 속성에 대한 설명은 [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--)을(를) 참조하십시오. |
| [setDesc(String value)](#setDesc-java.lang.String-) | 이 속성에 대한 설명은 [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--)을(를) 참조하십시오. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | 이 속성에 대한 설명은 [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--)을(를) 참조하십시오. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | 이 속성에 대한 설명은 [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--)을(를) 참조하십시오. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | 이 속성에 대한 설명은 [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--)을(를) 참조하십시오. |
| [setManager(String value)](#setManager-java.lang.String-) | 이 속성에 대한 설명은 [getManager()](../../com.aspose.diagram/documentproperties\#getManager--)을(를) 참조하십시오. |
| [setPreviewPicture(byte[] value)](#setPreviewPicture-byte---) | 이 속성에 대한 설명은 [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--)을(를) 참조하십시오. |
| [setSubject(String value)](#setSubject-java.lang.String-) | 이 속성에 대한 설명은 [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--)을(를) 참조하십시오. |
| [setTemplate(String value)](#setTemplate-java.lang.String-) | 이 속성에 대한 설명은 [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--)을(를) 참조하십시오. |
| [setTimeCreated(DateTime value)](#setTimeCreated-com.aspose.diagram.DateTime-) | 이 속성에 대한 설명은 [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--)을(를) 참조하십시오. |
| [setTimeEdited(DateTime value)](#setTimeEdited-com.aspose.diagram.DateTime-) | 이 속성에 대한 설명은 [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--)을(를) 참조하십시오. |
| [setTimePrinted(DateTime value)](#setTimePrinted-com.aspose.diagram.DateTime-) | 이 속성에 대한 설명은 [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--)을(를) 참조하십시오. |
| [setTimeSaved(DateTime value)](#setTimeSaved-com.aspose.diagram.DateTime-) | 이 속성에 대한 설명은 [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--)을(를) 참조하십시오. |
| [setTitle(String value)](#setTitle-java.lang.String-) | 이 속성에 대한 설명은 [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--)을(를) 참조하십시오. |
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
### getAlternateNames() {#getAlternateNames--}
```
public String getAlternateNames()
```


문서에 대한 대체 이름을 지정합니다.

**Returns:**
java.lang.String
### getBuildNumberCreated() {#getBuildNumberCreated--}
```
public String getBuildNumberCreated()
```


문서를 생성하는 데 사용된 인스턴스의 전체 빌드 번호를 포함합니다.

**Returns:**
java.lang.String
### getBuildNumberEdited() {#getBuildNumberEdited--}
```
public String getBuildNumberEdited()
```


문서를 마지막으로 편집한 인스턴스의 빌드 번호를 포함합니다.

**Returns:**
java.lang.String
### getCategory() {#getCategory--}
```
public String getCategory()
```


플로우차트나 사무실 레이아웃과 같은 도면 유형에 대한 설명 텍스트를 지정합니다. 이 텍스트는 Microsoft Visio 사용자 인터페이스의 속성 대화 상자에 있는 카테고리 상자에도 입력할 수 있습니다.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompany() {#getCompany--}
```
public String getCompany()
```


도면을 작성하는 회사 또는 도면이 작성되는 회사를 식별하는 사용자가 입력한 정보를 포함합니다. 최대 길이는 63자입니다.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


파일을 만든 사람 또는 마지막으로 업데이트한 사람을 식별합니다. 최대 길이는 63자입니다.

**Returns:**
java.lang.String
### getCustomProps() {#getCustomProps--}
```
public CustomPropCollection getCustomProps()
```


CustomProp 컬렉션.

**Returns:**
[CustomPropCollection](../../com.aspose.diagram/custompropcollection)
### getDesc() {#getDesc--}
```
public String getDesc()
```


문서에 대한 설명 텍스트 문자열을 포함합니다. 이 요소를 사용하여 문서의 목적, 최근 변경 사항 또는 보류 중인 변경 사항과 같은 중요한 정보를 저장합니다. 최대 길이는 191자입니다.

**Returns:**
java.lang.String
### getHyperlinkBase() {#getHyperlinkBase--}
```
public String getHyperlinkBase()
```


상대 하이퍼링크에 사용할 경로를 포함합니다(링크된 파일 위치가 Microsoft Visio 다이어그램을 기준으로 설명되는 하이퍼링크). 기본적으로 하이퍼링크 경로는 이 요소에 다른 경로가 지정되지 않는 한 현재 문서를 기준으로 상대적입니다. 최대 길이는 256자입니다.

**Returns:**
java.lang.String
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


프로젝트 이름, 클라이언트 이름 또는 버전 번호와 같이 파일에 대한 주제 또는 기타 중요한 정보를 식별하는 텍스트 문자열을 포함합니다. 최대 문자열 길이는 63자입니다.

**Returns:**
java.lang.String
### getLanguage() {#getLanguage--}
```
public String getLanguage()
```


언어를 지정합니다.

```
setLanguage("en-GB");
         setLanguage("en-US");
```

**Returns:**
java.lang.String
### getManager() {#getManager--}
```
public String getManager()
```


프로젝트 또는 부서를 담당하는 사람을 식별하는 사용자가 입력한 텍스트 문자열을 포함합니다. 최대 길이는 63자입니다.

**Returns:**
java.lang.String
### getPreviewPicture() {#getPreviewPicture--}
```
public byte[] getPreviewPicture()
```


문서의 미리보기 역할을 하는 메타파일 스트림을 포함합니다.

**Returns:**
byte[]
### getSubject() {#getSubject--}
```
public String getSubject()
```


문서의 내용을 설명하는 사용자가 정의한 텍스트 문자열을 포함합니다. 최대 길이는 63자입니다.

**Returns:**
java.lang.String
### getTemplate() {#getTemplate--}
```
public String getTemplate()
```


문서가 생성된 템플릿의 파일 이름을 지정하는 문자열 값을 포함합니다.

**Returns:**
java.lang.String
### getTimeCreated() {#getTimeCreated--}
```
public DateTime getTimeCreated()
```


문서가 생성된 시점을 나타내는 날짜 및 시간 값을 포함합니다.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeEdited() {#getTimeEdited--}
```
public DateTime getTimeEdited()
```


문서가 마지막으로 편집된 시점을 나타내는 날짜 및 시간 값을 포함합니다.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimePrinted() {#getTimePrinted--}
```
public DateTime getTimePrinted()
```


문서가 마지막으로 인쇄된 시점을 나타내는 날짜 및 시간 값을 포함합니다.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeSaved() {#getTimeSaved--}
```
public DateTime getTimeSaved()
```


문서가 마지막으로 저장된 시점을 나타내는 날짜 및 시간 값을 포함합니다.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTitle() {#getTitle--}
```
public String getTitle()
```


문서에 대한 설명 제목으로 사용되는 사용자가 정의한 텍스트 문자열을 포함합니다. 최대 길이는 63자입니다.

**Returns:**
java.lang.String
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




### setAlternateNames(String value) {#setAlternateNames-java.lang.String-}
```
public void setAlternateNames(String value)
```


이 속성에 대한 설명은 [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setBuildNumberCreated(String value) {#setBuildNumberCreated-java.lang.String-}
```
public void setBuildNumberCreated(String value)
```


이 속성에 대한 설명은 [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setBuildNumberEdited(String value) {#setBuildNumberEdited-java.lang.String-}
```
public void setBuildNumberEdited(String value)
```


이 속성에 대한 설명은 [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setCategory(String value) {#setCategory-java.lang.String-}
```
public void setCategory(String value)
```


이 속성에 대한 설명은 [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setCompany(String value) {#setCompany-java.lang.String-}
```
public void setCompany(String value)
```


이 속성에 대한 설명은 [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


이 속성에 대한 설명은 [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDesc(String value) {#setDesc-java.lang.String-}
```
public void setDesc(String value)
```


이 속성에 대한 설명은 [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public void setHyperlinkBase(String value)
```


이 속성에 대한 설명은 [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


이 속성에 대한 설명은 [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public void setLanguage(String value)
```


이 속성에 대한 설명은 [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setManager(String value) {#setManager-java.lang.String-}
```
public void setManager(String value)
```


이 속성에 대한 설명은 [getManager()](../../com.aspose.diagram/documentproperties\#getManager--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPreviewPicture(byte[] value) {#setPreviewPicture-byte---}
```
public void setPreviewPicture(byte[] value)
```


이 속성에 대한 설명은 [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


이 속성에 대한 설명은 [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setTemplate(String value) {#setTemplate-java.lang.String-}
```
public void setTemplate(String value)
```


이 속성에 대한 설명은 [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setTimeCreated(DateTime value) {#setTimeCreated-com.aspose.diagram.DateTime-}
```
public void setTimeCreated(DateTime value)
```


이 속성에 대한 설명은 [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeEdited(DateTime value) {#setTimeEdited-com.aspose.diagram.DateTime-}
```
public void setTimeEdited(DateTime value)
```


이 속성에 대한 설명은 [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePrinted(DateTime value) {#setTimePrinted-com.aspose.diagram.DateTime-}
```
public void setTimePrinted(DateTime value)
```


이 속성에 대한 설명은 [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeSaved(DateTime value) {#setTimeSaved-com.aspose.diagram.DateTime-}
```
public void setTimeSaved(DateTime value)
```


이 속성에 대한 설명은 [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


이 속성에 대한 설명은 [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--)을(를) 참조하십시오.

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

