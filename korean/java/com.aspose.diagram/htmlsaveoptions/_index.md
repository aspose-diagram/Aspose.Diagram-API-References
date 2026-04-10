---
title: HTMLSaveOptions
second_title: Aspose.Diagram for Java API 참조
description: 다이어그램 페이지를 HTML로 렌더링할 때 추가 옵션을 지정할 수 있게 합니다.
type: docs
weight: 187
url: /ko/java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

다이어그램 페이지를 HTML로 렌더링할 때 추가 옵션을 지정할 수 있게 합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | 이 클래스를 새 인스턴스로 초기화하여 Aspose.Diagram.SaveFileFormat 형식으로 문서를 저장할 수 있습니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 지정된 저장 형식에 적합한 클래스의 저장 옵션 객체를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | 다이어그램의 문자가 유니코드이고 올바른 글꼴 값이 설정되지 않았거나 로컬에 글꼴이 설치되지 않은 경우, pdf, 이미지 또는 XPS에서 블록으로 표시될 수 있습니다. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Emf 메타파일 렌더링 설정. |
| [getEnlargePage()](#getEnlargePage--) | 페이지를 확대할지 여부를 지정합니다. |
| [getExportGuideShapes()](#getExportGuideShapes--) | 가이드 도형을 내보낼지 여부를 정의합니다. |
| [getExportHiddenPage()](#getExportHiddenPage--) | 숨겨진 페이지를 내보낼지 여부를 정의합니다. |
| [getPageCount()](#getPageCount--) | HTML에서 렌더링할 페이지 수. |
| [getPageIndex()](#getPageIndex--) | 렌더링할 첫 번째 페이지의 0 기반 인덱스. |
| [getPageSize()](#getPageSize--) | 생성된 이미지의 페이지 크기. |
| [getResolution()](#getResolution--) | 생성된 HTML의 해상도(인치당 도트 수). |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | HTML을 단일 파일로 저장할지 여부를 나타냅니다. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | 모든 페이지를 이미지로 저장할지, 전경만 저장할지 여부를 지정합니다. |
| [getSaveFormat()](#getSaveFormat--) | 이 저장 옵션 객체를 사용할 경우 렌더링된 다이어그램 페이지가 저장될 형식을 지정합니다. |
| [getSaveTitle()](#getSaveTitle--) | 제목을 내보낼지 여부를 정의합니다. |
| [getSaveToolBar()](#getSaveToolBar--) | 툴바 저장 여부를 지정합니다. 기본값은 true입니다. |
| [getShapes()](#getShapes--) | 렌더링할 도형. |
| [getStreamProvider()](#getStreamProvider--) | 객체를 내보내기 위한 IStreamProvider. |
| [getTitle()](#getTitle--) | HTML에서 렌더링할 다이어그램의 제목. |
| [getWarningCallback()](#getWarningCallback--) | 경고 콜백. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | 주석을 내보낼지 여부를 정의합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | 이 속성에 대한 설명은 [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)을 참조하십시오. |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | 이 속성에 대한 설명은 [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)을 참조하십시오. |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | 이 속성에 대한 설명은 [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)을(를) 참조하십시오. |
| [setExportComments(boolean value)](#setExportComments-boolean-) | 이 속성에 대한 설명은 [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)을(를) 참조하십시오. |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | 이 속성에 대한 설명은 [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)을(를) 참조하십시오. |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | 이 속성에 대한 설명은 [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--)을(를) 참조하십시오. |
| [setPageCount(int value)](#setPageCount-int-) | 이 속성에 대한 설명은 [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--)을(를) 참조하십시오. |
| [setPageIndex(int value)](#setPageIndex-int-) | 이 속성에 대한 설명은 [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--)을(를) 참조하십시오. |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | 이 속성에 대한 설명은 [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)을(를) 참조하십시오. |
| [setResolution(int value)](#setResolution-int-) | 이 속성에 대한 설명은 [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--)을(를) 참조하십시오. |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | 이 속성에 대한 설명은 [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--)을(를) 참조하십시오. |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | 이 속성에 대한 설명은 [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--)을(를) 참조하십시오. |
| [setSaveFormat(int value)](#setSaveFormat-int-) | 이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--)을(를) 참조하십시오. |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | 이 속성에 대한 설명은 [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--)을(를) 참조하십시오. |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | 이 속성에 대한 설명은 [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--)을(를) 참조하십시오. |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | 이 속성에 대한 설명은 [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)을(를) 참조하십시오. |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | 이 속성에 대한 설명은 [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--)을(를) 참조하십시오. |
| [setTitle(String value)](#setTitle-java.lang.String-) | 이 속성에 대한 설명은 [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--)을(를) 참조하십시오. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
```


이 클래스를 새 인스턴스로 초기화하여 Aspose.Diagram.SaveFileFormat 형식으로 문서를 저장할 수 있습니다.

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


지정된 저장 형식에 적합한 클래스의 저장 옵션 객체를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| saveFormat | int | 저장 옵션 객체를 만들기 위한 Aspose.Diagram.SaveFileFormat입니다. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
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
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


다이어그램의 문자가 유니코드이며 올바른 글꼴 값이 설정되지 않았거나 글꼴이 로컬에 설치되지 않은 경우, PDF, 이미지 또는 XPS에서 블록으로 표시될 수 있습니다. MingLiu 또는 MS Gothic과 같은 DefaultFont를 설정하여 이러한 문자를 표시하십시오.

**Returns:**
java.lang.String
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Emf 메타파일 렌더링을 위한 설정입니다. "EMF+ Dual" 로 식별되는 EMF 메타파일은 EMF+ 레코드와 EMF 레코드를 모두 포함할 수 있습니다. 두 종류의 레코드 중 하나를 사용하여 이미지를 렌더링하거나, EMF+ 레코드만, 혹은 EMF 레코드만 사용할 수 있습니다. EmfPlusPrefer가 설정되면 EMF+ 레코드가 파싱되고, 그렇지 않으면 EMF 레코드만 파싱됩니다. 기본값은 EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


페이지 확대 여부를 지정합니다. true이면 페이지를 확대하고, false이면 확대하지 않습니다. 기본값은 true입니다.

**Returns:**
boolean
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


가이드 도형을 내보낼지 여부를 정의합니다. 기본값은 true입니다.

**Returns:**
boolean
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


숨겨진 페이지를 내보낼지 여부를 정의합니다. 기본값은 true입니다.

**Returns:**
boolean
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


HTML에서 렌더링할 페이지 수입니다. 기본값은 MaxValue이며, 이는 다이어그램의 모든 페이지가 렌더링됨을 의미합니다.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


렌더링할 첫 번째 페이지의 0부터 시작하는 인덱스입니다. 기본값은 0입니다.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


생성된 이미지의 페이지 크기입니다. [PageSize](../../com.aspose.diagram/pagesize)이거나 null일 수 있습니다. 기본값은 null입니다. PageSize가 null이면 생성된 이미지의 페이지 크기는 소스 다이어그램에서 가져옵니다.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getResolution() {#getResolution--}
```
public int getResolution()
```


생성된 HTML의 해상도(인치당 도트 수)입니다. 이 속성은 HTML로 저장할 때만 영향을 미칩니다. 기본값은 96입니다.

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


HTML을 단일 파일로 저장할지 여부를 나타냅니다. 기본값은 false입니다. 페이지가 여러 개 있는 경우 해당 페이지와 기타 리소스를 별도의 파일로 저장해야 합니다. 일부 시나리오에서는 전송 편의를 위해 하나의 결과 파일만 필요할 수 있습니다. 이 경우 사용자는 이 속성을 true로 설정할 수 있습니다.

**Returns:**
boolean
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


이미지에 모든 페이지를 저장할지 아니면 전경만 저장할지 지정합니다. true인 경우 전경 페이지만 렌더링됩니다(배경이 있으면 포함). false인 경우 전경 페이지가 렌더링된 뒤 빈 배경 페이지가 렌더링됩니다. PageCount가 1보다 클 때만 true를 반환할 수 있습니다. 기본값은 false입니다.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


이 저장 옵션 객체를 사용할 경우 렌더링된 다이어그램 페이지가 저장될 형식을 지정합니다. Aspose.Diagram.SaveFileFormat만 사용할 수 있습니다.

**Returns:**
int
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


제목을 내보낼지 여부를 정의합니다. 기본값은 true입니다.

**Returns:**
boolean
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


툴바 저장 여부를 지정합니다. 기본값은 true입니다.

**Returns:**
boolean
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


렌더링할 도형입니다. 기본 개수는 0입니다.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


객체를 내보내기 위한 IStreamProvider.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


HTML로 렌더링할 다이어그램의 제목입니다. Title이 null이면 Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties)가 제목으로 사용됩니다. Diagram.DocumentProperties.Title이 null이거나 비어 있으면 다이어그램 파일 이름이 제목으로 사용됩니다.

**Returns:**
java.lang.String
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


경고 콜백.

**Returns:**
[IWarningCallback](../../com.aspose.diagram/iwarningcallback)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExportComments() {#isExportComments--}
```
public boolean isExportComments()
```


주석을 내보낼지 여부를 정의합니다. 기본값은 false입니다.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


이 속성에 대한 설명은 [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


이 속성에 대한 설명은 [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


이 속성에 대한 설명은 [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


이 속성에 대한 설명은 [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


이 속성에 대한 설명은 [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


이 속성에 대한 설명은 [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


이 속성에 대한 설명은 [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


이 속성에 대한 설명은 [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


이 속성에 대한 설명은 [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


이 속성에 대한 설명은 [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


이 속성에 대한 설명은 [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


이 속성에 대한 설명은 [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


이 속성에 대한 설명은 [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


이 속성에 대한 설명은 [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


이 속성에 대한 설명은 [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


이 속성에 대한 설명은 [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


이 속성에 대한 설명은 [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.diagram/iwarningcallback) |  |

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

