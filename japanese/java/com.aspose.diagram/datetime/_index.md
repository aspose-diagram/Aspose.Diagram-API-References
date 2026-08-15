---
title: DateTime
second_title: Aspose.Diagram for Java API リファレンス
description: 通常、日付と時刻として表される瞬間を表します。
type: docs
weight: 115
url: /ja/java/com.aspose.diagram/datetime/
---

**Inheritance:**
java.lang.Object
```
public class DateTime
```

通常、日付と時刻として表される特定の時点を表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DateTime(int year, int month, int day)](#DateTime-int-int-int-) | 指定された年、月、日で DateTime オブジェクトの新しいインスタンスを初期化します。 |
| [DateTime(int year, int month, int day, int hour, int minute, int second)](#DateTime-int-int-int-int-int-int-) | 指定された年、月、日、時、分、秒で DateTime オブジェクトの新しいインスタンスを初期化します。 |
| [DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)](#DateTime-int-int-int-int-int-int-int-) | 指定された年、月、日、時、分、秒、ミリ秒で DateTime オブジェクトの新しいインスタンスを初期化します。 |
| [DateTime(Date date)](#DateTime-java.util.Date-) | 指定された Date オブジェクトで DateTime オブジェクトの新しいインスタンスを初期化します。 |
| [DateTime(Calendar cld)](#DateTime-java.util.Calendar-) | 指定された Calendar オブジェクトで DateTime オブジェクトの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addDays(double value)](#addDays-double-) | このインスタンスの値に指定された日数を加算します。 |
| [addHours(double value)](#addHours-double-) | このインスタンスの値に指定された時間数を加算します。 |
| [addMilliseconds(double value)](#addMilliseconds-double-) | このインスタンスの値に指定されたミリ秒数を加算します。 |
| [addMinutes(double value)](#addMinutes-double-) | このインスタンスの値に指定された分数を加算します。 |
| [addMonths(int months)](#addMonths-int-) | このインスタンスの値に指定された月数を加算します。 |
| [addSeconds(double value)](#addSeconds-double-) | このインスタンスの値に指定された秒数を加算します。 |
| [addYears(int value)](#addYears-int-) | このインスタンスの値に指定された年数を加算します。 |
| [compareTo(DateTime value)](#compareTo-com.aspose.diagram.DateTime-) | このインスタンスの値を指定された DateTime 値と比較し、このインスタンスが指定された DateTime 値より前か、同じか、後かを示す整数を返します。 |
| [compareTo(Object value)](#compareTo-java.lang.Object-) | このインスタンスの値を、指定された DateTime 値を含むオブジェクトと比較し、このインスタンスがその DateTime 値より前か、同じか、後かを示す整数を返します。 |
| [equals(Object value)](#equals-java.lang.Object-) | このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getDay()](#getDay--) | このインスタンスが表す月の日を取得します。 |
| [getDayOfWeek()](#getDayOfWeek--) | このインスタンスが表す曜日を取得します。 |
| [getDayOfYear()](#getDayOfYear--) | このインスタンスが表す年の日を取得します。 |
| [getHour()](#getHour--) | このインスタンスが表す日付の時間コンポーネントを取得します。 |
| [getMillisecond()](#getMillisecond--) | このインスタンスが表す日付のミリ秒コンポーネントを取得します。 |
| [getMinute()](#getMinute--) | このインスタンスが表す日付の分コンポーネントを取得します。 |
| [getMonth()](#getMonth--) | このインスタンスが表す日付の月コンポーネントを取得します。 |
| [getNow()](#getNow--) | このコンピューターの現在の日付と時刻をローカル時間として設定した DateTime オブジェクトを取得します。 |
| [getSecond()](#getSecond--) | このインスタンスが表す日付の秒コンポーネントを取得します。 |
| [getYear()](#getYear--) | このインスタンスが表す日付の年コンポーネントを取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toCalendar()](#toCalendar--) | 現在の DateTime オブジェクトの値を Calendar オブジェクトに変換します。 |
| [toDate()](#toDate--) | 現在の DateTime オブジェクトの値を Date オブジェクトに変換します。 |
| [toLocalTime()](#toLocalTime--) | 現在の DateTime オブジェクトの値をローカル時間に変換します。 |
| [toString()](#toString--) | 現在の DateTime オブジェクトの値を等価な文字列表現に変換します。 |
| [toUniversalTime()](#toUniversalTime--) | 現在の DateTime オブジェクトの値を協定世界時 (UTC) に変換します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DateTime(int year, int month, int day) {#DateTime-int-int-int-}
```
public DateTime(int year, int month, int day)
```


指定された年、月、日で DateTime オブジェクトの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 年 | int | 年 (1 から 9999)。 |
| 月 | int | 月 (1 から 12)。 |
| 日 | int | 日 (1 からその月の日数まで)。 |

### DateTime(int year, int month, int day, int hour, int minute, int second) {#DateTime-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second)
```


指定された年、月、日、時、分、秒で DateTime オブジェクトの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 年 | int | 年 (1 から 9999)。 |
| 月 | int | 月 (1 から 12)。 |
| 日 | int | 日 (1 からその月の日数まで)。 |
| 時 | int | 時 (0 から 23)。 |
| 分 | int | 分 (0 から 59)。 |
| 秒 | int | 秒 (0 から 59)。 |

### DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond) {#DateTime-int-int-int-int-int-int-int-}
```
public DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond)
```


指定された年、月、日、時、分、秒、ミリ秒で DateTime オブジェクトの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 年 | int | 年 (1 から 9999)。 |
| 月 | int | 月 (1 から 12)。 |
| 日 | int | 日 (1 からその月の日数まで)。 |
| 時 | int | 時 (0 から 23)。 |
| 分 | int | 分 (0 から 59)。 |
| 秒 | int | 秒 (0 から 59)。 |
| ミリ秒 | int | ミリ秒 (0 から 999)。 |

### DateTime(Date date) {#DateTime-java.util.Date-}
```
public DateTime(Date date)
```


指定された Date オブジェクトで DateTime オブジェクトの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 日付 | java.util.Date | Date オブジェクト |

### DateTime(Calendar cld) {#DateTime-java.util.Calendar-}
```
public DateTime(Calendar cld)
```


指定された Calendar オブジェクトで DateTime オブジェクトの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cld | java.util.Calendar | Calendar オブジェクト |

### addDays(double value) {#addDays-double-}
```
public DateTime addDays(double value)
```


このインスタンスの値に指定された日数を加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 整数部と小数部を含む日数。value パラメーターは負の値または正の値にできます。 |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of days represented by value.
### addHours(double value) {#addHours-double-}
```
public DateTime addHours(double value)
```


このインスタンスの値に指定された時間数を加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 整数部と小数部を含む時間数。value パラメーターは負の値または正の値にできます。 |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of hours represented by value.
### addMilliseconds(double value) {#addMilliseconds-double-}
```
public DateTime addMilliseconds(double value)
```


このインスタンスの値に指定されたミリ秒数を加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 整数部と小数部を含むミリ秒数。value パラメーターは負の値または正の値にできます。この値は最も近い整数に丸められることに注意してください。 |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of milliseconds represented by value.
### addMinutes(double value) {#addMinutes-double-}
```
public DateTime addMinutes(double value)
```


このインスタンスの値に指定された分数を加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 整数部と小数部を含む分数。value パラメーターは負の値または正の値にできます。 |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of minutes represented by value.
### addMonths(int months) {#addMonths-int-}
```
public DateTime addMonths(int months)
```


このインスタンスの値に指定された月数を加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 月 | int | 月数。months パラメーターは負の値または正の値にできます。 |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and months.
### addSeconds(double value) {#addSeconds-double-}
```
public DateTime addSeconds(double value)
```


このインスタンスの値に指定された秒数を加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 整数部と小数部を含む秒数。value パラメーターは負の値または正の値にできます。 |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of seconds represented by value.
### addYears(int value) {#addYears-int-}
```
public DateTime addYears(int value)
```


このインスタンスの値に指定された年数を加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 年数。value パラメーターは負の値または正の値にできます。 |

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the sum of the date and time represented by this instance and the number of years represented by value.
### compareTo(DateTime value) {#compareTo-com.aspose.diagram.DateTime-}
```
public int compareTo(DateTime value)
```


このインスタンスの値を指定された DateTime 値と比較し、このインスタンスが指定された DateTime 値より前か、同じか、後かを示す整数を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) | 比較対象の DateTime オブジェクト。 |

**Returns:**
int - このインスタンスと value パラメーターの相対的な値を示す符号付き数。値の説明: ゼロ未満 このインスタンスは value より前です。ゼロ このインスタンスは value と同じです。ゼロより大きい このインスタンスは value より後です。
### compareTo(Object value) {#compareTo-java.lang.Object-}
```
public int compareTo(Object value)
```


このインスタンスの値を、指定された DateTime 値を含むオブジェクトと比較し、このインスタンスがその DateTime 値より前か、同じか、後かを示す整数を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object | 比較対象のボックス化された DateTime オブジェクト、または null。 |

**Returns:**
int - このインスタンスと value の相対的な値を示す符号付き数。値の説明: ゼロ未満 このインスタンスは value より前です。ゼロ このインスタンスは value と同じです。ゼロより大きい このインスタンスは value より後です。または value が null の場合。
### equals(Object value) {#equals-java.lang.Object-}
```
public boolean equals(Object value)
```


このインスタンスが指定されたオブジェクトと等しいかどうかを示す値を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object | このインスタンスと比較するオブジェクト。 |

**Returns:**
boolean - value が DateTime のインスタンスであり、このインスタンスの値と等しい場合は true。そうでなければ false。
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


このインスタンスが表す月の日を取得します。

**Returns:**
int - 1 から 31 の範囲で表される日コンポーネント。
### getDayOfWeek() {#getDayOfWeek--}
```
public int getDayOfWeek()
```


このインスタンスが表す曜日を取得します。

**Returns:**
int - この DateTime 値の曜日。
### getDayOfYear() {#getDayOfYear--}
```
public int getDayOfYear()
```


このインスタンスが表す年の日を取得します。

**Returns:**
int - 年の日（1 から 366 の値で表されます）。
### getHour() {#getHour--}
```
public int getHour()
```


このインスタンスが表す日付の時間コンポーネントを取得します。

**Returns:**
int - 時間コンポーネント（0 から 23 の値で表されます）。
### getMillisecond() {#getMillisecond--}
```
public int getMillisecond()
```


このインスタンスが表す日付のミリ秒コンポーネントを取得します。

**Returns:**
int - ミリ秒コンポーネント（0 から 999 の値で表されます）。
### getMinute() {#getMinute--}
```
public int getMinute()
```


このインスタンスが表す日付の分コンポーネントを取得します。

**Returns:**
int - 分コンポーネント（0 から 59 の値で表されます）。
### getMonth() {#getMonth--}
```
public int getMonth()
```


このインスタンスが表す日付の月コンポーネントを取得します。

**Returns:**
int - 月コンポーネント（1 から 12 の値で表されます）。
### getNow() {#getNow--}
```
public static DateTime getNow()
```


このコンピューターの現在の日付と時刻をローカル時間として設定した DateTime オブジェクトを取得します。

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object whose value is the current local date and time.
### getSecond() {#getSecond--}
```
public int getSecond()
```


このインスタンスが表す日付の秒コンポーネントを取得します。

**Returns:**
int - 秒（0 から 59 の範囲）。
### getYear() {#getYear--}
```
public int getYear()
```


このインスタンスが表す日付の年コンポーネントを取得します。

**Returns:**
int - 年（1 から 9999 の範囲）。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
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


現在の DateTime オブジェクトの値を Calendar オブジェクトに変換します。

**Returns:**
[Calendar](../../java.util/calendar) - Calendar object
### toDate() {#toDate--}
```
public Date toDate()
```


現在の DateTime オブジェクトの値を Date オブジェクトに変換します。

**Returns:**
java.util.Date - 日付オブジェクト。
### toLocalTime() {#toLocalTime--}
```
public DateTime toLocalTime()
```


現在の DateTime オブジェクトの値をローカル時間に変換します。

**Returns:**
[DateTime](../../com.aspose.diagram/datetime) - A DateTime object of local
### toString() {#toString--}
```
public String toString()
```


現在の DateTime オブジェクトの値を等価な文字列表現に変換します。

**Returns:**
java.lang.String - 現在の DateTime オブジェクトの値を表す文字列。
### toUniversalTime() {#toUniversalTime--}
```
public DateTime toUniversalTime()
```


現在の DateTime オブジェクトの値を協定世界時 (UTC) に変換します。

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

