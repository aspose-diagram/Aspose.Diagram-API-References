---
title: PageSheet
second_title: Aspose.Diagram for Java API 참조
description: 페이지 또는 마스터 요소에 대한 페이지 시트를 정의하는 요소를 포함합니다.
type: docs
weight: 270
url: /ko/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

페이지 또는 마스터 요소에 대한 페이지 시트를 정의하는 요소를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | 소스 객체에서 페이지시트를 복사합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | Act 요소들의 컬렉션을 포함합니다. |
| [getAnnotations()](#getAnnotations--) | 문서 페이지에 삽입된 주석에 대한 정보를 포함하는 요소를 포함합니다. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | ConnectionABCD 요소의 컬렉션을 포함합니다. |
| [getConnections()](#getConnections--) | Connection 요소의 컬렉션을 포함합니다. |
| [getFillStyle()](#getFillStyle--) | PageSheet가 채우기 서식을 상속받는 StyleSheet 요소. |
| [getForeign()](#getForeign--) | Microsoft Visio 문서에서 사용되는 다른 프로그램의 객체 너비와 높이를 지정하는 요소를 포함합니다. |
| [getForeignData()](#getForeignData--) | Windows 메타파일, 비트맵 또는 OLE 데이터와 같은 그림 데이터의 MIME(다목적 인터넷 메일 확장) 인코딩 BLOB을 포함합니다. |
| [getHyperlinks()](#getHyperlinks--) | Hyperlink 요소들의 컬렉션을 포함합니다. |
| [getLayers()](#getLayers--) | Layer 요소들의 컬렉션을 포함합니다. |
| [getLineStyle()](#getLineStyle--) | PageSheet가 선 서식을 상속받는 StyleSheet 요소. |
| [getPageLayout()](#getPageLayout--) | 페이지의 도형 및 커넥터에 대한 레이아웃 설정을 제어하는 Diagram을 포함합니다. 여기에는 페이지 내 모든 도형 사이의 간격, 모든 커넥터 사이의 간격, 그리고 모든 커넥터의 라우팅 스타일이 포함됩니다. |
| [getPageProps()](#getPageProps--) | 페이지 너비, 높이 및 축척과 같은 페이지 속성을 제어하는 Diagram을 포함합니다. |
| [getPrintProps()](#getPrintProps--) | 그리기 페이지가 프린터 페이지에 어떻게 형식이 지정되는지(표시되는지) 제어하는 요소를 포함합니다. |
| [getProps()](#getProps--) | Prop 요소들의 컬렉션을 포함합니다. |
| [getRulerGrid()](#getRulerGrid--) | 페이지 눈금자와 격자 설정을 지정하는 요소를 포함합니다. |
| [getScratchs()](#getScratchs--) | Scratch 요소의 컬렉션을 포함합니다. |
| [getSmartTagDefs()](#getSmartTagDefs--) | SmartTagDef 요소들의 컬렉션을 포함합니다. |
| [getTextStyle()](#getTextStyle--) | PageSheet가 텍스트 서식을 상속받는 StyleSheet 요소. |
| [getUniqueID()](#getUniqueID--) | 요소에 대한 GUID(전역 고유 식별자)입니다. |
| [getUsers()](#getUsers--) | User 요소의 컬렉션을 포함합니다. |
| [getXForm()](#getXForm--) | 도형에 대한 일반적인 위치 정보를 지정하는 요소를 포함합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | 이 속성에 대한 설명은 [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--)을 참조하십시오. |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | 이 속성에 대한 설명은 [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--)을 참조하십시오. |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### copy(PageSheet source) {#copy-com.aspose.diagram.PageSheet-}
```
public void copy(PageSheet source)
```


소스 객체에서 페이지시트를 복사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | source pagesheet. |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Act 요소들의 컬렉션을 포함합니다.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
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
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


PageSheet가 채우기 서식을 상속받는 StyleSheet 요소.

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
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


Layer 요소들의 컬렉션을 포함합니다.

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


PageSheet가 선 서식을 상속받는 StyleSheet 요소.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


페이지의 도형 및 커넥터에 대한 레이아웃 설정을 제어하는 Diagram을 포함합니다. 여기에는 페이지 내 모든 도형 사이의 간격, 모든 커넥터 사이의 간격, 그리고 모든 커넥터의 라우팅 스타일이 포함됩니다.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


페이지 너비, 높이 및 축척과 같은 페이지 속성을 제어하는 Diagram을 포함합니다.

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


그리기 페이지가 프린터 페이지에 어떻게 형식이 지정되는지(표시되는지) 제어하는 요소를 포함합니다.

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Prop 요소들의 컬렉션을 포함합니다.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


페이지 눈금자와 격자 설정을 지정하는 요소를 포함합니다.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Scratch 요소의 컬렉션을 포함합니다.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


SmartTagDef 요소들의 컬렉션을 포함합니다.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


PageSheet가 텍스트 서식을 상속받는 StyleSheet 요소.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


요소에 대한 GUID(전역 고유 식별자)입니다.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


User 요소의 컬렉션을 포함합니다.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


도형에 대한 일반적인 위치 정보를 지정하는 요소를 포함합니다.

**Returns:**
[XForm](../../com.aspose.diagram/xform)
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


이 속성에 대한 설명은 [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


이 속성에 대한 설명은 [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

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

