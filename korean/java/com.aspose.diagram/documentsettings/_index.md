---
title: DocumentSettings
second_title: Aspose.Diagram for Java API 참조
description: 문서 설정을 지정하는 요소를 포함합니다.
type: docs
weight: 126
url: /ko/java/com.aspose.diagram/documentsettings/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSettings
```

문서 설정을 지정하는 요소를 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachedToolbars()](#getAttachedToolbars--) | 사용자 정의 도구 모음을 나타내는 MIME(다목적 인터넷 메일 확장) 인코딩된 Microsoft Visio 사용자 인터페이스(VSU) 파일입니다. |
| [getClass()](#getClass--) |  |
| [getCustomMenusFile()](#getCustomMenusFile--) | 문서에 대한 사용자 정의 메뉴와 단축키를 정의하는 Microsoft Visio 사용자 인터페이스(.vsu) 파일의 이름을 포함합니다. |
| [getCustomToolbarsFile()](#getCustomToolbarsFile--) | 문서에 대한 사용자 정의 도구 모음 및 상태 표시줄을 정의하는 Microsoft Visio 사용자 인터페이스(.vsu) 파일의 이름을 포함합니다. |
| [getDefaultFillStyle()](#getDefaultFillStyle--) | StyleSheet 요소의 ID를 지정합니다. |
| [getDefaultGuideStyle()](#getDefaultGuideStyle--) | StyleSheet 요소의 ID를 지정합니다. |
| [getDefaultLineStyle()](#getDefaultLineStyle--) | StyleSheet 요소의 ID를 지정합니다. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | StyleSheet 요소의 ID를 지정합니다. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | 문서 또는 창에 대해 동적 그리드 기능이 활성화되어 있는지 지정합니다. |
| [getGlueSettings()](#getGlueSettings--) | 문서에서 접착이 활성화된 경우 도형이 접착되는 객체를 지정합니다. |
| [getProtectBkgnds()](#getProtectBkgnds--) | 사용자가 배경 페이지를 삭제하거나 편집하지 못하도록 방지되는지 지정합니다. |
| [getProtectMasters()](#getProtectMasters--) | 사용자가 마스터를 만들거나 편집하거나 삭제하지 못하도록 방지되는지 지정합니다. |
| [getProtectShapes()](#getProtectShapes--) | 사용자가 LockSelect 요소가 1로 설정된 도형을 선택하지 못하도록 방지되는지 지정합니다. |
| [getProtectStyles()](#getProtectStyles--) | 사용자가 스타일을 만들거나 편집하지 못하도록 방지되는지 지정합니다. |
| [getSnapAngles()](#getSnapAngles--) | SnapAngle 요소들의 컬렉션을 포함합니다. |
| [getSnapExtensions()](#getSnapExtensions--) | 활성 창에 대해 특정 스냅 확장 설정이 활성화되었는지 비활성화되었는지 지정합니다. |
| [getSnapSettings()](#getSnapSettings--) | 창에서 스냅이 활성화될 때 도형이 스냅되는 객체를 지정합니다. |
| [getTopPage()](#getTopPage--) | Microsoft Visio에서 문서를 열 때 표시되어야 하는 페이지의 ID를 지정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttachedToolbars(byte[] value)](#setAttachedToolbars-byte---) | 이 속성에 대한 설명은 [getAttachedToolbars()](../../com.aspose.diagram/documentsettings\#getAttachedToolbars--)을(를) 참조하십시오. |
| [setCustomMenusFile(String value)](#setCustomMenusFile-java.lang.String-) | 이 속성에 대한 설명은 [getCustomMenusFile()](../../com.aspose.diagram/documentsettings\#getCustomMenusFile--)을(를) 참조하십시오. |
| [setCustomToolbarsFile(String value)](#setCustomToolbarsFile-java.lang.String-) | 이 속성에 대한 설명은 [getCustomToolbarsFile()](../../com.aspose.diagram/documentsettings\#getCustomToolbarsFile--)을(를) 참조하십시오. |
| [setDefaultFillStyle(int value)](#setDefaultFillStyle-int-) | 이 속성에 대한 설명은 [getDefaultFillStyle()](../../com.aspose.diagram/documentsettings\#getDefaultFillStyle--)을(를) 참조하십시오. |
| [setDefaultGuideStyle(int value)](#setDefaultGuideStyle-int-) | 이 속성에 대한 설명은 [getDefaultGuideStyle()](../../com.aspose.diagram/documentsettings\#getDefaultGuideStyle--)을(를) 참조하십시오. |
| [setDefaultLineStyle(int value)](#setDefaultLineStyle-int-) | 이 속성에 대한 설명은 [getDefaultLineStyle()](../../com.aspose.diagram/documentsettings\#getDefaultLineStyle--)을(를) 참조하십시오. |
| [setDefaultTextStyle(int value)](#setDefaultTextStyle-int-) | 이 속성에 대한 설명은 [getDefaultTextStyle()](../../com.aspose.diagram/documentsettings\#getDefaultTextStyle--)을(를) 참조하십시오. |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | 이 속성에 대한 설명은 [getDynamicGridEnabled()](../../com.aspose.diagram/documentsettings\#getDynamicGridEnabled--)을(를) 참조하십시오. |
| [setGlueSettings(int value)](#setGlueSettings-int-) | 이 속성에 대한 설명은 [getGlueSettings()](../../com.aspose.diagram/documentsettings\#getGlueSettings--)을(를) 참조하십시오. |
| [setProtectBkgnds(int value)](#setProtectBkgnds-int-) | 이 속성에 대한 설명은 [getProtectBkgnds()](../../com.aspose.diagram/documentsettings\#getProtectBkgnds--)을(를) 참조하십시오. |
| [setProtectMasters(int value)](#setProtectMasters-int-) | 이 속성에 대한 설명은 [getProtectMasters()](../../com.aspose.diagram/documentsettings\#getProtectMasters--)을(를) 참조하십시오. |
| [setProtectShapes(int value)](#setProtectShapes-int-) | 이 속성에 대한 설명은 [getProtectShapes()](../../com.aspose.diagram/documentsettings\#getProtectShapes--)을(를) 참조하십시오. |
| [setProtectStyles(int value)](#setProtectStyles-int-) | 이 속성에 대한 설명은 [getProtectStyles()](../../com.aspose.diagram/documentsettings\#getProtectStyles--)을(를) 참조하십시오. |
| [setSnapAngles(FloatPointNumCollection value)](#setSnapAngles-com.aspose.diagram.FloatPointNumCollection-) | 이 속성에 대한 설명은 [getSnapAngles()](../../com.aspose.diagram/documentsettings\#getSnapAngles--)을(를) 참조하십시오. |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | 이 속성에 대한 설명은 [getSnapExtensions()](../../com.aspose.diagram/documentsettings\#getSnapExtensions--)을(를) 참조하십시오. |
| [setSnapSettings(int value)](#setSnapSettings-int-) | 이 속성에 대한 설명은 [getSnapSettings()](../../com.aspose.diagram/documentsettings\#getSnapSettings--)을(를) 참조하십시오. |
| [setTopPage(int value)](#setTopPage-int-) | 이 속성에 대한 설명은 [getTopPage()](../../com.aspose.diagram/documentsettings\#getTopPage--)을(를) 참조하십시오. |
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
### getAttachedToolbars() {#getAttachedToolbars--}
```
public byte[] getAttachedToolbars()
```


사용자 정의 도구 모음을 나타내는 MIME(다목적 인터넷 메일 확장) 인코딩된 Microsoft Visio 사용자 인터페이스(VSU) 파일입니다.

**Returns:**
byte[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomMenusFile() {#getCustomMenusFile--}
```
public String getCustomMenusFile()
```


문서에 대한 사용자 정의 메뉴와 단축키를 정의하는 Microsoft Visio 사용자 인터페이스(.vsu) 파일의 이름을 포함합니다.

**Returns:**
java.lang.String
### getCustomToolbarsFile() {#getCustomToolbarsFile--}
```
public String getCustomToolbarsFile()
```


문서에 대한 사용자 정의 도구 모음 및 상태 표시줄을 정의하는 Microsoft Visio 사용자 인터페이스(.vsu) 파일의 이름을 포함합니다.

**Returns:**
java.lang.String
### getDefaultFillStyle() {#getDefaultFillStyle--}
```
public int getDefaultFillStyle()
```


StyleSheet 요소의 ID를 지정합니다. 사용자가 그리기 도구를 사용하여 도형을 만들 때, 해당 도형은 지정된 StyleSheet 요소의 채우기 스타일을 상속합니다.

**Returns:**
int
### getDefaultGuideStyle() {#getDefaultGuideStyle--}
```
public int getDefaultGuideStyle()
```


StyleSheet 요소의 ID를 지정합니다. 사용자가 가이드를 만들 때, 해당 가이드는 지정된 StyleSheet 요소의 가이드 스타일을 상속합니다.

**Returns:**
int
### getDefaultLineStyle() {#getDefaultLineStyle--}
```
public int getDefaultLineStyle()
```


StyleSheet 요소의 ID를 지정합니다. 사용자가 그리기 도구를 사용하여 도형을 만들 때, 해당 도형은 지정된 StyleSheet 요소의 선 스타일을 상속합니다.

**Returns:**
int
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public int getDefaultTextStyle()
```


