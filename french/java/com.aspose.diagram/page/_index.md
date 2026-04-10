---
title: Page
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient les éléments qui définissent une page dans le document.
type: docs
weight: 260
url: /fr/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

Contient les éléments qui définissent une page dans le document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Page()](#Page--) | Constructeur. |
| [Page(int ID)](#Page-int-) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Crée un contrôle Activex. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | Ajoute un commentaire à une forme. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | Ajoute un commentaire avec PinX et PinY définis. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | Ajoute un commentaire à une forme avec l'ID de la forme. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | Ajoute une forme créée par le maître à une page spécifique. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | Ajoute une forme créée par le maître sur la page avec PinX,PinY, largeur et hauteur définis. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | Ajoute une forme créée par le maître sur la page avec PinX et PinY définis. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | Ajoute du texte avec PinX et PinY définis. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | Ajoute du texte avec PinX et PinY définis. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | Applique le style pour toute la page. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | Espacement automatique des formes |
| [bringForward(long shapeId)](#bringForward-long-) | Déplace une forme, définie par ID, d'une position vers l'avant dans l'ordre Z. |
| [bringToFront(long shapeId)](#bringToFront-long-) | Déplace une forme, définie par ID, au premier plan de l'ordre Z. |
| [centerDrawing()](#centerDrawing--) | Centre les formes d'une page par rapport à l'étendue de la page. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Connecte les formes via un connecteur. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | Connecte les formes via un connecteur. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | Connecte les formes via un connecteur. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Connecte les formes via l'index du connecteur. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | Connecte les formes via l'index du connecteur. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | Effectue des tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | Le processus de dessin d'une ellipse. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | Le processus de dessin d'une ligne unique. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | Le processus de dessin d'une ligne. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | Le processus de dessin d'une polyligne. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | Le processus de dessin d'un rectangle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | L'ID de la page de dessin originale qui a été annotée avec des superpositions d'annotations séparées par les réviseurs du dessin. |
| [getBackPage()](#getBackPage--) | La page d'arrière-plan. |
| [getBackground()](#getBackground--) | Un indicateur indiquant si la page est une page d'arrière-plan. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Contient un élément Connect pour chaque connexion entre deux formes dans un dessin. |
| [getID()](#getID--) | L'ID unique de l'élément au sein de son élément parent. |
| [getName()](#getName--) | Le nom de l'élément. |
| [getNameU()](#getNameU--) | Le nom universel de l'élément. |
| [getPageSheet()](#getPageSheet--) | Contient des éléments qui définissent la feuille de page pour un élément Page ou Master. |
| [getPages()](#getPages--) | Collection de pages. |
| [getReviewerID()](#getReviewerID--) | L'ID du réviseur associé à la superposition d'annotation. |
| [getShapes()](#getShapes--) | Collection de formes. |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX et ViewCenterY spécifient un point central sur une page qu'une nouvelle vue (fenêtre) adopte lorsqu'elle est ouverte initialement. |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX et ViewCenterY spécifient un point central sur une page qu'une nouvelle vue (fenêtre) adopte lorsqu'elle est ouverte initialement. |
| [getViewScale()](#getViewScale--) | Le facteur d'agrandissement par défaut à utiliser lorsqu'une nouvelle vue (fenêtre) de la page est ouverte. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | Coller la forme au BeginX du connecteur |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | Coller la forme au EndX du connecteur |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Coller les formes. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | Coller les formes |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | Coller les formes dans le conteneur |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | Coller les formes dans le conteneur en utilisant le nom de connexion |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | Coller les formes par identifiant de connexion dans le conteneur |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Dispose les formes et/ou redirige les connecteurs pour la page. |
| [moveTo(int index)](#moveTo-int-) | Déplace la page vers un autre emplacement parmi les pages. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | Déplace une forme, définie par ID, d'une position en arrière dans l'ordre Z. |
| [sendToBack(long shapeId)](#sendToBack-long-) | Déplace une forme, définie par ID, à l'arrière de l'ordre Z. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | Pour la description de cette propriété, veuillez consulter [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | Pour la description de cette propriété, veuillez consulter [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | Pour la description de cette propriété, veuillez consulter [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | Pour la description de cette propriété, veuillez consulter [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Appliquer un thème prédéfini à cette page |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Appliquer une variante de thème prédéfini quickstyle à cette page |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Appliquer une variante de thème prédéfini à cette page |
| [setReviewerID(int value)](#setReviewerID-int-) | Pour la description de cette propriété, veuillez consulter [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Pour la description de cette propriété, veuillez consulter [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Pour la description de cette propriété, veuillez consulter [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Pour la description de cette propriété, veuillez consulter [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


Constructeur.

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


Constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Crée un contrôle Activex.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type du contrôle. |
| pinX | double | Spécifie la coordonnée x de l'épingle de la forme (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de l'épingle de la forme (centre de rotation) par rapport à la page. |
| largeur | double | Spécifie la largeur de la forme en pouces. |
| hauteur | double | Spécifie la hauteur de la forme en pouces. |

**Returns:**
long -
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


Ajoute un commentaire à une forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | Spécifie la forme qui ajoute le commentaire. |
| comment | java.lang.String | Chaîne du commentaire. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


Ajoute un commentaire avec PinX et PinY définis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double | Spécifie la coordonnée x de l'épingle du commentaire (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de l'épingle du commentaire (centre de rotation) par rapport à la page. |
| comment | java.lang.String | Chaîne du commentaire. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


Ajoute un commentaire à une forme avec l'ID de la forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | Chaîne du commentaire. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


Ajoute une forme créée par le maître à une page spécifique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Nouvel objet forme[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Nom du maître. |

**Returns:**
long - L'ID unique de la forme dans la collection de formes sur la page spécifiée.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| largeur | double |  |
| hauteur | double |  |
| stream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| largeur | double |  |
| hauteur | double |  |
| imageStream | java.io.InputStream |  |
| objectDataStream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, String masterName) {#addShape-double-double-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName)
```


Ajoute une forme créée par le maître sur la page avec PinX,PinY, largeur et hauteur définis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double | Spécifie la coordonnée x de l'épingle de la forme (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de l'épingle de la forme (centre de rotation) par rapport à la page. |
| largeur | double | Spécifie la largeur de la forme en pouces. |
| hauteur | double | Spécifie la hauteur de la forme en pouces. |
| masterName | java.lang.String | Nom du maître. |

**Returns:**
long - L'ID unique de la forme dans la collection de formes sur la page spécifiée.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


Ajoute une forme créée par le maître sur la page avec PinX et PinY définis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double | Spécifie la coordonnée x de l'épingle de la forme (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de l'épingle de la forme (centre de rotation) par rapport à la page. |
| masterName | java.lang.String | Nom du maître. |

**Returns:**
long - L'ID unique de la forme dans la collection de formes sur la page spécifiée.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


Ajoute du texte avec PinX et PinY définis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double | Spécifie la coordonnée x de la broche du texte (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de la broche du texte (centre de rotation) par rapport à la page. |
| largeur | double |  |
| hauteur | double |  |
| text | java.lang.String | chaîne de texte. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


Ajoute du texte avec PinX et PinY définis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double | Spécifie la coordonnée x de la broche du texte (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de la broche du texte (centre de rotation) par rapport à la page. |
| largeur | double | Spécifie la largeur du texte. |
| hauteur | double | Spécifie la hauteur du texte. |
| text | java.lang.String | chaîne de texte. |
| fontName | java.lang.String | nom de police du texte. |
| fontColor | java.lang.String | couleur de police du texte. |
| size | double | taille de police du texte. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


Applique le style pour toute la page. La valeur par défaut est -1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| textStyle | int | identifiant du style du texte. |
| lineStyle | int | identifiant du style de ligne. |
| fillStyle | int | identifiant du style de remplissage. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


Espacement automatique des formes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | Spécifie que les formes soient espacées automatiquement. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


Déplace une forme, définie par ID, d'une position vers l'avant dans l'ordre Z.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeId | long | ID de shape.long |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


Déplace une forme, définie par ID, au premier plan de l'ordre Z.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeId | long | ID de shape.long |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centre les formes d'une page par rapport à l'étendue de la page. Le centrage des formes ne modifie pas leur position les unes par rapport aux autres.

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


Connecte les formes via un connecteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | La forme où le connecteur commence [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | L'emplacement sur la première forme où le connecteur sera connecté Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | La forme où le connecteur se termine [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | L'emplacement sur la deuxième forme où le connecteur sera connecté Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | La forme avec le type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


Connecte les formes via un connecteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeFromId | long | L'ID de la forme où le connecteur commence [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | L'emplacement sur la première forme où le connecteur sera connecté Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | L'ID de la forme où le connecteur se termine [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | L'emplacement sur la deuxième forme où le connecteur sera connecté Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | L'ID de la forme avec le type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


Connecte les formes via un connecteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeFromId | long | L'ID de la forme où le connecteur commence [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | Le nom de connexion sur la première forme où le connecteur sera connecté. |
| shapeToId | long | L'ID de la forme où le connecteur se termine [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | Le nom de connexion sur la deuxième forme où le connecteur sera connecté. |
| connectorId | long | L'ID de la forme avec le type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


Connecte les formes via l'index du connecteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | La forme où le connecteur commence [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | L'index de la connexion sur la première forme |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | La forme où le connecteur se termine [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | L'index de la connexion sur la deuxième forme |
| connector | [Shape](../../com.aspose.diagram/shape) | La forme avec le type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


Connecte les formes via l'index du connecteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeFromId | long | L'ID de la forme où le connecteur commence [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | L'index de la connexion sur la première forme |
| shapeToId | long | L'ID de la forme où le connecteur se termine [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | L'index de la connexion sur la deuxième forme |
| connectorId | long | L'ID de la forme avec le type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


Effectue des tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


Le processus de dessin d'une ellipse.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double | Spécifie la coordonnée x de l'épingle de la forme (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de l'épingle de la forme (centre de rotation) par rapport à la page. |
| largeur | double | Spécifie la largeur de la forme |
| hauteur | double | Spécifie la hauteur de la forme |

**Returns:**
long -
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


Le processus de dessin d'une ligne unique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| beginX | double | Spécifie la coordonnée x de début de la position de la forme par rapport à la page. |
| beginY | double | Spécifie la coordonnée y de début de la position de la forme par rapport à la page. |
| endX | double | Spécifie la coordonnée x de fin de la position de la forme par rapport à la page. |
| endY | double | Spécifie la coordonnée y de fin de la position de la forme par rapport à la page. |

**Returns:**
long - L'ID unique de la forme dans la collection de formes sur la page spécifiée.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


Le processus de dessin d'une ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double | Spécifie la coordonnée x de l'épingle de la forme (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de l'épingle de la forme (centre de rotation) par rapport à la page. |
| largeur | double | Spécifie la largeur de la forme |
| hauteur | double | Spécifie la hauteur de la forme |
| xyArray | double[] | Un tableau de valeurs x et y alternées qui définit les points de la nouvelle forme |

**Returns:**
long - L'ID unique de la forme dans la collection de formes sur la page spécifiée.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


Le processus de dessin d'une polyligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double | Spécifie la coordonnée x de l'épingle de la forme (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de l'épingle de la forme (centre de rotation) par rapport à la page. |
| largeur | double | Spécifie la largeur de la forme |
| hauteur | double | Spécifie la hauteur de la forme |
| xyArray | double[] | Un tableau de valeurs x et y alternées qui définit les points de la nouvelle forme |

**Returns:**
long - L'ID unique de la forme dans la collection de formes sur la page spécifiée.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


Le processus de dessin d'un rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pinX | double | Spécifie la coordonnée x de l'épingle de la forme (centre de rotation) par rapport à la page. |
| pinY | double | Spécifie la coordonnée y de l'épingle de la forme (centre de rotation) par rapport à la page. |
| largeur | double | Spécifie la largeur de la forme |
| hauteur | double | Spécifie la hauteur de la forme |

**Returns:**
long - L'ID unique de la forme dans la collection de formes sur la page spécifiée.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


L'ID de la page de dessin originale qui a été annotée avec des superpositions d'annotations séparées par les réviseurs du dessin.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


La page d'arrière-plan.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


Un indicateur indiquant si la page est une page d'arrière-plan.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


Contient un élément Connect pour chaque connexion entre deux formes dans un dessin.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


L'ID unique de l'élément au sein de son élément parent.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Le nom de l'élément.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Le nom universel de l'élément.

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Contient des éléments qui définissent la feuille de page pour un élément Page ou Master.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Collection de pages.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


L'ID du réviseur associé à la superposition d'annotation.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Collection de formes.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX et ViewCenterY spécifient un point central sur une page qu'une nouvelle vue (fenêtre) adopte lorsqu'elle est ouverte initialement.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX et ViewCenterY spécifient un point central sur une page qu'une nouvelle vue (fenêtre) adopte lorsqu'elle est ouverte initialement.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Le facteur d'agrandissement par défaut à utiliser lorsqu'une nouvelle vue (fenêtre) de la page est ouverte. Par exemple, 1 = 100 %; 1,5 = 150 %, etc.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


Coller la forme au BeginX du connecteur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeFromId | long | L'ID de la forme où le connecteur commence [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Le nom de connexion sur la forme où le connecteur sera relié. |
| connectorId | long | L'ID de la forme avec le type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


Coller la forme au EndX du connecteur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeToId | long | L'ID de la forme où le connecteur se termine [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Le nom de connexion sur la deuxième forme où le connecteur sera connecté. |
| connectorId | long | L'ID de la forme avec le type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


Coller les formes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | La forme qui est collée depuis [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | L'emplacement sur la première forme où coller Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | La forme où coller à [Shape](../../com.aspose.diagram/shape). |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


Coller les formes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeFromId | long | L'ID de la forme qui est collée depuis [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | L'emplacement sur la première forme où coller Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | L'ID de la forme où coller à [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


Coller les formes dans le conteneur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeFromId | long | L'ID de la forme qui est collée depuis [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionIndex | int | L'emplacement sur le premier indice de connexion où coller. |
| shapeToEndConnectionIndex | int | L'emplacement sur l'indice de connexion final où coller. |
| shapeToId | long | L'ID de la forme où coller à [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


Coller les formes dans le conteneur en utilisant le nom de connexion

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeFromId | long | L'ID de la forme qui est collée depuis [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionName | java.lang.String | L'emplacement sur le premier nom de connexion où coller. |
| shapeToEndConnectionName | java.lang.String | L'emplacement sur le nom de connexion final où coller. |
| shapeToId | long | L'ID de la forme où coller à [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


Coller les formes par identifiant de connexion dans le conteneur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeFromId | long | L'ID de la forme qui est collée depuis [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionID | int | L'emplacement sur le premier ID de connexion où coller. |
| shapeToEndConnectionID | int | L'emplacement sur l'ID de connexion final où coller. |
| shapeToId | long | L'ID de la forme où coller à [Shape](../../com.aspose.diagram/shape). |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


Dispose les formes et/ou redirige les connecteurs pour la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Utilisation de [LayoutOptions](../../com.aspose.diagram/layoutoptions) pour configurer les options de mise en page. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


Déplace la page vers un autre emplacement parmi les pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | Indice de la page de destination. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sendBackward(long shapeId) {#sendBackward-long-}
```
public void sendBackward(long shapeId)
```


Déplace une forme, définie par ID, d'une position en arrière dans l'ordre Z.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeId | long | ID de shape.long |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


Déplace une forme, définie par ID, à l'arrière de l'ordre Z.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shapeId | long | ID de shape.long |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


Pour la description de cette propriété, veuillez consulter [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


Pour la description de cette propriété, veuillez consulter [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


Pour la description de cette propriété, veuillez consulter [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


Pour la description de cette propriété, veuillez consulter [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Appliquer un thème prédéfini à cette page

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Appliquer une variante de thème prédéfini quickstyle à cette page

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Appliquer une variante de thème prédéfini à cette page

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


Pour la description de cette propriété, veuillez consulter [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Pour la description de cette propriété, veuillez consulter [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Pour la description de cette propriété, veuillez consulter [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Pour la description de cette propriété, veuillez consulter [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

