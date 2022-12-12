---
title: Объединение файлов Excel API .NET C#

description: Объединяйте файлы электронных таблиц Excel и OpenOffice всего несколькими строками кода C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Объединение файлов Microsoft<sup>&reg;</sup> Excel через .NET" h2="Объедините 2 или более файлов Excel в одну таблицу, используя код C#" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Библиотека Excel](/cells/net/) предоставляет несколько способов объединения рабочих книг с различными типами содержимого, такими как формулы, данные, изображения, диаграммы и т. д., в один файл электронной таблицы. Поддерживаемые форматы файлов включают XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV и другие.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Объединение файлов Excel с изображениями и диаграммами" %}}
Самый простой способ объединить 2 файла Excel с изображениями и диаграммами — вызвать метод [Рабочая книга.Комбинировать](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) метод. Это позволяет объединять файлы Excel аналогичного типа в одну электронную таблицу.
{{% blocks/products/pf/feature-page-code h3="C# Код для объединения файлов Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Объединить несколько файлов Excel" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) метод поддерживает объединение данных, стилей и формул файла Excel в новую электронную таблицу того же формата. Это эффективный способ объединить несколько файлов при использовании кэширования. 
{{% blocks/products/pf/feature-page-code h3="C# Код для объединения нескольких файлов Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Объединение файлов Excel путем копирования рабочих листов" %}}
[Рабочий лист.Копировать](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index) может использоваться для копирования данных и форматирования с исходного рабочего листа на другой рабочий лист внутри или между рабочими книгами. Метод принимает исходный объект рабочего листа в качестве параметра.
{{% blocks/products/pf/feature-page-code h3="C# Код для копирования листов между файлами Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}