StyleSheet 요소의 ID를 지정합니다. 사용자가 그리기 도구를 사용하여 도형을 만들 때, 해당 도형은 지정된 StyleSheet 요소의 텍스트 스타일을 상속합니다.

**Returns:**
int
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
### getProtectBkgnds() {#getProtectBkgnds--}
```
public int getProtectBkgnds()
```


사용자가 배경 페이지를 삭제하거나 편집하지 못하도록 방지되는지 지정합니다.

**Returns:**
int
### getProtectMasters() {#getProtectMasters--}
```
public int getProtectMasters()
```


사용자가 마스터를 생성, 편집 또는 삭제하지 못하도록 방지하는지 지정합니다. 이 설정과 관계없이 사용자는 여전히 마스터 인스턴스를 생성할 수 있습니다.

**Returns:**
int
### getProtectShapes() {#getProtectShapes--}
```
public int getProtectShapes()
```


사용자가 LockSelect 요소가 1로 설정된 도형을 선택하지 못하도록 방지되는지 지정합니다.

**Returns:**
int
### getProtectStyles() {#getProtectStyles--}
```
public int getProtectStyles()
```


사용자가 스타일을 생성하거나 편집하지 못하도록 방지하는지 지정합니다. 그러나 이 설정과 관계없이 사용자는 여전히 스타일을 적용할 수 있습니다.

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


