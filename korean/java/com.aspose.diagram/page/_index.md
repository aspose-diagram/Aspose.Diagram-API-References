---
title: Page
second_title: Aspose.Diagram for Java API 참조
description: 문서에서 페이지를 정의하는 요소를 포함합니다.
type: docs
weight: 260
url: /ko/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

문서에서 페이지를 정의하는 요소를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Page()](#Page--) | 생성자. |
| [Page(int ID)](#Page-int-) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Activex 컨트롤을 생성합니다. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | 도형에 주석을 추가합니다. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | 정의된 PinX 및 PinY와 함께 주석을 추가합니다. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | 도형의 ID와 함께 도형에 주석을 추가합니다. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | 마스터에서 만든 도형을 특정 페이지에 추가합니다. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | 정의된 PinX, PinY, Width 및 Height를 사용하여 페이지에 마스터에서 만든 도형을 추가합니다. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | 정의된 PinX 및 PinY를 사용하여 페이지에 마스터에서 만든 도형을 추가합니다. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | 정의된 PinX 및 PinY와 함께 텍스트를 추가합니다. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | 정의된 PinX 및 PinY와 함께 텍스트를 추가합니다. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | 전체 페이지에 스타일을 적용합니다. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | 도형 자동 간격 |
| [bringForward(long shapeId)](#bringForward-long-) | ID로 정의된 도형을 Z-순서에서 한 단계 앞으로 이동합니다. |
| [bringToFront(long shapeId)](#bringToFront-long-) | ID로 정의된 도형을 Z-순서의 앞쪽으로 이동합니다. |
| [centerDrawing()](#centerDrawing--) | 페이지의 범위에 맞춰 페이지 내 도형을 중앙에 배치합니다. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | 연결자를 사용하여 도형을 연결합니다. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | 연결자를 사용하여 도형을 연결합니다. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | 연결자를 사용하여 도형을 연결합니다. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | 연결자 인덱스를 사용하여 도형을 연결합니다. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | 연결자 인덱스를 사용하여 도형을 연결합니다. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | 타원을 그리는 과정입니다. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | 단일 선을 그리는 과정입니다. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | 선을 그리는 과정입니다. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | 폴리라인을 그리는 과정입니다. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | 사각형을 그리는 과정입니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | 그림 검토자들이 별도의 마크업 오버레이에 표시한 원본 도면 페이지의 ID. |
| [getBackPage()](#getBackPage--) | 페이지의 배경 페이지. |
| [getBackground()](#getBackground--) | 페이지가 배경 페이지인지 여부를 나타내는 플래그. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | 그림에서 두 도형 사이의 각 연결에 대한 Connect 요소를 포함합니다. |
| [getID()](#getID--) | 부모 요소 내에서 해당 요소의 고유 ID입니다. |
| [getName()](#getName--) | 요소의 이름입니다. |
| [getNameU()](#getNameU--) | 요소의 보편적인 이름입니다. |
| [getPageSheet()](#getPageSheet--) | 페이지 또는 마스터 요소에 대한 페이지 시트를 정의하는 요소를 포함합니다. |
| [getPages()](#getPages--) | 페이지 컬렉션. |
| [getReviewerID()](#getReviewerID--) | 마크업 오버레이와 연결된 검토자의 ID. |
| [getShapes()](#getShapes--) | 도형 컬렉션. |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX와 ViewCenterY는 새 뷰(창)가 처음 열릴 때 페이지에서 가정하는 중심점을 지정합니다. |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX와 ViewCenterY는 새 뷰(창)가 처음 열릴 때 페이지에서 가정하는 중심점을 지정합니다. |
| [getViewScale()](#getViewScale--) | 페이지의 새 뷰(창)가 열릴 때 사용할 기본 확대 배율. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | Connector의 BeginX에 도형을 붙이기 |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | Connector의 EndX에 도형을 붙이기 |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | 도형을 붙이기. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | 도형을 붙이기 |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | 컨테이너 내 도형을 붙이기 |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | 연결 이름을 사용하여 컨테이너 내 도형을 붙이기 |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | 연결 ID로 컨테이너 내 도형을 붙이기 |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | 페이지의 도형을 배치하고/또는 커넥터를 재배치합니다. |
| [moveTo(int index)](#moveTo-int-) | 페이지를 페이지 목록의 다른 위치로 이동합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | ID로 정의된 도형을 Z-순서에서 한 단계 뒤로 이동합니다. |
| [sendToBack(long shapeId)](#sendToBack-long-) | ID로 정의된 도형을 Z-순서의 가장 뒤로 이동합니다. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | 이 속성에 대한 설명은 [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)을(를) 참조하십시오. |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | 이 속성에 대한 설명은 [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)을(를) 참조하십시오. |
| [setBackground(int value)](#setBackground-int-) | 이 속성에 대한 설명은 [getBackground()](../../com.aspose.diagram/page\#getBackground--)을(를) 참조하십시오. |
| [setID(int value)](#setID-int-) | 이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/page\#getID--)을(를) 참조하십시오. |
| [setName(String value)](#setName-java.lang.String-) | 이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/page\#getName--)을(를) 참조하십시오. |
| [setNameU(String value)](#setNameU-java.lang.String-) | 이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/page\#getNameU--)을(를) 참조하십시오. |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | 이 속성에 대한 설명은 [getPages()](../../com.aspose.diagram/page\#getPages--)을(를) 참조하십시오. |
| [setPresetTheme(int value)](#setPresetTheme-int-) | 이 페이지에 사전 설정된 테마를 적용합니다. |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | 이 페이지에 사전 설정된 테마 변형 퀵스타일을 적용합니다. |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | 이 페이지에 사전 설정된 테마 변형을 적용합니다. |
| [setReviewerID(int value)](#setReviewerID-int-) | 이 속성에 대한 설명은 [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)을(를) 참조하십시오. |
| [setViewCenterX(double value)](#setViewCenterX-double-) | 이 속성에 대한 설명은 [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)을(를) 참조하십시오. |
| [setViewCenterY(double value)](#setViewCenterY-double-) | 이 속성에 대한 설명은 [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)을(를) 참조하십시오. |
| [setViewScale(double value)](#setViewScale-double-) | 이 속성에 대한 설명은 [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


생성자.

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


생성자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Activex 컨트롤을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 유형 | int | 컨트롤의 유형입니다. |
| pinX | double | 페이지와 관련하여 도형 핀(회전 중심)의 x 좌표를 지정합니다. |
| pinY | double | 페이지와 관련하여 도형 핀(회전 중심)의 y 좌표를 지정합니다. |
| width | double | 도형의 너비를 인치 단위로 지정합니다. |
| height | double | 도형의 높이를 인치 단위로 지정합니다. |

**Returns:**
long -
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


도형에 주석을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | 주석을 추가하는 도형을 지정합니다. |
| comment | java.lang.String | 주석 문자열입니다. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


정의된 PinX 및 PinY와 함께 주석을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double | 페이지와 관련하여 주석 핀(회전 중심)의 x 좌표를 지정합니다. |
| pinY | double | 페이지와 관련하여 주석 핀(회전 중심)의 y 좌표를 지정합니다. |
| comment | java.lang.String | 주석 문자열입니다. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


도형의 ID와 함께 도형에 주석을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | 주석 문자열입니다. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


마스터에서 만든 도형을 특정 페이지에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | 새 도형 객체[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | 마스터 이름입니다. |

**Returns:**
long - 지정된 페이지의 도형 컬렉션 내에서 도형의 고유 ID입니다.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| 스트림 | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| imageStream | java.io.InputStream |  |
| objectDataStream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, String masterName) {#addShape-double-double-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName)
```


정의된 PinX, PinY, Width 및 Height를 사용하여 페이지에 마스터에서 만든 도형을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double | 페이지와 관련하여 도형 핀(회전 중심)의 x 좌표를 지정합니다. |
| pinY | double | 페이지와 관련하여 도형 핀(회전 중심)의 y 좌표를 지정합니다. |
| width | double | 도형의 너비를 인치 단위로 지정합니다. |
| height | double | 도형의 높이를 인치 단위로 지정합니다. |
| masterName | java.lang.String | 마스터 이름입니다. |

**Returns:**
long - 지정된 페이지의 도형 컬렉션 내에서 도형의 고유 ID입니다.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


정의된 PinX 및 PinY를 사용하여 페이지에 마스터에서 만든 도형을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double | 페이지와 관련하여 도형 핀(회전 중심)의 x 좌표를 지정합니다. |
| pinY | double | 페이지와 관련하여 도형 핀(회전 중심)의 y 좌표를 지정합니다. |
| masterName | java.lang.String | 마스터 이름입니다. |

**Returns:**
long - 지정된 페이지의 도형 컬렉션 내에서 도형의 고유 ID입니다.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


정의된 PinX 및 PinY와 함께 텍스트를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double | 페이지와 관련하여 텍스트 핀(회전 중심)의 x좌표를 지정합니다. |
| pinY | double | 페이지와 관련하여 텍스트 핀(회전 중심)의 y좌표를 지정합니다. |
| width | double |  |
| height | double |  |
| text | java.lang.String | 텍스트 문자열. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


정의된 PinX 및 PinY와 함께 텍스트를 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double | 페이지와 관련하여 텍스트 핀(회전 중심)의 x좌표를 지정합니다. |
| pinY | double | 페이지와 관련하여 텍스트 핀(회전 중심)의 y좌표를 지정합니다. |
| width | double | 텍스트의 너비를 지정합니다. |
| height | double | 텍스트의 높이를 지정합니다. |
| text | java.lang.String | 텍스트 문자열. |
| fontName | java.lang.String | 텍스트 글꼴 이름. |
| fontColor | java.lang.String | 텍스트 글꼴 색상. |
| size | double | 텍스트 글꼴 크기. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


전체 페이지에 스타일을 적용합니다. 기본값은 -1입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| textStyle | int | 텍스트 스타일 ID. |
| lineStyle | int | 선 스타일 ID. |
| fillStyle | int | 채우기 스타일 ID. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


도형 자동 간격

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | 도형이 자동으로 간격을 두도록 지정합니다. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


ID로 정의된 도형을 Z-순서에서 한 단계 앞으로 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeId | long | shape.long의 ID |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


ID로 정의된 도형을 Z-순서의 앞쪽으로 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeId | long | shape.long의 ID |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


페이지의 범위에 따라 페이지의 도형을 중앙에 배치합니다. 도형을 중앙에 배치해도 서로 간의 위치는 변경되지 않습니다.

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


연결자를 사용하여 도형을 연결합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | 연결기가 시작되는 도형 [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | 연결기가 연결될 첫 번째 도형의 위치 Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | 연결기가 끝나는 도형 [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | 연결기가 연결될 두 번째 도형의 위치 Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | Dynamic connector 유형을 가진 도형 [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


연결자를 사용하여 도형을 연결합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeFromId | long | 연결기가 시작되는 도형의 ID [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | 연결기가 연결될 첫 번째 도형의 위치 Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | 연결기가 끝나는 도형의 ID [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | 연결기가 연결될 두 번째 도형의 위치 Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | Dynamic connector 유형을 가진 도형의 ID [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


연결자를 사용하여 도형을 연결합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeFromId | long | 연결기가 시작되는 도형의 ID [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | 연결기가 연결될 첫 번째 도형의 연결 이름. |
| shapeToId | long | 연결기가 끝나는 도형의 ID [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | 연결기가 연결될 두 번째 도형의 연결 이름. |
| connectorId | long | Dynamic connector 유형을 가진 도형의 ID [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


연결자 인덱스를 사용하여 도형을 연결합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | 연결기가 시작되는 도형 [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | 첫 번째 도형의 연결 인덱스 |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | 연결기가 끝나는 도형 [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | 두 번째 도형의 연결 인덱스 |
| connector | [Shape](../../com.aspose.diagram/shape) | Dynamic connector 유형을 가진 도형 [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


연결자 인덱스를 사용하여 도형을 연결합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeFromId | long | 연결기가 시작되는 도형의 ID [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | 첫 번째 도형의 연결 인덱스 |
| shapeToId | long | 연결기가 끝나는 도형의 ID [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | 두 번째 도형의 연결 인덱스 |
| connectorId | long | Dynamic connector 유형을 가진 도형의 ID [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


타원을 그리는 과정입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double | 페이지와 관련하여 도형 핀(회전 중심)의 x 좌표를 지정합니다. |
| pinY | double | 페이지와 관련하여 도형 핀(회전 중심)의 y 좌표를 지정합니다. |
| width | double | 도형의 너비를 지정합니다 |
| height | double | 도형의 높이를 지정합니다 |

**Returns:**
long -
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


단일 선을 그리는 과정입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| beginX | double | 페이지에 대한 도형 위치의 시작 x좌표를 지정합니다. |
| beginY | double | 페이지에 대한 도형 위치의 시작 y좌표를 지정합니다. |
| endX | double | 페이지에 대한 도형 위치의 끝 x좌표를 지정합니다. |
| endY | double | 페이지와 관련된 도형 위치의 끝 y좌표를 지정합니다. |

**Returns:**
long - 지정된 페이지의 도형 컬렉션 내에서 도형의 고유 ID입니다.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


선을 그리는 과정입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double | 페이지와 관련하여 도형 핀(회전 중심)의 x 좌표를 지정합니다. |
| pinY | double | 페이지와 관련하여 도형 핀(회전 중심)의 y 좌표를 지정합니다. |
| width | double | 도형의 너비를 지정합니다 |
| height | double | 도형의 높이를 지정합니다 |
| xyArray | double[] | 새 도형의 점을 정의하는 교차되는 x 및 y 값 배열입니다. |

**Returns:**
long - 지정된 페이지의 도형 컬렉션 내에서 도형의 고유 ID입니다.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


폴리라인을 그리는 과정입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double | 페이지와 관련하여 도형 핀(회전 중심)의 x 좌표를 지정합니다. |
| pinY | double | 페이지와 관련하여 도형 핀(회전 중심)의 y 좌표를 지정합니다. |
| width | double | 도형의 너비를 지정합니다 |
| height | double | 도형의 높이를 지정합니다 |
| xyArray | double[] | 새 도형의 점을 정의하는 교차되는 x 및 y 값 배열입니다. |

**Returns:**
long - 지정된 페이지의 도형 컬렉션 내에서 도형의 고유 ID입니다.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


사각형을 그리는 과정입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double | 페이지와 관련하여 도형 핀(회전 중심)의 x 좌표를 지정합니다. |
| pinY | double | 페이지와 관련하여 도형 핀(회전 중심)의 y 좌표를 지정합니다. |
| width | double | 도형의 너비를 지정합니다 |
| height | double | 도형의 높이를 지정합니다 |

**Returns:**
long - 지정된 페이지의 도형 컬렉션 내에서 도형의 고유 ID입니다.
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
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


그림 검토자들이 별도의 마크업 오버레이에 표시한 원본 도면 페이지의 ID.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


페이지의 배경 페이지.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


페이지가 배경 페이지인지 여부를 나타내는 플래그.

**Returns:**
int
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
### getID() {#getID--}
```
public int getID()
```


부모 요소 내에서 해당 요소의 고유 ID입니다.

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
### getPages() {#getPages--}
```
public PageCollection getPages()
```


페이지 컬렉션.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


마크업 오버레이와 연결된 검토자의 ID.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


도형 컬렉션.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX와 ViewCenterY는 새 뷰(창)가 처음 열릴 때 페이지에서 가정하는 중심점을 지정합니다.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX와 ViewCenterY는 새 뷰(창)가 처음 열릴 때 페이지에서 가정하는 중심점을 지정합니다.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


페이지의 새 보기(창)가 열릴 때 사용할 기본 확대 비율입니다. 예를 들어, 1 = 100%; 1.5 = 150% 등입니다.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


Connector의 BeginX에 도형을 붙이기

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeFromId | long | 연결기가 시작되는 도형의 ID [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | 연결기가 연결될 도형의 연결 이름입니다. |
| connectorId | long | Dynamic connector 유형을 가진 도형의 ID [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


Connector의 EndX에 도형을 붙이기

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeToId | long | 연결기가 끝나는 도형의 ID [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | 연결기가 연결될 두 번째 도형의 연결 이름. |
| connectorId | long | Dynamic connector 유형을 가진 도형의 ID [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


도형을 붙이기.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | [Shape](../../com.aspose.diagram/shape)에서 접착되는 도형입니다. |
| placeTo | int | 첫 번째 도형에서 Aspose.Diagram.Manipulation.ConnectionPointPlace를 접착할 위치입니다. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | [Shape](../../com.aspose.diagram/shape)로 접착할 도형입니다. |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


도형을 붙이기

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeFromId | long | [Shape](../../com.aspose.diagram/shape)에서 접착되는 도형의 ID입니다. |
| placeTo | int | 첫 번째 도형에서 Aspose.Diagram.Manipulation.ConnectionPointPlace를 접착할 위치입니다. |
| shapeToId | long | [Shape](../../com.aspose.diagram/shape)로 접착할 도형의 ID입니다. |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


컨테이너 내 도형을 붙이기

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeFromId | long | [Shape](../../com.aspose.diagram/shape)에서 접착되는 도형의 ID입니다. |
| shapeToBeginConnectionIndex | int | 첫 번째 연결 인덱스에서 접착할 위치입니다. |
| shapeToEndConnectionIndex | int | 끝 연결 인덱스에서 접착할 위치입니다. |
| shapeToId | long | [Shape](../../com.aspose.diagram/shape)로 접착할 도형의 ID입니다. |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


연결 이름을 사용하여 컨테이너 내 도형을 붙이기

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeFromId | long | [Shape](../../com.aspose.diagram/shape)에서 접착되는 도형의 ID입니다. |
| shapeToBeginConnectionName | java.lang.String | 첫 번째 연결 이름에서 접착할 위치입니다. |
| shapeToEndConnectionName | java.lang.String | 끝 연결 이름에서 접착할 위치입니다. |
| shapeToId | long | [Shape](../../com.aspose.diagram/shape)로 접착할 도형의 ID입니다. |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


연결 ID로 컨테이너 내 도형을 붙이기

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeFromId | long | [Shape](../../com.aspose.diagram/shape)에서 접착되는 도형의 ID입니다. |
| shapeToBeginConnectionID | int | 첫 번째 연결 ID에서 접착할 위치입니다. |
| shapeToEndConnectionID | int | 끝 연결 ID에서 접착할 위치입니다. |
| shapeToId | long | [Shape](../../com.aspose.diagram/shape)로 접착할 도형의 ID입니다. |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


페이지의 도형을 배치하고/또는 커넥터를 재배치합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | [LayoutOptions](../../com.aspose.diagram/layoutoptions)를 사용하여 레이아웃 옵션을 구성합니다. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


페이지를 페이지 목록의 다른 위치로 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 인덱스 | int | 대상 페이지 인덱스. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sendBackward(long shapeId) {#sendBackward-long-}
```
public void sendBackward(long shapeId)
```


ID로 정의된 도형을 Z-순서에서 한 단계 뒤로 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeId | long | shape.long의 ID |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


ID로 정의된 도형을 Z-순서의 가장 뒤로 이동합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeId | long | shape.long의 ID |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


이 속성에 대한 설명은 [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


이 속성에 대한 설명은 [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


이 속성에 대한 설명은 [getBackground()](../../com.aspose.diagram/page\#getBackground--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/page\#getID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이 속성에 대한 설명은 [getName()](../../com.aspose.diagram/page\#getName--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


이 속성에 대한 설명은 [getNameU()](../../com.aspose.diagram/page\#getNameU--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


이 속성에 대한 설명은 [getPages()](../../com.aspose.diagram/page\#getPages--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


이 페이지에 사전 설정된 테마를 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


이 페이지에 사전 설정된 테마 변형 퀵스타일을 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


이 페이지에 사전 설정된 테마 변형을 적용합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


이 속성에 대한 설명은 [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


이 속성에 대한 설명은 [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


이 속성에 대한 설명은 [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


이 속성에 대한 설명은 [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

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

