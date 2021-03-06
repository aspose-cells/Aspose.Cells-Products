---
title: Convertir MHTML en GIF via l'application C++ 
weight: 3630
url: /fr/cpp/conversion/mhtml-to-gif/ 
description: Exemple de code de conversion C++ pour un document MHTML au format GIF. Les programmeurs peuvent utiliser ce code source pour la conversion par lots de MHTML en GIF dans n'importe quelle application C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir MHTML en GIF via C++" h2="Conversion MHTML en GIF haute performance à l\'aide de la bibliothèque C++ sans avoir besoin de l\'installation de Microsoft Excel, OpenOffice ou Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment convertir MHTML en GIF en utilisant C++" %}}

 Pour convertir MHTML en GIF, nous utiliserons
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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir MHTML en GIF via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Les développeurs C++ peuvent facilement convertir un fichier MHTML en GIF en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

1. Chargez le fichier MHTML à l'aide de Factory :: CreateIWorkbook.1. Sélectionnez la première feuille de calcul.1. Définir les options (GIF).1. Parcourez chaque page de la feuille et effectuez le rendu.1. Ouvrez le fichier GIF dans un programme compatible.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Avant d'exécuter l'exemple de code de conversion C++, assurez-vous que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec C++ Runtime Environment pour Windows 32 bits, Windows 64 bits et Linux 64 bits.- Aspose.Cells pour C++ DLL référencée dans votre projet.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Code source de conversion MHTML vers GIF C++" offSpacer="" %}}

```cs
// Chemin du répertoire de sortie.
StringPtr outDir = new String("OutputDirectoryPath");

// Chargez le MHTML.
intrusive_ptr<Aspose::Cells::IWorkbook> workbook = Factory::CreateIWorkbook(u"sourceFile.mhtml");

// Accéder à la première feuille de calcul.
intrusive_ptr<Aspose::Cells::IWorksheet> worksheet = workbook->GetIWorksheets()->GetObjectByIndex(0);

// Créez une image ou un objet d'options d'impression.
intrusive_ptr<Aspose::Cells::Rendering::IImageOrPrintOptions> imgOptions = Factory::CreateIImageOrPrintOptions();

// Spécifiez le format d'image.
imgOptions->SetImageFormat(Aspose::Cells::Systems::Drawing::Imaging::ImageFormat::GetGif());

// Spécifiez la résolution horizontale et verticale
imgOptions->SetHorizontalResolution(200);
imgOptions->SetVerticalResolution(200);

// Effectuez le rendu de la feuille en fonction de l'image ou des options d'impression spécifiées.
intrusive_ptr<Aspose::Cells::Rendering::ISheetRender> sr = Factory::CreateISheetRender(worksheet, imgOptions);

// Obtenez le nombre de pages.
Aspose::Cells::Systems::Int32 pageCount = sr->GetPageCount();

// Créer un objet générateur de chaînes pour les concaténations de chaînes.
intrusive_ptr<Aspose::Cells::Systems::Text::StringBuilder> sb = new Aspose::Cells::Systems::Text::StringBuilder();

// Rendez chaque page en image gif une par une.
for (int i = 0; i Clear();
	sb->Append(outDir);
	sb->Append((StringPtr)new String("outputConvertingWorksheetToImageGIF_"));
	sb->Append(i);
	sb->Append((StringPtr)new String(".gif"));

	// Obtenez le chemin de l'image de sortie.
	StringPtr outputGIF = sb->ToString();

	// Convertir la feuille de calcul en image gif.
	sr->ToImage(i, outputGIF);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Démonstrations en direct de conversion MHTML en GIF" sectionDescription="[Convertir MHTML en GIF](https://products.aspose.app/cells/conversion/mhtml-to-gif) dès maintenant en visitant notre site Web Live Demos. La démonstration en direct présente les avantages suivants" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire de code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement votre fichier MHTML, il sera converti instantanément en GIF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Vous obtiendrez le lien de téléchargement." >}}

    {{% blocks/products/pf/agp/content h2="C++ Bibliothèque de manipulation de fichiers Excel" %}}

 Excel API peut être utilisé pour créer, modifier, convertir et restituer des formats Microsoft Excel dans différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables dans les applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

Les fichiers avec l'extension MHTML représentent un format d'archive de page Web qui peut être créé par un certain nombre d'applications différentes. Le format est connu sous le nom de format d'archive car il enregistre le code HTML Web et les ressources associées dans un seul fichier. Ces ressources incluent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans une variété d'applications telles qu'Internet Explorer et Microsoft Word. Microsoft Windows utilise le format de fichier MHTML pour enregistrer les scénarios de problèmes observés lors de l'utilisation de toute application sous Windows qui pose des problèmes. Le format de fichier MHTML encode le contenu de la page de manière similaire aux spécifications définies dans message/rfc822, qui sont des spécifications relatives aux e-mails en texte brut. Les spécifications réelles du format sont détaillées dans la RFC 2557.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif/" >}}

Un format GIF ou Graphical Interchange est un type d'image hautement compressée. Propriété d'Unisys, GIF utilise l'algorithme de compression LZW qui ne dégrade pas la qualité de l'image. Pour chaque image, le GIF autorise généralement jusqu'à 8 bits par pixel et jusqu'à 256 couleurs sont autorisées sur l'image. Contrairement à une image JPEG, qui peut afficher jusqu'à 16 millions de couleurs et touche assez les limites de l'œil humain. À l'époque de l'émergence d'Internet, les GIF restaient le meilleur choix car ils nécessitaient une faible bande passante et étaient compatibles avec les graphiques qui consommaient des zones de couleur unies. Un GIF animé combine de nombreuses images ou cadres dans un seul fichier et les affiche dans une séquence pour générer un clip animé ou une courte vidéo. Les limitations de couleur vont jusqu'à 256 pour chaque image et sont probablement les moins appropriées pour reproduire d'autres images et photographies avec un dégradé de couleurs.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir MHTML en de nombreux autres formats de fichiers, dont quelques-uns sont répertoriés ci-dessous." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-bmp/" name="MHTML EN BMP" description="Image bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-csv/" name="MHTML VERS CSV" description="Valeurs séparées par des virgules" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-dif/" name="MHTML EN DIF" description="Format d\'échange de données" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-emf/" name="MHTML À EMF" description="Format de métafichier amélioré" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-html/" name="MHTML VERS HTML" description="Langage Signalétique Hyper Text" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-jpeg/" name="MHTML À JPEG" description="Images JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-ods/" name="MHTML À ODS" description="Fichier de feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-pdf/" name="MHTML EN PDF" description="Portable Document Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-png/" name="MHTML EN PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-svg/" name="MHTML EN SVG" description="Image Vectorielle" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-tiff/" name="MHTML VERS TIFF" description="Format d\'image balisé" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-tsv/" name="MHTML À TSV" description="Valeurs séparées par des tabulations" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xls/" name="MHTML À XLS" description="Format binaire Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsb/" name="MHTML VERS XLSB" description="Fichier de classeur Excel binaire" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsm/" name="MHTML À XLSM" description="Fichier de feuille de calcul" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xlsx/" name="MHTML À XLSX" description="Fichier Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xltm/" name="MHTML À XLTM" description="Modèle Excel compatible avec les macros" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xltx/" name="MHTML VERS XLTX" description="Modèle Office OpenXML Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/conversion/mhtml-to-xps/" name="MHTML À XPS" description="Spécifications papier XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}