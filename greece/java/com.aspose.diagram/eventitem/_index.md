---
title: EventItem
second_title: Αναφορά API του Aspose.Diagram για Java
description: Ενσωματώνει έναν κώδικα γεγονότος.
type: docs
weight: 145
url: /el/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

Περιέχει έναν κωδικό συμβάντος. Ένα στοιχείο EventItem μπορεί να ενεργοποιήσει δύο είδη ενεργειών: μπορεί να εκτελέσει ένα πρόσθετο ή να στείλει μια ειδοποίηση του συμβάντος στο πρόγραμμα που το καλεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [EventItem()](#EventItem--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Καθορίζει τον κωδικό ενέργειας του γονικού στοιχείου EventItem. Για να αποθηκευτεί ένα στοιχείο EventItem σε αρχείο DatadiagramML, πρέπει να είναι διατηρήσιμο. |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | Αντιπροσωπεύει μια σημαία που υποδεικνύει εάν το συμβάν είναι ενεργοποιημένο ή απενεργοποιημένο. |
| [getEventCode()](#getEventCode--) | Ένας κωδικός που υποδεικνύει το συμβάν που ενεργοποιεί το πρόσθετο. |
| [getID()](#getID--) | Το αναγνωριστικό (ID) του συμβάντος. |
| [getTarget()](#getTarget--) | Καθορίζει τον προορισμό ενός συμβάντος. |
| [getTargetArgs()](#getTargetArgs--) | Καθορίζει μια συμβολοσειρά που περιέχει επιχειρήματα προς αποστολή στον προορισμό ενός συμβάντος. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
```


Κατασκευαστής.

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
### getAction() {#getAction--}
```
public int getAction()
```


Καθορίζει τον κωδικό ενέργειας του γονικού στοιχείου EventItem. Για να αποθηκευτεί ένα στοιχείο EventItem σε αρχείο DatadiagramML, πρέπει να είναι διατηρήσιμο. Προς το παρόν, ο μοναδικός έγκυρος κωδικός ενέργειας που μπορεί να έχει ένα διατηρήσιμο συμβάν είναι 1 (ONEVENT_ACT_RUNADDON).

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnabled() {#getEnabled--}
```
public int getEnabled()
```


Αντιπροσωπεύει μια σημαία που υποδεικνύει εάν το συμβάν είναι ενεργοποιημένο ή απενεργοποιημένο.

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


Ένας κωδικός που υποδεικνύει το συμβάν που ενεργοποιεί το πρόσθετο. Για περισσότερες πληροφορίες σχετικά με τους κωδικούς συμβάντων, δείτε τους Κωδικούς Συμβάντων στην Αναφορά Αυτοματοποίησης του Microsoft Visio 2007.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


Το αναγνωριστικό (ID) του συμβάντος.

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


Καθορίζει τον προορισμό ενός συμβάντος.

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


Καθορίζει μια συμβολοσειρά που περιέχει επιχειρήματα προς αποστολή στον προορισμό ενός συμβάντος.

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




### setAction(int value) {#setAction-int-}
```
public void setAction(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

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

