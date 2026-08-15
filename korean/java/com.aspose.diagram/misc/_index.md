---
title: 기타
second_title: Aspose.Diagram for Java API 참조
description: 선택 강조 및 가시성을 제어하는 요소와 같은 도형 및 그룹의 다양한 요소를 포함합니다.
type: docs
weight: 247
url: /ko/java/com.aspose.diagram/misc/
---

**Inheritance:**
java.lang.Object
```
public class Misc
```

선택 강조 및 가시성을 제어하는 요소와 같이 도형 및 그룹의 다양한 요소를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBegTrigger()](#getBegTrigger--) | Microsoft Visio에서 생성된 트리거 수식을 포함하며, 이는 1차원 도형의 시작점을 이동하여 다른 도형과의 연결을 유지할지 여부를 결정합니다. |
| [getCalendar()](#getCalendar--) | 사용자 지정 속성, 텍스트 필드 및 요소 수식에 사용되는 달력을 결정합니다. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | 도형에 대한 주석 텍스트를 문자열 형식으로 포함합니다. |
| [getDel()](#getDel--) | 요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그. |
| [getDropOnPageScale()](#getDropOnPageScale--) | 도형을 그리기 페이지에 놓을 때 도형이 확대되는 비율을 결정합니다. |
| [getDynFeedback()](#getDynFeedback--) | 연결자를 끌 때 사용자에게 제공되는 시각적 피드백 유형을 지정합니다. |
| [getEndTrigger()](#getEndTrigger--) | Microsoft Visio에서 생성된 트리거 수식을 포함합니다. |
| [getGlueType()](#getGlueType--) | 도형에 연결할 때 동적(도형 간) 접착이 허용되는지 여부를 지정합니다. |
| [getHideText()](#getHideText--) | 도형의 텍스트를 숨깁니다. |
| [getLangID()](#getLangID--) | 셀 수식, 텍스트, 사용자 정의 속성 또는 주석이 입력된 언어의 로케일 ID(LCID)를 나타냅니다. |
| [getLocalizeMerge()](#getLocalizeMerge--) | 도형이 문서 간에 복사될 때 도형이 현지화되는지(그들의 LangID 요소가 재설정되는지) 여부를 결정합니다. |
| [getNoAlignBox()](#getNoAlignBox--) | 도형이 선택될 때 선택 사각형이 표시되는지 여부를 지정합니다. |
| [getNoCtlHandles()](#getNoCtlHandles--) | 도형이 선택될 때 제어 핸들이 표시되는지 여부를 지정합니다. |
| [getNoLiveDynamics()](#getNoLiveDynamics--) | 사용자가 도형을 조작할 때 도형이 동적으로 크기 조정되거나 회전하는지 여부를 지정합니다. |
| [getNoObjHandles()](#getNoObjHandles--) | 도형이 선택될 때 선택 핸들이 표시되는지 여부를 지정합니다. |
| [getNonPrinting()](#getNonPrinting--) | 선택된 도형을 인쇄할 수 있는지 여부를 지정합니다. |
| [getObjType()](#getObjType--) | Microsoft Visio를 사용하여 도면 페이지에 도형을 배치할 때 객체가 다이어그램에서 배치 가능하거나 라우팅 가능한지 여부를 지정합니다. |
| [getShapeKeywords()](#getShapeKeywords--) | 맞춤 마스터 도형에 할당된 검색 키워드를 포함합니다. |
| [getUpdateAlignBox()](#getUpdateAlignBox--) | 제어 핸들이 이동될 때마다 도형의 선택 사각형을 재계산할지 여부를 지정합니다. |
| [getWalkPreference()](#getWalkPreference--) | 동적 접착을 사용하여 도형이 모호한 위치로 이동할 때 1차원 도형의 끝점이 붙어 있는 도형의 수평 또는 수직 연결 지점으로 이동하는지를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [isDropSource()](#isDropSource--) | 도형을 그룹에 끌어다 놓아 그룹에 추가할 수 있는지 여부를 지정합니다. |
| [isReplaceLockShapeData()](#isReplaceLockShapeData--) | 마스터 도형의 지정된 셀 값이 도형 교체 작업 중 교체되는 도형의 값(로컬 값 포함)을 덮어쓰는지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/misc\#getDel--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBegTrigger() {#getBegTrigger--}
```
public DoubleValue getBegTrigger()
```


Microsoft Visio에서 생성된 트리거 수식을 포함하며, 이는 1차원 도형의 시작점을 이동하여 다른 도형과의 연결을 유지할지 여부를 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


사용자 지정 속성, 텍스트 필드 및 요소 수식에 사용되는 달력을 결정합니다.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public Str2Value getComment()
```


도형에 대한 주석 텍스트를 문자열 형식으로 포함합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDel() {#getDel--}
```
public int getDel()
```


요소가 로컬에서 삭제되었는지 여부를 나타내는 플래그입니다. 값 1은 요소가 로컬에서 삭제되었음을 나타냅니다.

**Returns:**
int
### getDropOnPageScale() {#getDropOnPageScale--}
```
public DoubleValue getDropOnPageScale()
```


도형을 그리기 페이지에 놓을 때 도형이 확대되는 비율을 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDynFeedback() {#getDynFeedback--}
```
public DynFeedback getDynFeedback()
```


연결자를 끌 때 사용자에게 제공되는 시각적 피드백 유형을 지정합니다.

**Returns:**
[DynFeedback](../../com.aspose.diagram/dynfeedback)
### getEndTrigger() {#getEndTrigger--}
```
public DoubleValue getEndTrigger()
```


Microsoft Visio에서 생성된 트리거 수식을 포함합니다. 이 트리거 수식은 1차원 도형의 끝점을 이동하여 다른 도형과의 연결을 유지할지 여부를 결정합니다.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGlueType() {#getGlueType--}
```
public GlueType getGlueType()
```


도형에 연결할 때 동적(도형 간) 접착이 허용되는지 여부를 지정합니다.

**Returns:**
[GlueType](../../com.aspose.diagram/gluetype)
### getHideText() {#getHideText--}
```
public BoolValue getHideText()
```


도형의 텍스트를 숨깁니다. 텍스트 블록의 텍스트를 보고, 속성을 편집하고, 스타일을 적용할 수 있지만, HideText 요소를 0으로 지정할 때까지 변경 사항이 표시되지 않습니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


셀 수식, 텍스트, 사용자 정의 속성 또는 주석이 입력된 언어의 로케일 ID(LCID)를 나타냅니다.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLocalizeMerge() {#getLocalizeMerge--}
```
public BoolValue getLocalizeMerge()
```


도형이 문서 간에 복사될 때 도형이 현지화되는지(그들의 LangID 요소가 재설정되는지) 여부를 결정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoAlignBox() {#getNoAlignBox--}
```
public BoolValue getNoAlignBox()
```


도형이 선택될 때 선택 사각형이 표시되는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoCtlHandles() {#getNoCtlHandles--}
```
public BoolValue getNoCtlHandles()
```


도형이 선택될 때 제어 핸들이 표시되는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLiveDynamics() {#getNoLiveDynamics--}
```
public BoolValue getNoLiveDynamics()
```


사용자가 도형을 조작할 때 도형이 동적으로 크기 조정되거나 회전하는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoObjHandles() {#getNoObjHandles--}
```
public BoolValue getNoObjHandles()
```


도형이 선택될 때 선택 핸들이 표시되는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNonPrinting() {#getNonPrinting--}
```
public BoolValue getNonPrinting()
```


선택된 도형을 인쇄할 수 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getObjType() {#getObjType--}
```
public ObjType getObjType()
```


Microsoft Visio를 사용하여 도면 페이지에 도형을 배치할 때 객체가 다이어그램에서 배치 가능하거나 라우팅 가능한지 여부를 지정합니다.

**Returns:**
[ObjType](../../com.aspose.diagram/objtype)
### getShapeKeywords() {#getShapeKeywords--}
```
public Str2Value getShapeKeywords()
```


맞춤 마스터 도형에 할당된 검색 키워드를 포함합니다.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getUpdateAlignBox() {#getUpdateAlignBox--}
```
public BoolValue getUpdateAlignBox()
```


제어 핸들이 이동될 때마다 도형의 선택 사각형을 재계산할지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getWalkPreference() {#getWalkPreference--}
```
public WalkPreference getWalkPreference()
```


동적 접착을 사용하여 도형이 모호한 위치로 이동할 때 1차원 도형의 끝점이 붙어 있는 도형의 수평 또는 수직 연결 지점으로 이동하는지를 지정합니다.

**Returns:**
[WalkPreference](../../com.aspose.diagram/walkpreference)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropSource() {#isDropSource--}
```
public BoolValue isDropSource()
```


도형을 그룹에 끌어다 놓아 그룹에 추가할 수 있는지 여부를 지정합니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isReplaceLockShapeData() {#isReplaceLockShapeData--}
```
public BoolValue isReplaceLockShapeData()
```


마스터 도형의 지정된 셀 값이 도형 교체 작업 중 교체되는 도형의 값(로컬 값 포함)을 덮어쓰는지 여부를 나타냅니다.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


이 속성에 대한 설명은 [getDel()](../../com.aspose.diagram/misc\#getDel--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

