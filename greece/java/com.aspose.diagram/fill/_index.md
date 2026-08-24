---
title: Fill
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει τις τρέχουσες τιμές μορφοποίησης γεμίσματος για το σχήμα και τη σκιά του σχήματος, συμπεριλαμβανομένου του χρώματος προσκηνίου του μοτίβου και του χρώματος φόντου.
type: docs
weight: 153
url: /el/java/com.aspose.diagram/fill/
---

**Inheritance:**
java.lang.Object
```
public class Fill
```

Περιέχει τις τρέχουσες τιμές μορφοποίησης γεμίσματος για το σχήμα και τη σκιά του σχήματος, συμπεριλαμβανομένου του μοτίβου, του χρώματος προσκηνίου και του χρώματος φόντου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getFillBkgnd()](#getFillBkgnd--) | Καθορίζει το χρώμα που χρησιμοποιείται για το φόντο του μοτίβου γεμίσματος του σχήματος. |
| [getFillBkgndTrans()](#getFillBkgndTrans--) | Καθορίζει το επίπεδο διαφάνειας για το χρώμα φόντου (γεμίσματος) του μοτίβου γεμίσματος του σχήματος, από 0 (πλήρως αδιαφανές) έως 1 (πλήρως διαφανές). |
| [getFillForegnd()](#getFillForegnd--) | Καθορίζει το χρώμα που χρησιμοποιείται για το προσκήνιο (γραμμή) του μοτίβου γεμίσματος του σχήματος. |
| [getFillForegndTrans()](#getFillForegndTrans--) | Καθορίζει το επίπεδο διαφάνειας για το χρώμα προσκηνίου (γεμίσματος) του μοτίβου γεμίσματος του σχήματος, από 0 (πλήρως αδιαφανές) έως 1 (πλήρως διαφανές). |
| [getFillPattern()](#getFillPattern--) | Καθορίζει το μοτίβο γεμίσματος για το σχήμα. |
| [getGradientFill()](#getGradientFill--) | Περιέχει τις τρέχουσες τιμές μορφοποίησης διαβάθμισης γεμίσματος για το σχήμα |
| [getShapeShdwBlur()](#getShapeShdwBlur--) | Καθορίζει το μέγεθος θολώματος της σκιάς ενός σχήματος. |
| [getShapeShdwObliqueAngle()](#getShapeShdwObliqueAngle--) | Καθορίζει τη γωνία της λοξής κατεύθυνσης της σκιάς ενός σχήματος. |
| [getShapeShdwOffsetX()](#getShapeShdwOffsetX--) | Καθορίζει την απόσταση σε μονάδες σελίδας που η σκιά ενός σχήματος μετατοπίζεται οριζόντια από το σχήμα. |
| [getShapeShdwOffsetY()](#getShapeShdwOffsetY--) | Καθορίζει την απόσταση σε μονάδες σελίδας που η σκιά ενός σχήματος μετατοπίζεται κάθετα από το σχήμα. |
| [getShapeShdwScaleFactor()](#getShapeShdwScaleFactor--) | Καθορίζει το ποσοστό κατά το οποίο η σκιά ενός σχήματος μπορεί να μεγεθυνθεί ή να μειωθεί. |
| [getShapeShdwShow()](#getShapeShdwShow--) | Καθορίζει τον τύπο σκιάς για ένα σχήμα. |
| [getShapeShdwType()](#getShapeShdwType--) | Καθορίζει τον τύπο σκιάς για ένα σχήμα. |
| [getShdwBkgnd()](#getShdwBkgnd--) | Καθορίζει το χρώμα που χρησιμοποιείται για το φόντο (γέμισμα) του μοτίβου γεμίσματος της σκιάς πτώσης του σχήματος. |
| [getShdwBkgndTrans()](#getShdwBkgndTrans--) | Καθορίζει το επίπεδο διαφάνειας για το φόντο (γέμισμα) του μοτίβου γεμίσματος της σκιάς πτώσης του σχήματος, από 0.0 (πλήρως αδιαφανές) έως 1.0 (πλήρως διαφανές). |
| [getShdwForegnd()](#getShdwForegnd--) | Καθορίζει το χρώμα που χρησιμοποιείται για το προσκήνιο (γραμμή) του μοτίβου γεμίσματος της σκιάς πτώσης του σχήματος. |
| [getShdwForegndTrans()](#getShdwForegndTrans--) | Καθορίζει το επίπεδο διαφάνειας για το προσκήνιο (γραμμή) του μοτίβου γεμίσματος της σκιάς πτώσης του σχήματος, από 0.0 (πλήρως αδιαφανές) έως 1.0 (πλήρως διαφανές). |
| [getShdwPattern()](#getShdwPattern--) | Καθορίζει το μοτίβο γεμίσματος για τη σκιά ενός σχήματος. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/fill\#getDel--) |
| [setFillBkgnd(ColorValue value)](#setFillBkgnd-com.aspose.diagram.ColorValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--) |
| [setFillBkgndTrans(DoubleValue value)](#setFillBkgndTrans-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--) |
| [setFillForegnd(ColorValue value)](#setFillForegnd-com.aspose.diagram.ColorValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--) |
| [setFillForegndTrans(DoubleValue value)](#setFillForegndTrans-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--) |
| [setFillPattern(IntValue value)](#setFillPattern-com.aspose.diagram.IntValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--) |
| [setShapeShdwBlur(DoubleValue value)](#setShapeShdwBlur-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--) |
| [setShapeShdwObliqueAngle(DoubleValue value)](#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--) |
| [setShapeShdwOffsetX(DoubleValue value)](#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--) |
| [setShapeShdwOffsetY(DoubleValue value)](#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--) |
| [setShapeShdwScaleFactor(DoubleValue value)](#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--) |
| [setShapeShdwShow(ShapeShdwShow value)](#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--) |
| [setShapeShdwType(ShapeShdwType value)](#setShapeShdwType-com.aspose.diagram.ShapeShdwType-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--) |
| [setShdwBkgnd(ColorValue value)](#setShdwBkgnd-com.aspose.diagram.ColorValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--) |
| [setShdwBkgndTrans(DoubleValue value)](#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--) |
| [setShdwForegnd(ColorValue value)](#setShdwForegnd-com.aspose.diagram.ColorValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--) |
| [setShdwForegndTrans(DoubleValue value)](#setShdwForegndTrans-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--) |
| [setShdwPattern(IntValue value)](#setShdwPattern-com.aspose.diagram.IntValue-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας.

**Returns:**
java.lang.Object -
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
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getFillBkgnd() {#getFillBkgnd--}
```
public ColorValue getFillBkgnd()
```


Καθορίζει το χρώμα που χρησιμοποιείται για το φόντο του μοτίβου γεμίσματος του σχήματος.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillBkgndTrans() {#getFillBkgndTrans--}
```
public DoubleValue getFillBkgndTrans()
```


Καθορίζει το επίπεδο διαφάνειας για το χρώμα φόντου (γεμίσματος) του μοτίβου γεμίσματος του σχήματος, από 0 (πλήρως αδιαφανές) έως 1 (πλήρως διαφανές).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillForegnd() {#getFillForegnd--}
```
public ColorValue getFillForegnd()
```


Καθορίζει το χρώμα που χρησιμοποιείται για το προσκήνιο (γραμμή) του μοτίβου γεμίσματος του σχήματος.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillForegndTrans() {#getFillForegndTrans--}
```
public DoubleValue getFillForegndTrans()
```


Καθορίζει το επίπεδο διαφάνειας για το χρώμα προσκηνίου (γεμίσματος) του μοτίβου γεμίσματος του σχήματος, από 0 (πλήρως αδιαφανές) έως 1 (πλήρως διαφανές).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillPattern() {#getFillPattern--}
```
public IntValue getFillPattern()
```


Καθορίζει το μοτίβο γεμίσματος για το σχήμα.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getGradientFill() {#getGradientFill--}
```
public GradientFill getGradientFill()
```


Περιέχει τις τρέχουσες τιμές μορφοποίησης διαβάθμισης γεμίσματος για το σχήμα

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getShapeShdwBlur() {#getShapeShdwBlur--}
```
public DoubleValue getShapeShdwBlur()
```


Καθορίζει το μέγεθος θολώματος της σκιάς ενός σχήματος. Δεν μπορεί να σχεδιάσει θόλωση τώρα, αλλά μπορεί να αναλύσει από το vsdx.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwObliqueAngle() {#getShapeShdwObliqueAngle--}
```
public DoubleValue getShapeShdwObliqueAngle()
```


Καθορίζει τη γωνία της λοξής κατεύθυνσης της σκιάς ενός σχήματος.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetX() {#getShapeShdwOffsetX--}
```
public DoubleValue getShapeShdwOffsetX()
```


Καθορίζει την απόσταση σε μονάδες σελίδας που η σκιά ενός σχήματος μετατοπίζεται οριζόντια από το σχήμα.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetY() {#getShapeShdwOffsetY--}
```
public DoubleValue getShapeShdwOffsetY()
```


Καθορίζει την απόσταση σε μονάδες σελίδας που η σκιά ενός σχήματος μετατοπίζεται κάθετα από το σχήμα.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwScaleFactor() {#getShapeShdwScaleFactor--}
```
public DoubleValue getShapeShdwScaleFactor()
```


Καθορίζει το ποσοστό κατά το οποίο η σκιά ενός σχήματος μπορεί να μεγεθυνθεί ή να μειωθεί.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwShow() {#getShapeShdwShow--}
```
public ShapeShdwShow getShapeShdwShow()
```


Καθορίζει τον τύπο σκιάς για ένα σχήμα.

**Returns:**
[ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow)
### getShapeShdwType() {#getShapeShdwType--}
```
public ShapeShdwType getShapeShdwType()
```


Καθορίζει τον τύπο σκιάς για ένα σχήμα.

**Returns:**
[ShapeShdwType](../../com.aspose.diagram/shapeshdwtype)
### getShdwBkgnd() {#getShdwBkgnd--}
```
public ColorValue getShdwBkgnd()
```


Καθορίζει το χρώμα που χρησιμοποιείται για το φόντο (γέμισμα) του μοτίβου γεμίσματος της σκιάς πτώσης του σχήματος.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwBkgndTrans() {#getShdwBkgndTrans--}
```
public DoubleValue getShdwBkgndTrans()
```


Καθορίζει το επίπεδο διαφάνειας για το φόντο (γέμισμα) του μοτίβου γεμίσματος της σκιάς πτώσης του σχήματος, από 0.0 (πλήρως αδιαφανές) έως 1.0 (πλήρως διαφανές).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwForegnd() {#getShdwForegnd--}
```
public ColorValue getShdwForegnd()
```


Καθορίζει το χρώμα που χρησιμοποιείται για το προσκήνιο (γραμμή) του μοτίβου γεμίσματος της σκιάς πτώσης του σχήματος.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwForegndTrans() {#getShdwForegndTrans--}
```
public DoubleValue getShdwForegndTrans()
```


Καθορίζει το επίπεδο διαφάνειας για το προσκήνιο (γραμμή) του μοτίβου γεμίσματος της σκιάς πτώσης του σχήματος, από 0.0 (πλήρως αδιαφανές) έως 1.0 (πλήρως διαφανές).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwPattern() {#getShdwPattern--}
```
public IntValue getShdwPattern()
```


Καθορίζει το μοτίβο γεμίσματος για τη σκιά ενός σχήματος.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getDel()](../../com.aspose.diagram/fill\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setFillBkgnd(ColorValue value) {#setFillBkgnd-com.aspose.diagram.ColorValue-}
```
public void setFillBkgnd(ColorValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillBkgndTrans(DoubleValue value) {#setFillBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillBkgndTrans(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillForegnd(ColorValue value) {#setFillForegnd-com.aspose.diagram.ColorValue-}
```
public void setFillForegnd(ColorValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillForegndTrans(DoubleValue value) {#setFillForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillForegndTrans(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillPattern(IntValue value) {#setFillPattern-com.aspose.diagram.IntValue-}
```
public void setFillPattern(IntValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setShapeShdwBlur(DoubleValue value) {#setShapeShdwBlur-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwBlur(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwObliqueAngle(DoubleValue value) {#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwObliqueAngle(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetX(DoubleValue value) {#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetX(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetY(DoubleValue value) {#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetY(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwScaleFactor(DoubleValue value) {#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwScaleFactor(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwShow(ShapeShdwShow value) {#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-}
```
public void setShapeShdwShow(ShapeShdwShow value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow) |  |

### setShapeShdwType(ShapeShdwType value) {#setShapeShdwType-com.aspose.diagram.ShapeShdwType-}
```
public void setShapeShdwType(ShapeShdwType value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShapeShdwType](../../com.aspose.diagram/shapeshdwtype) |  |

### setShdwBkgnd(ColorValue value) {#setShdwBkgnd-com.aspose.diagram.ColorValue-}
```
public void setShdwBkgnd(ColorValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwBkgndTrans(DoubleValue value) {#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwBkgndTrans(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwForegnd(ColorValue value) {#setShdwForegnd-com.aspose.diagram.ColorValue-}
```
public void setShdwForegnd(ColorValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwForegndTrans(DoubleValue value) {#setShdwForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwForegndTrans(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwPattern(IntValue value) {#setShdwPattern-com.aspose.diagram.IntValue-}
```
public void setShdwPattern(IntValue value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

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

