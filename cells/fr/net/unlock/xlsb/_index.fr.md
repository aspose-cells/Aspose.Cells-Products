---
title: Déverrouiller le document XLSB via .NET 
weight: 6410
url: /fr/net/unlock/xlsb/ 
description: Code source C# pour déverrouiller le fichier XLSB protégé par mot de passe sur .NET Framework, .NET Core, Mono ou Xamarin Platforms.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Déverrouiller la feuille de calcul XLSB via C#" h2="Supprimez la protection de XLSB à l\'aide de la bibliothèque .NET." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="XLSB" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLSB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment déverrouiller le fichier XLSB à l\'aide de C#" %}}

 Afin de supprimer le fichier XLSB de protection, nous utiliserons
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API qui est une plate-forme de protection de documents riche en fonctionnalités, puissante et facile à utiliser API pour C#. Ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 gestionnaire de paquets, recherchez
 **Aspose.Cells** 
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Aspose.Cells" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Déverrouiller XLSB via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Vous avez besoin
 [aspose.cells.dll](https://downloads.aspose.com/cells/net) 
 référencé dans votre projet pour exécuter le workflow suivant.

{{% /blocks/products/pf/agp/text %}}

1. Instancier la classe Workbook avec le chemin d'accès au fichier XLSB protégé1. Obtenez la valeur par défaut ou n'importe quelle feuille de calcul pour supprimer la protection1. Supprimer la protection de la feuille de calcul avec la méthode Worksheet.Unprotect1. Supprimer la protection du classeur avec la méthode Workbook.Unprotect1. Enregistrer le résultat au format XLSB
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET est pris en charge sur tous les principaux systèmes d'exploitation. Assurez-vous simplement que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec .NET Framework, .NET Core, Mono ou Xamarin Platforms- Environnement de développement comme Microsoft Visual Studio- Aspose.Cells for .NET référencé dans votre projet
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Commande" offSpacer="" %}}

```cs

// instancier un objet Workbook avec un fichier XLSB protégé
var workbook = new Aspose.Cells.Workbook("protected.xlsb");

// accéder à la feuille de calcul par défaut dans le fichier Excel
var worksheet = workbook.Worksheets[0];

// déprotéger la feuille de calcul sans mot de passe
worksheet.Unprotect();

// déprotéger le classeur avec un mot de passe
workbook.Unprotect("password");

// enregistrer le résultat au format XLSB
workbook.Save("unprotected.xlsb", Aspose.Cells.SaveFormat.Auto);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="À propos de Aspose.Cells for .NET API" %}}

 Aspose.Cells API peut être utilisé pour créer, modifier, convertir et restituer des formats Microsoft Excel dans différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables dans les applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Application gratuite pour débloquer XLSB" sectionDescription="Consultez nos démos en direct pour [déverrouiller les fichiers XLSB](https://products.aspose.app/cells/unlock/xlsb) avec les avantages suivants." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire ou de compiler du code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement le fichier XLSB et appuyez sur le bouton \"Déverrouiller\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Téléchargez le fichier XLSB résultant à partir du lien" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLSB" readMoreLink="https://docs.fileformat.com/spreadsheet/xlsb/" >}}
Le format de fichier XLSB spécifie le format de fichier binaire Excel, qui est une collection d'enregistrements et de structures qui spécifient le contenu du classeur Excel. Le contenu peut inclure des tableaux de nombres non structurés ou semi-structurés, du texte, ou à la fois des nombres et du texte, des formules, des connexions de données externes, des graphiques et des images. Contrairement à XLSX (qui est basé sur le format de fichier Open XML), le XLSB représente un fichier de classeur Excel binaire. Les fichiers XLSB peuvent être lus et écrits plus rapidement, ce qui les rend utiles pour travailler avec des fichiers volumineux. XLSB est rarement utilisé pour stocker des classeurs, car XLSX (et auparavant XLS) sont les formats de fichier sélectionnés par l'utilisateur les plus courants pour enregistrer des classeurs. Il peut être ouvert par Microsoft Office 2007 et supérieur.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de déverrouillage pris en charge" subTitle="En utilisant C#, on peut facilement supprimer la protection/déverrouillage de différents formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/ods/" name="SAO" description="Fichier de feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xls/" name="XLS" description="Format binaire Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsm/" name="XLSM" description="Fichier de feuille de calcul" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/unlock/xlsx/" name="XLSX" description="Fichier Excel OOXML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}