---
title: Window
second_title: Aspose.Diagram for .NET API Referansı
description: Microsoft Visio örneğindeki açık bir pencereyi temsil eder. Bu öğe DatadiagramML dosyası ilk olarak Visio. tarafından açıldığında uygulama çalışma alanında bir kullanıcı arabirimi penceresini tam olarak yeniden oluşturmak için gerekli bilgileri içerir.
type: docs
weight: 4390
url: /tr/net/aspose.diagram/window/
---
## Window class

Microsoft Visio örneğindeki açık bir pencereyi temsil eder. Bu öğe, DatadiagramML dosyası ilk olarak Visio. tarafından açıldığında uygulama çalışma alanında bir kullanıcı arabirimi penceresini tam olarak yeniden oluşturmak için gerekli bilgileri içerir.

```csharp
public class Window
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Window](window/)() | Yapıcı. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Container](../../aspose.diagram/window/container/) { get; set; } | Kapsayıcı kimliği: Sayfa, Sayfa veya Ana. Yalnızca ContainerType belirtilirse ilgili ve gereklidir. |
| [ContainerType](../../aspose.diagram/window/containertype/) { get; set; } | Aşağıdaki değerlerden biri olabilir: Document, Page veya Master. Yalnızca WindowType, Çizim veya Sayfa olarak belirtildiğinde geçerlidir. |
| [Document](../../aspose.diagram/window/document/) { get; set; } | Bu pencerede görüntülenen belgenin dosya yolu. Bu öznitelik, WindowType'ı Stencil. olarak belirtilen pencereler için geçerlidir. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled/) { get; set; } | Dinamik ızgara özelliğinin bir belge veya pencere için etkinleştirilip etkinleştirilmediğini belirtir. |
| [GlueSettings](../../aspose.diagram/window/gluesettings/) { get; set; } | Belgede yapıştırıcı etkinleştirildiğinde yapıştırıcıyı şekillendiren nesneleri belirtir. |
| [ID](../../aspose.diagram/window/id/) { get; set; } | Üst öğe içindeki öğenin benzersiz kimliği. |
| [Master](../../aspose.diagram/window/master/) { get; set; } | Ana Kimlik, bu pencere bir ana görüntülüyorsa. |
| [Page](../../aspose.diagram/window/page/) { get; set; } | Bu pencere bir sayfa görüntülüyorsa Sayfa Kimliği. Yalnızca WindowType, Drawing olarak belirtildiğinde ve ContainerType, Page. olarak belirtildiğinde geçerlidir. |
| [ParentWindow](../../aspose.diagram/window/parentwindow/) { get; set; } | Bu şablon penceresinin bulunduğu pencerenin kimliği. Yalnızca WindowType Stencil. olarak belirtildiğinde geçerlidir |
| [ReadOnly](../../aspose.diagram/window/readonly/) { get; set; } | Bu şablon bir belge şablonu değilse salt okunur bayrağı. |
| [Sheet](../../aspose.diagram/window/sheet/) { get; set; } | Kapsayıcıdaki sayfanın kimliği. Yalnızca Container, Sheet. olarak belirtildiğinde geçerlidir |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints/) { get; set; } | Bağlantı noktalarının bir pencerede gösterilip gösterilmeyeceğini belirtir. |
| [ShowGrid](../../aspose.diagram/window/showgrid/) { get; set; } | Çizim penceresinde bir kılavuzun gösterilip gösterilmeyeceğini belirtir. |
| [ShowGuides](../../aspose.diagram/window/showguides/) { get; set; } | Kılavuzların çizim penceresinde gösterilip gösterilmeyeceğini belirtir. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks/) { get; set; } | Sayfa sonlarının bir pencerede gösterilip gösterilmeyeceğini belirtir. |
| [ShowRulers](../../aspose.diagram/window/showrulers/) { get; set; } | Cetvellerin çizim penceresinde gösterilip gösterilmeyeceğini belirtir. |
| [SnapAngles](../../aspose.diagram/window/snapangles/) { get; } | Bir SnapAngle öğeleri koleksiyonu içerir. |
| [SnapExtensions](../../aspose.diagram/window/snapextensions/) { get; set; } | Etkin pencere için belirli bir ek uzantı ayarının etkinleştirilip etkinleştirilmediğini belirtir. Değer, aşağıdaki tablodaki değerlerin toplamı olabilir. |
| [SnapSettings](../../aspose.diagram/window/snapsettings/) { get; set; } | Pencerede yakalama etkinken şekillerin yapıştığı nesneleri belirtir. Değer, aşağıdaki tablodaki değerlerin toplamı olabilir. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup/) { get; set; } | Pencerenin üyesi olduğu birleştirilmiş kalıp pencereleri grubunu belirtir. Bu öznitelik, yalnızca WindowType özniteliği Stencil olan Window öğeleriyle ve yalnızca şablon penceresi birleştirilmiş bir şablon pencereleri grubunun parçasıysa geçerlidir. Aynı birleştirilmiş grubun parçası olan tüm şablon pencereleri aynı StencilGroup öğe değerine sahiptir. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos/) { get; set; } | Bir kalıbın penceredeki bir grup içindeki göreli konumunu belirten bir tamsayı içerir. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos/) { get; set; } | Bir çizim penceresinin sayfa sekmesi kontrolünün genişliğini belirtir (çizim penceresinin toplam genişliğinin bir bölümü olarak). |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx/) { get; set; } | İsteğe bağlı çift. |
| [ViewCenterY](../../aspose.diagram/window/viewcentery/) { get; set; } | İsteğe bağlı çift. |
| [ViewScale](../../aspose.diagram/window/viewscale/) { get; set; } | İsteğe bağlı çift. |
| [WindowHeight](../../aspose.diagram/window/windowheight/) { get; set; } | Pencere dikdörtgeninin yüksekliği. |
| [WindowLeft](../../aspose.diagram/window/windowleft/) { get; set; } | Pencere dikdörtgeninin sol koordinatı. |
| [WindowState](../../aspose.diagram/window/windowstate/) { get; set; } | Bu özellik aşağıdaki değerlerin toplamı olabilir. |
| [WindowTop](../../aspose.diagram/window/windowtop/) { get; set; } | Pencere dikdörtgeninin üst koordinatı. |
| [WindowType](../../aspose.diagram/window/windowtype/) { get; set; } | Aşağıdakilerden biri olabilecek numaralandırılmış bir değer: Çizim, Sayfa, Şablon veya Simge. WindowType='Stencil' öğesinin bir Pencere öğesi, üst çizim penceresinden (WindowType='Drawing') sonra ve diğer herhangi bir çizim penceresinden önce görünmelidir. elementler. |
| [WindowWidth](../../aspose.diagram/window/windowwidth/) { get; set; } | Pencere dikdörtgeninin genişliği. |

### Ayrıca bakınız

* ad alanı [Aspose.Diagram](../../aspose.diagram/)
* toplantı [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
