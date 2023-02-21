---
title: PdfPermissions
second_title: .NET API 참조용 Aspose.Diagram
description: PDF 문서에 대한 사용자 권한을 지정합니다.
type: docs
weight: 3400
url: /ko/net/aspose.diagram.saving/pdfpermissions/
---
## PdfPermissions enumeration

PDF 문서에 대한 사용자 권한을 지정합니다.

```csharp
[Flags]
public enum PdfPermissions
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| DisallowAll | `0` | PDF 문서에 대한 모든 작업을 허용하지 않습니다. 이것이 기본값입니다. |
| Printing | `4` | 문서 인쇄를 허용합니다. |
| ModifyContents | `8` | 문서의 내용을 수정할 수 있습니다. |
| ContentCopy | `10` | 액세스 가능성을 위한 추출을 포함하여 문서에서 텍스트 및 그래픽을 복사하거나 추출할 수 있습니다. |
| ModifyAnnotations | `20` | 텍스트 주석을 추가하거나 수정할 수 있습니다. RC4 40비트 암호화를 사용하는 경우 이 옵션을 사용하면 양식 필드를 채울 수도 있습니다. |
| FillIn | `100` | 양식을 채우고 문서에 서명할 수 있습니다. RC4 40비트 암호화를 사용하는 경우 이 옵션은 무시되며 ModifyAnnotations가 설정될 때마다 양식 채우기가 허용됩니다. |
| ContentCopyForAccessibility | `200` | 장애가 있는 사용자의 접근성을 지원하거나 다른 목적으로 텍스트 및 그래픽을 추출할 수 있습니다. RC4 40비트 암호화를 사용하는 경우 이 옵션은 무시되며 ContentCopy가 설정될 때마다 접근성이 허용됩니다. |
| DocumentAssembly | `400` | 페이지를 삽입, 회전 또는 삭제하고 책갈피 또는 축소판 이미지와 같은 탐색 요소를 생성하여 문서를 조립할 수 있습니다. RC4 40비트 암호화를 사용하는 경우 이 옵션은 무시되며 ModifyContents가 설정되면 문서 어셈블리가 허용됩니다. |
| HighResolutionPrinting | `804` | 문서를 가능한 최고 해상도로 인쇄할 수 있습니다. RC4 40비트 암호화를 사용하는 경우 이 옵션은 무시되며 인쇄가 설정되면 고해상도 인쇄가 허용됩니다. |
| AllowAll | `FFFF` | PDF 문서에 대한 모든 작업을 허용합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* 집회 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->