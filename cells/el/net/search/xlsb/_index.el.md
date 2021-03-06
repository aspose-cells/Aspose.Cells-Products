---
title: Αναζήτηση εγγράφου XLSB χωρίς άνοιγμα μέσω .NET 
weight: 8880
url: /el/net/search/xlsb/ 
description: C# πηγαίος κώδικας για αναζήτηση λέξεων με μοτίβο σε αρχείο XLSB σε πλατφόρμες .NET Framework, .NET Core, Mono ή Xamarin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Αναζήτηση μορφών XLSB σε C#" h2="Εγγενής και υψηλής απόδοσης αναζήτηση εγγράφων XLSB χρησιμοποιώντας API Aspose.Cells for .NET από την πλευρά του διακομιστή, χωρίς τη χρήση λογισμικού όπως η Microsoft ή το Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Τρόπος αναζήτησης αρχείου XLSB χρησιμοποιώντας το C#" %}}

 Για να αναζητήσουμε το αρχείο XLSB, θα χρησιμοποιήσουμε
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API που είναι μια πλατφόρμα αναζήτησης εγγράφων πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση API για C#. Ανοιξε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για την αναζήτηση αρχείων XLSB στο C#" %}}

{{% blocks/products/pf/agp/text %}}

 Μια βασική αναζήτηση εγγράφων με
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 Τα API μπορούν να γίνουν με λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

+ Φόρτωση αρχείου XLSB χρησιμοποιώντας την τάξη Βιβλίου εργασίας.
+ Λάβετε τα κελιά στο σχετικό φύλλο.
+ Αναζήτηση αριθμών, ημερομηνίας και κειμένου χρησιμοποιώντας τη μέθοδο Εύρεση

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Τα API μας υποστηρίζονται σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Πριν εκτελέσετε τον παρακάτω κώδικα, βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις στο σύστημά σας.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με πλατφόρμες .NET Framework, .NET Core, Mono ή Xamarin- Περιβάλλον ανάπτυξης όπως το Microsoft Visual Studio- Aspose.Cells for .NET DLL που αναφέρεται στο έργο σας - Εγκαταστήστε από το NuGet χρησιμοποιώντας το κουμπί Λήψη παραπάνω
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αναζήτηση αρχείων XLSB - C#" offSpacer="" %}}

```cs
// κελιά αναζήτησης που περιέχουν καθορισμένη τιμή συμβολοσειράς ή αριθμό
Workbook workbook = new Workbook("book1.xlsb");

// λάβετε τη συλλογή κυττάρων
Cells cells = workbook.Worksheets[0].Cells;

FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.EntireContent;

// βρείτε το κελί με τον ακέραιο ή το διπλό
Cell cell1 = cells.Find(205, null, opts);

if (cell1 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell1.Name);
}else{
    Console.WriteLine("Record not found ");
}

// βρείτε το κελί με τη συμβολοσειρά εισόδου
Aspose.Cells.Cell cell2 = cells.Find("Items A", null, opts);

if (cell2 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell2.Name);
}else{
    Console.WriteLine("Record not found ");
}

// βρείτε το κελί που περιέχει τη συμβολοσειρά εισόδου
opts.LookAtType = LookAtType.Contains;
Cell cell3 = cells.Find("Data", null, opts);

if (cell3 != null){
    Console.WriteLine("Name of the cell containing the value: " + cell3.Name);
}else{
    Console.WriteLine("Record not found ");
}  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for .NET API" %}}

 Το Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Διαδικτυακή αναζήτηση ζωντανών επιδείξεων XLSB" sectionDescription="Αναζητήστε κείμενο, λέξεις, φράσεις σε έγγραφα XLSB αυτήν τη στιγμή, επισκεπτόμενοι το δικό μας [Ζωντανή ιστοσελίδα Demos](https://products.aspose.app/cells/search). Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Απλώς ανεβάστε τα αρχεία σας XLSB." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Το αποτέλεσμα αναζήτησης εμφανίζεται αμέσως." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB " readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Η μορφή αρχείου XLSB καθορίζει τη Μορφή δυαδικού αρχείου του Excel, η οποία είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας του Excel. Το περιεχόμενο μπορεί να περιλαμβάνει μη δομημένους ή ημιδομημένους πίνακες αριθμών, κείμενο ή και αριθμούς και κείμενο, τύπους, εξωτερικές συνδέσεις δεδομένων, γραφήματα και εικόνες. Σε αντίθεση με το XLSX (το οποίο βασίζεται σε μορφή αρχείου Open XML), το XLSB αντιπροσωπεύει το δυαδικό αρχείο βιβλίου εργασίας του Excel. Τα αρχεία XLSB μπορούν να διαβαστούν και να γραφτούν ταχύτερα, γεγονός που τα καθιστά χρήσιμα για εργασία με μεγάλα αρχεία. Το XLSB χρησιμοποιείται σπάνια για την αποθήκευση βιβλίων εργασίας, καθώς το XLSX (και παλαιότερα το XLS) είναι οι πιο κοινές μορφές αρχείων που επιλέγονται από τον χρήστη για την αποθήκευση βιβλίων εργασίας. Μπορεί να ανοίξει από το Microsoft Office 2007 και νεότερη έκδοση. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές αναζήτησης" subTitle="Χρησιμοποιώντας το C#, μπορεί κανείς να αναζητήσει και άλλες μορφές, όπως." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/csv/" name="CSV" description="Τιμές διαχωρισμένες με κόμματα" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/ods/" name="ODS" description="Αρχείο υπολογιστικού φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/tsv/" name="TSV" description="Τιμές διαχωρισμένες με καρτέλες" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/txt/" name="κείμενο" description="Έγγραφο κειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/search/xlsm/" name="XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}