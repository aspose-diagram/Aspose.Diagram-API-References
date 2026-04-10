---
title: CollectionBase
second_title: Aspose.Diagram voor Java API-referentie
description: Biedt de abstracte basisklasse voor een sterk getypeerde verzameling.
type: docs
weight: 50
url: /nl/java/com.aspose.diagram/collectionbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class CollectionBase implements Iterable
```

Biedt de abstracte basisklasse voor een sterk getypeerde verzameling.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CollectionBase()](#CollectionBase--) | Initialiseert een nieuw exemplaar van de CollectionBase-klasse met de standaard initiële capaciteit. |
| [CollectionBase(int capacity)](#CollectionBase-int-) | Initialiseert een nieuw exemplaar van de CollectionBase-klasse met de opgegeven capaciteit. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | Voegt een item toe aan de CollectionBase-instantie. |
| [clear()](#clear--) | Verwijdert alle objecten uit de CollectionBase-instantie. |
| [contains(Object o)](#contains-java.lang.Object-) | Geeft terug of de instantie dit object bevat |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | Haal een item op op de opgegeven positie. |
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
### CollectionBase() {#CollectionBase--}
```
public CollectionBase()
```


Initialiseert een nieuw exemplaar van de CollectionBase-klasse met de standaard initiële capaciteit.

### CollectionBase(int capacity) {#CollectionBase-int-}
```
public CollectionBase(int capacity)
```


Initialiseert een nieuw exemplaar van de CollectionBase-klasse met de opgegeven capaciteit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| capaciteit | int | Het aantal elementen dat de nieuwe lijst aanvankelijk kan opslaan. |

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
### get(int index) {#get-int-}
```
public Object get(int index)
```


Haal een item op op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Gespecificeerde positie-index. |

**Returns:**
java.lang.Object - Het item op de gespecificeerde positie.
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

