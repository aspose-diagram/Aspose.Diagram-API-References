---
title: FontConfigs
second_title: Riferimento API di Aspose.Diagram per Java
description: Specifica le impostazioni del font
type: docs
weight: 160
url: /it/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

Specifica le impostazioni del font
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | il nome del carattere predefinito. |
| [getFontSources()](#getFontSources--) | Ottiene una copia dell'array che contiene l'elenco delle origini |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | Restituisce un array contenente i nomi dei caratteri sostitutivi da utilizzare se il carattere originale non è presente. |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | Indica se utilizzare prima i sostituti di caratteri di sistema o meno quando un carattere non è presente e il sostituto di questo carattere non è impostato. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Per la descrizione di questa proprietà, consultare [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | Imposta la cartella dei caratteri |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | Imposta le cartelle dei caratteri |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | Imposta le origini dei caratteri. |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | Nomi dei caratteri sostitutivi per il nome del carattere originale fornito. |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | Per la descrizione di questa proprietà, consultare [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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


il nome del carattere predefinito.

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


Ottiene una copia dell'array che contiene l'elenco delle origini

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


Restituisce un array contenente i nomi dei caratteri sostitutivi da utilizzare se il carattere originale non è presente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - Un array contenente i nomi dei sostituti di carattere da utilizzare se il carattere originale non è presente.
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


Indicare se utilizzare prima i sostituti di carattere di sistema o meno quando un carattere non è presente e il sostituto di questo carattere non è impostato. ad es. su Ubuntu, il carattere "Arial" è generalmente sostituito da "Liberation Sans". Il valore predefinito è false.

**Returns:**
boolean
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


Per la descrizione di questa proprietà, consultare [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


Imposta la cartella dei caratteri

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFolder | java.lang.String | La cartella che contiene i caratteri TrueType. |
| recursive | boolean | Determina se eseguire o meno la scansione delle sottocartelle. |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


Imposta le cartelle dei caratteri

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFolders | java.lang.String[] | Le cartelle che contengono i caratteri TrueType. |
| recursive | boolean | Determina se eseguire o meno la scansione delle sottocartelle. |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


Imposta le origini dei caratteri.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | Un array di sorgenti che contengono i caratteri TrueType. |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


Nomi dei caratteri sostitutivi per il nome del carattere originale fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| originalFontName | java.lang.String | Nome del carattere originale. |
| substituteFontNames | java.lang.String[] | Elenco dei nomi dei sostituti di carattere da utilizzare se il carattere originale non è presente. |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


Per la descrizione di questa proprietà, consultare [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

