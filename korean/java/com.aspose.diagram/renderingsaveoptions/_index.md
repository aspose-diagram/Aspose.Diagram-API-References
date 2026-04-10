---
title: RenderingSaveOptions
second_title: Aspose.Diagram for Java API 참조
description: 이것은 사용자가 다이어그램을 특정 형식으로 저장할 때 추가 옵션을 지정할 수 있도록 하는 클래스들을 위한 추상 기본 클래스입니다.
type: docs
weight: 327
url: /ko/java/com.aspose.diagram/renderingsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public abstract class RenderingSaveOptions extends SaveOptions
```

이것은 사용자가 다이어그램을 특정 형식으로 저장할 때 추가 옵션을 지정할 수 있도록 하는 클래스들을 위한 추상 기본 클래스입니다.
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
| [getPageSize()](#getPageSize--) | 생성된 이미지의 페이지 크기. |
| [getSaveFormat()](#getSaveFormat--) | 이 저장 옵션 객체가 사용될 경우 문서가 저장될 형식을 지정합니다. |
| [getShapes()](#getShapes--) | 렌더링할 도형. |
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
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | 이 속성에 대한 설명은 [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)을(를) 참조하십시오. |
| [setSaveFormat(int value)](#setSaveFormat-int-) | 이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)을(를) 참조하십시오. |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | 이 속성에 대한 설명은 [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)을(를) 참조하십시오. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


생성된 이미지의 페이지 크기입니다. [PageSize](../../com.aspose.diagram/pagesize)이거나 null일 수 있습니다. 기본값은 null입니다. PageSize가 null이면 생성된 이미지의 페이지 크기는 소스 다이어그램에서 가져옵니다.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


이 저장 옵션 객체가 사용될 경우 문서가 저장될 형식을 지정합니다.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


렌더링할 도형입니다. 기본 개수는 0입니다.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


이 속성에 대한 설명은 [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


이 속성에 대한 설명은 [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

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

