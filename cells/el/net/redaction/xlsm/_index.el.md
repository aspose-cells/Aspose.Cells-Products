---
title: Αναζήτηση και αντικατάσταση κειμένου σε έγγραφο XLSM μέσω .NET 
weight: 2370
url: /el/net/redaction/xlsm/ 
description: C# πηγαίος κώδικας για διόρθωση ευαίσθητων πληροφοριών σε αρχείο XLSM σε πλατφόρμες .NET Framework, .NET Core, Mono ή Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Redact Μορφές XLSM σε C#" h2="Εγγενείς και υψηλής απόδοσης XLSM έγγραφα ευαίσθητων πληροφοριών σύνταξης χρησιμοποιώντας API από την πλευρά του διακομιστή Aspose.Cells for .NET, χωρίς τη χρήση λογισμικού όπως η Microsoft ή το Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Πώς να επεξεργαστείτε το αρχείο XLSM χρησιμοποιώντας το C#" %}}

 Για να επεξεργαστούμε το αρχείο XLSM, θα χρησιμοποιήσουμε
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API που είναι μια πλατφόρμα πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση χειραγώγηση εγγράφων API για C#. Ανοιξε
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 διαχειριστής πακέτων, αναζητήστε
 **Aspose.Cells** 
 και εγκαταστήστε. Μπορείτε επίσης να χρησιμοποιήσετε την ακόλουθη εντολή από την Κονσόλα Package Manager.

{{% blocks/products/pf/agp/code-block title="Εντολή" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για την επεξεργασία αρχείων XLSM στο C#" %}}

{{% blocks/products/pf/agp/text %}}

 Μια βασική αναζήτηση εγγράφων και αντικατάσταση κειμένου σε περιεχόμενα, σχόλια ή μεταδεδομένα με
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 Τα API μπορούν να γίνουν με λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

+ Φόρτωση αρχείου XLSM.
+ Επιλέξτε το φύλλο.
+ Δημιουργία αντικειμένου FindOptions.
+ Ορισμός επιλογών αναζήτησης
+ Κάντε βρόχο σε κάθε κελί και χρησιμοποιήστε τη μέθοδο Εύρεση.
+ Αποθηκεύστε το βιβλίο εργασίας.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Τα API μας υποστηρίζονται σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Πριν εκτελέσετε τον παρακάτω κώδικα, βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις στο σύστημά σας.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με πλατφόρμες .NET Framework, .NET Core, Mono ή Xamarin- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio- Aspose.Cells for .NET DLL που αναφέρεται στο έργο σας - Εγκαταστήστε από το NuGet χρησιμοποιώντας το κουμπί Λήψη παραπάνω
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Επεξεργασία αρχείων XLSM - C#" offSpacer="" %}}

```cs
Workbook wb = new Workbook("e:\test2\Input.xlsm");
Worksheet sheet = wb.Worksheets[0];
FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.Contains;
opts.RegexKey = true;
Aspose.Cells.Cell cell = null;
do
{   //βρείτε μόνο ολόκληρη λέξη και όχι μέρος οποιασδήποτε λέξης.  
    cell = sheet.Cells.Find("\bKIM\b", cell, opts);
    if (cell != null)
    {
        string celltext = cell.Value.ToString();
        celltext = celltext.Replace("KIM", "^^^^^^^^^^");
        cell.PutValue(celltext);
    }
}
while (cell != null);

wb.Save("e:\test2\out1.xlsm");

// Εύρεση/αντικατάσταση σε ολόκληρο το βιβλίο εργασίας.

Workbook wb = new Workbook("e:\test2\Input.xlsm");
wb.Replace("\bKIM\b", "^^^^^^^^", new ReplaceOptions() { RegexKey = true });  
wb.Save("e:\test2\output.xlsm");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for .NET API" %}}

 Το Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online XLSM Redaction Live Demos" sectionDescription="Αναζητήστε και αντικαταστήστε κείμενο σε περιεχόμενα, σχόλια ή μεταδεδομένα σε έγγραφα XLSM τώρα, επισκεπτόμενοι το δικό μας [Ζωντανή ιστοσελίδα Demos](https://products.aspose.app/cells/redaction). Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε τα αρχεία XLSM σας." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα διορθωθεί αμέσως." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Τα αρχεία με επέκταση XLSM είναι ένας τύπος αρχείων υπολογιστικού φύλλου που υποστηρίζουν μακροεντολές. Από την άποψη της εφαρμογής, μια Μακροεντολή είναι ένα σύνολο οδηγιών που χρησιμοποιούνται για την αυτοματοποίηση των διαδικασιών. Μια μακροεντολή χρησιμοποιείται για την καταγραφή των βημάτων που εκτελούνται επανειλημμένα και διευκολύνει την εκτέλεση των ενεργειών εκτελώντας ξανά τη μακροεντολή. Οι μακροεντολές προγραμματίζονται με τη Visual Basic για Εφαρμογές (VBA) της Microsoft μέσα από το Βιβλίο εργασίας του Excel χρησιμοποιώντας τον Επεξεργαστή Visual Basic και μπορούν να εκτελεστούν/εντοπιστούν σφάλματα απευθείας από εκεί. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές επεξεργασίας" subTitle="Χρησιμοποιώντας το C#, μπορεί κανείς εύκολα να επεξεργαστεί διάφορες μορφές, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/ods/" name="ODS" description="Αρχείο υπολογιστικού φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsb/" name="XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}