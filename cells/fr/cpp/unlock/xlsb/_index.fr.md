---
title:  Débloquer le document XLSB via le C++
weight: 7420
description: Exemple de code C++ pour déverrouiller le fichier XLSB protégé par mot de passe sur l'environnement d'exécution C++ pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
keywords: [C++ Aspose.Cells., C++ unlock XLSB files., C++ how to unlock XLSB document., C++ unprotect XLSB files., remove protection from XLSB files., decrypt XLSB Files using C++]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Déverrouiller les fichiers XLSB via C++" h2="Supprimez la protection des feuilles de calcul Excel, y compris le fichier XLSB, à l\'aide de la bibliothèque C++." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment supprimer la protection du fichier XLSB à l\'aide de C++" %}}

 Afin de déverrouiller le fichier XLSB, nous utiliserons
 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp) 
 API qui est une plateforme de protection de documents API for C++ riche en fonctionnalités, puissante et facile à utiliser. Vous pouvez télécharger sa dernière version directement, ouvrez simplement
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 gestionnaire de paquets, recherchez
 **Aspose.Cells.Cpp** 
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console Package Manager.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Débloquez le XLSB via le C++" %}}

{{% blocks/products/pf/agp/text %}}

 Vous avez besoin
 [aspose.cells.dll](https://downloads.aspose.com/cells/cpp) 
 référencé dans votre projet pour exécuter le workflow suivant.

{{% /blocks/products/pf/agp/text %}}

1.  Instancier la classe Workbook avec le chemin d'accès au fichier protégé XLSB
1.  Obtenez la valeur par défaut ou n'importe quelle feuille de calcul pour supprimer la protection
1.  Supprimer la protection de la feuille de calcul avec la méthode Worksheet.Unprotect
1.  Supprimer la protection du classeur avec la méthode Workbook.Unprotect
1.  Enregistrer le résultat au format XLSB

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for C++ prend en charge toutes les principales plates-formes et systèmes d'exploitation. Veuillez vous assurer que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou un système d'exploitation compatible avec l'environnement d'exécution C++ pour Windows 32 bits, Windows 64 bits et Linux 64 bits.
-  Ajoutez une référence à la DLL Aspose.Cells for C++ dans votre projet.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Commande" offSpacer="" %}}

```cs

Aspose::Cells::Startup();

// instantiate a Workbook object with protected XLSB file
Workbook workbook(u"protected.xlsb");

// access the default worksheet in the Excel file
Worksheet worksheet = workbook.GetWorksheets().Get(0);

// unprotect worksheet without a password
worksheet.Unprotect();

// unprotect workbook with password
workbook.Unprotect("password");

// save the result back in XLSB format
workbook.Save("unprotected.xlsb", SaveFormat::Auto);

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

        {{< blocks/products/pf/agp/demobox sectionTitle="Application gratuite pour débloquer le XLSB" sectionDescription=" Consultez nos démos en direct pour[débloquer les fichiers XLSB](https://products.aspose.app/cells/unlock/xlsb) avec les avantages suivants." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire ou de compiler du code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement le fichier XLSB et cliquez sur le bouton \"Déverrouiller\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Téléchargez le fichier XLSB résultant à partir du lien" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Le format de fichier XLSB spécifie le format de fichier binaire Excel, qui est un ensemble d'enregistrements et de structures spécifiant le contenu du classeur Excel. Le contenu peut inclure des tableaux de nombres non structurés ou semi-structurés, du texte, ou à la fois des nombres et du texte, des formules, des connexions de données externes, des graphiques et des images. Contrairement à XLSX (qui est basé sur le format de fichier Open XML), le XLSB représente un fichier de classeur Excel binaire. Les fichiers XLSB peuvent être lus et écrits plus rapidement, ce qui les rend utiles pour travailler avec des fichiers volumineux. XLSB est rarement utilisé pour stocker des classeurs, car XLSX (et auparavant XLS) sont les formats de fichiers sélectionnés par les utilisateurs les plus courants pour enregistrer des classeurs. Il peut être ouvert par Microsoft Office 2007 et supérieur.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de déverrouillage pris en charge" subTitle="En utilisant le C++, on peut facilement supprimer la protection/déverrouillage de différents formats notamment." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/ods/" name="ODS" description="Fichier de feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xls/" name="XLS" description="Format binaire Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsm/" name="XLSM" description="Fichier de feuille de calcul" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/cpp/unlock/xlsx/" name="XLSX" description="Fichier Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
