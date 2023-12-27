---
title: Как добавить гистограмму через Aspose.Cells
weight: 7700
limit:
description: Узнайте, как добавить столбчатую диаграмму.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /ru/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Узнайте, как добавить гистограмму с помощью Aspose.Cells." >}}

<p>
В этом уроке мы добавим столбчатую диаграмму в файл Excel.
</p>

<p>
 Начнем с создания новой книги с помощью<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells библиотека</a> и добавьте столбчатую диаграмму.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: проверьте следующий код, чтобы узнать, как добавить гистограмму.
//ExStepSummary:0: следующий код показывает, как добавить гистограмму.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Следующий код показывает, как переместить легенду влево и установить цвет шрифта легенды.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Следующий код показывает, как задать заголовок диаграммы и изменить цвет шрифта на синий.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
используя Aspose.Cells;
используя Aspose.Cells.Рисование;

Рабочая книга рабочая книга = новая рабочая книга();
Лист листа = workbook.Worksheets[0];
лист.Имя = "Таблица диаграммы";
Cells ячейки = лист.Cells;
ячейки["A1"].Value = "Фрукты";
ячейки["A2"].Value = "яблоко";
ячейки["A3"].Value = "оранжевый";
ячейки["A4"].Value = "черника";
ячейки["A5"].Value = "киви";

ячейки["B1"].Значение = "Цена";
ячейки["B2"].Значение = 10;
ячейки["B3"].Значение = 5;
ячейки["B4"].Значение = 20;
ячейки["B5"].Значение = 8;

лист.PageSetup.PrintGridlines = true;
лист.PageSetup.PrintArea = "A1:F20";

ChartCollection диаграммы = лист.Диаграммы;

//Добавляем столбчатую диаграмму
int index =charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Диаграмма диаграмма = диаграммы[индекс];

//ExStep:1-
//Перемещаем легенду влево и устанавливаем цвет шрифта легенды
диаграмма.Легенда.Шрифт.Цвет = Цвет.Синий;
диаграмма.Легенда.Позиция = ТипЛегендыПозиции.Влево;

//ExStep:2-
//Устанавливаем заголовок диаграммы и меняем цвет шрифта на синий
chart.Title.Text = "Столбчатая диаграмма цен на фрукты";
диаграмма.Название.Шрифт.Цвет = Цвет.Синий;

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