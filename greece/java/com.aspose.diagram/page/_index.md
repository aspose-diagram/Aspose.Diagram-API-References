---
title: Page
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία που ορίζουν μια σελίδα στο έγγραφο.
type: docs
weight: 260
url: /el/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

Περιέχει στοιχεία που ορίζουν μια σελίδα στο έγγραφο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Page()](#Page--) | Κατασκευαστής. |
| [Page(int ID)](#Page-int-) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Creates an Activex Control. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | Adds comment to a shape. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | Adds comment with defined PinX and PinY. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | Adds comment to a shape with shape's id. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | Adds shape created by master to specific page. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | Adds shape created by master on page with defined PinX and PinY. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | Adds Text with defined PinX and PinY. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | Adds Text with defined PinX and PinY. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | Applies style for full page. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | Auto space shapes |
| [bringForward(long shapeId)](#bringForward-long-) | Brings a shape,defined by ID, forward one position in the z-order. |
| [bringToFront(long shapeId)](#bringToFront-long-) | Brings a shape,defined by ID, to the front of the z-order. |
| [centerDrawing()](#centerDrawing--) | Centers a page's shapes with respect to the extent of the page. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Connect shapes via connector. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | Connect shapes via connector. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | Connect shapes via connector. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Connect shapes via connector index. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | Connect shapes via connector index. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | Εκτελεί εργασίες που ορίζονται από την εφαρμογή, σχετικές με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | The process of drawing Ellipse. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | The process of drawing a single line. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | The process of drawing line. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | The process of drawing Polyline. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | The process of drawing rectangle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | Το αναγνωριστικό της αρχικής σελίδας σχεδίου που σημειώθηκε σε ξεχωριστές επικάλυψεις σημειώσεων από τους αξιολογητές του σχεδίου. |
| [getBackPage()](#getBackPage--) | Η σελίδα φόντου της σελίδας. |
| [getBackground()](#getBackground--) | Μια σημαία που υποδεικνύει εάν η σελίδα είναι σελίδα φόντου. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Περιέχει ένα στοιχείο Connect για κάθε σύνδεση μεταξύ δύο σχημάτων σε ένα σχέδιο. |
| [getID()](#getID--) | Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο. |
| [getName()](#getName--) | Το όνομα του στοιχείου. |
| [getNameU()](#getNameU--) | Το καθολικό όνομα του στοιχείου. |
| [getPageSheet()](#getPageSheet--) | Περιέχει στοιχεία που ορίζουν το φύλλο σελίδας για ένα στοιχείο Σελίδα ή Κύριο. |
| [getPages()](#getPages--) | Συλλογή σελίδων. |
| [getReviewerID()](#getReviewerID--) | Το αναγνωριστικό του αξιολογητή που συνδέεται με την επικάλυψη σημειώσεων. |
| [getShapes()](#getShapes--) | Συλλογή σχημάτων. |
| [getViewCenterX()](#getViewCenterX--) | Τα ViewCenterX και ViewCenterY καθορίζουν ένα κεντρικό σημείο σε μια σελίδα που υποθέτει μια νέα προβολή (παράθυρο) όταν ανοίγει αρχικά. |
| [getViewCenterY()](#getViewCenterY--) | Τα ViewCenterX και ViewCenterY καθορίζουν ένα κεντρικό σημείο σε μια σελίδα που υποθέτει μια νέα προβολή (παράθυρο) όταν ανοίγει αρχικά. |
| [getViewScale()](#getViewScale--) | Ο προεπιλεγμένος συντελεστής μεγέθυνσης που χρησιμοποιείται όταν ανοίγεται μια νέα προβολή (παράθυρο) της σελίδας. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | Συνδέστε το σχήμα με το BeginX του Connector. |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | Συνδέστε το σχήμα με το EndX του Connector. |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Συνδέστε σχήματα. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | Συνδέστε σχήματα |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | Συνδέστε σχήματα στο container |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | Συνδέστε σχήματα στο container χρησιμοποιώντας το όνομα σύνδεσης |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | Συνδέστε σχήματα με το αναγνωριστικό σύνδεσης στο container |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Διατάσσει τα σχήματα και/ή επαναδρομολογεί τους συνδέσμους για τη σελίδα. |
| [moveTo(int index)](#moveTo-int-) | Μετακινεί τη σελίδα σε άλλη θέση στις σελίδες. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | Μετακινεί ένα σχήμα, ορισμένο με ID, μία θέση πίσω στη σειρά z. |
| [sendToBack(long shapeId)](#sendToBack-long-) | Μετακινεί ένα σχήμα, ορισμένο με ID, στο τέλος της σειράς z. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Εφαρμόστε ένα προεπιλεγμένο θέμα σε αυτή τη σελίδα |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Εφαρμόστε μια προεπιλεγμένη παραλλαγή θέματος quickstyle σε αυτή τη σελίδα |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Εφαρμόστε μια προεπιλεγμένη παραλλαγή θέματος σε αυτή τη σελίδα |
| [setReviewerID(int value)](#setReviewerID-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


Κατασκευαστής.

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


Κατασκευαστής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Creates an Activex Control.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | int | Ο τύπος του ελέγχου. |
| pinX | double | Καθορίζει τη συντεταγμένη x του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| pinY | double | Καθορίζει τη συντεταγμένη y του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| width | double | Καθορίζει το πλάτος του σχήματος σε ίντσες. |
| height | double | Καθορίζει το ύψος του σχήματος σε ίντσες. |

**Returns:**
long - 
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


Adds comment to a shape.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | Καθορίζει το σχήμα που προσθέτει το σχόλιο. |
| comment | java.lang.String | Συμβολοσειρά σχολίου. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


Adds comment with defined PinX and PinY.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pinX | double | Καθορίζει τη συντεταγμένη x του ακροδέκτη του σχολίου (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| pinY | double | Καθορίζει τη συντεταγμένη y του ακροδέκτη του σχολίου (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| comment | java.lang.String | Συμβολοσειρά σχολίου. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


Adds comment to a shape with shape's id.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | Συμβολοσειρά σχολίου. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


Adds shape created by master to specific page.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Νέο αντικείμενο σχήματος[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Όνομα του Master. |

**Returns:**
long - Το μοναδικό ID του σχήματος μέσα στη συλλογή σχημάτων στη συγκεκριμένη σελίδα.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
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


Adds shape created by master on page with defined PinX,PinY,Width and Height.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pinX | double | Καθορίζει τη συντεταγμένη x του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| pinY | double | Καθορίζει τη συντεταγμένη y του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| width | double | Καθορίζει το πλάτος του σχήματος σε ίντσες. |
| height | double | Καθορίζει το ύψος του σχήματος σε ίντσες. |
| masterName | java.lang.String | Όνομα του Master. |

**Returns:**
long - Το μοναδικό ID του σχήματος μέσα στη συλλογή σχημάτων στη συγκεκριμένη σελίδα.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


Adds shape created by master on page with defined PinX and PinY.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pinX | double | Καθορίζει τη συντεταγμένη x του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| pinY | double | Καθορίζει τη συντεταγμένη y του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| masterName | java.lang.String | Όνομα του Master. |

**Returns:**
long - Το μοναδικό ID του σχήματος μέσα στη συλλογή σχημάτων στη συγκεκριμένη σελίδα.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


Adds Text with defined PinX and PinY.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| width | double |  |
| height | double |  |
| text | java.lang.String | text string. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


Adds Text with defined PinX and PinY.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| width | double | Specifies the width of the text. |
| height | double | Specifies the height of the text. |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| textStyle | int | text Style id. |
| lineStyle | int | line Style id. |
| fillStyle | int | fill Style id. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


Auto space shapes

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | Specifies the shapes be auto spaced. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


Brings a shape,defined by ID, forward one position in the z-order.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


Brings a shape,defined by ID, to the front of the z-order.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Connect shapes via connector.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | The shape where the connector begins [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | Η θέση στο πρώτο σχήμα όπου θα συνδεθεί ο σύνδεσμος Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Το σχήμα όπου λήγει ο σύνδεσμος [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Η θέση στο δεύτερο σχήμα όπου θα συνδεθεί ο σύνδεσμος Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | Το σχήμα με τύπο Δυναμικός σύνδεσμος [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


Connect shapes via connector.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeFromId | long | Το αναγνωριστικό του σχήματος όπου αρχίζει ο σύνδεσμος [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | Η θέση στο πρώτο σχήμα όπου θα συνδεθεί ο σύνδεσμος Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | Το αναγνωριστικό του σχήματος όπου λήγει ο σύνδεσμος [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Η θέση στο δεύτερο σχήμα όπου θα συνδεθεί ο σύνδεσμος Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | Το αναγνωριστικό του σχήματος με τύπο Δυναμικός σύνδεσμος [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


Connect shapes via connector.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeFromId | long | Το αναγνωριστικό του σχήματος όπου αρχίζει ο σύνδεσμος [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | Το όνομα σύνδεσης στο πρώτο σχήμα όπου θα συνδεθεί ο σύνδεσμος. |
| shapeToId | long | Το αναγνωριστικό του σχήματος όπου λήγει ο σύνδεσμος [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | Το όνομα σύνδεσης στο δεύτερο σχήμα όπου θα συνδεθεί ο σύνδεσμος. |
| connectorId | long | Το αναγνωριστικό του σχήματος με τύπο Δυναμικός σύνδεσμος [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


Connect shapes via connector index.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | The shape where the connector begins [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | Ο δείκτης της σύνδεσης στο πρώτο σχήμα |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Το σχήμα όπου λήγει ο σύνδεσμος [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | Ο δείκτης της σύνδεσης στο δεύτερο σχήμα |
| connector | [Shape](../../com.aspose.diagram/shape) | Το σχήμα με τύπο Δυναμικός σύνδεσμος [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


Connect shapes via connector index.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeFromId | long | Το αναγνωριστικό του σχήματος όπου αρχίζει ο σύνδεσμος [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | Ο δείκτης της σύνδεσης στο πρώτο σχήμα |
| shapeToId | long | Το αναγνωριστικό του σχήματος όπου λήγει ο σύνδεσμος [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | Ο δείκτης της σύνδεσης στο δεύτερο σχήμα |
| connectorId | long | Το αναγνωριστικό του σχήματος με τύπο Δυναμικός σύνδεσμος [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


Εκτελεί εργασίες που ορίζονται από την εφαρμογή, σχετικές με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


The process of drawing Ellipse.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pinX | double | Καθορίζει τη συντεταγμένη x του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| pinY | double | Καθορίζει τη συντεταγμένη y του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| width | double | Καθορίζει το πλάτος του σχήματος |
| height | double | Καθορίζει το ύψος του σχήματος |

**Returns:**
long - 
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


The process of drawing a single line.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginX | double | Καθορίζει τη αρχική συντεταγμένη x της θέσης του σχήματος σε σχέση με τη σελίδα. |
| beginY | double | Καθορίζει τη αρχική συντεταγμένη y της θέσης του σχήματος σε σχέση με τη σελίδα. |
| endX | double | Καθορίζει τη τελική συντεταγμένη x της θέσης του σχήματος σε σχέση με τη σελίδα. |
| endY | double | Καθορίζει τη τελική συντεταγμένη y της θέσης του σχήματος σε σχέση με τη σελίδα. |

**Returns:**
long - Το μοναδικό ID του σχήματος μέσα στη συλλογή σχημάτων στη συγκεκριμένη σελίδα.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


The process of drawing line.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pinX | double | Καθορίζει τη συντεταγμένη x του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| pinY | double | Καθορίζει τη συντεταγμένη y του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| width | double | Καθορίζει το πλάτος του σχήματος |
| height | double | Καθορίζει το ύψος του σχήματος |
| xyArray | double[] | Ένας πίνακας εναλλασσόμενων τιμών x και y που ορίζει σημεία στο νέο σχήμα |

**Returns:**
long - Το μοναδικό ID του σχήματος μέσα στη συλλογή σχημάτων στη συγκεκριμένη σελίδα.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


The process of drawing Polyline.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pinX | double | Καθορίζει τη συντεταγμένη x του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| pinY | double | Καθορίζει τη συντεταγμένη y του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| width | double | Καθορίζει το πλάτος του σχήματος |
| height | double | Καθορίζει το ύψος του σχήματος |
| xyArray | double[] | Ένας πίνακας εναλλασσόμενων τιμών x και y που ορίζει σημεία στο νέο σχήμα |

**Returns:**
long - Το μοναδικό ID του σχήματος μέσα στη συλλογή σχημάτων στη συγκεκριμένη σελίδα.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


The process of drawing rectangle.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pinX | double | Καθορίζει τη συντεταγμένη x του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| pinY | double | Καθορίζει τη συντεταγμένη y του ακροδέκτη του σχήματος (κέντρο περιστροφής) σε σχέση με τη σελίδα. |
| width | double | Καθορίζει το πλάτος του σχήματος |
| height | double | Καθορίζει το ύψος του σχήματος |

**Returns:**
long - Το μοναδικό ID του σχήματος μέσα στη συλλογή σχημάτων στη συγκεκριμένη σελίδα.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


Το αναγνωριστικό της αρχικής σελίδας σχεδίου που σημειώθηκε σε ξεχωριστές επικάλυψεις σημειώσεων από τους αξιολογητές του σχεδίου.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


Η σελίδα φόντου της σελίδας.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


Μια σημαία που υποδεικνύει εάν η σελίδα είναι σελίδα φόντου.

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


Περιέχει ένα στοιχείο Connect για κάθε σύνδεση μεταξύ δύο σχημάτων σε ένα σχέδιο.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Το όνομα του στοιχείου.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Το καθολικό όνομα του στοιχείου.

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Περιέχει στοιχεία που ορίζουν το φύλλο σελίδας για ένα στοιχείο Σελίδα ή Κύριο.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Συλλογή σελίδων.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


Το αναγνωριστικό του αξιολογητή που συνδέεται με την επικάλυψη σημειώσεων.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Συλλογή σχημάτων.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


Τα ViewCenterX και ViewCenterY καθορίζουν ένα κεντρικό σημείο σε μια σελίδα που υποθέτει μια νέα προβολή (παράθυρο) όταν ανοίγει αρχικά.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


Τα ViewCenterX και ViewCenterY καθορίζουν ένα κεντρικό σημείο σε μια σελίδα που υποθέτει μια νέα προβολή (παράθυρο) όταν ανοίγει αρχικά.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Ο προεπιλεγμένος συντελεστής μεγέθυνσης που χρησιμοποιείται όταν ανοίγεται μια νέα προβολή (παράθυρο) της σελίδας. Για παράδειγμα, 1 = 100%; 1.5 = 150%, κλπ.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


Συνδέστε το σχήμα με το BeginX του Connector.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeFromId | long | Το αναγνωριστικό του σχήματος όπου αρχίζει ο σύνδεσμος [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Το όνομα σύνδεσης στο σχήμα όπου θα συνδεθεί ο σύνδεσμος . |
| connectorId | long | Το αναγνωριστικό του σχήματος με τύπο Δυναμικός σύνδεσμος [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


Συνδέστε το σχήμα με το EndX του Connector.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeToId | long | Το αναγνωριστικό του σχήματος όπου λήγει ο σύνδεσμος [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | Το όνομα σύνδεσης στο δεύτερο σχήμα όπου θα συνδεθεί ο σύνδεσμος. |
| connectorId | long | Το αναγνωριστικό του σχήματος με τύπο Δυναμικός σύνδεσμος [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


Συνδέστε σχήματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | Το σχήμα που είναι κολλημένο από [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Η θέση στο πρώτο σχήμα όπου θα κολλήσει Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | Το σχήμα όπου θα κολληθεί στο [Shape](../../com.aspose.diagram/shape). |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


Συνδέστε σχήματα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeFromId | long | Το ID του σχήματος που είναι κολλημένο από [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | Η θέση στο πρώτο σχήμα όπου θα κολλήσει Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | Το ID του σχήματος όπου θα κολληθεί στο [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


Συνδέστε σχήματα στο container

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeFromId | long | Το ID του σχήματος που είναι κολλημένο από [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionIndex | int | Η θέση στον πρώτο δείκτη σύνδεσης όπου θα κολλήσει . |
| shapeToEndConnectionIndex | int | Η θέση στον τελικό δείκτη σύνδεσης όπου θα κολλήσει . |
| shapeToId | long | Το ID του σχήματος όπου θα κολληθεί στο [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


Συνδέστε σχήματα στο container χρησιμοποιώντας το όνομα σύνδεσης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeFromId | long | Το ID του σχήματος που είναι κολλημένο από [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionName | java.lang.String | Η θέση στο πρώτο όνομα σύνδεσης όπου θα κολλήσει . |
| shapeToEndConnectionName | java.lang.String | Η θέση στο τελικό όνομα σύνδεσης όπου θα κολλήσει . |
| shapeToId | long | Το ID του σχήματος όπου θα κολληθεί στο [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


Συνδέστε σχήματα με το αναγνωριστικό σύνδεσης στο container

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeFromId | long | Το ID του σχήματος που είναι κολλημένο από [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionID | int | Η θέση στο πρώτο αναγνωριστικό σύνδεσης όπου θα κολλήσει . |
| shapeToEndConnectionID | int | Η θέση στο τελικό αναγνωριστικό σύνδεσης όπου θα κολλήσει . |
| shapeToId | long | Το ID του σχήματος όπου θα κολληθεί στο [Shape](../../com.aspose.diagram/shape). |

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


Διατάσσει τα σχήματα και/ή επαναδρομολογεί τους συνδέσμους για τη σελίδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Χρησιμοποιώντας το [LayoutOptions](../../com.aspose.diagram/layoutoptions) για να διαμορφώσετε τις επιλογές διάταξης. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


Μετακινεί τη σελίδα σε άλλη θέση στις σελίδες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Δείκτης σελίδας προορισμού. |

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


Μετακινεί ένα σχήμα, ορισμένο με ID, μία θέση πίσω στη σειρά z.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


Μετακινεί ένα σχήμα, ορισμένο με ID, στο τέλος της σειράς z.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Εφαρμόστε ένα προεπιλεγμένο θέμα σε αυτή τη σελίδα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Εφαρμόστε μια προεπιλεγμένη παραλλαγή θέματος quickstyle σε αυτή τη σελίδα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Εφαρμόστε μια προεπιλεγμένη παραλλαγή θέματος σε αυτή τη σελίδα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

