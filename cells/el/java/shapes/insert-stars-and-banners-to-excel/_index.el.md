---
title:  Εισαγάγετε το Insert Star/Banner στο Excel via Java
weight: 381
description: Εισαγάγετε Star/Banner χρησιμοποιώντας το Aspose.Cells' Java API χωρίς κανένα λογισμικό όπως Microsoft ή Open Office, Adobe PDF κ.λπ.
keywords: [Java Aspose.Cells., Java add Star/Banner., Java insert Star/Banner., Java create Star/Banner]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Εισαγάγετε το Insert Star/Banner στο Excel via Java" h2="Εισαγάγετε το Star/Banner χρησιμοποιώντας το Aspose.Cells\' API χωρίς λογισμικό όπως Microsoft ή Open Office, Adobe PDF κ.λπ." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSX" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Τρόπος εισαγωγής Insert Star/Banner σε αρχείο Excel χρησιμοποιώντας το Java" %}}

 Για να εισαγάγουμε το Insert Star/Banner στο αρχείο excel, θα χρησιμοποιήσουμε
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API που είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα API for Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για την εισαγωγή Εισαγωγή Αστέρι/Banner στο αρχείο Excel via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

+ Δημιουργία αντικειμένου βιβλίου εργασίας.(ή->Φορτώστε το αρχείο XLSX με πλήρη διαδρομή.)
+ Επιλέξτε Φύλλο εργασίας μέσω του ευρετηρίου του.
 + Χρησιμοποιήστε το[μέθοδος προσθήκης](https://reference.aspose.com/cells/java/com.aspose.cells/shapecollection/#addAutoShape-int-int-int-int-int-int-int-) για να εισαγάγετε το Insert Star/Banner στο επιλεγμένο φύλλο εργασίας
+ Αποθήκευση βιβλίου εργασίας σε μορφή XLSX.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java υποστηρίζει σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για εφαρμογές JSP/JSF και εφαρμογές επιφάνειας εργασίας.
- Λάβετε την τελευταία έκδοση του Aspose.Cells for Java απευθείας από το Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

Το παρακάτω δείγμα κώδικα δείχνει τον τρόπο εισαγωγής "Κορδέλα: Curved and Tilted Up" και "Explosion: 8 Points". Για περισσότερους τύπους, ανατρέξτε στην "Επισκόπηση των τύπων εισαγωγής αστεριού και banner" παρακάτω.

{{% blocks/products/pf/agp/code-block title="Insert Insert Star/Banner - Java" offSpacer="" %}}

{{< gist "aspose-cells-gists" "5876dc77e47649b66bdb5deefb4b5639" "InsertStarsAndBannersIntoWorksheet.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
Επισκόπηση των τύπων εισαγωγής αστεριού και banner
   </h2>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/explosion_8_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.EXPLOSION_1
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/explosion_14_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.EXPLOSION_2
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_4_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.STAR_4
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_5_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.STAR_5
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_6_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.STAR_6
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_7_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.STAR_7
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_8_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.STAR_8
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_10_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.STAR_10
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_12_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.STAR_12
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_16_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.STAR_16
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_24_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.STAR_24
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/star_32_points.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.STAR_32
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/ribbon_tilted_up.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.UP_RIBBON
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/ribbon_tilted_down.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.DOWN_RIBBON
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/ribbon_curved_and_tilted_up.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.CURVED_UP_RIBBON
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/ribbon_curved_and_tilted_down.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.CURVED_DOWN_RIBBON
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/scroll_vertical.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.VERTICAL_SCROLL
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/scroll_horizontal.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.HORIZONTAL_SCROLL
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/wave.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.WAVE
    </p>
   </div>
   <div class="col-lg-4">
    <img src="/cells/net/shapes/insert-stars-and-banners-to-excel/double_wave.png" align="left" width="28" height="28">
    <p class="col-lg-10">
 AutoShapeType.DOUBLE_WAVE
    </p>
   </div>
  </div>
 </div>
</div>

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Σχετικά με Aspose.Cells for Java API" %}}

 Aspose.Cells API μπορεί να χρησιμοποιηθεί για τη δημιουργία, επεξεργασία, μετατροπή και απόδοση μορφών Excel Microsoft σε διαφορετικές μορφές. Επιπλέον, μπορεί να χρησιμοποιηθεί για ολοκληρωμένη χαρτογράφηση, κλιμακούμενη αναφορά και αξιόπιστους υπολογισμούς εντός εφαρμογών λογισμικού. Το Aspose.Cells είναι ένα αυτόνομο API και δεν απαιτεί λογισμικό όπως το Microsoft ή το OpenOffice.


    {{% /blocks/products/pf/agp/content %}}

    


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
