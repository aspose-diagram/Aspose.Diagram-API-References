---
title: CollectionBase
second_title: Αναφορά API του Aspose.Diagram για Java
description: Παρέχει την αφηρημένη βασική κλάση για μια συλλογή με ισχυρό τύπο.
type: docs
weight: 50
url: /el/java/com.aspose.diagram/collectionbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class CollectionBase implements Iterable
```

Παρέχει την αφηρημένη βασική κλάση για μια συλλογή με ισχυρό τύπο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CollectionBase()](#CollectionBase--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης CollectionBase με την προεπιλεγμένη αρχική χωρητικότητα. |
| [CollectionBase(int capacity)](#CollectionBase-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης CollectionBase με την καθορισμένη χωρητικότητα. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | Προσθέτει ένα στοιχείο στο αντικείμενο CollectionBase. |
| [clear()](#clear--) | Αφαιρεί όλα τα αντικείμενα από το αντικείμενο CollectionBase. |
| [contains(Object o)](#contains-java.lang.Object-) | Επιστρέφει αν η παρουσία περιέχει αυτό το αντικείμενο. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Λάβετε ένα στοιχείο στη συγκεκριμένη θέση. |
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
### CollectionBase() {#CollectionBase--}
```
public CollectionBase()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης CollectionBase με την προεπιλεγμένη αρχική χωρητικότητα.

### CollectionBase(int capacity) {#CollectionBase-int-}
```
public CollectionBase(int capacity)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης CollectionBase με την καθορισμένη χωρητικότητα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| χωρητικότητα | int | Ο αριθμός των στοιχείων που η νέα λίστα μπορεί αρχικά να αποθηκεύσει. |

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
### get(int index) {#get-int-}
```
public Object get(int index)
```


Λάβετε ένα στοιχείο στη συγκεκριμένη θέση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Δείκτης καθορισμένης θέσης. |

**Returns:**
java.lang.Object - Το στοιχείο στη καθορισμένη θέση.
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

