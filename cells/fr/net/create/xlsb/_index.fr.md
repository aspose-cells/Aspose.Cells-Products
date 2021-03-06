---
title: Créer des fichiers MS Excel XLSB via C# 
url: /fr/net/create-xlsb/ 
description: C# Exemple de code pour générer des documents XLSB. Utilisez ce code pour créer des fichiers MS Excel XLSB dans VB.NET, Asp.NET ou toute application basée sur .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Créer des documents XLSB via C#" h2="Création de feuilles de calcul MS Excel XLSB natives et hautes performances par programmation à l\'aide d\'API .NET côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 La génération dynamique de fichiers MS Excel XLSB dans l'application en cours d'exécution est facile. Afin de créer des documents XLSB à partir de zéro sans nécessiter MS Office, nous utiliserons
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API qui offre différentes fonctionnalités pour la création, la manipulation et la conversion de feuilles de calcul à l'aide de la plate-forme .NET. Les développeurs peuvent facilement améliorer le code pour écrire des données, générer des tableaux ou des graphiques ainsi que créer des tableaux dans des feuilles de calcul.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Comment créer XLSB via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Il est facile pour les développeurs de créer, charger, modifier et convertir une feuille de calcul MS Excel XLSB dans l'exécution de différentes applications de reporting pour le traitement des données en seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

1. Inclure l'espace de noms dans votre fichier de classe1. Créer une instance de classe Workbook.1. Accédez à la première feuille de calcul du classeur.1. Obtenez la ou les cellules souhaitées de la feuille de calcul et entrez la valeur dans la ou les cellules.1. Utilisez la méthode Enregistrer pour enregistrer le classeur en tant que fichier XLSB.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Assurez-vous simplement que ce système dispose de Microsoft Windows ou d'un système d'exploitation compatible avec .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin Platforms ainsi qu'un environnement de développement tel que Microsoft Visual Studio. 

{{% /blocks/products/pf/agp/text %}}

- Installer à partir de la ligne de commande en tant que <code>nuget install Aspose.Cells</code> ou via Package Manager Console de Visual Studio avec <code>Install-Package Aspose.Cells</code>.- Vous pouvez également obtenir le programme d'installation MSI hors ligne ou toutes les DLL dans un fichier ZIP à partir de <a href="https://downloads.aspose.com/cells/net">téléchargements</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Le code source suivant montre comment créer un fichier MS Excel XLSB à l\'aide de C#." offSpacer="" %}}

```cs

// Créer une instance de classe Workbook.
Workbook wkb = new Workbook();

// Accédez à la première feuille de calcul du classeur.
Worksheet sht = wkb.Worksheets[0];

// Obtenez la ou les cellules souhaitées de la feuille de calcul.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// entrez la valeur dans la ou les cellules.
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Enregistrez le classeur en tant que fichier .xlsb.
wkb.Save("created_one.xlsb");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Une bibliothèque de programmation de feuilles de calcul Excel capable de créer des applications multiplateformes avec la capacité de générer, modifier, convertir, rendre et imprimer des fichiers MS Excel XLSB. .NET Excel API convertit non seulement les formats de feuille de calcul, mais peut également afficher les fichiers Excel sous forme d'images, de PDF, de HTML, d'ODS, etc., ce qui en fait un choix idéal pour échanger des documents dans des formats standard de l'industrie.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Le format de fichier XLSB spécifie le format de fichier binaire Excel, qui est une collection d'enregistrements et de structures qui spécifient le contenu du classeur Excel. Le contenu peut inclure des tableaux de nombres non structurés ou semi-structurés, du texte, ou à la fois des nombres et du texte, des formules, des connexions de données externes, des graphiques et des images. Contrairement à XLSX (qui est basé sur le format de fichier Open XML), le XLSB représente un fichier de classeur Excel binaire. Les fichiers XLSB peuvent être lus et écrits plus rapidement, ce qui les rend utiles pour travailler avec des fichiers volumineux. XLSB est rarement utilisé pour stocker des classeurs, car XLSX (et auparavant XLS) sont les formats de fichier sélectionnés par l'utilisateur les plus courants pour enregistrer des classeurs. Il peut être ouvert par Microsoft Office 2007 et supérieur.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< /blocks/products/pf/agp/about-file-section >}}

          

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autre génération de feuille de calcul prise en charge" subTitle="Vous pouvez également créer d\'autres formats Microsoft Excel, dont quelques-uns répertoriés ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xls/" name="XLS" description="Feuille de calcul Microsoft Excel (ancienne version)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsx/" name="XLSX" description="Ouvrir le classeur XML" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsb/" name="XLSB" description="Classeur binaire Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlsm/" name="XLSM" description="Feuille de calcul prenant en charge les macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xlt/" name="XLT" description="Excel 97 - Modèle 2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltx/" name="XLTX" description="Modèle Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-xltm/" name="XLMC" description="Modèle Excel compatible avec les macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-csv/" name="CSV" description="Valeurs séparées par des virgules" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-tsv/" name="VST" description="Valeurs séparées par des tabulations" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create-ods/" name="SAO" description="Feuille de calcul OpenDocument" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
