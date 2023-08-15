---
title: Как добавить линейный график через Aspose.Cells
weight: 7700
limit:
description: Узнайте, как добавить линейную диаграмму.
keywords: [Add line chart., how to add line chart in Aspose.Cells., how to add line chart using Aspose.Cells]
url: /ru/tutorial/add-line-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Узнайте, как добавить линейную диаграмму с помощью Aspose.Cells." >}}

<p>
В этом уроке мы добавим линейную диаграмму в файл Excel.
</p>

<p>
 Начнем с создания новой книги с помощью<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells библиотека</a> и добавьте линейную диаграмму.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: проверьте следующий код, чтобы узнать, как добавить линейный график.
//ExStepSummary:0: В следующем коде показано, как добавить линейную диаграмму, установить диапазон данных ряда и установить диапазон данных категории.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Следующий код показывает, как переместить легенду вниз и установить цвет шрифта легенды.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Следующий код показывает, как получить доступ к меткам данных, включить имена категорий и установить положение.
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

//Добавить линейный график, установить диапазон данных серии и установить диапазон данных категории
int index = sheet.Charts.Add(ChartType.Line, 6, 0, 19, 5);
Диаграмма Диаграмма = лист.Диаграммы[индекс];
chart.NSeries.Add("B2:B5", true);
chart.NSeries.CategoryData = "A2:A5";

//ExStep:1-
//Перемещаем легенду вниз и устанавливаем цвет шрифта легенды
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Bottom;

//ExStep:2-
// Доступ к меткам данных, включение имен категорий и установка позиции
DataLabels dataLabels = chart.NSeries[0].DataLabels;
dataLabels.ShowCategoryName = true;
dataLabels.Position = LabelPositionType.Center;

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