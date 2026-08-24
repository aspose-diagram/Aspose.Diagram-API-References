---
title: StyleSheet
second_title: Riferimento API di Aspose.Diagram per Java
description: Rappresenta uno stile definito in un documento.
type: docs
weight: 393
url: /it/java/com.aspose.diagram/stylesheet/
---

**Inheritance:**
java.lang.Object
```
public class StyleSheet
```

Rappresenta uno stile definito in un documento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StyleSheet()](#StyleSheet--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia profonda di questa istanza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChars()](#getChars--) | Contiene una raccolta di elementi Char. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Contiene una raccolta di elementi ConnectionABCD. |
| [getConnections()](#getConnections--) | Contiene una raccolta di elementi Connection. |
| [getEvent()](#getEvent--) | Contiene elementi che specificano formule che controllano gli eventi della forma. |
| [getFill()](#getFill--) | Contiene i valori di formattazione di riempimento attuali per la forma e l'ombra della forma, inclusi modello, colore di primo piano e colore di sfondo. |
| [getFillStyle()](#getFillStyle--) | Elemento StyleSheet da cui questo stile eredita la formattazione di riempimento. |
| [getForeign()](#getForeign--) | Contiene elementi che specificano la larghezza e l'altezza di un oggetto proveniente da un altro programma utilizzato in un documento Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Contiene un BLOB codificato MIME (Multipurpose Internet Mail Extensions) di dati immagine, come metafile Windows, bitmap o dati OLE. |
| [getGroup()](#getGroup--) | Contiene gli elementi che controllano come aggiungere forme a un gruppo, spostare i membri di un gruppo e selezionare i gruppi. |
| [getHelp()](#getHelp--) | Contiene gli elementi che specificano l'argomento del file di aiuto dell'elemento Shape e le informazioni sul copyright. |
| [getID()](#getID--) | L'ID univoco dell'elemento all'interno del suo elemento genitore. |
| [getImage()](#getImage--) | Contiene i valori di gamma, luminosità, contrasto, sfocatura, nitidezza, riduzione del rumore e trasparenza per un bitmap. |
| [getLayout()](#getLayout--) | Contiene elementi che controllano il posizionamento delle forme e le impostazioni di instradamento dei connettori. |
| [getLine()](#getLine--) | Contiene elementi che controllano gli attributi di linea per una forma, come modello, spessore e colore. |
| [getLineStyle()](#getLineStyle--) | Elemento StyleSheet da cui questo stile eredita la formattazione della linea. |
| [getMisc()](#getMisc--) | Contiene gli elementi che specificano l'argomento del file di aiuto dell'elemento Shape e le informazioni sul copyright. |
| [getName()](#getName--) | Il nome dell'elemento. |
| [getNameU()](#getNameU--) | Il nome universale dell'elemento. |
| [getPageLayout()](#getPageLayout--) | Contiene Diagram che controlla le impostazioni di layout della pagina per forme e connettori, come la spaziatura tra tutte le forme sulla pagina, la spaziatura tra tutti i connettori sulla pagina e lo stile di instradamento per tutti i connettori sulla pagina. |
| [getParas()](#getParas--) | Contiene una raccolta di elementi Para. |
| [getProtection()](#getProtection--) | Il blocco aiuta a prevenire modifiche involontarie alla forma ma non impedisce a Microsoft Visio di ripristinare i valori in altre circostanze. |
| [getRulerGrid()](#getRulerGrid--) | Contiene elementi che specificano le impostazioni dei righelli e della griglia della pagina. |
| [getStyleProp()](#getStyleProp--) | Contiene elementi che controllano il comportamento dello stile, ad esempio se uno stile include attributi di testo, linea e riempimento. |
| [getTabsCollection()](#getTabsCollection--) | Contiene una raccolta di elementi Tab. |
| [getTextBlock()](#getTextBlock--) | Contiene elementi che specificano l'allineamento, i margini e le posizioni predefinite delle tabulazioni del testo nel blocco di testo di una forma. |
| [getTextStyle()](#getTextStyle--) | Elemento StyleSheet da cui questo stile eredita la formattazione del testo. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Per la descrizione di questa proprietà, vedere [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--) |
| [setID(int value)](#setID-int-) | Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/stylesheet\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Per la descrizione di questa proprietà, vedere [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/stylesheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Per la descrizione di questa proprietà, vedere [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StyleSheet() {#StyleSheet--}
```
public StyleSheet()
```


Costruttore.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia profonda di questa istanza.

**Returns:**
java.lang.Object -
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
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Contiene elementi che specificano formule che controllano gli eventi della forma.

**Returns:**
[Event](../../com.aspose.diagram/event)
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


Elemento StyleSheet da cui questo stile eredita la formattazione di riempimento.

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
### getID() {#getID--}
```
public int getID()
```


L'ID univoco dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getImage() {#getImage--}
```
public Image getImage()
```


Contiene i valori di gamma, luminosità, contrasto, sfocatura, nitidezza, riduzione del rumore e trasparenza per un bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
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


Elemento StyleSheet da cui questo stile eredita la formattazione della linea.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
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
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Contiene Diagram che controlla le impostazioni di layout della pagina per forme e connettori, come la spaziatura tra tutte le forme sulla pagina, la spaziatura tra tutti i connettori sulla pagina e lo stile di instradamento per tutti i connettori sulla pagina.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Contiene una raccolta di elementi Para.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Il blocco aiuta a prevenire modifiche involontarie alla forma ma non impedisce a Microsoft Visio di ripristinare i valori in altre circostanze. Inoltre non protegge dalle modifiche apportate nella finestra ShapeSheet.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Contiene elementi che specificano le impostazioni dei righelli e della griglia della pagina.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getStyleProp() {#getStyleProp--}
```
public StyleProp getStyleProp()
```


Contiene elementi che controllano il comportamento dello stile, ad esempio se uno stile include attributi di testo, linea e riempimento.

**Returns:**
[StyleProp](../../com.aspose.diagram/styleprop)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Contiene una raccolta di elementi Tab.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
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


Elemento StyleSheet da cui questo stile eredita la formattazione del testo.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Per la descrizione di questa proprietà, vedere [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/stylesheet\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Per la descrizione di questa proprietà, vedere [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Per la descrizione di questa proprietà, vedere [getName()](../../com.aspose.diagram/stylesheet\#getName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Per la descrizione di questa proprietà, vedere [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Per la descrizione di questa proprietà, vedere [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

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

