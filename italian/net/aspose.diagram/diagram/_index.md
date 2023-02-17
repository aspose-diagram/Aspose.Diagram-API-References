---
title: Diagram
second_title: Aspose.Diagram per riferimento API .NET
description: Elemento principale della gerarchia degli oggetti di Visio.
type: docs
weight: 1170
url: /it/net/aspose.diagram/diagram/
---
## Diagram class

Elemento principale della gerarchia degli oggetti di Visio.

```csharp
public class Diagram : IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Diagram](diagram/#constructor)() | Default_Costruttore |
| [Diagram](diagram/#constructor_1)(Stream) | Costruttore di classi pubbliche, carica il diagramma dallo stream. |
| [Diagram](diagram/#constructor_4)(string) | Costruttore di classi pubbliche, carica il diagramma dal file. |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | Costruttore di classi pubbliche, carica il diagramma dallo stream utilizzando il formato predefinito. |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | Costruttore di classe pubblico, carica il diagramma dallo stream utilizzando le opzioni predefinite del file di caricamento. |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | Costruttore di classe pubblico, carica il diagramma dal file utilizzando il formato predefinito. |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | Costruttore di classe pubblico, carica il diagramma dal file utilizzando le opzioni di caricamento del file predefinite. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | Specifica la pagina attiva |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | Il numero di build dell'istanza di Visio utilizzata per creare il documento. |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | Contiene la tavola dei colori del documento. Ogni documento contiene una singola tabella di colori, che elenca i 24 colori standard disponibili per l'applicazione agli oggetti come forme, testo e livelli nel documento. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | Contiene gli elementi DataConnection per il documento. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | La raccolta di oggetti DataRecordset associati a un oggetto Document. |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | L'ID univoco della lingua dell'interfaccia utente specificata dall'utente nelle preferenze della lingua di Microsoft Office 2010. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | Contiene elementi di proprietà del documento come il titolo del documento, l'autore e così via. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | Contiene elementi che specificano le impostazioni del documento. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | Specifica la struttura ShapeSheet di un documento. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | Contiene una lista di instradamento e-mail MAPI con codifica MIME (Multipurpose Internet Mail Extensions) per il documento. |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | Contiene un elemento EventItem per ogni evento a cui un oggetto dovrebbe rispondere. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | Indica il percorso della cartella Fonts |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | Contiene una raccolta di elementi Font |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | Contiene elementi per l'intestazione e il piè di pagina di un documento. |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | Ottiene e imposta il monitor di interrupt. |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | Indica se il documento è stato modificato all'esterno di Visio. Se presente, Visio verificherà completamente il contenuto del file. Ometti per i file che crei al di fuori di Visio. |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | Collezione Oggetti master. |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | Se utilizzare le unità metriche nel disegno. Imposta questo attributo su True (1) per utilizzare le unità metriche; impostalo su False (0) per utilizzare le unità inglesi. |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | Oggetti della pagina di raccolta. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | La stringa XML della barra multifunzione che viene passata al documento per personalizzare l'interfaccia utente della barra multifunzione. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | Valore XML. |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | Indica se il documento è stato modificato all'esterno di Visio. Se presente, Visio verificherà completamente il contenuto del file. Ometti per i file che crei al di fuori di Visio. |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | Raccolta oggetti StyleSheet. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | La stringa XML della barra multifunzione che viene passata al documento per personalizzare la barra degli strumenti di accesso rapido o la barra multifunzione. |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | Memorizza le informazioni sulla convalida del diagramma per il documento. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | Ottiene VbaProject[`VbaProject`](./vbaproject/) . |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | Contiene i dati del progetto Microsoft Visual Basic, Applications Edition in formato codificato MIME (Multipurpose Internet Mail Extensions). |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | Il numero di versione dell'istanza di Visio. Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | Contiene gli elementi Window per un documento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | Aggiunge il master al diagramma dal diagramma di origine in base al nome del master o al nomeU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | Aggiunge il master al diagramma dal flusso di modelli in base all'ID del master. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | Aggiunge il master al diagramma dal flusso di modelli in base al nome del master o al nomeU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | Aggiunge il master al diagramma dal file modello in base all'ID del master. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | Aggiunge il master al diagramma dal file modello in base al nome del master o al nomeU. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | Aggiunge la forma creata dal master a una pagina specifica. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | Aggiunge la forma creata dal master sulla pagina con PinX e PinY definiti. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | Aggiunge la forma creata dal master sulla pagina con PinX, PinY, Larghezza e Altezza definiti. |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | Combina un altro oggetto Diagram. |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | Copia il tema da un diagramma di origine. |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | Esegue attività definite dall'applicazione associate alla liberazione, al rilascio o al ripristino delle risorse non gestite. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | Ottieni il percorso della cartella Font predefiniti |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | Ottieni stili inutilizzati |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | Indica se questo diagramma contiene informazioni nascoste. |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | Dispone le forme e/o reindirizza i connettori per tutte le pagine del diagramma. |
| [Print](../../aspose.diagram/diagram/print/#print)() | Stampa l'intero documento sulla stampante predefinita. |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | Stampa il documento in base alle impostazioni della stampante specificate, utilizzando il controller di stampa standard (senza interfaccia utente). |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | Stampa l'intero documento sulla stampante predefinita. |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | Stampa l'intero documento sulla stampante specificata, utilizzando il controller di stampa standard (senza interfaccia utente). |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | Stampa il documento in base alle impostazioni della stampante specificate, utilizzando il controller di stampa standard (senza interfaccia utente). |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | Stampa il documento in base alle impostazioni della stampante specificate, utilizzando il controller di stampa standard (senza interfaccia utente) e un nome documento. |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | Stampa l'intero documento sulla stampante specificata, utilizzando il controller di stampa standard (senza interfaccia utente). |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | Stampa il documento utilizzando il controller di stampa standard (nessuna interfaccia utente) e un nome documento. |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | Stampa il documento in base alle impostazioni della stampante specificate, utilizzando il controller di stampa standard (senza interfaccia utente) e un nome documento. |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | Stampa il documento utilizzando il controller di stampa standard (nessuna interfaccia utente) e un nome documento. |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | Richiama il metodo Refresh per tutti i DataRecordSet nel diagramma. |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | Rimuovi informazioni inutilizzate |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | Rimuove VBA/macro da questo diagramma. |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | Salva i dati del diagramma nello stream. |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | Salva il diagramma in un flusso utilizzando le opzioni di salvataggio specificate. |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | Salva i dati del diagramma nel file. |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | Salva il documento in un file utilizzando le opzioni di salvataggio specificate. |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | Esporta il diagramma dal formato vsd stream al formato vdw stream. Non ancora implementato. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | Esporta il diagramma dal flusso vsd al formato di file *.vdw. Non ancora implementato. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | Esporta il diagramma dal file vsd al formato flusso vdw. Non ancora implementato. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | Esporta il diagramma dal formato vsd al formato vdw. Non ancora implementato. |

### Guarda anche

* spazio dei nomi [Aspose.Diagram](../../aspose.diagram/)
* assemblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
