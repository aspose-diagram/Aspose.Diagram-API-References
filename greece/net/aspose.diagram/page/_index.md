---
title: Page
second_title: Aspose.Diagram for .NET API Reference
description: Περιέχει στοιχεία που ορίζουν μια σελίδα στο έγγραφο.
type: docs
weight: 2490
url: /el/net/aspose.diagram/page/
---
## Page class

Περιέχει στοιχεία που ορίζουν μια σελίδα στο έγγραφο.

```csharp
public class Page : IDisposable
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Page](page/#constructor)() | Κατασκευαστής. |
| [Page](page/#constructor_1)(int) | Κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | Το αναγνωριστικό της αρχικής σελίδας σχεδίου που επισημάνθηκε σε ξεχωριστές επικαλύψεις σήμανσης από αναθεωρητές του σχεδίου. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | Μια σημαία που υποδεικνύει εάν η σελίδα είναι σελίδα φόντου. |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | Η σελίδα φόντου της σελίδας. |
| [Connects](../../aspose.diagram/page/connects/) { get; } | Περιέχει ένα στοιχείο Connect για κάθε σύνδεση μεταξύ δύο σχημάτων σε ένα σχέδιο. |
| [ID](../../aspose.diagram/page/id/) { get; set; } | Το μοναδικό αναγνωριστικό του στοιχείου μέσα στο γονικό του στοιχείο. |
| [Name](../../aspose.diagram/page/name/) { get; set; } | Το όνομα του στοιχείου. |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | Το καθολικό όνομα του στοιχείου. |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | Συλλογή σελίδων. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | Περιέχει στοιχεία που ορίζουν το φύλλο σελίδας για ένα στοιχείο Σελίδα ή Κύριο στοιχείο. |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | Εφαρμόστε ένα προκαθορισμένο θέμα σε αυτήν τη σελίδα |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | Εφαρμόστε μια προκαθορισμένη παραλλαγή θέματος quickstyle σε αυτήν τη σελίδα |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | Εφαρμόστε μια προκαθορισμένη παραλλαγή θέματος σε αυτήν τη σελίδα |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | Το αναγνωριστικό του αναθεωρητή που σχετίζεται με την επικάλυψη σήμανσης. |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | Συλλογή σχημάτων. |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | Το ViewCenterX και το ViewCenterY καθορίζουν ένα κεντρικό σημείο σε μια σελίδα που λαμβάνει μια νέα προβολή (παράθυρο) όταν ανοίγει αρχικά. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | Το ViewCenterX και το ViewCenterY καθορίζουν ένα κεντρικό σημείο σε μια σελίδα που λαμβάνει μια νέα προβολή (παράθυρο) όταν ανοίγει αρχικά. |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | Ο προεπιλεγμένος παράγοντας μεγέθυνσης που χρησιμοποιείται όταν ανοίγει μια νέα προβολή (παράθυρο) της σελίδας. Για παράδειγμα, 1 = 100%; 1,5 = 150%, και ούτω καθεξής. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | Δημιουργεί ένα στοιχείο ελέγχου Activex. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | Προσθέτει σχόλιο σε σχήμα με αναγνωριστικό σχήματος. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | Προσθέτει σχόλιο σε σχήμα. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | Προσθέτει σχόλιο με καθορισμένα PinX και PinY. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | Προσθέτει σχήμα που δημιουργήθηκε από τον κύριο σε συγκεκριμένη σελίδα. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | Προσθέτει σχήμα που δημιουργήθηκε από τον κύριο στη σελίδα με καθορισμένα PinX και PinY. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | Προσθέτει σχήμα που δημιουργήθηκε από τον κύριο στη σελίδα με καθορισμένα PinX, PinY, Πλάτος και Ύψος. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | Προσθέτει κείμενο με καθορισμένα PinX και PinY. |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | Προσθέτει κείμενο με καθορισμένα PinX και PinY. |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | Εφαρμόζει στυλ για πλήρη σελίδα. |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | Auto space shapes |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | Φέρνει ένα σχήμα, που ορίζεται με ID, προς τα εμπρός μία θέση στη σειρά z. |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | Φέρνει ένα σχήμα, που ορίζεται με ID, στο μπροστινό μέρος της τάξης z. |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | Κεντράρει τα σχήματα μιας σελίδας σε σχέση με την έκταση της σελίδας. Το κεντράρισμα των σχημάτων δεν αλλάζει τη θέση τους μεταξύ τους. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | Συνδέστε σχήματα μέσω σύνδεσης. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | Συνδέστε σχήματα μέσω σύνδεσης. |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | Συνδέστε σχήματα μέσω σύνδεσης. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | Συνδέστε σχήματα μέσω ευρετηρίου σύνδεσης. |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | Συνδέστε σχήματα μέσω ευρετηρίου σύνδεσης. |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | Εκτελεί εργασίες που καθορίζονται από την εφαρμογή που σχετίζονται με την απελευθέρωση, την απελευθέρωση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | Η διαδικασία σχεδίασης bezier. Το μήκος των σημείων πρέπει να είναι ίσο ή μεγαλύτερο από 3. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | Η διαδικασία σχεδίασης Ellipse. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | Η διαδικασία χάραξης μιας γραμμής. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | Η διαδικασία χάραξης γραμμής. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | Η διαδικασία χάραξης γραμμής. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | Η διαδικασία σχεδίασης Polyline. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | Η διαδικασία σχεδίασης πολυγραμμής. |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | Η διαδικασία σχεδίασης ορθογωνίου. |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | Η διαδικασία σχεδίασης spline. |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | Σχήματα κόλλας |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | Σχήματα κόλλας. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | Κολλήστε σχήματα σε δοχείο |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | Κολλήστε σχήματα σε δοχείο χρησιμοποιώντας όνομα σύνδεσης |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | Κολλήστε σχήματα με αναγνωριστικό σύνδεσης στο container |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | Κολλήστε σχήμα στην αρχή του συνδετήραX |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | Κολλήστε σχήμα στο τέλος του συνδετήραX |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | Απεικονίζει τα σχήματα και/ή επαναδρομολογεί τους συνδέσμους για τη σελίδα. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | Μετακινεί τη σελίδα σε άλλη θέση στις σελίδες. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | Μετακινεί ένα σχήμα, που ορίζεται από το αναγνωριστικό, πίσω μία θέση στη σειρά z. |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | Μετακινεί ένα σχήμα, που ορίζεται από το αναγνωριστικό, στο πίσω μέρος της τάξης z. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Diagram](../../aspose.diagram/)
* συνέλευση [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
