---
title: ImageSaveOptions
second_title: Справочник по Aspose.Diagram для .NET API
description: Позволяет указать дополнительные параметры при отображении страниц диаграммы в изображения.
type: docs
weight: 3280
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
| [ImageSaveOptions](imagesaveoptions/)(SaveFileFormat) | Инициализирует новый экземпляр этого класса, который можно использовать для сохранения визуализированных изображений в[`размолвка`](../../aspose.diagram/savefileformat/) , [`PNG`](../../aspose.diagram/savefileformat/) ,[`БМП`](../../aspose.diagram/savefileformat/) ,[`ЭДС`](../../aspose.diagram/savefileformat/) или[`JPEG`](../../aspose.diagram/savefileformat/) формат. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Получает или задает площадь сохраняемых фигур . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality/) { get; set; } | Указывает уровень качества для использования во время композитинга. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom/) { get; set; } | Этот параметр аналогичен масштабу, но не влияет на размер генерируемого изображения. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Если символы на диаграмме имеют формат Unicode и для них не задано правильное значение шрифта или шрифт не установлен локально, они могут отображаться как блоки в pdf, изображениях или XPS. Установите шрифт по умолчанию, например MingLiu или MS Gothic, чтобы отобразить эти символов. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Настройка для рендеринга метафайла EMF. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Указывает, следует ли увеличивать страницу . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Определяет, нужно ли экспортировать направляющие формы или нет. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage/) { get; set; } | Определяет, нужно ли экспортировать скрытую страницу или нет. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness/) { get; set; } | Получает или устанавливает яркость сгенерированных изображений. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode/) { get; set; } | Получает или задает цветовой режим для сгенерированных изображений. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast/) { get; set; } | Получает или задает контраст для сгенерированных изображений. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode/) { get; set; } | Указывает алгоритм, используемый при масштабировании или повороте изображений. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Определяет, нужно ли экспортировать комментарии или нет. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality/) { get; set; } | Получает или задает значение, определяющее качество сгенерированных изображений JPEG. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount/) { get; set; } | Получает или задает количество страниц для отображения при сохранении в многостраничный файл TIFF. Значение по умолчанию — MaxValue, что означает, что будут отображаться все страницы диаграммы. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex/) { get; set; } | Получает или задает отсчитываемый от 0 индекс первой отображаемой страницы. По умолчанию 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Получает или задает размер страницы для сгенерированных изображений. Может быть[`PageSize`](../pagesize/) или ноль. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode/) { get; set; } | Получает или задает значение, указывающее, как смещаются пиксели во время рендеринга. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution/) { get; set; } | Получает или задает разрешение сгенерированных изображений в точках на дюйм. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea/) { get; set; } | Указывает, будет ли область сохранения такой же, как в pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly/) { get; set; } | Указывает, будут ли сохранены все страницы в изображении или только передний план. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat/) { get; set; } | Задает формат, в котором будут сохранены визуализированные страницы диаграмм, если используется этот объект параметров сохранения. Может быть[`размолвка`](../../aspose.diagram/savefileformat/) ,[`PNG`](../../aspose.diagram/savefileformat/) , [`БМП`](../../aspose.diagram/savefileformat/) ,[`ЭДС`](../../aspose.diagram/savefileformat/) или[`JPEG`](../../aspose.diagram/savefileformat/) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale/) { get; set; } | Получает или задает коэффициент масштабирования для сгенерированных изображений. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Получает или задает фигуры для визуализации. Счетчик по умолчанию: 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode/) { get; set; } | Указывает, применяется ли сглаживание (сглаживание) к линиям и кривым, а также к краям заполненных областей. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression/) { get; set; } | Получает или задает тип сжатия, применяемый при сохранении сгенерированных изображений в формате TIFF. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Получает или задает обратный вызов предупреждения. |

### Смотрите также

* class [RenderingSaveOptions](../renderingsaveoptions/)
* пространство имен [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* сборка [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
