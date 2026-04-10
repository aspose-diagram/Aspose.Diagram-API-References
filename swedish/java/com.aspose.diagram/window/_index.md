---
title: Window
second_title: Aspose.Diagram för Java API-referens
description: Representerar ett öppet fönster i en Microsoft Visio-instans.
type: docs
weight: 444
url: /sv/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Representerar ett öppet fönster i en Microsoft Visio-instans. Detta element innehåller information som behövs för att exakt återskapa ett användargränssnittsfönster i applikationsarbetsytan när DatadiagramML-filen först öppnas av Visio.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Window()](#Window--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | ID för behållare: Sida, Ark eller Master. |
| [getContainerType()](#getContainerType--) | Kan vara ett av följande värden: Document, Page eller Master. |
| [getDocument()](#getDocument--) | Filsökväg för dokumentet som visas i detta fönster. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Anger om den dynamiska rutnätsfunktionen är aktiverad för ett dokument eller ett fönster. |
| [getGlueSettings()](#getGlueSettings--) | Anger de objekt som former limmas till när lim är aktiverat i dokumentet. |
| [getID()](#getID--) | Det unika ID:t för elementet inom dess överordnade element. |
| [getMaster()](#getMaster--) | Master-ID om detta fönster visar en master. |
| [getPage()](#getPage--) | Sid-ID om detta fönster visar en sida. |
| [getParentWindow()](#getParentWindow--) | ID för fönster som detta stencilsfönster är inbäddat i. |
| [getReadOnly()](#getReadOnly--) | Skrivskyddsflagga om detta stencil inte är ett dokumentstencil. |
| [getSheet()](#getSheet--) | ID för ark i behållare. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | Anger om anslutningspunkter visas i ett fönster. |
| [getShowGrid()](#getShowGrid--) | Anger om ett rutnät visas i ritfönstret. |
| [getShowGuides()](#getShowGuides--) | Anger om hjälplinjer visas i ritfönstret. |
| [getShowPageBreaks()](#getShowPageBreaks--) | Anger om sidbrytningar visas i ett fönster. |
| [getShowRulers()](#getShowRulers--) | Anger om linjaler visas i ritfönstret. |
| [getSnapAngles()](#getSnapAngles--) | Innehåller en samling av SnapAngle‑element. |
| [getSnapExtensions()](#getSnapExtensions--) | Specificerar om en specifik snap-förlängningsinställning är aktiverad eller inaktiverad för det aktiva fönstret. |
| [getSnapSettings()](#getSnapSettings--) | Specificerar de objekt som former fäster sig vid när snap är aktivt i fönstret. |
| [getStencilGroup()](#getStencilGroup--) | Anger gruppen av sammanslagna stencilsfönster som fönstret är medlem i. |
| [getStencilGroupPos()](#getStencilGroupPos--) | Innehåller ett heltal som anger den relativa positionen för ett stencil inom en grupp i ett fönster. |
| [getTabSplitterPos()](#getTabSplitterPos--) | Anger bredden på sidflikskontrollen i ett ritfönster (som en bråkdel av den totala bredden på ritfönstret). |
| [getViewCenterX()](#getViewCenterX--) | Valfri dubbel. |
| [getViewCenterY()](#getViewCenterY--) | Valfri dubbel. |
| [getViewScale()](#getViewScale--) | Valfri dubbel. |
| [getWindowHeight()](#getWindowHeight--) | Höjd på fönsterrektangeln. |
| [getWindowLeft()](#getWindowLeft--) | Vänsterkoordinat för fönsterrektangeln. |
| [getWindowState()](#getWindowState--) | Detta attribut kan vara en summa av följande värden. |
| [getWindowTop()](#getWindowTop--) | Övre koordinat för fönsterrektangeln. |
| [getWindowType()](#getWindowType--) | Ett uppräknat värde som kan vara ett av följande: Drawing, Sheet, Stencil eller Icon. Ett fönsterelement med WindowType='Stencil' måste förekomma efter dess föräldraritningsfönster (WindowType='Drawing') och före alla andra ritfönsterelement. |
| [getWindowWidth()](#getWindowWidth--) | Bredd på fönsterrektangeln. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | För beskrivningen av denna egenskap, se [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | För beskrivningen av denna egenskap, se [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | För beskrivningen av den här egenskapen, se [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | För beskrivningen av den här egenskapen, se [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | För beskrivningen av den här egenskapen, se [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | För beskrivningen av den här egenskapen, se [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | För beskrivningen av den här egenskapen, se [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | För beskrivningen av den här egenskapen, se [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | För beskrivningen av den här egenskapen, se [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | För beskrivningen av den här egenskapen, se [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | För beskrivningen av den här egenskapen, se [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | För beskrivningen av den här egenskapen, se [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | För beskrivningen av den här egenskapen, se [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | För beskrivningen av den här egenskapen, se [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | För beskrivningen av den här egenskapen, se [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | För beskrivningen av den här egenskapen, se [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | För beskrivningen av den här egenskapen, se [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | För beskrivningen av den här egenskapen, se [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | För beskrivningen av den här egenskapen, se [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | För beskrivningen av den här egenskapen, se [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | För beskrivningen av den här egenskapen, se [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | För beskrivningen av den här egenskapen, se [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | För beskrivningen av den här egenskapen, se [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | För beskrivningen av den här egenskapen, se [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | För beskrivningen av den här egenskapen, se [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | För beskrivningen av den här egenskapen, se [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | För beskrivningen av den här egenskapen, se [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | För beskrivningen av den här egenskapen, se [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | För beskrivningen av den här egenskapen, se [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | För beskrivningen av den här egenskapen, se [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
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
| Parameter | Typ | Beskrivning |
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


Behållarens ID: Page, Sheet eller Master. Endast relevant och nödvändig om ContainerType är specificerad.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


Kan vara ett av följande värden: Dokument, Sida eller Master. Endast relevant när WindowType anges som Drawing eller Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


Filväg till dokumentet som visas i detta fönster. Detta attribut är relevant för fönster vars WindowType är specificerad som Stencil.

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


Anger om den dynamiska rutnätsfunktionen är aktiverad för ett dokument eller ett fönster.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


Anger de objekt som former limmas till när lim är aktiverat i dokumentet.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Det unika ID:t för elementet inom dess överordnade element.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Master-ID om detta fönster visar en master.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


Sidans ID om detta fönster visar en sida. Relevant endast när WindowType är specificerad som Drawing och ContainerType är specificerad som Page.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


Fönstrets ID där detta stencil‑fönster finns. Relevant endast när WindowType är specificerad som Stencil.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


Skrivskyddsflagga om detta stencil inte är ett dokumentstencil.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


Bladets ID i behållaren. Relevant endast när Container är specificerad som Sheet.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


Anger om anslutningspunkter visas i ett fönster.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


Anger om ett rutnät visas i ritfönstret.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


Anger om hjälplinjer visas i ritfönstret.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


Anger om sidbrytningar visas i ett fönster.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


Anger om linjaler visas i ritfönstret.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


Innehåller en samling av SnapAngle‑element.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


Anger om en specifik snap‑utökninginställning är aktiverad eller inaktiverad för det aktiva fönstret. Värdet kan vara en summa av värdena i följande tabell.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Anger de objekt som former fäster sig vid när fästning är aktiv i fönstret. Värdet kan vara en summa av värdena i följande tabell.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


Anger gruppen av sammanslagna stencil‑fönster som detta fönster tillhör. Detta attribut är endast relevant för Window‑element vars WindowType‑attribut är Stencil, och endast om stencil‑fönstret är en del av en sammanslagen grupp av stencil‑fönster. Alla stencil‑fönster som är en del av samma sammanslagna grupp har samma StencilGroup‑elementvärde.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


Innehåller ett heltal som anger den relativa positionen för ett stencil inom en grupp i ett fönster.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


Anger bredden på sidflikskontrollen i ett ritfönster (som en bråkdel av den totala bredden på ritfönstret).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


Valfri dubbel.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


Valfri dubbel.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Valfri dubbel.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


Höjd på fönsterrektangeln.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


Vänsterkoordinat för fönsterrektangeln.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


Detta attribut kan vara en summa av följande värden.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


Övre koordinat för fönsterrektangeln.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


Ett uppräknat värde som kan vara ett av följande: Drawing, Sheet, Stencil eller Icon. Ett fönsterelement med WindowType='Stencil' måste förekomma efter dess föräldraritningsfönster (WindowType='Drawing') och före alla andra ritfönsterelement.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


Bredd på fönsterrektangeln.

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


För beskrivningen av denna egenskap, se [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


För beskrivningen av denna egenskap, se [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


För beskrivningen av den här egenskapen, se [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


För beskrivningen av den här egenskapen, se [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


För beskrivningen av den här egenskapen, se [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


För beskrivningen av den här egenskapen, se [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


För beskrivningen av den här egenskapen, se [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


För beskrivningen av den här egenskapen, se [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


För beskrivningen av den här egenskapen, se [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


För beskrivningen av den här egenskapen, se [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


För beskrivningen av den här egenskapen, se [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


För beskrivningen av den här egenskapen, se [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


För beskrivningen av den här egenskapen, se [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


För beskrivningen av den här egenskapen, se [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


För beskrivningen av den här egenskapen, se [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


För beskrivningen av den här egenskapen, se [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


För beskrivningen av den här egenskapen, se [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


För beskrivningen av den här egenskapen, se [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


För beskrivningen av den här egenskapen, se [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


För beskrivningen av den här egenskapen, se [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


För beskrivningen av den här egenskapen, se [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


För beskrivningen av den här egenskapen, se [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


För beskrivningen av den här egenskapen, se [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


För beskrivningen av den här egenskapen, se [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


För beskrivningen av den här egenskapen, se [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


För beskrivningen av den här egenskapen, se [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


För beskrivningen av den här egenskapen, se [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


För beskrivningen av den här egenskapen, se [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


För beskrivningen av den här egenskapen, se [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


För beskrivningen av den här egenskapen, se [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

