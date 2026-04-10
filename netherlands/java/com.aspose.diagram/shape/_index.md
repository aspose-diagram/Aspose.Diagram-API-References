---
title: Vorm
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen die een vorm definiëren in een Masterpagina of groepvormelement.
type: docs
weight: 355
url: /nl/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

Bevat elementen die een vorm definiëren in een Master-, Pagina- of groepsvormelement.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Shape()](#Shape--) | Constructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [bringForward()](#bringForward--) | Verplaatst de vorm één positie naar voren in de z-volgorde. |
| [bringToFront()](#bringToFront--) | Verplaatst de vorm naar de voorgrond van de z-volgorde. |
| [centerDrawing()](#centerDrawing--) | Centreer de vorm ten opzichte van de omvang van de pagina |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | Retourneert een array die de identifiers (ID's) bevat van de vormen die met de vorm zijn verbonden. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | Retourneert een array die de identifiers bevat van de vormen die afhankelijk zijn van een vorm. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | Haalt de ActiveX-besturingselement op. |
| [getActs()](#getActs--) | Bevat een verzameling Act-elementen. |
| [getAlign()](#getAlign--) | Geeft de uitlijning van een vorm ten opzichte van de gids of het gidspunt waaraan de vorm is vastgelijmd aan. |
| [getChars()](#getChars--) | Bevat een verzameling van Char-elementen. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Bevat een verzameling van ConnectionABCD-elementen. |
| [getConnections()](#getConnections--) | Bevat een verzameling van Connection-elementen. |
| [getConnectorRule()](#getConnectorRule--) | Retourneert een connectorRule die de vorm-id en connecton bevat die met de vorm zijn verbonden. |
| [getConnectorsType()](#getConnectorsType--) | Haal het type connectors op |
| [getControlData()](#getControlData--) | Haalt de gegevens van de besturingselement op. |
| [getControls()](#getControls--) | Bevat een verzameling Control-elementen. |
| [getData1()](#getData1--) | Bevat een willekeurige tekenreekswaarde die wordt gebruikt om extra informatie over een vorm te leveren. |
| [getData2()](#getData2--) | Bevat een willekeurige tekenreekswaarde die wordt gebruikt om extra informatie over een vorm te leveren. |
| [getData3()](#getData3--) | Bevat een willekeurige tekenreekswaarde die wordt gebruikt om extra informatie over een vorm te leveren. |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getDiagram()](#getDiagram--) | Hoofdelement van de Visio-objecthiërarchie. |
| [getDisplayText()](#getDisplayText--) | Haal de tekst op die op de interface wordt weergegeven |
| [getEvent()](#getEvent--) | Bevat elementen die formules specificeren die vormgebeurtenissen regelen. |
| [getFields()](#getFields--) | Bevat een verzameling Field-elementen. |
| [getFill()](#getFill--) | Bevat de huidige opvulopmaakwaarden voor de vorm en de slagschaduw van de vorm, inclusief patroon, voorgrondkleur en achtergrondkleur. |
| [getFillStyle()](#getFillStyle--) | StyleSheet waaruit deze vorm de opvulopmaak erft. |
| [getForeign()](#getForeign--) | Bevat elementen die de breedte en hoogte specificeren van een object uit een ander programma dat in een Microsoft Visio‑document wordt gebruikt. |
| [getForeignData()](#getForeignData--) | Bevat een MIME (Multipurpose Internet Mail Extensions) gecodeerde BLOB van afbeeldingsgegevens, zoals Windows‑metabestand, bitmap of OLE‑gegevens. |
| [getGeoms()](#getGeoms--) | Bevat een verzameling Geom-elementen. |
| [getGroup()](#getGroup--) | Bevat elementen die bepalen hoe je vormen aan een groep toevoegt, leden van een groep verplaatst en groepen selecteert. |
| [getHelp()](#getHelp--) | Bevat elementen die het Help-bestandonderwerp en de copyrightinformatie van het Shape‑element specificeren. |
| [getHyperlinks()](#getHyperlinks--) | Bevat een verzameling Hyperlink‑elementen. |
| [getID()](#getID--) | De unieke ID van het element binnen het bovenliggende element. |
| [getImage()](#getImage--) | Bevat de gamma-, helderheids-, contrast-, onscherpheids-, verscherpings-, ruisverwijderings- en transparantiewaarden voor een bitmap. |
| [getInheritChars()](#getInheritChars--) | Bevat de tekenwaarden voor de vorm die door de mastervorm worden geërfd. |
| [getInheritFill()](#getInheritFill--) | Bevat de opvulopmaakwaarden voor de vorm die door de bovenliggende stijl en de mastervorm worden geërfd. |
| [getInheritGeoms()](#getInheritGeoms--) | Bevat de Geoms-waarden voor de vorm die wordt geërfd door de mastervorm. |
| [getInheritLine()](#getInheritLine--) | Bevat de lijnopmaakwaarden voor de vorm die wordt geërfd door de bovenliggende stijl en de mastervorm. |
| [getInheritParas()](#getInheritParas--) | Bevat de paras voor de vorm die wordt geërfd door de bovenliggende stijl en de mastervorm. |
| [getInheritProps()](#getInheritProps--) | Bevat de props voor de vorm die wordt geërfd door de mastervorm. |
| [getInheritTextBlock()](#getInheritTextBlock--) | Bevat de tekstblokwaarden voor de vorm die wordt geërfd door de bovenliggende stijl en de mastervorm. |
| [getInheritUsers()](#getInheritUsers--) | Bevat de gebruikers voor de vorm die wordt geërfd door de mastervorm. |
| [getLayerMem()](#getLayerMem--) | Bevat het LayerMember-element, dat elke laag specificeert waaraan de vorm is toegewezen. |
| [getLayout()](#getLayout--) | Bevat elementen die de plaatsing van vormen en de routeringsinstellingen van connectoren regelen. |
| [getLine()](#getLine--) | Bevat elementen die lijneigenschappen voor een vorm regelen, zoals patroon, dikte en kleur. |
| [getLineStyle()](#getLineStyle--) | Stijlsheet waarvan deze vorm de lijnopmaak erft. |
| [getMaster()](#getMaster--) | De master waarvan de vorm haar gegevens erft. |
| [getMasterShape()](#getMasterShape--) | Dit attribuut mag alleen aanwezig zijn in vormen die leden zijn van een groepsvorm, en de groep is een instantie van een master. |
| [getMisc()](#getMisc--) | Bevat elementen die het Help-bestandonderwerp en de copyrightinformatie van het Shape‑element specificeren. |
| [getName()](#getName--) | De naam van het element. |
| [getNameU()](#getNameU--) | De universele naam van het element. |
| [getOneD()](#getOneD--) | Bepaalt of de vorm zich gedraagt als een één-dimensionaal (1-D) object. |
| [getPage()](#getPage--) | Hoofdelement van de Visio-objecthiërarchie. |
| [getParas()](#getParas--) | Bevat een verzameling van Para-elementen. |
| [getParentShape()](#getParentShape--) | Ouder van de vorm. |
| [getProps()](#getProps--) | Bevat een verzameling Prop‑elementen. |
| [getProtection()](#getProtection--) | Vergrendeling helpt onbedoelde wijzigingen aan de vorm te voorkomen, maar voorkomt niet dat Microsoft Visio waarden reset in andere omstandigheden. |
| [getPureText()](#getPureText--) | Haal de tekstreeks op. |
| [getRootShape()](#getRootShape--) | Retourneert de bovenste vorm van een instantie als deze vorm deel uitmaakt van een masterinstantie. |
| [getScratchs()](#getScratchs--) | Bevat een verzameling Scratch-elementen. |
| [getShapes()](#getShapes--) | Bevat een collectie van Shape-elementen. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Bevat een verzameling SmartTagDef-elementen. |
| [getTabsCollection()](#getTabsCollection--) | Bevat een collectie van Tab-elementen. |
| [getText()](#getText--) | Bevat de tekst van een vorm. |
| [getTextBlock()](#getTextBlock--) | Bevat elementen die de uitlijning, marges en standaard tabstopposities van tekst in het tekstblok van een vorm specificeren. |
| [getTextStyle()](#getTextStyle--) | Stijlsheet waarvan deze vorm de tekstopmaak erft. |
| [getTextXForm()](#getTextXForm--) | Bevat elementen die positioneringsinformatie over het tekstblok van een vorm specificeren. |
| [getThreeDFormat()](#getThreeDFormat--) | Haalt de ThreeDFormat op. |
| [getTwoD()](#getTwoD--) | Bepaalt of de vorm zich gedraagt als een twee-dimensionaal (2-D) object. |
| [getType()](#getType--) | Het type van een vorm. |
| [getUniqueID()](#getUniqueID--) | Een GUID (globaal unieke identifier) toegewezen aan de vorm. |
| [getUsers()](#getUsers--) | Bevat een verzameling User-elementen. |
| [getXForm()](#getXForm--) | Bevat elementen die algemene positioneringsinformatie over een vorm specificeren. |
| [getXForm1D()](#getXForm1D--) | Bevat x- en y-coördinaten van het beginpunt en eindpunt van een 1-D-vorm. |
| [getZOrderIndex()](#getZOrderIndex--) | Retourneert de index van een vorm in de z-volgorde, behalve de gidsvorm. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | Retourneert een array die de identifiers bevat van de vormen die aan een vorm zijn geplakt. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | Geeft aan of deze twee vormen met elkaar verbonden zijn. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | Geeft aan of deze vorm een andere vorm bevat. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | Geeft aan of deze twee vormen aan elkaar zijn geplakt. |
| [isInGroup()](#isInGroup--) | Geeft aan of deze vorm zich in een groepsvorm bevindt. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | Geeft aan of deze vorm een andere vorm kruist. |
| [isTextEmpty()](#isTextEmpty--) | Geeft aan of de vorm tekst heeft en of de tekst leeg is of niet. |
| [move(double dX, double dY)](#move-double-double-) | Verplaatst de vorm met dX en dY inches vanaf de huidige positie. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | Verplaatst de vorm naar een nieuwe absolute positie op de pagina. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | Ververs de positie van de vorm, inclusief xform, verbinding en geom, bij het wijzigen van de tekst van de vorm of van anderen. |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | Vervangt de tekenreeks van een vorm. |
| [sendBackward()](#sendBackward--) | Verplaatst de vorm één positie terug in de z‑volgorde. |
| [sendToBack()](#sendToBack--) | Verplaatst de vorm naar de achterkant van de z‑volgorde. |
| [setAngle(double angle)](#setAngle-double-) | Stelt een nieuwe hoek van de vorm in. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | Stel het type connectoren in. |
| [setData1(String value)](#setData1-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | Voor de beschrijving van deze eigenschap, zie [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | Voor de beschrijving van deze eigenschap, zie [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Voor de beschrijving van deze eigenschap, zie [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | Stelt een nieuwe hoogte van de vorm in. |
| [setID(long value)](#setID-long-) | Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Voor de beschrijving van deze eigenschap, zie [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Voor de beschrijving van deze eigenschap, zie [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | Voor de beschrijving van deze eigenschap, zie [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Voor de beschrijving van deze eigenschap, zie [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | Voor de beschrijving van deze eigenschap, zie [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Pas een vooraf ingesteld thema toe op deze vorm |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Pas een vooraf ingestelde thema-variant-quickstyle toe op deze vorm |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | Pas een vooraf ingestelde thema-variant-quickstyle toe op deze vorm, zoals thema-stijlenopties in de vervolgkeuzelijst van vormstijlen |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Pas een vooraf ingestelde thema-variant toe op deze vorm |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | Voor de beschrijving van deze eigenschap, zie [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | Voor de beschrijving van deze eigenschap, zie [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Voor de beschrijving van deze eigenschap, zie [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | Voor de beschrijving van deze eigenschap, zie [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | Voor de beschrijving van deze eigenschap, zie [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Voor de beschrijving van deze eigenschap, zie [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | Stelt de nieuwe breedte van de vorm in. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | Voor de beschrijving van deze eigenschap, zie [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | Voor de beschrijving van deze eigenschap, zie [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | Maakt de HTML van de vorm en slaat deze op in een stream in het opgegeven formaat. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | Maakt de HTML van de vorm en slaat deze op in een stream in het opgegeven formaat. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | Maakt de HTML en slaat deze op in een bestand. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | Maakt de afbeelding van de vorm en slaat deze op in een stream in het opgegeven formaat. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | Maakt de afbeelding van de vorm en slaat deze op in een stream in het opgegeven formaat. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | Maakt de afbeelding van de vorm en slaat deze op in een bestand. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | Maakt de PDF van de vorm en slaat deze op in een stream. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | Maakt de PDF van de vorm en slaat deze op in een stream. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | Slaat de vorm op in een PDF-bestand. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | Slaat de vorm op in een SVG-bestand. |
| [ungroup()](#ungroup--) | Degroeperen van vorm |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


Constructor.

### bringForward() {#bringForward--}
```
public void bringForward()
```


Verplaatst de vorm één positie naar voren in de z-volgorde.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


Verplaatst de vorm naar de voorgrond van de z-volgorde.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centreer de vorm ten opzichte van de omvang van de pagina

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


Retourneert een array die de identifiers (ID's) bevat van de vormen die met de vorm zijn verbonden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vlag | int | Filtert de array met geretourneerde vorm-ID's op basis van de richting van de connectoren. Zie Opmerkingen voor mogelijke waarden Aspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | Filtert de array met geretourneerde vorm-ID's door deze te beperken tot de ID's van vormen die overeenkomen met de opgegeven categoryString. |

**Returns:**
long[] - ID's arraylong.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


Retourneert een array die de identifiers bevat van de vormen die afhankelijk zijn van een vorm.

**Returns:**
long[] - ID's arraylong.
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


Haalt de ActiveX-besturingselement op.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Bevat een verzameling Act-elementen.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


Geeft de uitlijning van een vorm ten opzichte van de hulplijn of het hulppunt waaraan de vorm is vastgelijmd aan. Het Align‑element verschijnt alleen voor vormen die aan hulplijnen of hulppunten zijn vastgelijmd.

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Bevat een verzameling van Char-elementen.

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
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


Retourneert een connectorRule die de vorm-id en connecton bevat die met de vorm zijn verbonden.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


Haal het type connectors op

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


Haalt de gegevens van de besturingselement op.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Bevat een verzameling Control-elementen.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


Bevat een willekeurige tekenreekswaarde die wordt gebruikt om extra informatie over een vorm te leveren.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


Bevat een willekeurige tekenreekswaarde die wordt gebruikt om extra informatie over een vorm te leveren.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


Bevat een willekeurige tekenreekswaarde die wordt gebruikt om extra informatie over een vorm te leveren.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


Een vlag die aangeeft of het element lokaal is verwijderd. Een waarde van 1 geeft aan dat het element lokaal is verwijderd.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Hoofdelement van de Visio-objecthiërarchie.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


Haal de tekst op die op de interface wordt weergegeven

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Bevat elementen die formules specificeren die vormgebeurtenissen regelen.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Bevat een verzameling Field-elementen.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


Bevat de huidige opvulopmaakwaarden voor de vorm en de slagschaduw van de vorm, inclusief patroon, voorgrondkleur en achtergrondkleur.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet waaruit deze vorm de opvulopmaak erft.

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
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Bevat een verzameling Geom-elementen.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Bevat elementen die bepalen hoe je vormen aan een groep toevoegt, leden van een groep verplaatst en groepen selecteert.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Bevat elementen die het Help-bestandonderwerp en de copyrightinformatie van het Shape‑element specificeren.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Bevat een verzameling Hyperlink‑elementen.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


De unieke ID van het element binnen het bovenliggende element.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


Bevat de gamma-, helderheids-, contrast-, onscherpheids-, verscherpings-, ruisverwijderings- en transparantiewaarden voor een bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


Bevat de tekenwaarden voor de vorm die door de mastervorm worden geërfd.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


Bevat de opvulopmaakwaarden voor de vorm die door de bovenliggende stijl en de mastervorm worden geërfd.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


Bevat de Geoms-waarden voor de vorm die wordt geërfd door de mastervorm.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


Bevat de lijnopmaakwaarden voor de vorm die wordt geërfd door de bovenliggende stijl en de mastervorm.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


Bevat de paras voor de vorm die wordt geërfd door de bovenliggende stijl en de mastervorm.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


Bevat de props voor de vorm die wordt geërfd door de mastervorm.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


Bevat de tekstblokwaarden voor de vorm die wordt geërfd door de bovenliggende stijl en de mastervorm.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


Bevat de gebruikers voor de vorm die wordt geërfd door de mastervorm.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


Bevat het LayerMember-element, dat elke laag specificeert waaraan de vorm is toegewezen.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


Bevat elementen die de plaatsing van vormen en de routeringsinstellingen van connectoren regelen.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


Bevat elementen die lijnattributen voor een vorm regelen, zoals patroon, gewicht en kleur. Deze elementen bepalen of de lijneinden zijn opgemaakt (bijvoorbeeld met een pijlpunt), de grootte van de opmaak van de lijneinden, de straal van de afrondingscirkel die op de lijn wordt toegepast, en de stijl van de lijneinde (rond of vierkant).

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Stijlsheet waarvan deze vorm de lijnopmaak erft.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


De master waarvan de vorm haar gegevens erft.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


Dit attribuut kan alleen aanwezig zijn in vormen die leden zijn van een groepsvorm, en de groep is een instantie van een master. Het attribuut bevat een ID die verwijst naar de overeenkomstige sub-vorm in de master.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Bevat elementen die het Help-bestandonderwerp en de copyrightinformatie van het Shape‑element specificeren.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


De naam van het element.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


De universele naam van het element.

**Returns:**
java.lang.String
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


Bepaalt of de vorm zich gedraagt als een één-dimensionaal (1-D) object. Alleen-lezen.

**Returns:**
boolean
### getPage() {#getPage--}
```
public Page getPage()
```


Hoofdelement van de Visio-objecthiërarchie.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Bevat een verzameling van Para-elementen.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


Ouder van de vorm.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Bevat een verzameling Prop‑elementen.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Vergrendelen helpt onbedoelde wijzigingen aan de vorm te voorkomen, maar voorkomt niet dat Microsoft Visio waarden onder andere omstandigheden opnieuw instelt. Het beschermt ook niet tegen wijzigingen die in het ShapeSheet‑venster worden aangebracht.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


Haal de tekstreeks op.

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


Retourneert de bovenste vorm van een instantie als deze vorm deel uitmaakt van een master‑instantie. Alleen-lezen.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Bevat een verzameling Scratch-elementen.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Bevat een collectie van Shape-elementen.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Bevat een verzameling SmartTagDef-elementen.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Bevat een collectie van Tab-elementen.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


Bevat de tekst van een vorm.

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


Bevat elementen die de uitlijning, marges en standaard tabstopposities van tekst in het tekstblok van een vorm specificeren.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Stijlsheet waarvan deze vorm de tekstopmaak erft.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


Bevat elementen die positioneringsinformatie over het tekstblok van een vorm specificeren.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


Haalt de ThreeDFormat op.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


Bepaalt of de vorm zich gedraagt als een twee-dimensionaal (2-D) object.

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


Het type van een vorm. Het kan een van de volgende waarden zijn: Group, Shape, Guide, of Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Een GUID (globaal unieke identifier) toegewezen aan de vorm.

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
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


Bevat x- en y-coördinaten van het beginpunt en eindpunt van een 1-D-vorm. Dit element verschijnt alleen voor 1-D-vormen.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


Retourneert de index van een vorm in de z-volgorde, behalve de gidsvorm.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


Retourneert een array die de identifiers bevat van de vormen die aan een vorm zijn geplakt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vlag | int | De dimensionaliteit en richting van de verbindingspunten van de vormen die moeten worden geretourneerd. Zie Opmerkingen voor mogelijke waarden Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | Filtert de array met geretourneerde vorm-ID's door deze te beperken tot de ID's van vormen die overeenkomen met de opgegeven categoryString. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | Optioneel: extra vorm waaraan geretourneerde vormen ook moeten worden geplakt, kan [Shape](../../com.aspose.diagram/shape) of null zijn. |

**Returns:**
long[] - ID's arraylong.
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


Geeft aan of deze twee vormen met elkaar verbonden zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


Geeft aan of deze vorm een andere vorm bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


Geeft aan of deze twee vormen aan elkaar zijn geplakt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


Geeft aan of deze vorm zich in een groepsvorm bevindt.

**Returns:**
boolean
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


Geeft aan of deze vorm een andere vorm kruist.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


Geeft aan of de vorm tekst heeft en of de tekst leeg is of niet.

**Returns:**
boolean
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


Verplaatst de vorm met dX en dY inches vanaf de huidige positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dX | double | X offsetdouble. |
| dY | double | Y offsetdouble. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


Verplaatst de vorm naar een nieuwe absolute positie op de pagina.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newPinX | double | Nieuwe x-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de oorsprong van de ouder.double. |
| newPinY | double | Nieuwe y-coördinaat van de pin van de vorm (rotatiecentrum) ten opzichte van de oorsprong van de ouder.double. |

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


Vernieuwt de positie van de vorm inclusief xform, verbinding en geom bij het wijzigen van de tekst van de vorm of van anderen. We verzamelen de gegevens van de vorm, zoals de tekst van de vorm, en berekenen vervolgens de positie van de vorm. Deze methode wordt alleen gebruikt om de gegevens van de vorm te vernieuwen.

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


Vervangt de tekenreeks van een vorm.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


Verplaatst de vorm één positie terug in de z‑volgorde.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


Verplaatst de vorm naar de achterkant van de z‑volgorde.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


Stelt een nieuwe hoek van de vorm in. De eenheid van de hoek is radiaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| angle | double | Nieuwe hoek waarvan de eenheid radiaal is, niet graaddouble. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


Voor de beschrijving van deze eigenschap, zie [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


Stel het type connectoren in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


Voor de beschrijving van deze eigenschap, zie [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


Voor de beschrijving van deze eigenschap, zie [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


Voor de beschrijving van deze eigenschap, zie [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


Voor de beschrijving van deze eigenschap, zie [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


Voor de beschrijving van deze eigenschap, zie [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Voor de beschrijving van deze eigenschap, zie [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


Stelt een nieuwe hoogte van de vorm in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| height | double | New heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Voor de beschrijving van deze eigenschap, zie [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Voor de beschrijving van deze eigenschap, zie [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


Voor de beschrijving van deze eigenschap, zie [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Voor de beschrijving van deze eigenschap, zie [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


Voor de beschrijving van deze eigenschap, zie [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Pas een vooraf ingesteld thema toe op deze vorm

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Pas een vooraf ingestelde thema-variant-quickstyle toe op deze vorm

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


Pas een vooraf ingestelde thema-variant-quickstyle toe op deze vorm, zoals thema-stijlenopties in de vervolgkeuzelijst van vormstijlen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| styleIndex | int | the row of style matrics |
| colorIndex | int | the column of style matrics |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Pas een vooraf ingestelde thema-variant toe op deze vorm

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


Voor de beschrijving van deze eigenschap, zie [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


Voor de beschrijving van deze eigenschap, zie [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Voor de beschrijving van deze eigenschap, zie [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Voor de beschrijving van deze eigenschap, zie [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Voor de beschrijving van deze eigenschap, zie [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


Stelt de nieuwe breedte van de vorm in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | double | New widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


Voor de beschrijving van deze eigenschap, zie [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


Voor de beschrijving van deze eigenschap, zie [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


Maakt de HTML van de vorm en slaat deze op in een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


Maakt de HTML van de vorm en slaat deze op in een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


Maakt de HTML en slaat deze op in een bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html save options |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


Maakt de afbeelding van de vorm en slaat deze op in een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


Maakt de afbeelding van de vorm en slaat deze op in een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageFile | java.lang.String | The image file name with full path. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


Maakt de PDF van de vorm en slaat deze op in een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


Maakt de PDF van de vorm en slaat deze op in een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


Slaat de vorm op in een PDF-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | the pdf file name with full path |

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


Slaat de vorm op in een SVG-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


Degroeperen van vorm

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

