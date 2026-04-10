---
title: Hyperlien
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des éléments permettant de créer plusieurs sauts entre une forme ou une page de dessin et une autre page de dessin, un autre fichier ou un site Web.
type: docs
weight: 193
url: /fr/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

Contient les éléments permettant de créer plusieurs sauts entre une forme ou une page de dessin et une autre page de dessin, un autre fichier ou un site Web.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | Spécifie une adresse URL, un nom de fichier DOS ou un chemin UNC vers lequel sauter. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Spécifie l'hyperlien par défaut pour une forme ou une page. |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getDescription()](#getDescription--) | L'élément Description contient une chaîne de texte qui décrit l'hyperlien. |
| [getExtraInfo()](#getExtraInfo--) | Contient des informations à utiliser pour résoudre une URL, telles que les coordonnées d'une carte d'image. |
| [getFrame()](#getFrame--) | Contient le nom d'un cadre cible lorsque Microsoft Visio est ouvert comme document actif dans une application conteneur. |
| [getID()](#getID--) | L'ID unique de l'élément au sein de son élément parent. |
| [getInvisible()](#getInvisible--) | L'élément Invisible indique si un hyperlien apparaît dans le menu contextuel d'une forme ou d'une page. |
| [getName()](#getName--) | Le nom de l'élément. |
| [getNameU()](#getNameU--) | Le nom universel de l'élément. |
| [getNewWindow()](#getNewWindow--) | Spécifie si Microsoft Visio ouvre une fenêtre à un nouvel emplacement lorsqu'il suit un hyperlien pour ouvrir une page Web ou un autre document Visio. |
| [getSortKey()](#getSortKey--) | L'élément Invisible indique si un hyperlien apparaît dans le menu contextuel d'une forme ou d'une page. |
| [getSubAddress()](#getSubAddress--) | Spécifie un emplacement dans le document cible vers lequel créer le lien. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/hyperlink\#getDel--) |
| [setID(int value)](#setID-int-) | Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/hyperlink\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/hyperlink\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


Spécifie une adresse URL, un nom de fichier DOS ou un chemin UNC vers lequel sauter.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public BoolValue getDefault()
```


Spécifie l'hyperlien par défaut pour une forme ou une page.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Un indicateur indiquant si l'élément a été supprimé localement. Une valeur de 1 indique que l'élément a été supprimé localement.

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


L'élément Description contient une chaîne de texte qui décrit l'hyperlien.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


Contient des informations à utiliser pour résoudre une URL, telles que les coordonnées d'une carte d'image. Par exemple, x=41 y=7 spécifierait les coordonnées d'une carte d'image.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


Contient le nom d'un cadre cible lorsque Microsoft Visio est ouvert comme document actif dans une application conteneur. La valeur par défaut est une chaîne vide.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


L'ID unique de l'élément au sein de son élément parent.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


L'élément Invisible indique si un hyperlien apparaît dans le menu contextuel d'une forme ou d'une page.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


Spécifie si Microsoft Visio ouvre une fenêtre à un nouvel emplacement lorsqu'il suit un hyperlien pour ouvrir une page Web ou un autre document Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


L'élément Invisible indique si un hyperlien apparaît dans le menu contextuel d'une forme ou d'une page.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


Spécifie un emplacement dans le document cible vers lequel créer le lien.

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


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/hyperlink\#getID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/hyperlink\#getName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)

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

