---
title: StyleSheet
second_title: Référence API d'Aspose.Diagram pour Java
description: Représente un style défini dans un document.
type: docs
weight: 393
url: /fr/java/com.aspose.diagram/stylesheet/
---

**Inheritance:**
java.lang.Object
```
public class StyleSheet
```

Représente un style défini dans un document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [StyleSheet()](#StyleSheet--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChars()](#getChars--) | Contient une collection d'éléments Char. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Contient une collection d'éléments ConnectionABCD. |
| [getConnections()](#getConnections--) | Contient une collection d'éléments Connection. |
| [getEvent()](#getEvent--) | Contient des éléments qui spécifient les formules qui contrôlent les événements de forme. |
| [getFill()](#getFill--) | Contient les valeurs actuelles de format de remplissage pour la forme et son ombre portée, y compris le motif, la couleur de premier plan et la couleur d'arrière-plan. |
| [getFillStyle()](#getFillStyle--) | Élément StyleSheet dont ce style hérite du format de remplissage. |
| [getForeign()](#getForeign--) | Contient des éléments spécifiant la largeur et la hauteur d'un objet provenant d'un autre programme utilisé dans un document Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Contient un BLOB encodé MIME (Multipurpose Internet Mail Extensions) de données d'image, telles qu'un métafichier Windows, un bitmap ou des données OLE. |
| [getGroup()](#getGroup--) | Contient les éléments qui contrôlent comment ajouter des formes à un groupe, déplacer les membres d’un groupe et sélectionner des groupes. |
| [getHelp()](#getHelp--) | Contient les éléments spécifiant le sujet du fichier d’aide de l’élément Shape et les informations de copyright. |
| [getID()](#getID--) | L'ID unique de l'élément au sein de son élément parent. |
| [getImage()](#getImage--) | Contient les valeurs de gamma, de luminosité, de contraste, de flou, d’accentuation, de débruitage et de transparence d’un bitmap. |
| [getLayout()](#getLayout--) | Contient des éléments qui contrôlent le placement des formes et les paramètres de routage des connecteurs. |
| [getLine()](#getLine--) | Contient des éléments qui contrôlent les attributs de ligne d'une forme, tels que le motif, l'épaisseur et la couleur. |
| [getLineStyle()](#getLineStyle--) | Élément StyleSheet dont ce style hérite du format de ligne. |
| [getMisc()](#getMisc--) | Contient les éléments spécifiant le sujet du fichier d’aide de l’élément Shape et les informations de copyright. |
| [getName()](#getName--) | Le nom de l'élément. |
| [getNameU()](#getNameU--) | Le nom universel de l'élément. |
| [getPageLayout()](#getPageLayout--) | Contient un Diagram qui contrôle les paramètres de mise en page de la page pour les formes et les connecteurs, tels que l'espacement entre toutes les formes sur la page, l'espacement entre tous les connecteurs sur la page, et le style de routage pour tous les connecteurs sur la page. |
| [getParas()](#getParas--) | Contient une collection d'éléments Para. |
| [getProtection()](#getProtection--) | Le verrouillage aide à prévenir les modifications involontaires de la forme mais n'empêche pas Microsoft Visio de réinitialiser les valeurs dans d'autres circonstances. |
| [getRulerGrid()](#getRulerGrid--) | Contient des éléments qui spécifient les paramètres des règles et de la grille de la page. |
| [getStyleProp()](#getStyleProp--) | Contient des éléments qui contrôlent le comportement du style, comme le fait qu'un style inclue des attributs de texte, de ligne et de remplissage. |
| [getTabsCollection()](#getTabsCollection--) | Contient une collection d'éléments Tab. |
| [getTextBlock()](#getTextBlock--) | Contient des éléments qui spécifient l'alignement, les marges et les positions d'arrêt de tabulation par défaut du texte dans le bloc de texte d'une forme. |
| [getTextStyle()](#getTextStyle--) | Élément StyleSheet dont ce style hérite du format de texte. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Pour la description de cette propriété, veuillez consulter [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--) |
| [setID(int value)](#setID-int-) | Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/stylesheet\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Pour la description de cette propriété, veuillez consulter [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/stylesheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Pour la description de cette propriété, veuillez consulter [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StyleSheet() {#StyleSheet--}
```
public StyleSheet()
```


Constructeur.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée une copie profonde de cette instance.

**Returns:**
java.lang.Object -
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
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Contient des éléments qui spécifient les formules qui contrôlent les événements de forme.

**Returns:**
[Event](../../com.aspose.diagram/event)
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


Élément StyleSheet dont ce style hérite du format de remplissage.

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
### getID() {#getID--}
```
public int getID()
```


L'ID unique de l'élément au sein de son élément parent.

**Returns:**
int
### getImage() {#getImage--}
```
public Image getImage()
```


Contient les valeurs de gamma, de luminosité, de contraste, de flou, d’accentuation, de débruitage et de transparence d’un bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
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


Élément StyleSheet dont ce style hérite du format de ligne.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
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
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Contient un Diagram qui contrôle les paramètres de mise en page de la page pour les formes et les connecteurs, tels que l'espacement entre toutes les formes sur la page, l'espacement entre tous les connecteurs sur la page, et le style de routage pour tous les connecteurs sur la page.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Contient une collection d'éléments Para.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Le verrouillage aide à prévenir les modifications involontaires de la forme, mais n’empêche pas Microsoft Visio de réinitialiser les valeurs dans d’autres circonstances. Il ne protège pas non plus contre les modifications effectuées dans la fenêtre ShapeSheet.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Contient des éléments qui spécifient les paramètres des règles et de la grille de la page.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getStyleProp() {#getStyleProp--}
```
public StyleProp getStyleProp()
```


Contient des éléments qui contrôlent le comportement du style, comme le fait qu'un style inclue des attributs de texte, de ligne et de remplissage.

**Returns:**
[StyleProp](../../com.aspose.diagram/styleprop)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Contient une collection d'éléments Tab.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
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


Élément StyleSheet dont ce style hérite du format de texte.

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


Pour la description de cette propriété, veuillez consulter [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/stylesheet\#getID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Pour la description de cette propriété, veuillez consulter [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/stylesheet\#getName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Pour la description de cette propriété, veuillez consulter [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--)

**Parameters:**
| Paramètre | Type | Description |
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

