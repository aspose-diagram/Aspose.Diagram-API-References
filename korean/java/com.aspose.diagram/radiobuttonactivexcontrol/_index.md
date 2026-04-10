---
title: RadioButtonActiveXControl
second_title: Aspose.Diagram for Java API 참조
description: RadioButton ActiveX 컨트롤을 나타냅니다.
type: docs
weight: 313
url: /ko/java/com.aspose.diagram/radiobuttonactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol), [com.aspose.diagram.ToggleButtonActiveXControl](../../com.aspose.diagram/togglebuttonactivexcontrol)
```
public class RadioButtonActiveXControl extends ToggleButtonActiveXControl
```

RadioButton ActiveX 컨트롤을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccelerator()](#getAccelerator--) | 컨트롤의 단축키입니다. |
| [getAlignment()](#getAlignment--) | 컨트롤에 대한 Caption의 위치입니다. |
| [getBackOleColor()](#getBackOleColor--) | the ole color of the background. |
| [getCaption()](#getCaption--) | 컨트롤에 표시되는 설명 텍스트입니다. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | the binary data of the control. |
| [getForeOleColor()](#getForeOleColor--) | the ole color of the foreground. |
| [getGroupName()](#getGroupName--) | 그룹의 이름입니다. |
| [getHeight()](#getHeight--) | the height of the control in unit of points. |
| [getIMEMode()](#getIMEMode--) | the default run-time mode of the Input Method Editor for the control as it receives focus. |
| [getMouseIcon()](#getMouseIcon--) | 컨트롤에 대한 마우스 포인터로 표시할 사용자 지정 아이콘. |
| [getMousePointer()](#getMousePointer--) | 컨트롤에 대한 마우스 포인터로 표시되는 아이콘 유형. |
| [getPicture()](#getPicture--) | 그림의 데이터입니다. |
| [getPicturePosition()](#getPicturePosition--) | 컨트롤 캡션에 상대적인 그림의 위치. |
| [getSpecialEffect()](#getSpecialEffect--) | 컨트롤의 특수 효과. |
| [getType()](#getType--) | ActiveX 컨트롤의 유형을 가져옵니다. |
| [getValue()](#getValue--) | 컨트롤이 선택되었는지 여부를 나타냅니다. |
| [getWidth()](#getWidth--) | 포인트 단위의 컨트롤 너비. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | 컨트롤이 전체 내용을 표시하도록 자동으로 크기를 조정하는지 여부를 나타냅니다. |
| [isEnabled()](#isEnabled--) | 컨트롤이 포커스를 받을 수 있고 사용자 생성 이벤트에 응답할 수 있는지 여부를 나타냅니다. |
| [isLocked()](#isLocked--) | 컨트롤의 데이터가 편집을 위해 잠겨 있는지 여부를 나타냅니다. |
| [isTransparent()](#isTransparent--) | 컨트롤이 투명한지 여부를 나타냅니다. |
| [isTripleState()](#isTripleState--) | 지정된 컨트롤이 Null 값을 표시하는 방식을 나타냅니다. |
| [isWordWrapped()](#isWordWrapped--) | 컨트롤 내용이 줄 끝에서 자동으로 줄 바꿈되는지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccelerator(char value)](#setAccelerator-char-) | 이 속성에 대한 설명은 [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--)를 참조하십시오. |
| [setAlignment(int value)](#setAlignment-int-) | 이 속성에 대한 설명은 [getAlignment()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getAlignment--)를 참조하십시오. |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | 이 속성에 대한 설명은 [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)을 참조하십시오 |
| [setBackOleColor(int value)](#setBackOleColor-int-) | 이 속성에 대한 설명은 [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)을 참조하십시오 |
| [setCaption(String value)](#setCaption-java.lang.String-) | 이 속성에 대한 설명은 [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--)를 참조하십시오. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 이 속성에 대한 설명은 [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)을(를) 참조하십시오. |
| [setForeOleColor(int value)](#setForeOleColor-int-) | 이 속성에 대한 설명은 [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)을(를) 참조하십시오. |
| [setGroupName(String value)](#setGroupName-java.lang.String-) | 이 속성에 대한 설명은 [getGroupName()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getGroupName--)를 참조하십시오. |
| [setHeight(double value)](#setHeight-double-) | 이 속성에 대한 설명은 [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)을(를) 참조하십시오. |
| [setIMEMode(int value)](#setIMEMode-int-) | 이 속성에 대한 설명은 [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)을(를) 참조하십시오. |
| [setLocked(boolean value)](#setLocked-boolean-) | 이 속성에 대한 설명은 [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)을(를) 참조하십시오. |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | 이 속성에 대한 설명은 [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)을(를) 참조하십시오. |
| [setMousePointer(int value)](#setMousePointer-int-) | 이 속성에 대한 설명은 [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)을(를) 참조하십시오. |
| [setPicture(byte[] value)](#setPicture-byte---) | 이 속성에 대한 설명은 [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--)를 참조하십시오. |
| [setPicturePosition(int value)](#setPicturePosition-int-) | 이 속성에 대한 설명은 [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--)를 참조하십시오. |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | 이 속성에 대한 설명은 [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--)를 참조하십시오. |
| [setTransparent(boolean value)](#setTransparent-boolean-) | 이 속성에 대한 설명은 [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)을(를) 참조하십시오. |
| [setTripleState(boolean value)](#setTripleState-boolean-) | 이 속성에 대한 설명은 [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--)를 참조하십시오. |
| [setValue(int value)](#setValue-int-) | 이 속성에 대한 설명은 [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--)를 참조하십시오. |
| [setWidth(double value)](#setWidth-double-) | 이 속성에 대한 설명은 [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)을(를) 참조하십시오. |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | 이 속성에 대한 설명은 [isWordWrapped()](../../com.aspose.diagram/radiobuttonactivexcontrol\#isWordWrapped--)를 참조하십시오. |
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
### getAccelerator() {#getAccelerator--}
```
public char getAccelerator()
```


컨트롤의 단축키입니다.

**Returns:**
char
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


컨트롤에 대한 Caption의 위치입니다.

**Returns:**
int
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


the ole color of the background.

**Returns:**
int
### getCaption() {#getCaption--}
```
public String getCaption()
```


컨트롤에 표시되는 설명 텍스트입니다.

**Returns:**
java.lang.String
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
### getGroupName() {#getGroupName--}
```
public String getGroupName()
```


그룹의 이름입니다.

**Returns:**
java.lang.String
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
### getPicturePosition() {#getPicturePosition--}
```
public int getPicturePosition()
```


컨트롤 캡션에 상대적인 그림의 위치.

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
### getValue() {#getValue--}
```
public int getValue()
```


컨트롤이 선택되었는지 여부를 나타냅니다.

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
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


컨트롤이 투명한지 여부를 나타냅니다.

**Returns:**
boolean
### isTripleState() {#isTripleState--}
```
public boolean isTripleState()
```


지정된 컨트롤이 Null 값을 표시하는 방식을 나타냅니다.

| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| 설정 | 설명 |
| True    | 컨트롤은 Yes, No 및 Null 값에 대한 상태를 순환합니다. Value 속성이 Null로 설정되면 컨트롤이 흐리게(회색) 표시됩니다. |
| False   | (기본값) 컨트롤은 Yes와 No 값에 대한 상태를 순환합니다. Null 값은 No 값처럼 표시됩니다. |

|

**Returns:**
boolean
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


컨트롤 내용이 줄 끝에서 자동으로 줄 바꿈되는지 여부를 나타냅니다.

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




### setAccelerator(char value) {#setAccelerator-char-}
```
public void setAccelerator(char value)
```


이 속성에 대한 설명은 [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | char |  |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


이 속성에 대한 설명은 [getAlignment()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getAlignment--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


이 속성에 대한 설명은 [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)을 참조하십시오

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

### setCaption(String value) {#setCaption-java.lang.String-}
```
public void setCaption(String value)
```


이 속성에 대한 설명은 [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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

### setGroupName(String value) {#setGroupName-java.lang.String-}
```
public void setGroupName(String value)
```


이 속성에 대한 설명은 [getGroupName()](../../com.aspose.diagram/radiobuttonactivexcontrol\#getGroupName--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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


이 속성에 대한 설명은 [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### setPicturePosition(int value) {#setPicturePosition-int-}
```
public void setPicturePosition(int value)
```


이 속성에 대한 설명은 [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


이 속성에 대한 설명은 [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


이 속성에 대한 설명은 [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setTripleState(boolean value) {#setTripleState-boolean-}
```
public void setTripleState(boolean value)
```


이 속성에 대한 설명은 [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


이 속성에 대한 설명은 [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


이 속성에 대한 설명은 [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)을(를) 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


이 속성에 대한 설명은 [isWordWrapped()](../../com.aspose.diagram/radiobuttonactivexcontrol\#isWordWrapped--)를 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

