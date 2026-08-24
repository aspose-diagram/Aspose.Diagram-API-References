---
title: PdfSaveOptions
second_title: Αναφορά API του Aspose.Diagram για Java
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγράμματος σε PDF.
type: docs
weight: 281
url: /el/java/com.aspose.diagram/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PdfSaveOptions extends RenderingSaveOptions
```

Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγράμματος σε PDF.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης που μπορεί να χρησιμοποιηθεί για την αποθήκευση ενός εγγράφου στη μορφή Aspose.Diagram.SaveFileFormat. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Δημιουργεί ένα αντικείμενο επιλογών αποθήκευσης μιας κλάσης κατάλληλης για τη συγκεκριμένη μορφή αποθήκευσης. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompliance()](#getCompliance--) | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. |
| [getDefaultFont()](#getDefaultFont--) | Όταν οι χαρακτήρες στο διάγραμμα είναι Unicode και δεν έχουν οριστεί με τη σωστή τιμή γραμματοσειράς ή η γραμματοσειρά δεν είναι εγκατεστημένη τοπικά, μπορεί να εμφανιστούν ως μπλοκ σε PDF, εικόνα ή XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Ρύθμιση για την απόδοση αρχείου μεταδεδομένων Emf. |
| [getEncryptionDetails()](#getEncryptionDetails--) | λεπτομέρειες κρυπτογράφησης. |
| [getEnlargePage()](#getEnlargePage--) | Καθορίζει εάν να μεγεθυνθεί η σελίδα. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Ορίζει εάν χρειάζεται η εξαγωγή των σχημάτων οδηγού ή όχι. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Ορίζει εάν χρειάζεται η εξαγωγή της κρυφής σελίδας ή όχι. |
| [getHorizontalResolution()](#getHorizontalResolution--) | η οριζόντια ανάλυση για τις δημιουργημένες εικόνες, σε σημεία ανά ίντσα. |
| [getJpegQuality()](#getJpegQuality--) | Καθορίζει την ποιότητα της συμπίεσης JPEG για τις εικόνες (εάν χρησιμοποιείται συμπίεση JPEG). |
| [getPageCount()](#getPageCount--) | ο αριθμός των σελίδων που θα αποδοθούν σε PDF. |
| [getPageIndex()](#getPageIndex--) | ο δείκτης με βάση το 0 της πρώτης σελίδας που θα αποδοθεί. |
| [getPageSavingCallback()](#getPageSavingCallback--) | Έλεγχος/Ένδειξη προόδου της διαδικασίας αποθήκευσης σελίδας. |
| [getPageSize()](#getPageSize--) | το μέγεθος της σελίδας για τις παραγόμενες εικόνες. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Καθορίζει εάν όλες οι σελίδες θα αποθηκευτούν ως εικόνα ή μόνο το προσκήνιο. |
| [getSaveFormat()](#getSaveFormat--) | Καθορίζει τη μορφή στην οποία θα αποθηκευτούν οι αποδομένες σελίδες διαγράμματος εάν χρησιμοποιηθεί αυτό το αντικείμενο επιλογών αποθήκευσης. |
| [getShapes()](#getShapes--) | σχήματα προς απόδοση. |
| [getSplitMultiPages()](#getSplitMultiPages--) | Ορίζει εάν το διάγραμμα θα χωριστεί σε πολλές σελίδες σύμφωνα με τη ρύθμιση της σελίδας. |
| [getTextCompression()](#getTextCompression--) | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλα τα ρεύματα περιεχομένου εκτός από τις εικόνες. |
| [getVerticalResolution()](#getVerticalResolution--) | η κάθετη ανάλυση για τις δημιουργημένες εικόνες, σε σημεία ανά ίντσα. |
| [getWarningCallback()](#getWarningCallback--) | callback προειδοποίησης. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Ορίζει εάν χρειάζεται η εξαγωγή των σχολίων ή όχι. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompliance(int value)](#setCompliance-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEncryptionDetails(PdfEncryptionDetails value)](#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--) |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--) |
| [setPageSavingCallback(IPageSavingCallback value)](#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSplitMultiPages(boolean value)](#setSplitMultiPages-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--) |
| [setTextCompression(int value)](#setTextCompression-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--) |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
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
### getCompliance() {#getCompliance--}
```
public int getCompliance()
```


Επιθυμητό επίπεδο συμμόρφωσης για το δημιουργημένο έγγραφο PDF. Η προεπιλογή είναι PdfCompliance.PDF\_15.

**Returns:**
int
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
### getEncryptionDetails() {#getEncryptionDetails--}
```
public PdfEncryptionDetails getEncryptionDetails()
```


Λεπτομέρειες κρυπτογράφησης. Εάν δεν οριστεί, τότε δεν θα πραγματοποιηθεί κρυπτογράφηση.

**Returns:**
[PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails)
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
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Ορίζει αν χρειάζεται η εξαγωγή της κρυφής σελίδας ή όχι. Η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean
### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


η οριζόντια ανάλυση για τις δημιουργημένες εικόνες, σε σημεία ανά ίντσα. Εφαρμόζεται στη μέθοδο δημιουργίας εικόνας εκτός από εικόνες μορφής Emf. Η προεπιλεγμένη τιμή είναι 96.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Καθορίζει την ποιότητα της συμπίεσης JPEG για τις εικόνες (εάν χρησιμοποιείται συμπίεση JPEG). Η προεπιλογή είναι 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


ο αριθμός των σελίδων που θα αποδοθούν σε PDF. Η προεπιλογή είναι MaxValue, που σημαίνει ότι όλες οι σελίδες του διαγράμματος θα αποδοθούν.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


ο δείκτης 0‑βάσης της πρώτης σελίδας που θα αποδοθεί. Η προεπιλογή είναι 0.

**Returns:**
int
### getPageSavingCallback() {#getPageSavingCallback--}
```
public IPageSavingCallback getPageSavingCallback()
```


Έλεγχος/Ένδειξη προόδου της διαδικασίας αποθήκευσης σελίδας.

**Returns:**
[IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback)
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
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


σχήματα προς απόδοση. Η προεπιλεγμένη καταμέτρηση είναι 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSplitMultiPages() {#getSplitMultiPages--}
```
public boolean getSplitMultiPages()
```


Ορίζει εάν το διάγραμμα θα χωριστεί σε πολλές σελίδες σύμφωνα με τη ρύθμιση της σελίδας. Η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean
### getTextCompression() {#getTextCompression--}
```
public int getTextCompression()
```


Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλα τα ρεύματα περιεχομένου εκτός από εικόνες. Η προεπιλογή είναι PdfTextCompression.FLATE.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


η κάθετη ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα. Εφαρμόζεται στη μέθοδο δημιουργίας εικόνας εκτός από εικόνα μορφής Emf. Η προεπιλεγμένη τιμή είναι 96.

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




### setCompliance(int value) {#setCompliance-int-}
```
public void setCompliance(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

### setEncryptionDetails(PdfEncryptionDetails value) {#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-}
```
public void setEncryptionDetails(PdfEncryptionDetails value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails) |  |

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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPageSavingCallback(IPageSavingCallback value) {#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-}
```
public void setPageSavingCallback(IPageSavingCallback value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback) |  |

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


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--)

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

### setSplitMultiPages(boolean value) {#setSplitMultiPages-boolean-}
```
public void setSplitMultiPages(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setTextCompression(int value) {#setTextCompression-int-}
```
public void setTextCompression(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--)

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

