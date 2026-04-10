---
title: PageSheet
second_title: Riferimento API di Aspose.Diagram per Java
description: Contiene elementi che definiscono il foglio di pagina per un elemento Pagina o Master.
type: docs
weight: 270
url: /it/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

Contiene elementi che definiscono il foglio di pagina per un elemento Pagina o Master.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | Copia il pagesheet da un oggetto sorgente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | Contiene una raccolta di elementi Act. |
| [getAnnotations()](#getAnnotations--) | Contiene elementi che includono informazioni sui commenti inseriti in una pagina del documento. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Contiene una raccolta di elementi ConnectionABCD. |
| [getConnections()](#getConnections--) | Contiene una raccolta di elementi Connection. |
| [getFillStyle()](#getFillStyle--) | Elemento StyleSheet da cui il PageSheet eredita la formattazione di riempimento. |
| [getForeign()](#getForeign--) | Contiene elementi che specificano la larghezza e l'altezza di un oggetto proveniente da un altro programma utilizzato in un documento Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Contiene un BLOB codificato MIME (Multipurpose Internet Mail Extensions) di dati immagine, come metafile Windows, bitmap o dati OLE. |
| [getHyperlinks()](#getHyperlinks--) | Contiene una raccolta di elementi Hyperlink. |
| [getLayers()](#getLayers--) | Contiene una raccolta di elementi Layer. |
| [getLineStyle()](#getLineStyle--) | Elemento StyleSheet da cui il PageSheet eredita la formattazione delle linee. |
| [getPageLayout()](#getPageLayout--) | Contiene Diagram che controlla le impostazioni di layout della pagina per forme e connettori, come la spaziatura tra tutte le forme sulla pagina, la spaziatura tra tutti i connettori sulla pagina e lo stile di instradamento per tutti i connettori sulla pagina. |
| [getPageProps()](#getPageProps--) | Contiene Diagram che controlla gli attributi della pagina, come larghezza, altezza e scala della pagina. |
| [getPrintProps()](#getPrintProps--) | Contiene elementi che controllano come la pagina di disegno è formattata (appare) sulla pagina della stampante. |
| [getProps()](#getProps--) | Contiene una raccolta di elementi Prop. |
| [getRulerGrid()](#getRulerGrid--) | Contiene elementi che specificano le impostazioni dei righelli e della griglia della pagina. |
| [getScratchs()](#getScratchs--) | Contiene una raccolta di elementi Scratch. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Contiene una raccolta di elementi SmartTagDef. |
| [getTextStyle()](#getTextStyle--) | Elemento StyleSheet da cui il PageSheet eredita la formattazione del testo. |
| [getUniqueID()](#getUniqueID--) | Un GUID (identificatore univoco globale) per l'elemento. |
| [getUsers()](#getUsers--) | Contiene una raccolta di elementi Utente. |
| [getXForm()](#getXForm--) | Contiene elementi che specificano informazioni generali di posizionamento su una forma. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Per la descrizione di questa proprietà, vedere [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Per la descrizione di questa proprietà, vedere [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### copy(PageSheet source) {#copy-com.aspose.diagram.PageSheet-}
```
public void copy(PageSheet source)
```


Copia il pagesheet da un oggetto sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | source pagesheet. |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Contiene una raccolta di elementi Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Contiene elementi che includono informazioni sui commenti inseriti in una pagina del documento.

**Returns:**
[AnnotationCollection](../../com.aspose.diagram/annotationcollection)
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
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Elemento StyleSheet da cui il PageSheet eredita la formattazione di riempimento.

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
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Contiene una raccolta di elementi Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


Contiene una raccolta di elementi Layer.

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Elemento StyleSheet da cui il PageSheet eredita la formattazione delle linee.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Contiene Diagram che controlla le impostazioni di layout della pagina per forme e connettori, come la spaziatura tra tutte le forme sulla pagina, la spaziatura tra tutti i connettori sulla pagina e lo stile di instradamento per tutti i connettori sulla pagina.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


Contiene Diagram che controlla gli attributi della pagina, come larghezza, altezza e scala della pagina.

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


Contiene elementi che controllano come la pagina di disegno è formattata (appare) sulla pagina della stampante.

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Contiene una raccolta di elementi Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Contiene elementi che specificano le impostazioni dei righelli e della griglia della pagina.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Contiene una raccolta di elementi Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Contiene una raccolta di elementi SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Elemento StyleSheet da cui il PageSheet eredita la formattazione del testo.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Un GUID (identificatore univoco globale) per l'elemento.

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


Per la descrizione di questa proprietà, vedere [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Per la descrizione di questa proprietà, vedere [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.UUID |  |

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

