---
title: Encoding
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αναπαριστά μια κωδικοποίηση χαρακτήρων.
type: docs
weight: 143
url: /el/java/com.aspose.diagram/encoding/
---

**Inheritance:**
java.lang.Object
```
public class Encoding
```

Αναπαριστά μια κωδικοποίηση χαρακτήρων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Encoding()](#Encoding--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Encoding other)](#equals-com.aspose.diagram.Encoding-) | Καθορίζει εάν το συγκεκριμένο αντικείμενο Encoding είναι ίσο με την τρέχουσα παρουσία. |
| [equals(Object o)](#equals-java.lang.Object-) | Καθορίζει εάν το συγκεκριμένο αντικείμενο Object είναι ίσο με την τρέχουσα παρουσία. |
| [getASCII()](#getASCII--) | Λαμβάνει μια κωδικοποίηση για το σύνολο χαρακτήρων ASCII (7-bit). |
| [getBigEndianUnicode()](#getBigEndianUnicode--) | Λαμβάνει μια κωδικοποίηση για τη μορφή UTF-16 χρησιμοποιώντας τη σειρά byte big endian. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Λαμβάνει μια κωδικοποίηση για την τρέχουσα σελίδα κώδικα ANSI του λειτουργικού συστήματος. |
| [getEncoding(int codePage)](#getEncoding-int-) | Επιστρέφει την κωδικοποίηση που σχετίζεται με το συγκεκριμένο αναγνωριστικό σελίδας κώδικα. |
| [getEncoding(String charsetName)](#getEncoding-java.lang.String-) | Επιστρέφει μια κωδικοποίηση που σχετίζεται με το συγκεκριμένο όνομα charset. |
| [getEncoding(Charset charset)](#getEncoding-java.nio.charset.Charset-) | Επιστρέφει μια κωδικοποίηση που σχετίζεται με το συγκεκριμένο αντικείμενο charset. |
| [getUTF7()](#getUTF7--) | Λαμβάνει μια κωδικοποίηση για τη μορφή UTF-7. |
| [getUTF8()](#getUTF8--) | Λαμβάνει μια κωδικοποίηση για τη μορφή UTF-8. |
| [getUTF8NoBOM()](#getUTF8NoBOM--) | Λαμβάνει μια κωδικοποίηση για τη μορφή UTF-8 χωρίς το αναγνωριστικό UTF-8. |
| [getUnicode()](#getUnicode--) | Λαμβάνει μια κωδικοποίηση για τη μορφή UTF-16 χρησιμοποιώντας τη σειρά byte little endian. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Encoding() {#Encoding--}
```
public Encoding()
```


### equals(Encoding other) {#equals-com.aspose.diagram.Encoding-}
```
public boolean equals(Encoding other)
```


Καθορίζει εάν το συγκεκριμένο αντικείμενο Encoding είναι ίσο με την τρέχουσα παρουσία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [Encoding](../../com.aspose.diagram/encoding) | Το αντικείμενο Encoding για σύγκριση με την τρέχουσα παρουσία. |

**Returns:**
boolean - true εάν η τιμή είναι ίση με την τρέχουσα παρουσία· διαφορετικά, false.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Καθορίζει εάν το συγκεκριμένο αντικείμενο Object είναι ίσο με την τρέχουσα παρουσία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| o | java.lang.Object | Το Αντικείμενο για σύγκριση με την τρέχουσα παρουσία. |

**Returns:**
boolean - true εάν η τιμή είναι μια παρουσία του Encoding και είναι ίση με την τρέχουσα παρουσία· διαφορετικά, false.
### getASCII() {#getASCII--}
```
public static Encoding getASCII()
```


Λαμβάνει μια κωδικοποίηση για το σύνολο χαρακτήρων ASCII (7-bit).

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the ASCII (7-bit) character set.
### getBigEndianUnicode() {#getBigEndianUnicode--}
```
public static Encoding getBigEndianUnicode()
```


Λαμβάνει μια κωδικοποίηση για τη μορφή UTF-16 χρησιμοποιώντας τη σειρά byte big endian.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the big endian byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public static Encoding getDefault()
```


Λαμβάνει μια κωδικοποίηση για την τρέχουσα σελίδα κώδικα ANSI του λειτουργικού συστήματος.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - An encoding for the operating system's current ANSI code page.
### getEncoding(int codePage) {#getEncoding-int-}
```
public static Encoding getEncoding(int codePage)
```


Επιστρέφει την κωδικοποίηση που σχετίζεται με το συγκεκριμένο αναγνωριστικό σελίδας κώδικα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| codePage | int | Το αναγνωριστικό σελίδας κώδικα της προτιμώμενης κωδικοποίησης. -ή- 0, για χρήση της προεπιλεγμένης κωδικοποίησης. |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified code page.
### getEncoding(String charsetName) {#getEncoding-java.lang.String-}
```
public static Encoding getEncoding(String charsetName)
```


Επιστρέφει μια κωδικοποίηση που σχετίζεται με το συγκεκριμένο όνομα charset.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| charsetName | java.lang.String | καθορισμένο όνομα συνόλου χαρακτήρων |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset name.
### getEncoding(Charset charset) {#getEncoding-java.nio.charset.Charset-}
```
public static Encoding getEncoding(Charset charset)
```


Επιστρέφει μια κωδικοποίηση που σχετίζεται με το συγκεκριμένο αντικείμενο charset.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| charset | java.nio.charset.Charset | καθορισμένο αντικείμενο συνόλου χαρακτήρων |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset object.
### getUTF7() {#getUTF7--}
```
public static Encoding getUTF7()
```


Λαμβάνει μια κωδικοποίηση για τη μορφή UTF-7.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-7 format.
### getUTF8() {#getUTF8--}
```
public static Encoding getUTF8()
```


Λαμβάνει μια κωδικοποίηση για τη μορφή UTF-8.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format.
### getUTF8NoBOM() {#getUTF8NoBOM--}
```
public static Encoding getUTF8NoBOM()
```


Λαμβάνει μια κωδικοποίηση για τη μορφή UTF-8 χωρίς το αναγνωριστικό UTF-8.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format without UTF-8 identifier.
### getUnicode() {#getUnicode--}
```
public static Encoding getUnicode()
```


Λαμβάνει μια κωδικοποίηση για τη μορφή UTF-16 χρησιμοποιώντας τη σειρά byte little endian.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the little endian byte
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

