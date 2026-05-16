---
title: DataRecordSet
second_title: Справочник API Aspose.Diagram for Java
description: Хранит форматы обновлений и предоставляет данные, запрошенные из базы данных, в Microsoft Visio.
type: docs
weight: 113
url: /ru/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Хранит, форматирует, обновляет и предоставляет данные, полученные из базы данных в Microsoft Visio.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | Содержит XML, соответствующий классической схеме XML ADO для набора записей ADO и описывающий данные в наборе записей. |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | Определяет правило, сравнивающее столбец в родительском элементе DataRecordset с элементом данных фигуры из последнего успешного автоматического действия связывания, выполненного в пользовательском интерфейсе. |
| [getChecksum()](#getChecksum--) | Значение контрольной суммы, сгенерированное Visio и основанное на свойствах набора данных. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Строка команды, используемая для запроса данных из источника данных. |
| [getConnectionID()](#getConnectionID--) | Идентификатор соединения для связанного объекта DataConnection. |
| [getDataColumns()](#getDataColumns--) | Содержит все элементы DataColumn в наборе данных. |
| [getID()](#getID--) | Идентификатор набора данных, уникальный в пределах документа. |
| [getName()](#getName--) | Отображаемое (или «дружественное») имя набора данных. |
| [getNextRowID()](#getNextRowID--) | Следующий доступный идентификатор строки Visio. |
| [getOptions()](#getOptions--) | Параметры, применяемые к набору данных. |
| [getPrimaryKeys()](#getPrimaryKeys--) | Определяет один или несколько столбцов первичного ключа в наборе данных. |
| [getRefreshConflicts()](#getRefreshConflicts--) | Указывает строку в наборе данных, связанную с фигурой, находящейся в конфликте после обновления набора данных. |
| [getRefreshInterval()](#getRefreshInterval--) | Как часто (в минутах) Visio автоматически обновляет набор данных. |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | Нужно ли отключить пользовательский интерфейс согласования данных. |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | Нужно ли перезаписывать пользовательские изменения элементов данных фигур в фигурах, связанных с данными, при обновлении набора данных. |
| [getReplaceLinks()](#getReplaceLinks--) | Определяет, как обрабатываются ссылки данных фигур при копировании или вырезании фигур. 1 — заменять существующие ссылки в целевой фигуре. 0 — сохранять существующие ссылки в целевой фигуре. |
| [getRowMaps()](#getRowMaps--) | Отображает строку набора данных на фигуру. |
| [getRowOrder()](#getRowOrder--) | Нужно ли использовать порядок строк в наборе данных в качестве первичного ключа. |
| [getTimeRefreshed()](#getTimeRefreshed--) | Дата и время последнего обновления набора данных. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | Выполняет строку запроса, связанную с подключённым (не основанным на XML) DataRecordset, и обновляет связанные фигуры новыми данными из источника данных, возвращёнными запросом. |
| [setADOData(String value)](#setADOData-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | Для описания этого свойства, пожалуйста, смотрите \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | Для описания этого свойства, пожалуйста, смотрите [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | Для описания этого свойства, пожалуйста, смотрите \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | Для описания этого свойства, пожалуйста, смотрите \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | Для описания этого свойства, пожалуйста, см. \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | Для описания этого свойства, пожалуйста, см. [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | Для описания этого свойства, пожалуйста, см. \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | Для описания этого свойства, пожалуйста, см. [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | Для описания этого свойства, пожалуйста, см. [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | Для описания этого свойства, пожалуйста, см. [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | Для описания этого свойства, пожалуйста, см. [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | Для описания этого свойства, пожалуйста, см. [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
```


Конструктор.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getADOData() {#getADOData--}
```
public String getADOData()
```


Содержит XML, соответствующий классической схеме XML ADO для набора записей ADO и описывающий данные в наборе записей.

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


Определяет правило, сравнивающее столбец в родительском элементе DataRecordset с элементом данных фигуры из последнего успешного автоматического действия связывания, выполненного в пользовательском интерфейсе.

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


Контрольная сумма, генерируемая Visio и основанная на свойствах набора данных. Установите этот атрибут в 0; Visio пересчитывает это значение во время выполнения.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCommand() {#getCommand--}
```
public String getCommand()
```


Строка команды, используемая для запроса данных из источника данных.

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


Идентификатор соединения для связанного объекта DataConnection. Не существует для XML-источников данных.

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


Содержит все элементы DataColumn в наборе данных.

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


Идентификатор набора данных, уникальный в пределах документа.

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


Отображаемое (или «дружественное») имя набора данных.

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


Следующий доступный идентификатор строки Visio.

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


Параметры, применяемые к набору данных. Возможные значения могут быть любой комбинацией одного или нескольких из показанных в следующей таблице.

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


Определяет один или несколько столбцов первичного ключа в наборе данных.

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


Указывает строку в наборе данных, связанную с фигурой, находящейся в конфликте после обновления набора данных. RowID — Указывает строку в наборе данных, связанную с фигурой, находящейся в конфликте после обновления набора данных. ShapeID — Идентификатор фигуры, участвующей в конфликте. PageID — Идентификатор страницы фигуры, участвующей в конфликте.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


Как часто (в минутах) Visio автоматически обновляет набор данных. Это значение должно быть 1 или больше.

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


Определяет, следует ли отключить пользовательский интерфейс согласования данных. True (1) — отключить интерфейс (UI). False (0) — включить интерфейс.

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


Нужно ли перезаписывать пользовательские изменения элементов данных фигур в фигурах, связанных с данными, при обновлении набора данных.

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


Определяет, как обрабатываются ссылки данных фигур при копировании или вырезании фигур. 1 — заменять существующие ссылки в целевой фигуре. 0 — сохранять существующие ссылки в целевой фигуре. Если этот атрибут отсутствует, Visio спрашивает пользователя, заменять ли ссылки при копировании или вырезании.

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


Отображает строку набора данных на фигуру. RowID — идентификатор строки, уникальный в наборе данных. ShapeID — идентификатор фигуры, связанной с данными в строке набора данных, определенной RowID. PageID — идентификатор страницы фигуры, связанной с данными в строке набора данных, определенной RowID.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


Определяет, использовать ли порядок строк в наборе данных в качестве первичного ключа. True (1) — если идентификаторы строк определяются порядком строк. False (0) — если идентификаторы строк определяются значениями в столбце(цах) первичного ключа набора данных.

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


Дата и время последнего обновления набора данных.

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
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




### refresh(int connectionType) {#refresh-int-}
```
public void refresh(int connectionType)
```


Выполняет строку запроса, связанную с подключённым (не основанным на XML) DataRecordset, и обновляет связанные фигуры новыми данными из источника данных, возвращёнными запросом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| connectionType | int | Тип провайдера, который будет использоваться для connectionAspose.Diagram.Manipulation.DataConnectionType. |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


Для описания этого свойства, пожалуйста, смотрите \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


Для описания этого свойства, пожалуйста, смотрите [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


Для описания этого свойства, пожалуйста, смотрите \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Для описания этого свойства, пожалуйста, смотрите \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Для описания этого свойства, пожалуйста, см. [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


Для описания этого свойства, пожалуйста, см. \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Для описания этого свойства, пожалуйста, см. [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


Для описания этого свойства, пожалуйста, см. \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


Для описания этого свойства, пожалуйста, см. [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


Для описания этого свойства, пожалуйста, см. [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


Для описания этого свойства, пожалуйста, см. [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


Для описания этого свойства, пожалуйста, см. [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


Для описания этого свойства, пожалуйста, см. [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

