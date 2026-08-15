---
title: DocumentProperties
second_title: Référence API d'Aspose.Diagram pour Java
description: Contient des éléments de propriétés de document tels que le titre du document, l'auteur, etc.
type: docs
weight: 125
url: /fr/java/com.aspose.diagram/documentproperties/
---

**Inheritance:**
java.lang.Object
```
public class DocumentProperties
```

Contient des éléments de propriétés du document tels que le titre du document, l'auteur, etc.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlternateNames()](#getAlternateNames--) | Spécifie les noms alternatifs d'un document. |
| [getBuildNumberCreated()](#getBuildNumberCreated--) | Contient le numéro complet de build de l'instance utilisée pour créer le document. |
| [getBuildNumberEdited()](#getBuildNumberEdited--) | Contient le numéro de build de l'instance utilisée en dernier pour modifier le document. |
| [getCategory()](#getCategory--) | Spécifie le texte descriptif du type de dessin, tel que diagramme de flux ou aménagement de bureau. |
| [getClass()](#getClass--) |  |
| [getCompany()](#getCompany--) | Contient les informations saisies par l'utilisateur identifiant l'entreprise qui crée le dessin ou l'entreprise pour laquelle le dessin est créé. |
| [getCreator()](#getCreator--) | Identifie qui a créé ou mis à jour le fichier en dernier. |
| [getCustomProps()](#getCustomProps--) | Collection de CustomProp. |
| [getDesc()](#getDesc--) | Contient une chaîne de texte descriptive pour un document. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Contient le chemin à utiliser pour les hyperliens relatifs (hyperliens dont l'emplacement du fichier lié est décrit par rapport au diagramme Microsoft Visio). |
| [getKeywords()](#getKeywords--) | Contient une chaîne de texte qui identifie les sujets ou d'autres informations importantes concernant le fichier, telles que le nom du projet, le nom du client ou le numéro de version. |
| [getLanguage()](#getLanguage--) | Spécifie la langue |
| [getManager()](#getManager--) | Contient une chaîne de texte saisie par l'utilisateur identifiant la personne responsable du projet ou du département. |
| [getPreviewPicture()](#getPreviewPicture--) | Contient un flux de métafichier servant d'aperçu du document. |
| [getSubject()](#getSubject--) | Contient une chaîne de texte définie par l'utilisateur qui décrit le contenu du document. |
| [getTemplate()](#getTemplate--) | Contient une valeur chaîne spécifiant le nom de fichier du modèle à partir duquel le document a été créé. |
| [getTimeCreated()](#getTimeCreated--) | Contient une valeur de date et d'heure indiquant quand le document a été créé. |
| [getTimeEdited()](#getTimeEdited--) | Contient une valeur de date et d'heure indiquant quand le document a été modifié pour la dernière fois. |
| [getTimePrinted()](#getTimePrinted--) | Contient une valeur de date et d'heure indiquant quand le document a été imprimé pour la dernière fois. |
| [getTimeSaved()](#getTimeSaved--) | Contient une valeur de date et d'heure indiquant quand le document a été enregistré pour la dernière fois. |
| [getTitle()](#getTitle--) | Contient une chaîne de texte définie par l'utilisateur qui sert de titre descriptif pour le document. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlternateNames(String value)](#setAlternateNames-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--) |
| [setBuildNumberCreated(String value)](#setBuildNumberCreated-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--) |
| [setBuildNumberEdited(String value)](#setBuildNumberEdited-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--) |
| [setCategory(String value)](#setCategory-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--) |
| [setCompany(String value)](#setCompany-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--) |
| [setCreator(String value)](#setCreator-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--) |
| [setDesc(String value)](#setDesc-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--) |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--) |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--) |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--) |
| [setManager(String value)](#setManager-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getManager()](../../com.aspose.diagram/documentproperties\#getManager--) |
| [setPreviewPicture(byte[] value)](#setPreviewPicture-byte---) | Pour la description de cette propriété, veuillez consulter [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--) |
| [setSubject(String value)](#setSubject-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--) |
| [setTemplate(String value)](#setTemplate-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--) |
| [setTimeCreated(DateTime value)](#setTimeCreated-com.aspose.diagram.DateTime-) | Pour la description de cette propriété, veuillez consulter [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--) |
| [setTimeEdited(DateTime value)](#setTimeEdited-com.aspose.diagram.DateTime-) | Pour la description de cette propriété, veuillez consulter [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--) |
| [setTimePrinted(DateTime value)](#setTimePrinted-com.aspose.diagram.DateTime-) | Pour la description de cette propriété, veuillez consulter [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--) |
| [setTimeSaved(DateTime value)](#setTimeSaved-com.aspose.diagram.DateTime-) | Pour la description de cette propriété, veuillez consulter [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--) |
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
### getAlternateNames() {#getAlternateNames--}
```
public String getAlternateNames()
```


Spécifie les noms alternatifs d'un document.

**Returns:**
java.lang.String
### getBuildNumberCreated() {#getBuildNumberCreated--}
```
public String getBuildNumberCreated()
```


Contient le numéro complet de build de l'instance utilisée pour créer le document.

**Returns:**
java.lang.String
### getBuildNumberEdited() {#getBuildNumberEdited--}
```
public String getBuildNumberEdited()
```


Contient le numéro de build de l'instance utilisée en dernier pour modifier le document.

**Returns:**
java.lang.String
### getCategory() {#getCategory--}
```
public String getCategory()
```


Spécifie le texte descriptif du type de dessin, tel qu'un organigramme ou une disposition de bureau. Ce texte peut également être saisi dans l'interface utilisateur de Microsoft Visio dans la zone Catégorie de la boîte de dialogue Propriétés.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompany() {#getCompany--}
```
public String getCompany()
```


Contient les informations saisies par l'utilisateur identifiant l'entreprise qui crée le dessin ou l'entreprise pour laquelle le dessin est créé. La longueur maximale est de 63 caractères.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


Identifie la personne qui a créé ou mis à jour le fichier en dernier. La longueur maximale est de 63 caractères.

**Returns:**
java.lang.String
### getCustomProps() {#getCustomProps--}
```
public CustomPropCollection getCustomProps()
```


Collection de CustomProp.

**Returns:**
[CustomPropCollection](../../com.aspose.diagram/custompropcollection)
### getDesc() {#getDesc--}
```
public String getDesc()
```


Contient une chaîne de texte descriptive pour un document. Utilisez cet élément pour stocker des informations importantes sur le document, telles que son objectif, les modifications récentes ou les modifications en attente. Le maximum est de 191 caractères.

**Returns:**
java.lang.String
### getHyperlinkBase() {#getHyperlinkBase--}
```
public String getHyperlinkBase()
```


Contient le chemin à utiliser pour les hyperliens relatifs (hyperliens dont l'emplacement du fichier lié est décrit par rapport au diagramme Microsoft Visio). Par défaut, le chemin d'un hyperlien est relatif au document actuel, sauf si un chemin différent est spécifié dans cet élément. La longueur maximale est de 256 caractères.

**Returns:**
java.lang.String
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Contient une chaîne de texte qui identifie les sujets ou d'autres informations importantes concernant le fichier, telles que le nom du projet, le nom du client ou le numéro de version. La longueur maximale de la chaîne est de 63 caractères.

**Returns:**
java.lang.String
### getLanguage() {#getLanguage--}
```
public String getLanguage()
```


Spécifie la langue

```
setLanguage("en-GB");
         setLanguage("en-US");
```

**Returns:**
java.lang.String
### getManager() {#getManager--}
```
public String getManager()
```


Contient une chaîne de texte saisie par l'utilisateur identifiant la personne responsable du projet ou du département. La longueur maximale est de 63 caractères.

**Returns:**
java.lang.String
### getPreviewPicture() {#getPreviewPicture--}
```
public byte[] getPreviewPicture()
```


Contient un flux de métafichier servant d'aperçu du document.

**Returns:**
byte[]
### getSubject() {#getSubject--}
```
public String getSubject()
```


Contient une chaîne de texte définie par l'utilisateur qui décrit le contenu du document. La longueur maximale est de 63 caractères.

**Returns:**
java.lang.String
### getTemplate() {#getTemplate--}
```
public String getTemplate()
```


Contient une valeur chaîne spécifiant le nom de fichier du modèle à partir duquel le document a été créé.

**Returns:**
java.lang.String
### getTimeCreated() {#getTimeCreated--}
```
public DateTime getTimeCreated()
```


Contient une valeur de date et d'heure indiquant quand le document a été créé.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeEdited() {#getTimeEdited--}
```
public DateTime getTimeEdited()
```


Contient une valeur de date et d'heure indiquant quand le document a été modifié pour la dernière fois.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimePrinted() {#getTimePrinted--}
```
public DateTime getTimePrinted()
```


Contient une valeur de date et d'heure indiquant quand le document a été imprimé pour la dernière fois.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeSaved() {#getTimeSaved--}
```
public DateTime getTimeSaved()
```


Contient une valeur de date et d'heure indiquant quand le document a été enregistré pour la dernière fois.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTitle() {#getTitle--}
```
public String getTitle()
```


Contient une chaîne de texte définie par l'utilisateur qui sert de titre descriptif pour le document. La longueur maximale est de 63 caractères.

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




### setAlternateNames(String value) {#setAlternateNames-java.lang.String-}
```
public void setAlternateNames(String value)
```


Pour la description de cette propriété, veuillez consulter [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setBuildNumberCreated(String value) {#setBuildNumberCreated-java.lang.String-}
```
public void setBuildNumberCreated(String value)
```


Pour la description de cette propriété, veuillez consulter [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setBuildNumberEdited(String value) {#setBuildNumberEdited-java.lang.String-}
```
public void setBuildNumberEdited(String value)
```


Pour la description de cette propriété, veuillez consulter [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setCategory(String value) {#setCategory-java.lang.String-}
```
public void setCategory(String value)
```


Pour la description de cette propriété, veuillez consulter [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setCompany(String value) {#setCompany-java.lang.String-}
```
public void setCompany(String value)
```


Pour la description de cette propriété, veuillez consulter [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


Pour la description de cette propriété, veuillez consulter [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setDesc(String value) {#setDesc-java.lang.String-}
```
public void setDesc(String value)
```


Pour la description de cette propriété, veuillez consulter [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public void setHyperlinkBase(String value)
```


Pour la description de cette propriété, veuillez consulter [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Pour la description de cette propriété, veuillez consulter [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public void setLanguage(String value)
```


Pour la description de cette propriété, veuillez consulter [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setManager(String value) {#setManager-java.lang.String-}
```
public void setManager(String value)
```


Pour la description de cette propriété, veuillez consulter [getManager()](../../com.aspose.diagram/documentproperties\#getManager--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setPreviewPicture(byte[] value) {#setPreviewPicture-byte---}
```
public void setPreviewPicture(byte[] value)
```


Pour la description de cette propriété, veuillez consulter [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Pour la description de cette propriété, veuillez consulter [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setTemplate(String value) {#setTemplate-java.lang.String-}
```
public void setTemplate(String value)
```


Pour la description de cette propriété, veuillez consulter [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setTimeCreated(DateTime value) {#setTimeCreated-com.aspose.diagram.DateTime-}
```
public void setTimeCreated(DateTime value)
```


Pour la description de cette propriété, veuillez consulter [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeEdited(DateTime value) {#setTimeEdited-com.aspose.diagram.DateTime-}
```
public void setTimeEdited(DateTime value)
```


Pour la description de cette propriété, veuillez consulter [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePrinted(DateTime value) {#setTimePrinted-com.aspose.diagram.DateTime-}
```
public void setTimePrinted(DateTime value)
```


Pour la description de cette propriété, veuillez consulter [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeSaved(DateTime value) {#setTimeSaved-com.aspose.diagram.DateTime-}
```
public void setTimeSaved(DateTime value)
```


Pour la description de cette propriété, veuillez consulter [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Pour la description de cette propriété, veuillez consulter [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--)

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

