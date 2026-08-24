---
title: VbaProjectReferenceCollection
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αναπαριστά όλες τις αναφορές του έργου VBA.
type: docs
weight: 435
url: /el/java/com.aspose.diagram/vbaprojectreferencecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.CollectionBase](../../com.aspose.diagram/collectionbase)
```
public class VbaProjectReferenceCollection extends CollectionBase
```

Αναπαριστά όλες τις αναφορές του έργου VBA.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | Προσθέτει ένα στοιχείο στο αντικείμενο CollectionBase. |
| [addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)](#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Προσθέστε μια αναφορά σε μια τροποποιημένη βιβλιοθήκη τύπου και την εκτεταμένη βιβλιοθήκη τύπου της. |
| [addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)](#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-) | Προσθέστε μια αναφορά σε ένα εξωτερικό έργο VBA. |
| [addRegisteredReference(String name, String libid)](#addRegisteredReference-java.lang.String-java.lang.String-) | Προσθέστε μια αναφορά σε μια βιβλιοθήκη τύπου Automation. |
| [clear()](#clear--) | Αφαιρεί όλα τα αντικείμενα από το αντικείμενο CollectionBase. |
| [contains(Object o)](#contains-java.lang.Object-) | Επιστρέφει αν η παρουσία περιέχει αυτό το αντικείμενο. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int i)](#get-int-) | Αποκτήστε την αναφορά στη λίστα με το δείκτη. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται στην παρουσία CollectionBase. |
| [hashCode()](#hashCode--) |  |
| [indexOf(Object o)](#indexOf-java.lang.Object-) | Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου στην παρουσία CollectionBase. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διασχίζει την παρουσία CollectionBase. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Object o) {#add-java.lang.Object-}
```
public int add(Object o)
```


Προσθέτει ένα στοιχείο στο αντικείμενο CollectionBase.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| o | java.lang.Object | Το αντικείμενο προς προσθήκη στην παρουσία CollectionBase. |

**Returns:**
int - Η θέση στην οποία εισήχθη το νέο στοιχείο.
### addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid) {#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public int addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)
```


Προσθέστε μια αναφορά σε μια τροποποιημένη βιβλιοθήκη τύπου και την εκτεταμένη βιβλιοθήκη τύπου της.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String | Το όνομα της αναφοράς. |
| libid | java.lang.String | Το αναγνωριστικό μιας βιβλιοθήκης τύπου Automation. |
| twiddledlibid | java.lang.String | Το αναγνωριστικό μιας τροποποιημένης βιβλιοθήκης τύπου |
| extendedLibid | java.lang.String | The identifier of an extended type library |

**Returns:**
int -
### addProjectRefrernce(String name, String absoluteLibid, String relativeLibid) {#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-}
```
public int addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)
```


Προσθέστε μια αναφορά σε ένα εξωτερικό έργο VBA.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String | Το όνομα της αναφοράς. |
| absoluteLibid | java.lang.String | The referenced VBA project\\u9225\\u6a9a identifier with an absolute path. |
| relativeLibid | java.lang.String | The referenced VBA project\\u9225\\u6a9a identifier with an relative path. |

**Returns:**
int -
### addRegisteredReference(String name, String libid) {#addRegisteredReference-java.lang.String-java.lang.String-}
```
public int addRegisteredReference(String name, String libid)
```


Προσθέστε μια αναφορά σε μια βιβλιοθήκη τύπου Automation.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String | Το όνομα της αναφοράς. |
| libid | java.lang.String | Το αναγνωριστικό μιας βιβλιοθήκης τύπου Automation. |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Αφαιρεί όλα τα αντικείμενα από το αντικείμενο CollectionBase.

### contains(Object o) {#contains-java.lang.Object-}
```
public boolean contains(Object o)
```


Επιστρέφει αν η παρουσία περιέχει αυτό το αντικείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| o | java.lang.Object | αντικείμενο δοκιμής |

**Returns:**
boolean - Εάν το αντίγραφο περιέχει αυτό το αντικείμενο
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
### get(int i) {#get-int-}
```
public VbaProjectReference get(int i)
```


Αποκτήστε την αναφορά στη λίστα με το δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| i | int | The index. |

**Returns:**
[VbaProjectReference](../../com.aspose.diagram/vbaprojectreference) - 
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Λαμβάνει τον αριθμό των στοιχείων που περιέχονται στην παρουσία CollectionBase.

**Returns:**
int - Ο αριθμός των στοιχείων που περιέχονται στο αντίγραφο CollectionBase.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(Object o) {#indexOf-java.lang.Object-}
```
public int indexOf(Object o)
```


Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου στην παρουσία CollectionBase.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| o | java.lang.Object | Καθορίζει το δείκτη ενός συγκεκριμένου στοιχείου στην παρουσία CollectionBase. |

**Returns:**
int - Ο δείκτης της τιμής αν βρεθεί στη λίστα· διαφορετικά, -1.
### iterator() {#iterator--}
```
public Iterator iterator()
```


Επιστρέφει έναν απαριθμητή που διασχίζει την παρουσία CollectionBase.

**Returns:**
java.util.Iterator - Ένας επαναλήπτης για το αντίγραφο CollectionBase.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```


Αφαιρεί το στοιχείο στον καθορισμένο δείκτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Ο δείκτης μηδενικής βάσης του στοιχείου προς αφαίρεση. |

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

