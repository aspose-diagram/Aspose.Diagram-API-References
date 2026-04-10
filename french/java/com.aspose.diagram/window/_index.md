---
title: Window
second_title: Référence API d'Aspose.Diagram pour Java
description: Représente une fenêtre ouverte dans une instance de Microsoft Visio.
type: docs
weight: 444
url: /fr/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Représente une fenêtre ouverte dans une instance de Microsoft Visio. Cet élément contient les informations nécessaires pour recréer exactement une fenêtre d'interface utilisateur dans l'espace de travail de l'application lorsque le fichier DatadiagramML est ouvert initialement par Visio.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Window()](#Window--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | ID du conteneur : Page, Feuille ou Maître. |
| [getContainerType()](#getContainerType--) | Peut être l'une des valeurs suivantes : Document, Page ou Master. |
| [getDocument()](#getDocument--) | Chemin du fichier du document affiché dans cette fenêtre. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | Spécifie si la fonction de grille dynamique est activée pour un document ou une fenêtre. |
| [getGlueSettings()](#getGlueSettings--) | Spécifie les objets auxquels les formes sont collées lorsque la colle est activée dans le document. |
| [getID()](#getID--) | L'ID unique de l'élément au sein de son élément parent. |
| [getMaster()](#getMaster--) | ID du maître si cette fenêtre affiche un maître. |
| [getPage()](#getPage--) | ID de la page si cette fenêtre affiche une page. |
| [getParentWindow()](#getParentWindow--) | ID de la fenêtre dans laquelle cette fenêtre de pochoir est contenue. |
| [getReadOnly()](#getReadOnly--) | Indicateur en lecture seule si ce pochoir n'est pas un pochoir de document. |
| [getSheet()](#getSheet--) | ID de la feuille dans le conteneur. |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | Spécifie si les points de connexion sont affichés dans une fenêtre. |
| [getShowGrid()](#getShowGrid--) | Spécifie si une grille est affichée dans la fenêtre de dessin. |
| [getShowGuides()](#getShowGuides--) | Spécifie si les repères sont affichés dans la fenêtre de dessin. |
| [getShowPageBreaks()](#getShowPageBreaks--) | Spécifie si les sauts de page sont affichés dans une fenêtre. |
| [getShowRulers()](#getShowRulers--) | Spécifie si les règles sont affichées dans la fenêtre de dessin. |
| [getSnapAngles()](#getSnapAngles--) | Contient une collection d'éléments SnapAngle. |
| [getSnapExtensions()](#getSnapExtensions--) | Spécifie si un paramètre d'extension d'accrochage spécifique est activé ou désactivé pour la fenêtre active. |
| [getSnapSettings()](#getSnapSettings--) | Spécifie les objets auxquels les formes s'accrochent lorsque l'accrochage est actif dans la fenêtre. |
| [getStencilGroup()](#getStencilGroup--) | Spécifie le groupe de fenêtres de pochoir fusionnées dont la fenêtre fait partie. |
| [getStencilGroupPos()](#getStencilGroupPos--) | Contient un entier qui spécifie la position relative d'un pochoir au sein d'un groupe dans une fenêtre. |
| [getTabSplitterPos()](#getTabSplitterPos--) | Spécifie la largeur du contrôle d'onglet de page d'une fenêtre de dessin (en tant que fraction de la largeur totale de la fenêtre de dessin). |
| [getViewCenterX()](#getViewCenterX--) | Double optionnel. |
| [getViewCenterY()](#getViewCenterY--) | Double optionnel. |
| [getViewScale()](#getViewScale--) | Double optionnel. |
| [getWindowHeight()](#getWindowHeight--) | Hauteur du rectangle de la fenêtre. |
| [getWindowLeft()](#getWindowLeft--) | Coordonnée gauche du rectangle de la fenêtre. |
| [getWindowState()](#getWindowState--) | Cet attribut peut être une somme des valeurs suivantes. |
| [getWindowTop()](#getWindowTop--) | Coordonnée supérieure du rectangle de la fenêtre. |
| [getWindowType()](#getWindowType--) | Une valeur énumérée qui peut être l'une des suivantes : Drawing, Sheet, Stencil ou Icon. Un élément Window de WindowType='Stencil' doit apparaître après sa fenêtre de dessin parente (WindowType='Drawing') et avant tout autre élément de fenêtre de dessin. |
| [getWindowWidth()](#getWindowWidth--) | Largeur du rectangle de la fenêtre. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | Pour la description de cette propriété, veuillez consulter [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | Pour la description de cette propriété, veuillez consulter [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | Pour la description de cette propriété, veuillez consulter [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | Pour la description de cette propriété, veuillez consulter [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | Pour la description de cette propriété, veuillez consulter [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | Pour la description de cette propriété, veuillez consulter [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | Pour la description de cette propriété, veuillez consulter [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | Pour la description de cette propriété, veuillez consulter [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | Pour la description de cette propriété, veuillez consulter [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | Pour la description de cette propriété, veuillez consulter [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | Pour la description de cette propriété, veuillez consulter [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | Pour la description de cette propriété, veuillez consulter [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | Pour la description de cette propriété, veuillez consulter [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | Pour la description de cette propriété, veuillez consulter [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | Pour la description de cette propriété, veuillez consulter [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | Pour la description de cette propriété, veuillez consulter [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | Pour la description de cette propriété, veuillez consulter [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | Pour la description de cette propriété, veuillez consulter [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | Pour la description de cette propriété, veuillez consulter [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | Pour la description de cette propriété, veuillez consulter [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | Pour la description de cette propriété, veuillez consulter [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | Pour la description de cette propriété, veuillez consulter [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | Pour la description de cette propriété, veuillez consulter [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | Pour la description de cette propriété, veuillez consulter [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | Pour la description de cette propriété, veuillez consulter [getWindowTop()](../../com.aspose.diagram/window\\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | Pour la description de cette propriété, veuillez consulter [getWindowType()](../../com.aspose.diagram/window\\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | Pour la description de cette propriété, veuillez consulter [getWindowWidth()](../../com.aspose.diagram/window\\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
```


Constructeur.

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


ID du conteneur : Page, Feuille ou Maître. Pertinent et nécessaire uniquement si ContainerType est spécifié.

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


Chemin du fichier du document affiché dans cette fenêtre. Cet attribut est pertinent pour les fenêtres dont le WindowType est spécifié comme Stencil.

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


Spécifie si la fonction de grille dynamique est activée pour un document ou une fenêtre.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


Spécifie les objets auxquels les formes sont collées lorsque la colle est activée dans le document.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


L'ID unique de l'élément au sein de son élément parent.

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


ID du maître si cette fenêtre affiche un maître.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


ID de la page si cette fenêtre affiche une page. Pertinent uniquement lorsque WindowType est spécifié comme Drawing et que ContainerType est spécifié comme Page.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


ID de la fenêtre contenant cette fenêtre stencil. Pertinent uniquement lorsque WindowType est spécifié comme Stencil.

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


Indicateur en lecture seule si ce pochoir n'est pas un pochoir de document.

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


ID de la feuille dans le conteneur. Pertinent uniquement lorsque Container est spécifié comme Sheet.

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


Spécifie si les points de connexion sont affichés dans une fenêtre.

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


Spécifie si une grille est affichée dans la fenêtre de dessin.

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


Spécifie si les repères sont affichés dans la fenêtre de dessin.

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


Spécifie si les sauts de page sont affichés dans une fenêtre.

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


Spécifie si les règles sont affichées dans la fenêtre de dessin.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


Contient une collection d'éléments SnapAngle.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


Spécifie si un paramètre d'extension d'accrochage spécifique est activé ou désactivé pour la fenêtre active. La valeur peut être la somme des valeurs du tableau suivant.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


Spécifie les objets auxquels les formes s'alignent lorsque l'alignement est actif dans la fenêtre. La valeur peut être la somme des valeurs du tableau suivant.

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


Spécifie le groupe de fenêtres stencil fusionnées dont la fenêtre fait partie. Cet attribut est pertinent uniquement pour les éléments Window dont l'attribut WindowType est Stencil, et uniquement si la fenêtre stencil fait partie d'un groupe fusionné de fenêtres stencil. Toutes les fenêtres stencil appartenant au même groupe fusionné ont la même valeur d'élément StencilGroup.

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


Contient un entier qui spécifie la position relative d'un pochoir au sein d'un groupe dans une fenêtre.

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


Spécifie la largeur du contrôle d'onglet de page d'une fenêtre de dessin (en tant que fraction de la largeur totale de la fenêtre de dessin).

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


Double optionnel.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


Double optionnel.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


Double optionnel.

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


Hauteur du rectangle de la fenêtre.

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


Coordonnée gauche du rectangle de la fenêtre.

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


Cet attribut peut être une somme des valeurs suivantes.

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


Coordonnée supérieure du rectangle de la fenêtre.

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


Une valeur énumérée qui peut être l'une des suivantes : Drawing, Sheet, Stencil ou Icon. Un élément Window de WindowType='Stencil' doit apparaître après sa fenêtre de dessin parente (WindowType='Drawing') et avant tout autre élément de fenêtre de dessin.

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


Largeur du rectangle de la fenêtre.

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


Pour la description de cette propriété, veuillez consulter [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


Pour la description de cette propriété, veuillez consulter [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


Pour la description de cette propriété, veuillez consulter [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


Pour la description de cette propriété, veuillez consulter [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


Pour la description de cette propriété, veuillez consulter [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


Pour la description de cette propriété, veuillez consulter [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


Pour la description de cette propriété, veuillez consulter [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


Pour la description de cette propriété, veuillez consulter [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


Pour la description de cette propriété, veuillez consulter [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


Pour la description de cette propriété, veuillez consulter [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


Pour la description de cette propriété, veuillez consulter [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


Pour la description de cette propriété, veuillez consulter [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


Pour la description de cette propriété, veuillez consulter [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


Pour la description de cette propriété, veuillez consulter [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


Pour la description de cette propriété, veuillez consulter [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


Pour la description de cette propriété, veuillez consulter [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


Pour la description de cette propriété, veuillez consulter [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


Pour la description de cette propriété, veuillez consulter [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


Pour la description de cette propriété, veuillez consulter [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


Pour la description de cette propriété, veuillez consulter [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


Pour la description de cette propriété, veuillez consulter [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


Pour la description de cette propriété, veuillez consulter [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


Pour la description de cette propriété, veuillez consulter [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


Pour la description de cette propriété, veuillez consulter [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


Pour la description de cette propriété, veuillez consulter [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


Pour la description de cette propriété, veuillez consulter [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


Pour la description de cette propriété, veuillez consulter [getWindowTop()](../../com.aspose.diagram/window\\#getWindowTop--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


Pour la description de cette propriété, veuillez consulter [getWindowType()](../../com.aspose.diagram/window\\#getWindowType--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


Pour la description de cette propriété, veuillez consulter [getWindowWidth()](../../com.aspose.diagram/window\\#getWindowWidth--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

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

