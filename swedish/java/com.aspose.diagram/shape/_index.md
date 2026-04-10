---
title: Shape
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element som definierar en form i en Master Page eller gruppformselement.
type: docs
weight: 355
url: /sv/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

Innehåller element som definierar en form i ett Master-, Page- eller gruppformselement.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Shape()](#Shape--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bringForward()](#bringForward--) | Flyttar formen fram ett steg i z-ordningen. |
| [bringToFront()](#bringToFront--) | Flyttar formen till framkanten av z-ordningen. |
| [centerDrawing()](#centerDrawing--) | Centrera formen i förhållande till sidans omfång |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | Returnerar en array som innehåller identifierarna (ID:n) för de former som är anslutna till formen. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | Returnerar en array som innehåller identifierarna för de former som beror på en form. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | Hämtar ActiveX-kontrollen. |
| [getActs()](#getActs--) | Innehåller en samling av Act-element. |
| [getAlign()](#getAlign--) | Anger justeringen av en form i förhållande till guiden eller guidepunkten som formen är fäst vid. |
| [getChars()](#getChars--) | Innehåller en samling av Char-element. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Innehåller en samling av ConnectionABCD-element. |
| [getConnections()](#getConnections--) | Innehåller en samling av Connection-element. |
| [getConnectorRule()](#getConnectorRule--) | Returnerar en connectorRule som innehåller formens ID och anslutningen som är kopplad till formen. |
| [getConnectorsType()](#getConnectorsType--) | Hämta anslutningstyp |
| [getControlData()](#getControlData--) | Hämtar data för kontrollen. |
| [getControls()](#getControls--) | Innehåller en samling av Control-element. |
| [getData1()](#getData1--) | Innehåller ett godtyckligt strängvärde som används för att tillhandahålla ytterligare information om en form. |
| [getData2()](#getData2--) | Innehåller ett godtyckligt strängvärde som används för att tillhandahålla ytterligare information om en form. |
| [getData3()](#getData3--) | Innehåller ett godtyckligt strängvärde som används för att tillhandahålla ytterligare information om en form. |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getDiagram()](#getDiagram--) | Rot-element för Visio-objekthierarkin. |
| [getDisplayText()](#getDisplayText--) | Hämta texten som visas i gränssnittet |
| [getEvent()](#getEvent--) | Innehåller element som specificerar formler som styr formhändelser. |
| [getFields()](#getFields--) | Innehåller en samling av Field-element. |
| [getFill()](#getFill--) | Innehåller de aktuella fyllningsformateringsvärdena för formen och formens skuggning, inklusive mönster, förgrundsfärg och bakgrundsfärg. |
| [getFillStyle()](#getFillStyle--) | Stilmall som denna form ärver fyllningsformatering från. |
| [getForeign()](#getForeign--) | Innehåller element som specificerar bredd och höjd på ett objekt från ett annat program som används i ett Microsoft Visio-dokument. |
| [getForeignData()](#getForeignData--) | Innehåller en MIME (Multipurpose Internet Mail Extensions) kodad BLOB av bilddata, såsom Windows-metafil, bitmap eller OLE-data. |
| [getGeoms()](#getGeoms--) | Innehåller en samling av Geom-element. |
| [getGroup()](#getGroup--) | Innehåller element som styr hur du lägger till former i en grupp, flyttar medlemmar i en grupp och väljer grupper. |
| [getHelp()](#getHelp--) | Innehåller element som specificerar Shape-elementets hjälpfilsämne och upphovsrättsinformation. |
| [getHyperlinks()](#getHyperlinks--) | Innehåller en samling Hyperlink-element. |
| [getID()](#getID--) | Det unika ID:t för elementet inom dess överordnade element. |
| [getImage()](#getImage--) | Innehåller gamma-, ljus-, kontrast-, oskärpe-, skärpe-, brusreducerings- och transparensvärden för en bitmap. |
| [getInheritChars()](#getInheritChars--) | Innehåller teckenvärdena för formen som ärvs av masternformen. |
| [getInheritFill()](#getInheritFill--) | Innehåller fyllningsformateringsvärdena för formen som ärvs av förälderstilen och masternformen. |
| [getInheritGeoms()](#getInheritGeoms--) | Innehåller Geoms‑värdena för formen som ärvs av masterformen. |
| [getInheritLine()](#getInheritLine--) | Innehåller radformateringsvärdena för formen som ärvs av förälderstilen och masterformen. |
| [getInheritParas()](#getInheritParas--) | Innehåller paras för formen som ärvs av förälderstilen och masterformen. |
| [getInheritProps()](#getInheritProps--) | Innehåller egenskaperna för formen som ärvs av masterformen. |
| [getInheritTextBlock()](#getInheritTextBlock--) | Innehåller textblockvärdena för formen som ärvs av förälderstilen och masterformen. |
| [getInheritUsers()](#getInheritUsers--) | Innehåller användarna för formen som ärvs av masterformen. |
| [getLayerMem()](#getLayerMem--) | Innehåller LayerMember‑elementet, som specificerar varje lager som formen tilldelas. |
| [getLayout()](#getLayout--) | Innehåller element som styr formplacering och inställningar för anslutningsruttning. |
| [getLine()](#getLine--) | Innehåller element som styr linjeattribut för en form, såsom mönster, tjocklek och färg. |
| [getLineStyle()](#getLineStyle--) | Stilmall som denna form ärver radformatering från. |
| [getMaster()](#getMaster--) | Mastern som formen ärver sina data från. |
| [getMasterShape()](#getMasterShape--) | Detta attribut får endast finnas i former som är medlemmar i en gruppform, och gruppen är en instans av en master. |
| [getMisc()](#getMisc--) | Innehåller element som specificerar Shape-elementets hjälpfilsämne och upphovsrättsinformation. |
| [getName()](#getName--) | Elementets namn. |
| [getNameU()](#getNameU--) | Det universella namnet för elementet. |
| [getOneD()](#getOneD--) | Bestämmer om formen beter sig som ett endimensionellt (1‑D) objekt. |
| [getPage()](#getPage--) | Rot-element för Visio-objekthierarkin. |
| [getParas()](#getParas--) | Innehåller en samling av Para-element. |
| [getParentShape()](#getParentShape--) | Formens förälder. |
| [getProps()](#getProps--) | Innehåller en samling Prop-element. |
| [getProtection()](#getProtection--) | Låsning hjälper till att förhindra oavsiktliga ändringar av formen men hindrar inte Microsoft Visio från att återställa värden i andra situationer. |
| [getPureText()](#getPureText--) | Hämta textsträngen. |
| [getRootShape()](#getRootShape--) | Returnerar top‑nivåformen för en instans om denna form är en del av en masterinstans. |
| [getScratchs()](#getScratchs--) | Innehåller en samling Scratch-element. |
| [getShapes()](#getShapes--) | Innehåller en samling av Shape‑element. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Innehåller en samling av SmartTagDef-element. |
| [getTabsCollection()](#getTabsCollection--) | Innehåller en samling av Tab‑element. |
| [getText()](#getText--) | Innehåller texten för en figur. |
| [getTextBlock()](#getTextBlock--) | Innehåller element som specificerar justering, marginaler och standardtabbstoppositioner för text i en figurs textblock. |
| [getTextStyle()](#getTextStyle--) | Stilmall som denna form ärver textformatering från. |
| [getTextXForm()](#getTextXForm--) | Innehåller element som specificerar placeringsinformation om en figurs textblock. |
| [getThreeDFormat()](#getThreeDFormat--) | Hämtar ThreeDFormat. |
| [getTwoD()](#getTwoD--) | Bestämmer om formen beter sig som ett tvådimensionellt (2‑D) objekt. |
| [getType()](#getType--) | Typen av en form. |
| [getUniqueID()](#getUniqueID--) | En GUID (globalt unikt identifierare) tilldelad formen. |
| [getUsers()](#getUsers--) | Innehåller en samling User-element. |
| [getXForm()](#getXForm--) | Innehåller element som specificerar generell placeringsinformation om en form. |
| [getXForm1D()](#getXForm1D--) | Innehåller x- och y-koordinater för startpunkten och slutpunkten av en 1‑D-form. |
| [getZOrderIndex()](#getZOrderIndex--) | Returnerar indexet för en form i z‑ordningen förutom guideformen. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | Returnerar en array som innehåller identifierarna för de former som är limmade till en form. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | Indikerar om dessa två former är anslutna. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | Indikerar om denna form innehåller en annan form. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | Indikerar om dessa två former är limmade. |
| [isInGroup()](#isInGroup--) | Indikerar om denna form är i en gruppform. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | Anger om den här formen intersectar en annan form. |
| [isTextEmpty()](#isTextEmpty--) | Indikerar om formen har text och om texten är tom eller inte. |
| [move(double dX, double dY)](#move-double-double-) | Flyttar formen med dX och dY tum från den aktuella positionen. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | Flyttar formen till en ny absolut position på sidan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | Uppdaterar formens position inklusive xform, connection och geom när formens text eller annan ändras. |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | Ersätt textsträngen för en form. |
| [sendBackward()](#sendBackward--) | Flyttar formen ett steg bakåt i z-ordningen. |
| [sendToBack()](#sendToBack--) | Flyttar formen längst bak i z-ordningen. |
| [setAngle(double angle)](#setAngle-double-) | Ställer in ny vinkel för formen. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | För beskrivningen av denna egenskap, se [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | Ange anslutningstyp. |
| [setData1(String value)](#setData1-java.lang.String-) | För beskrivningen av denna egenskap, se [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | För beskrivningen av denna egenskap, se [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | För beskrivningen av denna egenskap, se [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | För beskrivningen av denna egenskap, se [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | För beskrivningen av denna egenskap, se [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av denna egenskap, se [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | Ställer in ny höjd för formen. |
| [setID(long value)](#setID-long-) | För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av denna egenskap, se [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | För beskrivningen av denna egenskap, se [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | För beskrivningen av denna egenskap, se [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | För beskrivningen av denna egenskap, se [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | För beskrivningen av denna egenskap, se [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Tillämpa ett förinställt tema på den här formen |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Tillämpa en förinställd temavariant snabbstil på den här formen |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | Tillämpa en förinställd temavariant snabbstil på den här formen, som temastilsalternativ i rullgardinsmenyn för formstilar |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Tillämpa en förinställd temavariant på den här formen |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | För beskrivningen av denna egenskap, se [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | För beskrivningen av denna egenskap, se [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | För beskrivningen av denna egenskap, se [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | För beskrivningen av denna egenskap, se [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | För beskrivningen av denna egenskap, se [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | För beskrivningen av denna egenskap, se [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | Ställer in ny bredd på formen. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | För beskrivningen av denna egenskap, se [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | För beskrivningen av denna egenskap, se [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | Skapar formens HTML och sparar den till en ström i angivet format. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | Skapar formens HTML och sparar den till en ström i angivet format. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | Skapar HTML och sparar den till en fil. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | Skapar formens bild och sparar den till en ström i angivet format. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | Skapar formens bild och sparar den till en ström i angivet format. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | Skapar formens bild och sparar den till en fil. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | Skapar formens PDF och sparar den till en ström. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | Skapar formens PDF och sparar den till en ström. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | Sparar formen till en PDF-fil. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | Sparar formen till en SVG-fil. |
| [ungroup()](#ungroup--) | Avgruppera form |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


Konstruktor.

### bringForward() {#bringForward--}
```
public void bringForward()
```


Flyttar formen fram ett steg i z-ordningen.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


Flyttar formen till framkanten av z-ordningen.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centrera formen i förhållande till sidans omfång

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


Returnerar en array som innehåller identifierarna (ID:n) för de former som är anslutna till formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flagga | int | Filtrerar arrayen av returnerade form-ID:n efter anslutarnas riktning. Se Kommentarer för möjliga värdenAspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | Filtrerar arrayen av returnerade form-ID:n genom att begränsa den till ID:n för former som matchar den angivna categoryString. |

**Returns:**
long[] - ID-array av typen long.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


Returnerar en array som innehåller identifierarna för de former som beror på en form.

**Returns:**
long[] - ID-array av typen long.
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


Hämtar ActiveX-kontrollen.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Innehåller en samling av Act-element.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


Anger justeringen av en form i förhållande till guiden eller guidepunkten som formen är fäst vid. Align-elementet visas endast för former som är fästa vid guider eller guidepunkter.

**Returns:**
[Align](../../com.aspose.diagram/align)
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
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


Returnerar en connectorRule som innehåller formens ID och anslutningen som är kopplad till formen.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


Hämta anslutningstyp

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


Hämtar data för kontrollen.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Innehåller en samling av Control-element.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


Innehåller ett godtyckligt strängvärde som används för att tillhandahålla ytterligare information om en form.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


Innehåller ett godtyckligt strängvärde som används för att tillhandahålla ytterligare information om en form.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


Innehåller ett godtyckligt strängvärde som används för att tillhandahålla ytterligare information om en form.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet är raderat lokalt. Ett värde på 1 indikerar att elementet är raderat lokalt.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Rot-element för Visio-objekthierarkin.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


Hämta texten som visas i gränssnittet

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Innehåller element som specificerar formler som styr formhändelser.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Innehåller en samling av Field-element.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
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


Stilmall som denna form ärver fyllningsformatering från.

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
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Innehåller en samling av Geom-element.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
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
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Innehåller en samling Hyperlink-element.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


Det unika ID:t för elementet inom dess överordnade element.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


Innehåller gamma-, ljus-, kontrast-, oskärpe-, skärpe-, brusreducerings- och transparensvärden för en bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


Innehåller teckenvärdena för formen som ärvs av masternformen.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


Innehåller fyllningsformateringsvärdena för formen som ärvs av förälderstilen och masternformen.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


Innehåller Geoms‑värdena för formen som ärvs av masterformen.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


Innehåller radformateringsvärdena för formen som ärvs av förälderstilen och masterformen.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


Innehåller paras för formen som ärvs av förälderstilen och masterformen.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


Innehåller egenskaperna för formen som ärvs av masterformen.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


Innehåller textblockvärdena för formen som ärvs av förälderstilen och masterformen.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


Innehåller användarna för formen som ärvs av masterformen.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


Innehåller LayerMember‑elementet, som specificerar varje lager som formen tilldelas.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
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


Stilmall som denna form ärver radformatering från.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Mastern som formen ärver sina data från.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


Detta attribut kan endast finnas i former som är medlemmar i en gruppform, och gruppen är en instans av en master. Attributet innehåller ett ID som refererar till motsvarande delform i mastern.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
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
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


Bestämmer om formen beter sig som ett endimensionellt (1-D) objekt. Skrivskyddad.

**Returns:**
boolean
### getPage() {#getPage--}
```
public Page getPage()
```


Rot-element för Visio-objekthierarkin.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Innehåller en samling av Para-element.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


Formens förälder.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Innehåller en samling Prop-element.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Låsning hjälper till att förhindra oavsiktliga ändringar av formen men hindrar inte Microsoft Visio från att återställa värden i andra situationer. Det skyddar inte heller mot ändringar som görs i ShapeSheet-fönstret.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


Hämta textsträngen.

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


Returnerar top-nivåformen för en instans om denna form är en del av en masterinstans. Skrivskyddad.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Innehåller en samling Scratch-element.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Innehåller en samling av Shape‑element.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Innehåller en samling av SmartTagDef-element.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Innehåller en samling av Tab‑element.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


Innehåller texten för en figur.

**Returns:**
[Text](../../com.aspose.diagram/text)
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


Stilmall som denna form ärver textformatering från.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


Innehåller element som specificerar placeringsinformation om en figurs textblock.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


Hämtar ThreeDFormat.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


Bestämmer om formen beter sig som ett tvådimensionellt (2‑D) objekt.

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


Typen av en form. Den kan vara ett av följande värden: Group, Shape, Guide eller Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


En GUID (globalt unikt identifierare) tilldelad formen.

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
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


Innehåller x- och y-koordinater för startpunkten och slutpunkten för en 1‑D-form. Detta element visas endast för 1‑D-former.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


Returnerar indexet för en form i z‑ordningen förutom guideformen.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


Returnerar en array som innehåller identifierarna för de former som är limmade till en form.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| flagga | int | Dimensionaliteten och riktningen för anslutningspunkterna på formerna som ska returneras. Se Kommentarer för möjliga värden Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | Filtrerar arrayen av returnerade form-ID:n genom att begränsa den till ID:n för former som matchar den angivna categoryString. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | Valfritt: ytterligare form som de returnerade formerna också måste fästas vid, kan vara [Shape](../../com.aspose.diagram/shape) eller null. |

**Returns:**
long[] - ID-array av typen long.
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


Indikerar om dessa två former är anslutna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | form |

**Returns:**
boolean
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


Indikerar om denna form innehåller en annan form.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


Indikerar om dessa två former är limmade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | form |

**Returns:**
boolean
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


Indikerar om denna form är i en gruppform.

**Returns:**
boolean
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


Anger om den här formen intersectar en annan form.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


Indikerar om formen har text och om texten är tom eller inte.

**Returns:**
boolean
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


Flyttar formen med dX och dY tum från den aktuella positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dX | double | X-förskjutning double. |
| dY | double | Y-förskjutning double. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


Flyttar formen till en ny absolut position på sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newPinX | double | Ny x-koordinat för formens pin (rotationscentrum) i förhållande till förälderns ursprung. double. |
| newPinY | double | Ny y-koordinat för formens pin (rotationscentrum) i förhållande till förälderns ursprung. double. |

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


Uppdaterar formens position inklusive xform, anslutning och geom när formens text eller annan ändras. Vi samlar in formens data såsom formens text och beräknar sedan formens position. Denna metod används endast för att uppdatera formens data.

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


Ersätt textsträngen för en form.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


Flyttar formen ett steg bakåt i z-ordningen.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


Flyttar formen längst bak i z-ordningen.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


Ställer in ny vinkel för formen. Vinkelns enhet är radian.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | double | Ny vinkel vars enhet är radian, inte grad double. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


För beskrivningen av denna egenskap, se [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


Ange anslutningstyp.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


För beskrivningen av denna egenskap, se [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


För beskrivningen av denna egenskap, se [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


För beskrivningen av denna egenskap, se [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


För beskrivningen av denna egenskap, se [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


För beskrivningen av denna egenskap, se [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


För beskrivningen av denna egenskap, se [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


Ställer in ny höjd för formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| höjd | double | Ny höjd double. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


För beskrivningen av denna egenskap, se [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


För beskrivningen av denna egenskap, se [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


För beskrivningen av denna egenskap, se [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


För beskrivningen av denna egenskap, se [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


För beskrivningen av denna egenskap, se [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Tillämpa ett förinställt tema på den här formen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Tillämpa en förinställd temavariant snabbstil på den här formen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


Tillämpa en förinställd temavariant snabbstil på den här formen, som temastilsalternativ i rullgardinsmenyn för formstilar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| styleIndex | int | raden i stilmatriser |
| colorIndex | int | kolumnen i stilmatriser |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Tillämpa en förinställd temavariant på den här formen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


För beskrivningen av denna egenskap, se [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


För beskrivningen av denna egenskap, se [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


För beskrivningen av denna egenskap, se [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


För beskrivningen av denna egenskap, se [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


För beskrivningen av denna egenskap, se [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


För beskrivningen av denna egenskap, se [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


Ställer in ny bredd på formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | double | Ny bredd double. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


För beskrivningen av denna egenskap, se [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


För beskrivningen av denna egenskap, se [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


Skapar formens HTML och sparar den till en ström i angivet format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Utdataflödet. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Ytterligare HTML-skapandealternativ |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


Skapar formens HTML och sparar den till en ström i angivet format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Utdataflödet. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Ytterligare HTML-skapandealternativ |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


Skapar HTML och sparar den till en fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html sparalternativ |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


Skapar formens bild och sparar den till en ström i angivet format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Utdataflödet. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Ytterligare bildskapandealternativ |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


Skapar formens bild och sparar den till en ström i angivet format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Utdataflödet. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Ytterligare bildskapandealternativ |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Skapar formbilden och sparar den till en fil. Filnamnets filändelse bestämmer bildens format.

Bildens format anges genom att använda filnamnets filändelse. Till exempel, om du anger \"myfile.png\", sparas bilden i PNG-format. Följande filändelser känns igen: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | java.lang.String | Bildfilens namn med fullständig sökväg. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Ytterligare bildskapandealternativ |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


Skapar formens PDF och sparar den till en ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Utdataflödet. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


Skapar formens PDF och sparar den till en ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Utdataflödet. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


Sparar formen till en PDF-fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | pdf-filens namn med fullständig sökväg |

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


Sparar formen till en SVG-fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


Avgruppera form

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

