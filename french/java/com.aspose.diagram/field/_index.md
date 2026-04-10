---
title: Champ
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des éléments qui spécifient les fonctions et formules insérées dans le texte des formes.
type: docs
weight: 147
url: /fr/java/com.aspose.diagram/field/
---

**Inheritance:**
java.lang.Object
```
public class Field
```

Contient des éléments qui spécifient les fonctions et formules insérées dans le texte de la forme.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Field()](#Field--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Détermine le calendrier utilisé pour les propriétés personnalisées, les champs de texte et les formules d'éléments. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getDisplayValue()](#getDisplayValue--) | Obtient la valeur de chaîne formatée de ce champ. |
| [getEditMode()](#getEditMode--) | Réservé pour une utilisation future. |
| [getFormat()](#getFormat--) | L'élément Format spécifie le formatage d'un champ texte qui est une chaîne, un nombre, une date ou une heure, une durée ou une devise. |
| [getIX()](#getIX--) | L'indice basé sur zéro de l'élément au sein de son élément parent. |
| [getObjectKind()](#getObjectKind--) | Indique le type de champ texte. |
| [getType()](#getType--) | Le type spécifie un type de données pour la valeur du champ texte. |
| [getUICat()](#getUICat--) | Spécifie la catégorie d'un champ inséré dans les versions de Microsoft Visio antérieures à Visio 2000. |
| [getUICod()](#getUICod--) | Spécifie le code d'un champ inséré dans les versions de Microsoft Visio antérieures à Visio 2000. |
| [getUIFmt()](#getUIFmt--) | Spécifie le format d'un champ inséré dans les versions de Microsoft Visio antérieures à Visio 2000. |
| [getValue()](#getValue--) | Il contient la valeur d'un champ texte. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/field\#getDel--) |
| [setIX(int value)](#setIX-int-) | Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/field\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Field() {#Field--}
```
public Field()
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
### getDisplayValue() {#getDisplayValue--}
```
public String getDisplayValue()
```


Obtient la valeur de chaîne formatée de ce champ.

**Returns:**
java.lang.String
### getEditMode() {#getEditMode--}
```
public DoubleValue getEditMode()
```


Réservé pour une utilisation future.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFormat() {#getFormat--}
```
public Value getFormat()
```


L'élément Format spécifie le formatage d'un champ texte qui est une chaîne, un nombre, une date ou une heure, une durée ou une devise. Le type du champ texte est indiqué dans l'élément Type correspondant.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getIX() {#getIX--}
```
public int getIX()
```


L'indice basé sur zéro de l'élément au sein de son élément parent.

**Returns:**
int
### getObjectKind() {#getObjectKind--}
```
public ObjectKind getObjectKind()
```


Indique le type de champ texte.

**Returns:**
[ObjectKind](../../com.aspose.diagram/objectkind)
### getType() {#getType--}
```
public TypeField getType()
```


Le type spécifie un type de données pour la valeur du champ texte.

**Returns:**
[TypeField](../../com.aspose.diagram/typefield)
### getUICat() {#getUICat--}
```
public DoubleValue getUICat()
```


Spécifie la catégorie d'un champ inséré dans les versions de Microsoft Visio antérieures à Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUICod() {#getUICod--}
```
public DoubleValue getUICod()
```


Spécifie le code d'un champ inséré dans les versions de Microsoft Visio antérieures à Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUIFmt() {#getUIFmt--}
```
public DoubleValue getUIFmt()
```


Spécifie le format d'un champ inséré dans les versions de Microsoft Visio antérieures à Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getValue() {#getValue--}
```
public Value getValue()
```


Il contient la valeur d'un champ texte.

**Returns:**
[Value](../../com.aspose.diagram/value)
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


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/field\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/field\#getIX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

