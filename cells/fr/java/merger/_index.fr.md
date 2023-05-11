---
title: Fusionner différents fichiers Excel en un seul dans Java
description: Fusionnez des fichiers Excel à l'aide de Java en plusieurs feuilles ou en une seule feuille. Fusionnez, combinez ou concaténez des documents Excel en PDF, Images et HTML également.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Fusion de fichiers Excel via Java" h2="Combinez deux ou plusieurs fichiers Excel dans une seule feuille de calcul en utilisant le code Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Bibliothèque Excel](/cells/fr/java/) fournit plusieurs façons de combiner des classeurs avec différents types de contenu tels que des formules, des images, des données, des graphiques, etc. dans un seul document de feuille de calcul. Les formats de fichiers pris en charge incluent XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV et plus encore.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Combinez des fichiers Excel avec des images et des graphiques" %}}
 Le moyen le plus simple de combiner deux fichiers Excel contenant des images et des graphiques consiste à appeler le[Classeur.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) méthode. Il permet de fusionner des fichiers Excel de type similaire dans une seule feuille de calcul.
{{% blocks/products/pf/feature-page-code h3="Java Code pour combiner des fichiers Excel" %}}

```cs
// load first Excel file
var book1 = new Workbook("with-charts.xlsx");
// load second Excel file into a separate instance
var book2 = new Workbook("with-images.xlsx");

// merge two workbooks
book1.combine(book2);
// save the target workbook 
book1.save("combined.xlsx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Fusionner plusieurs fichiers Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) prend en charge la fusion des données, du style et des formules d'un fichier Excel dans une nouvelle feuille de calcul du même format. C'est un moyen efficace de fusionner plusieurs fichiers tout en utilisant la mise en cache.
{{% blocks/products/pf/feature-page-code h3="Java Code pour fusionner plusieurs fichiers Excel" %}}

```cs
// create an Array (length=2)
String[] files = new String[2];
// specify file paths to be merged
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// merge the files to save the result
CellsHelper.mergeFiles(files, "cache", "merged.xls");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Fusionner des fichiers Excel en copiant des feuilles de calcul" %}}
[Feuille de travail.copie](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)) peut être utilisé pour copier des données et la mise en forme d'une feuille de calcul source vers une autre feuille de calcul dans ou entre des classeurs. La méthode prend l'objet feuille de calcul source comme paramètre.
{{% blocks/products/pf/feature-page-code h3="Java Code pour copier des feuilles de calcul entre des classeurs" %}}

```cs
// Create a Workbook.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Create another Workbook.
Workbook excelWorkbook1 = new Workbook();

// Copy the first sheet of the first book into second book.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Save the file.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de fusion pris en charge" subTitle="En utilisant Java, One peut également fusionner de nombreux autres formats de fichiers, y compris.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Valeurs séparées par des virgules" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Langage Signalétique Hyper Text" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Format d\'archivage des pages Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Fichier de feuille de calcul OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Valeurs séparées par des tabulations" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Document texte" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Format binaire Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Fichier de classeur Excel binaire" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Fichier de feuille de calcul" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="Fichier Excel OOXML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Modèle Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Modèle Excel compatible avec les macros" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
