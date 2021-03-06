---
title: Diviser la feuille de calcul Excel en feuilles de calcul dans Java
url: /fr/java/splitter/
description: Java codes sources expliquant comment diviser des fichiers Microsoft Excel en plusieurs documents à l'aide de la Java bibliothèque Excel
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Fractionnement de fichiers Microsoft<sup>®</sup> Excel via Java" h2="Divisez la feuille de calcul Excel en feuilles de calcul dans les applications basées sur Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Il existe une variété de scénarios, lorsqu'il est nécessaire de diviser des fichiers Excel comme une feuille de calcul contenant des données sur les étudiants avec l'attribution d'une seule feuille pour chaque étudiant. Et il est nécessaire de diviser chaque feuille par élève dans un fichier séparé. Pour l'automatiser via l'application Java, [Java Excel API](/cells/java/) est là pour diviser le document Excel par feuille. Les formats pris en charge incluent XLS, XLSX, XLSB, XLSM, ODS. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Diviser un document Excel en plusieurs fichiers" %}}

Le moyen le plus simple de diviser un fichier Excel en feuille est d'accéder à toutes les feuilles, de parcourir chaque feuille et de les enregistrer une par une dans le format souhaité. Pour charger la feuille de calcul, API fournit [Cahier](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) classe. [getWorksheets().getCount()](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) méthode obtient le nombre total de feuilles. Parcourez chaque feuille et utilisez [getWorksheets().get(sheetindex)](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) pour accéder à une feuille spécifique. Déplacez les données de feuille sélectionnées dans l'objet de classe Workbook nouvellement créé en utilisant [Méthode de copie](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Enfin, enregistrez-le au format requis.

{{% blocks/products/pf/feature-page-code h3="Java Code pour diviser les fichiers Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Diviser la feuille de calcul Excel en volets" %}}

API fournit également la fonctionnalité de fractionnement de la feuille de calcul Excel en différents volets. Le processus consiste à charger le fichier à l'aide de la classe Workbook. Sélectionnez la première feuille de calcul ou toute feuille requise en fournissant son index. Appelez le setActiveCell ayant l'index de cellule pertinent comme paramètre. Et enfin, divisez la fenêtre de la feuille de calcul en différents volets en appelant la méthode split ().

{{% blocks/products/pf/feature-page-code h3="Java Code pour diviser la feuille Excel en vue de volet" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}