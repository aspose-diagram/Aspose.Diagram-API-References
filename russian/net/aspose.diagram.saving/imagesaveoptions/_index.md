---
title: ImageSaveOptions
second_title: Справочник по Aspose.Diagram для .NET API
description: Позволяет указать дополнительные параметры при отображении страниц диаграммы в изображения.
type: docs
weight: 3270
url: /ru/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

Позволяет указать дополнительные параметры при отображении страниц диаграммы в изображения.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions)(SaveFileFormat) | Инициализирует новый экземпляр этого класса, который можно использовать для сохранения визуализированных изображений в формате[`Tiff`](../../aspose.diagram/savefileformat) , [`Png`](../../aspose.diagram/savefileformat) ,[`Bmp`](../../aspose.diagram/savefileformat) ,[`Emf`](../../aspose.diagram/savefileformat) или[`Jpeg`](../../aspose.diagram/savefileformat)Формат . |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area) { get; set; } | Получает или задает площадь сохраняемых фигур. |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality) { get; set; } | Указывает уровень качества для использования во время компоновки. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom) { get; set; } | Этот параметр аналогичен масштабу, но не влияет на размер генерируемого изображения. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | Когда символы на диаграмме имеют формат Unicode и для них не установлено правильное значение шрифта или шрифт не установлен локально, они могут отображаться как блочные в формате pdf, изображения или XPS. Установите DefaultFont, например MingLiu или MS Gothic, для отображения этих символов. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting) { get; set; } | Настройка для рендеринга метафайла EMF. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage) { get; set; } | Указывает, следует ли увеличивать страницу. |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes) { get; set; } | Определяет, нужно ли экспортировать направляющие формы или нет. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage) { get; set; } | Определяет, нужно ли экспортировать скрытую страницу или нет. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness) { get; set; } | Получает или устанавливает яркость сгенерированных изображений. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode) { get; set; } | Получает или задает цветовой режим для сгенерированных изображений. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast) { get; set; } | Получает или задает контраст для сгенерированных изображений. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode) { get; set; } | Указывает алгоритм, используемый при масштабировании или повороте изображений. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments) { get; set; } | Определяет, нужно ли экспортировать комментарии или нет. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality) { get; set; } | Получает или задает значение, определяющее качество сгенерированных изображений JPEG. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount) { get; set; } | Получает или задает количество отображаемых страниц при сохранении в многостраничный файл TIFF. По умолчанию установлено значение MaxValue, что означает, что будут отображены все страницы диаграммы. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex) { get; set; } | Получает или задает отсчитываемый от 0 индекс первой отображаемой страницы. По умолчанию 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize) { get; set; } | Получает или задает размер страницы для сгенерированных изображений. Может быть[`PageSize`](../pagesize) или null. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode) { get; set; } | Получает или задает значение, указывающее, как смещаются пиксели во время рендеринга. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution) { get; set; } | Получает или задает разрешение сгенерированных изображений в точках на дюйм. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea) { get; set; } | Указывает, будет ли область сохранения такой же, как в pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly) { get; set; } | Указывает, будут ли все страницы сохранены в изображении или только передний план. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat) { get; set; } | Задает формат, в котором будут сохранены визуализированные страницы схемы, если используется этот объект параметров сохранения. Может быть[`Tiff`](../../aspose.diagram/savefileformat) ,[`Png`](../../aspose.diagram/savefileformat) , [`Bmp`](../../aspose.diagram/savefileformat) ,[`Emf`](../../aspose.diagram/savefileformat) или[`Jpeg`](../../aspose.diagram/savefileformat) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale) { get; set; } | Получает или задает коэффициент масштабирования для сгенерированных изображений. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes) { get; set; } | Получает или задает фигуры для визуализации. Счетчик по умолчанию равен 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode) { get; set; } | Указывает, применяется ли сглаживание (сглаживание) к линиям, кривым и краям заполненных областей. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression) { get; set; } | Получает или задает тип сжатия, применяемый при сохранении сгенерированных изображений в формате TIFF. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | Получает или устанавливает обратный вызов предупреждения. |

### Смотрите также

* class [RenderingSaveOptions](../renderingsaveoptions)
* пространство имен [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* сборка [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
