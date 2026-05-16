---
title: XAMLSaveOptions
second_title: Справочник API Aspose.Diagram for Java
description: Позволяет указывать дополнительные параметры при рендеринге страниц диаграммы в XAML.
type: docs
weight: 448
url: /ru/java/com.aspose.diagram/xamlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XAMLSaveOptions extends SaveOptions
```

Позволяет указывать дополнительные параметры при рендеринге страниц диаграммы в XAML.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XAMLSaveOptions()](#XAMLSaveOptions--) | Инициализирует новый экземпляр этого класса, который может использоваться для сохранения документа в формате Aspose.Diagram.SaveFileFormat. |
## Методы

| Метод | Описание |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Создаёт объект параметров сохранения класса, подходящего для указанного формата сохранения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Если символы в диаграмме являются юникодом и не заданы с правильным значением шрифта или шрифт не установлен локально, они могут отображаться как блоки в PDF, изображении или XPS. |
| [getPageCount()](#getPageCount--) | the number of pages to render in XAML. |
| [getPageIndex()](#getPageIndex--) | ноль‑базовый индекс первой страницы для рендеринга. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Указывает, будут ли все страницы сохранены в виде изображения или только передний план. |
| [getSaveFormat()](#getSaveFormat--) | Указывает формат, в котором будут сохраняться отрендеренные страницы диаграммы, если используется этот объект параметров сохранения. |
| [getStreamProvider()](#getStreamProvider--) | IStreamProvider для экспорта объектов. |
| [getWarningCallback()](#getWarningCallback--) | обратный вызов предупреждения. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setPageCount(int value)](#setPageCount-int-) | Для описания этого свойства, пожалуйста, смотрите [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Для описания этого свойства, пожалуйста, смотрите [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Для описания этого свойства, пожалуйста, смотрите [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Для описания этого свойства, пожалуйста, смотрите [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | Для описания этого свойства, пожалуйста, смотрите [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XAMLSaveOptions() {#XAMLSaveOptions--}
```
public XAMLSaveOptions()
```


Инициализирует новый экземпляр этого класса, который может использоваться для сохранения документа в формате Aspose.Diagram.SaveFileFormat.

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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Количество страниц для рендеринга в XAML. По умолчанию — MaxValue, что означает, что будут отрисованы все страницы диаграммы.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Нулевой индекс первой страницы для рендеринга. По умолчанию — 0.

**Returns:**
int
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Указывает, будут ли сохраняться все страницы в изображении или только передний план. Если true — рендерятся только страницы переднего плана (с фоном, если он присутствует). Если false — рендерятся страницы переднего плана (с фоном, если он присутствует), после чего добавляются пустые страницы фона. Может возвращать true только когда PageCount > 1. Значение по умолчанию — false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Указывает формат, в котором будут сохраняться отрендеренные страницы диаграммы, если используется этот объект параметров сохранения. Может быть только Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


IStreamProvider для экспорта объектов.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
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




### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


Для описания этого свойства, пожалуйста, смотрите [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

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

