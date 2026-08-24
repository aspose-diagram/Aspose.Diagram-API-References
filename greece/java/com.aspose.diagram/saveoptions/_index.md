---
title: SaveOptions
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αυτή είναι μια αφηρημένη βασική κλάση για κλάσεις που επιτρέπουν στον χρήστη να καθορίσει πρόσθετες επιλογές κατά την αποθήκευση ενός διαγράμματος σε συγκεκριμένη μορφή.
type: docs
weight: 349
url: /el/java/com.aspose.diagram/saveoptions/
---

**Inheritance:**
java.lang.Object
```
public abstract class SaveOptions
```

Αυτή είναι μια αφηρημένη βασική κλάση για κλάσεις που επιτρέπουν στον χρήστη να καθορίσει πρόσθετες επιλογές κατά την αποθήκευση ενός διαγράμματος σε συγκεκριμένη μορφή. Μια παρουσία της κλάσης SaveOptions ή οποιασδήποτε παράγωγης κλάσης περνιέται στις υπερφορτώσεις stream Save ή string Save για να ορίσει προσαρμοσμένες επιλογές κατά την αποθήκευση ενός εγγράφου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Δημιουργεί ένα αντικείμενο επιλογών αποθήκευσης μιας κλάσης κατάλληλης για τη συγκεκριμένη μορφή αποθήκευσης. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Όταν οι χαρακτήρες στο διάγραμμα είναι Unicode και δεν έχουν οριστεί με τη σωστή τιμή γραμματοσειράς ή η γραμματοσειρά δεν είναι εγκατεστημένη τοπικά, μπορεί να εμφανιστούν ως μπλοκ σε PDF, εικόνα ή XPS. |
| [getSaveFormat()](#getSaveFormat--) | Καθορίζει τη μορφή στην οποία θα αποθηκευτεί το έγγραφο εάν χρησιμοποιηθεί αυτό το αντικείμενο επιλογών αποθήκευσης. |
| [getWarningCallback()](#getWarningCallback--) | callback προειδοποίησης. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


Δημιουργεί ένα αντικείμενο επιλογών αποθήκευσης μιας κλάσης κατάλληλης για τη συγκεκριμένη μορφή αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| saveFormat | int | Το Aspose.Diagram.SaveFileFormat για το οποίο να δημιουργηθεί ένα αντικείμενο επιλογών αποθήκευσης. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
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
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


Όταν οι χαρακτήρες στο διάγραμμα είναι Unicode και δεν έχουν οριστεί με τη σωστή τιμή γραμματοσειράς ή η γραμματοσειρά δεν είναι εγκατεστημένη τοπικά, μπορεί να εμφανίζονται ως μπλοκ σε PDF, εικόνα ή XPS. Ορίστε το DefaultFont, όπως MingLiu ή MS Gothic, για να εμφανιστούν αυτοί οι χαρακτήρες.

**Returns:**
java.lang.String
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Καθορίζει τη μορφή στην οποία θα αποθηκευτεί το έγγραφο εάν χρησιμοποιηθεί αυτό το αντικείμενο επιλογών αποθήκευσης.

**Returns:**
int
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


callback προειδοποίησης.

**Returns:**
[IWarningCallback](../../com.aspose.diagram/iwarningcallback)
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




### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.diagram/iwarningcallback) |  |

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

