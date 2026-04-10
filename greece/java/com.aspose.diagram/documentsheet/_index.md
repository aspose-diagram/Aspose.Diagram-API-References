---
title: DocumentSheet
second_title: Αναφορά API του Aspose.Diagram για Java
description: Καθορίζει τη δομή ShapeSheet ενός εγγράφου.
type: docs
weight: 127
url: /el/java/com.aspose.diagram/documentsheet/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSheet
```

Καθορίζει τη δομή ShapeSheet ενός εγγράφου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnnotations()](#getAnnotations--) | Περιέχει στοιχεία που περιέχουν πληροφορίες σχετικά με σχόλια που εισήχθησαν σε μια σελίδα εγγράφου. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Περιέχει μια συλλογή από στοιχεία ConnectionABCD. |
| [getConnections()](#getConnections--) | Περιέχει μια συλλογή από στοιχεία Connection. |
| [getDocProps()](#getDocProps--) | Περιέχει στοιχεία που ελέγχουν την ποιότητα προεπισκόπησης του εγγράφου, το πεδίο εφαρμογής και τη μορφή εξόδου. |
| [getFillStyle()](#getFillStyle--) | Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση γεμίσματος. |
| [getForeign()](#getForeign--) | Περιέχει στοιχεία που καθορίζουν το πλάτος και το ύψος ενός αντικειμένου από άλλο πρόγραμμα που χρησιμοποιείται σε έγγραφο Microsoft Visio. |
| [getForeignData()](#getForeignData--) | Περιέχει ένα κωδικοποιημένο MIME (Multipurpose Internet Mail Extensions) BLOB δεδομένων εικόνας, όπως αρχείο μεταφόρμας Windows, bitmap ή δεδομένα OLE. |
| [getHyperlinks()](#getHyperlinks--) | Περιέχει μια συλλογή στοιχείων Hyperlink. |
| [getLineStyle()](#getLineStyle--) | Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση γραμμής. |
| [getName()](#getName--) | Το όνομα του στοιχείου. |
| [getNameU()](#getNameU--) | Το καθολικό όνομα του στοιχείου. |
| [getProps()](#getProps--) | Περιέχει μια συλλογή στοιχείων Prop. |
| [getReviewers()](#getReviewers--) | Περιέχει στοιχεία που περιλαμβάνουν πληροφορίες ταυτοποίησης για έναν αξιολογητή εγγράφου. |
| [getScratchs()](#getScratchs--) | Περιέχει μια συλλογή από στοιχεία Scratch. |
| [getTextStyle()](#getTextStyle--) | Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση κειμένου. |
| [getUniqueID()](#getUniqueID--) | Ένα GUID (παγκοσμίως μοναδικό αναγνωριστικό) που αναγνωρίζει το σχήμα. |
| [getUsers()](#getUsers--) | Περιέχει μια συλλογή από στοιχεία User. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getName()](../../com.aspose.diagram/documentsheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Για την περιγραφή αυτής της ιδιότητας, δείτε [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--) |
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
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Περιέχει στοιχεία που περιέχουν πληροφορίες σχετικά με σχόλια που εισήχθησαν σε μια σελίδα εγγράφου.

**Returns:**
[AnnotationCollection](../../com.aspose.diagram/annotationcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


Περιέχει μια συλλογή από στοιχεία ConnectionABCD.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Περιέχει μια συλλογή από στοιχεία Connection.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getDocProps() {#getDocProps--}
```
public DocProps getDocProps()
```


Περιέχει στοιχεία που ελέγχουν την ποιότητα προεπισκόπησης του εγγράφου, το πεδίο εφαρμογής και τη μορφή εξόδου.

**Returns:**
[DocProps](../../com.aspose.diagram/docprops)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση γεμίσματος.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Περιέχει στοιχεία που καθορίζουν το πλάτος και το ύψος ενός αντικειμένου από άλλο πρόγραμμα που χρησιμοποιείται σε έγγραφο Microsoft Visio. Περιλαμβάνει επίσης στοιχεία που καθορίζουν την απόσταση με την οποία η εικόνα του αντικειμένου είναι μετατοπισμένη εντός των περιγραμμάτων του.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Περιέχει ένα κωδικοποιημένο MIME (Multipurpose Internet Mail Extensions) BLOB δεδομένων εικόνας, όπως αρχείο μεταφόρμας Windows, bitmap ή δεδομένα OLE.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Περιέχει μια συλλογή στοιχείων Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση γραμμής.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getName() {#getName--}
```
public String getName()
```


Το όνομα του στοιχείου.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Το καθολικό όνομα του στοιχείου.

**Returns:**
java.lang.String
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Περιέχει μια συλλογή στοιχείων Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getReviewers() {#getReviewers--}
```
public ReviewerCollection getReviewers()
```


Περιέχει στοιχεία που περιλαμβάνουν πληροφορίες ταυτοποίησης για έναν αξιολογητή εγγράφου.

**Returns:**
[ReviewerCollection](../../com.aspose.diagram/reviewercollection)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Περιέχει μια συλλογή από στοιχεία Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


Στοιχείο StyleSheet από το οποίο αυτό το στυλ κληρονομεί τη μορφοποίηση κειμένου.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Ένα GUID (παγκοσμίως μοναδικό αναγνωριστικό) που αναγνωρίζει το σχήμα.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Περιέχει μια συλλογή από στοιχεία User.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
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




### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getName()](../../com.aspose.diagram/documentsheet\#getName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Για την περιγραφή αυτής της ιδιότητας, δείτε [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.UUID |  |

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

