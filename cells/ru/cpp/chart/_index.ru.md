---
title: Создание диаграмм Excel и преобразование в изображения с помощью C++
url: /ru/cpp/chart/
description: Исходный код C++ для рисования и преобразования диаграммы или диаграммы в Microsoft Excel с использованием библиотеки C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Создавайте диаграммы Microsoft<sup>&reg;</sup> Excel и конвертируйте их в изображения с помощью C++" h2="Преобразование диаграмм документов Excel в изображения, а также создание диаграмм, включая круговые, пирамидальные, линейные и пузырьковые диаграммы, в приложениях на основе C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

Используя диаграммы Excel, можно получить более широкую картину и легко анализировать данные для принятия правильных решений. [C++ Библиотека Excel](/cells/cpp/) поддерживает создание различных диаграмм, перечисленных [перечисление Aspose::Cells::Charts::ChartType
](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) включая области, столбчатые, круговые, пирамидальные, линейные и пузырьковые диаграммы. Кроме того, для преобразования диаграмм в изображения API предоставляет [Метод ToImage](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) в требуемый формат изображения.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Создание диаграмм Excel" %}}

Процесс создания диаграммы Excel заключается в создании экземпляра [Класс iWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) и выберите нужный [Рабочий лист](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Добавьте диаграмму, используя [Добавить метод](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) с соответствующими параметрами, включая тип диаграммы. Доступ к диаграмме через индекс и [Добавлять](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) источник данных для диаграммы.

{{% blocks/products/pf/feature-page-code h3="C++ Код для создания диаграмм Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Преобразование диаграмм в изображения" %}}


Для процесса преобразования диаграмм сначала создайте диаграмму соответствующего типа, используя приведенный выше код, или получите к ней доступ с соответствующего листа. Определите выходной путь сохранения изображения и используйте метод ToImage для преобразования.

 
{{% blocks/products/pf/feature-page-code h3="C++ Код для преобразования диаграмм Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}