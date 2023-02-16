---
title: DataRecordSet
second_title: Aspose.Diagram para la referencia de la API de .NET
description: Almacena formatea actualiza y expone datos consultados desde una base de datos en Microsoft Visio.
type: docs
weight: 1140
url: /es/net/aspose.diagram/datarecordset/
---
## DataRecordSet class

Almacena, formatea, actualiza y expone datos consultados desde una base de datos en Microsoft Visio.

```csharp
public class DataRecordSet
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DataRecordSet](datarecordset/)() | Constructor. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ADOData](../../aspose.diagram/datarecordset/adodata/) { get; set; } | Contiene XML que se ajusta al esquema XML clásico de ADO para un conjunto de registros de ADO y que describe los datos en el conjunto de registros de datos. |
| [AutoLinkComparison](../../aspose.diagram/datarecordset/autolinkcomparison/) { get; } | Define una regla que compara una columna en el elemento principal DataRecordset con un elemento de datos de forma de la última acción de vinculación automática exitosa realizada en la interfaz de usuario. |
| [Checksum](../../aspose.diagram/datarecordset/checksum/) { get; set; } | Un valor de suma de comprobación, generado por Visio y basado en las propiedades del conjunto de registros de datos. Establezca este atributo en 0; Visio vuelve a calcular este valor en tiempo de ejecución. |
| [Command](../../aspose.diagram/datarecordset/command/) { get; set; } | La cadena de comando utilizada para consultar datos del origen de datos. |
| [ConnectionID](../../aspose.diagram/datarecordset/connectionid/) { get; set; } | El ID de conexión para el objeto DataConnection asociado. No existe para fuentes de datos XML. |
| [DataColumns](../../aspose.diagram/datarecordset/datacolumns/) { get; } | Contiene todos los elementos DataColumn en un conjunto de registros de datos. |
| [ID](../../aspose.diagram/datarecordset/id/) { get; set; } | El ID del conjunto de registros de datos, único dentro del documento. |
| [Name](../../aspose.diagram/datarecordset/name/) { get; set; } | El nombre para mostrar (o "descriptivo") del conjunto de registros de datos. |
| [NextRowID](../../aspose.diagram/datarecordset/nextrowid/) { get; set; } | El siguiente ID de fila de Visio disponible. |
| [Options](../../aspose.diagram/datarecordset/options/) { get; set; } | Opciones para aplicar al conjunto de registros de datos. Los valores posibles pueden ser cualquier combinación de uno o más de los que se muestran en la siguiente tabla. |
| [PrimaryKeys](../../aspose.diagram/datarecordset/primarykeys/) { get; } | Identifica una o más columnas de clave principal en el conjunto de registros de datos. |
| [RefreshConflicts](../../aspose.diagram/datarecordset/refreshconflicts/) { get; } | Indica una fila en el conjunto de registros de datos vinculada a una forma que está en conflicto después de actualizar el conjunto de registros de datos. RowID: indica una fila en el conjunto de registros de datos vinculada a una forma que está en conflicto después de actualizar el conjunto de registros de datos. ShapeID - Id. de forma de la forma involucrada en el conflicto. ID de página - Id. de página de la forma involucrada en el conflicto. |
| [RefreshInterval](../../aspose.diagram/datarecordset/refreshinterval/) { get; set; } | Con qué frecuencia (en minutos) Visio actualiza automáticamente el conjunto de registros de datos. Este valor debe ser 1 o mayor. |
| [RefreshNoReconciliationUI](../../aspose.diagram/datarecordset/refreshnoreconciliationui/) { get; set; } | Si se debe deshabilitar la interfaz de usuario de reconciliación de datos. Verdadero (1) para deshabilitar la interfaz de usuario (UI). Falso (0) para habilitar la interfaz de usuario. |
| [RefreshOverwriteAll](../../aspose.diagram/datarecordset/refreshoverwriteall/) { get; set; } | Si se sobrescriben los cambios del usuario en elementos de datos de forma en formas vinculadas a datos cuando se actualiza el conjunto de registros de datos. |
| [ReplaceLinks](../../aspose.diagram/datarecordset/replacelinks/) { get; set; } | Define cómo se tratan los enlaces de datos de forma cuando se copian o cortan formas. 1 para reemplazar los vínculos existentes en la forma de destino. 0 para mantener los vínculos existentes en la forma de destino. Si este atributo está ausente, Visio le pregunta al usuario si debe reemplazar los enlaces al copiar o cortar. |
| [RowMaps](../../aspose.diagram/datarecordset/rowmaps/) { get; } | Asigna una fila de conjunto de registros de datos a una forma. RowID: ID de fila de la fila, único dentro del conjunto de registros de datos. ShapeID: ID de forma de la forma vinculada a los datos en la fila del conjunto de registros de datos identificada por RowID. PageID - Id. de página de la forma vinculada a los datos en la fila del conjunto de registros de datos identificada por RowID. |
| [RowOrder](../../aspose.diagram/datarecordset/roworder/) { get; set; } | Si usar el orden de las filas en el conjunto de registros de datos como clave principal. Verdadero (1) si los ID de fila están determinados por el orden de fila. Falso (0) si los Id. de fila están determinados por los valores de la(s) columna(s) de clave principal del conjunto de registros de datos. |
| [TimeRefreshed](../../aspose.diagram/datarecordset/timerefreshed/) { get; set; } | La fecha y la hora en que se actualizó por última vez el conjunto de registros de datos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh)() | Ejecuta la cadena de consulta asociada con el DataRecordset conectado (no basado en XML) y actualiza las formas vinculadas con nuevos datos del origen de datos devuelto por la consulta. |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh_1)(DataConnectionType) | Ejecuta la cadena de consulta asociada con el DataRecordset conectado (no basado en XML) y actualiza las formas vinculadas con nuevos datos del origen de datos devuelto por la consulta. |

### Ver también

* espacio de nombres [Aspose.Diagram](../../aspose.diagram/)
* asamblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
