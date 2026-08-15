---
title: ListBoxActiveXControl
second_title: Référence API d'Aspose.Diagram pour Java
description: Représente un contrôle ActiveX ListBox.
type: docs
weight: 234
url: /fr/java/com.aspose.diagram/listboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class ListBoxActiveXControl extends ActiveXControl
```

Représente un contrôle ActiveX ListBox.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | la couleur OLE de l'arrière-plan. |
| [getBorderOleColor()](#getBorderOleColor--) | la couleur OLE de l'arrière-plan. |
| [getBorderStyle()](#getBorderStyle--) | le type de bordure utilisé par le contrôle. |
| [getBoundColumn()](#getBoundColumn--) | Représente la façon dont la propriété Value est déterminée pour une ComboBox ou une ListBox lorsque la valeur de la propriété MultiSelect (fmMultiSelectSingle). |
| [getClass()](#getClass--) |  |
| [getColumnCount()](#getColumnCount--) | Représente le nombre de colonnes à afficher dans une ComboBox ou une ListBox. |
| [getColumnWidths()](#getColumnWidths--) | la largeur de la colonne. |
| [getData()](#getData--) | les données binaires du contrôle. |
| [getForeOleColor()](#getForeOleColor--) | la couleur OLE du premier plan. |
| [getHeight()](#getHeight--) | la hauteur du contrôle en points. |
| [getIMEMode()](#getIMEMode--) | le mode d'exécution par défaut de l'éditeur de méthode d'entrée pour le contrôle lorsqu'il reçoit le focus. |
| [getIntegralHeight()](#getIntegralHeight--) | Indique si le contrôle n'affichera que des lignes complètes de texte sans afficher de lignes partielles. |
| [getListStyle()](#getListStyle--) | l'apparence visuelle. |
| [getListWidth()](#getListWidth--) | la largeur en unité de points. |
| [getMatchEntry()](#getMatchEntry--) | Indique comment une ListBox ou une ComboBox recherche dans sa liste pendant que l'utilisateur tape. |
| [getMouseIcon()](#getMouseIcon--) | une icône personnalisée à afficher comme pointeur de la souris pour le contrôle. |
| [getMousePointer()](#getMousePointer--) | le type d'icône affiché comme pointeur de la souris pour le contrôle. |
| [getScrollBars()](#getScrollBars--) | Indique si le contrôle possède des barres de défilement verticales, des barres de défilement horizontales, les deux ou aucune. |
| [getShowColumnHeads()](#getShowColumnHeads--) | Indique si les en-têtes de colonne sont affichés. |
| [getSpecialEffect()](#getSpecialEffect--) | l'effet spécial du contrôle. |
| [getTextColumn()](#getTextColumn--) | Représente la colonne dans une ComboBox ou une ListBox à afficher à l'utilisateur. |
| [getType()](#getType--) | Obtient le type du contrôle ActiveX. |
| [getValue()](#getValue--) | la valeur du contrôle. |
| [getWidth()](#getWidth--) | la largeur du contrôle en unité de point. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indique si le contrôle redimensionnera automatiquement pour afficher tout son contenu. |
| [isEnabled()](#isEnabled--) | Indique si le contrôle peut recevoir le focus et répondre aux événements générés par l'utilisateur. |
| [isLocked()](#isLocked--) | Indique si les données du contrôle sont verrouillées pour la modification. |
| [isTransparent()](#isTransparent--) | Indique si le contrôle est transparent. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Pour la description de cette propriété, veuillez consulter [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Pour la description de cette propriété, veuillez consulter [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Pour la description de cette propriété, veuillez consulter [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Pour la description de cette propriété, veuillez consulter [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\\#getBorderStyle--) |
| [setBoundColumn(int value)](#setBoundColumn-int-) | Pour la description de cette propriété, veuillez consulter [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\\#getBoundColumn--) |
| [setColumnCount(int value)](#setColumnCount-int-) | Pour la description de cette propriété, veuillez consulter [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\\#getColumnCount--) |
| [setColumnWidths(double value)](#setColumnWidths-double-) | Pour la description de cette propriété, veuillez consulter [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\\#getColumnWidths--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Pour la description de cette propriété, veuillez consulter [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Pour la description de cette propriété, veuillez consulter [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Pour la description de cette propriété, veuillez consulter [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Pour la description de cette propriété, veuillez consulter [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | Pour la description de cette propriété, veuillez consulter [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\\#getIntegralHeight--) |
| [setListStyle(int value)](#setListStyle-int-) | Pour la description de cette propriété, veuillez consulter [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--) |
| [setListWidth(double value)](#setListWidth-double-) | Pour la description de cette propriété, veuillez consulter [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Pour la description de cette propriété, veuillez consulter [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMatchEntry(int value)](#setMatchEntry-int-) | Pour la description de cette propriété, veuillez consulter [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Pour la description de cette propriété, veuillez consulter [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Pour la description de cette propriété, veuillez consulter [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setScrollBars(int value)](#setScrollBars-int-) | Pour la description de cette propriété, veuillez consulter [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--) |
| [setShowColumnHeads(boolean value)](#setShowColumnHeads-boolean-) | Pour la description de cette propriété, veuillez consulter [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Pour la description de cette propriété, veuillez consulter [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--) |
| [setTextColumn(int value)](#setTextColumn-int-) | Pour la description de cette propriété, veuillez consulter [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Pour la description de cette propriété, veuillez consulter [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setValue(String value)](#setValue-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--) |
| [setWidth(double value)](#setWidth-double-) | Pour la description de cette propriété, veuillez consulter [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBackOleColor() {#getBackOleColor--}
```
public int getBackOleColor()
```


la couleur OLE de l'arrière-plan.

**Returns:**
int
### getBorderOleColor() {#getBorderOleColor--}
```
public int getBorderOleColor()
```


la couleur OLE de l'arrière-plan.

**Returns:**
int
### getBorderStyle() {#getBorderStyle--}
```
public int getBorderStyle()
```


le type de bordure utilisé par le contrôle.

**Returns:**
int
### getBoundColumn() {#getBoundColumn--}
```
public int getBoundColumn()
```


Représente la façon dont la propriété Value est déterminée pour une ComboBox ou une ListBox lorsque la valeur de la propriété MultiSelect (fmMultiSelectSingle).

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumnCount() {#getColumnCount--}
```
public int getColumnCount()
```


Représente le nombre de colonnes à afficher dans une ComboBox ou une ListBox.

**Returns:**
int
### getColumnWidths() {#getColumnWidths--}
```
public double getColumnWidths()
```


la largeur de la colonne.

**Returns:**
double
### getData() {#getData--}
```
public byte[] getData()
```


les données binaires du contrôle.

**Returns:**
byte[]
### getForeOleColor() {#getForeOleColor--}
```
public int getForeOleColor()
```


la couleur OLE du premier plan. Ne s'applique pas au contrôle Image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public double getHeight()
```


