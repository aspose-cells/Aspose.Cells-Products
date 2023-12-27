---
title: Ajouter ou supprimer des annotations de fichiers Excel via C++
description: Ajoutez ou supprimez des commentaires d'annotation de données des feuilles de calcul Excel et OpenOffice avec la bibliothèque C++.
keywords: [C++ Aspose.Cells., add excel annotation., insert excel annotation., access excel annotation., remove excel annotation., delete excel annotation., add annotation in excel., insert annotation in excel., access annotation in excel., remove annotation in excel., delete annotation in excel]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gérer les annotations de fichiers Excel Microsoft<sup>&reg;</sup> via C++" h2="Ajoutez ou supprimez des notes simples pour des annotations ou des commentaires dans les applications basées sur C++." >}}
{{% blocks/products/pf/feature-page-summary %}}
[C++ Exceller API](/cells/fr/cpp/) fournit un support pour gérer les annotations au niveau des cellules en ajoutant, accédant et supprimant des commentaires. API fournit[Commentaire](https://reference.aspose.com/cells/cpp/aspose.cells/comment/) et[Collection de commentaires](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/) ainsi que[GetComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/getcomments/)pour gérer les commentaires sous tous leurs aspects. Les formats Excel pris en charge incluent ODS, XLS, XLSX, XLSB et XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Annotations de données de fichiers Excel" %}}
 Manipulation des commentaires dans les feuilles de calcul - Le nombre de commentaires d'une feuille dans MS Excel n'est pas limité. On peut en insérer autant que nécessaire. Le processus d'insertion de commentaires est de créer[Cahier d'exercices](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) objet de classe pour charger un fichier existant et sélectionner la feuille de calcul dans laquelle vous souhaitez ajouter le commentaire. Obtenez tous ses commentaires en utilisant getComments(). Ajoutez le commentaire en utilisant[Ajouter(const char16_t* cellName)](https://reference.aspose.com/cells/cpp/aspose.cells/commentcollection/add/) méthode. Obtenez l'index de cellule et utilisez[DéfinirNote](https://reference.aspose.com/cells/cpp/aspose.cells/comment/setnote/) pour insérer des commentaires. De plus, API est capable de supprimer tous les commentaires. Peu de méthodes sont[ClearComments()](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/clearcomments/) à Efface tous les commentaires dans la feuille de calcul du concepteur. De plus,***Supprimer à*** méthode pour supprimer l’élément à un index spécifié ou avec un nom spécifié.

{{% blocks/products/pf/feature-page-code h3="C++ Code pour ajouter des commentaires dans un fichier Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "add-comment-in-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
