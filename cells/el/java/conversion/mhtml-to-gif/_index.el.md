---
title: Μετατροπή MHTML σε GIF μέσω Java 
weight: 2000
url: /el/java/conversion/mhtml-to-gif/ 
description: Δείγμα κώδικα μετατροπής Java για μορφή MHTML σε αρχείο GIF. Οι προγραμματιστές μπορούν να χρησιμοποιήσουν αυτό το παράδειγμα κώδικα για να εξάγουν υπολογιστικά φύλλα Excel και OpenOffice σε GIF σε οποιαδήποτε εφαρμογή που βασίζεται στον Ιστό ή στην επιφάνεια εργασίας Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή MHTML σε GIF μέσω Java" h2="Μετατροπή MHTML σε GIF Java για μετατροπή μεμονωμένων ή πολλαπλών σελίδων σε GIF χρησιμοποιώντας εσωτερική βιβλιοθήκη Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε MHTML σε GIF χρησιμοποιώντας το Java" %}}

 Για να αποδώσουμε το MHTML σε GIF, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή MHTML σε GIF μέσω Java" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές του Java μπορούν εύκολα να μετατρέψουν το αρχείο MHTML σε GIF σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου MHTML με μια παρουσία του βιβλίου εργασίας1. Επιλέξτε προεπιλογή ή οποιοδήποτε φύλλο εργασίας από τη συλλογή1. Δημιουργήστε και ορίστε το αντικείμενο του ImageOrPrintOptions1. Δημιουργήστε SheetRender με αντικείμενα φύλλου εργασίας & ImageOrPrintOptions1. Καλέστε τη μέθοδο SheetRender.toImage για να αποθηκεύσετε το αποτέλεσμα σε μορφή GIF
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε τον πηγαίο κώδικα μετατροπής Java, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για JSP/JSF Application and Desktop Applications.- Λάβετε την τελευταία έκδοση του Aspose.Cells for Java απευθείας από τη Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής MHTML σε GIF Java" offSpacer="" %}}

```cs
// φορτώστε το αρχείο MHTML που πρόκειται να αποδοθεί
Workbook workbook = new Workbook("sourceFile.mhtml");
// πρόσβαση στο προεπιλεγμένο φύλλο εργασίας από τη συλλογή
Worksheet worksheet = workbook.getWorksheets().get(0);
// ορίστε παραμέτρους για την εικόνα που προκύπτει
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.GIF);
// μετατροπή φύλλου εργασίας σε εικόνα σε μορφή GIF
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.gif");   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Ζωντανές επιδείξεις μετατροπής MHTML σε GIF" sectionDescription="[Μετατροπή MHTML σε GIF](https://products.aspose.app/cells/conversion/mhtml-to-gif) αυτή τη στιγμή, επισκεπτόμενοι τον ιστότοπο Live Demos. Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο MHTML σας, θα μετατραπεί αμέσως σε GIF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε τον σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="Java Βιβλιοθήκη χειρισμού υπολογιστικών φύλλων" %}}

 Το Excel API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Microsoft Excel σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι αυτόνομο API και δεν απαιτεί λογισμικό όπως η Microsoft ή το OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

Τα αρχεία με επέκταση MHTML αντιπροσωπεύουν μια μορφή αρχείου ιστοσελίδων που μπορεί να δημιουργηθεί από μια σειρά από διαφορετικές εφαρμογές. Η μορφή είναι γνωστή ως μορφή αρχειοθέτησης επειδή αποθηκεύει τον κώδικα HTML web και τους σχετικούς πόρους σε ένα μόνο αρχείο. Αυτοί οι πόροι περιλαμβάνουν οτιδήποτε συνδέεται με την ιστοσελίδα, όπως εικόνες, μικροεφαρμογές, κινούμενα σχέδια, αρχεία ήχου και ούτω καθεξής. Τα αρχεία MHTML μπορούν να ανοίξουν σε μια ποικιλία εφαρμογών όπως ο Internet Explorer και το Microsoft Word. Τα Microsoft Windows χρησιμοποιούν μορφή αρχείου MHTML για την καταγραφή σεναρίων προβλημάτων που παρατηρούνται κατά τη χρήση οποιασδήποτε εφαρμογής στα Windows που εγείρει προβλήματα. Η μορφή αρχείου MHTML κωδικοποιεί τα περιεχόμενα της σελίδας παρόμοια με τις προδιαγραφές που ορίζονται στο μήνυμα/rfc822, το οποίο είναι προδιαγραφές που σχετίζονται με μηνύματα ηλεκτρονικού ταχυδρομείου απλού κειμένου. Οι πραγματικές προδιαγραφές της μορφής αναφέρονται λεπτομερώς στο RFC 2557.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

Μια μορφή GIF ή Graphical Interchange Format είναι ένας τύπος υψηλής συμπίεσης εικόνας. Ανήκει στην Unisys, το GIF χρησιμοποιεί τον αλγόριθμο συμπίεσης LZW που δεν υποβαθμίζει την ποιότητα της εικόνας. Για κάθε εικόνα GIF επιτρέπονται συνήθως έως 8 bit ανά pixel και έως 256 χρώματα επιτρέπονται σε όλη την εικόνα. Σε αντίθεση με μια εικόνα JPEG, η οποία μπορεί να εμφανίσει έως και 16 εκατομμύρια χρώματα και αγγίζει αρκετά τα όρια του ανθρώπινου ματιού. Όταν εμφανίστηκε το Διαδίκτυο, τα GIF παρέμειναν η καλύτερη επιλογή επειδή απαιτούσαν χαμηλό εύρος ζώνης και συμβατά για τα γραφικά που καταναλώνουν συμπαγείς περιοχές χρωμάτων. Ένα κινούμενο GIF συνδυάζει πολλές εικόνες ή καρέ σε ένα μόνο αρχείο και τα εμφανίζει με μια σειρά για να δημιουργήσει ένα κινούμενο κλιπ ή ένα σύντομο βίντεο. Οι χρωματικοί περιορισμοί είναι έως 256 για κάθε καρέ και είναι πιθανό να είναι οι λιγότερο κατάλληλοι για την αναπαραγωγή άλλων εικόνων και φωτογραφιών με χρωματική διαβάθμιση.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε το MHTML σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων μερικών που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-bmp/" name="MHTML ΣΕ BMP" description="Εικόνα Bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-csv/" name="MHTML ΣΕ CSV" description="Τιμές διαχωρισμένες με κόμματα" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-dif/" name="MHTML ΣΕ ΔΙΑΦ" description="Μορφή ανταλλαγής δεδομένων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/conversion/mhtml-to-emf/" name="MHTML ΣΕ EMF" description="Βελτιωμένη μορφή μετα-αρχείου" >}}
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