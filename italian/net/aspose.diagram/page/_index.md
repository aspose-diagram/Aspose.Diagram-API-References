---
title: Page
second_title: Aspose.Diagram per riferimento API .NET
description: Contiene elementi che definiscono una pagina nel documento.
type: docs
weight: 2490
url: /it/net/aspose.diagram/page/
---
## Page class

Contiene elementi che definiscono una pagina nel documento.

```csharp
public class Page : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Page](page/#constructor)() | Costruttore. |
| [Page](page/#constructor_1)(int) | Costruttore. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | L'ID della pagina di disegno originale che è stata contrassegnata su sovrapposizioni di markup separate dai revisori del disegno. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | Un flag che indica se la pagina è una pagina di sfondo. |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | La pagina di sfondo della pagina. |
| [Connects](../../aspose.diagram/page/connects/) { get; } | Contiene un elemento Connect per ogni connessione tra due forme in un disegno. |
| [ID](../../aspose.diagram/page/id/) { get; set; } | L'ID univoco dell'elemento all'interno del suo elemento padre. |
| [Name](../../aspose.diagram/page/name/) { get; set; } | Il nome dell'elemento. |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | Il nome universale dell'elemento. |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | Raccolta di pagine. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | Contiene elementi che definiscono il foglio di pagina per un elemento Page o Master. |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | Applica un tema predefinito a questa pagina |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | Applicazione rapida di una variante del tema preimpostata a questa pagina |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | Applica una variante del tema preimpostato a questa pagina |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | L'ID del revisore associato all'overlay di markup. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | Collezione di forme. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX e ViewCenterY specificano un punto centrale su una pagina che una nuova vista (finestra) assume quando viene aperta inizialmente. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX e ViewCenterY specificano un punto centrale su una pagina che una nuova vista (finestra) assume quando viene aperta inizialmente. |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | Il fattore di ingrandimento predefinito da utilizzare quando viene aperta una nuova vista (finestra) della pagina. Ad esempio, 1 = 100%; 1,5 = 150% e così via. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Crea un controllo Activex. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | Aggiunge un commento a una forma con l'id della forma. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | Aggiunge un commento a una forma. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | Aggiunge commento con PinX e PinY definiti. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | Aggiunge la forma creata dal master a una pagina specifica. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | Aggiunge la forma creata dal master sulla pagina con PinX e PinY definiti. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | Aggiunge la forma creata dal master sulla pagina con PinX, PinY, Larghezza e Altezza definiti. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | Aggiunge testo con PinX e PinY definiti. |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | Aggiunge testo con PinX e PinY definiti. |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | Applica lo stile per la pagina intera. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | Forme spaziali automatiche |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | Porta una forma, definita da ID, in avanti di una posizione nell'ordine z. |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | Porta una forma, definita da ID, in primo piano nell'ordine z. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | Centra le forme di una pagina rispetto all'estensione della pagina. Centrare le forme non cambia la loro posizione l'una rispetto all'altra. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Collega le forme tramite connettore. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | Collega le forme tramite connettore. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Collega le forme tramite connettore. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | Collega le forme tramite l'indice del connettore. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Collega le forme tramite l'indice del connettore. |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | Esegue attività definite dall'applicazione associate alla liberazione, al rilascio o al ripristino delle risorse non gestite. |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | Il processo di disegno bezier. La lunghezza dei punti deve essere uguale o maggiore di 3. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | Il processo di disegno dell'ellisse. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | Il processo di tracciare una singola linea. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | Il processo di tracciare una linea. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | Il processo di tracciare una linea. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | Il processo di disegno della polilinea. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | Il processo di disegno della polilinea. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | Il processo di disegno del rettangolo. |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | Il processo di disegno della spline. |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | Forme di colla |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | Incolla forme. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | Incolla le forme nel contenitore |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | Incolla le forme nel contenitore utilizzando il nome della connessione |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | Incolla le forme in base all'ID connessione nel contenitore |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | Incolla la forma all'inizio del connettoreX |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | Incolla la forma all'estremità del connettoreX |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | Dispone le forme e/o reindirizza i connettori per la pagina. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | Sposta la pagina in un'altra posizione nelle pagine. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | Sposta una forma, definita dall'ID, indietro di una posizione nell'ordine z. |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | Sposta una forma, definita dall'ID, in fondo all'ordine z. |

### Guarda anche

* spazio dei nomi [Aspose.Diagram](../../aspose.diagram/)
* assemblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
