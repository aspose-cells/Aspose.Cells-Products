---
title: Criação de Gráficos Excel e Conversão para Imagens via .NET
description:  Código fonte C# para desenhar e converter gráfico ou diagrama no Excel Microsoft usando a Biblioteca .NET.
keywords: [C# Aspose.Cells., c# Convert chart to image., c# Save chart to image., c# chart to image., create charts in c#., insert charts in c#., manage charts in c#]
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Criação e conversão de gráficos em arquivos Excel via .NET" h2="Crie gráficos de documentos Excel e converta-os em imagens usando APIs do lado do servidor em aplicativos baseados em .NET." >}}
{{% blocks/products/pf/feature-page-summary %}}
 Desenhar gráficos é uma arte de exibir dados graficamente para facilitar a análise.[.NET Biblioteca Excel](/cells/pt/net/) suporta desenho de gráficos em arquivos Excel. API suporta a criação de diferentes gráficos listados em[Enumeração ChartType](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) incluindo gráficos de pizza, pirâmide, linhas e bolhas. Além disso, também converte gráficos em imagens. API fornece um[Classe de gráficos](https://reference.aspose.com/cells/net/aspose.cells.charts) para blocos de construção de gráficos.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Crie gráficos em arquivo Excel" %}}

 Criar gráficos usando Excel API é simples. O processo é, criar[Aula de apostila](https://reference.aspose.com/cells/net/aspose.cells/workbook)objeto e selecione a primeira planilha ou a planilha relevante fornecendo seu índice. Insira os dados das células necessárias usando[Método PutValue](https://reference.aspose.com/cells/net/aspose.cells/cell/methods/putvalue/index) . Adicione gráfico à planilha usando a coleção Charts[Adicionar método](https://reference.aspose.com/cells/net/aspose.cells.charts/chartcollection/methods/add) . Especifique o[Tipo de Gráfico](https://reference.aspose.com/cells/net/aspose.cells.charts/charttype) da enumeração ChartType.
{{% blocks/products/pf/feature-page-code h3="Código C# para criar gráficos Excel" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "create-excel-chart.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section h2="Converter gráficos do Excel em imagens" %}}

 O processo de conversão de gráficos em imagens é: Use a classe Workbook para carregar o arquivo Excel, selecione o workset relevante que contém os gráficos e chame o[Método ToImage](https://reference.aspose.com/cells/net/aspose.cells.charts.chart/toimage/methods/7) para conversão.

{{% blocks/products/pf/feature-page-code h3="C# Código para converter gráfico do Excel em imagem" %}}

{{< gist "aspose-com-gists" "47151e6b1cd698683d5eefb538a4a52a" "convert-xlsx-file-chart-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}
