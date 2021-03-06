---
title: Μετατροπή MHTML σε CSV μέσω Java 
weight: 1900
url: /el/java/conversion/mhtml-to-csv/ 
description: Δείγμα κώδικα μετατροπής Java για μορφή MHTML σε αρχείο CSV. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν αυτό το παράδειγμα κώδικα για να εξάγουν υπολογιστικά φύλλα Excel και OpenOffice σε CSV σε οποιαδήποτε εφαρμογή που βασίζεται στον Ιστό ή στην επιφάνεια εργασίας Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή MHTML σε CSV μέσω Java" h2="Μετατροπή Java MHTML σε CSV για μετατροπή μεμονωμένων ή πολλαπλών σελίδων σε CSV χρησιμοποιώντας βιβλιοθήκη εσωτερικής εγκατάστασης Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="CSV" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Τρόπος μετατροπής MHTML σε CSV χρησιμοποιώντας Java" %}}

 Για να αποδώσουμε το MHTML σε CSV, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή MHTML σε CSV μέσω Java" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές του Java μπορούν εύκολα να μετατρέψουν το αρχείο MHTML σε CSV σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου MHTML με μια παρουσία της κλάσης Βιβλίο εργασίας1. Καλέστε τη μέθοδο Workbook.save1. Περάστε τη διαδρομή εξόδου με επέκταση CSV & SaveFormat ως παραμέτρους1. Ελέγξτε την καθορισμένη διαδρομή για το αρχείο CSV που προκύπτει
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε τον πηγαίο κώδικα μετατροπής Java, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για JSP/JSF Application and Desktop Applications.- Λάβετε την τελευταία έκδοση του Aspose.Cells for Java απευθείας από τη Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής MHTML σε CSV Java" offSpacer="" %}}

```cs
// φορτώστε το αρχείο MHTML σε μια παρουσία του βιβλίου εργασίας
Workbook book = new Workbook("template.mhtml");
// αποθήκευση MHTML ως CSV
book.save("output.csv", SaveFormat.AUTO);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Ζωντανές επιδείξεις μετατροπής MHTML σε CSV" sectionDescription="[Μετατροπή MHTML σε CSV](https://products.aspose.app/cells/conversion/mhtml-to-csv) αυτή τη στιγμή, επισκεπτόμενοι τον ιστότοπο Live Demos. Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο MHTML σας, θα μετατραπεί αμέσως σε CSV." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε τον σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="Java Βιβλιοθήκη χειρισμού υπολογιστικών φύλλων" %}}

 Το Excel API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

Τα αρχεία με επέκταση MHTML αντιπροσωπεύουν μια μορφή αρχείου ιστοσελίδων που μπορεί να δημιουργηθεί από μια σειρά από διαφορετικές εφαρμογές. Η μορφή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML web και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με την ιστοσελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου και ούτω καθεξής. Τα αρχεία MHTML μπορούν να ανοίξουν σε μια ποικιλία εφαρμογών όπως ο Internet Explorer και το Microsoft Word. Τα Microsoft Windows χρησιμοποιούν μορφή αρχείου MHTML για την καταγραφή σεναρίων προβλημάτων που παρατηρούνται κατά τη χρήση οποιασδήποτε εφαρμογής στα Windows που εγείρει προβλήματα. Η μορφή αρχείου MHTML κωδικοποιεί τα περιεχόμενα της σελίδας παρόμοια με τις προδιαγραφές που ορίζονται στο μήνυμα/rfc822, το οποίο είναι προδιαγραφές που σχετίζονται με μηνύματα ηλεκτρονικού ταχυδρομείου απλού κειμένου. Οι πραγματικές προδιαγραφές της μορφής αναφέρονται λεπτομερώς στο RFC 2557.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

Τα αρχεία με επέκταση CSV (Τιμές διαχωρισμένες με κόμματα) αντιπροσωπεύουν αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές διαχωρισμένες με κόμμα. Κάθε γραμμή σε ένα αρχείο CSV είναι μια νέα εγγραφή από το σύνολο εγγραφών που περιέχεται στο αρχείο. Τέτοια αρχεία δημιουργούνται όταν η μεταφορά δεδομένων προορίζεται από το ένα σύστημα αποθήκευσης στο άλλο. Δεδομένου ότι όλες οι εφαρμογές μπορούν να αναγνωρίσουν εγγραφές που χωρίζονται με κόμμα, η εισαγωγή τέτοιων αρχείων δεδομένων στη βάση δεδομένων γίνεται πολύ εύκολα. Σχεδόν όλες οι εφαρμογές υπολογιστικών φύλλων όπως το Microsoft Excel ή το OpenOffice Calc μπορούν να εισάγουν CSV χωρίς μεγάλη προσπάθεια. Τα δεδομένα που εισάγονται από τέτοια αρχεία ταξινομούνται σε κελιά ενός υπολογιστικού φύλλου για αναπαράσταση στον χρήστη.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το MHTML σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-bmp/" name="MHTML ΣΕ BMP" description="Εικόνα Bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-dif/" name="MHTML ΣΕ ΔΙΑΦ" description="Μορφή ανταλλαγής δεδομένων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-emf/" name="MHTML ΣΕ EMF" description="Βελτιωμένη μορφή μετα-αρχείου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-gif/" name="MHTML ΣΕ GIF" description="Μορφή γραφικής ανταλλαγής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-html/" name="MHTML ΣΕ HTML" description="Γλώσσα σήμανσης υπερκειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-jpeg/" name="MHTML ΣΕ JPEG" description="Εικόνα JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-ods/" name="MHTML TO ODS" description="Αρχείο υπολογιστικού φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-pdf/" name="MHTML ΣΕ PDF" description="Μορφή φορητού εγγράφου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-png/" name="MHTML ΣΕ PNG" description="Φορητά γραφικά δικτύου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-svg/" name="MHTML ΣΕ SVG" description="Κλιμακόμενα διανυσματικά γραφικά" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-tiff/" name="MHTML TO TIFF" description="Με ετικέτα Μορφή εικόνας" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-tsv/" name="MHTML TO TSV" description="Τιμές διαχωρισμένες με καρτέλες" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-txt/" name="MHTML ΣΕ TXT" description="Έγγραφο κειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlm/" name="MHTML ΣΕ XLM" description="Αρχείο Macro Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xls/" name="MHTML ΣΕ XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlsb/" name="MHTML ΣΕ XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlsx/" name="MHTML ΣΕ XLSX" description="Αρχείο Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xlt/" name="MHTML ΣΕ XLT" description="Πρότυπο Microsoft Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xltm/" name="MHTML ΣΕ XLTM" description="Πρότυπο με δυνατότητα μακροεντολής Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xltx/" name="MHTML ΣΕ XLTX" description="Πρότυπο Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-xps/" name="MHTML ΣΕ XPS" description="Προδιαγραφές χαρτιού XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-json/" name="MHTML ΣΕ JSON" description="Σημείωση αντικειμένου JavaScript" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}