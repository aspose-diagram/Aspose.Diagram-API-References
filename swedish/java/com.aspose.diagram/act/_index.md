---
title: Act
second_title: Aspose.Diagram för Java API-referens
description: Definierar anpassade kommandonamn som visas i ett objekts snabbmeny och specificerar de åtgärder som kommandona utför.
type: docs
weight: 11
url: /sv/java/com.aspose.diagram/act/
---

**Inheritance:**
java.lang.Object
```
public class Act
```

Definierar anpassade kommandonamn som visas i ett objekts snabbmeny och specificerar de åtgärder som kommandona utför.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Act()](#Act--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Innehåller formeln som ska köras när en användare klickar på kommandonamnet som definierats i motsvarande Menu‑element. |
| [getBeginGroup()](#getBeginGroup--) | Anger om en avgränsare ska infogas i menyn ovanför denna åtgärd. |
| [getButtonFace()](#getButtonFace--) | Den identifierar ikonen som visas bredvid ett objekt i en snabbmeny. |
| [getChecked()](#getChecked--) | Bestämmer om en bockmarkering visas bredvid kommandonamnet i en formes snabbmeny. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getDisabled()](#getDisabled--) | Inaktiverat element avgör om kommandonamnet visas i snabbmenyn. |
| [getFlyoutChild()](#getFlyoutChild--) | Bestämmer om åtgärdsraden är en undermeny till den sista raden ovanför den som inte är ett flyout‑barn. |
| [getID()](#getID--) | Det unika ID:t för elementet inom dess överordnade element. |
| [getIX()](#getIX--) | Det nollbaserade indexet för elementet inom dess föräldraelement. |
| [getInvisible()](#getInvisible--) | Osynligt element indikerar om åtgärden är synlig på smart‑taggen eller snabbmenyn. |
| [getMenu()](#getMenu--) | Specificerar namnet på kommandot som visas i snabbmenyn för en form eller sida. |
| [getName()](#getName--) | Elementets namn. |
| [getNameU()](#getNameU--) | Det universella namnet för elementet. |
| [getReadOnly()](#getReadOnly--) | Bestämmer om åtgärden på en smart‑tagg eller snabbmeny är skrivskyddad. |
| [getSortKey()](#getSortKey--) | Den specificerar ett nummer som bestämmer ordningen på åtgärder som visas i en snabbmeny eller smart‑taggmeny. |
| [getTagName()](#getTagName--) | Den innehåller namnet på smarttaggen som åtgärden är associerad med. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av den här egenskapen, se [getDel()](../../com.aspose.diagram/act\#getDel--) |
| [setID(int value)](#setID-int-) | För beskrivningen av den här egenskapen, se [getID()](../../com.aspose.diagram/act\#getID--) |
| [setIX(int value)](#setIX-int-) | För beskrivningen av den här egenskapen, se [getIX()](../../com.aspose.diagram/act\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | För beskrivningen av den här egenskapen, se [getName()](../../com.aspose.diagram/act\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | För beskrivningen av den här egenskapen, se [getNameU()](../../com.aspose.diagram/act\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Act() {#Act--}
```
public Act()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar en djup kopia av denna instans.

**Returns:**
java.lang.Object -
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAction() {#getAction--}
```
public DoubleValue getAction()
```


Innehåller formeln som ska köras när en användare klickar på kommandonamnet som definierats i motsvarande Menu‑element.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBeginGroup() {#getBeginGroup--}
```
public BoolValue getBeginGroup()
```


Anger om en avgränsare ska infogas i menyn ovanför denna åtgärd.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getButtonFace() {#getButtonFace--}
```
public Str2Value getButtonFace()
```


Den identifierar ikonen som visas bredvid ett objekt i en snabbmeny.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getChecked() {#getChecked--}
```
public BoolValue getChecked()
```


Bestämmer om en bockmarkering visas bredvid kommandonamnet i en formes snabbmeny.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


En flagga som indikerar om elementet har raderats lokalt. Ett värde på 1 indikerar att elementet raderades lokalt.

**Returns:**
int
### getDisabled() {#getDisabled--}
```
public BoolValue getDisabled()
```


Inaktiverat element avgör om kommandonamnet visas i snabbmenyn.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlyoutChild() {#getFlyoutChild--}
```
public BoolValue getFlyoutChild()
```


Bestämmer om åtgärdsraden är en undermeny till den sista raden ovanför den som inte är ett flyout‑barn.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getID() {#getID--}
```
public int getID()
```


Det unika ID:t för elementet inom dess överordnade element.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


Det nollbaserade indexet för elementet inom dess föräldraelement.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Osynligt element indikerar om åtgärden är synlig på smart‑taggen eller snabbmenyn.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getMenu() {#getMenu--}
```
public Str2Value getMenu()
```


Specificerar namnet på kommandot som visas i snabbmenyn för en form eller sida.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getName() {#getName--}
```
public String getName()
```


Elementets namn.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


Det universella namnet för elementet.

**Returns:**
java.lang.String
### getReadOnly() {#getReadOnly--}
```
public BoolValue getReadOnly()
```


Bestämmer om åtgärden på en smart‑tagg eller snabbmeny är skrivskyddad.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Den specificerar ett nummer som bestämmer ordningen på åtgärder som visas i en snabbmeny eller smart‑taggmeny.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getTagName() {#getTagName--}
```
public Str2Value getTagName()
```


Den innehåller namnet på smarttaggen som åtgärden är associerad med.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


För beskrivningen av den här egenskapen, se [getDel()](../../com.aspose.diagram/act\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


För beskrivningen av den här egenskapen, se [getID()](../../com.aspose.diagram/act\#getID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


För beskrivningen av den här egenskapen, se [getIX()](../../com.aspose.diagram/act\#getIX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


För beskrivningen av den här egenskapen, se [getName()](../../com.aspose.diagram/act\#getName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


För beskrivningen av den här egenskapen, se [getNameU()](../../com.aspose.diagram/act\#getNameU--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

