---
title: Como adicionar formas via Aspose.Cells
weight: 7700
limit:
description: Aprenda como adicionar formas.
keywords: [add shapes., how to add shapes in Aspose.Cells., how to add shapes using Aspose.Cells]
url: /pt/tutorial/add-shapes-in-excel
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/feature-page-section h2="Aprenda como adicionar formas com Aspose.Cells" >}}

<p>
Neste tutorial, adicionaremos formas em um arquivo Excel.
</p>

<p>
 Começaremos criando uma nova pasta de trabalho usando o<a href="https://www.nuget.org/packages/Aspose.Cells">Aspose.Cells biblioteca</a> e adicione formas.
</p>

<br />
{{< app/cells/tutorial >}}
//ExSummary: Verifique o código a seguir para descobrir como adicionar formas.
//ExStepSummary:0: O código a seguir mostra como adicionar a forma de retângulo.
//ExStepImage:0:step-1.png
//ExStepSummary:1: O código a seguir mostra como adicionar formato de linha.
//ExStepImage:1:step-2.png
//ExStepSummary:2: O código a seguir mostra como adicionar uma forma oval.
//ExStepImage:2:step-3.png
//ExStart
//ExEtapa:0-
usando Aspose.Cells;
usando Aspose.Cells.Desenho;





Pasta de trabalho pasta de trabalho = nova pasta de trabalho();
Planilha = pasta de trabalho.Worksheets[0];
planilha.PageSetup.PrintGridlines = true;
folha.PageSetup.PrintArea = "A1:F20";

ShapeCollection formas = folha.Formas;

//Adiciona forma retangular
formas.AddRectangle(1, 0, 1, 0, 100, 150);

//ExEtapa:1-
//Adiciona forma de linha
formas.AddLine(8, 0, 1, 0, 100, 150);

//ExEtapa:2-
//Adiciona forma oval
formas.AddOval(13, 0, 1, 0, 100, 150);

//ExEtapa:0-
pasta de trabalho
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