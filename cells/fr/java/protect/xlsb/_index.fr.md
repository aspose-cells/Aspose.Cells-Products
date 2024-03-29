---
title:  Protéger et verrouiller le document XLSB via Java
weight: 6590
description: Exemple de code Java pour verrouiller le fichier XLSB à l'aide d'un mot de passe sur l'environnement d'exécution Java pour les applications JSP/JSF et les applications de bureau.
keywords: [Java Aspose.Cells., Java Lock XLSB files., Java How to Protect and lock XLSB document., Java Protect XLSB files., Encrypt XLSB Files using Java]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chiffrer les fichiers XLSB via Java" h2="Protégez par mot de passe les feuilles de calcul Excel, y compris le format XLSB, à l\'aide de la bibliothèque .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/java/" installationsDocsLink="https://docs.aspose.com/cells/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/java" learnAsLink="https://docs.aspose.com/cells/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells" >}}

{{% blocks/products/pf/agp/content h2="Comment sécuriser le fichier XLSB à l\'aide de Java" %}}

 Afin de protéger le fichier XLSB, nous utiliserons
 [Aspose.Cells for Java](https://products.aspose.com/cells/java) 
 API qui est une plate-forme de cryptage API for Java riche en fonctionnalités, puissante et facile à utiliser. Vous pouvez télécharger sa dernière version directement depuis
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells) 
 et installez-le dans votre projet basé sur Maven en ajoutant les configurations suivantes au pom.xml.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dépôt" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour protéger les fichiers XLSB via Java" %}}

{{% blocks/products/pf/agp/text %}}

 La protection des documents à l'aide des API Aspose.Cells peut être effectuée avec seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

1.  Chargez le fichier XLSB en instanciant la classe Workbook
1.  Utilisez la méthode Protect(..) avec ProtectionType et Mot de passe
1.  Enregistrez le fichier protégé XLSB par la méthode save()

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for Java prend en charge toutes les principales plates-formes et systèmes d'exploitation. Veuillez vous assurer que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou un système d'exploitation compatible avec l'environnement d'exécution Java pour les applications JSP/JSF et les applications de bureau.
-  Obtenez la dernière version de Aspose.Cells for Java directement à partir de
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cells)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dépendance" offSpacer="" %}}

```cs

// Open the XLSB file
Workbook wkb = new Workbook("sourceFile.xlsb");

// Protect workbook by specifying protection type
wkb.protect(ProtectionType.ALL, "12345");

// Save the XLSB file
wkb.save("lockedFile.xlsb");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="À propos du Aspose.Cells for Java API" %}}

 Aspose.Cells API peut être utilisé pour créer, éditer, convertir et restituer Microsoft des formats Excel vers différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables au sein d'applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Application gratuite pour protéger XLSB" sectionDescription=" Consultez nos démos en direct pour[chiffrer les fichiers XLSB](https://products.aspose.app/cells/protect/xlsb) avec les avantages suivants." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire ou de compiler du code" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement le fichier XLSB et cliquez sur le bouton \"Déverrouiller\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Téléchargez le fichier XLSB résultant à partir du lien" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Le format de fichier XLSB spécifie le format de fichier binaire Excel, qui est un ensemble d'enregistrements et de structures spécifiant le contenu du classeur Excel. Le contenu peut inclure des tableaux de nombres non structurés ou semi-structurés, du texte, ou à la fois des nombres et du texte, des formules, des connexions de données externes, des graphiques et des images. Contrairement à XLSX (qui est basé sur le format de fichier Open XML), le XLSB représente un fichier de classeur Excel binaire. Les fichiers XLSB peuvent être lus et écrits plus rapidement, ce qui les rend utiles pour travailler avec des fichiers volumineux. XLSB est rarement utilisé pour stocker des classeurs, car XLSX (et auparavant XLS) sont les formats de fichiers sélectionnés par les utilisateurs les plus courants pour enregistrer des classeurs. Il peut être ouvert par Microsoft Office 2007 et supérieur.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres documents de protection pris en charge" subTitle="En utilisant Java, on peut protéger d’autres fichiers, notamment." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/ods/" name="ODS" description="Fichier de feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xls/" name="XLS" description="Format binaire Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsm/" name="XLSM" description="Fichier de feuille de calcul" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/protect/xlsx/" name="XLSX" description="Fichier Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
