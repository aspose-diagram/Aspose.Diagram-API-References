---
title: FontConfigs
second_title: Referencia de API de Aspose.Diagram para Java
description: Especifica la configuración de la fuente
type: docs
weight: 160
url: /es/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

Especifica la configuración de la fuente
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | el nombre de fuente predeterminado. |
| [getFontSources()](#getFontSources--) | Obtiene una copia del arreglo que contiene la lista de fuentes |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | Devuelve un arreglo que contiene nombres de fuentes sustitutas que se usarán si la fuente original no está presente. |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | Indica si se deben usar primero sustitutos de fuentes del sistema cuando una fuente no está presente y el sustituto de esa fuente no está configurado. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Para la descripción de esta propiedad, consulte [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | Establece la carpeta de fuentes |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | Establece las carpetas de fuentes |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | Establece los orígenes de fuentes. |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | Nombres de fuentes sustitutas para el nombre de fuente original dado. |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | Para la descripción de esta propiedad, consulte [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) |
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
| Parámetro | Tipo | Descripción |
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


el nombre de fuente predeterminado.

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


Obtiene una copia del arreglo que contiene la lista de fuentes

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


Devuelve un arreglo que contiene nombres de fuentes sustitutas que se usarán si la fuente original no está presente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - Una matriz que contiene nombres de sustitutos de fuentes que se usarán si la fuente original no está presente.
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


Indique si se deben usar primero los sustitutos de fuentes del sistema o no cuando una fuente no está presente y el sustituto de esa fuente no está configurado. Por ejemplo, en Ubuntu, la fuente "Arial" suele ser sustituida por "Liberation Sans". El valor predeterminado es false.

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


Para la descripción de esta propiedad, consulte [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


Establece la carpeta de fuentes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFolder | java.lang.String | La carpeta que contiene fuentes TrueType. |
| recursivo | boolean | Determina si se deben o no escanear subcarpetas. |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


Establece las carpetas de fuentes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFolders | java.lang.String[] | Las carpetas que contienen fuentes TrueType. |
| recursivo | boolean | Determina si se deben o no escanear subcarpetas. |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


Establece los orígenes de fuentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | Una matriz de fuentes que contienen fuentes TrueType. |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


Nombres de fuentes sustitutas para el nombre de fuente original dado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| originalFontName | java.lang.String | Nombre de la fuente original. |
| substituteFontNames | java.lang.String[] | Lista de nombres de sustitutos de fuentes que se usarán si la fuente original no está presente. |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


Para la descripción de esta propiedad, consulte [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

