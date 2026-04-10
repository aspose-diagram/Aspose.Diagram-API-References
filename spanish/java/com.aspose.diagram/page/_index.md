---
title: Página
second_title: Referencia de API de Aspose.Diagram para Java
description: Contiene elementos que definen una página en el documento.
type: docs
weight: 260
url: /es/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

Contiene elementos que definen una página en el documento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Page()](#Page--) | Constructor. |
| [Page(int ID)](#Page-int-) | Constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Crea un control Activex. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | Añade un comentario a una forma. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | Añade un comentario con PinX y PinY definidos. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | Añade un comentario a una forma con el id de la forma. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | Añade una forma creada por el maestro a una página específica. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | Añade una forma creada por el maestro en la página con PinX, PinY, Width y Height definidos. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | Añade una forma creada por el maestro en la página con PinX y PinY definidos. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | Añade texto con PinX y PinY definidos. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | Añade texto con PinX y PinY definidos. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | Aplica estilo para la página completa. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | Espaciado automático de formas |
| [bringForward(long shapeId)](#bringForward-long-) | Mueve una forma, definida por ID, una posición hacia adelante en el orden Z. |
| [bringToFront(long shapeId)](#bringToFront-long-) | Mueve una forma, definida por ID, al frente del orden Z. |
| [centerDrawing()](#centerDrawing--) | Centra las formas de una página con respecto a la extensión de la página. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Conecta formas mediante un conector. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | Conecta formas mediante un conector. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | Conecta formas mediante un conector. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Conecta formas mediante el índice del conector. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | Conecta formas mediante el índice del conector. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | Realiza tareas definidas por la aplicación asociadas con la liberación, el lanzamiento o el restablecimiento de recursos no administrados. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | El proceso de dibujar una elipse. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | El proceso de dibujar una sola línea. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | El proceso de dibujar una línea. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | El proceso de dibujar una polilínea. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | El proceso de dibujar un rectángulo. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | El ID de la página de dibujo original que fue anotada en superposiciones de anotaciones separadas por revisores del dibujo. |
| [getBackPage()](#getBackPage--) | La página de fondo de la página. |
| [getBackground()](#getBackground--) | Una bandera que indica si la página es una página de fondo. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Contiene un elemento Connect para cada conexión entre dos formas en un dibujo. |
| [getID()](#getID--) | El ID único del elemento dentro de su elemento padre. |
| [getName()](#getName--) | El nombre del elemento. |
| [getNameU()](#getNameU--) | El nombre universal del elemento. |
| [getPageSheet()](#getPageSheet--) | Contiene elementos que definen la hoja de página para un elemento Página o Maestro. |
| [getPages()](#getPages--) | Colección de páginas. |
| [getReviewerID()](#getReviewerID--) | El ID del revisor asociado con la superposición de anotaciones. |
| [getShapes()](#getShapes--) | Colección de formas. |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX y ViewCenterY especifican un punto central en una página que una nueva vista (ventana) asume cuando se abre inicialmente. |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX y ViewCenterY especifican un punto central en una página que una nueva vista (ventana) asume cuando se abre inicialmente. |
| [getViewScale()](#getViewScale--) | El factor de magnificación predeterminado a usar cuando se abre una nueva vista (ventana) de la página. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | Unir forma al BeginX del Conector |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | Unir forma al EndX del Conector |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Unir formas. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | Unir formas |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | Unir formas en el contenedor |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | Unir formas en el contenedor usando el nombre de conexión |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | Unir formas por ID de conexión en el contenedor |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Distribuye las formas y/o redirige los conectores para la página. |
| [moveTo(int index)](#moveTo-int-) | Mueve la página a otra ubicación en las páginas. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | Mueve una forma,definida por ID, una posición atrás en el orden Z. |
| [sendToBack(long shapeId)](#sendToBack-long-) | Mueve una forma,definida por ID, al fondo del orden Z. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | Para la descripción de esta propiedad, consulte [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | Para la descripción de esta propiedad, consulte [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | Para la descripción de esta propiedad, consulte [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | Para la descripción de esta propiedad, consulte [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Aplicar un tema preestablecido a esta página |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Aplicar una variante de tema preestablecido estilo rápido a esta página |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Aplicar una variante de tema preestablecido a esta página |
| [setReviewerID(int value)](#setReviewerID-int-) | Para la descripción de esta propiedad, consulte [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Para la descripción de esta propiedad, consulte [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Para la descripción de esta propiedad, consulte [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Para la descripción de esta propiedad, consulte [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


Constructor.

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


Constructor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Crea un control Activex.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | int | El tipo del control. |
| pinX | double | Especifica la coordenada x del pin de la forma (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del pin de la forma (centro de rotación) en relación con la página. |
| width | double | Especifica el ancho de la forma en pulgadas. |
| height | double | Especifica la altura de la forma en pulgadas. |

**Returns:**
long -
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


Añade un comentario a una forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | Especifica la forma que está añadiendo el comentario. |
| comment | java.lang.String | Cadena del comentario. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


Añade un comentario con PinX y PinY definidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double | Especifica la coordenada x del pin del comentario (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del pin del comentario (centro de rotación) en relación con la página. |
| comment | java.lang.String | Cadena del comentario. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


Añade un comentario a una forma con el id de la forma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | Cadena del comentario. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


Añade una forma creada por el maestro a una página específica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Nuevo objeto de forma[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Nombre del maestro. |

**Returns:**
long - El ID único de la forma dentro de la colección de formas en la página especificada.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| flujo | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Añade una forma creada por el maestro en la página con PinX, PinY, Width y Height definidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double | Especifica la coordenada x del pin de la forma (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del pin de la forma (centro de rotación) en relación con la página. |
| width | double | Especifica el ancho de la forma en pulgadas. |
| height | double | Especifica la altura de la forma en pulgadas. |
| masterName | java.lang.String | Nombre del maestro. |

**Returns:**
long - El ID único de la forma dentro de la colección de formas en la página especificada.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


Añade una forma creada por el maestro en la página con PinX y PinY definidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double | Especifica la coordenada x del pin de la forma (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del pin de la forma (centro de rotación) en relación con la página. |
| masterName | java.lang.String | Nombre del maestro. |

**Returns:**
long - El ID único de la forma dentro de la colección de formas en la página especificada.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


Añade texto con PinX y PinY definidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double | Especifica la coordenada x del punto de anclaje del texto (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del punto de anclaje del texto (centro de rotación) en relación con la página. |
| width | double |  |
| height | double |  |
| text | java.lang.String | cadena de texto. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


Añade texto con PinX y PinY definidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double | Especifica la coordenada x del punto de anclaje del texto (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del punto de anclaje del texto (centro de rotación) en relación con la página. |
| width | double | Especifica el ancho del texto. |
| height | double | Especifica la altura del texto. |
| text | java.lang.String | cadena de texto. |
| fontName | java.lang.String | nombre de la fuente del texto. |
| fontColor | java.lang.String | color de la fuente del texto. |
| size | double | tamaño de la fuente del texto. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


Aplica estilo para la página completa. El valor predeterminado es -1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textStyle | int | identificador de estilo de texto. |
| lineStyle | int | identificador de estilo de línea. |
| fillStyle | int | identificador de estilo de relleno. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


Espaciado automático de formas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | Especifica que las formas se espacien automáticamente. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


Mueve una forma, definida por ID, una posición hacia adelante en el orden Z.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeId | long | ID de shape.long |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


Mueve una forma, definida por ID, al frente del orden Z.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeId | long | ID de shape.long |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centra las formas de una página respecto a la extensión de la página. Centrar las formas no cambia su posición relativa entre sí.

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


Conecta formas mediante un conector.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | La forma donde comienza el conector [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | La ubicación en la primera forma donde se conectará el conector Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | La forma donde termina el conector [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | La ubicación en la segunda forma donde se conectará el conector Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | La forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


Conecta formas mediante un conector.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeFromId | long | El ID de la forma donde comienza el conector [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | La ubicación en la primera forma donde se conectará el conector Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | El ID de la forma donde termina el conector [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | La ubicación en la segunda forma donde se conectará el conector Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | El ID de la forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


Conecta formas mediante un conector.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeFromId | long | El ID de la forma donde comienza el conector [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | El nombre de la conexión en la primera forma donde se conectará el conector. |
| shapeToId | long | El ID de la forma donde termina el conector [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | El nombre de la conexión en la segunda forma donde se conectará el conector. |
| connectorId | long | El ID de la forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


Conecta formas mediante el índice del conector.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | La forma donde comienza el conector [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | El índice de la conexión en la primera forma |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | La forma donde termina el conector [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | El índice de la conexión en la segunda forma |
| connector | [Shape](../../com.aspose.diagram/shape) | La forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


Conecta formas mediante el índice del conector.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeFromId | long | El ID de la forma donde comienza el conector [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | El índice de la conexión en la primera forma |
| shapeToId | long | El ID de la forma donde termina el conector [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | El índice de la conexión en la segunda forma |
| connectorId | long | El ID de la forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


Realiza tareas definidas por la aplicación asociadas con la liberación, el lanzamiento o el restablecimiento de recursos no administrados.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


El proceso de dibujar una elipse.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double | Especifica la coordenada x del pin de la forma (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del pin de la forma (centro de rotación) en relación con la página. |
| width | double | Especifica el ancho de la forma |
| height | double | Especifica la altura de la forma |

**Returns:**
long -
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


El proceso de dibujar una sola línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginX | double | Especifica la coordenada x inicial de la posición de la forma en relación con la página. |
| beginY | double | Especifica la coordenada y inicial de la posición de la forma en relación con la página. |
| endX | double | Especifica la coordenada x final de la posición de la forma en relación con la página. |
| endY | double | Especifica la coordenada y final de la posición de la forma en relación con la página. |

**Returns:**
long - El ID único de la forma dentro de la colección de formas en la página especificada.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


El proceso de dibujar una línea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double | Especifica la coordenada x del pin de la forma (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del pin de la forma (centro de rotación) en relación con la página. |
| width | double | Especifica el ancho de la forma |
| height | double | Especifica la altura de la forma |
| xyArray | double[] | Una matriz de valores x e y alternados que define los puntos en la nueva forma |

**Returns:**
long - El ID único de la forma dentro de la colección de formas en la página especificada.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


El proceso de dibujar una polilínea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double | Especifica la coordenada x del pin de la forma (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del pin de la forma (centro de rotación) en relación con la página. |
| width | double | Especifica el ancho de la forma |
| height | double | Especifica la altura de la forma |
| xyArray | double[] | Una matriz de valores x e y alternados que define los puntos en la nueva forma |

**Returns:**
long - El ID único de la forma dentro de la colección de formas en la página especificada.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


El proceso de dibujar un rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pinX | double | Especifica la coordenada x del pin de la forma (centro de rotación) en relación con la página. |
| pinY | double | Especifica la coordenada y del pin de la forma (centro de rotación) en relación con la página. |
| width | double | Especifica el ancho de la forma |
| height | double | Especifica la altura de la forma |

**Returns:**
long - El ID único de la forma dentro de la colección de formas en la página especificada.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


El ID de la página de dibujo original que fue anotada en superposiciones de anotaciones separadas por revisores del dibujo.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


La página de fondo de la página.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


Una bandera que indica si la página es una página de fondo.

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


Contiene un elemento Connect para cada conexión entre dos formas en un dibujo.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


El ID único del elemento dentro de su elemento padre.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


El nombre del elemento.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


El nombre universal del elemento.

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Contiene elementos que definen la hoja de página para un elemento Página o Maestro.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Colección de páginas.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


El ID del revisor asociado con la superposición de anotaciones.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Colección de formas.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX y ViewCenterY especifican un punto central en una página que una nueva vista (ventana) asume cuando se abre inicialmente.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX y ViewCenterY especifican un punto central en una página que una nueva vista (ventana) asume cuando se abre inicialmente.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


El factor de ampliación predeterminado que se usa cuando se abre una nueva vista (ventana) de la página. Por ejemplo, 1 = 100%; 1.5 = 150%, etc.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


Unir forma al BeginX del Conector

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeFromId | long | El ID de la forma donde comienza el conector [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | El nombre de la conexión en la forma donde se conectará el conector. |
| connectorId | long | El ID de la forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


Unir forma al EndX del Conector

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeToId | long | El ID de la forma donde termina el conector [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | El nombre de la conexión en la segunda forma donde se conectará el conector. |
| connectorId | long | El ID de la forma con tipo Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


Unir formas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | La forma que se pega desde [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | La ubicación en la primera forma donde pegar Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | La forma donde pegar a [Shape](../../com.aspose.diagram/shape). |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


Unir formas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeFromId | long | El ID de la forma que se pega desde [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | La ubicación en la primera forma donde pegar Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | El ID de la forma donde pegar a [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


Unir formas en el contenedor

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeFromId | long | El ID de la forma que se pega desde [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionIndex | int | La ubicación en el índice de conexión inicial donde pegar. |
| shapeToEndConnectionIndex | int | La ubicación en el índice de conexión final donde pegar. |
| shapeToId | long | El ID de la forma donde pegar a [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


Unir formas en el contenedor usando el nombre de conexión

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeFromId | long | El ID de la forma que se pega desde [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionName | java.lang.String | La ubicación en el nombre de conexión inicial donde pegar. |
| shapeToEndConnectionName | java.lang.String | La ubicación en el nombre de conexión final donde pegar. |
| shapeToId | long | El ID de la forma donde pegar a [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


Unir formas por ID de conexión en el contenedor

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeFromId | long | El ID de la forma que se pega desde [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionID | int | La ubicación en el ID de conexión inicial donde pegar. |
| shapeToEndConnectionID | int | La ubicación en el ID de conexión final donde pegar. |
| shapeToId | long | El ID de la forma donde pegar a [Shape](../../com.aspose.diagram/shape). |

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


Distribuye las formas y/o redirige los conectores para la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Usando [LayoutOptions](../../com.aspose.diagram/layoutoptions) para configurar las opciones de diseño. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


Mueve la página a otra ubicación en las páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Índice de página de destino. |

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


Mueve una forma,definida por ID, una posición atrás en el orden Z.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeId | long | ID de shape.long |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


Mueve una forma,definida por ID, al fondo del orden Z.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeId | long | ID de shape.long |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


Para la descripción de esta propiedad, consulte [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


Para la descripción de esta propiedad, consulte [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


Para la descripción de esta propiedad, consulte [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Para la descripción de esta propiedad, consulte [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Para la descripción de esta propiedad, consulte [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Para la descripción de esta propiedad, consulte [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


Para la descripción de esta propiedad, consulte [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Aplicar un tema preestablecido a esta página

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Aplicar una variante de tema preestablecido estilo rápido a esta página

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Aplicar una variante de tema preestablecido a esta página

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


Para la descripción de esta propiedad, consulte [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Para la descripción de esta propiedad, consulte [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Para la descripción de esta propiedad, consulte [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Para la descripción de esta propiedad, consulte [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

