---
title: ComboBoxActiveXControl
second_title: Справочник API Aspose.Diagram for Java
description: Представляет элемент управления ComboBox ActiveX.
type: docs
weight: 55
url: /ru/java/com.aspose.diagram/comboboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ComboBoxActiveXControl extends ActiveXControl
```

Представляет элемент управления ComboBox ActiveX.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | the ole color of the background. |
| [getBorderOleColor()](#getBorderOleColor--) | the ole color of the background. |
| [getBorderStyle()](#getBorderStyle--) | the type of border used by the control. |
| [getBoundColumn()](#getBoundColumn--) | Represents how the Value property is determined for a ComboBox or ListBox when the MultiSelect propertys value (fmMultiSelectSingle). |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | Represents the number of columns to display in a ComboBox or ListBox. |
| [getColumnWidths()](#getColumnWidths--) | the width of the column. |
| [getData()](#getData--) | the binary data of the control. |
| [getDropButtonStyle()](#getDropButtonStyle--) | Specifies the symbol displayed on the drop button |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | Specifies selection behavior when entering the control. |
| [getForeOleColor()](#getForeOleColor--) | the ole color of the foreground. |
| [getHeight()](#getHeight--) | the height of the control in unit of points. |
| [getHideSelection()](#getHideSelection--) | Indicates whether selected text in the control appears highlighted when the control does not have focus. |
| [getIMEMode()](#getIMEMode--) | the default run-time mode of the Input Method Editor for the control as it receives focus. |
| [getListRows()](#getListRows--) | Представляет максимальное количество строк, отображаемых в списке. |
| [getListStyle()](#getListStyle--) | визуальный вид. |
| [getListWidth()](#getListWidth--) | ширина в единицах пунктов. |
| [getMatchEntry()](#getMatchEntry--) | Указывает, как ListBox или ComboBox ищут в списке по мере ввода пользователем. |
| [getMaxLength()](#getMaxLength--) | максимальное количество символов |
| [getMouseIcon()](#getMouseIcon--) | пользовательский значок, отображаемый в качестве указателя мыши для элемента управления. |
| [getMousePointer()](#getMousePointer--) | тип значка, отображаемого в качестве указателя мыши для элемента управления. |
| [getSelectionMargin()](#getSelectionMargin--) | Указывает, может ли пользователь выделять строку текста, щелкнув в области слева от текста. |
| [getShowColumnHeads()](#getShowColumnHeads--) | Указывает, отображаются ли заголовки столбцов. |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | Specifies the symbol displayed on the drop button |
| [getSpecialEffect()](#getSpecialEffect--) | специальный эффект элемента управления. |
| [getTextColumn()](#getTextColumn--) | Представляет столбец в ComboBox или ListBox, отображаемый пользователю. |
| [getType()](#getType--) | Получает тип ActiveX‑элемента управления. |
| [getValue()](#getValue--) | значение элемента управления. |
| [getWidth()](#getWidth--) | ширина элемента управления в единицах пунктов. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Указывает, будет ли элемент управления автоматически изменять размер для отображения всего содержимого. |
| [isAutoWordSelected()](#isAutoWordSelected--) | Указывает базовую единицу, используемую для расширения выделения. |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | Указывает, включено ли перетаскивание для элемента управления. |
| [isEditable()](#isEditable--) | Указывает, может ли пользователь вводить текст в элемент управления. |
| [isEnabled()](#isEnabled--) | Указывает, может ли элемент управления получать фокус и реагировать на события, генерируемые пользователем. |
| [isLocked()](#isLocked--) | Указывает, заблокированы ли данные в элементе управления для редактирования. |
| [isTransparent()](#isTransparent--) | Указывает, является ли элемент управления прозрачным. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Для описания этого свойства, пожалуйста, см. [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | Для описания этого свойства, пожалуйста, см. [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Для описания этого свойства, пожалуйста, см. [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Для описания этого свойства, пожалуйста, см. [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Для описания этого свойства, пожалуйста, смотрите [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--) |
| [setBoundColumn(int value)](#setBoundColumn-int-) | Для описания этого свойства, пожалуйста, смотрите [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--) |
| [setColumnCount(int value)](#setColumnCount-int-) | Для описания этого свойства, пожалуйста, смотрите [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--) |
| [setColumnWidths(double value)](#setColumnWidths-double-) | Для описания этого свойства, пожалуйста, смотрите [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | Для описания этого свойства, пожалуйста, смотрите [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | Для описания этого свойства, пожалуйста, смотрите [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | Для описания этого свойства, пожалуйста, смотрите [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Для описания этого свойства, пожалуйста, смотрите [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | Для описания этого свойства, пожалуйста, смотрите [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Для описания этого свойства, пожалуйста, смотрите [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Для описания этого свойства, пожалуйста, смотрите [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | Для описания этого свойства, пожалуйста, смотрите [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Для описания этого свойства, пожалуйста, смотрите [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setListRows(int value)](#setListRows-int-) | Для описания этого свойства, пожалуйста, смотрите [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--) |
| [setListStyle(int value)](#setListStyle-int-) | Для описания этого свойства, пожалуйста, смотрите [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--) |
| [setListWidth(double value)](#setListWidth-double-) | Для описания этого свойства, пожалуйста, смотрите [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Для описания этого свойства, пожалуйста, смотрите [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMatchEntry(int value)](#setMatchEntry-int-) | Для описания этого свойства, пожалуйста, смотрите [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--) |
| [setMaxLength(int value)](#setMaxLength-int-) | Для описания этого свойства, пожалуйста, смотрите [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Для описания этого свойства, пожалуйста, смотрите [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Для описания этого свойства, пожалуйста, смотрите [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setSelectionMargin(boolean value)](#setSelectionMargin-boolean-) | Для описания этого свойства, пожалуйста, смотрите [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--) |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | Для описания этого свойства, пожалуйста, смотрите [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | Для описания этого свойства, пожалуйста, смотрите [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Для описания этого свойства, пожалуйста, смотрите [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--) |
| [setTextColumn(int value)](#setTextColumn-int-) | Для описания этого свойства см. [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Для описания этого свойства см. [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setValue(String value)](#setValue-java.lang.String-) | Для описания этого свойства см. [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--) |
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
### getBoundColumn() {#getBoundColumn--}
```
public int getBoundColumn()
```


Represents how the Value property is determined for a ComboBox or ListBox when the MultiSelect propertys value (fmMultiSelectSingle).

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnCount() {#getColumnCount--}
```
public int getColumnCount()
```


Represents the number of columns to display in a ComboBox or ListBox.

**Returns:**
int
### getColumnWidths() {#getColumnWidths--}
```
public double getColumnWidths()
```


the width of the column.

**Returns:**
double
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
### getListRows() {#getListRows--}
```
public int getListRows()
```


Представляет максимальное количество строк, отображаемых в списке.

**Returns:**
int
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


визуальный вид.

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


ширина в единицах пунктов.

**Returns:**
double
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


Указывает, как ListBox или ComboBox ищут в списке по мере ввода пользователем.

**Returns:**
int
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
### getSelectionMargin() {#getSelectionMargin--}
```
public boolean getSelectionMargin()
```


Указывает, может ли пользователь выделять строку текста, щелкнув в области слева от текста.

**Returns:**
boolean
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


Указывает, отображаются ли заголовки столбцов.

**Returns:**
boolean
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
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


Представляет столбец в ComboBox или ListBox, отображаемый пользователю.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Получает тип ActiveX‑элемента управления.

**Returns:**
int
### getValue() {#getValue--}
```
public String getValue()
```


значение элемента управления.

**Returns:**
java.lang.String
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

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


Для описания этого свойства, пожалуйста, см. [isAutoWordSelected()](../../com.aspose.diagram/comboboxactivexcontrol\#isAutoWordSelected--)

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


Для описания этого свойства, пожалуйста, см. [getBorderOleColor()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getBorderStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getBoundColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getBoundColumn--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getColumnCount()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnCount--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


Для описания этого свойства, пожалуйста, смотрите [getColumnWidths()](../../com.aspose.diagram/comboboxactivexcontrol\#getColumnWidths--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [isDragBehaviorEnabled()](../../com.aspose.diagram/comboboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getDropButtonStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [isEditable()](../../com.aspose.diagram/comboboxactivexcontrol\#isEditable--)

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


Для описания этого свойства, пожалуйста, смотрите [getEnterFieldBehavior()](../../com.aspose.diagram/comboboxactivexcontrol\#getEnterFieldBehavior--)

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


Для описания этого свойства, пожалуйста, смотрите [getHideSelection()](../../com.aspose.diagram/comboboxactivexcontrol\#getHideSelection--)

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

### setListRows(int value) {#setListRows-int-}
```
public void setListRows(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getListRows()](../../com.aspose.diagram/comboboxactivexcontrol\#getListRows--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getListStyle()](../../com.aspose.diagram/comboboxactivexcontrol\#getListStyle--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


Для описания этого свойства, пожалуйста, смотрите [getListWidth()](../../com.aspose.diagram/comboboxactivexcontrol\#getListWidth--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getMatchEntry()](../../com.aspose.diagram/comboboxactivexcontrol\#getMatchEntry--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getMaxLength()](../../com.aspose.diagram/comboboxactivexcontrol\#getMaxLength--)

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

### setSelectionMargin(boolean value) {#setSelectionMargin-boolean-}
```
public void setSelectionMargin(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [getSelectionMargin()](../../com.aspose.diagram/comboboxactivexcontrol\#getSelectionMargin--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [getShowColumnHeads()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowColumnHeads--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getShowDropButtonTypeWhen()](../../com.aspose.diagram/comboboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getSpecialEffect()](../../com.aspose.diagram/comboboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


Для описания этого свойства см. [getTextColumn()](../../com.aspose.diagram/comboboxactivexcontrol\#getTextColumn--)

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

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Для описания этого свойства см. [getValue()](../../com.aspose.diagram/comboboxactivexcontrol\#getValue--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

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

