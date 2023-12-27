---
title: Разделить лист Excel по номеру C#
description: C# исходные коды, объясняющие, как разделить Microsoft файлы Excel на несколько файлов в приложениях Visual C#.NET
keywords: [C# Aspose.Cells., C# split excel files., C# how to split excel files into multiple files., C# excel splitter., C# split Cell., Cell splitter using C#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Разделение файла Excel via .NET" h2="Разделите один документ Excel на разные файлы, используя код C# в приложениях на основе .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Библиотека Excel](/cells/ru/net/) способен разделить документ Excel на несколько электронных таблиц в приложениях на базе .NET. Поддерживаемые форматы файлов: XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Разделить документ Excel на несколько файлов" %}}
Самый простой способ разделить файлы Excel по листам — получить доступ ко всем листам через[Рабочие листы](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets) , Перебирая каждый лист и вызывая[Копировать](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) метод. Наконец, сохраните его по указанному пути.

 + Загрузите файл Excel с полным путем, используя[Класс рабочей тетради](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Перебирать каждый лист
+ Создайте новый объект класса Workbook.
 + Скопируйте лист через[Метод копирования](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Вызовите метод Save() и передайте имя файла (полный путь) с соответствующим форматом SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Код для разделения файлов Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Разделить лист Excel на панели" %}}

 Для разделения окна рабочего листа на панели API предоставляет[Метод разделения](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) класса рабочего листа, который обеспечивает разделенное представление рабочего листа. Чтобы удалить разделенное представление, API предоставляет[Метод RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit) . Наконец сохраните его по указанному пути.

{{% blocks/products/pf/feature-page-code h3="C# Код для разделения окна листа Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Код для удаления разделенного панорамного вида" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
