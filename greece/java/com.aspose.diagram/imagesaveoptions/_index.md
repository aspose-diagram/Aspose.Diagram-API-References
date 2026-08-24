---
title: ImageSaveOptions
second_title: Αναφορά API του Aspose.Diagram για Java
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγράμματος σε εικόνες.
type: docs
weight: 200
url: /el/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγράμματος σε εικόνες.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης που μπορεί να χρησιμοποιηθεί για την αποθήκευση αποδοθέντων εικόνων στη μορφή Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat ή Aspose.Diagram.SaveFileFormat. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | Δημιουργεί ένα αντικείμενο επιλογών αποθήκευσης μιας κλάσης κατάλληλης για τη συγκεκριμένη μορφή αποθήκευσης. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | Καθορίζει το επίπεδο ποιότητας που θα χρησιμοποιηθεί κατά τη σύνθεση. |
| [getContentZoom()](#getContentZoom--) | Αυτή η παράμετρος είναι παρόμοια με την κλίμακα, αλλά δεν επηρεάζει το μέγεθος της παραγόμενης εικόνας. |
| [getDefaultFont()](#getDefaultFont--) | Όταν οι χαρακτήρες στο διάγραμμα είναι Unicode και δεν έχουν οριστεί με τη σωστή τιμή γραμματοσειράς ή η γραμματοσειρά δεν είναι εγκατεστημένη τοπικά, μπορεί να εμφανιστούν ως μπλοκ σε PDF, εικόνα ή XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Ρύθμιση για την απόδοση αρχείου μεταδεδομένων Emf. |
| [getEnlargePage()](#getEnlargePage--) | Καθορίζει εάν να μεγεθυνθεί η σελίδα. |
| [getExportGuideShapes()](#getExportGuideShapes--) | Ορίζει εάν χρειάζεται η εξαγωγή των σχημάτων οδηγού ή όχι. |
| [getExportHiddenPage()](#getExportHiddenPage--) | Ορίζει εάν χρειάζεται η εξαγωγή της κρυφής σελίδας ή όχι. |
| [getImageBrightness()](#getImageBrightness--) | η φωτεινότητα για τις παραγόμενες εικόνες. |
| [getImageColorMode()](#getImageColorMode--) | η λειτουργία χρώματος για τις παραγόμενες εικόνες. |
| [getImageContrast()](#getImageContrast--) | η αντίθεση για τις παραγόμενες εικόνες. |
| [getInterpolationMode()](#getInterpolationMode--) | Καθορίζει τον αλγόριθμο που χρησιμοποιείται όταν οι εικόνες κλιμακώνονται ή περιστρέφονται. |
| [getJpegQuality()](#getJpegQuality--) | μια τιμή που καθορίζει την ποιότητα των παραγόμενων εικόνων JPEG. |
| [getPageCount()](#getPageCount--) | ο αριθμός των σελίδων που θα αποδοθούν κατά την αποθήκευση σε αρχείο TIFF πολλαπλών σελίδων. |
| [getPageIndex()](#getPageIndex--) | ο δείκτης με βάση το 0 της πρώτης σελίδας που θα αποδοθεί. |
| [getPageSize()](#getPageSize--) | το μέγεθος της σελίδας για τις παραγόμενες εικόνες. |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | μια τιμή που καθορίζει πώς μετατοπίζονται τα pixel κατά την απόδοση. |
| [getResolution()](#getResolution--) | η ανάλυση για τις παραγόμενες εικόνες, σε κουκκίδες ανά ίντσα. |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | Καθορίζει εάν η περιοχή αποθήκευσης είναι η ίδια με το PDF. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | Καθορίζει εάν όλες οι σελίδες θα αποθηκευτούν ως εικόνα ή μόνο το προσκήνιο. |
| [getSaveFormat()](#getSaveFormat--) | Καθορίζει τη μορφή στην οποία θα αποθηκευτούν οι αποδομένες σελίδες διαγράμματος εάν χρησιμοποιηθεί αυτό το αντικείμενο επιλογών αποθήκευσης. |
| [getScale()](#getScale--) | ο συντελεστής ζουμ για τις παραγόμενες εικόνες. |
| [getShapes()](#getShapes--) | σχήματα προς απόδοση. |
| [getSmoothingMode()](#getSmoothingMode--) | Καθορίζει εάν η εξομάλυνση (antialiasing) εφαρμόζεται σε γραμμές και καμπύλες και στις άκρες γεμάτων περιοχών. |
| [getTiffCompression()](#getTiffCompression--) | ο τύπος συμπίεσης που θα εφαρμοστεί κατά την αποθήκευση των παραγόμενων εικόνων σε μορφή TIFF. |
| [getWarningCallback()](#getWarningCallback--) | callback προειδοποίησης. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | Ορίζει εάν χρειάζεται η εξαγωγή των σχολίων ή όχι. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) |
| [setContentZoom(float value)](#setContentZoom-float-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) |
| [setImageBrightness(float value)](#setImageBrightness-float-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) |
| [setImageColorMode(int value)](#setImageColorMode-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) |
| [setImageContrast(float value)](#setImageContrast-float-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) |
| [setResolution(float value)](#setResolution-float-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) |
| [setScale(float value)](#setScale-float-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) |
| [setTiffCompression(int value)](#setTiffCompression-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης που μπορεί να χρησιμοποιηθεί για την αποθήκευση αποδοθέντων εικόνων στη μορφή Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat ή Aspose.Diagram.SaveFileFormat.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| saveFormat | int | Μπορεί να είναι Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat ή Aspose.Diagram.SaveFileFormat. |

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
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


Καθορίζει το επίπεδο ποιότητας που θα χρησιμοποιηθεί κατά τη σύνθεση. Αυτή η ιδιότητα έχει αποτέλεσμα μόνο όταν αποθηκεύεται σε μορφές raster εικόνας. Η προεπιλεγμένη τιμή είναι Aspose.Diagram.Saving.CompositingQuality.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


Αυτή η παράμετρος είναι παρόμοια με την κλίμακα, αλλά δεν επηρεάζει το μέγεθος της παραγόμενης εικόνας. Η προεπιλεγμένη τιμή είναι 1.0. Η τιμή πρέπει να είναι μεγαλύτερη από 0.

**Returns:**
float
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
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


Ορίζει αν χρειάζεται η εξαγωγή της κρυφής σελίδας ή όχι. Η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


η φωτεινότητα για τις παραγόμενες εικόνες. Αυτή η ιδιότητα έχει αποτέλεσμα μόνο όταν αποθηκεύεται σε μορφές raster εικόνας. Η προεπιλεγμένη τιμή είναι 0.5. Η τιμή πρέπει να βρίσκεται στο εύρος μεταξύ 0 και 1.

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


η λειτουργία χρώματος για τις παραγόμενες εικόνες. Αυτή η ιδιότητα έχει αποτέλεσμα μόνο όταν αποθηκεύεται σε μορφές raster εικόνας. Η προεπιλεγμένη τιμή είναι Aspose.Diagram.Saving.ImageColorMode.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


η αντίθεση για τις παραγόμενες εικόνες. Αυτή η ιδιότητα έχει αποτέλεσμα μόνο όταν αποθηκεύεται σε μορφές raster εικόνας. Η προεπιλεγμένη τιμή είναι 0.5. Η τιμή πρέπει να βρίσκεται στο εύρος μεταξύ 0 και 1.

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


Καθορίζει τον αλγόριθμο που χρησιμοποιείται όταν οι εικόνες κλιμακώνονται ή περιστρέφονται. Αυτή η ιδιότητα έχει αποτέλεσμα μόνο όταν αποθηκεύεται σε μορφές raster εικόνας. Η προεπιλεγμένη τιμή είναι Aspose.Diagram.Saving.InterpolationMode.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


μια τιμή που καθορίζει την ποιότητα των παραγόμενων JPEG εικόνων. Έχει αποτέλεσμα μόνο όταν αποθηκεύεται σε JPEG. Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε ή να ορίσετε την ποιότητα των παραγόμενων εικόνων κατά την αποθήκευση σε μορφή JPEG. Η τιμή μπορεί να κυμαίνεται από 0 έως 100, όπου 0 σημαίνει τη χειρότερη ποιότητα αλλά μέγιστη συμπίεση και 100 σημαίνει την καλύτερη ποιότητα αλλά ελάχιστη συμπίεση. Η προεπιλεγμένη τιμή είναι 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


ο αριθμός των σελίδων που θα αποδοθούν όταν αποθηκεύεται σε αρχείο TIFF πολλαπλών σελίδων. Η προεπιλεγμένη τιμή είναι MaxValue, που σημαίνει ότι όλες οι σελίδες του διαγράμματος θα αποδοθούν.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


ο δείκτης 0‑βάσης της πρώτης σελίδας που θα αποδοθεί. Η προεπιλογή είναι 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


το μέγεθος σελίδας για τις δημιουργημένες εικόνες. Μπορεί να είναι [PageSize](../../com.aspose.diagram/pagesize) ή null. Η προεπιλεγμένη τιμή είναι null. Εάν το PageSize είναι null, τότε το μέγεθος σελίδας για τη δημιουργημένη εικόνα λαμβάνεται από το πηγαίο διάγραμμα.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


μια τιμή που καθορίζει πώς μετατοπίζονται τα pixel κατά την απόδοση. Αυτή η ιδιότητα έχει αποτέλεσμα μόνο όταν αποθηκεύεται σε μορφές raster εικόνας. Η προεπιλεγμένη τιμή είναι Aspose.Diagram.Saving.PixelOffsetMode.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


η ανάλυση για τις παραγόμενες εικόνες, σε σημεία ανά ίντσα. Αυτή η ιδιότητα έχει αποτέλεσμα μόνο όταν αποθηκεύεται σε μορφές raster εικόνας. Η προεπιλεγμένη τιμή είναι 96.

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


Καθορίζει αν η περιοχή αποθήκευσης είναι η ίδια με το pdf. Εάν είναι true - η αποδοθείσα περιοχή είναι η ίδια με το pdf. Εάν είναι false - η αποδοθείσα περιοχή είναι η προεπιλεγμένη. Η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean
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


Καθορίζει τη μορφή στην οποία θα αποθηκευτούν οι σελίδες του αποδοθέντος διαγράμματος εάν χρησιμοποιηθεί αυτό το αντικείμενο επιλογών αποθήκευσης. Μπορεί να είναι Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat ή Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


ο συντελεστής μεγέθυνσης για τις παραγόμενες εικόνες. Η προεπιλεγμένη τιμή είναι 1.0. Η τιμή πρέπει να είναι μεγαλύτερη από 0.

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


σχήματα προς απόδοση. Η προεπιλεγμένη καταμέτρηση είναι 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


Καθορίζει αν η εξομάλυνση (antialiasing) εφαρμόζεται σε γραμμές και καμπύλες και στις άκρες των γεμισμένων περιοχών. Αυτή η ιδιότητα έχει αποτέλεσμα μόνο όταν αποθηκεύεται σε μορφές raster εικόνας. Η προεπιλεγμένη τιμή είναι Aspose.Diagram.Saving.SmoothingMode.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


ο τύπος συμπίεσης που θα εφαρμοστεί όταν αποθηκεύονται οι παραγόμενες εικόνες σε μορφή TIFF. Έχει αποτέλεσμα μόνο όταν αποθηκεύεται σε TIFF. Η προεπιλεγμένη τιμή είναι Aspose.Diagram.Saving.TiffCompression.

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




### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)

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

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλούμε δείτε [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)

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

