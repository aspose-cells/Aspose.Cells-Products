---
title:  Rechercher et remplacer le texte dans le document XLSM via Java
weight: 1590
description: Exemple de code Java pour supprimer les informations sensibles dans le fichier XLSM sur l'environnement d'exécution Java pour les applications JSP/JSF et les applications de bureau.
keywords: [Java Aspose.Cells., Java Search and replace text in XLSM file., Java redact XLSM file., Java edit XLSM file., Java XLSM file redaction., Java Search and replace string in XLSM file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Rédiger les formats XLSM dans Java" h2="XLSM natif et hautes performances documentent des informations de rédaction sensibles à l\'aide d\'API Aspose.Cells for Java côté serveur, sans utiliser de logiciel tel que Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Comment expurger le fichier XLSM à l\'aide de Java" %}}

 Afin de rédiger le fichier XLSM, nous utiliserons[Aspose.Cells for Java](https://products.aspose.com/cells/java) API qui est une plateforme de rédaction API for Java riche en fonctionnalités, puissante et facile à utiliser. Vous pouvez télécharger sa dernière version directement depuis[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) et installez-le dans votre projet basé sur Maven en ajoutant les configurations suivantes au pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour expurger les fichiers XLSM dans Java" %}}

{{% blocks/products/pf/agp/text %}}

 Un document de base recherche et remplace le texte dans le contenu, les commentaires ou les métadonnées par[Aspose.Cells for Java](https://products.aspose.com/cells/java) Les API peuvent être réalisées avec seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

+ Chargez le fichier XLSM.
+ Sélectionnez la feuille concernée.
+ Définir et spécifier les options de recherche.
+ Précisez la plage dans laquelle vous souhaitez rechercher
Parcourez chaque cellule et utilisez getCells().find(...).
+ Remplacez la valeur.
+ Enregistrez le classeur.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java prend en charge toutes les principales plates-formes et systèmes d'exploitation. Veuillez vous assurer que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou un système d'exploitation compatible avec l'environnement d'exécution Java pour les applications JSP/JSF et les applications de bureau.
-  Obtenez la dernière version de Aspose.Cells for Java directement à partir de
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Rédiger les dossiers XLSM - Java" offSpacer="" %}}

```cs
Workbook workbook = new Workbook(dataDir + "sourceFile.xlsm");

Worksheet worksheet = workbook.getWorksheets().get(0);

// Specify the range where you want to search
// Here the range is E3:H6
CellArea area = CellArea.createCellArea("E3", "H6");

// Specify Find options
FindOptions opts = new FindOptions();
opts.setLookInType(LookInType.VALUES);
opts.setLookAtType(LookAtType.ENTIRE_CONTENT);
opts.setRange(area);

Cell cell = null;

do {
	// Search the cell with value search within range
	cell = worksheet.getCells().find("search", cell, opts);

	// If no such cell found, then break the loop
	if (cell == null)
		break;

	// Replace the cell with value replace
	cell.putValue("replace");

} while (true);

// Save the workbook
workbook.save(dataDir + "output.xlsm");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="À propos du Aspose.Cells for Java API" %}}

 Aspose.Cells API peut être utilisé pour créer, éditer, convertir et restituer Microsoft des formats Excel vers différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables au sein d'applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="En ligne XLSM Rédaction Démos en direct" sectionDescription=" Recherchez et remplacez du texte dans le contenu, les commentaires ou les métadonnées des documents XLSM dès maintenant en visitant notre[Site Web de démonstrations en direct](https://products.aspose.app/cells/redaction). La démo en direct présente les avantages suivants" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger le Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire de code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement vos fichiers XLSM." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Il sera expurgé instantanément." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Les fichiers avec l'extension XLSM sont un type de fichier de feuille de calcul prenant en charge les macros. Du point de vue de l'application, une macro est un ensemble d'instructions utilisées pour automatiser les processus. Une macro est utilisée pour enregistrer les étapes effectuées à plusieurs reprises et facilite l'exécution des actions en exécutant à nouveau la macro. Les macros sont programmées avec Visual Basic pour Applications (VBA) de Microsoft à partir du classeur Excel à l'aide de Visual Basic Editor et peuvent être exécutées/déboguées directement à partir de là.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres documents de rédaction pris en charge" subTitle="En utilisant le Java, on peut facilement rédiger différents formats, notamment." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/ods/" name="ODS" description="Fichier de feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xls/" name="XLS" description="Format binaire Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsb/" name="XLSB" description="Fichier de classeur Excel binaire" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/redaction/xlsx/" name="XLSX" description="Fichier Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
