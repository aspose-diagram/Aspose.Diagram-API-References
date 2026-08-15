---
title: PdfSaveOptions
second_title: Aspose.Diagram for Java API 참조
description: 다이어그램 페이지를 PDF로 렌더링할 때 추가 옵션을 지정할 수 있습니다.
type: docs
weight: 281
url: /ko/java/com.aspose.diagram/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PdfSaveOptions extends RenderingSaveOptions
```

다이어그램 페이지를 PDF로 렌더링할 때 추가 옵션을 지정할 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | 이 클래스를 새 인스턴스로 초기화하여 Aspose.Diagram.SaveFileFormat 형식으로 문서를 저장할 수 있습니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 지정된 저장 형식에 적합한 클래스의 저장 옵션 객체를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompliance()](#getCompliance--) | 생성된 PDF 문서에 대한 원하는 호환성 수준. |
| [getDefaultFont()](#getDefaultFont--) | 다이어그램의 문자가 유니코드이고 올바른 글꼴 값이 설정되지 않았거나 로컬에 글꼴이 설치되지 않은 경우, pdf, 이미지 또는 XPS에서 블록으로 표시될 수 있습니다. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Emf 메타파일 렌더링 설정. |
| [getEncryptionDetails()](#getEncryptionDetails--) | 암호화 세부 정보. |
| [getEnlargePage()](#getEnlargePage--) | 페이지를 확대할지 여부를 지정합니다. |
| [getExportGuideShapes()](#getExportGuideShapes--) | 가이드 도형을 내보낼지 여부를 정의합니다. |
| [getExportHiddenPage()](#getExportHiddenPage--) | 숨겨진 페이지를 내보낼지 여부를 정의합니다. |
| [getHorizontalResolution()](#getHorizontalResolution--) | 생성된 이미지의 수평 해상도, 인치당 도트 수. |
| [getJpegQuality()](#getJpegQuality--) | 이미지에 대한 JPEG 압축 품질을 지정합니다( JPEG 압축을 사용하는 경우). |
| [getPageCount()](#getPageCount--) | PDF에서 렌더링할 페이지 수입니다. |
| [getPageIndex()](#getPageIndex--) | 렌더링할 첫 번째 페이지의 0 기반 인덱스. |
| [getPageSavingCallback()](#getPageSavingCallback--) | 페이지 저장 프로세스의 진행 상황을 제어/표시합니다. |
| [getPageSize()](#getPageSize--) | 생성된 이미지의 페이지 크기. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | 모든 페이지를 이미지로 저장할지, 전경만 저장할지 여부를 지정합니다. |
| [getSaveFormat()](#getSaveFormat--) | 이 저장 옵션 객체를 사용할 경우 렌더링된 다이어그램 페이지가 저장될 형식을 지정합니다. |
| [getShapes()](#getShapes--) | 렌더링할 도형. |
| [getSplitMultiPages()](#getSplitMultiPages--) | 페이지 설정에 따라 다이어그램을 여러 페이지로 분할할지 여부를 정의합니다. |
| [getTextCompression()](#getTextCompression--) | 이미지를 제외한 모든 콘텐츠 스트림에 사용할 압축 유형을 지정합니다. |
| [getVerticalResolution()](#getVerticalResolution--) | 생성된 이미지의 수직 해상도, 인치당 도트 수. |
| [getWarningCallback()](#getWarningCallback--) | 경고 콜백. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | 주석을 내보낼지 여부를 정의합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompliance(int value)](#setCompliance-int-) | 이 속성에 대한 설명은 [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--)을(를) 참조하십시오. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | 이 속성에 대한 설명은 [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)을 참조하십시오. |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | 이 속성에 대한 설명은 [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)을 참조하십시오. |
| [setEncryptionDetails(PdfEncryptionDetails value)](#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-) | 이 속성에 대한 설명은 [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--)을(를) 참조하십시오. |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | 이 속성에 대한 설명은 [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)을(를) 참조하십시오. |
| [setExportComments(boolean value)](#setExportComments-boolean-) | 이 속성에 대한 설명은 [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)을(를) 참조하십시오. |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | 이 속성에 대한 설명은 [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)을(를) 참조하십시오. |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | 이 속성에 대한 설명은 [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--)을(를) 참조하십시오. |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | 이 속성에 대한 설명은 [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--)을(를) 참조하십시오. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 이 속성에 대한 설명은 [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--)을(를) 참조하십시오. |
| [setPageCount(int value)](#setPageCount-int-) | 이 속성에 대한 설명은 [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--)을(를) 참조하십시오. |
| [setPageIndex(int value)](#setPageIndex-int-) | 이 속성에 대한 설명은 [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--)을(를) 참조하십시오. |
| [setPageSavingCallback(IPageSavingCallback value)](#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-) | 이 속성에 대한 설명은 [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--)을(를) 참조하십시오. |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | 이 속성에 대한 설명은 [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)을(를) 참조하십시오. |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | 이 속성에 대한 설명은 [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--)을(를) 참조하십시오. |
| [setSaveFormat(int value)](#setSaveFormat-int-) | 이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--)을(를) 참조하십시오. |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | 이 속성에 대한 설명은 [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)을(를) 참조하십시오. |
| [setSplitMultiPages(boolean value)](#setSplitMultiPages-boolean-) | 이 속성에 대한 설명은 [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--)을(를) 참조하십시오. |
| [setTextCompression(int value)](#setTextCompression-int-) | 이 속성에 대한 설명은 [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--)을(를) 참조하십시오. |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | 이 속성에 대한 설명은 [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--)을(를) 참조하십시오. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
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
### getCompliance() {#getCompliance--}
```
public int getCompliance()
```


생성된 PDF 문서에 대한 원하는 호환성 수준입니다. 기본값은 PdfCompliance.PDF\_15입니다.

**Returns:**
int
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
### getEncryptionDetails() {#getEncryptionDetails--}
```
public PdfEncryptionDetails getEncryptionDetails()
```


암호화 세부 정보입니다. 설정되지 않으면 암호화가 수행되지 않습니다.

**Returns:**
[PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails)
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
### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


생성된 이미지의 수평 해상도, 인치당 도트 수입니다. EMF 형식 이미지를 제외한 이미지 생성 메서드에 적용됩니다. 기본값은 96입니다.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


이미지에 대한 JPEG 압축 품질을 지정합니다( JPEG 압축을 사용하는 경우). 기본값은 95입니다.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


PDF에서 렌더링할 페이지 수입니다. 기본값은 MaxValue이며, 이는 다이어그램의 모든 페이지가 렌더링됨을 의미합니다.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


렌더링할 첫 번째 페이지의 0부터 시작하는 인덱스입니다. 기본값은 0입니다.

**Returns:**
int
### getPageSavingCallback() {#getPageSavingCallback--}
```
public IPageSavingCallback getPageSavingCallback()
```


페이지 저장 프로세스의 진행 상황을 제어/표시합니다.

**Returns:**
[IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback)
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


생성된 이미지의 페이지 크기입니다. [PageSize](../../com.aspose.diagram/pagesize)이거나 null일 수 있습니다. 기본값은 null입니다. PageSize가 null이면 생성된 이미지의 페이지 크기는 소스 다이어그램에서 가져옵니다.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
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
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


렌더링할 도형입니다. 기본 개수는 0입니다.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSplitMultiPages() {#getSplitMultiPages--}
```
public boolean getSplitMultiPages()
```


페이지 설정에 따라 다이어그램을 여러 페이지로 분할할지 여부를 정의합니다. 기본값은 false입니다.

**Returns:**
boolean
### getTextCompression() {#getTextCompression--}
```
public int getTextCompression()
```


이미지를 제외한 모든 콘텐츠 스트림에 사용할 압축 유형을 지정합니다. 기본값은 PdfTextCompression.FLATE입니다.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


생성된 이미지의 수직 해상도(인치당 도트 수)입니다. Emf 형식 이미지를 제외한 이미지 생성 메서드에 적용됩니다. 기본값은 96입니다.

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




### setCompliance(int value) {#setCompliance-int-}
```
public void setCompliance(int value)
```


이 속성에 대한 설명은 [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

### setEncryptionDetails(PdfEncryptionDetails value) {#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-}
```
public void setEncryptionDetails(PdfEncryptionDetails value)
```


이 속성에 대한 설명은 [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails) |  |

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


이 속성에 대한 설명은 [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int value)
```


이 속성에 대한 설명은 [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


이 속성에 대한 설명은 [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


이 속성에 대한 설명은 [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


이 속성에 대한 설명은 [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPageSavingCallback(IPageSavingCallback value) {#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-}
```
public void setPageSavingCallback(IPageSavingCallback value)
```


이 속성에 대한 설명은 [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback) |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


이 속성에 대한 설명은 [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


이 속성에 대한 설명은 [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--)을(를) 참조하십시오.

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

### setSplitMultiPages(boolean value) {#setSplitMultiPages-boolean-}
```
public void setSplitMultiPages(boolean value)
```


이 속성에 대한 설명은 [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setTextCompression(int value) {#setTextCompression-int-}
```
public void setTextCompression(int value)
```


이 속성에 대한 설명은 [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int value)
```


이 속성에 대한 설명은 [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--)을(를) 참조하십시오.

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

