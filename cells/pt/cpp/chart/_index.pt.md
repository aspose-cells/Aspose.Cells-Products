---
title: Crie gráficos do Excel e converta em imagens via C++
description: Código fonte C++ para desenhar e converter gráfico ou diagrama no Excel Microsoft usando a Biblioteca C++
keywords: [C++ Aspose.Cells., C++ Convert chart to image., C++ Save chart to image., C++ chart to image., create charts in C++., insert charts in C++., manage charts in C++]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crie gráficos Microsoft<sup>&reg;</sup> Excel e converta em imagens via C++" h2="Converta gráficos de documentos do Excel em imagens e também crie gráficos, incluindo gráficos de pizza, pirâmide, linhas e bolhas em aplicativos baseados em C++." >}}

{{% blocks/products/pf/feature-page-summary %}}

 Usando gráficos do Excel, é possível ter uma visão geral e analisar os dados facilmente para tomar decisões corretas.[C++ Biblioteca Excel](/cells/pt/cpp/) suporta a criação de diferentes gráficos listados por[enum Aspose::Cells::Gráficos::ChartType
](https://reference.aspose.com/cells/cpp/aspose.cells.charts/charttype/) incluindo gráficos de área, barra, pizza, pirâmide, linha e bolha. Além disso, para conversão de gráficos em imagens, API fornece um[Para imagem](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chart/toimage/) mehtod no formato de imagem necessário.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Crie gráficos do Excel" %}}

 O processo de criação de gráfico do Excel é criar uma instância do[Aula de apostila](https://reference.aspose.com/cells/cpp/aspose.cells/workbook/) e selecione o desejado[Planilha](https://reference.aspose.com/cells/cpp/aspose.cells/worksheet/) . Adicione o gráfico usando[Adicionar método](https://reference.aspose.com/cells/cpp/aspose.cells.charts/chartcollection/add/)com parâmetros relevantes, incluindo tipo de gráfico. Acesse o gráfico via índice e[Adicionar](https://reference.aspose.com/cells/cpp/aspose.cells.charts/seriescollection/add/) a fonte de dados do gráfico.

{{% blocks/products/pf/feature-page-code h3="Código C++ para criar gráficos Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "create-excel-chart.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Converter gráficos em imagens" %}}


Para converter gráficos, o processo é primeiro criar um gráfico do tipo relevante usando o código acima ou acessá-lo na planilha relevante. Defina o caminho de salvamento de saída para a imagem e use o método ToImage para conversão.

 
{{% blocks/products/pf/feature-page-code h3="Código C++ para converter gráficos do Excel" %}}

{{< gist "aspose-cells-gists" "6f7d9819d85793c3a3b5d040af42e1a9" "convert-excel-chart-to-image.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
