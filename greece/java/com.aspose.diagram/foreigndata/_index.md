---
title: ForeignData
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει ένα BLOB κωδικοποιημένο με MIME Multipurpose Internet Mail Extensions δεδομένων εικόνας, όπως bitmap μετα-αρχείου Windows ή δεδομένα OLE.
type: docs
weight: 164
url: /el/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

Περιέχει ένα κωδικοποιημένο MIME (Multipurpose Internet Mail Extensions) BLOB δεδομένων εικόνας, όπως αρχείο μεταφόρμας Windows, bitmap ή δεδομένα OLE.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα αντικείμενο βασισμένο σε raster, όπως αρχείο DIB, JPG, PNG, TIFF ή GIF. |
| [getCompressionType()](#getCompressionType--) | Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα αντικείμενο βασισμένο σε raster, όπως αρχείο DIB, JPG, PNG, TIFF ή GIF. |
| [getExtentX()](#getExtentX--) | Αυτό το χαρακτηριστικό είναι σημαντικό μόνο εάν τα ξένα δεδομένα είναι μετα-αρχείο. |
| [getExtentY()](#getExtentY--) | Αυτό το χαρακτηριστικό είναι σημαντικό μόνο εάν τα ξένα δεδομένα είναι μετα-αρχείο. |
| [getForeignType()](#getForeignType--) | Τύπος δεδομένων. |
| [getImageData()](#getImageData--) | Αναπαριστά την εικόνα του αντικειμένου ole ως πίνακα byte. |
| [getMappingMode()](#getMappingMode--) | Αυτό το χαρακτηριστικό είναι σημαντικό μόνο εάν τα ξένα δεδομένα είναι μετα-αρχείο. |
| [getObjectData()](#getObjectData--) | Αναπαριστά τα ενσωματωμένα δεδομένα του αντικειμένου ole ως πίνακα byte. |
| [getObjectHeight()](#getObjectHeight--) | Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα ενσωματωμένο αντικείμενο OLE2. |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | Επιστρέφει το πλήρες όνομα προέλευσης του αρχείου προέλευσης για το συνδεδεμένο αντικείμενο OLE. |
| [getObjectType()](#getObjectType--) | Εάν το χαρακτηριστικό ForeignType είναι "Object", το στοιχείο ForeignData πρέπει επίσης να έχει χαρακτηριστικό ObjectType. |
| [getObjectWidth()](#getObjectWidth--) | Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα ενσωματωμένο αντικείμενο OLE2. |
| [getShowAsIcon()](#getShowAsIcon--) | Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα ενσωματωμένο αντικείμενο OLE2. |
| [getValue()](#getValue--) | Περιέχει ένα κωδικοποιημένο MIME (Multipurpose Internet Mail Extensions) BLOB δεδομένων εικόνας, όπως αρχείο μεταφόρμας Windows, bitmap ή δεδομένα OLE. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getValue()](../../com.aspose.diagram/foreigndata\#getValue--) |
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
### getCompressionLevel() {#getCompressionLevel--}
```
public double getCompressionLevel()
```


Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα αντικείμενο βασισμένο σε raster, όπως αρχείο DIB, JPG, PNG, TIFF ή GIF. Η τιμή υποδεικνύει το επίπεδο συμπίεσης που εφαρμόζεται στο αρχείο. Το επίπεδο συμπίεσης μετράται σε εκατοντάδες του ποσοστού.

**Returns:**
double
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα αντικείμενο βασισμένο σε raster, όπως αρχείο DIB, JPG, PNG, TIFF ή GIF. Η τιμή υποδεικνύει τον τύπο της συμπίεσης που εφαρμόζεται στο αρχείο.

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα μετααρχείο. Η τιμή υποδεικνύει την οριζόντια έκταση του μετααρχείου.

**Returns:**
double
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα μετααρχείο. Η τιμή υποδεικνύει την κάθετη έκταση του μετααρχείου.

**Returns:**
double
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


Τύπος δεδομένων.

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


Αναπαριστά την εικόνα του αντικειμένου ole ως πίνακα byte.

**Returns:**
byte[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα μετααρχείο. Η τιμή υποδεικνύει τη λειτουργία χαρτογράφησης του μετααρχείου.

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


Αναπαριστά τα ενσωματωμένα δεδομένα του αντικειμένου ole ως πίνακα byte.

**Returns:**
byte[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα ενσωματωμένο αντικείμενο OLE2. Η τιμή εκφράζει το ύψος του αντικειμένου σε μονάδες σελίδας.

**Returns:**
double
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


Επιστρέφει το πλήρες όνομα προέλευσης του αρχείου προέλευσης για το συνδεδεμένο αντικείμενο OLE. Υποστηρίζει μόνο τον ορισμό του πλήρους ονόματος προέλευσης όταν ο τύπος αρχείου είναι OleFileType.Unknown. Όπως αρχεία wav, avi κ.λπ.

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


Εάν το χαρακτηριστικό ForeignType είναι "Object", το στοιχείο ForeignData πρέπει επίσης να έχει χαρακτηριστικό ObjectType.

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα ενσωματωμένο αντικείμενο OLE2. Η τιμή εκφράζει το πλάτος του αντικειμένου σε μονάδες σελίδας.

**Returns:**
double
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


Αυτό το χαρακτηριστικό έχει νόημα μόνο εάν τα ξένα δεδομένα είναι ένα ενσωματωμένο αντικείμενο OLE2.

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


Περιέχει ένα κωδικοποιημένο MIME (Multipurpose Internet Mail Extensions) BLOB δεδομένων εικόνας, όπως αρχείο μεταφόρμας Windows, bitmap ή δεδομένα OLE.

**Returns:**
byte[]
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




### setCompressionLevel(double value) {#setCompressionLevel-double-}
```
public void setCompressionLevel(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

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

