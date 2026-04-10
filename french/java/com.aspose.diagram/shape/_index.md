---
title: Forme
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des éléments qui définissent une forme dans une page maître ou un élément de forme groupée.
type: docs
weight: 355
url: /fr/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

Contient des éléments qui définissent une forme dans un Master, une Page ou un élément de forme groupée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Shape()](#Shape--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [bringForward()](#bringForward--) | Déplace la forme d'une position vers l'avant dans l'ordre Z. |
| [bringToFront()](#bringToFront--) | Déplace la forme au premier plan de l'ordre Z. |
| [centerDrawing()](#centerDrawing--) | Centrer la forme par rapport à l'étendue de la page |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | Renvoie un tableau contenant les identifiants (ID) des formes qui sont connectées à la forme. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | Renvoie un tableau contenant les identifiants des formes qui dépendent d'une forme. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | Obtient le contrôle ActiveX. |
| [getActs()](#getActs--) | Contient une collection d'éléments Act. |
| [getAlign()](#getAlign--) | Indique l'alignement d'une forme par rapport au guide ou au point de guide auquel la forme est collée. |
| [getChars()](#getChars--) | Contient une collection d'éléments Char. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Contient une collection d'éléments ConnectionABCD. |
| [getConnections()](#getConnections--) | Contient une collection d'éléments Connection. |
| [getConnectorRule()](#getConnectorRule--) | Renvoie un connectorRule qui contient l'ID de la forme et la connexion qui sont reliés à la forme. |
| [getConnectorsType()](#getConnectorsType--) | Obtenir le type de connecteurs |
| [getControlData()](#getControlData--) | Obtient les données du contrôle. |
| [getControls()](#getControls--) | Contient une collection d'éléments Control. |
| [getData1()](#getData1--) | Contient une valeur de chaîne arbitraire utilisée pour fournir des informations supplémentaires sur une forme. |
| [getData2()](#getData2--) | Contient une valeur de chaîne arbitraire utilisée pour fournir des informations supplémentaires sur une forme. |
| [getData3()](#getData3--) | Contient une valeur de chaîne arbitraire utilisée pour fournir des informations supplémentaires sur une forme. |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément est supprimé localement. |
| [getDiagram()](#getDiagram--) | Élément racine de la hiérarchie des objets Visio. |
| [getDisplayText()](#getDisplayText--) | Obtenir le texte affiché sur l'interface |
| [getEvent()](#getEvent--) | Contient des éléments qui spécifient les formules qui contrôlent les événements de forme. |
| [getFields()](#getFields--) | Contient une collection d'éléments Field. |
| [getFill()](#getFill--) | Contient les valeurs actuelles de format de remplissage pour la forme et son ombre portée, y compris le motif, la couleur de premier plan et la couleur d'arrière-plan. |
| [getFillStyle()](#getFillStyle--) | Feuille de style dont cette forme hérite du format de remplissage. |
| [getForeign()](#getForeign--) | Contient des éléments spécifiant la largeur et la hauteur d'un objet provenant d'un autre programme utilisé dans un document Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Contient un BLOB encodé MIME (Multipurpose Internet Mail Extensions) de données d'image, telles qu'un métafichier Windows, un bitmap ou des données OLE. |
| [getGeoms()](#getGeoms--) | Contient une collection d'éléments Geom. |
| [getGroup()](#getGroup--) | Contient les éléments qui contrôlent comment ajouter des formes à un groupe, déplacer les membres d’un groupe et sélectionner des groupes. |
| [getHelp()](#getHelp--) | Contient les éléments spécifiant le sujet du fichier d’aide de l’élément Shape et les informations de copyright. |
| [getHyperlinks()](#getHyperlinks--) | Contient une collection d'éléments Hyperlink. |
| [getID()](#getID--) | L'ID unique de l'élément au sein de son élément parent. |
| [getImage()](#getImage--) | Contient les valeurs de gamma, de luminosité, de contraste, de flou, d’accentuation, de débruitage et de transparence d’un bitmap. |
| [getInheritChars()](#getInheritChars--) | Contient les valeurs de caractères pour la forme héritées de la forme maître. |
| [getInheritFill()](#getInheritFill--) | Contient les valeurs de format de remplissage pour la forme héritées du style parent et de la forme maître. |
| [getInheritGeoms()](#getInheritGeoms--) | Contient les valeurs Geoms pour la forme héritée de la forme maître. |
| [getInheritLine()](#getInheritLine--) | Contient les valeurs de formatage de ligne pour la forme héritée du style parent et de la forme maître. |
| [getInheritParas()](#getInheritParas--) | Contient les paras pour la forme héritée du style parent et de la forme maître. |
| [getInheritProps()](#getInheritProps--) | Contient les props pour la forme héritée de la forme maître. |
| [getInheritTextBlock()](#getInheritTextBlock--) | Contient les valeurs textblock pour la forme héritée du style parent et de la forme maître. |
| [getInheritUsers()](#getInheritUsers--) | Contient les utilisateurs pour la forme héritée de la forme maître. |
| [getLayerMem()](#getLayerMem--) | Contient l'élément LayerMember, qui spécifie chaque couche à laquelle la forme est assignée. |
| [getLayout()](#getLayout--) | Contient des éléments qui contrôlent le placement des formes et les paramètres de routage des connecteurs. |
| [getLine()](#getLine--) | Contient des éléments qui contrôlent les attributs de ligne d'une forme, tels que le motif, l'épaisseur et la couleur. |
| [getLineStyle()](#getLineStyle--) | Feuille de style dont cette forme hérite du formatage de ligne |
| [getMaster()](#getMaster--) | Le maître dont la forme hérite de ses données. |
| [getMasterShape()](#getMasterShape--) | Cet attribut ne peut être présent que dans les formes qui sont membres d'une forme groupe, et le groupe est une instance d'un maître. |
| [getMisc()](#getMisc--) | Contient les éléments spécifiant le sujet du fichier d’aide de l’élément Shape et les informations de copyright. |
| [getName()](#getName--) | Le nom de l'élément. |
| [getNameU()](#getNameU--) | Le nom universel de l'élément. |
| [getOneD()](#getOneD--) | Détermine si la forme se comporte comme un objet unidimensionnel (1-D). |
| [getPage()](#getPage--) | Élément racine de la hiérarchie des objets Visio. |
| [getParas()](#getParas--) | Contient une collection d'éléments Para. |
| [getParentShape()](#getParentShape--) | Parent de la forme. |
| [getProps()](#getProps--) | Contient une collection d'éléments Prop. |
| [getProtection()](#getProtection--) | Le verrouillage aide à prévenir les modifications involontaires de la forme mais n'empêche pas Microsoft Visio de réinitialiser les valeurs dans d'autres circonstances. |
| [getPureText()](#getPureText--) | Obtenir la chaîne de texte |
| [getRootShape()](#getRootShape--) | Renvoie la forme de niveau supérieur d'une instance si cette forme fait partie d'une instance maître. |
| [getScratchs()](#getScratchs--) | Contient une collection d'éléments Scratch. |
| [getShapes()](#getShapes--) | Contient une collection d'éléments Shape. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Contient une collection d'éléments SmartTagDef. |
| [getTabsCollection()](#getTabsCollection--) | Contient une collection d'éléments Tab. |
| [getText()](#getText--) | Contient le texte d'une forme. |
| [getTextBlock()](#getTextBlock--) | Contient des éléments qui spécifient l'alignement, les marges et les positions d'arrêt de tabulation par défaut du texte dans le bloc de texte d'une forme. |
| [getTextStyle()](#getTextStyle--) | Feuille de style dont cette forme hérite du formatage du texte. |
| [getTextXForm()](#getTextXForm--) | Contient des éléments qui spécifient les informations de positionnement du bloc de texte d'une forme. |
| [getThreeDFormat()](#getThreeDFormat--) | Obtient le ThreeDFormat. |
| [getTwoD()](#getTwoD--) | Détermine si la forme se comporte comme un objet bidimensionnel (2-D). |
| [getType()](#getType--) | Le type d'une forme. |
| [getUniqueID()](#getUniqueID--) | Un GUID (identifiant global unique) attribué à la forme. |
| [getUsers()](#getUsers--) | Contient une collection d'éléments User. |
| [getXForm()](#getXForm--) | Contient des éléments spécifiant les informations de positionnement général d'une forme. |
| [getXForm1D()](#getXForm1D--) | Contient les coordonnées x et y du point de départ et du point d'arrivée d'une forme 1D. |
| [getZOrderIndex()](#getZOrderIndex--) | Renvoie l'index d'une forme dans l'ordre Z, à l'exception de la forme guide. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | Renvoie un tableau contenant les identifiants des formes collées à une forme. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | Indique si ces deux formes sont connectées. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | Indique si cette forme contient une autre forme. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | Indique si ces deux formes sont collées. |
| [isInGroup()](#isInGroup--) | Indique si cette forme se trouve dans une forme groupe. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | Indique si cette forme intersecte une autre forme. |
| [isTextEmpty()](#isTextEmpty--) | Indique si la forme possède du texte et si le texte est vide ou non. |
| [move(double dX, double dY)](#move-double-double-) | Déplace la forme de dX et dY pouces par rapport à la position actuelle. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | Déplace la forme vers une nouvelle position absolue sur la page. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | Actualise la position de la forme, y compris xform, connection et geom, lors de la modification du texte de la forme ou d'autres éléments. |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | Remplace la chaîne de texte d'une forme. |
| [sendBackward()](#sendBackward--) | Déplace la forme d'une position en arrière dans l'ordre Z. |
| [sendToBack()](#sendToBack--) | Déplace la forme tout au fond de l'ordre Z. |
| [setAngle(double angle)](#setAngle-double-) | Définit le nouvel angle de la forme. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | Définir le type des connecteurs |
| [setData1(String value)](#setData1-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | Pour la description de cette propriété, veuillez consulter [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | Pour la description de cette propriété, veuillez consulter [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Pour la description de cette propriété, veuillez consulter [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | Définit la nouvelle hauteur de la forme. |
| [setID(long value)](#setID-long-) | Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Pour la description de cette propriété, veuillez consulter [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Pour la description de cette propriété, veuillez consulter [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | Pour la description de cette propriété, veuillez consulter [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Pour la description de cette propriété, veuillez consulter [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | Pour la description de cette propriété, veuillez consulter [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Appliquer un thème prédéfini à cette forme |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Appliquer un style rapide de variante de thème prédéfini à cette forme |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | Appliquer un style rapide de variante de thème prédéfini à cette forme, comme les options de styles de thème dans la liste déroulante des styles de forme |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Appliquer une variante de thème prédéfini à cette forme |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | Pour la description de cette propriété, veuillez consulter [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | Pour la description de cette propriété, veuillez consulter [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Pour la description de cette propriété, veuillez consulter [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | Pour la description de cette propriété, veuillez consulter [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | Pour la description de cette propriété, veuillez consulter [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Pour la description de cette propriété, veuillez consulter [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | Définit la nouvelle largeur de la forme. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | Pour la description de cette propriété, veuillez consulter [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | Pour la description de cette propriété, veuillez consulter [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | Crée le HTML de la forme et l’enregistre dans un flux au format spécifié. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | Crée le HTML de la forme et l’enregistre dans un flux au format spécifié. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | Crée le HTML et l’enregistre dans un fichier. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | Crée l’image de la forme et l’enregistre dans un flux au format spécifié. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | Crée l’image de la forme et l’enregistre dans un flux au format spécifié. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | Crée l’image de la forme et l’enregistre dans un fichier. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | Crée le PDF de la forme et l’enregistre dans un flux. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | Crée le PDF de la forme et l’enregistre dans un flux. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | Enregistre la forme dans un fichier PDF. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | Enregistre la forme dans un fichier SVG. |
| [ungroup()](#ungroup--) | Dégrouper la forme |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


Constructeur.

### bringForward() {#bringForward--}
```
public void bringForward()
```


Déplace la forme d'une position vers l'avant dans l'ordre Z.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


Déplace la forme au premier plan de l'ordre Z.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centrer la forme par rapport à l'étendue de la page

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


Renvoie un tableau contenant les identifiants (ID) des formes qui sont connectées à la forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| drapeau | int | Filtre le tableau des ID de forme retournés selon la directionnalité des connecteurs. Voir les remarques pour les valeurs possiblesAspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | Filtre le tableau d'ID de formes retournés en le limitant aux ID des formes qui correspondent à la catégorie spécifiée categoryString. |

**Returns:**
long[] - tableau d'ID de type long.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


Renvoie un tableau contenant les identifiants des formes qui dépendent d'une forme.

**Returns:**
long[] - tableau d'ID de type long.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


Obtient le contrôle ActiveX.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Contient une collection d'éléments Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


Indique l'alignement d'une forme par rapport au guide ou au point de guidage auquel la forme est collée. L'élément Align apparaît uniquement pour les formes collées aux guides ou aux points de guidage.

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Contient une collection d'éléments Char.

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


Contient une collection d'éléments ConnectionABCD.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Contient une collection d'éléments Connection.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


Renvoie un connectorRule qui contient l'ID de la forme et la connexion qui sont reliés à la forme.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


Obtenir le type de connecteurs

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


Obtient les données du contrôle.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Contient une collection d'éléments Control.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


Contient une valeur de chaîne arbitraire utilisée pour fournir des informations supplémentaires sur une forme.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


Contient une valeur de chaîne arbitraire utilisée pour fournir des informations supplémentaires sur une forme.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


Contient une valeur de chaîne arbitraire utilisée pour fournir des informations supplémentaires sur une forme.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


Indicateur indiquant si l'élément est supprimé localement. Une valeur de 1 indique que l'élément est supprimé localement.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Élément racine de la hiérarchie des objets Visio.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


Obtenir le texte affiché sur l'interface

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Contient des éléments qui spécifient les formules qui contrôlent les événements de forme.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Contient une collection d'éléments Field.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


Contient les valeurs actuelles de format de remplissage pour la forme et son ombre portée, y compris le motif, la couleur de premier plan et la couleur d'arrière-plan.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Feuille de style dont cette forme hérite du format de remplissage.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Contient des éléments spécifiant la largeur et la hauteur d'un objet provenant d'un autre programme utilisé dans un document Microsoft Visio. Inclut également des éléments spécifiant la distance à laquelle l'image de l'objet est décalée à l'intérieur de ses bordures.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Contient un BLOB encodé MIME (Multipurpose Internet Mail Extensions) de données d'image, telles qu'un métafichier Windows, un bitmap ou des données OLE.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Contient une collection d'éléments Geom.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Contient les éléments qui contrôlent comment ajouter des formes à un groupe, déplacer les membres d’un groupe et sélectionner des groupes.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Contient les éléments spécifiant le sujet du fichier d’aide de l’élément Shape et les informations de copyright.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Contient une collection d'éléments Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


L'ID unique de l'élément au sein de son élément parent.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


Contient les valeurs de gamma, de luminosité, de contraste, de flou, d’accentuation, de débruitage et de transparence d’un bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


Contient les valeurs de caractères pour la forme héritées de la forme maître.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


Contient les valeurs de format de remplissage pour la forme héritées du style parent et de la forme maître.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


Contient les valeurs Geoms pour la forme héritée de la forme maître.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


Contient les valeurs de formatage de ligne pour la forme héritée du style parent et de la forme maître.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


Contient les paras pour la forme héritée du style parent et de la forme maître.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


Contient les props pour la forme héritée de la forme maître.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


Contient les valeurs textblock pour la forme héritée du style parent et de la forme maître.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


Contient les utilisateurs pour la forme héritée de la forme maître.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


Contient l'élément LayerMember, qui spécifie chaque couche à laquelle la forme est assignée.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


Contient des éléments qui contrôlent le placement des formes et les paramètres de routage des connecteurs.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


Contient des éléments qui contrôlent les attributs de ligne d’une forme, tels que le motif, l’épaisseur et la couleur. Ces éléments déterminent si les extrémités de la ligne sont formatées (par exemple, avec une pointe de flèche), la taille des formats d’extrémité de ligne, le rayon du cercle d’arrondi appliqué à la ligne, et le style de terminaison de ligne (arrondi ou carré).

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Feuille de style dont cette forme hérite du formatage de ligne

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


Le maître dont la forme hérite de ses données.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


Cet attribut ne peut être présent que dans les formes qui sont membres d'une forme de groupe, et dont le groupe est une instance d'un modèle. L'attribut contient un ID qui fait référence à la sous-forme correspondante dans le modèle.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Contient les éléments spécifiant le sujet du fichier d’aide de l’élément Shape et les informations de copyright.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


Le nom de l'élément.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Le nom universel de l'élément.

**Returns:**
java.lang.String
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


Détermine si la forme se comporte comme un objet unidimensionnel (1-D). Lecture seule.

**Returns:**
booléen
### getPage() {#getPage--}
```
public Page getPage()
```


Élément racine de la hiérarchie des objets Visio.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Contient une collection d'éléments Para.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


Parent de la forme.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Contient une collection d'éléments Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Le verrouillage aide à prévenir les modifications involontaires de la forme, mais n’empêche pas Microsoft Visio de réinitialiser les valeurs dans d’autres circonstances. Il ne protège pas non plus contre les modifications effectuées dans la fenêtre ShapeSheet.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


Obtenir la chaîne de texte

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


Renvoie la forme de niveau supérieur d'une instance si cette forme fait partie d'une instance maître. Lecture seule.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Contient une collection d'éléments Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Contient une collection d'éléments Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Contient une collection d'éléments SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Contient une collection d'éléments Tab.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


Contient le texte d'une forme.

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


Contient des éléments qui spécifient l'alignement, les marges et les positions d'arrêt de tabulation par défaut du texte dans le bloc de texte d'une forme.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Feuille de style dont cette forme hérite du formatage du texte.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


Contient des éléments qui spécifient les informations de positionnement du bloc de texte d'une forme.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


Obtient le ThreeDFormat.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


Détermine si la forme se comporte comme un objet bidimensionnel (2-D).

**Returns:**
booléen
### getType() {#getType--}
```
public int getType()
```


Le type d'une forme. Il peut être l'une des valeurs suivantes : Group, Shape, Guide ou Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Un GUID (identifiant global unique) attribué à la forme.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Contient une collection d'éléments User.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


Contient des éléments spécifiant les informations de positionnement général d'une forme.

**Returns:**
[XForm](../../com.aspose.diagram/xform)
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


Contient les coordonnées x et y du point de départ et du point d'arrivée d'une forme 1-D. Cet élément apparaît uniquement pour les formes 1-D.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


Renvoie l'index d'une forme dans l'ordre Z, à l'exception de la forme guide.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


Renvoie un tableau contenant les identifiants des formes collées à une forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| drapeau | int | La dimensionnalité et la directionnalité des points de connexion des formes à retourner. Voir les remarques pour les valeurs possibles Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | Filtre le tableau d'ID de formes retournés en le limitant aux ID des formes qui correspondent à la catégorie spécifiée categoryString. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | Optionnel : forme supplémentaire à laquelle les formes retournées doivent également être collées, peut être [Shape](../../com.aspose.diagram/shape) ou null. |

**Returns:**
long[] - tableau d'ID de type long.
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


Indique si ces deux formes sont connectées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
booléen
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


Indique si cette forme contient une autre forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
booléen
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


Indique si ces deux formes sont collées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
booléen
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


Indique si cette forme se trouve dans une forme groupe.

**Returns:**
booléen
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


Indique si cette forme intersecte une autre forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
booléen
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


Indique si la forme possède du texte et si le texte est vide ou non.

**Returns:**
booléen
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


Déplace la forme de dX et dY pouces par rapport à la position actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dX | double | Décalage X double. |
| dY | double | Décalage Y double. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


Déplace la forme vers une nouvelle position absolue sur la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newPinX | double | Nouvelle coordonnée x du point d'ancrage de la forme (centre de rotation) par rapport à l'origine de son parent. double. |
| newPinY | double | Nouvelle coordonnée y du point d'ancrage de la forme (centre de rotation) par rapport à l'origine de son parent. double. |

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


Actualise la position de la forme, y compris la transformation, la connexion et la géométrie, lors de la modification du texte de la forme ou d'autres éléments. Nous recueillerons les données de la forme, telles que le texte, puis calculerons sa position. Cette méthode n'est utilisée que pour actualiser les données de la forme.

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


Remplace la chaîne de texte d'une forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


Déplace la forme d'une position en arrière dans l'ordre Z.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


Déplace la forme tout au fond de l'ordre Z.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


Définit le nouvel angle de la forme. L'unité de l'angle est le radian.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | double | Nouvel angle dont l'unité est le radian, pas le degré double. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


Pour la description de cette propriété, veuillez consulter [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


Définir le type des connecteurs

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


Pour la description de cette propriété, veuillez consulter [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


Pour la description de cette propriété, veuillez consulter [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


Pour la description de cette propriété, veuillez consulter [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


Pour la description de cette propriété, veuillez consulter [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


Pour la description de cette propriété, veuillez consulter [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Pour la description de cette propriété, veuillez consulter [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


Définit la nouvelle hauteur de la forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hauteur | double | Nouvelle hauteur double. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Pour la description de cette propriété, veuillez consulter [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Pour la description de cette propriété, veuillez consulter [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


Pour la description de cette propriété, veuillez consulter [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Pour la description de cette propriété, veuillez consulter [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


Pour la description de cette propriété, veuillez consulter [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Appliquer un thème prédéfini à cette forme

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Appliquer un style rapide de variante de thème prédéfini à cette forme

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


Appliquer un style rapide de variante de thème prédéfini à cette forme, comme les options de styles de thème dans la liste déroulante des styles de forme

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| styleIndex | int | la ligne des matrices de style |
| colorIndex | int | la colonne des matrices de style |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Appliquer une variante de thème prédéfini à cette forme

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


Pour la description de cette propriété, veuillez consulter [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


Pour la description de cette propriété, veuillez consulter [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Pour la description de cette propriété, veuillez consulter [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Pour la description de cette propriété, veuillez consulter [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Pour la description de cette propriété, veuillez consulter [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


Définit la nouvelle largeur de la forme.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | double | Nouvelle largeur double. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


Pour la description de cette propriété, veuillez consulter [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


Pour la description de cette propriété, veuillez consulter [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


Crée le HTML de la forme et l’enregistre dans un flux au format spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux de sortie. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Options supplémentaires de création HTML |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


Crée le HTML de la forme et l’enregistre dans un flux au format spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux de sortie. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Options supplémentaires de création HTML |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


Crée le HTML et l’enregistre dans un fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | options d'enregistrement HTML |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


Crée l’image de la forme et l’enregistre dans un flux au format spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux de sortie. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Options supplémentaires de création d'image |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


Crée l’image de la forme et l’enregistre dans un flux au format spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux de sortie. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Options supplémentaires de création d'image |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Crée l'image de forme et l'enregistre dans un fichier. L'extension du nom de fichier détermine le format de l'image.

Le format de l'image est spécifié en utilisant l'extension du nom de fichier. Par exemple, si vous spécifiez "myfile.png", l'image sera enregistrée au format PNG. Les extensions de fichier suivantes sont reconnues : .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageFile | java.lang.String | Le nom de fichier image avec le chemin complet. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Options supplémentaires de création d'image |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


Crée le PDF de la forme et l’enregistre dans un flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux de sortie. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


Crée le PDF de la forme et l’enregistre dans un flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux de sortie. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


Enregistre la forme dans un fichier PDF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | le nom de fichier PDF avec le chemin complet |

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


Enregistre la forme dans un fichier SVG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


Dégrouper la forme

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

