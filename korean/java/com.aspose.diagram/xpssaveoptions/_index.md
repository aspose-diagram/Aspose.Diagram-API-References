---
title: XPSSaveOptions
second_title: Aspose.Diagram for Java API 참조
description: 다이어그램 페이지를 XPS로 렌더링할 때 추가 옵션을 지정할 수 있습니다.
type: docs
weight: 453
url: /ko/java/com.aspose.diagram/xpssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XPSSaveOptions extends SaveOptions
```

다이어그램 페이지를 XPS로 렌더링할 때 추가 옵션을 지정할 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [XPSSaveOptions()](#XPSSaveOptions--) | 이 클래스를 새 인스턴스로 초기화하여 Aspose.Diagram.SaveFileFormat 형식으로 문서를 저장할 수 있습니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 지정된 저장 형식에 적합한 클래스의 저장 옵션 객체를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | 다이어그램의 문자가 유니코드이고 올바른 글꼴 값이 설정되지 않았거나 로컬에 글꼴이 설치되지 않은 경우, pdf, 이미지 또는 XPS에서 블록으로 표시될 수 있습니다. |
| [getExportHiddenPage()](#getExportHiddenPage--) | 숨겨진 페이지를 내보낼지 여부를 정의합니다. |
| [getPageCount()](#getPageCount--) | XPS에서 렌더링할 페이지 수. |
| [getPageIndex()](#getPageIndex--) | 렌더링할 첫 번째 페이지의 0 기반 인덱스. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | 모든 페이지를 이미지로 저장할지, 전경만 저장할지 여부를 지정합니다. |
| [getSaveFormat()](#getSaveFormat--) | 이 저장 옵션 객체를 사용할 경우 렌더링된 다이어그램 페이지가 저장될 형식을 지정합니다. |
| [getWarningCallback()](#getWarningCallback--) | 경고 콜백. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | 이 속성에 대한 설명은 [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)을 참조하십시오. |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | 이 속성에 대한 설명은 [getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--)을 참조하십시오. |
| [setPageCount(int value)](#setPageCount-int-) | 이 속성에 대한 설명은 [getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--)을 참조하십시오. |
| [setPageIndex(int value)](#setPageIndex-int-) | 이 속성에 대한 설명은 [getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--)을 참조하십시오. |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | 이 속성에 대한 설명은 [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--)을 참조하십시오. |
| [setSaveFormat(int value)](#setSaveFormat-int-) | 이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--)을 참조하십시오. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XPSSaveOptions() {#XPSSaveOptions--}
```
public XPSSaveOptions()
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


XPS에서 렌더링할 페이지 수. 기본값은 MaxValue이며, 이는 다이어그램의 모든 페이지가 렌더링됨을 의미합니다.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


렌더링할 첫 번째 페이지의 0부터 시작하는 인덱스입니다. 기본값은 0입니다.

**Returns:**
int
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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


이 속성에 대한 설명은 [getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


이 속성에 대한 설명은 [getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


이 속성에 대한 설명은 [getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


이 속성에 대한 설명은 [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

