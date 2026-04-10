---
title: Page
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen die een pagina in het document definiëren.
type: docs
weight: 260
url: /nl/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

Bevat elementen die een pagina in het document definiëren.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Page()](#Page--) | Constructor. |
| [Page(int ID)](#Page-int-) | Constructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Maakt een Activex-besturingselement. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | Voegt een opmerking toe aan een vorm. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | Voegt een opmerking toe met gedefinieerde PinX en PinY. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | Voegt een opmerking toe aan een vorm met de ID van de vorm. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | Voegt een vorm toe, gemaakt door master, aan een specifieke pagina. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | Voegt een vorm toe, gemaakt door master, op de pagina met gedefinieerde PinX, PinY, Breedte en Hoogte. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | Voegt een vorm toe, gemaakt door master, op de pagina met gedefinieerde PinX en PinY. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | Voegt tekst toe met gedefinieerde PinX en PinY. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | Voegt tekst toe met gedefinieerde PinX en PinY. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | Past stijl toe voor de volledige pagina. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | Automatisch ruimte tussen vormen |
| [bringForward(long shapeId)](#bringForward-long-) | Brengt een vorm, gedefinieerd door ID, één positie naar voren in de Z-volgorde. |
| [bringToFront(long shapeId)](#bringToFront-long-) | Brengt een vorm, gedefinieerd door ID, naar de voorkant van de Z-volgorde. |
| [centerDrawing()](#centerDrawing--) | Centreert de vormen van een pagina ten opzichte van de omvang van de pagina. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Verbind vormen via connector. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | Verbind vormen via connector. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | Verbind vormen via connector. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Verbind vormen via connector-index. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | Verbind vormen via connector-index. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | Het proces van het tekenen van een ellips. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | Het proces van het tekenen van een enkele lijn. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | Het proces van het tekenen van een lijn. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | Het proces van het tekenen van een polyline. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | Het proces van het tekenen van een rechthoek. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | De ID van de oorspronkelijke tekenpagina die werd gemarkeerd op afzonderlijke markup‑overlays door beoordelaars van de tekening. |
| [getBackPage()](#getBackPage--) | De achtergrondpagina van de pagina. |
| [getBackground()](#getBackground--) | Een vlag die aangeeft of de pagina een achtergrondpagina is. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Bevat een Connect-element voor elke verbinding tussen twee vormen in een tekening. |
| [getID()](#getID--) | De unieke ID van het element binnen het bovenliggende element. |
| [getName()](#getName--) | De naam van het element. |
| [getNameU()](#getNameU--) | De universele naam van het element. |
| [getPageSheet()](#getPageSheet--) | Bevat elementen die het paginablad definiëren voor een Pagina- of Master-element. |
| [getPages()](#getPages--) | Paginasamenstelling. |
| [getReviewerID()](#getReviewerID--) | De ID van de beoordelaar die is gekoppeld aan de markup‑overlay. |
| [getShapes()](#getShapes--) | Vormverzameling. |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX en ViewCenterY geven een middelpunt op een pagina aan dat een nieuw view (venster) aanneemt wanneer het voor het eerst wordt geopend. |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX en ViewCenterY geven een middelpunt op een pagina aan dat een nieuw view (venster) aanneemt wanneer het voor het eerst wordt geopend. |
| [getViewScale()](#getViewScale--) | De standaard vergrotingsfactor die moet worden gebruikt wanneer een nieuw view (venster) van de pagina wordt geopend. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | Vorm plakken op BeginX van Connector |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | Vorm plakken op EndX van Connector |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Vormen plakken. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | Vormen plakken |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | Vormen plakken in container |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | Vormen plakken in container met verbindingsnaam |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | Vormen plakken op verbindings‑ID in container |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Rangschikt de vormen en/of leidt de connectors voor de pagina opnieuw. |
| [moveTo(int index)](#moveTo-int-) | Verplaatst de pagina naar een andere locatie in de pagina's. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | Verplaatst een vorm, gedefinieerd door ID, één positie terug in de z‑volgorde. |
| [sendToBack(long shapeId)](#sendToBack-long-) | Verplaatst een vorm, gedefinieerd door ID, naar de achterkant van de z‑volgorde. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | Voor de beschrijving van deze eigenschap, zie [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | Voor de beschrijving van deze eigenschap, zie [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | Voor de beschrijving van deze eigenschap, zie [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | Voor de beschrijving van deze eigenschap, zie [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Pas een vooraf ingesteld thema toe op deze pagina |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Pas een vooraf ingestelde themavariant quickstyle toe op deze pagina |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Pas een vooraf ingestelde themavariant toe op deze pagina |
| [setReviewerID(int value)](#setReviewerID-int-) | Voor de beschrijving van deze eigenschap, zie [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Voor de beschrijving van deze eigenschap, zie [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Voor de beschrijving van deze eigenschap, zie [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Voor de beschrijving van deze eigenschap, zie [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Maakt een Activex-besturingselement.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Het type van het besturingselement. |
| pinX | double | Specificeert de x-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| width | double | Specificeert de breedte van de vorm in inches. |
| height | double | Specificeert de hoogte van de vorm in inches. |

**Returns:**
long - 
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


Voegt een opmerking toe aan een vorm.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | Specificeert de vorm die een opmerking toevoegt. |
| comment | java.lang.String | String van de opmerking. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


Voegt een opmerking toe met gedefinieerde PinX en PinY.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double | Specificeert de x-coördinaat van de pin van de opmerking (rotatiecentrum) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de opmerking (rotatiecentrum) ten opzichte van de pagina. |
| comment | java.lang.String | String van de opmerking. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


Voegt een opmerking toe aan een vorm met de ID van de vorm.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | String van de opmerking. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


Voegt een vorm toe, gemaakt door master, aan een specifieke pagina.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Nieuw vormobject[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Naam van de master. |

**Returns:**
long - De unieke ID van de vorm binnen de vormverzameling op de opgegeven pagina.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| stream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Voegt een vorm toe, gemaakt door master, op de pagina met gedefinieerde PinX, PinY, Breedte en Hoogte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double | Specificeert de x-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| width | double | Specificeert de breedte van de vorm in inches. |
| height | double | Specificeert de hoogte van de vorm in inches. |
| masterName | java.lang.String | Naam van de master. |

**Returns:**
long - De unieke ID van de vorm binnen de vormverzameling op de opgegeven pagina.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


Voegt een vorm toe, gemaakt door master, op de pagina met gedefinieerde PinX en PinY.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double | Specificeert de x-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| masterName | java.lang.String | Naam van de master. |

**Returns:**
long - De unieke ID van de vorm binnen de vormverzameling op de opgegeven pagina.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


Voegt tekst toe met gedefinieerde PinX en PinY.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double | Specificeert de x-coördinaat van de pin van de tekst (centrum van rotatie) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de tekst (centrum van rotatie) ten opzichte van de pagina. |
| width | double |  |
| height | double |  |
| text | java.lang.String | tekstreeks. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


Voegt tekst toe met gedefinieerde PinX en PinY.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double | Specificeert de x-coördinaat van de pin van de tekst (centrum van rotatie) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de tekst (centrum van rotatie) ten opzichte van de pagina. |
| width | double | Specificeert de breedte van de tekst. |
| height | double | Specificeert de hoogte van de tekst. |
| text | java.lang.String | tekstreeks. |
| fontName | java.lang.String | naam van het tekstlettertype. |
| fontColor | java.lang.String | kleur van het tekstlettertype. |
| size | double | grootte van het tekstlettertype. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


Past stijl toe voor de volledige pagina. Standaardwaarde is -1.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| textStyle | int | tekststijl-id. |
| lineStyle | int | lijnstijl-id. |
| fillStyle | int | vullingsstijl-id. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


Automatisch ruimte tussen vormen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | Specificeert dat de vormen automatisch worden gespreid. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


Brengt een vorm, gedefinieerd door ID, één positie naar voren in de Z-volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeId | long | ID van shape.long |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


Brengt een vorm, gedefinieerd door ID, naar de voorkant van de Z-volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeId | long | ID van shape.long |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centreert de vormen van een pagina ten opzichte van de omvang van de pagina. Het centreren van vormen verandert hun positie ten opzichte van elkaar niet.

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


Verbind vormen via connector.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | De vorm waar de connector begint [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | De locatie op de eerste vorm waar de connector wordt verbonden Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | De vorm waar de connector eindigt [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | De locatie op de tweede vorm waar de connector wordt verbonden Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | De vorm met type Dynamische connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


Verbind vormen via connector.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeFromId | long | De ID van de vorm waar de connector begint [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | De locatie op de eerste vorm waar de connector wordt verbonden Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | De ID van de vorm waar de connector eindigt [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | De locatie op de tweede vorm waar de connector wordt verbonden Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | De ID van de vorm met type Dynamische connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


Verbind vormen via connector.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeFromId | long | De ID van de vorm waar de connector begint [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | De verbindingsnaam op de eerste vorm waar de connector wordt verbonden. |
| shapeToId | long | De ID van de vorm waar de connector eindigt [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | De verbindingsnaam op de tweede vorm waar de connector wordt verbonden. |
| connectorId | long | De ID van de vorm met type Dynamische connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


Verbind vormen via connector-index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | De vorm waar de connector begint [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | De index van de verbinding op de eerste vorm |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | De vorm waar de connector eindigt [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | De index van de verbinding op de tweede vorm |
| connector | [Shape](../../com.aspose.diagram/shape) | De vorm met type Dynamische connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


Verbind vormen via connector-index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeFromId | long | De ID van de vorm waar de connector begint [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | De index van de verbinding op de eerste vorm |
| shapeToId | long | De ID van de vorm waar de connector eindigt [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | De index van de verbinding op de tweede vorm |
| connectorId | long | De ID van de vorm met type Dynamische connector [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


Voert door de applicatie gedefinieerde taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet-beheerde bronnen.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


Het proces van het tekenen van een ellips.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double | Specificeert de x-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| width | double | Specificeert de breedte van de vorm |
| height | double | Specificeert de hoogte van de vorm |

**Returns:**
long - 
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


Het proces van het tekenen van een enkele lijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginX | double | Specificeert de begin x-coördinaat van de positie van de vorm ten opzichte van de pagina. |
| beginY | double | Specificeert de begin y-coördinaat van de positie van de vorm ten opzichte van de pagina. |
| endX | double | Specificeert de eind x-coördinaat van de positie van de vorm ten opzichte van de pagina. |
| endY | double | Specificeert de eind-y-coördinaat van de positie van de vorm ten opzichte van de pagina. |

**Returns:**
long - De unieke ID van de vorm binnen de vormverzameling op de opgegeven pagina.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


Het proces van het tekenen van een lijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double | Specificeert de x-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| width | double | Specificeert de breedte van de vorm |
| height | double | Specificeert de hoogte van de vorm |
| xyArray | double[] | Een array van afwisselende x- en y-waarden die punten in de nieuwe vorm definieert |

**Returns:**
long - De unieke ID van de vorm binnen de vormverzameling op de opgegeven pagina.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


Het proces van het tekenen van een polyline.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double | Specificeert de x-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| width | double | Specificeert de breedte van de vorm |
| height | double | Specificeert de hoogte van de vorm |
| xyArray | double[] | Een array van afwisselende x- en y-waarden die punten in de nieuwe vorm definieert |

**Returns:**
long - De unieke ID van de vorm binnen de vormverzameling op de opgegeven pagina.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


Het proces van het tekenen van een rechthoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pinX | double | Specificeert de x-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| pinY | double | Specificeert de y-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de pagina. |
| width | double | Specificeert de breedte van de vorm |
| height | double | Specificeert de hoogte van de vorm |

**Returns:**
long - De unieke ID van de vorm binnen de vormverzameling op de opgegeven pagina.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


De ID van de oorspronkelijke tekenpagina die werd gemarkeerd op afzonderlijke markup‑overlays door beoordelaars van de tekening.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


De achtergrondpagina van de pagina.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


Een vlag die aangeeft of de pagina een achtergrondpagina is.

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


Bevat een Connect-element voor elke verbinding tussen twee vormen in een tekening.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


De unieke ID van het element binnen het bovenliggende element.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


De naam van het element.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


De universele naam van het element.

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Bevat elementen die het paginablad definiëren voor een Pagina- of Master-element.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Paginasamenstelling.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


De ID van de beoordelaar die is gekoppeld aan de markup‑overlay.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Vormverzameling.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX en ViewCenterY geven een middelpunt op een pagina aan dat een nieuw view (venster) aanneemt wanneer het voor het eerst wordt geopend.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX en ViewCenterY geven een middelpunt op een pagina aan dat een nieuw view (venster) aanneemt wanneer het voor het eerst wordt geopend.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


De standaard vergrotingsfactor die wordt gebruikt wanneer een nieuw overzicht (venster) van de pagina wordt geopend. Bijvoorbeeld, 1 = 100%; 1.5 = 150%, en zo verder.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


Vorm plakken op BeginX van Connector

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeFromId | long | De ID van de vorm waar de connector begint [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | De verbindingsnaam op de vorm waar de connector aan wordt gekoppeld. |
| connectorId | long | De ID van de vorm met type Dynamische connector [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


Vorm plakken op EndX van Connector

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeToId | long | De ID van de vorm waar de connector eindigt [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | De verbindingsnaam op de tweede vorm waar de connector wordt verbonden. |
| connectorId | long | De ID van de vorm met type Dynamische connector [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


Vormen plakken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | De vorm die wordt geplakt vanaf [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | De locatie op de eerste vorm waar Aspose.Diagram.Manipulation.ConnectionPointPlace moet worden geplakt. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | De vorm waarnaar moet worden geplakt [Shape](../../com.aspose.diagram/shape). |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


Vormen plakken

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeFromId | long | De ID van de vorm die wordt geplakt vanaf [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | De locatie op de eerste vorm waar Aspose.Diagram.Manipulation.ConnectionPointPlace moet worden geplakt. |
| shapeToId | long | De ID van de vorm waarnaar moet worden geplakt [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


Vormen plakken in container

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeFromId | long | De ID van de vorm die wordt geplakt vanaf [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionIndex | int | De locatie op de eerste verbindingsindex waar moet worden geplakt. |
| shapeToEndConnectionIndex | int | De locatie op de eindverbindingsindex waar moet worden geplakt. |
| shapeToId | long | De ID van de vorm waarnaar moet worden geplakt [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


Vormen plakken in container met verbindingsnaam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeFromId | long | De ID van de vorm die wordt geplakt vanaf [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionName | java.lang.String | De locatie op de eerste verbindingsnaam waar moet worden geplakt. |
| shapeToEndConnectionName | java.lang.String | De locatie op de eindverbindingsnaam waar moet worden geplakt. |
| shapeToId | long | De ID van de vorm waarnaar moet worden geplakt [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


Vormen plakken op verbindings‑ID in container

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeFromId | long | De ID van de vorm die wordt geplakt vanaf [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionID | int | De locatie op de eerste verbindings-id waar moet worden geplakt. |
| shapeToEndConnectionID | int | De locatie op de eindverbindings-id waar moet worden geplakt. |
| shapeToId | long | De ID van de vorm waarnaar moet worden geplakt [Shape](../../com.aspose.diagram/shape). |

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


Rangschikt de vormen en/of leidt de connectors voor de pagina opnieuw.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Gebruik de [LayoutOptions](../../com.aspose.diagram/layoutoptions) om de opties van de lay-out te configureren. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


Verplaatst de pagina naar een andere locatie in de pagina's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Doelpagina-index. |

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


Verplaatst een vorm, gedefinieerd door ID, één positie terug in de z‑volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeId | long | ID van shape.long |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


Verplaatst een vorm, gedefinieerd door ID, naar de achterkant van de z‑volgorde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeId | long | ID van shape.long |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


Voor de beschrijving van deze eigenschap, zie [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


Voor de beschrijving van deze eigenschap, zie [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


Voor de beschrijving van deze eigenschap, zie [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


Voor de beschrijving van deze eigenschap, zie [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Pas een vooraf ingesteld thema toe op deze pagina

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Pas een vooraf ingestelde themavariant quickstyle toe op deze pagina

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Pas een vooraf ingestelde themavariant toe op deze pagina

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


Voor de beschrijving van deze eigenschap, zie [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Voor de beschrijving van deze eigenschap, zie [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Voor de beschrijving van deze eigenschap, zie [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Voor de beschrijving van deze eigenschap, zie [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

