---
title: Window
second_title: Aspose.Diagram för .NET API-referens
description: Representerar ett öppet fönster i en Microsoft Visioinstans. Detta element innehåller information som är nödvändig för att exakt återskapa ett användargränssnittsfönster i applikationens arbetsyta när DatadiagramMLfilen initialt öppnas av Visio.
type: docs
weight: 4390
url: /sv/net/aspose.diagram/window/
---
## Window class

Representerar ett öppet fönster i en Microsoft Visio-instans. Detta element innehåller information som är nödvändig för att exakt återskapa ett användargränssnittsfönster i applikationens arbetsyta när DatadiagramML-filen initialt öppnas av Visio.

```csharp
public class Window
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Window](window/)() | Konstruktör. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Container](../../aspose.diagram/window/container/) { get; set; } | Behållarens ID: sida, ark eller master. Endast relevant och nödvändig om ContainerType anges. |
| [ContainerType](../../aspose.diagram/window/containertype/) { get; set; } | Kan vara ett av följande värden: Document, Page eller Master. Endast relevant när WindowType anges som Ritning eller Ark. |
| [Document](../../aspose.diagram/window/document/) { get; set; } | Filsökväg för dokumentet som visas i det här fönstret. Det här attributet är relevant för fönster vars WindowType anges som Stencil. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled/) { get; set; } | Anger om den dynamiska rutnätsfunktionen är aktiverad för ett dokument eller fönster. |
| [GlueSettings](../../aspose.diagram/window/gluesettings/) { get; set; } | Anger objekten som formar lim till när lim är aktiverat i dokumentet. |
| [ID](../../aspose.diagram/window/id/) { get; set; } | Elementets unika ID i dess överordnade element. |
| [Master](../../aspose.diagram/window/master/) { get; set; } | Master ID om det här fönstret visar en master. |
| [Page](../../aspose.diagram/window/page/) { get; set; } | Sid-ID om det här fönstret visar en sida. Relevant endast när WindowType anges som Drawing och ContainerType anges som Page. |
| [ParentWindow](../../aspose.diagram/window/parentwindow/) { get; set; } | ID för fönstret där detta stencilfönster finns. Endast relevant när WindowType anges som Stencil. |
| [ReadOnly](../../aspose.diagram/window/readonly/) { get; set; } | Skrivskyddad flagga om denna stencil inte är en dokumentstencil. |
| [Sheet](../../aspose.diagram/window/sheet/) { get; set; } | ID för arket i behållaren. Endast relevant när behållare är angiven som Sheet. |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints/) { get; set; } | Anger om anslutningspunkter visas i ett fönster. |
| [ShowGrid](../../aspose.diagram/window/showgrid/) { get; set; } | Anger om ett rutnät visas i ritfönstret. |
| [ShowGuides](../../aspose.diagram/window/showguides/) { get; set; } | Anger om stödlinjer visas i ritfönstret. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks/) { get; set; } | Anger om sidbrytningar ska visas i ett fönster. |
| [ShowRulers](../../aspose.diagram/window/showrulers/) { get; set; } | Anger om linjaler ska visas i ritfönstret. |
| [SnapAngles](../../aspose.diagram/window/snapangles/) { get; } | Innehåller en samling SnapAngle-element. |
| [SnapExtensions](../../aspose.diagram/window/snapextensions/) { get; set; } | Anger om en specifik snaptilläggsinställning är aktiverad eller inaktiverad för det aktiva fönstret. Värdet kan vara summan av värdena i följande tabell. |
| [SnapSettings](../../aspose.diagram/window/snapsettings/) { get; set; } | Anger objekten som formar snap till när snap är aktivt i fönstret. Värdet kan vara summan av värdena i följande tabell. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup/) { get; set; } | Anger gruppen av sammanslagna stencilfönster som fönstret är en medlem av. Det här attributet är endast relevant för Window-element vars WindowType-attribut är Stencil, och endast om stencilfönstret är en del av en sammanslagen grupp av stencilfönster. Alla stencilfönster som ingår i samma sammanslagna grupp har samma elementvärde för StencilGroup. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos/) { get; set; } | Innehåller ett heltal som anger den relativa positionen för en stencil inom en grupp i ett fönster. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos/) { get; set; } | Anger bredden på sidflikkontrollen för ett ritfönster (som en bråkdel av ritfönstrets totala bredd). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx/) { get; set; } | Valfri dubbel. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery/) { get; set; } | Valfri dubbel. |
| [ViewScale](../../aspose.diagram/window/viewscale/) { get; set; } | Valfri dubbel. |
| [WindowHeight](../../aspose.diagram/window/windowheight/) { get; set; } | Fönsterrektangelns höjd. |
| [WindowLeft](../../aspose.diagram/window/windowleft/) { get; set; } | Vänster koordinat för fönsterrektangeln. |
| [WindowState](../../aspose.diagram/window/windowstate/) { get; set; } | Det här attributet kan vara en summa av följande värden. |
| [WindowTop](../../aspose.diagram/window/windowtop/) { get; set; } | Översta koordinaten för fönsterrektangeln. |
| [WindowType](../../aspose.diagram/window/windowtype/) { get; set; } | Ett uppräknat värde som kan vara något av följande: Ritning, Ark, Stencil eller Icon. Ett fönsterelement av WindowType='Stencil' måste visas efter dess överordnade ritfönster (WindowType='Drawing') och före något annat ritfönster elements. |
| [WindowWidth](../../aspose.diagram/window/windowwidth/) { get; set; } | Bredd på fönsterrektangeln. |

### Se även

* namnutrymme [Aspose.Diagram](../../aspose.diagram/)
* hopsättning [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
