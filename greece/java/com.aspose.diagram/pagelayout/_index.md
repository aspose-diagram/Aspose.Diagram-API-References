---
title: PageLayout
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει κελιά που ελέγχουν τις ρυθμίσεις διάταξης σελίδας για σχήματα και συνδέσμους, όπως η απόσταση μεταξύ όλων των σχημάτων στη σελίδα, η απόσταση μεταξύ όλων των συνδέσμων στη σελίδα και το στυλ δρομολόγησης για όλους τους συνδέσμους στη σελίδα.
type: docs
weight: 263
url: /el/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

Περιέχει κελιά που ελέγχουν τις ρυθμίσεις διάταξης σελίδας για σχήματα και συνδέσμους, όπως η απόσταση μεταξύ όλων των σχημάτων στη σελίδα, η απόσταση μεταξύ όλων των συνδέσμων στη σελίδα και το στυλ δρομολόγησης για όλους τους συνδέσμους στη σελίδα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | Καθορίζει την ποσότητα κάθετης απόστασης μεταξύ σχημάτων στη σελίδα σχεδίασης όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη των σχημάτων στη σελίδα σχεδίασης. |
| [getAvenueSizeY()](#getAvenueSizeY--) | Καθορίζει την ποσότητα κάθετης απόστασης μεταξύ σχημάτων στη σελίδα σχεδίασης όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη των σχημάτων στη σελίδα σχεδίασης. |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | Καθορίζει πώς τοποθετούνται τα σχήματα στη σελίδα όταν τα σχήματα διατάσσονται όταν ο χρήστης επιλέγει «Διάταξη Σχημάτων» (μενού Σχήμα). |
| [getBlockSizeX()](#getBlockSizeX--) | Καθορίζει το κάθετο μέγεθος μπλοκ, την περιοχή στην οποία πρέπει να χωράει το καθένα από τα σχήματά σας στη σελίδα σχεδίασης όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη των σχημάτων. |
| [getBlockSizeY()](#getBlockSizeY--) | Καθορίζει την ποσότητα οριζόντιας απόστασης μεταξύ σχημάτων στη σελίδα σχεδίασης όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη των σχημάτων. |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | Καθορίζει ποιο σχήμα είναι το γονικό όταν χρησιμοποιείτε σχήματα με χειριστήρια ελέγχου. |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getDynamicsOff()](#getDynamicsOff--) | Καθορίζει εάν τα τοποθετήσιμα σχήματα μετακινούνται και οι σύνδεσμοι επαναδρομολογούνται γύρω από άλλα σχήματα και συνδέσμους στη σελίδα σχεδίασης. |
| [getEnableGrid()](#getEnableGrid--) | Καθορίζει εάν το Microsoft Visio διατάσσει τα σχήματα βάσει ενός εσωτερικού πλέγματος σελίδας όταν ο χρήστης επιλέγει τη λειτουργία Lay Out Shapes (μενού Shape). |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | Καθορίζει ποιοι δυναμικοί συνδέσμοι να διαχωριστούν εάν δρομολογηθούν πάνω ο ένας στον άλλο. |
| [getLineAdjustTo()](#getLineAdjustTo--) | Καθορίζει ποιοι δυναμικοί συνδέσμοι να ευθυγραμμιστούν πάνω ο ένας στον άλλο εάν δρομολογηθούν πάνω ο ένας στον άλλο. |
| [getLineJumpCode()](#getLineJumpCode--) | Καθορίζει το στυλ άλματος γραμμής για όλους τους συνδέσμους στη σελίδα σχεδίασης που δεν έχουν τοπικό στυλ άλματος γραμμής. |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | Καθορίζει το μέγεθος των διαλειμμάτων γραμμής σε οριζόντια τμήματα των δυναμικών συνδέσμων στη σελίδα, ως ποσοστό της τιμής του στοιχείου LineToLineX (που καθορίζει την οριζόντια απόσταση μεταξύ όλων των συνδέσμων στη σελίδα σχεδίασης). |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | Καθορίζει το μέγεθος των διαλειμμάτων γραμμής σε κάθετα τμήματα των δυναμικών συνδέσμων στη σελίδα, ως ποσοστό της τιμής του στοιχείου LineToLineY (που καθορίζει την κάθετη απόσταση μεταξύ όλων των συνδέσμων στη σελίδα σχεδίασης). |
| [getLineJumpStyle()](#getLineJumpStyle--) | Καθορίζει την κατεύθυνση των άλματα γραμμής σε οριζόντια τμήματα δυναμικών συνδέσμων στη σελίδα σχεδίασης για τα οποία δεν έχετε εφαρμόσει τοπική κατεύθυνση άλματος. |
| [getLineRouteExt()](#getLineRouteExt--) | Καθορίζει την προεπιλεγμένη εμφάνιση για όλους τους συνδέσμους σε μια σελίδα. |
| [getLineToLineX()](#getLineToLineX--) | Καθορίζει την ελάχιστη οριζόντια απόσταση μεταξύ των δυναμικών συνδέσμων στη σελίδα σχεδίασης. |
| [getLineToLineY()](#getLineToLineY--) | Καθορίζει την ελάχιστη κάθετη απόσταση μεταξύ των δυναμικών συνδέσμων στη σελίδα σχεδίασης. |
| [getLineToNodeX()](#getLineToNodeX--) | Καθορίζει την ελάχιστη κάθετη απόσταση μεταξύ των δυναμικών συνδέσμων και των σχημάτων στη σελίδα σχεδίασης. |
| [getLineToNodeY()](#getLineToNodeY--) | Καθορίζει το οριζόντιο μέγεθος μπλοκ, την περιοχή στην οποία πρέπει να χωράει το καθένα από τα σχήματά σας στη σελίδα σχεδίασης όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη των σχημάτων. |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | Καθορίζει την κατεύθυνση των άλματα γραμμής σε κάθετα δυναμικά συνδέσμους στη σελίδα σχεδίασης για τα οποία δεν έχετε εφαρμόσει τοπική κατεύθυνση άλματος. |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | Καθορίζει την ελάχιστη οριζόντια απόσταση μεταξύ των δυναμικών συνδέσμων και των σχημάτων στη σελίδα σχεδίασης. |
| [getPageShapeSplit()](#getPageShapeSplit--) | Δείχνει εάν τα σχήματα στη σελίδα μπορούν να χωριστούν αυτόματα. |
| [getPlaceDepth()](#getPlaceDepth--) | Καθορίζει εάν τα τοποθετήσιμα σχήματα απομακρύνονται όταν ο χρήστης σύρει ένα τοποθετήσιμο σχήμα κοντά σε άλλο τοποθετήσιμο σχήμα στη σελίδα σχεδίασης. |
| [getPlaceFlip()](#getPlaceFlip--) | Καθορίζει πώς τα τοποθετήσιμα σχήματα αναστρέφονται και/ή περιστρέφονται σε μια σελίδα όταν τα σχήματα διατάσσονται χρησιμοποιώντας την εντολή «Διάταξη Σχημάτων» στο Microsoft Visio. |
| [getPlaceStyle()](#getPlaceStyle--) | Καθορίζει το στυλ δρομολόγησης και την κατεύθυνση για όλους τους δυναμικούς συνδέσμους στη σελίδα σχεδίασης που δεν έχουν τοπικό στυλ δρομολόγησης. |
| [getPlowCode()](#getPlowCode--) | Καθορίζει τους δυναμικούς συνδέσμους στους οποίους θέλετε να προσθέσετε άλματα. |
| [getResizePage()](#getResizePage--) | Καθορίζει εάν θα επεκταθεί η σελίδα για να περιλάβει το σχέδιο μετά την επιλογή του χρήστη της λειτουργίας Lay Out Shapes (μενού Shapes). |
| [getRouteStyle()](#getRouteStyle--) | Για ένα σχέδιο που διατάσσεται αυτόματα, καθορίζει τη μέθοδο με την οποία το σχέδιο αναλύεται πριν δημιουργηθεί η διάταξη και προσδιορίζει τον τύπο διάταξης. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/pagelayout\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


Καθορίζει την ποσότητα κάθετης απόστασης μεταξύ σχημάτων στη σελίδα σχεδίασης όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη των σχημάτων στη σελίδα σχεδίασης.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


Καθορίζει την ποσότητα κάθετης απόστασης μεταξύ σχημάτων στη σελίδα σχεδίασης όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη των σχημάτων στη σελίδα σχεδίασης.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


Καθορίζει πώς τοποθετούνται τα σχήματα στη σελίδα όταν τα σχήματα διατάσσονται όταν ο χρήστης επιλέγει «Διάταξη Σχημάτων» (μενού Σχήμα).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


Καθορίζει το κάθετο μέγεθος μπλοκ, την περιοχή στην οποία πρέπει να χωράει το καθένα από τα σχήματά σας στη σελίδα σχεδίασης όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη των σχημάτων.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


Καθορίζει την ποσότητα οριζόντιας απόστασης μεταξύ σχημάτων στη σελίδα σχεδίασης όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη των σχημάτων.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


Καθορίζει ποιο σχήμα είναι το γονικό όταν χρησιμοποιείτε σχήματα με χειριστήρια ελέγχου. Αυτό το στοιχείο ορίζει τη συμπεριφορά για όλα τα σχήματα στη σελίδα σχεδίασης.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


Καθορίζει εάν τα τοποθετήσιμα σχήματα μετακινούνται και οι σύνδεσμοι επαναδρομολογούνται γύρω από άλλα σχήματα και συνδέσμους στη σελίδα σχεδίασης.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


Καθορίζει εάν το Microsoft Visio διατάσσει τα σχήματα βάσει ενός εσωτερικού πλέγματος σελίδας όταν ο χρήστης επιλέγει τη λειτουργία Lay Out Shapes (μενού Shape).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


Καθορίζει ποιοι δυναμικοί συνδέσμοι να διαχωριστούν εάν δρομολογηθούν πάνω ο ένας στον άλλο.

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


Καθορίζει ποιοι δυναμικοί συνδέσμοι να ευθυγραμμιστούν πάνω ο ένας στον άλλο εάν δρομολογηθούν πάνω ο ένας στον άλλο.

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


Καθορίζει το στυλ άλματος γραμμής για όλους τους συνδέσμους στη σελίδα σχεδίασης που δεν έχουν τοπικό στυλ άλματος γραμμής.

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


Καθορίζει το μέγεθος των διαλειμμάτων γραμμής σε οριζόντια τμήματα των δυναμικών συνδέσμων στη σελίδα, ως ποσοστό της τιμής του στοιχείου LineToLineX (που καθορίζει την οριζόντια απόσταση μεταξύ όλων των συνδέσμων στη σελίδα σχεδίασης). Η τιμή αυτού του στοιχείου κυμαίνεται από 0 έως 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


Καθορίζει το μέγεθος των διαλειμμάτων γραμμής σε κάθετα τμήματα των δυναμικών συνδέσμων στη σελίδα, ως ποσοστό της τιμής του στοιχείου LineToLineY (που καθορίζει την κάθετη απόσταση μεταξύ όλων των συνδέσμων στη σελίδα σχεδίασης). Αυτό το στοιχείο μπορεί να περιέχει τιμή από 0 έως 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


Καθορίζει την κατεύθυνση των άλματα γραμμής σε οριζόντια τμήματα δυναμικών συνδέσμων στη σελίδα σχεδίασης για τα οποία δεν έχετε εφαρμόσει τοπική κατεύθυνση άλματος.

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


Καθορίζει την προεπιλεγμένη εμφάνιση για όλους τους συνδέσμους σε μια σελίδα.

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


Καθορίζει την ελάχιστη οριζόντια απόσταση μεταξύ των δυναμικών συνδέσμων στη σελίδα σχεδίασης.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


Καθορίζει την ελάχιστη κάθετη απόσταση μεταξύ των δυναμικών συνδέσμων στη σελίδα σχεδίασης.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


Καθορίζει την ελάχιστη κάθετη απόσταση μεταξύ των δυναμικών συνδέσμων και των σχημάτων στη σελίδα σχεδίασης.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


Καθορίζει το οριζόντιο μέγεθος μπλοκ, την περιοχή στην οποία πρέπει να χωράει το καθένα από τα σχήματά σας στη σελίδα σχεδίασης όταν χρησιμοποιείτε το Microsoft Visio για τη διάταξη των σχημάτων.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


Καθορίζει την κατεύθυνση των άλματα γραμμής σε κάθετα δυναμικά συνδέσμους στη σελίδα σχεδίασης για τα οποία δεν έχετε εφαρμόσει τοπική κατεύθυνση άλματος.

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


Καθορίζει την ελάχιστη οριζόντια απόσταση μεταξύ των δυναμικών συνδέσμων και των σχημάτων στη σελίδα σχεδίασης.

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


Δείχνει εάν τα σχήματα στη σελίδα μπορούν να χωριστούν αυτόματα.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


Καθορίζει εάν τα τοποθετήσιμα σχήματα απομακρύνονται όταν ο χρήστης σύρει ένα τοποθετήσιμο σχήμα κοντά σε άλλο τοποθετήσιμο σχήμα στη σελίδα σχεδίασης.

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


Καθορίζει πώς τα τοποθετήσιμα σχήματα περιστρέφονται και/ή αναστρέφονται σε μια σελίδα όταν τα σχήματα τοποθετούνται χρησιμοποιώντας την εντολή Lay Out Shapes στο Microsoft Visio. Επιτρέπονται οι παρακάτω δεκαεξαδικές τιμές.

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


Καθορίζει το στυλ δρομολόγησης και την κατεύθυνση για όλους τους δυναμικούς συνδέσμους στη σελίδα σχεδίασης που δεν έχουν τοπικό στυλ δρομολόγησης.

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


Καθορίζει τους δυναμικούς συνδέσμους στους οποίους θέλετε να προσθέσετε άλματα.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


Καθορίζει εάν θα επεκταθεί η σελίδα για να περιλάβει το σχέδιο μετά την επιλογή του χρήστη της λειτουργίας Lay Out Shapes (μενού Shapes).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


Για ένα σχέδιο που διατάσσεται αυτόματα, καθορίζει τη μέθοδο με την οποία το σχέδιο αναλύεται πριν δημιουργηθεί η διάταξη και προσδιορίζει τον τύπο διάταξης.

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/pagelayout\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

