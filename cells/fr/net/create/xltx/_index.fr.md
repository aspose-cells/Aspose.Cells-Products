---
title: Créer des fichiers MS Excel XLTX via C# 
url: /fr/net/create-xltx/ 
description: C# Exemple de code pour générer des documents XLTX. Utilisez ce code pour créer des fichiers MS Excel XLTX dans VB.NET, Asp.NET ou toute application basée sur .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Créer des documents XLTX via C#" h2="Création de feuilles de calcul MS Excel XLTX natives et hautes performances par programmation à l\'aide d\'API .NET côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLTX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 La génération dynamique de fichiers MS Excel XLTX dans l'application en cours d'exécution est facile. Afin de créer des documents XLTX à partir de zéro sans nécessiter MS Office, nous utiliserons
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API qui offre différentes fonctionnalités pour la création, la manipulation et la conversion de feuilles de calcul à l'aide de la plate-forme .NET. Les développeurs peuvent facilement améliorer le code pour écrire des données, générer des tableaux ou des graphiques ainsi que créer des tableaux dans des feuilles de calcul.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Comment créer XLTX via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Il est facile pour les développeurs de créer, charger, modifier et convertir une feuille de calcul MS Excel XLTX dans l'exécution de différentes applications de création de rapports pour le traitement des données en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

1. Inclure l'espace de noms dans votre fichier de classe1. Créer une instance de classe Workbook.1. Accédez à la première feuille de calcul du classeur.1. Obtenez la ou les cellules souhaitées de la feuille de calcul et entrez la valeur dans la ou les cellules.1. Utilisez la méthode Enregistrer pour enregistrer le classeur en tant que fichier XLTX.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Assurez-vous simplement que ce système dispose de Microsoft Windows ou d'un système d'exploitation compatible avec .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin Platforms ainsi qu'un environnement de développement tel que Microsoft Visual Studio. 

{{% /blocks/products/pf/agp/text %}}

- Installer à partir de la ligne de commande en tant que <code>nuget install Aspose.Cells</code> ou via Package Manager Console de Visual Studio avec <code>Install-Package Aspose.Cells</code>.- Vous pouvez également obtenir le programme d'installation MSI hors ligne ou toutes les DLL dans un fichier ZIP à partir de <a href="https://downloads.aspose.com/cells/net">téléchargements</a>
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Le code source suivant montre comment créer un fichier MS Excel XLTX à l\'aide de C#." offSpacer="" %}}

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

// Enregistrez le classeur en tant que fichier .xltx.
wkb.Save("created_one.xltx");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

     
     {{% blocks/products/pf/agp/content h2="" %}}

 Une bibliothèque de programmation de feuilles de calcul Excel capable de créer des applications multiplateformes avec la possibilité de générer, modifier, convertir, rendre et imprimer des fichiers MS Excel XLTX. .NET Excel API convertit non seulement les formats de feuille de calcul, mais peut également afficher les fichiers Excel sous forme d'images, de PDF, de HTML, d'ODS, etc., ce qui en fait un choix idéal pour échanger des documents dans des formats standard de l'industrie.

    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLTX" readMoreLink="https://docs.fileformat.com/spreadsheet/xltx/" >}}
Les fichiers avec l'extension .xltx représentent des fichiers de modèle Microsoft Excel basés sur les spécifications de format de fichier Office OpenXML. Il est utilisé pour créer un fichier de modèle standard qui peut être utilisé pour générer des fichiers XLSX qui présentent les mêmes paramètres que ceux spécifiés dans le fichier XLTX.

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
