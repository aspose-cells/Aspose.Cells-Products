---
title:  Modifier ou afficher les métadonnées du document ODS via C++
weight: 1000
description: Exemple de code C++ pour modifier ou afficher les métadonnées du fichier ODS sur l'environnement d'exécution C++ pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
keywords: [C++ Aspose.Cells., C++ view ods metadata., C++ add ods metadata., C++ insert ods metadata., C++ edit ods metadata., C++ remove ods metadata., C++ extract ods metadata., C++ modify ods metadata]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Extraire les métadonnées ODS via C++" h2="Créez vos propres applications C++ pour ajouter, modifier, supprimer ou extraire des métadonnées des fichiers ODS à l\'aide d\'API côté serveur." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODS" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment obtenir les métadonnées ODS à l\'aide de C++" %}}

Afin d'extraire les métadonnées ODS, nous utiliserons
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API qui est une plateforme d'extraction de métadonnées de documents riche en fonctionnalités, puissante et facile à utiliser API for C++. Vous pouvez télécharger sa dernière version directement, ouvrez simplement
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 gestionnaire de paquets, recherchez
 **Aspose.Cells.Cpp** 
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console Package Manager.

{{% blocks/products/pf/agp/code-block title="Commande" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour extraire les métadonnées du ODS via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Accédez aux informations utiles stockées dans le fichier ODS, notamment quand le fichier ODS a été reçu, traité, horodaté, etc.

{{% /blocks/products/pf/agp/text %}}

+ Créer des options à l'aide de MetadataOptions
+ Charger le fichier ODS à l'aide de WorkbookMetadata
+ Ajouter de nouvelles propriétés par GetCustomDocumentProperties() et Add
+ Enregistrer le document ODS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ prend en charge toutes les principales plates-formes et systèmes d'exploitation. Veuillez vous assurer que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou un système d'exploitation compatible avec l'environnement d'exécution C++ pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
-  Ajoutez une référence à la DLL Aspose.Cells for C++ dans votre projet.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extraire les métadonnées de ODS - C++" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

//Load the sample excel file
MetadataOptions options(MetadataType::Document_Properties);
WorkbookMetadata meta(u"c:\\book1.ods", options);
//Add a new custom property
meta.GetCustomDocumentProperties().Add(u"test", u"test");
//Save the output excel file
meta.Save(u"c:\\book2.ods");

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

        {{< blocks/products/pf/agp/demobox sectionTitle="Extraire les métadonnées du ODS via l\'application en ligne" sectionDescription=" Afficher et modifier les métadonnées des documents ODS en utilisant notre[Démos en direct](https://products.aspose.app/cells/metadata) avec les avantages suivants." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire de code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement votre fichier ODS et modifiez les propriétés du document." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtenez instantanément le lien de téléchargement du fichier résultant" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Les fichiers avec l'extension ODS représentent le format de document OpenDocument Spreadsheet qui sont modifiables par l'utilisateur. Les données sont stockées dans le fichier ODF en lignes et colonnes. Il s'agit d'un format basé sur XML et l'un des nombreux sous-types de la famille Open Document Formats (ODF). Le format est spécifié dans le cadre des spécifications ODF 1.2 publiées et maintenues par OASIS. Un certain nombre d'applications sur Windows ainsi que d'autres systèmes d'exploitation peuvent ouvrir des fichiers ODS pour les éditer et les manipuler, notamment Microsoft Excel, NeoOffice et LibreOffice. Les fichiers ODS peuvent également être convertis dans d'autres formats de feuilles de calcul, comme XLS, XLSX et autres par différentes applications.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de métadonnées pris en charge" subTitle="En utilisant C++, on peut également manipuler des métadonnées de nombreux autres formats, notamment" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xls/" name="XLS" description="Format binaire Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsb/" name="XLSB" description="Fichier de classeur Excel binaire" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsm/" name="XLSM" description="Fichier de feuille de calcul" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/metadata/xlsx/" name="XLSX" description="Fichier Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
