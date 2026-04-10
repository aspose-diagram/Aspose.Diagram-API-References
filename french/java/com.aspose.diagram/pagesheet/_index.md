---
title: PageSheet
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des éléments qui définissent la feuille de page pour un élément Page ou Master.
type: docs
weight: 270
url: /fr/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

Contient des éléments qui définissent la feuille de page pour un élément Page ou Master.
## Méthodes

| Méthode | Description |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | Copie pagesheet d'un objet source. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | Contient une collection d'éléments Act. |
| [getAnnotations()](#getAnnotations--) | Contient des éléments qui renferment des informations sur les commentaires insérés dans une page de document. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Contient une collection d'éléments ConnectionABCD. |
| [getConnections()](#getConnections--) | Contient une collection d'éléments Connection. |
| [getFillStyle()](#getFillStyle--) | Élément StyleSheet dont la PageSheet hérite du format de remplissage. |
| [getForeign()](#getForeign--) | Contient des éléments spécifiant la largeur et la hauteur d'un objet provenant d'un autre programme utilisé dans un document Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Contient un BLOB encodé MIME (Multipurpose Internet Mail Extensions) de données d'image, telles qu'un métafichier Windows, un bitmap ou des données OLE. |
| [getHyperlinks()](#getHyperlinks--) | Contient une collection d'éléments Hyperlink. |
| [getLayers()](#getLayers--) | Contient une collection d'éléments Layer. |
| [getLineStyle()](#getLineStyle--) | Élément StyleSheet dont la PageSheet hérite du format de ligne. |
| [getPageLayout()](#getPageLayout--) | Contient un Diagram qui contrôle les paramètres de mise en page de la page pour les formes et les connecteurs, tels que l'espacement entre toutes les formes sur la page, l'espacement entre tous les connecteurs sur la page, et le style de routage pour tous les connecteurs sur la page. |
| [getPageProps()](#getPageProps--) | Contient Diagram qui contrôle les attributs de page, tels que la largeur, la hauteur et l'échelle de la page. |
| [getPrintProps()](#getPrintProps--) | Contient des éléments qui contrôlent la façon dont la page de dessin est formatée (apparaît) sur la page d'impression. |
| [getProps()](#getProps--) | Contient une collection d'éléments Prop. |
| [getRulerGrid()](#getRulerGrid--) | Contient des éléments qui spécifient les paramètres des règles et de la grille de la page. |
| [getScratchs()](#getScratchs--) | Contient une collection d'éléments Scratch. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Contient une collection d'éléments SmartTagDef. |
| [getTextStyle()](#getTextStyle--) | Élément StyleSheet dont la PageSheet hérite du format de texte. |
| [getUniqueID()](#getUniqueID--) | Un GUID (identifiant globalement unique) pour l'élément. |
| [getUsers()](#getUsers--) | Contient une collection d'éléments User. |
| [getXForm()](#getXForm--) | Contient des éléments spécifiant les informations de positionnement général d'une forme. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Pour la description de cette propriété, veuillez consulter [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Pour la description de cette propriété, veuillez consulter [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Pour la description de cette propriété, veuillez consulter [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Pour la description de cette propriété, veuillez consulter [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### copy(PageSheet source) {#copy-com.aspose.diagram.PageSheet-}
```
public void copy(PageSheet source)
```


Copie pagesheet d'un objet source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | pagesheet source. |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Contient une collection d'éléments Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Contient des éléments qui renferment des informations sur les commentaires insérés dans une page de document.

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
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Élément StyleSheet dont la PageSheet hérite du format de remplissage.

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
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Contient une collection d'éléments Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


Contient une collection d'éléments Layer.

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Élément StyleSheet dont la PageSheet hérite du format de ligne.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Contient un Diagram qui contrôle les paramètres de mise en page de la page pour les formes et les connecteurs, tels que l'espacement entre toutes les formes sur la page, l'espacement entre tous les connecteurs sur la page, et le style de routage pour tous les connecteurs sur la page.

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


Contient Diagram qui contrôle les attributs de page, tels que la largeur, la hauteur et l'échelle de la page.

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


Contient des éléments qui contrôlent la façon dont la page de dessin est formatée (apparaît) sur la page d'impression.

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Contient une collection d'éléments Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


Contient des éléments qui spécifient les paramètres des règles et de la grille de la page.

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Contient une collection d'éléments Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Contient une collection d'éléments SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Élément StyleSheet dont la PageSheet hérite du format de texte.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Un GUID (identifiant globalement unique) pour l'élément.

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


Pour la description de cette propriété, veuillez consulter [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Pour la description de cette propriété, veuillez consulter [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Pour la description de cette propriété, veuillez consulter [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Pour la description de cette propriété, veuillez consulter [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.UUID |  |

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

