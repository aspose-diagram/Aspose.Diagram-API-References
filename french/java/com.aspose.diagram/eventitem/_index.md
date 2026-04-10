---
title: EventItem
second_title: Référence API d'Aspose.Diagram pour Java
description: Encapsule un code d'événement.
type: docs
weight: 145
url: /fr/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

Encapsule un code d'événement. Un élément EventItem peut déclencher deux types d'actions : il peut exécuter un module complémentaire, ou il peut envoyer une notification de l'événement au programme appelant.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EventItem()](#EventItem--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Spécifie le code d'action de l'élément parent EventItem. Pour qu'un élément EventItem soit enregistré dans un fichier DatadiagramML, il doit être persistant. |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | Représente un indicateur indiquant si l'événement est activé ou désactivé. |
| [getEventCode()](#getEventCode--) | Un code indiquant l'événement qui déclenche le module complémentaire. |
| [getID()](#getID--) | L'ID de l'événement. |
| [getTarget()](#getTarget--) | Spécifie la cible d'un événement. |
| [getTargetArgs()](#getTargetArgs--) | Spécifie une chaîne contenant les arguments à envoyer à la cible d'un événement. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | Pour la description de cette propriété, veuillez consulter [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | Pour la description de cette propriété, veuillez consulter [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | Pour la description de cette propriété, veuillez consulter [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
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
### getAction() {#getAction--}
```
public int getAction()
```


Spécifie le code d'action de l'élément parent EventItem. Pour qu'un élément EventItem soit enregistré dans un fichier DatadiagramML, il doit être persistant. Actuellement, le seul code d'action valide qu'un événement persistant peut avoir est 1 (ONEVENT\_ACT\_RUNADDON).

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnabled() {#getEnabled--}
```
public int getEnabled()
```


Représente un indicateur indiquant si l'événement est activé ou désactivé.

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


Un code indiquant l'événement qui déclenche le module complémentaire. Pour plus d'informations sur les codes d'événement, consultez les Codes d'événement dans la Référence d'automatisation Microsoft Visio 2007.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


L'ID de l'événement.

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


Spécifie la cible d'un événement.

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


Spécifie une chaîne contenant les arguments à envoyer à la cible d'un événement.

**Returns:**
java.lang.String
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




### setAction(int value) {#setAction-int-}
```
public void setAction(int value)
```


Pour la description de cette propriété, veuillez consulter [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


Pour la description de cette propriété, veuillez consulter [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


Pour la description de cette propriété, veuillez consulter [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Pour la description de cette propriété, veuillez consulter [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


Pour la description de cette propriété, veuillez consulter [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


Pour la description de cette propriété, veuillez consulter [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

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

