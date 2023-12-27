---
title: Gérer les métadonnées des fichiers Excel via .NET C#
description: Afficher, ajouter, modifier, supprimer ou extraire les métadonnées des fichiers Excel avec seulement quelques lignes de code C#
keywords: [C# Aspose.Cells., c# view excel metadata., c# add excel metadata., c# insert excel metadata., c# edit excel metadata., c# remove excel metadata., c# extract excel metadata., c# modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gérer les métadonnées du fichier Excel Microsoft<sup>&reg;</sup> via .NET" h2="Affichez, ajoutez, mettez à jour, supprimez ou extrayez les propriétés de fichiers Excel intégrées et personnalisées à l\'aide des API .NET côté serveur." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Exceller API](/cells/fr/net/) prend en charge la gestion des propriétés (intégrées) définies par le système telles que le titre, le nom de l'auteur, les statistiques du document, etc. ainsi que les propriétés (personnalisées) définies par l'utilisateur sous la forme d'une paire nom-valeur. Il y a[Classe de classeur](https://reference.aspose.com/cells/net/aspose.cells/workbook) pour charger les fichiers, et[Collection de feuilles de calcul](https://reference.aspose.com/cells/net/aspose.cells/worksheetcollection) traite de la collecte de feuilles de travail ainsi que[Classe de feuille de travail](https://reference.aspose.com/cells/net/aspose.cells/worksheet) pour représenter une seule feuille de calcul. Parallèlement à ces classes, BuiltInDocumentProperties et CustomDocumentProperties simplifient le processus de gestion des métadonnées.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gestion des propriétés intégrées" %}}

 Pour gérer les propriétés définies par le système, API fournit[Propriétés du document intégré](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/builtindocumentproperties) et les programmeurs peuvent facilement accéder à une propriété intégrée et mettre à jour sa valeur. En fonction des besoins de l'application, les développeurs peuvent utiliser l'index ou le nom de propriété du[DocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/documentpropertycollection). 

{{% blocks/products/pf/feature-page-code h3="C# Code pour gérer les propriétés intégrées" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "manage-system-defined-excel-file-metadata.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Gestion des propriétés définies personnalisées" %}}

 Pour gérer les propriétés définies par l'utilisateur, API fournit[Propriétés du document personnalisé](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/customdocumentproperties) , et les développeurs peuvent facilement accéder aux propriétés déjà ajoutées ainsi qu'en ajouter de nouvelles. Afin d'ajouter des propriétés personnalisées,[Ajouter une méthode](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) de[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) la classe ajoute la propriété et renvoie une référence pour la nouvelle propriété en tant que[Propriétés.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty) objet. La classe DocumentProperty est utilisée pour récupérer le nom, la valeur et le type de la propriété du document comme[DocumentProperty.Name](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/name), [DocumentProperty.Value](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/value),  [DocumentProperty.Type](https://reference.aspose.com/cells/net/aspose.cells.properties/documentproperty/properties/type) qui renvoie l'un des[Type de propriété](https://reference.aspose.com/cells/net/aspose.cells.properties/propertytype) valeurs d'énumération.
 
{{% blocks/products/pf/feature-page-code h3="C# Code pour ajouter des métadonnées dans un fichier Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "add-metadata-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C# Code pour supprimer une propriété personnalisée dans un fichier Excel" %}}

{{< gist "aspose-com-gists" "4a24d575e6a00d294868ca9df12f21ae" "remove-custom-properties-in-excel-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
