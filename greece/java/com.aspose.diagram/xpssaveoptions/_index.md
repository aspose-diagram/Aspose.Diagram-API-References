---
title: XPSSaveOptions
second_title: Αναφορά API του Aspose.Diagram για Java
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγράμματος σε XPS.
type: docs
weight: 453
url: /el/java/com.aspose.diagram/xpssaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XPSSaveOptions extends SaveOptions
```

Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγράμματος σε XPS.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [XPSSaveOptions()](#XPSSaveOptions--) | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης που μπορεί να χρησιμοποιηθεί για την αποθήκευση ενός εγγράφου στη μορφή Aspose.Diagram.SaveFileFormat. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Δημιουργεί ένα αντικείμενο επιλογών αποθήκευσης μιας κλάσης κατάλληλης για τη συγκεκριμένη μορφή αποθήκευσης. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Όταν οι χαρακτήρες στο διάγραμμα είναι Unicode και δεν έχουν οριστεί με τη σωστή τιμή γραμματοσειράς ή η γραμματοσειρά δεν είναι εγκατεστημένη τοπικά, μπορεί να εμφανιστούν ως μπλοκ σε PDF, εικόνα ή XPS. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Ορίζει εάν χρειάζεται η εξαγωγή της κρυφής σελίδας ή όχι. |
| [getPageCount()](#getPageCount--) | ο αριθμός των σελίδων που θα αποδοθούν στο XPS. |
| [getPageIndex()](#getPageIndex--) | ο δείκτης με βάση το 0 της πρώτης σελίδας που θα αποδοθεί. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Καθορίζει εάν όλες οι σελίδες θα αποθηκευτούν ως εικόνα ή μόνο το προσκήνιο. |
| [getSaveFormat()](#getSaveFormat--) | Καθορίζει τη μορφή στην οποία θα αποθηκευτούν οι αποδομένες σελίδες διαγράμματος εάν χρησιμοποιηθεί αυτό το αντικείμενο επιλογών αποθήκευσης. |
| [getWarningCallback()](#getWarningCallback--) | callback προειδοποίησης. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XPSSaveOptions() {#XPSSaveOptions--}
```
public XPSSaveOptions()
```


Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης που μπορεί να χρησιμοποιηθεί για την αποθήκευση ενός εγγράφου στη μορφή Aspose.Diagram.SaveFileFormat.

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
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Ορίζει αν χρειάζεται η εξαγωγή της κρυφής σελίδας ή όχι. Η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


ο αριθμός των σελίδων που θα αποδοθούν στο XPS. Η προεπιλογή είναι MaxValue, που σημαίνει ότι όλες οι σελίδες του διαγράμματος θα αποδοθούν.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


ο δείκτης 0‑βάσης της πρώτης σελίδας που θα αποδοθεί. Η προεπιλογή είναι 0.

**Returns:**
int
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Καθορίζει αν όλες οι σελίδες θα αποθηκευτούν σε εικόνα ή μόνο το προσκήνιο. Εάν είναι true - αποδίδονται μόνο οι σελίδες του προσκηνίου (με φόντο αν υπάρχει). Εάν είναι false - αποδίδονται οι σελίδες του προσκηνίου (με φόντο αν υπάρχει) και μετά κενές σελίδες φόντου. Μπορεί να επιστρέψει true μόνο όταν το PageCount > 1. Η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Καθορίζει τη μορφή στην οποία θα αποθηκευτούν οι αποδομένες σελίδες διαγράμματος εάν χρησιμοποιηθεί αυτό το αντικείμενο επιλογών αποθήκευσης. Μπορεί να είναι μόνο Aspose.Diagram.SaveFileFormat.

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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExportHiddenPage()](../../com.aspose.diagram/xpssaveoptions\#getExportHiddenPage--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageCount()](../../com.aspose.diagram/xpssaveoptions\#getPageCount--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageIndex()](../../com.aspose.diagram/xpssaveoptions\#getPageIndex--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xpssaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveFormat()](../../com.aspose.diagram/xpssaveoptions\#getSaveFormat--)

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

