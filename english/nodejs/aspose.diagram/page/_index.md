---
title: "Page Class"
linktitle: "Page"
articleTitle: "Page"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains elements that define a page in the document."
type: docs
weight: 1650
url: /nodejs/aspose.diagram/page/
---

## Page class

Contains elements that define a page in the document.

```js
new Page()
```

Constructor.

## Methods

| Name | Description |
| --- | --- |
| [addActiveXControl(type, pinX, pinY, width, height)](./addactivexcontrol/) | Creates an Activex Control. |
| [addComment(shapeID, comment)](./addcomment/) | Adds comment to a shape with shape's id. |
| [addComment(shape, comment)](./addcomment-1/) | Adds comment to a shape. |
| [addComment(pinX, pinY, comment)](./addcomment-2/) | Adds comment with defined PinX and PinY. |
| [addShape(pinX, pinY, masterName, isCalculate)](./addshape/) | Adds shape created by master on page with defined PinX and PinY. |
| [addShape(pinX, pinY, width, height, masterName, isCalculate)](./addshape-1/) | Adds shape created by master on page with defined PinX and PinY. |
| [addShape(pinX, pinY, masterName)](./addshape-2/) | Adds shape created by master on page with defined PinX and PinY. |
| [addShape(pinX, pinY, width, height, masterName)](./addshape-3/) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [addShape(newShape, masterName)](./addshape-4/) | Adds shape created by master to specific page. |
| [addText(pinX, pinY, width, height, text, fontName, fontColor, size)](./addtext/) | Adds Text with defined PinX and PinY. |
| [addText(pinX, pinY, text)](./addtext-1/) | Adds Text with defined PinX and PinY. |
| [applyStyle(textStyle, lineStyle, fillStyle)](./applystyle/) | Applies style for full page. Default value is -1. |
| [autoSpaceShapes(shapes)](./autospaceshapes/) | Auto space shapes |
| [bringForward(shapeId)](./bringforward/) | Brings a shape,defined by ID, forward one position in the z-order. |
| [bringToFront(shapeId)](./bringtofront/) | Brings a shape,defined by ID, to the front of the z-order. |
| [centerDrawing()](./centerdrawing/) | Centers a page's shapes with respect to the extent of the page. Centering shapes does not change their position relative |
| [connectShapesViaConnector(shapeFrom, placeFrom, shapeTo, placeTo, connector)](./connectshapesviaconnector/) | Connect shapes via connector. |
| [connectShapesViaConnector(shapeFromId, placeFrom, shapeToId, placeTo, connectorId)](./connectshapesviaconnector-1/) | Connect shapes via connector. |
| [connectShapesViaConnector(shapeFromId, fromConnectionName, shapeToId, toConnectionName, connectorId)](./connectshapesviaconnector-2/) | Connect shapes via connector. |
| [connectShapesViaConnectorIndex(shapeFromId, fromIndex, shapeToId, toIndex, connectorId)](./connectshapesviaconnectorindex/) | Connect shapes via connector index. |
| [connectShapesViaConnectorIndex(shapeFrom, fromIndex, shapeTo, toIndex, connector)](./connectshapesviaconnectorindex-1/) | Connect shapes via connector index. |
| [constructor_overload$1()](./constructor-overload1/) | Constructor. |
| [copy()](./copy/) |  |
| [dispose()](./dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [drawEllipse(pinX, pinY, width, height)](./drawellipse/) | The process of drawing Ellipse. |
| [drawLine(beginX, beginY, endX, endY)](./drawline/) | The process of drawing a single line. |
| [drawLine(pinX, pinY, width, height, xyArray)](./drawline-1/) | The process of drawing line. |
| [drawOwal(x1, y1, x2, y2)](./drawowal/) | The process of drawing owal. |
| [drawPolyline(xyArray)](./drawpolyline/) | The process of drawing Polyline. |
| [drawPolyline(pinX, pinY, width, height, xyArray)](./drawpolyline-1/) | The process of drawing Polyline. |
| [drawRectangle(pinX, pinY, width, height)](./drawrectangle/) | The process of drawing rectangle. |
| [drawRectangle(x1, y1, x2, y2)](./drawrectangle-1/) | The process of drawing rectangle. |
| [dropContainer(targetShape)](./dropcontainer/) | The process of creating Container. |
| [getAssociatedPage()](./getassociatedpage/) | The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing. |
| [getBackground()](./getbackground/) | A flag indicating if the page is a background page. The value of the property is BOOL integer constant. |
| [getBackPage()](./getbackpage/) | The page's background page. |
| [getConnects()](./getconnects/) | Contains a Connect element for each connection between two shapes in a drawing. |
| [getID()](./getid/) | The unique ID of the element within its parent element. |
| [getName()](./getname/) | The name of the element. |
| [getNameU()](./getnameu/) | The universal name of the element. |
| [getPages()](./getpages/) | Page collection. |
| [getPageSheet()](./getpagesheet/) | Contains elements that define the page sheet for a Page or Master element. |
| [getReviewerID()](./getreviewerid/) | The ID of the reviewer associated with the markup overlay. |
| [getShapes()](./getshapes/) | Shape collection. |
| [getViewCenterX()](./getviewcenterx/) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [getViewCenterY()](./getviewcentery/) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [getViewScale()](./getviewscale/) | The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150 |
| [glueShapes(shapeFrom, placeTo, shapeTo)](./glueshapes/) | Glue shapes. |
| [glueShapes(shapeFromId, placeTo, shapeToId)](./glueshapes-1/) | Glue shapes |
| [glueShapesInContainer(shapeFromId, shapeToBeginConnectionName, shapeToEndConnectionName, shapeToId)](./glueshapesincontainer/) | Glue shapes in container using connection name |
| [glueShapesInContainer(shapeFromId, shapeToBeginConnectionIndex, shapeToEndConnectionIndex, shapeToId)](./glueshapesincontainer-1/) | Glue shapes in container |
| [glueShapesInContainerByID(shapeFromId, shapeToBeginConnectionID, shapeToEndConnectionID, shapeToId)](./glueshapesincontainerbyid/) | Glue shapes by connection id in container |
| [glueShapeToConnectorBeginX(shapeFromId, connectionName, connectorId)](./glueshapetoconnectorbeginx/) | Glue shape to Connector's BeginX |
| [glueShapeToConnectorEndX(shapeToId, connectionName, connectorId)](./glueshapetoconnectorendx/) | Glue shape to Connector's EndX |
| [layout(options)](./layout/) | Lays out the shapes and/or reroutes the connectors for the page. |
| [moveTo(index)](./moveto/) | Moves the page to another location in the pages. |
| [sendBackward(shapeId)](./sendbackward/) | Moves a shape,defined by ID, back one position in the z-order. |
| [sendToBack(shapeId)](./sendtoback/) | Moves a shape,defined by ID, to the back of the z-order. |
| [setAssociatedPage()](./setassociatedpage/) | The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing. |
| [setBackground()](./setbackground/) | A flag indicating if the page is a background page. The value of the property is BOOL integer constant. |
| [setBackPage()](./setbackpage/) | The page's background page. |
| [setID()](./setid/) | The unique ID of the element within its parent element. |
| [setName()](./setname/) | The name of the element. |
| [setNameU()](./setnameu/) | The universal name of the element. |
| [setPages()](./setpages/) | Page collection. |
| [setPresetTheme()](./setpresettheme/) | Apply a preset theme to this page The value of the property is PresetThemeValue integer constant. |
| [setPresetThemeQuickStyle()](./setpresetthemequickstyle/) | Apply a preset theme variant quickstyle to this page The value of the property is PresetQuickStyleValue integer constant |
| [setPresetThemeVariant()](./setpresetthemevariant/) | Apply a preset theme variant to this page The value of the property is PresetThemeVariantValue integer constant. |
| [setReviewerID()](./setreviewerid/) | The ID of the reviewer associated with the markup overlay. |
| [setViewCenterX()](./setviewcenterx/) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [setViewCenterY()](./setviewcentery/) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [setViewScale()](./setviewscale/) | The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150 |
