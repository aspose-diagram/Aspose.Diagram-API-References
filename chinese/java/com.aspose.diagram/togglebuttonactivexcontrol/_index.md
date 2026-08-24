---
title: ToggleButtonActiveXControl
second_title: Aspose.Diagram for Java API 参考
description: 表示 ToggleButton ActiveX 控件。
type: docs
weight: 410
url: /zh/java/com.aspose.diagram/togglebuttonactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ToggleButtonActiveXControl extends ActiveXControl
```

表示 ToggleButton ActiveX 控件。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAccelerator()](#getAccelerator--) | 控件的加速键。 |
| [getBackOleColor()](#getBackOleColor--) | 背景的 OLE 颜色。 |
| [getCaption()](#getCaption--) | 显示在控件上的描述性文本。 |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | 控件的二进制数据。 |
| [getForeOleColor()](#getForeOleColor--) | 前景的 OLE 颜色。 |
| [getHeight()](#getHeight--) | 控件的高度（单位为点）。 |
| [getIMEMode()](#getIMEMode--) | 控件获得焦点时，输入法编辑器的默认运行时模式。 |
| [getMouseIcon()](#getMouseIcon--) | 用于在控件上显示为鼠标指针的自定义图标。 |
| [getMousePointer()](#getMousePointer--) | 在控件上显示为鼠标指针的图标类型。 |
| [getPicture()](#getPicture--) | 图片的数据。 |
| [getPicturePosition()](#getPicturePosition--) | 控件图片相对于其标题的位置。 |
| [getSpecialEffect()](#getSpecialEffect--) | 控件的特殊效果。 |
| [getType()](#getType--) | 获取 ActiveX 控件的类型。 |
| [getValue()](#getValue--) | 指示控件是否被选中。 |
| [getWidth()](#getWidth--) | 控件的宽度，以点为单位。 |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | 指示控件是否会自动调整大小以显示其全部内容。 |
| [isEnabled()](#isEnabled--) | 指示控件是否可以获取焦点并响应用户生成的事件。 |
| [isLocked()](#isLocked--) | 指示控件中的数据是否被锁定以进行编辑。 |
| [isTransparent()](#isTransparent--) | 指示控件是否透明。 |
| [isTripleState()](#isTripleState--) | 指示指定的控件将如何显示 Null 值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccelerator(char value)](#setAccelerator-char-) | 有关此属性的描述，请参阅 [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--) |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | 有关此属性的描述，请参阅 [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | 有关此属性的描述，请参阅 [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setCaption(String value)](#setCaption-java.lang.String-) | 有关此属性的描述，请参阅 [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 有关此属性的描述，请参阅 [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | 有关此属性的描述，请参阅 [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | 有关此属性的描述，请参阅 [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | 有关此属性的描述，请参阅 [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | 有关此属性的描述，请参阅 [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | 有关此属性的描述，请参阅 [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | 有关此属性的描述，请参阅 [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setPicture(byte[] value)](#setPicture-byte---) | 有关此属性的描述，请参阅 [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--) |
| [setPicturePosition(int value)](#setPicturePosition-int-) | 有关此属性的描述，请参阅 [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | 有关此属性的描述，请参阅 [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | 有关此属性的描述，请参阅 [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setTripleState(boolean value)](#setTripleState-boolean-) | 有关此属性的描述，请参阅 [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--) |
| [setValue(int value)](#setValue-int-) | 有关此属性的描述，请参阅 [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--) |
| [setWidth(double value)](#setWidth-double-) | 有关此属性的描述，请参阅 [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getAccelerator() {#getAccelerator--}
```
public char getAccelerator()
```


控件的加速键。

**Returns:**
字符
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


背景的 OLE 颜色。

**Returns:**
int
### getCaption() {#getCaption--}
```
public String getCaption()
```


显示在控件上的描述性文本。

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


控件的二进制数据。

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


前景的 OLE 颜色。不适用于 Image 控件。

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


控件的高度（单位为点）。

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


控件获得焦点时，输入法编辑器的默认运行时模式。

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


用于在控件上显示为鼠标指针的自定义图标。

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


在控件上显示为鼠标指针的图标类型。

**Returns:**
int
### getPicture() {#getPicture--}
```
public byte[] getPicture()
```


图片的数据。

**Returns:**
byte[]
### getPicturePosition() {#getPicturePosition--}
```
public int getPicturePosition()
```


控件图片相对于其标题的位置。

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


控件的特殊效果。

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


获取 ActiveX 控件的类型。

**Returns:**
int
### getValue() {#getValue--}
```
public int getValue()
```


指示控件是否被选中。

**Returns:**
int
### getWidth() {#getWidth--}
```
public double getWidth()
```


控件的宽度，以点为单位。

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


指示控件是否会自动调整大小以显示其全部内容。

**Returns:**
布尔
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


指示控件是否可以获取焦点并响应用户生成的事件。

**Returns:**
布尔
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


指示控件中的数据是否被锁定以进行编辑。

**Returns:**
布尔
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


指示控件是否透明。

**Returns:**
布尔
### isTripleState() {#isTripleState--}
```
public boolean isTripleState()
```


指示指定的控件将如何显示 Null 值。

| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Setting | Description                                                                                                                                     |
| True    | 控件将在 Yes、No 和 Null 值之间循环。 当其 Value 属性设置为 Null 时，控件显示为暗淡（灰色）。 |
| False   | (默认) 控件将在 Yes 和 No 值之间循环。 Null 值显示为 No 值的效果。 |

|

**Returns:**
布尔
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


有关此属性的描述，请参阅 [getAccelerator()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getAccelerator--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 字符 |  |

### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


有关此属性的描述，请参阅 [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


有关此属性的描述，请参阅 [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setCaption(String value) {#setCaption-java.lang.String-}
```
public void setCaption(String value)
```


有关此属性的描述，请参阅 [getCaption()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getCaption--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


有关此属性的描述，请参阅 [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


有关此属性的描述，请参阅 [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


有关此属性的描述，请参阅 [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


有关此属性的描述，请参阅 [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


有关此属性的描述，请参阅 [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


有关此属性的描述，请参阅 [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


有关此属性的描述，请参阅 [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPicture(byte[] value) {#setPicture-byte---}
```
public void setPicture(byte[] value)
```


有关此属性的描述，请参阅 [getPicture()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicture--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setPicturePosition(int value) {#setPicturePosition-int-}
```
public void setPicturePosition(int value)
```


有关此属性的描述，请参阅 [getPicturePosition()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getPicturePosition--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


有关此属性的描述，请参阅 [getSpecialEffect()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getSpecialEffect--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


有关此属性的描述，请参阅 [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setTripleState(boolean value) {#setTripleState-boolean-}
```
public void setTripleState(boolean value)
```


有关此属性的描述，请参阅 [isTripleState()](../../com.aspose.diagram/togglebuttonactivexcontrol\#isTripleState--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


有关此属性的描述，请参阅 [getValue()](../../com.aspose.diagram/togglebuttonactivexcontrol\#getValue--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


有关此属性的描述，请参阅 [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

