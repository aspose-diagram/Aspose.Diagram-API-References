---
title: Line
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία που καθορίζουν γενικές πληροφορίες τοποθέτησης για ένα σχήμα.
type: docs
weight: 221
url: /el/java/com.aspose.diagram/line/
---

**Inheritance:**
java.lang.Object
```
public class Line
```

Περιέχει στοιχεία που καθορίζουν γενικές πληροφορίες τοποθέτησης για ένα σχήμα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginArrow()](#getBeginArrow--) | Υποδεικνύει εάν μια γραμμή έχει κεφαλή βέλους ή άλλη μορφή άκρου γραμμής στο πρώτο της άκρο. |
| [getBeginArrowSize()](#getBeginArrowSize--) | Καθορίζει το μέγεθος της κεφαλής βέλους στην αρχή της γραμμής. |
| [getClass()](#getClass--) |  |
| [getCompoundType()](#getCompoundType--) | Καθορίζει το CompoundType της γραμμής του σχήματος. |
| [getDel()](#getDel--) | Μία σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. |
| [getEndArrow()](#getEndArrow--) | Υποδεικνύει εάν μια γραμμή έχει κεφαλή βέλους ή άλλη μορφή άκρου γραμμής στο τελευταίο της άκρο. |
| [getEndArrowSize()](#getEndArrowSize--) | Καθορίζει το μέγεθος της κεφαλής βέλους στο τέλος της γραμμής. |
| [getGradientLine()](#getGradientLine--) | Περιέχει τις τρέχουσες τιμές μορφοποίησης διαβάθμισης γραμμής για το σχήμα |
| [getLineCap()](#getLineCap--) | Καθορίζει εάν μια γραμμή έχει στρογγυλεμένα ή τετράγωνα άκρα γραμμής. |
| [getLineColor()](#getLineColor--) | Καθορίζει το χρώμα γραμμής του σχήματος. |
| [getLineColorTrans()](#getLineColorTrans--) | Καθορίζει το επίπεδο διαφάνειας του χρώματος γραμμής ενός σχήματος, από 0 (αδιαφανές) έως 1 (πλήρως διαφανές). |
| [getLinePattern()](#getLinePattern--) | Καθορίζει το μοτίβο γραμμής του σχήματος |
| [getLineWeight()](#getLineWeight--) | Καθορίζει το πάχος γραμμής ενός σχήματος. |
| [getRounding()](#getRounding--) | Καθορίζει την ακτίνα του στρογγυλεμένου τόξου που εφαρμόζεται όπου συναντώνται δύο συνεχόμενα τμήματα ενός μονοπατιού. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBeginArrow(IntValue value)](#setBeginArrow-com.aspose.diagram.IntValue-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--) |
| [setBeginArrowSize(ArrowSize value)](#setBeginArrowSize-com.aspose.diagram.ArrowSize-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--) |
| [setCompoundType(CompoundType value)](#setCompoundType-com.aspose.diagram.CompoundType-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--) |
| [setDel(int value)](#setDel-int-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getDel()](../../com.aspose.diagram/line\#getDel--) |
| [setEndArrow(IntValue value)](#setEndArrow-com.aspose.diagram.IntValue-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--) |
| [setEndArrowSize(ArrowSize value)](#setEndArrowSize-com.aspose.diagram.ArrowSize-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--) |
| [setLineCap(BoolValue value)](#setLineCap-com.aspose.diagram.BoolValue-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getLineCap()](../../com.aspose.diagram/line\#getLineCap--) |
| [setLineColor(ColorValue value)](#setLineColor-com.aspose.diagram.ColorValue-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getLineColor()](../../com.aspose.diagram/line\#getLineColor--) |
| [setLineColorTrans(DoubleValue value)](#setLineColorTrans-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--) |
| [setLinePattern(IntValue value)](#setLinePattern-com.aspose.diagram.IntValue-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--) |
| [setLineWeight(DoubleValue value)](#setLineWeight-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--) |
| [setRounding(DoubleValue value)](#setRounding-com.aspose.diagram.DoubleValue-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getRounding()](../../com.aspose.diagram/line\#getRounding--) |
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
### getBeginArrow() {#getBeginArrow--}
```
public IntValue getBeginArrow()
```


Υποδεικνύει εάν μια γραμμή έχει κεφαλή βέλους ή άλλη μορφή άκρου γραμμής στο πρώτο της άκρο. Εισάγετε έναν αριθμό από 0 έως 45 ή τη λειτουργία USE με το όνομα ενός προσαρμοσμένου άκρου γραμμής.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBeginArrowSize() {#getBeginArrowSize--}
```
public ArrowSize getBeginArrowSize()
```


Καθορίζει το μέγεθος της κεφαλής του βέλους στην αρχή της γραμμής. Εισάγετε έναν αριθμό από 0 έως 6.

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompoundType() {#getCompoundType--}
```
public CompoundType getCompoundType()
```


Καθορίζει το CompoundType της γραμμής του σχήματος.

**Returns:**
[CompoundType](../../com.aspose.diagram/compoundtype)
### getDel() {#getDel--}
```
public int getDel()
```


Σημαία που υποδεικνύει εάν το στοιχείο έχει διαγραφεί τοπικά. Μια τιμή 1 υποδεικνύει ότι το στοιχείο διαγράφηκε τοπικά.

**Returns:**
int
### getEndArrow() {#getEndArrow--}
```
public IntValue getEndArrow()
```


Υποδεικνύει εάν μια γραμμή έχει κεφαλή βέλους ή άλλη μορφή άκρου γραμμής στο τελευταίο της άκρο.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getEndArrowSize() {#getEndArrowSize--}
```
public ArrowSize getEndArrowSize()
```


Καθορίζει το μέγεθος της κεφαλής βέλους στο τέλος της γραμμής.

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getGradientLine() {#getGradientLine--}
```
public GradientFill getGradientLine()
```


Περιέχει τις τρέχουσες τιμές μορφοποίησης διαβάθμισης γραμμής για το σχήμα

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getLineCap() {#getLineCap--}
```
public BoolValue getLineCap()
```


Καθορίζει εάν μια γραμμή έχει στρογγυλεμένα ή τετράγωνα άκρα γραμμής.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineColor() {#getLineColor--}
```
public ColorValue getLineColor()
```


Καθορίζει το χρώμα γραμμής του σχήματος.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getLineColorTrans() {#getLineColorTrans--}
```
public DoubleValue getLineColorTrans()
```


Καθορίζει το επίπεδο διαφάνειας του χρώματος γραμμής ενός σχήματος, από 0 (αδιαφανές) έως 1 (πλήρως διαφανές). Η προεπιλογή είναι 0.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLinePattern() {#getLinePattern--}
```
public IntValue getLinePattern()
```


Καθορίζει το μοτίβο γραμμής του σχήματος

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLineWeight() {#getLineWeight--}
```
public DoubleValue getLineWeight()
```


Καθορίζει το πάχος της γραμμής ενός σχήματος. Το πάχος της γραμμής είναι ανεξάρτητο από την κλίμακα του σχεδίου. Εάν το σχέδιο κλιμακωθεί, το πάχος της γραμμής παραμένει το ίδιο.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRounding() {#getRounding--}
```
public DoubleValue getRounding()
```


Καθορίζει την ακτίνα του κυρτού τόξου που εφαρμόζεται όπου δύο συνεχόμενα τμήματα μιας διαδρομής συναντιούνται. Για παράδειγμα, η στρογγυλοποίηση μπορεί να χρησιμοποιηθεί για να δώσει σε ένα ορθογώνιο στρογγυλεμένες γωνίες.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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




### setBeginArrow(IntValue value) {#setBeginArrow-com.aspose.diagram.IntValue-}
```
public void setBeginArrow(IntValue value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBeginArrowSize(ArrowSize value) {#setBeginArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setBeginArrowSize(ArrowSize value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setCompoundType(CompoundType value) {#setCompoundType-com.aspose.diagram.CompoundType-}
```
public void setCompoundType(CompoundType value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [CompoundType](../../com.aspose.diagram/compoundtype) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getDel()](../../com.aspose.diagram/line\#getDel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEndArrow(IntValue value) {#setEndArrow-com.aspose.diagram.IntValue-}
```
public void setEndArrow(IntValue value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setEndArrowSize(ArrowSize value) {#setEndArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setEndArrowSize(ArrowSize value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setLineCap(BoolValue value) {#setLineCap-com.aspose.diagram.BoolValue-}
```
public void setLineCap(BoolValue value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getLineCap()](../../com.aspose.diagram/line\#getLineCap--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setLineColor(ColorValue value) {#setLineColor-com.aspose.diagram.ColorValue-}
```
public void setLineColor(ColorValue value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getLineColor()](../../com.aspose.diagram/line\#getLineColor--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setLineColorTrans(DoubleValue value) {#setLineColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setLineColorTrans(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLinePattern(IntValue value) {#setLinePattern-com.aspose.diagram.IntValue-}
```
public void setLinePattern(IntValue value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLineWeight(DoubleValue value) {#setLineWeight-com.aspose.diagram.DoubleValue-}
```
public void setLineWeight(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRounding(DoubleValue value) {#setRounding-com.aspose.diagram.DoubleValue-}
```
public void setRounding(DoubleValue value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getRounding()](../../com.aspose.diagram/line\#getRounding--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

