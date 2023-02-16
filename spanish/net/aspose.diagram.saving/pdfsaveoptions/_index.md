---
title: PdfSaveOptions
second_title: Aspose.Diagram para la referencia de la API de .NET
description: Permite especificar opciones adicionales al representar páginas de diagramas en PDF.
type: docs
weight: 3410
url: /es/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Permite especificar opciones adicionales al representar páginas de diagramas en PDF.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Inicializa una nueva instancia de esta clase que se puede usar para guardar un documento en el[`pdf`](../../aspose.diagram/savefileformat/) formato. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Obtiene o establece el área de las formas que se guardarán . |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance/) { get; set; } | Nivel de conformidad deseado para el documento PDF generado. El valor predeterminado esPdf15 . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Cuando los caracteres en el diagrama son Unicode y no están configurados con el valor de fuente correcto o la fuente no está instalada localmente, pueden aparecer como bloques en pdf, imagen o XPS. Establezca la fuente predeterminada como MingLiu o MS Gothic para mostrar estos personajes. |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails/) { get; set; } | Obtiene o establece los detalles de una firma digital. Si no se establece, no se realizará ninguna firma. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Configuración para representar el metarchivo Emf. |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails/) { get; set; } | Obtiene o establece detalles de cifrado. Si no se establece, no se realizará ningún cifrado. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Especifica si ampliar página . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Define si es necesario exportar las formas guía o no. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage/) { get; set; } | Define si es necesario exportar la página oculta o no. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution/) { get; set; } | Obtiene o establece la resolución horizontal de las imágenes generadas, en puntos por pulgada. Aplica el método de generación de imágenes excepto las imágenes en formato Emf. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Define si es necesario exportar los comentarios o no. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality/) { get; set; } | Especifica la calidad de la compresión JPEG para imágenes (si se utiliza la compresión JPEG). El valor predeterminado es 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount/) { get; set; } | Obtiene o establece el número de páginas para representar en PDF. El valor predeterminado es MaxValue, lo que significa que se representarán todas las páginas del diagrama. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex/) { get; set; } | Obtiene o establece el índice basado en 0 de la primera página que se va a representar. El valor predeterminado es 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback/) { get; set; } | Controlar/Indicar el progreso del proceso de guardado de página. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Obtiene o establece el tamaño de página para las imágenes generadas. Puede ser[`PageSize`](../pagesize/) o nulo. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly/) { get; set; } | Especifica si todas las páginas se guardarán en imagen o solo en primer plano. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat/) { get; set; } | Especifica el formato en el que se guardarán las páginas del diagrama renderizado si se usa este objeto de opciones de guardado. Puede ser[`PDF`](../../aspose.diagram/savefileformat/) solo. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Obtiene o establece formas para renderizar. El recuento predeterminado es 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages/) { get; set; } | Define si dividir el diagrama en varias páginas según la configuración de la página. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression/) { get; set; } | Especifica el tipo de compresión que se usará para todos los flujos de contenido excepto imágenes. El valor predeterminado esFlate . |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution/) { get; set; } | Obtiene o establece la resolución vertical de las imágenes generadas, en puntos por pulgada. Aplica el método de generación de imágenes, excepto la imagen en formato Emf. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback/) { get; set; } | Obtiene o establece la devolución de llamada de advertencia. |

### Ver también

* class [RenderingSaveOptions](../renderingsaveoptions/)
* espacio de nombres [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* asamblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
