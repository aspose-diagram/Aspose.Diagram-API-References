---
title: FontConfigs
second_title: Aspose.Diagram för Java API-referens
description: Specificerar typsnittsinställningar
type: docs
weight: 160
url: /sv/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

Specificerar typsnittsinställningar
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | det förvalda teckensnittets namn. |
| [getFontSources()](#getFontSources--) | Hämtar en kopia av arrayen som innehåller listan över källor |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | Returnerar en array som innehåller teckensnittsbytesnamn att använda om originalteckensnittet inte finns. |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | Indikerar om systemets teckensnittsbyten ska användas först eller inte när ett teckensnitt inte finns och bytet för detta teckensnitt inte är angivet. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | För beskrivningen av den här egenskapen, se [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | Ställer in teckensnittsmappen |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | Ställer in teckensnittsmapparna |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | Ställer in teckensnittskällorna. |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | Teckensnittsbytesnamn för givet originalteckensnitt. |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | För beskrivningen av den här egenskapen, se [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) |
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
| Parameter | Typ | Beskrivning |
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


det förvalda teckensnittets namn.

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


Hämtar en kopia av arrayen som innehåller listan över källor

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


Returnerar en array som innehåller teckensnittsbytesnamn att använda om originalteckensnittet inte finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - En array som innehåller namn på teckensnittssubstitut som ska användas om originalteckensnittet inte finns.
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


Ange om systemteckensnittssubstitut ska användas först eller inte när ett teckensnitt inte finns och substitutet för detta teckensnitt inte är angivet. t.ex. På Ubuntu ersätts "Arial"-teckensnittet vanligtvis av "Liberation Sans". Standardvärdet är false.

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


För beskrivningen av den här egenskapen, se [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


Ställer in teckensnittsmappen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFolder | java.lang.String | Mappen som innehåller TrueType-teckensnitt. |
| recursive | boolean | Bestämmer om undermappar ska genomsökas eller inte. |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


Ställer in teckensnittsmapparna

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFolders | java.lang.String[] | Mapparna som innehåller TrueType-teckensnitt. |
| recursive | boolean | Bestämmer om undermappar ska genomsökas eller inte. |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


Ställer in teckensnittskällorna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | En array av källor som innehåller TrueType-teckensnitt. |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


Teckensnittsbytesnamn för givet originalteckensnitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| originalFontName | java.lang.String | Originalt teckensnittsnamn. |
| substituteFontNames | java.lang.String[] | Lista över namn på teckensnittssubstitut som ska användas om originalteckensnittet inte finns. |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


För beskrivningen av den här egenskapen, se [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

