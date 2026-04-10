---
title: DateTime
second_title: Aspose.Diagram voor Java API-referentie
description: Stelt een moment in de tijd voor, meestal uitgedrukt als een datum en tijd van de dag.
type: docs
weight: 115
url: /nl/java/com.aspose.diagram/datetime/
---

**Inheritance:**
java.lang.Object
```
public class DateTime
```

Geeft een moment in de tijd weer, meestal uitgedrukt als een datum en tijd van de dag.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DateTime(int year, int month, int day)](#DateTime-int-int-int-) | Initialiseert een nieuw exemplaar van het DateTime-object met het opgegeven jaar, maand en dag. |
| [DateTime(int year, int month, int day, int hour, int minute, int second)](#DateTime-int-int-int-int-int-int-) | Initialiseert een nieuw exemplaar van het DateTime-object met het opgegeven jaar, maand, dag, uur, minuut en seconde. |
| [DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)](#DateTime-int-int-int-int-int-int-int-) | Initialiseert een nieuw exemplaar van het DateTime-object met het opgegeven jaar, maand, dag, uur, minuut, seconde en milliseconde. |
| [DateTime(Date date)](#DateTime-java.util.Date-) | Initialiseert een nieuw exemplaar van het DateTime-object met het opgegeven Date-object |
| [DateTime(Calendar cld)](#DateTime-java.util.Calendar-) | Initialiseert een nieuw exemplaar van het DateTime-object met het opgegeven Calendar-object |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addDays(double value)](#addDays-double-) | Voegt het opgegeven aantal dagen toe aan de waarde van dit exemplaar. |
| [addHours(double value)](#addHours-double-) | Voegt het opgegeven aantal uren toe aan de waarde van dit exemplaar. |
| [addMilliseconds(double value)](#addMilliseconds-double-) | Voegt het opgegeven aantal milliseconden toe aan de waarde van dit exemplaar. |
| [addMinutes(double value)](#addMinutes-double-) | Voegt het opgegeven aantal minuten toe aan de waarde van dit exemplaar. |
| [addMonths(int months)](#addMonths-int-) | Voegt het opgegeven aantal maanden toe aan de waarde van dit exemplaar. |
| [addSeconds(double value)](#addSeconds-double-) | Voegt het opgegeven aantal seconden toe aan de waarde van dit exemplaar. |
| [addYears(int value)](#addYears-int-) | Voegt het opgegeven aantal jaren toe aan de waarde van dit exemplaar. |
| [compareTo(DateTime value)](#compareTo-com.aspose.diagram.DateTime-) | Vergelijkt de waarde van dit exemplaar met een opgegeven DateTime-waarde en retourneert een geheel getal dat aangeeft of dit exemplaar eerder, gelijk of later is dan de opgegeven DateTime-waarde. |
| [compareTo(Object value)](#compareTo-java.lang.Object-) | Vergelijkt de waarde van dit exemplaar met een opgegeven object dat een opgegeven DateTime-waarde bevat, en retourneert een geheel getal dat aangeeft of dit exemplaar eerder, gelijk of later is dan de opgegeven DateTime-waarde. |
| [equals(Object value)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of dit exemplaar gelijk is aan een opgegeven object. |
| [getClass()](#getClass--) |  |
| [getDay()](#getDay--) | Haalt de dag van de maand op die door dit exemplaar wordt weergegeven. |
| [getDayOfWeek()](#getDayOfWeek--) | Haalt de dag van de week op die door dit exemplaar wordt weergegeven. |
| [getDayOfYear()](#getDayOfYear--) | Haalt de dag van het jaar op die door deze instantie wordt weergegeven. |
| [getHour()](#getHour--) | Haalt het uurcomponent van de datum op die door deze instantie wordt weergegeven. |
| [getMillisecond()](#getMillisecond--) | Haalt het millisecondencomponent van de datum op die door deze instantie wordt weergegeven. |
| [getMinute()](#getMinute--) | Haalt het minuutcomponent van de datum op die door deze instantie wordt weergegeven. |
| [getMonth()](#getMonth--) | Haalt het maandcomponent van de datum op die door deze instantie wordt weergegeven. |
| [getNow()](#getNow--) | Haalt een DateTime-object op dat is ingesteld op de huidige datum en tijd op deze computer, weergegeven als lokale tijd. |
| [getSecond()](#getSecond--) | Haalt het secondencomponent van de datum op die door deze instantie wordt weergegeven. |
| [getYear()](#getYear--) | Haalt het jaarcomponent van de datum op die door deze instantie wordt weergegeven. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toCalendar()](#toCalendar--) | Converteert de waarde van het huidige DateTime-object naar een Calendar-object. |
| [toDate()](#toDate--) | Converteert de waarde van het huidige DateTime-object naar een Date-object. |
| [toLocalTime()](#toLocalTime--) | Converteert de waarde van het huidige DateTime-object naar lokale tijd. |
| [toString()](#toString--) | Converteert de waarde van het huidige DateTime-object naar de equivalente tekenreeksrepresentatie. |
| [toUniversalTime()](#toUniversalTime--) | Converteert de waarde van het huidige DateTime-object naar Coordinated Universal Time (UTC). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DateTime(int year, int month, int day) {#DateTime-int-int-int-}
```
public DateTime(int year, int month, int day)
```


Initialiseert een nieuw exemplaar van het DateTime-object met het opgegeven jaar, maand en dag.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| jaar | int | Het jaar (1 tot en met 9999). |
| maand | int | De maand (1 tot en met 12). |
| dag | int | De dag (1 tot en met het aantal dagen in de maand). |

### DateTime(int year, int month, int day, int hour, int minute, int second) {#DateTime-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second)
```


Initialiseert een nieuw exemplaar van het DateTime-object met het opgegeven jaar, maand, dag, uur, minuut en seconde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| jaar | int | Het jaar (1 tot en met 9999). |
| maand | int | De maand (1 tot en met 12). |
| dag | int | De dag (1 tot en met het aantal dagen in de maand). |
| uur | int | De uren (0 tot en met 23). |
| minuut | int | De minuten (0 tot en met 59). |
| seconde | int | De seconden (0 tot en met 59). |

### DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond) {#DateTime-int-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)
```


Initialiseert een nieuw exemplaar van het DateTime-object met het opgegeven jaar, maand, dag, uur, minuut, seconde en milliseconde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| jaar | int | Het jaar (1 tot en met 9999). |
| maand | int | De maand (1 tot en met 12). |
| dag | int | De dag (1 tot en met het aantal dagen in de maand). |
| uur | int | De uren (0 tot en met 23). |
| minuut | int | De minuten (0 tot en met 59). |
| seconde | int | De seconden (0 tot en met 59). |
| milliseconde | int | De milliseconden (0 tot en met 999). |

### DateTime(Date date) {#DateTime-java.util.Date-}
```
public DateTime(Date date)
```


Initialiseert een nieuw exemplaar van het DateTime-object met het opgegeven Date-object

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| datum | java.util.Date | Het Date-object |

### DateTime(Calendar cld) {#DateTime-java.util.Calendar-}
```
public DateTime(Calendar cld)
```


Initialiseert een nieuw exemplaar van het DateTime-object met het opgegeven Calendar-object

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cld | java.util.Calendar | Het Calendar-object |

### addDays(double value) {#addDays-double-}
```
public DateTime addDays(double value)
```


Voegt het opgegeven aantal dagen toe aan de waarde van dit exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Een aantal gehele en fractionele dagen. De value-parameter kan negatief of positief zijn. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of days represented by value.
### addHours(double value) {#addHours-double-}
```
public DateTime addHours(double value)
```


Voegt het opgegeven aantal uren toe aan de waarde van dit exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Een aantal gehele en fractionele uren. De value-parameter kan negatief of positief zijn. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of hours represented by value.
### addMilliseconds(double value) {#addMilliseconds-double-}
```
public DateTime addMilliseconds(double value)
```


Voegt het opgegeven aantal milliseconden toe aan de waarde van dit exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Een aantal gehele en fractionele milliseconden. De value-parameter kan negatief of positief zijn. Merk op dat deze waarde naar het dichtstbijzijnde gehele getal wordt afgerond. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of milliseconds represented by value.
### addMinutes(double value) {#addMinutes-double-}
```
public DateTime addMinutes(double value)
```


Voegt het opgegeven aantal minuten toe aan de waarde van dit exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Een aantal gehele en fractionele minuten. De value-parameter kan negatief of positief zijn. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of minutes represented by value.
### addMonths(int months) {#addMonths-int-}
```
public DateTime addMonths(int months)
```


Voegt het opgegeven aantal maanden toe aan de waarde van dit exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maanden | int | Een aantal maanden. De months-parameter kan negatief of positief zijn. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and months.
### addSeconds(double value) {#addSeconds-double-}
```
public DateTime addSeconds(double value)
```


Voegt het opgegeven aantal seconden toe aan de waarde van dit exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Een aantal gehele en fractionele seconden. De value-parameter kan negatief of positief zijn. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of seconds represented by value.
### addYears(int value) {#addYears-int-}
```
public DateTime addYears(int value)
```


Voegt het opgegeven aantal jaren toe aan de waarde van dit exemplaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Een aantal jaren. De value-parameter kan negatief of positief zijn. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of years represented by value.
### compareTo(DateTime value) {#compareTo-com.aspose.diagram.DateTime-}
```
public int compareTo(DateTime value)
```


Vergelijkt de waarde van dit exemplaar met een opgegeven DateTime-waarde en retourneert een geheel getal dat aangeeft of dit exemplaar eerder, gelijk of later is dan de opgegeven DateTime-waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) | Een DateTime-object om te vergelijken. |

**Returns:**
int - Een ondertekend getal dat de relatieve waarden van deze instantie en de value-parameter aangeeft. Waarde Beschrijving Minder dan nul Deze instantie is eerder dan value. Nul Deze instantie is gelijk aan value. Groter dan nul Deze instantie is later dan value.
### compareTo(Object value) {#compareTo-java.lang.Object-}
```
public int compareTo(Object value)
```


Vergelijkt de waarde van dit exemplaar met een opgegeven object dat een opgegeven DateTime-waarde bevat, en retourneert een geheel getal dat aangeeft of dit exemplaar eerder, gelijk of later is dan de opgegeven DateTime-waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object | Een verpakt DateTime-object om te vergelijken, of null. |

**Returns:**
int - Een ondertekend getal dat de relatieve waarden van deze instantie en value aangeeft. Waarde Beschrijving Minder dan nul Deze instantie is eerder dan value. Nul Deze instantie is gelijk aan value. Groter dan nul Deze instantie is later dan value, of value is null.
### equals(Object value) {#equals-java.lang.Object-}
```
public boolean equals(Object value)
```


Retourneert een waarde die aangeeft of dit exemplaar gelijk is aan een opgegeven object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Object | Een object om te vergelijken met deze instantie. |

**Returns:**
boolean - true als value een instantie van DateTime is en gelijk is aan de waarde van deze instantie; anders false.
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


Haalt de dag van de maand op die door dit exemplaar wordt weergegeven.

**Returns:**
int - Het dagcomponent, uitgedrukt als een waarde tussen 1 en 31.
### getDayOfWeek() {#getDayOfWeek--}
```
public int getDayOfWeek()
```


Haalt de dag van de week op die door dit exemplaar wordt weergegeven.

**Returns:**
int - de dag van de week van deze DateTime-waarde.
### getDayOfYear() {#getDayOfYear--}
```
public int getDayOfYear()
```


Haalt de dag van het jaar op die door deze instantie wordt weergegeven.

**Returns:**
int - De dag van het jaar, weergegeven als een waarde tussen 1 en 366.
### getHour() {#getHour--}
```
public int getHour()
```


Haalt het uurcomponent van de datum op die door deze instantie wordt weergegeven.

**Returns:**
int - Het uurcomponent, weergegeven als een waarde tussen 0 en 23.
### getMillisecond() {#getMillisecond--}
```
public int getMillisecond()
```


Haalt het millisecondencomponent van de datum op die door deze instantie wordt weergegeven.

**Returns:**
int - Het millisecondencomponent, weergegeven als een waarde tussen 0 en 999.
### getMinute() {#getMinute--}
```
public int getMinute()
```


Haalt het minuutcomponent van de datum op die door deze instantie wordt weergegeven.

**Returns:**
int - Het minuutcomponent, weergegeven als een waarde tussen 0 en 59.
### getMonth() {#getMonth--}
```
public int getMonth()
```


Haalt het maandcomponent van de datum op die door deze instantie wordt weergegeven.

**Returns:**
int - Het maandcomponent, weergegeven als een waarde tussen 1 en 12.
### getNow() {#getNow--}
```
public static DateTime getNow()
```


Haalt een DateTime-object op dat is ingesteld op de huidige datum en tijd op deze computer, weergegeven als lokale tijd.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the current local date and time.
### getSecond() {#getSecond--}
```
public int getSecond()
```


Haalt het secondencomponent van de datum op die door deze instantie wordt weergegeven.

**Returns:**
int - De seconden, tussen 0 en 59.
### getYear() {#getYear--}
```
public int getYear()
```


Haalt het jaarcomponent van de datum op die door deze instantie wordt weergegeven.

**Returns:**
int - Het jaar, tussen 1 en 9999.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bit ondertekende integer hashcode.
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


Converteert de waarde van het huidige DateTime-object naar een Calendar-object.

**Returns:**
[Calendar](../../java.util/calendar) - Calendar object
### toDate() {#toDate--}
```
public Date toDate()
```


Converteert de waarde van het huidige DateTime-object naar een Date-object.

**Returns:**
java.util.Date - Datumobject
### toLocalTime() {#toLocalTime--}
```
public DateTime toLocalTime()
```


Converteert de waarde van het huidige DateTime-object naar lokale tijd.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object of local
### toString() {#toString--}
```
public String toString()
```


Converteert de waarde van het huidige DateTime-object naar de equivalente tekenreeksrepresentatie.

**Returns:**
java.lang.String - Een tekenreeksrepresentatie van de waarde van het huidige DateTime-object.
### toUniversalTime() {#toUniversalTime--}
```
public DateTime toUniversalTime()
```


Converteert de waarde van het huidige DateTime-object naar Coordinated Universal Time (UTC).

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

