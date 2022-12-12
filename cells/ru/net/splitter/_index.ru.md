---
title: Разделить лист Excel по частям C#

description: Исходные коды C#, объясняющие, как разделить файлы Microsoft Excel на несколько файлов в приложениях Visual C#.NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Разделение файлов Microsoft<sup>&reg;</sup> Excel через .NET" h2="Разделить один документ Excel на разные файлы с помощью кода C# в приложениях на основе .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Библиотека Excel](/cells/net/) может разбить документ Excel на несколько электронных таблиц в приложениях на основе .NET. Поддерживаемые форматы файлов включают XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Разделить документ Excel на несколько файлов" %}}
Самый простой способ разделить файлы Excel на листы — это получить доступ ко всем листам через [Рабочие листы](https://reference.aspose.com/cells/net/aspose.cells/workbook/properties/worksheets), Итерация по каждому листу и вызов [Копировать](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy) метод. Наконец, сохраните его по указанному пути. 

+ Загрузите файл Excel с полным путем, используя [Класс рабочей тетради](https://reference.aspose.com/cells/net/aspose.cells/workbook).
+ Итерация по каждому листу
+ Создать новый объект класса Workbook
+ Скопируйте лист через [Метод копирования](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/copy)
+ Вызвать метод Save() и передать имя файла (полный путь) с соответствующим SaveFormat.

{{% blocks/products/pf/feature-page-code h3="C# Код для разделения файлов Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Разделить рабочий лист Excel на панели" %}}

Для разделения окна рабочего листа на области API обеспечивает [Метод разделения](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/split) класса рабочего листа, который обеспечивает разделенный вид рабочего листа. Чтобы удалить разделенный вид, API предоставляет [Метод RemoveSplit](https://reference.aspose.com/cells/net/aspose.cells/worksheet/methods/removesplit). Наконец, сохраните его по указанному пути. 

{{% blocks/products/pf/feature-page-code h3="C# Код для разделения окна рабочего листа Excel" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "split-xlsx-spreadsheet-into-pane.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code h3="C# Код для удаления разделенного панорамного вида" %}}

{{< gist "aspose-com-gists" "bff05bb3d479c29ac0aa116d1a641264" "remove-splitted-spreadsheet-pane-view.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
