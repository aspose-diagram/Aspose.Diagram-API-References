---
title: ImageSaveOptions
second_title: Aspose.Diagram para la referencia de la API de .NET
description: Permite especificar opciones adicionales al representar páginas de diagramas en imágenes.
type: docs
weight: 3280
url: /es/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

Permite especificar opciones adicionales al representar páginas de diagramas en imágenes.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/)(SaveFileFormat) | Inicializa una nueva instancia de esta clase que se puede usar para guardar imágenes renderizadas en el[`Pelea`](../../aspose.diagram/savefileformat/) , [`png`](../../aspose.diagram/savefileformat/) ,[`bmp`](../../aspose.diagram/savefileformat/) ,[`fem`](../../aspose.diagram/savefileformat/) o[`JPEG`](../../aspose.diagram/savefileformat/) formato. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Obtiene o establece el área de las formas que se guardarán . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality/) { get; set; } | Especifica el nivel de calidad que se utilizará durante la composición. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom/) { get; set; } | Este parámetro es similar a la escala, pero no afecta el tamaño de la imagen generada. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Cuando los caracteres en el diagrama son Unicode y no están configurados con el valor de fuente correcto o la fuente no está instalada localmente, pueden aparecer como bloques en pdf, imagen o XPS. Establezca la fuente predeterminada como MingLiu o MS Gothic para mostrar estos personajes. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Configuración para representar el metarchivo Emf. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Especifica si ampliar página . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Define si es necesario exportar las formas guía o no. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage/) { get; set; } | Define si es necesario exportar la página oculta o no. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness/) { get; set; } | Obtiene o establece el brillo de las imágenes generadas. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode/) { get; set; } | Obtiene o establece el modo de color de las imágenes generadas. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast/) { get; set; } | Obtiene o establece el contraste de las imágenes generadas. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode/) { get; set; } | Especifica el algoritmo que se utiliza cuando las imágenes se escalan o giran. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Define si es necesario exportar los comentarios o no. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality/) { get; set; } | Obtiene o establece un valor que determina la calidad de las imágenes JPEG generadas. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount/) { get; set; } | Obtiene o establece el número de páginas a representar cuando se guarda en un archivo TIFF de varias páginas. El valor predeterminado es MaxValue, lo que significa que se representarán todas las páginas del diagrama. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex/) { get; set; } | Obtiene o establece el índice basado en 0 de la primera página que se va a representar. El valor predeterminado es 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Obtiene o establece el tamaño de página para las imágenes generadas. Puede ser[`PageSize`](../pagesize/) o nulo. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode/) { get; set; } | Obtiene o establece un valor que especifica cómo se compensan los píxeles durante el renderizado. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution/) { get; set; } | Obtiene o establece la resolución de las imágenes generadas, en puntos por pulgada. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea/) { get; set; } | Especifica si el área de guardado es igual que pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly/) { get; set; } | Especifica si todas las páginas se guardarán en imagen o solo en primer plano. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat/) { get; set; } | Especifica el formato en el que se guardarán las páginas del diagrama renderizado si se usa este objeto de opciones de guardado. Puede ser[`Pelea`](../../aspose.diagram/savefileformat/) ,[`png`](../../aspose.diagram/savefileformat/) , [`bmp`](../../aspose.diagram/savefileformat/) ,[`fem`](../../aspose.diagram/savefileformat/) o[`JPEG`](../../aspose.diagram/savefileformat/) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale/) { get; set; } | Obtiene o establece el factor de zoom para las imágenes generadas. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Obtiene o establece formas para renderizar. El recuento predeterminado es 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode/) { get; set; } | Especifica si se aplica suavizado (antialiasing) a las líneas y curvas y los bordes de las áreas rellenas. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression/) { get; set; } | Obtiene o establece el tipo de compresión que se aplicará al guardar las imágenes generadas en formato TIFF. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Obtiene o establece la devolución de llamada de advertencia. |

### Ver también

* class [RenderingSaveOptions](../renderingsaveoptions/)
* espacio de nombres [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* asamblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
