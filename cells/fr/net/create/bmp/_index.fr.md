---
title: Créer BMP - Créer un fichier BMP dans C#
description: Aspose Exceller. C# Créez un fichier BMP rapidement et facilement avec Aspose.Cells. Générez un fichier BMP à l'aide de C#. Créez BMP dans C#. C# BMP Creater.
keywords: [Aspose Excel., C# Aspose.Cells., C# Create BMP file., Generate BMP file in C#., Create BMP file using C#., Write data to BMP file via C#., Create a BMP file in C#., C# Generate a BMP file., C# BMP Creater]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Créer un fichier BMP dans C#" h2="Bibliothèque C# haute vitesse pour créer BMP. Il s\'agit d\'une solution logicielle professionnelle pour importer et exporter XLSX, PDF et de nombreux autres formats sur les plates-formes .NET Framework, .NET Core ou Mono." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://releases.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Créer un fichier BMP à l\'aide de C#" %}}
 Comment créer le fichier BMP ? Avec la bibliothèque Aspose.Cells for .NET, vous pouvez facilement créer un fichier BMP par programme avec quelques lignes de code.[Aspose.Cells for .NET](https://products.aspose.com/cells/net)est capable de créer des applications multiplateformes avec la possibilité de générer, modifier, convertir, restituer et imprimer tous les fichiers Excel. .NET Excel API convertit non seulement entre les formats de feuilles de calcul, il peut également restituer des fichiers Excel sous forme d'images, PDF, HTML, ODS, CSV, SVG, JSON, WORD, PPT et plus, ce qui en fait un choix parfait pour échanger des documents dans des formats standard de l'industrie. Ouvrir[NuGet](https://www.nuget.org/packages/aspose.cells) gestionnaire de packages, recherchez Aspose.Cells et installez. Vous pouvez également utiliser la commande suivante à partir de la console Package Manager.

{{% blocks/products/pf/agp/code-block title="Commande de la console du gestionnaire de packages" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}
 
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="Comment créer BMP dans C#" %}}

{{% blocks/products/pf/agp/text %}}

 Il est facile pour les développeurs de créer, charger, modifier et convertir des fichiers BMP en exécutant différentes applications de reporting pour le traitement des données en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

1.  Incluez l'espace de noms dans votre fichier de classe
1.  Créez une instance de classe Workbook.
1.  Accédez à la première feuille de calcul du classeur.
1.  Obtenez la ou les cellules souhaitées de la feuille de calcul et saisissez la valeur dans la ou les cellules.
1.  Utilisez la méthode Save pour enregistrer le classeur en tant que fichier BMP.

{{% blocks/products/pf/agp/code-block title="L\'exemple de code montre comment créer le fichier BMP dans C#." offSpacer="" %}}

```cs

// Create Workbook class instance.
Workbook wkb = new Workbook();

// Access the first worksheet of the workbook.
Worksheet sht = wkb.Worksheets[0];

// Get the desired cell(s) of the worksheet.
Cell c00 = sht.Cells["A1"];
Cell c01 = sht.Cells["B1"];
Cell c10 = sht.Cells["A2"];
Cell c11 = sht.Cells["B2"];

// input the value into the cell(s).
c00.PutValue("ColumnA");
c01.PutValue("ColumnB");
c10.PutValue("ValueA");
c11.PutValue("ValueB");

// Save the Workbook as .bmp file.
wkb.Save("created_one.bmp");

```

{{% /blocks/products/pf/agp/code-block %}}
{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="Bibliothèque C# pour créer le fichier BMP" %}}

{{% blocks/products/pf/agp/text %}}

Il existe deux options alternatives pour installer « Aspose.Cells for .NET » sur votre système. Veuillez en choisir un qui correspond à vos besoins et suivre les instructions étape par étape :

{{% /blocks/products/pf/agp/text %}}

1.  Installer un[NuGet Colis](https://www.nuget.org/packages/Aspose.Cells/) . Voir[Documentation](https://docs.aspose.com/cells/net/installation/#install-asposecells-for-net-through-nuget)
1.  Installez la bibliothèque en utilisant[Console du gestionnaire de packages](https://docs.aspose.com/cells/net/installation/#install-asposecells-using-the-package-manager-console) dans l'IDE de Visual Studio

{{% /blocks/products/pf/agp/content %}}


{{% blocks/products/pf/agp/content h2="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Avant d'exécuter l'exemple de code de conversion .NET, assurez-vous que vous disposez des conditions préalables suivantes.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou un système d'exploitation compatible avec les plates-formes .NET, .NET Core, Windows Azure ou Mono.
-  Environnement de développement comme Microsoft Visual Studio.
-  Ajoutez une référence à la DLL Aspose.Cells for .NET dans votre projet.

{{% /blocks/products/pf/agp/content %}}

<!-- aboutfile Starts -->
    {{< blocks/products/pf/agp/about-file-section >}}
        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" >}}Les fichiers ayant l'extension .BMP représentent des fichiers d'images Bitmap utilisés pour stocker des images numériques bitmap. Ces images sont indépendantes de la carte graphique et sont également appelées format de fichier bitmap indépendant du périphérique (DIB). Cette indépendance sert à ouvrir le fichier sur plusieurs plateformes telles que Microsoft Windows et Mac. Le format de fichier BMP peut stocker des données sous forme d'images numériques bidimensionnelles au format monochrome et couleur avec différentes profondeurs de couleur.{{< /blocks/products/pf/agp/i18n/about-file-text >}}
    {{< /blocks/products/pf/agp/about-file-section >}}
<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres générations de feuilles de calcul prises en charge" subTitle="Vous pouvez également créer d’autres formats Excel Microsoft, dont quelques-uns répertoriés ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xls/" name="XLS" description="Microsoft Feuille de calcul Excel (ancienne version)" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsx/" name="XLSX" description="Classeur XML ouvert" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsb/" name="XLSB" description="Classeur binaire Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlsm/" name="XLSM" description="Feuille de calcul prenant en charge les macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xlt/" name="XLT" description="Modèle Excel 97-2003" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltx/" name="XLTX" description="Modèle Excel" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/xltm/" name="XLTM" description="Modèle Excel prenant en charge les macros" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/csv/" name="CSV" description="Valeurs séparées par des virgules" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/tsv/" name="TSV" description="Valeurs séparées par des tabulations" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/ods/" name="ODS" description="Feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/pdf/" name="PDF" description="Portable Document Format" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/create/html/" name="HTML" description="Langage Signalétique Hyper Text" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
