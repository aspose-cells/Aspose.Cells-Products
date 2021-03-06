---
title: Convertissez XLT en XML via l'application C++ 
url: /fr/cpp/conversion/xlt-to-xml/ 
description: Exemple de code de conversion C++ pour le document XLT au format XML. Les programmeurs peuvent utiliser ce code source pour la conversion par lots de XLT en XML dans n'importe quelle application C++.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir XLT en XML via C++" h2="Conversion XLT vers XML haute performance à l\'aide de la bibliothèque C++ sans avoir besoin de l\'installation de Microsoft Excel, OpenOffice ou Adobe Acrobat." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="XML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="XLT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/cpp" installationsDocsLink="https://docs.aspose.com/cells/cpp" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/cpp" learnAsLink="https://docs.aspose.com/cells/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment convertir XLT en XML à l\'aide de C++" %}}

 Pour convertir XLT en XML, nous utiliserons
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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir XLT en XML via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Les développeurs C++ peuvent facilement convertir un fichier XLT en XML en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

1. Chargez le fichier XLT à l'aide de Factory :: CreateIWorkbook.1. Appelez la méthode Save().1. Transmettez le chemin du fichier de sortie avec l'extension de fichier (XML).1. Le fichier XML sera enregistré dans le chemin spécifié.1. Ouvrez le fichier XML dans un programme compatible.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Avant d'exécuter l'exemple de code de conversion C++, assurez-vous que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec C++ Runtime Environment pour Windows 32 bits, Windows 64 bits et Linux 64 bits.- Aspose.Cells pour C++ DLL référencée dans votre projet.
- Microsoft Windows ou un système d'exploitation compatible avec C++ Runtime Environment pour Windows 32 bits, Windows 64 bits et Linux 64 bits.- Aspose.Cells pour C++ DLL référencée dans votre projet.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Code source de conversion XLT vers XML C++" offSpacer="" %}}

```cs
// Chargez le XLT.
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlt");

// Enregistrer au format XML.
wkb->Save(u"convertedFile.xml", SaveFormat_Xml);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Démonstrations en direct de conversion XLT vers XML" sectionDescription="[Convertir XLT en XML](https://products.aspose.app/cells/conversion/xlt-to-xml) dès maintenant en visitant notre site Web Live Demos. La démonstration en direct présente les avantages suivants" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire de code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement votre fichier XLT, il sera converti instantanément en XML." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Vous obtiendrez le lien de téléchargement." >}}

    {{% blocks/products/pf/agp/content h2="C++ Bibliothèque de manipulation de fichiers Excel" %}}

 Excel API peut être utilisé pour créer, modifier, convertir et restituer des formats Microsoft Excel dans différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables dans les applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XLT" readMoreLink="https://docs.fileformat.com/spreadsheet/xlt/" >}}

Les fichiers avec l'extension .XLT sont des fichiers modèles créés avec Microsoft Excel qui est une application de feuille de calcul qui fait partie de la suite Microsoft Office. Microsoft Office 97-2003 prenait en charge la création de nouveaux fichiers XLT ainsi que leur ouverture. La dernière version d'Excel est toujours capable d'ouvrir les fichiers de modèle de cet ancien format. Un tel fichier de modèle est utilisé pour créer rapidement de nouveaux fichiers Excel avec des données et des paramètres par défaut tels que le formatage de la page, la taille de la police, les marges, les graphiques, etc., qui peuvent ensuite être enregistrés en tant que nouveaux fichiers .XLS.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="XML" readMoreLink="https://docs.fileformat.com/web/xml/" >}}

XML signifie Extensible Markup Language qui est similaire à HTML mais différent dans l'utilisation de balises pour définir des objets. L'idée derrière la création du format de fichier XML était de stocker et de transporter des données sans dépendre d'outils logiciels ou matériels. Sa popularité est due au fait qu'il est à la fois lisible par l'homme et par la machine. Cela lui permet de créer des protocoles de données communs sous la forme d'objets à stocker et à partager sur un réseau tel que le World Wide Web (WWW). Le "X" dans XML est pour extensible, ce qui implique que le langage peut être étendu à n'importe quel nombre de symboles selon les besoins de l'utilisateur. C'est pour ces fonctionnalités que de nombreux formats de fichiers standard l'utilisent tels que Microsoft Open XML, LibreOffice OpenDocument, XHTML et SVG.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}