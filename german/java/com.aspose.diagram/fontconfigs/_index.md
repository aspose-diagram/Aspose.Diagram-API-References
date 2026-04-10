---
title: FontConfigs
second_title: Aspose.Diagram for Java API-Referenz
description: Gibt Schrift-Einstellungen an
type: docs
weight: 160
url: /de/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

Gibt Schrift-Einstellungen an
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | der Standard-Schriftname. |
| [getFontSources()](#getFontSources--) | Gibt eine Kopie des Arrays zurück, das die Liste der Quellen enthält. |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | Gibt ein Array zurück, das Schriftart-Ersatznamen enthält, die verwendet werden, wenn die Originalschriftart nicht vorhanden ist. |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | Gibt an, ob System-Schriftart-Ersatz zuerst verwendet werden soll, wenn eine Schriftart nicht vorhanden ist und der Ersatz für diese Schriftart nicht festgelegt ist. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Für die Beschreibung dieser Eigenschaft siehe [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | Legt den Schriftartenordner fest. |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | Legt die Schriftartenordner fest. |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | Legt die Schriftartenquellen fest. |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | Schriftart-Ersatznamen für den angegebenen Originalschriftartnamen. |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | Für die Beschreibung dieser Eigenschaft siehe [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) |
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
| Parameter | Typ | Beschreibung |
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


der Standard-Schriftname.

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


Gibt eine Kopie des Arrays zurück, das die Liste der Quellen enthält.

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


Gibt ein Array zurück, das Schriftart-Ersatznamen enthält, die verwendet werden, wenn die Originalschriftart nicht vorhanden ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - Ein Array, das Schriftart-Ersatznamen enthält, die verwendet werden, wenn die Originalschriftart nicht vorhanden ist.
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


Geben Sie an, ob System-Schriftart-Ersatz zuerst verwendet werden soll, wenn eine Schriftart nicht vorhanden ist und der Ersatz dieser Schriftart nicht festgelegt ist. z. B. unter Ubuntu wird die Schriftart "Arial" in der Regel durch "Liberation Sans" ersetzt. Der Standardwert ist false.

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


Für die Beschreibung dieser Eigenschaft siehe [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


Legt den Schriftartenordner fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFolder | java.lang.String | Der Ordner, der TrueType-Schriftarten enthält. |
| recursive | boolean | Bestimmt, ob Unterordner durchsucht werden sollen oder nicht. |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


Legt die Schriftartenordner fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFolders | java.lang.String[] | Die Ordner, die TrueType-Schriftarten enthalten. |
| recursive | boolean | Bestimmt, ob Unterordner durchsucht werden sollen oder nicht. |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


Legt die Schriftartenquellen fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | Ein Array von Quellen, die TrueType-Schriftarten enthalten. |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


Schriftart-Ersatznamen für den angegebenen Originalschriftartnamen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| originalFontName | java.lang.String | Originaler Schriftartname. |
| substituteFontNames | java.lang.String[] | Liste von Schriftart-Ersatznamen, die verwendet werden, wenn die Originalschriftart nicht vorhanden ist. |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


Für die Beschreibung dieser Eigenschaft siehe [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

