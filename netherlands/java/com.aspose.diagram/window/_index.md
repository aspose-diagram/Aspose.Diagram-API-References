---
title: Window
second_title: Aspose.Diagram voor Java API-referentie
description: Stelt een geopend venster in een Microsoft Visio‑instantie voor.
type: docs
weight: 444
url: /nl/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Stelt een geopend venster voor in een Microsoft Visio‑instantie. Dit element bevat de informatie die nodig is om een gebruikersinterface‑venster precies opnieuw te maken in de toepassingswerkruimte wanneer het DatadiagramML‑bestand voor het eerst door Visio wordt geopend.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Window()](#Window--) | Constructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | ID van container: Pagina, Blad of Master. |
| [getContainerType()](#getContainerType--) | Kan een van de volgende waarden zijn: Document, Page of Master. |
| [getDocument()](#getDocument--) | Bestandspad van het document dat in dit venster wordt weergegeven. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Specificeert of de dynamische rasterfunctie is ingeschakeld voor een document of venster. |
| [getGlueSettings()](#getGlueSettings--) | Specificeert de objecten waaraan vormen worden geplakt wanneer lijm is ingeschakeld in het document. |
| [getID()](#getID--) | De unieke ID van het element binnen het bovenliggende element. |
| [getMaster()](#getMaster--) | Master‑ID als dit venster een master weergeeft. |
| [getPage()](#getPage--) | Pagina‑ID als dit venster een pagina weergeeft. |
| [getParentWindow()](#getParentWindow--) | ID van het venster waarin dit sjabloonvenster zich bevindt. |
| [getReadOnly()](#getReadOnly--) | Alleen‑lezen‑vlag als dit sjabloon geen document‑sjabloon is. |
| [getSheet()](#getSheet--) | ID van blad in container. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | Specificeert of verbindingspunten in een venster worden weergegeven. |
| [getShowGrid()](#getShowGrid--) | Specificeert of een raster in het tekenvenster wordt weergegeven. |
| [getShowGuides()](#getShowGuides--) | Specificeert of hulplijnen in het tekenvenster worden weergegeven. |
| [getShowPageBreaks()](#getShowPageBreaks--) | Specificeert of pagina‑eindes in een venster worden weergegeven. |
| [getShowRulers()](#getShowRulers--) | Specificeert of linialen in het tekenvenster worden weergegeven. |
| [getSnapAngles()](#getSnapAngles--) | Bevat een verzameling SnapAngle‑elementen. |
| [getSnapExtensions()](#getSnapExtensions--) | Specificeert of een specifieke snap-extensie-instelling is ingeschakeld of uitgeschakeld voor het actieve venster. |
| [getSnapSettings()](#getSnapSettings--) | Specificeert de objecten waaraan vormen zich vastklikken wanneer snap actief is in het venster. |
| [getStencilGroup()](#getStencilGroup--) | Specificeert de groep van samengevoegde sjabloonvensters waarvan het venster lid is. |
| [getStencilGroupPos()](#getStencilGroupPos--) | Bevat een geheel getal dat de relatieve positie van een sjabloon binnen een groep in een venster specificeert. |
| [getTabSplitterPos()](#getTabSplitterPos--) | Specificeert de breedte van de paginatab‑bediening van een tekenvenster (als een fractie van de totale breedte van het tekenvenster). |
| [getViewCenterX()](#getViewCenterX--) | Optioneel double. |
| [getViewCenterY()](#getViewCenterY--) | Optioneel double. |
| [getViewScale()](#getViewScale--) | Optioneel double. |
| [getWindowHeight()](#getWindowHeight--) | Hoogte van de vensterrechthoek. |
| [getWindowLeft()](#getWindowLeft--) | Linker coördinaat van de vensterrechthoek. |
| [getWindowState()](#getWindowState--) | Dit attribuut kan een som zijn van de volgende waarden. |
| [getWindowTop()](#getWindowTop--) | Bovenste coördinaat van de vensterrechthoek. |
| [getWindowType()](#getWindowType--) | Een genummerde waarde die een van de volgende kan zijn: Drawing, Sheet, Stencil of Icon. Een Window‑element met WindowType='Stencil' moet verschijnen na zijn bovenliggende tekenvenster (WindowType='Drawing') en vóór alle andere tekenvensterelementen. |
| [getWindowWidth()](#getWindowWidth--) | Breedte van de vensterrechthoek. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | Voor de beschrijving van deze eigenschap, zie [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | Voor de beschrijving van deze eigenschap, zie [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | Voor de beschrijving van deze eigenschap, zie [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | Voor de beschrijving van deze eigenschap, zie [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Voor de beschrijving van deze eigenschap, zie [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Voor de beschrijving van deze eigenschap, zie [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | Voor de beschrijving van deze eigenschap, zie [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | Voor de beschrijving van deze eigenschap, zie [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | Voor de beschrijving van deze eigenschap, zie [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | Voor de beschrijving van deze eigenschap, zie [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | Voor de beschrijving van deze eigenschap, zie [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | Voor de beschrijving van deze eigenschap, zie [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | Voor de beschrijving van deze eigenschap, zie [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | Voor de beschrijving van deze eigenschap, zie [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | Voor de beschrijving van deze eigenschap, zie [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | Voor de beschrijving van deze eigenschap, zie [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | Voor de beschrijving van deze eigenschap, zie [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | Voor de beschrijving van deze eigenschap, zie [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Voor de beschrijving van deze eigenschap, zie [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Voor de beschrijving van deze eigenschap, zie [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Voor de beschrijving van deze eigenschap, zie [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | Voor de beschrijving van deze eigenschap, zie [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | Voor de beschrijving van deze eigenschap, zie [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | Voor de beschrijving van deze eigenschap, zie [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | Voor de beschrijving van deze eigenschap, zie [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | Voor de beschrijving van deze eigenschap, zie [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | Voor de beschrijving van deze eigenschap, zie [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
```


Constructor.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


ID van container: Pagina, Werkblad of Master. Alleen relevant en noodzakelijk als ContainerType is gespecificeerd.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


Kan een van de volgende waarden zijn: Document, Page of Master. Alleen relevant wanneer WindowType is opgegeven als Drawing of Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


Bestandspad van het document dat in dit venster wordt weergegeven. Dit attribuut is relevant voor vensters waarvan WindowType is gespecificeerd als Stencil.

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


Specificeert of de dynamische rasterfunctie is ingeschakeld voor een document of venster.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


Specificeert de objecten waaraan vormen worden geplakt wanneer lijm is ingeschakeld in het document.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


De unieke ID van het element binnen het bovenliggende element.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Master‑ID als dit venster een master weergeeft.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


Pagina-ID als dit venster een pagina weergeeft. Alleen relevant wanneer WindowType is gespecificeerd als Drawing en ContainerType is gespecificeerd als Page.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


ID van het venster waarin dit stencil-venster is opgenomen. Alleen relevant wanneer WindowType is gespecificeerd als Stencil.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


Alleen‑lezen‑vlag als dit sjabloon geen document‑sjabloon is.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


ID van werkblad in container. Alleen relevant wanneer Container is gespecificeerd als Sheet.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


Specificeert of verbindingspunten in een venster worden weergegeven.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


Specificeert of een raster in het tekenvenster wordt weergegeven.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


Specificeert of hulplijnen in het tekenvenster worden weergegeven.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


Specificeert of pagina‑eindes in een venster worden weergegeven.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


Specificeert of linialen in het tekenvenster worden weergegeven.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


Bevat een verzameling SnapAngle‑elementen.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


Specificeert of een specifieke snap-extensie-instelling is ingeschakeld of uitgeschakeld voor het actieve venster. De waarde kan een som zijn van de waarden in de volgende tabel.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Specificeert de objecten waaraan vormen zich vastklikken wanneer snap actief is in het venster. De waarde kan een som zijn van de waarden in de onderstaande tabel.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


Specificeert de groep van samengevoegde stencil-vensters waar dit venster deel van uitmaakt. Dit attribuut is alleen relevant voor Window-elementen waarvan het WindowType-attribuut Stencil is, en alleen als het stencil-venster deel uitmaakt van een samengevoegde groep stencil-vensters. Alle stencil-vensters die deel uitmaken van dezelfde samengevoegde groep hebben dezelfde StencilGroup-elementwaarde.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


Bevat een geheel getal dat de relatieve positie van een sjabloon binnen een groep in een venster specificeert.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


Specificeert de breedte van de paginatab‑bediening van een tekenvenster (als een fractie van de totale breedte van het tekenvenster).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


Optioneel double.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


Optioneel double.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Optioneel double.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


Hoogte van de vensterrechthoek.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


Linker coördinaat van de vensterrechthoek.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


Dit attribuut kan een som zijn van de volgende waarden.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


Bovenste coördinaat van de vensterrechthoek.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


Een genummerde waarde die een van de volgende kan zijn: Drawing, Sheet, Stencil of Icon. Een Window‑element met WindowType='Stencil' moet verschijnen na zijn bovenliggende tekenvenster (WindowType='Drawing') en vóór alle andere tekenvensterelementen.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


Breedte van de vensterrechthoek.

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


Voor de beschrijving van deze eigenschap, zie [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


Voor de beschrijving van deze eigenschap, zie [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


Voor de beschrijving van deze eigenschap, zie [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


Voor de beschrijving van deze eigenschap, zie [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


Voor de beschrijving van deze eigenschap, zie [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Voor de beschrijving van deze eigenschap, zie [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Voor de beschrijving van deze eigenschap, zie [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


Voor de beschrijving van deze eigenschap, zie [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


Voor de beschrijving van deze eigenschap, zie [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


Voor de beschrijving van deze eigenschap, zie [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


Voor de beschrijving van deze eigenschap, zie [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


Voor de beschrijving van deze eigenschap, zie [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


Voor de beschrijving van deze eigenschap, zie [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


Voor de beschrijving van deze eigenschap, zie [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


Voor de beschrijving van deze eigenschap, zie [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


Voor de beschrijving van deze eigenschap, zie [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


Voor de beschrijving van deze eigenschap, zie [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


Voor de beschrijving van deze eigenschap, zie [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Voor de beschrijving van deze eigenschap, zie [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Voor de beschrijving van deze eigenschap, zie [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Voor de beschrijving van deze eigenschap, zie [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


Voor de beschrijving van deze eigenschap, zie [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


Voor de beschrijving van deze eigenschap, zie [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


Voor de beschrijving van deze eigenschap, zie [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


Voor de beschrijving van deze eigenschap, zie [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


Voor de beschrijving van deze eigenschap, zie [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


Voor de beschrijving van deze eigenschap, zie [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

