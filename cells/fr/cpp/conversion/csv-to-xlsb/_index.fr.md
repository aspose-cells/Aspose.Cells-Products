---
title: Convertir CSV en XLSB via l'application C++ 
weight: 9780
url: /fr/cpp/conversion/csv-to-xlsb/ 
description: Exemple de code de conversion C++ pour le document CSV au format XLSB. Les programmeurs peuvent utiliser ce code source pour la conversion par lots CSV vers XLSB dans n'importe quelle application C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir CSV en XLSB via C++" h2="Conversion CSV vers XLSB haute performance à l\'aide de la bibliothèque C++ sans avoir besoin de l\'installation de Microsoft Excel, OpenOffice ou Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CSV" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment convertir CSV en XLSB en utilisant C++" %}}

 Pour convertir CSV en XLSB, nous utiliserons
 [Aspose.Cells pour C++](https://products.aspose.com/cells/cpp) 
 API qui est une plate-forme de manipulation et de conversion de documents riche en fonctionnalités, puissante et facile à utiliser API pour C++. Vous pouvez télécharger sa dernière version directement, il suffit d'ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 gestionnaire de paquets, recherchez
 Aspose.Cells.Cpp 
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Commande" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir CSV en XLSB via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Les développeurs C++ peuvent facilement convertir un fichier CSV en XLSB en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

1. Chargez le fichier CSV à l'aide de Factory :: CreateIWorkbook.1. Appelez la méthode Save().1. Transmettez le chemin du fichier de sortie avec l'extension de fichier (XLSB).1. Le fichier XLSB sera enregistré dans le chemin spécifié.1. Ouvrez le fichier XLSB dans un programme compatible.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Avant d'exécuter l'exemple de code de conversion C++, assurez-vous que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec C++ Runtime Environment pour Windows 32 bits, Windows 64 bits et Linux 64 bits.- Aspose.Cells pour C++ DLL référencée dans votre projet.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="CSV vers XLSB C++ Code source de conversion" offSpacer="" %}}

```cs
// Chargez le CSV.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.csv");

// Enregistrer au format XLSB.
wkb->Save(u"convertedFile.xlsb", SaveFormat_Xlsb);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Démonstrations en direct de conversion CSV vers XLSB" sectionDescription="[Convertir CSV en XLSB](https://products.aspose.app/cells/conversion/csv-to-xlsb) dès maintenant en visitant notre site Web Live Demos. La démonstration en direct présente les avantages suivants" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire de code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement votre fichier CSV, il sera converti instantanément en XLSB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Vous obtiendrez le lien de téléchargement." >}}

    {{% blocks/products/pf/agp/content h2="C++ Bibliothèque de manipulation de fichiers Excel" %}}

 Excel API peut être utilisé pour créer, modifier, convertir et restituer des formats Microsoft Excel dans différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables dans les applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="CSV" readMoreLink="https://docs.fileformat.com/spreadsheet/csv/" >}}

Les fichiers avec l'extension CSV (Comma Separated Values) représentent des fichiers de texte brut qui contiennent des enregistrements de données avec des valeurs séparées par des virgules. Chaque ligne d'un fichier CSV est un nouvel enregistrement de l'ensemble d'enregistrements contenus dans le fichier. De tels fichiers sont générés lorsque le transfert de données est prévu d'un système de stockage à un autre. Étant donné que toutes les applications peuvent reconnaître les enregistrements séparés par des virgules, l'importation de ces fichiers de données dans la base de données se fait de manière très pratique. Presque toutes les applications de tableur telles que Microsoft Excel ou OpenOffice Calc peuvent importer du CSV sans trop d'effort. Les données importées à partir de ces fichiers sont disposées dans des cellules d'une feuille de calcul pour être présentées à l'utilisateur.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}

Le format de fichier XLSB spécifie le format de fichier binaire Excel, qui est une collection d'enregistrements et de structures qui spécifient le contenu du classeur Excel. Le contenu peut inclure des tableaux de nombres non structurés ou semi-structurés, du texte, ou à la fois des nombres et du texte, des formules, des connexions de données externes, des graphiques et des images. Contrairement à XLSX (qui est basé sur le format de fichier Open XML), le XLSB représente un fichier de classeur Excel binaire. Les fichiers XLSB peuvent être lus et écrits plus rapidement, ce qui les rend utiles pour travailler avec des fichiers volumineux. XLSB est rarement utilisé pour stocker des classeurs, car XLSX (et auparavant XLS) sont les formats de fichier sélectionnés par l'utilisateur les plus courants pour enregistrer des classeurs. Il peut être ouvert par Microsoft Office 2007 et supérieur.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir CSV en de nombreux autres formats de fichiers, dont quelques-uns sont répertoriés ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-bmp/" name="CSV VERS BMP" description="Image bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-dif/" name="CSV VERS DIF" description="Format d\'échange de données" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-emf/" name="CSV VERS EMF" description="Format de métafichier amélioré" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-gif/" name="CSV VERS GIF" description="Format d\'échange graphique" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-html/" name="CSV VERS HTML" description="Langage Signalétique Hyper Text" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-jpeg/" name="CSV VERS JPEG" description="Images JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-mhtml/" name="CSV VERS MHTML" description="Format d\'archivage des pages Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-ods/" name="CSV VERS ODS" description="Fichier de feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-pdf/" name="CSV EN PDF" description="Portable Document Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-png/" name="CSV EN PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-svg/" name="CSV VERS SVG" description="Image Vectorielle" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tiff/" name="CSV VERS TIFF" description="Format d\'image balisé" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-tsv/" name="CSV VERS TSV" description="Valeurs séparées par des tabulations" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xls/" name="CSV VERS XLS" description="Format binaire Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsm/" name="CSV VERS XLSM" description="Fichier de feuille de calcul" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xlsx/" name="CSV VERS XLSX" description="Fichier Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltm/" name="CSV VERS XLTM" description="Modèle Excel compatible avec les macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xltx/" name="CSV VERS XLTX" description="Modèle Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/csv-to-xps/" name="CSV VERS XPS" description="Spécifications papier XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}