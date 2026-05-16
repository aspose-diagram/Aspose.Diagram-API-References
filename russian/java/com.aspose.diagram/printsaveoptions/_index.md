---
title: PrintSaveOptions
second_title: Справочник API Aspose.Diagram for Java
description: Позволяет указать дополнительные параметры при печати диаграммы.
type: docs
weight: 308
url: /ru/java/com.aspose.diagram/printsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PrintSaveOptions extends RenderingSaveOptions
```

Позволяет указать дополнительные параметры при печати диаграммы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PrintSaveOptions()](#PrintSaveOptions--) | Инициализирует новый экземпляр этого класса |
## Методы

| Метод | Описание |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Создаёт объект параметров сохранения класса, подходящего для указанного формата сохранения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Если символы в диаграмме являются юникодом и не заданы с правильным значением шрифта или шрифт не установлен локально, они могут отображаться как блоки в PDF, изображении или XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Настройка рендеринга метафайла Emf. |
| [getEnlargePage()](#getEnlargePage--) | Указывает, следует ли увеличивать страницу. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Определяет, нужно ли экспортировать направляющие фигуры или нет. |
| [getPageCount()](#getPageCount--) | Количество страниц для рендеринга при сохранении в многостраничный файл. |
| [getPageSize()](#getPageSize--) | размер страницы для создаваемых изображений. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Указывает, будут ли печататься все страницы или только передний план. |
| [getSaveFormat()](#getSaveFormat--) | Указывает формат, в котором будет сохранён документ, если используется этот объект параметров сохранения. |
| [getShapes()](#getShapes--) | фигуры для рендеринга. |
| [getWarningCallback()](#getWarningCallback--) | обратный вызов предупреждения. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Определяет, нужно ли экспортировать комментарии или нет. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Для описания этого свойства, пожалуйста, смотрите [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Для описания этого свойства, пожалуйста, см. [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Для описания этого свойства, пожалуйста, см. [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Для описания этого свойства, пожалуйста, см. [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setPageCount(int value)](#setPageCount-int-) | Для описания этого свойства, пожалуйста, смотрите [getPageCount()](../../com.aspose.diagram/printsaveoptions\\#getPageCount--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Для описания этого свойства, пожалуйста, см. [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Для описания этого свойства, пожалуйста, смотрите [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Для описания этого свойства см. [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Для описания этого свойства, пожалуйста, см. [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintSaveOptions() {#PrintSaveOptions--}
```
public PrintSaveOptions()
```


Инициализирует новый экземпляр этого класса

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
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Настройка для рендеринга метафайла Emf. Метаприложения EMF, идентифицированные как "EMF+ Dual", могут содержать как записи EMF+, так и записи EMF. Любой тип записи может быть использован для рендеринга изображения, только записи EMF+, или только записи EMF. Когда установлен EmfPlusPrefer, будут разбирать записи EMF+, иначе будут разбирать только записи EMF. Значение по умолчанию — EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


Указывает, следует ли увеличивать страницу. Если true — увеличивать страницу. Если false — не увеличивать страницу. Значение по умолчанию — true.

**Returns:**
boolean
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


Определяет, требуется ли экспортировать направляющие фигуры. Значение по умолчанию — true.

**Returns:**
boolean
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Количество страниц для рендеринга при сохранении в многостраничный файл. По умолчанию используется MaxValue, что означает печать всех страниц диаграммы.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


размер страницы для создаваемых изображений. Может быть [PageSize](../../com.aspose.diagram/pagesize) или null. Значение по умолчанию — null. Если PageSize равен null, то размер страницы для создаваемого изображения берётся из исходной диаграммы.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Указывает, будут ли печататься все страницы или только передний план. Если true — печатаются только страницы переднего плана (с фоном, если он присутствует). Если false — печатаются страницы переднего плана (с фоном, если он присутствует), после чего следуют пустые страницы фона. Может возвращать true только когда PageCount > 1. Значение по умолчанию — false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Указывает формат, в котором будет сохранён документ, если используется этот объект параметров сохранения.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


фигуры для рендеринга. Количество по умолчанию — 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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
### isExportComments() {#isExportComments--}
```
public boolean isExportComments()
```


Определяет, нужно ли экспортировать комментарии. Значение по умолчанию — false.

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




### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


Для описания этого свойства, пожалуйста, см. [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


Для описания этого свойства, пожалуйста, см. [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


Для описания этого свойства, пожалуйста, см. [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Для описания этого свойства, пожалуйста, смотрите [getPageCount()](../../com.aspose.diagram/printsaveoptions\\#getPageCount--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Для описания этого свойства, пожалуйста, см. [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\\#getSaveForegroundPagesOnly--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Для описания этого свойства см. [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Для описания этого свойства, пожалуйста, см. [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

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

