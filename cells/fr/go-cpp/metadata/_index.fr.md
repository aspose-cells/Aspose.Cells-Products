---
title: Gérez les métadonnées des fichiers Excel avec Go via C++
description: Afficher, ajouter, modifier, supprimer ou extraire les métadonnées des fichiers Excel à l'aide de Go via la bibliothèque C++
keywords: [Go via C++ Aspose.Cells., Go via C++ view excel metadata., Go via C++ add excel metadata., Go via C++ insert excel metadata., Go via C++ edit excel metadata., Go via C++ remove excel metadata., Go via C++ extract excel metadata., Go via C++ modify excel metadata]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gérer les métadonnées du document Excel Microsoft via Go via C++" h2="Afficher, insérer, mettre à jour, supprimer ou extraire des propriétés de document Excel personnalisées et intégrées dans les applications C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Métadonnées dans Excel - Comment afficher, insérer et supprimer les métadonnées d'un fichier Excel.[Accédez à la bibliothèque Excel via C++](/cells/fr/go-cpp/)La bibliothèque facilite la gestion des propriétés intégrées/définies par le système, telles que le nom de l'auteur, le titre et les statistiques du document, nécessaires notamment pour vérifier la dernière modification ou le dernier enregistrement d'un fichier, ainsi que des propriétés personnalisées/définies par l'utilisateur sous forme de paires nom/valeur. Pour automatiser le processus, elle permet de créer et de gérer des fichiers Excel de métadonnées volumineux.[Cahier d'exercices](https://reference.aspose.com/cells/go-cpp/workbook/) Cette classe ouvre un classeur par chemin, par flux et par un format de fichier spécifique. Chargez ensuite le fichier avec la méthode appropriée pour un traitement ultérieur. Quelques exemples sont présentés ci-dessous ; les développeurs peuvent ainsi facilement adapter leur code aux besoins de l’application.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Lire et mettre à jour les propriétés intégrées" %}}

 Pour automatiser les propriétés intégrées, API fournit[GetBuiltInDocumentProperties()](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/)Cette méthode renvoie une collection DocumentProperties représentant toutes les propriétés intégrées du document. Après avoir accédé à toutes les propriétés intégrées, utilisez les méthodes appropriées telles que GetTitle(), GetSubject(), etc. Pour mettre à jour les propriétés, la bibliothèque API propose des méthodes telles que SetTitle, SetSubject, SetAuthor, SetComments, etc. Consultez la documentation.[collection de propriétés de document intégrée](https://reference.aspose.com/cells/go-cpp/workbook/getbuiltindocumentproperties/) pour la fonction requise.

{{% blocks/products/pf/feature-page-code h3="Accédez au code C++ pour lire les propriétés définies par le système" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "read-system-defined-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Accédez au code C++ pour mettre à jour les propriétés intégrées" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "update-built-in-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Afficher et ajouter des propriétés personnalisées" %}}

 Pour la gestion des propriétés personnalisées, API fournit[Classeur::ObtenirPropriétésDocumentPersonnalisées](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/)Cette méthode renvoie la collection complète des propriétés personnalisées du document. En accédant à ces propriétés, les développeurs peuvent utiliser les méthodes appropriées pour ajouter des propriétés telles que `AddIDocumentProperty` et `AddLinkToContentProperty`, et de même, utiliser `UpdateLinkedPropertyValue` et `UpdateLinkedRange` pour mettre à jour la valeur des propriétés personnalisées liées respectivement au contenu et à la plage de fichiers. Les développeurs peuvent utiliser les méthodes appropriées de…[collection de propriétés de document personnalisées](https://reference.aspose.com/cells/go-cpp/workbook/getcustomdocumentproperties/).

{{% blocks/products/pf/feature-page-code h3="Accédez au code C++ pour consulter les propriétés personnalisées" %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "view-custom-properties.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="Utilisez le code C++ pour ajouter des métadonnées à un fichier Excel." %}}

{{< gist "aspose-cells-gists" "b414abd53259bbc47d2c3c0fe985395b" "add-custom-property.go" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/feature-page-wrap >}}