---
title: "Page Class"
linktitle: "Page"
articleTitle: "Page"
second_title: "Aspose.Diagram for Python via Java"
description: "Contains elements that define a page in the document."
type: docs
weight: 2240
url: /python-java/asposediagram.api/page/
---

## Page class

Contains elements that define a page in the document.

```python
Page()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Pages](./pages/) | PageCollection | Page collection. |
| [Shapes](./shapes/) | ShapeCollection | Shape collection. |
| [PageSheet](./pagesheet/) | PageSheet | Contains elements that define the page sheet for a Page or Master element. |
| [Connects](./connects/) | ConnectCollection | Contains a Connect element for each connection between two shapes in a drawing. |
| [ID](./id/) | int | The unique ID of the element within its parent element. |
| [Name](./name/) | String | The name of the element. |
| [NameU](./nameu/) | String | The universal name of the element. |
| [Background](./background/) | int | A flag indicating if the page is a background page. The value of the property is BOOL integer constant. |
| [BackPage](./backpage/) | Page | The page's background page. |
| [ViewScale](./viewscale/) | float | The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150 |
| [ViewCenterX](./viewcenterx/) | float | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [ViewCenterY](./viewcentery/) | float | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [ReviewerID](./reviewerid/) | int | The ID of the reviewer associated with the markup overlay. |
| [AssociatedPage](./associatedpage/) | Page | The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing. |
| [PresetTheme](./presettheme/) | int | Apply a preset theme to this page The value of the property is PresetThemeValue integer constant. |
| [PresetThemeVariant](./presetthemevariant/) | int | Apply a preset theme variant to this page The value of the property is PresetThemeVariantValue integer constant. |
| [PresetThemeQuickStyle](./presetthemequickstyle/) | int | Apply a preset theme variant quickstyle to this page The value of the property is PresetQuickStyleValue integer constant |

## Methods

| Name | Description |
| --- | --- |
| [centerDrawing](./centerdrawing/) | Centers a page's shapes with respect to the extent of the page. Centering shapes does not change their position relative |
| [copy](./copy/) |  |
| [dispose](./dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [applyStyle](./applystyle/) | Applies style for full page.

Default value is -1. |
| [moveTo](./moveto/) | Moves the page to another location in the pages. |
| [addShape](./addshape/) | Adds shape created by master on page with defined PinX and PinY. |
| [connectShapesViaConnector](./connectshapesviaconnector/) | Connect shapes via connector. |
| [glueShapeToConnectorBeginX](./glueshapetoconnectorbeginx/) | Glue shape to Connector's BeginX |
| [glueShapeToConnectorEndX](./glueshapetoconnectorendx/) | Glue shape to Connector's EndX |
| [connectShapesViaConnectorIndex](./connectshapesviaconnectorindex/) | Connect shapes via connector index. |
| [glueShapesInContainerByID](./glueshapesincontainerbyid/) | Glue shapes by connection id in container |
| [glueShapesInContainer](./glueshapesincontainer/) | Glue shapes in container using connection name |
| [bringForward](./bringforward/) | Brings a shape,defined by ID, forward one position in the z-order. |
| [sendBackward](./sendbackward/) | Moves a shape,defined by ID, back one position in the z-order. |
| [bringToFront](./bringtofront/) | Brings a shape,defined by ID, to the front of the z-order. |
| [sendToBack](./sendtoback/) | Moves a shape,defined by ID, to the back of the z-order. |
| [addComment](./addcomment/) | Adds comment to a shape with shape's id. |
| [autoSpaceShapes](./autospaceshapes/) | Auto space shapes |
| [addText](./addtext/) | Adds Text with defined PinX and PinY. |
| [drawLine](./drawline/) | The process of drawing a single line. |
| [drawRectangle](./drawrectangle/) | The process of drawing rectangle. |
| [drawEllipse](./drawellipse/) | The process of drawing Ellipse. |
| [drawOwal](./drawowal/) | The process of drawing owal. |
| [dropContainer](./dropcontainer/) | The process of creating Container. |
| [drawPolyline](./drawpolyline/) | The process of drawing Polyline. |
