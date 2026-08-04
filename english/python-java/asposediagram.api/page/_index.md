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
| [Pages](/python-java/asposediagram.api/page/pages/) | PageCollection | Page collection. |
| [Shapes](/python-java/asposediagram.api/page/shapes/) | ShapeCollection | Shape collection. |
| [PageSheet](/python-java/asposediagram.api/page/pagesheet/) | PageSheet | Contains elements that define the page sheet for a Page or Master element. |
| [Connects](/python-java/asposediagram.api/page/connects/) | ConnectCollection | Contains a Connect element for each connection between two shapes in a drawing. |
| [ID](/python-java/asposediagram.api/page/id/) | int | The unique ID of the element within its parent element. |
| [Name](/python-java/asposediagram.api/page/name/) | String | The name of the element. |
| [NameU](/python-java/asposediagram.api/page/nameu/) | String | The universal name of the element. |
| [Background](/python-java/asposediagram.api/page/background/) | int | A flag indicating if the page is a background page. The value of the property is BOOL integer constant. |
| [BackPage](/python-java/asposediagram.api/page/backpage/) | Page | The page's background page. |
| [ViewScale](/python-java/asposediagram.api/page/viewscale/) | float | The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150 |
| [ViewCenterX](/python-java/asposediagram.api/page/viewcenterx/) | float | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [ViewCenterY](/python-java/asposediagram.api/page/viewcentery/) | float | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [ReviewerID](/python-java/asposediagram.api/page/reviewerid/) | int | The ID of the reviewer associated with the markup overlay. |
| [AssociatedPage](/python-java/asposediagram.api/page/associatedpage/) | Page | The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing. |
| [PresetTheme](/python-java/asposediagram.api/page/presettheme/) | int | Apply a preset theme to this page The value of the property is PresetThemeValue integer constant. |
| [PresetThemeVariant](/python-java/asposediagram.api/page/presetthemevariant/) | int | Apply a preset theme variant to this page The value of the property is PresetThemeVariantValue integer constant. |
| [PresetThemeQuickStyle](/python-java/asposediagram.api/page/presetthemequickstyle/) | int | Apply a preset theme variant quickstyle to this page The value of the property is PresetQuickStyleValue integer constant |

## Methods

| Name | Description |
| --- | --- |
| [centerDrawing](/python-java/asposediagram.api/page/centerdrawing/) | Centers a page's shapes with respect to the extent of the page. Centering shapes does not change their position relative |
| [copy](/python-java/asposediagram.api/page/copy/) |  |
| [dispose](/python-java/asposediagram.api/page/dispose/) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [applyStyle](/python-java/asposediagram.api/page/applystyle/) | Applies style for full page.

Default value is -1. |
| [moveTo](/python-java/asposediagram.api/page/moveto/) | Moves the page to another location in the pages. |
| [addShape](/python-java/asposediagram.api/page/addshape/) | Adds shape created by master on page with defined PinX and PinY. |
| [connectShapesViaConnector](/python-java/asposediagram.api/page/connectshapesviaconnector/) | Connect shapes via connector. |
| [glueShapeToConnectorBeginX](/python-java/asposediagram.api/page/glueshapetoconnectorbeginx/) | Glue shape to Connector's BeginX |
| [glueShapeToConnectorEndX](/python-java/asposediagram.api/page/glueshapetoconnectorendx/) | Glue shape to Connector's EndX |
| [connectShapesViaConnectorIndex](/python-java/asposediagram.api/page/connectshapesviaconnectorindex/) | Connect shapes via connector index. |
| [glueShapesInContainerByID](/python-java/asposediagram.api/page/glueshapesincontainerbyid/) | Glue shapes by connection id in container |
| [glueShapesInContainer](/python-java/asposediagram.api/page/glueshapesincontainer/) | Glue shapes in container using connection name |
| [bringForward](/python-java/asposediagram.api/page/bringforward/) | Brings a shape,defined by ID, forward one position in the z-order. |
| [sendBackward](/python-java/asposediagram.api/page/sendbackward/) | Moves a shape,defined by ID, back one position in the z-order. |
| [bringToFront](/python-java/asposediagram.api/page/bringtofront/) | Brings a shape,defined by ID, to the front of the z-order. |
| [sendToBack](/python-java/asposediagram.api/page/sendtoback/) | Moves a shape,defined by ID, to the back of the z-order. |
| [addComment](/python-java/asposediagram.api/page/addcomment/) | Adds comment to a shape with shape's id. |
| [autoSpaceShapes](/python-java/asposediagram.api/page/autospaceshapes/) | Auto space shapes |
| [addText](/python-java/asposediagram.api/page/addtext/) | Adds Text with defined PinX and PinY. |
| [drawLine](/python-java/asposediagram.api/page/drawline/) | The process of drawing a single line. |
| [drawRectangle](/python-java/asposediagram.api/page/drawrectangle/) | The process of drawing rectangle. |
| [drawEllipse](/python-java/asposediagram.api/page/drawellipse/) | The process of drawing Ellipse. |
| [drawOwal](/python-java/asposediagram.api/page/drawowal/) | The process of drawing owal. |
| [dropContainer](/python-java/asposediagram.api/page/dropcontainer/) | The process of creating Container. |
| [drawPolyline](/python-java/asposediagram.api/page/drawpolyline/) | The process of drawing Polyline. |
