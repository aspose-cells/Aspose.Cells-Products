---
title: Insérer des commentaires dans Excel via .NET
description:  C# codes sources indiquant comment insérer un commentaire dans les fichiers Excel Microsoft à l'aide de la bibliothèque .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Insertion de commentaires Excel via .NET" h2="Créez des documents Excel et insérez des commentaires à l\'aide des API côté serveur dans les applications basées sur .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}

 Vous pouvez ajouter des commentaires aux cellules. Lorsqu'une cellule contient un commentaire, un indicateur apparaît dans le coin de la cellule. Les commentaires s'affichent lorsque vous placez votre curseur sur une cellule. Ces commentaires peuvent être utilisés pour la discussion, des instructions spéciales ou le balisage du contenu du document.[.NET Bibliothèque Excel](/cells/fr/net/)prend en charge l'insertion de commentaires dans les fichiers Excel. Pour cela, le API fournit un[Commentaire](https://reference.aspose.com/cells/net/aspose.cells/comment) classe pour le bloc de construction de commentaires.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Insérer des commentaires dans le fichier Excel" %}}

 L'insertion de commentaires à l'aide d'Excel API est simple. Le processus est, Créer[Classe de classeur](https://reference.aspose.com/cells/net/aspose.cells/workbook) objet et sélectionnez la première feuille de calcul ou la feuille pertinente en fournissant son index. Insérez les données de cellules requises à l'aide de[Méthode PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Ajouter un commentaire à la feuille de calcul en utilisant[Collection de commentaires](https://reference.aspose.com/cells/net/aspose.cells/commentcollection) c'est[Ajouter une méthode](https://reference.aspose.com/cells/net/aspose.cells.commentcollection/add/methods/1).

{{% blocks/products/pf/feature-page-code h3="C# Code pour insérer un commentaire dans Excel" %}}

{{< gist "aspose-cells-gists" "59a1901d62ea9ceb08456a818431a898" "InsertCommentIntoWorksheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
