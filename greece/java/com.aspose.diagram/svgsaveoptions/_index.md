---
title: SVGSaveOptions
second_title: Αναφορά API του Aspose.Diagram για Java
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγράμματος σε SVG.
type: docs
weight: 347
url: /el/java/com.aspose.diagram/svgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class SVGSaveOptions extends RenderingSaveOptions
```

Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγράμματος σε SVG.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SVGSaveOptions()](#SVGSaveOptions--) | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης που μπορεί να χρησιμοποιηθεί για την αποθήκευση ενός εγγράφου στη μορφή Aspose.Diagram.SaveFileFormat. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Δημιουργεί ένα αντικείμενο επιλογών αποθήκευσης μιας κλάσης κατάλληλης για τη συγκεκριμένη μορφή αποθήκευσης. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomImagePath()](#getCustomImagePath--) | Η προσαρμοσμένη διαδρομή (URL) του χρήστη που αποθηκεύεται στο παραγόμενο αρχείο svg για την εικόνα. |
| [getDefaultFont()](#getDefaultFont--) | Όταν οι χαρακτήρες στο διάγραμμα είναι Unicode και δεν έχουν οριστεί με τη σωστή τιμή γραμματοσειράς ή η γραμματοσειρά δεν είναι εγκατεστημένη τοπικά, μπορεί να εμφανιστούν ως μπλοκ σε PDF, εικόνα ή XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Ρύθμιση για την απόδοση αρχείου μεταδεδομένων Emf. |
| [getEnlargePage()](#getEnlargePage--) | Καθορίζει εάν να μεγεθυνθεί η σελίδα. |
| [getExportElementAsRectTag()](#getExportElementAsRectTag--) | Ορίζει εάν χρειάζεται η εξαγωγή στοιχείων ορθογωνίου ως ετικέτα rect ή όχι. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Ορίζει εάν χρειάζεται η εξαγωγή των σχημάτων οδηγού ή όχι. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Ορίζει εάν χρειάζεται η εξαγωγή της κρυφής σελίδας ή όχι. |
| [getPageIndex()](#getPageIndex--) | ο δείκτης μηδενικής βάσης της σελίδας που θα αποδοθεί. |
| [getPageSize()](#getPageSize--) | το μέγεθος της σελίδας για τις παραγόμενες εικόνες. |
| [getQuality()](#getQuality--) | μια τιμή που καθορίζει την ποιότητα των παραγόμενων εικόνων και εφαρμόζεται μόνο όταν αποθηκεύονται οι σελίδες σε μορφή Jpeg. |
| [getSVGFitToViewPort()](#getSVGFitToViewPort--) | εάν αυτή η ιδιότητα είναι αληθής, το παραγόμενο svg θα προσαρμοστεί στο παράθυρο προβολής. |
| [getSaveFormat()](#getSaveFormat--) | Καθορίζει τη μορφή στην οποία θα αποθηκευτεί το έγγραφο εάν χρησιμοποιηθεί αυτό το αντικείμενο επιλογών αποθήκευσης. |
| [getShapes()](#getShapes--) | σχήματα προς απόδοση. |
| [getWarningCallback()](#getWarningCallback--) | callback προειδοποίησης. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Ορίζει εάν χρειάζεται η εξαγωγή των σχολίων ή όχι. |
| [isExportScaleInMatrix()](#isExportScaleInMatrix--) | Ορίζει εάν χρειάζεται η εξαγωγή κλίμακας σε μήτρα ή όχι. |
| [isSavingCustomLinePattern()](#isSavingCustomLinePattern--) | Ορίζει εάν αποθηκεύεται προσαρμοσμένο μοτίβο γραμμής. |
| [isSavingImageSeparately()](#isSavingImageSeparately--) | Ορίζει εάν η εικόνα αποθηκεύεται ξεχωριστά. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomImagePath(String value)](#setCustomImagePath-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportElementAsRectTag(boolean value)](#setExportElementAsRectTag-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--) |
| [setExportScaleInMatrix(boolean value)](#setExportScaleInMatrix-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setQuality(int value)](#setQuality-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--) |
| [setSVGFitToViewPort(boolean value)](#setSVGFitToViewPort-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setSavingCustomLinePattern(boolean value)](#setSavingCustomLinePattern-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--) |
| [setSavingImageSeparately(boolean value)](#setSavingImageSeparately-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SVGSaveOptions() {#SVGSaveOptions--}
```
public SVGSaveOptions()
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
### getCustomImagePath() {#getCustomImagePath--}
```
public String getCustomImagePath()
```


