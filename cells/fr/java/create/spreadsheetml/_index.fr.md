---
title: Créer SPREADSHEETML - Créer un fichier SPREADSHEETML dans Java
description:  Aspose Exceller. Java Créez un fichier SPREADSHEETML rapidement et facilement avec Aspose.Cells. Générez un fichier SPREADSHEETML en utilisant Java. Créez SPREADSHEETML dans Java. Java SPREADSHEETML Creater.
keywords: [Aspose Excel., Java Aspose.Cells., Java Create SPREADSHEETML file., Generate SPREADSHEETML file in Java., Create SPREADSHEETML file using Java., Write data to SPREADSHEETML file via Java., Create a SPREADSHEETML file in Java., Java Generate a SPREADSHEETML file., Java SPREADSHEETML Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Créer un fichier SPREADSHEETML dans Java" h2="Bibliothèque Java haute vitesse pour créer un fichier SPREADSHEETML. Il s\'agit d\'une solution logicielle professionnelle pour importer et exporter XLSX, PDF et de nombreux autres formats utilisant Java." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SPREADSHEETML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Créer un fichier SPREADSHEETML à l\'aide de Java" %}}

 Comment créer un fichier SPREADSHEETML ? Avec la bibliothèque Aspose.Cells for Java, vous pouvez facilement créer un fichier SPREADSHEETML par programme avec quelques lignes de code.[Aspose.Cells for Java](https://products.aspose.com/cells/java)est capable de créer des applications multiplateformes avec la possibilité de générer, modifier, convertir, restituer et imprimer tous les fichiers Excel. Java Excel API convertit non seulement entre les formats de feuilles de calcul, il peut également restituer des fichiers Excel sous forme d'images, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT et plus, ce qui en fait un choix parfait pour échanger des documents dans des formats standard de l'industrie. Vous pouvez télécharger sa dernière version directement depuis[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) et installez-le dans votre projet basé sur Maven en ajoutant les configurations suivantes au pom.xml.

{{% blocks/products/pf/agp/code-block title="Dépôt" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dépendance" offSpacer="true" %}}

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



{{% blocks/products/pf/agp/content h2="Comment créer SPREADSHEETML dans Java" %}}

{{% blocks/products/pf/agp/text %}}

 Il est facile pour les développeurs de créer, charger, modifier et convertir des fichiers SPREADSHEETML en exécutant différentes applications de reporting pour le traitement des données en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

1.  Créer une instance de[Classe de classeur](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
1.  Accédez à la feuille de calcul appropriée à l’aide de la méthode getWorksheets.get().
1.  Sélectionnez la cellule appropriée, saisissez la valeur dans la cellule souhaitée en utilisant le nom de la cellule, comme A1, B3, etc.
1.  Enregistrez le classeur au format SPREADSHEETML à l'aide de la méthode save().

{{% blocks/products/pf/agp/code-block title="Un exemple de code montre comment créer un fichier SPREADSHEETML dans Java." offSpacer="" %}}

```cs

// Create a new workbook
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet worksheet = wkb.getWorksheets().get(0);

// Add relevant content in the cell
worksheet.getCells().get("A1").putValue("ColumnA");
worksheet.getCells().get("B1").putValue("ColumnB")
worksheet.getCells().get("A2").putValue("ValueA")
worksheet.getCells().get("B2").putValue("ValueB")

// Save the workbook as SPREADSHEETML file
wkb.save("Excel.xml"); 

// To enhance the code for further functionalities here are more functions
// getCells() and setValue for modifying the cell content
// getCharts().add() to add charts
// getPivotTables().add() for creating a Pivot Table
// getCells().get(int cell id).setFormula for adding cell level formula

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Bibliothèque Java pour créer un fichier SPREADSHEETML" %}}
{{% blocks/products/pf/agp/text %}}

 Nous hébergeons nos colis Java en[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) référentiels. « Aspose.Cells for Java » est un fichier JAR commun contenant du byte-code. Veuillez suivre le[instructions étape par étape](https://docs.aspose.com/cells/java/installation/) sur la façon de l'installer dans votre environnement de développement Java.

{{% /blocks/products/pf/agp/text %}}
{{% /blocks/products/pf/agp/content %}}

{{% blocks/products/pf/agp/content h2="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Avant d’exécuter l’exemple de code source de conversion Java, assurez-vous que vous disposez des conditions préalables suivantes.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec l'environnement d'exécution Java pour les applications JSP/JSF et les applications de bureau.
- Aspose.Cells for Java prend en charge les versions Java suivantes : J2SE 6.0 (1.6), J2SE 7.0 (1.7) ou supérieure.
- [Obtenez la dernière version de Aspose.Cells for Java directement à partir de Maven.](https://docs.aspose.com/cells/java/installation/) 

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="SPREADSHEETML" readMoreLink="https://docs.fileformat.com/web/xml/" >}}XML signifie Extensible Markup Language qui est similaire à HTML mais différent dans l'utilisation de balises pour définir des objets. L'idée derrière la création du format de fichier XML était de stocker et de transporter des données sans dépendre d'outils logiciels ou matériels. Sa popularité est due au fait qu’il est à la fois lisible par l’homme et par la machine. Cela lui permet de créer des protocoles de données communs sous la forme d'objets à stocker et à partager sur un réseau tel que le World Wide Web (WWW). Le "X" dans XML signifie extensible, ce qui implique que le langage peut être étendu à n'importe quel nombre de symboles selon les besoins de l'utilisateur. C'est pour ces fonctionnalités que de nombreux formats de fichiers standards l'utilisent comme Microsoft Open XML, LibreOffice OpenDocument, XHTML et SVG.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres générations de feuilles de calcul prises en charge" subTitle="Vous pouvez également créer d’autres formats Excel Microsoft, dont quelques-uns répertoriés ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xls/" name="XLS" description="Microsoft Feuille de calcul Excel (ancienne version)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsx/" name="XLSX" description="Classeur XML ouvert" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsb/" name="XLSB" description="Classeur binaire Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlsm/" name="XLSM" description="Feuille de calcul prenant en charge les macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xlt/" name="XLT" description="Modèle Excel 97-2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xltx/" name="XLTX" description="Modèle Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/xltm/" name="XLTM" description="Modèle Excel prenant en charge les macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/csv/" name="CSV" description="Valeurs séparées par des virgules" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/tsv/" name="TSV" description="Valeurs séparées par des tabulations" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/ods/" name="ODS" description="Feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/pdf/" name="PDF" description="Portable Document Format" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/create/html/" name="HTML" description="Langage Signalétique Hyper Text" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
