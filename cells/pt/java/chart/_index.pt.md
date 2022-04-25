---
title: Crie gráficos do Excel e converta em imagens via Java
url: /pt/java/chart/
description: Java código-fonte para desenhar e converter gráfico ou diagrama no Microsoft Excel usando a biblioteca Java. 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversão e criação de gráficos de arquivos do Excel via Java" h2="Converta gráficos de documentos do Excel em imagens, bem como crie vários gráficos usando APIs do lado do servidor em aplicativos baseados em Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

A análise de dados por meio de gráficos mostra o panorama geral e é fácil tomar decisões mais informadas com insights mais claros. [Java Biblioteca do Excel](/cells/java/) suporta o desenho de diferentes criações de gráficos listados por [Tipo de Gráfico](https://apireference.aspose.com/cells/java/com.aspose.cells/ChartType) incluindo gráficos de pizza, pirâmide, linhas e bolhas. Além disso, também converte gráficos em imagens. API fornece um [Classe de gráficos](https://apireference.aspose.com/cells/java/com.aspose.cells/Chart) para representar um único gráfico do Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Converter gráficos do Excel em imagens" %}}

Processo de conversão de gráficos para imagens incluindo JPG, PNG, TIFF, BMP etc é, Use o [Pasta de trabalho](https://apireference.aspose.com/java/cells/com.aspose.cells/workbook) classe para carregar o arquivo Excel, selecione o [workset](https://apireference.aspose.com/cells/java/com.aspose.cells/worksheet) contendo os gráficos ou iterar através de cada gráfico em cada planilha. Definir [ImageOrPrintOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) e renderize a imagem de saída do gráfico usando [Chart.toImage](https://apireference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Código para converter gráfico do Excel em imagem" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Criar gráficos dentro do arquivo do Excel" %}}

Criar gráficos usando o Excel API é simples, pois API fornece um conjunto de diferentes classes, como Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection etc. para diferentes tipos de gráficos. Processo é, Criar objeto de classe Workbook e selecionar a primeira planilha ou a planilha relevante fornecendo seu índice. Para fonte de dados do gráfico, insira valores nas células da planilha usando [setValue](https://apireference.aspose.com/cells/java/com.aspose.cells/cell#Value) método. Use a coleção ChartCollection [adicionar método](https://apireference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int)) para adicionar o gráfico, defina o tipo de gráfico com a enumeração ChartType. Acesse o novo objeto Chart da coleção ChartCollection passando seu índice. Use o [Coleção de Séries](https://apireference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) objeto de gráfico para especificar a fonte de dados do gráfico.

{{% blocks/products/pf/feature-page-code h3="Java Código para criar gráficos do Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}