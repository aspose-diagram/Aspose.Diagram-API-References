---
title: Master
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient les éléments qui définissent un maître pour le document.
type: docs
weight: 240
url: /fr/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

Contient des éléments qui définissent un master pour le document. Un master est une forme sur un gabarit que vous utilisez de manière répétée pour créer des dessins. Lorsque vous faites glisser une forme depuis un gabarit vers la page de dessin, la forme devient une instance de ce master, et une copie locale du master est incluse dans le document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Master()](#Master--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Crée une copie profonde de cette instance. |
| [dispose()](#dispose--) | Effectue des tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | Spécifie si le texte du master dans la fenêtre du gabarit est aligné à gauche, à droite ou au centre. |
| [getBaseID()](#getBaseID--) | Un GUID (identifiant global unique) qui identifie le master à travers les documents. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Contient un élément Connect pour chaque connexion entre deux formes dans un dessin. |
| [getHidden()](#getHidden--) | Spécifie si le master est masqué dans l'interface utilisateur. |
| [getID()](#getID--) | L'ID unique de l'élément au sein de son élément parent. |
| [getIcon()](#getIcon--) | Spécifie une icône binaire encodée MIME (Multipurpose Internet Mail Extensions) (au format .ico) pour un élément Master ou MasterShortcut dans un document. |
| [getIconSize()](#getIconSize--) | La taille de l'icône de l'élément. |
| [getIconUpdate()](#getIconUpdate--) | Spécifie si l'icône est générée automatiquement à partir du master lui-même. |
| [getMatchByName()](#getMatchByName--) | L'attribut MatchByName détermine comment Microsoft Visio décide si un master de document est déjà présent lorsqu'une instance d'un master est déposée sur la page de dessin. |
| [getName()](#getName--) | Le nom de l'élément. |
| [getNameU()](#getNameU--) | Le nom universel de l'élément. |
| [getPageSheet()](#getPageSheet--) | Contient des éléments qui définissent la feuille de page pour un élément Page ou Master. |
| [getPatternFlags()](#getPatternFlags--) | L'attribut PatternFlags détermine si un master se comporte comme un motif personnalisé. |
| [getPrompt()](#getPrompt--) | La barre d'état et l'infobulle affichent une invite pour l'élément. |
| [getShapes()](#getShapes--) | Collection d'objets Shape. |
| [getUniqueID()](#getUniqueID--) | Un GUID qui identifie le master dans le document. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | Pour la description de cette propriété, veuillez consulter [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | Pour la description de cette propriété, veuillez consulter [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | Pour la description de cette propriété, veuillez consulter [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | Pour la description de cette propriété, veuillez consulter [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | Pour la description de cette propriété, veuillez consulter [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | Pour la description de cette propriété, veuillez consulter [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | Pour la description de cette propriété, veuillez consulter [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | Pour la description de cette propriété, veuillez consulter [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Pour la description de cette propriété, veuillez consulter [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


Constructeur.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée une copie profonde de cette instance.

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


Effectue des tâches définies par l'application associées à la libération, la remise ou la réinitialisation des ressources non gérées.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


Spécifie si le texte du master dans la fenêtre du gabarit est aligné à gauche, à droite ou au centre.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


Un GUID (identifiant global unique) qui identifie le master à travers les documents.

**Returns:**
java.util.UUID
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


Contient un élément Connect pour chaque connexion entre deux formes dans un dessin.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


Spécifie si le master est masqué dans l'interface utilisateur.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


L'ID unique de l'élément au sein de son élément parent.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


Spécifie une icône binaire encodée MIME (Multipurpose Internet Mail Extensions) (au format .ico) pour un élément Master ou MasterShortcut dans un document.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


La taille de l'icône de l'élément.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


Spécifie si l'icône est générée automatiquement à partir du master lui-même.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


L'attribut MatchByName détermine comment Microsoft Visio décide si un master de document est déjà présent lorsqu'une instance d'un master est déposée sur la page de dessin. Il permet aux modifications apportées à un master de document de s'appliquer aux nouvelles instances du master, même si les instances sont glissées depuis un fichier stencil autonome.

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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Contient des éléments qui définissent la feuille de page pour un élément Page ou Master.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


L'attribut PatternFlags détermine si un master se comporte comme un motif personnalisé.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


La barre d'état et l'infobulle affichent une invite pour l'élément.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Collection d'objets Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Un GUID qui identifie le master dans le document.

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


Pour la description de cette propriété, veuillez consulter [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


Pour la description de cette propriété, veuillez consulter [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


Pour la description de cette propriété, veuillez consulter [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


Pour la description de cette propriété, veuillez consulter [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


Pour la description de cette propriété, veuillez consulter [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


Pour la description de cette propriété, veuillez consulter [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


Pour la description de cette propriété, veuillez consulter [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Pour la description de cette propriété, veuillez consulter [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


Pour la description de cette propriété, veuillez consulter [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


Pour la description de cette propriété, veuillez consulter [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Pour la description de cette propriété, veuillez consulter [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

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

