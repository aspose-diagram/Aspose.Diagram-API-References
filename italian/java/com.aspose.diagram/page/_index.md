---
title: Page
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene gli elementi che definiscono una pagina nel documento.
type: docs
weight: 260
url: /it/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

Contiene gli elementi che definiscono una pagina nel documento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Page()](#Page--) | Costruttore. |
| [Page(int ID)](#Page-int-) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Crea un controllo Activex. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | Aggiunge un commento a una forma. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | Aggiunge un commento con PinX e PinY definiti. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | Aggiunge un commento a una forma con l'ID della forma. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | Aggiunge una forma creata dal master a una pagina specifica. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | Aggiunge una forma creata dal master sulla pagina con PinX, PinY, larghezza e altezza definiti. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | Aggiunge una forma creata dal master sulla pagina con PinX e PinY definiti. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | Aggiunge testo con PinX e PinY definiti. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | Aggiunge testo con PinX e PinY definiti. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | Applica lo stile per l'intera pagina. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | Spaziatura automatica delle forme |
| [bringForward(long shapeId)](#bringForward-long-) | Porta una forma, definita per ID, avanti di una posizione nell'ordine Z. |
| [bringToFront(long shapeId)](#bringToFront-long-) | Porta una forma, definita per ID, in primo piano nell'ordine Z. |
| [centerDrawing()](#centerDrawing--) | Centra le forme della pagina rispetto all'estensione della pagina. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Collega le forme tramite connettore. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | Collega le forme tramite connettore. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | Collega le forme tramite connettore. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Collega le forme tramite indice del connettore. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | Collega le forme tramite indice del connettore. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | Esegue operazioni definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | Il processo di disegno dell'ellisse. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | Il processo di disegno di una linea singola. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | Il processo di disegno della linea. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | Il processo di disegno della polilinea. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | Il processo di disegno del rettangolo. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | L'ID della pagina di disegno originale che è stata annotata su overlay di markup separati dai revisori del disegno. |
| [getBackPage()](#getBackPage--) | La pagina di sfondo della pagina. |
| [getBackground()](#getBackground--) | Un flag che indica se la pagina è una pagina di sfondo. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Contiene un elemento Connect per ogni connessione tra due forme in un disegno. |
| [getID()](#getID--) | L'ID univoco dell'elemento all'interno del suo elemento genitore. |
| [getName()](#getName--) | Il nome dell'elemento. |
| [getNameU()](#getNameU--) | Il nome universale dell'elemento. |
| [getPageSheet()](#getPageSheet--) | Contiene elementi che definiscono il foglio di pagina per un elemento Pagina o Master. |
| [getPages()](#getPages--) | Raccolta di pagine. |
| [getReviewerID()](#getReviewerID--) | L'ID del revisore associato all'overlay di markup. |
| [getShapes()](#getShapes--) | Raccolta di forme. |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX e ViewCenterY specificano un punto centrale su una pagina che una nuova vista (finestra) assume quando viene aperta inizialmente. |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX e ViewCenterY specificano un punto centrale su una pagina che una nuova vista (finestra) assume quando viene aperta inizialmente. |
| [getViewScale()](#getViewScale--) | Il fattore di ingrandimento predefinito da utilizzare quando viene aperta una nuova vista (finestra) della pagina. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | Incolla la forma al BeginX del Connettore |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | Incolla la forma al EndX del Connettore |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Incolla forme. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | Incolla forme |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | Incolla forme nel contenitore |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | Incolla forme nel contenitore usando il nome della connessione |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | Incolla forme per ID di connessione nel contenitore |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Dispone le forme e/o riorienta i connettori per la pagina. |
| [moveTo(int index)](#moveTo-int-) | Sposta la pagina in un'altra posizione tra le pagine. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | Sposta una forma, definita per ID, indietro di una posizione nell'ordine Z. |
| [sendToBack(long shapeId)](#sendToBack-long-) | Sposta una forma, definita per ID, in fondo all'ordine Z. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | Per la descrizione di questa proprietà, vedere [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | Per la descrizione di questa proprietà, vedere [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | Per la descrizione di questa proprietà, vedere [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | Per la descrizione di questa proprietà, vedere [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Applica un tema predefinito a questa pagina |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Applica una variante di tema predefinito quickstyle a questa pagina |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Applica una variante di tema predefinito a questa pagina |
| [setReviewerID(int value)](#setReviewerID-int-) | Per la descrizione di questa proprietà, vedere [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Per la descrizione di questa proprietà, vedere [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Per la descrizione di questa proprietà, vedere [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Per la descrizione di questa proprietà, vedere [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


Costruttore.

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


Costruttore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Crea un controllo Activex.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int | Il tipo del controllo. |
| pinX | double | Specifica la coordinata x del perno della forma (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno della forma (centro di rotazione) in relazione alla pagina. |
| width | double | Specifica la larghezza della forma in pollici. |
| height | double | Specifica l'altezza della forma in pollici. |

**Returns:**
long -
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


Aggiunge un commento a una forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | Specifica la forma che aggiunge il commento. |
| comment | java.lang.String | Stringa del commento. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


Aggiunge un commento con PinX e PinY definiti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double | Specifica la coordinata x del perno del commento (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno del commento (centro di rotazione) in relazione alla pagina. |
| comment | java.lang.String | Stringa del commento. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


Aggiunge un commento a una forma con l'ID della forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | Stringa del commento. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


Aggiunge una forma creata dal master a una pagina specifica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Nuovo oggetto shape[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Nome del master. |

**Returns:**
long - L'ID univoco della forma all'interno della collezione di forme nella pagina specificata.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| flusso | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| imageStream | java.io.InputStream |  |
| objectDataStream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, String masterName) {#addShape-double-double-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName)
```


Aggiunge una forma creata dal master sulla pagina con PinX, PinY, larghezza e altezza definiti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double | Specifica la coordinata x del perno della forma (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno della forma (centro di rotazione) in relazione alla pagina. |
| width | double | Specifica la larghezza della forma in pollici. |
| height | double | Specifica l'altezza della forma in pollici. |
| masterName | java.lang.String | Nome del master. |

**Returns:**
long - L'ID univoco della forma all'interno della collezione di forme nella pagina specificata.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


Aggiunge una forma creata dal master sulla pagina con PinX e PinY definiti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double | Specifica la coordinata x del perno della forma (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno della forma (centro di rotazione) in relazione alla pagina. |
| masterName | java.lang.String | Nome del master. |

**Returns:**
long - L'ID univoco della forma all'interno della collezione di forme nella pagina specificata.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


Aggiunge testo con PinX e PinY definiti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double | Specifica la coordinata x del perno del testo (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno del testo (centro di rotazione) in relazione alla pagina. |
| width | double |  |
| height | double |  |
| text | java.lang.String | stringa di testo. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


Aggiunge testo con PinX e PinY definiti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double | Specifica la coordinata x del perno del testo (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno del testo (centro di rotazione) in relazione alla pagina. |
| width | double | Specifica la larghezza del testo. |
| height | double | Specifica l'altezza del testo. |
| text | java.lang.String | stringa di testo. |
| fontName | java.lang.String | nome del carattere del testo. |
| fontColor | java.lang.String | colore del carattere del testo. |
| size | double | dimensione del carattere del testo. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


Applica lo stile per l'intera pagina. Il valore predefinito è -1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textStyle | int | ID dello stile del testo. |
| lineStyle | int | ID dello stile della linea. |
| fillStyle | int | ID dello stile di riempimento. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


Spaziatura automatica delle forme

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | Specifica che le forme siano spaziati automaticamente. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


Porta una forma, definita per ID, avanti di una posizione nell'ordine Z.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeId | long | ID di shape.long |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


Porta una forma, definita per ID, in primo piano nell'ordine Z.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeId | long | ID di shape.long |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centra le forme di una pagina rispetto all'estensione della pagina. Il centramento delle forme non cambia la loro posizione relativa tra loro.

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


Collega le forme tramite connettore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | La forma dove inizia il connettore [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | La posizione sulla prima forma dove il connettore sarà collegato Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | La forma dove il connettore termina [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | La posizione sulla seconda forma dove il connettore sarà collegato Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | La forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


Collega le forme tramite connettore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeFromId | long | L'ID della forma dove il connettore inizia [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | La posizione sulla prima forma dove il connettore sarà collegato Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | L'ID della forma dove il connettore termina [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | La posizione sulla seconda forma dove il connettore sarà collegato Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | L'ID della forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


Collega le forme tramite connettore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeFromId | long | L'ID della forma dove il connettore inizia [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | Il nome della connessione sulla prima forma dove il connettore sarà collegato. |
| shapeToId | long | L'ID della forma dove il connettore termina [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | Il nome della connessione sulla seconda forma dove il connettore sarà collegato. |
| connectorId | long | L'ID della forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


Collega le forme tramite indice del connettore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | La forma dove inizia il connettore [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | L'indice della connessione sulla prima forma |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | La forma dove il connettore termina [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | L'indice della connessione sulla seconda forma |
| connector | [Shape](../../com.aspose.diagram/shape) | La forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


Collega le forme tramite indice del connettore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeFromId | long | L'ID della forma dove il connettore inizia [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | L'indice della connessione sulla prima forma |
| shapeToId | long | L'ID della forma dove il connettore termina [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | L'indice della connessione sulla seconda forma |
| connectorId | long | L'ID della forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


Esegue operazioni definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


Il processo di disegno dell'ellisse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double | Specifica la coordinata x del perno della forma (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno della forma (centro di rotazione) in relazione alla pagina. |
| width | double | Specifica la larghezza della forma |
| height | double | Specifica l'altezza della forma |

**Returns:**
long -
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


Il processo di disegno di una linea singola.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginX | double | Specifica la coordinata x iniziale della posizione della forma in relazione alla pagina. |
| beginY | double | Specifica la coordinata y iniziale della posizione della forma in relazione alla pagina. |
| endX | double | Specifica la coordinata x finale della posizione della forma in relazione alla pagina. |
| endY | double | Specifica la coordinata y finale della posizione della forma rispetto alla pagina. |

**Returns:**
long - L'ID univoco della forma all'interno della collezione di forme nella pagina specificata.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


Il processo di disegno della linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double | Specifica la coordinata x del perno della forma (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno della forma (centro di rotazione) in relazione alla pagina. |
| width | double | Specifica la larghezza della forma |
| height | double | Specifica l'altezza della forma |
| xyArray | double[] | Un array di valori x e y alternati che definisce i punti nella nuova forma |

**Returns:**
long - L'ID univoco della forma all'interno della collezione di forme nella pagina specificata.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


Il processo di disegno della polilinea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double | Specifica la coordinata x del perno della forma (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno della forma (centro di rotazione) in relazione alla pagina. |
| width | double | Specifica la larghezza della forma |
| height | double | Specifica l'altezza della forma |
| xyArray | double[] | Un array di valori x e y alternati che definisce i punti nella nuova forma |

**Returns:**
long - L'ID univoco della forma all'interno della collezione di forme nella pagina specificata.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


Il processo di disegno del rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double | Specifica la coordinata x del perno della forma (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno della forma (centro di rotazione) in relazione alla pagina. |
| width | double | Specifica la larghezza della forma |
| height | double | Specifica l'altezza della forma |

**Returns:**
long - L'ID univoco della forma all'interno della collezione di forme nella pagina specificata.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


L'ID della pagina di disegno originale che è stata annotata su overlay di markup separati dai revisori del disegno.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


La pagina di sfondo della pagina.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


Un flag che indica se la pagina è una pagina di sfondo.

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


Contiene un elemento Connect per ogni connessione tra due forme in un disegno.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


L'ID univoco dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Il nome dell'elemento.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Il nome universale dell'elemento.

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Contiene elementi che definiscono il foglio di pagina per un elemento Pagina o Master.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Raccolta di pagine.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


L'ID del revisore associato all'overlay di markup.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Raccolta di forme.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX e ViewCenterY specificano un punto centrale su una pagina che una nuova vista (finestra) assume quando viene aperta inizialmente.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX e ViewCenterY specificano un punto centrale su una pagina che una nuova vista (finestra) assume quando viene aperta inizialmente.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Il fattore di ingrandimento predefinito da utilizzare quando viene aperta una nuova visualizzazione (finestra) della pagina. Per esempio, 1 = 100%; 1.5 = 150%, e così via.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


Incolla la forma al BeginX del Connettore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeFromId | long | L'ID della forma dove il connettore inizia [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Il nome della connessione sulla forma dove verrà collegato il connettore. |
| connectorId | long | L'ID della forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


Incolla la forma al EndX del Connettore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeToId | long | L'ID della forma dove il connettore termina [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Il nome della connessione sulla seconda forma dove il connettore sarà collegato. |
| connectorId | long | L'ID della forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


Incolla forme.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | La forma da cui è incollata [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | La posizione sulla prima forma dove incollare Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | La forma a cui incollare [Shape](../../com.aspose.diagram/shape). |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


Incolla forme

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeFromId | long | L'ID della forma da cui è incollata [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | La posizione sulla prima forma dove incollare Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | L'ID della forma a cui incollare [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


Incolla forme nel contenitore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeFromId | long | L'ID della forma da cui è incollata [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionIndex | int | La posizione sul primo indice di connessione dove incollare. |
| shapeToEndConnectionIndex | int | La posizione sull'indice di connessione finale dove incollare. |
| shapeToId | long | L'ID della forma a cui incollare [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


Incolla forme nel contenitore usando il nome della connessione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeFromId | long | L'ID della forma da cui è incollata [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionName | java.lang.String | La posizione sul primo nome di connessione dove incollare. |
| shapeToEndConnectionName | java.lang.String | La posizione sul nome di connessione finale dove incollare. |
| shapeToId | long | L'ID della forma a cui incollare [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


Incolla forme per ID di connessione nel contenitore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeFromId | long | L'ID della forma da cui è incollata [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionID | int | La posizione sul primo ID di connessione dove incollare. |
| shapeToEndConnectionID | int | La posizione sull'ID di connessione finale dove incollare. |
| shapeToId | long | L'ID della forma a cui incollare [Shape](../../com.aspose.diagram/shape). |

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


Dispone le forme e/o riorienta i connettori per la pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Utilizzando [LayoutOptions](../../com.aspose.diagram/layoutoptions) per configurare le opzioni del layout. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


Sposta la pagina in un'altra posizione tra le pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | Indice della pagina di destinazione. |

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


Sposta una forma, definita per ID, indietro di una posizione nell'ordine Z.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeId | long | ID di shape.long |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


Sposta una forma, definita per ID, in fondo all'ordine Z.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeId | long | ID di shape.long |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


Per la descrizione di questa proprietà, vedere [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


Per la descrizione di questa proprietà, vedere [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


Per la descrizione di questa proprietà, vedere [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


Per la descrizione di questa proprietà, vedere [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Applica un tema predefinito a questa pagina

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Applica una variante di tema predefinito quickstyle a questa pagina

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Applica una variante di tema predefinito a questa pagina

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


Per la descrizione di questa proprietà, vedere [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Per la descrizione di questa proprietà, vedere [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Per la descrizione di questa proprietà, vedere [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Per la descrizione di questa proprietà, vedere [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

