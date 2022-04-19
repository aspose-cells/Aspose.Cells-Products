---
title: Annotations de fichiers Excel via Java
url: /fr/java/annotation/
description: Ajoutez ou supprimez des annotations de données de feuilles de calcul Excel et OpenOffice avec la bibliothèque Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Gérer les annotations de fichiers Excel Microsoft<sup>&reg;</sup> via Java" h2="Insérez des notes simples pour les annotations ou supprimez les commentaires au niveau des cellules de la feuille de calcul Excel dans les applications basées sur Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Excel API](/cells/java/) fournit un support pour gérer les annotations au niveau de la cellule en ajoutant, accédant et supprimant des commentaires. API fournit [Commenter](https://apireference.aspose.com/cells/java/com.aspose.cells/Comment), [Collection de commentaires](https://apireference.aspose.com/cells/java/com.aspose.cells/CommentCollection), [Commentaire fileté](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedComment) et [ThreadedCommentCollection](https://apireference.aspose.com/cells/java/com.aspose.cells/ThreadedCommentCollection) pour traiter les commentaires sous tous leurs aspects.
Les formats de fichiers pris en charge incluent ODS, XLS, XLSX, XLSB et XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Annotations des données des fichiers Excel" %}}
Gestion des commentaires dans les feuilles de calcul - Il n'y a pas de limite au nombre de commentaires d'une feuille dans MS Excel. On peut ajouter autant d'exigences d'application. Le processus d'ajout de commentaires consiste à créer [Cahier](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) objet de classe ou chargez un fichier existant à l'aide de la classe Workbook. Accédez à tous ses commentaires à l'aide de getComments(). Obtenez l'index de cellule et utilisez [setNote](https://apireference.aspose.com/cells/java/com.aspose.cells/comment#Note) pour insérer des commentaires. De plus, API est capable de supprimer tous les commentaires. 

{{% blocks/products/pf/feature-page-code h3="Java Code pour ajouter des commentaires dans le fichier Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "add-comments-excel-file.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Java Code pour supprimer les commentaires dans le fichier Excel" %}}

{{< gist "aspose-com-gists" "1b223bbd23b1c5b3fb5c96614e5584c6" "remove-annotation-in-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}