Η προσαρμοσμένη διαδρομή (URL) του χρήστη αποθηκεύεται στο παραγόμενο αρχείο svg για την εικόνα. Εάν δεν οριστεί από τον χρήστη, θα χρησιμοποιηθεί ο τρέχων φάκελος.

**Returns:**
java.lang.String
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
### getExportElementAsRectTag() {#getExportElementAsRectTag--}
```
public boolean getExportElementAsRectTag()
```


Ορίζει εάν χρειάζεται εξαγωγή στοιχείων ορθογωνίου ως ετικέτα rect ή όχι. Η προεπιλεγμένη τιμή είναι false.

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
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Ο δείκτης μηδενικής βάσης της σελίδας για απόδοση. Η προεπιλεγμένη τιμή είναι 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


το μέγεθος σελίδας για τις δημιουργημένες εικόνες. Μπορεί να είναι [PageSize](../../com.aspose.diagram/pagesize) ή null. Η προεπιλεγμένη τιμή είναι null. Εάν το PageSize είναι null, τότε το μέγεθος σελίδας για τη δημιουργημένη εικόνα λαμβάνεται από το πηγαίο διάγραμμα.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getQuality() {#getQuality--}
```
public int getQuality()
```


μια τιμή που καθορίζει την ποιότητα των παραγόμενων εικόνων και εφαρμόζεται μόνο όταν αποθηκεύονται σελίδες σε μορφή JPEG. Η προεπιλεγμένη τιμή είναι 100. Έχει αποτέλεσμα μόνο κατά την αποθήκευση σε JPEG. Η τιμή πρέπει να είναι μεταξύ 0 και 100. Η προεπιλεγμένη τιμή είναι 100.

**Returns:**
int
### getSVGFitToViewPort() {#getSVGFitToViewPort--}
```
public boolean getSVGFitToViewPort()
```


εάν αυτή η ιδιότητα είναι αληθής, το παραγόμενο svg θα προσαρμοστεί στο παράθυρο προβολής.

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
### isExportScaleInMatrix() {#isExportScaleInMatrix--}
```
public boolean isExportScaleInMatrix()
```


Ορίζει εάν χρειάζεται εξαγωγή κλίμακας σε μήτρα ή όχι. Η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean
### isSavingCustomLinePattern() {#isSavingCustomLinePattern--}
```
public boolean isSavingCustomLinePattern()
```


Ορίζει εάν αποθηκεύεται προσαρμοσμένο μοτίβο γραμμής.

**Returns:**
boolean
### isSavingImageSeparately() {#isSavingImageSeparately--}
```
public boolean isSavingImageSeparately()
```


Ορίζει εάν η εικόνα αποθηκεύεται ξεχωριστά.

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




### setCustomImagePath(String value) {#setCustomImagePath-java.lang.String-}
```
public void setCustomImagePath(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

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

### setExportElementAsRectTag(boolean value) {#setExportElementAsRectTag-boolean-}
```
public void setExportElementAsRectTag(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--)

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


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setExportScaleInMatrix(boolean value) {#setExportScaleInMatrix-boolean-}
```
public void setExportScaleInMatrix(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--)

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSVGFitToViewPort(boolean value) {#setSVGFitToViewPort-boolean-}
```
public void setSVGFitToViewPort(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--)

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

### setSavingCustomLinePattern(boolean value) {#setSavingCustomLinePattern-boolean-}
```
public void setSavingCustomLinePattern(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setSavingImageSeparately(boolean value) {#setSavingImageSeparately-boolean-}
```
public void setSavingImageSeparately(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

