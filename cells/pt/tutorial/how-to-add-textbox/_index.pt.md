---
title: Como adicionar TextBox via Aspose.Cells
weight: 7700
limit:
description: Aprenda como adicionar TextBox.
keywords: [Add TextBox., how to add TextBox in Aspose.Cells., how to add TextBox using Aspose.Cells]
url: /pt/tutorial/add-textbox-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aprenda como adicionar TextBox com Aspose.Cells" >}}

<p>
Neste tutorial, adicionaremos TextBox em um arquivo Excel.
</p>

<p>
 Começaremos criando uma nova pasta de trabalho usando o<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteca</a> e adicione TextBox.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Verifique o código a seguir para descobrir como adicionar TextBox.
//ExStepSummary:0: O código a seguir mostra como adicionar TextBox e definir texto.
//ExStepImage:0:step-1.png
//ExStepSummary:1: O código a seguir mostra como alterar a cor do texto.
//ExStepImage:1:step-2.png
//ExStepSummary:2: O código a seguir mostra como alterar o ângulo de rotação de TextBox.
//ExStepImage:2:step-3.png
//ExStart
//ExEtapa:0-
usando Aspose.Cells;
usando Aspose.Cells.Desenho;

Pasta de trabalho pasta de trabalho = new Pasta de trabalho();
Folha de planilha = pasta de trabalho.Planilhas[0];
sheet.PageSetup.PrintGridlines = verdadeiro;
sheet.PageSetup.PrintArea = "A1:F20";

ShapeCollection formas = folha.Formas;

//Adiciona TextBox e define o texto
TextBox textBox = formas.AddTextBox(1, 0, 1, 0, 200, 200);
textBox.Text = "Aspose.Cells for .NET é uma biblioteca de classes de programação que permite aos desenvolvedores de software manipular e processar arquivos de planilha em seus próprios aplicativos.";

//ExEtapa:1-
//Muda a cor do texto
textBox.Font.Color = Color.Blue;

//ExEtapa:2-
//Altera o ângulo de rotação do TextBox
textBox.RotationAngle = 90;

//ExEtapa:0-

//ExEnd
{{< /app/cells/tutorial >}}
<br />

<br />
<br />
<div class="code-sample">
    <ul class="link-list">
        <li class="link-item"><a href="https://docs.aspose.com/cells/net/installation/">Instalação de Aspose.Cells</a></li>
        <li class="link-item"><a href="https://products.aspose.app/cells/editor/">Aspose.Cells Editora</a></li>
    </ul>
</div>

{{< /blocks/products/pf/feature-page-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< blocks/products/products-backtop-button >}}