---
title: Разделить электронную таблицу Excel на рабочие листы в Java
url: /ru/java/splitter/
description: Исходные коды Java, объясняющие, как разделить файлы Microsoft Excel на несколько документов с помощью библиотеки Java Excel
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Разделение файлов Microsoft<sup>&reg;</sup> Excel через Java" h2="Разделить электронную таблицу Excel на рабочие листы в приложениях на основе Java" >}}
{{% blocks/products/pf/feature-page-summary %}}
Существует множество сценариев, когда необходимо разделить файлы Excel, такие как электронная таблица, содержащая данные учащихся, с выделением отдельного листа для каждого ученика. И есть необходимость разделить каждый лист студента на отдельный файл. Чтобы автоматизировать его с помощью приложения Java, [Java Excel API](/cells/java/) есть ли разделять документ Excel по листам. Поддерживаемые форматы включают XLS, XLSX, XLSB, XLSM, ODS. 
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Разделить документ Excel на несколько файлов" %}}

Самый простой способ разделить файл Excel на листы — получить доступ ко всем листам, перебрать каждый лист и сохранить один за другим в нужном формате. Для загрузки рабочего листа API предоставляет [Рабочая тетрадь](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) класс. [получить рабочие листы(). getCount()](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) метод получает общее количество листов. Переберите каждый лист и используйте [getWorksheets (). Получить (индекс листа)](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) для доступа к конкретному листу. Переместите выбранные данные листа во вновь созданный объект класса Workbook с помощью [Метод копирования](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Наконец, сохраните его в нужном формате.

{{% blocks/products/pf/feature-page-code h3="Java Код для разделения файлов Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Разделить рабочий лист Excel на панели" %}}

API также обеспечивает функцию разделения рабочего листа Excel на разные области. Процесс заключается в загрузке файла с использованием класса Workbook. Выберите первый рабочий лист или любой требуемый лист, указав его индекс. Вызовите setActiveCell с соответствующим индексом ячейки в качестве параметра. И, наконец, разделите окно рабочего листа на разные панели, вызвав метод split().

{{% blocks/products/pf/feature-page-code h3="Java Код для разделения листа Excel на представление панели" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}