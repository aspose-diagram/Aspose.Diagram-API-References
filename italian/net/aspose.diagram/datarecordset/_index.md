---
title: DataRecordSet
second_title: Aspose.Diagram per riferimento API .NET
description: Memorizza formatta aggiorna ed espone i dati interrogati da un database in Microsoft Visio.
type: docs
weight: 1140
url: /it/net/aspose.diagram/datarecordset/
---
## DataRecordSet class

Memorizza, formatta, aggiorna ed espone i dati interrogati da un database in Microsoft Visio.

```csharp
public class DataRecordSet
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DataRecordSet](datarecordset/)() | Costruttore. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ADOData](../../aspose.diagram/datarecordset/adodata/) { get; set; } | Contiene XML conforme allo schema XML classico ADO per un recordset ADO e che descrive i dati nel recordset di dati. |
| [AutoLinkComparison](../../aspose.diagram/datarecordset/autolinkcomparison/) { get; } | Definisce una regola che confronta una colonna nell'elemento DataRecordset padre con un elemento di dati shape dall'ultima azione di collegamento automatico eseguita correttamente nell'interfaccia utente. |
| [Checksum](../../aspose.diagram/datarecordset/checksum/) { get; set; } | Un valore di checksum, generato da Visio e basato sulle proprietà del recordset di dati. Imposta questo attributo su 0; Visio ricalcola questo valore in fase di esecuzione. |
| [Command](../../aspose.diagram/datarecordset/command/) { get; set; } | La stringa di comando utilizzata per interrogare i dati dall'origine dati. |
| [ConnectionID](../../aspose.diagram/datarecordset/connectionid/) { get; set; } | L'ID connessione per l'oggetto DataConnection associato. Non esiste per origini dati XML. |
| [DataColumns](../../aspose.diagram/datarecordset/datacolumns/) { get; } | Contiene tutti gli elementi DataColumn in un recordset di dati. |
| [ID](../../aspose.diagram/datarecordset/id/) { get; set; } | L'ID del recordset di dati, univoco all'interno del documento. |
| [Name](../../aspose.diagram/datarecordset/name/) { get; set; } | Il nome visualizzato (o "descrittivo") del recordset di dati. |
| [NextRowID](../../aspose.diagram/datarecordset/nextrowid/) { get; set; } | Il successivo ID riga Visio disponibile. |
| [Options](../../aspose.diagram/datarecordset/options/) { get; set; } | Opzioni da applicare al recordset di dati. I valori possibili possono essere qualsiasi combinazione di uno o più di quelli mostrati nella tabella seguente. |
| [PrimaryKeys](../../aspose.diagram/datarecordset/primarykeys/) { get; } | Identifica una o più colonne di chiave primaria nel recordset di dati. |
| [RefreshConflicts](../../aspose.diagram/datarecordset/refreshconflicts/) { get; } | Indica una riga nel recordset di dati collegata a una forma in conflitto dopo l'aggiornamento del recordset di dati. RowID - Indica una riga nel recordset di dati collegata a una forma in conflitto dopo l'aggiornamento del recordset di dati. ShapeID - ID forma della forma coinvolta nel conflitto. PageID - ID pagina della forma coinvolta nel conflitto. |
| [RefreshInterval](../../aspose.diagram/datarecordset/refreshinterval/) { get; set; } | La frequenza (in minuti) in cui Visio aggiorna automaticamente il recordset di dati. Questo valore deve essere 1 o superiore. |
| [RefreshNoReconciliationUI](../../aspose.diagram/datarecordset/refreshnoreconciliationui/) { get; set; } | Indica se l'interfaccia utente per la riconciliazione dei dati deve essere disabilitata. True (1) per disabilitare l'interfaccia utente (UI). Falso (0) per abilitare l'interfaccia utente. |
| [RefreshOverwriteAll](../../aspose.diagram/datarecordset/refreshoverwriteall/) { get; set; } | Indica se sovrascrivere le modifiche apportate dall'utente agli elementi di dati della forma nelle forme collegate ai dati quando il recordset di dati viene aggiornato. |
| [ReplaceLinks](../../aspose.diagram/datarecordset/replacelinks/) { get; set; } | Definisce come vengono trattati i collegamenti forma-dati quando le forme vengono copiate o tagliate. 1 per sostituire i collegamenti esistenti nella forma di destinazione. 0 per mantenere i collegamenti esistenti nella forma di destinazione. Se questo attributo è assente, Visio chiede all'utente se sostituire i collegamenti su copia o taglia. |
| [RowMaps](../../aspose.diagram/datarecordset/rowmaps/) { get; } | Associa una riga del recordset di dati a una forma. RowID - ID riga della riga, univoco all'interno del recordset di dati. ShapeID - ID forma della forma collegata ai dati nella riga del recordset di dati identificata da RowID. PageID - ID pagina della forma collegata ai dati nella riga del recordset di dati identificata da RowID. |
| [RowOrder](../../aspose.diagram/datarecordset/roworder/) { get; set; } | Indica se utilizzare l'ordine delle righe nel recordset di dati come chiave primaria. True (1) se gli ID riga sono determinati dall'ordine delle righe. Falso (0) se gli ID di riga sono determinati dai valori nelle colonne della chiave primaria del recordset di dati. |
| [TimeRefreshed](../../aspose.diagram/datarecordset/timerefreshed/) { get; set; } | La data e l'ora dell'ultimo aggiornamento del recordset di dati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh)() | Esegue la stringa di query associata al DataRecordset connesso (non basato su XML) e aggiorna le forme collegate con nuovi dati dall'origine dati restituita dalla query. |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh_1)(DataConnectionType) | Esegue la stringa di query associata al DataRecordset connesso (non basato su XML) e aggiorna le forme collegate con nuovi dati dall'origine dati restituita dalla query. |

### Guarda anche

* spazio dei nomi [Aspose.Diagram](../../aspose.diagram/)
* assemblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
