---
title: Как добавить круговую диаграмму через Aspose.Cells
weight: 7700
limit:
description: Узнайте, как добавить круговую диаграмму.
keywords: [Add pie chart., how to add pie chart in Aspose.Cells., how to add pie chart using Aspose.Cells]
url: /ru/tutorial/add-pie-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Узнайте, как добавить круговую диаграмму с помощью Aspose.Cells" >}}

<p>
В этом уроке мы добавим круговую диаграмму в файл Excel.
</p>

<p>
 Начнем с создания новой книги с помощью<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells библиотека</a> и добавьте круговую диаграмму.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: проверьте следующий код, чтобы узнать, как добавить круговую диаграмму.
//ExStepSummary:0: В следующем коде показано, как добавить круговую диаграмму, установить диапазон данных ряда и установить диапазон данных категории.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Следующий код показывает, как отключить легенду.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Следующий код показывает, как получить доступ к меткам данных, включить имена категорий, включить процентный формат и установить позицию.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
используя Aspose.Cells;
с использованием Aspose.Cells.Чертеж;

Рабочая книга рабочая книга = новая рабочая книга();
Рабочий лист = рабочая книга. Рабочие листы [0];
лист.Имя = "Лист Диаграммы";
Cells кл = лист.Cells;
ячейки["A1"].Value = "Фрукты";
ячейки["A2"].Value = "яблоко";
ячейки["A3"].Value = "оранжевый";
ячейки["A4"].Value = "черника";
ячейки["A5"].Value = "киви";

ячейки["B1"].Value = "Цена";
ячейки["B2"].Value = 10;
ячейки["B3"].Значение = 5;
ячейки["B4"].Value = 20;
ячейки["B5"].Value = 8;

лист.PageSetup.PrintGridlines = true;
лист.PageSetup.PrintArea = "A1:F20";

Диаграммы ChartCollection = sheet.Charts;

//Добавить круговую диаграмму, установить диапазон данных серии и установить диапазон данных категории
int index = лист.Charts.Add(ChartType.Pie, 6, 0, 19, 5);
Диаграмма Диаграмма = лист.Диаграммы[индекс];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Отключить легенду
chart.ShowLegend = ложь;

//ExStep:2-
// Доступ к меткам данных, включение имен категорий, включение процентного формата и установка позиции
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.ShowPercentage = истина;
dataLabels.Position = LabelPositionType.OutsideEnd;

//ExStep:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Установка Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Редактор</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}