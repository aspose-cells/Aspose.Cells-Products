---
title:  Προβολή TSV Μορφές αρχείων via .NET
weight: 3090
description: C# πηγαίος κώδικας για φόρτωση, απόδοση και εμφάνιση εγγράφων TSV στο .NET Framework, .NET Core, Mono ή Xamarin Platforms.
keywords: [C# Aspose.Cells., c# view TSV files., c# how to render TSV document., c# load and display TSV files., TSV File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="TSV Προβολή αρχείων for .NET" h2="Προβάλετε υπολογιστικά φύλλα Excel & OpenOffice όπως TSV χωρίς να απαιτείται Microsoft Excel ή Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TSV" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να προβάλετε το αρχείο TSV χρησιμοποιώντας το C#" %}}

 Για να προβάλουμε το αρχείο TSV, θα χρησιμοποιήσουμε
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API που είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα API για C# για χρήση με οποιοδήποτε πρόγραμμα προβολής. Ανοιξε
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 διαχειριστής πακέτων, αναζητήστε
 **Aspose.Cells** 
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή κονσόλας διαχείρισης πακέτων" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για προβολή TSV μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Το Aspose.Cells διευκολύνει τους προγραμματιστές να δουν το αρχείο TSV με λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1.  Φορτώστε το αρχείο TSV σε μια παρουσία του βιβλίου εργασίας
1.  Δημιουργήστε μια παρουσία του HtmlSaveOptions και ορίστε την ιδιότητα ExportHeadings σε true
1. Αποθηκεύστε το αρχείο TSV σε μορφή HTML χρησιμοποιώντας τη μέθοδο Workbook.Save
1.  Φορτώστε το προκύπτον HTML στο προεπιλεγμένο πρόγραμμα περιήγησης με το Process.Start

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET υποστηρίζεται σε όλα τα κύρια λειτουργικά συστήματα. Απλώς βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ή συμβατό λειτουργικό σύστημα με .NET Framework, .NET Core, Mono ή Xamarin Platforms
-  Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio
-  Προσθέστε αναφορά στο Aspose.Cells for .NET DLL στο έργο σας

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# παράδειγμα κώδικα για να δείτε το αρχείο TSV" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the TSV file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.tsv");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the TSV file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for .NET API" %}}

 Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Excel Microsoft σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι ένα αυτόνομο API και δεν απαιτεί λογισμικό όπως το Microsoft ή το OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Δωρεάν εφαρμογή για προβολή TSV" sectionDescription=" Ελέγξτε τις ζωντανές επιδείξεις μας στο[Προβολή TSV](https://products.aspose.app/cells/viewer/tsv) με τα ακόλουθα οφέλη." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε ή να μεταγλωττίσετε κώδικα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο TSV και πατήστε το κουμπί \"Προβολή\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Κατεβάστε το αρχείο TSV από τον σύνδεσμο, εάν απαιτείται" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV" readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
Μια μορφή αρχείου τιμών διαχωρισμένων με καρτέλες (TSV) αντιπροσωπεύει δεδομένα διαχωρισμένα με καρτέλες σε μορφή απλού κειμένου. Η μορφή αρχείου, παρόμοια με το CSV, χρησιμοποιείται για την οργάνωση δεδομένων με δομημένο τρόπο ώστε να γίνεται εισαγωγή και εξαγωγή μεταξύ διαφορετικών εφαρμογών. Η μορφή χρησιμοποιείται κυρίως για εισαγωγή/εξαγωγή και ανταλλαγή δεδομένων σε εφαρμογές υπολογιστικών φύλλων και βάσεις δεδομένων. Κάθε εγγραφή σε ένα αρχείο TSV περιέχεται σε μία γραμμή αρχείου κειμένου όπου κάθε τιμή πεδίου διαχωρίζεται από έναν χαρακτήρα καρτέλας. Ο τύπος μέσου για τη μορφή αρχείου TSV είναι κείμενο/τιμές διαχωρισμένες με καρτέλες.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές προβολής" subTitle="Χρησιμοποιώντας το C#, κάποιος μπορεί επίσης να δει πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/csv/" name="CSV" description="Τιμές διαχωρισμένες με κόμματα" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/ods/" name="ODS" description="Αρχείο Υπολογιστικού Φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/txt/" name="TXT" description="Έγγραφο κειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsb/" name="XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsm/" name="XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlsx/" name="XLSX" description="Αρχείο Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xlt/" name="XLT" description="Microsoft Πρότυπο Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltm/" name="XLTM" description="Πρότυπο με δυνατότητα μακροεντολής Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/viewer/xltx/" name="XLTX" description="Πρότυπο Office OpenXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
