---
title: Rechercher et remplacer du texte dans le document ODS via .NET 
weight: 6100
url: /fr/net/redaction/ods/ 
description: Code source C# pour masquer les informations sensibles dans le fichier ODS sur .NET Framework, .NET Core, Mono ou Xamarin Platforms.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Masquer les formats ODS dans C#" h2="ODS natif et hautes performances documente les informations de masquage sensibles à l\'aide d\'API Aspose.Cells for .NET côté serveur, sans utiliser de logiciel tel que Microsoft ou Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Cells" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cells/aspose_cells-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-cells" liveDemosLink="https://products.aspose.app/cells/family" docsLink="https://docs.aspose.com/cells/net" installationsDocsLink="https://docs.aspose.com/cells/net" nugetLink="https://www.nuget.org/packages/aspose.cells" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cells/net" learnAsLink="https://docs.aspose.com/cells/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment expurger le fichier ODS à l\'aide de C#" %}}

 Pour expurger le fichier ODS, nous utiliserons
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 API qui est une plate-forme de manipulation de documents riche en fonctionnalités, puissante et facile à utiliser API pour C#. Ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.cells) 
 gestionnaire de paquets, recherchez
 **Aspose.Cells** 
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Commande" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Cells


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour expurger les fichiers ODS dans C#" %}}

{{% blocks/products/pf/agp/text %}}

 Une recherche de document de base et remplacer le texte dans le contenu, les commentaires ou les métadonnées avec
 [Aspose.Cells for .NET](https://products.aspose.com/cells/net) 
 Les API peuvent être réalisées avec seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

+ Charger le fichier ODS.
+ Sélectionnez la feuille.
+ Créer un objet FindOptions.
+ Définir les options de recherche
+ Parcourez chaque cellule et utilisez la méthode Find.
+ Enregistrez le classeur.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Nos API sont prises en charge sur toutes les principales plates-formes et systèmes d'exploitation. Avant d'exécuter le code ci-dessous, assurez-vous que vous disposez des prérequis suivants sur votre système.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec .NET Framework, .NET Core, Mono ou Xamarin Platforms- Environnement de développement comme Microsoft Visual Studio- Aspose.Cells for .NET DLL référencée dans votre projet : installez-la à partir de NuGet à l'aide du bouton Télécharger ci-dessus
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Masquer les fichiers ODS - C#" offSpacer="" %}}

```cs
Workbook wb = new Workbook("e:\test2\Input.ods");
Worksheet sheet = wb.Worksheets[0];
FindOptions opts = new FindOptions();
opts.LookInType = LookInType.Values;
opts.LookAtType = LookAtType.Contains;
opts.RegexKey = true;
Aspose.Cells.Cell cell = null;
do
{   //trouver uniquement le mot entier et non une partie d'un mot.  
    cell = sheet.Cells.Find("\bKIM\b", cell, opts);
    if (cell != null)
    {
        string celltext = cell.Value.ToString();
        celltext = celltext.Replace("KIM", "^^^^^^^^^^");
        cell.PutValue(celltext);
    }
}
while (cell != null);

wb.Save("e:\test2\out1.ods");

// Rechercher/Remplacer dans tout le classeur.

Workbook wb = new Workbook("e:\test2\Input.ods");
wb.Replace("\bKIM\b", "^^^^^^^^", new ReplaceOptions() { RegexKey = true });  
wb.Save("e:\test2\output.ods");


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="À propos de Aspose.Cells for .NET API" %}}

 Aspose.Cells API peut être utilisé pour créer, modifier, convertir et restituer des formats Microsoft Excel dans différents formats. De plus, il peut être utilisé pour des graphiques complets, des rapports évolutifs et des calculs fiables dans les applications logicielles. Aspose.Cells est un API autonome et ne nécessite aucun logiciel comme Microsoft ou OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Démos en direct sur la rédaction d\'ODS en ligne" sectionDescription="Recherchez et remplacez du texte dans le contenu, les commentaires ou les métadonnées des documents ODS dès maintenant en visitant notre [Site Web de démos en direct](https://products.aspose.app/cells/redaction). La démo en direct présente les avantages suivants" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire de code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement vos fichiers ODS." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Il sera expurgé instantanément." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODS" readMoreLink="https://docs.fileformat.com/spreadsheet/ods/" >}}
Les fichiers avec l'extension ODS représentent le format de document de feuille de calcul OpenDocument modifiable par l'utilisateur. Les données sont stockées dans le fichier ODF en lignes et en colonnes. Il s'agit d'un format basé sur XML et l'un des nombreux sous-types de la famille Open Document Formats (ODF). Le format est spécifié dans le cadre des spécifications ODF 1.2 publiées et maintenues par OASIS. Un certain nombre d'applications sous Windows ainsi que d'autres systèmes d'exploitation peuvent ouvrir des fichiers ODS pour l'édition et la manipulation, notamment Microsoft Excel, NeoOffice et LibreOffice. Les fichiers ODS peuvent également être convertis dans d'autres formats de feuille de calcul, tels que XLS, XLSX et autres, par différentes applications. 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de rédaction pris en charge" subTitle="En utilisant C#, on peut facilement expurger différents formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xls/" name="XLS" description="Format binaire Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsb/" name="XLSB" description="Fichier de classeur Excel binaire" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/redaction/xlsm/" name="XLSM" description="Fichier de feuille de calcul" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}