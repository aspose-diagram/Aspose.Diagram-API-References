---
title: ActiveXControl
second_title: Справочник API Aspose.Diagram for Java
description: Представляет элемент управления ActiveX.
type: docs
weight: 13
url: /ru/java/com.aspose.diagram/activexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase)
```
public abstract class ActiveXControl extends ActiveXControlBase
```

Представляет элемент управления ActiveX.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | the ole color of the background. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | the binary data of the control. |
| [getForeOleColor()](#getForeOleColor--) | the ole color of the foreground. |
| [getHeight()](#getHeight--) | the height of the control in unit of points. |
| [getIMEMode()](#getIMEMode--) | the default run-time mode of the Input Method Editor for the control as it receives focus. |
| [getMouseIcon()](#getMouseIcon--) | пользовательский значок, отображаемый в качестве указателя мыши для элемента управления. |
| [getMousePointer()](#getMousePointer--) | тип значка, отображаемого в качестве указателя мыши для элемента управления. |
| [getType()](#getType--) | Получает тип ActiveX‑элемента управления. |
| [getWidth()](#getWidth--) | ширина элемента управления в единицах пунктов. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Указывает, будет ли элемент управления автоматически изменять размер для отображения всего содержимого. |
| [isEnabled()](#isEnabled--) | Указывает, может ли элемент управления получать фокус и реагировать на события, генерируемые пользователем. |
| [isLocked()](#isLocked--) | Указывает, заблокированы ли данные в элементе управления для редактирования. |
| [isTransparent()](#isTransparent--) | Указывает, является ли элемент управления прозрачным. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Для описания этого свойства, пожалуйста, см. [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Для описания этого свойства, пожалуйста, см. [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Для описания этого свойства, пожалуйста, смотрите [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Для описания этого свойства, пожалуйста, смотрите [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Для описания этого свойства, пожалуйста, смотрите [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Для описания этого свойства, пожалуйста, смотрите [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Для описания этого свойства, пожалуйста, смотрите [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Для описания этого свойства, пожалуйста, смотрите [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Для описания этого свойства, пожалуйста, смотрите [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Для описания этого свойства см. [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | Для описания этого свойства см. [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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


OLE‑цвет переднего плана. Не применяется к элементу Image.

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


пользовательский значок, отображаемый в качестве указателя мыши для элемента управления.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


тип значка, отображаемого в качестве указателя мыши для элемента управления.

**Returns:**
int
### getType() {#getType--}
```
public abstract int getType()
```


Получает тип ActiveX‑элемента управления.

**Returns:**
int
### getWidth() {#getWidth--}
```
public double getWidth()
```


ширина элемента управления в единицах пунктов.

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


Указывает, будет ли элемент управления автоматически изменять размер для отображения всего содержимого.

**Returns:**
boolean
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


Указывает, может ли элемент управления получать фокус и реагировать на события, генерируемые пользователем.

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


Указывает, заблокированы ли данные в элементе управления для редактирования.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Указывает, является ли элемент управления прозрачным.

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


Для описания этого свойства, пожалуйста, см. [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


Для описания этого свойства, пожалуйста, см. [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Для описания этого свойства, пожалуйста, смотрите [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


Для описания этого свойства, пожалуйста, смотрите [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Для описания этого свойства см. [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Для описания этого свойства см. [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

