---
title: Создание диаграмм Excel и преобразование в изображения via Java
description:  Java исходный код для рисования и преобразования диаграммы или диаграммы в Microsoft Excel с использованием библиотеки Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Преобразование файлов Excel и создание диаграмм via Java" h2="Преобразование диаграмм документов Excel в изображения, а также создание различных диаграмм с использованием серверных API в приложениях на основе Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

 Анализ данных с помощью диаграмм показывает более широкую картину, и благодаря более четкому пониманию становится легче принимать более обоснованные решения.[Java Библиотека Excel](/cells/ru/java/) поддерживает рисование различных диаграмм, перечисленных[Тип диаграммы](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) включая круговые, пирамидальные, линейные и пузырьковые диаграммы. Кроме того, он также преобразует диаграммы в изображения. API предоставляет[Класс диаграмм](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)для представления одной диаграммы Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Преобразование диаграмм Excel в изображения" %}}

 Процесс преобразования диаграмм в изображения, включая JPG, PNG, TIFF, BMP и т. д.,[Рабочая тетрадь](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) класс для загрузки файла Excel, выберите соответствующий[рабочий стол](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) содержащие диаграммы или перебирать каждую диаграмму на каждом листе. Определять[Имажеорпринтоптионс](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) и визуализировать выходное изображение диаграммы, используя[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Код для преобразования диаграммы Excel в изображение" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Создание диаграмм в файле Excel" %}}

 Создание диаграмм с помощью Excel API очень просто, так как API предоставляет набор различных классов, таких как Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection и т. д. для различных типов диаграмм. Процесс заключается в том, чтобы создать объект класса Workbook и выбрать первый рабочий лист или соответствующий лист, указав его индекс. Для источника данных диаграммы вставьте значения в ячейки рабочего листа, используя[установить значение](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)метод. Используйте коллекцию ChartCollection[добавить метод](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) чтобы добавить диаграмму, определите тип диаграммы с помощью перечисления ChartType. Получите доступ к новому объекту Chart из коллекции ChartCollection, передав его индекс. Использовать[СерияКоллекция](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) объект диаграммы, чтобы указать источник данных диаграммы.

{{% blocks/products/pf/feature-page-code h3="Java Код для создания диаграмм Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
