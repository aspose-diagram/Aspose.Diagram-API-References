---
title: IssueTarget
second_title: Αναφορά API του Aspose.Diagram για Java
description: Ανάλογα με τον προορισμό του γονικού ζητήματος επικύρωσης, καθορίζει είτε τη σελίδα είτε τόσο τη σελίδα όσο και το σχήμα με τα οποία σχετίζεται το γονικό ζήτημα επικύρωσης.
type: docs
weight: 210
url: /el/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

Ανάλογα με τον προορισμό του γονικού ζητήματος επικύρωσης, καθορίζει είτε τη σελίδα, είτε τόσο τη σελίδα όσο και το σχήμα, με τα οποία σχετίζεται το γονικό ζήτημα επικύρωσης. Εάν ο προορισμός του γονικού ζητήματος επικύρωσης είναι ένα έγγραφο, το IssueTarget δεν καθορίζει ούτε σελίδα ούτε σχήμα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | Καθορίζει το μοναδικό αναγνωριστικό της σελίδας που σχετίζεται με το γονικό ζήτημα επικύρωσης. |
| [getShapeId()](#getShapeId--) | Καθορίζει το μοναδικό αναγνωριστικό του σχήματος που σχετίζεται με το γονικό ζήτημα επικύρωσης. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--) |
| [setShapeId(long value)](#setShapeId-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IssueTarget(long pageID, long shapeID) {#IssueTarget-long-long-}
```
public IssueTarget(long pageID, long shapeID)
```


Κατασκευαστής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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
### getPageId() {#getPageId--}
```
public long getPageId()
```


Καθορίζει το μοναδικό αναγνωριστικό της σελίδας που σχετίζεται με το γονικό ζήτημα επικύρωσης. Εάν ο προορισμός είναι το έγγραφο, η τιμή PageID μπορεί να είναι 0xFFFFFFFF.

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


Καθορίζει το μοναδικό αναγνωριστικό του σχήματος που σχετίζεται με το γονικό ζήτημα επικύρωσης. Εάν ο προορισμός είναι το έγγραφο ή μια σελίδα, η τιμή ShapeID μπορεί να είναι 0xFFFFFFFF.

**Returns:**
long
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




### setPageId(long value) {#setPageId-long-}
```
public void setPageId(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

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

