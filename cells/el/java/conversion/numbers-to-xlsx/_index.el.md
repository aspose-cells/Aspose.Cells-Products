---
title: Μετατροπή NUMBERS σε XLSX μέσω Java 
url: /el/java/conversion/numbers-to-xlsx/ 
description: Δείγμα κώδικα μετατροπής Java για μορφή NUMBERS σε αρχείο XLSX. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν αυτό το παράδειγμα κώδικα για να εξάγουν υπολογιστικά φύλλα Excel και OpenOffice σε XLSX σε οποιαδήποτε εφαρμογή που βασίζεται στον Ιστό ή στην επιφάνεια εργασίας Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή NUMBERS σε XLSX μέσω Java" h2="Μετατροπή NUMBERS σε XLSX Java για μετατροπή μεμονωμένων ή πολλαπλών σελίδων σε XLSX χρησιμοποιώντας βιβλιοθήκη εσωτερικής εγκατάστασης Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="NUMBERS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε NUMBERS σε XLSX χρησιμοποιώντας το Java" %}}

 Για να αποδώσουμε τα NUMBERS σε XLSX, θα χρησιμοποιήσουμε
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API που είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα μετατροπής API for Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή NUMBERS σε XLSX μέσω Java" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές του Java μπορούν εύκολα να μετατρέψουν το αρχείο NUMBERS σε XLSX σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου NUMBERS με μια παρουσία της κλάσης Βιβλίο εργασίας1. Καλέστε τη μέθοδο Workbook.save1. Περάστε τη διαδρομή εξόδου με την επέκταση XLSX & SaveFormat ως παραμέτρους1. Ελέγξτε την καθορισμένη διαδρομή για το αρχείο XLSX που προκύπτει

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε τον πηγαίο κώδικα μετατροπής Java, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για JSP/JSF Application and Desktop Applications.- Λάβετε την τελευταία έκδοση του Aspose.Cells for Java απευθείας από τη Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής NUMBERS σε XLSX Java" offSpacer="" %}}

```cs
// φορτώστε το αρχείο NUMBERS σε μια παρουσία του βιβλίου εργασίας
Workbook book = new Workbook("template.numbers");
// αποθηκεύστε ΑΡΙΘΜΟΥΣ ως XLSX
book.save("output.xlsx", SaveFormat.AUTO);   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Ζωντανές επιδείξεις μετατροπής NUMBERS σε XLSX" sectionDescription="[Μετατροπή NUMBERS σε XLSX](https://products.aspose.app/cells/conversion/numbers-to-xlsx) αυτή τη στιγμή, επισκεπτόμενοι τον ιστότοπο Live Demos. Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο NUMBERS, θα μετατραπεί αμέσως σε XLSX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε τον σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="Java Βιβλιοθήκη χειρισμού υπολογιστικών φύλλων" %}}

 Το Excel API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="NUMBERS" readMoreLink="https://docs.fileformat.com/spreadsheet/numbers/" >}}

Τα αρχεία με επέκταση .numbers είναι παρόμοια με τα αρχεία .xlsx. Τα αρχεία Numbers δημιουργούνται χρησιμοποιώντας το λογισμικό υπολογιστικών φύλλων Apple iWork Numbers. Το Apple iWork Numbers είναι ένα λογισμικό μονάδας του iWork Productivity Suite. Το iWork Productivity Suite είναι ισοδύναμο με το Microsoft Office Suite που χρησιμοποιείται σε υπολογιστές με Windows.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSX" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsx/" >}}

Το XLSX είναι μια πολύ γνωστή μορφή για έγγραφα του Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. Με βάση τη δομή που οργανώθηκε σύμφωνα με τις συμβάσεις ανοιχτής συσκευασίας, όπως περιγράφεται στο Μέρος 2 του προτύπου OOXML ECMA-376, η νέα μορφή είναι ένα πακέτο zip που περιέχει έναν αριθμό αρχείων XML. Η υποκείμενη δομή και τα αρχεία μπορούν να εξεταστούν απλά αποσυμπιέζοντας το αρχείο .xlsx.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}