---
title: PageSheet
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element som definierar sidbladet för ett Page- eller Master-element.
type: docs
weight: 270
url: /sv/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

Innehåller element som definierar sidbladet för ett Page- eller Master-element.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | Kopierar pagesheet från ett källobjekt. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | Innehåller en samling av Act-element. |
| [getAnnotations()](#getAnnotations--) | Innehåller element som innehåller information om kommentarer som infogats i en dokumentsida. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Innehåller en samling av ConnectionABCD-element. |
| [getConnections()](#getConnections--) | Innehåller en samling av Connection-element. |
| [getFillStyle()](#getFillStyle--) | StyleSheet-element som PageSheet ärver fyllningsformatering från. |
| [getForeign()](#getForeign--) | Innehåller element som specificerar bredd och höjd på ett objekt från ett annat program som används i ett Microsoft Visio-dokument. |
| [getForeignData()](#getForeignData--) | Innehåller en MIME (Multipurpose Internet Mail Extensions) kodad BLOB av bilddata, såsom Windows-metafil, bitmap eller OLE-data. |
| [getHyperlinks()](#getHyperlinks--) | Innehåller en samling Hyperlink-element. |
| [getLayers()](#getLayers--) | Innehåller en samling av Layer-element. |
| [getLineStyle()](#getLineStyle--) | StyleSheet-element som PageSheet ärver linjeformatering från. |
| [getPageLayout()](#getPageLayout--) | Innehåller Diagram som styr sidlayoutinställningarna för former och anslutningar, såsom avstånd mellan alla former på sidan, avstånd mellan alla anslutningar på sidan och routningsstil för alla anslutningar på sidan. |
| [getPageProps()](#getPageProps--) | Innehåller Diagram som styr sidattribut, såsom sidbredd, höjd och skala. |
| [getPrintProps()](#getPrintProps--) | Innehåller element som styr hur ritningssidan formateras (visas) på utskriftssidan. |
| [getProps()](#getProps--) | Innehåller en samling Prop-element. |
| [getRulerGrid()](#getRulerGrid--) | Innehåller element som specificerar inställningarna för sidans linjaler och rutnät. |
| [getScratchs()](#getScratchs--) | Innehåller en samling Scratch-element. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Innehåller en samling av SmartTagDef-element. |
| [getTextStyle()](#getTextStyle--) | StyleSheet-element som PageSheet ärver textformatering från. |
| [getUniqueID()](#getUniqueID--) | En GUID (globalt unik identifierare) för elementet. |
| [getUsers()](#getUsers--) | Innehåller en samling User-element. |
| [getXForm()](#getXForm--) | Innehåller element som specificerar generell placeringsinformation om en form. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av denna egenskap, se [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av denna egenskap, se [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av den här egenskapen, se [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | För beskrivningen av den här egenskapen, se [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### copy(PageSheet source) {#copy-com.aspose.diagram.PageSheet-}
```
public void copy(PageSheet source)
```


Kopierar pagesheet från ett källobjekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | käll‑pagesheet. |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Innehåller en samling av Act-element.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Innehåller element som innehåller information om kommentarer som infogats i en dokumentsida.

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


Innehåller en samling av ConnectionABCD-element.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Innehåller en samling av Connection-element.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet-element som PageSheet ärver fyllningsformatering från.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Innehåller element som specificerar bredd och höjd på ett objekt från ett annat program som används i ett Microsoft Visio-dokument. Inkluderar också element som specificerar avståndet som objektets bild förskjuts inom dess kanter.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Innehåller en MIME (Multipurpose Internet Mail Extensions) kodad BLOB av bilddata, såsom Windows-metafil, bitmap eller OLE-data.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Innehåller en samling Hyperlink-element.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


Innehåller en samling av Layer-element.

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet-element som PageSheet ärver linjeformatering från.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Innehåller Diagram som styr sidlayoutinställningarna för former och anslutningar, såsom avstånd mellan alla former på sidan, avstånd mellan alla anslutningar på sidan och routningsstil för alla anslutningar på sidan.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


Innehåller Diagram som styr sidattribut, såsom sidbredd, höjd och skala.

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


Innehåller element som styr hur ritningssidan formateras (visas) på utskriftssidan.

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Innehåller en samling Prop-element.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Innehåller element som specificerar inställningarna för sidans linjaler och rutnät.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Innehåller en samling Scratch-element.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Innehåller en samling av SmartTagDef-element.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet-element som PageSheet ärver textformatering från.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


En GUID (globalt unik identifierare) för elementet.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Innehåller en samling User-element.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


Innehåller element som specificerar generell placeringsinformation om en form.

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


För beskrivningen av denna egenskap, se [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


För beskrivningen av denna egenskap, se [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


För beskrivningen av den här egenskapen, se [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


För beskrivningen av den här egenskapen, se [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID |  |

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

