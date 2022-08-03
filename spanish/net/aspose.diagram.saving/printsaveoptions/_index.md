---
title: PrintSaveOptions
second_title: Aspose.Diagram para la referencia de la API de .NET
description: Permite especificar opciones adicionales al imprimir el diagrama.
type: docs
weight: 3430
url: /es/net/aspose.diagram.saving/printsaveoptions/
---
## PrintSaveOptions class

Permite especificar opciones adicionales al imprimir el diagrama.

```csharp
public class PrintSaveOptions : RenderingSaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PrintSaveOptions](printsaveoptions)() | Inicializa una nueva instancia de esta clase |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area) { get; set; } | Obtiene o establece el área de las formas que se guardarán . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont) { get; set; } | Cuando los caracteres en el diagrama son Unicode y no están configurados con el valor de fuente correcto o la fuente no está instalada localmente, pueden aparecer como bloques en pdf, imagen o XPS. Establezca la fuente predeterminada como MingLiu o MS Gothic para mostrar estos personajes. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting) { get; set; } | Configuración para representar el metarchivo Emf. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage) { get; set; } | Especifica si ampliar página . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes) { get; set; } | Define si es necesario exportar las formas guía o no. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments) { get; set; } | Define si es necesario exportar los comentarios o no. |
| [PageCount](../../aspose.diagram.saving/printsaveoptions/pagecount) { get; set; } | Obtiene o establece el número de páginas a representar cuando se guarda en un archivo de varias páginas. El valor predeterminado es MaxValue, lo que significa que se imprimirán todas las páginas del diagrama. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize) { get; set; } | Obtiene o establece el tamaño de página para las imágenes generadas. Puede ser[`PageSize`](../pagesize) o nulo. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/printsaveoptions/saveforegroundpagesonly) { get; set; } | Especifica si se imprimirán todas las páginas o solo en primer plano. |
| virtual [SaveFormat](../../aspose.diagram.saving/saveoptions/saveformat) { get; set; } | Especifica el formato en el que se guardará el documento si se utiliza este objeto de opciones de guardado. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes) { get; set; } | Obtiene o establece formas para renderizar. El recuento predeterminado es 0. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback) { get; set; } | Obtiene o establece la devolución de llamada de advertencia. |

### Ver también

* class [RenderingSaveOptions](../renderingsaveoptions)
* espacio de nombres [Aspose.Diagram.Saving](../../aspose.diagram.saving)
* asamblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->