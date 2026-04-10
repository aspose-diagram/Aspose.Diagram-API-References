---
title: VbaProjectReferenceCollection
second_title: Aspose.Diagram voor Java API-referentie
description: Stelt alle referenties van het VBA-project voor.
type: docs
weight: 435
url: /nl/java/com.aspose.diagram/vbaprojectreferencecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.CollectionBase](../../com.aspose.diagram/collectionbase)
```
public class VbaProjectReferenceCollection extends CollectionBase
```

Stelt alle referenties van het VBA-project voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | Voegt een item toe aan de CollectionBase-instantie. |
| [addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)](#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Voeg een referentie toe aan een twiddled type library en de bijbehorende uitgebreide type library. |
| [addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)](#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-) | Voeg een referentie toe aan een extern VBA-project. |
| [addRegisteredReference(String name, String libid)](#addRegisteredReference-java.lang.String-java.lang.String-) | Voeg een referentie toe aan een Automation type library. |
| [clear()](#clear--) | Verwijdert alle objecten uit de CollectionBase-instantie. |
| [contains(Object o)](#contains-java.lang.Object-) | Geeft terug of de instantie dit object bevat |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int i)](#get-int-) | Haal de referentie op in de lijst op basis van de index. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Haalt het aantal elementen op dat in de CollectionBase-instantie zit. |
| [hashCode()](#hashCode--) |  |
| [indexOf(Object o)](#indexOf-java.lang.Object-) | Bepaalt de index van een specifiek item in de CollectionBase-instantie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de CollectionBase-instantie iterereert. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het item op de opgegeven index. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Object o) {#add-java.lang.Object-}
```
public int add(Object o)
```


Voegt een item toe aan de CollectionBase-instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| o | java.lang.Object | Het object om toe te voegen aan de CollectionBase-instantie. |

**Returns:**
int - De positie waarin het nieuwe element werd ingevoegd.
### addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid) {#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public int addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)
```


Voeg een referentie toe aan een twiddled type library en de bijbehorende uitgebreide type library.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de referentie. |
| libid | java.lang.String | De identifier van een Automation type library. |
| twiddledlibid | java.lang.String | De identifier van een twiddled type library |
| extendedLibid | java.lang.String | De identifier van een uitgebreide typebibliotheek |

**Returns:**
int -
### addProjectRefrernce(String name, String absoluteLibid, String relativeLibid) {#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-}
```
public int addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)
```


Voeg een referentie toe aan een extern VBA-project.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de referentie. |
| absoluteLibid | java.lang.String | De verwijzende VBA project\u9225\u6a9a identifier met een absoluut pad. |
| relativeLibid | java.lang.String | De verwijzende VBA project\u9225\u6a9a identifier met een relatief pad. |

**Returns:**
int -
### addRegisteredReference(String name, String libid) {#addRegisteredReference-java.lang.String-java.lang.String-}
```
public int addRegisteredReference(String name, String libid)
```


Voeg een referentie toe aan een Automation type library.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van de referentie. |
| libid | java.lang.String | De identifier van een Automation type library. |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


Verwijdert alle objecten uit de CollectionBase-instantie.

### contains(Object o) {#contains-java.lang.Object-}
```
public boolean contains(Object o)
```


Geeft terug of de instantie dit object bevat

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| o | java.lang.Object | testobject |

**Returns:**
boolean - Of de instantie dit object bevat
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int i) {#get-int-}
```
public VbaProjectReference get(int i)
```


Haal de referentie op in de lijst op basis van de index.

**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt het aantal elementen op dat in de CollectionBase-instantie zit.

**Returns:**
int - Het aantal elementen dat in de CollectionBase‑instantie zit.
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


Bepaalt de index van een specifiek item in de CollectionBase-instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| o | java.lang.Object | Bepaalt de index van een specifiek item in de CollectionBase-instantie. |

**Returns:**
int - De index van de waarde als deze in de lijst wordt gevonden; anders -1.
### iterator() {#iterator--}
```
public Iterator iterator()
```


Retourneert een enumerator die door de CollectionBase-instantie iterereert.

**Returns:**
java.util.Iterator - Een iterator voor de CollectionBase‑instantie.
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


Verwijdert het item op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen item. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

