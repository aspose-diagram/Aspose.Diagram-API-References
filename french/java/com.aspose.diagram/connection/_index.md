---
title: Connexion
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des éléments pour un point de connexion défini pour la forme.
type: docs
weight: 78
url: /fr/java/com.aspose.diagram/connection/
---

**Inheritance:**
java.lang.Object
```
public class Connection
```

Contient des éléments pour un point de connexion défini pour la forme.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Connection()](#Connection--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoGen()](#getAutoGen--) | Spécifie si le point de connexion est généré automatiquement. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getDirX()](#getDirX--) | Spécifie la composante x du vecteur d’alignement requis d’un point de connexion correspondant. |
| [getDirY()](#getDirY--) | Spécifie la composante y du vecteur d’alignement requis d’un point de connexion correspondant. |
| [getID()](#getID--) | L'ID unique de l'élément au sein de son élément parent. |
| [getIX()](#getIX--) | L'indice basé sur zéro de l'élément au sein de son élément parent. |
| [getName()](#getName--) | Le nom de l'élément. |
| [getNameU()](#getNameU--) | Le nom universel de l'élément. |
| [getPrompt()](#getPrompt--) | Contient des informations d’invite variables, en fonction de l’élément dans lequel il est contenu. |
| [getType()](#getType--) | Spécifie divers types, en fonction de l'élément dans lequel il est contenu. |
| [getX()](#getX--) | Spécifie une coordonnée x sur une forme dans les coordonnées locales. |
| [getY()](#getY--) | Spécifie une coordonnée y sur une forme dans les coordonnées locales. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/connection\#getDel--) |
| [setID(int value)](#setID-int-) | Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/connection\#getID--) |
| [setIX(int value)](#setIX-int-) | Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/connection\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/connection\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/connection\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Connection() {#Connection--}
```
public Connection()
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
### getAutoGen() {#getAutoGen--}
```
public BoolValue getAutoGen()
```


Spécifie si le point de connexion est généré automatiquement. Une valeur de 1 indique que le point de connexion est généré automatiquement.

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
### getDirX() {#getDirX--}
```
public DoubleValue getDirX()
```


Spécifie la composante x du vecteur d’alignement requis d’un point de connexion correspondant. L’élément DirX est également utilisé pour orienter la jambe attachée d’un connecteur dynamique.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDirY() {#getDirY--}
```
public DoubleValue getDirY()
```


Spécifie la composante y du vecteur d’alignement requis d’un point de connexion correspondant. L’élément DirY est également utilisé pour orienter la jambe attachée d’un connecteur dynamique.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


Contient des informations d’invite variables, en fonction de l’élément dans lequel il est contenu.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeConnection getType()
```


Spécifie divers types, en fonction de l'élément dans lequel il est contenu.

**Returns:**
[TypeConnection](../../com.aspose.diagram/typeconnection)
### getX() {#getX--}
```
public DoubleValue getX()
```


Spécifie une coordonnée x sur une forme dans les coordonnées locales.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


Spécifie une coordonnée y sur une forme en coordonnées locales. Les coordonnées locales sont celles dont le cadre de référence est la forme, plutôt que la page.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/connection\#getDel--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/connection\#getID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Pour la description de cette propriété, veuillez consulter [getIX()](../../com.aspose.diagram/connection\#getIX--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/connection\#getName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/connection\#getNameU--)

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

