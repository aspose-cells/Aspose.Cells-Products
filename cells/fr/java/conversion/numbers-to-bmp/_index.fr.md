---
title: Convertir des NUMBERS en BMP via Java 
url: /fr/java/conversion/numbers-to-bmp/ 
description: Exemple de code de conversion Java pour le format NUMBERS en fichier BMP. Les programmeurs peuvent utiliser cet exemple de code pour exporter des feuilles de calcul Excel et OpenOffice vers BMP dans n'importe quelle application Web ou de bureau Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir des NUMBERS en BMP via Java" h2="Conversion de NUMBERS en BMP Java pour convertir une ou plusieurs pages en BMP à l\'aide de la bibliothèque Java sur site." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="NUMBERS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Comment convertir des NUMBERS en BMP en utilisant Java" %}}

 Afin de rendre NUMBERS en BMP, nous utiliserons
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API qui est une plate-forme de conversion riche en fonctionnalités, puissante et facile à utiliser API for Java. Vous pouvez télécharger sa dernière version directement depuis
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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir des NUMBERS en BMP via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Les développeurs Java peuvent facilement convertir le fichier NUMBERS en BMP en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

1. Charger le fichier NUMBERS avec une instance de Workbook1. Sélectionnez la valeur par défaut ou n'importe quelle feuille de calcul de la collection1. Créer et définir l'objet de ImageOrPrintOptions1. Créer SheetRender avec des objets Worksheet et ImageOrPrintOptions1. Appelez la méthode SheetRender.toImage pour enregistrer le résultat au format BMP

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Avant d'exécuter le code source de conversion Java, assurez-vous que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec Java Runtime Environment for JSP/JSF Application and Desktop Applications.- Obtenez la dernière version de Aspose.Cells for Java directement auprès de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="NUMBERS à BMP Java Code source de conversion" offSpacer="" %}}

```cs
// charger le fichier NUMBERS à rendre
Workbook workbook = new Workbook("sourceFile.numbers");
// accéder à la feuille de calcul par défaut de la collection
Worksheet worksheet = workbook.getWorksheets().get(0);
// définir les paramètres de l'image résultante
ImageOrPrintOptions options = new ImageOrPrintOptions();
options.setOnePagePerSheet(true);
options.setImageType(ImageType.BMP);
// convertir une feuille de calcul en image au format BMP
SheetRender renderer = new SheetRender(worksheet, options);
renderer.toImage(0, "output.bmp");   
   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Démonstrations en direct de la conversion de NUMBERS en BMP" sectionDescription="[Convertir des NUMBERS en BMP](https://products.aspose.app/cells/conversion/numbers-to-bmp) dès maintenant en visitant notre site Web Live Demos. La démonstration en direct présente les avantages suivants" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire de code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement votre fichier NUMBERS, il sera converti instantanément en BMP." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Vous obtiendrez le lien de téléchargement." >}}

    {{% blocks/products/pf/agp/content h2="Java Bibliothèque de manipulation de feuilles de calcul" %}}

 Excel API peut être utilisé pour créer, modifier, convertir et restituer des formats Microsoft Excel dans différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables dans les applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="NUMBERS" readMoreLink="https://docs.fileformat.com/spreadsheet/numbers/" >}}

Les fichiers avec l'extension .numbers sont similaires aux fichiers .xlsx. Les fichiers Numbers sont créés à l'aide du logiciel de feuille de calcul Apple iWork Numbers. Apple iWork Numbers est un logiciel unitaire de la suite de productivité iWork. La suite de productivité iWork est équivalente à la suite Microsoft Office utilisée sur les PC Windows.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" >}}

Les fichiers ayant l'extension .BMP représentent des fichiers d'image bitmap utilisés pour stocker des images numériques bitmap. Ces images sont indépendantes de la carte graphique et sont également appelées format de fichier bitmap indépendant du périphérique (DIB). Cette indépendance sert à ouvrir le fichier sur plusieurs plates-formes telles que Microsoft Windows et Mac. Le format de fichier BMP peut stocker des données sous forme d'images numériques bidimensionnelles au format monochrome et couleur avec différentes profondeurs de couleur.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}