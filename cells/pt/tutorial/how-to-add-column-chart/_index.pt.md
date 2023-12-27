---
title: Como adicionar gráfico de colunas via Aspose.Cells
weight: 7700
limit:
description: Aprenda como adicionar gráfico de colunas.
keywords: [Add column chart., how to add column chart in Aspose.Cells., how to add column chart using Aspose.Cells]
url: /pt/tutorial/add-column-chart-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aprenda como adicionar gráfico de colunas com Aspose.Cells" >}}

<p>
Neste tutorial, adicionaremos gráfico de colunas em um arquivo Excel.
</p>

<p>
 Começaremos criando uma nova pasta de trabalho usando o<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteca</a> e adicione gráfico de colunas.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: verifique o código a seguir para descobrir como adicionar gráfico de colunas.
//ExStepSummary:0: O código a seguir mostra como adicionar gráfico de colunas.
//ExStepImage:0:step-1.png
//ExStepSummary:1: O código a seguir mostra como mover a legenda para a esquerda e definir a cor da fonte da legenda.
//ExStepImage:1:step-2.png
//ExStepSummary:2: O código a seguir mostra como definir o título de um gráfico e alterar a cor da fonte para azul.
//ExStepImage:2:step-3.png
//ExStart
//ExEtapa:0-
usando Aspose.Cells;
usando Aspose.Cells.Desenho;

Pasta de trabalho pasta de trabalho = nova pasta de trabalho();
Planilha = pasta de trabalho.Worksheets[0];
planilha.Name = "Planilha";
Cells células = folha.Cells;
células["A1"].Valor = "Fruta";
células["A2"].Valor = "maçã";
células["A3"].Valor = "laranja";
células["A4"].Valor = "mirtilo";
células["A5"].Valor = "kiwi";

células["B1"].Valor = "Preço";
células["B2"].Valor = 10;
células["B3"].Valor = 5;
células["B4"].Valor = 20;
células["B5"].Valor = 8;

planilha.PageSetup.PrintGridlines = true;
folha.PageSetup.PrintArea = "A1:F20";

Gráficos ChartCollection = planilha.Charts;

//Adiciona gráfico de colunas
int index = charts.Add(ChartType.Column, "=ChartSheet!A1:B5", false, 6, 0, 19, 5);
Gráfico gráfico = gráficos[índice];

//ExEtapa:1-
//Move a legenda para a esquerda e define a cor da fonte da legenda
chart.Legend.Font.Color = Color.Blue;
chart.Legend.Position = LegendPositionType.Left;

//ExEtapa:2-
//Define o título de um gráfico e altera a cor da fonte para azul
chart.Title.Text = "Gráfico de colunas de preços de frutas";
chart.Title.Font.Color = Color.Blue;

//ExEtapa:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Instalação de Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Editor</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}