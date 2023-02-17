---
title: Window
second_title: Aspose.Diagram per riferimento API .NET
description: Rappresenta una finestra aperta in unistanza di Microsoft Visio. Questo elemento contiene le informazioni necessarie per ricreare esattamente una finestra dellinterfaccia utente nellarea di lavoro dellapplicazione quando il file DatadiagramML viene inizialmente aperto da Visio.
type: docs
weight: 4390
url: /it/net/aspose.diagram/window/
---
## Window class

Rappresenta una finestra aperta in un'istanza di Microsoft Visio. Questo elemento contiene le informazioni necessarie per ricreare esattamente una finestra dell'interfaccia utente nell'area di lavoro dell'applicazione quando il file DatadiagramML viene inizialmente aperto da Visio.

```csharp
public class Window
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Window](window/)() | Costruttore. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Container](../../aspose.diagram/window/container/) { get; set; } | ID del contenitore: Pagina, Foglio o Master. Rilevante e necessario solo se viene specificato ContainerType. |
| [ContainerType](../../aspose.diagram/window/containertype/) { get; set; } | Può essere uno dei seguenti valori: Documento, Pagina o Master. Rilevante solo quando WindowType è specificato come Disegno o Foglio. |
| [Document](../../aspose.diagram/window/document/) { get; set; } | Percorso file del documento visualizzato in questa finestra. Questo attributo è rilevante per le finestre il cui WindowType è specificato come Stencil. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled/) { get; set; } | Specifica se la funzione griglia dinamica è abilitata per un documento o una finestra. |
| [GlueSettings](../../aspose.diagram/window/gluesettings/) { get; set; } | Specifica gli oggetti a cui le forme si incollano quando la colla è abilitata nel documento. |
| [ID](../../aspose.diagram/window/id/) { get; set; } | L'ID univoco dell'elemento all'interno del suo elemento padre. |
| [Master](../../aspose.diagram/window/master/) { get; set; } | ID master se questa finestra visualizza un master. |
| [Page](../../aspose.diagram/window/page/) { get; set; } | ID pagina se questa finestra sta visualizzando una pagina. Rilevante solo quando WindowType è specificato come Drawing e ContainerType è specificato come Page. |
| [ParentWindow](../../aspose.diagram/window/parentwindow/) { get; set; } | ID della finestra in cui è contenuta questa finestra stencil. Rilevante solo quando WindowType è specificato come Stencil. |
| [ReadOnly](../../aspose.diagram/window/readonly/) { get; set; } | Flag di sola lettura se questo stencil non è uno stencil di documento. |
| [Sheet](../../aspose.diagram/window/sheet/) { get; set; } | ID del foglio nel contenitore. Rilevante solo quando Contenitore è specificato come Foglio. |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints/) { get; set; } | Specifica se i punti di connessione vengono visualizzati in una finestra. |
| [ShowGrid](../../aspose.diagram/window/showgrid/) { get; set; } | Specifica se visualizzare una griglia nella finestra di disegno. |
| [ShowGuides](../../aspose.diagram/window/showguides/) { get; set; } | Specifica se le guide vengono visualizzate nella finestra di disegno. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks/) { get; set; } | Specifica se le interruzioni di pagina vengono visualizzate in una finestra. |
| [ShowRulers](../../aspose.diagram/window/showrulers/) { get; set; } | Specifica se i righelli vengono visualizzati nella finestra di disegno. |
| [SnapAngles](../../aspose.diagram/window/snapangles/) { get; } | Contiene una raccolta di elementi SnapAngle. |
| [SnapExtensions](../../aspose.diagram/window/snapextensions/) { get; set; } | Specifica se un'impostazione di estensione snap specifica è abilitata o disabilitata per la finestra attiva. Il valore può essere una somma dei valori nella tabella seguente. |
| [SnapSettings](../../aspose.diagram/window/snapsettings/) { get; set; } | Specifica gli oggetti a cui le forme si agganciano quando lo snap è attivo nella finestra. Il valore può essere una somma dei valori nella tabella seguente. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup/) { get; set; } | Specifica il gruppo di finestre stencil unite di cui la finestra è membro. Questo attributo è rilevante solo per gli elementi Window il cui attributo WindowType è Stencil e solo se la finestra stencil fa parte di un gruppo unito di finestre stencil. Tutte le finestre di stencil che fanno parte dello stesso gruppo unito hanno lo stesso valore dell'elemento StencilGroup. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos/) { get; set; } | Contiene un numero intero che specifica la posizione relativa di uno stencil all'interno di un gruppo in una finestra. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos/) { get; set; } | Specifica la larghezza del controllo struttura a schede della pagina di una finestra di disegno (come frazione della larghezza totale della finestra di disegno). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx/) { get; set; } | Doppio opzionale. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery/) { get; set; } | Doppio opzionale. |
| [ViewScale](../../aspose.diagram/window/viewscale/) { get; set; } | Doppio opzionale. |
| [WindowHeight](../../aspose.diagram/window/windowheight/) { get; set; } | Altezza del rettangolo della finestra. |
| [WindowLeft](../../aspose.diagram/window/windowleft/) { get; set; } | Coordinata sinistra del rettangolo della finestra. |
| [WindowState](../../aspose.diagram/window/windowstate/) { get; set; } | Questo attributo può essere una somma dei seguenti valori. |
| [WindowTop](../../aspose.diagram/window/windowtop/) { get; set; } | Coordinata superiore del rettangolo della finestra. |
| [WindowType](../../aspose.diagram/window/windowtype/) { get; set; } | Un valore enumerato che può essere uno dei seguenti: Drawing, Sheet, Stencil o Icon.Un elemento Window di WindowType='Stencil' deve essere visualizzato dopo la relativa finestra di disegno padre (WindowType='Drawing') e prima di qualsiasi altra finestra di disegno elementi. |
| [WindowWidth](../../aspose.diagram/window/windowwidth/) { get; set; } | Larghezza del rettangolo della finestra. |

### Guarda anche

* spazio dei nomi [Aspose.Diagram](../../aspose.diagram/)
* assemblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
