---
title: FontConfigs
second_title: Aspose.Diagram voor Java API-referentie
description: Specificeert lettertype‑instellingen
type: docs
weight: 160
url: /nl/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

Specificeert lettertype‑instellingen
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | de standaardlettertype‑naam. |
| [getFontSources()](#getFontSources--) | Haalt een kopie op van de array die de lijst met bronnen bevat. |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | Retourneert een array met vervangende lettertypenamen die gebruikt worden als het oorspronkelijke lettertype niet aanwezig is. |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | Geeft aan of systeemlettertype‑vervangers eerst moeten worden gebruikt wanneer een lettertype niet aanwezig is en de vervanger voor dit lettertype niet is ingesteld. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | Stelt de lettertype‑map in |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | Stelt de lettertype‑mappen in |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | Stelt de lettertype‑bronnen in. |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | Vervangende lettertypenamen voor een opgegeven oorspronkelijke lettertype‑naam. |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | Voor de beschrijving van deze eigenschap, zie [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) |
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
| Parameter | Type | Beschrijving |
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


de standaardlettertype‑naam.

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


Haalt een kopie op van de array die de lijst met bronnen bevat.

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


Retourneert een array met vervangende lettertypenamen die gebruikt worden als het oorspronkelijke lettertype niet aanwezig is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - Een array met vervangende lettertype‑namen die gebruikt worden als het oorspronkelijke lettertype niet aanwezig is.
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


Geef aan of eerst systeemlettertype‑vervangers moeten worden gebruikt wanneer een lettertype niet aanwezig is en de vervanger voor dit lettertype niet is ingesteld. Bijvoorbeeld op Ubuntu wordt het lettertype "Arial" doorgaans vervangen door "Liberation Sans". Standaardwaarde is false.

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


Voor de beschrijving van deze eigenschap, zie [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


Stelt de lettertype‑map in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontFolder | java.lang.String | De map die TrueType-lettertypen bevat. |
| recursive | boolean | Bepaalt of de submappen al dan niet moeten worden gescand. |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


Stelt de lettertype‑mappen in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontFolders | java.lang.String[] | De mappen die TrueType-lettertypen bevatten. |
| recursive | boolean | Bepaalt of de submappen al dan niet moeten worden gescand. |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


Stelt de lettertype‑bronnen in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | Een array van bronnen die TrueType-lettertypen bevatten. |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


Vervangende lettertypenamen voor een opgegeven oorspronkelijke lettertype‑naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| originalFontName | java.lang.String | Naam van het oorspronkelijke lettertype. |
| substituteFontNames | java.lang.String[] | Lijst met vervangende lettertype‑namen die gebruikt worden als het oorspronkelijke lettertype niet aanwezig is. |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


Voor de beschrijving van deze eigenschap, zie [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

