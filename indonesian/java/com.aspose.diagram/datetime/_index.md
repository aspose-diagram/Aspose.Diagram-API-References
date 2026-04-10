---
title: DateTime
second_title: Referensi API Aspose.Diagram untuk Java
description: Mewakili suatu momen dalam waktu yang biasanya dinyatakan sebagai tanggal dan waktu hari.
type: docs
weight: 115
url: /id/java/com.aspose.diagram/datetime/
---

**Inheritance:**
java.lang.Object
```
public class DateTime
```

Mewakili suatu momen dalam waktu, biasanya dinyatakan sebagai tanggal dan waktu hari.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DateTime(int year, int month, int day)](#DateTime-int-int-int-) | Menginisialisasi instance baru dari objek DateTime dengan tahun, bulan, dan hari yang ditentukan. |
| [DateTime(int year, int month, int day, int hour, int minute, int second)](#DateTime-int-int-int-int-int-int-) | Menginisialisasi instance baru dari objek DateTime dengan tahun, bulan, hari, jam, menit, dan detik yang ditentukan. |
| [DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)](#DateTime-int-int-int-int-int-int-int-) | Menginisialisasi instance baru dari objek DateTime dengan tahun, bulan, hari, jam, menit, detik, dan milidetik yang ditentukan. |
| [DateTime(Date date)](#DateTime-java.util.Date-) | Menginisialisasi instance baru dari objek DateTime dengan objek Date yang ditentukan. |
| [DateTime(Calendar cld)](#DateTime-java.util.Calendar-) | Menginisialisasi instance baru dari objek DateTime dengan objek Calendar yang ditentukan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addDays(double value)](#addDays-double-) | Menambahkan sejumlah hari yang ditentukan ke nilai instance ini. |
| [addHours(double value)](#addHours-double-) | Menambahkan sejumlah jam yang ditentukan ke nilai instance ini. |
| [addMilliseconds(double value)](#addMilliseconds-double-) | Menambahkan sejumlah milidetik yang ditentukan ke nilai instance ini. |
| [addMinutes(double value)](#addMinutes-double-) | Menambahkan sejumlah menit yang ditentukan ke nilai instance ini. |
| [addMonths(int months)](#addMonths-int-) | Menambahkan sejumlah bulan yang ditentukan ke nilai instance ini. |
| [addSeconds(double value)](#addSeconds-double-) | Menambahkan sejumlah detik yang ditentukan ke nilai instance ini. |
| [addYears(int value)](#addYears-int-) | Menambahkan sejumlah tahun yang ditentukan ke nilai instance ini. |
| [compareTo(DateTime value)](#compareTo-com.aspose.diagram.DateTime-) | Membandingkan nilai instance ini dengan nilai DateTime yang ditentukan dan mengembalikan sebuah integer yang menunjukkan apakah instance ini lebih awal, sama, atau lebih lambat daripada nilai DateTime yang ditentukan. |
| [compareTo(Object value)](#compareTo-java.lang.Object-) | Membandingkan nilai instance ini dengan objek yang ditentukan yang berisi nilai DateTime tertentu, dan mengembalikan sebuah integer yang menunjukkan apakah instance ini lebih awal, sama, atau lebih lambat daripada nilai DateTime yang ditentukan. |
| [equals(Object value)](#equals-java.lang.Object-) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan objek yang ditentukan. |
| [getClass()](#getClass--) |  |
| [getDay()](#getDay--) | Mendapatkan hari dalam bulan yang diwakili oleh instance ini. |
| [getDayOfWeek()](#getDayOfWeek--) | Mendapatkan hari dalam minggu yang diwakili oleh instance ini. |
| [getDayOfYear()](#getDayOfYear--) | Mendapatkan hari dalam tahun yang diwakili oleh instance ini. |
| [getHour()](#getHour--) | Mendapatkan komponen jam dari tanggal yang diwakili oleh instance ini. |
| [getMillisecond()](#getMillisecond--) | Mendapatkan komponen milidetik dari tanggal yang diwakili oleh instance ini. |
| [getMinute()](#getMinute--) | Mendapatkan komponen menit dari tanggal yang diwakili oleh instance ini. |
| [getMonth()](#getMonth--) | Mendapatkan komponen bulan dari tanggal yang diwakili oleh instance ini. |
| [getNow()](#getNow--) | Mendapatkan objek DateTime yang diatur ke tanggal dan waktu saat ini pada komputer ini, dinyatakan sebagai waktu lokal. |
| [getSecond()](#getSecond--) | Mendapatkan komponen detik dari tanggal yang diwakili oleh instance ini. |
| [getYear()](#getYear--) | Mendapatkan komponen tahun dari tanggal yang diwakili oleh instance ini. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toCalendar()](#toCalendar--) | Mengonversi nilai objek DateTime saat ini ke objek Calendar. |
| [toDate()](#toDate--) | Mengonversi nilai objek DateTime saat ini ke objek Date. |
| [toLocalTime()](#toLocalTime--) | Mengonversi nilai objek DateTime saat ini ke waktu lokal. |
| [toString()](#toString--) | Mengonversi nilai objek DateTime saat ini ke representasi string yang setara. |
| [toUniversalTime()](#toUniversalTime--) | Mengonversi nilai objek DateTime saat ini ke Waktu Universal Terkoordinasi (UTC). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DateTime(int year, int month, int day) {#DateTime-int-int-int-}
```
public DateTime(int year, int month, int day)
```


Menginisialisasi instance baru dari objek DateTime dengan tahun, bulan, dan hari yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tahun | int | Tahun (1 sampai 9999). |
| bulan | int | Bulan (1 sampai 12). |
| hari | int | Hari (1 sampai jumlah hari dalam bulan). |

### DateTime(int year, int month, int day, int hour, int minute, int second) {#DateTime-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second)
```


Menginisialisasi instance baru dari objek DateTime dengan tahun, bulan, hari, jam, menit, dan detik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tahun | int | Tahun (1 sampai 9999). |
| bulan | int | Bulan (1 sampai 12). |
| hari | int | Hari (1 sampai jumlah hari dalam bulan). |
| jam | int | Jam (0 sampai 23). |
| menit | int | Menit (0 sampai 59). |
| detik | int | Detik (0 hingga 59). |

### DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond) {#DateTime-int-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)
```


Menginisialisasi instance baru dari objek DateTime dengan tahun, bulan, hari, jam, menit, detik, dan milidetik yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tahun | int | Tahun (1 sampai 9999). |
| bulan | int | Bulan (1 sampai 12). |
| hari | int | Hari (1 sampai jumlah hari dalam bulan). |
| jam | int | Jam (0 sampai 23). |
| menit | int | Menit (0 sampai 59). |
| detik | int | Detik (0 hingga 59). |
| milidetik | int | Milidetik (0 hingga 999). |

### DateTime(Date date) {#DateTime-java.util.Date-}
```
public DateTime(Date date)
```


Menginisialisasi instance baru dari objek DateTime dengan objek Date yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tanggal | java.util.Date | Objek Date |

### DateTime(Calendar cld) {#DateTime-java.util.Calendar-}
```
public DateTime(Calendar cld)
```


Menginisialisasi instance baru dari objek DateTime dengan objek Calendar yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cld | java.util.Calendar | Objek Calendar |

### addDays(double value) {#addDays-double-}
```
public DateTime addDays(double value)
```


Menambahkan sejumlah hari yang ditentukan ke nilai instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Jumlah hari penuh dan pecahan. Parameter nilai dapat bernilai negatif atau positif. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of days represented by value.
### addHours(double value) {#addHours-double-}
```
public DateTime addHours(double value)
```


Menambahkan sejumlah jam yang ditentukan ke nilai instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Jumlah jam penuh dan pecahan. Parameter nilai dapat bernilai negatif atau positif. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of hours represented by value.
### addMilliseconds(double value) {#addMilliseconds-double-}
```
public DateTime addMilliseconds(double value)
```


Menambahkan sejumlah milidetik yang ditentukan ke nilai instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Jumlah milidetik penuh dan pecahan. Parameter nilai dapat bernilai negatif atau positif. Catatan bahwa nilai ini dibulatkan ke bilangan bulat terdekat. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of milliseconds represented by value.
### addMinutes(double value) {#addMinutes-double-}
```
public DateTime addMinutes(double value)
```


Menambahkan sejumlah menit yang ditentukan ke nilai instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Jumlah menit penuh dan pecahan. Parameter nilai dapat bernilai negatif atau positif. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of minutes represented by value.
### addMonths(int months) {#addMonths-int-}
```
public DateTime addMonths(int months)
```


Menambahkan sejumlah bulan yang ditentukan ke nilai instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bulan | int | Jumlah bulan. Parameter bulan dapat bernilai negatif atau positif. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and months.
### addSeconds(double value) {#addSeconds-double-}
```
public DateTime addSeconds(double value)
```


Menambahkan sejumlah detik yang ditentukan ke nilai instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Jumlah detik penuh dan pecahan. Parameter nilai dapat bernilai negatif atau positif. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of seconds represented by value.
### addYears(int value) {#addYears-int-}
```
public DateTime addYears(int value)
```


Menambahkan sejumlah tahun yang ditentukan ke nilai instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Jumlah tahun. Parameter nilai dapat bernilai negatif atau positif. |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of years represented by value.
### compareTo(DateTime value) {#compareTo-com.aspose.diagram.DateTime-}
```
public int compareTo(DateTime value)
```


Membandingkan nilai instance ini dengan nilai DateTime yang ditentukan dan mengembalikan sebuah integer yang menunjukkan apakah instance ini lebih awal, sama, atau lebih lambat daripada nilai DateTime yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) | Objek DateTime untuk dibandingkan. |

**Returns:**
int - Sebuah bilangan bertanda yang menunjukkan nilai relatif dari instance ini dan parameter nilai. Deskripsi Nilai Kurang dari nol Instance ini lebih awal daripada nilai. Nol Instance ini sama dengan nilai. Lebih dari nol Instance ini lebih lambat daripada nilai.
### compareTo(Object value) {#compareTo-java.lang.Object-}
```
public int compareTo(Object value)
```


Membandingkan nilai instance ini dengan objek yang ditentukan yang berisi nilai DateTime tertentu, dan mengembalikan sebuah integer yang menunjukkan apakah instance ini lebih awal, sama, atau lebih lambat daripada nilai DateTime yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object | Objek DateTime yang dibungkus untuk dibandingkan, atau null. |

**Returns:**
int - Sebuah bilangan bertanda yang menunjukkan nilai relatif dari instance ini dan nilai. Deskripsi Nilai Kurang dari nol Instance ini lebih awal daripada nilai. Nol Instance ini sama dengan nilai. Lebih dari nol Instance ini lebih lambat daripada nilai, atau nilai adalah null.
### equals(Object value) {#equals-java.lang.Object-}
```
public boolean equals(Object value)
```


Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan objek yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object | Objek untuk dibandingkan dengan instance ini. |

**Returns:**
boolean - true jika nilai adalah instance dari DateTime dan sama dengan nilai instance ini; jika tidak, false.
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


Mendapatkan hari dalam bulan yang diwakili oleh instance ini.

**Returns:**
int - Komponen hari, dinyatakan sebagai nilai antara 1 dan 31.
### getDayOfWeek() {#getDayOfWeek--}
```
public int getDayOfWeek()
```


Mendapatkan hari dalam minggu yang diwakili oleh instance ini.

**Returns:**
int - hari dalam seminggu dari nilai DateTime ini.
### getDayOfYear() {#getDayOfYear--}
```
public int getDayOfYear()
```


Mendapatkan hari dalam tahun yang diwakili oleh instance ini.

**Returns:**
int - Hari dalam tahun, dinyatakan sebagai nilai antara 1 dan 366.
### getHour() {#getHour--}
```
public int getHour()
```


Mendapatkan komponen jam dari tanggal yang diwakili oleh instance ini.

**Returns:**
int - Komponen jam, dinyatakan sebagai nilai antara 0 dan 23.
### getMillisecond() {#getMillisecond--}
```
public int getMillisecond()
```


Mendapatkan komponen milidetik dari tanggal yang diwakili oleh instance ini.

**Returns:**
int - Komponen milidetik, dinyatakan sebagai nilai antara 0 dan 999.
### getMinute() {#getMinute--}
```
public int getMinute()
```


Mendapatkan komponen menit dari tanggal yang diwakili oleh instance ini.

**Returns:**
int - Komponen menit, dinyatakan sebagai nilai antara 0 dan 59.
### getMonth() {#getMonth--}
```
public int getMonth()
```


Mendapatkan komponen bulan dari tanggal yang diwakili oleh instance ini.

**Returns:**
int - Komponen bulan, dinyatakan sebagai nilai antara 1 dan 12.
### getNow() {#getNow--}
```
public static DateTime getNow()
```


Mendapatkan objek DateTime yang diatur ke tanggal dan waktu saat ini pada komputer ini, dinyatakan sebagai waktu lokal.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the current local date and time.
### getSecond() {#getSecond--}
```
public int getSecond()
```


Mendapatkan komponen detik dari tanggal yang diwakili oleh instance ini.

**Returns:**
int - Detik, antara 0 dan 59.
### getYear() {#getYear--}
```
public int getYear()
```


Mendapatkan komponen tahun dari tanggal yang diwakili oleh instance ini.

**Returns:**
int - Tahun, antara 1 dan 9999.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash integer bertanda 32-bit.
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


Mengonversi nilai objek DateTime saat ini ke objek Calendar.

**Returns:**
[Calendar](../../java.util/calendar) - Calendar object
### toDate() {#toDate--}
```
public Date toDate()
```


Mengonversi nilai objek DateTime saat ini ke objek Date.

**Returns:**
java.util.Date - Objek tanggal
### toLocalTime() {#toLocalTime--}
```
public DateTime toLocalTime()
```


Mengonversi nilai objek DateTime saat ini ke waktu lokal.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object of local
### toString() {#toString--}
```
public String toString()
```


Mengonversi nilai objek DateTime saat ini ke representasi string yang setara.

**Returns:**
java.lang.String - Representasi string dari nilai objek DateTime saat ini.
### toUniversalTime() {#toUniversalTime--}
```
public DateTime toUniversalTime()
```


Mengonversi nilai objek DateTime saat ini ke Waktu Universal Terkoordinasi (UTC).

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

