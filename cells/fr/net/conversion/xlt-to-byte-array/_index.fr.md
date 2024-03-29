---
title:  Convertir XLT en tableau d'octets via C#
weight: 7690
description: C# Exemple de code pour la conversion XLT en tableau d’octets. Utilisez ce code pour la conversion Excel XLT en Byte Array dans VB.NET, Asp.NET ou toute application basée sur .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir XLT en tableau d\'octets via C#" h2="Conversion native et haute performance Microsoft Excel XLT en tableau d\'octets ou vice versa pour le traitement des données des feuilles de calcul à l\'aide des API .NET côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

 Byte Array est utile pour le traitement ou le stockage de données. Vous pouvez convertir le fichier XLT en Byte Array ainsi qu'un**Tableau d'octets à XLT** document utilisant la langue C#. Afin de convertir XLT en tableau d'octets, nous utiliserons
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API qui offre différentes fonctionnalités pour la manipulation et la conversion de documents à l'aide de la plateforme .NET.
{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Comment convertir XLT en tableau d\'octets via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Il est facile pour les développeurs de charger et de convertir des fichiers XLT en tableau d'octets pour des tâches de manipulation ultérieures en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

1.  Incluez l'espace de noms dans votre fichier de classe
1.  Charger le fichier d'entrée XLT à l'aide du classeur
1.  Initialiser l'objet MemoryStream
1.  Convertir les données de flux en tableau d'octets
1.  Traitez les données selon vos besoins

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

Assurez-vous simplement que ce système dispose de Microsoft Windows ou d'un système d'exploitation compatible avec .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin Platforms ainsi qu'un environnement de développement tel que Microsoft Visual Studio.

{{% /blocks/products/pf/agp/text %}}

-  Installer à partir de la ligne de commande en tant que<code>nuget install Aspose.Cells</code> ou via la console Package Manager de Visual Studio avec<code>Install-Package Aspose.Cells</code>.
-  Vous pouvez également obtenir le programme d'installation MSI hors ligne ou toutes les DLL dans un fichier ZIP à partir de<a href="https://downloads.aspose.com/cells/net">téléchargements</a>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Cet exemple de code montre la conversion XLT en tableau d\'octets C#." offSpacer="" %}}

```cs
Workbook workbook = new Workbook("sourceFile.xlt");

//Save the workbook in memory stream
MemoryStream ms = new MemoryStream();

workbook.Save(ms, SaveFormat.Xlt);

//Read bytes from memory stream
byte[] byte_array = new byte[ms.Length];
ms.Read(byte_array, 0, byte_array.Length);

// Process the memory stream byte array data as of your requirement 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->
      
     {{% blocks/products/pf/agp/content h2="" %}}

Une bibliothèque de programmation de feuilles de calcul Excel capable de créer des applications multiplateformes avec la possibilité de générer, modifier, convertir, restituer et imprimer tous les fichiers Excel. .NET Excel API convertit non seulement entre les formats de feuilles de calcul, il peut également restituer des fichiers Excel, notamment XLT sous forme d'images, PDF, HTML, ODS et plus, ce qui en fait un choix parfait pour échanger des documents dans des formats standard de l'industrie.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}
Les fichiers avec l'extension .xlt sont des fichiers modèles créés avec Microsoft Excel, un tableur faisant partie de la suite Office Microsoft. Microsoft Office 97-2003 prenait en charge la création de nouveaux fichiers XLT ainsi que leur ouverture. La dernière version d'Excel est toujours capable d'ouvrir les fichiers modèles dans cet ancien format. Un tel fichier modèle est utilisé pour créer rapidement de nouveaux fichiers Excel avec des données et des paramètres par défaut tels que le formatage de la page, la taille de la police, les marges, les graphiques, etc., qui peuvent ensuite être enregistrés en tant que nouveaux fichiers .xls.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

           {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir d\'autres formats de fichiers en tableau d\'octets ou vice versa, dont quelques-uns répertoriés ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-byte-array/" name="XLS vers un tableau d\'octets" description="Microsoft Feuille de calcul Excel (ancienne version)" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-byte-array/" name="XLSX vers un tableau d\'octets" description="Classeur XML ouvert" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsb-to-byte-array/" name="XLSB vers un tableau d\'octets" description="Classeur binaire Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsm-to-byte-array/" name="XLSM vers un tableau d\'octets" description="Feuille de calcul prenant en charge les macros" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlt-to-byte-array/" name="XLT vers un tableau d\'octets" description="Modèle Excel 97-2003" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltx-to-byte-array/" name="XLTX vers un tableau d\'octets" description="Modèle Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xltm-to-byte-array/" name="XLTM vers un tableau d\'octets" description="Modèle Excel prenant en charge les macros" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/csv-to-byte-array/" name="CSV vers un tableau d\'octets" description="Valeurs séparées par des virgules" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/tsv-to-byte-array/" name="TSV vers un tableau d\'octets" description="Valeurs séparées par des tabulations" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/ods-to-byte-array/" name="ODS vers un tableau d\'octets" description="Feuille de calcul OpenDocument" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-pdf/" name="XLS Au PDF" description="Portable Document Format" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-html/" name="XLS Au HTML" description="Langage Signalétique Hyper Text" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-pdf/" name="XLSX Au XPS" description="Microsoft Fichier Excel OOXML Excel" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-html/" name="XLSX Au HTML" description="Fichier Excel OOXML" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xlsx-to-svg/" name="XLSX Au SVG" description="Image Vectorielle" >}} {{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/conversion/xls-to-jpeg/" name="XLS Au JPEG" description="JPEG Image" >}} 

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
