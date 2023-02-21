---
title: Page
second_title: .NET API 참조용 Aspose.Diagram
description: 문서의 페이지를 정의하는 요소를 포함합니다.
type: docs
weight: 2490
url: /ko/net/aspose.diagram/page/
---
## Page class

문서의 페이지를 정의하는 요소를 포함합니다.

```csharp
public class Page : IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Page](page/#constructor)() | 생성자. |
| [Page](page/#constructor_1)(int) | 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | 드로잉 검토자가 별도의 마크업 오버레이에 마크업한 원본 드로잉 페이지의 ID입니다. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | 페이지가 배경 페이지인지 여부를 나타내는 플래그입니다. |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | 페이지의 배경 페이지입니다. |
| [Connects](../../aspose.diagram/page/connects/) { get; } | 드로잉의 두 셰이프 간의 각 연결에 대한 연결 요소를 포함합니다. |
| [ID](../../aspose.diagram/page/id/) { get; set; } | 상위 요소 내 요소의 고유 ID입니다. |
| [Name](../../aspose.diagram/page/name/) { get; set; } | 요소의 이름입니다. |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | 요소의 범용 이름입니다. |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | 페이지 모음. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | 페이지 또는 마스터 요소에 대한 페이지 시트를 정의하는 요소를 포함합니다. |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | 이 페이지에 사전 설정 테마 적용 |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | 이 페이지에 미리 설정된 테마 변형 퀵스타일 적용 |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | 이 페이지에 미리 설정된 테마 변형을 적용합니다 |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | 마크업 오버레이와 연결된 검토자의 ID입니다. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | 모양 컬렉션. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX 및 ViewCenterY는 새 보기(창)가 처음 열릴 때 가정하는 페이지의 중심점을 지정합니다. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX 및 ViewCenterY는 새 보기(창)가 처음 열릴 때 가정하는 페이지의 중심점을 지정합니다. |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | 페이지의 새 보기(창)가 열릴 때 사용할 기본 배율입니다. 예를 들어, 1 = 100%; 1.5 = 150% 등. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Activex 컨트롤을 생성합니다. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | 셰이프 ID가 있는 셰이프에 설명을 추가합니다. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | 도형에 주석을 추가합니다. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | 정의된 PinX 및 PinY로 주석을 추가합니다. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | 마스터가 생성한 도형을 특정 페이지에 추가합니다. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | 정의된 PinX 및 PinY가 있는 페이지에서 마스터가 생성한 모양을 추가합니다. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | 정의된 PinX,PinY,Width 및 Height를 사용하여 페이지에서 마스터에 의해 생성된 모양을 추가합니다. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | 정의된 PinX 및 PinY로 텍스트를 추가합니다. |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | 정의된 PinX 및 PinY로 텍스트를 추가합니다. |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | 전체 페이지에 스타일을 적용합니다. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | 자동 공간 모양 |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | ID로 정의된 모양을 z 순서에서 한 위치 앞으로 가져옵니다. |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | ID로 정의된 모양을 z-order의 맨 앞으로 가져옵니다. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | 페이지 범위를 기준으로 페이지의 모양을 중앙에 맞춥니다. 모양을 가운데에 놓으면 서로 상대적인 위치가 변경되지 않습니다. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | 커넥터를 통해 도형을 연결합니다. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | 커넥터를 통해 도형을 연결합니다. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | 커넥터를 통해 도형을 연결합니다. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | 커넥터 인덱스를 통해 도형을 연결합니다. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | 커넥터 인덱스를 통해 도형을 연결합니다. |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | 비관리 리소스 해제, 해제 또는 재설정과 관련된 응용 프로그램 정의 작업을 수행합니다. |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | 베지어를 그리는 과정. 포인트의 길이는 3. 보다 크거나 같아야 합니다. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | 타원을 그리는 과정. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | 한 줄을 그리는 과정. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | 선을 그리는 과정. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | 선을 그리는 과정. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | 폴리라인을 그리는 과정. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | 폴리라인을 그리는 과정. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | 사각형을 그리는 과정. |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | 스플라인을 그리는 과정. |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | 접착제 모양 |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | 접착제 모양. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | container 의 접착제 모양 |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | 연결 이름 를 사용하여 컨테이너의 모양을 붙입니다. |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | container 의 연결 ID로 모양을 붙입니다. |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | 모양을 커넥터의 BeginX 에 붙입니다. |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | 모양을 커넥터의 EndX 에 붙입니다. |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | 페이지의 모양을 배치하거나 커넥터를 다시 라우팅합니다. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | 페이지를 페이지의 다른 위치로 이동합니다. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | ID로 정의된 도형을 z 순서에서 한 위치 뒤로 이동합니다. |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | ID로 정의된 도형을 z-order의 뒤로 이동합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Diagram](../../aspose.diagram/)
* 집회 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
