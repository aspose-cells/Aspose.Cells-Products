---
title: Создание диаграмм Excel и преобразование в изображения via .NET
description:  C# исходный код для рисования и преобразования диаграммы или диаграммы в Microsoft Excel с использованием библиотеки .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Создание и преобразование диаграмм файлов Excel via .NET" h2="Создавайте диаграммы документов Excel и преобразовывайте их в изображения с помощью серверных API-интерфейсов в приложениях на основе .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Рисование диаграмм — это искусство графического отображения данных для облегчения анализа.[.NET Библиотека Excel](/cells/ru/net/) поддерживает рисование диаграмм в файлах Excel. API поддерживает создание различных диаграмм, перечисленных в[Перечисление ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) включая круговые, пирамидальные, линейные и пузырьковые диаграммы. Кроме того, он также преобразует диаграммы в изображения. API предоставляет[Класс диаграмм](https://reference.aspose.com/cells/net/aspose.cells.charts) для строительных блоков диаграммы.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Создание диаграмм в файле Excel" %}}

 Создание диаграмм с помощью Excel API очень просто. Процесс, Создай[Класс рабочей тетради](https://reference.aspose.com/cells/net/aspose.cells/workbook) объект и выберите первый рабочий лист или соответствующий лист, указав его индекс. Вставьте необходимые данные ячеек, используя[Метод PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Добавьте диаграмму на лист с помощью коллекции Charts.[Добавить метод](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Укажите[Тип диаграммы](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)из перечисления ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Код для создания диаграмм Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Преобразование диаграмм Excel в изображения" %}}

 Процесс преобразования диаграмм в изображения. Используйте класс Workbook для загрузки файла Excel, выберите соответствующий рабочий набор, содержащий диаграммы, и вызовите метод[Метод ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) для преобразования.

{{% blocks/products/pf/feature-page-code h3="C# Код для преобразования диаграммы Excel в изображение" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
