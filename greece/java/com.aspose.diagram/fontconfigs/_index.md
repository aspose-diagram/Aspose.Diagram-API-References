---
title: FontConfigs
second_title: Αναφορά API του Aspose.Diagram για Java
description: Καθορίζει τις ρυθμίσεις γραμματοσειράς
type: docs
weight: 160
url: /el/java/com.aspose.diagram/fontconfigs/
---

**Inheritance:**
java.lang.Object
```
public class FontConfigs
```

Καθορίζει τις ρυθμίσεις γραμματοσειράς
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontConfigs()](#FontConfigs--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | το προεπιλεγμένο όνομα γραμματοσειράς. |
| [getFontSources()](#getFontSources--) | Λαμβάνει ένα αντίγραφο του πίνακα που περιέχει τη λίστα των πηγών |
| [getFontSubstitutes(String originalFontName)](#getFontSubstitutes-java.lang.String-) | Επιστρέφει πίνακα που περιέχει ονόματα υποκατάστασης γραμματοσειράς που θα χρησιμοποιηθούν εάν η αρχική γραμματοσειρά δεν είναι διαθέσιμη. |
| [getPreferSystemFontSubstitutes()](#getPreferSystemFontSubstitutes--) | Δείξτε εάν θα χρησιμοποιηθούν πρώτα τα υποκατάστατα γραμματοσειρών του συστήματος ή όχι όταν μια γραμματοσειρά δεν είναι διαθέσιμη και το υποκατάστατο αυτής της γραμματοσειράς δεν έχει οριστεί. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--) |
| [setFontFolder(String fontFolder, boolean recursive)](#setFontFolder-java.lang.String-boolean-) | Ορίζει το φάκελο γραμματοσειρών |
| [setFontFolders(String[] fontFolders, boolean recursive)](#setFontFolders-java.lang.String---boolean-) | Ορίζει τους φακέλους γραμματοσειρών |
| [setFontSources(FontSourceBase[] sources)](#setFontSources-com.aspose.diagram.FontSourceBase---) | Ορίζει τις πηγές γραμματοσειρών. |
| [setFontSubstitutes(String originalFontName, String[] substituteFontNames)](#setFontSubstitutes-java.lang.String-java.lang.String---) | Ονόματα υποκατάστασης γραμματοσειράς για το δοσμένο αρχικό όνομα γραμματοσειράς. |
| [setPreferSystemFontSubstitutes(boolean value)](#setPreferSystemFontSubstitutes-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--) |
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
| Παράμετρος | Τύπος | Περιγραφή |
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


το προεπιλεγμένο όνομα γραμματοσειράς.

**Returns:**
java.lang.String
### getFontSources() {#getFontSources--}
```
public static FontSourceBase[] getFontSources()
```


Λαμβάνει ένα αντίγραφο του πίνακα που περιέχει τη λίστα των πηγών

**Returns:**
com.aspose.diagram.FontSourceBase[] -
### getFontSubstitutes(String originalFontName) {#getFontSubstitutes-java.lang.String-}
```
public static String[] getFontSubstitutes(String originalFontName)
```


Επιστρέφει πίνακα που περιέχει ονόματα υποκατάστασης γραμματοσειράς που θα χρησιμοποιηθούν εάν η αρχική γραμματοσειρά δεν είναι διαθέσιμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| originalFontName | java.lang.String | originalFontName |

**Returns:**
java.lang.String[] - Ένας πίνακας που περιέχει ονόματα υποκατάστασης γραμματοσειρών που θα χρησιμοποιηθούν εάν η αρχική γραμματοσειρά δεν είναι διαθέσιμη.
### getPreferSystemFontSubstitutes() {#getPreferSystemFontSubstitutes--}
```
public static boolean getPreferSystemFontSubstitutes()
```


Καθορίστε εάν θα χρησιμοποιούνται πρώτα τα υποκατάστατα γραμματοσειρών του συστήματος ή όχι όταν μια γραμματοσειρά δεν είναι διαθέσιμη και το υποκατάστατο αυτής της γραμματοσειράς δεν έχει οριστεί. π.χ. Στο Ubuntu, η γραμματοσειρά "Arial" υποκαθίσταται γενικά από τη "Liberation Sans". Η προεπιλεγμένη τιμή είναι false.

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


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDefaultFontName()](../../com.aspose.diagram/fontconfigs\#getDefaultFontName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setFontFolder(String fontFolder, boolean recursive) {#setFontFolder-java.lang.String-boolean-}
```
public static void setFontFolder(String fontFolder, boolean recursive)
```


Ορίζει το φάκελο γραμματοσειρών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontFolder | java.lang.String | Ο φάκελος που περιέχει γραμματοσειρές TrueType. |
| recursive | boolean | Καθορίζει αν θα σαρώσει ή όχι τους υποφακέλους. |

### setFontFolders(String[] fontFolders, boolean recursive) {#setFontFolders-java.lang.String---boolean-}
```
public static void setFontFolders(String[] fontFolders, boolean recursive)
```


Ορίζει τους φακέλους γραμματοσειρών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontFolders | java.lang.String[] | Οι φάκελοι που περιέχουν γραμματοσειρές TrueType. |
| recursive | boolean | Καθορίζει αν θα σαρώσει ή όχι τους υποφακέλους. |

### setFontSources(FontSourceBase[] sources) {#setFontSources-com.aspose.diagram.FontSourceBase---}
```
public static void setFontSources(FontSourceBase[] sources)
```


Ορίζει τις πηγές γραμματοσειρών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sources | [FontSourceBase\[\]](../../com.aspose.diagram/fontsourcebase) | Ένας πίνακας πηγών που περιέχουν γραμματοσειρές TrueType. |

### setFontSubstitutes(String originalFontName, String[] substituteFontNames) {#setFontSubstitutes-java.lang.String-java.lang.String---}
```
public static void setFontSubstitutes(String originalFontName, String[] substituteFontNames)
```


Ονόματα υποκατάστασης γραμματοσειράς για το δοσμένο αρχικό όνομα γραμματοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| originalFontName | java.lang.String | Αρχικό όνομα γραμματοσειράς. |
| substituteFontNames | java.lang.String[] | Λίστα ονομάτων υποκατάστασης γραμματοσειρών που θα χρησιμοποιηθούν εάν η αρχική γραμματοσειρά δεν είναι διαθέσιμη. |

### setPreferSystemFontSubstitutes(boolean value) {#setPreferSystemFontSubstitutes-boolean-}
```
public static void setPreferSystemFontSubstitutes(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPreferSystemFontSubstitutes()](../../com.aspose.diagram/fontconfigs\#getPreferSystemFontSubstitutes--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

