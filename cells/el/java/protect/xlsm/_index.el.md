---
title:  Προστατέψτε και κλειδώστε το έγγραφο XLSM via Java
weight: 9620
description: Java δείγμα κώδικα για να κλειδώσετε το αρχείο XLSM με χρήση κωδικού πρόσβασης στο Java Runtime Environment for JSP/JSF Application and Desktop Applications.
keywords: [Java Aspose.Cells., Java Lock XLSM files., Java How to Protect and lock XLSM document., Java Protect XLSM files., Encrypt XLSM Files using Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Κρυπτογράφηση XLSM Αρχεία via Java" h2="Προστατέψτε με κωδικό πρόσβασης υπολογιστικά φύλλα Excel, συμπεριλαμβανομένης της μορφής XLSM, χρησιμοποιώντας τη Βιβλιοθήκη .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSM" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java/" installationsDocsLink="https://docs.aspose.com/cells/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Πώς να ασφαλίσετε το αρχείο XLSM χρησιμοποιώντας το Java" %}}

 Για να προστατεύσουμε το αρχείο XLSM, θα χρησιμοποιήσουμε
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API που είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα κρυπτογράφησης API for Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 και εγκαταστήστε το στο έργο σας που βασίζεται στο Maven προσθέτοντας τις ακόλουθες διαμορφώσεις στο pom.xml.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Αποθήκη" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για την προστασία XLSM Αρχεία via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Η προστασία εγγράφων με χρήση Aspose.Cells API μπορεί να γίνει με λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1.  Φόρτωση αρχείου XLSM με τη δημιουργία της κλάσης Βιβλίο εργασίας
1.  Χρησιμοποιήστε τη μέθοδο προστασίας (..) με ProtectionType και Password
1.  Αποθηκεύστε το προστατευμένο αρχείο XLSM με τη μέθοδο save().

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java υποστηρίζει σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
-  Λάβετε την τελευταία έκδοση του Aspose.Cells for Java απευθείας από
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Εξάρτηση" offSpacer="" %}}

```cs

// Open the XLSM file
Workbook wkb = new Workbook("sourceFile.xlsm");

// Protect workbook by specifying protection type
wkb.protect(ProtectionType.ALL, "12345");

// Save the XLSM file
wkb.save("lockedFile.xlsm");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for Java API" %}}

 Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Excel Microsoft σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι ένα αυτόνομο API και δεν απαιτεί λογισμικό όπως το Microsoft ή το OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Δωρεάν εφαρμογή για προστασία XLSM" sectionDescription=" Ελέγξτε τις ζωντανές επιδείξεις μας στο[κρυπτογράφηση XLSM αρχείων](https://products.aspose.app/cells/protect/xlsm) με τα ακόλουθα οφέλη." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κατεβάσετε ή να ρυθμίσετε τίποτα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε ή να μεταγλωττίσετε κώδικα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς ανεβάστε το αρχείο XLSM και πατήστε το κουμπί \"Ξεκλείδωμα\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Κατεβάστε το αρχείο XLSM που προκύπτει από τον σύνδεσμο" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Τα αρχεία με επέκταση XLSM είναι ένας τύπος αρχείων υπολογιστικών φύλλων που υποστηρίζουν μακροεντολές. Από την άποψη της εφαρμογής, μια Μακροεντολή είναι ένα σύνολο οδηγιών που χρησιμοποιούνται για την αυτοματοποίηση των διαδικασιών. Μια μακροεντολή χρησιμοποιείται για την καταγραφή των βημάτων που εκτελούνται επανειλημμένα και διευκολύνει την εκτέλεση των ενεργειών εκτελώντας ξανά τη μακροεντολή. Οι μακροεντολές προγραμματίζονται με το Visual Basic for Applications (VBA) του Microsoft μέσα από το Βιβλίο εργασίας του Excel χρησιμοποιώντας τον Επεξεργαστή Visual Basic και μπορούν να εκτελεστούν/εντοπιστούν σφάλματα απευθείας από εκεί.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλα υποστηριζόμενα έγγραφα προστασίας" subTitle="Χρησιμοποιώντας το Java, μπορεί κανείς να προστατεύσει άλλα αρχεία συμπεριλαμβανομένων." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/ods/" name="ODS" description="Αρχείο Υπολογιστικού Φύλλου OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xls/" name="XLS" description="Δυαδική μορφή Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsb/" name="XLSB" description="Δυαδικό αρχείο βιβλίου εργασίας Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsx/" name="XLSX" description="Αρχείο Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
