---
title: Gérer les métadonnées des fichiers Excel via C++

description: Afficher, ajouter, modifier, supprimer ou extraire les métadonnées des fichiers Excel à l'aide de la bibliothèque C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gérez les métadonnées de document Microsoft<sup>&reg;</sup> Excel via C++" h2="Affichez, insérez, mettez à jour, supprimez ou extrayez des propriétés de document Excel personnalisées et intégrées dans C++ applications." >}}
{{% blocks/products/pf/feature-page-summary %}}
Métadonnées dans Excel - Comment afficher, insérer et supprimer les métadonnées d'un fichier Excel. [C++ Bibliothèque Excel](/cells/cpp/) faclitates est de manière simple en prenant en charge les propriétés intégrées / définies par le système telles que le nom de l'auteur, le titre, les statistiques du document, etc. paires nom/valeur. Pour automatiser le processus, la bibliothèque prend en charge la création et la maintenance de fichiers Excel de métadonnées volumineux. [Méthode CreateIWorkbookCreateIWorkbook method](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) de [Classe Usine](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Ouvrez un classeur par chemin, par flux et par FileFormatType spécial. Chargez donc le fichier avec la méthode appropriée pour un traitement ultérieur. Quelques-unes des possibilités énumérées ci-dessous et les développeurs peuvent facilement améliorer leur code en fonction des besoins de l'application. 
 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Lire et mettre à jour les propriétés intégrées" %}}

Pour automatiser les propriétés intégrées, API fournit [GetIBuiltInDocumentProperties()](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata) méthode qui renvoie une collection DocumentProperties représentant toutes les propriétés de document intégrées de la feuille de calcul. Après avoir accédé à toutes les propriétés intégrées, accédez aux propriétés pertinentes à l'aide de la méthode appropriée telle que GetTitle(), GetSubject() etc. Pour mettre à jour les propriétés, API fournit une méthode telle que SetTitle, SetSubject, SetAuthor, SetComments etc. [collection de propriétés de document intégrée](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_built_in_document_property_collection) pour la fonction requise.

{{% blocks/products/pf/feature-page-code h3="C++ Code pour lire les propriétés définies par le système" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "read-system-defined-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C++ Code pour mettre à jour les propriétés intégrées" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "update-built-in-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Metadata" >}}
{{% blocks/products/pf/feature-page-section h2="Afficher et ajouter des propriétés définies personnalisées" %}}

Pour gérer les propriétés personnalisées, API fournit [IWorkbookMetadata::GetICustomDocumentProperties](https://reference.aspose.com/cells/cpp/class/aspose.cells.metadata.i_workbook_metadata#a69f0226813ce18c03ebc13b8ca691e79) qui renvoie toute la collection de propriétés de document personnalisées de la feuille de calcul. En accédant d'abord aux propriétés personnalisées via cette méthode, les développeurs peuvent utiliser des méthodes pertinentes pour ajouter des propriétés telles que AddIDocumentProperty, AddLinkToContentProperty et utiliser de la même manière UpdateLinkedPropertyValue, UpdateLinkedRange pour mettre à jour la valeur de la propriété du document personnalisé qui lie respectivement au contenu et à la plage liée. Les développeurs peuvent utiliser la méthode pertinente à partir de [ensemble de propriétés de document personnalisées](https://reference.aspose.com/cells/cpp/class/aspose.cells.properties.i_custom_document_property_collection).

{{% blocks/products/pf/feature-page-code h3="C++ Code pour afficher les propriétés personnalisées" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "view-custom-properties.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C++ Code pour ajouter des métadonnées dans un fichier Excel" %}}

{{< gist "aspose-com-gists" "d3c95be1fcfce10bd88c9cf1be2f923e" "add-custom-property.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
