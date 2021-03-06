---
title: Document XLS en filigrane via Java 
weight: 2210
url: /fr/java/watermark/xls/ 
description: Java exemple de code pour ajouter ou supprimer un filigrane au fichier XLS sur Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ajouter un filigrane de texte à XLS via Java" h2="Créez vos propres applications Java pour filigraner les fichiers XLS à l\'aide d\'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Comment filigraner un fichier XLS à l\'aide de Java" %}}

 Pour filigraner le fichier XLS, nous utiliserons
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API qui est une plate-forme de filigrane riche en fonctionnalités, puissante et facile à utiliser API for Java. Vous pouvez télécharger sa dernière version directement depuis
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 et installez-le dans votre projet basé sur Maven en ajoutant les configurations suivantes au fichier pom.xml.

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

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour ajouter un filigrane à XLS via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Créer un nouvel objet Workbook1. Sélectionnez Feuille de calcul via son index1. Créez une forme et utilisez sa fonction addTextEffect1. Définir les couleurs, la transparence et plus encore1. Enregistrer le classeur au format XLS
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java est compatible avec toutes les principales plates-formes et systèmes d'exploitation. Veuillez vous assurer que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec Java Runtime Environment for JSP/JSF Application and Desktop Applications.- Obtenez la dernière version de Aspose.Cells for Java directement auprès de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ajouter un filigrane à XLS - Java" offSpacer="" %}}

```cs

// Instancier un nouveau classeur
Workbook workbook = new Workbook();

// Obtenir la première feuille par défaut
Worksheet sheet = workbook.getWorksheets().get(0);

// Ajouter un filigrane
Shape wordart = sheet.getShapes().addTextEffect(MsoPresetTextEffect.TEXT_EFFECT_1, "CONFIDENTIAL",
		"Arial Black", 50, false, true, 18, 8, 1, 1, 130, 800);

// Obtenir le format de remplissage du mot art
FillFormat wordArtFormat = wordart.getFill();

// Définir la couleur
wordArtFormat.setOneColorGradient(Color.getRed(), 0.2, GradientStyleType.HORIZONTAL, 2);

// Définir la transparence
wordArtFormat.setTransparency(0.9);

// Rendre la ligne invisible
LineFormat lineFormat = wordart.getLine();
lineFormat.setWeight(0.0);

// Enregistrez le fichier
workbook.save(dataDir + "AWArtWToWorksheet_out.xls");  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="À propos de Aspose.Cells for Java API" %}}

 Aspose.Cells API peut être utilisé pour créer, modifier, convertir et restituer des formats Microsoft Excel dans différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables dans les applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Filigrane XLS via l\'application en ligne" sectionDescription="Ajoutez un filigrane aux documents XLS en visitant notre [Site Web de démos en direct](https://products.aspose.app/cells/watermark). La démo en direct présente les avantages suivants" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire de code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Téléchargez simplement votre fichier XLS, définissez votre filigrane et appuyez sur le bouton \"Ajouter\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtenez instantanément le lien de téléchargement du fichier résultant" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Les fichiers avec l'extension XLS représentent le format de fichier binaire Excel. Ces fichiers peuvent être créés par Microsoft Excel ainsi que par d'autres tableurs similaires tels que OpenOffice Calc ou Apple Numbers. Le fichier enregistré par Excel est connu sous le nom de classeur où chaque classeur peut avoir une ou plusieurs feuilles de calcul. Les données sont stockées et affichées aux utilisateurs sous forme de tableau dans une feuille de calcul et peuvent couvrir des valeurs numériques, des données textuelles, des formules, des connexions de données externes, des images et des graphiques. Des applications telles que Microsoft Excel vous permettent d'exporter des données de classeur vers plusieurs formats différents, notamment PDF, CSV, XLSX, TXT, HTML, XPS et plusieurs autres. Le format de fichier XLS a été remplacé par un format plus ouvert et structuré, XLSX, avec la sortie de Microsoft Excel 2007. Les dernières versions prennent toujours en charge la création et la lecture de fichiers XLS, bien que XLSX soit désormais le premier choix d'utilisation.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de filigrane pris en charge" subTitle="En utilisant Java, on peut facilement filigraner différents formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/ods/" name="SAO" description="Fichier de feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsb/" name="XLSB" description="Fichier de classeur Excel binaire" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/watermark/xlsm/" name="XLSM" description="Fichier de feuille de calcul" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}