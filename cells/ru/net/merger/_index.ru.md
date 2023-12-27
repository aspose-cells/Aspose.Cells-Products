---
title: Объединение файлов Excel API .NET C#
description: Объедините файлы электронных таблиц Excel и OpenOffice, используя всего несколько строк кода C#.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Объединение файлов Excel via .NET" h2="Объедините 2 или более файлов Excel в одну таблицу, используя код C#." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Библиотека Excel](/cells/ru/net/) предоставляет несколько способов объединения книг с различными типами содержимого, такими как формулы, данные, изображения, диаграммы и т. д., в один файл электронной таблицы. Поддерживаемые форматы файлов: XLS, XLSX, XLSB, XLT, XLTX, XLTM, ODS, CSV, TSV и другие.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Объединение файлов Excel с изображениями и диаграммами" %}}
 Самый простой способ объединить два файла Excel с изображениями и диаграммами — вызвать метод[Рабочая тетрадь.Объединить](https://reference.aspose.com/cells/net/aspose.cells/workbook/methods/combine) метод. Это позволяет объединять файлы Excel одного типа в одну электронную таблицу.
{{% blocks/products/pf/feature-page-code h3="C# Код для объединения файлов Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "combine-two-workbooks.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Объединить несколько файлов Excel" %}}
[CellsHelper.MergeFiles](https://reference.aspose.com/cells/net/aspose.cells/cellshelper/methods/mergefiles) Метод поддерживает объединение данных, стиля и формул файла Excel в новую электронную таблицу того же формата. Это эффективный способ объединить несколько файлов при использовании кэширования.
{{% blocks/products/pf/feature-page-code h3="C# Код для объединения нескольких файлов Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "merge-several-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Объединение файлов Excel путем копирования листов" %}}
[Рабочий лист.Копировать](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy/index)может использоваться для копирования данных и форматирования из исходного листа на другой лист внутри книг или между ними. Метод принимает объект исходного листа в качестве параметра.
{{% blocks/products/pf/feature-page-code h3="C# Код для копирования листов в файлы Excel" %}}

{{< gist "aspose-com-gists" "d7c757e7471bd38006ac0d35d221b2e2" "copy-worksheets-across-excel-files.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы слияния" subTitle="Используя C#, можно также объединить файлы многих других форматов, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/csv/" name="CSV" description="Значения, разделенные запятыми" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/html/" name="HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/mhtml/" name="MHTML" description="Формат архива веб-страниц" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/ods/" name="ODS" description="Файл электронной таблицы OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/tsv/" name="TSV" description="Значения, разделенные табуляцией" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/txt/" name="TXT" description="Текстовый документ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xls/" name="XLS" description="Двоичный формат Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsb/" name="XLSB" description="Двоичный файл книги Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsm/" name="XLSM" description="Файл электронной таблицы" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlsx/" name="XLSX" description="OOXML-файл Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xlt/" name="XLT" description="Microsoft Шаблон Excel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/cells/net/merger/xltm/" name="XLTM" description="Шаблон Excel с поддержкой макросов" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}
