---
title: MasterCollection
second_title: Αναφορά API του Aspose.Diagram για Java
description: Συλλογή Master.
type: docs
weight: 241
url: /el/java/com.aspose.diagram/mastercollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Collection](../../com.aspose.diagram/collection)
```
public class MasterCollection extends Collection
```

Συλλογή Master.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(Master master)](#add-com.aspose.diagram.Master-) | Προσθέστε το αντικείμενο Master στη συλλογή. |
| [clear()](#clear--) | Removes all elements from collection. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Gets the element at the specified index. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [getMaster(int ID)](#getMaster-int-) | Λαμβάνει το στοιχείο με το καθορισμένο ID. |
| [getMasterByName(String name)](#getMasterByName-java.lang.String-) | Αποκτήστε το master με όνομα. |
| [getMasterShortcuts()](#getMasterShortcuts--) | Συλλογή MasterShortcut. |
| [getMaxRelID()](#getMaxRelID--) | λάβετε το μέγιστο rel id στη συλλογή. |
| [hashCode()](#hashCode--) |  |
| [isExist(int index)](#isExist-int-) | Is exist item in the collection. |
| [isExist(String name)](#isExist-java.lang.String-) | Υπάρχει master στη συλλογή. |
| [isExistRelId(String relID)](#isExistRelId-java.lang.String-) | Υπάρχει rel id του master στη συλλογή. |
| [iterator()](#iterator--) | Υποστηρίζει απλή επανάληψη πάνω σε μια μη γενική συλλογή. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Master master)](#remove-com.aspose.diagram.Master-) | Αφαιρέστε το αντικείμενο Master από τη συλλογή. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Master master) {#add-com.aspose.diagram.Master-}
```
public int add(Master master)
```


Προσθέστε το αντικείμενο Master στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| master | [Master](../../com.aspose.diagram/master) |  |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Removes all elements from collection.

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
public Master get(int index)
```


Gets the element at the specified index.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int |  |

**Returns:**
[Master](../../com.aspose.diagram/master) - 
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


Gets the number of elements actually contained in the collection.

**Returns:**
int
### getMaster(int ID) {#getMaster-int-}
```
public Master getMaster(int ID)
```


Λαμβάνει το στοιχείο με το καθορισμένο ID.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ID | int |  |

**Returns:**
[Master](../../com.aspose.diagram/master) - 
### getMasterByName(String name) {#getMasterByName-java.lang.String-}
```
public Master getMasterByName(String name)
```


Αποκτήστε το master με όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[Master](../../com.aspose.diagram/master) - 
### getMasterShortcuts() {#getMasterShortcuts--}
```
public MasterShortcutCollection getMasterShortcuts()
```


Συλλογή MasterShortcut.

**Returns:**
[MasterShortcutCollection](../../com.aspose.diagram/mastershortcutcollection)
### getMaxRelID() {#getMaxRelID--}
```
public int getMaxRelID()
```


λάβετε το μέγιστο rel id στη συλλογή.

**Returns:**
int -
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExist(int index) {#isExist-int-}
```
public boolean isExist(int index)
```


Is exist item in the collection.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | δείκτης του στοιχείου. |

**Returns:**
boolean -
### isExist(String name) {#isExist-java.lang.String-}
```
public boolean isExist(String name)
```


Υπάρχει master στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
boolean -
### isExistRelId(String relID) {#isExistRelId-java.lang.String-}
```
public boolean isExistRelId(String relID)
```


Υπάρχει rel id του master στη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| relID | java.lang.String |  |

**Returns:**
boolean -
### iterator() {#iterator--}
```
public Iterator iterator()
```


Υποστηρίζει απλή επανάληψη πάνω σε μια μη γενική συλλογή.

**Returns:**
java.util.Iterator -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Master master) {#remove-com.aspose.diagram.Master-}
```
public void remove(Master master)
```


Αφαιρέστε το αντικείμενο Master από τη συλλογή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| master | [Master](../../com.aspose.diagram/master) |  |

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

