---
title: Page
second_title: Aspose.Diagram para la referencia de la API de .NET
description: Contiene elementos que definen una página en el documento.
type: docs
weight: 2490
url: /es/net/aspose.diagram/page/
---
## Page class

Contiene elementos que definen una página en el documento.

```csharp
public class Page : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Page](page/#constructor)() | Constructor. |
| [Page](page/#constructor_1)(int) | Constructor. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | El ID de la página de dibujo original que los revisores del dibujo marcaron en superposiciones de marcado separadas. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | Un indicador que indica si la página es una página de fondo. |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | La página de fondo de la página. |
| [Connects](../../aspose.diagram/page/connects/) { get; } | Contiene un elemento Connect para cada conexión entre dos formas en un dibujo. |
| [ID](../../aspose.diagram/page/id/) { get; set; } | El ID único del elemento dentro de su elemento principal. |
| [Name](../../aspose.diagram/page/name/) { get; set; } | El nombre del elemento. |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | El nombre universal del elemento. |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | Colección de páginas. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | Contiene elementos que definen la hoja de página para un elemento Página o Maestro. |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | Aplicar un tema predeterminado a esta página |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | Aplicar un estilo rápido de variante de tema preestablecido a esta página |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | Aplicar una variante de tema preestablecido a esta página |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | El ID del revisor asociado con la superposición de marcado. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | Colección de formas. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX y ViewCenterY especifican un punto central en una página que asume una nueva vista (ventana) cuando se abre inicialmente. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX y ViewCenterY especifican un punto central en una página que asume una nueva vista (ventana) cuando se abre inicialmente. |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | El factor de ampliación predeterminado que se utilizará cuando se abra una nueva vista (ventana) de la página. Por ejemplo, 1 = 100%; 1,5 = 150%, y así sucesivamente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Crea un Control Activex. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | Agrega un comentario a una forma con la identificación de la forma. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | Agrega comentario a una forma. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | Agrega comentario con PinX y PinY definidos. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | Agrega la forma creada por el maestro a la página específica. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | Agrega la forma creada por el maestro en la página con PinX y PinY definidos. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | Agrega la forma creada por el maestro en la página con PinX, PinY, ancho y alto definidos. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | Agrega Texto con PinX y PinY definidos. |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | Agrega Texto con PinX y PinY definidos. |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | Aplica estilo para página completa. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | Formas de espacio automático |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | Trae una forma, definida por ID, avanza una posición en el orden z. |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | Trae una forma, definida por ID, al frente del orden z. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | Centra las formas de una página con respecto a la extensión de la página. Centrar las formas no cambia su posición entre sí. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Conecta formas a través del conector. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | Conecta formas a través del conector. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Conecta formas a través del conector. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | Conecta formas a través del conector index. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Conecta formas a través del conector index. |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | Realiza tareas definidas por la aplicación asociadas con la liberación, liberación o restablecimiento de recursos no administrados. |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | El proceso de dibujar bezier. La longitud de los puntos debe ser igual o mayor a 3. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | El proceso de dibujar Elipse. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | El proceso de dibujar una sola línea. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | El proceso de dibujo de línea. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | El proceso de dibujo de línea. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | El proceso de dibujar Polilínea. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | El proceso de dibujar polilínea. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | El proceso de dibujar un rectángulo. |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | El proceso de dibujar spline. |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | Formas de pegamento |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | Pega formas. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | Pegar formas en contenedor |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | Pegue las formas en el contenedor usando la conexión name |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | Pegar formas por ID de conexión en container |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | Pegue la forma al conector BeginX |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | Pegue la forma al extremo del conectorX |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | Distribuye las formas y/o redirige los conectores para la página. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | Mueve la página a otra ubicación en las páginas. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | Mueve una forma, definida por ID, una posición hacia atrás en el orden z. |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | Mueve una forma, definida por ID, al final del orden z. |

### Ver también

* espacio de nombres [Aspose.Diagram](../../aspose.diagram/)
* asamblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
