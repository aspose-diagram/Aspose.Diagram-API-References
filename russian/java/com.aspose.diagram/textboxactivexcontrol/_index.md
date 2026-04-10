---
title: TextBoxActiveXControl
second_title: Справочник API Aspose.Diagram for Java
description: Представляет элемент управления ActiveX текстовым полем.
type: docs
weight: 401
url: /ru/java/com.aspose.diagram/textboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class TextBoxActiveXControl extends ActiveXControl
```

Представляет элемент управления ActiveX текстовым полем.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | the ole color of the background. |
| [getBorderOleColor()](#getBorderOleColor--) | the ole color of the background. |
| [getBorderStyle()](#getBorderStyle--) | the type of border used by the control. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | the binary data of the control. |
| [getDropButtonStyle()](#getDropButtonStyle--) | Specifies the symbol displayed on the drop button |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | Specifies selection behavior when entering the control. |
| [getEnterKeyBehavior()](#getEnterKeyBehavior--) | Указывает поведение клавиши ENTER. |
| [getForeOleColor()](#getForeOleColor--) | the ole color of the foreground. |
| [getHeight()](#getHeight--) | the height of the control in unit of points. |
| [getHideSelection()](#getHideSelection--) | Indicates whether selected text in the control appears highlighted when the control does not have focus. |
| [getIMEMode()](#getIMEMode--) | the default run-time mode of the Input Method Editor for the control as it receives focus. |
| [getIntegralHeight()](#getIntegralHeight--) | Указывает, будет ли элемент управления показывать только полные строки текста без отображения частичных строк. |
| [getMaxLength()](#getMaxLength--) | максимальное количество символов |
| [getMouseIcon()](#getMouseIcon--) | пользовательский значок, отображаемый в качестве указателя мыши для элемента управления. |
| [getMousePointer()](#getMousePointer--) | тип значка, отображаемого в качестве указателя мыши для элемента управления. |
| [getPasswordChar()](#getPasswordChar--) | символ, отображаемый вместо введённых символов. |
| [getScrollBars()](#getScrollBars--) | Указывает, имеет ли элемент управления вертикальные полосы прокрутки, горизонтальные полосы прокрутки, оба или ни один. |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | Specifies the symbol displayed on the drop button |
| [getSpecialEffect()](#getSpecialEffect--) | специальный эффект элемента управления. |
| [getTabKeyBehavior()](#getTabKeyBehavior--) | Указывает, разрешены ли символы табуляции в тексте элемента управления. |
| [getText()](#getText--) | текст элемента управления. |
| [getType()](#getType--) | Получает тип ActiveX‑элемента управления. |
| [getWidth()](#getWidth--) | ширина элемента управления в единицах пунктов. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Указывает, будет ли элемент управления автоматически изменять размер для отображения всего содержимого. |
| [isAutoTab()](#isAutoTab--) | Указывает, будет ли фокус автоматически перемещаться к следующему элементу управления, когда пользователь вводит максимальное количество символов. |
| [isAutoWordSelected()](#isAutoWordSelected--) | Указывает базовую единицу, используемую для расширения выделения. |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | Указывает, включено ли перетаскивание для элемента управления. |
| [isEditable()](#isEditable--) | Указывает, может ли пользователь вводить текст в элемент управления. |
| [isEnabled()](#isEnabled--) | Указывает, может ли элемент управления получать фокус и реагировать на события, генерируемые пользователем. |
| [isLocked()](#isLocked--) | Указывает, заблокированы ли данные в элементе управления для редактирования. |
| [isMultiLine()](#isMultiLine--) | Указывает, может ли элемент управления отображать более одной строки текста. |
| [isTransparent()](#isTransparent--) | Указывает, является ли элемент управления прозрачным. |
| [isWordWrapped()](#isWordWrapped--) | Указывает, будет ли содержимое элемента управления автоматически переноситься в конце строки. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Для описания этого свойства, пожалуйста, см. [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoTab(boolean value)](#setAutoTab-boolean-) | Для описания этого свойства см. [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | Для описания этого свойства см. [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Для описания этого свойства, пожалуйста, см. [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Для описания этого свойства см. [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Для описания этого свойства см. [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | Для описания этого свойства см. [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | Для описания этого свойства см. [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | Для описания этого свойства см. [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Для описания этого свойства, пожалуйста, смотрите [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | Для описания этого свойства см. [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--) |
| [setEnterKeyBehavior(boolean value)](#setEnterKeyBehavior-boolean-) | Для описания этого свойства см. [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Для описания этого свойства, пожалуйста, смотрите [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Для описания этого свойства, пожалуйста, смотрите [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | Для описания этого свойства см. [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Для описания этого свойства, пожалуйста, смотрите [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | Для описания этого свойства см. [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Для описания этого свойства, пожалуйста, смотрите [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMaxLength(int value)](#setMaxLength-int-) | Для описания этого свойства см. [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Для описания этого свойства, пожалуйста, смотрите [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Для описания этого свойства, пожалуйста, смотрите [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setMultiLine(boolean value)](#setMultiLine-boolean-) | Для описания этого свойства см. [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--) |
| [setPasswordChar(char value)](#setPasswordChar-char-) | Для описания этого свойства см. [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--) |
| [setScrollBars(int value)](#setScrollBars-int-) | Для описания этого свойства см. [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | Для описания этого свойства см. [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Для описания этого свойства см. [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--) |
| [setTabKeyBehavior(boolean value)](#setTabKeyBehavior-boolean-) | Для описания этого свойства см. [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--) |
| [setText(String value)](#setText-java.lang.String-) | Для описания этого свойства см. [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Для описания этого свойства см. [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | Для описания этого свойства см. [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Для описания этого свойства см. [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--) |
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
### getDropButtonStyle() {#getDropButtonStyle--}
```
public int getDropButtonStyle()
```


Specifies the symbol displayed on the drop button

**Returns:**
int
### getEnterFieldBehavior() {#getEnterFieldBehavior--}
```
public boolean getEnterFieldBehavior()
```


Указывает поведение выбора при входе в элемент управления. True указывает, что выбор остаётся неизменным с последнего раза, когда элемент был активен. False указывает, что весь текст в элементе будет выбран при входе в элемент.

**Returns:**
boolean
### getEnterKeyBehavior() {#getEnterKeyBehavior--}
```
public boolean getEnterKeyBehavior()
```


Определяет поведение клавиши ENTER. Значение true указывает, что нажатие ENTER создаст новую строку. Значение false указывает, что нажатие ENTER переместит фокус к следующему объекту в порядке табуляции.

**Returns:**
boolean
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
### getHideSelection() {#getHideSelection--}
```
public boolean getHideSelection()
```


Indicates whether selected text in the control appears highlighted when the control does not have focus.

**Returns:**
boolean
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


the default run-time mode of the Input Method Editor for the control as it receives focus.

**Returns:**
int
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


Указывает, будет ли элемент управления показывать только полные строки текста без отображения частичных строк.

**Returns:**
boolean
### getMaxLength() {#getMaxLength--}
```
public int getMaxLength()
```


максимальное количество символов

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
### getPasswordChar() {#getPasswordChar--}
```
public char getPasswordChar()
```


символ, отображаемый вместо введённых символов.

**Returns:**
char
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


Указывает, имеет ли элемент управления вертикальные полосы прокрутки, горизонтальные полосы прокрутки, оба или ни один.

**Returns:**
int
### getShowDropButtonTypeWhen() {#getShowDropButtonTypeWhen--}
```
public int getShowDropButtonTypeWhen()
```


Specifies the symbol displayed on the drop button

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


специальный эффект элемента управления.

**Returns:**
int
### getTabKeyBehavior() {#getTabKeyBehavior--}
```
public boolean getTabKeyBehavior()
```


Указывает, разрешены ли символы табуляции в тексте элемента управления.

**Returns:**
boolean
### getText() {#getText--}
```
public String getText()
```


текст элемента управления.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public int getType()
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
### isAutoTab() {#isAutoTab--}
```
public boolean isAutoTab()
```


Указывает, будет ли фокус автоматически перемещаться к следующему элементу управления, когда пользователь вводит максимальное количество символов.

**Returns:**
boolean
### isAutoWordSelected() {#isAutoWordSelected--}
```
public boolean isAutoWordSelected()
```


Указывает базовую единицу, используемую для расширения выбора. True указывает, что базовая единица — один символ. false указывает, что базовая единица — целое слово.

**Returns:**
boolean
### isDragBehaviorEnabled() {#isDragBehaviorEnabled--}
```
public boolean isDragBehaviorEnabled()
```


Указывает, включено ли перетаскивание для элемента управления.

**Returns:**
boolean
### isEditable() {#isEditable--}
```
public boolean isEditable()
```


Указывает, может ли пользователь вводить текст в элемент управления.

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
### isMultiLine() {#isMultiLine--}
```
public boolean isMultiLine()
```


Указывает, может ли элемент управления отображать более одной строки текста.

**Returns:**
boolean
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Указывает, является ли элемент управления прозрачным.

**Returns:**
boolean
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Указывает, будет ли содержимое элемента управления автоматически переноситься в конце строки.

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

### setAutoTab(boolean value) {#setAutoTab-boolean-}
```
public void setAutoTab(boolean value)
```


Для описания этого свойства см. [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


Для описания этого свойства см. [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--)

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

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


Для описания этого свойства см. [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Для описания этого свойства см. [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


Для описания этого свойства см. [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


Для описания этого свойства см. [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


Для описания этого свойства см. [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setEnterFieldBehavior(boolean value) {#setEnterFieldBehavior-boolean-}
```
public void setEnterFieldBehavior(boolean value)
```


Для описания этого свойства см. [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setEnterKeyBehavior(boolean value) {#setEnterKeyBehavior-boolean-}
```
public void setEnterKeyBehavior(boolean value)
```


Для описания этого свойства см. [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--)

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

### setHideSelection(boolean value) {#setHideSelection-boolean-}
```
public void setHideSelection(boolean value)
```


Для описания этого свойства см. [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


Для описания этого свойства см. [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


Для описания этого свойства см. [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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

### setMultiLine(boolean value) {#setMultiLine-boolean-}
```
public void setMultiLine(boolean value)
```


Для описания этого свойства см. [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setPasswordChar(char value) {#setPasswordChar-char-}
```
public void setPasswordChar(char value)
```


Для описания этого свойства см. [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | char |  |

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


Для описания этого свойства см. [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


Для описания этого свойства см. [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Для описания этого свойства см. [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTabKeyBehavior(boolean value) {#setTabKeyBehavior-boolean-}
```
public void setTabKeyBehavior(boolean value)
```


Для описания этого свойства см. [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Для описания этого свойства см. [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


Для описания этого свойства см. [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

