---
title: Сгенерируйте файлы Excel через C#
description: Создание электронных таблиц Excel Microsoft из листа шаблона с использованием кода C#
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Создание файлов на основе шаблона Excel via .NET" h2="Создание отчетов в виде файлов Excel на основе предопределенного шаблона в приложениях на основе .NET" >}}
{{% blocks/products/pf/feature-page-summary %}}
[.NET Библиотека Excel](/cells/ru/net/) поддерживает создание файлов Excel на основе шаблонов для массового создания отчетов. Шаблоны — это предварительно разработанные форматы, используемые для создания отчетов по одному шаблону. Код .NET создает новый файл Excel, такой же, как документ шаблона, заполненный данными. Поддерживаемые форматы файлов включают XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Создание отчетов на основе предварительно разработанного шаблона Excel" %}}

Автоматизировать процесс создания одинаковых файлов шаблонов легко с помощью сборки .NET API. Существуют разные способы[импортировать данные](https://docs.aspose.com/cells/net/import-data-into-worksheet/#importing-data-from-json) и создавать файлы Excel. API предоставляет[Класс WorkbookDesigner](https://reference.aspose.com/cells/net/aspose.cells/workbookdesigner) для представления рабочего листа дизайнера. Создайте его объект и используйте его, чтобы открыть файл шаблона. Установите источник данных, который может быть DataTable, Array, файл Json и т. д. Обработайте его, чтобы импортировать данные и сохранить файл с данными в требуемом формате. Программисты могут собирать данные в отчеты в других форматах файлов по ссылкам, указанным ниже.



{{% blocks/products/pf/feature-page-code h3="C# Код для создания отчетов Excel" %}}

{{< gist "aspose-com-gists" "5c193070f1b6acdc3eed001f52eadbc2" "generate-excel-reports.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Generate" afterslug="Reports" >}}
