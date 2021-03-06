---
title: Générer des rapports dans des fichiers XLS via Java 
weight: 1090
url: /fr/java/assembly/xls/ 
description: Java exemple de code pour créer des rapports au format XLS sur Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Génération de rapports en masse au format XLS via Java" h2="Générez des rapports au format XLS à l\'aide d\'une source de données et d\'un modèle." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLS" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Comment générer des rapports XLS à l\'aide de Java" %}}

 Afin de créer des rapports de fichiers XLS, nous utiliserons
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API qui est une plate-forme d'assemblage API for Java riche en fonctionnalités, puissante et facile à utiliser. Vous pouvez télécharger sa dernière version directement depuis
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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour générer des rapports XLS via Java" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Instancier la classe WorkbookDesigner1. Ajouter des objets Datasource dans une ArrayList1. Définir la source de données et le processus pour l'objet WorkbookDesigner1. Enregistrer le résultat au format XLS via la méthode Worbook.save
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java est compatible avec toutes les principales plates-formes et systèmes d'exploitation. Veuillez vous assurer que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec Java Runtime Environment for JSP/JSF Application and Desktop Applications.- Obtenez la dernière version de Aspose.Cells for Java directement auprès de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Générer des rapports Excel au format XLS - C#" offSpacer="" %}}

```cs
//Créer un concepteur de classeur
WorkbookDesigner designer = new WorkbookDesigner(workbook);

//Créer des objets Personnes avec des photos
ArrayList persons = new ArrayList();       
persons.add(new Person("George", "New York", photo1));
persons.add(new Person("George", "New York", photo2));

//Définir la source de données et traiter les marqueurs intelligents
designer.setDataSource("Person", persons);
designer.process();

//Enregistrer le classeur
workbook.save(dataDir + "output.xls", SaveFormat.XLS);
	
System.out.println("File saved");
    


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="À propos de Aspose.Cells for Java API" %}}

 Aspose.Cells API peut être utilisé pour créer, modifier, convertir et restituer des formats Microsoft Excel dans différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables dans les applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Application gratuite pour assembler XLS" sectionDescription="Consultez nos démos en direct pour [créer des fichiers XLS](https://products.aspose.app/cells/assembly/xls) avec les avantages suivants." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire ou de compiler du code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Il suffit de télécharger le fichier XLS et de cliquer sur le bouton \"Assembler\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Téléchargez le fichier XLS résultant à partir du lien" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLS" readMoreLink="https://docs.fileformat.com/spreadsheet/xls/" >}}
Les fichiers avec l'extension XLS représentent le format de fichier binaire Excel. Ces fichiers peuvent être créés par Microsoft Excel ainsi que par d'autres tableurs similaires tels que OpenOffice Calc ou Apple Numbers. Le fichier enregistré par Excel est connu sous le nom de classeur où chaque classeur peut avoir une ou plusieurs feuilles de calcul. Les données sont stockées et affichées aux utilisateurs sous forme de tableau dans une feuille de calcul et peuvent couvrir des valeurs numériques, des données textuelles, des formules, des connexions de données externes, des images et des graphiques. Des applications telles que Microsoft Excel vous permettent d'exporter des données de classeur vers plusieurs formats différents, notamment PDF, CSV, XLSX, TXT, HTML, XPS et plusieurs autres. Le format de fichier XLS a été remplacé par un format plus ouvert et structuré, XLSX, avec la sortie de Microsoft Excel 2007. Les dernières versions prennent toujours en charge la création et la lecture de fichiers XLS, bien que XLSX soit désormais le premier choix d'utilisation.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de génération de rapport pris en charge" subTitle="En utilisant Java, on peut facilement générer des rapports de plusieurs formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/ods/" name="SAO" description="Fichier de feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsb/" name="XLSB" description="Fichier de classeur Excel binaire" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsm/" name="XLSM" description="Fichier de feuille de calcul" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/assembly/xlsx/" name="XLSX" description="Fichier Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}