la hauteur du contrôle en points.

**Returns:**
double
### getIMEMode() {#getIMEMode--}
```
public int getIMEMode()
```


le mode d'exécution par défaut de l'éditeur de méthode d'entrée pour le contrôle lorsqu'il reçoit le focus.

**Returns:**
int
### getIntegralHeight() {#getIntegralHeight--}
```
public boolean getIntegralHeight()
```


Indique si le contrôle n'affichera que des lignes complètes de texte sans afficher de lignes partielles.

**Returns:**
booléen
### getListStyle() {#getListStyle--}
```
public int getListStyle()
```


l'apparence visuelle.

**Returns:**
int
### getListWidth() {#getListWidth--}
```
public double getListWidth()
```


la largeur en unité de points.

**Returns:**
double
### getMatchEntry() {#getMatchEntry--}
```
public int getMatchEntry()
```


Indique comment une ListBox ou une ComboBox recherche dans sa liste pendant que l'utilisateur tape.

**Returns:**
int
### getMouseIcon() {#getMouseIcon--}
```
public byte[] getMouseIcon()
```


une icône personnalisée à afficher comme pointeur de la souris pour le contrôle.

**Returns:**
byte[]
### getMousePointer() {#getMousePointer--}
```
public int getMousePointer()
```


le type d'icône affiché comme pointeur de la souris pour le contrôle.

**Returns:**
int
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


Indique si le contrôle possède des barres de défilement verticales, des barres de défilement horizontales, les deux ou aucune.

**Returns:**
int
### getShowColumnHeads() {#getShowColumnHeads--}
```
public boolean getShowColumnHeads()
```


Indique si les en-têtes de colonne sont affichés.

**Returns:**
booléen
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


l'effet spécial du contrôle.

**Returns:**
int
### getTextColumn() {#getTextColumn--}
```
public int getTextColumn()
```


Représente la colonne dans une ComboBox ou une ListBox à afficher à l'utilisateur.

**Returns:**
int
### getType() {#getType--}
```
public int getType()
```


Obtient le type du contrôle ActiveX.

**Returns:**
int
### getValue() {#getValue--}
```
public String getValue()
```


