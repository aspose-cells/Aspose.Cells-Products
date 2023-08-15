---
title: Как добавить фигуры через Aspose.Cells
weight: 7700
limit:
description: Узнайте, как добавлять фигуры.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /ru/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Узнайте, как добавлять фигуры с помощью Aspose.Cells." >}}

<p>
В этом уроке мы добавим фигуры в файл Excel.
</p>

<p>
 Начнем с создания новой книги с помощью<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells библиотека</a> и добавить формы.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: проверьте следующий код, чтобы узнать, как добавлять фигуры.
//ExStepSummary:0: Следующий код показывает, как добавить форму прямоугольника.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Следующий код показывает, как добавить форму линии.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Следующий код показывает, как добавить овальную форму.
//ExStepImage:2:step-3.png
//ExStart
//ExStep:0-
используя Aspose.Cells;
с использованием Aspose.Cells.Чертеж;





Рабочая книга рабочая книга = новая рабочая книга();
Рабочий лист = рабочая книга. Рабочие листы [0];
лист.PageSetup.PrintGridlines = true;
лист.PageSetup.PrintArea = "A1:F20";

Формы ShapeCollection = sheet.Shapes;

//Добавляем прямоугольную форму
shape.AddRectangle(1, 0, 1, 0, 100, 150);

//ExStep:1-
//Добавляем форму линии
shape.AddLine(8, 0, 1, 0, 100, 150);

//ExStep:2-
//Добавляем овал
shape.AddOval(13, 0, 1, 0, 100, 150);

//ExStep:0-
рабочая тетрадь
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