---
title: ImageSaveOptions
second_title: Справочник API Aspose.Diagram for Java
description: Позволяет указать дополнительные параметры при рендеринге страниц диаграммы в изображения.
type: docs
weight: 200
url: /ru/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

Позволяет указать дополнительные параметры при рендеринге страниц диаграммы в изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | Инициализирует новый экземпляр этого класса, который может использоваться для сохранения отрисованных изображений в формате Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspise.Diagram.SaveFileFormat или Aspose.Diagram.SaveFileFormat. |
## Методы

| Метод | Описание |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Создаёт объект параметров сохранения класса, подходящего для указанного формата сохранения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | Указывает уровень качества, используемый при композитинге. |
| [getContentZoom()](#getContentZoom--) | Этот параметр похож на масштаб, но не влияет на размер генерируемого изображения. |
| [getDefaultFont()](#getDefaultFont--) | Если символы в диаграмме являются юникодом и не заданы с правильным значением шрифта или шрифт не установлен локально, они могут отображаться как блоки в PDF, изображении или XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Настройка рендеринга метафайла Emf. |
| [getEnlargePage()](#getEnlargePage--) | Указывает, следует ли увеличивать страницу. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Определяет, нужно ли экспортировать направляющие фигуры или нет. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Определяет, нужно ли экспортировать скрытую страницу или нет. |
| [getImageBrightness()](#getImageBrightness--) | яркость генерируемых изображений. |
| [getImageColorMode()](#getImageColorMode--) | цветовой режим генерируемых изображений. |
| [getImageContrast()](#getImageContrast--) | контраст генерируемых изображений. |
| [getInterpolationMode()](#getInterpolationMode--) | Указывает алгоритм, используемый при масштабировании или вращении изображений. |
| [getJpegQuality()](#getJpegQuality--) | значение, определяющее качество генерируемых JPEG‑изображений. |
| [getPageCount()](#getPageCount--) | число страниц для рендеринга при сохранении в многостраничный файл TIFF. |
| [getPageIndex()](#getPageIndex--) | ноль‑базовый индекс первой страницы для рендеринга. |
| [getPageSize()](#getPageSize--) | размер страницы для создаваемых изображений. |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | значение, указывающее, как пиксели смещаются во время рендеринга. |
| [getResolution()](#getResolution--) | разрешение сгенерированных изображений в точках на дюйм. |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | Указывает, является ли область сохранения такой же, как у PDF. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Указывает, будут ли все страницы сохранены в виде изображения или только передний план. |
| [getSaveFormat()](#getSaveFormat--) | Указывает формат, в котором будут сохраняться отрендеренные страницы диаграммы, если используется этот объект параметров сохранения. |
| [getScale()](#getScale--) | коэффициент масштабирования сгенерированных изображений. |
| [getShapes()](#getShapes--) | фигуры для рендеринга. |
| [getSmoothingMode()](#getSmoothingMode--) | Указывает, применяется ли сглаживание (антиалиасинг) к линиям и кривым и к краям заполненных областей. |
| [getTiffCompression()](#getTiffCompression--) | тип сжатия, применяемый при сохранении сгенерированных изображений в формате TIFF. |
| [getWarningCallback()](#getWarningCallback--) | обратный вызов предупреждения. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Определяет, нужно ли экспортировать комментарии или нет. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Для описания этого свойства см. [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) |
| [setContentZoom(float value)](#setContentZoom-float-) | Для описания этого свойства см. [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Для описания этого свойства, пожалуйста, смотрите [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Для описания этого свойства, пожалуйста, см. [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Для описания этого свойства, пожалуйста, см. [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Для описания этого свойства, пожалуйста, см. [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Для описания этого свойства см. [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) |
| [setImageBrightness(float value)](#setImageBrightness-float-) | Для описания этого свойства см. [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) |
| [setImageColorMode(int value)](#setImageColorMode-int-) | Для описания этого свойства см. [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) |
| [setImageContrast(float value)](#setImageContrast-float-) | Для описания этого свойства см. [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Для описания этого свойства см. [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Для описания этого свойства см. [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Для описания этого свойства см. [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Для описания этого свойства см. [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Для описания этого свойства, пожалуйста, см. [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | Для описания этого свойства см. [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) |
| [setResolution(float value)](#setResolution-float-) | Для описания этого свойства см. [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | Для описания этого свойства см. [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Для описания этого свойства см. [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Для описания этого свойства см. [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) |
| [setScale(float value)](#setScale-float-) | Для описания этого свойства см. [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Для описания этого свойства, пожалуйста, см. [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Для описания этого свойства см. [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) |
| [setTiffCompression(int value)](#setTiffCompression-int-) | Для описания этого свойства см. [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


Инициализирует новый экземпляр этого класса, который может использоваться для сохранения отрисованных изображений в формате Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspise.Diagram.SaveFileFormat или Aspose.Diagram.SaveFileFormat.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| saveFormat | int | Может быть Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat или Aspose.Diagram.SaveFileFormat. |

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
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Указывает уровень качества, используемый при композитинге. Это свойство действует только при сохранении в растровые форматы изображений. Значение по умолчанию — Aspose.Diagram.Saving.CompositingQuality.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


Этот параметр похож на масштаб, но не влияет на размер генерируемого изображения. Значение по умолчанию — 1.0. Значение должно быть больше 0.

**Returns:**
float
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
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Определяет, требуется ли экспортировать скрытую страницу. Значение по умолчанию — true.

**Returns:**
boolean
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


яркость генерируемых изображений. Это свойство действует только при сохранении в растровые форматы изображений. Значение по умолчанию — 0.5. Значение должно находиться в диапазоне от 0 до 1.

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


режим цвета генерируемых изображений. Это свойство действует только при сохранении в растровые форматы изображений. Значение по умолчанию — Aspose.Diagram.Saving.ImageColorMode.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


контраст генерируемых изображений. Это свойство действует только при сохранении в растровые форматы изображений. Значение по умолчанию — 0.5. Значение должно находиться в диапазоне от 0 до 1.

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Указывает алгоритм, используемый при масштабировании или вращении изображений. Это свойство действует только при сохранении в растровые форматы изображений. Значение по умолчанию — Aspose.Diagram.Saving.InterpolationMode.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


значение, определяющее качество генерируемых JPEG‑изображений. Действует только при сохранении в JPEG. Используйте это свойство для получения или установки качества генерируемых изображений при сохранении в формате JPEG. Значение может варьироваться от 0 до 100, где 0 означает наихудшее качество при максимальном сжатии, а 100 — лучшее качество при минимальном сжатии. Значение по умолчанию — 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


количество страниц для рендеринга при сохранении в многостраничный TIFF‑файл. По умолчанию — MaxValue, что означает рендеринг всех страниц диаграммы.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Нулевой индекс первой страницы для рендеринга. По умолчанию — 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


размер страницы для создаваемых изображений. Может быть [PageSize](../../com.aspose.diagram/pagesize) или null. Значение по умолчанию — null. Если PageSize равен null, то размер страницы для создаваемого изображения берётся из исходной диаграммы.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


значение, указывающее, как пиксели смещаются во время рендеринга. Это свойство действует только при сохранении в растровые форматы изображений. Значение по умолчанию — Aspose.Diagram.Saving.PixelOffsetMode.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


разрешение генерируемых изображений в точках на дюйм. Это свойство действует только при сохранении в растровые форматы изображений. Значение по умолчанию — 96.

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


Указывает, совпадает ли область сохранения с областью PDF. Если true — отрисованная область совпадает с PDF. Если false — используется область по умолчанию. Значение по умолчанию — false.

**Returns:**
boolean
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


Указывает формат, в котором будут сохранены отрисованные страницы диаграммы, если используется этот объект параметров сохранения. Может быть Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat или Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


коэффициент масштабирования генерируемых изображений. Значение по умолчанию — 1.0. Значение должно быть больше 0.

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


фигуры для рендеринга. Количество по умолчанию — 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Указывает, применяется ли сглаживание (антиалиасинг) к линиям, кривым и краям заполненных областей. Это свойство действует только при сохранении в растровые форматы изображений. Значение по умолчанию — Aspose.Diagram.Saving.SmoothingMode.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


тип сжатия, применяемый при сохранении генерируемых изображений в формат TIFF. Действует только при сохранении в TIFF. Значение по умолчанию — Aspose.Diagram.Saving.TiffCompression.

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




### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Для описания этого свойства см. [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


Для описания этого свойства см. [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Для описания этого свойства см. [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


Для описания этого свойства см. [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


Для описания этого свойства см. [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


Для описания этого свойства см. [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Для описания этого свойства см. [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Для описания этого свойства см. [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Для описания этого свойства см. [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Для описания этого свойства см. [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)

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

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


Для описания этого свойства см. [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Для описания этого свойства см. [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


Для описания этого свойства см. [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Для описания этого свойства см. [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Для описания этого свойства см. [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


Для описания этого свойства см. [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Для описания этого свойства, пожалуйста, см. [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Для описания этого свойства см. [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


Для описания этого свойства см. [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)

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

