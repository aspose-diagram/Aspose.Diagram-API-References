---
title: TextBoxActiveXControl
second_title: Référence API d'Aspose.Diagram pour Java
description: Représente un contrôle ActiveX de zone de texte.
type: docs
weight: 401
url: /fr/java/com.aspose.diagram/textboxactivexcontrol/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.ActiveXControlBase](../../com.aspose.diagram/activexcontrolbase), [com.aspose.diagram.ActiveXControl](../../com.aspose.diagram/activexcontrol)
```
public class TextBoxActiveXControl extends ActiveXControl
```

Représente un contrôle ActiveX de zone de texte.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackOleColor()](#getBackOleColor--) | la couleur OLE de l'arrière-plan. |
| [getBorderOleColor()](#getBorderOleColor--) | la couleur OLE de l'arrière-plan. |
| [getBorderStyle()](#getBorderStyle--) | le type de bordure utilisé par le contrôle. |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | les données binaires du contrôle. |
| [getDropButtonStyle()](#getDropButtonStyle--) | Spécifie le symbole affiché sur le bouton déroulant |
| [getEnterFieldBehavior()](#getEnterFieldBehavior--) | Spécifie le comportement de sélection lors de l'entrée dans le contrôle. |
| [getEnterKeyBehavior()](#getEnterKeyBehavior--) | Spécifie le comportement de la touche ENTER. |
| [getForeOleColor()](#getForeOleColor--) | la couleur OLE du premier plan. |
| [getHeight()](#getHeight--) | la hauteur du contrôle en points. |
| [getHideSelection()](#getHideSelection--) | Indique si le texte sélectionné dans le contrôle apparaît en surbrillance lorsque le contrôle n'a pas le focus. |
| [getIMEMode()](#getIMEMode--) | le mode d'exécution par défaut de l'éditeur de méthode d'entrée pour le contrôle lorsqu'il reçoit le focus. |
| [getIntegralHeight()](#getIntegralHeight--) | Indique si le contrôle n'affichera que des lignes complètes de texte sans afficher de lignes partielles. |
| [getMaxLength()](#getMaxLength--) | le nombre maximal de caractères |
| [getMouseIcon()](#getMouseIcon--) | une icône personnalisée à afficher comme pointeur de la souris pour le contrôle. |
| [getMousePointer()](#getMousePointer--) | le type d'icône affiché comme pointeur de la souris pour le contrôle. |
| [getPasswordChar()](#getPasswordChar--) | un caractère à afficher à la place des caractères saisis. |
| [getScrollBars()](#getScrollBars--) | Indique si le contrôle possède des barres de défilement verticales, des barres de défilement horizontales, les deux ou aucune. |
| [getShowDropButtonTypeWhen()](#getShowDropButtonTypeWhen--) | Spécifie le symbole affiché sur le bouton déroulant |
| [getSpecialEffect()](#getSpecialEffect--) | l'effet spécial du contrôle. |
| [getTabKeyBehavior()](#getTabKeyBehavior--) | Indique si les caractères de tabulation sont autorisés dans le texte du contrôle. |
| [getText()](#getText--) | texte du contrôle. |
| [getType()](#getType--) | Obtient le type du contrôle ActiveX. |
| [getWidth()](#getWidth--) | la largeur du contrôle en unité de point. |
| [hashCode()](#hashCode--) |  |
| [isAutoSize()](#isAutoSize--) | Indique si le contrôle redimensionnera automatiquement pour afficher tout son contenu. |
| [isAutoTab()](#isAutoTab--) | Indique si le focus se déplacera automatiquement vers le contrôle suivant lorsque l'utilisateur saisit le nombre maximal de caractères. |
| [isAutoWordSelected()](#isAutoWordSelected--) | Spécifie l'unité de base utilisée pour étendre une sélection. |
| [isDragBehaviorEnabled()](#isDragBehaviorEnabled--) | Indique si le glisser-déposer est activé pour le contrôle. |
| [isEditable()](#isEditable--) | Indique si l'utilisateur peut saisir du texte dans le contrôle. |
| [isEnabled()](#isEnabled--) | Indique si le contrôle peut recevoir le focus et répondre aux événements générés par l'utilisateur. |
| [isLocked()](#isLocked--) | Indique si les données du contrôle sont verrouillées pour la modification. |
| [isMultiLine()](#isMultiLine--) | Indique si le contrôle peut afficher plus d'une ligne de texte. |
| [isTransparent()](#isTransparent--) | Indique si le contrôle est transparent. |
| [isWordWrapped()](#isWordWrapped--) | Indique si le contenu du contrôle passe automatiquement à la ligne à la fin d'une ligne. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSize(boolean value)](#setAutoSize-boolean-) | Pour la description de cette propriété, veuillez consulter [isAutoSize()](../../com.aspose.diagram/activexcontrol\#isAutoSize--) |
| [setAutoTab(boolean value)](#setAutoTab-boolean-) | Pour la description de cette propriété, veuillez consulter [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--) |
| [setAutoWordSelected(boolean value)](#setAutoWordSelected-boolean-) | Pour la description de cette propriété, veuillez consulter [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--) |
| [setBackOleColor(int value)](#setBackOleColor-int-) | Pour la description de cette propriété, veuillez consulter [getBackOleColor()](../../com.aspose.diagram/activexcontrolbase\#getBackOleColor--) |
| [setBorderOleColor(int value)](#setBorderOleColor-int-) | Pour la description de cette propriété, veuillez consulter [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--) |
| [setBorderStyle(int value)](#setBorderStyle-int-) | Pour la description de cette propriété, veuillez consulter [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--) |
| [setDragBehaviorEnabled(boolean value)](#setDragBehaviorEnabled-boolean-) | Pour la description de cette propriété, veuillez consulter [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--) |
| [setDropButtonStyle(int value)](#setDropButtonStyle-int-) | Pour la description de cette propriété, veuillez consulter [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--) |
| [setEditable(boolean value)](#setEditable-boolean-) | Pour la description de cette propriété, veuillez consulter [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--) |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Pour la description de cette propriété, veuillez consulter [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--) |
| [setEnterFieldBehavior(boolean value)](#setEnterFieldBehavior-boolean-) | Pour la description de cette propriété, veuillez consulter [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--) |
| [setEnterKeyBehavior(boolean value)](#setEnterKeyBehavior-boolean-) | Pour la description de cette propriété, veuillez consulter [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--) |
| [setForeOleColor(int value)](#setForeOleColor-int-) | Pour la description de cette propriété, veuillez consulter [getForeOleColor()](../../com.aspose.diagram/activexcontrolbase\#getForeOleColor--) |
| [setHeight(double value)](#setHeight-double-) | Pour la description de cette propriété, veuillez consulter [getHeight()](../../com.aspose.diagram/activexcontrolbase\#getHeight--) |
| [setHideSelection(boolean value)](#setHideSelection-boolean-) | Pour la description de cette propriété, veuillez consulter [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--) |
| [setIMEMode(int value)](#setIMEMode-int-) | Pour la description de cette propriété, veuillez consulter [getIMEMode()](../../com.aspose.diagram/activexcontrol\#getIMEMode--) |
| [setIntegralHeight(boolean value)](#setIntegralHeight-boolean-) | Pour la description de cette propriété, veuillez consulter [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--) |
| [setLocked(boolean value)](#setLocked-boolean-) | Pour la description de cette propriété, veuillez consulter [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--) |
| [setMaxLength(int value)](#setMaxLength-int-) | Pour la description de cette propriété, veuillez consulter [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--) |
| [setMouseIcon(byte[] value)](#setMouseIcon-byte---) | Pour la description de cette propriété, veuillez consulter [getMouseIcon()](../../com.aspose.diagram/activexcontrolbase\#getMouseIcon--) |
| [setMousePointer(int value)](#setMousePointer-int-) | Pour la description de cette propriété, veuillez consulter [getMousePointer()](../../com.aspose.diagram/activexcontrolbase\#getMousePointer--) |
| [setMultiLine(boolean value)](#setMultiLine-boolean-) | Pour la description de cette propriété, veuillez consulter [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--) |
| [setPasswordChar(char value)](#setPasswordChar-char-) | Pour la description de cette propriété, veuillez consulter [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--) |
| [setScrollBars(int value)](#setScrollBars-int-) | Pour la description de cette propriété, veuillez consulter [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--) |
| [setShowDropButtonTypeWhen(int value)](#setShowDropButtonTypeWhen-int-) | Pour la description de cette propriété, veuillez consulter [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--) |
| [setSpecialEffect(int value)](#setSpecialEffect-int-) | Pour la description de cette propriété, veuillez consulter [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--) |
| [setTabKeyBehavior(boolean value)](#setTabKeyBehavior-boolean-) | Pour la description de cette propriété, veuillez consulter [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--) |
| [setText(String value)](#setText-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--) |
| [setTransparent(boolean value)](#setTransparent-boolean-) | Pour la description de cette propriété, veuillez consulter [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--) |
| [setWidth(double value)](#setWidth-double-) | Pour la description de cette propriété, veuillez consulter [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--) |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Pour la description de cette propriété, veuillez consulter [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--) |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


les données binaires du contrôle.

**Returns:**
byte[]
### getDropButtonStyle() {#getDropButtonStyle--}
```
public int getDropButtonStyle()
```


Spécifie le symbole affiché sur le bouton déroulant

**Returns:**
int
### getEnterFieldBehavior() {#getEnterFieldBehavior--}
```
public boolean getEnterFieldBehavior()
```


Spécifie le comportement de sélection lors de l'entrée dans le contrôle. True indique que la sélection reste inchangée depuis la dernière fois que le contrôle était actif. False indique que tout le texte du contrôle sera sélectionné lors de l'entrée dans le contrôle.

**Returns:**
booléen
### getEnterKeyBehavior() {#getEnterKeyBehavior--}
```
public boolean getEnterKeyBehavior()
```


Spécifie le comportement de la touche ENTRÉE. Vrai indique que l'appui sur ENTRÉE créera une nouvelle ligne. Faux indique que l'appui sur ENTRÉE déplacera le focus vers l'objet suivant dans l'ordre de tabulation.

**Returns:**
booléen
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
### getHideSelection() {#getHideSelection--}
```
public boolean getHideSelection()
```


Indique si le texte sélectionné dans le contrôle apparaît en surbrillance lorsque le contrôle n'a pas le focus.

**Returns:**
booléen
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
### getMaxLength() {#getMaxLength--}
```
public int getMaxLength()
```


le nombre maximal de caractères

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
### getPasswordChar() {#getPasswordChar--}
```
public char getPasswordChar()
```


un caractère à afficher à la place des caractères saisis.

**Returns:**
char
### getScrollBars() {#getScrollBars--}
```
public int getScrollBars()
```


Indique si le contrôle possède des barres de défilement verticales, des barres de défilement horizontales, les deux ou aucune.

**Returns:**
int
### getShowDropButtonTypeWhen() {#getShowDropButtonTypeWhen--}
```
public int getShowDropButtonTypeWhen()
```


Spécifie le symbole affiché sur le bouton déroulant

**Returns:**
int
### getSpecialEffect() {#getSpecialEffect--}
```
public int getSpecialEffect()
```


l'effet spécial du contrôle.

**Returns:**
int
### getTabKeyBehavior() {#getTabKeyBehavior--}
```
public boolean getTabKeyBehavior()
```


Indique si les caractères de tabulation sont autorisés dans le texte du contrôle.

**Returns:**
booléen
### getText() {#getText--}
```
public String getText()
```


texte du contrôle.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public int getType()
```


Obtient le type du contrôle ActiveX.

**Returns:**
int
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
### isAutoTab() {#isAutoTab--}
```
public boolean isAutoTab()
```


Indique si le focus se déplacera automatiquement vers le contrôle suivant lorsque l'utilisateur saisit le nombre maximal de caractères.

**Returns:**
booléen
### isAutoWordSelected() {#isAutoWordSelected--}
```
public boolean isAutoWordSelected()
```


Spécifie l'unité de base utilisée pour étendre une sélection. True indique que l'unité de base est un caractère unique. false indique que l'unité de base est un mot entier.

**Returns:**
booléen
### isDragBehaviorEnabled() {#isDragBehaviorEnabled--}
```
public boolean isDragBehaviorEnabled()
```


Indique si le glisser-déposer est activé pour le contrôle.

**Returns:**
booléen
### isEditable() {#isEditable--}
```
public boolean isEditable()
```


Indique si l'utilisateur peut saisir du texte dans le contrôle.

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
### isMultiLine() {#isMultiLine--}
```
public boolean isMultiLine()
```


Indique si le contrôle peut afficher plus d'une ligne de texte.

**Returns:**
booléen
### isTransparent() {#isTransparent--}
```
public boolean isTransparent()
```


Indique si le contrôle est transparent.

**Returns:**
booléen
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


Indique si le contenu du contrôle passe automatiquement à la ligne à la fin d'une ligne.

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

### setAutoTab(boolean value) {#setAutoTab-boolean-}
```
public void setAutoTab(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isAutoTab()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoTab--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setAutoWordSelected(boolean value) {#setAutoWordSelected-boolean-}
```
public void setAutoWordSelected(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isAutoWordSelected()](../../com.aspose.diagram/textboxactivexcontrol\#isAutoWordSelected--)

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


Pour la description de cette propriété, veuillez consulter [getBorderOleColor()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderOleColor--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setBorderStyle(int value) {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```


Pour la description de cette propriété, veuillez consulter [getBorderStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getBorderStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setDragBehaviorEnabled(boolean value) {#setDragBehaviorEnabled-boolean-}
```
public void setDragBehaviorEnabled(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isDragBehaviorEnabled()](../../com.aspose.diagram/textboxactivexcontrol\#isDragBehaviorEnabled--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setDropButtonStyle(int value) {#setDropButtonStyle-int-}
```
public void setDropButtonStyle(int value)
```


Pour la description de cette propriété, veuillez consulter [getDropButtonStyle()](../../com.aspose.diagram/textboxactivexcontrol\#getDropButtonStyle--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEditable(boolean value) {#setEditable-boolean-}
```
public void setEditable(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isEditable()](../../com.aspose.diagram/textboxactivexcontrol\#isEditable--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isEnabled()](../../com.aspose.diagram/activexcontrol\#isEnabled--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setEnterFieldBehavior(boolean value) {#setEnterFieldBehavior-boolean-}
```
public void setEnterFieldBehavior(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getEnterFieldBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterFieldBehavior--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setEnterKeyBehavior(boolean value) {#setEnterKeyBehavior-boolean-}
```
public void setEnterKeyBehavior(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getEnterKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getEnterKeyBehavior--)

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

### setHideSelection(boolean value) {#setHideSelection-boolean-}
```
public void setHideSelection(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getHideSelection()](../../com.aspose.diagram/textboxactivexcontrol\#getHideSelection--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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


Pour la description de cette propriété, veuillez consulter [getIntegralHeight()](../../com.aspose.diagram/textboxactivexcontrol\#getIntegralHeight--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public void setLocked(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isLocked()](../../com.aspose.diagram/activexcontrol\#isLocked--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setMaxLength(int value) {#setMaxLength-int-}
```
public void setMaxLength(int value)
```


Pour la description de cette propriété, veuillez consulter [getMaxLength()](../../com.aspose.diagram/textboxactivexcontrol\#getMaxLength--)

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

### setMultiLine(boolean value) {#setMultiLine-boolean-}
```
public void setMultiLine(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isMultiLine()](../../com.aspose.diagram/textboxactivexcontrol\#isMultiLine--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setPasswordChar(char value) {#setPasswordChar-char-}
```
public void setPasswordChar(char value)
```


Pour la description de cette propriété, veuillez consulter [getPasswordChar()](../../com.aspose.diagram/textboxactivexcontrol\#getPasswordChar--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | char |  |

### setScrollBars(int value) {#setScrollBars-int-}
```
public void setScrollBars(int value)
```


Pour la description de cette propriété, veuillez consulter [getScrollBars()](../../com.aspose.diagram/textboxactivexcontrol\#getScrollBars--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setShowDropButtonTypeWhen(int value) {#setShowDropButtonTypeWhen-int-}
```
public void setShowDropButtonTypeWhen(int value)
```


Pour la description de cette propriété, veuillez consulter [getShowDropButtonTypeWhen()](../../com.aspose.diagram/textboxactivexcontrol\#getShowDropButtonTypeWhen--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSpecialEffect(int value) {#setSpecialEffect-int-}
```
public void setSpecialEffect(int value)
```


Pour la description de cette propriété, veuillez consulter [getSpecialEffect()](../../com.aspose.diagram/textboxactivexcontrol\#getSpecialEffect--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTabKeyBehavior(boolean value) {#setTabKeyBehavior-boolean-}
```
public void setTabKeyBehavior(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getTabKeyBehavior()](../../com.aspose.diagram/textboxactivexcontrol\#getTabKeyBehavior--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Pour la description de cette propriété, veuillez consulter [getText()](../../com.aspose.diagram/textboxactivexcontrol\#getText--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setTransparent(boolean value) {#setTransparent-boolean-}
```
public void setTransparent(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isTransparent()](../../com.aspose.diagram/activexcontrol\#isTransparent--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Pour la description de cette propriété, veuillez consulter [getWidth()](../../com.aspose.diagram/activexcontrolbase\#getWidth--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


Pour la description de cette propriété, veuillez consulter [isWordWrapped()](../../com.aspose.diagram/textboxactivexcontrol\#isWordWrapped--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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

