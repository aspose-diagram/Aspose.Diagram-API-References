---
title: Seite
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die eine Seite im Dokument definieren.
type: docs
weight: 260
url: /de/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

Enthält Elemente, die eine Seite im Dokument definieren.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Page()](#Page--) | Konstruktor. |
| [Page(int ID)](#Page-int-) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Erstellt ein Activex-Steuerelement. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | Fügt einem Shape einen Kommentar hinzu. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | Fügt einen Kommentar mit definierten PinX und PinY hinzu. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | Fügt einem Shape einen Kommentar mit der Shape-ID hinzu. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | Fügt ein vom Master erstelltes Shape zu einer bestimmten Seite hinzu. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | Fügt ein vom Master erstelltes Shape auf einer Seite mit definierten PinX, PinY, Breite und Höhe hinzu. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | Fügt ein vom Master erstelltes Shape auf einer Seite mit definierten PinX und PinY hinzu. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | Fügt Text mit definierten PinX und PinY hinzu. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | Fügt Text mit definierten PinX und PinY hinzu. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | Wendet Stil für die gesamte Seite an. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | Automatischer Abstand zwischen Shapes. |
| [bringForward(long shapeId)](#bringForward-long-) | Bringt ein Shape, definiert durch ID, eine Position im Z-Order nach vorne. |
| [bringToFront(long shapeId)](#bringToFront-long-) | Bringt ein Shape, definiert durch ID, an die Spitze des Z-Order. |
| [centerDrawing()](#centerDrawing--) | Zentriert die Shapes einer Seite relativ zum Umfang der Seite. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Verbinde Shapes über einen Connector. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | Verbinde Shapes über einen Connector. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | Verbinde Shapes über einen Connector. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Verbinde Shapes über den Connector-Index. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | Verbinde Shapes über den Connector-Index. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | Der Vorgang des Zeichnens einer Ellipse. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | Der Vorgang des Zeichnens einer einzelnen Linie. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | Der Vorgang des Zeichnens einer Linie. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | Der Vorgang des Zeichnens einer Polylinie. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | Der Vorgang des Zeichnens eines Rechtecks. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | Die ID der ursprünglichen Zeichenblattseite, die von Prüfern der Zeichnung in separaten Markup-Overlays markiert wurde. |
| [getBackPage()](#getBackPage--) | Die Hintergrundseite der Seite. |
| [getBackground()](#getBackground--) | Ein Flag, das angibt, ob die Seite eine Hintergrundseite ist. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Enthält ein Connect-Element für jede Verbindung zwischen zwei Formen in einer Zeichnung. |
| [getID()](#getID--) | Die eindeutige ID des Elements innerhalb seines übergeordneten Elements. |
| [getName()](#getName--) | Der Name des Elements. |
| [getNameU()](#getNameU--) | Der universelle Name des Elements. |
| [getPageSheet()](#getPageSheet--) | Enthält Elemente, die das Seitenblatt für ein Seiten‑ oder Master‑Element definieren. |
| [getPages()](#getPages--) | Seitensammlung. |
| [getReviewerID()](#getReviewerID--) | Die ID des Prüfers, der mit dem Markup-Overlay verknüpft ist. |
| [getShapes()](#getShapes--) | Formensammlung. |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX und ViewCenterY geben einen Mittelpunkt auf einer Seite an, den eine neue Ansicht (Fenster) beim ersten Öffnen annimmt. |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX und ViewCenterY geben einen Mittelpunkt auf einer Seite an, den eine neue Ansicht (Fenster) beim ersten Öffnen annimmt. |
| [getViewScale()](#getViewScale--) | Der standardmäßige Vergrößerungsfaktor, der verwendet wird, wenn eine neue Ansicht (Fenster) der Seite geöffnet wird. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | Form an Connector's BeginX anheften |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | Form an Connector's EndX anheften |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Formen anheften. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | Formen anheften |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | Formen im Container anheften |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | Formen im Container mithilfe des Verbindungsnamens anheften |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | Formen im Container nach Verbindungs-ID anheften |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Ordnet die Formen an und/oder leitet die Connectoren für die Seite um. |
| [moveTo(int index)](#moveTo-int-) | Verschiebt die Seite an einen anderen Ort in den Seiten. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | Verschiebt eine Form, definiert durch ID, um eine Position im Z-Order zurück. |
| [sendToBack(long shapeId)](#sendToBack-long-) | Verschiebt eine Form, definiert durch ID, an das Ende des Z-Order. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Ein vordefiniertes Design auf dieser Seite anwenden |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Ein vordefinierter Designvarianten‑Quickstyle auf dieser Seite anwenden |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Eine vordefinierte Designvariante auf dieser Seite anwenden |
| [setReviewerID(int value)](#setReviewerID-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


Konstruktor.

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


Konstruktor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Erstellt ein Activex-Steuerelement.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int | Der Typ des Steuerelements. |
| pinX | double | Gibt die x‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| pinY | double | Gibt die y‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| Breite | double | Gibt die Breite der Form in Zoll an. |
| Höhe | double | Gibt die Höhe der Form in Zoll an. |

**Returns:**
long -
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


Fügt einem Shape einen Kommentar hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | Gibt die Form an, die den Kommentar hinzufügt. |
| comment | java.lang.String | Zeichenkette des Kommentars. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


Fügt einen Kommentar mit definierten PinX und PinY hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double | Gibt die x‑Koordinate des Pins des Kommentars (Rotationszentrum) in Bezug auf die Seite an. |
| pinY | double | Gibt die y‑Koordinate des Pins des Kommentars (Rotationszentrum) in Bezug auf die Seite an. |
| comment | java.lang.String | Zeichenkette des Kommentars. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


Fügt einem Shape einen Kommentar mit der Shape-ID hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | Zeichenkette des Kommentars. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


Fügt ein vom Master erstelltes Shape zu einer bestimmten Seite hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Neues Formobjekt[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Name des Masters. |

**Returns:**
long - Die eindeutige ID der Form innerhalb der Formensammlung auf der angegebenen Seite.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| Breite | double |  |
| Höhe | double |  |
| stream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| Breite | double |  |
| Höhe | double |  |
| imageStream | java.io.InputStream |  |
| objectDataStream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, String masterName) {#addShape-double-double-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName)
```


Fügt ein vom Master erstelltes Shape auf einer Seite mit definierten PinX, PinY, Breite und Höhe hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double | Gibt die x‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| pinY | double | Gibt die y‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| Breite | double | Gibt die Breite der Form in Zoll an. |
| Höhe | double | Gibt die Höhe der Form in Zoll an. |
| masterName | java.lang.String | Name des Masters. |

**Returns:**
long - Die eindeutige ID der Form innerhalb der Formensammlung auf der angegebenen Seite.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


Fügt ein vom Master erstelltes Shape auf einer Seite mit definierten PinX und PinY hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double | Gibt die x‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| pinY | double | Gibt die y‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| masterName | java.lang.String | Name des Masters. |

**Returns:**
long - Die eindeutige ID der Form innerhalb der Formensammlung auf der angegebenen Seite.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


Fügt Text mit definierten PinX und PinY hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| Breite | double |  |
| Höhe | double |  |
| text | java.lang.String | text string. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


Fügt Text mit definierten PinX und PinY hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| Breite | double | Specifies the width of the text. |
| Höhe | double | Specifies the height of the text. |
| text | java.lang.String | text string. |
| fontName | java.lang.String | text font name. |
| fontColor | java.lang.String | text font color. |
| size | double | text font size. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


Applies style for full page. Default value is -1.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textStyle | int | text Style id. |
| lineStyle | int | line Style id. |
| fillStyle | int | fill Style id. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


Automatischer Abstand zwischen Shapes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | Specifies the shapes be auto spaced. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


Bringt ein Shape, definiert durch ID, eine Position im Z-Order nach vorne.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


Bringt ein Shape, definiert durch ID, an die Spitze des Z-Order.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centers a page's shapes with respect to the extent of the page. Centering shapes does not change their position relative to each other.

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


Verbinde Shapes über einen Connector.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | The shape where the connector begins [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | Der Ort auf der ersten Form, an dem der Connector verbunden wird Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Die Form, in der der Connector endet [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Der Ort auf der zweiten Form, an dem der Connector verbunden wird Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | Die Form mit dem Typ Dynamischer Connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


Verbinde Shapes über einen Connector.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeFromId | long | Die ID der Form, in der der Connector beginnt [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | Der Ort auf der ersten Form, an dem der Connector verbunden wird Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | Die ID der Form, in der der Connector endet [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Der Ort auf der zweiten Form, an dem der Connector verbunden wird Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | Die ID der Form mit dem Typ Dynamischer Connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


Verbinde Shapes über einen Connector.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeFromId | long | Die ID der Form, in der der Connector beginnt [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | Der Verbindungsname auf der ersten Form, an dem der Connector verbunden wird. |
| shapeToId | long | Die ID der Form, in der der Connector endet [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | Der Verbindungsname auf der zweiten Form, an dem der Connector verbunden wird. |
| connectorId | long | Die ID der Form mit dem Typ Dynamischer Connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


Verbinde Shapes über den Connector-Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | The shape where the connector begins [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | Der Index der Verbindung auf der ersten Form |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Die Form, in der der Connector endet [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | Der Index der Verbindung auf der zweiten Form |
| connector | [Shape](../../com.aspose.diagram/shape) | Die Form mit dem Typ Dynamischer Connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


Verbinde Shapes über den Connector-Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeFromId | long | Die ID der Form, in der der Connector beginnt [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | Der Index der Verbindung auf der ersten Form |
| shapeToId | long | Die ID der Form, in der der Connector endet [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | Der Index der Verbindung auf der zweiten Form |
| connectorId | long | Die ID der Form mit dem Typ Dynamischer Connector [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


Der Vorgang des Zeichnens einer Ellipse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double | Gibt die x‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| pinY | double | Gibt die y‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| Breite | double | Gibt die Breite der Form an |
| Höhe | double | Gibt die Höhe der Form an |

**Returns:**
long -
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


Der Vorgang des Zeichnens einer einzelnen Linie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginX | double | Gibt die Anfangs-x-Koordinate der Position der Form in Bezug auf die Seite an. |
| beginY | double | Gibt die Anfangs-y-Koordinate der Position der Form in Bezug auf die Seite an. |
| endX | double | Gibt die End-x-Koordinate der Position der Form in Bezug auf die Seite an. |
| endY | double | Gibt die End‑Y‑Koordinate der Position der Form in Bezug auf die Seite an. |

**Returns:**
long - Die eindeutige ID der Form innerhalb der Formensammlung auf der angegebenen Seite.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


Der Vorgang des Zeichnens einer Linie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double | Gibt die x‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| pinY | double | Gibt die y‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| Breite | double | Gibt die Breite der Form an |
| Höhe | double | Gibt die Höhe der Form an |
| xyArray | double[] | Ein Array aus abwechselnden x‑ und y‑Werten, das Punkte in der neuen Form definiert. |

**Returns:**
long - Die eindeutige ID der Form innerhalb der Formensammlung auf der angegebenen Seite.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


Der Vorgang des Zeichnens einer Polylinie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double | Gibt die x‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| pinY | double | Gibt die y‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| Breite | double | Gibt die Breite der Form an |
| Höhe | double | Gibt die Höhe der Form an |
| xyArray | double[] | Ein Array aus abwechselnden x‑ und y‑Werten, das Punkte in der neuen Form definiert. |

**Returns:**
long - Die eindeutige ID der Form innerhalb der Formensammlung auf der angegebenen Seite.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


Der Vorgang des Zeichnens eines Rechtecks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pinX | double | Gibt die x‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| pinY | double | Gibt die y‑Koordinate des Pins der Form (Rotationszentrum) in Bezug auf die Seite an. |
| Breite | double | Gibt die Breite der Form an |
| Höhe | double | Gibt die Höhe der Form an |

**Returns:**
long - Die eindeutige ID der Form innerhalb der Formensammlung auf der angegebenen Seite.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


Die ID der ursprünglichen Zeichenblattseite, die von Prüfern der Zeichnung in separaten Markup-Overlays markiert wurde.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


Die Hintergrundseite der Seite.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


Ein Flag, das angibt, ob die Seite eine Hintergrundseite ist.

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


Enthält ein Connect-Element für jede Verbindung zwischen zwei Formen in einer Zeichnung.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


Die eindeutige ID des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Der Name des Elements.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Der universelle Name des Elements.

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Enthält Elemente, die das Seitenblatt für ein Seiten‑ oder Master‑Element definieren.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Seitensammlung.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


Die ID des Prüfers, der mit dem Markup-Overlay verknüpft ist.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Formensammlung.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX und ViewCenterY geben einen Mittelpunkt auf einer Seite an, den eine neue Ansicht (Fenster) beim ersten Öffnen annimmt.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX und ViewCenterY geben einen Mittelpunkt auf einer Seite an, den eine neue Ansicht (Fenster) beim ersten Öffnen annimmt.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Der standardmäßige Vergrößerungsfaktor, der verwendet wird, wenn eine neue Ansicht (Fenster) der Seite geöffnet wird. Zum Beispiel 1 = 100 %; 1,5 = 150 % und so weiter.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


Form an Connector's BeginX anheften

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeFromId | long | Die ID der Form, in der der Connector beginnt [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Der Verbindungsname an der Form, an der der Connector angeschlossen wird. |
| connectorId | long | Die ID der Form mit dem Typ Dynamischer Connector [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


Form an Connector's EndX anheften

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeToId | long | Die ID der Form, in der der Connector endet [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Der Verbindungsname auf der zweiten Form, an dem der Connector verbunden wird. |
| connectorId | long | Die ID der Form mit dem Typ Dynamischer Connector [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


Formen anheften.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | Die Form, die von [Shape](../../com.aspose.diagram/shape) geklebt wird. |
| placeTo | int | Der Ort auf der ersten Form, an dem Aspose.Diagram.Manipulation.ConnectionPointPlace geklebt wird. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Die Form, an die [Shape](../../com.aspose.diagram/shape) geklebt wird. |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


Formen anheften

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeFromId | long | Die ID der Form, die von [Shape](../../com.aspose.diagram/shape) geklebt wird. |
| placeTo | int | Der Ort auf der ersten Form, an dem Aspose.Diagram.Manipulation.ConnectionPointPlace geklebt wird. |
| shapeToId | long | Die ID der Form, an die [Shape](../../com.aspose.diagram/shape) geklebt wird. |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


Formen im Container anheften

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeFromId | long | Die ID der Form, die von [Shape](../../com.aspose.diagram/shape) geklebt wird. |
| shapeToBeginConnectionIndex | int | Der Ort am ersten Verbindungsindex, an dem geklebt wird. |
| shapeToEndConnectionIndex | int | Der Ort am Endverbindungsindex, an dem geklebt wird. |
| shapeToId | long | Die ID der Form, an die [Shape](../../com.aspose.diagram/shape) geklebt wird. |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


Formen im Container mithilfe des Verbindungsnamens anheften

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeFromId | long | Die ID der Form, die von [Shape](../../com.aspose.diagram/shape) geklebt wird. |
| shapeToBeginConnectionName | java.lang.String | Der Ort am ersten Verbindungsnamen, an dem geklebt wird. |
| shapeToEndConnectionName | java.lang.String | Der Ort am Endverbindungsnamen, an dem geklebt wird. |
| shapeToId | long | Die ID der Form, an die [Shape](../../com.aspose.diagram/shape) geklebt wird. |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


Formen im Container nach Verbindungs-ID anheften

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeFromId | long | Die ID der Form, die von [Shape](../../com.aspose.diagram/shape) geklebt wird. |
| shapeToBeginConnectionID | int | Der Ort an der ersten Verbindungs-ID, an dem geklebt wird. |
| shapeToEndConnectionID | int | Der Ort an der Endverbindungs-ID, an dem geklebt wird. |
| shapeToId | long | Die ID der Form, an die [Shape](../../com.aspose.diagram/shape) geklebt wird. |

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


Ordnet die Formen an und/oder leitet die Connectoren für die Seite um.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Verwendung von [LayoutOptions](../../com.aspose.diagram/layoutoptions), um Layout‑Optionen zu konfigurieren. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


Verschiebt die Seite an einen anderen Ort in den Seiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Zielseitenindex. |

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


Verschiebt eine Form, definiert durch ID, um eine Position im Z-Order zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


Verschiebt eine Form, definiert durch ID, an das Ende des Z-Order.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Ein vordefiniertes Design auf dieser Seite anwenden

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Ein vordefinierter Designvarianten‑Quickstyle auf dieser Seite anwenden

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Eine vordefinierte Designvariante auf dieser Seite anwenden

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