활성 창에 대해 특정 스냅 확장 설정이 활성화되었는지 비활성화되었는지 지정합니다.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


창에서 스냅이 활성화될 때 도형이 스냅되는 객체를 지정합니다.

**Returns:**
int
### getTopPage() {#getTopPage--}
```
public int getTopPage()
```


Microsoft Visio에서 문서를 열 때 표시되어야 하는 페이지의 ID를 지정합니다.

**Returns:**
int
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




### setAttachedToolbars(byte[] value) {#setAttachedToolbars-byte---}
```
public void setAttachedToolbars(byte[] value)
```


이 속성에 대한 설명은 [getAttachedToolbars()](../../com.aspose.diagram/documentsettings\#getAttachedToolbars--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setCustomMenusFile(String value) {#setCustomMenusFile-java.lang.String-}
```
public void setCustomMenusFile(String value)
```


이 속성에 대한 설명은 [getCustomMenusFile()](../../com.aspose.diagram/documentsettings\#getCustomMenusFile--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setCustomToolbarsFile(String value) {#setCustomToolbarsFile-java.lang.String-}
```
public void setCustomToolbarsFile(String value)
```


이 속성에 대한 설명은 [getCustomToolbarsFile()](../../com.aspose.diagram/documentsettings\#getCustomToolbarsFile--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDefaultFillStyle(int value) {#setDefaultFillStyle-int-}
```
public void setDefaultFillStyle(int value)
```


이 속성에 대한 설명은 [getDefaultFillStyle()](../../com.aspose.diagram/documentsettings\#getDefaultFillStyle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDefaultGuideStyle(int value) {#setDefaultGuideStyle-int-}
```
public void setDefaultGuideStyle(int value)
```


이 속성에 대한 설명은 [getDefaultGuideStyle()](../../com.aspose.diagram/documentsettings\#getDefaultGuideStyle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDefaultLineStyle(int value) {#setDefaultLineStyle-int-}
```
public void setDefaultLineStyle(int value)
```


이 속성에 대한 설명은 [getDefaultLineStyle()](../../com.aspose.diagram/documentsettings\#getDefaultLineStyle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDefaultTextStyle(int value) {#setDefaultTextStyle-int-}
```
public void setDefaultTextStyle(int value)
```


이 속성에 대한 설명은 [getDefaultTextStyle()](../../com.aspose.diagram/documentsettings\#getDefaultTextStyle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


이 속성에 대한 설명은 [getDynamicGridEnabled()](../../com.aspose.diagram/documentsettings\#getDynamicGridEnabled--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


이 속성에 대한 설명은 [getGlueSettings()](../../com.aspose.diagram/documentsettings\#getGlueSettings--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setProtectBkgnds(int value) {#setProtectBkgnds-int-}
```
public void setProtectBkgnds(int value)
```


이 속성에 대한 설명은 [getProtectBkgnds()](../../com.aspose.diagram/documentsettings\#getProtectBkgnds--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setProtectMasters(int value) {#setProtectMasters-int-}
```
public void setProtectMasters(int value)
```


이 속성에 대한 설명은 [getProtectMasters()](../../com.aspose.diagram/documentsettings\#getProtectMasters--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setProtectShapes(int value) {#setProtectShapes-int-}
```
public void setProtectShapes(int value)
```


이 속성에 대한 설명은 [getProtectShapes()](../../com.aspose.diagram/documentsettings\#getProtectShapes--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setProtectStyles(int value) {#setProtectStyles-int-}
```
public void setProtectStyles(int value)
```


이 속성에 대한 설명은 [getProtectStyles()](../../com.aspose.diagram/documentsettings\#getProtectStyles--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSnapAngles(FloatPointNumCollection value) {#setSnapAngles-com.aspose.diagram.FloatPointNumCollection-}
```
public void setSnapAngles(FloatPointNumCollection value)
```


이 속성에 대한 설명은 [getSnapAngles()](../../com.aspose.diagram/documentsettings\#getSnapAngles--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection) |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


이 속성에 대한 설명은 [getSnapExtensions()](../../com.aspose.diagram/documentsettings\#getSnapExtensions--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


이 속성에 대한 설명은 [getSnapSettings()](../../com.aspose.diagram/documentsettings\#getSnapSettings--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTopPage(int value) {#setTopPage-int-}
```
public void setTopPage(int value)
```


이 속성에 대한 설명은 [getTopPage()](../../com.aspose.diagram/documentsettings\#getTopPage--)을(를) 참조하십시오.

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

