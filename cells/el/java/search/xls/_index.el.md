---
title: Αναζήτηση εγγράφου XLS χωρίς άνοιγμα μέσω Java 
weight: 9430
url: /el/java/search/xls/ 
description: Java δείγμα κώδικα για αναζήτηση λέξεων με μοτίβο σε αρχείο XLS στο Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Αναζήτηση μορφών XLS σε Java" h2="Εγγενής και υψηλής απόδοσης αναζήτηση εγγράφων XLS χρησιμοποιώντας API Aspose.Cells for Java από την πλευρά του διακομιστή, χωρίς τη χρήση λογισμικού όπως η Microsoft ή το Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Τρόπος αναζήτησης αρχείου XLS χρησιμοποιώντας το Java" %}}

 Για να αναζητήσουμε το αρχείο XLS, θα χρησιμοποιήσουμε
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API που είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα Αναζήτησης API for Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 και εγκαταστήστε το στο έργο σας που βασίζεται στο Maven προσθέτοντας τις ακόλουθες διαμορφώσεις στο pom.xml.

{{% blocks/products/pf/agp/code-block title="Αποθήκη" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Εξάρτηση" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cells</artifactId>
<version>version of aspose-cells API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για την αναζήτηση αρχείων XLS στο Java" %}}

{{% blocks/products/pf/agp/text %}}

 Μια βασική αναζήτηση εγγράφων χρησιμοποιώντας Aspose.Cells API μπορεί να γίνει με λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

+ Φορτώστε το αρχείο XLS δημιουργώντας ένα αντικείμενο βιβλίου εργασίας.
Πρόσβαση στο πρώτο φύλλο εργασίας στο αρχείο XLS.
+ Βρείτε το κελί που περιέχει τον καθορισμένο τύπο.
+ Instantiate FindOptions.
+ Βρείτε το κελί που περιέχει μια τιμή συμβολοσειράς
+ Εκτυπώστε τα κελιά που βρέθηκαν μετά το αποτέλεσμα αναζήτησης

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Το Aspose.Cells for Java υποστηρίζει σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για JSP/JSF Application and Desktop Applications.- Λάβετε την τελευταία έκδοση του Aspose.Cells for Java απευθείας από [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Αναζήτηση αρχείων XLS - Java" offSpacer="" %}}

```cs
// Δημιουργία αντικειμένου βιβλίου εργασίας
Workbook workbook = new Workbook(dataDir + "book1.xls");

// Πρόσβαση στο πρώτο φύλλο εργασίας στο αρχείο XLS
Worksheet worksheet = workbook.getWorksheets().get(0);

// Εύρεση του κελιού που περιέχει τον καθορισμένο τύπο
Cells cells = worksheet.getCells();

// Instantiate FindOptions
FindOptions findOptions = new FindOptions();

// Εύρεση του κελιού που περιέχει μια τιμή συμβολοσειράς που ξεκινά με Or
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// Εκτύπωση του ονόματος του κελιού που βρέθηκε μετά από αναζήτηση 
System.out.println("Name of the cell containing String: " + cell.getName());  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for Java API" %}}

 Το Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Ηλεκτρονική Αναζήτηση XLS Live Demos" sectionDescription="Αναζητήστε κείμενο, λέξεις, φράσεις σε έγγραφα XLS αυτήν τη στιγμή, επισκεπτόμενοι το δικό μας [Ζωντανή ιστοσελίδα Demos](https://products.aspose.app/cells/search). Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Απλώς ανεβάστε τα αρχεία σας XLS." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Το αποτέλεσμα αναζήτησης εμφανίζεται αμέσως." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS " readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Τα αρχεία με επέκταση XLS αντιπροσωπεύουν τη μορφή δυαδικού αρχείου του Excel. Τέτοια αρχεία μπορούν να δημιουργηθούν από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα υπολογιστικών φύλλων, όπως το OpenOffice Calc ή το Apple Numbers. Το αρχείο που αποθηκεύεται από το Excel είναι γνωστό ως Βιβλίο εργασίας όπου κάθε βιβλίο εργασίας μπορεί να έχει ένα ή περισσότερα φύλλα εργασίας. Τα δεδομένα αποθηκεύονται και εμφανίζονται στους χρήστες σε μορφή πίνακα σε φύλλο εργασίας και μπορούν να εκτείνονται σε αριθμητικές τιμές, δεδομένα κειμένου, τύπους, εξωτερικές συνδέσεις δεδομένων, εικόνες και γραφήματα. Εφαρμογές όπως το Microsoft Excel σάς επιτρέπουν να εξάγετε δεδομένα βιβλίου εργασίας σε πολλές διαφορετικές μορφές, όπως PDF, CSV, XLSX, TXT, HTML, XPS και πολλές άλλες. Η μορφή αρχείου XLS αντικαταστάθηκε με μια πιο ανοιχτή και δομημένη μορφή, το XLSX, με την κυκλοφορία του Microsoft Excel 2007. Οι πιο πρόσφατες εκδόσεις εξακολουθούν να παρέχουν υποστήριξη για τη δημιουργία και την ανάγνωση αρχείων XLS, αν και το XLSX είναι η πρώτη επιλογή χρήσης τώρα. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλα υποστηριζόμενα έγγραφα αναζήτησης" subTitle="Χρησιμοποιώντας το Java, μπορεί κανείς να αναζητήσει και άλλα αρχεία όπως." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/csv/" name="CSV" description="Τιμές διαχωρισμένες με κόμματα" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/ods/" name="ODS" description="Αρχείο υπολογιστικού φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/tsv/" name="TSV" description="Τιμές διαχωρισμένες με καρτέλες" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/txt/" name="κείμενο" description="Έγγραφο κειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsb/" name="XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}