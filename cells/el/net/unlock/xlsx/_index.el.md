---
title:  Ξεκλείδωμα XLSX έγγραφο via .NET
weight: 2040
description: C# πηγαίος κώδικας για ξεκλείδωμα αρχείου XLSX με προστασία κωδικού πρόσβασης στο .NET Framework, .NET Core, Mono ή Xamarin Platforms.
keywords: [C# Aspose.Cells., c# unlock XLSX files., c# how to unlock XLSX document., c# unprotect XLSX files., remove protection from XLSX files., decrypt XLSX Files using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ξεκλείδωμα XLSX Υπολογιστικό φύλλο μέσω C#" h2="Καταργήστε την προστασία από το XLSX χρησιμοποιώντας τη βιβλιοθήκη .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να ξεκλειδώσετε το αρχείο XLSX χρησιμοποιώντας το C#" %}}

 Για να καταργήσουμε το αρχείο προστασίας XLSX, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Ξεκλείδωμα XLSX μέσω C#" %}}

{{% blocks/products/pf/agp/text %}}

 Χρειάζεσαι
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 αναφέρεται στο έργο σας για να εκτελέσετε την ακόλουθη ροή εργασίας.

{{% /blocks/products/pf/agp/text %}}

1.  Instantiate classbook Workbook με διαδρομή προς το προστατευμένο αρχείο XLSX
1.  Λάβετε την προεπιλογή ή οποιοδήποτε φύλλο εργασίας για να καταργήσετε την προστασία
1.  Καταργήστε την προστασία φύλλου εργασίας με τη μέθοδο φύλλου εργασίας. Κατάργηση προστασίας
1.  Καταργήστε την προστασία βιβλίου εργασίας με τη μέθοδο Workbook.Unprotect
1.  Αποθήκευση αποτελέσματος σε μορφή XLSX

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

// instantiate a Workbook object with protected XLSX file
var workbook = new Aspose.Cells.Workbook("protected.xlsx");

// access the default worksheet in the Excel file
var worksheet = workbook.Worksheets[0];

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in XLSX format
workbook.Save("unprotected.xlsx", Aspose.Cells.SaveFormat.Auto);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for .NET API" %}}

 Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Excel Microsoft σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι ένα αυτόνομο API και δεν απαιτεί λογισμικό όπως το Microsoft ή το OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Δωρεάν εφαρμογή για ξεκλείδωμα XLSX" sectionDescription=" Ελέγξτε τις ζωντανές επιδείξεις μας στο[ξεκλείδωμα XLSX αρχείων](https://products.aspose.app/cells/unlock/xlsx) με τα ακόλουθα οφέλη." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε ή να μεταγλωττίσετε κώδικα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο XLSX και πατήστε το κουμπί \"Ξεκλείδωμα\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Κατεβάστε το αρχείο XLSX που προκύπτει από τον σύνδεσμο" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}
Το XLSX είναι γνωστή μορφή για έγγραφα Excel Microsoft που εισήχθη από τον Microsoft με την κυκλοφορία του Microsoft Office 2007. Βάσει δομής οργανωμένης σύμφωνα με τις Συμβάσεις Ανοιχτής Συσκευασίας όπως περιγράφεται στο Μέρος 2 του νέου προτύπου OOX37 είναι το πρότυπο ECMA ένα πακέτο zip που περιέχει έναν αριθμό αρχείων XML. Η υποκείμενη δομή και τα αρχεία μπορούν να εξεταστούν απλά αποσυμπιέζοντας το αρχείο .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές ξεκλειδώματος" subTitle="Χρησιμοποιώντας το C#, μπορεί κανείς εύκολα να αφαιρέσει την προστασία / ξεκλείδωμα διαφορετικών μορφών, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="ODS" description="Αρχείο Υπολογιστικού Φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsb/" name="XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsm/" name="XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
