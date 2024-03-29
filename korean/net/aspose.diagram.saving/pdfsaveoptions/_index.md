---
title: PdfSaveOptions
second_title: .NET API 참조용 Aspose.Diagram
description: 다이어그램 페이지를 PDF로 렌더링할 때 추가 옵션을 지정할 수 있습니다.
type: docs
weight: 3410
url: /ko/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

다이어그램 페이지를 PDF로 렌더링할 때 추가 옵션을 지정할 수 있습니다.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | 문서를 저장하는 데 사용할 수 있는 이 클래스의 새 인스턴스를 초기화합니다.[`PDF`](../../aspose.diagram/savefileformat/) 형식. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | 저장될 모양의 영역을 가져오거나 설정합니다. |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance/) { get; set; } | 생성된 PDF 문서에 대한 원하는 적합성 수준. 기본값은 다음과 같습니다.Pdf15 . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | 다이어그램의 문자가 유니코드이고 올바른 글꼴 값으로 설정되지 않았거나 글꼴이 로컬에 설치되지 않은 경우 pdf, 이미지 또는 XPS에서 블록으로 나타날 수 있습니다. MingLiu 또는 MS Gothic과 같은 DefaultFont를 설정하여 이를 표시합니다 문자. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails/) { get; set; } | 디지털 서명 정보를 가져오거나 설정합니다. 설정하지 않으면 서명이 수행되지 않습니다. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Emf 메타파일 렌더링 설정. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails/) { get; set; } | 암호화 세부 정보를 가져오거나 설정합니다. 설정하지 않으면 암호화가 수행되지 않습니다. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | 페이지 확대 여부를 지정합니다. |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | 가이드 모양을 내보낼 필요가 있는지 여부를 정의합니다. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage/) { get; set; } | 숨겨진 페이지를 내보내야 하는지 여부를 정의합니다. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution/) { get; set; } | 생성된 이미지의 수평 해상도를 인치당 도트 수로 가져오거나 설정합니다. Emf 형식 이미지를 제외한 이미지 생성 방법을 적용합니다. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | 주석을 내보낼 필요가 있는지 여부를 정의합니다. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality/) { get; set; } | 이미지의 JPEG 압축 품질을 지정합니다(JPEG 압축을 사용하는 경우). 기본값은 95입니다. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount/) { get; set; } | PDF로 렌더링할 페이지 수를 가져오거나 설정합니다. 기본값은 다이어그램의 모든 페이지가 렌더링됨을 의미하는 MaxValue입니다. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex/) { get; set; } | 렌더링할 첫 번째 페이지의 0 기반 인덱스를 가져오거나 설정합니다. 기본값은 0. 입니다. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback/) { get; set; } | 페이지 저장 프로세스의 진행 상황을 제어/표시합니다. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | 생성된 이미지의 페이지 크기를 가져오거나 설정합니다. Can be be[`PageSize`](../pagesize/) 또는 null. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly/) { get; set; } | 모든 페이지를 이미지로 저장할지 또는 전경으로만 저장할지 지정합니다. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat/) { get; set; } | 이 저장 옵션 개체를 사용하는 경우 렌더링된 다이어그램 페이지가 저장되는 형식을 지정합니다. Can be[`PDF`](../../aspose.diagram/savefileformat/) 만. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | 렌더링할 모양을 가져오거나 설정합니다. 기본 개수는 0. 입니다. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages/) { get; set; } | 페이지 설정에 따라 다이어그램을 여러 페이지로 분할할지 여부를 정의합니다. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression/) { get; set; } | 이미지를 제외한 모든 콘텐츠 스트림에 사용할 압축 유형을 지정합니다. 기본값은Flate . |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution/) { get; set; } | 생성된 이미지의 수직 해상도를 인치당 도트 수로 가져오거나 설정합니다. Emf 형식 이미지를 제외한 이미지 생성 방법을 적용합니다. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback/) { get; set; } | 경고 콜백을 가져오거나 설정합니다. |

### 또한보십시오

* class [RenderingSaveOptions](../renderingsaveoptions/)
* 네임스페이스 [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* 집회 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
