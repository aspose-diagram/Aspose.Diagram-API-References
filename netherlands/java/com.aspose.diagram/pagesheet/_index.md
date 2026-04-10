---
title: PageSheet
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen die het paginablad definiëren voor een Pagina- of Master-element.
type: docs
weight: 270
url: /nl/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

Bevat elementen die het paginablad definiëren voor een Pagina- of Master-element.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | Kopieert pagesheet van een bronobject. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | Bevat een verzameling Act-elementen. |
| [getAnnotations()](#getAnnotations--) | Bevat elementen die informatie bevatten over opmerkingen die in een documentpagina zijn ingevoegd. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Bevat een verzameling van ConnectionABCD-elementen. |
| [getConnections()](#getConnections--) | Bevat een verzameling van Connection-elementen. |
| [getFillStyle()](#getFillStyle--) | StyleSheet-element waaruit de PageSheet opvulopmaak erft. |
| [getForeign()](#getForeign--) | Bevat elementen die de breedte en hoogte specificeren van een object uit een ander programma dat in een Microsoft Visio‑document wordt gebruikt. |
| [getForeignData()](#getForeignData--) | Bevat een MIME (Multipurpose Internet Mail Extensions) gecodeerde BLOB van afbeeldingsgegevens, zoals Windows‑metabestand, bitmap of OLE‑gegevens. |
| [getHyperlinks()](#getHyperlinks--) | Bevat een verzameling Hyperlink‑elementen. |
| [getLayers()](#getLayers--) | Bevat een verzameling Layer-elementen. |
| [getLineStyle()](#getLineStyle--) | StyleSheet-element waaruit de PageSheet lijnopmaak erft. |
| [getPageLayout()](#getPageLayout--) | Bevat Diagram dat de paginalay-outinstellingen voor vormen en connectoren regelt, zoals de afstand tussen alle vormen op de pagina, de afstand tussen alle connectoren op de pagina en de routeringsstijl voor alle connectoren op de pagina. |
| [getPageProps()](#getPageProps--) | Bevat Diagram dat paginaparameters beheert, zoals paginabreedte, -hoogte en schaal. |
| [getPrintProps()](#getPrintProps--) | Bevat elementen die bepalen hoe de tekenpagina wordt opgemaakt (weergegeven) op de printerpagina. |
| [getProps()](#getProps--) | Bevat een verzameling Prop‑elementen. |
| [getRulerGrid()](#getRulerGrid--) | Bevat elementen die de instellingen van de linialen en het raster van de pagina specificeren. |
| [getScratchs()](#getScratchs--) | Bevat een verzameling Scratch-elementen. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Bevat een verzameling SmartTagDef-elementen. |
| [getTextStyle()](#getTextStyle--) | StyleSheet-element waaruit de PageSheet tekstopmaak erft. |
| [getUniqueID()](#getUniqueID--) | Een GUID (globaal unieke identifier) voor het element. |
| [getUsers()](#getUsers--) | Bevat een verzameling User-elementen. |
| [getXForm()](#getXForm--) | Bevat elementen die algemene positioneringsinformatie over een vorm specificeren. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Voor de beschrijving van deze eigenschap, zie [getFillStyle()](../../com.aspose.diagram/pagesheet\\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Voor de beschrijving van deze eigenschap, zie [getLineStyle()](../../com.aspose.diagram/pagesheet\\#getLineStyle--) |
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


Kopieert pagesheet van een bronobject.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | source pagesheet. |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Bevat een verzameling Act-elementen.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Bevat elementen die informatie bevatten over opmerkingen die in een documentpagina zijn ingevoegd.

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


Bevat een verzameling van ConnectionABCD-elementen.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Bevat een verzameling van Connection-elementen.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet-element waaruit de PageSheet opvulopmaak erft.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Bevat elementen die de breedte en hoogte van een object uit een ander programma specificeren dat in een Microsoft Visio‑document wordt gebruikt. Bevat ook elementen die de afstand specificeren waarmee de afbeelding van het object binnen zijn randen is verschoven.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Bevat een MIME (Multipurpose Internet Mail Extensions) gecodeerde BLOB van afbeeldingsgegevens, zoals Windows‑metabestand, bitmap of OLE‑gegevens.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Bevat een verzameling Hyperlink‑elementen.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


Bevat een verzameling Layer-elementen.

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet-element waaruit de PageSheet lijnopmaak erft.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Bevat Diagram dat de paginalay-outinstellingen voor vormen en connectoren regelt, zoals de afstand tussen alle vormen op de pagina, de afstand tussen alle connectoren op de pagina en de routeringsstijl voor alle connectoren op de pagina.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


Bevat Diagram dat paginaparameters beheert, zoals paginabreedte, -hoogte en schaal.

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


Bevat elementen die bepalen hoe de tekenpagina wordt opgemaakt (weergegeven) op de printerpagina.

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Bevat een verzameling Prop‑elementen.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Bevat elementen die de instellingen van de linialen en het raster van de pagina specificeren.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Bevat een verzameling Scratch-elementen.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Bevat een verzameling SmartTagDef-elementen.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet-element waaruit de PageSheet tekstopmaak erft.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Een GUID (globaal unieke identifier) voor het element.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Bevat een verzameling User-elementen.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


Bevat elementen die algemene positioneringsinformatie over een vorm specificeren.

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


Voor de beschrijving van deze eigenschap, zie [getFillStyle()](../../com.aspose.diagram/pagesheet\\#getFillStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Voor de beschrijving van deze eigenschap, zie [getLineStyle()](../../com.aspose.diagram/pagesheet\\#getLineStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.UUID |  |

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

