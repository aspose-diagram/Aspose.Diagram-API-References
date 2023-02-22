---
title: Diagram
second_title: .NET API 참조용 Aspose.Diagram
description: Visio 개체 계층 구조의 루트 요소.
type: docs
weight: 1170
url: /ko/net/aspose.diagram/diagram/
---
## Diagram class

Visio 개체 계층 구조의 루트 요소.

```csharp
public class Diagram : IDisposable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Diagram](diagram/#constructor)() | 기본 생성자입니다. |
| [Diagram](diagram/#constructor_1)(Stream) | 공용 클래스 생성자, 는 스트림에서 다이어그램을 로드합니다. |
| [Diagram](diagram/#constructor_4)(string) | 공용 클래스 생성자, 는 파일에서 다이어그램을 로드합니다. |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | 공용 클래스 생성자, 미리 정의된 형식을 사용하여 스트림에서 다이어그램을 로드합니다. |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | 공용 클래스 생성자, 미리 정의된 로드 파일 옵션을 사용하여 스트림에서 다이어그램을 로드합니다. |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | 공용 클래스 생성자, 미리 정의된 형식을 사용하여 파일에서 다이어그램을 로드합니다. |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | 공용 클래스 생성자, 미리 정의된 로드 파일 옵션을 사용하여 파일에서 다이어그램을 로드합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | 활성 page 를 지정합니다. |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | 문서를 만드는 데 사용된 Visio 인스턴스의 빌드 번호입니다. |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | 문서의 색상표를 포함합니다. 각 문서에는 단일 색상표 가 포함되어 있으며 문서의 모양, 텍스트 및 레이어와 같은 객체 에 적용할 수 있는 24가지 표준 색상을 나열합니다. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | 문서에 대한 DataConnection 요소를 포함합니다. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | 문서 개체와 연결된 DataRecordset 개체의 컬렉션입니다. |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | 사용자가 Microsoft Office 2010 언어 기본 설정에서 지정한 사용자 인터페이스 언어의 고유 ID입니다. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | 문서의 제목, 작성자 등과 같은 문서 속성 요소를 포함합니다. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | 문서 설정을 지정하는 요소를 포함합니다. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | 문서의 셰이프시트 구조를 지정합니다. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | 문서에 대한 MIME(Multipurpose Internet Mail Extensions) 인코딩 MAPI 전자 메일 회람 쪽지를 포함합니다. |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | 개체가 응답해야 하는 각 이벤트에 대한 EventItem 요소를 포함합니다. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | 글꼴 폴더 경로 를 나타냅니다. |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | 글꼴 요소 컬렉션을 포함합니다. |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | 문서의 머리글 및 바닥글에 대한 요소를 포함합니다. |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | 인터럽트 모니터를 가져오고 설정합니다. |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | 문서가 Visio 외부에서 수정되었는지 여부를 나타냅니다. 있는 경우 Visio는 파일의 내용을 완전히 테스트합니다. Visio. 외부에서 만드는 파일은 생략하십시오. |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | 컬렉션 마스터 객체. |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | 도면에서 미터법 단위를 사용할지 여부. 미터법 단위를 사용하려면 이 속성을 True(1)로 설정하십시오. 영어 단위를 사용하려면 False(0)로 설정하세요. |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | 컬렉션 페이지 개체. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | 리본 사용자 인터페이스를 사용자 지정하기 위해 문서에 전달되는 리본 XML 문자열입니다. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | XML 값. |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | 문서가 Visio 외부에서 수정되었는지 여부를 나타냅니다. 있는 경우 Visio는 파일 내용을 완전히 테스트합니다. Visio. 외부에서 만드는 파일은 생략하십시오. |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | 컬렉션 스타일시트 객체. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | 빠른 액세스 도구 모음이나 리본을 사용자 지정하기 위해 문서에 전달되는 리본 XML 문자열입니다. |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | 문서에 대한 다이어그램 유효성 검사에 대한 정보를 저장합니다. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | VbaProject 가져오기[`VbaProject`](./vbaproject/) . |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | MIME(Multipurpose Internet Mail Extensions) 인코딩 형식의 Microsoft Visual Basic for Applications 프로젝트 데이터를 포함합니다. |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Visio 인스턴스의 버전 번호입니다. Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | 문서에 대한 창 요소를 포함합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | 마스터의 이름 또는 NameU로 소스 다이어그램에서 다이어그램에 마스터를 추가합니다. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | 마스터의 ID로 템플릿 스트림에서 다이어그램에 마스터를 추가합니다. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | 마스터의 이름 또는 NameU로 템플릿 스트림에서 다이어그램에 마스터를 추가합니다. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | 마스터의 ID로 템플릿 파일에서 다이어그램에 마스터를 추가합니다. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | 마스터의 이름 또는 NameU로 템플릿 파일에서 다이어그램에 마스터를 추가합니다. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | 마스터가 생성한 도형을 특정 페이지에 추가합니다. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | 정의된 PinX 및 PinY가 있는 페이지에서 마스터가 생성한 모양을 추가합니다. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | 정의된 PinX,PinY,Width 및 Height를 사용하여 페이지에서 마스터에 의해 생성된 모양을 추가합니다. |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | 다른 다이어그램 개체를 결합합니다. |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | 소스 다이어그램에서 테마를 복사합니다. |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | 비관리 리소스 해제, 해제 또는 재설정과 관련된 응용 프로그램 정의 작업을 수행합니다. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | 기본 글꼴 폴더 경로 가져오기 |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | 미사용 Styles 가져오기 |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | 이 다이어그램에 숨겨진 정보가 있는지 여부를 나타냅니다. |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | 다이어그램의 모든 페이지에 대한 모양을 배치하거나 커넥터를 다시 라우팅합니다. |
| [Print](../../aspose.diagram/diagram/print/#print)() | 전체 문서를 기본 프린터로 인쇄합니다. |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | 표준(사용자 인터페이스 없음) 인쇄 컨트롤러를 사용하여 지정된 프린터 설정에 따라 문서를 인쇄합니다. |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | 전체 문서를 기본 프린터로 인쇄합니다. |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | 표준(사용자 인터페이스 없음) 인쇄 컨트롤러를 사용하여 전체 문서를 지정된 프린터로 인쇄합니다. |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | 표준(사용자 인터페이스 없음) 인쇄 컨트롤러를 사용하여 지정된 프린터 설정에 따라 문서를 인쇄합니다. |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | 표준(사용자 인터페이스 없음) 인쇄 컨트롤러와 문서 이름을 사용하여 지정된 프린터 설정에 따라 문서를 인쇄합니다. |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | 표준(사용자 인터페이스 없음) 인쇄 컨트롤러를 사용하여 전체 문서를 지정된 프린터로 인쇄합니다. |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | 표준(사용자 인터페이스 없음) 인쇄 컨트롤러와 문서 이름을 사용하여 문서를 인쇄합니다. |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | 표준(사용자 인터페이스 없음) 인쇄 컨트롤러와 문서 이름을 사용하여 지정된 프린터 설정에 따라 문서를 인쇄합니다. |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | 표준(사용자 인터페이스 없음) 인쇄 컨트롤러와 문서 이름을 사용하여 문서를 인쇄합니다. |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | 다이어그램의 모든 DataRecordSet에 대한 Refresh 메서드를 호출합니다. |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | 사용하지 않는 정보 제거 |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | 이 다이어그램에서 VBA/매크로를 제거합니다. |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | 다이어그램 데이터를 스트림에 저장합니다. |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | 지정된 저장 옵션을 사용하여 다이어그램을 스트림에 저장합니다. |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | 다이어그램 데이터를 파일에 저장합니다. |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | 지정된 저장 옵션을 사용하여 문서를 파일로 저장합니다. |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | 다이어그램을 vsd 스트림에서 vdw 스트림 형식으로 내보냅니다. 아직 구현되지 않았습니다. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | 다이어그램을 vsd 스트림에서 *.vdw 파일 형식으로 내보냅니다. 아직 구현되지 않았습니다. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | 다이어그램을 vsd 파일에서 vdw 스트림 형식으로 내보냅니다. 아직 구현되지 않았습니다. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | 다이어그램을 vsd에서 vdw 형식으로 내보냅니다. 아직 구현되지 않았습니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Diagram](../../aspose.diagram/)
* 집회 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
