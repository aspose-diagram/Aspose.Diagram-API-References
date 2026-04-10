---
title: Prop
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des éléments pour définir des propriétés personnalisées et des éléments pour associer des données à une forme.
type: docs
weight: 309
url: /fr/java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

Contient des éléments pour définir des propriétés personnalisées et des éléments pour associer des données à une forme.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Prop()](#Prop--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Détermine le calendrier utilisé pour les propriétés personnalisées, les champs de texte et les formules d'éléments. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getFormat()](#getFormat--) | L'élément de format spécifie le format d'une propriété personnalisée qui est une chaîne, une liste fixe, un nombre, une liste variable, une date ou une heure, une durée ou une devise. |
| [getID()](#getID--) | L'ID unique de l'élément au sein de son élément parent. |
| [getIX()](#getIX--) | L'indice basé sur zéro de l'élément au sein de son élément parent. |
| [getInvisible()](#getInvisible--) | L'élément Invisible spécifie si la propriété personnalisée est visible dans la boîte de dialogue Propriétés personnalisées de Microsoft Visio. |
| [getLabel()](#getLabel--) | Spécifie l'étiquette qui apparaît aux utilisateurs dans la boîte de dialogue Propriétés personnalisées. |
| [getLangID()](#getLangID--) | Indique l'ID de paramètre régional (LCID) de la langue dans laquelle la formule de cellule, le texte, la propriété personnalisée ou le commentaire a été saisi. |
| [getName()](#getName--) | Le nom de l'élément. |
| [getNameU()](#getNameU--) | Le nom universel de l'élément. |
| [getPrompt()](#getPrompt--) | L'élément Invite spécifie le texte descriptif ou instructif qui apparaît aux utilisateurs dans la boîte de dialogue Propriétés personnalisées lorsque la propriété est sélectionnée. |
| [getSortKey()](#getSortKey--) | Il spécifie une clé qui détermine l'ordre dans lequel les propriétés personnalisées sont listées dans l'interface utilisateur de l'application. |
| [getType()](#getType--) | Le type spécifie un type de données pour la valeur de la propriété personnalisée. |
| [getValue()](#getValue--) | Contient des données XML bien formées spécifiques à la solution, préfixées dans un espace de noms explicite et stockées avec un document. |
| [getVerify()](#getVerify--) | Spécifie si l'utilisateur est invité à saisir les informations de propriété personnalisée pour une forme lorsqu'une instance est créée ou que la forme est dupliquée ou copiée. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/prop\#getDel--) |
| [setID(int value)](#setID-int-) | Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/prop\#getID--) |
| [setIX(int value)](#setIX-int-) | Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/prop\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/prop\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/prop\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


Constructeur.

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


Crée une copie profonde de cette instance.

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Détermine le calendrier utilisé pour les propriétés personnalisées, les champs de texte et les formules d'éléments.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
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
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


L'élément Format spécifie le formatage d'une propriété personnalisée qui est une chaîne, une liste fixe, un nombre, une liste variable, une date ou une heure, une durée ou une devise. Le type de propriété personnalisée est indiqué dans l'élément Type correspondant.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
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


L'élément Invisible spécifie si la propriété personnalisée est visible dans la boîte de dialogue Propriétés personnalisées de Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


Spécifie l'étiquette qui apparaît aux utilisateurs dans la boîte de dialogue Propriétés personnalisées.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Indique l'ID de paramètre régional (LCID) de la langue dans laquelle la formule de cellule, le texte, la propriété personnalisée ou le commentaire a été saisi.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


L'élément Prompt spécifie le texte descriptif ou d'instruction qui apparaît aux utilisateurs dans la boîte de dialogue Propriétés personnalisées lorsque la propriété est sélectionnée. Ce texte apparaît également comme une infobulle lorsque le pointeur de la souris est placé sur la propriété dans la fenêtre Propriétés personnalisées.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Il spécifie une clé qui détermine l'ordre dans lequel les propriétés personnalisées sont listées dans l'interface utilisateur de l'application.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Le type spécifie un type de données pour la valeur de la propriété personnalisée.

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


Contient des données XML bien formées spécifiques à la solution, préfixées dans un espace de noms explicite et stockées avec un document.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


Spécifie si l'utilisateur est invité à saisir les informations de propriété personnalisée pour une forme lorsqu'une instance est créée ou que la forme est dupliquée ou copiée.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/prop\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/prop\#getID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/prop\#getIX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/prop\#getName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/prop\#getNameU--)

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

