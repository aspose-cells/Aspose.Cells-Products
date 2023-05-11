---
title: Crie gráficos do Excel e converta em imagens via Java
description:  Java código-fonte para desenhar e converter gráficos ou diagramas no Microsoft Excel usando a biblioteca Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>&reg;</sup> Conversão e Criação de Gráficos de Arquivo Excel via Java" h2="Converta gráficos de documentos do Excel em imagens, bem como crie vários gráficos usando APIs do lado do servidor em aplicativos baseados em Java." >}}


{{% blocks/products/pf/feature-page-summary %}}

 A análise de dados por meio de gráficos mostra o quadro geral e é fácil tomar decisões mais informadas com insights mais claros.[Java Biblioteca Excel](/cells/pt/java/) suporta o desenho de criação de gráficos diferentes listados por[Tipo de Gráfico](https://reference.aspose.com/cells/java/com.aspose.cells/ChartType) incluindo gráficos de pizza, pirâmide, linha e bolha. Além disso, também converte gráficos em imagens. API fornece um[classe de gráficos](https://reference.aspose.com/cells/java/com.aspose.cells/Chart)para representar um único gráfico do Excel.

{{% /blocks/products/pf/feature-page-summary %}}
{{% blocks/products/pf/feature-page-section h2="Converter gráficos do Excel em imagens" %}}

 Processo de conversão de gráficos em imagens, incluindo JPG, PNG, TIFF, BMP, etc.[pasta de trabalho](https://reference.aspose.com/java/cells/com.aspose.cells/workbook) classe para carregar o arquivo do Excel, selecione o relevante[planilha](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet) contendo os gráficos ou percorrer cada gráfico em cada planilha. Definir[ImageOrPrintOptions](https://reference.aspose.com/cells/java/com.aspose.cells/ImageOrPrintOptions) e renderize a imagem de saída do gráfico usando[Chart.toImage](https://reference.aspose.com/cells/java/com.aspose.cells/chart#toImage(java.io.OutputStream,%20com.aspose.cells.ImageOrPrintOptions)).


{{% blocks/products/pf/feature-page-code h3="Java Código para converter gráfico do Excel em imagem" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "render-excel-chart-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Chart Conversion" >}}


{{% blocks/products/pf/feature-page-section h2="Criar gráficos dentro do arquivo do Excel" %}}

 Criar gráficos usando o Excel API é simples, pois API fornece um conjunto de classes diferentes, como Axis, Chart, ChartArea, ChartDataTable, ChartFrame, ChartPoint, ChartPointCollection, ChartCollection, etc., para diferentes tipos de gráficos. O processo é criar um objeto de classe Workbook e selecionar a primeira planilha ou a planilha relevante fornecendo seu índice. Para fonte de dados do gráfico, insira valores nas células da planilha usando[valor definido](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)método. Use a coleção ChartCollection[adicionar método](https://reference.aspose.com/cells/java/com.aspose.cells/chartcollection#add(int,%20int,%20int,%20int,%20int) ) para adicionar o gráfico, defina o tipo de gráfico com a enumeração ChartType. Acesse o novo objeto Chart da coleção ChartCollection passando seu índice. Use o[SeriesCollection](https://reference.aspose.com/cells/java/com.aspose.cells/SeriesCollection) objeto charting para especificar a fonte de dados do gráfico.

{{% blocks/products/pf/feature-page-code h3="Java Código para criar gráficos do Excel" %}}

{{< gist "aspose-com-gists" "b48fa96f2807e16db8031eb177e5bb60" "create-excel-chart-pyramid.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}
