---
title: Window
second_title: Aspose.Diagram voor .NET API-referentie
description: Vertegenwoordigt een open venster in een Microsoft Visioexemplaar. Dit element bevat informatie die nodig is om een gebruikersinterfacevenster exact opnieuw te maken in de werkruimte van de toepassing wanneer het DatadiagramMLbestand voor het eerst wordt geopend door Visio.
type: docs
weight: 4390
url: /nl/net/aspose.diagram/window/
---
## Window class

Vertegenwoordigt een open venster in een Microsoft Visio-exemplaar. Dit element bevat informatie die nodig is om een gebruikersinterfacevenster exact opnieuw te maken in de werkruimte van de toepassing wanneer het DatadiagramML-bestand voor het eerst wordt geopend door Visio.

```csharp
public class Window
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Window](window/)() | Aannemer. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Container](../../aspose.diagram/window/container/) { get; set; } | ID van container: pagina, blad of model. Alleen relevant en noodzakelijk als ContainerType is opgegeven. |
| [ContainerType](../../aspose.diagram/window/containertype/) { get; set; } | Kan een van de volgende waarden zijn: Document, Pagina of Master. Alleen relevant wanneer WindowType is opgegeven als Tekening of Blad. |
| [Document](../../aspose.diagram/window/document/) { get; set; } | Bestandspad van het document dat in dit venster wordt weergegeven. Dit kenmerk is relevant voor vensters waarvan het WindowType is opgegeven als Stencil. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled/) { get; set; } | Geeft aan of de dynamische rasterfunctie is ingeschakeld voor een document of venster. |
| [GlueSettings](../../aspose.diagram/window/gluesettings/) { get; set; } | Specificeert de objecten die lijm vormen wanneer lijm is ingeschakeld in het document. |
| [ID](../../aspose.diagram/window/id/) { get; set; } | De unieke ID van het element binnen het bovenliggende element. |
| [Master](../../aspose.diagram/window/master/) { get; set; } | Master-ID als dit venster een master weergeeft. |
| [Page](../../aspose.diagram/window/page/) { get; set; } | Pagina-ID als dit venster een pagina weergeeft. Alleen relevant wanneer WindowType is opgegeven als Drawing en ContainerType is opgegeven als Page. |
| [ParentWindow](../../aspose.diagram/window/parentwindow/) { get; set; } | ID van het venster waarin dit stencilvenster zich bevindt. Alleen relevant wanneer WindowType is opgegeven als Stencil. |
| [ReadOnly](../../aspose.diagram/window/readonly/) { get; set; } | Markering Alleen-lezen als dit stencil geen documentstencil is. |
| [Sheet](../../aspose.diagram/window/sheet/) { get; set; } | ID van blad in container. Alleen relevant wanneer Container is opgegeven als Blad. |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints/) { get; set; } | Geeft aan of aansluitingen in een venster worden weergegeven. |
| [ShowGrid](../../aspose.diagram/window/showgrid/) { get; set; } | Geeft aan of er een raster wordt weergegeven in het tekenvenster. |
| [ShowGuides](../../aspose.diagram/window/showguides/) { get; set; } | Geeft aan of hulplijnen worden weergegeven in het tekenvenster. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks/) { get; set; } | Geeft aan of pagina-einden in een venster worden weergegeven. |
| [ShowRulers](../../aspose.diagram/window/showrulers/) { get; set; } | Bepaalt of linialen worden weergegeven in het tekenvenster. |
| [SnapAngles](../../aspose.diagram/window/snapangles/) { get; } | Bevat een verzameling SnapAngle-elementen. |
| [SnapExtensions](../../aspose.diagram/window/snapextensions/) { get; set; } | Geeft aan of een specifieke snapextensie-instelling is ingeschakeld of uitgeschakeld voor het actieve venster. De waarde kan een som zijn van de waarden in de volgende tabel. |
| [SnapSettings](../../aspose.diagram/window/snapsettings/) { get; set; } | Hiermee geeft u de objecten op waarnaar vormen worden uitgelijnd wanneer snappen actief is in het venster. De waarde kan een som zijn van de waarden in de volgende tabel. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup/) { get; set; } | Specificeert de groep samengevoegde stencilvensters waarvan het venster lid is. Dit attribuut is alleen relevant voor Window-elementen waarvan het WindowType-attribuut Stencil is, en alleen als het stencilvenster deel uitmaakt van een samengevoegde groep stencilvensters. Alle stencilvensters die deel uitmaken van dezelfde samengevoegde groep hebben dezelfde waarde voor het StencilGroup-element. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos/) { get; set; } | Bevat een geheel getal dat de relatieve positie van een stencil binnen een groep in een venster specificeert. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos/) { get; set; } | Specificeert de breedte van het paginatabblad van een tekenvenster (als een fractie van de totale breedte van het tekenvenster). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx/) { get; set; } | Optioneel dubbel. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery/) { get; set; } | Optioneel dubbel. |
| [ViewScale](../../aspose.diagram/window/viewscale/) { get; set; } | Optioneel dubbel. |
| [WindowHeight](../../aspose.diagram/window/windowheight/) { get; set; } | Hoogte van de vensterrechthoek. |
| [WindowLeft](../../aspose.diagram/window/windowleft/) { get; set; } | Linkercoördinaat van de vensterrechthoek. |
| [WindowState](../../aspose.diagram/window/windowstate/) { get; set; } | Dit attribuut kan een som zijn van de volgende waarden. |
| [WindowTop](../../aspose.diagram/window/windowtop/) { get; set; } | Topcoördinaat van de vensterrechthoek. |
| [WindowType](../../aspose.diagram/window/windowtype/) { get; set; } | Een opgesomde waarde die een van de volgende kan zijn: Tekening, Blad, Stencil of Pictogram. Een vensterelement van WindowType='Stencil' moet verschijnen na het bovenliggende tekenvenster (WindowType='Drawing') en vóór elk ander tekenvenster elementen. |
| [WindowWidth](../../aspose.diagram/window/windowwidth/) { get; set; } | Breedte van de vensterrechthoek. |

### Zie ook

* naamruimte [Aspose.Diagram](../../aspose.diagram/)
* montage [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
