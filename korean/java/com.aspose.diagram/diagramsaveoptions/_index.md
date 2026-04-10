---
title: DiagramSaveOptions
second_title: Aspose.Diagram for Java API 참조
description: Visio VDXVSX 형식으로 다이어그램을 저장할 때 추가 옵션을 지정하는 데 사용할 수 있습니다.
type: docs
weight: 119
url: /ko/java/com.aspose.diagram/diagramsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class DiagramSaveOptions extends SaveOptions
```

Visio (VDX\\VSX) 형식으로 다이어그램을 저장할 때 추가 옵션을 지정하는 데 사용할 수 있습니다. 현재는 SaveFormat 속성만 제공하지만, 향후 다른 옵션이 추가될 예정입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DiagramSaveOptions()](#DiagramSaveOptions--) | VDX 형식으로 다이어그램을 저장하는 데 사용할 수 있는 이 클래스의 새 인스턴스를 초기화합니다. |
| [DiagramSaveOptions(int saveFormat)](#DiagramSaveOptions-int-) | VDX 또는 VSX 형식으로 다이어그램을 저장하는 데 사용할 수 있는 이 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 지정된 저장 형식에 적합한 클래스의 저장 옵션 객체를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoFitPageToDrawingContent()](#getAutoFitPageToDrawingContent--) | 그리기 내용에 맞게 페이지를 확대해야 하는지 여부를 정의합니다. |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | 다이어그램의 문자가 유니코드이고 올바른 글꼴 값이 설정되지 않았거나 로컬에 글꼴이 설치되지 않은 경우, pdf, 이미지 또는 XPS에서 블록으로 표시될 수 있습니다. |
| [getSaveFormat()](#getSaveFormat--) | 이 저장 옵션 개체를 사용하는 경우 렌더링된 다이어그램이 저장될 형식을 지정합니다. |
| [getWarningCallback()](#getWarningCallback--) | 경고 콜백. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoFitPageToDrawingContent(boolean value)](#setAutoFitPageToDrawingContent-boolean-) | 이 속성에 대한 설명은 [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--)을(를) 참조하십시오. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | 이 속성에 대한 설명은 [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)을 참조하십시오. |
| [setSaveFormat(int value)](#setSaveFormat-int-) | 이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--)을(를) 참조하십시오. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DiagramSaveOptions() {#DiagramSaveOptions--}
```
public DiagramSaveOptions()
```


VDX 형식으로 다이어그램을 저장하는 데 사용할 수 있는 이 클래스의 새 인스턴스를 초기화합니다.

### DiagramSaveOptions(int saveFormat) {#DiagramSaveOptions-int-}
```
public DiagramSaveOptions(int saveFormat)
```


VDX 또는 VSX 형식으로 다이어그램을 저장하는 데 사용할 수 있는 이 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| saveFormat | int |  |

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
### getAutoFitPageToDrawingContent() {#getAutoFitPageToDrawingContent--}
```
public boolean getAutoFitPageToDrawingContent()
```


그리기 내용에 맞게 페이지를 확대해야 하는지 여부를 정의합니다. 기본값은 false입니다.

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
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


이 저장 옵션 개체를 사용하는 경우 렌더링된 다이어그램이 저장될 형식을 지정합니다. Aspose.Diagram.SaveFileFormat 또는 Aspose.Diagram.SaveFileFormat일 수 있습니다.

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




### setAutoFitPageToDrawingContent(boolean value) {#setAutoFitPageToDrawingContent-boolean-}
```
public void setAutoFitPageToDrawingContent(boolean value)
```


이 속성에 대한 설명은 [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


이 속성에 대한 설명은 [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--)을(를) 참조하십시오.

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

