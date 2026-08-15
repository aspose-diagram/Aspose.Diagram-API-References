---
title: DocumentProperties
second_title: Aspose.Diagram för Java API-referens
description: Innehåller dokumentegenskapselement såsom dokumentets titel, författare och så vidare.
type: docs
weight: 125
url: /sv/java/com.aspose.diagram/documentproperties/
---

**Inheritance:**
java.lang.Object
```
public class DocumentProperties
```

Innehåller element för dokumentegenskaper såsom dokumentets titel, författare osv.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlternateNames()](#getAlternateNames--) | Anger alternativa namn för ett dokument. |
| [getBuildNumberCreated()](#getBuildNumberCreated--) | Innehåller det fullständiga byggnumret för den instans som användes för att skapa dokumentet. |
| [getBuildNumberEdited()](#getBuildNumberEdited--) | Innehåller byggnumret för den instans som senast användes för att redigera dokumentet. |
| [getCategory()](#getCategory--) | Anger den beskrivande texten för ritningstypen, såsom flödesschema eller kontorslayout. |
| [getClass()](#getClass--) |  |
| [getCompany()](#getCompany--) | Innehåller användarinmatad information som identifierar företaget som skapar ritningen eller företaget som ritningen skapas för. |
| [getCreator()](#getCreator--) | Identifierar vem som skapade eller senast uppdaterade filen. |
| [getCustomProps()](#getCustomProps--) | Samling av CustomProp. |
| [getDesc()](#getDesc--) | Innehåller en beskrivande textsträng för ett dokument. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Innehåller sökvägen som ska användas för relativa hyperlänkar (hyperlänkar där den länkade filens plats beskrivs i förhållande till Microsoft Visio-diagrammet). |
| [getKeywords()](#getKeywords--) | Innehåller en textsträng som identifierar ämnen eller annan viktig information om filen, såsom projektnamn, kundnamn eller versionsnummer. |
| [getLanguage()](#getLanguage--) | Anger språket |
| [getManager()](#getManager--) | Innehåller en användarinskriven textsträng som identifierar den ansvariga för projektet eller avdelningen. |
| [getPreviewPicture()](#getPreviewPicture--) | Innehåller en metafilström som fungerar som en förhandsgranskning av dokumentet. |
| [getSubject()](#getSubject--) | Innehåller en användardefinierad textsträng som beskriver dokumentets innehåll. |
| [getTemplate()](#getTemplate--) | Innehåller ett strängvärde som anger filnamnet på mallen som dokumentet skapades från. |
| [getTimeCreated()](#getTimeCreated--) | Innehåller datum- och tidsvärde som anger när dokumentet skapades. |
| [getTimeEdited()](#getTimeEdited--) | Innehåller datum- och tidsvärde som anger när dokumentet senast redigerades. |
| [getTimePrinted()](#getTimePrinted--) | Innehåller datum- och tidsvärde som anger när dokumentet senast skrevs ut. |
| [getTimeSaved()](#getTimeSaved--) | Innehåller datum- och tidsvärde som anger när dokumentet senast sparades. |
| [getTitle()](#getTitle--) | Innehåller en användardefinierad textsträng som fungerar som en beskrivande titel för dokumentet. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlternateNames(String value)](#setAlternateNames-java.lang.String-) | För beskrivningen av denna egenskap, se [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--) |
| [setBuildNumberCreated(String value)](#setBuildNumberCreated-java.lang.String-) | För beskrivningen av denna egenskap, se [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--) |
| [setBuildNumberEdited(String value)](#setBuildNumberEdited-java.lang.String-) | För beskrivningen av denna egenskap, se [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--) |
| [setCategory(String value)](#setCategory-java.lang.String-) | För beskrivningen av denna egenskap, se [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--) |
| [setCompany(String value)](#setCompany-java.lang.String-) | För beskrivningen av denna egenskap, se [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--) |
| [setCreator(String value)](#setCreator-java.lang.String-) | För beskrivningen av denna egenskap, se [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--) |
| [setDesc(String value)](#setDesc-java.lang.String-) | För beskrivningen av denna egenskap, se [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--) |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | För beskrivningen av denna egenskap, se [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--) |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | För beskrivningen av denna egenskap, se [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--) |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | För beskrivningen av denna egenskap, se [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--) |
| [setManager(String value)](#setManager-java.lang.String-) | För beskrivningen av denna egenskap, se [getManager()](../../com.aspose.diagram/documentproperties\#getManager--) |
| [setPreviewPicture(byte[] value)](#setPreviewPicture-byte---) | För beskrivningen av denna egenskap, se [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--) |
| [setSubject(String value)](#setSubject-java.lang.String-) | För beskrivningen av denna egenskap, se [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--) |
| [setTemplate(String value)](#setTemplate-java.lang.String-) | För beskrivningen av denna egenskap, se [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--) |
| [setTimeCreated(DateTime value)](#setTimeCreated-com.aspose.diagram.DateTime-) | För beskrivningen av denna egenskap, se [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--) |
| [setTimeEdited(DateTime value)](#setTimeEdited-com.aspose.diagram.DateTime-) | För beskrivningen av denna egenskap, se [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--) |
| [setTimePrinted(DateTime value)](#setTimePrinted-com.aspose.diagram.DateTime-) | För beskrivningen av denna egenskap, se [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--) |
| [setTimeSaved(DateTime value)](#setTimeSaved-com.aspose.diagram.DateTime-) | För beskrivningen av denna egenskap, se [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | För beskrivningen av denna egenskap, se [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAlternateNames() {#getAlternateNames--}
```
public String getAlternateNames()
```


Anger alternativa namn för ett dokument.

**Returns:**
java.lang.String
### getBuildNumberCreated() {#getBuildNumberCreated--}
```
public String getBuildNumberCreated()
```


Innehåller det fullständiga byggnumret för den instans som användes för att skapa dokumentet.

**Returns:**
java.lang.String
### getBuildNumberEdited() {#getBuildNumberEdited--}
```
public String getBuildNumberEdited()
```


Innehåller byggnumret för den instans som senast användes för att redigera dokumentet.

**Returns:**
java.lang.String
### getCategory() {#getCategory--}
```
public String getCategory()
```


Anger den beskrivande texten för ritningstypen, t.ex. flödesschema eller kontorslayout. Denna text kan också anges i Microsoft Visio-användargränssnittet i Kategori-rutan i dialogrutan Egenskaper.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompany() {#getCompany--}
```
public String getCompany()
```


Innehåller användarinskriven information som identifierar företaget som skapar ritningen eller företaget som ritningen skapas för. Maxlängden är 63 tecken.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


Identifierar vem som skapade eller senast uppdaterade filen. Maxlängden är 63 tecken.

**Returns:**
java.lang.String
### getCustomProps() {#getCustomProps--}
```
public CustomPropCollection getCustomProps()
```


Samling av CustomProp.

**Returns:**
[CustomPropCollection](../../com.aspose.diagram/custompropcollection)
### getDesc() {#getDesc--}
```
public String getDesc()
```


Innehåller en beskrivande textsträng för ett dokument. Använd detta element för att lagra viktig information om dokumentet, såsom dess syfte, senaste ändringar eller pågående ändringar. Maxlängden är 191 tecken.

**Returns:**
java.lang.String
### getHyperlinkBase() {#getHyperlinkBase--}
```
public String getHyperlinkBase()
```


Innehåller sökvägen som ska användas för relativa hyperlänkar (hyperlänkar där den länkade filens plats beskrivs i förhållande till Microsoft Visio-diagrammet). Som standard är en hyperlänksökväg relativ till det aktuella dokumentet om inte en annan sökväg anges i detta element. Maxlängden är 256 tecken.

**Returns:**
java.lang.String
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Innehåller en textsträng som identifierar ämnen eller annan viktig information om filen, såsom projektnamn, kundnamn eller versionsnummer. Maxlängden på strängen är 63 tecken.

**Returns:**
java.lang.String
### getLanguage() {#getLanguage--}
```
public String getLanguage()
```


Anger språket

```
setLanguage("en-GB");
         setLanguage("en-US");
```

**Returns:**
java.lang.String
### getManager() {#getManager--}
```
public String getManager()
```


Innehåller en användarinskriven textsträng som identifierar den ansvariga personen för projektet eller avdelningen. Maxlängden är 63 tecken.

**Returns:**
java.lang.String
### getPreviewPicture() {#getPreviewPicture--}
```
public byte[] getPreviewPicture()
```


Innehåller en metafilström som fungerar som en förhandsgranskning av dokumentet.

**Returns:**
byte[]
### getSubject() {#getSubject--}
```
public String getSubject()
```


Innehåller en användardefinierad textsträng som beskriver dokumentets innehåll. Maxlängden är 63 tecken.

**Returns:**
java.lang.String
### getTemplate() {#getTemplate--}
```
public String getTemplate()
```


Innehåller ett strängvärde som anger filnamnet på mallen som dokumentet skapades från.

**Returns:**
java.lang.String
### getTimeCreated() {#getTimeCreated--}
```
public DateTime getTimeCreated()
```


Innehåller datum- och tidsvärde som anger när dokumentet skapades.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeEdited() {#getTimeEdited--}
```
public DateTime getTimeEdited()
```


Innehåller datum- och tidsvärde som anger när dokumentet senast redigerades.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimePrinted() {#getTimePrinted--}
```
public DateTime getTimePrinted()
```


Innehåller datum- och tidsvärde som anger när dokumentet senast skrevs ut.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeSaved() {#getTimeSaved--}
```
public DateTime getTimeSaved()
```


Innehåller datum- och tidsvärde som anger när dokumentet senast sparades.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTitle() {#getTitle--}
```
public String getTitle()
```


Innehåller en användardefinierad textsträng som fungerar som en beskrivande titel för dokumentet. Maxlängden är 63 tecken.

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




### setAlternateNames(String value) {#setAlternateNames-java.lang.String-}
```
public void setAlternateNames(String value)
```


För beskrivningen av denna egenskap, se [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setBuildNumberCreated(String value) {#setBuildNumberCreated-java.lang.String-}
```
public void setBuildNumberCreated(String value)
```


För beskrivningen av denna egenskap, se [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setBuildNumberEdited(String value) {#setBuildNumberEdited-java.lang.String-}
```
public void setBuildNumberEdited(String value)
```


För beskrivningen av denna egenskap, se [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setCategory(String value) {#setCategory-java.lang.String-}
```
public void setCategory(String value)
```


För beskrivningen av denna egenskap, se [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setCompany(String value) {#setCompany-java.lang.String-}
```
public void setCompany(String value)
```


För beskrivningen av denna egenskap, se [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


För beskrivningen av denna egenskap, se [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDesc(String value) {#setDesc-java.lang.String-}
```
public void setDesc(String value)
```


För beskrivningen av denna egenskap, se [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public void setHyperlinkBase(String value)
```


För beskrivningen av denna egenskap, se [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


För beskrivningen av denna egenskap, se [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public void setLanguage(String value)
```


För beskrivningen av denna egenskap, se [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setManager(String value) {#setManager-java.lang.String-}
```
public void setManager(String value)
```


För beskrivningen av denna egenskap, se [getManager()](../../com.aspose.diagram/documentproperties\#getManager--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPreviewPicture(byte[] value) {#setPreviewPicture-byte---}
```
public void setPreviewPicture(byte[] value)
```


För beskrivningen av denna egenskap, se [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


För beskrivningen av denna egenskap, se [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setTemplate(String value) {#setTemplate-java.lang.String-}
```
public void setTemplate(String value)
```


För beskrivningen av denna egenskap, se [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setTimeCreated(DateTime value) {#setTimeCreated-com.aspose.diagram.DateTime-}
```
public void setTimeCreated(DateTime value)
```


För beskrivningen av denna egenskap, se [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeEdited(DateTime value) {#setTimeEdited-com.aspose.diagram.DateTime-}
```
public void setTimeEdited(DateTime value)
```


För beskrivningen av denna egenskap, se [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePrinted(DateTime value) {#setTimePrinted-com.aspose.diagram.DateTime-}
```
public void setTimePrinted(DateTime value)
```


För beskrivningen av denna egenskap, se [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeSaved(DateTime value) {#setTimeSaved-com.aspose.diagram.DateTime-}
```
public void setTimeSaved(DateTime value)
```


För beskrivningen av denna egenskap, se [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


För beskrivningen av denna egenskap, se [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--)

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

