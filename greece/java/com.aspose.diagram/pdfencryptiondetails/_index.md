---
title: PdfEncryptionDetails
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει λεπτομέρειες για κρυπτογράφηση PDF.
type: docs
weight: 279
url: /el/java/com.aspose.diagram/pdfencryptiondetails/
---

**Inheritance:**
java.lang.Object
```
public class PdfEncryptionDetails
```

Περιέχει λεπτομέρειες για κρυπτογράφηση PDF.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)](#PdfEncryptionDetails-java.lang.String-java.lang.String-int-) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncryptionAlgorithm()](#getEncryptionAlgorithm--) | η λειτουργία κρυπτογράφησης. |
| [getOwnerPassword()](#getOwnerPassword--) | ο κωδικός πρόσβασης Ιδιοκτήτη. |
| [getPermissions()](#getPermissions--) | οι άδειες. |
| [getUserPassword()](#getUserPassword--) | ο κωδικός πρόσβασης Χρήστη. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncryptionAlgorithm(int value)](#setEncryptionAlgorithm-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--) |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--) |
| [setPermissions(int value)](#setPermissions-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--) |
| [setUserPassword(String value)](#setUserPassword-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm) {#PdfEncryptionDetails-java.lang.String-java.lang.String-int-}
```
public PdfEncryptionDetails(String userPassword, String ownerPassword, int encryptionAlgorithm)
```


Κατασκευαστής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| userPassword | java.lang.String |  |
| ownerPassword | java.lang.String |  |
| encryptionAlgorithm | int |  |

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
### getEncryptionAlgorithm() {#getEncryptionAlgorithm--}
```
public int getEncryptionAlgorithm()
```


η λειτουργία κρυπτογράφησης.

**Returns:**
int
### getOwnerPassword() {#getOwnerPassword--}
```
public String getOwnerPassword()
```


ο κωδικός πρόσβασης του Ιδιοκτήτη. Το άνοιγμα του εγγράφου με τον σωστό κωδικό πρόσβασης του ιδιοκτήτη (υποθέτοντας ότι δεν είναι ίδιος με τον κωδικό πρόσβασης του χρήστη) επιτρέπει πλήρη (ιδιοκτησιακή) πρόσβαση στο έγγραφο. Αυτή η απεριόριστη πρόσβαση περιλαμβάνει τη δυνατότητα αλλαγής των κωδικών πρόσβασης του εγγράφου\\u9225\\u6a9a και των δικαιωμάτων πρόσβασης.

**Returns:**
java.lang.String
### getPermissions() {#getPermissions--}
```
public int getPermissions()
```


οι άδειες.

**Returns:**
int
### getUserPassword() {#getUserPassword--}
```
public String getUserPassword()
```


ο κωδικός πρόσβασης του Χρήστη. Το άνοιγμα του εγγράφου με τον σωστό κωδικό πρόσβασης του χρήστη (ή το άνοιγμα ενός εγγράφου που δεν έχει κωδικό πρόσβασης χρήστη) επιτρέπει πρόσθετες λειτουργίες να εκτελεστούν σύμφωνα με τα δικαιώματα πρόσβασης του χρήστη που καθορίζονται στο λεξικό κρυπτογράφησης του εγγράφου\\u9225\\u6a9a.

**Returns:**
java.lang.String
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




### setEncryptionAlgorithm(int value) {#setEncryptionAlgorithm-int-}
```
public void setEncryptionAlgorithm(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEncryptionAlgorithm()](../../com.aspose.diagram/pdfencryptiondetails\#getEncryptionAlgorithm--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getOwnerPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getOwnerPassword--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPermissions(int value) {#setPermissions-int-}
```
public void setPermissions(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPermissions()](../../com.aspose.diagram/pdfencryptiondetails\#getPermissions--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setUserPassword(String value) {#setUserPassword-java.lang.String-}
```
public void setUserPassword(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getUserPassword()](../../com.aspose.diagram/pdfencryptiondetails\#getUserPassword--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

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

