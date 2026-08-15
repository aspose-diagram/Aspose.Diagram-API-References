---
title: ImageSaveOptions
second_title: Aspose.Diagram for Java API 참조
description: 다이어그램 페이지를 이미지로 렌더링할 때 추가 옵션을 지정할 수 있게 합니다.
type: docs
weight: 200
url: /ko/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

다이어그램 페이지를 이미지로 렌더링할 때 추가 옵션을 지정할 수 있게 합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | 이 클래스를 새 인스턴스로 초기화하며, 이 인스턴스를 사용하여 Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat 또는 Aspose.Diagram.SaveFileFormat 형식으로 렌더링된 이미지를 저장할 수 있습니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | 지정된 저장 형식에 적합한 클래스의 저장 옵션 객체를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | 합성 중에 사용할 품질 수준을 지정합니다. |
| [getContentZoom()](#getContentZoom--) | 이 매개변수는 스케일과 유사하지만 생성된 이미지 크기에 영향을 주지는 않습니다. |
| [getDefaultFont()](#getDefaultFont--) | 다이어그램의 문자가 유니코드이고 올바른 글꼴 값이 설정되지 않았거나 로컬에 글꼴이 설치되지 않은 경우, pdf, 이미지 또는 XPS에서 블록으로 표시될 수 있습니다. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Emf 메타파일 렌더링 설정. |
| [getEnlargePage()](#getEnlargePage--) | 페이지를 확대할지 여부를 지정합니다. |
| [getExportGuideShapes()](#getExportGuideShapes--) | 가이드 도형을 내보낼지 여부를 정의합니다. |
| [getExportHiddenPage()](#getExportHiddenPage--) | 숨겨진 페이지를 내보낼지 여부를 정의합니다. |
| [getImageBrightness()](#getImageBrightness--) | 생성된 이미지의 밝기. |
| [getImageColorMode()](#getImageColorMode--) | 생성된 이미지의 색상 모드. |
| [getImageContrast()](#getImageContrast--) | 생성된 이미지의 대비. |
| [getInterpolationMode()](#getInterpolationMode--) | 이미지를 스케일링하거나 회전할 때 사용되는 알고리즘을 지정합니다. |
| [getJpegQuality()](#getJpegQuality--) | 생성된 JPEG 이미지의 품질을 결정하는 값. |
| [getPageCount()](#getPageCount--) | 멀티 페이지 TIFF 파일로 저장할 때 렌더링할 페이지 수. |
| [getPageIndex()](#getPageIndex--) | 렌더링할 첫 번째 페이지의 0 기반 인덱스. |
| [getPageSize()](#getPageSize--) | 생성된 이미지의 페이지 크기. |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | 렌더링 중 픽셀이 어떻게 오프셋되는지를 지정하는 값. |
| [getResolution()](#getResolution--) | 생성된 이미지의 해상도(인치당 도트 수). |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | 저장 영역이 PDF와 동일한지 여부를 지정합니다. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | 모든 페이지를 이미지로 저장할지, 전경만 저장할지 여부를 지정합니다. |
| [getSaveFormat()](#getSaveFormat--) | 이 저장 옵션 객체를 사용할 경우 렌더링된 다이어그램 페이지가 저장될 형식을 지정합니다. |
| [getScale()](#getScale--) | 생성된 이미지의 확대 배율. |
| [getShapes()](#getShapes--) | 렌더링할 도형. |
| [getSmoothingMode()](#getSmoothingMode--) | 선과 곡선 및 채워진 영역의 가장자리에 스무딩(안티앨리어싱)이 적용되는지 여부를 지정합니다. |
| [getTiffCompression()](#getTiffCompression--) | 생성된 이미지를 TIFF 형식으로 저장할 때 적용할 압축 유형. |
| [getWarningCallback()](#getWarningCallback--) | 경고 콜백. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | 주석을 내보낼지 여부를 정의합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | 이 속성에 대한 설명은 [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)을(를) 참조하십시오. |
| [setContentZoom(float value)](#setContentZoom-float-) | 이 속성에 대한 설명은 [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)을(를) 참조하십시오. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | 이 속성에 대한 설명은 [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)을 참조하십시오. |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | 이 속성에 대한 설명은 [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)을 참조하십시오. |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | 이 속성에 대한 설명은 [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)을(를) 참조하십시오. |
| [setExportComments(boolean value)](#setExportComments-boolean-) | 이 속성에 대한 설명은 [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)을(를) 참조하십시오. |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | 이 속성에 대한 설명은 [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)을(를) 참조하십시오. |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | 이 속성에 대한 설명은 [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)을(를) 참조하십시오. |
| [setImageBrightness(float value)](#setImageBrightness-float-) | 이 속성에 대한 설명은 [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)을(를) 참조하십시오. |
| [setImageColorMode(int value)](#setImageColorMode-int-) | 이 속성에 대한 설명은 [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)을(를) 참조하십시오. |
| [setImageContrast(float value)](#setImageContrast-float-) | 이 속성에 대한 설명은 [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)을(를) 참조하십시오. |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | 이 속성에 대한 설명은 [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)을(를) 참조하십시오. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 이 속성에 대한 설명은 [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)을(를) 참조하십시오. |
| [setPageCount(int value)](#setPageCount-int-) | 이 속성에 대한 설명은 [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)을(를) 참조하십시오. |
| [setPageIndex(int value)](#setPageIndex-int-) | 이 속성에 대한 설명은 [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)을(를) 참조하십시오. |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | 이 속성에 대한 설명은 [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)을(를) 참조하십시오. |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | 이 속성에 대한 설명은 [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)을(를) 참조하십시오. |
| [setResolution(float value)](#setResolution-float-) | 이 속성에 대한 설명은 [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)을(를) 참조하십시오. |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | 이 속성에 대한 설명은 [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)을(를) 참조하십시오. |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | 이 속성에 대한 설명은 [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)을(를) 참조하십시오. |
| [setSaveFormat(int value)](#setSaveFormat-int-) | 이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)을(를) 참조하십시오. |
| [setScale(float value)](#setScale-float-) | 이 속성에 대한 설명은 [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)을(를) 참조하십시오. |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | 이 속성에 대한 설명은 [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)을(를) 참조하십시오. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | 이 속성에 대한 설명은 [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)을(를) 참조하십시오. |
| [setTiffCompression(int value)](#setTiffCompression-int-) | 이 속성에 대한 설명은 [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)을(를) 참조하십시오. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


이 클래스를 새 인스턴스로 초기화하며, 이 인스턴스를 사용하여 Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat 또는 Aspose.Diagram.SaveFileFormat 형식으로 렌더링된 이미지를 저장할 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| saveFormat | int | Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat 또는 Aspose.Diagram.SaveFileFormat일 수 있습니다. |

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
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


합성 중에 사용할 품질 수준을 지정합니다. 이 속성은 래스터 이미지 형식으로 저장할 때만 영향을 미칩니다. 기본값은 Aspose.Diagram.Saving.CompositingQuality입니다.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


이 매개변수는 scale과 유사하지만 생성된 이미지 크기에 영향을 주지는 않습니다. 기본값은 1.0입니다. 값은 0보다 커야 합니다.

**Returns:**
float
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
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


생성된 이미지의 밝기입니다. 이 속성은 래스터 이미지 형식으로 저장할 때만 영향을 미칩니다. 기본값은 0.5입니다. 값은 0과 1 사이여야 합니다.

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


생성된 이미지의 색상 모드입니다. 이 속성은 래스터 이미지 형식으로 저장할 때만 영향을 미칩니다. 기본값은 Aspose.Diagram.Saving.ImageColorMode입니다.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


생성된 이미지의 대비입니다. 이 속성은 래스터 이미지 형식으로 저장할 때만 영향을 미칩니다. 기본값은 0.5입니다. 값은 0과 1 사이여야 합니다.

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


이미지를 확대/축소하거나 회전할 때 사용되는 알고리즘을 지정합니다. 이 속성은 래스터 이미지 형식으로 저장할 때만 영향을 미칩니다. 기본값은 Aspose.Diagram.Saving.InterpolationMode입니다.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


생성된 JPEG 이미지의 품질을 결정하는 값입니다. JPEG로 저장할 때만 영향을 미칩니다. 이 속성을 사용하여 JPEG 형식으로 저장할 때 생성된 이미지의 품질을 가져오거나 설정할 수 있습니다. 값은 0에서 100 사이이며, 0은 최저 품질이지만 최대 압축, 100은 최고 품질이지만 최소 압축을 의미합니다. 기본값은 95입니다.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


다중 페이지 TIFF 파일로 저장할 때 렌더링할 페이지 수입니다. 기본값은 MaxValue이며, 이는 다이어그램의 모든 페이지가 렌더링됨을 의미합니다.

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
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


렌더링 중 픽셀 오프셋 방식을 지정하는 값입니다. 이 속성은 래스터 이미지 형식으로 저장할 때만 영향을 미칩니다. 기본값은 Aspose.Diagram.Saving.PixelOffsetMode입니다.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


생성된 이미지의 해상도(인치당 도트 수)입니다. 이 속성는 래스터 이미지 형식으로 저장할 때만 영향을 미칩니다. 기본값은 96입니다.

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


저장 영역이 PDF와 동일한지 여부를 지정합니다. true이면 렌더링 영역이 PDF와 동일합니다. false이면 렌더링 영역이 기본값입니다. 기본값은 false입니다.

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


이 저장 옵션 객체를 사용할 경우 렌더링된 다이어그램 페이지가 저장될 형식을 지정합니다. Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat 또는 Aspose.Diagram.SaveFileFormat 중 하나일 수 있습니다.

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


생성된 이미지의 확대 배율입니다. 기본값은 1.0입니다. 값은 0보다 커야 합니다.

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


렌더링할 도형입니다. 기본 개수는 0입니다.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


선과 곡선 및 채워진 영역의 가장자리에 스무딩(안티앨리어싱)이 적용되는지 여부를 지정합니다. 이 속성은 래스터 이미지 형식으로 저장할 때만 영향을 미칩니다. 기본값은 Aspose.Diagram.Saving.SmoothingMode입니다.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


생성된 이미지를 TIFF 형식으로 저장할 때 적용할 압축 유형입니다. TIFF로 저장할 때만 영향을 미칩니다. 기본값은 Aspose.Diagram.Saving.TiffCompression입니다.

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




### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


이 속성에 대한 설명은 [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


이 속성에 대한 설명은 [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

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


이 속성에 대한 설명은 [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


이 속성에 대한 설명은 [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


이 속성에 대한 설명은 [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


이 속성에 대한 설명은 [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


이 속성에 대한 설명은 [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


이 속성에 대한 설명은 [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


이 속성에 대한 설명은 [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


이 속성에 대한 설명은 [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)을(를) 참조하십시오.

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

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


이 속성에 대한 설명은 [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


이 속성에 대한 설명은 [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


이 속성에 대한 설명은 [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


이 속성에 대한 설명은 [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


이 속성에 대한 설명은 [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


이 속성에 대한 설명은 [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


이 속성에 대한 설명은 [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


이 속성에 대한 설명은 [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


이 속성에 대한 설명은 [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)을(를) 참조하십시오.

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

