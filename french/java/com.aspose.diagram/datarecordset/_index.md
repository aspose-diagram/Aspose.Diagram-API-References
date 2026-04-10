---
title: DataRecordSet
second_title: Référence API d'Aspose.Diagram pour Java
description: Stocke les formats, actualise et expose les données interrogées depuis une base de données dans Microsoft Visio.
type: docs
weight: 113
url: /fr/java/com.aspose.diagram/datarecordset/
---

**Inheritance:**
java.lang.Object
```
public class DataRecordSet
```

Stocke, formate, actualise et expose les données interrogées depuis une base de données dans Microsoft Visio.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DataRecordSet()](#DataRecordSet--) | Constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getADOData()](#getADOData--) | Contient du XML conforme au schéma XML classique ADO pour un ensemble d'enregistrements ADO et qui décrit les données dans l'ensemble d'enregistrements de données. |
| [getAutoLinkComparison()](#getAutoLinkComparison--) | Définit une règle qui compare une colonne de l'élément DataRecordset parent avec un élément de données de forme provenant de la dernière action de liaison automatique réussie effectuée dans l'interface utilisateur. |
| [getChecksum()](#getChecksum--) | Une valeur de somme de contrôle, générée par Visio, et basée sur les propriétés de l'ensemble d'enregistrements de données. |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | La chaîne de commande utilisée pour interroger les données depuis la source de données. |
| [getConnectionID()](#getConnectionID--) | L'ID de connexion pour l'objet DataConnection associé. |
| [getDataColumns()](#getDataColumns--) | Contient tous les éléments DataColumn dans un ensemble d'enregistrements de données. |
| [getID()](#getID--) | L'ID de l'ensemble d'enregistrements de données, unique dans le document. |
| [getName()](#getName--) | Le nom d'affichage (ou « convivial ») de l'ensemble d'enregistrements de données. |
| [getNextRowID()](#getNextRowID--) | L'ID de ligne Visio suivant disponible. |
| [getOptions()](#getOptions--) | Options à appliquer à l'ensemble d'enregistrements de données. |
| [getPrimaryKeys()](#getPrimaryKeys--) | Identifie une ou plusieurs colonnes de clé primaire dans l'ensemble d'enregistrements de données. |
| [getRefreshConflicts()](#getRefreshConflicts--) | Indique une ligne de l'ensemble d'enregistrements de données liée à une forme qui est en conflit après le rafraîchissement de l'ensemble d'enregistrements de données. |
| [getRefreshInterval()](#getRefreshInterval--) | Fréquence (en minutes) à laquelle Visio rafraîchit automatiquement l'ensemble d'enregistrements de données. |
| [getRefreshNoReconciliationUI()](#getRefreshNoReconciliationUI--) | Indique si l'interface utilisateur de réconciliation des données doit être désactivée. |
| [getRefreshOverwriteAll()](#getRefreshOverwriteAll--) | Indique s'il faut écraser les modifications utilisateur des éléments de données de forme dans les formes liées aux données lorsque l'ensemble d'enregistrements de données est rafraîchi. |
| [getReplaceLinks()](#getReplaceLinks--) | Définit comment les liens forme-données sont traités lorsque les formes sont copiées ou coupées. 1 pour remplacer les liens existants dans la forme cible. 0 pour conserver les liens existants dans la forme cible. |
| [getRowMaps()](#getRowMaps--) | Mappe une ligne de l'ensemble d'enregistrements de données à une forme. |
| [getRowOrder()](#getRowOrder--) | Indique s'il faut utiliser l'ordre des lignes dans l'ensemble d'enregistrements de données comme clé primaire. |
| [getTimeRefreshed()](#getTimeRefreshed--) | La date et l'heure du dernier rafraîchissement de l'ensemble d'enregistrements de données. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refresh(int connectionType)](#refresh-int-) | Exécute la chaîne de requête associée à l'ensemble d'enregistrements de données connecté (non basé sur XML) et met à jour les formes liées avec les nouvelles données de la source de données retournées par la requête. |
| [setADOData(String value)](#setADOData-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--) |
| [setChecksum(long value)](#setChecksum-long-) | Pour la description de cette propriété, veuillez consulter \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\} |
| [setCommand(String value)](#setCommand-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--) |
| [setConnectionID(long value)](#setConnectionID-long-) | Pour la description de cette propriété, veuillez consulter \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\} |
| [setID(long value)](#setID-long-) | Pour la description de cette propriété, veuillez consulter \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\} |
| [setName(String value)](#setName-java.lang.String-) | Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/datarecordset\#getName--) |
| [setNextRowID(long value)](#setNextRowID-long-) | Pour la description de cette propriété, veuillez consulter \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\} |
| [setOptions(int value)](#setOptions-int-) | Pour la description de cette propriété, veuillez consulter [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--) |
| [setRefreshInterval(long value)](#setRefreshInterval-long-) | Pour la description de cette propriété, veuillez consulter \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\} |
| [setRefreshNoReconciliationUI(int value)](#setRefreshNoReconciliationUI-int-) | Pour la description de cette propriété, veuillez consulter [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--) |
| [setRefreshOverwriteAll(int value)](#setRefreshOverwriteAll-int-) | Pour la description de cette propriété, veuillez consulter [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--) |
| [setReplaceLinks(int value)](#setReplaceLinks-int-) | Pour la description de cette propriété, veuillez consulter [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--) |
| [setRowOrder(int value)](#setRowOrder-int-) | Pour la description de cette propriété, veuillez consulter [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--) |
| [setTimeRefreshed(DateTime value)](#setTimeRefreshed-com.aspose.diagram.DateTime-) | Pour la description de cette propriété, veuillez consulter [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataRecordSet() {#DataRecordSet--}
```
public DataRecordSet()
```


Constructeur.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getADOData() {#getADOData--}
```
public String getADOData()
```


Contient du XML conforme au schéma XML classique ADO pour un ensemble d'enregistrements ADO et qui décrit les données dans l'ensemble d'enregistrements de données.

**Returns:**
java.lang.String
### getAutoLinkComparison() {#getAutoLinkComparison--}
```
public AutoLinkComparison getAutoLinkComparison()
```


Définit une règle qui compare une colonne de l'élément DataRecordset parent avec un élément de données de forme provenant de la dernière action de liaison automatique réussie effectuée dans l'interface utilisateur.

**Returns:**
[AutoLinkComparison](../../com.aspose.diagram/autolinkcomparison)
### getChecksum() {#getChecksum--}
```
public long getChecksum()
```


Une valeur de somme de contrôle, générée par Visio, et basée sur les propriétés du jeu d’enregistrements de données. Définissez cet attribut à 0 ; Visio recalcule cette valeur à l’exécution.

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


La chaîne de commande utilisée pour interroger les données depuis la source de données.

**Returns:**
java.lang.String
### getConnectionID() {#getConnectionID--}
```
public long getConnectionID()
```


L’ID de connexion pour l’objet DataConnection associé. N’existe pas pour les sources de données XML.

**Returns:**
long
### getDataColumns() {#getDataColumns--}
```
public DataColumnCollection getDataColumns()
```


Contient tous les éléments DataColumn dans un ensemble d'enregistrements de données.

**Returns:**
[DataColumnCollection](../../com.aspose.diagram/datacolumncollection)
### getID() {#getID--}
```
public long getID()
```


L'ID de l'ensemble d'enregistrements de données, unique dans le document.

**Returns:**
long
### getName() {#getName--}
```
public String getName()
```


Le nom d'affichage (ou « convivial ») de l'ensemble d'enregistrements de données.

**Returns:**
java.lang.String
### getNextRowID() {#getNextRowID--}
```
public long getNextRowID()
```


L'ID de ligne Visio suivant disponible.

**Returns:**
long
### getOptions() {#getOptions--}
```
public int getOptions()
```


Options à appliquer au jeu d’enregistrements de données. Les valeurs possibles peuvent être n’importe quelle combinaison d’une ou plusieurs de celles affichées dans le tableau suivant.

**Returns:**
int
### getPrimaryKeys() {#getPrimaryKeys--}
```
public ArrayList<String> getPrimaryKeys()
```


Identifie une ou plusieurs colonnes de clé primaire dans l'ensemble d'enregistrements de données.

**Returns:**
java.util.ArrayList<java.lang.String>
### getRefreshConflicts() {#getRefreshConflicts--}
```
public RowCollection getRefreshConflicts()
```


Indique une ligne du jeu d’enregistrements de données liée à une forme qui est en conflit après le rafraîchissement du jeu d’enregistrements de données. RowID - Indique une ligne du jeu d’enregistrements de données liée à une forme qui est en conflit après le rafraîchissement du jeu d’enregistrements de données. ShapeID - Identifiant de la forme impliquée dans le conflit. PageID - Identifiant de la page de la forme impliquée dans le conflit.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRefreshInterval() {#getRefreshInterval--}
```
public long getRefreshInterval()
```


Fréquence (en minutes) à laquelle Visio rafraîchit automatiquement le jeu d’enregistrements de données. Cette valeur doit être supérieure ou égale à 1.

**Returns:**
long
### getRefreshNoReconciliationUI() {#getRefreshNoReconciliationUI--}
```
public int getRefreshNoReconciliationUI()
```


Indique si l’interface utilisateur de réconciliation des données doit être désactivée. Vrai (1) pour désactiver l’interface utilisateur (UI). Faux (0) pour activer l’UI.

**Returns:**
int
### getRefreshOverwriteAll() {#getRefreshOverwriteAll--}
```
public int getRefreshOverwriteAll()
```


Indique s'il faut écraser les modifications utilisateur des éléments de données de forme dans les formes liées aux données lorsque l'ensemble d'enregistrements de données est rafraîchi.

**Returns:**
int
### getReplaceLinks() {#getReplaceLinks--}
```
public int getReplaceLinks()
```


Définit la façon dont les liens forme-données sont traités lorsque les formes sont copiées ou coupées. 1 pour remplacer les liens existants dans la forme cible. 0 pour conserver les liens existants dans la forme cible. Si cet attribut est absent, Visio demande à l’utilisateur s’il faut remplacer les liens lors de la copie ou de la coupe.

**Returns:**
int
### getRowMaps() {#getRowMaps--}
```
public RowCollection getRowMaps()
```


Mappe une ligne du jeu d’enregistrements de données à une forme. RowID - Identifiant de la ligne, unique dans le jeu d’enregistrements de données. ShapeID - Identifiant de la forme liée aux données de la ligne du jeu d’enregistrements de données identifiée par RowID. PageID - Identifiant de la page de la forme liée aux données de la ligne du jeu d’enregistrements de données identifiée par RowID.

**Returns:**
[RowCollection](../../com.aspose.diagram/rowcollection)
### getRowOrder() {#getRowOrder--}
```
public int getRowOrder()
```


Indique s’il faut utiliser l’ordre des lignes du jeu d’enregistrements de données comme clé primaire. Vrai (1) si les ID de ligne sont déterminés par l’ordre des lignes. Faux (0) si les ID de ligne sont déterminés par les valeurs des colonnes de clé primaire du jeu d’enregistrements de données.

**Returns:**
int
### getTimeRefreshed() {#getTimeRefreshed--}
```
public DateTime getTimeRefreshed()
```


La date et l'heure du dernier rafraîchissement de l'ensemble d'enregistrements de données.

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


Exécute la chaîne de requête associée à l'ensemble d'enregistrements de données connecté (non basé sur XML) et met à jour les formes liées avec les nouvelles données de la source de données retournées par la requête.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| connectionType | int | Le type de fournisseur qui sera utilisé pour la connexion Aspose.Diagram.Manipulation.DataConnectionType. |

### setADOData(String value) {#setADOData-java.lang.String-}
```
public void setADOData(String value)
```


Pour la description de cette propriété, veuillez consulter [getADOData()](../../com.aspose.diagram/datarecordset\#getADOData--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setChecksum(long value) {#setChecksum-long-}
```
public void setChecksum(long value)
```


Pour la description de cette propriété, veuillez consulter \{@link DataRecordSet\#(getChecksum() & 0xFFFFFFFFL)\}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


Pour la description de cette propriété, veuillez consulter [getCommand()](../../com.aspose.diagram/datarecordset\#getCommand--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setConnectionID(long value) {#setConnectionID-long-}
```
public void setConnectionID(long value)
```


Pour la description de cette propriété, veuillez consulter \{@link DataRecordSet\#(getConnectionID() & 0xFFFFFFFFL)\}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


Pour la description de cette propriété, veuillez consulter \{@link DataRecordSet\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Pour la description de cette propriété, veuillez consulter [getName()](../../com.aspose.diagram/datarecordset\#getName--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setNextRowID(long value) {#setNextRowID-long-}
```
public void setNextRowID(long value)
```


Pour la description de cette propriété, veuillez consulter \{@link DataRecordSet\#(getNextRowID() & 0xFFFFFFFFL)\}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Pour la description de cette propriété, veuillez consulter [getOptions()](../../com.aspose.diagram/datarecordset\#getOptions--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRefreshInterval(long value) {#setRefreshInterval-long-}
```
public void setRefreshInterval(long value)
```


Pour la description de cette propriété, veuillez consulter \{@link DataRecordSet\#(getRefreshInterval() & 0xFFFFFFFFL)\}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setRefreshNoReconciliationUI(int value) {#setRefreshNoReconciliationUI-int-}
```
public void setRefreshNoReconciliationUI(int value)
```


Pour la description de cette propriété, veuillez consulter [getRefreshNoReconciliationUI()](../../com.aspose.diagram/datarecordset\#getRefreshNoReconciliationUI--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRefreshOverwriteAll(int value) {#setRefreshOverwriteAll-int-}
```
public void setRefreshOverwriteAll(int value)
```


Pour la description de cette propriété, veuillez consulter [getRefreshOverwriteAll()](../../com.aspose.diagram/datarecordset\#getRefreshOverwriteAll--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setReplaceLinks(int value) {#setReplaceLinks-int-}
```
public void setReplaceLinks(int value)
```


Pour la description de cette propriété, veuillez consulter [getReplaceLinks()](../../com.aspose.diagram/datarecordset\#getReplaceLinks--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRowOrder(int value) {#setRowOrder-int-}
```
public void setRowOrder(int value)
```


Pour la description de cette propriété, veuillez consulter [getRowOrder()](../../com.aspose.diagram/datarecordset\#getRowOrder--)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setTimeRefreshed(DateTime value) {#setTimeRefreshed-com.aspose.diagram.DateTime-}
```
public void setTimeRefreshed(DateTime value)
```


Pour la description de cette propriété, veuillez consulter [getTimeRefreshed()](../../com.aspose.diagram/datarecordset\#getTimeRefreshed--)

**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

