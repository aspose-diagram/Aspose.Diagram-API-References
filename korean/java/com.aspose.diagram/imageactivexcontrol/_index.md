---
title: ImageActiveXControl
second_title: Aspose.Diagram for Java API 참조
description: 이미지 컨트롤을 나타냅니다.
type: docs
weight: 197
url: /ko/java/com.aspose.diagram/imageactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ImageActiveXControl extends ActiveXControl
```

이미지 컨트롤을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | the ole color of the background. |
| [getBorderOleColor()](#getBorderOleColor--) | the ole color of the background. |
| [getBorderStyle()](#getBorderStyle--) | the type of border used by the control. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | the binary data of the control. |
| [getForeOleColor()](#getForeOleColor--) | the ole color of the foreground. |
| [getHeight()](#getHeight--) | the height of the control in unit of points. |
| [getIMEMode()](#getIMEMode--) | the default run-time mode of the Input Method Editor for the control as it receives focus. |
| [getMouseIcon()](#getMouseIcon--) | 컨트롤에 대한 마우스 포인터로 표시할 사용자 지정 아이콘. |
| [getMousePointer()](#getMousePointer--) | 컨트롤에 대한 마우스 포인터로 표시되는 아이콘 유형. |
| [getPicture()](#getPicture--) | 그림의 데이터입니다. |
| [getPictureAlignment()](#getPictureAlignment--) | 폼 또는 이미지 내부에서 그림의 정렬. |
| [getPictureSizeMode()](#getPictureSizeMode--) | 그림을 표시하는 방법. |
| [getSpecialEffect()](#getSpecialEffect--) | 컨트롤의 특수 효과. |
| [getType()](#getType--) | ActiveX 컨트롤의 유형을 가져옵니다. |
| [getWidth()](#getWidth--) | 포인트 단위의 컨트롤 너비. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | 컨트롤이 전체 내용을 표시하도록 자동으로 크기를 조정하는지 여부를 나타냅니다. |
| [isEnabled()](#isEnabled--) | 컨트롤이 포커스를 받을 수 있고 사용자 생성 이벤트에 응답할 수 있는지 여부를 나타냅니다. |
| [isLocked()](#isLocked--) | 컨트롤의 데이터가 편집을 위해 잠겨 있는지 여부를 나타냅니다. |
| [isTiled()](#isTiled--) | 그림이 배경 전체에 타일 형식으로 표시되는지 여부를 나타냅니다. |
| [isTransparent()](#isTransparent--) | 컨트롤이 투명한지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | 이 속성에 대한 설명은 [isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\#isAutoSize--)을(를) 참조하십시오. |
| [setBackOleColor(int value)](#setBackOleColor-int-) | 이 속성에 대한 설명은 [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)을 참조하십시오 |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | 이 속성에 대한 설명은 [getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\#getBorderOleColor--)을(를) 참조하십시오. |
| [setBorderStyle(int value)](#setBorderStyle-int-) | 이 속성에 대한 설명은 [getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\#getBorderStyle--)을(를) 참조하십시오. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 이 속성에 대한 설명은 [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)을(를) 참조하십시오. |
| [setForeOleColor(int value)](#setForeOleColor-int-) | 이 속성에 대한 설명은 [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)을(를) 참조하십시오. |
| [setHeight(double value)](#setHeight-double-) | 이 속성에 대한 설명은 [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)을(를) 참조하십시오. |
| [setIMEMode(int value)](#setIMEMode-int-) | 이 속성에 대한 설명은 [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)을(를) 참조하십시오. |
| [setLocked(boolean value)](#setLocked-boolean-) | 이 속성에 대한 설명은 [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)을(를) 참조하십시오. |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | 이 속성에 대한 설명은 [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)을(를) 참조하십시오. |
| [setMousePointer(int value)](#setMousePointer-int-) | 이 속성에 대한 설명은 [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)을(를) 참조하십시오. |
| [setPicture(byte[] value)](#setPicture-byte---) | 이 속성에 대한 설명은 [getPicture()](../../com.aspose.diagram/imageactivexcontrol\#getPicture--)을(를) 참조하십시오. |
| [setPictureAlignment(int value)](#setPictureAlignment-int-) | 이 속성에 대한 설명은 [getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--)을(를) 참조하십시오. |
| [setPictureSizeMode(int value)](#setPictureSizeMode-int-) | 이 속성에 대한 설명은 [getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--)을(를) 참조하십시오. |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | 이 속성에 대한 설명은 [getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--)을(를) 참조하십시오. |
| [setTiled(boolean value)](#setTiled-boolean-) | 이 속성에 대한 설명은 [isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--)을(를) 참조하십시오. |
| [setTransparent(boolean value)](#setTransparent-boolean-) | 이 속성에 대한 설명은 [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)을(를) 참조하십시오. |
| [setWidth(double value)](#setWidth-double-) | 이 속성에 대한 설명은 [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)을(를) 참조하십시오. |
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
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


the ole color of the background.

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


the ole color of the background.

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


the type of border used by the control.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


the binary data of the control.

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


전경의 OLE 색상입니다. Image 컨트롤에는 적용되지 않습니다.

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


the height of the control in unit of points.

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


the default run-time mode of the Input Method Editor for the control as it receives focus.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


컨트롤에 대한 마우스 포인터로 표시할 사용자 지정 아이콘.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


컨트롤에 대한 마우스 포인터로 표시되는 아이콘 유형.

**Returns:**
int
### getPicture() {#getPicture--}
```
public byte[] getPicture()
```


그림의 데이터입니다.

**Returns:**
byte[]
### getPictureAlignment() {#getPictureAlignment--}
```
public int getPictureAlignment()
```


폼 또는 이미지 내부에서 그림의 정렬.

**Returns:**
int
### getPictureSizeMode() {#getPictureSizeMode--}
```
public int getPictureSizeMode()
```


그림을 표시하는 방법.

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


컨트롤의 특수 효과.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


ActiveX 컨트롤의 유형을 가져옵니다.

**Returns:**
int
### getWidth() {#getWidth--}
```
public double getWidth()
```


포인트 단위의 컨트롤 너비.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoSize() {#isAutoSize--}
```
public boolean isAutoSize()
```


컨트롤이 전체 내용을 표시하도록 자동으로 크기를 조정하는지 여부를 나타냅니다.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


컨트롤이 포커스를 받을 수 있고 사용자 생성 이벤트에 응답할 수 있는지 여부를 나타냅니다.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


컨트롤의 데이터가 편집을 위해 잠겨 있는지 여부를 나타냅니다.

**Returns:**
boolean
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


그림이 배경 전체에 타일 형식으로 표시되는지 여부를 나타냅니다.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


컨트롤이 투명한지 여부를 나타냅니다.

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




### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


이 속성에 대한 설명은 [isAutoSize()](../../com.aspose.diagram/imageactivexcontrol\#isAutoSize--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


이 속성에 대한 설명은 [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)을 참조하십시오

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


이 속성에 대한 설명은 [getBorderOleColor()](../../com.aspose.diagram/imageactivexcontrol\#getBorderOleColor--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


이 속성에 대한 설명은 [getBorderStyle()](../../com.aspose.diagram/imageactivexcontrol\#getBorderStyle--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


이 속성에 대한 설명은 [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


이 속성에 대한 설명은 [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


이 속성에 대한 설명은 [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


이 속성에 대한 설명은 [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


이 속성에 대한 설명은 [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


이 속성에 대한 설명은 [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


이 속성에 대한 설명은 [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPicture(byte[] value) {#setPicture-byte---}
```
public void setPicture(byte[] value)
```


이 속성에 대한 설명은 [getPicture()](../../com.aspose.diagram/imageactivexcontrol\#getPicture--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setPictureAlignment(int value) {#setPictureAlignment-int-}
```
public void setPictureAlignment(int value)
```


이 속성에 대한 설명은 [getPictureAlignment()](../../com.aspose.diagram/imageactivexcontrol\#getPictureAlignment--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setPictureSizeMode(int value) {#setPictureSizeMode-int-}
```
public void setPictureSizeMode(int value)
```


이 속성에 대한 설명은 [getPictureSizeMode()](../../com.aspose.diagram/imageactivexcontrol\#getPictureSizeMode--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


이 속성에 대한 설명은 [getSpecialEffect()](../../com.aspose.diagram/imageactivexcontrol\#getSpecialEffect--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTiled(boolean value) {#setTiled-boolean-}
```
public void setTiled(boolean value)
```


이 속성에 대한 설명은 [isTiled()](../../com.aspose.diagram/imageactivexcontrol\#isTiled--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


이 속성에 대한 설명은 [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


이 속성에 대한 설명은 [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

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

