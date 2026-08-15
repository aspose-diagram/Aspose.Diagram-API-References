---
title: FontConfigs
second_title: Référence API d'Aspose.Diagram pour Java
description: Spécifie les paramètres de police
type: docs
weight: 160
url: /fr/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

Spécifie les paramètres de police
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | le nom de police par défaut. |
| [getFontSources()](#getFontSources--) | Obtient une copie du tableau qui contient la liste des sources |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | Renvoie un tableau contenant les noms de substituts de police à utiliser si la police d'origine n'est pas présentée. |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | Indique s'il faut utiliser d'abord les substituts de police système ou non lorsqu'une police n'est pas présentée et que le substitut de cette police n'est pas défini. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | Définit le dossier des polices |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | Définit les dossiers des polices |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | Définit les sources des polices. |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | Noms de substituts de police pour le nom de police d'origine donné. |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | Pour la description de cette propriété, veuillez consulter [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontConfigs() {#FontConfigs--}
```
public FontConfigs()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


le nom de police par défaut.

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


Obtient une copie du tableau qui contient la liste des sources

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


Renvoie un tableau contenant les noms de substituts de police à utiliser si la police d'origine n'est pas présentée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - Un tableau contenant les noms de substituts de police à utiliser si la police d'origine n'est pas disponible.
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


Indique s'il faut utiliser d'abord les substituts de police du système ou non lorsqu'une police n'est pas présentée et que le substitut de cette police n'est pas défini. Par exemple, sous Ubuntu, la police "Arial" est généralement substituée par "Liberation Sans". La valeur par défaut est false.

**Returns:**
booléen
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




### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String value)
```


Pour la description de cette propriété, veuillez consulter [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


Définit le dossier des polices

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontFolder | java.lang.String | Le dossier qui contient les polices TrueType. |
| récursif | booléen | Détermine s’il faut ou non analyser les sous‑dossiers. |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


Définit les dossiers des polices

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontFolders | java.lang.String[] | Les dossiers qui contiennent les polices TrueType. |
| récursif | booléen | Détermine s’il faut ou non analyser les sous‑dossiers. |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


Définit les sources des polices.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | Un tableau de sources contenant des polices TrueType. |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


Noms de substituts de police pour le nom de police d'origine donné.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| originalFontName | java.lang.String | Nom de police d'origine. |
| substituteFontNames | java.lang.String[] | Liste des noms de substituts de police à utiliser si la police d'origine n'est pas disponible. |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


Pour la description de cette propriété, veuillez consulter [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)

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

