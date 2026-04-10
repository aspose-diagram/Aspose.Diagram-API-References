---
title: Master
second_title: Αναφορά API του Aspose.Diagram για Java
description: Περιέχει στοιχεία που ορίζουν ένα master για το έγγραφο.
type: docs
weight: 240
url: /el/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

Περιέχει στοιχεία που ορίζουν ένα master για το έγγραφο. Ένα master είναι ένα σχήμα σε ένα πρότυπο που χρησιμοποιείτε επανειλημμένα για τη δημιουργία σχεδίων. Όταν σύρετε ένα σχήμα από το πρότυπο στη σελίδα σχεδίασης, το σχήμα γίνεται ένα αντίτυπο αυτού του master, και ένα τοπικό αντίγραφο του master περιλαμβάνεται στο έγγραφο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Master()](#Master--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας. |
| [dispose()](#dispose--) | Εκτελεί εργασίες που ορίζονται από την εφαρμογή, σχετικές με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | Καθορίζει εάν το κείμενο του master στο παράθυρο πρότυπου είναι ευθυγραμμισμένο αριστερά, δεξιά ή κεντρικά. |
| [getBaseID()](#getBaseID--) | Ένα GUID (καθολικά μοναδικό αναγνωριστικό) που ταυτοποιεί το master σε όλα τα έγγραφα. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Περιέχει ένα στοιχείο Connect για κάθε σύνδεση μεταξύ δύο σχημάτων σε ένα σχέδιο. |
| [getHidden()](#getHidden--) | Καθορίζει εάν το master είναι κρυφό στη διεπαφή χρήστη. |
| [getID()](#getID--) | Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο. |
| [getIcon()](#getIcon--) | Καθορίζει ένα εικονίδιο δυαδικού τύπου κωδικοποιημένο με MIME (Multipurpose Internet Mail Extensions) (σε μορφή .ico) για ένα στοιχείο Master ή MasterShortcut σε ένα έγγραφο. |
| [getIconSize()](#getIconSize--) | Το μέγεθος του εικονιδίου του στοιχείου. |
| [getIconUpdate()](#getIconUpdate--) | Καθορίζει εάν το εικονίδιο δημιουργείται αυτόματα από το ίδιο το master. |
| [getMatchByName()](#getMatchByName--) | Το χαρακτηριστικό MatchByName καθορίζει πώς το Microsoft Visio αποφασίζει εάν υπάρχει ήδη ένα master εγγράφου όταν μια παρουσία ενός master τοποθετείται στη σελίδα σχεδίασης. |
| [getName()](#getName--) | Το όνομα του στοιχείου. |
| [getNameU()](#getNameU--) | Το καθολικό όνομα του στοιχείου. |
| [getPageSheet()](#getPageSheet--) | Περιέχει στοιχεία που ορίζουν το φύλλο σελίδας για ένα στοιχείο Σελίδα ή Κύριο. |
| [getPatternFlags()](#getPatternFlags--) | Το χαρακτηριστικό PatternFlags καθορίζει εάν ένα master λειτουργεί ως προσαρμοσμένο μοτίβο. |
| [getPrompt()](#getPrompt--) | Η γραμμή κατάστασης και η υπόδειξη εργαλείου για το στοιχείο. |
| [getShapes()](#getShapes--) | Συλλογή αντικειμένων Shape. |
| [getUniqueID()](#getUniqueID--) | Ένα GUID που αναγνωρίζει το master μέσα στο έγγραφο. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


Κατασκευαστής.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Δημιουργεί βαθιά αντιγραφή αυτής της παρουσίας.

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


Εκτελεί εργασίες που ορίζονται από την εφαρμογή, σχετικές με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


Καθορίζει εάν το κείμενο του master στο παράθυρο πρότυπου είναι ευθυγραμμισμένο αριστερά, δεξιά ή κεντρικά.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


Ένα GUID (καθολικά μοναδικό αναγνωριστικό) που ταυτοποιεί το master σε όλα τα έγγραφα.

**Returns:**
java.util.UUID
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


Περιέχει ένα στοιχείο Connect για κάθε σύνδεση μεταξύ δύο σχημάτων σε ένα σχέδιο.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


Καθορίζει εάν το master είναι κρυφό στη διεπαφή χρήστη.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Το μοναδικό ID του στοιχείου μέσα στο γονικό του στοιχείο.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


Καθορίζει ένα εικονίδιο δυαδικού τύπου κωδικοποιημένο με MIME (Multipurpose Internet Mail Extensions) (σε μορφή .ico) για ένα στοιχείο Master ή MasterShortcut σε ένα έγγραφο.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


Το μέγεθος του εικονιδίου του στοιχείου.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


Καθορίζει εάν το εικονίδιο δημιουργείται αυτόματα από το ίδιο το master.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


Το χαρακτηριστικό MatchByName καθορίζει πώς το Microsoft Visio αποφασίζει αν ένα master εγγράφου υπάρχει ήδη όταν μια παρουσία ενός master τοποθετείται στη σελίδα σχεδίασης. Επιτρέπει τις αλλαγές που γίνονται σε ένα master εγγράφου να εφαρμόζονται σε νέες παρουσίες του master, ακόμη και αν οι παρουσίες σύρονται από ένα αυτόνομο αρχείο στένσιλ.

**Returns:**
int
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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Περιέχει στοιχεία που ορίζουν το φύλλο σελίδας για ένα στοιχείο Σελίδα ή Κύριο.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


Το χαρακτηριστικό PatternFlags καθορίζει εάν ένα master λειτουργεί ως προσαρμοσμένο μοτίβο.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


Η γραμμή κατάστασης και η υπόδειξη εργαλείου για το στοιχείο.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Συλλογή αντικειμένων Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


Ένα GUID που αναγνωρίζει το master μέσα στο έγγραφο.

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

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

