---
title: FileFormatUtil
second_title: Αναφορά API του Aspose.Diagram για Java
description: Παρέχει βοηθητικές μεθόδους για τη μετατροπή των enum μορφής αρχείου σε συμβολοσειρές ή επεκτάσεις αρχείων και αντίστροφα.
type: docs
weight: 152
url: /el/java/com.aspose.diagram/fileformatutil/
---

**Inheritance:**
java.lang.Object
```
public class FileFormatUtil
```

Παρέχει βοηθητικές μεθόδους για τη μετατροπή των enum μορφής αρχείου σε συμβολοσειρές ή επεκτάσεις αρχείων και αντίστροφα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FileFormatUtil()](#FileFormatUtil--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [detectFileFormat(InputStream stream)](#detectFileFormat-java.io.InputStream-) | Ανιχνεύει και επιστρέφει τις πληροφορίες σχετικά με τη μορφή ενός Visio που αποθηκεύεται σε ροή. |
| [detectFileFormat(String filePath)](#detectFileFormat-java.lang.String-) | Ανιχνεύει και επιστρέφει τις πληροφορίες σχετικά με τη μορφή ενός Visio που αποθηκεύεται σε αρχείο. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileFormatUtil() {#FileFormatUtil--}
```
public FileFormatUtil()
```


### detectFileFormat(InputStream stream) {#detectFileFormat-java.io.InputStream-}
```
public static FileFormatInfo detectFileFormat(InputStream stream)
```


Ανιχνεύει και επιστρέφει τις πληροφορίες σχετικά με τη μορφή ενός Visio που αποθηκεύεται σε ροή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
### detectFileFormat(String filePath) {#detectFileFormat-java.lang.String-}
```
public static FileFormatInfo detectFileFormat(String filePath)
```


Ανιχνεύει και επιστρέφει τις πληροφορίες σχετικά με τη μορφή ενός Visio που αποθηκεύεται σε αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου. |

**Returns:**
[FileFormatInfo](../../com.aspose.diagram/fileformatinfo) - A [FileFormatInfo](../../com.aspose.diagram/fileformatinfo) object that contains the detected information.
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

