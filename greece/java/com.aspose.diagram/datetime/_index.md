---
title: DateTime
second_title: Αναφορά API του Aspose.Diagram για Java
description: Αντιπροσωπεύει μια στιγμή στο χρόνο που συνήθως εκφράζεται ως ημερομηνία και ώρα της ημέρας.
type: docs
weight: 115
url: /el/java/com.aspose.diagram/datetime/
---

**Inheritance:**
java.lang.Object
```
public class DateTime
```

Αντιπροσωπεύει μια στιγμή στο χρόνο, συνήθως εκφρασμένη ως ημερομηνία και ώρα της ημέρας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DateTime(int year, int month, int day)](#DateTime-int-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο DateTime με το καθορισμένο έτος, μήνα και ημέρα. |
| [DateTime(int year, int month, int day, int hour, int minute, int second)](#DateTime-int-int-int-int-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο DateTime με το καθορισμένο έτος, μήνα, ημέρα, ώρα, λεπτό και δευτερόλεπτο. |
| [DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)](#DateTime-int-int-int-int-int-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο DateTime με το καθορισμένο έτος, μήνα, ημέρα, ώρα, λεπτό, δευτερόλεπτο και χιλιοστό του δευτερολέπτου. |
| [DateTime(Date date)](#DateTime-java.util.Date-) | Αρχικοποιεί ένα νέο αντικείμενο DateTime με το καθορισμένο αντικείμενο Date |
| [DateTime(Calendar cld)](#DateTime-java.util.Calendar-) | Αρχικοποιεί ένα νέο αντικείμενο DateTime με το καθορισμένο αντικείμενο Calendar |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addDays(double value)](#addDays-double-) | Προσθέτει τον καθορισμένο αριθμό ημερών στην τιμή αυτού του αντικειμένου. |
| [addHours(double value)](#addHours-double-) | Προσθέτει τον καθορισμένο αριθμό ωρών στην τιμή αυτού του αντικειμένου. |
| [addMilliseconds(double value)](#addMilliseconds-double-) | Προσθέτει τον καθορισμένο αριθμό χιλιοστών του δευτερολέπτου στην τιμή αυτού του αντικειμένου. |
| [addMinutes(double value)](#addMinutes-double-) | Προσθέτει τον καθορισμένο αριθμό λεπτών στην τιμή αυτού του αντικειμένου. |
| [addMonths(int months)](#addMonths-int-) | Προσθέτει τον καθορισμένο αριθμό μηνών στην τιμή αυτού του αντικειμένου. |
| [addSeconds(double value)](#addSeconds-double-) | Προσθέτει τον καθορισμένο αριθμό δευτερολέπτων στην τιμή αυτού του αντικειμένου. |
| [addYears(int value)](#addYears-int-) | Προσθέτει τον καθορισμένο αριθμό ετών στην τιμή αυτού του αντικειμένου. |
| [compareTo(DateTime value)](#compareTo-com.aspose.diagram.DateTime-) | Συγκρίνει την τιμή αυτού του αντικειμένου με μια καθορισμένη τιμή DateTime και επιστρέφει έναν ακέραιο που υποδεικνύει εάν αυτό το αντικείμενο είναι νωρίτερα, το ίδιο ή αργότερα από την καθορισμένη τιμή DateTime. |
| [compareTo(Object value)](#compareTo-java.lang.Object-) | Συγκρίνει την τιμή αυτού του αντικειμένου με ένα καθορισμένο αντικείμενο που περιέχει μια καθορισμένη τιμή DateTime και επιστρέφει έναν ακέραιο που υποδεικνύει εάν αυτό το αντικείμενο είναι νωρίτερα, το ίδιο ή αργότερα από την καθορισμένη τιμή DateTime. |
| [equals(Object value)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι ίσο με ένα καθορισμένο αντικείμενο. |
| [getClass()](#getClass--) |  |
| [getDay()](#getDay--) | Λαμβάνει την ημέρα του μήνα που αντιπροσωπεύεται από αυτό το αντικείμενο. |
| [getDayOfWeek()](#getDayOfWeek--) | Λαμβάνει την ημέρα της εβδομάδας που αντιπροσωπεύεται από αυτό το αντικείμενο. |
| [getDayOfYear()](#getDayOfYear--) | Λαμβάνει την ημέρα του έτους που αντιπροσωπεύεται από αυτό το αντικείμενο. |
| [getHour()](#getHour--) | Λαμβάνει το στοιχείο ώρας της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο. |
| [getMillisecond()](#getMillisecond--) | Λαμβάνει το στοιχείο χιλιοστών του δευτερολέπτου της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο. |
| [getMinute()](#getMinute--) | Λαμβάνει το στοιχείο λεπτών της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο. |
| [getMonth()](#getMonth--) | Λαμβάνει το στοιχείο μήνα της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο. |
| [getNow()](#getNow--) | Λαμβάνει ένα αντικείμενο DateTime που ορίζεται στην τρέχουσα ημερομηνία και ώρα σε αυτόν τον υπολογιστή, εκφρασμένη ως τοπική ώρα. |
| [getSecond()](#getSecond--) | Λαμβάνει το στοιχείο δευτερολέπτων της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο. |
| [getYear()](#getYear--) | Λαμβάνει το στοιχείο έτους της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτό το αντικείμενο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toCalendar()](#toCalendar--) | Μετατρέπει την τιμή του τρέχοντος αντικειμένου DateTime σε αντικείμενο Calendar. |
| [toDate()](#toDate--) | Μετατρέπει την τιμή του τρέχοντος αντικειμένου DateTime σε αντικείμενο Date. |
| [toLocalTime()](#toLocalTime--) | Μετατρέπει την τιμή του τρέχοντος αντικειμένου DateTime σε τοπική ώρα. |
| [toString()](#toString--) | Μετατρέπει την τιμή του τρέχοντος αντικειμένου DateTime στην ισοδύναμη αναπαράσταση σε συμβολοσειρά. |
| [toUniversalTime()](#toUniversalTime--) | Μετατρέπει την τιμή του τρέχοντος αντικειμένου DateTime σε Συντονισμένο Παγκόσμιο Χρόνο (UTC). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DateTime(int year, int month, int day) {#DateTime-int-int-int-}
```
public DateTime(int year, int month, int day)
```


Αρχικοποιεί ένα νέο αντικείμενο DateTime με το καθορισμένο έτος, μήνα και ημέρα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έτος | int | Το έτος (1 έως 9999). |
| μήνας | int | Ο μήνας (1 έως 12). |
| ημέρα | int | Η ημέρα (1 έως τον αριθμό των ημερών του μήνα). |

### DateTime(int year, int month, int day, int hour, int minute, int second) {#DateTime-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second)
```


Αρχικοποιεί ένα νέο αντικείμενο DateTime με το καθορισμένο έτος, μήνα, ημέρα, ώρα, λεπτό και δευτερόλεπτο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έτος | int | Το έτος (1 έως 9999). |
| μήνας | int | Ο μήνας (1 έως 12). |
| ημέρα | int | Η ημέρα (1 έως τον αριθμό των ημερών του μήνα). |
| ώρα | int | Οι ώρες (0 έως 23). |
| λεπτό | int | Τα λεπτά (0 έως 59). |
| δευτερόλεπτο | int | The seconds (0 through 59). |

### DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond) {#DateTime-int-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)
```


Αρχικοποιεί ένα νέο αντικείμενο DateTime με το καθορισμένο έτος, μήνα, ημέρα, ώρα, λεπτό, δευτερόλεπτο και χιλιοστό του δευτερολέπτου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έτος | int | Το έτος (1 έως 9999). |
| μήνας | int | Ο μήνας (1 έως 12). |
| ημέρα | int | Η ημέρα (1 έως τον αριθμό των ημερών του μήνα). |
| ώρα | int | Οι ώρες (0 έως 23). |
| λεπτό | int | Τα λεπτά (0 έως 59). |
| δευτερόλεπτο | int | The seconds (0 through 59). |
| millisecond | int | The milliseconds (0 through 999). |

### DateTime(Date date) {#DateTime-java.util.Date-}
```
public DateTime(Date date)
```


Αρχικοποιεί ένα νέο αντικείμενο DateTime με το καθορισμένο αντικείμενο Date

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| date | java.util.Date | The Date object |

### DateTime(Calendar cld) {#DateTime-java.util.Calendar-}
```
public DateTime(Calendar cld)
```


Αρχικοποιεί ένα νέο αντικείμενο DateTime με το καθορισμένο αντικείμενο Calendar

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cld | java.util.Calendar | The Calendar object |

### addDays(double value) {#addDays-double-}
```
public DateTime addDays(double value)
```


Προσθέτει τον καθορισμένο αριθμό ημερών στην τιμή αυτού του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | A number of whole and fractional days. The value parameter can be negative or positive. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of days represented by value.
### addHours(double value) {#addHours-double-}
```
public DateTime addHours(double value)
```


Προσθέτει τον καθορισμένο αριθμό ωρών στην τιμή αυτού του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | A number of whole and fractional hours. The value parameter can be negative or positive. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of hours represented by value.
### addMilliseconds(double value) {#addMilliseconds-double-}
```
public DateTime addMilliseconds(double value)
```


Προσθέτει τον καθορισμένο αριθμό χιλιοστών του δευτερολέπτου στην τιμή αυτού του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | A number of whole and fractional milliseconds. The value parameter can be negative or positive. Note that this value is rounded to the nearest integer. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of milliseconds represented by value.
### addMinutes(double value) {#addMinutes-double-}
```
public DateTime addMinutes(double value)
```


Προσθέτει τον καθορισμένο αριθμό λεπτών στην τιμή αυτού του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | A number of whole and fractional minutes. The value parameter can be negative or positive. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of minutes represented by value.
### addMonths(int months) {#addMonths-int-}
```
public DateTime addMonths(int months)
```


Προσθέτει τον καθορισμένο αριθμό μηνών στην τιμή αυτού του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| months | int | A number of months. The months parameter can be negative or positive. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and months.
### addSeconds(double value) {#addSeconds-double-}
```
public DateTime addSeconds(double value)
```


Προσθέτει τον καθορισμένο αριθμό δευτερολέπτων στην τιμή αυτού του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | A number of whole and fractional seconds. The value parameter can be negative or positive. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of seconds represented by value.
### addYears(int value) {#addYears-int-}
```
public DateTime addYears(int value)
```


Προσθέτει τον καθορισμένο αριθμό ετών στην τιμή αυτού του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | A number of years. The value parameter can be negative or positive. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of years represented by value.
### compareTo(DateTime value) {#compareTo-com.aspose.diagram.DateTime-}
```
public int compareTo(DateTime value)
```


Συγκρίνει την τιμή αυτού του αντικειμένου με μια καθορισμένη τιμή DateTime και επιστρέφει έναν ακέραιο που υποδεικνύει εάν αυτό το αντικείμενο είναι νωρίτερα, το ίδιο ή αργότερα από την καθορισμένη τιμή DateTime.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) | A DateTime object to compare. |

**Returns:**
int - A signed number indicating the relative values of this instance and the value parameter. Value Description Less than zero This instance is earlier than value. Zero This instance is the same as value. Greater than zero This instance is later than value.
### compareTo(Object value) {#compareTo-java.lang.Object-}
```
public int compareTo(Object value)
```


Συγκρίνει την τιμή αυτού του αντικειμένου με ένα καθορισμένο αντικείμενο που περιέχει μια καθορισμένη τιμή DateTime και επιστρέφει έναν ακέραιο που υποδεικνύει εάν αυτό το αντικείμενο είναι νωρίτερα, το ίδιο ή αργότερα από την καθορισμένη τιμή DateTime.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object | A boxed DateTime object to compare, or null. |

**Returns:**
int - A signed number indicating the relative values of this instance and value. Value Description Less than zero This instance is earlier than value. Zero This instance is the same as value. Greater than zero This instance is later than value, or value is null.
### equals(Object value) {#equals-java.lang.Object-}
```
public boolean equals(Object value)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι ίσο με ένα καθορισμένο αντικείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.Object | An object to compare to this instance. |

**Returns:**
boolean - true if value is an instance of DateTime and equals the value of this instance; otherwise, false.
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


Λαμβάνει την ημέρα του μήνα που αντιπροσωπεύεται από αυτό το αντικείμενο.

**Returns:**
int - The day component, expressed as a value between 1 and 31.
### getDayOfWeek() {#getDayOfWeek--}
```
public int getDayOfWeek()
```


Λαμβάνει την ημέρα της εβδομάδας που αντιπροσωπεύεται από αυτό το αντικείμενο.

**Returns:**
int - the day of the week of this DateTime value.
### getDayOfYear() {#getDayOfYear--}
```
public int getDayOfYear()
```


Λαμβάνει την ημέρα του έτους που αντιπροσωπεύεται από αυτό το αντικείμενο.

**Returns:**
int - Η ημέρα του έτους, εκφρασμένη ως τιμή μεταξύ 1 και 366.
### getHour() {#getHour--}
```
public int getHour()
```


Λαμβάνει το στοιχείο ώρας της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο.

**Returns:**
int - Το στοιχείο ώρας, εκφρασμένο ως τιμή μεταξύ 0 και 23.
### getMillisecond() {#getMillisecond--}
```
public int getMillisecond()
```


Λαμβάνει το στοιχείο χιλιοστών του δευτερολέπτου της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο.

**Returns:**
int - Το στοιχείο χιλιοστών του δευτερολέπτου, εκφρασμένο ως τιμή μεταξύ 0 και 999.
### getMinute() {#getMinute--}
```
public int getMinute()
```


Λαμβάνει το στοιχείο λεπτών της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο.

**Returns:**
int - Το στοιχείο λεπτών, εκφρασμένο ως τιμή μεταξύ 0 και 59.
### getMonth() {#getMonth--}
```
public int getMonth()
```


Λαμβάνει το στοιχείο μήνα της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο.

**Returns:**
int - Το στοιχείο μήνα, εκφρασμένο ως τιμή μεταξύ 1 και 12.
### getNow() {#getNow--}
```
public static DateTime getNow()
```


Λαμβάνει ένα αντικείμενο DateTime που ορίζεται στην τρέχουσα ημερομηνία και ώρα σε αυτόν τον υπολογιστή, εκφρασμένη ως τοπική ώρα.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the current local date and time.
### getSecond() {#getSecond--}
```
public int getSecond()
```


Λαμβάνει το στοιχείο δευτερολέπτων της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο.

**Returns:**
int - Τα δευτερόλεπτα, μεταξύ 0 και 59.
### getYear() {#getYear--}
```
public int getYear()
```


Λαμβάνει το στοιχείο έτους της ημερομηνίας που αντιπροσωπεύεται από αυτό το αντικείμενο.

**Returns:**
int - Το έτος, μεταξύ 1 και 9999.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτό το αντικείμενο.

**Returns:**
int - Ένας κωδικός κατακερματισμού 32-bit με πρόσημο.
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


Μετατρέπει την τιμή του τρέχοντος αντικειμένου DateTime σε αντικείμενο Calendar.

**Returns:**
[Calendar](../../java.util/calendar) - Calendar object
### toDate() {#toDate--}
```
public Date toDate()
```


Μετατρέπει την τιμή του τρέχοντος αντικειμένου DateTime σε αντικείμενο Date.

**Returns:**
java.util.Date - Αντικείμενο ημερομηνίας
### toLocalTime() {#toLocalTime--}
```
public DateTime toLocalTime()
```


Μετατρέπει την τιμή του τρέχοντος αντικειμένου DateTime σε τοπική ώρα.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object of local
### toString() {#toString--}
```
public String toString()
```


Μετατρέπει την τιμή του τρέχοντος αντικειμένου DateTime στην ισοδύναμη αναπαράσταση σε συμβολοσειρά.

**Returns:**
java.lang.String - Μία αλφαριθμητική αναπαράσταση της τιμής του τρέχοντος αντικειμένου DateTime.
### toUniversalTime() {#toUniversalTime--}
```
public DateTime toUniversalTime()
```


Μετατρέπει την τιμή του τρέχοντος αντικειμένου DateTime σε Συντονισμένο Παγκόσμιο Χρόνο (UTC).

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

