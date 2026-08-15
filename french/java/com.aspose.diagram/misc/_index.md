---
title: Misc
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient divers éléments de formes et de groupes tels que ceux qui contrôlent la mise en surbrillance de la sélection et la visibilité.
type: docs
weight: 247
url: /fr/java/com.aspose.diagram/misc/
---

**Inheritance:**
java.lang.Object
```
public class Misc
```

Contient divers éléments de formes et de groupes, tels que ceux qui contrôlent la mise en évidence de la sélection et la visibilité.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBegTrigger()](#getBegTrigger--) | Contient une formule de déclenchement générée par Microsoft Visio qui détermine s'il faut déplacer le point de départ d'une forme 1-D afin de maintenir sa connexion à une autre forme. |
| [getCalendar()](#getCalendar--) | Détermine le calendrier utilisé pour les propriétés personnalisées, les champs de texte et les formules d'éléments. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Contient le texte du commentaire au format chaîne pour une forme. |
| [getDel()](#getDel--) | Un indicateur indiquant si l'élément a été supprimé localement. |
| [getDropOnPageScale()](#getDropOnPageScale--) | Détermine le pourcentage selon lequel une forme est mise à l'échelle lorsqu'elle est déposée sur la page de dessin. |
| [getDynFeedback()](#getDynFeedback--) | Spécifie le type de retour visuel fourni aux utilisateurs lorsqu'ils font glisser un connecteur. |
| [getEndTrigger()](#getEndTrigger--) | Contient une formule de déclenchement générée par Microsoft Visio. |
| [getGlueType()](#getGlueType--) | Spécifie si la colle dynamique (forme à forme) est autorisée lors de la connexion à une forme. |
| [getHideText()](#getHideText--) | Masque le texte d'une forme. |
| [getLangID()](#getLangID--) | Indique l'ID de paramètre régional (LCID) de la langue dans laquelle la formule de cellule, le texte, la propriété personnalisée ou le commentaire a été saisi. |
| [getLocalizeMerge()](#getLocalizeMerge--) | Détermine si les formes sont localisées (si leur LangIDelement est réinitialisé) lorsqu'elles sont copiées entre documents. |
| [getNoAlignBox()](#getNoAlignBox--) | Spécifie si le rectangle de sélection est affiché lorsque la forme est sélectionnée. |
| [getNoCtlHandles()](#getNoCtlHandles--) | Spécifie si les poignées de contrôle sont affichées lorsque la forme est sélectionnée. |
| [getNoLiveDynamics()](#getNoLiveDynamics--) | Spécifie si une forme se redimensionne ou pivote dynamiquement lorsque l'utilisateur la manipule. |
| [getNoObjHandles()](#getNoObjHandles--) | Spécifie si les poignées de sélection sont affichées lorsque la forme est sélectionnée. |
| [getNonPrinting()](#getNonPrinting--) | Spécifie si une forme sélectionnée peut être imprimée. |
| [getObjType()](#getObjType--) | Spécifie si les objets sont placables ou routables dans les diagrammes lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin. |
| [getShapeKeywords()](#getShapeKeywords--) | Contient des mots-clés de recherche qui ont été attribués aux formes maîtres personnalisées. |
| [getUpdateAlignBox()](#getUpdateAlignBox--) | Spécifie s'il faut recalculer le rectangle de sélection d'une forme chaque fois qu'une poignée de contrôle est déplacée. |
| [getWalkPreference()](#getWalkPreference--) | Spécifie si une extrémité d'une forme 1D se déplace vers un point de connexion horizontal ou vertical sur la forme à laquelle elle est collée, en utilisant la colle dynamique, lorsque la forme est déplacée vers une position ambiguë. |
| [hashCode()](#hashCode--) |  |
| [isDropSource()](#isDropSource--) | Spécifie si la forme peut être ajoutée à un groupe en la déposant sur le groupe. |
| [isReplaceLockShapeData()](#isReplaceLockShapeData--) | Indique si les valeurs des cellules spécifiées dans une forme maître écrasent les valeurs (y compris les valeurs locales) d'une forme remplacée lors d'une opération de remplacement de forme. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/misc\#getDel--) |
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
### getBegTrigger() {#getBegTrigger--}
```
public DoubleValue getBegTrigger()
```


Contient une formule de déclenchement générée par Microsoft Visio qui détermine s'il faut déplacer le point de départ d'une forme 1-D afin de maintenir sa connexion à une autre forme.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getComment() {#getComment--}
```
public Str2Value getComment()
```


Contient le texte du commentaire au format chaîne pour une forme.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDel() {#getDel--}
```
public int getDel()
```


Un indicateur indiquant si l'élément a été supprimé localement. Une valeur de 1 indique que l'élément a été supprimé localement.

**Returns:**
int
### getDropOnPageScale() {#getDropOnPageScale--}
```
public DoubleValue getDropOnPageScale()
```


Détermine le pourcentage selon lequel une forme est mise à l'échelle lorsqu'elle est déposée sur la page de dessin.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDynFeedback() {#getDynFeedback--}
```
public DynFeedback getDynFeedback()
```


Spécifie le type de retour visuel fourni aux utilisateurs lorsqu'ils font glisser un connecteur.

**Returns:**
[DynFeedback](../../com.aspose.diagram/dynfeedback)
### getEndTrigger() {#getEndTrigger--}
```
public DoubleValue getEndTrigger()
```


Contient une formule de déclenchement générée par Microsoft Visio. Cette formule de déclenchement détermine s'il faut déplacer le point d'extrémité d'une forme 1-D afin de maintenir sa connexion à une autre forme.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGlueType() {#getGlueType--}
```
public GlueType getGlueType()
```


Spécifie si la colle dynamique (forme à forme) est autorisée lors de la connexion à une forme.

**Returns:**
[GlueType](../../com.aspose.diagram/gluetype)
### getHideText() {#getHideText--}
```
public BoolValue getHideText()
```


Masque le texte d'une forme. Vous pouvez afficher le texte, modifier les propriétés et appliquer des styles au texte dans le bloc de texte, bien que les modifications n'apparaissent pas tant que vous ne spécifiez pas l'élément HideText à 0.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Indique l'ID de paramètre régional (LCID) de la langue dans laquelle la formule de cellule, le texte, la propriété personnalisée ou le commentaire a été saisi.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLocalizeMerge() {#getLocalizeMerge--}
```
public BoolValue getLocalizeMerge()
```


Détermine si les formes sont localisées (si leur LangIDelement est réinitialisé) lorsqu'elles sont copiées entre documents.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoAlignBox() {#getNoAlignBox--}
```
public BoolValue getNoAlignBox()
```


Spécifie si le rectangle de sélection est affiché lorsque la forme est sélectionnée.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoCtlHandles() {#getNoCtlHandles--}
```
public BoolValue getNoCtlHandles()
```


Spécifie si les poignées de contrôle sont affichées lorsque la forme est sélectionnée.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLiveDynamics() {#getNoLiveDynamics--}
```
public BoolValue getNoLiveDynamics()
```


Spécifie si une forme se redimensionne ou pivote dynamiquement lorsque l'utilisateur la manipule.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoObjHandles() {#getNoObjHandles--}
```
public BoolValue getNoObjHandles()
```


Spécifie si les poignées de sélection sont affichées lorsque la forme est sélectionnée.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNonPrinting() {#getNonPrinting--}
```
public BoolValue getNonPrinting()
```


Spécifie si une forme sélectionnée peut être imprimée.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getObjType() {#getObjType--}
```
public ObjType getObjType()
```


Spécifie si les objets sont placables ou routables dans les diagrammes lorsque vous utilisez Microsoft Visio pour disposer les formes sur la page de dessin.

**Returns:**
[ObjType](../../com.aspose.diagram/objtype)
### getShapeKeywords() {#getShapeKeywords--}
```
public Str2Value getShapeKeywords()
```


Contient des mots-clés de recherche qui ont été attribués aux formes maîtres personnalisées.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getUpdateAlignBox() {#getUpdateAlignBox--}
```
public BoolValue getUpdateAlignBox()
```


Spécifie s'il faut recalculer le rectangle de sélection d'une forme chaque fois qu'une poignée de contrôle est déplacée.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getWalkPreference() {#getWalkPreference--}
```
public WalkPreference getWalkPreference()
```


Spécifie si une extrémité d'une forme 1D se déplace vers un point de connexion horizontal ou vertical sur la forme à laquelle elle est collée, en utilisant la colle dynamique, lorsque la forme est déplacée vers une position ambiguë.

**Returns:**
[WalkPreference](../../com.aspose.diagram/walkpreference)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropSource() {#isDropSource--}
```
public BoolValue isDropSource()
```


Spécifie si la forme peut être ajoutée à un groupe en la déposant sur le groupe.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isReplaceLockShapeData() {#isReplaceLockShapeData--}
```
public BoolValue isReplaceLockShapeData()
```


Indique si les valeurs des cellules spécifiées dans une forme maître écrasent les valeurs (y compris les valeurs locales) d'une forme remplacée lors d'une opération de remplacement de forme.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


Pour la description de cette propriété, veuillez consulter [getDel()](../../com.aspose.diagram/misc\#getDel--)

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

