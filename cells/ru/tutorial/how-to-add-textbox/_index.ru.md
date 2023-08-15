---
title: Как добавить TextBox через Aspose.Cells
weight: 7700
limit:
description: Узнайте, как добавить текстовое поле.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /ru/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Узнайте, как добавить TextBox с помощью Aspose.Cells" >}}

<p>
В этом уроке мы добавим TextBox в файл Excel.
</p>

<p>
 Начнем с создания новой книги с помощью<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells библиотека</a> и добавьте текстовое поле.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Пожалуйста, проверьте следующий код, чтобы узнать, как добавить TextBox.
//ExStepSummary:0: Следующий код показывает, как добавить TextBox и установить текст.
//ExStepImage:0:step-1.png
//ExStepSummary:1: Следующий код показывает, как изменить цвет текста.
//ExStepImage:1:step-2.png
//ExStepSummary:2: Следующий код показывает, как изменить угол поворота TextBox.
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

// Добавляем TextBox и устанавливаем текст
TextBox textBox = shape.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET — это библиотека классов программирования, которая позволяет разработчикам программного обеспечения манипулировать и обрабатывать файлы электронных таблиц в своих собственных приложениях.";

//ExStep:1-
//Изменить цвет текста
textBox.Font.Color = Цвет.Синий;

//ExStep:2-
//Изменяем угол поворота TextBox
textBox.RotationAngle = 90;

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