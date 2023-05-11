---
title: Criação de Gráficos Excel e Conversão para Imagens via .NET
description:  C# código-fonte para desenhar e converter gráficos ou diagramas no Microsoft Excel usando a biblioteca .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Criação e conversão de gráficos de arquivo Excel via .NET" h2="Crie gráficos de documentos do Excel e converta em imagens usando APIs do lado do servidor em aplicativos baseados em .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Desenhar gráficos é uma arte para exibir dados graficamente para facilitar a análise.[.NET Biblioteca Excel](/cells/pt/net/) suporta gráficos de desenho dentro de arquivos do Excel. API oferece suporte à criação de gráficos diferentes listados em[Enumeração ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) incluindo gráficos de pizza, pirâmide, linha e bolha. Além disso, também converte gráficos em imagens. API fornece um[classe de gráficos](https://reference.aspose.com/cells/net/aspose.cells.charts) para blocos de construção de gráficos.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Criar gráficos dentro do arquivo do Excel" %}}

 Criar gráficos usando o Excel API é simples. Processo é, Criar[classe de pasta de trabalho](https://reference.aspose.com/cells/net/aspose.cells/workbook) objeto e selecione a primeira planilha ou a planilha relevante fornecendo seu índice. Insira os dados de células necessários usando[Método PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Adicionar gráfico à planilha usando a coleção Charts[Adicionar método](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Especifique o[Tipo de Gráfico](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype)da enumeração ChartType.
{{% blocks/products/pf/feature-page-code h3="C# Código para criar gráficos do Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Converter gráficos do Excel em imagens" %}}

 O processo de conversão de gráficos em imagens é: Use a classe Workbook para carregar o arquivo Excel, selecione a workseet relevante que contém os gráficos e chame o[Método ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) para conversão.

{{% blocks/products/pf/feature-page-code h3="C# Código para converter gráfico do Excel em imagem" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
