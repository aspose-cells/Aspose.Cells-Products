---
title:  Συγχώνευση XLSB Αρχεία via Java
weight: 4840
description: Java δείγμα κώδικα για συνδυασμό εγγράφων XLSB στο Java Runtime Environment για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Συγχώνευση μορφών XLSB στο Java" h2="Εγγενής συγχώνευση εγγράφων XLSB με χρήση API Java από την πλευρά του διακομιστή." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Τρόπος συγχώνευσης αρχείων XLSB χρησιμοποιώντας το Java" %}}

 Για να συγχωνεύσουμε το αρχείο XLSB, θα χρησιμοποιήσουμε[Aspose.Cells for Java](https://products.aspose.com/cells/java) API που είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα συγχώνευσης API for Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) και εγκαταστήστε το στο έργο σας που βασίζεται στο Maven προσθέτοντας τις ακόλουθες διαμορφώσεις στο pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για συγχώνευση αρχείων XLSB στο Java" %}}

{{% blocks/products/pf/agp/text %}}

 Ένα βασικό έγγραφο που συγχωνεύεται και συνενώνεται με[Aspose.Cells for Java](https://products.aspose.com/cells/java) Τα API μπορούν να γίνουν με λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

+ Φορτώστε το πρώτο αρχείο XLSB με μια παρουσία της κλάσης Βιβλίο εργασίας.
+ Φορτώστε το δεύτερο έγγραφο XLSB με μια παρουσία της κλάσης Βιβλίο εργασίας.
+ Συγχώνευση αρχείων χρησιμοποιώντας τη μέθοδο combination().
+ αποθηκεύστε το συγχωνευμένο αρχείο XLSB σε καθορισμένη διαδρομή

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java υποστηρίζει σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
-  Λάβετε την τελευταία έκδοση του Aspose.Cells for Java απευθείας από
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Συγχώνευση Αρχείων XLSB - Java" offSpacer="" %}}

```cs
// Open the first XLSB file.
Workbook xlsbFile1 = new Workbook("chartsFileWithPath.xlsb");

// Define the second source book.
// Open the second XLSB file.
Workbook xlsbFile2 = new Workbook("pictureFileWithPath.xlsb");

// Combining the two workbooks
xlsbFile1.combine(xlsbFile2);

// Save the target book file.
xlsbFile1.save("combinedFileWithPath.xlsb");  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online XLSB Merger Live Demos" sectionDescription=" Συγχωνεύστε έγγραφα XLSB τώρα, επισκεπτόμενοι το δικό μας[Ζωντανή ιστοσελίδα Demos](https://products.aspose.app/cells/merger). Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε το Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Απλώς ανεβάστε τα XLSB αρχεία σας." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα συγχωνευθεί και θα ενωθεί αμέσως." >}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for Java API" %}}

 Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Excel Microsoft σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι ένα αυτόνομο API και δεν απαιτεί λογισμικό όπως το Microsoft ή το OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}


        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Η μορφή αρχείου XLSB καθορίζει τη μορφή δυαδικού αρχείου του Excel, η οποία είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας του Excel. Το περιεχόμενο μπορεί να περιλαμβάνει αδόμητους ή ημι-δομημένους πίνακες αριθμών, κείμενο ή και αριθμούς και κείμενο, τύπους, εξωτερικές συνδέσεις δεδομένων, γραφήματα και εικόνες. Σε αντίθεση με το XLSX (το οποίο βασίζεται σε μορφή αρχείου Open XML), το XLSB αντιπροσωπεύει το δυαδικό αρχείο βιβλίου εργασίας του Excel. Τα αρχεία XLSB μπορούν να διαβαστούν και να γραφτούν ταχύτερα, γεγονός που τα καθιστά χρήσιμα για εργασία με μεγάλα αρχεία. Το XLSB χρησιμοποιείται σπάνια για την αποθήκευση βιβλίων εργασίας, καθώς το XLSX (και παλαιότερα το XLS) είναι οι πιο συνηθισμένες μορφές αρχείων που επιλέγονται από τον χρήστη για την αποθήκευση βιβλίων εργασίας. Μπορεί να ανοίξει από το Microsoft Office 2007 και άνω.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές συγχώνευσης" subTitle="Χρησιμοποιώντας το Java, το One μπορεί επίσης να συγχωνεύσει πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Τιμές διαχωρισμένες με κόμματα" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Μορφή αρχείου ιστοσελίδας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Αρχείο Υπολογιστικού Φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Τιμές διαχωρισμένες με καρτέλες" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Έγγραφο κειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Αρχείο Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Πρότυπο Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Πρότυπο με δυνατότητα μακροεντολής Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltx/" name="XLTX" description="Πρότυπο Office OpenXML Excel" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
