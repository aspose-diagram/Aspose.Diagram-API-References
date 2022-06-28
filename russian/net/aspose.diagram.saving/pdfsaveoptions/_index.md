---
title: PdfSaveOptions
second_title: Справочник по Aspose.Diagram для .NET API
description: Позволяет указать дополнительные параметры при рендеринге страниц схемы в PDF.
type: docs
weight: 3400
url: /ru/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Позволяет указать дополнительные параметры при рендеринге страниц схемы в PDF.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | Инициализирует новый экземпляр этого класса, который можно использовать для сохранения документа в формате[`Pdf`](../../aspose.diagram/savefileformat)Формат . |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area) { get; set; } | Получает или задает площадь сохраняемых фигур. |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance) { get; set; } | Желаемый уровень соответствия для сгенерированного документа PDF. По умолчанию:Pdf15. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | Когда символы на диаграмме имеют формат Unicode и для них не установлено правильное значение шрифта или шрифт не установлен локально, они могут отображаться как блочные в формате pdf, изображения или XPS. Установите DefaultFont, например MingLiu или MS Gothic, для отображения этих символов. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails) { get; set; } | Получает или задает сведения о цифровой подписи. Если не задано, то подписание производиться не будет. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting) { get; set; } | Настройка для рендеринга метафайла EMF. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails) { get; set; } | Получает или устанавливает детали шифрования. Если не установлено, то шифрование выполняться не будет. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage) { get; set; } | Указывает, следует ли увеличивать страницу. |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes) { get; set; } | Определяет, нужно ли экспортировать направляющие формы или нет. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage) { get; set; } | Определяет, нужно ли экспортировать скрытую страницу или нет. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution) { get; set; } | Получает или задает горизонтальное разрешение для сгенерированных изображений в точках на дюйм. Применяет метод генерации изображения, за исключением изображений формата Emf. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments) { get; set; } | Определяет, нужно ли экспортировать комментарии или нет. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality) { get; set; } | Указывает качество сжатия JPEG для изображений (если используется сжатие JPEG). По умолчанию 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount) { get; set; } | Получает или задает количество страниц для отображения в PDF. По умолчанию установлено значение MaxValue, что означает, что будут отображены все страницы диаграммы. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex) { get; set; } | Получает или задает отсчитываемый от 0 индекс первой отображаемой страницы. По умолчанию 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback) { get; set; } | Управление/указание хода процесса сохранения страницы. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize) { get; set; } | Получает или задает размер страницы для сгенерированных изображений. Может быть[`PageSize`](../pagesize) или null. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly) { get; set; } | Указывает, будут ли все страницы сохранены в изображении или только передний план. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat) { get; set; } | Задает формат, в котором будут сохранены визуализированные страницы схемы, если используется этот объект параметров сохранения. Может быть[`PDF`](../../aspose.diagram/savefileformat)Только . |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes) { get; set; } | Получает или задает фигуры для визуализации. Счетчик по умолчанию равен 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages) { get; set; } | Определяет, следует ли разделить диаграмму на несколько страниц в соответствии с настройкой страницы. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression) { get; set; } | Указывает тип сжатия, который будет использоваться для всех потоков содержимого, кроме изображений. Значение по умолчанию:!:PdfTextCompressionCore.Flate. |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution) { get; set; } | Получает или задает вертикальное разрешение для сгенерированных изображений в точках на дюйм. Применяет метод генерации изображения, за исключением изображения в формате Emf. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback) { get; set; } | Получает или устанавливает обратный вызов предупреждения. |

### Смотрите также

* class [RenderingSaveOptions](../renderingsaveoptions)
* пространство имен [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* сборка [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
