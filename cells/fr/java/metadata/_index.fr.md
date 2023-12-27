---
title: Gérer les métadonnées des fichiers Excel via Java
description: Afficher, ajouter, modifier, supprimer ou extraire les métadonnées des fichiers Excel avec seulement quelques lignes de code Java
keywords: [Java Aspose.Cells., Java view excel metadata., Java add excel metadata., Java insert excel metadata., Java edit excel metadata., Java remove excel metadata., Java extract excel metadata., Java modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gérer les métadonnées du fichier Excel Microsoft<sup>&reg;</sup> via Java" h2="Affichez, ajoutez, mettez à jour, supprimez ou extrayez les propriétés de fichiers Excel personnalisées et intégrées à l\'aide des API Java côté serveur." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Exceller API](/cells/fr/java/) prend en charge la gestion des propriétés intégrées (définies par le système) telles que le titre, le nom de l'auteur, les statistiques du document, etc., ainsi que des propriétés personnalisées (définies par l'utilisateur) sous la forme d'une paire nom/valeur. Il y a[Classe de classeur](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) pour charger les fichiers, et[Collection de feuilles de calcul](https://reference.aspose.com/cells/java/com.aspose.cells/WorksheetCollection) traite de la collecte de feuilles de travail ainsi que[Classe de feuille de travail](https://reference.aspose.com/cells/java/com.aspose.cells/Worksheet) pour représenter une seule feuille de calcul. Pour accéder aux propriétés intégrées et personnalisées, BuiltInDocumentProperties, CustomDocumentProperties simplifie le processus de gestion des métadonnées.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Gestion des propriétés définies par le système" %}}

 Pour gérer les propriétés intégrées, API fournit[Propriétés du document intégré](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#BuiltInDocumentProperties) et les programmeurs peuvent facilement accéder à une propriété intégrée et mettre à jour sa valeur. En fonction des besoins de l'application, les développeurs peuvent utiliser l'index ou le nom de propriété du[DocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentPropertyCollection). 

{{% blocks/products/pf/feature-page-code h3="Java Code pour gérer les propriétés définies par le système" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "update-system-defined-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Ajouter et supprimer des métadonnées définies personnalisées" %}}

Pour gérer les propriétés personnalisées, API fournit[Propriétés du document personnalisé](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#CustomDocumentProperties) , et les développeurs peuvent facilement accéder aux propriétés existantes ainsi qu'en ajouter de nouvelles à l'aide de[ajouter une méthode](https://reference.aspose.com/cells/java/com.aspose.cells/customdocumentpropertycollection#add(java.lang.String,%20boolean) ) de[CustomDocumentPropertyCollection](https://reference.aspose.com/cells/java/com.aspose.cells/CustomDocumentPropertyCollection) la classe ajoute la propriété et renvoie une référence pour la nouvelle propriété en tant que[Propriétés.DocumentProperty](https://reference.aspose.com/cells/java/com.aspose.cells/DocumentProperty) objet. La classe DocumentProperty est utilisée pour récupérer le nom, la valeur et le type de la propriété du document comme[DocumentProperty.Name](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Name), [DocumentProperty.Value](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Value),  [DocumentProperty.Type](https://reference.aspose.com/cells/java/com.aspose.cells/documentproperty#Type) qui renvoie l'un des[Type de propriété](https://reference.aspose.com/cells/java/com.aspose.cells/PropertyType) valeurs d'énumération.
 
{{% blocks/products/pf/feature-page-code h3="Java Code pour ajouter des métadonnées dans un fichier Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "add-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Code pour supprimer une propriété personnalisée dans un fichier Excel" %}}

{{< gist "aspose-com-gists" "5e0a55903d07671e241651dd9711c555" "remove-custom-properties.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
