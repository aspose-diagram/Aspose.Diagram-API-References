---
title: Issue
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αναπαριστά ένα μεμονωμένο ζήτημα επικύρωσης στο έγγραφο.
type: docs
weight: 208
url: /el/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

Αναπαριστά ένα μεμονωμένο ζήτημα επικύρωσης στο έγγραφο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Issue()](#Issue--) | Κατασκευαστής |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | Καθορίζει το μοναδικό αναγνωριστικό του ζητήματος επικύρωσης. |
| [getIgnored()](#getIgnored--) | Καθορίζει αν το ζήτημα επικύρωσης αγνοείται επί του παρόντος. |
| [getIssueTarget()](#getIssueTarget--) | Ανάλογα με τον προορισμό του γονικού ζητήματος επικύρωσης, καθορίζει είτε τη σελίδα, είτε τόσο τη σελίδα όσο και το σχήμα, με τα οποία σχετίζεται το γονικό ζήτημα επικύρωσης. |
| [getRuleInfo()](#getRuleInfo--) | Καθορίζει πληροφορίες σχετικά με τον κανόνα επικύρωσης στον οποίο αναφέρεται το γονικό ζήτημα επικύρωσης. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


Κατασκευαστής

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
### getID() {#getID--}
```
public long getID()
```


Καθορίζει το μοναδικό αναγνωριστικό του ζητήματος επικύρωσης.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


Καθορίζει αν το ζήτημα επικύρωσης αγνοείται επί του παρόντος. Η προεπιλογή είναι False.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


Ανάλογα με τον προορισμό του γονικού ζητήματος επικύρωσης, καθορίζει είτε τη σελίδα, είτε τόσο τη σελίδα όσο και το σχήμα, με τα οποία σχετίζεται το γονικό ζήτημα επικύρωσης. Εάν ο προορισμός του γονικού ζητήματος επικύρωσης είναι ένα έγγραφο, το IssueTarget δεν καθορίζει ούτε σελίδα ούτε σχήμα.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


Καθορίζει πληροφορίες σχετικά με τον κανόνα επικύρωσης στον οποίο αναφέρεται το γονικό ζήτημα επικύρωσης.

**Returns:**
[RuleInfo](../../com.aspose.diagram/ruleinfo)
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




### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


Για την περιγραφή αυτής της ιδιότητας, παρακαλώ δείτε [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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

