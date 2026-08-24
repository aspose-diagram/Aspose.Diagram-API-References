---
title: Shape
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi che definiscono una forma in una pagina master o in un elemento forma di gruppo.
type: docs
weight: 355
url: /it/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

Contiene elementi che definiscono una forma in un elemento Master, Pagina o forma di gruppo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Shape()](#Shape--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bringForward()](#bringForward--) | Sposta la forma in avanti di una posizione nell'ordine Z. |
| [bringToFront()](#bringToFront--) | Sposta la forma in primo piano nell'ordine Z. |
| [centerDrawing()](#centerDrawing--) | Centra la forma rispetto all'estensione della pagina |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | Restituisce un array che contiene gli identificatori (ID) delle forme collegate alla forma. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | Restituisce un array che contiene gli identificatori delle forme che dipendono da una forma. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | Ottiene il controllo ActiveX. |
| [getActs()](#getActs--) | Contiene una raccolta di elementi Act. |
| [getAlign()](#getAlign--) | Indica l'allineamento di una forma rispetto alla guida o al punto guida a cui la forma è incollata. |
| [getChars()](#getChars--) | Contiene una raccolta di elementi Char. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Contiene una raccolta di elementi ConnectionABCD. |
| [getConnections()](#getConnections--) | Contiene una raccolta di elementi Connection. |
| [getConnectorRule()](#getConnectorRule--) | Restituisce un connectorRule che contiene l'ID della forma e la connessione collegata alla forma. |
| [getConnectorsType()](#getConnectorsType--) | Ottieni il tipo di connettori |
| [getControlData()](#getControlData--) | Ottiene i dati del controllo. |
| [getControls()](#getControls--) | Contiene una raccolta di elementi Control. |
| [getData1()](#getData1--) | Contiene un valore stringa arbitrario utilizzato per fornire informazioni aggiuntive su una forma. |
| [getData2()](#getData2--) | Contiene un valore stringa arbitrario utilizzato per fornire informazioni aggiuntive su una forma. |
| [getData3()](#getData3--) | Contiene un valore stringa arbitrario utilizzato per fornire informazioni aggiuntive su una forma. |
| [getDel()](#getDel--) | Un flag che indica se l'elemento è stato eliminato localmente. |
| [getDiagram()](#getDiagram--) | Elemento radice della gerarchia degli oggetti Visio. |
| [getDisplayText()](#getDisplayText--) | Ottieni il testo visualizzato sull'interfaccia |
| [getEvent()](#getEvent--) | Contiene elementi che specificano formule che controllano gli eventi della forma. |
| [getFields()](#getFields--) | Contiene una raccolta di elementi Field. |
| [getFill()](#getFill--) | Contiene i valori di formattazione di riempimento attuali per la forma e l'ombra della forma, inclusi modello, colore di primo piano e colore di sfondo. |
| [getFillStyle()](#getFillStyle--) | Foglio di stile da cui questa forma eredita la formattazione di riempimento. |
| [getForeign()](#getForeign--) | Contiene elementi che specificano la larghezza e l'altezza di un oggetto proveniente da un altro programma utilizzato in un documento Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Contiene un BLOB codificato MIME (Multipurpose Internet Mail Extensions) di dati immagine, come metafile Windows, bitmap o dati OLE. |
| [getGeoms()](#getGeoms--) | Contiene una raccolta di elementi Geom. |
| [getGroup()](#getGroup--) | Contiene gli elementi che controllano come aggiungere forme a un gruppo, spostare i membri di un gruppo e selezionare i gruppi. |
| [getHelp()](#getHelp--) | Contiene gli elementi che specificano l'argomento del file di aiuto dell'elemento Shape e le informazioni sul copyright. |
| [getHyperlinks()](#getHyperlinks--) | Contiene una raccolta di elementi Hyperlink. |
| [getID()](#getID--) | L'ID univoco dell'elemento all'interno del suo elemento genitore. |
| [getImage()](#getImage--) | Contiene i valori di gamma, luminosità, contrasto, sfocatura, nitidezza, riduzione del rumore e trasparenza per un bitmap. |
| [getInheritChars()](#getInheritChars--) | Contiene i valori char per la forma ereditati dalla forma master. |
| [getInheritFill()](#getInheritFill--) | Contiene i valori di formattazione di riempimento per la forma ereditati dallo stile genitore e dalla forma master. |
| [getInheritGeoms()](#getInheritGeoms--) | Contiene i valori Geoms per la forma ereditata dalla forma master. |
| [getInheritLine()](#getInheritLine--) | Contiene i valori di formattazione delle linee per la forma ereditata dallo stile genitore e dalla forma master. |
| [getInheritParas()](#getInheritParas--) | Contiene i paras per la forma ereditata dallo stile genitore e dalla forma master. |
| [getInheritProps()](#getInheritProps--) | Contiene le props per la forma ereditata dalla forma master. |
| [getInheritTextBlock()](#getInheritTextBlock--) | Contiene i valori del blocco di testo per la forma ereditata dallo stile genitore e dalla forma master. |
| [getInheritUsers()](#getInheritUsers--) | Contiene gli utenti per la forma ereditata dalla forma master. |
| [getLayerMem()](#getLayerMem--) | Contiene l'elemento LayerMember, che specifica ogni livello a cui la forma è assegnata. |
| [getLayout()](#getLayout--) | Contiene elementi che controllano il posizionamento delle forme e le impostazioni di instradamento dei connettori. |
| [getLine()](#getLine--) | Contiene elementi che controllano gli attributi di linea per una forma, come modello, spessore e colore. |
| [getLineStyle()](#getLineStyle--) | Foglio di stile da cui questa forma eredita la formattazione delle linee |
| [getMaster()](#getMaster--) | Il master da cui la forma eredita i suoi dati. |
| [getMasterShape()](#getMasterShape--) | Questo attributo può essere presente solo nelle forme che sono membri di una forma di gruppo, e il gruppo è un'istanza di un master. |
| [getMisc()](#getMisc--) | Contiene gli elementi che specificano l'argomento del file di aiuto dell'elemento Shape e le informazioni sul copyright. |
| [getName()](#getName--) | Il nome dell'elemento. |
| [getNameU()](#getNameU--) | Il nome universale dell'elemento. |
| [getOneD()](#getOneD--) | Determina se la forma si comporta come un oggetto unidimensionale (1-D). |
| [getPage()](#getPage--) | Elemento radice della gerarchia degli oggetti Visio. |
| [getParas()](#getParas--) | Contiene una raccolta di elementi Para. |
| [getParentShape()](#getParentShape--) | Genitore della forma. |
| [getProps()](#getProps--) | Contiene una raccolta di elementi Prop. |
| [getProtection()](#getProtection--) | Il blocco aiuta a prevenire modifiche involontarie alla forma ma non impedisce a Microsoft Visio di ripristinare i valori in altre circostanze. |
| [getPureText()](#getPureText--) | Ottieni la stringa di testo |
| [getRootShape()](#getRootShape--) | Restituisce la forma di livello superiore di un'istanza se questa forma fa parte di un'istanza master. |
| [getScratchs()](#getScratchs--) | Contiene una raccolta di elementi Scratch. |
| [getShapes()](#getShapes--) | Contiene una collezione di elementi Shape. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Contiene una raccolta di elementi SmartTagDef. |
| [getTabsCollection()](#getTabsCollection--) | Contiene una raccolta di elementi Tab. |
| [getText()](#getText--) | Contiene il testo di una forma. |
| [getTextBlock()](#getTextBlock--) | Contiene elementi che specificano l'allineamento, i margini e le posizioni predefinite delle tabulazioni del testo nel blocco di testo di una forma. |
| [getTextStyle()](#getTextStyle--) | Foglio di stile da cui questa forma eredita la formattazione del testo. |
| [getTextXForm()](#getTextXForm--) | Contiene elementi che specificano le informazioni di posizionamento del blocco di testo di una forma. |
| [getThreeDFormat()](#getThreeDFormat--) | Ottiene il ThreeDFormat. |
| [getTwoD()](#getTwoD--) | Determina se la forma si comporta come un oggetto bidimensionale (2-D). |
| [getType()](#getType--) | Il tipo di una forma. |
| [getUniqueID()](#getUniqueID--) | Un GUID (identificatore unico globale) assegnato alla forma. |
| [getUsers()](#getUsers--) | Contiene una raccolta di elementi Utente. |
| [getXForm()](#getXForm--) | Contiene elementi che specificano informazioni generali di posizionamento su una forma. |
| [getXForm1D()](#getXForm1D--) | Contiene le coordinate x e y del punto iniziale e del punto finale di una forma 1-D. |
| [getZOrderIndex()](#getZOrderIndex--) | Restituisce l'indice di una forma nell'ordine Z, esclusa la forma guida. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | Restituisce un array che contiene gli identificatori delle forme incollate a una forma. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | Indica se queste due forme sono connesse. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | Indica se questa forma contiene un'altra forma. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | Indica se queste due forme sono incollate. |
| [isInGroup()](#isInGroup--) | Indica se questa forma è in una forma di gruppo. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | Indica se questa forma interseca un'altra forma. |
| [isTextEmpty()](#isTextEmpty--) | Indica se la forma contiene testo e se il testo è vuoto o meno. |
| [move(double dX, double dY)](#move-double-double-) | Sposta la forma di dX e dY pollici dalla posizione corrente. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | Sposta la forma a una nuova posizione assoluta nella pagina. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | Aggiorna la posizione della forma includendo xform, connection e geom quando si modifica il testo della forma o di altri. |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | Sostituisce la stringa di testo di una forma. |
| [sendBackward()](#sendBackward--) | Sposta la forma indietro di una posizione nell'ordine Z. |
| [sendToBack()](#sendToBack--) | Sposta la forma in fondo all'ordine Z. |
| [setAngle(double angle)](#setAngle-double-) | Imposta il nuovo angolo della forma. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | Imposta il tipo di connettori |
| [setData1(String value)](#setData1-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | Per la descrizione di questa proprietà, vedere [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | Per la descrizione di questa proprietà, vedere [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Per la descrizione di questa proprietà, vedere [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | Imposta la nuova altezza della forma. |
| [setID(long value)](#setID-long-) | Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Per la descrizione di questa proprietà, vedere [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Per la descrizione di questa proprietà, vedere [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | Per la descrizione di questa proprietà, vedere [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Per la descrizione di questa proprietà, vedere [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | Per la descrizione di questa proprietà, vedere [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Applica un tema predefinito a questa forma |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Applica una variante di tema predefinita quickstyle a questa forma |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | Applica una variante di tema predefinita quickstyle a questa forma, come le opzioni di stili tema nell'elenco a discesa degli stili della forma |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Applica una variante di tema predefinita a questa forma |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | Per la descrizione di questa proprietà, vedere [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | Per la descrizione di questa proprietà, vedere [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Per la descrizione di questa proprietà, vedere [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | Per la descrizione di questa proprietà, vedere [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | Per la descrizione di questa proprietà, vedere [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Per la descrizione di questa proprietà, vedere [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | Imposta la nuova larghezza della forma. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | Per la descrizione di questa proprietà, vedere [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | Per la descrizione di questa proprietà, vedere [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | Crea l'html della forma e lo salva in uno stream nel formato specificato. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | Crea l'html della forma e lo salva in uno stream nel formato specificato. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | Crea l'html e lo salva in un file. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | Crea l'immagine della forma e la salva in uno stream nel formato specificato. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | Crea l'immagine della forma e la salva in uno stream nel formato specificato. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | Crea l'immagine della forma e la salva in un file. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | Crea il pdf della forma e lo salva in uno stream. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | Crea il pdf della forma e lo salva in uno stream. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | Salva la forma in un file pdf. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | Salva la forma in un file svg. |
| [ungroup()](#ungroup--) | Separa forma |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


Costruttore.

### bringForward() {#bringForward--}
```
public void bringForward()
```


Sposta la forma in avanti di una posizione nell'ordine Z.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


Sposta la forma in primo piano nell'ordine Z.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centra la forma rispetto all'estensione della pagina

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


Restituisce un array che contiene gli identificatori (ID) delle forme collegate alla forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flag | int | Filtra l'array di ID di forma restituiti in base alla direzionalità dei connettori. Vedere le Osservazioni per i valori possibili Aspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | Filtra l'array di ID di forma restituiti limitandolo agli ID delle forme che corrispondono alla categoryString specificata. |

**Returns:**
long[] - array di ID long.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


Restituisce un array che contiene gli identificatori delle forme che dipendono da una forma.

**Returns:**
long[] - array di ID long.
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


Ottiene il controllo ActiveX.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Contiene una raccolta di elementi Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


Indica l'allineamento di una forma rispetto alla guida o al punto guida a cui la forma è incollata. L'elemento Align appare solo per le forme che sono incollate a guide o punti guida.

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Contiene una raccolta di elementi Char.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClippingPath() {#getClippingPath--}
```
public String getClippingPath()
```




**Returns:**
java.lang.String
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


Contiene una raccolta di elementi ConnectionABCD.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Contiene una raccolta di elementi Connection.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


Restituisce un connectorRule che contiene l'ID della forma e la connessione collegata alla forma.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


Ottieni il tipo di connettori

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


Ottiene i dati del controllo.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Contiene una raccolta di elementi Control.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


Contiene un valore stringa arbitrario utilizzato per fornire informazioni aggiuntive su una forma.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


Contiene un valore stringa arbitrario utilizzato per fornire informazioni aggiuntive su una forma.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


Contiene un valore stringa arbitrario utilizzato per fornire informazioni aggiuntive su una forma.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


Un flag che indica se l'elemento è eliminato localmente. Un valore di 1 indica che l'elemento è eliminato localmente.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Elemento radice della gerarchia degli oggetti Visio.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


Ottieni il testo visualizzato sull'interfaccia

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Contiene elementi che specificano formule che controllano gli eventi della forma.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Contiene una raccolta di elementi Field.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


Contiene i valori di formattazione di riempimento attuali per la forma e l'ombra della forma, inclusi modello, colore di primo piano e colore di sfondo.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Foglio di stile da cui questa forma eredita la formattazione di riempimento.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Contiene elementi che specificano la larghezza e l'altezza di un oggetto proveniente da un altro programma utilizzato in un documento Microsoft Visio. Include anche elementi che specificano la distanza di offset dell'immagine dell'oggetto all'interno dei suoi bordi.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Contiene un BLOB codificato MIME (Multipurpose Internet Mail Extensions) di dati immagine, come metafile Windows, bitmap o dati OLE.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Contiene una raccolta di elementi Geom.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Contiene gli elementi che controllano come aggiungere forme a un gruppo, spostare i membri di un gruppo e selezionare i gruppi.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Contiene gli elementi che specificano l'argomento del file di aiuto dell'elemento Shape e le informazioni sul copyright.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Contiene una raccolta di elementi Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


L'ID univoco dell'elemento all'interno del suo elemento genitore.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


Contiene i valori di gamma, luminosità, contrasto, sfocatura, nitidezza, riduzione del rumore e trasparenza per un bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


Contiene i valori char per la forma ereditati dalla forma master.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


Contiene i valori di formattazione di riempimento per la forma ereditati dallo stile genitore e dalla forma master.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


Contiene i valori Geoms per la forma ereditata dalla forma master.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


Contiene i valori di formattazione delle linee per la forma ereditata dallo stile genitore e dalla forma master.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


Contiene i paras per la forma ereditata dallo stile genitore e dalla forma master.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


Contiene le props per la forma ereditata dalla forma master.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


Contiene i valori del blocco di testo per la forma ereditata dallo stile genitore e dalla forma master.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


Contiene gli utenti per la forma ereditata dalla forma master.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


Contiene l'elemento LayerMember, che specifica ogni livello a cui la forma è assegnata.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


Contiene elementi che controllano il posizionamento delle forme e le impostazioni di instradamento dei connettori.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


Contiene elementi che controllano gli attributi della linea per una forma, come modello, spessore e colore. Questi elementi determinano se le estremità della linea sono formattate (ad esempio, con una punta di freccia), la dimensione dei formati delle estremità della linea, il raggio del cerchio di arrotondamento applicato alla linea e lo stile del cappuccio della linea (rotondo o quadrato).

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Foglio di stile da cui questa forma eredita la formattazione delle linee

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Il master da cui la forma eredita i suoi dati.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


Questo attributo può essere presente solo nelle forme che sono membri di una forma di gruppo, e il gruppo è un'istanza di un master. L'attributo contiene un ID che fa riferimento alla sottoforma corrispondente nel master.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Contiene gli elementi che specificano l'argomento del file di aiuto dell'elemento Shape e le informazioni sul copyright.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


Il nome dell'elemento.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Il nome universale dell'elemento.

**Returns:**
java.lang.String
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


Determina se la forma si comporta come un oggetto unidimensionale (1-D). Sola lettura.

**Returns:**
boolean
### getPage() {#getPage--}
```
public Page getPage()
```


Elemento radice della gerarchia degli oggetti Visio.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Contiene una raccolta di elementi Para.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


Genitore della forma.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Contiene una raccolta di elementi Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Il blocco aiuta a prevenire modifiche involontarie alla forma ma non impedisce a Microsoft Visio di ripristinare i valori in altre circostanze. Inoltre non protegge dalle modifiche apportate nella finestra ShapeSheet.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


Ottieni la stringa di testo

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


Restituisce la forma di livello superiore di un'istanza se questa forma fa parte di un'istanza master. Sola lettura.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Contiene una raccolta di elementi Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Contiene una collezione di elementi Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Contiene una raccolta di elementi SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Contiene una raccolta di elementi Tab.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


Contiene il testo di una forma.

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


Contiene elementi che specificano l'allineamento, i margini e le posizioni predefinite delle tabulazioni del testo nel blocco di testo di una forma.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Foglio di stile da cui questa forma eredita la formattazione del testo.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


Contiene elementi che specificano le informazioni di posizionamento del blocco di testo di una forma.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


Ottiene il ThreeDFormat.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


Determina se la forma si comporta come un oggetto bidimensionale (2-D).

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


Il tipo di una forma. Può essere uno dei seguenti valori: Group, Shape, Guide o Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Un GUID (identificatore unico globale) assegnato alla forma.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Contiene una raccolta di elementi Utente.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


Contiene elementi che specificano informazioni generali di posizionamento su una forma.

**Returns:**
[XForm](../../com.aspose.diagram/xform)
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


Contiene le coordinate x e y del punto iniziale e del punto finale di una forma 1-D. Questo elemento appare solo per forme 1-D.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


Restituisce l'indice di una forma nell'ordine Z, esclusa la forma guida.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


Restituisce un array che contiene gli identificatori delle forme incollate a una forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flag | int | La dimensionalità e la direzionalità dei punti di connessione delle forme da restituire. Vedi Note per i possibili valori Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | Filtra l'array di ID di forma restituiti limitandolo agli ID delle forme che corrispondono alla categoryString specificata. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | Opzionale: forma aggiuntiva a cui le forme restituite devono anche essere incollate, può essere [Shape](../../com.aspose.diagram/shape) o null. |

**Returns:**
long[] - array di ID long.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isConnected(Shape shape) {#isConnected-com.aspose.diagram.Shape-}
```
public boolean isConnected(Shape shape)
```


Indica se queste due forme sono connesse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


Indica se questa forma contiene un'altra forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


Indica se queste due forme sono incollate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


Indica se questa forma è in una forma di gruppo.

**Returns:**
boolean
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


Indica se questa forma interseca un'altra forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


Indica se la forma contiene testo e se il testo è vuoto o meno.

**Returns:**
boolean
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


Sposta la forma di dX e dY pollici dalla posizione corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dX | double | Offset X double. |
| dY | double | Offset Y double. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


Sposta la forma a una nuova posizione assoluta nella pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newPinX | double | Nuova coordinata x del pin della forma (centro di rotazione) in relazione all'origine del suo genitore. double. |
| newPinY | double | Nuova coordinata y del pin della forma (centro di rotazione) in relazione all'origine del suo genitore. double. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshData() {#refreshData--}
```
public void refreshData()
```


Aggiorna la posizione della forma includendo xform, connection e geom quando si modifica il testo della forma o di altri. Raccoglieremo i dati della forma, come il testo della forma, quindi calcoleremo la posizione della forma. Questo metodo è usato solo per aggiornare i dati della forma.

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


Sostituisce la stringa di testo di una forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


Sposta la forma indietro di una posizione nell'ordine Z.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


Sposta la forma in fondo all'ordine Z.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


Imposta il nuovo angolo della forma. L'unità dell'angolo è il radiante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | double | Nuovo angolo la cui unità è radiante, non grado double. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


Per la descrizione di questa proprietà, vedere [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


Imposta il tipo di connettori

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


Per la descrizione di questa proprietà, vedere [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


Per la descrizione di questa proprietà, vedere [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


Per la descrizione di questa proprietà, vedere [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Per la descrizione di questa proprietà, vedere [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


Per la descrizione di questa proprietà, vedere [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


Per la descrizione di questa proprietà, vedere [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Per la descrizione di questa proprietà, vedere [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


Imposta la nuova altezza della forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| height | double | New heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Per la descrizione di questa proprietà, vedere [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Per la descrizione di questa proprietà, vedere [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


Per la descrizione di questa proprietà, vedere [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Per la descrizione di questa proprietà, vedere [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


Per la descrizione di questa proprietà, vedere [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Applica un tema predefinito a questa forma

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Applica una variante di tema predefinita quickstyle a questa forma

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


Applica una variante di tema predefinita quickstyle a questa forma, come le opzioni di stili tema nell'elenco a discesa degli stili della forma

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| styleIndex | int | the row of style matrics |
| colorIndex | int | the column of style matrics |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Applica una variante di tema predefinita a questa forma

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


Per la descrizione di questa proprietà, vedere [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


Per la descrizione di questa proprietà, vedere [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Per la descrizione di questa proprietà, vedere [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


Per la descrizione di questa proprietà, vedere [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Per la descrizione di questa proprietà, vedere [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Per la descrizione di questa proprietà, vedere [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


Imposta la nuova larghezza della forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | double | New widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


Per la descrizione di questa proprietà, vedere [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


Per la descrizione di questa proprietà, vedere [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


Crea l'html della forma e lo salva in uno stream nel formato specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


Crea l'html della forma e lo salva in uno stream nel formato specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


Crea l'html e lo salva in un file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html save options |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


Crea l'immagine della forma e la salva in uno stream nel formato specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


Crea l'immagine della forma e la salva in uno stream nel formato specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageFile | java.lang.String | The image file name with full path. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


Crea il pdf della forma e lo salva in uno stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | The output stream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


Crea il pdf della forma e lo salva in uno stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | The output stream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


Salva la forma in un file pdf.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | the pdf file name with full path |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toSvg(String imageFile, SVGSaveOptions options) {#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-}
```
public void toSvg(String imageFile, SVGSaveOptions options)
```


Salva la forma in un file svg.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


Separa forma

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

