---
title: Diagramma
second_title: Riferimento API di Aspose.Diagram per Java
description: Elemento radice della gerarchia degli oggetti Visio.
type: docs
weight: 117
url: /it/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

Elemento radice della gerarchia degli oggetti Visio.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | Costruttore pubblico della classe, carica il diagramma dal file. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | Costruttore pubblico della classe, carica il diagramma dallo stream. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | Costruttore pubblico della classe, carica il diagramma dallo stream usando il formato predefinito. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | Costruttore pubblico della classe, carica il diagramma dallo stream usando le opzioni di caricamento predefinite. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | Costruttore pubblico della classe, carica il diagramma dal file usando il formato predefinito. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | Costruttore pubblico della classe, carica il diagramma dal file usando le opzioni di caricamento predefinite. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | Aggiunge il master al diagramma dal diagramma sorgente per Name o NameU del master. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | Aggiunge il master al diagramma dallo stream del modello per ID del master. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | Aggiunge il master al diagramma dallo stream del modello per Name o NameU del master. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | Aggiunge il master al diagramma dal file del modello per ID del master. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | Aggiunge il master al diagramma dal file del modello per Name o NameU del master. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | Aggiunge una forma creata dal master a una pagina specifica. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | Aggiunge una forma creata dal master sulla pagina con PinX, PinY, larghezza e altezza definiti. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | Aggiunge una forma creata dal master sulla pagina con PinX e PinY definiti. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | Combina un altro oggetto Diagram. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | Copia il Tema da un Diagramma sorgente. |
| [dispose()](#dispose--) | Esegue operazioni definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | Esporta il diagramma dallo stream vsd al formato stream vdw. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | Esporta il diagramma dallo stream vsd al formato file *.vdw. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | Esporta il diagramma dal file vsd al formato stream vdw. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | Esporta il diagramma da vsd a formato vdw. |
| [getActivePage()](#getActivePage--) | Specifica la pagina attiva |
| [getBuildnum()](#getBuildnum--) | Il numero di build dell'istanza Visio usata per creare il documento. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | Contiene la tabella dei colori del documento. |
| [getDataConnections()](#getDataConnections--) | Contiene gli elementi DataConnection per il documento. |
| [getDataRecordSets()](#getDataRecordSets--) | La collezione di oggetti DataRecordset associati a un oggetto Document. |
| [getDefaultFontDir()](#getDefaultFontDir--) | Ottieni il percorso della cartella Font predefinita |
| [getDocLangID()](#getDocLangID--) | L'ID univoco della lingua dell'interfaccia utente specificata dall'utente nelle Preferenze lingua di Microsoft Office 2010. |
| [getDocumentProps()](#getDocumentProps--) | Contiene elementi di proprietà del documento come il titolo del documento, l'autore e così via. |
| [getDocumentSettings()](#getDocumentSettings--) | Contiene elementi che specificano le impostazioni del documento. |
| [getDocumentSheet()](#getDocumentSheet--) | Specifica la struttura ShapeSheet di un documento. |
| [getEmailRoutingData()](#getEmailRoutingData--) | Contiene una busta di instradamento e-mail MAPI codificata in MIME (Multipurpose Internet Mail Extensions) per il documento. |
| [getEventItems()](#getEventItems--) | Contiene un elemento EventItem per ogni evento a cui un oggetto dovrebbe rispondere. |
| [getFonts()](#getFonts--) | Contiene una raccolta di elementi Font |
| [getHeaderFooter()](#getHeaderFooter--) | Contiene gli elementi per l'intestazione e il piè di pagina di un documento. |
| [getInterruptMonitor()](#getInterruptMonitor--) | il monitor di interruzione. |
| [getKey()](#getKey--) | Indica se il documento è stato modificato al di fuori di Visio. |
| [getMasters()](#getMasters--) | Raccolta di oggetti Master. |
| [getMetric()](#getMetric--) | Indica se utilizzare unità metriche nel disegno. |
| [getPages()](#getPages--) | Raccolta di oggetti Page. |
| [getRibbonX()](#getRibbonX--) | La stringa Ribbon XML che viene passata al documento per personalizzare l'interfaccia utente del ribbon. |
| [getSolutionXMLs()](#getSolutionXMLs--) | Valore XML. |
| [getStart()](#getStart--) | Indica se il documento è stato modificato al di fuori di Visio. |
| [getStyleSheets()](#getStyleSheets--) | Raccolta di oggetti StyleSheet. |
| [getUnusedStyles()](#getUnusedStyles--) | Ottieni gli Stili non utilizzati |
| [getUserCustomUI()](#getUserCustomUI--) | La stringa Ribbon XML che viene passata al documento per personalizzare la barra degli strumenti di accesso rapido o il ribbon. |
| [getValidation()](#getValidation--) | Memorizza informazioni sulla convalida del diagramma per il documento. |
| [getVbProjectData()](#getVbProjectData--) | Contiene i dati del progetto Microsoft Visual Basic for Applications in formato codificato MIME (Multipurpose Internet Mail Extensions). |
| [getVbaProject()](#getVbaProject--) | Ottiene il VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\\#getVbaProject--). |
| [getVersion()](#getVersion--) | Il numero di versione dell'istanza di Visio. |
| [getWindows()](#getWindows--) | Contiene gli elementi Window per un documento. |
| [hasHiddenInfo()](#hasHiddenInfo--) | Indica se questo diagramma contiene informazioni nascoste. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Dispone le forme e/o riorienta i connettori per tutte le pagine del diagramma. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | Stampa l'intero documento sulla stampante specificata,utilizzando il controller di stampa standard (senza interfaccia utente). |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Stampa l'intero documento sulla stampante specificata,utilizzando il controller di stampa standard (senza interfaccia utente). |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | Stampa il documento,utilizzando il controller di stampa standard (senza interfaccia utente) e un nome documento. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | Stampa il documento,utilizzando il controller di stampa standard (senza interfaccia utente) e un nome documento. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | Rimuovi le informazioni non utilizzate |
| [removeMacro()](#removeMacro--) | Rimuove VBA/macro da questo diagramma. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | Salva il diagramma sullo stream. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Salva il diagramma sullo stream. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | Salva il documento su un file utilizzando le opzioni di salvataggio specificate. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Salva i dati del diagramma sul file. |
| [setBuildnum(long value)](#setBuildnum-long-) | Per la descrizione di questa proprietà, vedere [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | Per la descrizione di questa proprietà, vedere [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | Per la descrizione di questa proprietà, vedere [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | Indica il percorso della cartella Fonts |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | Per la descrizione di questa proprietà, vedere [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getKey()](../../com.aspose.diagram/diagram\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | Per la descrizione di questa proprietà, vedere [getMetric()](../../com.aspose.diagram/diagram\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | Per la descrizione di questa proprietà, vedere [getStart()](../../com.aspose.diagram/diagram\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | Per la descrizione di questa proprietà, vedere [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getVersion()](../../com.aspose.diagram/diagram\#getVersion--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Diagram() {#Diagram--}
```
public Diagram()
```


### Diagram(String filename) {#Diagram-java.lang.String-}
```
public Diagram(String filename)
```


Costruttore pubblico della classe, carica il diagramma dal file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il nome del file. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


Costruttore pubblico della classe, carica il diagramma dallo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso di dati. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


Costruttore pubblico della classe, carica il diagramma dallo stream usando il formato predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso di dati. |
| formato | int | I dati Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


Costruttore pubblico della classe, carica il diagramma dallo stream usando le opzioni di caricamento predefinite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Il flusso di dati. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | I dati [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


Costruttore pubblico della classe, carica il diagramma dal file usando il formato predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il nome del file. |
| formato | int | Il formato del file. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


Costruttore pubblico della classe, carica il diagramma dal file usando le opzioni di caricamento predefinite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il nome del file. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | I dati [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


Aggiunge il master al diagramma dal diagramma sorgente per Name o NameU del master.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | diagramma di origine. |
| masterName | java.lang.String | Nome del master o NameU. |

**Returns:**
int - L'ID univoco del master nella raccolta dei master in questo diagramma.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


Aggiunge il master al diagramma dallo stream del modello per ID del master.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| templateStream | java.io.InputStream | flusso del modello. |
| masterID | int | L'ID univoco del master nella raccolta dei master nel modello. |

**Returns:**
int - L'ID univoco del master nella raccolta dei master in questo diagramma.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


Aggiunge il master al diagramma dallo stream del modello per Name o NameU del master.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| templateStream | java.io.InputStream | flusso del modello. |
| masterName | java.lang.String | Nome del master o NameU. |

**Returns:**
int - L'ID univoco del master nella raccolta dei master in questo diagramma.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


Aggiunge il master al diagramma dal file del modello per ID del master.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| templateFilePath | java.lang.String | Percorso del file modello (può essere in formato vdx, vst o vsd). |
| masterID | int | L'ID univoco del master nella raccolta dei master nel modello. |

**Returns:**
int - L'ID univoco del master nella raccolta dei master in questo diagramma.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


Aggiunge il master al diagramma dal file del modello per Name o NameU del master.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| templateFilePath | java.lang.String | Percorso del file modello (può essere in formato vdx, vst o vsd). |
| masterName | java.lang.String | Nome del master o NameU. |

**Returns:**
int - L'ID univoco del master nella raccolta dei master in questo diagramma.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


Aggiunge una forma creata dal master a una pagina specifica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | Nuovo oggetto shape[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Nome del master. |
| pageNumber | int | Indice della pagina. |

**Returns:**
long - L'ID univoco della forma all'interno della collezione di forme nella pagina specificata.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


Aggiunge una forma creata dal master sulla pagina con PinX, PinY, larghezza e altezza definiti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double | Specifica la coordinata x del perno della forma (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno della forma (centro di rotazione) in relazione alla pagina. |
| width | double | Specifica la larghezza della forma in pollici. |
| height | double | Specifica l'altezza della forma in pollici. |
| masterName | java.lang.String | Nome del master. |
| pageNumber | int | Indice della pagina. |

**Returns:**
long - L'ID univoco della forma all'interno della collezione di forme nella pagina specificata.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


Aggiunge una forma creata dal master sulla pagina con PinX e PinY definiti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pinX | double | Specifica la coordinata x del perno della forma (centro di rotazione) in relazione alla pagina. |
| pinY | double | Specifica la coordinata y del perno della forma (centro di rotazione) in relazione alla pagina. |
| masterName | java.lang.String | Nome del master. |
| pageNumber | int | Indice della pagina. |

**Returns:**
long - L'ID univoco della forma all'interno della collezione di forme nella pagina specificata.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


Combina un altro oggetto Diagram.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | Un altro oggetto Diagram. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


Copia il Tema da un Diagramma sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | diagramma di origine. |

### dispose() {#dispose--}
```
public void dispose()
```


Esegue operazioni definite dall'applicazione associate al rilascio, alla liberazione o al reset delle risorse non gestite.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


Esporta il diagramma dallo stream vsd al formato stream vdw. Non ancora implementato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputVsd | java.io.InputStream | stream vsd. |
| outputVdw | java.io.InputStream | stream vdw. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


Esporta il diagramma dallo stream vsd al formato file \*.vdw. Non ancora implementato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputVsd | java.io.InputStream | Nome file \*.vsd. |
| outputVdw | java.lang.String | stream vdw. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


Esporta il diagramma dal file vsd al formato stream vdw. Non ancora implementato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputVsd | java.lang.String | Nome file \*.vsd. |
| outputVdw | java.io.InputStream | stream vdw. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


Esporta il diagramma da vsd a formato vdw. Non ancora implementato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputVsd | java.lang.String | Nome file \*.vsd. |
| outputVdw | java.lang.String | Nome file \*.vdw. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


Specifica la pagina attiva

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


Il numero di build dell'istanza Visio usata per creare il documento.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColors() {#getColors--}
```
public ColorEntryCollection getColors()
```


Contiene la tavola dei colori del documento. Ogni documento contiene una singola tavola dei colori, che elenca i 24 colori standard disponibili per l'applicazione a oggetti come forme, testo e livelli nel documento.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


Contiene gli elementi DataConnection per il documento.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


La collezione di oggetti DataRecordset associati a un oggetto Document.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


Ottieni il percorso della cartella Font predefinita

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


L'ID univoco della lingua dell'interfaccia utente specificata dall'utente nelle Preferenze lingua di Microsoft Office 2010.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


Contiene elementi di proprietà del documento come il titolo del documento, l'autore e così via.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


Contiene elementi che specificano le impostazioni del documento.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


Specifica la struttura ShapeSheet di un documento.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


Contiene una busta di instradamento e-mail MAPI codificata in MIME (Multipurpose Internet Mail Extensions) per il documento.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


Contiene un elemento EventItem per ogni evento a cui un oggetto dovrebbe rispondere.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Contiene una raccolta di elementi Font

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


Contiene gli elementi per l'intestazione e il piè di pagina di un documento.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


il monitor di interruzione.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


Indica se il documento è stato modificato al di fuori di Visio. Se presente, Visio testerà completamente il contenuto del file. Omettere per i file creati al di fuori di Visio.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


Raccolta di oggetti Master.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


Indica se utilizzare unità metriche nel disegno. Impostare questo attributo su True (1) per usare unità metriche; impostarlo su False (0) per usare unità inglesi.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Raccolta di oggetti Page.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


La stringa Ribbon XML che viene passata al documento per personalizzare l'interfaccia utente del ribbon.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


Valore XML.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


Indica se il documento è stato modificato al di fuori di Visio. Se presente, Visio testerà completamente il contenuto del file. Omettere per i file creati al di fuori di Visio.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


Raccolta di oggetti StyleSheet.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


Ottieni gli Stili non utilizzati

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


La stringa Ribbon XML che viene passata al documento per personalizzare la barra degli strumenti di accesso rapido o il ribbon.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


Memorizza informazioni sulla convalida del diagramma per il documento.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


Contiene i dati del progetto Microsoft Visual Basic for Applications in formato codificato MIME (Multipurpose Internet Mail Extensions).

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


Ottiene il VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\\#getVbaProject--).

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


Il numero di versione dell'istanza di Visio. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


Contiene gli elementi Window per un documento.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


Indica se questo diagramma contiene informazioni nascoste.

**Returns:**
boolean
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


Dispone le forme e/o riorienta i connettori per tutte le pagine del diagramma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Utilizzando [LayoutOptions](../../com.aspose.diagram/layoutoptions) per configurare le opzioni del layout. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### print(String printerName) {#print-java.lang.String-}
```
public void print(String printerName)
```


Stampa l'intero documento sulla stampante specificata, usando il controller di stampa standard (senza interfaccia utente). Se printerName è Null o vuoto verrà usata la stampante predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| printerName | java.lang.String | Il nome della stampante. Può essere Null. |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


Stampa l'intero documento sulla stampante specificata, usando il controller di stampa standard (senza interfaccia utente). Se printerName è Null o vuoto verrà usata la stampante predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| printerName | java.lang.String | Il nome della stampante. Può essere Null. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Le opzioni di stampa. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


Stampa il documento,utilizzando il controller di stampa standard (senza interfaccia utente) e un nome documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| printerName | java.lang.String | Il nome della stampante. Può essere Null. |
| documentName | java.lang.String | Il nome del documento da visualizzare (ad esempio, in una finestra di dialogo di stato di stampa o nella coda della stampante) durante la stampa del documento. |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


Stampa il documento,utilizzando il controller di stampa standard (senza interfaccia utente) e un nome documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| printerName | java.lang.String | Il nome della stampante. Può essere Null. |
| documentName | java.lang.String | Il nome del documento da visualizzare (ad esempio, in una finestra di dialogo di stato di stampa o nella coda della stampante) durante la stampa del documento. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | Le opzioni di stampa. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


Rimuovi le informazioni non utilizzate

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


Rimuove VBA/macro da questo diagramma.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


Salva il diagramma sullo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | Il flusso di file. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | Le opzioni di salvataggio. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


Salva il diagramma sullo stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | Il flusso di file. |
| formato | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


Salva il documento su un file utilizzando le opzioni di salvataggio specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il nome del file. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) salva le opzioni del diagramma. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


Salva i dati del diagramma sul file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il nome del file. |
| formato | int | Aspose.Diagram.SaveFileFormat salva il formato del file. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


Per la descrizione di questa proprietà, vedere [getBuildnum()](../../com.aspose.diagram/diagram\#getBuildnum--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


Per la descrizione di questa proprietà, vedere [getDocLangID()](../../com.aspose.diagram/diagram\#getDocLangID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


Per la descrizione di questa proprietà, vedere [getEmailRoutingData()](../../com.aspose.diagram/diagram\#getEmailRoutingData--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


Indica il percorso della cartella Fonts

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


Per la descrizione di questa proprietà, vedere [getInterruptMonitor()](../../com.aspose.diagram/diagram\#getInterruptMonitor--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


Per la descrizione di questa proprietà, vedere [getKey()](../../com.aspose.diagram/diagram\#getKey--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


Per la descrizione di questa proprietà, vedere [getMetric()](../../com.aspose.diagram/diagram\#getMetric--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


Per la descrizione di questa proprietà, vedere [getRibbonX()](../../com.aspose.diagram/diagram\#getRibbonX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


Per la descrizione di questa proprietà, vedere [getStart()](../../com.aspose.diagram/diagram\#getStart--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


Per la descrizione di questa proprietà, vedere [getUserCustomUI()](../../com.aspose.diagram/diagram\#getUserCustomUI--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


Per la descrizione di questa proprietà, vedere [getVbProjectData()](../../com.aspose.diagram/diagram\#getVbProjectData--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Per la descrizione di questa proprietà, vedere [getVersion()](../../com.aspose.diagram/diagram\#getVersion--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

