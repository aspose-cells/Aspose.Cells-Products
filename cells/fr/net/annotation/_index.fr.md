---
title: Annotations de fichier Excel NET C#
description: Ajoutez ou supprimez les annotations de données des feuilles de calcul Excel et OpenOffice avec seulement quelques lignes de code C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Supprimer les annotations de fichier Excel Microsoft<sup>&reg;</sup> via .NET" h2="Ajoutez ou supprimez des annotations de fichiers Excel à l\'aide du code C# dans les applications basées sur .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Bibliothèque Excel](/cells/fr/net/) fournit un support pour gérer les annotations au niveau de la cellule en ajoutant, accédant et supprimant des commentaires. À l'aide de commentaires au niveau de la cellule, des informations pertinentes peuvent être stockées pour les utilisateurs finaux. Les formats de fichiers pris en charge incluent ODS, XLS, XLSX, XLSB et XLSM.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Annotations des données des fichiers Excel" %}}
 Gestion des commentaires dans les feuilles de calcul - Il n'y a pas de limite au nombre de commentaires d'une feuille dans MS Excel. On peut ajouter autant d'exigences d'application. Nous utiliserons le[Classe de commentaire](https://reference.aspose.com/cells/net/aspose.cells/comment)pour toutes ces fonctionnalités.

+ Charger le fichier Excel à l'aide de l'objet de classe Workbook
+ Accéder à la feuille de travail pertinente et à son index Cell pertinent
+ Appelez RemoveAt avec l'identifiant Cell pour le supprimer
 + Utilisation[Remarque propriété](https://reference.aspose.com/cells/net/aspose.cells/comment/properties/note) pour ajouter du contenu de commentaires
+ Enregistrez le classeur avant et après avoir appelé la méthode RemoveAt pour comparer

{{% blocks/products/pf/feature-page-code h3="C# Code pour accéder, insérer et supprimer des fichiers Excel Cell Commentaires" %}}


{{< gist "aspose-com-gists" "e3dcb9c341b81d4db3a404ca7cd6e4cf" "access-insert-and-delete-excel-files-cell-comments.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Annotation" >}}
