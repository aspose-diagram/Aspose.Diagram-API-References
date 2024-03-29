---
title: ImageSaveOptions
second_title: .NET API 참조용 Aspose.Diagram
description: 다이어그램 페이지를 이미지로 렌더링할 때 추가 옵션을 지정할 수 있습니다.
type: docs
weight: 3280
url: /ko/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

다이어그램 페이지를 이미지로 렌더링할 때 추가 옵션을 지정할 수 있습니다.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/)(SaveFileFormat) | 렌더링된 이미지를 저장하는 데 사용할 수 있는 이 클래스의 새 인스턴스를 초기화합니다.[`사소한 말다툼`](../../aspose.diagram/savefileformat/) , [`PNG`](../../aspose.diagram/savefileformat/) ,[`비엠피`](../../aspose.diagram/savefileformat/) ,[`EMF`](../../aspose.diagram/savefileformat/) 또는[`Jpeg`](../../aspose.diagram/savefileformat/) 형식. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | 저장될 모양의 영역을 가져오거나 설정합니다. |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality/) { get; set; } | 합성 중에 사용할 품질 수준을 지정합니다. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom/) { get; set; } | 이 매개변수는 스케일과 유사하지만 생성된 이미지 크기에는 영향을 미치지 않습니다. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | 다이어그램의 문자가 유니코드이고 올바른 글꼴 값으로 설정되지 않았거나 글꼴이 로컬에 설치되지 않은 경우 pdf, 이미지 또는 XPS에서 블록으로 나타날 수 있습니다. MingLiu 또는 MS Gothic과 같은 DefaultFont를 설정하여 이를 표시합니다 문자. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Emf 메타파일 렌더링 설정. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | 페이지 확대 여부를 지정합니다. |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | 가이드 모양을 내보낼 필요가 있는지 여부를 정의합니다. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage/) { get; set; } | 숨겨진 페이지를 내보내야 하는지 여부를 정의합니다. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness/) { get; set; } | 생성된 이미지의 밝기를 가져오거나 설정합니다. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode/) { get; set; } | 생성된 이미지의 색상 모드를 가져오거나 설정합니다. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast/) { get; set; } | 생성된 이미지의 대비를 가져오거나 설정합니다. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode/) { get; set; } | 이미지 크기를 조정하거나 회전할 때 사용되는 알고리즘을 지정합니다. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | 주석을 내보낼 필요가 있는지 여부를 정의합니다. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality/) { get; set; } | 생성된 JPEG 이미지의 품질을 결정하는 값을 가져오거나 설정합니다. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount/) { get; set; } | 다중 페이지 TIFF 파일로 저장할 때 렌더링할 페이지 수를 가져오거나 설정합니다. 기본값은 다이어그램의 모든 페이지가 렌더링됨을 의미하는 MaxValue입니다. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex/) { get; set; } | 렌더링할 첫 번째 페이지의 0 기반 인덱스를 가져오거나 설정합니다. 기본값은 0. 입니다. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | 생성된 이미지의 페이지 크기를 가져오거나 설정합니다. Can be be[`PageSize`](../pagesize/) 또는 null. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode/) { get; set; } | 렌더링 중에 픽셀이 오프셋되는 방법을 지정하는 값을 가져오거나 설정합니다. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution/) { get; set; } | 생성된 이미지의 해상도를 인치당 도트 수로 가져오거나 설정합니다. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea/) { get; set; } | 저장 영역이 pdf와 같은지 여부를 지정합니다. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly/) { get; set; } | 모든 페이지를 이미지로 저장할지 또는 전경으로만 저장할지 지정합니다. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat/) { get; set; } | 이 저장 옵션 개체를 사용하는 경우 렌더링된 다이어그램 페이지가 저장되는 형식을 지정합니다. Can be[`사소한 말다툼`](../../aspose.diagram/savefileformat/) ,[`PNG`](../../aspose.diagram/savefileformat/) , [`비엠피`](../../aspose.diagram/savefileformat/) ,[`EMF`](../../aspose.diagram/savefileformat/) 또는[`Jpeg`](../../aspose.diagram/savefileformat/) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale/) { get; set; } | 생성된 이미지의 줌 배율을 가져오거나 설정합니다. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | 렌더링할 모양을 가져오거나 설정합니다. 기본 개수는 0. 입니다. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode/) { get; set; } | 선과 곡선 및 채워진 영역의 가장자리에 스무딩(앤티앨리어싱)을 적용할지 여부를 지정합니다. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression/) { get; set; } | 생성된 이미지를 TIFF 형식으로 저장할 때 적용할 압축 유형을 가져오거나 설정합니다. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | 경고 콜백을 가져오거나 설정합니다. |

### 또한보십시오

* class [RenderingSaveOptions](../renderingsaveoptions/)
* 네임스페이스 [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* 집회 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
