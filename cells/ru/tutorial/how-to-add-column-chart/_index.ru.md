---
title: Как добавить столбчатую диаграмму через Aspose.Cells
weight: 7700
limit:
description: Узнайте, как добавить столбчатую диаграмму.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /ru/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Узнайте, как добавить столбчатую диаграмму с помощью Aspose.Cells." >}}

<p>
В этом уроке мы добавим столбчатую диаграмму в файл Excel.
</p>

<p>
 Начнем с создания новой книги с помощью<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells библиотека</a> и добавьте столбчатую диаграмму.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: проверьте следующий код, чтобы узнать, как добавить столбчатую диаграмму.
//ExStepSummary:0: Следующий код показывает, как добавить столбчатую диаграмму.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Следующий код показывает, как переместить легенду влево и установить цвет шрифта легенды.
//ExStepImage:1:step-2.png
//ExStepSummary:2: В следующем коде показано, как установить заголовок диаграммы и изменить цвет шрифта на синий.
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

//Добавить столбчатую диаграмму
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Диаграмма Диаграмма = диаграммы[индекс];

//ExStep:1-
//Перемещаем легенду влево и устанавливаем цвет шрифта легенды
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Left;

//ExStep:2-
//Задаем заголовок графика и меняем цвет шрифта на синий
chart.Title.Text = "Столбчатая диаграмма цен на фрукты";
chart.Title.Font.Color = Color.Blue;

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