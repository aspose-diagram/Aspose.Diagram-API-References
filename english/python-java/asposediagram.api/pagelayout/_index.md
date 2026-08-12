---
title: "PageLayout"
linktitle: "PageLayout"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains cells that control the page layout settings for shapes and connectors, such as spacing between all shapes on the page, spacing between all connectors o"
type: docs
weight: 2260
url: /python-java/asposediagram.api/pagelayout/
---

## PageLayout class

Contains cells that control the page layout settings for shapes and connectors, such as spacing between all shapes on the page, spacing between all connectors on the page, and routing style for all connectors on the page.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [ResizePage](#resizepage) | BoolValue | Specifies whether to enlarge the page to enclose the drawing after a user selects Lay Out Shapes (Shapes menu). |
| [EnableGrid](#enablegrid) | BoolValue | Specifies whether Microsoft Visio lays out shapes based on an internal page grid when the user selects Lay Out Shapes (S |
| [DynamicsOff](#dynamicsoff) | BoolValue | Specifies whether placeable shapes move and connectors reroute around other shapes and connectors on the drawing page. |
| [CtrlAsInput](#ctrlasinput) | BoolValue | Determines which shape is the parent when using shapes by control handles. This element sets the behavior for all the sh |
| [AvoidPageBreaks](#avoidpagebreaks) | BoolValue | Specifies how shapes are placed on the page when shapes are laid out when a user selects Lay Out Shapes (Shape menu). |
| [PlaceStyle](#placestyle) | PlaceStyle | Specifies the routing style and direction for all dynamic connectors on the drawing page that don't have a local routing |
| [RouteStyle](#routestyle) | RouteStyle | For a drawing that is laid out automatically, specifies the method by which the drawing is analyzed before creating the  |
| [PlaceDepth](#placedepth) | PlaceDepth | Specifies whether placeable shapes move away when the user drags a placeable shape near another placeable shape on the d |
| [PlowCode](#plowcode) | BoolValue | Determines the dynamic connectors to which you want to add jumps. |
| [LineJumpCode](#linejumpcode) | LineJumpCode | Specifies the line jump style for all connectors on the drawing page that don't have a local line jump style. |
| [LineJumpStyle](#linejumpstyle) | LineJumpStyle | Specifies the direction of line jumps on horizontal segments of dynamic connectors on the drawing page for which you hav |
| [PageLineJumpDirX](#pagelinejumpdirx) | PageLineJumpDirX | Specifies the direction of line jumps on vertical dynamic connectors on the drawing page for which you haven't applied a |
| [PageLineJumpDirY](#pagelinejumpdiry) | PageLineJumpDirY | Specifies the minimum horizontal clearance between dynamic connectors and shapes on the drawing page. |
| [LineToNodeX](#linetonodex) | DoubleValue | Specifies the minimum vertical clearance between dynamic connectors and shapes on the drawing page. |
| [LineToNodeY](#linetonodey) | DoubleValue | Determines the horizontal block size, the area in which each of your shapes must fit on the drawing page when you use Mi |
| [BlockSizeX](#blocksizex) | DoubleValue | Determines the vertical block size, the area in which each of your shapes must fit on the drawing page when you use Micr |
| [BlockSizeY](#blocksizey) | DoubleValue | Determines the amount of horizontal space between shapes on the drawing page when you use Microsoft Visio to lay out sha |
| [AvenueSizeX](#avenuesizex) | DoubleValue | Determines the amount of vertical space between shapes on the drawing page when you use Microsoft Visio to lay out shape |
| [AvenueSizeY](#avenuesizey) | DoubleValue | Determines the amount of vertical space between shapes on the drawing page when you use Microsoft Visio to lay out shape |
| [LineToLineX](#linetolinex) | DoubleValue | Specifies the minimum horizontal clearance between dynamic connectors on the drawing page. |
| [LineToLineY](#linetoliney) | DoubleValue | Specifies the minimum vertical clearance between dynamic connectors on the drawing page. |
| [LineJumpFactorX](#linejumpfactorx) | DoubleValue | Specifies the size of line jumps on horizontal segments of dynamic connectors on the page, as a percentage of the value  |
| [LineJumpFactorY](#linejumpfactory) | DoubleValue | Specifies the size of line jumps on vertical segments of dynamic connectors on the page, as a percentage of the value of |
| [LineAdjustFrom](#lineadjustfrom) | LineAdjustFrom | Specifies which dynamic connectors to space apart if they route on top of each other. |
| [LineAdjustTo](#lineadjustto) | LineAdjustTo | Specifies which dynamic connectors to line up on top of one another if they route on top of each other. |
| [PlaceFlip](#placeflip) | PlaceFlip | Specifies how placeable shapes flip and/or rotate on a page when shapes are laid out using the Lay Out Shapes command in |
| [LineRouteExt](#linerouteext) | LineRouteExt | Specifies the default appearance for all connectors on a page. |
| [PageShapeSplit](#pageshapesplit) | BoolValue | Indicates whether shapes on the page can be split automatically. |

### PageLayout.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### PageLayout.ResizePage property {#resizepage}

Specifies whether to enlarge the page to enclose the drawing after a user selects Lay Out Shapes (Shapes menu).

**Type:** BoolValue

### PageLayout.EnableGrid property {#enablegrid}

Specifies whether Microsoft Visio lays out shapes based on an internal page grid when the user selects Lay Out Shapes (Shape menu).

**Type:** BoolValue

### PageLayout.DynamicsOff property {#dynamicsoff}

Specifies whether placeable shapes move and connectors reroute around other shapes and connectors on the drawing page.

**Type:** BoolValue

### PageLayout.CtrlAsInput property {#ctrlasinput}

Determines which shape is the parent when using shapes by control handles. This element sets the behavior for all the shapes on the drawing page.

**Type:** BoolValue

### PageLayout.AvoidPageBreaks property {#avoidpagebreaks}

Specifies how shapes are placed on the page when shapes are laid out when a user selects Lay Out Shapes (Shape menu).

**Type:** BoolValue

### PageLayout.PlaceStyle property {#placestyle}

Specifies the routing style and direction for all dynamic connectors on the drawing page that don't have a local routing style.

**Type:** PlaceStyle

### PageLayout.RouteStyle property {#routestyle}

For a drawing that is laid out automatically, specifies the method by which the drawing is analyzed before creating the layout and determines the type of layout.

**Type:** RouteStyle

### PageLayout.PlaceDepth property {#placedepth}

Specifies whether placeable shapes move away when the user drags a placeable shape near another placeable shape on the drawing page.

**Type:** PlaceDepth

### PageLayout.PlowCode property {#plowcode}

Determines the dynamic connectors to which you want to add jumps.

**Type:** BoolValue

### PageLayout.LineJumpCode property {#linejumpcode}

Specifies the line jump style for all connectors on the drawing page that don't have a local line jump style.

**Type:** LineJumpCode

### PageLayout.LineJumpStyle property {#linejumpstyle}

Specifies the direction of line jumps on horizontal segments of dynamic connectors on the drawing page for which you haven't applied a local jump direction.

**Type:** LineJumpStyle

### PageLayout.PageLineJumpDirX property {#pagelinejumpdirx}

Specifies the direction of line jumps on vertical dynamic connectors on the drawing page for which you haven't applied a local jump direction.

**Type:** PageLineJumpDirX

### PageLayout.PageLineJumpDirY property {#pagelinejumpdiry}

Specifies the minimum horizontal clearance between dynamic connectors and shapes on the drawing page.

**Type:** PageLineJumpDirY

### PageLayout.LineToNodeX property {#linetonodex}

Specifies the minimum vertical clearance between dynamic connectors and shapes on the drawing page.

**Type:** DoubleValue

### PageLayout.LineToNodeY property {#linetonodey}

Determines the horizontal block size, the area in which each of your shapes must fit on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page.

**Type:** DoubleValue

### PageLayout.BlockSizeX property {#blocksizex}

Determines the vertical block size, the area in which each of your shapes must fit on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page.

**Type:** DoubleValue

### PageLayout.BlockSizeY property {#blocksizey}

Determines the amount of horizontal space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page.

**Type:** DoubleValue

### PageLayout.AvenueSizeX property {#avenuesizex}

Determines the amount of vertical space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page.

**Type:** DoubleValue

### PageLayout.AvenueSizeY property {#avenuesizey}

Determines the amount of vertical space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page.

**Type:** DoubleValue

### PageLayout.LineToLineX property {#linetolinex}

Specifies the minimum horizontal clearance between dynamic connectors on the drawing page.

**Type:** DoubleValue

### PageLayout.LineToLineY property {#linetoliney}

Specifies the minimum vertical clearance between dynamic connectors on the drawing page.

**Type:** DoubleValue

### PageLayout.LineJumpFactorX property {#linejumpfactorx}

Specifies the size of line jumps on horizontal segments of dynamic connectors on the page, as a percentage of the value of the LineToLineX element (which specifies the horizontal clearance between all connectors on the drawing page). The value of this element ranges from 0 to 10.

**Type:** DoubleValue

### PageLayout.LineJumpFactorY property {#linejumpfactory}

Specifies the size of line jumps on vertical segments of dynamic connectors on the page, as a percentage of the value of the LineToLineY element (which specifies the vertical clearance between all connectors on the drawing page). This element can contain a value from 0 to 10.

**Type:** DoubleValue

### PageLayout.LineAdjustFrom property {#lineadjustfrom}

Specifies which dynamic connectors to space apart if they route on top of each other.

**Type:** LineAdjustFrom

### PageLayout.LineAdjustTo property {#lineadjustto}

Specifies which dynamic connectors to line up on top of one another if they route on top of each other.

**Type:** LineAdjustTo

### PageLayout.PlaceFlip property {#placeflip}

Specifies how placeable shapes flip and/or rotate on a page when shapes are laid out using the Lay Out Shapes command in Microsoft Visio. The following hexadecimal values are allowed.

**Type:** PlaceFlip

### PageLayout.LineRouteExt property {#linerouteext}

Specifies the default appearance for all connectors on a page.

**Type:** LineRouteExt

### PageLayout.PageShapeSplit property {#pageshapesplit}

Indicates whether shapes on the page can be split automatically.

**Type:** BoolValue
