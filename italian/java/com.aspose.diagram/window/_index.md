---
title: Window
second_title: Riferimento API di Aspose.Diagram per Java
description: Rappresenta una finestra aperta in un'istanza di Microsoft Visio.
type: docs
weight: 444
url: /it/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Rappresenta una finestra aperta in un'istanza di Microsoft Visio. Questo elemento contiene le informazioni necessarie per ricreare esattamente una finestra dell'interfaccia utente nello spazio di lavoro dell'applicazione quando il file DatadiagramML viene aperto inizialmente da Visio.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Window()](#Window--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | ID del contenitore: Pagina, Foglio o Master. |
| [getContainerType()](#getContainerType--) | Può essere uno dei seguenti valori: Document, Page o Master. |
| [getDocument()](#getDocument--) | Percorso file del documento visualizzato in questa finestra. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Specifica se la funzionalità griglia dinamica è abilitata per un documento o una finestra. |
| [getGlueSettings()](#getGlueSettings--) | Specifica gli oggetti a cui le forme si incollano quando la colla è abilitata nel documento. |
| [getID()](#getID--) | L'ID univoco dell'elemento all'interno del suo elemento genitore. |
| [getMaster()](#getMaster--) | ID del master se questa finestra sta visualizzando un master. |
| [getPage()](#getPage--) | ID della pagina se questa finestra sta visualizzando una pagina. |
| [getParentWindow()](#getParentWindow--) | ID della finestra in cui è contenuta questa finestra stencil. |
| [getReadOnly()](#getReadOnly--) | Flag di sola lettura se questo stencil non è uno stencil di documento. |
| [getSheet()](#getSheet--) | ID del foglio nel contenitore. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | Specifica se i punti di connessione sono mostrati in una finestra. |
| [getShowGrid()](#getShowGrid--) | Specifica se una griglia è mostrata nella finestra di disegno. |
| [getShowGuides()](#getShowGuides--) | Specifica se le guide sono mostrate nella finestra di disegno. |
| [getShowPageBreaks()](#getShowPageBreaks--) | Specifica se le interruzioni di pagina sono mostrate in una finestra. |
| [getShowRulers()](#getShowRulers--) | Specifica se i righelli sono mostrati nella finestra di disegno. |
| [getSnapAngles()](#getSnapAngles--) | Contiene una raccolta di elementi SnapAngle. |
| [getSnapExtensions()](#getSnapExtensions--) | Specifica se un'impostazione specifica di estensione snap è abilitata o disabilitata per la finestra attiva. |
| [getSnapSettings()](#getSnapSettings--) | Specifica gli oggetti a cui le forme si agganciano quando lo snap è attivo nella finestra. |
| [getStencilGroup()](#getStencilGroup--) | Specifica il gruppo di finestre stencil unite di cui la finestra è membro. |
| [getStencilGroupPos()](#getStencilGroupPos--) | Contiene un intero che specifica la posizione relativa di uno stencil all'interno di un gruppo in una finestra. |
| [getTabSplitterPos()](#getTabSplitterPos--) | Specifica la larghezza del controllo della scheda pagina di una finestra di disegno (come frazione della larghezza totale della finestra di disegno). |
| [getViewCenterX()](#getViewCenterX--) | Double opzionale. |
| [getViewCenterY()](#getViewCenterY--) | Double opzionale. |
| [getViewScale()](#getViewScale--) | Double opzionale. |
| [getWindowHeight()](#getWindowHeight--) | Altezza del rettangolo della finestra. |
| [getWindowLeft()](#getWindowLeft--) | Coordinata sinistra del rettangolo della finestra. |
| [getWindowState()](#getWindowState--) | Questo attributo può essere una somma dei seguenti valori. |
| [getWindowTop()](#getWindowTop--) | Coordinata superiore del rettangolo della finestra. |
| [getWindowType()](#getWindowType--) | Un valore enumerato che può essere uno dei seguenti: Drawing, Sheet, Stencil o Icon. Un elemento Window con WindowType='Stencil' deve apparire dopo la sua finestra di disegno padre (WindowType='Drawing') e prima di qualsiasi altro elemento di finestra di disegno. |
| [getWindowWidth()](#getWindowWidth--) | Larghezza del rettangolo della finestra. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | Per la descrizione di questa proprietà, vedere [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | Per la descrizione di questa proprietà, vedere [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | Per la descrizione di questa proprietà, vedere [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | Per la descrizione di questa proprietà, vedere [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Per la descrizione di questa proprietà, vedere [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Per la descrizione di questa proprietà, vedere [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | Per la descrizione di questa proprietà, vedere [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | Per la descrizione di questa proprietà, vedere [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | Per la descrizione di questa proprietà, vedere [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | Per la descrizione di questa proprietà, vedere [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | Per la descrizione di questa proprietà, vedere [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | Per la descrizione di questa proprietà, vedere [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | Per la descrizione di questa proprietà, vedere [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | Per la descrizione di questa proprietà, vedere [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | Per la descrizione di questa proprietà, vedere [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | Per la descrizione di questa proprietà, vedere [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | Per la descrizione di questa proprietà, vedere [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | Per la descrizione di questa proprietà, vedere [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | Per la descrizione di questa proprietà, vedere [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Per la descrizione di questa proprietà, vedere [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Per la descrizione di questa proprietà, vedere [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Per la descrizione di questa proprietà, vedere [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | Per la descrizione di questa proprietà, vedere [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | Per la descrizione di questa proprietà, vedere [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | Per la descrizione di questa proprietà, vedere [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | Per la descrizione di questa proprietà, vedere [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | Per la descrizione di questa proprietà, vedere [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | Per la descrizione di questa proprietà, vedere [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
```


Costruttore.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public int getContainer()
```


ID del contenitore: Page, Sheet o Master. Rilevante e necessario solo se è specificato ContainerType.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


Percorso file del documento visualizzato in questa finestra. Questo attributo è rilevante per le finestre il cui WindowType è specificato come Stencil.

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


Specifica se la funzionalità griglia dinamica è abilitata per un documento o una finestra.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


Specifica gli oggetti a cui le forme si incollano quando la colla è abilitata nel documento.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


L'ID univoco dell'elemento all'interno del suo elemento genitore.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


ID del master se questa finestra sta visualizzando un master.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


ID della pagina se questa finestra visualizza una pagina. Rilevante solo quando WindowType è specificato come Drawing e ContainerType è specificato come Page.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


ID della finestra in cui è contenuta questa finestra stencil. Rilevante solo quando WindowType è specificato come Stencil.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


Flag di sola lettura se questo stencil non è uno stencil di documento.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


ID del foglio nel contenitore. Rilevante solo quando Container è specificato come Sheet.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


Specifica se i punti di connessione sono mostrati in una finestra.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


Specifica se una griglia è mostrata nella finestra di disegno.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


Specifica se le guide sono mostrate nella finestra di disegno.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


Specifica se le interruzioni di pagina sono mostrate in una finestra.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


Specifica se i righelli sono mostrati nella finestra di disegno.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


Contiene una raccolta di elementi SnapAngle.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


Specifica se un'impostazione di estensione di aggancio specifica è abilitata o disabilitata per la finestra attiva. Il valore può essere la somma dei valori nella tabella seguente.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Specifica gli oggetti a cui le forme si agganciano quando l'aggancio è attivo nella finestra. Il valore può essere la somma dei valori nella tabella seguente.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


Specifica il gruppo di finestre stencil unite di cui la finestra è membro. Questo attributo è rilevante solo per gli elementi Window il cui attributo WindowType è Stencil, e solo se la finestra stencil fa parte di un gruppo unito di finestre stencil. Tutte le finestre stencil che fanno parte dello stesso gruppo unito hanno lo stesso valore dell'elemento StencilGroup.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


Contiene un intero che specifica la posizione relativa di uno stencil all'interno di un gruppo in una finestra.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


Specifica la larghezza del controllo della scheda pagina di una finestra di disegno (come frazione della larghezza totale della finestra di disegno).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


Double opzionale.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


Double opzionale.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Double opzionale.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


Altezza del rettangolo della finestra.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


Coordinata sinistra del rettangolo della finestra.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


Questo attributo può essere una somma dei seguenti valori.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


Coordinata superiore del rettangolo della finestra.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


Un valore enumerato che può essere uno dei seguenti: Drawing, Sheet, Stencil o Icon. Un elemento Window con WindowType='Stencil' deve apparire dopo la sua finestra di disegno padre (WindowType='Drawing') e prima di qualsiasi altro elemento di finestra di disegno.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


Larghezza del rettangolo della finestra.

**Returns:**
long
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




### setContainer(int value) {#setContainer-int-}
```
public void setContainer(int value)
```


Per la descrizione di questa proprietà, vedere [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


Per la descrizione di questa proprietà, vedere [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


Per la descrizione di questa proprietà, vedere [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


Per la descrizione di questa proprietà, vedere [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


Per la descrizione di questa proprietà, vedere [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Per la descrizione di questa proprietà, vedere [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Per la descrizione di questa proprietà, vedere [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Per la descrizione di questa proprietà, vedere [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


Per la descrizione di questa proprietà, vedere [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


Per la descrizione di questa proprietà, vedere [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


Per la descrizione di questa proprietà, vedere [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


Per la descrizione di questa proprietà, vedere [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


Per la descrizione di questa proprietà, vedere [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


Per la descrizione di questa proprietà, vedere [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


Per la descrizione di questa proprietà, vedere [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


Per la descrizione di questa proprietà, vedere [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


Per la descrizione di questa proprietà, vedere [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


Per la descrizione di questa proprietà, vedere [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


Per la descrizione di questa proprietà, vedere [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


Per la descrizione di questa proprietà, vedere [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


Per la descrizione di questa proprietà, vedere [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Per la descrizione di questa proprietà, vedere [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Per la descrizione di questa proprietà, vedere [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Per la descrizione di questa proprietà, vedere [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


Per la descrizione di questa proprietà, vedere [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


Per la descrizione di questa proprietà, vedere [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


Per la descrizione di questa proprietà, vedere [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


Per la descrizione di questa proprietà, vedere [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


Per la descrizione di questa proprietà, vedere [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


Per la descrizione di questa proprietà, vedere [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

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

