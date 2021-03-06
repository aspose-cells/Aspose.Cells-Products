---
title: Rechercher un document TSV sans ouvrir via Java 
weight: 4940
url: /fr/java/search/tsv/ 
description: Java exemple de code pour rechercher des mots avec un modèle dans le fichier TSV sur Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Rechercher des formats TSV dans Java" h2="Recherche de documents TSV native et hautes performances à l\'aide d\'API Aspose.Cells for Java côté serveur, sans l\'utilisation de logiciels tels que Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="TSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java" installationsDocsLink="https://docs.aspose.com/cells/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Comment rechercher un fichier TSV à l\'aide de Java" %}}

 Afin de rechercher le fichier TSV, nous utiliserons
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API qui est une plate-forme de recherche API for Java riche en fonctionnalités, puissante et facile à utiliser. Vous pouvez télécharger sa dernière version directement depuis
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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour rechercher des fichiers TSV dans Java" %}}

{{% blocks/products/pf/agp/text %}}

 Une recherche de documents de base à l'aide des API Aspose.Cells peut être effectuée avec seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

+ Charger le fichier TSV en instanciant un objet Workbook.
+ Accédez à la première feuille de calcul du fichier TSV.
+ Trouvez la cellule contenant la formule spécifiée.
+ Instancier FindOptions.
+ Trouver la cellule contenant une valeur de chaîne
+ Imprimer les cellules trouvées après le résultat de la recherche

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java est compatible avec toutes les principales plates-formes et systèmes d'exploitation. Veuillez vous assurer que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec Java Runtime Environment for JSP/JSF Application and Desktop Applications.- Obtenez la dernière version de Aspose.Cells for Java directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Rechercher des fichiers TSV - Java" offSpacer="" %}}

```cs
// Instanciation d'un objet Workbook
Workbook workbook = new Workbook(dataDir + "book1.tsv");

// Accéder à la première feuille de calcul du fichier TSV
Worksheet worksheet = workbook.getWorksheets().get(0);

// Recherche de la cellule contenant la formule spécifiée
Cells cells = worksheet.getCells();

// Instancier FindOptions
FindOptions findOptions = new FindOptions();

// Recherche de la cellule contenant une valeur de chaîne commençant par Ou
findOptions.setLookAtType(LookAtType.START_WITH);

Cell cell = cells.find("SH", null, findOptions);

// Impression du nom de la cellule trouvée après recherche 
System.out.println("Name of the cell containing String: " + cell.getName());  


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="À propos de Aspose.Cells for Java API" %}}

 Aspose.Cells API peut être utilisé pour créer, modifier, convertir et restituer des formats Microsoft Excel dans différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables dans les applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Démos en direct de recherche TSV en ligne" sectionDescription="Recherchez du texte, des mots, des phrases dans les documents TSV dès maintenant en visitant notre [Site Web de démos en direct](https://products.aspose.app/cells/search). La démo en direct présente les avantages suivants" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire de code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Téléchargez simplement vos fichiers TSV." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Le résultat de la recherche apparaît instantanément." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="TSV " readMoreLink="https://docs.fileformat.com/spreadsheet/tsv/" >}}
Un format de fichier de valeurs séparées par des tabulations (TSV) représente des données séparées par des tabulations au format texte brut. Le format de fichier, similaire au CSV, est utilisé pour l'organisation des données de manière structurée afin d'importer et d'exporter entre différentes applications. Le format est principalement utilisé pour l'importation/exportation et l'échange de données dans les applications et les bases de données de feuille de calcul. Chaque enregistrement d'un fichier TSV est contenu dans une seule ligne de fichier texte où chaque valeur de champ est séparée par un caractère de tabulation. Le type de support pour le format de fichier TSV est texte/valeurs séparées par des tabulations. 

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres documents de recherche pris en charge" subTitle="En utilisant Java, on peut également rechercher d\'autres fichiers, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/csv/" name="CSV" description="Valeurs séparées par des virgules" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/ods/" name="SAO" description="Fichier de feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/txt/" name="SMS" description="Document texte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xls/" name="XLS" description="Format binaire Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsb/" name="XLSB" description="Fichier de classeur Excel binaire" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/search/xlsm/" name="XLSM" description="Fichier de feuille de calcul" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}