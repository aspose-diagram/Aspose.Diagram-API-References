---
title: Window
second_title: Aspose.Diagram for Java API-Referenz
description: Stellt ein offenes Fenster in einer Microsoft‑Visio‑Instanz dar.
type: docs
weight: 444
url: /de/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Stellt ein offenes Fenster in einer Microsoft Visio-Instanz dar. Dieses Element enthält die Informationen, die erforderlich sind, um ein Benutzeroberflächenfenster im Anwendungsarbeitsbereich exakt wiederherzustellen, wenn die DatadiagramML-Datei zunächst von Visio geöffnet wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Window()](#Window--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | ID des Containers: Seite, Blatt oder Master. |
| [getContainerType()](#getContainerType--) | Kann einen der folgenden Werte haben: Document, Page oder Master. |
| [getDocument()](#getDocument--) | Dateipfad des in diesem Fenster angezeigten Dokuments. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Gibt an, ob die dynamische Rasterfunktion für ein Dokument oder Fenster aktiviert ist. |
| [getGlueSettings()](#getGlueSettings--) | Gibt die Objekte an, an die Formen geklebt werden, wenn Kleben im Dokument aktiviert ist. |
| [getID()](#getID--) | Die eindeutige ID des Elements innerhalb seines übergeordneten Elements. |
| [getMaster()](#getMaster--) | Master-ID, wenn dieses Fenster einen Master anzeigt. |
| [getPage()](#getPage--) | Seiten-ID, wenn dieses Fenster eine Seite anzeigt. |
| [getParentWindow()](#getParentWindow--) | ID des Fensters, in dem dieses Stencil-Fenster enthalten ist. |
| [getReadOnly()](#getReadOnly--) | Nur-Lese-Flag, wenn dieses Stencil kein Dokument-Stencil ist. |
| [getSheet()](#getSheet--) | ID des Blatts im Container. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | Gibt an, ob Verbindungspunkte in einem Fenster angezeigt werden. |
| [getShowGrid()](#getShowGrid--) | Gibt an, ob ein Raster im Zeichenfenster angezeigt wird. |
| [getShowGuides()](#getShowGuides--) | Gibt an, ob Hilfslinien im Zeichenfenster angezeigt werden. |
| [getShowPageBreaks()](#getShowPageBreaks--) | Gibt an, ob Seitenumbrüche in einem Fenster angezeigt werden. |
| [getShowRulers()](#getShowRulers--) | Gibt an, ob Lineale im Zeichenfenster angezeigt werden. |
| [getSnapAngles()](#getSnapAngles--) | Enthält eine Sammlung von SnapAngle-Elementen. |
| [getSnapExtensions()](#getSnapExtensions--) | Gibt an, ob eine bestimmte Snap‑Erweiterungseinstellung für das aktive Fenster aktiviert oder deaktiviert ist. |
| [getSnapSettings()](#getSnapSettings--) | Gibt die Objekte an, an die Formen einrasten, wenn das Einrasten im Fenster aktiv ist. |
| [getStencilGroup()](#getStencilGroup--) | Gibt die Gruppe zusammengeführter Stencil-Fenster an, deren Mitglied dieses Fenster ist. |
| [getStencilGroupPos()](#getStencilGroupPos--) | Enthält eine ganze Zahl, die die relative Position eines Stencils innerhalb einer Gruppe in einem Fenster angibt. |
| [getTabSplitterPos()](#getTabSplitterPos--) | Gibt die Breite der Seitenregister-Steuerung eines Zeichenfensters an (als Bruchteil der Gesamtheit der Breite des Zeichenfensters). |
| [getViewCenterX()](#getViewCenterX--) | Optionaler Double. |
| [getViewCenterY()](#getViewCenterY--) | Optionaler Double. |
| [getViewScale()](#getViewScale--) | Optionaler Double. |
| [getWindowHeight()](#getWindowHeight--) | Höhe des Fensterrechtecks. |
| [getWindowLeft()](#getWindowLeft--) | Linke Koordinate des Fensterrechtecks. |
| [getWindowState()](#getWindowState--) | Dieses Attribut kann die Summe der folgenden Werte sein. |
| [getWindowTop()](#getWindowTop--) | Obere Koordinate des Fensterrechtecks. |
| [getWindowType()](#getWindowType--) | Ein aufzählbarer Wert, der einer der folgenden sein kann: Drawing, Sheet, Stencil oder Icon. Ein Window-Element mit WindowType='Stencil' muss nach seinem übergeordneten Zeichenfenster (WindowType='Drawing') und vor allen anderen Zeichenfenster-Elementen erscheinen. |
| [getWindowWidth()](#getWindowWidth--) | Breite des Fensterrechtecks. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
```


Konstruktor.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


ID des Containers: Seite, Blatt oder Master. Nur relevant und erforderlich, wenn ContainerType angegeben ist.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


Kann einer der folgenden Werte sein: Dokument, Seite oder Master. Nur relevant, wenn WindowType als Zeichnung oder Blatt angegeben ist.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


Dateipfad des im Fenster angezeigten Dokuments. Dieses Attribut ist relevant für Fenster, deren WindowType als Stencil angegeben ist.

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


Gibt an, ob die dynamische Rasterfunktion für ein Dokument oder Fenster aktiviert ist.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


Gibt die Objekte an, an die Formen geklebt werden, wenn Kleben im Dokument aktiviert ist.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Die eindeutige ID des Elements innerhalb seines übergeordneten Elements.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Master-ID, wenn dieses Fenster einen Master anzeigt.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


Seiten-ID, wenn dieses Fenster eine Seite anzeigt. Nur relevant, wenn WindowType als Drawing angegeben ist und ContainerType als Page angegeben ist.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


ID des Fensters, in dem dieses Stencil-Fenster enthalten ist. Nur relevant, wenn WindowType als Stencil angegeben ist.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


Nur-Lese-Flag, wenn dieses Stencil kein Dokument-Stencil ist.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


ID des Blatts im Container. Nur relevant, wenn Container als Sheet angegeben ist.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


Gibt an, ob Verbindungspunkte in einem Fenster angezeigt werden.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


Gibt an, ob ein Raster im Zeichenfenster angezeigt wird.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


Gibt an, ob Hilfslinien im Zeichenfenster angezeigt werden.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


Gibt an, ob Seitenumbrüche in einem Fenster angezeigt werden.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


Gibt an, ob Lineale im Zeichenfenster angezeigt werden.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


Enthält eine Sammlung von SnapAngle-Elementen.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


Specifies whether a specific snap extension setting is enabled or disabled for the active window. The value can be a sum of the values in the following table.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Gibt die Objekte an, an denen Formen einrasten, wenn das Einrasten im Fenster aktiv ist. Der Wert kann die Summe der Werte in der folgenden Tabelle sein.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


Gibt die Gruppe zusammengeführter Stencil-Fenster an, deren Mitglied dieses Fenster ist. Dieses Attribut ist nur für Window-Elemente relevant, deren WindowType-Attribut Stencil ist, und nur, wenn das Stencil-Fenster Teil einer zusammengeführten Gruppe von Stencil-Fenstern ist. Alle Stencil-Fenster, die Teil derselben zusammengeführten Gruppe sind, haben denselben StencilGroup-Elementwert.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


Enthält eine ganze Zahl, die die relative Position eines Stencils innerhalb einer Gruppe in einem Fenster angibt.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


Gibt die Breite der Seitenregister-Steuerung eines Zeichenfensters an (als Bruchteil der Gesamtheit der Breite des Zeichenfensters).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


Optionaler Double.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


Optionaler Double.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Optionaler Double.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


Höhe des Fensterrechtecks.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


Linke Koordinate des Fensterrechtecks.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


Dieses Attribut kann die Summe der folgenden Werte sein.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


Obere Koordinate des Fensterrechtecks.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


Ein aufzählbarer Wert, der einer der folgenden sein kann: Drawing, Sheet, Stencil oder Icon. Ein Window-Element mit WindowType='Stencil' muss nach seinem übergeordneten Zeichenfenster (WindowType='Drawing') und vor allen anderen Zeichenfenster-Elementen erscheinen.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


Breite des Fensterrechtecks.

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


Für die Beschreibung dieser Eigenschaft siehe bitte [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