la valeur du contrôle.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public double getWidth()
```


la largeur du contrôle en unité de point.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoSize() {#isAutoSize--}
```
public boolean isAutoSize()
```


Indique si le contrôle redimensionnera automatiquement pour afficher tout son contenu.

**Returns:**
booléen
### isEnabled() {#isEnabled--}
```
public boolean isEnabled()
```


Indique si le contrôle peut recevoir le focus et répondre aux événements générés par l'utilisateur.

**Returns:**
booléen
### isLocked() {#isLocked--}
```
public boolean isLocked()
```


Indique si les données du contrôle sont verrouillées pour la modification.

**Returns:**
booléen
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Indique si le contrôle est transparent.

**Returns:**
booléen
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAutoSize(boolean value) {#setAutoSize-boolean-}
```
public void setAutoSize(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setBackOleColor(int value) {#setBackOleColor-int-}
```
public void setBackOleColor(int value)
```


Pour la description de cette propriété, veuillez consulter [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setBorderOleColor(int value) {#setBorderOleColor-int-}
```
public void setBorderOleColor(int value)
```


Pour la description de cette propriété, veuillez consulter [getBorderOleColor()](../../com.aspose.diagram/listboxactivexcontrol\\#getBorderOleColor--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Pour la description de cette propriété, veuillez consulter [getBorderStyle()](../../com.aspose.diagram/listboxactivexcontrol\\#getBorderStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setBoundColumn(int value) {#setBoundColumn-int-}
```
public void setBoundColumn(int value)
```


Pour la description de cette propriété, veuillez consulter [getBoundColumn()](../../com.aspose.diagram/listboxactivexcontrol\\#getBoundColumn--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setColumnCount(int value) {#setColumnCount-int-}
```
public void setColumnCount(int value)
```


Pour la description de cette propriété, veuillez consulter [getColumnCount()](../../com.aspose.diagram/listboxactivexcontrol\\#getColumnCount--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setColumnWidths(double value) {#setColumnWidths-double-}
```
public void setColumnWidths(double value)
```


Pour la description de cette propriété, veuillez consulter [getColumnWidths()](../../com.aspose.diagram/listboxactivexcontrol\\#getColumnWidths--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setForeOleColor(int value) {#setForeOleColor-int-}
```
public void setForeOleColor(int value)
```


Pour la description de cette propriété, veuillez consulter [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Pour la description de cette propriété, veuillez consulter [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setIMEMode(int value) {#setIMEMode-int-}
```
public void setIMEMode(int value)
```


Pour la description de cette propriété, veuillez consulter [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setIntegralHeight(boolean value) {#setIntegralHeight-boolean-}
```
public void setIntegralHeight(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getIntegralHeight()](../../com.aspose.diagram/listboxactivexcontrol\\#getIntegralHeight--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setListStyle(int value) {#setListStyle-int-}
```
public void setListStyle(int value)
```


Pour la description de cette propriété, veuillez consulter [getListStyle()](../../com.aspose.diagram/listboxactivexcontrol\#getListStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setListWidth(double value) {#setListWidth-double-}
```
public void setListWidth(double value)
```


Pour la description de cette propriété, veuillez consulter [getListWidth()](../../com.aspose.diagram/listboxactivexcontrol\#getListWidth--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setMatchEntry(int value) {#setMatchEntry-int-}
```
public void setMatchEntry(int value)
```


Pour la description de cette propriété, veuillez consulter [getMatchEntry()](../../com.aspose.diagram/listboxactivexcontrol\#getMatchEntry--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMouseIcon(byte[] value) {#setMouseIcon-byte---}
```
public void setMouseIcon(byte[] value)
```


Pour la description de cette propriété, veuillez consulter [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setMousePointer(int value) {#setMousePointer-int-}
```
public void setMousePointer(int value)
```


Pour la description de cette propriété, veuillez consulter [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


Pour la description de cette propriété, veuillez consulter [getScrollBars()](../../com.aspose.diagram/listboxactivexcontrol\#getScrollBars--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShowColumnHeads(boolean value) {#setShowColumnHeads-boolean-}
```
public void setShowColumnHeads(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getShowColumnHeads()](../../com.aspose.diagram/listboxactivexcontrol\#getShowColumnHeads--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Pour la description de cette propriété, veuillez consulter [getSpecialEffect()](../../com.aspose.diagram/listboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTextColumn(int value) {#setTextColumn-int-}
```
public void setTextColumn(int value)
```


Pour la description de cette propriété, veuillez consulter [getTextColumn()](../../com.aspose.diagram/listboxactivexcontrol\#getTextColumn--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Pour la description de cette propriété, veuillez consulter [getValue()](../../com.aspose.diagram/listboxactivexcontrol\#getValue--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Pour la description de cette propriété, veuillez consulter [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

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

