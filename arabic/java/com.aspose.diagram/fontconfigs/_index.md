---
title: FontConfigs
second_title: Aspose.Diagram لـ Java API Reference
description: يحدد إعدادات الخط.
type: docs
weight: 160
url: /ar/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

يحدد إعدادات الخط.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | اسم الخط الافتراضي. |
| [getFontSources()](#getFontSources--) | يحصل على نسخة من المصفوفة التي تحتوي على قائمة المصادر |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | يرجع مصفوفة تحتوي على أسماء الخطوط البديلة التي تُستخدم إذا لم يتوفر الخط الأصلي. |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | يحدد ما إذا كان يجب استخدام بدائل الخطوط النظامية أولاً أم لا عندما لا يتوفر الخط ولا يتم تعيين بديل لهذا الخط. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | يضبط مجلد الخطوط |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | يضبط مجلدات الخطوط |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | يضبط مصادر الخطوط. |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | أسماء الخطوط البديلة للخط الأصلي المحدد. |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | لوصف هذه الخاصية، يرجى الاطلاع على [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
منطقي
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


اسم الخط الافتراضي.

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


يحصل على نسخة من المصفوفة التي تحتوي على قائمة المصادر

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


يرجع مصفوفة تحتوي على أسماء الخطوط البديلة التي تُستخدم إذا لم يتوفر الخط الأصلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - مصفوفة تحتوي على أسماء بدائل الخط لاستخدامها إذا لم يتم تقديم الخط الأصلي.
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


حدد ما إذا كان يجب استخدام بدائل الخط النظام أولاً أم لا عندما لا يتم تقديم خط وما زال بديل هذا الخط غير محدد. على سبيل المثال، في أوبونتو، يُستبدل خط "Arial" عادةً بـ "Liberation Sans". القيمة الافتراضية هي false.

**Returns:**
منطقي
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


لوصف هذه الخاصية، يرجى الاطلاع على [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


يضبط مجلد الخطوط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontFolder | java.lang.String | المجلد الذي يحتوي على خطوط TrueType. |
| recursive | منطقي | يحدد ما إذا كان يجب فحص المجلدات الفرعية أم لا. |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


يضبط مجلدات الخطوط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontFolders | java.lang.String[] | المجلدات التي تحتوي على خطوط TrueType. |
| recursive | منطقي | يحدد ما إذا كان يجب فحص المجلدات الفرعية أم لا. |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


يضبط مصادر الخطوط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | مصفوفة من المصادر التي تحتوي على خطوط TrueType. |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


أسماء الخطوط البديلة للخط الأصلي المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| originalFontName | java.lang.String | اسم الخط الأصلي. |
| substituteFontNames | java.lang.String[] | قائمة بأسماء بدائل الخط لاستخدامها إذا لم يتم تقديم الخط الأصلي. |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

