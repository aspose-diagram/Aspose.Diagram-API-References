---
title: FontConfigs
second_title: Справочник API Aspose.Diagram for Java
description: Задает настройки шрифта
type: docs
weight: 160
url: /ru/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

Задает настройки шрифта
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | имя шрифта по умолчанию. |
| [getFontSources()](#getFontSources--) | Получает копию массива, содержащего список источников |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | Возвращает массив, содержащий имена заменяющих шрифтов, которые будут использоваться, если оригинальный шрифт не представлен. |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | Указывает, использовать ли системные заменяющие шрифты в первую очередь, когда шрифт не представлен и замена для этого шрифта не задана. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | Устанавливает папку шрифтов |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | Устанавливает папки шрифтов |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | Устанавливает источники шрифтов. |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | Имена заменяющих шрифтов для заданного оригинального имени шрифта. |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | Для описания этого свойства, пожалуйста, смотрите [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) |
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
| Параметр | Тип | Описание |
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


имя шрифта по умолчанию.

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


Получает копию массива, содержащего список источников

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


Возвращает массив, содержащий имена заменяющих шрифтов, которые будут использоваться, если оригинальный шрифт не представлен.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] — массив, содержащий имена замен шрифтов, которые будут использоваться, если оригинальный шрифт не представлен.
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


Укажите, следует ли сначала использовать системные заменители шрифтов, когда шрифт не представлен и замена для этого шрифта не задана. Например, в Ubuntu шрифт "Arial" обычно заменяется на "Liberation Sans". Значение по умолчанию — false.

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


Для описания этого свойства, пожалуйста, смотрите [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


Устанавливает папку шрифтов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFolder | java.lang.String | Папка, содержащая шрифты TrueType. |
| рекурсивный | boolean | Определяет, сканировать ли подпапки. |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


Устанавливает папки шрифтов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFolders | java.lang.String[] | Папки, содержащие шрифты TrueType. |
| рекурсивный | boolean | Определяет, сканировать ли подпапки. |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


Устанавливает источники шрифтов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | Массив источников, содержащих шрифты TrueType. |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


Имена заменяющих шрифтов для заданного оригинального имени шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| originalFontName | java.lang.String | Исходное имя шрифта. |
| substituteFontNames | java.lang.String[] | Список имен замен шрифтов, которые будут использоваться, если исходный шрифт не представлен. |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


Для описания этого свойства, пожалуйста, смотрите [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

