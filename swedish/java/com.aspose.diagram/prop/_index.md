---
title: Egenskap
second_title: Aspose.Diagram för Java API-referens
description: Innehåller element för att definiera anpassade egenskaper och element för att associera data med en form.
type: docs
weight: 309
url: /sv/java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

Innehåller element för att definiera anpassade egenskaper och element för att associera data med en form.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Prop()](#Prop--) | Konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone()](#deepClone--) | Skapar en djup kopia av denna instans. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Bestämmer den kalender som används för anpassade egenskaper, textfält och elementformler. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | En flagga som indikerar om elementet har raderats lokalt. |
| [getFormat()](#getFormat--) | Format‑elementet specificerar formateringen av en anpassad egenskap som är en sträng, fast lista, nummer, variabel lista, datum eller tid, varaktighet eller valuta. |
| [getID()](#getID--) | Det unika ID:t för elementet inom dess överordnade element. |
| [getIX()](#getIX--) | Det nollbaserade indexet för elementet inom dess föräldraelement. |
| [getInvisible()](#getInvisible--) | Osynligt element specificerar om den anpassade egenskapen är synlig i dialogrutan Anpassade egenskaper i Microsoft Visio. |
| [getLabel()](#getLabel--) | Specificerar etiketten som visas för användare i dialogrutan Anpassade egenskaper. |
| [getLangID()](#getLangID--) | Anger språk‑ID (LCID) för det språk som cellformeln, texten, den anpassade egenskapen eller kommentaren angavs i. |
| [getName()](#getName--) | Elementets namn. |
| [getNameU()](#getNameU--) | Det universella namnet för elementet. |
| [getPrompt()](#getPrompt--) | Prompt‑elementet specificerar beskrivande eller instruktiv text som visas för användare i dialogrutan Anpassade egenskaper när egenskapen är markerad. |
| [getSortKey()](#getSortKey--) | Det specificerar en nyckel som bestämmer i vilken ordning anpassade egenskaper listas i programmets användargränssnitt. |
| [getType()](#getType--) | Typ anger en datatyp för det anpassade egenskapsvärdet. |
| [getValue()](#getValue--) | Innehåller lösningsspecifik, välformad XML-data som har ett prefix i ett explicit namnrymd och lagras med ett dokument. |
| [getVerify()](#getVerify--) | Specificerar om användaren frågas att ange information för en anpassad egenskap för en form när en instans skapas eller formen dupliceras eller kopieras. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/prop\#getDel--) |
| [setID(int value)](#setID-int-) | För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/prop\#getID--) |
| [setIX(int value)](#setIX-int-) | För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/prop\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/prop\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/prop\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


Konstruktor.

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


Skapar en djup kopia av denna instans.

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Bestämmer den kalender som används för anpassade egenskaper, textfält och elementformler.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
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
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


Format-elementet specificerar formateringen av en anpassad egenskap som är en sträng, fast lista, tal, variabel lista, datum eller tid, varaktighet eller valuta. Den anpassade egenskapstypen specificeras i motsvarande Type-element.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
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


Osynligt element specificerar om den anpassade egenskapen är synlig i dialogrutan Anpassade egenskaper i Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


Specificerar etiketten som visas för användare i dialogrutan Anpassade egenskaper.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Anger språk‑ID (LCID) för det språk som cellformeln, texten, den anpassade egenskapen eller kommentaren angavs i.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Prompt-elementet specificerar beskrivande eller instruktiv text som visas för användare i dialogrutan Anpassade egenskaper när egenskapen är markerad. Denna text visas också som verktygstips när muspekaren hålls över egenskapen i fönstret Anpassade egenskaper.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Det specificerar en nyckel som bestämmer i vilken ordning anpassade egenskaper listas i programmets användargränssnitt.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Typ anger en datatyp för det anpassade egenskapsvärdet.

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


Innehåller lösningsspecifik, välformad XML-data som har ett prefix i ett explicit namnrymd och lagras med ett dokument.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


Specificerar om användaren frågas att ange information för en anpassad egenskap för en form när en instans skapas eller formen dupliceras eller kopieras.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


För beskrivningen av denna egenskap, se [getDel()](../../com.aspose.diagram/prop\#getDel--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


För beskrivningen av denna egenskap, se [getID()](../../com.aspose.diagram/prop\#getID--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


För beskrivningen av denna egenskap, se [getIX()](../../com.aspose.diagram/prop\#getIX--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


För beskrivningen av denna egenskap, se [getName()](../../com.aspose.diagram/prop\#getName--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


För beskrivningen av denna egenskap, se [getNameU()](../../com.aspose.diagram/prop\#getNameU--)

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

