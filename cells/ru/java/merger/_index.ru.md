---
title: Объедините разные файлы Excel в один в Java.
description: Объедините файлы Excel с помощью Java в несколько листов или один лист. Объединяйте, объединяйте или объединяйте документы Excel с номерами PDF, изображениями и HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Объединение файлов Excel via Java" h2="Объедините два или более файла Excel в одну таблицу, используя код Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Библиотека Excel](/cells/ru/java/)предоставляет несколько способов объединения книг с различными типами контента, такими как формулы, изображения, данные, диаграммы и т. д., в один документ электронной таблицы. Поддерживаемые форматы файлов: XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV и другие.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Объединение файлов Excel с изображениями и диаграммами" %}}
 Самый простой способ объединить два файла Excel с изображениями и диаграммами — вызвать метод[Рабочая книга.объединить](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) метод. Это позволяет объединять файлы Excel одного типа в одну электронную таблицу.
{{% blocks/products/pf/feature-page-code h3="Java Код для объединения файлов Excel" %}}

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

{{% blocks/products/pf/feature-page-section h2="Объединить несколько файлов Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) Метод поддерживает объединение данных, стиля и формул файла Excel в новую электронную таблицу того же формата. Это эффективный способ объединить несколько файлов при использовании кэширования.
{{% blocks/products/pf/feature-page-code h3="Java Код для объединения нескольких файлов Excel" %}}

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

{{% blocks/products/pf/feature-page-section h2="Объединение файлов Excel путем копирования листов" %}}
[Рабочий лист.копия](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)можно использовать для копирования данных и форматирования из исходного листа на другой лист внутри книг или между ними. Метод принимает объект исходного листа в качестве параметра.
{{% blocks/products/pf/feature-page-code h3="Java Код для копирования листов между книгами" %}}

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

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы слияния" subTitle="Используя Java, можно также объединить файлы многих других форматов, включая.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/csv/" name="CSV" description="Значения, разделенные запятыми" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/html/" name="HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/mhtml/" name="MHTML" description="Формат архива веб-страниц" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/ods/" name="ODS" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/tsv/" name="TSV" description="Значения, разделенные табуляцией" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/txt/" name="TXT" description="Текстовый документ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsb/" name="XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsm/" name="XLSM" description="Файл электронной таблицы" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlsx/" name="XLSX" description="OOXML-файл Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xlt/" name="XLT" description="Microsoft Шаблон Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/java/merger/xltm/" name="XLTM" description="Шаблон Excel с поддержкой макросов" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
