---
title: OptionsValue
second_title: Aspose.Diagram for Java API Reference
description: Optional unsigned integer.
type: docs
weight: 257
url: /java/com.aspose.diagram/optionsvalue/
---

**Inheritance:**
java.lang.Object
```
public final class OptionsValue
```

Optional unsigned integer. Options to apply to the data recordset. Possible values can be any combination of one or more of those shown in the following table.
## Fields

| Field | Description |
| --- | --- |
| [DELAY_QUERY](#DELAY-QUERY) | Does not execute the command-string query until the next time the data recordset is refreshed. |
| [NO_ADV_CONFIG](#NO-ADV-CONFIG) | Limits the control users have of how the data recordset is refreshed in the Configure Refresh dialog box for the data recordset. |
| [NO_EXTERNAL_DATA_UI](#NO-EXTERNAL-DATA-UI) | Prevents data in the data recordset from being displayed in the External Data window. |
| [NO_LINK_ON_PASTE](#NO-LINK-ON-PASTE) | Does not copy shape-data links to the Clipboard when shapes are copied or cut. |
| [NO_REFRESH_UI](#NO-REFRESH-UI) | Prevents the data recordset from being displayed in the Refresh Data dialog box. |
| [UNDEFINED](#UNDEFINED) | Undefined. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DELAY_QUERY {#DELAY-QUERY}
```
public static final int DELAY_QUERY
```


Does not execute the command-string query until the next time the data recordset is refreshed.

### NO_ADV_CONFIG {#NO-ADV-CONFIG}
```
public static final int NO_ADV_CONFIG
```


Limits the control users have of how the data recordset is refreshed in the Configure Refresh dialog box for the data recordset. In particular, users cannot change the primary key or specify when shape data should be overwritten; however, users can set the refresh interval and can change the data source.

### NO_EXTERNAL_DATA_UI {#NO-EXTERNAL-DATA-UI}
```
public static final int NO_EXTERNAL_DATA_UI
```


Prevents data in the data recordset from being displayed in the External Data window.

### NO_LINK_ON_PASTE {#NO-LINK-ON-PASTE}
```
public static final int NO_LINK_ON_PASTE
```


Does not copy shape-data links to the Clipboard when shapes are copied or cut.

### NO_REFRESH_UI {#NO-REFRESH-UI}
```
public static final int NO_REFRESH_UI
```


Prevents the data recordset from being displayed in the Refresh Data dialog box.

### UNDEFINED {#UNDEFINED}
```
public static final int UNDEFINED
```


Undefined.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

