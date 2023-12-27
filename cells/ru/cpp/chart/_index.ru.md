---
title: Создавайте диаграммы Excel и конвертируйте их в изображения по номеру C++.
description: C++ исходный код для рисования и преобразования диаграммы или диаграммы в Microsoft Excel с использованием библиотеки C++
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создайте Microsoft<sup>&reg;</sup> диаграммы Excel и преобразуйте их в изображения с помощью C++." h2="Преобразуйте диаграммы документов Excel в изображения, а также создавайте диаграммы, включая круговые, пирамидальные, линейные и пузырьковые диаграммы, в приложениях на базе C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Используя диаграммы Excel, можно получить более широкую картину и легко проанализировать данные для принятия правильных решений.[C++ Библиотека Excel](/cells/ru/cpp/) поддерживает создание различных диаграмм, перечисленных[перечисление Aspose::Cells::Charts::ChartType
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/) включая площади, гистограммы, круговые, пирамидальные, линейные и пузырьковые диаграммы. Кроме того, для преобразования диаграмм в изображения API предоставляет[Изображать](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/) метод в необходимый формат изображения.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Создание диаграмм Excel" %}}

 Процесс создания диаграммы Excel заключается в создании экземпляра[Класс рабочей тетради](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) и выберите нужный[Рабочий лист](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/) . Добавьте диаграмму, используя[Добавить метод](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/)с соответствующими параметрами, включая тип диаграммы. Доступ к диаграмме через индекс и[Добавлять](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/) источник данных для диаграммы.

{{% blocks/products/pf/feature-page-code h3="C++ Код для создания диаграмм Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Преобразование диаграмм в изображения" %}}


Для процесса преобразования диаграмм сначала создайте диаграмму соответствующего типа, используя приведенный выше код, или получите к ней доступ из соответствующего листа. Определите путь сохранения выходного изображения и используйте метод ToImage для преобразования.

 
{{% blocks/products/pf/feature-page-code h3="C++ Код для преобразования диаграмм Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
