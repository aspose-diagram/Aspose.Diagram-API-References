---
title: Protection
second_title: .NET API 참조용 Aspose.Diagram
description: 잠금은 셰이프에 대한 부주의한 변경을 방지하는 데 도움이 되지만 Microsoft Visio가 다른 상황에서 값을 재설정하는 것을 방지하지는 않습니다. 또한 셰이프시트 창에서 변경한 사항에 대해서도 보호하지 않습니다.
type: docs
weight: 2880
url: /ko/net/aspose.diagram/protection/
---
## Protection class

잠금은 셰이프에 대한 부주의한 변경을 방지하는 데 도움이 되지만 Microsoft Visio가 다른 상황에서 값을 재설정하는 것을 방지하지는 않습니다. 또한 셰이프시트 창에서 변경한 사항에 대해서도 보호하지 않습니다.

```csharp
public class Protection
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Del](../../aspose.diagram/protection/del/) { get; set; } | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다. |
| [LockAspect](../../aspose.diagram/protection/lockaspect/) { get; } | 모양의 종횡비가 잠겨 있는지 여부를 지정합니다. 잠긴 경우 모양의 크기는 비례적으로만 조정할 수 있습니다. 단일 치수로 크기를 조정할 수 없습니다. |
| [LockBegin](../../aspose.diagram/protection/lockbegin/) { get; } | 1차원 도형의 시작점이 특정 위치에 잠겨 있는지 여부를 지정합니다. |
| [LockCalcWH](../../aspose.diagram/protection/lockcalcwh/) { get; } | Geom 요소에서 정점을 편집하거나 요소 유형을 변경할 때 다시 계산할 수 없도록 도형의 선택 사각형을 잠글지 여부를 지정합니다. |
| [LockCrop](../../aspose.diagram/protection/lockcrop/) { get; } | 외부 개체가 Microsoft Visio의 자르기 도구로 잘리지 않도록 잠겨 있는지 여부를 지정합니다. |
| [LockCustProp](../../aspose.diagram/protection/lockcustprop/) { get; } | 사용자가 사용자 정의 속성 정의 대화 상자를 사용하여 UI(사용자 인터페이스)에서 사용자 정의 속성을 추가, 삭제 또는 수정할 수 있는지 여부를 결정합니다. |
| [LockDelete](../../aspose.diagram/protection/lockdelete/) { get; } | 도형이 삭제되지 않도록 잠겨 있는지 여부를 지정합니다. |
| [LockEnd](../../aspose.diagram/protection/lockend/) { get; } | 1차원 도형의 끝점이 특정 위치에 잠겨 있는지 여부를 지정합니다. |
| [LockFormat](../../aspose.diagram/protection/lockformat/) { get; } | 도형의 서식을 변경할 수 없도록 잠겨 있는지 여부를 지정합니다. 특히 이 요소는 텍스트, 선 및 채우기 서식이 변경되거나 모양이 상속되는 스타일 요소가 변경되지 않도록 보호합니다. |
| [LockFromGroupFormat](../../aspose.diagram/protection/lockfromgroupformat/) { get; } | 하위 모양이 Visio 사용자 인터페이스에서 상위 그룹 모양에 적용되고 그렇지 않으면 개별 그룹 모양으로 계단식으로 적용되는 형식 변경을 차단하도록 허용합니다. |
| [LockGroup](../../aspose.diagram/protection/lockgroup/) { get; } | 그룹을 해제할 수 없도록 그룹을 잠글지 여부를 지정합니다. |
| [LockHeight](../../aspose.diagram/protection/lockheight/) { get; } | 모양의 높이를 잠글지 여부를 지정합니다. 잠겨 있으면 모양의 크기를 조정할 때 높이가 변경되지 않습니다. |
| [LockMoveX](../../aspose.diagram/protection/lockmovex/) { get; } | 가로로 이동할 수 없도록 도형의 가로 위치를 잠글지 여부를 지정합니다. |
| [LockMoveY](../../aspose.diagram/protection/lockmovey/) { get; } | 수직으로 이동할 수 없도록 도형의 수직 위치를 잠글지 여부를 지정합니다. |
| [LockRotate](../../aspose.diagram/protection/lockrotate/) { get; } | Microsoft Visio에서 회전 도구나 왼쪽으로 회전 또는 오른쪽으로 회전 명령을 사용하여 도형을 회전하지 않도록 잠글지 여부를 지정합니다. |
| [LockSelect](../../aspose.diagram/protection/lockselect/) { get; } | Geom 요소에서 정점을 편집하거나 요소 유형을 변경할 때 다시 계산할 수 없도록 도형의 선택 사각형을 잠글지 여부를 지정합니다. |
| [LockTextEdit](../../aspose.diagram/protection/locktextedit/) { get; } | 도형의 텍스트를 편집할 수 없도록 잠글지 여부를 지정합니다. 그러나 텍스트 대화 상자의 글꼴 탭에 있는 스타일 옵션을 사용하여 스타일을 적용하여 텍스트 서식을 지정할 수 있습니다. |
| [LockThemeColors](../../aspose.diagram/protection/lockthemecolors/) { get; } | 사용자가 도형에 테마 색상을 적용하지 못하도록 합니다. |
| [LockThemeEffects](../../aspose.diagram/protection/lockthemeeffects/) { get; } | 사용자가 도형에 테마 효과를 적용하지 못하도록 합니다. |
| [LockVtxEdit](../../aspose.diagram/protection/lockvtxedit/) { get; } | 도구 모음의 어떤 도구로도 편집할 수 없도록 모양의 정점을 잠글지 여부를 지정합니다. |
| [LockWidth](../../aspose.diagram/protection/lockwidth/) { get; } | 도형의 크기를 조정할 때 변경되지 않도록 도형의 너비를 잠글지 여부를 지정합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Diagram](../../aspose.diagram/)
* 집회 [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
