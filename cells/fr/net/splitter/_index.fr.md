---
title: Diviser la feuille de calcul Excel en C#
description: C# codes sources qui expliquent comment diviser les fichiers Excel Microsoft en plusieurs fichiers dans les applications Visual C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Fractionnement de fichier Excel via .NET" h2="Divisez un seul document Excel en différents fichiers à l\'aide du code C# dans les applications basées sur .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Bibliothèque Excel](/cells/fr/net/) est capable de diviser un document Excel en plusieurs feuilles de calcul dans des applications basées sur .NET. Les formats de fichiers pris en charge incluent XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Diviser un document Excel en plusieurs fichiers" %}}
 Le moyen le plus simple de diviser les fichiers Excel par feuille est d'accéder à toutes les feuilles via[Des feuilles de calcul](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Itérer sur chaque feuille et appeler le[Copie](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) méthode. Enfin, enregistrez-le dans un chemin spécifié.

 + Chargez le fichier Excel avec le chemin complet en utilisant[Classe de classeur](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Itérer à travers chaque feuille
+ Créer un nouvel objet de classe Workbook
 + Copier la feuille via[Méthode de copie](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Appelez la méthode Save() et transmettez le nom du fichier (chemin complet) ayant le SaveFormat pertinent.

{{% blocks/products/pf/feature-page-code h3="C# Code pour diviser les fichiers Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Diviser la feuille de calcul Excel en volets" %}}

 Pour diviser la fenêtre de la feuille de calcul en volets, API fournit[Méthode de fractionnement](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split)de la classe de feuille de calcul, qui fournit la vue fractionnée de la feuille de calcul. Pour supprimer la vue fractionnée API fournit[Méthode RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Enfin, enregistrez-le dans un chemin spécifié.

{{% blocks/products/pf/feature-page-code h3="C# Code pour diviser la fenêtre de feuille de calcul Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Code pour supprimer la vue panoramique fractionnée" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
