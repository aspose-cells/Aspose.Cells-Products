---
title: Fusionner différents fichiers Excel en un seul dans Java
url: /fr/java/merger/
description: Fusionnez des fichiers Excel à l'aide de Java en plusieurs feuilles ou en une seule feuille. Fusionnez, combinez ou concaténez des documents Excel en PDF, images et HTML également.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Fusion de fichiers Microsoft<sup>&reg;</sup> Excel via Java" h2="Combinez deux ou plusieurs fichiers Excel dans une seule feuille de calcul en utilisant le code Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Bibliothèque Excel](/cells/java/) fournit plusieurs façons de combiner des classeurs avec différents types de contenu tels que des formules, des images, des données, des graphiques, etc. dans un seul document de feuille de calcul. Les formats de fichiers pris en charge incluent XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV et plus encore.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combinez des fichiers Excel avec des images et des graphiques" %}}
Le moyen le plus simple de combiner deux fichiers Excel contenant des images et des graphiques consiste à appeler le [Classeur.combine](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) méthode. Il permet de fusionner des fichiers Excel de type similaire dans une seule feuille de calcul.
{{% blocks/products/pf/feature-page-code h3="Java Code pour combiner des fichiers Excel" %}}

```cs
// charger le premier fichier Excel
var book1 = new Workbook("with-charts.xlsx");
// charger le deuxième fichier Excel dans une instance distincte
var book2 = new Workbook("with-images.xlsx");

// fusionner deux classeurs
book1.combine(book2);
// enregistrer le classeur cible 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Fusionner plusieurs fichiers Excel" %}}
[CellsHelper.mergeFiles](https://apireference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) prend en charge la fusion des données, du style et des formules d'un fichier Excel dans une nouvelle feuille de calcul du même format. C'est un moyen efficace de fusionner plusieurs fichiers tout en utilisant la mise en cache. 
{{% blocks/products/pf/feature-page-code h3="Java Code pour fusionner plusieurs fichiers Excel" %}}

```cs
// créer un tableau (longueur=2)
String[] files = new String[2];
// spécifier les chemins des fichiers à fusionner
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// fusionner les fichiers pour enregistrer le résultat
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Fusionner des fichiers Excel en copiant des feuilles de calcul" %}}
[Feuille de travail.copie](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)peut être utilisé pour copier des données et la mise en forme d'une feuille de calcul source vers une autre feuille de calcul dans ou entre des classeurs. La méthode prend l'objet feuille de calcul source comme paramètre.
{{% blocks/products/pf/feature-page-code h3="Java Code pour copier des feuilles de calcul entre des classeurs" %}}

```cs
// Créer un classeur.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Créez un autre classeur.
Workbook excelWorkbook1 = new Workbook();

// Copiez la première feuille du premier livre dans le deuxième livre.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Enregistrez le fichier.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}