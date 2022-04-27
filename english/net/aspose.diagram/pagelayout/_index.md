---
title: PageLayout
second_title: Aspose.Diagram for .NET API Reference
description: 
type: docs
weight: 2500
url: /net/aspose.diagram/pagelayout/
---
## PageLayout class

Contains cells that control the page layout settings for shapes and connectors, such as spacing between all shapes on the page, spacing between all connectors on the page, and routing style for all connectors on the page.

```csharp
public class PageLayout
```

## Properties

| Name | Description |
| --- | --- |
| [AvenueSizeX](avenuesizex) { get; } | Determines the amount of vertical space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page. |
| [AvenueSizeY](avenuesizey) { get; } | Determines the amount of vertical space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page. |
| [AvoidPageBreaks](avoidpagebreaks) { get; } | Specifies how shapes are placed on the page when shapes are laid out when a user selects Lay Out Shapes (Shape menu). |
| [BlockSizeX](blocksizex) { get; } | Determines the vertical block size, the area in which each of your shapes must fit on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page. |
| [BlockSizeY](blocksizey) { get; } | Determines the amount of horizontal space between shapes on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page. |
| [CtrlAsInput](ctrlasinput) { get; } | Determines which shape is the parent when using shapes by control handles. This element sets the behavior for all the shapes on the drawing page. |
| [Del](del) { get; set; } | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. |
| [DynamicsOff](dynamicsoff) { get; } | Specifies whether placeable shapes move and connectors reroute around other shapes and connectors on the drawing page. |
| [EnableGrid](enablegrid) { get; } | Specifies whether Microsoft Visio lays out shapes based on an internal page grid when the user selects Lay Out Shapes (Shape menu). |
| [LineAdjustFrom](lineadjustfrom) { get; } | Specifies which dynamic connectors to space apart if they route on top of each other. |
| [LineAdjustTo](lineadjustto) { get; } | Specifies which dynamic connectors to line up on top of one another if they route on top of each other. |
| [LineJumpCode](linejumpcode) { get; } | Specifies the line jump style for all connectors on the drawing page that don't have a local line jump style. |
| [LineJumpFactorX](linejumpfactorx) { get; } | Specifies the size of line jumps on horizontal segments of dynamic connectors on the page, as a percentage of the value of the LineToLineX element (which specifies the horizontal clearance between all connectors on the drawing page). The value of this element ranges from 0 to 10. |
| [LineJumpFactorY](linejumpfactory) { get; } | Specifies the size of line jumps on vertical segments of dynamic connectors on the page, as a percentage of the value of the LineToLineY element (which specifies the vertical clearance between all connectors on the drawing page). This element can contain a value from 0 to 10. |
| [LineJumpStyle](linejumpstyle) { get; } | Specifies the direction of line jumps on horizontal segments of dynamic connectors on the drawing page for which you haven't applied a local jump direction. |
| [LineRouteExt](linerouteext) { get; } | Specifies the default appearance for all connectors on a page. |
| [LineToLineX](linetolinex) { get; } | Specifies the minimum horizontal clearance between dynamic connectors on the drawing page. |
| [LineToLineY](linetoliney) { get; } | Specifies the minimum vertical clearance between dynamic connectors on the drawing page. |
| [LineToNodeX](linetonodex) { get; } | Specifies the minimum vertical clearance between dynamic connectors and shapes on the drawing page. |
| [LineToNodeY](linetonodey) { get; } | Determines the horizontal block size, the area in which each of your shapes must fit on the drawing page when you use Microsoft Visio to lay out shapes on the drawing page. |
| [PageLineJumpDirX](pagelinejumpdirx) { get; } | Specifies the direction of line jumps on vertical dynamic connectors on the drawing page for which you haven't applied a local jump direction. |
| [PageLineJumpDirY](pagelinejumpdiry) { get; } | Specifies the minimum horizontal clearance between dynamic connectors and shapes on the drawing page. |
| [PageShapeSplit](pageshapesplit) { get; } | Indicates whether shapes on the page can be split automatically. |
| [PlaceDepth](placedepth) { get; } | Specifies whether placeable shapes move away when the user drags a placeable shape near another placeable shape on the drawing page. |
| [PlaceFlip](placeflip) { get; } | Specifies how placeable shapes flip and/or rotate on a page when shapes are laid out using the Lay Out Shapes command in Microsoft Visio. The following hexadecimal values are allowed. |
| [PlaceStyle](placestyle) { get; } | Specifies the routing style and direction for all dynamic connectors on the drawing page that don't have a local routing style. |
| [PlowCode](plowcode) { get; } | Determines the dynamic connectors to which you want to add jumps. |
| [ResizePage](resizepage) { get; } | Specifies whether to enlarge the page to enclose the drawing after a user selects Lay Out Shapes (Shapes menu). |
| [RouteStyle](routestyle) { get; } | For a drawing that is laid out automatically, specifies the method by which the drawing is analyzed before creating the layout and determines the type of layout. |

### See Also

* namespace [Aspose.Diagram](../../aspose.diagram)
* assembly [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
