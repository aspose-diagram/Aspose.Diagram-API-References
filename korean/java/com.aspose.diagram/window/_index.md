---
title: 창
second_title: Aspose.Diagram for Java API 참조
description: Microsoft Visio 인스턴스에서 열린 창을 나타냅니다.
type: docs
weight: 444
url: /ko/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Microsoft Visio 인스턴스에서 열려 있는 창을 나타냅니다. 이 요소는 DatadiagramML 파일이 Visio에 처음 열릴 때 애플리케이션 작업 영역에 사용자 인터페이스 창을 정확히 재생성하는 데 필요한 정보를 포함합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Window()](#Window--) | 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | 컨테이너 ID: 페이지, 시트 또는 마스터. |
| [getContainerType()](#getContainerType--) | 다음 값 중 하나일 수 있습니다: Document, Page, 또는 Master. |
| [getDocument()](#getDocument--) | 이 창에 표시되는 문서의 파일 경로. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | 문서 또는 창에 대해 동적 그리드 기능이 활성화되어 있는지 지정합니다. |
| [getGlueSettings()](#getGlueSettings--) | 문서에서 접착이 활성화된 경우 도형이 접착되는 객체를 지정합니다. |
| [getID()](#getID--) | 부모 요소 내에서 해당 요소의 고유 ID입니다. |
| [getMaster()](#getMaster--) | 이 창이 마스터를 표시하는 경우 마스터 ID. |
| [getPage()](#getPage--) | 이 창이 페이지를 표시하는 경우 페이지 ID. |
| [getParentWindow()](#getParentWindow--) | 이 스텐실 창이 포함된 창의 ID. |
| [getReadOnly()](#getReadOnly--) | 이 스텐실이 문서 스텐실이 아닌 경우 읽기 전용 플래그. |
| [getSheet()](#getSheet--) | 컨테이너 내 시트 ID. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | 창에 연결 지점이 표시되는지 여부를 지정합니다. |
| [getShowGrid()](#getShowGrid--) | 그리기 창에 격자가 표시되는지 여부를 지정합니다. |
| [getShowGuides()](#getShowGuides--) | 그리기 창에 가이드가 표시되는지 여부를 지정합니다. |
| [getShowPageBreaks()](#getShowPageBreaks--) | 창에 페이지 구분이 표시되는지 여부를 지정합니다. |
| [getShowRulers()](#getShowRulers--) | 그리기 창에 눈금자가 표시되는지 여부를 지정합니다. |
| [getSnapAngles()](#getSnapAngles--) | SnapAngle 요소들의 컬렉션을 포함합니다. |
| [getSnapExtensions()](#getSnapExtensions--) | 활성 창에 대해 특정 스냅 확장 설정이 활성화되었는지 비활성화되었는지 지정합니다. |
| [getSnapSettings()](#getSnapSettings--) | 창에서 스냅이 활성화될 때 도형이 스냅되는 객체를 지정합니다. |
| [getStencilGroup()](#getStencilGroup--) | 창이 속한 병합된 스텐실 창 그룹을 지정합니다. |
| [getStencilGroupPos()](#getStencilGroupPos--) | 창 내 그룹에서 스텐실의 상대 위치를 지정하는 정수를 포함합니다. |
| [getTabSplitterPos()](#getTabSplitterPos--) | 그리기 창의 페이지 탭 컨트롤 너비를 지정합니다(그리기 창 전체 너비에 대한 비율). |
| [getViewCenterX()](#getViewCenterX--) | 선택적 double. |
| [getViewCenterY()](#getViewCenterY--) | 선택적 double. |
| [getViewScale()](#getViewScale--) | 선택적 double. |
| [getWindowHeight()](#getWindowHeight--) | 창 사각형의 높이. |
| [getWindowLeft()](#getWindowLeft--) | 창 사각형의 왼쪽 좌표. |
| [getWindowState()](#getWindowState--) | 이 속성은 다음 값들의 합계가 될 수 있습니다. |
| [getWindowTop()](#getWindowTop--) | 창 사각형의 상단 좌표. |
| [getWindowType()](#getWindowType--) | 다음 중 하나일 수 있는 열거형 값: Drawing, Sheet, Stencil 또는 Icon. WindowType='Stencil'인 Window 요소는 부모 그리기 창(WindowType='Drawing') 뒤에, 다른 그리기 창 요소들 앞에 나타나야 합니다. |
| [getWindowWidth()](#getWindowWidth--) | 창 사각형의 너비. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | 이 속성에 대한 설명은 [getContainer()](../../com.aspose.diagram/window\#getContainer--)을(를) 참조하십시오. |
| [setContainerType(int value)](#setContainerType-int-) | 이 속성에 대한 설명은 [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)을(를) 참조하십시오. |
| [setDocument(String value)](#setDocument-java.lang.String-) | 이 속성에 대한 설명은 [getDocument()](../../com.aspose.diagram/window\#getDocument--) 를 참조하십시오. |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | 이 속성에 대한 설명은 [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) 를 참조하십시오. |
| [setGlueSettings(int value)](#setGlueSettings-int-) | 이 속성에 대한 설명은 [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) 를 참조하십시오. |
| [setID(int value)](#setID-int-) | 이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/window\#getID--) 를 참조하십시오. |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | 이 속성에 대한 설명은 [getMaster()](../../com.aspose.diagram/window\#getMaster--) 를 참조하십시오. |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | 이 속성에 대한 설명은 [getPage()](../../com.aspose.diagram/window\#getPage--) 를 참조하십시오. |
| [setParentWindow(int value)](#setParentWindow-int-) | 이 속성에 대한 설명은 [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) 를 참조하십시오. |
| [setReadOnly(int value)](#setReadOnly-int-) | 이 속성에 대한 설명은 [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) 를 참조하십시오. |
| [setSheet(int value)](#setSheet-int-) | 이 속성에 대한 설명은 [getSheet()](../../com.aspose.diagram/window\#getSheet--) 를 참조하십시오. |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | 이 속성에 대한 설명은 [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) 를 참조하십시오. |
| [setShowGrid(int value)](#setShowGrid-int-) | 이 속성에 대한 설명은 [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) 를 참조하십시오. |
| [setShowGuides(int value)](#setShowGuides-int-) | 이 속성에 대한 설명은 [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) 를 참조하십시오. |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | 이 속성에 대한 설명은 [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) 를 참조하십시오. |
| [setShowRulers(int value)](#setShowRulers-int-) | 이 속성에 대한 설명은 [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) 를 참조하십시오. |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | 이 속성에 대한 설명은 [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) 를 참조하십시오. |
| [setSnapSettings(int value)](#setSnapSettings-int-) | 이 속성에 대한 설명은 [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) 를 참조하십시오. |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | 이 속성에 대한 설명은 [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) 를 참조하십시오. |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | 이 속성에 대한 설명은 [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) 를 참조하십시오. |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | 이 속성에 대한 설명은 [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) 를 참조하십시오. |
| [setViewCenterX(double value)](#setViewCenterX-double-) | 이 속성에 대한 설명은 [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) 를 참조하십시오. |
| [setViewCenterY(double value)](#setViewCenterY-double-) | 이 속성에 대한 설명은 [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) 를 참조하십시오. |
| [setViewScale(double value)](#setViewScale-double-) | 이 속성에 대한 설명은 [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) 를 참조하십시오. |
| [setWindowHeight(long value)](#setWindowHeight-long-) | 이 속성에 대한 설명은 [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) 를 참조하십시오. |
| [setWindowLeft(int value)](#setWindowLeft-int-) | 이 속성에 대한 설명은 [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) 를 참조하십시오. |
| [setWindowState(int value)](#setWindowState-int-) | 이 속성에 대한 설명은 [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) 를 참조하십시오. |
| [setWindowTop(int value)](#setWindowTop-int-) | 이 속성에 대한 설명은 [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)을(를) 참조하십시오. |
| [setWindowType(int value)](#setWindowType-int-) | 이 속성에 대한 설명은 [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)을(를) 참조하십시오. |
| [setWindowWidth(long value)](#setWindowWidth-long-) | 이 속성에 대한 설명은 [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)을(를) 참조하십시오. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
```


생성자.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public int getContainer()
```


컨테이너 ID: 페이지, 시트 또는 마스터. ContainerType이 지정된 경우에만 관련 있고 필요합니다.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


다음 값 중 하나일 수 있습니다: Document, Page, 또는 Master. WindowType이 Drawing 또는 Sheet로 지정된 경우에만 해당됩니다.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


이 창에 표시되는 문서의 파일 경로입니다. 이 속성은 WindowType이 Stencil으로 지정된 창에 해당합니다.

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


문서 또는 창에 대해 동적 그리드 기능이 활성화되어 있는지 지정합니다.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


문서에서 접착이 활성화된 경우 도형이 접착되는 객체를 지정합니다.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


부모 요소 내에서 해당 요소의 고유 ID입니다.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


이 창이 마스터를 표시하는 경우 마스터 ID.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


창이 페이지를 표시하는 경우 페이지 ID입니다. WindowType이 Drawing으로, ContainerType이 Page로 지정된 경우에만 해당합니다.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


이 스텐실 창이 포함된 창의 ID입니다. WindowType이 Stencil으로 지정된 경우에만 해당합니다.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


이 스텐실이 문서 스텐실이 아닌 경우 읽기 전용 플래그.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


컨테이너에 있는 시트의 ID입니다. Container가 Sheet로 지정된 경우에만 해당합니다.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


창에 연결 지점이 표시되는지 여부를 지정합니다.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


그리기 창에 격자가 표시되는지 여부를 지정합니다.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


그리기 창에 가이드가 표시되는지 여부를 지정합니다.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


창에 페이지 구분이 표시되는지 여부를 지정합니다.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


그리기 창에 눈금자가 표시되는지 여부를 지정합니다.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


SnapAngle 요소들의 컬렉션을 포함합니다.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


특정 스냅 확장 설정이 활성 창에 대해 활성화되었는지 비활성화되었는지를 지정합니다. 값은 다음 표에 있는 값들의 합이 될 수 있습니다.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


창에서 스냅이 활성화된 경우 도형이 맞추는 객체를 지정합니다. 값은 다음 표에 있는 값들의 합일 수 있습니다.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


창이 속한 병합된 스텐실 창 그룹을 지정합니다. 이 속성은 WindowType 속성이 Stencil인 Window 요소에만 해당하며, 스텐실 창이 병합된 스텐실 창 그룹의 일부인 경우에만 적용됩니다. 동일한 병합 그룹에 속한 모든 스텐실 창은 동일한 StencilGroup 요소 값을 가집니다.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


창 내 그룹에서 스텐실의 상대 위치를 지정하는 정수를 포함합니다.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


그리기 창의 페이지 탭 컨트롤 너비를 지정합니다(그리기 창 전체 너비에 대한 비율).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


선택적 double.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


선택적 double.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


선택적 double.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


창 사각형의 높이.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


창 사각형의 왼쪽 좌표.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


이 속성은 다음 값들의 합계가 될 수 있습니다.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


창 사각형의 상단 좌표.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


다음 중 하나일 수 있는 열거형 값: Drawing, Sheet, Stencil 또는 Icon. WindowType='Stencil'인 Window 요소는 부모 그리기 창(WindowType='Drawing') 뒤에, 다른 그리기 창 요소들 앞에 나타나야 합니다.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


창 사각형의 너비.

**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setContainer(int value) {#setContainer-int-}
```
public void setContainer(int value)
```


이 속성에 대한 설명은 [getContainer()](../../com.aspose.diagram/window\#getContainer--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


이 속성에 대한 설명은 [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


이 속성에 대한 설명은 [getDocument()](../../com.aspose.diagram/window\#getDocument--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


이 속성에 대한 설명은 [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


이 속성에 대한 설명은 [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


이 속성에 대한 설명은 [getID()](../../com.aspose.diagram/window\#getID--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


이 속성에 대한 설명은 [getMaster()](../../com.aspose.diagram/window\#getMaster--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


이 속성에 대한 설명은 [getPage()](../../com.aspose.diagram/window\#getPage--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


이 속성에 대한 설명은 [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


이 속성에 대한 설명은 [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


이 속성에 대한 설명은 [getSheet()](../../com.aspose.diagram/window\#getSheet--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


이 속성에 대한 설명은 [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


이 속성에 대한 설명은 [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


이 속성에 대한 설명은 [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


이 속성에 대한 설명은 [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


이 속성에 대한 설명은 [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


이 속성에 대한 설명은 [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


이 속성에 대한 설명은 [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


이 속성에 대한 설명은 [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


이 속성에 대한 설명은 [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


이 속성에 대한 설명은 [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


이 속성에 대한 설명은 [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


이 속성에 대한 설명은 [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


이 속성에 대한 설명은 [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


이 속성에 대한 설명은 [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


이 속성에 대한 설명은 [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


이 속성에 대한 설명은 [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) 를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


이 속성에 대한 설명은 [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


이 속성에 대한 설명은 [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


이 속성에 대한 설명은 [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

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

