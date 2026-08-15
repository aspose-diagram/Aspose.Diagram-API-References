---
title: DateTime
second_title: Aspose.Diagram för Java API-referens
description: Representerar ett ögonblick i tiden som vanligtvis uttrycks som ett datum och en tid på dagen.
type: docs
weight: 115
url: /sv/java/com.aspose.diagram/datetime/
---

**Inheritance:**
java.lang.Object
```
public class DateTime
```

Representerar ett ögonblick i tiden, vanligtvis uttryckt som ett datum och en tid på dagen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DateTime(int year, int month, int day)](#DateTime-int-int-int-) | Initierar en ny instans av DateTime-objektet med det angivna året, månaden och dagen. |
| [DateTime(int year, int month, int day, int hour, int minute, int second)](#DateTime-int-int-int-int-int-int-) | Initierar en ny instans av DateTime-objektet med det angivna året, månaden, dagen, timmen, minuten och sekunden. |
| [DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)](#DateTime-int-int-int-int-int-int-int-) | Initierar en ny instans av DateTime-objektet med det angivna året, månaden, dagen, timmen, minuten, sekunden och millisekunden. |
| [DateTime(Date date)](#DateTime-java.util.Date-) | Initierar en ny instans av DateTime-objektet med det angivna Date-objektet |
| [DateTime(Calendar cld)](#DateTime-java.util.Calendar-) | Initierar en ny instans av DateTime-objektet med det angivna Calendar-objektet |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addDays(double value)](#addDays-double-) | Lägger till det angivna antalet dagar till värdet av den här instansen. |
| [addHours(double value)](#addHours-double-) | Lägger till det angivna antalet timmar till värdet av den här instansen. |
| [addMilliseconds(double value)](#addMilliseconds-double-) | Lägger till det angivna antalet millisekunder till värdet av den här instansen. |
| [addMinutes(double value)](#addMinutes-double-) | Lägger till det angivna antalet minuter till värdet av den här instansen. |
| [addMonths(int months)](#addMonths-int-) | Lägger till det angivna antalet månader till värdet av den här instansen. |
| [addSeconds(double value)](#addSeconds-double-) | Lägger till det angivna antalet sekunder till värdet av den här instansen. |
| [addYears(int value)](#addYears-int-) | Lägger till det angivna antalet år till värdet av den här instansen. |
| [compareTo(DateTime value)](#compareTo-com.aspose.diagram.DateTime-) | Jämför värdet av den här instansen med ett angivet DateTime‑värde och returnerar ett heltal som indikerar om denna instans är tidigare än, samma som eller senare än det angivna DateTime‑värdet. |
| [compareTo(Object value)](#compareTo-java.lang.Object-) | Jämför värdet av den här instansen med ett angivet objekt som innehåller ett angivet DateTime‑värde och returnerar ett heltal som indikerar om denna instans är tidigare än, samma som eller senare än det angivna DateTime‑värdet. |
| [equals(Object value)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om denna instans är lika med ett angivet objekt. |
| [getClass()](#getClass--) |  |
| [getDay()](#getDay--) | Hämtar dagen i månaden som representeras av den här instansen. |
| [getDayOfWeek()](#getDayOfWeek--) | Hämtar veckodagen som representeras av den här instansen. |
| [getDayOfYear()](#getDayOfYear--) | Hämtar dagen på året som representeras av detta objekt. |
| [getHour()](#getHour--) | Hämtar timkomponenten i datumet som representeras av detta objekt. |
| [getMillisecond()](#getMillisecond--) | Hämtar millisekundkomponenten i datumet som representeras av detta objekt. |
| [getMinute()](#getMinute--) | Hämtar minutkomponenten i datumet som representeras av detta objekt. |
| [getMonth()](#getMonth--) | Hämtar månadsdelen i datumet som representeras av detta objekt. |
| [getNow()](#getNow--) | Hämtar ett DateTime-objekt som är inställt på det aktuella datumet och tiden på den här datorn, uttryckt i lokal tid. |
| [getSecond()](#getSecond--) | Hämtar sekundkomponenten i datumet som representeras av detta objekt. |
| [getYear()](#getYear--) | Hämtar årskomponenten i datumet som representeras av detta objekt. |
| [hashCode()](#hashCode--) | Returnerar hashkoden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toCalendar()](#toCalendar--) | Konverterar värdet av det aktuella DateTime-objektet till ett Calendar-objekt. |
| [toDate()](#toDate--) | Konverterar värdet av det aktuella DateTime-objektet till ett Date-objekt. |
| [toLocalTime()](#toLocalTime--) | Konverterar värdet av det aktuella DateTime-objektet till lokal tid. |
| [toString()](#toString--) | Konverterar värdet av det aktuella DateTime-objektet till dess motsvarande strängrepresentation. |
| [toUniversalTime()](#toUniversalTime--) | Konverterar värdet av det aktuella DateTime-objektet till koordinerad universell tid (UTC). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DateTime(int year, int month, int day) {#DateTime-int-int-int-}
```
public DateTime(int year, int month, int day)
```


Initierar en ny instans av DateTime-objektet med det angivna året, månaden och dagen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | Året (1 till 9999). |
| månad | int | Månad (1 till 12). |
| dag | int | Dag (1 till antalet dagar i månaden). |

### DateTime(int year, int month, int day, int hour, int minute, int second) {#DateTime-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second)
```


Initierar en ny instans av DateTime-objektet med det angivna året, månaden, dagen, timmen, minuten och sekunden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | Året (1 till 9999). |
| månad | int | Månad (1 till 12). |
| dag | int | Dag (1 till antalet dagar i månaden). |
| timme | int | Timmar (0 till 23). |
| minut | int | Minuter (0 till 59). |
| sekund | int | Sekunderna (0 till 59). |

### DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond) {#DateTime-int-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)
```


Initierar en ny instans av DateTime-objektet med det angivna året, månaden, dagen, timmen, minuten, sekunden och millisekunden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| år | int | Året (1 till 9999). |
| månad | int | Månad (1 till 12). |
| dag | int | Dag (1 till antalet dagar i månaden). |
| timme | int | Timmar (0 till 23). |
| minut | int | Minuter (0 till 59). |
| sekund | int | Sekunderna (0 till 59). |
| millisekund | int | Millisekunderna (0 till 999). |

### DateTime(Date date) {#DateTime-java.util.Date-}
```
public DateTime(Date date)
```


Initierar en ny instans av DateTime-objektet med det angivna Date-objektet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| datum | java.util.Date | Date-objektet |

### DateTime(Calendar cld) {#DateTime-java.util.Calendar-}
```
public DateTime(Calendar cld)
```


Initierar en ny instans av DateTime-objektet med det angivna Calendar-objektet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cld | java.util.Calendar | Calendar-objektet |

### addDays(double value) {#addDays-double-}
```
public DateTime addDays(double value)
```


Lägger till det angivna antalet dagar till värdet av den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Ett antal hela och bråkdelar av dagar. Parametern value kan vara negativ eller positiv. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of days represented by value.
### addHours(double value) {#addHours-double-}
```
public DateTime addHours(double value)
```


Lägger till det angivna antalet timmar till värdet av den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Ett antal hela och bråkdelar av timmar. Parametern value kan vara negativ eller positiv. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of hours represented by value.
### addMilliseconds(double value) {#addMilliseconds-double-}
```
public DateTime addMilliseconds(double value)
```


Lägger till det angivna antalet millisekunder till värdet av den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Ett antal hela och bråkdelar av millisekunder. Parametern value kan vara negativ eller positiv. Observera att detta värde avrundas till närmaste heltal. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of milliseconds represented by value.
### addMinutes(double value) {#addMinutes-double-}
```
public DateTime addMinutes(double value)
```


Lägger till det angivna antalet minuter till värdet av den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Ett antal hela och bråkdelar av minuter. Parametern value kan vara negativ eller positiv. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of minutes represented by value.
### addMonths(int months) {#addMonths-int-}
```
public DateTime addMonths(int months)
```


Lägger till det angivna antalet månader till värdet av den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| månader | int | Ett antal månader. Parametern months kan vara negativ eller positiv. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and months.
### addSeconds(double value) {#addSeconds-double-}
```
public DateTime addSeconds(double value)
```


Lägger till det angivna antalet sekunder till värdet av den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Ett antal hela och bråkdelar av sekunder. Parametern value kan vara negativ eller positiv. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of seconds represented by value.
### addYears(int value) {#addYears-int-}
```
public DateTime addYears(int value)
```


Lägger till det angivna antalet år till värdet av den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Ett antal år. Parametern value kan vara negativ eller positiv. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of years represented by value.
### compareTo(DateTime value) {#compareTo-com.aspose.diagram.DateTime-}
```
public int compareTo(DateTime value)
```


Jämför värdet av den här instansen med ett angivet DateTime‑värde och returnerar ett heltal som indikerar om denna instans är tidigare än, samma som eller senare än det angivna DateTime‑värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) | Ett DateTime-objekt att jämföra. |

**Returns:**
int - Ett signerat tal som indikerar de relativa värdena för detta objekt och value‑parametern. Värdebeskrivning Mindre än noll Detta objekt är tidigare än value. Noll Detta objekt är samma som value. Större än noll Detta objekt är senare än value.
### compareTo(Object value) {#compareTo-java.lang.Object-}
```
public int compareTo(Object value)
```


Jämför värdet av den här instansen med ett angivet objekt som innehåller ett angivet DateTime‑värde och returnerar ett heltal som indikerar om denna instans är tidigare än, samma som eller senare än det angivna DateTime‑värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object | Ett inbäddat DateTime-objekt att jämföra, eller null. |

**Returns:**
int - Ett signerat tal som indikerar de relativa värdena för detta objekt och value. Värdebeskrivning Mindre än noll Detta objekt är tidigare än value. Noll Detta objekt är samma som value. Större än noll Detta objekt är senare än value, eller value är null.
### equals(Object value) {#equals-java.lang.Object-}
```
public boolean equals(Object value)
```


Returnerar ett värde som indikerar om denna instans är lika med ett angivet objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Object | Ett objekt att jämföra med detta objekt. |

**Returns:**
boolean - true om value är en instans av DateTime och är lika med värdet för detta objekt; annars false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDay() {#getDay--}
```
public int getDay()
```


Hämtar dagen i månaden som representeras av den här instansen.

**Returns:**
int - Dagkomponenten, uttryckt som ett värde mellan 1 och 31.
### getDayOfWeek() {#getDayOfWeek--}
```
public int getDayOfWeek()
```


Hämtar veckodagen som representeras av den här instansen.

**Returns:**
int - veckodagen för detta DateTime‑värde.
### getDayOfYear() {#getDayOfYear--}
```
public int getDayOfYear()
```


Hämtar dagen på året som representeras av detta objekt.

**Returns:**
int - Dagen på året, uttryckt som ett värde mellan 1 och 366.
### getHour() {#getHour--}
```
public int getHour()
```


Hämtar timkomponenten i datumet som representeras av detta objekt.

**Returns:**
int - Timkomponenten, uttryckt som ett värde mellan 0 och 23.
### getMillisecond() {#getMillisecond--}
```
public int getMillisecond()
```


Hämtar millisekundkomponenten i datumet som representeras av detta objekt.

**Returns:**
int - Millisekundkomponenten, uttryckt som ett värde mellan 0 och 999.
### getMinute() {#getMinute--}
```
public int getMinute()
```


Hämtar minutkomponenten i datumet som representeras av detta objekt.

**Returns:**
int - Minutkomponenten, uttryckt som ett värde mellan 0 och 59.
### getMonth() {#getMonth--}
```
public int getMonth()
```


Hämtar månadsdelen i datumet som representeras av detta objekt.

**Returns:**
int - Månadskomponenten, uttryckt som ett värde mellan 1 och 12.
### getNow() {#getNow--}
```
public static DateTime getNow()
```


Hämtar ett DateTime-objekt som är inställt på det aktuella datumet och tiden på den här datorn, uttryckt i lokal tid.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the current local date and time.
### getSecond() {#getSecond--}
```
public int getSecond()
```


Hämtar sekundkomponenten i datumet som representeras av detta objekt.

**Returns:**
int - Sekunderna, mellan 0 och 59.
### getYear() {#getYear--}
```
public int getYear()
```


Hämtar årskomponenten i datumet som representeras av detta objekt.

**Returns:**
int - Året, mellan 1 och 9999.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hashkoden för detta objekt.

**Returns:**
int - En 32-bitars signerad heltals hashkod.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toCalendar() {#toCalendar--}
```
public Calendar toCalendar()
```


Konverterar värdet av det aktuella DateTime-objektet till ett Calendar-objekt.

**Returns:**
[Calendar](../../java.util/calendar) - Calendar object
### toDate() {#toDate--}
```
public Date toDate()
```


Konverterar värdet av det aktuella DateTime-objektet till ett Date-objekt.

**Returns:**
java.util.Date - Datumobjekt
### toLocalTime() {#toLocalTime--}
```
public DateTime toLocalTime()
```


Konverterar värdet av det aktuella DateTime-objektet till lokal tid.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object of local
### toString() {#toString--}
```
public String toString()
```


Konverterar värdet av det aktuella DateTime-objektet till dess motsvarande strängrepresentation.

**Returns:**
java.lang.String - En strängrepresentation av värdet för det aktuella DateTime-objektet.
### toUniversalTime() {#toUniversalTime--}
```
public DateTime toUniversalTime()
```


Konverterar värdet av det aktuella DateTime-objektet till koordinerad universell tid (UTC).

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object of UTC
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

