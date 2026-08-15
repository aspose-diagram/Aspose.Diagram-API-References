---
title: StyleSheet
second_title: Aspose.Diagram för Java API-referens
description: Representerar en stil som definierats i ett dokument.
type: docs
weight: 393
url: /sv/java/com.aspose.diagram/stylesheet/
---

**Inheritance:**
java.lang.Object
```
public class StyleSheet
```

Representerar en stil som definierats i ett dokument.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [StyleSheet()](#StyleSheet--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChars()](#getChars--) | Innehåller en samling av Char-element. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Innehåller en samling av ConnectionABCD-element. |
| [getConnections()](#getConnections--) | Innehåller en samling av Connection-element. |
| [getEvent()](#getEvent--) | Innehåller element som specificerar formler som styr formhändelser. |
| [getFill()](#getFill--) | Innehåller de aktuella fyllningsformateringsvärdena för formen och formens skuggning, inklusive mönster, förgrundsfärg och bakgrundsfärg. |
| [getFillStyle()](#getFillStyle--) | StyleSheet-element från vilket detta stil ärver fyllningsformatering. |
| [getForeign()](#getForeign--) | Innehåller element som specificerar bredd och höjd på ett objekt från ett annat program som används i ett Microsoft Visio-dokument. |
| [getForeignData()](#getForeignData--) | Innehåller en MIME (Multipurpose Internet Mail Extensions) kodad BLOB av bilddata, såsom Windows-metafil, bitmap eller OLE-data. |
| [getGroup()](#getGroup--) | Innehåller element som styr hur du lägger till former i en grupp, flyttar medlemmar i en grupp och väljer grupper. |
| [getHelp()](#getHelp--) | Innehåller element som specificerar Shape-elementets hjälpfilsämne och upphovsrättsinformation. |
| [getID()](#getID--) | Det unika ID:t för elementet inom dess överordnade element. |
| [getImage()](#getImage--) | Innehåller gamma-, ljus-, kontrast-, oskärpe-, skärpe-, brusreducerings- och transparensvärden för en bitmap. |
| [getLayout()](#getLayout--) | Innehåller element som styr formplacering och inställningar för anslutningsruttning. |
| [getLine()](#getLine--) | Innehåller element som styr linjeattribut för en form, såsom mönster, tjocklek och färg. |
| [getLineStyle()](#getLineStyle--) | StyleSheet-element från vilket detta stil ärver linjeformatering. |
| [getMisc()](#getMisc--) | Innehåller element som specificerar Shape-elementets hjälpfilsämne och upphovsrättsinformation. |
| [getName()](#getName--) | Elementets namn. |
| [getNameU()](#getNameU--) | Det universella namnet för elementet. |
| [getPageLayout()](#getPageLayout--) | Innehåller Diagram som styr sidlayoutinställningarna för former och anslutningar, såsom avstånd mellan alla former på sidan, avstånd mellan alla anslutningar på sidan och routningsstil för alla anslutningar på sidan. |
| [getParas()](#getParas--) | Innehåller en samling av Para-element. |
| [getProtection()](#getProtection--) | Låsning hjälper till att förhindra oavsiktliga ändringar av formen men hindrar inte Microsoft Visio från att återställa värden i andra situationer. |
| [getRulerGrid()](#getRulerGrid--) | Innehåller element som specificerar inställningarna för sidans linjaler och rutnät. |
| [getStyleProp()](#getStyleProp--) | Innehåller element som styr stilbeteende, såsom om en stil inkluderar text-, linje- och fyllnadsattribut. |
| [getTabsCollection()](#getTabsCollection--) | Innehåller en samling av Tab‑element. |
| [getTextBlock()](#getTextBlock--) | Innehåller element som specificerar justering, marginaler och standardtabbstoppositioner för text i en figurs textblock. |
| [getTextStyle()](#getTextStyle--) | StyleSheet-element från vilket detta stil ärver textformatering. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av denna egenskap, se [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--) |
| [setID(int value)](#setID-int-) | För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/stylesheet\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av denna egenskap, se [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/stylesheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av denna egenskap, se [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StyleSheet() {#StyleSheet--}
```
public StyleSheet()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en djup kopia av denna instans.

**Returns:**
java.lang.Object -
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
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Innehåller en samling av Char-element.

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
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Innehåller element som specificerar formler som styr formhändelser.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFill() {#getFill--}
```
public Fill getFill()
```


Innehåller de aktuella fyllningsformateringsvärdena för formen och formens skuggning, inklusive mönster, förgrundsfärg och bakgrundsfärg.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet-element från vilket detta stil ärver fyllningsformatering.

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
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Innehåller element som styr hur du lägger till former i en grupp, flyttar medlemmar i en grupp och väljer grupper.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Innehåller element som specificerar Shape-elementets hjälpfilsämne och upphovsrättsinformation.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getID() {#getID--}
```
public int getID()
```


Det unika ID:t för elementet inom dess överordnade element.

**Returns:**
int
### getImage() {#getImage--}
```
public Image getImage()
```


Innehåller gamma-, ljus-, kontrast-, oskärpe-, skärpe-, brusreducerings- och transparensvärden för en bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


Innehåller element som styr formplacering och inställningar för anslutningsruttning.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


Innehåller element som styr linjeattribut för en form, såsom mönster, tjocklek och färg. Dessa element bestämmer om linjeändarna är formaterade (till exempel med en pilspets), storleken på linjeändformat, radien på den avrundade cirkeln som tillämpas på linjen och linjeändstil (rund eller fyrkantig).

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet-element från vilket detta stil ärver linjeformatering.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Innehåller element som specificerar Shape-elementets hjälpfilsämne och upphovsrättsinformation.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


Elementets namn.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Det universella namnet för elementet.

**Returns:**
java.lang.String
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Innehåller Diagram som styr sidlayoutinställningarna för former och anslutningar, såsom avstånd mellan alla former på sidan, avstånd mellan alla anslutningar på sidan och routningsstil för alla anslutningar på sidan.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Innehåller en samling av Para-element.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Låsning hjälper till att förhindra oavsiktliga ändringar av formen men hindrar inte Microsoft Visio från att återställa värden i andra situationer. Det skyddar inte heller mot ändringar som görs i ShapeSheet-fönstret.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Innehåller element som specificerar inställningarna för sidans linjaler och rutnät.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getStyleProp() {#getStyleProp--}
```
public StyleProp getStyleProp()
```


Innehåller element som styr stilbeteende, såsom om en stil inkluderar text-, linje- och fyllnadsattribut.

**Returns:**
[StyleProp](../../com.aspose.diagram/styleprop)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Innehåller en samling av Tab‑element.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


Innehåller element som specificerar justering, marginaler och standardtabbstoppositioner för text i en figurs textblock.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet-element från vilket detta stil ärver textformatering.

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


För beskrivningen av denna egenskap, se [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/stylesheet\#getID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


För beskrivningen av denna egenskap, se [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/stylesheet\#getName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


För beskrivningen av denna egenskap, se [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
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

