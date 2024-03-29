---
title:  Προστατέψτε και κλειδώστε το έγγραφο XLS via .NET
weight: 7010
description: C# πηγαίος κώδικας για κλείδωμα του αρχείου XLS με χρήση κωδικού πρόσβασης στο .NET Framework, .NET Core, Mono ή Xamarin Platforms.
keywords: [C# Aspose.Cells., c# Lock XLS files., c# How to Protect and lock XLS document., c# Protect XLS files., Encrypt XLS Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Κρυπτογράφηση XLS Αρχείων μέσω C#" h2="Προστατέψτε με κωδικό πρόσβασης υπολογιστικά φύλλα Excel, συμπεριλαμβανομένης της μορφής XLS, χρησιμοποιώντας τη Βιβλιοθήκη .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να προστατέψετε το αρχείο XLS χρησιμοποιώντας το C#" %}}

 Για να προστατεύσουμε το αρχείο XLS, θα χρησιμοποιήσουμε
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API που είναι μια πλατφόρμα προστασίας εγγράφων πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση API για C#. Ανοιξε
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 διαχειριστής πακέτων, αναζητήστε
 **Aspose.Cells** 
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Προστασία XLS μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Χρειάζεσαι
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 αναφέρεται στο έργο σας για να εκτελέσετε την ακόλουθη ροή εργασίας.

{{% /blocks/products/pf/agp/text %}}

1.  Instantiate class Book Work με διαδρομή προς το αρχείο XLS
1.  Λάβετε την προεπιλογή ή οποιοδήποτε φύλλο εργασίας για να προσθέσετε προστασία
1.  Προστασία φύλλου εργασίας με φύλλο εργασίας. Μέθοδος προστασίας
1.  Προστασία βιβλίου εργασίας με βιβλίο εργασίας. Μέθοδος προστασίας
1.  Αποθήκευση αποτελέσματος σε μορφή XLS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET υποστηρίζεται σε όλα τα κύρια λειτουργικά συστήματα. Απλώς βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ή συμβατό λειτουργικό σύστημα με .NET Framework, .NET Core, Mono ή Xamarin Platforms
-  Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio
-  Προσθέστε αναφορά στο Aspose.Cells for .NET DLL στο έργο σας

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Εντολή" offSpacer="" %}}

```cs

// load the XLS Excel file 
var book = new Aspose.Cells.Workbook("unlocked.xls");

// access the first worksheet
var worksheet = book.Worksheets[0];

// protect the worksheet with password
worksheet.Protect(Aspose.Cells.ProtectionType.All, "password", null);

// protect the whole workbook with password
book.Protect(Aspose.Cells.ProtectionType.All, "password");

// save the modified file in default format
book.Save("protected.xls");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for .NET API" %}}

 Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Excel Microsoft σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι ένα αυτόνομο API και δεν απαιτεί λογισμικό όπως το Microsoft ή το OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Δωρεάν εφαρμογή για προστασία XLS" sectionDescription=" Ελέγξτε τις ζωντανές επιδείξεις μας στο[κρυπτογράφηση XLS αρχείων](https://products.aspose.app/cells/protect/xls) με τα ακόλουθα οφέλη." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε ή να μεταγλωττίσετε κώδικα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο XLS και πατήστε το κουμπί \"Ξεκλείδωμα\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Κατεβάστε το αρχείο XLS που προκύπτει από τον σύνδεσμο" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Τα αρχεία με επέκταση XLS αντιπροσωπεύουν τη μορφή δυαδικού αρχείου του Excel. Τέτοια αρχεία μπορούν να δημιουργηθούν από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα υπολογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. Το αρχείο που αποθηκεύεται από το Excel είναι γνωστό ως Workbook όπου κάθε βιβλίο εργασίας μπορεί να έχει ένα ή περισσότερα φύλλα εργασίας. Τα δεδομένα αποθηκεύονται και εμφανίζονται στους χρήστες σε μορφή πίνακα σε φύλλο εργασίας και μπορούν να εκτείνονται σε αριθμητικές τιμές, δεδομένα κειμένου, τύπους, εξωτερικές συνδέσεις δεδομένων, εικόνες και γραφήματα. Εφαρμογές όπως το Microsoft Excel σάς επιτρέπουν να εξάγετε δεδομένα βιβλίου εργασίας σε πολλές διαφορετικές μορφές, συμπεριλαμβανομένων των PDF, CSV, XLSX, TXT, HTML, XPS και πολλών άλλων. Η μορφή αρχείου XLS αντικαταστάθηκε με μια πιο ανοιχτή και δομημένη μορφή, XLSX, με την κυκλοφορία του Microsoft Excel 2007. Οι πιο πρόσφατες εκδόσεις εξακολουθούν να παρέχουν υποστήριξη για τη δημιουργία και την ανάγνωση αρχείων XLS, αν και η πρώτη επιλογή που χρησιμοποιείται τώρα είναι το 076114348.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές προστασίας" subTitle="Χρησιμοποιώντας το C#, μπορεί κανείς εύκολα να προστατεύσει άλλες μορφές, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/ods/" name="ODS" description="Αρχείο Υπολογιστικού Φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsb/" name="XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsm/" name="XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/protect/xlsx/" name="XLSX" description="Αρχείο Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
