---
title: DiagramSaveOptions
second_title: Справочник API Aspose.Diagram for Java
description: Можно использовать для указания дополнительных параметров при сохранении диаграммы в формат Visio VDXVSX.
type: docs
weight: 119
url: /ru/java/com.aspose.diagram/diagramsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class DiagramSaveOptions extends SaveOptions
```

Можно использовать для указания дополнительных параметров при сохранении диаграммы в формат Visio (VDX\VSX). В данный момент предоставляется только свойство SaveFormat, но в будущем будут добавлены другие параметры.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DiagramSaveOptions()](#DiagramSaveOptions--) | Инициализирует новый экземпляр этого класса, который можно использовать для сохранения диаграммы в формате VDX. |
| [DiagramSaveOptions(int saveFormat)](#DiagramSaveOptions-int-) | Инициализирует новый экземпляр этого класса, который можно использовать для сохранения диаграммы в формате VDX или VSX. |
## Методы

| Метод | Описание |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Создаёт объект параметров сохранения класса, подходящего для указанного формата сохранения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoFitPageToDrawingContent()](#getAutoFitPageToDrawingContent--) | Определяет, нужно ли увеличивать страницу, чтобы вместить содержимое рисунка, или нет. |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Если символы в диаграмме являются юникодом и не заданы с правильным значением шрифта или шрифт не установлен локально, они могут отображаться как блоки в PDF, изображении или XPS. |
| [getSaveFormat()](#getSaveFormat--) | Указывает формат, в котором будет сохранена отрисованная диаграмма, если используется этот объект параметров сохранения. |
| [getWarningCallback()](#getWarningCallback--) | обратный вызов предупреждения. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoFitPageToDrawingContent(boolean value)](#setAutoFitPageToDrawingContent-boolean-) | Для описания этого свойства см. [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Для описания этого свойства см. [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DiagramSaveOptions() {#DiagramSaveOptions--}
```
public DiagramSaveOptions()
```


Инициализирует новый экземпляр этого класса, который можно использовать для сохранения диаграммы в формате VDX.

### DiagramSaveOptions(int saveFormat) {#DiagramSaveOptions-int-}
```
public DiagramSaveOptions(int saveFormat)
```


Инициализирует новый экземпляр этого класса, который можно использовать для сохранения диаграммы в формате VDX или VSX.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| saveFormat | int |  |

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Создаёт объект параметров сохранения класса, подходящего для указанного формата сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| saveFormat | int | Aspose.Diagram.SaveFileFormat, для которого необходимо создать объект параметров сохранения. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
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
### getAutoFitPageToDrawingContent() {#getAutoFitPageToDrawingContent--}
```
public boolean getAutoFitPageToDrawingContent()
```


Определяет, нужно ли увеличивать страницу, чтобы вместить содержимое рисунка, или нет. Значение по умолчанию — false.

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


Если символы в диаграмме являются Unicode и не заданы с правильным значением шрифта или шрифт не установлен локально, они могут отображаться в виде блоков в PDF, изображении или XPS. Установите DefaultFont, например MingLiu или MS Gothic, чтобы отобразить эти символы.

**Returns:**
java.lang.String
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Указывает формат, в котором будет сохранена отрисованная диаграмма, если используется этот объект параметров сохранения. Может быть Aspose.Diagram.SaveFileFormat или Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


обратный вызов предупреждения.

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


Для описания этого свойства см. [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Для описания этого свойства см. [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Параметр | Тип | Описание |
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

