---
title: Συγχώνευση αρχείων MHTML μέσω Java 
weight: 4420
url: /el/java/merger/mhtml/ 
description: Java δείγμα κώδικα για συνδυασμό εγγράφων MHTML σε Java Runtime Environment για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Συγχώνευση μορφών MHTML στο Java" h2="Συγχώνευση εγγενών εγγράφων MHTML χρησιμοποιώντας API Java από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Τρόπος συγχώνευσης αρχείων MHTML χρησιμοποιώντας το Java" %}}

 Για να συγχωνεύσουμε το αρχείο MHTML, θα χρησιμοποιήσουμε
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API που είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύχρηστη πλατφόρμα συγχώνευσης API for Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη συγχώνευση αρχείων MHTML στο Java" %}}

{{% blocks/products/pf/agp/text %}}

 Ένα βασικό έγγραφο που συγχωνεύεται και συνενώνεται με
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 Τα API μπορούν να γίνουν με λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

+ Φορτώστε το πρώτο αρχείο MHTML με μια παρουσία της κλάσης Βιβλίο εργασίας.
+ Φορτώστε το δεύτερο έγγραφο MHTML με μια παρουσία της κλάσης Βιβλίο εργασίας.
+ Συγχώνευση αρχείων χρησιμοποιώντας τη μέθοδο combination().
+ αποθηκεύστε το συγχωνευμένο αρχείο MHTML στην καθορισμένη διαδρομή

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Το Aspose.Cells for Java υποστηρίζει σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για JSP/JSF Application and Desktop Applications.- Λάβετε την τελευταία έκδοση του Aspose.Cells for Java απευθείας από [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Συγχώνευση αρχείων MHTML - Java" offSpacer="" %}}

```cs
// Ανοίξτε το πρώτο αρχείο MHTML.
Workbook mhtmlFile1 = new Workbook("chartsFileWithPath.mhtml");

// Ορίστε το δεύτερο βιβλίο πηγής.
// Ανοίξτε το δεύτερο αρχείο MHTML.
Workbook mhtmlFile2 = new Workbook("pictureFileWithPath.mhtml");

// Συνδυάζοντας τα δύο βιβλία εργασίας
mhtmlFile1.combine(mhtmlFile2);

// Αποθηκεύστε το αρχείο του βιβλίου προορισμού.
mhtmlFile1.save("combinedFileWithPath.mhtml");  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for Java API" %}}

 Το Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Διαδικτυακά MHTML Merger Live Demos" sectionDescription="Συγχωνεύστε έγγραφα MHTML αυτήν τη στιγμή, επισκεπτόμενοι το δικό μας [Ζωντανή ιστοσελίδα Demos](https://products.aspose.app/cells/merger). Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Απλώς ανεβάστε τα αρχεία MHTML σας." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα συγχωνευθεί και θα ενωθεί αμέσως." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}
Τα αρχεία με επέκταση MHTML αντιπροσωπεύουν μια μορφή αρχείου ιστοσελίδων που μπορεί να δημιουργηθεί από μια σειρά από διαφορετικές εφαρμογές. Η μορφή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML web και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με την ιστοσελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου και ούτω καθεξής. Τα αρχεία MHTML μπορούν να ανοίξουν σε μια ποικιλία εφαρμογών όπως ο Internet Explorer και το Microsoft Word. Τα Microsoft Windows χρησιμοποιούν μορφή αρχείου MHTML για την καταγραφή σεναρίων προβλημάτων που παρατηρούνται κατά τη χρήση οποιασδήποτε εφαρμογής στα Windows που εγείρει προβλήματα. Η μορφή αρχείου MHTML κωδικοποιεί τα περιεχόμενα της σελίδας παρόμοια με τις προδιαγραφές που ορίζονται στο μήνυμα/rfc822, το οποίο είναι προδιαγραφές που σχετίζονται με μηνύματα ηλεκτρονικού ταχυδρομείου απλού κειμένου. Οι πραγματικές προδιαγραφές της μορφής αναφέρονται λεπτομερώς στο RFC 2557. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές συγχώνευσης" subTitle="Χρησιμοποιώντας το Java, το One μπορεί επίσης να συγχωνεύσει πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων των.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Τιμές διαχωρισμένες με κόμματα" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Αρχείο υπολογιστικού φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Τιμές διαχωρισμένες με καρτέλες" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="κείμενο" description="Έγγραφο κειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Αρχείο Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Πρότυπο Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Πρότυπο με δυνατότητα μακροεντολής Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltx/" name="XLTX" description="Πρότυπο Office OpenXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}