---
title: 도형
second_title: Aspose.Diagram for Java API 참조
description: 마스터 페이지 또는 그룹 도형 요소에 도형을 정의하는 요소를 포함합니다.
type: docs
weight: 355
url: /ko/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

마스터, 페이지 또는 그룹 도형 요소에서 도형을 정의하는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Shape()](#Shape--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [bringForward()](#bringForward--) | 도형을 Z-순서에서 한 단계 앞으로 이동합니다. |
| [bringToFront()](#bringToFront--) | 도형을 Z-순서의 앞쪽으로 이동합니다. |
| [centerDrawing()](#centerDrawing--) | 페이지 범위에 대해 도형을 가운데 정렬합니다. |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | 도형에 연결된 도형들의 식별자(ID)를 포함하는 배열을 반환합니다. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | 도형에 의존하는 도형들의 식별자를 포함하는 배열을 반환합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | ActiveX 컨트롤을 가져옵니다. |
| [getActs()](#getActs--) | Act 요소들의 컬렉션을 포함합니다. |
| [getAlign()](#getAlign--) | 도형이 고정된 가이드 또는 가이드 포인트에 대한 도형의 정렬을 나타냅니다. |
| [getChars()](#getChars--) | Char 요소의 컬렉션을 포함합니다. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | ConnectionABCD 요소의 컬렉션을 포함합니다. |
| [getConnections()](#getConnections--) | Connection 요소의 컬렉션을 포함합니다. |
| [getConnectorRule()](#getConnectorRule--) | 도형에 연결된 도형 ID와 연결 정보를 포함하는 connectorRule을 반환합니다. |
| [getConnectorsType()](#getConnectorsType--) | 연결자 유형을 가져옵니다. |
| [getControlData()](#getControlData--) | 컨트롤의 데이터를 가져옵니다. |
| [getControls()](#getControls--) | Control 요소들의 컬렉션을 포함합니다. |
| [getData1()](#getData1--) | 도형에 대한 추가 정보를 제공하는 임의의 문자열 값을 포함합니다. |
| [getData2()](#getData2--) | 도형에 대한 추가 정보를 제공하는 임의의 문자열 값을 포함합니다. |
| [getData3()](#getData3--) | 도형에 대한 추가 정보를 제공하는 임의의 문자열 값을 포함합니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. |
| [getDiagram()](#getDiagram--) | Visio 개체 계층 구조의 루트 요소. |
| [getDisplayText()](#getDisplayText--) | 인터페이스에 표시되는 텍스트를 가져옵니다. |
| [getEvent()](#getEvent--) | 도형 이벤트를 제어하는 수식을 지정하는 요소를 포함합니다. |
| [getFields()](#getFields--) | Field 요소들의 컬렉션을 포함합니다. |
| [getFill()](#getFill--) | 패턴, 전경색 및 배경색을 포함하여 도형 및 도형의 그림자에 대한 현재 채우기 서식 값을 포함합니다. |
| [getFillStyle()](#getFillStyle--) | 이 도형이 채우기 서식을 상속받는 StyleSheet입니다. |
| [getForeign()](#getForeign--) | Microsoft Visio 문서에서 사용되는 다른 프로그램의 객체 너비와 높이를 지정하는 요소를 포함합니다. |
| [getForeignData()](#getForeignData--) | Windows 메타파일, 비트맵 또는 OLE 데이터와 같은 그림 데이터의 MIME(다목적 인터넷 메일 확장) 인코딩 BLOB을 포함합니다. |
| [getGeoms()](#getGeoms--) | Geom 요소들의 컬렉션을 포함합니다. |
| [getGroup()](#getGroup--) | 그룹에 도형을 추가하고, 그룹 구성원을 이동하며, 그룹을 선택하는 방식을 제어하는 요소를 포함합니다. |
| [getHelp()](#getHelp--) | Shape 요소의 도움말 파일 주제와 저작권 정보를 지정하는 요소를 포함합니다. |
| [getHyperlinks()](#getHyperlinks--) | Hyperlink 요소들의 컬렉션을 포함합니다. |
| [getID()](#getID--) | 부모 요소 내에서 해당 요소의 고유 ID입니다. |
| [getImage()](#getImage--) | 비트맵에 대한 감마, 밝기, 대비, 흐림, 선명화, 노이즈 제거 및 투명도 값을 포함합니다. |
| [getInheritChars()](#getInheritChars--) | 마스터 도형에 의해 상속되는 도형의 문자 값을 포함합니다. |
| [getInheritFill()](#getInheritFill--) | 부모 스타일 및 마스터 도형에 의해 상속되는 도형의 채우기 서식 값을 포함합니다. |
| [getInheritGeoms()](#getInheritGeoms--) | 마스터 도형에 의해 상속되는 도형의 Geoms 값을 포함합니다. |
| [getInheritLine()](#getInheritLine--) | 부모 스타일 및 마스터 도형에 의해 상속되는 도형의 선 서식 값을 포함합니다. |
| [getInheritParas()](#getInheritParas--) | 부모 스타일 및 마스터 도형에 의해 상속되는 도형의 단락(paras)을 포함합니다. |
| [getInheritProps()](#getInheritProps--) | 마스터 도형에 의해 상속되는 도형의 속성(props)을 포함합니다. |
| [getInheritTextBlock()](#getInheritTextBlock--) | 부모 스타일 및 마스터 도형에 의해 상속되는 도형의 텍스트 블록 값을 포함합니다. |
| [getInheritUsers()](#getInheritUsers--) | 마스터 도형에 의해 상속되는 도형의 사용자(users)를 포함합니다. |
| [getLayerMem()](#getLayerMem--) | 도형이 할당된 각 레이어를 지정하는 LayerMember 요소를 포함합니다. |
| [getLayout()](#getLayout--) | 도형 배치 및 커넥터 라우팅 설정을 제어하는 요소를 포함합니다. |
| [getLine()](#getLine--) | 패턴, 두께 및 색상과 같은 도형의 선 속성을 제어하는 요소를 포함합니다. |
| [getLineStyle()](#getLineStyle--) | 이 도형이 선 서식을 상속받는 StyleSheet |
| [getMaster()](#getMaster--) | 도형이 데이터를 상속받는 마스터 |
| [getMasterShape()](#getMasterShape--) | 이 속성은 그룹 도형의 구성원이며 해당 그룹이 마스터의 인스턴스인 도형에만 존재할 수 있습니다. |
| [getMisc()](#getMisc--) | Shape 요소의 도움말 파일 주제와 저작권 정보를 지정하는 요소를 포함합니다. |
| [getName()](#getName--) | 요소의 이름입니다. |
| [getNameU()](#getNameU--) | 요소의 보편적인 이름입니다. |
| [getOneD()](#getOneD--) | 도형이 1차원(1-D) 객체로 동작하는지 여부를 결정합니다. |
| [getPage()](#getPage--) | Visio 개체 계층 구조의 루트 요소. |
| [getParas()](#getParas--) | Para 요소의 컬렉션을 포함합니다. |
| [getParentShape()](#getParentShape--) | 도형의 부모. |
| [getProps()](#getProps--) | Prop 요소들의 컬렉션을 포함합니다. |
| [getProtection()](#getProtection--) | 잠금은 도형에 대한 실수로 인한 변경을 방지하는 데 도움이 되지만 다른 상황에서 Microsoft Visio가 값을 재설정하는 것을 방지하지는 않습니다. |
| [getPureText()](#getPureText--) | 텍스트 문자열을 가져옵니다 |
| [getRootShape()](#getRootShape--) | 이 도형이 마스터 인스턴스의 일부인 경우 인스턴스의 최상위 도형을 반환합니다. |
| [getScratchs()](#getScratchs--) | Scratch 요소의 컬렉션을 포함합니다. |
| [getShapes()](#getShapes--) | Shape 요소들의 컬렉션을 포함합니다. |
| [getSmartTagDefs()](#getSmartTagDefs--) | SmartTagDef 요소들의 컬렉션을 포함합니다. |
| [getTabsCollection()](#getTabsCollection--) | Tab 요소의 컬렉션을 포함합니다. |
| [getText()](#getText--) | 도형의 텍스트를 포함합니다. |
| [getTextBlock()](#getTextBlock--) | 도형 텍스트 블록의 텍스트 정렬, 여백 및 기본 탭 정지 위치를 지정하는 요소를 포함합니다. |
| [getTextStyle()](#getTextStyle--) | 이 도형이 텍스트 서식을 상속받는 StyleSheet. |
| [getTextXForm()](#getTextXForm--) | 도형 텍스트 블록에 대한 위치 정보를 지정하는 요소를 포함합니다. |
| [getThreeDFormat()](#getThreeDFormat--) | ThreeDFormat을 가져옵니다. |
| [getTwoD()](#getTwoD--) | 도형이 2차원(2-D) 객체로 동작하는지 여부를 결정합니다. |
| [getType()](#getType--) | 도형의 유형. |
| [getUniqueID()](#getUniqueID--) | 도형에 할당된 GUID(전역 고유 식별자). |
| [getUsers()](#getUsers--) | User 요소의 컬렉션을 포함합니다. |
| [getXForm()](#getXForm--) | 도형에 대한 일반적인 위치 정보를 지정하는 요소를 포함합니다. |
| [getXForm1D()](#getXForm1D--) | 1차원 도형의 시작점과 끝점의 x 및 y 좌표를 포함합니다. |
| [getZOrderIndex()](#getZOrderIndex--) | 가이드 도형을 제외한 z-순서에서 도형의 인덱스를 반환합니다. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | 도형에 붙어 있는 도형들의 식별자를 포함하는 배열을 반환합니다. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | 이 두 도형이 연결되어 있는지 여부를 나타냅니다. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | 이 도형이 다른 도형을 포함하고 있는지 여부를 나타냅니다. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | 이 두 도형이 접착되어 있는지 여부를 나타냅니다. |
| [isInGroup()](#isInGroup--) | 이 도형이 그룹 도형에 포함되어 있는지 여부를 나타냅니다. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | 이 도형이 다른 도형과 교차하는지 여부를 나타냅니다. |
| [isTextEmpty()](#isTextEmpty--) | 도형에 텍스트가 있는지 및 텍스트가 비어 있는지 여부를 나타냅니다. |
| [move(double dX, double dY)](#move-double-double-) | 도형을 현재 위치에서 dX 및 dY 인치만큼 이동합니다. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | 도형을 페이지의 새로운 절대 위치로 이동합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | 도형의 텍스트 또는 기타 속성을 변경할 때 xform, 연결 및 geom을 포함한 도형 위치를 새로 고칩니다. |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | 도형의 텍스트 문자열을 교체합니다. |
| [sendBackward()](#sendBackward--) | 도형을 Z 순서에서 한 단계 뒤로 이동합니다. |
| [sendToBack()](#sendToBack--) | 도형을 Z 순서의 뒤쪽으로 이동합니다. |
| [setAngle(double angle)](#setAngle-double-) | 도형의 새로운 각도를 설정합니다. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | 이 속성에 대한 설명은 [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)을 참조하십시오. |
| [setConnectorsType(int type)](#setConnectorsType-int-) | 연결자 유형을 설정합니다. |
| [setData1(String value)](#setData1-java.lang.String-) | 이 속성에 대한 설명은 [getData1()](../../com.aspose.diagram/shape\#getData1--)을 참조하십시오. |
| [setData2(String value)](#setData2-java.lang.String-) | 이 속성에 대한 설명은 [getData2()](../../com.aspose.diagram/shape\#getData2--)을 참조하십시오. |
| [setData3(String value)](#setData3-java.lang.String-) | 이 속성에 대한 설명은 [getData3()](../../com.aspose.diagram/shape\#getData3--)을 참조하십시오. |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/shape\#getDel--)을 참조하십시오. |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | 이 속성에 대한 설명은 [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)을 참조하십시오. |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | 이 속성에 대한 설명은 [getEvent()](../../com.aspose.diagram/shape\#getEvent--)을 참조하십시오. |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | 이 속성에 대한 설명은 [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)을 참조하십시오. |
| [setHeight(double height)](#setHeight-double-) | 도형의 새로운 높이를 설정합니다. |
| [setID(long value)](#setID-long-) | 이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/shape\#getID--)을 참조하십시오. |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | 이 속성에 대한 설명은 [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)을 참조하십시오. |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | 이 속성에 대한 설명은 [getMaster()](../../com.aspose.diagram/shape\#getMaster--)을 참조하십시오. |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | 이 속성에 대한 설명은 [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)을 참조하십시오. |
| [setName(String value)](#setName-java.lang.String-) | 이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/shape\#getName--)을 참조하십시오. |
| [setNameU(String value)](#setNameU-java.lang.String-) | 이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/shape\#getNameU--)을 참조하십시오. |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | 이 속성에 대한 설명은 [getPage()](../../com.aspose.diagram/shape\#getPage--)를 참조하십시오. |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | 이 속성에 대한 설명은 [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)를 참조하십시오. |
| [setPresetTheme(int value)](#setPresetTheme-int-) | 이 도형에 사전 설정 테마를 적용합니다. |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | 이 도형에 사전 설정 테마 변형 퀵스타일을 적용합니다. |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | 이 도형에 사전 설정 테마 변형 퀵스타일을 적용합니다. 도형 스타일 드롭다운 목록의 테마 스타일 옵션과 같습니다. |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | 이 도형에 사전 설정 테마 변형을 적용합니다. |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | 이 속성에 대한 설명은 [getProps()](../../com.aspose.diagram/shape\#getProps--)를 참조하십시오. |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | 이 속성에 대한 설명은 [getText()](../../com.aspose.diagram/shape\#getText--)를 참조하십시오. |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | 이 속성에 대한 설명은 [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)를 참조하십시오. |
| [setTwoD(boolean value)](#setTwoD-boolean-) | 이 속성에 대한 설명은 [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)를 참조하십시오. |
| [setType(int value)](#setType-int-) | 이 속성에 대한 설명은 [getType()](../../com.aspose.diagram/shape\#getType--)를 참조하십시오. |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | 이 속성에 대한 설명은 [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)를 참조하십시오. |
| [setWidth(double width)](#setWidth-double-) | 도형의 새 너비를 설정합니다. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | 이 속성에 대한 설명은 [getXForm()](../../com.aspose.diagram/shape\#getXForm--)를 참조하십시오. |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | 이 속성에 대한 설명은 [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)를 참조하십시오. |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | 도형 HTML을 생성하고 지정된 형식으로 스트림에 저장합니다. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | 도형 HTML을 생성하고 지정된 형식으로 스트림에 저장합니다. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | HTML을 생성하고 파일에 저장합니다. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | 도형 이미지를 생성하고 지정된 형식으로 스트림에 저장합니다. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | 도형 이미지를 생성하고 지정된 형식으로 스트림에 저장합니다. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | 도형 이미지를 생성하고 파일에 저장합니다. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | 도형 PDF를 생성하고 스트림에 저장합니다. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | 도형 PDF를 생성하고 스트림에 저장합니다. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | 도형을 PDF 파일로 저장합니다. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | 도형을 SVG 파일로 저장합니다. |
| [ungroup()](#ungroup--) | 도형 그룹 해제 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


생성자.

### bringForward() {#bringForward--}
```
public void bringForward()
```


도형을 Z-순서에서 한 단계 앞으로 이동합니다.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


도형을 Z-순서의 앞쪽으로 이동합니다.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


페이지 범위에 대해 도형을 가운데 정렬합니다.

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


도형에 연결된 도형들의 식별자(ID)를 포함하는 배열을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 플래그 | int | 연결기의 방향성에 따라 반환된 shape ID 배열을 필터링합니다. 가능한 값은 Remarks를 참조하십시오Aspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | 지정된 categoryString과 일치하는 도형의 ID만 포함하도록 반환된 도형 ID 배열을 필터링합니다. |

**Returns:**
long[] - ID 배열 long.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


도형에 의존하는 도형들의 식별자를 포함하는 배열을 반환합니다.

**Returns:**
long[] - ID 배열 long.
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


ActiveX 컨트롤을 가져옵니다.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Act 요소들의 컬렉션을 포함합니다.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


도형이 붙어 있는 가이드 또는 가이드 포인트에 대한 도형의 정렬을 나타냅니다. Align 요소는 가이드 또는 가이드 포인트에 붙어 있는 도형에만 표시됩니다.

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Char 요소의 컬렉션을 포함합니다.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClippingPath() {#getClippingPath--}
```
public String getClippingPath()
```




**Returns:**
java.lang.String
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
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


도형에 연결된 도형 ID와 연결 정보를 포함하는 connectorRule을 반환합니다.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


연결자 유형을 가져옵니다.

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


컨트롤의 데이터를 가져옵니다.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Control 요소들의 컬렉션을 포함합니다.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


도형에 대한 추가 정보를 제공하는 임의의 문자열 값을 포함합니다.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


도형에 대한 추가 정보를 제공하는 임의의 문자열 값을 포함합니다.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


도형에 대한 추가 정보를 제공하는 임의의 문자열 값을 포함합니다.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값이 1이면 요소가 로컬에서 삭제된 것입니다.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Visio 개체 계층 구조의 루트 요소.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


인터페이스에 표시되는 텍스트를 가져옵니다.

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


도형 이벤트를 제어하는 수식을 지정하는 요소를 포함합니다.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Field 요소들의 컬렉션을 포함합니다.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


패턴, 전경색 및 배경색을 포함하여 도형 및 도형의 그림자에 대한 현재 채우기 서식 값을 포함합니다.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


이 도형이 채우기 서식을 상속받는 StyleSheet입니다.

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
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Geom 요소들의 컬렉션을 포함합니다.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


그룹에 도형을 추가하고, 그룹 구성원을 이동하며, 그룹을 선택하는 방식을 제어하는 요소를 포함합니다.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Shape 요소의 도움말 파일 주제와 저작권 정보를 지정하는 요소를 포함합니다.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Hyperlink 요소들의 컬렉션을 포함합니다.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


부모 요소 내에서 해당 요소의 고유 ID입니다.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


비트맵에 대한 감마, 밝기, 대비, 흐림, 선명화, 노이즈 제거 및 투명도 값을 포함합니다.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


마스터 도형에 의해 상속되는 도형의 문자 값을 포함합니다.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


부모 스타일 및 마스터 도형에 의해 상속되는 도형의 채우기 서식 값을 포함합니다.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


마스터 도형에 의해 상속되는 도형의 Geoms 값을 포함합니다.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


부모 스타일 및 마스터 도형에 의해 상속되는 도형의 선 서식 값을 포함합니다.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


부모 스타일 및 마스터 도형에 의해 상속되는 도형의 단락(paras)을 포함합니다.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


마스터 도형에 의해 상속되는 도형의 속성(props)을 포함합니다.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


부모 스타일 및 마스터 도형에 의해 상속되는 도형의 텍스트 블록 값을 포함합니다.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


마스터 도형에 의해 상속되는 도형의 사용자(users)를 포함합니다.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


도형이 할당된 각 레이어를 지정하는 LayerMember 요소를 포함합니다.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


도형 배치 및 커넥터 라우팅 설정을 제어하는 요소를 포함합니다.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


모양의 선 속성을 제어하는 요소들을 포함합니다. 예를 들어 패턴, 두께, 색상 등이 있습니다. 이러한 요소들은 선 끝이 형식화되는지 여부(예: 화살표 머리), 선 끝 형식의 크기, 선에 적용되는 둥근 원의 반경, 그리고 선 캡 스타일(둥근 또는 사각)을 결정합니다.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


이 도형이 선 서식을 상속받는 StyleSheet

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


도형이 데이터를 상속받는 마스터

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


이 속성은 그룹 도형의 구성원이며 해당 그룹이 마스터의 인스턴스인 도형에만 존재할 수 있습니다. 이 속성은 마스터에서 해당 하위 도형을 참조하는 ID를 포함합니다.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Shape 요소의 도움말 파일 주제와 저작권 정보를 지정하는 요소를 포함합니다.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
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
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


도형이 1차원(1-D) 객체로 동작하는지 여부를 결정합니다. 읽기 전용.

**Returns:**
boolean
### getPage() {#getPage--}
```
public Page getPage()
```


Visio 개체 계층 구조의 루트 요소.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Para 요소의 컬렉션을 포함합니다.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


도형의 부모.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Prop 요소들의 컬렉션을 포함합니다.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


잠금은 모양에 대한 의도치 않은 변경을 방지하는 데 도움이 되지만, 다른 상황에서 Microsoft Visio가 값을 재설정하는 것을 방지하지는 않습니다. 또한 ShapeSheet 창에서 이루어지는 변경으로부터 보호하지도 않습니다.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


텍스트 문자열을 가져옵니다

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


이 도형이 마스터 인스턴스의 일부인 경우 인스턴스의 최상위 도형을 반환합니다. 읽기 전용.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Scratch 요소의 컬렉션을 포함합니다.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Shape 요소들의 컬렉션을 포함합니다.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


SmartTagDef 요소들의 컬렉션을 포함합니다.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Tab 요소의 컬렉션을 포함합니다.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


도형의 텍스트를 포함합니다.

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


도형 텍스트 블록의 텍스트 정렬, 여백 및 기본 탭 정지 위치를 지정하는 요소를 포함합니다.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


이 도형이 텍스트 서식을 상속받는 StyleSheet.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


도형 텍스트 블록에 대한 위치 정보를 지정하는 요소를 포함합니다.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


ThreeDFormat을 가져옵니다.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


도형이 2차원(2-D) 객체로 동작하는지 여부를 결정합니다.

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


도형의 유형입니다. 다음 값 중 하나일 수 있습니다: Group, Shape, Guide, 또는 Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


도형에 할당된 GUID(전역 고유 식별자).

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
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


1-D 도형의 시작점과 끝점의 x 및 y 좌표를 포함합니다. 이 요소는 1-D 도형에만 나타납니다.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


가이드 도형을 제외한 z-순서에서 도형의 인덱스를 반환합니다.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


도형에 붙어 있는 도형들의 식별자를 포함하는 배열을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 플래그 | int | 반환할 도형의 연결 지점의 차원 및 방향성입니다. 가능한 값은 Remarks를 참조하십시오 Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | 지정된 categoryString과 일치하는 도형의 ID만 포함하도록 반환된 도형 ID 배열을 필터링합니다. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | 옵션: 반환된 도형이 추가로 붙어 있어야 하는 추가 도형이며, [Shape](../../com.aspose.diagram/shape) 또는 null일 수 있습니다. |

**Returns:**
long[] - ID 배열 long.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isConnected(Shape shape) {#isConnected-com.aspose.diagram.Shape-}
```
public boolean isConnected(Shape shape)
```


이 두 도형이 연결되어 있는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


이 도형이 다른 도형을 포함하고 있는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


이 두 도형이 접착되어 있는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


이 도형이 그룹 도형에 포함되어 있는지 여부를 나타냅니다.

**Returns:**
boolean
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


이 도형이 다른 도형과 교차하는지 여부를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


도형에 텍스트가 있는지 및 텍스트가 비어 있는지 여부를 나타냅니다.

**Returns:**
boolean
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


도형을 현재 위치에서 dX 및 dY 인치만큼 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dX | double | X 오프셋 double. |
| dY | double | Y 오프셋 double. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


도형을 페이지의 새로운 절대 위치로 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newPinX | double | 부모의 원점에 대한 도형 핀(회전 중심)의 새로운 x 좌표입니다. double. |
| newPinY | double | 부모의 원점에 대한 도형 핀(회전 중심)의 새로운 y 좌표입니다. double. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshData() {#refreshData--}
```
public void refreshData()
```


도형의 텍스트 또는 기타 속성을 변경할 때 xform, connection 및 geom을 포함한 도형 위치를 새로 고칩니다. 도형 텍스트와 같은 도형 데이터를 수집한 후 도형 위치를 계산합니다. 이 메서드는 도형 데이터를 새로 고치는 데만 사용됩니다.

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


도형의 텍스트 문자열을 교체합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


도형을 Z 순서에서 한 단계 뒤로 이동합니다.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


도형을 Z 순서의 뒤쪽으로 이동합니다.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


도형의 새로운 각도를 설정합니다. 각도의 단위는 라디안입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| angle | double | 새로운 각도(단위는 라디안이며 degree가 아님) double. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


이 속성에 대한 설명은 [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


연결자 유형을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 유형 | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


이 속성에 대한 설명은 [getData1()](../../com.aspose.diagram/shape\#getData1--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


이 속성에 대한 설명은 [getData2()](../../com.aspose.diagram/shape\#getData2--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


이 속성에 대한 설명은 [getData3()](../../com.aspose.diagram/shape\#getData3--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/shape\#getDel--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


이 속성에 대한 설명은 [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


이 속성에 대한 설명은 [getEvent()](../../com.aspose.diagram/shape\#getEvent--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


이 속성에 대한 설명은 [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


도형의 새로운 높이를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| height | double | New heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/shape\#getID--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


이 속성에 대한 설명은 [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


이 속성에 대한 설명은 [getMaster()](../../com.aspose.diagram/shape\#getMaster--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


이 속성에 대한 설명은 [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/shape\#getName--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/shape\#getNameU--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


이 속성에 대한 설명은 [getPage()](../../com.aspose.diagram/shape\#getPage--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


이 속성에 대한 설명은 [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


이 도형에 사전 설정 테마를 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


이 도형에 사전 설정 테마 변형 퀵스타일을 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


이 도형에 사전 설정 테마 변형 퀵스타일을 적용합니다. 도형 스타일 드롭다운 목록의 테마 스타일 옵션과 같습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| styleIndex | int | the row of style matrics |
| colorIndex | int | the column of style matrics |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


이 도형에 사전 설정 테마 변형을 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


이 속성에 대한 설명은 [getProps()](../../com.aspose.diagram/shape\#getProps--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


이 속성에 대한 설명은 [getText()](../../com.aspose.diagram/shape\#getText--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


이 속성에 대한 설명은 [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


이 속성에 대한 설명은 [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


이 속성에 대한 설명은 [getType()](../../com.aspose.diagram/shape\#getType--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


이 속성에 대한 설명은 [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


도형의 새 너비를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| width | double | New widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


이 속성에 대한 설명은 [getXForm()](../../com.aspose.diagram/shape\#getXForm--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


이 속성에 대한 설명은 [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


도형 HTML을 생성하고 지정된 형식으로 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


도형 HTML을 생성하고 지정된 형식으로 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


HTML을 생성하고 파일에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html save options |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


도형 이미지를 생성하고 지정된 형식으로 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


도형 이미지를 생성하고 지정된 형식으로 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageFile | java.lang.String | The image file name with full path. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


도형 PDF를 생성하고 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | The output stream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


도형 PDF를 생성하고 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream | The output stream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


도형을 PDF 파일로 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | the pdf file name with full path |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toSvg(String imageFile, SVGSaveOptions options) {#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-}
```
public void toSvg(String imageFile, SVGSaveOptions options)
```


도형을 SVG 파일로 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


도형 그룹 해제

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

