---
title: Diagram
second_title: Aspose.Diagram para la referencia de la API de .NET
description: Elemento raíz de la jerarquía de objetos de Visio.
type: docs
weight: 1150
url: /es/net/aspose.diagram/diagram/
---
## Diagram class

Elemento raíz de la jerarquía de objetos de Visio.

```csharp
public class Diagram : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Diagram](diagram#constructor)() | Constructor predeterminado |
| [Diagram](diagram#constructor_1)(Stream) | PúblicoDiagram constructor de clase, carga el diagrama de la secuencia. |
| [Diagram](diagram#constructor_4)(string) | PúblicoDiagram constructor de clase, carga el diagrama desde el archivo. |
| [Diagram](diagram#constructor_2)(Stream, LoadFileFormat) | PúblicoDiagram constructor de clase, carga el diagrama de la secuencia usando un formato predefinido. |
| [Diagram](diagram#constructor_3)(Stream, LoadOptions) | PúblicoDiagram constructor de clase, carga el diagrama de la secuencia usando opciones de archivo de carga predefinidas. |
| [Diagram](diagram#constructor_5)(string, LoadFileFormat) | PúblicoDiagramconstructor de clase, carga el diagrama desde el archivo usando un formato predefinido. |
| [Diagram](diagram#constructor_6)(string, LoadOptions) | PúblicoDiagram constructor de clase, carga el diagrama desde el archivo utilizando opciones de archivo de carga predefinidas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage) { get; } | Especifica la página activa |
| [Buildnum](../../aspose.diagram/diagram/buildnum) { get; set; } | El número de compilación de la instancia de Visio utilizada para crear el documento. |
| [Colors](../../aspose.diagram/diagram/colors) { get; } | Contiene la tabla de colores del documento. Cada documento contiene una tabla de un solo color, que enumera los 24 colores estándar que están disponibles para aplicar a objetos como formas, texto y capas en el documento. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections) { get; } | Contiene los elementos DataConnection para el documento. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets) { get; } | La colección de objetos DataRecordset asociados con un objeto Documento. |
| [DocLangID](../../aspose.diagram/diagram/doclangid) { get; set; } | El ID exclusivo del idioma de la interfaz de usuario que el usuario especificó en las Preferencias de idioma de Microsoft Office 2010. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops) { get; } | Contiene elementos de propiedad del documento, como el título del documento, el autor, etc. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings) { get; } | Contiene elementos que especifican la configuración del documento. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet) { get; } | Especifica la estructura ShapeSheet de un documento. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata) { get; set; } | Contiene una hoja de enrutamiento de correo electrónico MAPI codificada con MIME (Extensiones multipropósito de correo de Internet) para el documento. |
| [EventItems](../../aspose.diagram/diagram/eventitems) { get; } | Contiene un elemento EventItem para cada evento al que debe responder un objeto. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs) { set; } | Indica la ruta de la carpeta Fuentes |
| [Fonts](../../aspose.diagram/diagram/fonts) { get; } | Contiene una colección de elementos de fuente |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter) { get; } | Contiene elementos para el encabezado y pie de página de un documento. |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor) { get; set; } | Obtiene y establece el monitor de interrupción. |
| [Key](../../aspose.diagram/diagram/key) { get; set; } | Indica si el documento se ha modificado fuera de Visio. Si está presente, Visio probará completamente el contenido del archivo. Omitir para los archivos que cree fuera de Visio. |
| [Masters](../../aspose.diagram/diagram/masters) { get; } | Objetos maestros de colección. |
| [Metric](../../aspose.diagram/diagram/metric) { get; set; } | Si utilizar unidades métricas en el dibujo. Establezca este atributo en Verdadero (1) para usar unidades métricas; configúrelo en Falso (0) para usar unidades inglesas. |
| [Pages](../../aspose.diagram/diagram/pages) { get; } | Objetos de página de colección. |
| [RibbonX](../../aspose.diagram/diagram/ribbonx) { get; set; } | La cadena XML de la cinta que se pasa al documento para personalizar la interfaz de usuario de la cinta. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls) { get; } | Valor XML. |
| [Start](../../aspose.diagram/diagram/start) { get; set; } | Indica si el documento se ha modificado fuera de Visio. Si está presente, Visio probará completamente el contenido del archivo. Omitir para los archivos que cree fuera de Visio. |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets) { get; } | Colección de objetos StyleSheet. |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui) { get; set; } | La cadena XML de la cinta que se pasa al documento para personalizar la barra de herramientas de acceso rápido o la cinta. |
| [Validation](../../aspose.diagram/diagram/validation) { get; } | Almacena información sobre la validación del diagrama para el documento. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject) { get; } | Obtiene el Proyecto Vba[`VbaProject`](./vbaproject). |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata) { get; set; } | Contiene los datos del proyecto de Microsoft Visual Basic para Aplicaciones en formato codificado MIME (Multipurpose Internet Mail Extensions). |
| [Version](../../aspose.diagram/diagram/version) { get; set; } | El número de versión de la instancia de Visio. Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows) { get; } | Contiene los elementos de Ventana para un documento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster#addmaster)(Diagram, string) | Agrega maestro al diagrama desde el diagrama de origen por Nombre del maestro o NombreU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster#addmaster_1)(Stream, int) | Agrega el maestro al diagrama desde el flujo de plantilla por ID del maestro. |
| [AddMaster](../../aspose.diagram/diagram/addmaster#addmaster_2)(Stream, string) | Agrega maestro al diagrama desde el flujo de plantilla por Nombre del maestro o NombreU. |
| [AddMaster](../../aspose.diagram/diagram/addmaster#addmaster_3)(string, int) | Agrega el maestro al diagrama desde el archivo de plantilla por ID del maestro. |
| [AddMaster](../../aspose.diagram/diagram/addmaster#addmaster_4)(string, string) | Agrega maestro al diagrama desde el archivo de plantilla por Nombre del maestro o NombreU. |
| [AddShape](../../aspose.diagram/diagram/addshape#addshape)(Shape, string, int) | Agrega la forma creada por el maestro a la página específica. |
| [AddShape](../../aspose.diagram/diagram/addshape#addshape_2)(double, double, string, int) | Agrega la forma creada por el maestro en la página con PinX y PinY definidos. |
| [AddShape](../../aspose.diagram/diagram/addshape#addshape_1)(double, double, double, double, string, int) | Agrega la forma creada por el maestro en la página con PinX, PinY, ancho y alto definidos. |
| [Combine](../../aspose.diagram/diagram/combine)(Diagram) | Combina otro objeto Diagram. |
| [CopyTheme](../../aspose.diagram/diagram/copytheme)(Diagram) | Copia el tema de un diagrama fuente. |
| [Dispose](../../aspose.diagram/diagram/dispose)() | Realiza tareas definidas por la aplicación asociadas con la liberación, liberación o restablecimiento de recursos no administrados. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir)() | Obtenga la ruta de la carpeta Fuentes predeterminadas |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles)() | Obtener estilos no utilizados |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo)() | Indica si este diagrama tiene información oculta. |
| [Layout](../../aspose.diagram/diagram/layout)(LayoutOptions) | Presenta las formas y/o redirige los conectores para todas las páginas del diagrama. |
| [Print](../../aspose.diagram/diagram/print#print)() | Imprime todo el documento en la impresora predeterminada. |
| [Print](../../aspose.diagram/diagram/print#print_2)(PrinterSettings) | Imprime el documento de acuerdo con la configuración de impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario). |
| [Print](../../aspose.diagram/diagram/print#print_1)(PrintSaveOptions) | Imprime todo el documento en la impresora predeterminada. |
| [Print](../../aspose.diagram/diagram/print#print_6)(string) | Imprima todo el documento en la impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario). |
| [Print](../../aspose.diagram/diagram/print#print_3)(PrinterSettings, PrintSaveOptions) | Imprime el documento de acuerdo con la configuración de impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario). |
| [Print](../../aspose.diagram/diagram/print#print_4)(PrinterSettings, string) | Imprime el documento de acuerdo con la configuración de impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario) y un nombre de documento. |
| [Print](../../aspose.diagram/diagram/print#print_7)(string, PrintSaveOptions) | Imprima todo el documento en la impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario). |
| [Print](../../aspose.diagram/diagram/print#print_8)(string, string) | Imprime el documento, utilizando el controlador de impresión estándar (sin interfaz de usuario) y un nombre de documento. |
| [Print](../../aspose.diagram/diagram/print#print_5)(PrinterSettings, string, PrintSaveOptions) | Imprime el documento de acuerdo con la configuración de impresora especificada, utilizando el controlador de impresión estándar (sin interfaz de usuario) y un nombre de documento. |
| [Print](../../aspose.diagram/diagram/print#print_9)(string, string, PrintSaveOptions) | Imprime el documento, utilizando el controlador de impresión estándar (sin interfaz de usuario) y un nombre de documento. |
| [Refresh](../../aspose.diagram/diagram/refresh)() | Invoca el método Refresh para todos los DataRecordSet en el diagrama. |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation)(int) | Eliminar información no utilizada |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro)() | Elimina VBA/macro de este diagrama. |
| [Save](../../aspose.diagram/diagram/save#save)(Stream, SaveFileFormat) | Guarda los datos del diagrama en la corriente. |
| [Save](../../aspose.diagram/diagram/save#save_1)(Stream, SaveOptions) | Guarda el diagrama en una secuencia usando las opciones de guardado especificadas. |
| [Save](../../aspose.diagram/diagram/save#save_2)(string, SaveFileFormat) | Guarda los datos del diagrama en el archivo. |
| [Save](../../aspose.diagram/diagram/save#save_3)(string, SaveOptions) | Guarda el documento en un archivo usando las opciones de guardado especificadas. |
| static [Export](../../aspose.diagram/diagram/export#export)(Stream, Stream) | Exporta el diagrama del formato de flujo vsd al formato de flujo vdw. Aún no implementado. |
| static [Export](../../aspose.diagram/diagram/export#export_1)(Stream, string) | Exporta el diagrama del flujo vsd al formato de archivo *.vdw. Aún no implementado. |
| static [Export](../../aspose.diagram/diagram/export#export_2)(string, Stream) | Exporta el diagrama del archivo vsd al formato de flujo vdw. Aún no implementado. |
| static [Export](../../aspose.diagram/diagram/export#export_3)(string, string) | Exporta el diagrama de formato vsd a vdw. Aún no implementado. |

### Ver también

* espacio de nombres [Aspose.Diagram](../../aspose.diagram)
* asamblea [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
