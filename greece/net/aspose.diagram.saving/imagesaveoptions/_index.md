---
title: ImageSaveOptions
second_title: Aspose.Diagram for .NET API Reference
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγραμμάτων σε εικόνες.
type: docs
weight: 3280
url: /el/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

Επιτρέπει τον καθορισμό πρόσθετων επιλογών κατά την απόδοση σελίδων διαγραμμάτων σε εικόνες.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/)(SaveFileFormat) | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης που μπορεί να χρησιμοποιηθεί για την αποθήκευση εικόνων που έχουν αποδοθεί στο[`Καβγαδάκι`](../../aspose.diagram/savefileformat/) , [`Png`](../../aspose.diagram/savefileformat/) ,[`Bmp`](../../aspose.diagram/savefileformat/) ,[`Εμφ`](../../aspose.diagram/savefileformat/) ή[`Jpeg`](../../aspose.diagram/savefileformat/) μορφή. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | Λαμβάνει ή ορίζει την περιοχή των σχημάτων που θα αποθηκευτούν . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality/) { get; set; } | Καθορίζει το επίπεδο ποιότητας που θα χρησιμοποιηθεί κατά τη σύνθεση. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom/) { get; set; } | Αυτή η παράμετρος είναι παρόμοια με την κλίμακα, αλλά δεν επηρεάζει το μέγεθος της εικόνας που δημιουργείται. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | Όταν οι χαρακτήρες στο διάγραμμα είναι unicode και δεν έχουν οριστεί με τη σωστή τιμή γραμματοσειράς ή η γραμματοσειρά δεν είναι εγκατεστημένη τοπικά, μπορεί να εμφανίζονται ως μπλοκ σε pdf, εικόνα ή XPS. Ορίστε την Προεπιλεγμένη Γραμματοσειρά όπως MingLiu ή MS Gothic για να εμφανίζονται χαρακτήρες. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | Ρύθμιση για την απόδοση του μετααρχείου Emf. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | Καθορίζει αν θα γίνει μεγέθυνση της σελίδας . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | Καθορίζει εάν χρειάζεται ή όχι εξαγωγή των σχημάτων οδηγών. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage/) { get; set; } | Καθορίζει εάν χρειάζεται εξαγωγή της κρυφής σελίδας ή όχι. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness/) { get; set; } | Λαμβάνει ή ρυθμίζει τη φωτεινότητα για τις εικόνες που δημιουργούνται. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία χρώματος για τις εικόνες που δημιουργούνται. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast/) { get; set; } | Λαμβάνει ή ρυθμίζει την αντίθεση για τις εικόνες που δημιουργούνται. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode/) { get; set; } | Καθορίζει τον αλγόριθμο που χρησιμοποιείται όταν οι εικόνες κλιμακώνονται ή περιστρέφονται. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | Καθορίζει εάν χρειάζεται εξαγωγή των σχολίων ή όχι. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που καθορίζει την ποιότητα των δημιουργούμενων εικόνων JPEG. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των σελίδων προς απόδοση κατά την αποθήκευση σε ένα αρχείο TIFF πολλών σελίδων. Η προεπιλογή είναι MaxValue που σημαίνει ότι όλες οι σελίδες του διαγράμματος θα αποδοθούν. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex/) { get; set; } | Λαμβάνει ή ορίζει το ευρετήριο με βάση το 0 της πρώτης σελίδας για απόδοση. Η προεπιλογή είναι 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος σελίδας για τις εικόνες που δημιουργούνται. Μπορεί να[`PageSize`](../pagesize/) ή null. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που καθορίζει τον τρόπο μετατόπισης των pixel κατά την απόδοση. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution/) { get; set; } | Λαμβάνει ή ορίζει την ανάλυση για τις εικόνες που δημιουργούνται, σε κουκκίδες ανά ίντσα. |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea/) { get; set; } | Καθορίζει εάν η περιοχή αποθήκευσης είναι ίδια με το pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly/) { get; set; } | Καθορίζει εάν όλες οι σελίδες θα αποθηκεύονται σε εικόνα ή μόνο σε πρώτο πλάνο. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat/) { get; set; } | Καθορίζει τη μορφή με την οποία θα αποθηκευτούν οι σελίδες του διαγράμματος που έχουν αποδοθεί εάν χρησιμοποιείται αυτό το αντικείμενο επιλογών αποθήκευσης. Μπορεί να[`Καβγαδάκι`](../../aspose.diagram/savefileformat/) ,[`Png`](../../aspose.diagram/savefileformat/) , [`Bmp`](../../aspose.diagram/savefileformat/) ,[`Εμφ`](../../aspose.diagram/savefileformat/) ή[`Jpeg`](../../aspose.diagram/savefileformat/) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale/) { get; set; } | Λαμβάνει ή ορίζει τον συντελεστή ζουμ για τις εικόνες που δημιουργούνται. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | Λαμβάνει ή ορίζει σχήματα για απόδοση. Το προεπιλεγμένο πλήθος είναι 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode/) { get; set; } | Καθορίζει εάν η εξομάλυνση (antialiasing) εφαρμόζεται σε γραμμές και καμπύλες και στις άκρες των γεμισμένων περιοχών. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο συμπίεσης που θα εφαρμόζεται κατά την αποθήκευση των δημιουργούμενων εικόνων στη μορφή TIFF. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | Λαμβάνει ή ορίζει προειδοποιητική επανάκληση. |

### Δείτε επίσης

* class [RenderingSaveOptions](../renderingsaveoptions/)
* χώρος ονομάτων [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* συνέλευση [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
