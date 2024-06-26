---
title: Rechercher et remplacer le texte dans le document XLSM via C++
weight: 9570
description: Exemple de code C++ pour rédiger des informations sensibles dans le fichier XLSM sur l'environnement d'exécution C++ pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
keywords: [C++ Aspose.Cells., C++ Search and replace text in XLSM file., C++ redact XLSM file., C++ edit XLSM file., C++ XLSM file redaction., C++ Search and replace string in XLSM file]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Rédiger les formats XLSM dans C++" h2="XLSM natif et hautes performances documentent des informations de rédaction sensibles à l\'aide d\'API Aspose.Cells for C++ côté serveur, sans utiliser de logiciel tel que Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="XLSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment expurger le fichier XLSM à l\'aide de C++" %}}

 Afin de rédiger le fichier XLSM, nous utiliserons[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) API qui est une plateforme de rédaction de documents API for C++ riche en fonctionnalités, puissante et facile à utiliser. Vous pouvez télécharger sa dernière version directement, ouvrez simplement[NuGet](https://www.nuget.org/packages/aspose.cells) gestionnaire de paquets, recherchez**Aspose.Cells.Cpp** et installer. Vous pouvez également utiliser la commande suivante à partir de la console Package Manager.

{{% blocks/products/pf/agp/code-block title="Commande" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour expurger les fichiers XLSM dans C++" %}}

{{% blocks/products/pf/agp/text %}}

 Un document de base recherche et remplace le texte dans le contenu, les commentaires ou les métadonnées par[Aspose.Cells for C++](https://products.aspose.com/cells/cpp) Les API peuvent être réalisées avec seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

+ Chargez le fichier XLSM.
+ Définir les options de remplacement.
Définir l'option de sensibilité à la casse.
+ Définir l'option de correspondance de texte
+ Remplacer le texte en utilisant la méthode Replace(...)
+ Enregistrez le classeur.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ prend en charge toutes les principales plates-formes et systèmes d'exploitation. Veuillez vous assurer que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou un système d'exploitation compatible avec l'environnement d'exécution C++ pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
-  Ajoutez une référence à la DLL Aspose.Cells for C++ dans votre projet.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Rédiger les dossiers XLSM - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// Load XLSM file
Workbook wb(u"Input.xlsm");
//Create an instance of the ReplaceOptions class
ReplaceOptions replaceOptions;
// Set text matching option
replaceOptions.SetRegexKey(true);
// Set case sensitivity option
replaceOptions.SetCaseSensitive(false);
// Set text matching option
replaceOptions.SetMatchEntireCellContents(false);
// Replace text
wb.Replace(u"\bKIM\b", u"^^^^^^^^", replaceOptions);
// Save as XLSM file
wb.Save("output.xlsm");

Aspose::Cells::Cleanup();

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="À propos du Aspose.Cells for C++ API" %}}

 Aspose.Cells API peut être utilisé pour créer, éditer, convertir et restituer Microsoft des formats Excel vers différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables au sein d'applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="En ligne XLSM Rédaction Démos en direct" sectionDescription=" Recherchez et remplacez du texte dans le contenu, les commentaires ou les métadonnées des documents XLSM dès maintenant en visitant notre[Site Web de démonstrations en direct](https://products.aspose.app/cells/redaction). La démo en direct présente les avantages suivants" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger le Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire de code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement vos fichiers XLSM." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Il sera expurgé instantanément." >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSM" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsm/" >}}
Les fichiers avec l'extension XLSM sont un type de fichier de feuille de calcul prenant en charge les macros. Du point de vue de l'application, une macro est un ensemble d'instructions utilisées pour automatiser les processus. Une macro est utilisée pour enregistrer les étapes effectuées à plusieurs reprises et facilite l'exécution des actions en exécutant à nouveau la macro. Les macros sont programmées avec Visual Basic pour Applications (VBA) de Microsoft à partir du classeur Excel à l'aide de Visual Basic Editor et peuvent être exécutées/déboguées directement à partir de là.

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres documents de rédaction pris en charge" subTitle="En utilisant le C++, on peut facilement rédiger différents formats, notamment." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/ods/" name="ODS" description="Fichier de feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xls/" name="XLS" description="Format binaire Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsb/" name="XLSB" description="Fichier de classeur Excel binaire" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/redaction/xlsx/" name="XLSX" description="Fichier Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
