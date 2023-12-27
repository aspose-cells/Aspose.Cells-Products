---
title: Разделить таблицу Excel на рабочие листы в Java
description: Java исходные коды, объясняющие, как разделить Microsoft файлы Excel на несколько документов с помощью Java библиотеки Excel.
keywords: [Java Aspose.Cells., Java split excel files., Java how to split excel files into multiple files., Java excel splitter., Java split Cell., Cell splitter using Java]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Разделение файла Excel via Java" h2="Разделите таблицу Excel на листы в приложениях на основе Java." >}}
{{% blocks/products/pf/feature-page-summary %}}
Существует множество сценариев. Когда необходимо разделить файлы Excel, например электронную таблицу, содержащую данные учащихся, с выделением одного листа для каждого учащегося. И есть необходимость разделить каждый лист ученика на отдельный файл. Чтобы автоматизировать это, используйте приложение via Java,[Java Эксель API](/cells/ru/java/) Есть ли возможность разделить документ Excel по листам. Поддерживаемые форматы: XLS, XLSX, XLSB, XLSM, ODS.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Разделить документ Excel на несколько файлов" %}}

 Самый простой способ разделить файл Excel на листы: получить доступ ко всем листам, пройтись по каждому листу и сохранить один за другим в нужном формате. Для загрузки рабочего листа API предоставляет[Рабочая тетрадь](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) сорт.[getWorksheets().getCount()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#Count) метод получает общее количество листов. Перебирайте каждый лист и используйте[getWorksheets().get(листиндекс)](https://reference.aspose.com/cells/java/com.aspose.cells/worksheetcollection#get) для доступа к определенному листу. Переместите выбранные данные листа во вновь созданный объект класса Workbook, используя[Метод копирования](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#copy(com.aspose.cells.Workbook)). Наконец сохраните его в необходимый формат.

{{% blocks/products/pf/feature-page-code h3="Java Код для разделения файлов Excel" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-xls-spreadsheet.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Splitter" >}}

{{% blocks/products/pf/feature-page-section h2="Разделить лист Excel на панели" %}}

API также обеспечивает функцию разделения листа Excel на разные панели. Процесс таков: загрузить файл с помощью класса Workbook. Выберите первый рабочий лист или любой необходимый лист, указав его индекс. Вызовите setActiveCell с соответствующим индексом ячейки в качестве параметра. И, наконец, разделите окно рабочего листа на разные панели, вызвав метод Split().

{{% blocks/products/pf/feature-page-code h3="Java Код для разделения листа Excel на панель" %}}

{{< gist "aspose-com-gists" "ad89e1c7bdb5a4c72f65aae895d95c40" "split-excel-spreadsheet-into-panes.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
