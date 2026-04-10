---
title: PrintSaveOptions
second_title: Αναφορά API του Aspose.Diagram για Java
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την εκτύπωση διαγράμματος.
type: docs
weight: 308
url: /el/java/com.aspose.diagram/printsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PrintSaveOptions extends RenderingSaveOptions
```

Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την εκτύπωση διαγράμματος.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PrintSaveOptions()](#PrintSaveOptions--) | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Δημιουργεί ένα αντικείμενο επιλογών αποθήκευσης μιας κλάσης κατάλληλης για τη συγκεκριμένη μορφή αποθήκευσης. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Όταν οι χαρακτήρες στο διάγραμμα είναι Unicode και δεν έχουν οριστεί με τη σωστή τιμή γραμματοσειράς ή η γραμματοσειρά δεν είναι εγκατεστημένη τοπικά, μπορεί να εμφανιστούν ως μπλοκ σε PDF, εικόνα ή XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Ρύθμιση για την απόδοση αρχείου μεταδεδομένων Emf. |
| [getEnlargePage()](#getEnlargePage--) | Καθορίζει εάν να μεγεθυνθεί η σελίδα. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Ορίζει εάν χρειάζεται η εξαγωγή των σχημάτων οδηγού ή όχι. |
| [getPageCount()](#getPageCount--) | ο αριθμός των σελίδων που θα αποδοθούν κατά την αποθήκευση σε αρχείο πολλαπλών σελίδων. |
| [getPageSize()](#getPageSize--) | το μέγεθος της σελίδας για τις παραγόμενες εικόνες. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Καθορίζει εάν θα εκτυπωθούν όλες οι σελίδες ή μόνο το προσκήνιο. |
| [getSaveFormat()](#getSaveFormat--) | Καθορίζει τη μορφή στην οποία θα αποθηκευτεί το έγγραφο εάν χρησιμοποιηθεί αυτό το αντικείμενο επιλογών αποθήκευσης. |
| [getShapes()](#getShapes--) | σχήματα προς απόδοση. |
| [getWarningCallback()](#getWarningCallback--) | callback προειδοποίησης. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Ορίζει εάν χρειάζεται η εξαγωγή των σχολίων ή όχι. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setPageCount(int value)](#setPageCount-int-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintSaveOptions() {#PrintSaveOptions--}
```
public PrintSaveOptions()
```


Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης

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
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


Ρύθμιση για την απόδοση αρχείου metafile EMF. Τα αρχεία metafile EMF που αναγνωρίζονται ως "EMF+ Dual" μπορούν να περιέχουν τόσο εγγραφές EMF+ όσο και εγγραφές EMF. Κάθε τύπος εγγραφής μπορεί να χρησιμοποιηθεί για την απόδοση της εικόνας, μόνο εγγραφές EMF+, ή μόνο εγγραφές EMF. Όταν το EmfPlusPrefer είναι ορισμένο, τότε οι εγγραφές EMF+ θα αναλυθούν, διαφορετικά θα αναλυθούν μόνο οι εγγραφές EMF. Η προεπιλεγμένη τιμή είναι EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


Καθορίζει αν θα γίνει μεγέθυνση της σελίδας. Εάν είναι true - η σελίδα μεγαλώνει. Εάν είναι false - η σελίδα δεν μεγαλώνει. Η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


Ορίζει αν χρειάζεται η εξαγωγή των σχημάτων οδηγού ή όχι. Η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


ο αριθμός των σελίδων που θα αποδοθούν κατά την αποθήκευση σε αρχείο πολλαπλών σελίδων. Η προεπιλογή είναι MaxValue, που σημαίνει ότι όλες οι σελίδες του διαγράμματος θα εκτυπωθούν.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


το μέγεθος σελίδας για τις δημιουργημένες εικόνες. Μπορεί να είναι [PageSize](../../com.aspose.diagram/pagesize) ή null. Η προεπιλεγμένη τιμή είναι null. Εάν το PageSize είναι null, τότε το μέγεθος σελίδας για τη δημιουργημένη εικόνα λαμβάνεται από το πηγαίο διάγραμμα.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


Καθορίζει εάν θα εκτυπωθούν όλες οι σελίδες ή μόνο το προσκήνιο. Εάν είναι true - εκτυπώνονται μόνο οι σελίδες προσκηνίου (με φόντο αν υπάρχει). Εάν είναι false - εκτυπώνονται οι σελίδες προσκηνίου (με φόντο αν υπάρχει) μετά από κενές σελίδες φόντου. Μπορεί να επιστρέψει true μόνο όταν το PageCount > 1. Η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Καθορίζει τη μορφή στην οποία θα αποθηκευτεί το έγγραφο εάν χρησιμοποιηθεί αυτό το αντικείμενο επιλογών αποθήκευσης.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


σχήματα προς απόδοση. Η προεπιλεγμένη καταμέτρηση είναι 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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
### isExportComments() {#isExportComments--}
```
public boolean isExportComments()
```


Ορίζει αν χρειάζεται η εξαγωγή των σχολίων ή όχι. Η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean
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

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getPageCount()](../../com.aspose.diagram/printsaveoptions\#getPageCount--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getSaveForegroundPagesOnly()](../../com.aspose.diagram/printsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

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

