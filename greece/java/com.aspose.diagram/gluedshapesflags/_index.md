---
title: GluedShapesFlags
second_title: Αναφορά API του Aspose.Diagram για Java
description: Specifies constants that identify which shapes to return based on the dimensionality and directionality of the connection points that are glued to a particular shape passed to the Shape.GluedShapes method.
type: docs
weight: 176
url: /el/java/com.aspose.diagram/gluedshapesflags/
---

**Inheritance:**
java.lang.Object
```
public final class GluedShapesFlags
```

Καθορίζει σταθερές που προσδιορίζουν ποια σχήματα να επιστραφούν, βάσει της διαστατικότητας και κατευθυντικότητας των σημείων σύνδεσης που είναι κολλημένα σε ένα συγκεκριμένο σχήμα· περνιούνται στη μέθοδο Shape.GluedShapes.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [GLUED_SHAPES_ALL_1_D](#GLUED-SHAPES-ALL-1-D) | Return IDs of all 1-D shapes that are glued to this shape. |
| [GLUED_SHAPES_ALL_2_D](#GLUED-SHAPES-ALL-2-D) | Return all 2-D shapes that are glued to this shape and all 2-D shapes to which this shape is glued. |
| [GLUED_SHAPES_INCOMING_1_D](#GLUED-SHAPES-INCOMING-1-D) | Return IDs of 1-D shapes whose end points are glued to this shape. |
| [GLUED_SHAPES_INCOMING_2_D](#GLUED-SHAPES-INCOMING-2-D) | If the source object is a 1-D shape, return IDs of 2-D shape to which the begin point is glued. |
| [GLUED_SHAPES_OUTGOING_1_D](#GLUED-SHAPES-OUTGOING-1-D) | Επιστρέψτε IDs των 1-D σχημάτων των οποίων τα σημεία έναρξης είναι κολλημένα σε αυτό το σχήμα. |
| [GLUED_SHAPES_OUTGOING_2_D](#GLUED-SHAPES-OUTGOING-2-D) | Εάν το αντικείμενο προέλευσης είναι ένα 1-D σχήμα, επιστρέψτε IDs του 2-D σχήματος στο οποίο το σημείο λήξης είναι κολλημένο. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GLUED_SHAPES_ALL_1_D {#GLUED-SHAPES-ALL-1-D}
```
public static final int GLUED_SHAPES_ALL_1_D
```


Return IDs of all 1-D shapes that are glued to this shape.

### GLUED_SHAPES_ALL_2_D {#GLUED-SHAPES-ALL-2-D}
```
public static final int GLUED_SHAPES_ALL_2_D
```


Return all 2-D shapes that are glued to this shape and all 2-D shapes to which this shape is glued.

### GLUED_SHAPES_INCOMING_1_D {#GLUED-SHAPES-INCOMING-1-D}
```
public static final int GLUED_SHAPES_INCOMING_1_D
```


Return IDs of 1-D shapes whose end points are glued to this shape.

### GLUED_SHAPES_INCOMING_2_D {#GLUED-SHAPES-INCOMING-2-D}
```
public static final int GLUED_SHAPES_INCOMING_2_D
```


Εάν το αντικείμενο προέλευσης είναι ένα 1-D σχήμα, επιστρέψτε IDs του 2-D σχήματος στο οποίο το σημείο έναρξης είναι κολλημένο. Εάν το αντικείμενο προέλευσης είναι ένα 2-D σχήμα, επιστρέψτε IDs των 2-D σχημάτων που είναι κολλημένα σε αυτό το σχήμα.

### GLUED_SHAPES_OUTGOING_1_D {#GLUED-SHAPES-OUTGOING-1-D}
```
public static final int GLUED_SHAPES_OUTGOING_1_D
```


Επιστρέψτε IDs των 1-D σχημάτων των οποίων τα σημεία έναρξης είναι κολλημένα σε αυτό το σχήμα.

### GLUED_SHAPES_OUTGOING_2_D {#GLUED-SHAPES-OUTGOING-2-D}
```
public static final int GLUED_SHAPES_OUTGOING_2_D
```


Εάν το αντικείμενο προέλευσης είναι ένα 1-D σχήμα, επιστρέψτε IDs του 2-D σχήματος στο οποίο το σημείο λήξης είναι κολλημένο. Εάν το αντικείμενο προέλευσης είναι ένα 2-D σχήμα, επιστρέψτε IDs των 2-D σχημάτων στα οποία αυτό το σχήμα είναι κολλημένο.

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

