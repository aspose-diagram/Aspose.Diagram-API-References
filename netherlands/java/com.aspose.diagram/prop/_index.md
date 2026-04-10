---
title: Eigenschap
second_title: Aspose.Diagram voor Java API-referentie
description: Bevat elementen voor het definiëren van aangepaste eigenschappen en elementen voor het koppelen van gegevens aan een vorm.
type: docs
weight: 309
url: /nl/java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

Bevat elementen voor het definiëren van aangepaste eigenschappen en elementen voor het koppelen van gegevens aan een vorm.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Prop()](#Prop--) | Constructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [deepClone()](#deepClone--) | Maakt een diepe kopie van deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | Bepaalt de kalender die wordt gebruikt voor aangepaste eigenschappen, tekstvelden en elementformules. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | Een vlag die aangeeft of het element lokaal is verwijderd. |
| [getFormat()](#getFormat--) | Format-element specificeert de opmaak van een aangepaste eigenschap die een tekenreeks, vaste lijst, getal, variabele lijst, datum of tijd, duur of valuta is. |
| [getID()](#getID--) | De unieke ID van het element binnen het bovenliggende element. |
| [getIX()](#getIX--) | De nulgebaseerde index van het element binnen zijn bovenliggende element. |
| [getInvisible()](#getInvisible--) | Onzichtbaar element specificeert of de aangepaste eigenschap zichtbaar is in het dialoogvenster Aangepaste eigenschappen in Microsoft Visio. |
| [getLabel()](#getLabel--) | Specificeert het label dat aan gebruikers wordt getoond in het dialoogvenster Aangepaste eigenschappen. |
| [getLangID()](#getLangID--) | Geeft de locale‑ID (LCID) aan van de taal waarin de cel‑formule, tekst, aangepaste eigenschap of commentaar is ingevoerd. |
| [getName()](#getName--) | De naam van het element. |
| [getNameU()](#getNameU--) | De universele naam van het element. |
| [getPrompt()](#getPrompt--) | Prompt-element specificeert beschrijvende of instructieve tekst die aan gebruikers wordt getoond in het dialoogvenster Aangepaste eigenschappen wanneer de eigenschap is geselecteerd. |
| [getSortKey()](#getSortKey--) | Het specificeert een sleutel die de volgorde bepaalt waarin aangepaste eigenschappen worden weergegeven in de gebruikersinterface van de applicatie. |
| [getType()](#getType--) | Type specificeert een gegevenstype voor de waarde van de aangepaste eigenschap. |
| [getValue()](#getValue--) | Bevat oplossingsspecifieke, goed gevormde XML-gegevens die zijn geprefixt in een expliciete namespace en worden opgeslagen met een document. |
| [getVerify()](#getVerify--) | Specificeert of de gebruiker wordt gevraagd aangepaste eigenschapsinformatie in te voeren voor een vorm wanneer een instantie wordt gemaakt of de vorm wordt gedupliceerd of gekopieerd. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/prop\#getDel--) |
| [setID(int value)](#setID-int-) | Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/prop\#getID--) |
| [setIX(int value)](#setIX-int-) | Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/prop\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/prop\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/prop\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


Constructor.

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


Maakt een diepe kopie van deze instantie.

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


Bepaalt de kalender die wordt gebruikt voor aangepaste eigenschappen, tekstvelden en elementformules.

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


Een vlag die aangeeft of het element lokaal is verwijderd. Een waarde van 1 geeft aan dat het element lokaal is verwijderd.

**Returns:**
int
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


Het Format‑element specificeert de opmaak van een aangepaste eigenschap die een tekenreeks, vaste lijst, getal, variabele lijst, datum of tijd, duur of valuta is. Het type van de aangepaste eigenschap wordt gespecificeerd in het overeenkomstige Type‑element.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getID() {#getID--}
```
public int getID()
```


De unieke ID van het element binnen het bovenliggende element.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


De nulgebaseerde index van het element binnen zijn bovenliggende element.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Onzichtbaar element specificeert of de aangepaste eigenschap zichtbaar is in het dialoogvenster Aangepaste eigenschappen in Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


Specificeert het label dat aan gebruikers wordt getoond in het dialoogvenster Aangepaste eigenschappen.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


Geeft de locale‑ID (LCID) aan van de taal waarin de cel‑formule, tekst, aangepaste eigenschap of commentaar is ingevoerd.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getName() {#getName--}
```
public String getName()
```


De naam van het element.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


De universele naam van het element.

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Het Prompt‑element specificeert beschrijvende of instructieve tekst die aan gebruikers wordt getoond in het dialoogvenster Aangepaste eigenschappen wanneer de eigenschap is geselecteerd. Deze tekst verschijnt ook als een tooltip wanneer de muisaanwijzer boven de eigenschap wordt gehouden in het venster Aangepaste eigenschappen.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Het specificeert een sleutel die de volgorde bepaalt waarin aangepaste eigenschappen worden weergegeven in de gebruikersinterface van de applicatie.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Type specificeert een gegevenstype voor de waarde van de aangepaste eigenschap.

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


Bevat oplossingsspecifieke, goed gevormde XML-gegevens die zijn geprefixt in een expliciete namespace en worden opgeslagen met een document.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


Specificeert of de gebruiker wordt gevraagd aangepaste eigenschapsinformatie in te voeren voor een vorm wanneer een instantie wordt gemaakt of de vorm wordt gedupliceerd of gekopieerd.

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


Voor de beschrijving van deze eigenschap, zie [getDel()](../../com.aspose.diagram/prop\#getDel--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


Voor de beschrijving van deze eigenschap, zie [getID()](../../com.aspose.diagram/prop\#getID--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


Voor de beschrijving van deze eigenschap, zie [getIX()](../../com.aspose.diagram/prop\#getIX--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Voor de beschrijving van deze eigenschap, zie [getName()](../../com.aspose.diagram/prop\#getName--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


Voor de beschrijving van deze eigenschap, zie [getNameU()](../../com.aspose.diagram/prop\#getNameU--)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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

