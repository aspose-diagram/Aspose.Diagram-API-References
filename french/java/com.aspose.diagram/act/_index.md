---
title: Act
second_title: Référence API d'Aspose.Diagram pour Java
description: Définit les noms de commandes personnalisées qui apparaissent dans le menu contextuel d'un objet et spécifie les actions que les commandes exécutent.
type: docs
weight: 11
url: /fr/java/com.aspose.diagram/act/
---

**Inheritance:**
java.lang.Object
```
public class Act
```

Définit les noms de commandes personnalisées qui apparaissent dans le menu contextuel d'un objet et spécifie les actions que ces commandes exécutent.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Act()](#Act--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Contient la formule à exécuter lorsqu'un utilisateur clique sur le nom de commande défini dans l'élément Menu correspondant. |
| [getBeginGroup()](#getBeginGroup--) | Indique si un séparateur est inséré dans le menu au-dessus de cette action. |
| [getButtonFace()](#getButtonFace--) | Il identifie l'icône qui apparaît à côté d'un élément dans un menu contextuel. |
| [getChecked()](#getChecked--) | Détermine si une coche est affichée à côté du nom de la commande dans le menu contextuel d'une forme. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getDisabled()](#getDisabled--) | L'élément Disabled détermine si le nom de la commande est affiché dans le menu contextuel. |
| [getFlyoutChild()](#getFlyoutChild--) | Détermine si la ligne d'action est un sous‑menu déroulant enfant de la dernière ligne au-dessus qui n'est pas un enfant déroulant. |
| [getID()](#getID--) | L'ID unique de l'élément au sein de son élément parent. |
| [getIX()](#getIX--) | L'indice basé sur zéro de l'élément au sein de son élément parent. |
| [getInvisible()](#getInvisible--) | L'élément Invisible indique si l'action est visible sur le smart tag ou le menu contextuel. |
| [getMenu()](#getMenu--) | Spécifie le nom de la commande qui apparaît dans le menu contextuel d'une forme ou d'une page. |
| [getName()](#getName--) | Le nom de l'élément. |
| [getNameU()](#getNameU--) | Le nom universel de l'élément. |
| [getReadOnly()](#getReadOnly--) | Détermine si l'action sur un smart tag ou un menu contextuel est en lecture seule. |
| [getSortKey()](#getSortKey--) | Il spécifie un nombre qui détermine l'ordre des actions apparaissant dans un menu contextuel ou smart tag. |
| [getTagName()](#getTagName--) | Il contient le nom de l'étiquette intelligente à laquelle l'action est associée. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/act\#getDel--) |
| [setID(int value)](#setID-int-) | Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/act\#getID--) |
| [setIX(int value)](#setIX-int-) | Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/act\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/act\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/act\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Act() {#Act--}
```
public Act()
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
### getAction() {#getAction--}
```
public DoubleValue getAction()
```


Contient la formule à exécuter lorsqu'un utilisateur clique sur le nom de commande défini dans l'élément Menu correspondant.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBeginGroup() {#getBeginGroup--}
```
public BoolValue getBeginGroup()
```


Indique si un séparateur est inséré dans le menu au-dessus de cette action.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getButtonFace() {#getButtonFace--}
```
public Str2Value getButtonFace()
```


Il identifie l'icône qui apparaît à côté d'un élément dans un menu contextuel.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getChecked() {#getChecked--}
```
public BoolValue getChecked()
```


Détermine si une coche est affichée à côté du nom de la commande dans le menu contextuel d'une forme.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


Un indicateur indiquant si l'élément a été supprimé localement. Une valeur de 1 indique que l'élément a été supprimé localement.

**Returns:**
int
### getDisabled() {#getDisabled--}
```
public BoolValue getDisabled()
```


L'élément Disabled détermine si le nom de la commande est affiché dans le menu contextuel.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlyoutChild() {#getFlyoutChild--}
```
public BoolValue getFlyoutChild()
```


Détermine si la ligne d'action est un sous‑menu déroulant enfant de la dernière ligne au-dessus qui n'est pas un enfant déroulant.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getID() {#getID--}
```
public int getID()
```


L'ID unique de l'élément au sein de son élément parent.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basé sur zéro de l'élément au sein de son élément parent.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


L'élément Invisible indique si l'action est visible sur le smart tag ou le menu contextuel.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getMenu() {#getMenu--}
```
public Str2Value getMenu()
```


Spécifie le nom de la commande qui apparaît dans le menu contextuel d'une forme ou d'une page.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getReadOnly() {#getReadOnly--}
```
public BoolValue getReadOnly()
```


Détermine si l'action sur un smart tag ou un menu contextuel est en lecture seule.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Il spécifie un nombre qui détermine l'ordre des actions apparaissant dans un menu contextuel ou smart tag.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getTagName() {#getTagName--}
```
public Str2Value getTagName()
```


Il contient le nom de l'étiquette intelligente à laquelle l'action est associée.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/act\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/act\#getID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/act\#getIX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/act\#getName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/act\#getNameU--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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

