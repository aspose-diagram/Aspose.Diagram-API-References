---
title: Sida
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element som definierar en sida i dokumentet.
type: docs
weight: 260
url: /sv/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

Innehåller element som definierar en sida i dokumentet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Page()](#Page--) | Konstruktor. |
| [Page(int ID)](#Page-int-) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Skapar en Activex-kontroll. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | Lägger till en kommentar till en form. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | Lägger till en kommentar med definierade PinX och PinY. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | Lägger till en kommentar till en form med formens id. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | Lägger till en form skapad av master till en specifik sida. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | Lägger till en form skapad av master på sidan med definierade PinX, PinY, bredd och höjd. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | Lägger till en form skapad av master på sidan med definierade PinX och PinY. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | Lägger till text med definierade PinX och PinY. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | Lägger till text med definierade PinX och PinY. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | Tillämpar stil för hela sidan. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | Automatiskt mellanrum mellan former. |
| [bringForward(long shapeId)](#bringForward-long-) | Flyttar en form, definierad av ID, fram ett steg i z-ordningen. |
| [bringToFront(long shapeId)](#bringToFront-long-) | Flyttar en form, definierad av ID, till fronten av z-ordningen. |
| [centerDrawing()](#centerDrawing--) | Centrerar sidans former i förhållande till sidans omfång. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Koppla samman former via anslutning. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | Koppla samman former via anslutning. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | Koppla samman former via anslutning. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Koppla samman former via anslutningsindex. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | Koppla samman former via anslutningsindex. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | Processen för att rita en ellips. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | Processen för att rita en enkel linje. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | Processen för att rita en linje. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | Processen för att rita en polylinje. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | Processen för att rita en rektangel. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | ID för den ursprungliga ritningssidan som markerades på separata markup‑lager av ritningens granskare. |
| [getBackPage()](#getBackPage--) | Sidans bakgrundssida. |
| [getBackground()](#getBackground--) | En flagga som indikerar om sidan är en bakgrundssida. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Innehåller ett Connect-element för varje anslutning mellan två former i en ritning. |
| [getID()](#getID--) | Det unika ID:t för elementet inom dess överordnade element. |
| [getName()](#getName--) | Elementets namn. |
| [getNameU()](#getNameU--) | Det universella namnet för elementet. |
| [getPageSheet()](#getPageSheet--) | Innehåller element som definierar sidbladet för ett Page- eller Master-element. |
| [getPages()](#getPages--) | Sidcollection. |
| [getReviewerID()](#getReviewerID--) | ID för den granskare som är associerad med markup‑lagret. |
| [getShapes()](#getShapes--) | Formsamling. |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX och ViewCenterY anger en mittpunkt på en sida som en ny vy (fönster) antar när den öppnas initialt. |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX och ViewCenterY anger en mittpunkt på en sida som en ny vy (fönster) antar när den öppnas initialt. |
| [getViewScale()](#getViewScale--) | Standardförstoringsfaktor att använda när en ny vy (fönster) av sidan öppnas. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | Fäst form till Connectorns BeginX |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | Fäst form till Connectorns EndX |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Fäst former. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | Fäst former |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | Fäst former i behållare |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | Fäst former i behållare med anslutningsnamn |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | Fäst former efter anslutnings‑ID i behållare |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Lägger ut formerna och/eller omdirigerar anslutningarna för sidan. |
| [moveTo(int index)](#moveTo-int-) | Flyttar sidan till en annan plats bland sidorna. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | Flyttar en form, definierad av ID, ett steg bakåt i z‑ordningen. |
| [sendToBack(long shapeId)](#sendToBack-long-) | Flyttar en form, definierad av ID, till slutet av z‑ordningen. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | För beskrivningen av denna egenskap, se [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | För beskrivningen av denna egenskap, se [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | För beskrivningen av denna egenskap, se [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | För beskrivningen av denna egenskap, se [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Tillämpa ett förinställt tema på den här sidan |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Tillämpa en förinställd temavariant snabbstil på den här sidan |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Tillämpa en förinställd temavariant på den här sidan |
| [setReviewerID(int value)](#setReviewerID-int-) | För beskrivningen av den här egenskapen, se [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | För beskrivningen av den här egenskapen, se [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | För beskrivningen av den här egenskapen, se [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | För beskrivningen av den här egenskapen, se [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Skapar en Activex-kontroll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int | Typen av kontrollen. |
| pinX | double | Anger x-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| bredd | double | Anger figurens bredd i tum. |
| höjd | double | Anger figurens höjd i tum. |

**Returns:**
long - 
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


Lägger till en kommentar till en form.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | Anger figuren som lägger till kommentaren. |
| kommentar | java.lang.String | Kommentarssträng. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


Lägger till en kommentar med definierade PinX och PinY.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double | Anger x-koordinaten för kommentarens pinne (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för kommentarens pinne (rotationscentrum) i förhållande till sidan. |
| kommentar | java.lang.String | Kommentarssträng. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


Lägger till en kommentar till en form med formens id.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeID | long |  |
| kommentar | java.lang.String | Kommentarssträng. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


Lägger till en form skapad av master till en specifik sida.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Nytt figurobjekt[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Mästarens namn. |

**Returns:**
long - Det unika ID:t för figuren inom figurkollektionen på den angivna sidan.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| bredd | double |  |
| höjd | double |  |
| ström | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| bredd | double |  |
| höjd | double |  |
| imageStream | java.io.InputStream |  |
| objectDataStream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, String masterName) {#addShape-double-double-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName)
```


Lägger till en form skapad av master på sidan med definierade PinX, PinY, bredd och höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double | Anger x-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| bredd | double | Anger figurens bredd i tum. |
| höjd | double | Anger figurens höjd i tum. |
| masterName | java.lang.String | Mästarens namn. |

**Returns:**
long - Det unika ID:t för figuren inom figurkollektionen på den angivna sidan.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


Lägger till en form skapad av master på sidan med definierade PinX och PinY.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double | Anger x-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| masterName | java.lang.String | Mästarens namn. |

**Returns:**
long - Det unika ID:t för figuren inom figurkollektionen på den angivna sidan.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


Lägger till text med definierade PinX och PinY.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double | Anger x-koordinaten för textens fästpunkt (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för textens fästpunkt (rotationscentrum) i förhållande till sidan. |
| bredd | double |  |
| höjd | double |  |
| text | java.lang.String | textsträng. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


Lägger till text med definierade PinX och PinY.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double | Anger x-koordinaten för textens fästpunkt (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för textens fästpunkt (rotationscentrum) i förhållande till sidan. |
| bredd | double | Anger bredden på texten. |
| höjd | double | Anger höjden på texten. |
| text | java.lang.String | textsträng. |
| fontName | java.lang.String | textens teckensnittsnamn. |
| fontColor | java.lang.String | textens teckensnittsfärg. |
| size | double | textens teckensnittsstorlek. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


Tillämpar stil för hela sidan. Standardvärdet är -1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textStyle | int | textstil‑id. |
| lineStyle | int | linjestil‑id. |
| fillStyle | int | fyllningsstil‑id. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


Automatiskt mellanrum mellan former.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | Anger att formerna ska placeras automatiskt med jämna mellanrum. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


Flyttar en form, definierad av ID, fram ett steg i z-ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


Flyttar en form, definierad av ID, till fronten av z-ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centrerar en sidas former i förhållande till sidans omfång. Att centrera former ändrar inte deras position i förhållande till varandra.

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


Koppla samman former via anslutning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | Formen där anslutaren börjar [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | Platsen på den första formen där anslutningen kommer att anslutas Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Formen där anslutningen slutar [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Platsen på den andra formen där anslutningen kommer att anslutas Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | Formen med typen Dynamisk anslutning [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


Koppla samman former via anslutning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeFromId | long | ID för formen där anslutningen börjar [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | Platsen på den första formen där anslutningen kommer att anslutas Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | ID för formen där anslutningen slutar [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Platsen på den andra formen där anslutningen kommer att anslutas Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | ID för formen med typen Dynamisk anslutning [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


Koppla samman former via anslutning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeFromId | long | ID för formen där anslutningen börjar [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | Anslutningsnamnet på den första formen där anslutningen kommer att anslutas. |
| shapeToId | long | ID för formen där anslutningen slutar [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | Anslutningsnamnet på den andra formen där anslutningen kommer att anslutas. |
| connectorId | long | ID för formen med typen Dynamisk anslutning [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


Koppla samman former via anslutningsindex.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | Formen där anslutaren börjar [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | Indexet för anslutningen på den första formen |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Formen där anslutningen slutar [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | indexet för anslutningen på den andra formen |
| connector | [Shape](../../com.aspose.diagram/shape) | Formen med typen Dynamisk anslutning [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


Koppla samman former via anslutningsindex.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeFromId | long | ID för formen där anslutningen börjar [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | Indexet för anslutningen på den första formen |
| shapeToId | long | ID för formen där anslutningen slutar [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | indexet för anslutningen på den andra formen |
| connectorId | long | ID för formen med typen Dynamisk anslutning [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


Utför applikationsdefinierade uppgifter som är relaterade till att frigöra, släppa eller återställa ohanterade resurser.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


Processen för att rita en ellips.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double | Anger x-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| bredd | double | Anger bredden på formen |
| höjd | double | Anger höjden på formen |

**Returns:**
long - 
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


Processen för att rita en enkel linje.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginX | double | Anger den inledande x-koordinaten för formens position i förhållande till sidan. |
| beginY | double | Anger den inledande y-koordinaten för formens position i förhållande till sidan. |
| endX | double | Anger den avslutande x-koordinaten för formens position i förhållande till sidan. |
| endY | double | Anger den slutliga y-koordinaten för figurens position i förhållande till sidan. |

**Returns:**
long - Det unika ID:t för figuren inom figurkollektionen på den angivna sidan.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


Processen för att rita en linje.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double | Anger x-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| bredd | double | Anger bredden på formen |
| höjd | double | Anger höjden på formen |
| xyArray | double[] | En array med alternerande x- och y-värden som definierar punkter i den nya figuren |

**Returns:**
long - Det unika ID:t för figuren inom figurkollektionen på den angivna sidan.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


Processen för att rita en polylinje.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double | Anger x-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| bredd | double | Anger bredden på formen |
| höjd | double | Anger höjden på formen |
| xyArray | double[] | En array med alternerande x- och y-värden som definierar punkter i den nya figuren |

**Returns:**
long - Det unika ID:t för figuren inom figurkollektionen på den angivna sidan.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


Processen för att rita en rektangel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pinX | double | Anger x-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| pinY | double | Anger y-koordinaten för figurens pinne (rotationscentrum) i förhållande till sidan. |
| bredd | double | Anger bredden på formen |
| höjd | double | Anger höjden på formen |

**Returns:**
long - Det unika ID:t för figuren inom figurkollektionen på den angivna sidan.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


ID för den ursprungliga ritningssidan som markerades på separata markup‑lager av ritningens granskare.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


Sidans bakgrundssida.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


En flagga som indikerar om sidan är en bakgrundssida.

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


Innehåller ett Connect-element för varje anslutning mellan två former i en ritning.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


Det unika ID:t för elementet inom dess överordnade element.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Elementets namn.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Det universella namnet för elementet.

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Innehåller element som definierar sidbladet för ett Page- eller Master-element.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Sidcollection.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


ID för den granskare som är associerad med markup‑lagret.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Formsamling.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX och ViewCenterY anger en mittpunkt på en sida som en ny vy (fönster) antar när den öppnas initialt.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX och ViewCenterY anger en mittpunkt på en sida som en ny vy (fönster) antar när den öppnas initialt.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Standardförstoringsfaktorn som ska användas när en ny vy (fönster) av sidan öppnas. Till exempel, 1 = 100 %; 1,5 = 150 %, osv.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


Fäst form till Connectorns BeginX

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeFromId | long | ID för formen där anslutningen börjar [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Anslutningsnamnet på figuren där anslutaren kommer att kopplas. |
| connectorId | long | ID för formen med typen Dynamisk anslutning [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


Fäst form till Connectorns EndX

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeToId | long | ID för formen där anslutningen slutar [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Anslutningsnamnet på den andra formen där anslutningen kommer att anslutas. |
| connectorId | long | ID för formen med typen Dynamisk anslutning [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


Fäst former.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | Figuren som är limmad från [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Platsen på den första figuren där Aspose.Diagram.Manipulation.ConnectionPointPlace ska limmas. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Figuren där man ska limma till [Shape](../../com.aspose.diagram/shape). |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


Fäst former

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeFromId | long | ID för figuren som är limmad från [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Platsen på den första figuren där Aspose.Diagram.Manipulation.ConnectionPointPlace ska limmas. |
| shapeToId | long | ID för figuren där man ska limma till [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


Fäst former i behållare

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeFromId | long | ID för figuren som är limmad från [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionIndex | int | Platsen på det första anslutningsindexet där man ska limma. |
| shapeToEndConnectionIndex | int | Platsen på det sista anslutningsindexet där man ska limma. |
| shapeToId | long | ID för figuren där man ska limma till [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


Fäst former i behållare med anslutningsnamn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeFromId | long | ID för figuren som är limmad från [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionName | java.lang.String | Platsen på det första anslutningsnamnet där man ska limma. |
| shapeToEndConnectionName | java.lang.String | Platsen på det sista anslutningsnamnet där man ska limma. |
| shapeToId | long | ID för figuren där man ska limma till [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


Fäst former efter anslutnings‑ID i behållare

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeFromId | long | ID för figuren som är limmad från [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionID | int | Platsen på det första anslutnings-ID:t där man ska limma. |
| shapeToEndConnectionID | int | Platsen på det sista anslutnings-ID:t där man ska limma. |
| shapeToId | long | ID för figuren där man ska limma till [Shape](../../com.aspose.diagram/shape). |

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


Lägger ut formerna och/eller omdirigerar anslutningarna för sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Använd [LayoutOptions](../../com.aspose.diagram/layoutoptions) för att konfigurera layoutalternativ. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


Flyttar sidan till en annan plats bland sidorna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Destinationssidans index. |

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


Flyttar en form, definierad av ID, ett steg bakåt i z‑ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


Flyttar en form, definierad av ID, till slutet av z‑ordningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


För beskrivningen av denna egenskap, se [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


För beskrivningen av denna egenskap, se [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


För beskrivningen av denna egenskap, se [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


För beskrivningen av denna egenskap, se [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Tillämpa ett förinställt tema på den här sidan

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Tillämpa en förinställd temavariant snabbstil på den här sidan

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Tillämpa en förinställd temavariant på den här sidan

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


För beskrivningen av den här egenskapen, se [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


För beskrivningen av den här egenskapen, se [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


För beskrivningen av den här egenskapen, se [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


För beskrivningen av den här egenskapen, se [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

