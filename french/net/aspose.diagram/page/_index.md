---
title: Page
second_title: Référence de l'API Aspose.Diagram pour .NET
description: Contient des éléments qui définissent une page dans le document.
type: docs
weight: 2490
url: /fr/net/aspose.diagram/page/
---
## Page class

Contient des éléments qui définissent une page dans le document.

```csharp
public class Page : IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Page](page/#constructor)() | Constructeur. |
| [Page](page/#constructor_1)(int) | Constructeur. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | L'ID de la page de dessin d'origine qui a été annotée sur des superpositions de balisage distinctes par les réviseurs du dessin. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | Un indicateur indiquant si la page est une page d'arrière-plan. |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | La page d'arrière-plan de la page. |
| [Connects](../../aspose.diagram/page/connects/) { get; } | Contient un élément Connect pour chaque connexion entre deux formes dans un dessin. |
| [ID](../../aspose.diagram/page/id/) { get; set; } | L'identifiant unique de l'élément dans son élément parent. |
| [Name](../../aspose.diagram/page/name/) { get; set; } | Le nom de l'élément. |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | Le nom universel de l'élément. |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | Collection de pages. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | Contient des éléments qui définissent la feuille de page pour un élément Page ou Master. |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | Appliquer un thème prédéfini à cette page |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | Appliquer un style rapide de variante de thème prédéfini à cette page |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | Appliquer une variante de thème prédéfinie à cette page |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | ID du réviseur associé à la superposition de balisage. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | Collection de formes. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX et ViewCenterY spécifient un point central sur une page qu'une nouvelle vue (fenêtre) assume lors de son ouverture initiale. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX et ViewCenterY spécifient un point central sur une page qu'une nouvelle vue (fenêtre) assume lors de son ouverture initiale. |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | Le facteur d'agrandissement par défaut à utiliser lorsqu'une nouvelle vue (fenêtre) de la page est ouverte. Par exemple, 1 = 100 % ; 1,5 = 150 %, et ainsi de suite. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Crée un contrôle Activex. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | Ajoute un commentaire à une forme avec l'identifiant de la forme. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | Ajoute un commentaire à une forme. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | Ajoute un commentaire avec PinX et PinY définis. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | Ajoute la forme créée par le maître à une page spécifique. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | Ajoute la forme créée par le maître sur la page avec PinX et PinY définis. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | Ajoute la forme créée par le maître sur la page avec PinX, PinY, Largeur et Hauteur définis. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | Ajoute du texte avec PinX et PinY définis. |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | Ajoute du texte avec PinX et PinY définis. |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | Applique le style pour la pleine page. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | Formes d'espacement automatique |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | Fait avancer une forme, définie par ID, d'une position dans l'ordre z. |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | Amène une forme, définie par ID, au début de l'ordre z. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | Centre les formes d'une page par rapport à l'étendue de la page. Le centrage des formes ne modifie pas leur position les unes par rapport aux autres. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Connecter les formes via le connecteur. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | Connecter les formes via le connecteur. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Connecter les formes via le connecteur. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | Connecter les formes via l'index du connecteur. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Connecter les formes via l'index du connecteur. |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | Le processus de dessin de bezier. La longueur des points doit être égale ou supérieure à 3. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | Le processus de dessin Ellipse. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | Le processus de dessin d'une seule ligne. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | Le processus de tracer une ligne. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | Le processus de tracer une ligne. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | Le processus de dessin Polyline. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | Le processus de dessin d'une polyligne. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | Le processus de dessin d'un rectangle. |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | Le processus de dessin de la spline. |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | Formes à coller |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | Formes de colle. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | Collez les formes dans le conteneur |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | Collez les formes dans le conteneur en utilisant le nom de connexion |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | Collez les formes par identifiant de connexion dans le conteneur |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | Collez la forme au BeginX du connecteur |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | Collez la forme à l'extrémité du connecteurX |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | Présente les formes et/ou redirige les connecteurs pour la page. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | Déplace la page vers un autre emplacement dans les pages. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | Déplace une forme, définie par ID, vers l'arrière d'une position dans l'ordre z. |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | Déplace une forme, définie par ID, à l'arrière de l'ordre z. |

### Voir également

* espace de noms [Aspose.Diagram](../../aspose.diagram/)
* Assemblée [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
