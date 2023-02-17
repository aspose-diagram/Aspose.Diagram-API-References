---
title: Print
second_title: Aspose.Diagram for .NET API Referansı
description: Belgenin tamamını varsayılan yazıcıya yazdırır.
type: docs
weight: 400
url: /tr/net/aspose.diagram/diagram/print/
---
## Print(PrintSaveOptions) {#print_1}

Belgenin tamamını varsayılan yazıcıya yazdırır.

```csharp
public void Print(PrintSaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| options | PrintSaveOptions | Yazdırma seçenekleri. |

### Ayrıca bakınız

* class [PrintSaveOptions](../../../aspose.diagram.saving/printsaveoptions/)
* class [Diagram](../)
* ad alanı [Aspose.Diagram](../../diagram/)
* toplantı [Aspose.Diagram](../../../)

---

## Print() {#print}

Belgenin tamamını varsayılan yazıcıya yazdırır.

```csharp
public void Print()
```

### Ayrıca bakınız

* class [Diagram](../)
* ad alanı [Aspose.Diagram](../../diagram/)
* toplantı [Aspose.Diagram](../../../)

---

## Print(string) {#print_6}

Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini kullanarak tüm belgeyi belirtilen yazıcıda yazdırın.

```csharp
public void Print(string printerName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| printerName | String | Yazıcının adı.Null olabilir |

### Notlar

YazıcıAdı Null veya boş ise, varsayılan yazıcı kullanılacaktır.

### Ayrıca bakınız

* class [Diagram](../)
* ad alanı [Aspose.Diagram](../../diagram/)
* toplantı [Aspose.Diagram](../../../)

---

## Print(string, PrintSaveOptions) {#print_7}

Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini kullanarak tüm belgeyi belirtilen yazıcıda yazdırın.

```csharp
public void Print(string printerName, PrintSaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| printerName | String | Yazıcının adı.Null olabilir |
| options | PrintSaveOptions | Yazdırma seçenekleri. |

### Notlar

YazıcıAdı Null veya boş ise, varsayılan yazıcı kullanılacaktır.

### Ayrıca bakınız

* class [PrintSaveOptions](../../../aspose.diagram.saving/printsaveoptions/)
* class [Diagram](../)
* ad alanı [Aspose.Diagram](../../diagram/)
* toplantı [Aspose.Diagram](../../../)

---

## Print(PrinterSettings, PrintSaveOptions) {#print_3}

Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini kullanarak belgeyi belirtilen yazıcı ayarlarına göre yazdırır.

```csharp
public void Print(PrinterSettings printerSettings, PrintSaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| printerSettings | PrinterSettings | Kullanılacak yazıcı ayarları. |
| options | PrintSaveOptions | Yazdırma seçenekleri. |

### Notlar

System.Drawing.Printing.PrinterSettingsobject yazdırılacak yazıcıyı, yazdırılacak sayfa aralığını ve diğer seçenekleri belirtmenize olanak tanır.

### Ayrıca bakınız

* class [PrintSaveOptions](../../../aspose.diagram.saving/printsaveoptions/)
* class [Diagram](../)
* ad alanı [Aspose.Diagram](../../diagram/)
* toplantı [Aspose.Diagram](../../../)

---

## Print(PrinterSettings) {#print_2}

Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini kullanarak belgeyi belirtilen yazıcı ayarlarına göre yazdırır.

```csharp
public void Print(PrinterSettings printerSettings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| printerSettings | PrinterSettings | Kullanılacak yazıcı ayarları. |

### Notlar

System.Drawing.Printing.PrinterSettingsobject yazdırılacak yazıcıyı, yazdırılacak sayfa aralığını ve diğer seçenekleri belirtmenize olanak tanır.

### Ayrıca bakınız

* class [Diagram](../)
* ad alanı [Aspose.Diagram](../../diagram/)
* toplantı [Aspose.Diagram](../../../)

---

## Print(PrinterSettings, string, PrintSaveOptions) {#print_5}

Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini ve bir belge adını kullanarak belgeyi belirtilen yazıcı ayarlarına göre yazdırır.

```csharp
public void Print(PrinterSettings printerSettings, string documentName, PrintSaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| printerSettings | PrinterSettings | Kullanılacak yazıcı ayarları. |
| documentName | String | Belgeyi yazdırırken görüntülenecek belge adı (örneğin, bir yazdırma durumu iletişim kutusunda veya yazıcı kuyruğunda). |
| options | PrintSaveOptions | Yazdırma seçenekleri. |

### Ayrıca bakınız

* class [PrintSaveOptions](../../../aspose.diagram.saving/printsaveoptions/)
* class [Diagram](../)
* ad alanı [Aspose.Diagram](../../diagram/)
* toplantı [Aspose.Diagram](../../../)

---

## Print(PrinterSettings, string) {#print_4}

Standart (Kullanıcı Arayüzü yok) yazdırma denetleyicisini ve bir belge adını kullanarak belgeyi belirtilen yazıcı ayarlarına göre yazdırır.

```csharp
public void Print(PrinterSettings printerSettings, string documentName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| printerSettings | PrinterSettings | Kullanılacak yazıcı ayarları. |
| documentName | String | Belgeyi yazdırırken görüntülenecek belge adı (örneğin, bir yazdırma durumu iletişim kutusunda veya yazıcı kuyruğunda). |

### Ayrıca bakınız

* class [Diagram](../)
* ad alanı [Aspose.Diagram](../../diagram/)
* toplantı [Aspose.Diagram](../../../)

---

## Print(string, string, PrintSaveOptions) {#print_9}

Standart (Kullanıcı Arayüzü olmayan) yazdırma denetleyicisini ve bir belge adını kullanarak belgeyi yazdırır.

```csharp
public void Print(string printerName, string documentName, PrintSaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| printerName | String | Yazıcının adı.Null olabilir |
| documentName | String | Belgeyi yazdırırken görüntülenecek belge adı (örneğin, bir yazdırma durumu iletişim kutusunda veya yazıcı kuyruğunda). |
| options | PrintSaveOptions | Yazdırma seçenekleri. |

### Ayrıca bakınız

* class [PrintSaveOptions](../../../aspose.diagram.saving/printsaveoptions/)
* class [Diagram](../)
* ad alanı [Aspose.Diagram](../../diagram/)
* toplantı [Aspose.Diagram](../../../)

---

## Print(string, string) {#print_8}

Standart (Kullanıcı Arayüzü olmayan) yazdırma denetleyicisini ve bir belge adını kullanarak belgeyi yazdırır.

```csharp
public void Print(string printerName, string documentName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| printerName | String | Yazıcının adı.Null olabilir |
| documentName | String | Belgeyi yazdırırken görüntülenecek belge adı (örneğin, bir yazdırma durumu iletişim kutusunda veya yazıcı kuyruğunda). |

### Ayrıca bakınız

* class [Diagram](../)
* ad alanı [Aspose.Diagram](../../diagram/)
* toplantı [Aspose.Diagram](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
