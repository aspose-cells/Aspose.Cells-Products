---
title:  Afficher les formats de fichiers HTML via .NET
description: Code source C# pour charger, restituer et afficher les documents HTML sur les plateformes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
keywords: [C# Aspose.Cells., c# view HTML files., c# how to render HTML document., c# load and display HTML files., HTML File Viewer using C#]
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="HTML Visionneuse de fichiers for .NET" h2="Affichez des feuilles de calcul Excel et OpenOffice telles que HTML sans nécessiter Microsoft Excel ou Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DOC" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment afficher le fichier HTML à l\'aide de C#" %}}

 Afin de visualiser le fichier HTML, nous utiliserons<a href="https://products.aspose.com/cells/net">Aspose.Cells for .NET</a>API qui est une plate-forme API riche en fonctionnalités, puissante et facile à utiliser pour C# à utiliser avec n'importe quel visualiseur. Ouvrir<a href="https://www.nuget.org/packages/aspose.cells">NuGet</a> gestionnaire de paquets, recherchez<b>Aspose.Cells</b> et installer. Vous pouvez également utiliser la commande suivante à partir de la console Package Manager.

{{% blocks/products/pf/agp/code-block title="Commande de la console du gestionnaire de packages" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour afficher le HTML via le C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells permet aux développeurs de visualiser facilement le fichier HTML avec seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

1. Charger le fichier HTML dans une instance de Workbook
1. Créez une instance de HtmlSaveOptions et définissez la propriété ExportHeadings sur true
1. Enregistrez le fichier HTML au format HTML à l'aide de la méthode Workbook.Save
1. Charger le résultat HTML dans le navigateur par défaut avec Process.Start


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Cells for .NET est pris en charge sur tous les principaux systèmes d'exploitation. Assurez-vous simplement que vous disposez des conditions préalables suivantes.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou un système d'exploitation compatible avec .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin Platforms
-  Environnement de développement comme Microsoft Visual Studio
-  Ajoutez une référence à la DLL Aspose.Cells for .NET dans votre projet

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Exemple de code C# pour afficher le fichier HTML" offSpacer="" %}}

```cs


string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the HTML file in an instance of Workbook
var book = new Aspose.Cells.Workbook("template.html");
// create an instance of HtmlSaveOptions & set ExportHeadings property to true
var options = new Aspose.Cells.HtmlSaveOptions();
options.ExportHeadings = true;

// save the HTML file in HTML format
book.Save(output, options);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Cells API peut être utilisé pour créer, éditer, convertir et restituer Microsoft des formats Excel vers différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables au sein d'applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Application gratuite pour afficher le HTML" sectionDescription=" Consultez nos démos en direct pour[Voir HTML](https://products.aspose.app/cells/viewer/html) avec les avantages suivants." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire ou de compiler du code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement le fichier HTML et cliquez sur le bouton \"Afficher\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Téléchargez le fichier HTML à partir du lien, si nécessaire" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML (Hyper Text Markup Language) est l'extension pour les pages Web créées pour être affichées dans les navigateurs. Connu sous le nom de langage du Web, le HTML a évolué avec les exigences de nouvelles informations à afficher dans les pages Web. La dernière variante est connue sous le nom de HTML 5 et offre une grande flexibilité pour travailler avec le langage. Les pages HTML sont soit reçues du serveur, où elles sont hébergées, soit peuvent également être chargées à partir du système local. Chaque page HTML est composée de HTML éléments tels que des formulaires, du texte, des images, des animations, des liens, etc. Ces éléments sont représentés par des balises telles que img, a, p et plusieurs autres où chaque balise a un début et une fin. Il peut également intégrer des applications écrites dans des langages de script tels que JavaScript et des feuilles de style (CSS) pour une représentation globale de la mise en page.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
