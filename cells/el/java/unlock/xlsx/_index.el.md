---
title:  Ξεκλείδωμα XLSX έγγραφο via Java
weight: 310
description: Java δείγμα κώδικα για ξεκλείδωμα αρχείου XLSX με προστασία κωδικού πρόσβασης στο Java Περιβάλλον χρόνου εκτέλεσης για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
keywords: [Java Aspose.Cells., Java unlock XLSX files., Java how to unlock XLSX document., Java unprotect XLSX files., remove protection from XLSX files., decrypt XLSX Files using Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ξεκλείδωμα XLSX Αρχεία via Java" h2="Καταργήστε την προστασία από υπολογιστικά φύλλα Excel, συμπεριλαμβανομένου του αρχείου XLSX χρησιμοποιώντας τη Βιβλιοθήκη Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Πώς να αφαιρέσετε το αρχείο προστασίας XLSX χρησιμοποιώντας το Java" %}}

 Για να ξεκλειδώσετε το αρχείο XLSX, θα χρησιμοποιήσουμε
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για ξεκλείδωμα XLSX via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1.  Instantiate classbook Workbook με διαδρομή προς το προστατευμένο αρχείο XLSX
1.  Λάβετε την προεπιλογή ή οποιοδήποτε φύλλο εργασίας για να καταργήσετε την προστασία
1.  Καταργήστε την προστασία φύλλου εργασίας με τη μέθοδο φύλλου εργασίας. Κατάργηση προστασίας
1.  Καταργήστε την προστασία βιβλίου εργασίας με τη μέθοδο Workbook.Unprotect
1.  Αποθήκευση αποτελέσματος σε μορφή XLSX

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java υποστηρίζει σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ξεκλείδωμα XLSX Αρχεία via Java" offSpacer="" %}}

```cs

Workbook wkb = new Workbook("source.xlsx");

WorksheetCollection wksc = wkb.getWorksheets();
Worksheet wks = wksc.get(0);

// Unprotecting the XLSX
wks.unprotect();

// Save the XLSX file.
wkb.save("Worksheet_out.xlsx", FileFormatType.EXCEL_97_TO_2003);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for Java API" %}}

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

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μορφές ξεκλειδώματος" subTitle="Χρησιμοποιώντας το Java, μπορεί κανείς εύκολα να αφαιρέσει την προστασία / ξεκλείδωμα διαφορετικών μορφών, συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/ods/" name="ODS" description="Αρχείο Υπολογιστικού Φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsb/" name="XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/unlock/xlsm/" name="XLSM" description="Αρχείο υπολογιστικού φύλλου" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
