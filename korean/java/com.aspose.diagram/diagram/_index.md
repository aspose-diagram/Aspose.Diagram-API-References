---
title: 다이어그램
second_title: Aspose.Diagram for Java API 참조
description: Visio 개체 계층 구조의 루트 요소.
type: docs
weight: 117
url: /ko/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Visio 개체 계층 구조의 루트 요소.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | Public 클래스 생성자, 파일에서 다이어그램을 로드합니다. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | Public 클래스 생성자, 스트림에서 다이어그램을 로드합니다. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | Public 클래스 생성자, 미리 정의된 형식을 사용하여 스트림에서 다이어그램을 로드합니다. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | Public 클래스 생성자, 미리 정의된 로드 파일 옵션을 사용하여 스트림에서 다이어그램을 로드합니다. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | Public 클래스 생성자, 미리 정의된 형식을 사용하여 파일에서 다이어그램을 로드합니다. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | Public 클래스 생성자, 미리 정의된 로드 파일 옵션을 사용하여 파일에서 다이어그램을 로드합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | 마스터의 Name 또는 NameU를 사용하여 소스 다이어그램에서 마스터를 다이어그램에 추가합니다. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | 마스터의 ID를 사용하여 템플릿 스트림에서 마스터를 다이어그램에 추가합니다. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | 마스터의 Name 또는 NameU를 사용하여 템플릿 스트림에서 마스터를 다이어그램에 추가합니다. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | 마스터의 ID를 사용하여 템플릿 파일에서 마스터를 다이어그램에 추가합니다. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | 마스터의 Name 또는 NameU를 사용하여 템플릿 파일에서 마스터를 다이어그램에 추가합니다. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | 마스터에서 만든 도형을 특정 페이지에 추가합니다. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | 정의된 PinX, PinY, Width 및 Height를 사용하여 페이지에 마스터에서 만든 도형을 추가합니다. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | 정의된 PinX 및 PinY를 사용하여 페이지에 마스터에서 만든 도형을 추가합니다. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | 다른 Diagram 객체와 결합합니다. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | 소스 Diagram에서 테마를 복사합니다. |
| [dispose()](#dispose--) | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | vsd 스트림에서 vdw 스트림 형식으로 다이어그램을 내보냅니다. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | vsd 스트림에서 *.vdw 파일 형식으로 다이어그램을 내보냅니다. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | vsd 파일에서 vdw 스트림 형식으로 다이어그램을 내보냅니다. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | vsd에서 vdw 형식으로 다이어그램을 내보냅니다. |
| [getActivePage()](#getActivePage--) | 활성 페이지를 지정합니다. |
| [getBuildnum()](#getBuildnum--) | 문서를 만드는 데 사용된 Visio 인스턴스의 빌드 번호입니다. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | 문서의 색상표를 포함합니다. |
| [getDataConnections()](#getDataConnections--) | 문서에 대한 DataConnection 요소를 포함합니다. |
| [getDataRecordSets()](#getDataRecordSets--) | Document 객체와 연결된 DataRecordset 객체 컬렉션입니다. |
| [getDefaultFontDir()](#getDefaultFontDir--) | 기본 글꼴 폴더 경로를 가져옵니다. |
| [getDocLangID()](#getDocLangID--) | 사용자가 Microsoft Office 2010 언어 기본 설정에서 지정한 사용자 인터페이스 언어의 고유 ID입니다. |
| [getDocumentProps()](#getDocumentProps--) | 문서의 제목, 작성자 등과 같은 문서 속성 요소를 포함합니다. |
| [getDocumentSettings()](#getDocumentSettings--) | 문서 설정을 지정하는 요소를 포함합니다. |
| [getDocumentSheet()](#getDocumentSheet--) | 문서의 ShapeSheet 구조를 지정합니다. |
| [getEmailRoutingData()](#getEmailRoutingData--) | 문서에 대한 MIME (Multipurpose Internet Mail Extensions) 인코딩된 MAPI 이메일 라우팅 슬립을 포함합니다. |
| [getEventItems()](#getEventItems--) | 각 이벤트에 대해 객체가 응답해야 하는 EventItem 요소를 포함합니다. |
| [getFonts()](#getFonts--) | Font 요소들의 컬렉션을 포함합니다. |
| [getHeaderFooter()](#getHeaderFooter--) | 문서의 머리글 및 바닥글 요소를 포함합니다. |
| [getInterruptMonitor()](#getInterruptMonitor--) | 인터럽트 모니터. |
| [getKey()](#getKey--) | 문서가 Visio 외부에서 수정되었는지 여부를 나타냅니다. |
| [getMasters()](#getMasters--) | Master 객체들의 컬렉션입니다. |
| [getMetric()](#getMetric--) | 도면에서 미터법 단위를 사용할지 여부입니다. |
| [getPages()](#getPages--) | Page 객체들의 컬렉션입니다. |
| [getRibbonX()](#getRibbonX--) | 리본 사용자 인터페이스를 사용자 지정하기 위해 문서에 전달되는 Ribbon XML 문자열입니다. |
| [getSolutionXMLs()](#getSolutionXMLs--) | XML 값입니다. |
| [getStart()](#getStart--) | 문서가 Visio 외부에서 수정되었는지 여부를 나타냅니다. |
| [getStyleSheets()](#getStyleSheets--) | StyleSheet 객체들의 컬렉션입니다. |
| [getUnusedStyles()](#getUnusedStyles--) | 사용되지 않은 스타일을 가져옵니다. |
| [getUserCustomUI()](#getUserCustomUI--) | 리본 또는 빠른 실행 도구 모음을 사용자 지정하기 위해 문서에 전달되는 Ribbon XML 문자열입니다. |
| [getValidation()](#getValidation--) | 문서에 대한 다이어그램 검증 정보를 저장합니다. |
| [getVbProjectData()](#getVbProjectData--) | MIME (Multipurpose Internet Mail Extensions) 인코딩 형식의 Microsoft Visual Basic for Applications 프로젝트 데이터를 포함합니다. |
| [getVbaProject()](#getVbaProject--) | VbaProject을 가져옵니다[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--). |
| [getVersion()](#getVersion--) | Visio 인스턴스의 버전 번호입니다. |
| [getWindows()](#getWindows--) | 문서에 대한 Window 요소들을 포함합니다. |
| [hasHiddenInfo()](#hasHiddenInfo--) | 이 다이어그램에 숨겨진 정보가 있는지 여부를 나타냅니다. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | 다이어그램의 모든 페이지에 대해 도형을 배치하고/또는 연결기를 재배치합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | 전체 문서를 지정된 프린터에 인쇄합니다, 표준(사용자 인터페이스 없음) 인쇄 컨트롤러를 사용하여. |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | 전체 문서를 지정된 프린터에 인쇄합니다, 표준(사용자 인터페이스 없음) 인쇄 컨트롤러를 사용하여. |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | 문서를 인쇄합니다, 표준(사용자 인터페이스 없음) 인쇄 컨트롤러와 문서 이름을 사용하여. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | 문서를 인쇄합니다, 표준(사용자 인터페이스 없음) 인쇄 컨트롤러와 문서 이름을 사용하여. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | 사용되지 않은 정보를 제거합니다. |
| [removeMacro()](#removeMacro--) | 이 다이어그램에서 VBA/매크로를 제거합니다. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | 다이어그램을 스트림에 저장합니다. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | 다이어그램을 스트림에 저장합니다. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | 지정된 저장 옵션을 사용하여 파일에 문서를 저장합니다. |
| [save(String filename, int format)](#save-java.lang.String-int-) | 다이어그램 데이터를 파일에 저장합니다. |
| [setBuildnum(long value)](#setBuildnum-long-) | 이 속성에 대한 설명은 [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)을(를) 참조하십시오. |
| [setDocLangID(int value)](#setDocLangID-int-) | 이 속성에 대한 설명은 [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)을(를) 참조하십시오. |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | 이 속성에 대한 설명은 [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)을(를) 참조하십시오. |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | 폰트 폴더 경로를 나타냅니다. |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | 이 속성에 대한 설명은 [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)을(를) 참조하십시오. |
| [setKey(String value)](#setKey-java.lang.String-) | 이 속성에 대한 설명은 [getKey()](../../com.aspose.diagram/diagram\#getKey--)을(를) 참조하십시오. |
| [setMetric(int value)](#setMetric-int-) | 이 속성에 대한 설명은 [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)을(를) 참조하십시오. |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | 이 속성에 대한 설명은 [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)을(를) 참조하십시오. |
| [setStart(long value)](#setStart-long-) | 이 속성에 대한 설명은 [getStart()](../../com.aspose.diagram/diagram\#getStart--)을(를) 참조하십시오. |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | 이 속성에 대한 설명은 [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)을(를) 참조하십시오. |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | 이 속성에 대한 설명은 [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)을(를) 참조하십시오. |
| [setVersion(String value)](#setVersion-java.lang.String-) | 이 속성에 대한 설명은 [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Diagram() {#Diagram--}
```
public Diagram()
```


### Diagram(String filename) {#Diagram-java.lang.String-}
```
public Diagram(String filename)
```


Public 클래스 생성자, 파일에서 다이어그램을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 이름 | java.lang.String | 파일 이름입니다. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


Public 클래스 생성자, 스트림에서 다이어그램을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 데이터 스트림입니다. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


Public 클래스 생성자, 미리 정의된 형식을 사용하여 스트림에서 다이어그램을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 데이터 스트림입니다. |
| 형식 | int | 데이터 Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


Public 클래스 생성자, 미리 정의된 로드 파일 옵션을 사용하여 스트림에서 다이어그램을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 데이터 스트림입니다. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | 데이터 [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


Public 클래스 생성자, 미리 정의된 형식을 사용하여 파일에서 다이어그램을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 이름 | java.lang.String | 파일 이름입니다. |
| 형식 | int | 파일 형식입니다. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


Public 클래스 생성자, 미리 정의된 로드 파일 옵션을 사용하여 파일에서 다이어그램을 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 이름 | java.lang.String | 파일 이름입니다. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | 데이터 [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


마스터의 Name 또는 NameU를 사용하여 소스 다이어그램에서 마스터를 다이어그램에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | 소스 다이어그램입니다. |
| masterName | java.lang.String | 마스터의 Name 또는 NameU. |

**Returns:**
int - 이 다이어그램의 마스터 컬렉션 내 마스터의 고유 ID입니다.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


마스터의 ID를 사용하여 템플릿 스트림에서 마스터를 다이어그램에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| templateStream | java.io.InputStream | 템플릿 스트림입니다. |
| masterID | int | 템플릿의 마스터 컬렉션 내 마스터의 고유 ID입니다. |

**Returns:**
int - 이 다이어그램의 마스터 컬렉션 내 마스터의 고유 ID입니다.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


마스터의 Name 또는 NameU를 사용하여 템플릿 스트림에서 마스터를 다이어그램에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| templateStream | java.io.InputStream | 템플릿 스트림입니다. |
| masterName | java.lang.String | 마스터의 Name 또는 NameU. |

**Returns:**
int - 이 다이어그램의 마스터 컬렉션 내 마스터의 고유 ID입니다.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


마스터의 ID를 사용하여 템플릿 파일에서 마스터를 다이어그램에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| templateFilePath | java.lang.String | 템플릿 파일 경로(vdx, vst 또는 vsd 형식일 수 있음). |
| masterID | int | 템플릿의 마스터 컬렉션 내 마스터의 고유 ID입니다. |

**Returns:**
int - 이 다이어그램의 마스터 컬렉션 내 마스터의 고유 ID입니다.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


마스터의 Name 또는 NameU를 사용하여 템플릿 파일에서 마스터를 다이어그램에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| templateFilePath | java.lang.String | 템플릿 파일 경로(vdx, vst 또는 vsd 형식일 수 있음). |
| masterName | java.lang.String | 마스터의 Name 또는 NameU. |

**Returns:**
int - 이 다이어그램의 마스터 컬렉션 내 마스터의 고유 ID입니다.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


마스터에서 만든 도형을 특정 페이지에 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | 새 도형 객체[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | 마스터 이름입니다. |
| pageNumber | int | 페이지 인덱스. |

**Returns:**
long - 지정된 페이지의 도형 컬렉션 내에서 도형의 고유 ID입니다.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
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
| pageNumber | int | 페이지 인덱스. |

**Returns:**
long - 지정된 페이지의 도형 컬렉션 내에서 도형의 고유 ID입니다.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


정의된 PinX 및 PinY를 사용하여 페이지에 마스터에서 만든 도형을 추가합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pinX | double | 페이지와 관련하여 도형 핀(회전 중심)의 x 좌표를 지정합니다. |
| pinY | double | 페이지와 관련하여 도형 핀(회전 중심)의 y 좌표를 지정합니다. |
| masterName | java.lang.String | 마스터 이름입니다. |
| pageNumber | int | 페이지 인덱스. |

**Returns:**
long - 지정된 페이지의 도형 컬렉션 내에서 도형의 고유 ID입니다.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


다른 Diagram 객체와 결합합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | 다른 Diagram 객체. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


소스 Diagram에서 테마를 복사합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | 소스 다이어그램입니다. |

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
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


vsd 스트림에서 vdw 스트림 형식으로 다이어그램을 내보냅니다. 아직 구현되지 않았습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputVsd | java.io.InputStream | vsd 스트림. |
| outputVdw | java.io.InputStream | vdw 스트림. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


vsd 스트림에서 \*.vdw 파일 형식으로 다이어그램을 내보냅니다. 아직 구현되지 않았습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputVsd | java.io.InputStream | \*.vsd 파일 이름. |
| outputVdw | java.lang.String | vdw 스트림. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


vsd 파일에서 vdw 스트림 형식으로 다이어그램을 내보냅니다. 아직 구현되지 않았습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd 파일 이름. |
| outputVdw | java.io.InputStream | vdw 스트림. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


vsd에서 vdw 형식으로 다이어그램을 내보냅니다. 아직 구현되지 않았습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputVsd | java.lang.String | \*.vsd 파일 이름. |
| outputVdw | java.lang.String | \*.vdw 파일 이름. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


활성 페이지를 지정합니다.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


문서를 만드는 데 사용된 Visio 인스턴스의 빌드 번호입니다.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColors() {#getColors--}
```
public ColorEntryCollection getColors()
```


문서의 색상 테이블을 포함합니다. 각 문서는 단일 색상 테이블을 가지고 있으며, 여기에는 도형, 텍스트 및 레이어와 같은 객체에 적용할 수 있는 24가지 표준 색상이 나열됩니다.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


문서에 대한 DataConnection 요소를 포함합니다.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


Document 객체와 연결된 DataRecordset 객체 컬렉션입니다.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


기본 글꼴 폴더 경로를 가져옵니다.

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


사용자가 Microsoft Office 2010 언어 기본 설정에서 지정한 사용자 인터페이스 언어의 고유 ID입니다.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


문서의 제목, 작성자 등과 같은 문서 속성 요소를 포함합니다.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


문서 설정을 지정하는 요소를 포함합니다.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


문서의 ShapeSheet 구조를 지정합니다.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


문서에 대한 MIME (Multipurpose Internet Mail Extensions) 인코딩된 MAPI 이메일 라우팅 슬립을 포함합니다.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


각 이벤트에 대해 객체가 응답해야 하는 EventItem 요소를 포함합니다.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Font 요소들의 컬렉션을 포함합니다.

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


문서의 머리글 및 바닥글 요소를 포함합니다.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


인터럽트 모니터.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


문서가 Visio 외부에서 수정되었는지 여부를 나타냅니다. 이 값이 있으면 Visio가 파일 내용을 완전히 검사합니다. Visio 외부에서 만든 파일의 경우 생략하십시오.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Master 객체들의 컬렉션입니다.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


도면에서 미터법 단위를 사용할지 여부입니다. 이 속성을 True(1)로 설정하면 미터법 단위를 사용하고, False(0)로 설정하면 영국식 단위를 사용합니다.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Page 객체들의 컬렉션입니다.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


리본 사용자 인터페이스를 사용자 지정하기 위해 문서에 전달되는 Ribbon XML 문자열입니다.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


XML 값입니다.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


문서가 Visio 외부에서 수정되었는지 여부를 나타냅니다. 이 값이 있으면 Visio가 파일 내용을 완전히 검사합니다. Visio 외부에서 만든 파일의 경우 생략하십시오.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


StyleSheet 객체들의 컬렉션입니다.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


사용되지 않은 스타일을 가져옵니다.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


리본 또는 빠른 실행 도구 모음을 사용자 지정하기 위해 문서에 전달되는 Ribbon XML 문자열입니다.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


문서에 대한 다이어그램 검증 정보를 저장합니다.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


MIME (Multipurpose Internet Mail Extensions) 인코딩 형식의 Microsoft Visual Basic for Applications 프로젝트 데이터를 포함합니다.

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


VbaProject을 가져옵니다[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--).

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Visio 인스턴스의 버전 번호입니다. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


문서에 대한 Window 요소들을 포함합니다.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


이 다이어그램에 숨겨진 정보가 있는지 여부를 나타냅니다.

**Returns:**
boolean
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


다이어그램의 모든 페이지에 대해 도형을 배치하고/또는 연결기를 재배치합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | [LayoutOptions](../../com.aspose.diagram/layoutoptions)를 사용하여 레이아웃 옵션을 구성합니다. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### print(String printerName) {#print-java.lang.String-}
```
public void print(String printerName)
```


표준(사용자 인터페이스 없음) 인쇄 컨트롤러를 사용하여 전체 문서를 지정된 프린터에 인쇄합니다. printerName이 Null이거나 비어 있으면 기본 프린터가 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| printerName | java.lang.String | 프린터 이름입니다. Null일 수 있습니다. |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


표준(사용자 인터페이스 없음) 인쇄 컨트롤러를 사용하여 전체 문서를 지정된 프린터에 인쇄합니다. printerName이 Null이거나 비어 있으면 기본 프린터가 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| printerName | java.lang.String | 프린터 이름입니다. Null일 수 있습니다. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | 인쇄 옵션. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


문서를 인쇄합니다, 표준(사용자 인터페이스 없음) 인쇄 컨트롤러와 문서 이름을 사용하여.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| printerName | java.lang.String | 프린터 이름입니다. Null일 수 있습니다. |
| documentName | java.lang.String | 문서를 인쇄하는 동안 표시할 문서 이름(예: 인쇄 상태 대화 상자 또는 프린터 대기열에 표시). |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


문서를 인쇄합니다, 표준(사용자 인터페이스 없음) 인쇄 컨트롤러와 문서 이름을 사용하여.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| printerName | java.lang.String | 프린터 이름입니다. Null일 수 있습니다. |
| documentName | java.lang.String | 문서를 인쇄하는 동안 표시할 문서 이름(예: 인쇄 상태 대화 상자 또는 프린터 대기열에 표시). |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | 인쇄 옵션. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


사용되지 않은 정보를 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


이 다이어그램에서 VBA/매크로를 제거합니다.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


다이어그램을 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream | 파일 스트림. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | 저장 옵션. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


다이어그램을 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream | 파일 스트림. |
| 형식 | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


지정된 저장 옵션을 사용하여 파일에 문서를 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 이름 | java.lang.String | 파일 이름입니다. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) 다이어그램 저장 옵션. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


다이어그램 데이터를 파일에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 이름 | java.lang.String | 파일 이름입니다. |
| 형식 | int | Aspose.Diagram.SaveFileFormat 파일 형식. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


이 속성에 대한 설명은 [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


이 속성에 대한 설명은 [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


이 속성에 대한 설명은 [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


폰트 폴더 경로를 나타냅니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


이 속성에 대한 설명은 [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


이 속성에 대한 설명은 [getKey()](../../com.aspose.diagram/diagram\#getKey--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


이 속성에 대한 설명은 [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


이 속성에 대한 설명은 [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


이 속성에 대한 설명은 [getStart()](../../com.aspose.diagram/diagram\#getStart--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


이 속성에 대한 설명은 [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


이 속성에 대한 설명은 [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


이 속성에 대한 설명은 [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)을(를) 참조하십시오.

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

