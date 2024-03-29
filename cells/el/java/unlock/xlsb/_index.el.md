---
title:  Ξεκλείδωμα XLSB έγγραφο via Java
weight: 5860
description: Java δείγμα κώδικα για ξεκλείδωμα αρχείου XLSB με προστασία κωδικού πρόσβασης στο Java Περιβάλλον χρόνου εκτέλεσης για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
keywords: [Java Aspose.Cells., Java unlock XLSB files., Java how to unlock XLSB document., Java unprotect XLSB files., remove protection from XLSB files., decrypt XLSB Files using Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ξεκλείδωμα XLSB Αρχεία via Java" h2="Καταργήστε την προστασία από υπολογιστικά φύλλα Excel, συμπεριλαμβανομένου του αρχείου XLSB χρησιμοποιώντας τη Βιβλιοθήκη Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Πώς να αφαιρέσετε το αρχείο προστασίας XLSB χρησιμοποιώντας το Java" %}}

 Για να ξεκλειδώσετε το αρχείο XLSB, θα χρησιμοποιήσουμε
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API που είναι μια πλατφόρμα προστασίας με πλούσια χαρακτηριστικά, ισχυρή και εύκολη στη χρήση API for Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για ξεκλείδωμα XLSB via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Instantiate classbook Workbook με διαδρομή προς το προστατευμένο αρχείο XLSB
1.  Λάβετε την προεπιλογή ή οποιοδήποτε φύλλο εργασίας για να καταργήσετε την προστασία
1.  Καταργήστε την προστασία φύλλου εργασίας με τη μέθοδο φύλλου εργασίας. Κατάργηση προστασίας
1.  Καταργήστε την προστασία βιβλίου εργασίας με τη μέθοδο Workbook.Unprotect
1.  Αποθήκευση αποτελέσματος σε μορφή XLSB

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java υποστηρίζει σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ξεκλείδωμα XLSB Αρχεία via Java" offSpacer="" %}}

```cs

Workbook wkb = new Workbook("source.xlsb");

WorksheetCollection wksc = wkb.getWorksheets();
Worksheet wks = wksc.get(0);

// Unprotecting the XLSB
wks.unprotect();

// Save the XLSB file.
wkb.save("Worksheet_out.xlsb", FileFormatType.EXCEL_97_TO_2003);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for Java API" %}}

 Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Excel Microsoft σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι ένα αυτόνομο API και δεν απαιτεί λογισμικό όπως το Microsoft ή το OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Δωρεάν εφαρμογή για ξεκλείδωμα XLSB" sectionDescription=" Ελέγξτε τις ζωντανές επιδείξεις μας στο[ξεκλείδωμα XLSB αρχείων](https://products.aspose.app/cells/unlock/xlsb) με τα ακόλουθα οφέλη." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε ή να μεταγλωττίσετε κώδικα" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο XLSB και πατήστε το κουμπί \"Ξεκλείδωμα\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Κατεβάστε το αρχείο XLSB που προκύπτει από τον σύνδεσμο" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Η μορφή αρχείου XLSB καθορίζει τη μορφή δυαδικού αρχείου του Excel, η οποία είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας του Excel. Το περιεχόμενο μπορεί να περιλαμβάνει αδόμητους ή ημι-δομημένους πίνακες αριθμών, κείμενο ή και αριθμούς και κείμενο, τύπους, εξωτερικές συνδέσεις δεδομένων, γραφήματα και εικόνες. Σε αντίθεση με το XLSX (το οποίο βασίζεται σε μορφή αρχείου Open XML), το XLSB αντιπροσωπεύει το δυαδικό αρχείο βιβλίου εργασίας του Excel. Τα αρχεία XLSB μπορούν να διαβαστούν και να γραφτούν ταχύτερα, γεγονός που τα καθιστά χρήσιμα για εργασία με μεγάλα αρχεία. Το XLSB χρησιμοποιείται σπάνια για την αποθήκευση βιβλίων εργασίας, καθώς το XLSX (και παλαιότερα το XLS) είναι οι πιο συνηθισμένες μορφές αρχείων που επιλέγονται από τον χρήστη για την αποθήκευση βιβλίων εργασίας. Μπορεί να ανοίξει από το Microsoft Office 2007 και άνω.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές ξεκλειδώματος" subTitle="Χρησιμοποιώντας το Java, μπορεί κανείς εύκολα να αφαιρέσει την προστασία / ξεκλείδωμα διαφορετικών μορφών, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/ods/" name="ODS" description="Αρχείο Υπολογιστικού Φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsm/" name="XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsx/" name="XLSX" description="Αρχείο Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
