---
title: Объединить разные файлы Excel в один в Java

description: Объедините файлы Excel с помощью Java в несколько листов или один лист. Объединяйте, комбинируйте или объединяйте документы Excel в PDF, изображения и HTML.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Объединение файлов Microsoft<sup>&reg;</sup> Excel через Java" h2="Объединение двух или более файлов Excel в одну таблицу с помощью кода Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Java Библиотека Excel](/cells/java/) предоставляет несколько способов объединения рабочих книг с различными типами содержимого, такими как формулы, изображения, данные, диаграммы и т. д., в единый документ электронной таблицы. Поддерживаемые форматы файлов включают XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV и другие.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Объединение файлов Excel с изображениями и диаграммами" %}}
Самый простой способ объединить два файла Excel с изображениями и диаграммами — вызвать метод [Workbook.combine](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#combine(com.aspose.cells.Workbook)) метод. Это позволяет объединять файлы Excel аналогичного типа в одну электронную таблицу.
{{% blocks/products/pf/feature-page-code h3="Java Код для объединения файлов Excel" %}}

```cs
// загрузить первый файл Excel
var book1 = new Workbook("with-charts.xlsx");
// загрузить второй файл Excel в отдельный экземпляр
var book2 = new Workbook("with-images.xlsx");

// объединить две книги
book1.combine(book2);
// сохранить целевую книгу 
book1.save("combined.xlsx");

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Объединить несколько файлов Excel" %}}
[CellsHelper.mergeFiles](https://reference.aspose.com/cells/java/com.aspose.cells/cellshelper#mergeFiles) метод поддерживает объединение данных, стилей и формул файла Excel в новую электронную таблицу того же формата. Это эффективный способ объединить несколько файлов при использовании кэширования. 
{{% blocks/products/pf/feature-page-code h3="Java Код для объединения нескольких файлов Excel" %}}

```cs
// создать массив (длина = 2)
String[] files = new String[2];
// указать пути к файлам для объединения
files[0] = "Book1.xls";
files[1] = "Book2.xls";
// объединить файлы, чтобы сохранить результат
CellsHelper.mergeFiles(files, "cache", "merged.xls");


```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Объединение файлов Excel путем копирования рабочих листов" %}}
[Рабочий лист.копировать](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet#copy(com.aspose.cells.Worksheet)можно использовать для копирования данных и форматирования с исходного листа на другой лист внутри или между книгами. Метод принимает исходный объект рабочего листа в качестве параметра.
{{% blocks/products/pf/feature-page-code h3="Java Код для копирования листов между книгами" %}}

```cs
// Создайте рабочую книгу.
Workbook excelWorkbook0 = new Workbook(dataDir + "book1.xls");

// Создайте еще одну рабочую книгу.
Workbook excelWorkbook1 = new Workbook();

// Скопируйте первый лист первой книги во вторую книгу.
excelWorkbook1.getWorksheets().get(0).copy(excelWorkbook0.getWorksheets().get(0));

// Сохраните файл.
excelWorkbook1.save(dataDir + "out.xls", FileFormatType.EXCEL_97_TO_2003);

```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
