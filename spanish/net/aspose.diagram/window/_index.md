---
title: Window
second_title: Aspose.Diagram para la referencia de la API de .NET
description: Representa una ventana abierta en una instancia de Microsoft Visio. Este elemento contiene información necesaria para volver a crear exactamente una ventana de interfaz de usuario en el área de trabajo de la aplicación cuando Visio abre inicialmente el archivo DatadiagramML.
type: docs
weight: 4380
url: /es/net/aspose.diagram/window/
---
## Window class

Representa una ventana abierta en una instancia de Microsoft Visio. Este elemento contiene información necesaria para volver a crear exactamente una ventana de interfaz de usuario en el área de trabajo de la aplicación cuando Visio abre inicialmente el archivo DatadiagramML.

```csharp
public class Window
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Window](window)() | Constructor. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Container](../../aspose.diagram/window/container) { get; set; } | ID del contenedor: Página, Hoja o Máster. Solo relevante y necesario si se especifica ContainerType. |
| [ContainerType](../../aspose.diagram/window/containertype) { get; set; } | Puede ser uno de los siguientes valores: Documento, Página o Maestro. Solo es relevante cuando WindowType se especifica como Drawing u Sheet. |
| [Document](../../aspose.diagram/window/document) { get; set; } | Ruta del archivo del documento que se muestra en esta ventana. Este atributo es relevante para ventanas cuyo WindowType se especifica como Stencil. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled) { get; set; } | Especifica si la función de cuadrícula dinámica está habilitada para un documento o ventana. |
| [GlueSettings](../../aspose.diagram/window/gluesettings) { get; set; } | Especifica los objetos a los que se pega la forma cuando se activa el pegamento en el documento. |
| [ID](../../aspose.diagram/window/id) { get; set; } | El ID único del elemento dentro de su elemento principal. |
| [Master](../../aspose.diagram/window/master) { get; set; } | ID maestro si esta ventana muestra un maestro. |
| [Page](../../aspose.diagram/window/page) { get; set; } | ID de página si esta ventana muestra una página. Relevante solo cuando WindowType se especifica como Drawing y ContainerType se especifica como Page. |
| [ParentWindow](../../aspose.diagram/window/parentwindow) { get; set; } | ID de la ventana en la que se encuentra esta ventana de plantilla. Relevante solo cuando WindowType se especifica como Stencil. |
| [ReadOnly](../../aspose.diagram/window/readonly) { get; set; } | Indicador de solo lectura si esta plantilla no es una plantilla de documento. |
| [Sheet](../../aspose.diagram/window/sheet) { get; set; } | ID de hoja en contenedor. Relevante solo cuando se especifica Contenedor como Hoja. |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints) { get; set; } | Especifica si los puntos de conexión se muestran en una ventana. |
| [ShowGrid](../../aspose.diagram/window/showgrid) { get; set; } | Especifica si se muestra una rejilla en la ventana de dibujo. |
| [ShowGuides](../../aspose.diagram/window/showguides) { get; set; } | Especifica si las guías se muestran en la ventana de dibujo. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks) { get; set; } | Especifica si los saltos de página se muestran en una ventana. |
| [ShowRulers](../../aspose.diagram/window/showrulers) { get; set; } | Especifica si las reglas se muestran en la ventana de dibujo. |
| [SnapAngles](../../aspose.diagram/window/snapangles) { get; } | Contiene una colección de elementos SnapAngle. |
| [SnapExtensions](../../aspose.diagram/window/snapextensions) { get; set; } | Especifica si una configuración de extensión de ajuste específica está habilitada o deshabilitada para la ventana activa. El valor puede ser una suma de los valores de la siguiente tabla. |
| [SnapSettings](../../aspose.diagram/window/snapsettings) { get; set; } | Especifica los objetos a los que se ajustan las formas cuando el ajuste está activo en la ventana. El valor puede ser una suma de los valores de la siguiente tabla. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup) { get; set; } | Especifica el grupo de ventanas de galería de símbolos combinadas del que forma parte la ventana. Este atributo es relevante solo para los elementos Window cuyo atributo WindowType es Stencil, y solo si la ventana de la plantilla es parte de un grupo fusionado de ventanas de la plantilla. Todas las ventanas de plantilla que forman parte del mismo grupo fusionado tienen el mismo valor de elemento StencilGroup. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos) { get; set; } | Contiene un número entero que especifica la posición relativa de una plantilla dentro de un grupo en una ventana. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos) { get; set; } | Especifica el ancho del control de pestaña de página de una ventana de dibujo (como una fracción del ancho total de la ventana de dibujo). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx) { get; set; } | Opcional doble. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery) { get; set; } | Opcional doble. |
| [ViewScale](../../aspose.diagram/window/viewscale) { get; set; } | Opcional doble. |
| [WindowHeight](../../aspose.diagram/window/windowheight) { get; set; } | Altura del rectángulo de la ventana. |
| [WindowLeft](../../aspose.diagram/window/windowleft) { get; set; } | Coordenada izquierda del rectángulo de la ventana. |
| [WindowState](../../aspose.diagram/window/windowstate) { get; set; } | Este atributo puede ser la suma de los siguientes valores. |
| [WindowTop](../../aspose.diagram/window/windowtop) { get; set; } | Coordenada superior del rectángulo de la ventana. |
| [WindowType](../../aspose.diagram/window/windowtype) { get; set; } | Un valor enumerado que puede ser uno de los siguientes: Drawing, Sheet, Stencil o Icon. Un elemento Window de WindowType='Stencil' debe aparecer después de su ventana de dibujo principal (WindowType='Drawing') y antes de cualquier otra ventana de dibujo elementos. |
| [WindowWidth](../../aspose.diagram/window/windowwidth) { get; set; } | Ancho del rectángulo de la ventana. |

### Ver también

* espacio de nombres [Aspose.Diagram](../../aspose.diagram)
* asamblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
