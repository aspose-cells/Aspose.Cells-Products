---
title: Gérer les métadonnées des fichiers Excel via C++
description: Afficher, ajouter, modifier, supprimer ou extraire les métadonnées des fichiers Excel à l'aide de la bibliothèque C++
keywords: [C++ Aspose.Cells., C++ view excel metadata., C++ add excel metadata., C++ insert excel metadata., C++ edit excel metadata., C++ remove excel metadata., C++ extract excel metadata., C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gérer les métadonnées des documents Excel Microsoft<sup>&reg;</sup> via C++" h2="Affichez, insérez, mettez à jour, supprimez ou extrayez les propriétés de documents Excel personnalisées et intégrées dans les applications C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Métadonnées dans Excel - Comment afficher, insérer et supprimer les métadonnées d'un fichier Excel.[C++ Bibliothèque Excel](/cells/fr/cpp/) facilite cela de manière simple en prenant en charge les propriétés intégrées/définies par le système telles que le nom de l'auteur, le titre, les statistiques du document, etc. nécessaires parfois, comme pour vérifier quand le dernier fichier est modifié ou enregistré avec des propriétés personnalisées/définies par l'utilisateur sous la forme de paires nom/valeur. Pour automatiser le processus, la bibliothèque prend en charge la création et la maintenance de gros fichiers Excel de métadonnées.[Cahier d'exercices](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/)classe Ouvre un classeur par chemin, par flux et par FileFormatType spécial. Chargez donc le fichier avec la méthode appropriée pour un traitement ultérieur. Peu de possibilités répertoriées ci-dessous et les développeurs peuvent facilement améliorer leur code en fonction des besoins de l'application.
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Lire et mettre à jour les propriétés intégrées" %}}

 Pour automatiser les propriétés intégrées, API fournit[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getbuiltindocumentproperties/) méthode qui renvoie une collection DocumentProperties représentant toutes les propriétés de document intégrées de la feuille de calcul. Après avoir accédé à toutes les propriétés intégrées, accédez aux propriétés pertinentes à l'aide de la méthode appropriée telle que GetTitle(), GetSubject() etc. Pour mettre à jour les propriétés, API fournit une méthode telle que SetTitle, SetSubject, SetAuthor, SetComments etc.[collection de propriétés de document intégrée](https://reference.aspose.com/cells/cpp/aspose.cells.properties/builtindocumentpropertycollection/) pour la fonction requise.

{{% blocks/products/pf/feature-page-code h3="C++ Code pour lire les propriétés définies par le système" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Code pour mettre à jour les propriétés intégrées" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Afficher et ajouter des propriétés définies personnalisées" %}}

Pour gérer les propriétés personnalisées, API fournit[Classeur ::GetCustomDocumentProperties](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/getcustomdocumentproperties/) qui renvoie toute la collection de propriétés de document personnalisées de la feuille de calcul. En accédant d'abord aux propriétés personnalisées via cette méthode, les développeurs peuvent utiliser des méthodes pertinentes pour ajouter des propriétés telles que AddIDocumentProperty, AddLinkToContentProperty et utiliser de la même manière UpdateLinkedPropertyValue, UpdateLinkedRange pour mettre à jour la valeur de la propriété du document personnalisé qui est respectivement liée au contenu et à la plage liée. Les développeurs peuvent utiliser la méthode pertinente de[collection de propriétés de document personnalisées](https://reference.aspose.com/cells/cpp/aspose.cells.properties/customdocumentpropertycollection/).

{{% blocks/products/pf/feature-page-code h3="C++ Code pour afficher les propriétés personnalisées" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Code pour ajouter des métadonnées dans un fichier Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
