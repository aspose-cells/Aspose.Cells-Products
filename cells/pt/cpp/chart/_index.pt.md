---
title: Crie gráficos do Excel e converta em imagens via C++
url: /pt/cpp/chart/
description: C++ código-fonte para desenhar e converter gráfico ou diagrama no Microsoft Excel usando a biblioteca C++
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crie gráficos do Microsoft<sup>&reg;</sup> Excel e converta em imagens por meio de C++" h2="Converta gráficos de documentos do Excel em imagens, bem como crie gráficos, incluindo gráficos de pizza, pirâmide, linhas e bolhas em aplicativos baseados em C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

Usando gráficos do Excel, é possível obter uma visão geral e analisar dados facilmente para tomar decisões corretas. [C++ Biblioteca do Excel](/cells/cpp/) suporta a criação de diferentes gráficos listados por [enum Aspose::Cells::Charts::ChartType
](https://apireference.aspose.com/cells/cpp/namespace/aspose.cells.charts#a2f17e69bcefc754569019185d0621b70) incluindo gráficos de área, barra, pizza, pirâmide, linha e bolha. Além disso, para conversão de gráficos em imagens, API fornece um [Método ToImage](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_sparkline#a28d76dd585c48366e1657f2982722ddb) no formato de imagem necessário.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Criar gráficos do Excel" %}}

O processo de criação do gráfico do Excel é criar uma instância do [Classe IWorkbook](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) e selecione o desejado [Planilha](https://apireference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet_collection#a5574d624796043233420d0e0459ccc43). Adicione o gráfico usando [Adicionar método](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_chart_collection#ab7e8cce835c251a4682605299a6aa068) com parâmetros relevantes, incluindo o tipo de gráfico. Acesse o gráfico via índice e [Adicionar](https://apireference.aspose.com/cells/cpp/class/aspose.cells.charts.i_series_collection#a8f4dc4d883f32f65b1fb673e2aa7862f) a fonte de dados para o gráfico.

{{% blocks/products/pf/feature-page-code h3="C++ Código para criar gráficos do Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Converter gráficos em imagens" %}}


Para o processo de conversão de gráficos, primeiro crie o gráfico do tipo relevante usando o código acima ou acesse-o na planilha relevante. Defina o caminho de salvamento de saída para imagem e use o método ToImage para conversão.

 
{{% blocks/products/pf/feature-page-code h3="C++ Código para converter gráficos do Excel" %}}

{{< gist "aspose-com-gists" "da2fd423617bf9013a7673870c81d708" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}