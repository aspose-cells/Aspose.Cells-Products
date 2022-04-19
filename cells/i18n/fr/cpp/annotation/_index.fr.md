---
title: Annotations de fichiers Excel via C++
url: /fr/cpp/annotation/
description: Ajoutez ou supprimez des commentaires d'annotation de données de feuilles de calcul Excel et OpenOffice avec la bibliothèque C++.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gérer les annotations de fichiers Excel Microsoft<sup>&reg;</sup> via C++" h2="Ajoutez ou supprimez des notes simples pour les annotations ou les commentaires dans les applications basées sur C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Excel API](/cells/cpp/) fournit un support pour gérer les annotations au niveau de la cellule en ajoutant, accédant et supprimant des commentaires. API fournit [ICommentaire](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment) et [ICommentCollection](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection) ainsi que [GetIComments()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ae7cce5f85b7b25a1e5c58df1b613ca5a) pour traiter les commentaires sous tous leurs aspects. Les formats Excel pris en charge incluent ODS, XLS, XLSX, XLSB et XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Annotations des données des fichiers Excel" %}}
Manipulation des commentaires dans les feuilles de calcul - Le nombre de commentaires d'une feuille dans MS Excel n'est pas limité. On peut insérer autant de besoin d'application. Le processus d'insertion de commentaires consiste à créer [IClasseur](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) objet de classe pour charger un fichier existant et sélectionner la feuille de calcul dans laquelle vous souhaitez ajouter le commentaire. Obtenez tous ses commentaires en utilisant getComments(). Ajoutez le commentaire en utilisant [Ajouter](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_comment_collection#a3f014415e292fa15c6220e9727dad384)(intrusif_ptr < Aspose::Cells::Systems::String > méthode CellName). Obtenez l'index de cellule et utilisez [setNote](https://apireference.aspose.com/cells/cpp/com.aspose.cells/comment#Note) pour insérer des commentaires. De plus, API est capable de supprimer tous les commentaires. Peu de méthodes sont [Effacer les commentaires()](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet#ad4e0ea291ae60fc1b5d815e520edc6c3) à Efface tous les commentaires dans la feuille de calcul du concepteur. En outre, [Supprimer à](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#addabcc7d7d76874694018fb3ba37b72c)(intrusif_ptr< Aspose::Cells::Systems::String > name) pour supprimer l'élément à un index spécifié ou avec un nom spécifié.

{{% blocks/products/pf/feature-page-code h3="C++ Code pour ajouter des commentaires dans le fichier Excel" %}}

{{< gist "aspose-com-gists" "e144512d2c395c3336f12ce960424686" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}