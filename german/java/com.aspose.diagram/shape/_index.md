---
title: Form
second_title: Aspose.Diagram for Java API-Referenz
description: Enthält Elemente, die eine Form in einer Masterseite oder einem Gruppenelement definieren.
type: docs
weight: 355
url: /de/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

Enthält Elemente, die eine Form in einem Master, einer Seite oder einem Gruppenform-Element definieren.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Shape()](#Shape--) | Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bringForward()](#bringForward--) | Verschiebt die Form um eine Position nach vorne in der Z‑Reihenfolge. |
| [bringToFront()](#bringToFront--) | Verschiebt die Form an die Spitze der Z‑Reihenfolge. |
| [centerDrawing()](#centerDrawing--) | Zentriere die Form relativ zur Ausdehnung der Seite. |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | Gibt ein Array zurück, das die Bezeichner (IDs) der Formen enthält, die mit der Form verbunden sind. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | Gibt ein Array zurück, das die Bezeichner der Formen enthält, die von einer Form abhängen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | Liefert das ActiveX‑Steuerelement. |
| [getActs()](#getActs--) | Enthält eine Sammlung von Act-Elementen. |
| [getAlign()](#getAlign--) | Gibt die Ausrichtung einer Form relativ zur Führungslinie oder zum Führungspunkt an, an dem die Form befestigt ist. |
| [getChars()](#getChars--) | Enthält eine Sammlung von Char-Elementen. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Enthält eine Sammlung von ConnectionABCD-Elementen. |
| [getConnections()](#getConnections--) | Enthält eine Sammlung von Connection-Elementen. |
| [getConnectorRule()](#getConnectorRule--) | Gibt ein connectorRule zurück, das die Form‑ID und die Verbindung enthält, die mit der Form verbunden sind. |
| [getConnectorsType()](#getConnectorsType--) | Connector‑Typ abrufen. |
| [getControlData()](#getControlData--) | Liest die Daten des Steuerelements. |
| [getControls()](#getControls--) | Enthält eine Sammlung von Control‑Elementen. |
| [getData1()](#getData1--) | Enthält einen beliebigen Zeichenkettenwert, der verwendet wird, um zusätzliche Informationen über eine Form bereitzustellen. |
| [getData2()](#getData2--) | Enthält einen beliebigen Zeichenkettenwert, der verwendet wird, um zusätzliche Informationen über eine Form bereitzustellen. |
| [getData3()](#getData3--) | Enthält einen beliebigen Zeichenkettenwert, der verwendet wird, um zusätzliche Informationen über eine Form bereitzustellen. |
| [getDel()](#getDel--) | Ein Flag, das angibt, ob das Element lokal gelöscht wurde. |
| [getDiagram()](#getDiagram--) | Stammelement der Visio-Objekthierarchie. |
| [getDisplayText()](#getDisplayText--) | Den auf der Oberfläche angezeigten Text abrufen. |
| [getEvent()](#getEvent--) | Enthält Elemente, die Formeln angeben, die Formereignisse steuern. |
| [getFields()](#getFields--) | Enthält eine Sammlung von Field‑Elementen. |
| [getFill()](#getFill--) | Enthält die aktuellen Füllformatierungswerte für die Form und den Formschatten, einschließlich Muster, Vordergrundfarbe und Hintergrundfarbe. |
| [getFillStyle()](#getFillStyle--) | StyleSheet, von dem diese Form die Füllformatierung erbt. |
| [getForeign()](#getForeign--) | Enthält Elemente, die die Breite und Höhe eines Objekts aus einem anderen Programm angeben, das in einem Microsoft Visio-Dokument verwendet wird. |
| [getForeignData()](#getForeignData--) | Enthält einen MIME (Multipurpose Internet Mail Extensions) codierten BLOB von Bilddaten, wie Windows-Metadatei, Bitmap oder OLE-Daten. |
| [getGeoms()](#getGeoms--) | Enthält eine Sammlung von Geom‑Elementen. |
| [getGroup()](#getGroup--) | Enthält Elemente, die steuern, wie Sie Formen zu einer Gruppe hinzufügen, Gruppenmitglieder verschieben und Gruppen auswählen. |
| [getHelp()](#getHelp--) | Enthält Elemente, die das Hilfedatei-Thema und die Copyright-Informationen des Shape-Elements angeben. |
| [getHyperlinks()](#getHyperlinks--) | Enthält eine Sammlung von Hyperlink-Elementen. |
| [getID()](#getID--) | Die eindeutige ID des Elements innerhalb seines übergeordneten Elements. |
| [getImage()](#getImage--) | Enthält die Gamma-, Helligkeits-, Kontrast-, Unschärfe-, Schärfungs-, Rauschunterdrückungs- und Transparenzwerte für ein Bitmap. |
| [getInheritChars()](#getInheritChars--) | Enthält die Zeichenwerte für die Form, die vom Master‑Shape geerbt werden. |
| [getInheritFill()](#getInheritFill--) | Enthält die Füllformatierungswerte für die Form, die vom übergeordneten Stil und dem Master‑Shape geerbt werden. |
| [getInheritGeoms()](#getInheritGeoms--) | Enthält die Geoms-Werte für die Form, die vom Master-Shape geerbt wird. |
| [getInheritLine()](#getInheritLine--) | Enthält die Linienformatierungswerte für die Form, die vom übergeordneten Stil und dem Master-Shape geerbt wird. |
| [getInheritParas()](#getInheritParas--) | Enthält die Paras für die Form, die vom übergeordneten Stil und dem Master-Shape geerbt wird. |
| [getInheritProps()](#getInheritProps--) | Enthält die Props für die Form, die vom Master-Shape geerbt wird. |
| [getInheritTextBlock()](#getInheritTextBlock--) | Enthält die Textblock-Werte für die Form, die vom übergeordneten Stil und dem Master-Shape geerbt wird. |
| [getInheritUsers()](#getInheritUsers--) | Enthält die Benutzer für die Form, die vom Master-Shape geerbt wird. |
| [getLayerMem()](#getLayerMem--) | Enthält das Element LayerMember, das jede Ebene angibt, der die Form zugewiesen ist. |
| [getLayout()](#getLayout--) | Enthält Elemente, die die Platzierung von Formen und die Routing‑Einstellungen von Verbindern steuern. |
| [getLine()](#getLine--) | Enthält Elemente, die Linienattribute für eine Form steuern, wie Muster, Stärke und Farbe. |
| [getLineStyle()](#getLineStyle--) | StyleSheet, von dem diese Form die Linienformatierung erbt |
| [getMaster()](#getMaster--) | Der Master, von dem die Form ihre Daten erbt. |
| [getMasterShape()](#getMasterShape--) | Dieses Attribut darf nur in Formen vorhanden sein, die Mitglieder einer Gruppenform sind, und die Gruppe ist eine Instanz eines Masters. |
| [getMisc()](#getMisc--) | Enthält Elemente, die das Hilfedatei-Thema und die Copyright-Informationen des Shape-Elements angeben. |
| [getName()](#getName--) | Der Name des Elements. |
| [getNameU()](#getNameU--) | Der universelle Name des Elements. |
| [getOneD()](#getOneD--) | Bestimmt, ob sich die Form als eindimensionales (1‑D) Objekt verhält. |
| [getPage()](#getPage--) | Stammelement der Visio-Objekthierarchie. |
| [getParas()](#getParas--) | Enthält eine Sammlung von Para-Elementen. |
| [getParentShape()](#getParentShape--) | Elternteil der Form. |
| [getProps()](#getProps--) | Enthält eine Sammlung von Prop-Elementen. |
| [getProtection()](#getProtection--) | Sperren hilft, unbeabsichtigte Änderungen an der Form zu verhindern, verhindert jedoch nicht, dass Microsoft Visio Werte unter anderen Umständen zurücksetzt. |
| [getPureText()](#getPureText--) | Liefere die Textzeichenfolge |
| [getRootShape()](#getRootShape--) | Gibt die übergeordnete Form einer Instanz zurück, wenn diese Form Teil einer Master-Instanz ist. |
| [getScratchs()](#getScratchs--) | Enthält eine Sammlung von Scratch-Elementen. |
| [getShapes()](#getShapes--) | Enthält eine Sammlung von Shape-Elementen. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Enthält eine Sammlung von SmartTagDef-Elementen. |
| [getTabsCollection()](#getTabsCollection--) | Enthält eine Sammlung von Tab-Elementen. |
| [getText()](#getText--) | Enthält den Text einer Form. |
| [getTextBlock()](#getTextBlock--) | Enthält Elemente, die die Ausrichtung, Ränder und Standard-Tabstopp-Positionen des Textes im Textblock einer Form festlegen. |
| [getTextStyle()](#getTextStyle--) | StyleSheet, von dem diese Form die Textformatierung erbt. |
| [getTextXForm()](#getTextXForm--) | Enthält Elemente, die Positionsinformationen zum Textblock einer Form angeben. |
| [getThreeDFormat()](#getThreeDFormat--) | Liefert das ThreeDFormat. |
| [getTwoD()](#getTwoD--) | Bestimmt, ob sich die Form als zweidimensionales (2‑D) Objekt verhält. |
| [getType()](#getType--) | Der Typ einer Form. |
| [getUniqueID()](#getUniqueID--) | Eine GUID (global eindeutiger Bezeichner), die der Form zugewiesen ist. |
| [getUsers()](#getUsers--) | Enthält eine Sammlung von User-Elementen. |
| [getXForm()](#getXForm--) | Enthält Elemente, die allgemeine Positionsinformationen zu einer Form angeben. |
| [getXForm1D()](#getXForm1D--) | Enthält x- und y-Koordinaten des Anfangs- und Endpunkts einer 1‑D‑Form. |
| [getZOrderIndex()](#getZOrderIndex--) | Gibt den Index einer Form in der Z-Reihenfolge zurück, ausgenommen die Leitform. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | Gibt ein Array zurück, das die Bezeichner der Formen enthält, die an einer Form geklebt sind. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | Gibt an, ob diese beiden Formen verbunden sind. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | Gibt an, ob diese Form eine andere Form enthält. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | Gibt an, ob diese beiden Formen geklebt sind. |
| [isInGroup()](#isInGroup--) | Gibt an, ob diese Form in einer Gruppenform ist. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | Gibt an, ob diese Form eine andere Form schneidet. |
| [isTextEmpty()](#isTextEmpty--) | Gibt an, ob die Form Text hat und ob der Text leer ist oder nicht. |
| [move(double dX, double dY)](#move-double-double-) | Verschiebt die Form um dX und dY Zoll von der aktuellen Position. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | Verschiebt die Form an eine neue absolute Position auf der Seite. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | Aktualisiert die Position der Form einschließlich xform ,Verbindung und Geometrie, wenn der Text der Form oder anderer geändert wird . |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | Ersetzt die Textzeichenkette einer Form . |
| [sendBackward()](#sendBackward--) | Verschiebt die Form um eine Position im Z-Order zurück. |
| [sendToBack()](#sendToBack--) | Verschiebt die Form an den hinteren Rand des Z-Order. |
| [setAngle(double angle)](#setAngle-double-) | Setzt den neuen Winkel der Form. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | Setzt den Typ der Anschlüsse |
| [setData1(String value)](#setData1-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | Setzt die neue Höhe der Form. |
| [setID(long value)](#setID-long-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Wende ein vordefiniertes Design auf diese Form an |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Wende einen vordefinierten Designvarianten-Quickstyle auf diese Form an |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | Wende einen vordefinierten Designvarianten-Quickstyle auf diese Form an, wie Designstil-Optionen in der Dropdown-Liste der Formstile |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Wende eine vordefinierte Designvariante auf diese Form an |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | Setzt die neue Breite der Form. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | Für die Beschreibung dieser Eigenschaft siehe bitte [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | Erstellt das HTML der Form und speichert es in einem Stream im angegebenen Format. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | Erstellt das HTML der Form und speichert es in einem Stream im angegebenen Format. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | Erstellt das HTML und speichert es in einer Datei. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | Erstellt das Bild der Form und speichert es in einem Stream im angegebenen Format. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | Erstellt das Bild der Form und speichert es in einem Stream im angegebenen Format. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | Erstellt das Bild der Form und speichert es in einer Datei. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | Erstellt das PDF der Form und speichert es in einem Stream. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | Erstellt das PDF der Form und speichert es in einem Stream. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | Speichert die Form in einer PDF-Datei. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | Speichert die Form in einer SVG-Datei. |
| [ungroup()](#ungroup--) | Form entgruppieren |
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


Verschiebt die Form um eine Position nach vorne in der Z‑Reihenfolge.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


Verschiebt die Form an die Spitze der Z‑Reihenfolge.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Zentriere die Form relativ zur Ausdehnung der Seite.

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


Gibt ein Array zurück, das die Bezeichner (IDs) der Formen enthält, die mit der Form verbunden sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Flag | int | Filtert das Array der zurückgegebenen Form-IDs nach der Richtung der Verbinder. Siehe Anmerkungen für mögliche Werte Aspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | Filtert das Array der zurückgegebenen Shape-IDs, indem es auf die IDs von Shapes beschränkt wird, die der angegebenen categoryString entsprechen. |

**Returns:**
long[] - IDs-Array.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


Gibt ein Array zurück, das die Bezeichner der Formen enthält, die von einer Form abhängen.

**Returns:**
long[] - IDs-Array.
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


Liefert das ActiveX‑Steuerelement.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Enthält eine Sammlung von Act-Elementen.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


Gibt die Ausrichtung einer Form in Bezug auf die Führung oder den Führungspunkt an, an dem die Form befestigt ist. Das Align-Element erscheint nur bei Formen, die an Führungen oder Führungspunkten befestigt sind.

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Enthält eine Sammlung von Char-Elementen.

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


Enthält eine Sammlung von ConnectionABCD-Elementen.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Enthält eine Sammlung von Connection-Elementen.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


Gibt ein connectorRule zurück, das die Form‑ID und die Verbindung enthält, die mit der Form verbunden sind.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


Connector‑Typ abrufen.

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


Liest die Daten des Steuerelements.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Enthält eine Sammlung von Control‑Elementen.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


Enthält einen beliebigen Zeichenkettenwert, der verwendet wird, um zusätzliche Informationen über eine Form bereitzustellen.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


Enthält einen beliebigen Zeichenkettenwert, der verwendet wird, um zusätzliche Informationen über eine Form bereitzustellen.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


Enthält einen beliebigen Zeichenkettenwert, der verwendet wird, um zusätzliche Informationen über eine Form bereitzustellen.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


Ein Flag, das angibt, ob das Element lokal gelöscht wurde. Der Wert 1 bedeutet, dass das Element lokal gelöscht wurde.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Stammelement der Visio-Objekthierarchie.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


Den auf der Oberfläche angezeigten Text abrufen.

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Enthält Elemente, die Formeln angeben, die Formereignisse steuern.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Enthält eine Sammlung von Field‑Elementen.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


Enthält die aktuellen Füllformatierungswerte für die Form und den Formschatten, einschließlich Muster, Vordergrundfarbe und Hintergrundfarbe.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet, von dem diese Form die Füllformatierung erbt.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Enthält Elemente, die die Breite und Höhe eines aus einem anderen Programm stammenden Objekts in einem Microsoft Visio-Dokument angeben. Außerdem enthält es Elemente, die den Abstand angeben, um den das Bild des Objekts innerhalb seiner Ränder versetzt ist.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Enthält einen MIME (Multipurpose Internet Mail Extensions) codierten BLOB von Bilddaten, wie Windows-Metadatei, Bitmap oder OLE-Daten.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Enthält eine Sammlung von Geom‑Elementen.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Enthält Elemente, die steuern, wie Sie Formen zu einer Gruppe hinzufügen, Gruppenmitglieder verschieben und Gruppen auswählen.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Enthält Elemente, die das Hilfedatei-Thema und die Copyright-Informationen des Shape-Elements angeben.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Enthält eine Sammlung von Hyperlink-Elementen.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


Die eindeutige ID des Elements innerhalb seines übergeordneten Elements.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


Enthält die Gamma-, Helligkeits-, Kontrast-, Unschärfe-, Schärfungs-, Rauschunterdrückungs- und Transparenzwerte für ein Bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


Enthält die Zeichenwerte für die Form, die vom Master‑Shape geerbt werden.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


Enthält die Füllformatierungswerte für die Form, die vom übergeordneten Stil und dem Master‑Shape geerbt werden.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


Enthält die Geoms-Werte für die Form, die vom Master-Shape geerbt wird.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


Enthält die Linienformatierungswerte für die Form, die vom übergeordneten Stil und dem Master-Shape geerbt wird.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


Enthält die Paras für die Form, die vom übergeordneten Stil und dem Master-Shape geerbt wird.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


Enthält die Props für die Form, die vom Master-Shape geerbt wird.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


Enthält die Textblock-Werte für die Form, die vom übergeordneten Stil und dem Master-Shape geerbt wird.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


Enthält die Benutzer für die Form, die vom Master-Shape geerbt wird.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


Enthält das Element LayerMember, das jede Ebene angibt, der die Form zugewiesen ist.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


Enthält Elemente, die die Platzierung von Formen und die Routing‑Einstellungen von Verbindern steuern.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


Enthält Elemente, die die Linieneigenschaften für eine Form steuern, wie Muster, Stärke und Farbe. Diese Elemente bestimmen, ob die Linienenden formatiert sind (zum Beispiel mit einer Pfeilspitze), die Größe der Linienendformate, der Radius des Rundungskreises, der auf die Linie angewendet wird, und den Linientyp (rund oder eckig).

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet, von dem diese Form die Linienformatierung erbt

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Der Master, von dem die Form ihre Daten erbt.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


Dieses Attribut kann nur in Shapes vorhanden sein, die Mitglieder eines Gruppenshapes sind, und die Gruppe ist eine Instanz eines Masters. Das Attribut enthält eine ID, die auf das entsprechende Untershape im Master verweist.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Enthält Elemente, die das Hilfedatei-Thema und die Copyright-Informationen des Shape-Elements angeben.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


Der Name des Elements.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Der universelle Name des Elements.

**Returns:**
java.lang.String
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


Bestimmt, ob das Shape sich wie ein eindimensionales (1‑D) Objekt verhält. Nur lesbar.

**Returns:**
boolean
### getPage() {#getPage--}
```
public Page getPage()
```


Stammelement der Visio-Objekthierarchie.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Enthält eine Sammlung von Para-Elementen.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


Elternteil der Form.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Enthält eine Sammlung von Prop-Elementen.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Das Sperren hilft, unbeabsichtigte Änderungen an der Form zu verhindern, verhindert jedoch nicht, dass Microsoft Visio Werte unter anderen Umständen zurücksetzt. Es schützt auch nicht vor Änderungen, die im ShapeSheet‑Fenster vorgenommen werden.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


Liefere die Textzeichenfolge

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


Gibt das Shape der obersten Ebene einer Instanz zurück, wenn dieses Shape Teil einer Master‑Instanz ist. Nur lesbar.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Enthält eine Sammlung von Scratch-Elementen.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Enthält eine Sammlung von Shape-Elementen.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Enthält eine Sammlung von SmartTagDef-Elementen.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Enthält eine Sammlung von Tab-Elementen.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


Enthält den Text einer Form.

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


Enthält Elemente, die die Ausrichtung, Ränder und Standard-Tabstopp-Positionen des Textes im Textblock einer Form festlegen.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet, von dem diese Form die Textformatierung erbt.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


Enthält Elemente, die Positionsinformationen zum Textblock einer Form angeben.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


Liefert das ThreeDFormat.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


Bestimmt, ob sich die Form als zweidimensionales (2‑D) Objekt verhält.

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


Der Typ eines Shapes. Er kann einer der folgenden Werte sein: Group, Shape, Guide oder Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Eine GUID (global eindeutiger Bezeichner), die der Form zugewiesen ist.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Enthält eine Sammlung von User-Elementen.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


Enthält Elemente, die allgemeine Positionsinformationen zu einer Form angeben.

**Returns:**
[XForm](../../com.aspose.diagram/xform)
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


Enthält die x- und y-Koordinaten des Anfangs- und Endpunkts einer 1‑D‑Form. Dieses Element erscheint nur bei 1‑D‑Formen.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


Gibt den Index einer Form in der Z-Reihenfolge zurück, ausgenommen die Leitform.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


Gibt ein Array zurück, das die Bezeichner der Formen enthält, die an einer Form geklebt sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Flag | int | Die Dimensionalität und Richtungsabhängigkeit der Verbindungspunkte der zurückzugebenden Shapes. Siehe Anmerkungen für mögliche Werte Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | Filtert das Array der zurückgegebenen Shape-IDs, indem es auf die IDs von Shapes beschränkt wird, die der angegebenen categoryString entsprechen. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | Optional: zusätzliches Shape, an das die zurückgegebenen Shapes ebenfalls geklebt werden müssen, kann [Shape](../../com.aspose.diagram/shape) oder null sein. |

**Returns:**
long[] - IDs-Array.
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


Gibt an, ob diese beiden Formen verbunden sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


Gibt an, ob diese Form eine andere Form enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


Gibt an, ob diese beiden Formen geklebt sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


Gibt an, ob diese Form in einer Gruppenform ist.

**Returns:**
boolean
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


Gibt an, ob diese Form eine andere Form schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


Gibt an, ob die Form Text hat und ob der Text leer ist oder nicht.

**Returns:**
boolean
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


Verschiebt die Form um dX und dY Zoll von der aktuellen Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dX | double | X-Versatz double. |
| dY | double | Y-Versatz double. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


Verschiebt die Form an eine neue absolute Position auf der Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newPinX | double | Neue x-Koordinate des Pins des Shapes (Rotationszentrum) in Bezug auf den Ursprung seines übergeordneten Elements. double. |
| newPinY | double | Neue y-Koordinate des Pins des Shapes (Rotationszentrum) in Bezug auf den Ursprung seines übergeordneten Elements. double. |

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


Aktualisiert die Position des Shapes einschließlich xform, Verbindung und Geometrie, wenn der Text des Shapes oder anderer geändert wird. Wir sammeln Shape‑Daten wie den Text des Shapes und berechnen dann die Position des Shapes. Diese Methode wird nur verwendet, um Shape‑Daten zu aktualisieren.

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


Ersetzt die Textzeichenkette einer Form .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


Verschiebt die Form um eine Position im Z-Order zurück.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


Verschiebt die Form an den hinteren Rand des Z-Order.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


Setzt den neuen Winkel des Shapes. Die Einheit des Winkels ist Radiant.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | double | Neuer Winkel, dessen Einheit Radiant und nicht Grad ist. double. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


Setzt den Typ der Anschlüsse

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


Setzt die neue Höhe der Form.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Höhe | double | Neue heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Wende ein vordefiniertes Design auf diese Form an

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Wende einen vordefinierten Designvarianten-Quickstyle auf diese Form an

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


Wende einen vordefinierten Designvarianten-Quickstyle auf diese Form an, wie Designstil-Optionen in der Dropdown-Liste der Formstile

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| styleIndex | int | die Zeile der Stilmatrizen |
| colorIndex | int | die Spalte der Stilmatrizen |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Wende eine vordefinierte Designvariante auf diese Form an

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


Setzt die neue Breite der Form.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | double | Neue widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


Für die Beschreibung dieser Eigenschaft siehe bitte [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


Erstellt das HTML der Form und speichert es in einem Stream im angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Ausgabestream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Zusätzliche HTML-Erstellungsoptionen |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


Erstellt das HTML der Form und speichert es in einem Stream im angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Ausgabestream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Zusätzliche HTML-Erstellungsoptionen |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


Erstellt das HTML und speichert es in einer Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | HTML-Speicheroptionen |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


Erstellt das Bild der Form und speichert es in einem Stream im angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Ausgabestream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Zusätzliche Bild-Erstellungsoptionen |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


Erstellt das Bild der Form und speichert es in einem Stream im angegebenen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Ausgabestream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Zusätzliche Bild-Erstellungsoptionen |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Erstellt das Formbild und speichert es in einer Datei. Die Erweiterung des Dateinamens bestimmt das Format des Bildes.

Das Format des Bildes wird durch die Verwendung der Dateinamenerweiterung angegeben. Zum Beispiel, wenn Sie "myfile.png" angeben, wird das Bild im PNG-Format gespeichert. Die folgenden Dateierweiterungen werden erkannt: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageFile | java.lang.String | Der Bilddateiname mit vollständigem Pfad. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Zusätzliche Bild-Erstellungsoptionen |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


Erstellt das PDF der Form und speichert es in einem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Ausgabestream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


Erstellt das PDF der Form und speichert es in einem Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Der Ausgabestream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


Speichert die Form in einer PDF-Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | java.lang.String | der PDF-Dateiname mit vollständigem Pfad |

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


Speichert die Form in einer SVG-Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


Form entgruppieren

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

