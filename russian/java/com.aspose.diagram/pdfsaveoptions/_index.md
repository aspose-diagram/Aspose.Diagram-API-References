---
title: PdfSaveOptions
second_title: Справочник API Aspose.Diagram for Java
description: Позволяет указать дополнительные параметры при рендеринге страниц диаграммы в PDF.
type: docs
weight: 281
url: /ru/java/com.aspose.diagram/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PdfSaveOptions extends RenderingSaveOptions
```

Позволяет указать дополнительные параметры при рендеринге страниц диаграммы в PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Инициализирует новый экземпляр этого класса, который может использоваться для сохранения документа в формате Aspose.Diagram.SaveFileFormat. |
## Методы

| Метод | Описание |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Создаёт объект параметров сохранения класса, подходящего для указанного формата сохранения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompliance()](#getCompliance--) | Желаемый уровень соответствия для генерируемого PDF‑документа. |
| [getDefaultFont()](#getDefaultFont--) | Если символы в диаграмме являются юникодом и не заданы с правильным значением шрифта или шрифт не установлен локально, они могут отображаться как блоки в PDF, изображении или XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Настройка рендеринга метафайла Emf. |
| [getEncryptionDetails()](#getEncryptionDetails--) | детали шифрования. |
| [getEnlargePage()](#getEnlargePage--) | Указывает, следует ли увеличивать страницу. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Определяет, нужно ли экспортировать направляющие фигуры или нет. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Определяет, нужно ли экспортировать скрытую страницу или нет. |
| [getHorizontalResolution()](#getHorizontalResolution--) | горизонтальное разрешение генерируемых изображений, в точках на дюйм. |
| [getJpegQuality()](#getJpegQuality--) | Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие). |
| [getPageCount()](#getPageCount--) | количество страниц для рендеринга в PDF. |
| [getPageIndex()](#getPageIndex--) | ноль‑базовый индекс первой страницы для рендеринга. |
| [getPageSavingCallback()](#getPageSavingCallback--) | Управление/индикация прогресса процесса сохранения страницы. |
| [getPageSize()](#getPageSize--) | размер страницы для создаваемых изображений. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Указывает, будут ли все страницы сохранены в виде изображения или только передний план. |
| [getSaveFormat()](#getSaveFormat--) | Указывает формат, в котором будут сохраняться отрендеренные страницы диаграммы, если используется этот объект параметров сохранения. |
| [getShapes()](#getShapes--) | фигуры для рендеринга. |
| [getSplitMultiPages()](#getSplitMultiPages--) | Определяет, следует ли разбивать диаграмму на несколько страниц в соответствии с настройками страницы. |
| [getTextCompression()](#getTextCompression--) | Указывает тип сжатия, используемый для всех потоков содержимого, кроме изображений. |
| [getVerticalResolution()](#getVerticalResolution--) | вертикальное разрешение генерируемых изображений, в точках на дюйм. |
| [getWarningCallback()](#getWarningCallback--) | обратный вызов предупреждения. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Определяет, нужно ли экспортировать комментарии или нет. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompliance(int value)](#setCompliance-int-) | Для описания этого свойства см. [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Для описания этого свойства, пожалуйста, смотрите [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEncryptionDetails(PdfEncryptionDetails value)](#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-) | Для описания этого свойства см. [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Для описания этого свойства, пожалуйста, см. [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Для описания этого свойства, пожалуйста, см. [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Для описания этого свойства, пожалуйста, см. [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Для описания этого свойства см. [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--) |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Для описания этого свойства см. [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Для описания этого свойства см. [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Для описания этого свойства см. [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Для описания этого свойства см. [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--) |
| [setPageSavingCallback(IPageSavingCallback value)](#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-) | Для описания этого свойства см. [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Для описания этого свойства, пожалуйста, см. [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Для описания этого свойства см. [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Для описания этого свойства см. [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Для описания этого свойства, пожалуйста, см. [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSplitMultiPages(boolean value)](#setSplitMultiPages-boolean-) | Для описания этого свойства см. [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--) |
| [setTextCompression(int value)](#setTextCompression-int-) | Для описания этого свойства см. [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--) |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | Для описания этого свойства см. [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
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
### getCompliance() {#getCompliance--}
```
public int getCompliance()
```


Желаемый уровень соответствия генерируемого PDF‑документа. По умолчанию PdfCompliance.PDF\_15.

**Returns:**
int
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
### getEncryptionDetails() {#getEncryptionDetails--}
```
public PdfEncryptionDetails getEncryptionDetails()
```


детали шифрования. Если не заданы, шифрование не будет выполнено.

**Returns:**
[PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails)
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
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Определяет, требуется ли экспортировать скрытую страницу. Значение по умолчанию — true.

**Returns:**
boolean
### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


горизонтальное разрешение генерируемых изображений, в точках на дюйм. Применяется к методу генерации изображений, за исключением изображений формата EMF. Значение по умолчанию — 96.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие). По умолчанию — 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


количество страниц для рендеринга в PDF. По умолчанию MaxValue, что означает рендеринг всех страниц диаграммы.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Нулевой индекс первой страницы для рендеринга. По умолчанию — 0.

**Returns:**
int
### getPageSavingCallback() {#getPageSavingCallback--}
```
public IPageSavingCallback getPageSavingCallback()
```


Управление/индикация прогресса процесса сохранения страницы.

**Returns:**
[IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback)
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
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


фигуры для рендеринга. Количество по умолчанию — 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSplitMultiPages() {#getSplitMultiPages--}
```
public boolean getSplitMultiPages()
```


Определяет, следует ли разбивать диаграмму на несколько страниц в соответствии с настройками страницы. Значение по умолчанию — false.

**Returns:**
boolean
### getTextCompression() {#getTextCompression--}
```
public int getTextCompression()
```


Указывает тип сжатия, используемый для всех потоков содержимого, кроме изображений. По умолчанию — PdfTextCompression.FLATE.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Вертикальное разрешение генерируемых изображений, в точках на дюйм. Применяется к методу генерации изображения, кроме изображений формата Emf. Значение по умолчанию — 96.

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




### setCompliance(int value) {#setCompliance-int-}
```
public void setCompliance(int value)
```


Для описания этого свойства см. [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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

### setEncryptionDetails(PdfEncryptionDetails value) {#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-}
```
public void setEncryptionDetails(PdfEncryptionDetails value)
```


Для описания этого свойства см. [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails) |  |

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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Для описания этого свойства см. [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int value)
```


Для описания этого свойства см. [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Для описания этого свойства см. [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Для описания этого свойства см. [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Для описания этого свойства см. [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPageSavingCallback(IPageSavingCallback value) {#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-}
```
public void setPageSavingCallback(IPageSavingCallback value)
```


Для описания этого свойства см. [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback) |  |

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


Для описания этого свойства см. [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Для описания этого свойства см. [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--)

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

### setSplitMultiPages(boolean value) {#setSplitMultiPages-boolean-}
```
public void setSplitMultiPages(boolean value)
```


Для описания этого свойства см. [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setTextCompression(int value) {#setTextCompression-int-}
```
public void setTextCompression(int value)
```


Для описания этого свойства см. [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int value)
```


Для описания этого свойства см. [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--)

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

